# MLflow Prompt Management UI Exploration

Setup instructions

1. Set Open AI API Key 

```
export OPENAI_API_KEY=your_api_key_here
```

2. Start AI Gateway

```
mlflow gateway start --config-path config.yaml --port 7000
```

3. Set Gateway URI and start MLflow server

```
export MLFLOW_GATEWAY_URI="http://127.0.0.1:7000"
mlflow server --port 5000

```