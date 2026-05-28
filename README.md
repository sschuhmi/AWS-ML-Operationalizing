# AWS-ML-Operationalizing
Project "Operationalizing an AWS Machine Learning Project" (part of Udacity nd189)

## Intro

This project focuses on the operationalizing of a completed ML Project in AWS SageMaker.
The project uses several important tools and features of AWS to adjust, improve, configure, and prepare the model for production-grade deployment.
The following aspects of AWS machine learning operations are regarded:
- How to manage computing resources efficiently
- How to train models with large datasets using multi-instance training
- How to set up high-throughput, low-latency pipelines
- How to exploit AWS security

## Step 1: Training & deployment in AWS Sagemaker

### 1.1 Creation of Jupyter Notebook in Sagemaker Studio 
The notebook was created using the instance "type ml.t3.medium" (see screenshot), which should be an adequate choice since it provides sufficient performance for most typical tasks, but reasonably limits costs. In case more power is needed, a change of the instance type to one with more power (e.g., "ml.m5.xlarge") could be the next step.

The notebook uses the AWS Execution Role also shown in the screenshot. Moreover, this execution role was given the S3FullAccess permission to be able to communicate with S3 buckets.
![image](01a_Notebook-Setup.jpg)

![image](01b_Notebook-Creation.jpg)

![image](01c_Permissions.jpg)

### 1.2 Creation of S3 Bucket
To be able to save and provide data to Sagemaker, the following S3 bucket (see screenshot) was created in the AWS account.
![image](02_S3-Bucket.jpg)

### 1.3 Deployment & Training


## Step 2: Training on EC2

## Step 3: Setup of Lambda Function

## Step 4: Lambda security setup & testing

## Step 5: Lambda Concurrency setup & Endpoint Auto-scaling
