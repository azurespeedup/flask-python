# flask-ml-service
A sample Flask application to showcase the Azure Pipeline.

## Environment
Python 3.7

## command to create new webapp with specific resource group
az webapp up --resource-group Azuredevops --n flaskpythontrong --sku F1

## adding runtime & logs for above command
az webapp up --resource-group Azuredevops --n flaskpythontrong --sku F1 --logs --runtime "PYTHON:3.9"

