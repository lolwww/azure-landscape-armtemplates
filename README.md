# Deploy Landscape Server on Azure

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Flolwww%2Fazure-landscape-armtemplates%2Fmain%2Flandscapeserver.json)


Installs Landscape on VM with Public IP on it's NIC and Network security group with ports 80,443,22 open.

Usage:

Deploy (for now) with:

https://portal.azure.com/#create/Microsoft.Template

Then click "build template in the editor"

Available params:

- Azure region
- VM size
- VM name
- dnsPrefix ( 'mylandscapeserver'for url like mylandscapeserver.eastus.cloudapp.azure.com)
- admin Username (for VM user)
- Vnet name to place VM
- Vnet subnet name
- ssh pulic key to access Landscape VM
