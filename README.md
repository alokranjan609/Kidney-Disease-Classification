# Kidney-Disease-Classification-MLflow-DVC




# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/alokranjan609/Kidney-Disease-Classification
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up your localhost and port
```






## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI="YOUR_URI
MLFLOW_TRACKING_USERNAME="YOUR_USERNAME
MLFLOW_TRACKING_PASSWORD="YOUR_KEY"
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=""

export MLFLOW_TRACKING_USERNAME=""

export MLFLOW_TRACKING_PASSWORD=""

```


### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)



