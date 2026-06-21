Resilient Architecture with RDS and SNS

Overview

This lab demonstrates how to build a resilient AWS architecture using Amazon RDS with Multi-AZ deployment and Amazon SNS event notifications, ensuring high availability and automated alerting for database events.

Services Used


Amazon RDS
Amazon SNS
Amazon VPC
AWS Identity and Access Management (IAM)


Steps Performed


Created an Amazon RDS instance with Multi-AZ deployment enabled
Configured RDS subnet groups across multiple availability zones
Created an Amazon SNS topic for RDS event notifications
Subscribed an email endpoint to the SNS topic and confirmed subscription
Configured RDS event subscriptions to publish to the SNS topic
Tested failover and verified SNS notification delivery


Outcome

Lab validation passed ✅ — 100%