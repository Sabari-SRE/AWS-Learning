# AWS-Learning
To practice AWS for solution architect 

## Important aws commands
```
aws iam create-user --user-name (name details) example: test-machine-user 
aws iam create-access-key --user-name (name details) --output table
Next step is to configure by following --> aws configure command
Enter your access key then secret key
aws sts get-caller-identity --> To know the user details (Who am I)
```
```
S3 (simple storage service) is important service to store and retrieve data like images, videos etc...
EC2 stands for Amazon Elastic Compute Cloud, which is a service within Amazon Web Services (AWS) 
that allows users to run applications on virtual computers in the cloud.
```

## SIX pillar of AWS well architected framework
1. Operational excellence
2. Security
3. Reliability
4. Performance efficiency
5. Cost optimization
6. Sustainability