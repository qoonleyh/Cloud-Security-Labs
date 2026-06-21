AWS Access Control Alerts with CloudWatch and CloudTrail

Overview

This lab demonstrates how to set up access control alerting by integrating AWS CloudTrail with CloudWatch Logs, creating metric filters and alarms to detect and notify on specific API activity such as EC2 instance stop events.

Services Used


AWS CloudTrail
Amazon CloudWatch
Amazon CloudWatch Logs
Amazon SNS
Amazon EC2


Steps Performed


Created a CloudTrail trail with CloudWatch Logs integration enabled
Created a CloudWatch Log Group metric filter targeting $.eventName = "StopInstances"
Created a CloudWatch Alarm triggered by the metric filter
Created an Amazon SNS topic and subscribed an email address
Confirmed the SNS email subscription
Linked the SNS topic to the CloudWatch Alarm for notifications
Verified the full alerting pipeline from CloudTrail → CloudWatch → SNS → Email


Outcome

Lab validation passed ✅ — 100%