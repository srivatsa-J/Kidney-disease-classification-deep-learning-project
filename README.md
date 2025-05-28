# Kidney Disease Classification Deep Learning Project

## Workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml
10. app.py

## How to run?

### STEPS:

#### Step 1: Clone the repository

```bash
git clone https://github.com/srivatsa-J/Kidney-disease-classification-deep-learning-project
cd Kidney-disease-classification-deep-learning-project
```

#### Step 2: Create and activate the conda environment

```bash
conda create -n cnncls python=3.8 -y
conda activate cnncls
```

#### Step 3: Install the requirements

```bash
pip install -r requirements.txt
```

## MLflow Tracking with DagsHub

This project uses [MLflow](https://mlflow.org/) for experiment tracking, integrated with [DagsHub](https://dagshub.com/).

### Launch MLflow UI Locally

To run the MLflow UI locally, use:

```bash
mlflow ui

'''
set MLFLOW_TRACKING_URI=https://dagshub.com/srivatsa.ai22/Kidney-disease-classification-deep-learning-project.mlflow
set MLFLOW_TRACKING_USERNAME=srivatsa.ai22
set MLFLOW_TRACKING_PASSWORD=52794c4800701621d7b6dc515564aa936a6c6d6a
'''
