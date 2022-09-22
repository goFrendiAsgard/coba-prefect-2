# Prefect 2 with Docker Compose

# Start prefect

```bash
docker-compose up
# or docker-compose up -d
```

You can access orion UI by visiting `http://localhost:4200`

# Create a deployment

```bash
python -m venv venv
source ./venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
export PREFECT_API_URL=http://localhost:4200/api
python deployment.py
```

# Run the flow

Click on `Deployments` menu.

# Stop prefect

```bash
docker-compose down
```