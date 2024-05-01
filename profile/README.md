# Openfido

Welcome to the Openfido Organization's repository hub! Here is where you can find the repositories used to build our open-source application, as well as the pipeline's used within the Openfido framework.

# Getting Started
There are several options to help new users starting out with OpenFIDO, which is accessible through several distinct methods, or developers looking to help contribute to the project. 
	
## Sign up to shared app
You can email support@openfido.org to request to utilize the online application's resources. Once your request to use the application is approved, you will have access to all publicly available repositories that can be automatically searched in this organization, or you can manually designate your own repositories to run.

## Host Locally
You can follow the instructions on the [OpenFIDO App Service](https://github.com/openfido/openfido-app-service) page or the [OpenFIDO Command Line Interface](https://github.com/openfido/cli) to set up locally, and run OpenFIDO to your prefererred method. 

## Deploy to AWS
You can use this code as a base to deploy your own OpenFIDO AWS servers. While the majority of the terraform modules used to deploy this are available in the centralized [OpenFIDO](https://github.com/openfido/openfido) repository, you will need to provide your own code for the cloudfront, rds, ecs, and ses terraform modules, as those are proprietary and licensed to us, and therefore unavailable for use. 


## Application Status

| [App Service](https://github.com/openfido/openfido-app-service) | [Auth Service](https://github.com/openfido/openfido-auth-service) | [Workflow Service](https://github.com/openfido/openfido-workflow-service) | [Client Service](https://github.com/openfido/openfido-client)
| :---: | :---: | :---: | :---: |
| [![Test-build](https://github.com/openfido/openfido-app-service/actions/workflows/test-build.yml/badge.svg)](https://github.com/openfido/openfido-app-service/actions/workflows/test-build.yml) | [![Test-build](https://github.com/openfido/openfido-auth-service/actions/workflows/test-build.yml/badge.svg)](https://github.com/openfido/openfido-auth-service/actions/workflows/test-build.yml) | [![Test-build](https://github.com/openfido/openfido-workflow-service/actions/workflows/test-build.yml/badge.svg?branch=master)](https://github.com/openfido/openfido-workflow-service/actions/workflows/test-build.yml) | [![Test-build](https://github.com/openfido/openfido-client/actions/workflows/test-build.yml/badge.svg?branch=master)](https://github.com/openfido/openfido-client/actions/workflows/test-build.yml) |
| [![Deploy Staging](https://github.com/openfido/openfido-app-service/actions/workflows/docker-deploy-stage.yml/badge.svg?branch=develop)](https://github.com/openfido/openfido-app-service/actions/workflows/docker-deploy-stage.yml) | [![Deploy Staging](https://github.com/openfido/openfido-auth-service/actions/workflows/docker-deploy-stage.yml/badge.svg?branch=develop)](https://github.com/openfido/openfido-auth-service/actions/workflows/docker-deploy-stage.yml) | [![Deploy Staging](https://github.com/openfido/openfido-workflow-service/actions/workflows/docker-deploy-stage.yml/badge.svg?branch=develop)](https://github.com/openfido/openfido-workflow-service/actions/workflows/docker-deploy-stage.yml) | [![Deploy Staging](https://github.com/openfido/openfido-client/actions/workflows/docker-deploy-stage.yml/badge.svg?branch=develop)](https://github.com/openfido/openfido-client/actions/workflows/docker-deploy-stage.yml) |
| [![Deploy Production](https://github.com/openfido/openfido-app-service/actions/workflows/docker-deploy-prod.yml/badge.svg)](https://github.com/openfido/openfido-app-service/actions/workflows/docker-deploy-prod.yml) | [![Deploy Production](https://github.com/openfido/openfido-auth-service/actions/workflows/docker-deploy-prod.yml/badge.svg)](https://github.com/openfido/openfido-auth-service/actions/workflows/docker-deploy-prod.yml) | [![Deploy Production](https://github.com/openfido/openfido-workflow-service/actions/workflows/docker-deploy-prod.yml/badge.svg)](https://github.com/openfido/openfido-workflow-service/actions/workflows/docker-deploy-prod.yml) | [![Deploy Production](https://github.com/openfido/openfido-client/actions/workflows/docker-deploy-prod.yml/badge.svg)](https://github.com/openfido/openfido-client/actions/workflows/docker-deploy-prod.yml) |

## Pipeline Status

Pipeline  | Status
------------- | -------------
[Tariff Design](https://github.com/openfido/tariff_design)  | [![validation](https://github.com/openfido/tariff_design/actions/workflows/main.yml/badge.svg)](https://github.com/openfido/tariff_design/actions/workflows/main.yml)
[Loadshape](https://github.com/openfido/loadshape)  | [![validation](https://github.com/openfido/loadshape/actions/workflows/main.yml/badge.svg)](https://github.com/openfido/loadshape/actions/workflows/autotest.yml)
[Weather](https://github.com/openfido/weather)  |  [![validation](https://github.com/openfido/weather/actions/workflows/autotest.yml/badge.svg)](https://github.com/openfido/weather/actions/workflows/autotest.yml)
[HiPAS GridLAB-D](https://github.com/openfido/gridlabd)  |  [![validation](https://github.com/openfido/gridlabd/actions/workflows/autotest.yml/badge.svg)](https://github.com/openfido/gridlabd/actions/workflows/autotest.yml)
[Census](https://github.com/openfido/census)  |  [![validation](https://github.com/openfido/census/actions/workflows/main.yml/badge.svg)](https://github.com/openfido/census/actions/workflows/main.yml)
[Resilience](https://github.com/openfido/resilience)  |  [![validation](https://github.com/openfido/resilience/actions/workflows/main.yml/badge.svg)](https://github.com/openfido/resilience/actions/workflows/main.yml)
[Hosting Capacity](https://github.com/openfido/hosting_capacity)  |  [![validation](https://github.com/openfido/hosting_capacity/actions/workflows/autotest.yml/badge.svg)](https://github.com/openfido/hosting_capacity/actions/workflows/autotest.yml)
[Electrification](https://github.com/openfido/electrification)  |  [![validation](https://github.com/openfido/electrification/actions/workflows/autotest.yml/badge.svg)](https://github.com/openfido/electrification/actions/workflows/autotest.yml)
[Address](https://github.com/openfido/address)  |  [![validation](https://github.com/openfido/address/actions/workflows/main.yml/badge.svg)](https://github.com/openfido/address/actions/workflows/main.yml)
[Cyme Converter](https://github.com/openfido/cyme-extract) | [![validation](https://github.com/openfido/cyme-extract/actions/workflows/main.yml/badge.svg)](https://github.com/openfido/cyme-extract/actions/workflows/main.yml)
