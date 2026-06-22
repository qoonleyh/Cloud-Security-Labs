Azure Service Endpoints for Storage

Overview

This lab demonstrates how to configure Azure Service Endpoints to enable secure, direct connectivity from a Virtual Network to Azure Storage, restricting storage account access to traffic originating from specific VNet subnets only.

Services Used


Azure Virtual Network (VNet)
Azure Service Endpoints
Azure Storage Account
Azure Virtual Machines
Network Security Groups (NSG)


Steps Performed


Created a VNet with a subnet for the VM and enabled the Microsoft.Storage service endpoint
Created an Azure Storage Account
Configured the Storage Account firewall to allow access only from the specific VNet subnet
Deployed a VM in the VNet and verified storage access from within the VNet
Confirmed that storage access was denied from outside the VNet


Outcome

Lab validation passed ✅ — 100%