Student Performance Prediction
Project Overview
This project aims to predict students' final grades based on demographic and academic features using machine learning. We use a Random Forest regression model to estimate student success and interpret the results with SHAP values for feature importance and explainability.

Dataset
The dataset used is the Student Performance Data Set from the UCI Machine Learning Repository, containing various attributes related to students’ school performance.

Features
Demographic features (e.g., age, sex, address, family size)

Academic-related features (e.g., study time, failures, school support)

Behavioral features (e.g., free time, going out, alcohol consumption)

Target variable: Final grade (G3)

Getting Started
Requirements
Python 3.x

pandas

numpy

scikit-learn

shap

matplotlib

Installation
pip install pandas numpy scikit-learn shap matplotlib
Running the Project
Download the dataset (student-mat.csv) and place it in the project folder.

Run the main script:
python student_performance_prediction.py
The script will perform data preprocessing, model training, evaluation, and display SHAP plots explaining the model predictions.

Results
The model predicts the final grades with a test RMSE of approximately 14.85

SHAP plots visualize the impact of different features on the prediction, highlighting which factors most influence student performance.

Acknowledgments
Dataset from UCI Machine Learning Repository

SHAP library for model interpretability

