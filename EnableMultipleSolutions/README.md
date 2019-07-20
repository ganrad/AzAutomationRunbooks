# Enable Multiple Solutions on Azure VMs

This sample automation runbook onboards Azure VMs for either the Update or ChangeTracking (which includes Inventory) solution. It requires an existing Azure VM to already be onboarded to the solution as it uses this information to onboard the new VM to the same Log Analytics workspace and Automation Account.
