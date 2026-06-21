AWS S3 Pre-Signed URLs

Overview

This lab demonstrates how to generate and use Amazon S3 pre-signed URLs to provide temporary, time-limited access to private S3 objects without requiring AWS credentials, enabling secure and controlled object sharing.

Services Used


Amazon S3
AWS Identity and Access Management (IAM)
AWS CLI / SDK


Steps Performed


Created a private Amazon S3 bucket
Uploaded objects to the bucket
Generated pre-signed URLs for private objects using the AWS CLI
Tested object access using the pre-signed URL within the validity window
Verified that the URL expired correctly after the specified time limit
Explored use cases for pre-signed URLs in application development


Outcome

Lab validation passed ✅ — 100%