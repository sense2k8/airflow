FROM apache/airflow:2.5.0

USER root

RUN apt-get update -y
RUN apt-get install -y iputils-ping

RUN pip3 install Faker numpy boto3 botocore
