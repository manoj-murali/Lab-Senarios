#Lab Scenario : Deploy a Windows VM with Custom script extension

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmanoj-murali%2FLab-Senarios%2Fcustomscript-windows-troubleshooting%2Fazuredeploy.json)


This template deploys a simple windows VM nd execute a custom PowerShell script using the custom script extension. The PowerShell script installs a file on the VM. The script and file must be staged in Azure storage and that can be done automatically using the deployment scripts in the root of this repo.

Note** This template is created for a lab senarios to troubleshoot extension failures
for the working template go to https://github.com/Azure/azure-quickstart-templates/tree/master/201-vm-custom-script-windows



