# 🚗 End-to-End MLOps Vehicle Insurance Prediction System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-API-green)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-success)
![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue)
![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-black)
![MLOps](https://img.shields.io/badge/MLOps-Production-red)

### Production-Grade Machine Learning Pipeline with CI/CD, Cloud Deployment & Model Registry

Built using modern MLOps practices including Data Validation, Feature Engineering, Model Training, Model Evaluation, Docker, AWS, MongoDB, GitHub Actions, EC2, ECR and Automated Deployment.

</div>

---

# 📌 Project Overview

This project demonstrates a complete **Machine Learning Operations (MLOps)** workflow for Vehicle Insurance Prediction.

The objective is not only to train a machine learning model but also to build a **production-ready system** capable of:

* Automated Data Ingestion
* Data Validation
* Data Transformation
* Model Training
* Model Evaluation
* Model Registry
* Cloud Storage
* CI/CD Automation
* Dockerized Deployment
* Real-Time Predictions

The entire pipeline follows industry-standard MLOps architecture used by modern AI companies.

---

# 🏗️ System Architecture

```text
MongoDB Atlas
      │
      ▼
Data Ingestion
      │
      ▼
Data Validation
      │
      ▼
Data Transformation
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
AWS S3 Model Registry
      │
      ▼
Model Pusher
      │
      ▼
Prediction Pipeline
      │
      ▼
FastAPI Web Application
      │
      ▼
Docker Container
      │
      ▼
AWS EC2 Deployment
```

---

# 🚀 Key Features

### ✅ End-to-End MLOps Pipeline

Complete automation from raw data to production deployment.

### ✅ MongoDB Atlas Integration

* Cloud-hosted NoSQL database
* Dataset storage
* Data retrieval for training pipeline

### ✅ Modular Project Structure

* Config Driven Architecture
* Reusable Components
* Scalable Design

### ✅ Data Validation Framework

* Schema Validation
* Missing Column Detection
* Data Drift Checks
* Automated Validation Reports

### ✅ Feature Engineering Pipeline

* Missing Value Handling
* Data Cleaning
* Feature Transformation
* Preprocessing Automation

### ✅ Model Training Framework

* Multiple ML Algorithms
* Automated Model Selection
* Hyperparameter Optimization
* Performance Tracking

### ✅ Model Evaluation System

* Current vs Production Model Comparison
* Threshold Based Acceptance
* Model Promotion Logic

### ✅ AWS S3 Model Registry

* Version Controlled Models
* Model Storage
* Model Retrieval
* Production Ready Registry

### ✅ Prediction Pipeline

* Batch Predictions
* Real-Time Predictions
* Deployment Ready Inference

### ✅ FastAPI Web Application

* User Friendly Interface
* Training Trigger Endpoint
* Prediction Endpoint

### ✅ Dockerized Application

* Consistent Deployment
* Environment Isolation
* Portable Infrastructure

### ✅ CI/CD Automation

* GitHub Actions Workflow
* Continuous Integration
* Continuous Deployment
* Self Hosted Runner

### ✅ AWS Cloud Deployment

* EC2 Hosting
* ECR Container Registry
* IAM Security
* S3 Storage

---

# 🛠️ Technology Stack

## Programming

* Python 3.10

## Machine Learning

* Scikit-Learn
* NumPy
* Pandas

## Database

* MongoDB Atlas

## Cloud Services

* AWS EC2
* AWS ECR
* AWS S3
* AWS IAM

## Backend

* FastAPI

## DevOps

* Docker
* GitHub Actions
* Self Hosted Runner

## MLOps

* Model Registry
* Training Pipeline
* Prediction Pipeline
* Automated Deployment

---

# 📂 Project Structure

```text
Vehicle-Insurance-Project/
│
├── notebook/
│   ├── EDA.ipynb
│   ├── Feature_Engineering.ipynb
│   └── mongoDB_demo.ipynb
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_validation.py
│   │   ├── data_transformation.py
│   │   ├── model_trainer.py
│   │   ├── model_evaluation.py
│   │   └── model_pusher.py
│   │
│   ├── configuration/
│   ├── data_access/
│   ├── entity/
│   ├── aws_storage/
│   ├── pipeline/
│   ├── exception/
│   └── logger/
│
├── static/
├── templates/
├── app.py
├── requirements.txt
├── Dockerfile
├── setup.py
├── pyproject.toml
└── .github/workflows/aws.yaml
```

---

# ⚙️ Pipeline Components

## 1️⃣ Data Ingestion

Responsible for:

* Connecting to MongoDB Atlas
* Extracting data
* Converting JSON documents into DataFrames
* Storing ingestion artifacts

---

## 2️⃣ Data Validation

Ensures:

* Correct schema
* Required columns exist
* Data quality checks
* Validation reports generation

---

## 3️⃣ Data Transformation

Performs:

* Data Cleaning
* Encoding
* Scaling
* Feature Engineering

---

## 4️⃣ Model Training

Trains machine learning models and:

* Evaluates performance
* Selects best model
* Saves trained artifacts

---

## 5️⃣ Model Evaluation

Compares:

* Existing Production Model
* Newly Trained Model

Promotes model only when performance improves.

---

## 6️⃣ Model Pusher

Pushes approved models to:

```text
AWS S3 Model Registry
```

---

## 7️⃣ Prediction Pipeline

Loads latest production model and performs:

* Single Prediction
* Batch Prediction
* Real-Time Inference

---

# ☁️ AWS Infrastructure

## AWS Services Used

### IAM

* Access Management
* Security Credentials

### S3

* Model Registry
* Artifact Storage

### ECR

* Docker Image Repository

### EC2

* Production Server Hosting

---

# 🔄 CI/CD Workflow

```text
Developer Push
      │
      ▼
GitHub Repository
      │
      ▼
GitHub Actions
      │
      ▼
Build Docker Image
      │
      ▼
Push to AWS ECR
      │
      ▼
EC2 Pulls Latest Image
      │
      ▼
Deploy Updated Application
```

---

# 🐳 Docker Deployment

Build Docker Image

```bash
docker build -t vehicleproj .
```

Run Container

```bash
docker run -p 5080:5080 vehicleproj
```

---

# 📈 Production Features

✔ Automated Training Pipeline

✔ Automated Model Validation

✔ Model Registry

✔ Cloud Deployment

✔ Dockerized Infrastructure

✔ CI/CD Integration

✔ Scalable Architecture

✔ Production Ready API

✔ AWS Hosted Deployment

✔ Real-Time Predictions

---

# 🎯 Recruiter Highlights

This project demonstrates practical experience with:

* Machine Learning Engineering
* Production MLOps
* Cloud Computing
* AWS Services
* Docker
* GitHub Actions
* CI/CD Pipelines
* MongoDB
* FastAPI
* Software Engineering Best Practices
* Model Lifecycle Management
* Production Deployment

---

# 📊 Business Value

This system can be adapted for:

* Insurance Risk Prediction
* Fraud Detection
* Credit Scoring
* Customer Churn Prediction
* Healthcare Predictions
* Manufacturing Analytics

making it a reusable enterprise-grade MLOps framework.

---

# 👨‍💻 Author

**Maluk Chand**

Machine Learning | MLOps | AI Engineering | Cloud Deployment

If you found this project interesting, feel free to ⭐ the repository.
