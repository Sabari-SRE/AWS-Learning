## Amazon S3 (Simple Storage Service)
S3 service provides object storage through a web service interface.

#### Buckets are similar to file folders and the data stored in them is organized into object 
We can create buckets through aws console or aws CLI
````
aws s3api list -buckets --> To list all the buckets under the user(IAM or root)
aws s3api cp c:\\directory\\filename s3://bucket name --> To create bucket and upload file
aws s3 ls s3://bucket name --> To get the list of files under the folder
aws s3 mv s3://folder s3://foldername --> TO move files from one folder to another folder on the bucket.
**mv command also used to rename the file**
````

### Storage tiers
s3 standard, s3 glacier, s3 intelligent tiering, s3 one zone-IA, s3 glacier deep archive

### Object lock --> To enable object lock in s3 buckets the versioning must be enabled.
1) Legal hold --> Make the file immutable and cannot be deleted
2) Retention period --> Set the retention period 

### S3 bucket policies --> Configure policies to restrict/provide access to specific group of users.
policy can be configured manually by using json format or aws policy editor.

### AWS storage gateway --> Hybrid cloud storage service that allows users to access cloud storage from their on-premises environments.
### S3 bucket encryption --> Enables server side encryption
````
aws se cp filname s3://bucketname --sse AES256
````
## AWS CDN (Content Delivery Network)
It acts as a cache to serve the content to local users instead of fetching from the source for every request.
AWS solution for CDN is aws cloud front. 

![AWS CDN](C:\Users\sabar\Sabari-SRE\AWS-Learning\images\aws_cdn.png)
