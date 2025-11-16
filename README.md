Dealership AI — Model Training

This repository contains the machine learning code used to train the Dealership AI Car Price Prediction model. The focus of this project is on data preprocessing, feature engineering, and model training using Python and scikit-learn.

Project Overview

Train a Random Forest Regressor to predict car prices based on key features.

Handle categorical features with OneHotEncoding.

Scale numeric features for better model performance.

Save the trained model, scaler, and feature names as .pkl files for deployment.

Features Used

fueltype

carbody

drivewheel

enginesize

horsepower

Brand

These features are preprocessed, encoded, and scaled to ensure the model generalizes well.

Files in This Repo

dealership_ai_training.ipynb — Notebook for model training and preprocessing.

car_price_model.pkl — Trained Random Forest Regressor.

scaler.pkl — StandardScaler for numeric features.

feature_names.pkl — Column names after encoding.

column_transformer.pkl — ColumnTransformer used for preprocessing.

Dependencies include:

Python >=3.8

pandas

numpy

scikit-learn

joblib

How to Use

Load the dataset and features.

Preprocess categorical and numeric features.

Train the Random Forest model.

Save the model, scaler, and feature names for deployment.

This repo provides the backend training code only. For the frontend prediction app, see the[ Dealership AI Streamlit repository](https://github.com/MOKSH0077/ML-PROJECT-1-dealership-ai-)
.
