![Azure Public Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/101-hub-and-spoke-sandbox/PublicLastTestDate.svg)
![Azure Public Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/101-hub-and-spoke-sandbox/PublicDeployment.svg)

![Best Practice Check](https://azurequickstartsservice.blob.core.windows.net/badges/101-hub-and-spoke-sandbox/BestPracticeResult.svg)


[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-hub-and-spoke-sandbox%2Fazuredeploy.json)
[![Deploy To Azure US Gov](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.svg?sanitize=true)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-hub-and-spoke-sandbox%2Fazuredeploy.json)
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-hub-and-spoke-sandbox%2Fazuredeploy.json)

This template creates a basic hub-and-spoke topology setup. It creates a Hub VNet with subnets DMZ, Management, Shared and Gateway (optionally), with two Spoke VNets, development and production, containing a workload subnet each. It also deploys a Windows Jump-Host on the Management subnet of the HUB, and establishes VNet peerings between the Hub and the two spokes. And also it creates a VM SPoke VM1 in Spoke Prod network.

Note that if you choose to deploy the VPN gateway, it may take up to 45 minutes to complete.
