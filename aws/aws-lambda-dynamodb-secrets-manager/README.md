AWS Lambda with DynamoDB and Secrets Manager

Overview

This lab demonstrates how to build a serverless function using AWS Lambda that securely retrieves database credentials from AWS Secrets Manager and interacts with an Amazon DynamoDB table, following security best practices for credential management.

Services Used


AWS Lambda
Amazon DynamoDB
AWS Secrets Manager
AWS Identity and Access Management (IAM)


Steps Performed


Created an Amazon DynamoDB table
Stored database credentials securely in AWS Secrets Manager
Created an IAM role with permissions for Lambda to access Secrets Manager and DynamoDB
Created a Lambda function that retrieves credentials from Secrets Manager
Configured the Lambda function to read and write to DynamoDB
Tested the Lambda function and reviewed execution logs


Outcome

Lab validation passed ✅ — 100%