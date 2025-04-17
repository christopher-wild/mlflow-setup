FROM python:3.12.slim

RUN apt-get -qq update && apt-get -qq install -y

# Install python packages
RUN pip install mlflow psycopg2-binary boto3

