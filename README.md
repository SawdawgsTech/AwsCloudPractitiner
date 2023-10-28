# AwsCloudPractitiner/Cloud computing essetials
aws cloud quest badge.
cloud practitioner will build cloud solutions using aws services. you will learn about aws cloud concepts.
#1 you will start with cloud computing essentials/aws services amazon s3.
aws data center powers most of the technical infrastructure here in the city, but it takes months to procure and configure resources.
cloud computing on aws provides access to technology services. such as compute power, storage and databases. resources are available on demand, and you pay only for what you use. you can choose from hundreds of aws services to help build your solutions.
with aws, you can deploy resources, such as servers, in mins and at a fraction of the cost of traditional resources. with this type of flexibility you can transform your operations.
does your webpage include any scripts that must ruun on the web server, these are lnown as server side scripts. if your site doesnt run server side scripts it is a static website.
Q? it is a static website.
we can migrate your webpage to an amazon s3 will get you back up and running quickly and make your site more resistant to failure. we can start by creating a new s3 bucket to hold your webpage content.
Q? dont we need to run a web server to publish the webpage?
using amazon s3, uou can store any type or amount of data and retrieve it from anywhere, after we upload your data into the s3 bucket, we can enable the static website hosting feature on the bucket.
because amazon s3 is afully managed service you dont need to deploy or manage any servers. s3 buckets are automatically replicated across multiple aws data centers for high resiliency.
also any website hosted in an s3 bucket can automatically scale to handle thousands of concurrent requests.
learn/plan/practice/diy.
files that support the webpage functionality, such as client side sctipts and style sheets, are uploaded into the s3 bucket together with an html file. you can configure any of your s3 buckets as static website
aws global infrastructure overview
aws regions
each region is a separate geo area
each reagions has a seperate avaliblity zones (az)
avalibility zones are fully isolated and many kms apart there are atleast 2 and up to 6.
each zones have 1 or more discrete data centers typically 3, redundant power, separate facilities and dedicated metro fiber.
the network are purpose built, highly available, low latency, fully redundant parallel 100 gbe metro fiber network.
point of presence (pop), amazon cloudfront global content deliver network (cdn)
elastic load balancer distributes across the AZ
aws global infrastructure benefits 
performance, low latancy, avalibility, resiliance, redundancy, custum hardware, no single point of falure 
tco overall IT infastructure reduces cost and footprint
aws well-architected the six pillars are 1=operational excellence 2=security 3=reliability 4=performance efficiency 5=cost optimization 6=sistaomability
s3 standard - s3 intelligent tiering - s3 standard ia - s3 one zone ia-  s3 glacier instant retrieval - s3 glacier flexible retrieval - s3 glacier deep archive
