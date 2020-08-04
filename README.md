# Introduction 
Azure DevOps Resource Group Example.


The basic root of the ARM Template

```json

{
  "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
  "contentVersion": "1.0.0.0",
  "resources": []
}

```


- $schema: Specifies the location of the JSON schema file. The schema file describes the properties that are available within a template. For example, the schema defines resources as one of the valid properties for a template. Don't worry that the date for the schema is 2019-04-01. This schema version is up to date and includes all of the latest features. The schema date hasn't been changed because there have been no breaking changes since its introduction.
- contentVersion: Specifies the version of the template (such as 1.0.0.0). You can provide any value for this element. Use this value to document significant changes in your template. When deploying resources using the template, this value can be used to make sure that the right template is being used.
- resources: Contains the resources you want to deploy or update.

# Document Links
- [Create Resource Group With ARM](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-create-first-template)
- [Create Empty Resource Group](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-subscription)

# Type Links
- [Microsoft.Resources/resourceGroups](https://docs.microsoft.com/en-us/azure/templates/microsoft.resources/2020-06-01/resourcegroups)

# Extensions
- [ARM Parameter Generator](https://marketplace.visualstudio.com/items?itemName=wilfriedwoivre.arm-params-generator)
- [ARM Template Viewer](https://marketplace.visualstudio.com/items?itemName=bencoleman.armview)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Azure Resource Manager](https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools)
- [AzSK (Secure DevOps Kit for Azure)](https://aka.ms/devopskit/baseline)
- [Visual Studio Security IntelliSense](https://github.com/azsk/DevOpsKit-docs/blob/master/02-Secure-Development/Readme.md#security-intellisense-dev-secintel-1)


# Microsoft GitHub
- [Microsoft GitHub Registration Guide](https://microsoftapc.sharepoint.com/:w:/r/teams/Selfhost-VisionAIDevKit/_layouts/15/doc2.aspx?sourcedoc=%7B4C91E1B5-80B2-433F-BB40-C1C8FD49AAEB%7D&file=MicrosoftGitHub-RegistrationGuide.docx&action=default&mobileredirect=true&DefaultItemOpen=1&cid=3f3ae1cf-90e1-45ca-9d33-03b89972cf09)
- [GitHub Inside Microsoft](https://microsoft.sharepoint.com/teams/GitHubInsideMicrosoft)
- [Early Adopters](https://aka.ms/1es/github/early-adopters)