Azure VM Disk Encryption

Overview

This lab demonstrates how to enable Azure Disk Encryption on Virtual Machine disks using Azure Key Vault to store the encryption keys, protecting data at rest on both OS and data disks.

Services Used


Azure Virtual Machines
Azure Disk Encryption
Azure Key Vault
Azure Active Directory (IAM)


Steps Performed


Created an Azure Key Vault with disk encryption permissions enabled
Deployed an Azure Virtual Machine
Enabled Azure Disk Encryption on the VM's OS disk
Configured Key Vault access policies to allow disk encryption operations
Verified encryption status on the VM disks
Reviewed Key Vault audit logs for encryption key usage


Outcome

Lab validation passed ✅ — 100%