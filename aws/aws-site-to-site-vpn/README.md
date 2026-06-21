How to Setup an AWS Site-to-Site (S2S) VPN Connection

Overview

This lab demonstrates how to establish a secure Site-to-Site VPN connection between an AWS VPC and a simulated on-premises network, using a Virtual Private Gateway, Customer Gateway, and IPsec VPN tunnels.

Services Used


Amazon VPC
Virtual Private Gateway
Customer Gateway
Site-to-Site VPN
Amazon EC2
IPsec (strongSwan / Libreswan)


Steps Performed


Created a custom VPC with subnets in the Mumbai region
Created a Virtual Private Gateway and attached it to the VPC
Created a Customer Gateway representing the on-premises router
Created a Site-to-Site VPN connection between the Virtual Private Gateway and Customer Gateway
Downloaded and applied the VPN configuration to the on-premises EC2 instance (Libreswan)
Started the IPsec service and verified tunnel establishment
Tested connectivity by pinging across the VPN tunnel between AWS and on-premises networks


Outcome

Lab validation passed ✅ — 100%