# Cmdlet for deployment

`az policy definition create --name 'LA-AI-Deny-Public-Access-For-Query-Ingestion' --description 'Deny or Audit Public Access for Query or Ingestion' --display-name 'Log Analytics Application Insights - Deny Public Access For Query Ingestion' --rules Log-Analytics-Application-Insights-Deny-Public-Access-For-Query-Ingestion.json --params Log-Analytics-Application-Insights-Deny-Public-Access-For-Query-Ingestion.parameters.json --mode ALL`

`az policy definition create --management-group testmg --name 'LA-AI-Deny-Public-Access-For-Query-Ingestion' --description 'Deny or Audit Public Access for Query or Ingestion' --display-name 'Log Analytics Application Insights - Deny Public Access For Query Ingestion' --rules Log-Analytics-Application-Insights-Deny-Public-Access-For-Query-Ingestion.json --params Log-Analytics-Application-Insights-Deny-Public-Access-For-Query-Ingestion.parameters.json --mode ALL`
