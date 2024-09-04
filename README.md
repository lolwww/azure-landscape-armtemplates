# azure-landscape-armtemplates
ARM templates to deploy Landscape server

Use it to deploy single-instance Landscape Server on Azure.
Installs Landscape on VM with Public IP on it's NIC and Network security group with ports 80,443,22 open.

Usage:

Deploy (for now) with:
https://portal.azure.com/#create/Microsoft.Template

Available params:

- Azure region
- VM size
- VM name
- dnsPrefix ( 'mylandscapeserver'for url like mylandscapeserver.eastus.cloudapp.azure.com)
- admin Username (for VM user)
- Vnet name to place VM
- Vnet subnet name
- ssh pulic key to access Landscape VM
