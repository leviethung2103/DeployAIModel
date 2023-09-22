## Deploy-ML-Model-FastAPI-MLFlow-MINIO-MySQL
This repository about how to deploy machine learning model end serving with FastAPI and using MLFlow-MINIO

## Setup

Firstly, you need to create the virtual environment. There are two options such as Anaconda or native virtual environment.
### Option 1: Create a new environment
```
# create virtual env
conda create -n myenv python=3.8
# activate environment
conda activate myenv
# install requirements
pip install -r requirements.txt
```

### Option 2: Native Virtual Environment
```
# create virtual env
virtualenv deploy_env
# activate environment
source deploy_env/bin/activate
```

## Usage
```
docker-compose up -d mysql mlflow minio
```

