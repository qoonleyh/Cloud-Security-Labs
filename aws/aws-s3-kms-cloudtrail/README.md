S3 Encryption with KMS and CloudTrail

Overview

This lab demonstrates how to encrypt Amazon S3 bucket objects using AWS KMS customer-managed keys and audit encryption-related API activity using AWS CloudTrail, implementing encryption at rest with full auditability.

Services Used


Amazon S3
AWS Key Management Service (KMS)
AWS CloudTrail
Amazon Web Services (IAM)


Steps Performed


Created a KMS customer-managed key (CMK)
Created an S3 bucket with KMS server-side encryption enabled using the CMK
Uploaded objects to the S3 bucket and verified encryption status
Enabled AWS CloudTrail to log S3 data events
Reviewed CloudTrail logs for KMS API calls related to S3 object encryption
Verified encryption and decryption audit trail in CloudTrail


Outcome

Lab validation passed ✅ — 100%