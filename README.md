Useful Links for Terraform operations in an Azure environment.
Install:
Installing Terraform | Terraform
Install and configure Terraform to provision Azure resources - Azure Linux Virtual Machines
Auth methods:
Provider: Azure
Azure Provider: Authenticating via the Azure CLI
Azure Provider: Authenticating via a Service Principal and a Client Certificate
Resource deployments covered in this course:
Resource Groups
Azure Resource Manager: azurerm_resource_group
Storage:
Azure Resource Manager: azurerm_storage_account
Recovery Service Vaults don’t fall under storage for Terraform, but they *are* storage
and fairly important so I’ve included the link in this section as well.
Azure Resource Manager: azurerm_recovery_services_vault
Azure Resource Manager: azurerm_storage_blob
Azure Resource Manager: azurerm_storage_share
Networking:
Azure Resource Manager: azurerm_virtual_network
Azure Resource Manager: azurerm_subnet
Azure Resource Manager: azurerm_network_security_group
VMs:
Azure Resource Manager: azurerm_virtual_machine
Web Applications:
Azure Resource Manager: azurerm_app_service
Database Instances:
Azure Resource Manager: azurerm_mysql_database
State Files & Azure “Backends”
Backend Type: azurerm
Where to go from here?
https://linuxacademy.com/cp/modules/view/id/415
# terraform