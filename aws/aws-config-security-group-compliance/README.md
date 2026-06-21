Check Compliance Status of Security Group using AWS Config

Overview

This lab demonstrates how to use AWS Config to monitor and evaluate the compliance status of EC2 security groups. A Config rule is created to detect security groups that allow unrestricted SSH access (0.0.0.0/0), flagging them as non-compliant.

Services Used


AWS Config
Amazon EC2 (Security Groups)
Amazon Web Services (IAM)


Steps Performed


Set up AWS Config using the 1-Click option
Created a Config rule using the managed rule restricted-ssh
Created a Security Group with an inbound SSH rule open to 0.0.0.0/0
Triggered a Config evaluation and reviewed compliance results
Confirmed the Security Group was flagged as Non-Compliant
Reviewed the Config rule evaluation details


Outcome

Lab validation passed ✅ — 100%