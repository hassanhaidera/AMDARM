# AMDARM
<h4>to creat a group :<h4>
az group create --name  NAME --location eastus 
<h4>deploy:<h4>
az deployment group create --resource-group NAME --template-file azuredeploy.json --parameters azuredeploy.parameters.json
