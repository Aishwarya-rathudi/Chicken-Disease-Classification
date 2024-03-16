# Chicken-Disease-Classification-Project

## Workflows
1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml

## AZURE-CICD-Deployment-with-Github-Actions

## Save pass

## Run from terminal:
docker build -t chicken.azurecr.io/chicken:latest .

docker login chicken.azurecr.io

docker push chickenapp.azurecr.io/chicken:latest

## Deployment Steps:
Build the Docker image of the Source Code
Push the Docker image to Container Registry
Launch the Web App Server in Azure
Pull the Docker image from the container registry to Web App server and run
