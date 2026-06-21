AWS ALB with Bastion Host

Overview

This lab covers setting up a Bastion Host architecture with an Application Load Balancer to provide secure access to EC2 instances in a private subnet, while distributing public-facing traffic through the ALB.

Services Used


Amazon EC2
Elastic Load Balancing (ALB)
Amazon VPC (Public/Private Subnets)
Security Groups


Steps Performed


Created a VPC with public and private subnets
Launched a Bastion Host EC2 instance in the public subnet
Launched backend EC2 instances in the private subnet
Configured Security Groups to allow SSH only via the Bastion Host
Created an Application Load Balancer targeting the private EC2 instances
Validated connectivity through the Bastion Host and ALB DNS


Outcome

Lab validation passed ✅ — 100%
