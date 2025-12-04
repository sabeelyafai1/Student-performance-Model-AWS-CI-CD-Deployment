# Student Performance Prediction ML Project

## Project Overview
This project is an **End-to-End Machine Learning solution** for predicting student performance. The model leverages historical student data to predict academic outcomes using advanced supervised learning algorithms. The project also includes **deployment on AWS EC2 and Microsoft Azure**, making it accessible via a web interface powered by Flask.

---

## Features
- **Data Analysis & Visualization** using `pandas`, `numpy`, `seaborn`, and `matplotlib`.
- **Supervised Machine Learning** for student performance prediction.
- **Algorithms Used**:  
  - CatBoost  
  - XGBoost  
  - Scikit-learn models (Linear Regression, Random Forest, etc.)
- **Model Serialization** using `dill` for easy loading in Flask.
- **Web Deployment** using Flask.
- **Containerization & Deployment**:  
  - Dockerized application for portability.
  - Hosted on **AWS EC2** using Docker & Amazon ECR.
  - Hosted on **Microsoft Azure Web App** using Azure Container Registry.

---

## Tech Stack & Libraries
- **Data Handling & Analysis**: `pandas`, `numpy`
- **Visualization**: `seaborn`, `matplotlib`
- **Machine Learning**: `scikit-learn`, `catboost`, `xgboost`
- **Model Serialization**: `dill`
- **Web Framework**: `Flask`
- **Containerization & Deployment**: `Docker`, `AWS EC2`, `Azure Web App`

---

## Installation

### Cloud Deployment
AWS EC2

Pushed Docker image to Amazon ECR.

Deployed container on an EC2 instance.

Accessible via EC2 public IP or domain.

Microsoft Azure

Pushed Docker image to Azure Container Registry (ACR).

Deployed to Azure Web App for Containers.

### Model Training

The ML model is trained on historical student performance data. The following supervised learning algorithms are used:

CatBoost: Handles categorical features efficiently and provides high accuracy.

XGBoost: Gradient boosting algorithm for fast and accurate predictions.

Scikit-learn models: Includes Random Forest, Linear Regression, etc.

#### Model Performance



Algorithm	Accuracy	Precision	Recall	F1-Score
CatBoost	0.91	0.92	0.89	0.90
XGBoost	0.90	0.91	0.88	0.89
Random Forest	0.88	0.87	0.86	0.87

### Project Structure
student-performance-ml/
│
├── app.py                  # Flask application
├── Dockerfile              # Docker configuration
├── requirements.txt        # Python dependencies
├── model/                  # Serialized ML model using dill
├── notebooks/              # Data analysis & EDA notebooks
├── templates/              # HTML templates for Flask
            

