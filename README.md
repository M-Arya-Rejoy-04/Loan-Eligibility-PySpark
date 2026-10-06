# Loan Eligibility Prediction Using PySpark

## Project Overview

Loan Eligibility Prediction is a machine learning project designed to predict whether a loan application is likely to be approved or rejected based on applicant information.

The project uses PySpark for scalable data processing and machine learning models to analyze applicant characteristics such as income, credit history, education, employment status, and property area.

## Objective

The main objective of this project is to build a machine learning system that can:

- Predict loan approval outcomes
- Process and transform loan application data
- Identify important factors influencing loan eligibility
- Compare multiple classification algorithms
- Evaluate model performance using standard classification metrics

## Technologies Used

- Python
- PySpark
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn / Spark MLlib
- Jupyter Notebook

## Dataset

The dataset contains information related to loan applicants, including:

- Gender
- Married status
- Dependents
- Education
- Self-employment status
- Applicant income
- Co-applicant income
- Loan amount
- Loan term
- Credit history
- Property area
- Loan approval status

## Project Workflow

Data Collection
↓
Data Cleaning
↓
Exploratory Data Analysis
↓
Feature Engineering
↓
Feature Transformation
↓
Model Training
↓
Model Evaluation
↓
Model Comparison
↓
Loan Eligibility Prediction

## Data Preprocessing

The preprocessing stage includes:

- Handling missing values
- Converting categorical variables into numerical representations
- Preparing features for machine learning
- Creating derived features such as total income
- Preparing the target variable

## Feature Engineering

Some derived features include:

### Total Income

Total Income = Applicant Income + Co-applicant Income

### Income-to-Loan Ratio

Used to understand the relationship between applicant income and requested loan amount.

## Machine Learning Models

Three classification models were implemented and compared:

### 1. Random Forest

An ensemble learning method that combines multiple decision trees to make predictions.

### 2. Gradient Boosting

An ensemble technique that builds models sequentially, where each new model attempts to improve upon the errors of previous models.

### 3. Logistic Regression

A statistical classification algorithm used to estimate the probability of loan approval.

## Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Model performance is compared to identify the most suitable model for the loan eligibility prediction task.

## Business Applications

A loan eligibility prediction system can help financial institutions:

- Automate initial loan screening
- Reduce processing time
- Support consistent decision-making
- Identify important applicant characteristics
- Handle large volumes of applications

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Explainable AI using SHAP
- Deployment using Flask/FastAPI
- Interactive dashboard using Power BI/Tableau
- Real-time loan prediction API

## 👩‍💻 Author

M Arya Rejoy

MSc Data Science & Analytics
Mahatma Gandhi University
