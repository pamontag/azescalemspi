# Cmdlet for deployment

`az policy definition create --name 'sql-azure-deploy-if-not-exists-azure-sql-firewall-rules' --description 'Deploy or Audit If Not Exists Azure Sql Firewall Rules' --display-name 'Sql Azure - Deploy If Not Exists Azure Sql Firewall Rules' --rules Sql-Azure-Deploy-If-Not-Exists-Azure-Firewall-Rules.json --params Sql-Azure-Deploy-If-Not-Exists-Azure-Firewall-Rules.parameters.json --mode ALL`

`az deployment create --template-file Sql-Azure-Deploy-If-Not-Exists-Azure-Firewall-Rules-Initiative.json --location westeurope`