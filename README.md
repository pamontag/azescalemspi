# Azure Enterprise Scale 

Selection of Azure Policies for Enterprise Scale

Deploy them with
```
az policy definition create --name 'audit-subnets-without-NSG' --display-name 'Audit Virtual Networks Subnets Without Network Security Group' --description 'This policy ensures that virtual network subnets has assigned a Network Security Group.' --rules 'Deny_subnet_without_network_security_group.json' --mode All
```
