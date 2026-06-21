Access Amazon SQS using Amazon VPC Interface Endpoint

Overview

This lab demonstrates how to access Amazon SQS privately from within a VPC using a VPC Interface Endpoint, ensuring SQS traffic does not traverse the public internet and remains within the AWS network.

Services Used


Amazon SQS
Amazon VPC
VPC Interface Endpoint (AWS PrivateLink)
Amazon EC2
Security Groups


Steps Performed


Created a Standard SQS Queue
Created a custom VPC with a public subnet and Internet Gateway
Created a VPC Interface Endpoint for Amazon SQS
Launched an EC2 instance in the VPC with appropriate security group rules
Connected to the EC2 instance and sent a sample message to SQS via the VPC endpoint
Verified private SQS access without internet routing


Outcome

Lab validation passed ✅ — 100%