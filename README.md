🔥 Algerian Forest Fires Prediction
This project predicts forest fire occurrence in Algeria based on environmental and weather-related factors. It includes Exploratory Data Analysis (EDA), model training using Ridge, Lasso, and ElasticNet regression, model serialization (pickling), and deployment via a Flask web application.

🧾 Table of Contents
Features

Folder Structure

Installation

Usage

Project Details

Author

✅ Features
📊 EDA using pandas, matplotlib, seaborn

🧠 Model Training with Ridge, Lasso, and ElasticNet

📦 Model Pickling using joblib

🌐 Flask API to serve predictions

📈 Metrics logging (e.g., RMSE, R²)

📁 Clean folder structure

AlgerianForestFire/
│
├── static/                  # Static files (if used in Flask)
├── templates/               # HTML templates for Flask
│   └── index.html
│
├── notebook/                # Jupyter notebooks for EDA and experimentation
│   └── eda.ipynb
│
├── models/                  # Pickled models
│   └── ridge_model.pkl
│
├── app.py                   # Flask backend
├── requirements.txt         # Dependencies
├── utils.py                 # Helper functions (optional)
├── README.md                # Project documentation
└── data/
    └── Algerian_forest_fires_dataset.csv


    Project Details
Dataset: Algerian Forest Fires Dataset

Models Used:

Ridge Regression (final model)

Lasso Regression

ElasticNet Regression

Evaluation Metrics:

RMSE, MAE, R² Score

Tools:

pandas, numpy, scikit-learn, seaborn, matplotlib

flask, joblib

👤 Author
Name: Sanskar

Focus: Data Science and ML Deployment


