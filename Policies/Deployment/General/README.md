# Cmdlet for deployment

`az policy definition create --name 'General-Deny-Public-Network-Access-For-PaaS-Services' --description 'Deny Public Network Access For PaaS Services' --display-name 'General - Deny Public Network Access For PaaS Services' --rules General-Deny-Public-Network-Access-For-PaaS-Services.json --params General-Deny-Public-Network-Access-For-PaaS-Services.parameters.json --mode ALL`

`az policy definition create --management-group testmg --name 'General-Deny-Public-Network-Access-For-PaaS-Services' --description 'Deny Public Network Access For PaaS Services' --display-name 'General - Deny Public Network Access For PaaS Services' --rules General-Deny-Public-Network-Access-For-PaaS-Services.json --params General-Deny-Public-Network-Access-For-PaaS-Services.parameters.json --mode ALL`
