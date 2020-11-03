![Azure Public Test Date](https://azurequickstarttemplates.blob.core.windows.net/hubspoke/PublicLastTestDate.svg)
![Azure Public Test Result](https://azurequickstarttemplates.blob.core.windows.net/hubspoke/PublicDeployment.svg)

![Best Practice Check](https://azurequickstarttemplates.blob.core.windows.net/hubspoke/BestPracticeResult.svg)

[![Visualize](https://azurequickstarttemplates.blob.core.windows.net/hubspoke/visualizebutton.svg)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FLaxmanranga%2FHub-spoke%2FMaster%2FAzure-Hub-Spoke.json)

[![Deploy To Azure](https://azurequickstarttemplates.blob.core.windows.net/hubspoke/deploytoazure.svg)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FLaxmanranga%2FHub-spoke%2FMaster%2FAzure-Hub-Spoke.json)



This template creates a basic hub-and-spoke topology setup. It creates a Hub VNet with subnets DMZ, Management, Shared and Gateway (optionally), with two Spoke VNets, development and production, containing a workload subnet each. It also deploys a Windows Jump-Host on the Management subnet of the HUB, and establishes VNet peerings between the Hub and the two spokes. And also it creates a VM SPoke VM1 in Spoke Prod network.

Note that if you choose to deploy the VPN gateway, it may take up to 45 minutes to complete.


