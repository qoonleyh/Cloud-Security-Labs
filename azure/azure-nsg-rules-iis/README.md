NSG Rules for IIS

Overview

This lab demonstrates how to configure Azure Network Security Group (NSG) rules to control inbound and outbound traffic to a Windows Server running IIS, allowing HTTP/HTTPS web traffic while restricting other access.

Services Used


Azure Network Security Groups (NSG)
Azure Virtual Machines (Windows Server)
Internet Information Services (IIS)
Azure Virtual Network (VNet)


Steps Performed


Deployed a Windows Server VM in Azure
Installed and configured IIS on the VM
Created an NSG with inbound rules allowing HTTP (port 80) and HTTPS (port 443)
Associated the NSG with the VM's network interface and subnet
Tested web server accessibility via the VM's public IP
Verified that other ports were correctly blocked by the NSG


Outcome

Lab validation passed ✅ — 100%