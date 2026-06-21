CloudWatch Events with EC2 and SNS

Overview

This lab demonstrates how to configure Amazon CloudWatch Events (EventBridge) rules to monitor EC2 instance state changes and trigger SNS notifications, enabling automated alerting on infrastructure events.

Services Used


Amazon CloudWatch Events (EventBridge)
Amazon EC2
Amazon SNS
Amazon Web Services (IAM)


Steps Performed


Created an Amazon SNS topic and subscribed an email endpoint
Confirmed the SNS subscription via email
Created a CloudWatch Events rule targeting EC2 instance state change events
Configured the rule to trigger the SNS topic as the target
Stopped and started an EC2 instance to trigger the event rule
Verified receipt of SNS email notification on instance state change


Outcome

Lab validation passed ✅ — 100%