# Cmdlet for deployment

`az policy definition create --name 'app-services-deploy-if-not-exists-firewall-rules' --description 'Deploy If Not Exists Firewall Rules To App Services And Deny Internet Access' --display-name 'App Services - Deploy If Not Exists Firewall Rules To App Service And Deny Internet Access' --rules App-Services-Deploy-If-Not-Exists-Firewall-Rules.json --params App-Services-Deploy-If-Not-Exists-Firewall-Rules.parameters.json --mode ALL`

`az policy definition create --management-group testmg --name 'app-services-deploy-if-not-exists-firewall-rules' --description 'Deploy If Not Exists Firewall Rules To App Services And Deny Internet Access' --display-name 'App Services - Deploy If Not Exists Firewall Rules To Storage Account And Deny Internet Access' --rules App-Services-Deploy-If-Not-Exists-Firewall-Rules.json --params App-Services-Deploy-If-Not-Exists-Firewall-Rules.parameters.json --mode ALL`
