
# New Product Holding Page

This is a [domain-holding page](https://lpool.valentineezeja.com/) page for a soon to be launched product. This is 


# Tools versions/access prerequisites:
- AWS CLI: aws-cli/2.6.4 Python/3.9.11
- Visual Studio Code: v1.73.1
- Git:  v2.37.2.windows.2

- Access: 
    - AWS admin user and security credentials
    - GitHub access token 

# Design considerations
The following factors influenced my choice of tools and technology for architecting this solution:
-	Scalability
-	Availability
-	Disaster Recovery
-	Deployments
-	Testing 
-	Costs
-	Security
-	Monitoring

# Technology employed:
- AWS CloudFormation
- Amazon S3
- Amazon Codebuild, Codedeploy and Codepipeline
- Amazon CloudFront, ACM and Route53
- AWS Lambda
- CloudWatch
- Secrets Manager

# Summarised flowchart:
- Here is a flowchart showing the processes involved in the website deployment; I have added only necessary details to keep it as simple as possible

![Infra diagram drawio](https://user-images.githubusercontent.com/25130252/219280500-f4a8d56c-2da2-4826-a520-64f733bf4fb1.svg)


# Cloudformatiion stack diagrams:

##Secrets manager stack:
![Secrets Manager](https://user-images.githubusercontent.com/25130252/219281060-f9633b31-eb45-4dc2-b849-de6b9abd92c5.png)

## Frontend deployment stack:

![Frontend deployment](https://user-images.githubusercontent.com/25130252/219281274-27b9d8be-3da6-4159-b68a-455f83e74819.png)

## main infrastructure stack:

![image](https://user-images.githubusercontent.com/25130252/219281591-bd8678ab-1476-4c66-9b1b-c55977e792db.png)

