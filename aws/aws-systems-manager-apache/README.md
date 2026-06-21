AWS Systems Manager — Apache Web Server Management

Overview

This lab demonstrates how to use AWS Systems Manager to remotely manage and configure Apache web servers on EC2 instances without requiring SSH access, using Run Command and Session Manager for secure instance management.

Services Used


AWS Systems Manager
Amazon EC2
Apache HTTP Server
AWS Identity and Access Management (IAM)


Steps Performed


Launched EC2 instances with SSM Agent and appropriate IAM instance profile
Used SSM Run Command to install and configure Apache HTTP Server
Verified Apache installation and service status via SSM Session Manager
Managed Apache service (start, stop, restart) using SSM Run Command
Confirmed web server accessibility without direct SSH access


Outcome

Lab validation passed ✅ — 100%