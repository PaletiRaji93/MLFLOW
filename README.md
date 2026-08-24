#ML FLOW EXPERIMENTS


import dagshub
dagshub.init(repo_owner='PaletiRaji93', repo_name='MLFLOW', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


https://dagshub.com/PaletiRaji93/MLFLOW.mlflow