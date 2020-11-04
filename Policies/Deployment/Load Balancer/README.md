# Cmdlet for deployment

`az policy definition create --name 'Load-Balancer-Application-Gateway-Deny-PublicIpAddress' --description 'Deny or Audit Public Ip Addresses' --display-name 'Load Balancer Application Gateway - Deny or Audit Public Ip Addresses' --rules Load-Balancer-Application-Gateway-Deny-PublicIpAddress.json --params Load-Balancer-Application-Gateway-Deny-PublicIpAddress.parameters.json --mode ALL`

`az policy definition create --management-group testmg --name 'Load-Balancer-Application-Gateway-Deny-PublicIpAddress' --description 'Deny or Audit Public Ip Addresses' --display-name 'Load Balancer Application Gateway - Deny or Audit Public Ip Addresses' --rules Load-Balancer-Application-Gateway-Deny-PublicIpAddress.json --params Load-Balancer-Application-Gateway-Deny-PublicIpAddress.parameters.json --mode ALL`
