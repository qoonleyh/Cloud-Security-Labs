Encrypt and Decrypt Data at Rest

Overview

This lab demonstrates how to encrypt and decrypt data at rest in Azure Storage using customer-managed keys stored in Azure Key Vault, implementing bring-your-own-key (BYOK) encryption for storage accounts.

Services Used


Azure Storage Account
Azure Key Vault
Azure Key Vault Keys
Azure Active Directory (Managed Identity)
Azure Monitor


Steps Performed


Created an Azure Key Vault and generated a customer-managed key
Created an Azure Storage Account
Configured the Storage Account to use the customer-managed key from Key Vault
Assigned a managed identity to the Storage Account for Key Vault access
Uploaded data to the storage account and verified encryption with the CMK
Rotated the key and confirmed continued access to encrypted data


Outcome

Lab validation passed ✅ — 100%