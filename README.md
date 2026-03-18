🚗 Car Price Predictor API
📄 Project Description

Developed a Machine Learning–powered REST API that predicts the selling price of used cars based on multiple vehicle attributes. The system allows users to upload a CSV dataset to dynamically train a machine learning model and generate accurate price predictions through API endpoints.

The application is built using FastAPI for high-performance backend services and integrates Scikit-learn pipelines to preprocess data, handle missing values, encode categorical features, and train a Random Forest Regression model. The trained model is serialized using Joblib and used to provide real-time price predictions through a REST endpoint.

The API supports file uploads for model training, automated data preprocessing, and performance evaluation using MAE and R² metrics. This enables a flexible workflow where models can be retrained using new datasets without changing the application code.

The project demonstrates the integration of Machine Learning models with production-ready APIs, enabling scalable deployment and easy integration with frontend applications or external systems.

🛠 Tech Stack
Backend

FastAPI

Python

Machine Learning

Scikit-learn

Random Forest Regressor

Data Processing

Pandas

NumPy

Model Pipeline

ColumnTransformer

OneHotEncoder

SimpleImputer

Scikit-learn Pipeline

Model Persistence

Joblib

API Features

REST API

File Upload Handling (CSV)

JSON Request/Response

Deployment

Render Cloud Platform

Uvicorn ASGI Server

Data Science Metrics

Mean Absolute Error (MAE)

R² Score

⭐ Key Features

CSV dataset upload for dynamic model training

Automated data preprocessing pipeline

Machine learning model training via API

Real-time car price prediction

Model performance evaluation

Production-ready REST API endpoints

Cloud deployment ready
