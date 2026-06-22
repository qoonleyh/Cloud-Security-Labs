NSG VM-to-VM Communication

Overview

This lab demonstrates how to use Azure Network Security Groups to control traffic between virtual machines within the same Virtual Network, implementing micro-segmentation to restrict lateral movement between workloads.

Services Used


Azure Network Security Groups (NSG)
Azure Virtual Machines
Azure Virtual Network (VNet)
Azure Subnets


Steps Performed


Created a VNet with multiple subnets
Deployed two Azure Virtual Machines in separate subnets
Configured NSG rules to allow and deny specific traffic between VMs
Tested VM-to-VM connectivity before and after NSG rule changes
Verified that NSG rules correctly enforced traffic restrictions between workloads


Outcome

Lab validation passed ✅ — 100%