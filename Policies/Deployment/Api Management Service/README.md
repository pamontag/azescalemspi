# Cmdlet for deployment

`az policy definition create --name 'Api-Management-Services-Deny-Public-Ip-Addresses' --description 'Deny or Audit Public Ip Addresses' --display-name 'Api Management Services - Deny or Audit Public Ip Addresses' --rules Api-Management-Services-Deny-Public-Ip-Addresses.json --params Api-Management-Services-Deny-Public-Ip-Addresses.parameters.json --mode ALL`

`az policy definition create --management-group testmg --name 'Api-Management-Services-Deny-Public-Ip-Addresses' --description 'Deny or Audit Public Ip Addresses' --display-name 'Api Management Services - Deny or Audit Public Ip Addresses' --rules Api-Management-Services-Deny-Public-Ip-Addresses.json --params Api-Management-Services-Deny-Public-Ip-Addresses.parameters.json --mode ALL`
