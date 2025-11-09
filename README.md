# Basic MLproject

This is an End-to-End Machine Learning Project designed to predict a student's Math Score based on their demographic information, parental background, and other exam scores (Reading and Writing).

The project implements a complete Machine Learning lifecycle, from data ingestion and cleaning to model training (including hyperparameter tuning) and deployment via a simple Flask web application.

Key Features
Predictive Model: Uses various Regression algorithms (Random Forest, Gradient Boosting, XGBoost, CatBoost, etc.) to predict the math_score.

Data Pipeline: Implements a robust pipeline for Data Ingestion, Data Transformation (handling categorical features and scaling numerical ones), and Model Training.

Hyperparameter Tuning: Uses GridSearchCV within the utils.py module to find the best parameters for each model, ensuring optimal performance.

Custom Logging & Exception Handling: Includes custom logger.py and exception.py modules for robust error tracing and system monitoring.

Web Application: Deployed using Flask to allow users to input features and get real-time math score predictions.

Run:

-python src/components/data_ingestion.py

-python app.py
