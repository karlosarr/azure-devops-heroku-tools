# Azure DevOps Heroku Tools
[![Build Status](https://dev.azure.com/karlosarr/Azure%20DevOps%20Heroku%20Tools/_apis/build/status/karlosarr.azure-devops-heroku-tools?branchName=master)](https://dev.azure.com/karlosarr/Azure%20DevOps%20Heroku%20Tools/_build/latest?definitionId=19&branchName=master)

Release tasks for [Azure Pipelines](http://go.microsoft.com/fwlink/?LinkId=619385) to work with [Heroku](https://www.heroku.com).

## Installation
The release tasks can be installed by adding the [Heroku Release Tools Extension](https://marketplace.visualstudio.com/items?itemName=ckrnstck.devops-heroku-tools) from the Marketplace to your organization.

## Build
Use the [tfx cli](https://www.npmjs.com/package/tfx-cli) to build an extension package.

```bash
$ tfx extension create
```
