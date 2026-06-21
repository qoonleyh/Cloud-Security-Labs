Discover Sensitive Data in S3 using Amazon Macie

Overview

This lab demonstrates how to use Amazon Macie to automatically discover and classify sensitive data stored in Amazon S3 buckets, using custom data identifiers to detect specific sensitive data patterns.

Services Used


Amazon Macie
Amazon S3
AWS Identity and Access Management (IAM)


Steps Performed


Enabled Amazon Macie in the AWS Management Console
Created an S3 bucket and uploaded a sample CSV file containing sensitive data
Created a custom data identifier in Macie for targeted detection
Created and ran a Macie classification job against the S3 bucket
Reviewed Macie findings showing a Medium severity SensitiveData:S3Object/CustomIdentifier finding
Explored finding details including affected resources and data sample


Outcome

Lab validation passed ✅ — 100%