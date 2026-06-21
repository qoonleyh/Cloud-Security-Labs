Understanding AWS ALB Path Based Routing

Overview

This lab demonstrates how to configure path-based routing on an AWS Application Load Balancer to direct traffic to different backend servers based on the URL path. Traffic to /admin routes to one server and /user routes to another.

Services Used


Amazon EC2
Elastic Load Balancing (ALB)
Amazon Web Services (VPC, Security Groups)


Steps Performed


Launched two Amazon Linux 2 EC2 instances (MyWebServer1, MyWebServer2)
Created three ELB target groups: DefaultTargetGroup, AdminTargetGroup, UserTargetGroup
Created an Application Load Balancer with an HTTP:80 listener
Configured listener rules:

Path /admin* → AdminTargetGroup (MyWebServer1)
Path /user* → UserTargetGroup (MyWebServer2)
Default → DefaultTargetGroup (both servers)



Tested routing by accessing ELB DNS with /admin and /user paths


Outcome

Lab validation passed ✅ — 100%
