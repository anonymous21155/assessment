# Assessment Evaluation Repo

## TASK 1
**Objective:** Create a Azure VM using ARM template

**Output:** created a json file with resoucrces and paramters for the vm creation. The result is uploaded in the repo [azure-deploy.json](https://github.com/anonymous21155/assessment/blob/main/azure-deploy.json). Used __Deploy a custom template__ service from azure portal upload the json and ethe file was succesfully validated for deployment.

## TASK 2

**Objective:** Build a java app using azure pipeline

**Resource**: [forked repo](https://github.com/anonymous21155/pipelines-java)

**Output:** Forked a java app from github, connected to my project in azure devops organization and successfully build and archived the artifacts.The yaml file is uploaded in the repo [azure-pipeline.yaml](https://github.com/anonymous21155/assessment/blob/main/java-app-azure-pipelines.yml).

## TASK 3

__Objective:__ Run container image from node js app

__Resource:__ [source repo](https://github.com/anonymous21155/nodejs-app)

**Output**: Created a sample nodejs app with `npm init -y` command, hosted locally, build a docker file and run it locally, also pushed the container image to docker hub

## TASK 4

**Objective**: Deploy the containeraised image to AKS

__Output__: Connected the same [nodejs repo](https://github.com/anonymous21155/nodejs-app/tree/main) to another devops project and used *Deploy_to_azure_kubernetes_service* to build and upload the image to ACR and then to deploy to AKS.The pipeline ran succesfully and  the associated files are here with: [pipeline.yaml](https://github.com/anonymous21155/nodejs-app/blob/main/azure-pipelines.yml) , [deployment.yaml](https://github.com/anonymous21155/nodejs-app/blob/main/manifests/deployment.yml) , [service.yaml](https://github.com/anonymous21155/nodejs-app/blob/main/manifests/service.yml).

## Challenges

- I was not able to create a free subscription with a debit card. As per my understanding Azure won't accept debit cards.
