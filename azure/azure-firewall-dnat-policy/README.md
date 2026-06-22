Azure Firewall DNAT Policy

Overview

This lab demonstrates how to configure Destination Network Address Translation (DNAT) rules in Azure Firewall Policy to redirect inbound internet traffic to specific internal resources, enabling controlled public access to private workloads.

Services Used


Azure Firewall
Azure Firewall Policy
Azure Virtual Network (VNet)
Azure Virtual Machines
Azure Public IP


Steps Performed


Created a VNet with dedicated AzureFirewallSubnet
Deployed an Azure Firewall with a public IP address
Created an Azure Firewall Policy with a DNAT rule collection
Configured DNAT rules to translate inbound traffic to internal VM IP addresses
Tested connectivity by accessing the public IP and verifying redirection to the internal resource


Outcome

Lab validation passed ✅ — 100%