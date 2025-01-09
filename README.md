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
```