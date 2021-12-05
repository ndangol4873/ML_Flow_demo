# ML_Flow_demo
Working with the ML_Flow_Liabrary

# Important Commands

mlflow.set_tracking_uri(remote_server_uri)

mlflow.set_experiment(mlflow_config["experiment_name"]

## mlflow server command -

mlflow server \
--backend-store-uri sqlite:///mlflow.db \
--default-artifact-root ./artifacts \
--host 0.0.0.0 -p 1234