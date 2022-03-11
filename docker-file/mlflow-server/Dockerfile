FROM python:3.8.12-slim

# Install mlflow
RUN python -m pip install --upgrade pip mlflow==1.24.0 psycopg2-binary pymysql boto3

# Expose mlflow port
EXPOSE 5001

# Define entry point
#ENTRYPOINT mlflow server --host 0.0.0.0 --port 5001