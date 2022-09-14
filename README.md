# swa-sample

This is a repo you can use to create you resume or perhaps host a project, up to you.

## Deploy

To deploy to Azure, you need to first do the following:

1. [Sign up to Azure](https://azure.microsoft.com/en-gb/free/students/)
1. [Install Visual Studio Code](https://code.visualstudio.com/download)
1. [Install Azure Static Web Apps extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurestaticwebapps)

Onece you have those prereqs, you're ready to go.

In Visual Studio Code,

1. Open up the Command Palette (select View / Command Pallette) and type "Azure Static Web Apps :Create Static Web Apps" (you don't need to type out the whole thing, due to auto complete, but start typing and select the indicated option)
1. Select subscription
1. If you haven't create a Git repo, the dialog can create for you (select Create in that case). An initial commit will be added as well
1. Enter the name of your static web app, for example "my-project" 
1. Enter the name of the GitHub repository (select what it suggests if you don't have another repo in mind)
1. Select region
1. Select custom when asked about preset
1. Enter "/" as location of application code
1. Enter blank as build location (a simple static app doesn't have one)

