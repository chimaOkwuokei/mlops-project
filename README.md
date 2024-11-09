# mlops-project

# config.yaml
this is where you initialize the dataset amongst others

# to create a virtual environment
conda create -n mlproj

# incase the powershell hasn't been initialized to use conda
conda init powershell

# to deactivate venv
conda deactivate

# Run these on terminal to set environment variables
$env:MLFLOW_TRACKING_URI = "https://dagshub.com/chimaOkwuokei/mlops-project.mlflow"
$env:MLFLOW_TRACKING_USERNAME = "chimaOkwuokei"        
$env:MLFLOW_TRACKING_PASSWORD = "aaffcd86f8b97bfe6e1e606aaee57ca5cd3512dc"