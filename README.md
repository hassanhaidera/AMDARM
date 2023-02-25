# AMDARM
to creat a group :
az group create --name  NAME --location eastus
deploy:
az deployment group create --resource-group NAME --template-file azuredeploy.json --parameters azuredeploy.parameters.json
