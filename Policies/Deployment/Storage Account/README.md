# Cmdlet for deployment

`az policy definition create --name 'storage-account-deploy-if-not-exists-firewall-rules' --description 'Deploy If Not Exists Firewall Rules To Storage Account And Deny Internet Access' --display-name 'Storage Account - Deploy If Not Exists Firewall Rules To Storage Account And Deny Internet Access' --rules Storage-Account-Deploy-If-Not-Exists-Firewall-Rules.json --params Storage-Account-Deploy-If-Not-Exists-Firewall-Rules.parameters.json --mode ALL`

`az policy definition create --management-group testmg --name 'storage-account-deploy-if-not-exists-firewall-rules' --description 'Deploy If Not Exists Firewall Rules To Storage Account And Deny Internet Access' --display-name 'Storage Account - Deploy If Not Exists Firewall Rules To Storage Account And Deny Internet Access' --rules Storage-Account-Deploy-If-Not-Exists-Firewall-Rules.json --params Storage-Account-Deploy-If-Not-Exists-Firewall-Rules.parameters.json --mode ALL`
