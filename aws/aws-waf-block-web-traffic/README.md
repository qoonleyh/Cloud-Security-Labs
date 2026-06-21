Blocking Web Traffic with WAF in AWS

Overview

This lab demonstrates how to use AWS Web Application Firewall (WAF) to block malicious web traffic targeting an Application Load Balancer. An IP set is created and associated with a WAF Web ACL to block traffic from specific IP addresses.

Services Used


AWS WAF
Application Load Balancer (ALB)
Amazon EC2
Amazon Web Services (VPC)


Steps Performed


Launched an Amazon Linux 2 EC2 instance
Created an Application Load Balancer and verified HTTP access via ELB DNS
Created a WAF IP Set containing the IP address to block
Created a WAF Web ACL with a rule referencing the IP Set (Block action)
Associated the Web ACL with the Application Load Balancer
Tested that traffic from the blocked IP received a 403 Forbidden response


Outcome

Lab validation passed ✅ — 100%