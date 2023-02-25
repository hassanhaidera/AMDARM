# AMDARM
to creat a group :
az group create --name  NAME --location eastus /n
deploy:
az deployment group create --resource-group NAME --template-file azuredeploy.json --parameters azuredeploy.parameters.json
