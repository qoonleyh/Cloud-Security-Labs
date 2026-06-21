Understanding Stateful vs Stateless Firewalls

Overview

This lab demonstrates the difference between stateful and stateless firewalls in AWS by comparing Security Groups (stateful) and Network ACLs (stateless). It covers how each handles inbound and outbound traffic rules and the practical implications for network security design.

Services Used


Amazon VPC
Security Groups (Stateful)
Network ACLs (Stateless)
Amazon EC2
Amazon Web Services


Steps Performed


Created a custom Amazon VPC with public and private subnets
Launched EC2 instances and connected via SSH using a key pair
Configured Security Group rules and tested stateful behaviour (automatic return traffic)
Configured Network ACL rules and demonstrated stateless behaviour (explicit return rules required)
Tested ping (ICMP) connectivity with and without outbound rules to highlight the difference
Added outbound rules to Network ACLs and verified restored connectivity


Validation Checks


✅ Create an Amazon Custom VPC


Outcome

Lab validation passed ✅ — 100%