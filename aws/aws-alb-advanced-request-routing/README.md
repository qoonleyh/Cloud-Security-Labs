
Understanding AWS ALB Advanced Request Routing

Overview

This lab demonstrates how to configure advanced request routing rules on an AWS Application Load Balancer (ALB). Traffic is routed to different targets based on query strings and cookies, enabling flexible content delivery and user segmentation.

Services Used


Amazon EC2
Elastic Load Balancing (ALB)
Amazon Web Services (VPC, Security Groups)


Steps Performed


Launched an Amazon Linux 2 EC2 instance
Created an Application Load Balancer with an HTTP listener
Created ELB target groups and registered EC2 instances
Configured listener rules to route traffic based on:

Query string (id=Amazon) → Fixed HTML response
Cookie (user=su) → Fixed HTML response
Default (ELB DNS only) → Webserver



Tested routing by accessing the ELB DNS with different query strings and cookies


Outcome

Lab validation passed ✅ — 100%
