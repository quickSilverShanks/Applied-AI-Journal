## MLFlow - Optuna - Orchestration

The module is based off a Kaggle notebook that uses mlflow and optuna to optimize hyperparametrs for an xgboost model to predict diabetes.


### Setting Up the Module

#### Virtual environment creation

```bash
conda create --name aijournal python=3.10
conda activate aijournal
pip install ipykernel
pip install mlflow xgboost optuna seaborn umap-learn
pip freeze > requirements.txt
```


Once the notebook has been run with experiment being logged in mlflow, below command can be run in terminal to launch and compare model performances in mlflow UI

```bash
mlflow ui
```

<hr>

### Reference Links

- Notebook: https://www.kaggle.com/code/andrprovensi/diabetes-eda-xgboost-optuna-and-mlflow
- Data: https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
