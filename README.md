# cpe393-mlflow
Experiment tracking CPE93

Dataset - https://github.com/DataTalksClub/nyc-tlc-data/releases/tag/green

Lab - model_registry

# REFERENCES

1. https://stephen137.github.io/posts/MLOps_Zoomcamp_Module_2/MLOps_Zoomcamp_Module_2.html

2. https://github.com/DataTalksClub/mlops-zoomcamp

# cpe393-mlflow
Experiment tracking CPE93

Dataset - https://github.com/DataTalksClub/nyc-tlc-data/releases/tag/green

Lab - model_registry

# REFERENCES

1. https://stephen137.github.io/posts/MLOps_Zoomcamp_Module_2/MLOps_Zoomcamp_Module_2.html

2. https://github.com/DataTalksClub/mlops-zoomcamp



Lab: Model Registry (Submit to LEB2) 
• Write a python notebook for model registry (model_registry.ipynb) →use notebook from Github
https://github.com/ayehninnkhine/cpe393-mlflow
Comparing versions and selecting the new "Production" model
The idea is to simulate the scenario in which a deployment engineer has to interact with the model registry to decide whether toupdate the model version that is in production or not.
These are the steps:
Load the test dataset, which corresponds to the NYC Green Taxi data from the month of March 2021.
Download the DictVectorizer that was fitted using the training data and saved to MLflow as an artifact,  and load it with pickle.
Preprocess the test set using the DictVectorizer so we can properly feed the regressors.
Make predictions on the test set using the model versions that are currently in the "Staging" and "Production" stages, and co mpare their performance.
Based on the results, update the "Production" model version accordingly.