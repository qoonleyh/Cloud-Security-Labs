Install CloudWatch Logs Agent on EC2 and View CloudWatch Metrics

Overview

This lab covers installing and configuring the Amazon CloudWatch Agent on an EC2 instance to collect system-level metrics and push them to CloudWatch for monitoring and visualisation.

Services Used


Amazon EC2
Amazon CloudWatch
Amazon CloudWatch Logs
AWS Identity and Access Management (IAM)


Steps Performed


Launched an Amazon Linux 2 EC2 instance with an IAM instance profile (CloudWatchAgentServerPolicy)
Connected to the instance via EC2 Instance Connect
Installed the Amazon CloudWatch Agent on the instance
Configured the agent using a TOML configuration file
Started the CloudWatch Agent service and verified it was active and running
Navigated to CloudWatch Metrics to confirm CWAgent metrics were being published
Viewed metrics grouped by ImageId, InstanceId, InstanceType, cpu, disk, and memory


Outcome

Lab validation passed ✅ — 100%