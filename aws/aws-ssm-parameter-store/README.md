AWS SSM Parameter Store

Overview

This lab demonstrates how to use AWS Systems Manager Parameter Store to securely store and retrieve configuration data and secrets, integrating with EC2 instances to manage application configuration without hardcoding sensitive values.

Services Used


AWS Systems Manager (Parameter Store)
Amazon EC2
AWS Identity and Access Management (IAM)


Steps Performed


Created parameters in SSM Parameter Store (String and SecureString types)
Created an IAM role with SSM Parameter Store read permissions
Launched an EC2 instance with the IAM role attached
Connected to the EC2 instance and retrieved parameters using the AWS CLI
Verified secure retrieval of SecureString parameters with KMS decryption
Demonstrated parameter versioning and access control


Outcome

Lab validation passed ✅ — 100%
