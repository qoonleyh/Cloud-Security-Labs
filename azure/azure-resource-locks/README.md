Azure Resource Locks

Overview

This lab demonstrates how to apply Azure Resource Locks to prevent accidental deletion or modification of critical resources, implementing both ReadOnly and Delete lock types at different resource hierarchy levels.

Services Used


Azure Resource Locks
Azure Resource Manager (ARM)
Azure Virtual Machines
Azure Storage Account
Azure Role-Based Access Control (RBAC)


Steps Performed


Created Azure resources including a VM and Storage Account
Applied a Delete lock to the Storage Account to prevent accidental deletion
Applied a ReadOnly lock to the VM to prevent modifications
Attempted to delete and modify locked resources to verify lock enforcement
Removed locks and verified resources could then be modified or deleted
Reviewed lock inheritance behaviour across resource groups


Outcome

Lab validation passed ✅ — 100%