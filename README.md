# Scheduler Job with Web App

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FWelasco%2FAzureTemplate%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FWelasco%2AzureTemplate%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template will deploy a WebApp and a Application Service Plan.

The Application Service Plan will have this size:

VM Size: S1 

Service Plan: Standard

The WebApp will have a autoscale setup to:

Default instance: 1

Max instances: 2

CPU load: 60%

WebApp config:

Always On: True
