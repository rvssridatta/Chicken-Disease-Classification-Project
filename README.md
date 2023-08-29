# Chicken-Disease-Classification-Project



## Workflows

Update config.yaml
Update secrets.yaml [Optional]
Update params.yaml
Update the entity
Update the configuration manager in src config
Update the components
Update the pipeline
Update the main.py
Update the dvc.yaml


# How to run?

## STEPS:

Clone the repository

https://github.com/rvssridatta/Chicken-Disease-Classification-Project.git


## STEP 01- Create a conda environment after opening the repository

conda create -n envchicken python=3.8 -y

conda activate envchicken

## STEP 02- install the requirements

pip install -r requirements.txt

#Finally run the following command
python app.py

Now,

open up you local host and port



# AZURE-CICD-Deployment-with-Github-Actions

## Save password:

******************

## Run from terminal:

docker build -t chickenapp.azurecr.io/chicken:latest

docker login chickenapp.azurecr.io

docker push chickenapp.azurecr.io/chicken:latest

# Deployment Steps:

1) Build the Docker image of the Source Code
2) Push the Docker image to Container Registry
3) Launch the Web App Server in Azure
4) Pull the Docker image from the container registry to Web App server and run