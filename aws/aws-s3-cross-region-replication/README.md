AWS S3 Cross Region Replication

Overview

This lab demonstrates how to configure Amazon S3 Cross-Region Replication (CRR) to automatically replicate objects from a source bucket in one AWS region to a destination bucket in another region, supporting disaster recovery and compliance requirements.

Services Used


Amazon S3
AWS Identity and Access Management (IAM)
Amazon Web Services (multiple regions)


Steps Performed


Created a source S3 bucket with versioning enabled
Created a destination S3 bucket in a different AWS region with versioning enabled
Created an IAM role granting S3 replication permissions
Configured a replication rule on the source bucket targeting the destination bucket
Uploaded objects to the source bucket and verified replication to the destination bucket
Confirmed replication status and object availability in both regions


Outcome

Lab validation passed ✅ — 100%