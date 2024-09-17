# deploy-azure-resources-arm-bicep
A collection of Azure ARM templates and Bicep files for deploying IaaS, PaaS, and hybrid cloud resources. Includes examples for Virtual Networks, Storage Accounts, Virtual Machines, and Azure Arc integration.
# Azure ARM Templates and Bicep Files for IaaS, PaaS, and Hybrid Cloud Deployments
This repository contains a collection of Azure Resource Manager (ARM) templates and Bicep files designed to simplify the deployment of Azure resources, including Virtual Networks, Storage Accounts, Virtual Machines, and Azure Arc-enabled services. These examples cater to different deployment models such as IaaS (Infrastructure as a Service), PaaS (Platform as a Service), and hybrid cloud setups.
## IaaS Deployments
### Virtual Network Deployment
- [ARM Template](iaas/virtual-network/virtual-network-arm-template.json)
- [Bicep File](iaas/virtual-network/virtual-network-bicep-template.bicep)
### Keywords
Azure ARM templates, Bicep files, Azure deployment, IaaS, PaaS, hybrid cloud, virtual networks, storage accounts, virtual machines, Azure Arc
## How to Deploy
### Deploying ARM Templates
Save the ARM template file and use the following Azure CLI command:
```bash
az deployment group create --resource-group <your-resource-group> --template-file <filename>.json
az deployment group create --resource-group <your-resource-group> --template-file <filename>.bicep
