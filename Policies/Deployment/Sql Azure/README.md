# Cmdlet for deployment

`az policy definition create --name 'deploy-if-not-exists-azure-sql-firewall-rules' --description 'deploy or audit if not exists azure sql firewall rules' --display-name 'deploy if not exists azure sql firewall rules' --rules Deploy-If-Not-Exists-Azure-Firewall-Rules.json --params Deploy-If-Not-Exists-Azure-Firewall-Rules.parameters.json --mode ALL`
