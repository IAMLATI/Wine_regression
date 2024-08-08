# Wine_regression

## DAGSHUB:
MLFLOW_TRACKING_URI=https://dagshub.com/IAMLATI/Wine_regression.mlflow
MLFLOW_TRACKING_USERNAME=IAMLATI
MLFLOW_TRACKING_PASSWORD=8646df330d26e1031e07a28bb8aaa00589856d67

python script.py


CMD
set MLFLOW_TRACKING_URI=https://dagshub.com/IAMLATI/Wine_regression.mlflow
set MLFLOW_TRACKING_USERNAME=IAMLATI
set MLFLOW_TRACKING_PASSWORD=8646df330d26e1031e07a28bb8aaa00589856d67

AWS
mlflow server -h 0.0.0.0 --default-artifact-root s3://iamlati-mlflow-buc
set MLFLOW_TRACKING_URI=http://ec2-51-20-54-147.eu-north-1.compute.amazonaws.com:5000
