# Azure-devops-pipelines-with-CloudFormation
Creating a vpc with a s3 bucket that has get and put permissions with cloud formation has a pipeline for staging and approvals via aws code pipeline.

## This project was practice using Azure devops alongside Cloudformation. 

## Steps 
1. Create CloudFormation template defining a VPC, subnets, route tables, and security groups.
2. Create an S3 Bucket: Define an S3 bucket and configure permissions for GET and PUT requests.
3. Create a CodePipeline that includes the following stages: Source Stage, Build Stage, Staging Stage, Approval Stage, and Production Stage.
4. Define IAM Roles and Policies: Create IAM roles and policies for your EC2 instances or Lambda functions to interact with the S3 bucket and execute deployments through CodePipeline.
