## Project Description

Implement a fictious Serverless Banking App (AccountBalanceStatus) using AWS API Gateway, AWS Lambda and S3, provisioned through CloudFormation.


## CloudFormation

* A s3 Bucket for store the user data.
* A lambda execution role for lambda to access s3 bucket.
* A lambda function to query the s3 bucket.
* An API gateway with resource, method and deploy stage, to invoke the lambda function.

