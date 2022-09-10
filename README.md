# Prefect 2 with Docker Compose

# How to start

```bash
docker-compose up
```

You can access orion UI by visiting `http://localhost:4200`

# Create a deployment

```bash
python -m venv venv
pip install -r requirements.txt
export PREFECT_API_URL=http://localhost:4200/api
python deployment.py
```

# Run the flow

Click on `Deployments` menu.