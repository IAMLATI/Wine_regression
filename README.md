###Wine_regression

## DAGSHUB:
MLFLOW_TRACKING_URI=https://dagshub.com/IAMLATI/Wine_regression.mlflow
MLFLOW_TRACKING_USERNAME=IAMLATI.


python script.py


CMD
set MLFLOW_TRACKING_URI=https://dagshub.com/IAMLATI/Wine_regression.mlflow
set MLFLOW_TRACKING_USERNAME=IAMLATI


AWS
mlflow server -h 0.0.0.0 --default-artifact-root s3://iamlati-mlflow-buc
set MLFLOW_TRACKING_URI=http://ec2-51-20-54-147.eu-north-1.compute.amazonaws.com:5000
