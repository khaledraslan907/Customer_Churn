# Customer Churn Prediction using Machine Learning
This project aims to predict customer churn using machine learning models, specifically logistic regression. The application allows users to input customer details via a Streamlit-based web interface and receive a prediction indicating whether a customer is likely to churn or not. The project utilizes data transformation techniques and a pre-trained logistic regression model to make predictions.
# Project Overview
Customer churn is a critical issue for businesses, particularly those with subscription-based services. This project helps businesses predict customer churn by analyzing customer behaviors and service details. The project is built using Python, and key features include data preprocessing with a ColumnTransformer, logistic regression for prediction, and a Streamlit interface for user interaction.
# Features
Customer Input Interface: A simple web form created using Streamlit, where users can input customer data such as contract type, online security, tenure, and monthly charges.
Machine Learning Pipeline: The project uses a logistic regression model with a transformation pipeline (including one-hot encoding and feature scaling).
Churn Prediction: Based on the input data, the model predicts whether a customer is likely to churn or not.
Deployable Web App: The app can be deployed using Streamlit for real-time predictions.
# Tools and Libraries
Python: Core programming language for the project.
Streamlit: For creating an interactive web-based user interface.
Pandas: For data manipulation and analysis.
Scikit-learn: For data transformation and machine learning model training.
Pickle: For loading pre-trained models and transformers.
