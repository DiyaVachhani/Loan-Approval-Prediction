# Loan Approval Prediction
## Description
The Loan Approval Prediction project is aimed at predicting whether a loan application will be approved or not based on various applicant features. By utilizing machine learning algorithms, this model predicts the loan approval status (Approved/Not Approved) based on the applicant's demographic and financial data such as income, education, credit history, etc.

This project leverages a Logistic Regression model to classify loan eligibility. The goal is to help financial institutions automatically assess loan applications and make decisions based on the provided data.

## Features:
Gender: Gender of the applicant (Male/Female).

Married: Whether the applicant is married or not (Married/Not Married).

Dependents: Number of dependents of the applicant.

Education: Educational background of the applicant (Graduate/Not Graduate).

Self_Employed: Whether the applicant is self-employed (Yes/No).

ApplicantIncome: Income of the applicant.

CoapplicantIncome: Income of the coapplicant.

LoanAmount: Amount of the loan requested.

Loan_Amount_Term: Duration of the loan (in months).

Credit_History: Credit history of the applicant (1 for good, 0 for poor).

Property_Area: Type of area the applicant resides in (Urban/Semiurban/Rural).

Loan_Status: Target variable (Loan Approved or Not Approved).

## Installation:
pandas

numpy

scikit-learn

matplotlib

seaborn

Jupyter Notebook
## Dataset:
-<a href="https://github.com/DiyaVachhani/Loan-Approval-Prediction/blob/main/loan_data.csv">Dataset</a>
## Steps Involved:
Data Loading: The dataset is loaded into a pandas DataFrame to explore and clean the data.

Data Preprocessing: Missing values are handled, and categorical variables are encoded. Numeric values are normalized or scaled if necessary.

Feature Engineering: Features are selected or transformed to improve the model's performance.

Model Training: A machine learning model (such as Logistic Regression) is trained on the training dataset.

Evaluation: The model is evaluated on the test data using metrics such as accuracy, precision, recall, and F1 score.
## Conclusion:
This project provides a simple yet effective machine learning model to predict whether a loan will be approved based on the applicant’s demographic and financial details. With improvements in data preprocessing, feature engineering, and model selection, this system could be enhanced further to handle more complex datasets and improve prediction accuracy.
