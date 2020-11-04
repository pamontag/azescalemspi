# Cmdlet for deployment

`az policy definition create --name 'Data-Lake-Deny-Firewall-State-Disabled' --description 'Deny Firewall State Disabled For Data Lake Services' --display-name 'Data Lake - Deny Firewall State Disabled' --rules Data-Lake-Deny-Firewall-State-Disabled.json --params Data-Lake-Deny-Firewall-State-Disabled.parameters.json --mode ALL`

`az policy definition create --management-group testmg --name 'Data-Lake-Deny-Firewall-State-Disabled' --description 'Deny Firewall State Disabled For Data Lake Services' --display-name 'Data Lake - Deny Firewall State Disabled' --rules Data-Lake-Deny-Firewall-State-Disabled.json --params Data-Lake-Deny-Firewall-State-Disabled.parameters.json --mode ALL`
