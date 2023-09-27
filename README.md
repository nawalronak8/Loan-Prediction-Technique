# Loan-Prediction-Technique
This project is a machine learning model that predicts whether a loan application will be approved or rejected using logistic regression. The model is trained on a dataset containing information about previous loan applicants such as their income, credit history, loan amount, loan term, and other relevant factors.

# Dataset
The dataset used in this project is the Loan Prediction Dataset from Kaggle. It contains 614 observations and 13 variables. The variables include:

Loan_ID: Unique Loan ID

Gender: Male/Female

Married: Applicant married (Y/N)

Dependents: Number of dependents

Education: Applicant Education (Graduate/Under Graduate)

Self_Employed: Self employed (Y/N)

ApplicantIncome: Applicant income

CoapplicantIncome: Coapplicant income

LoanAmount: Loan amount in thousands

Loan_Amount_Term: Term of loan in months

Credit_History: credit history meets guidelines

Property_Area: Urban/Semi-Urban/Rural

Loan_Status: Loan approved (Y/N)

# Model
We will be using logistic regression to predict the Loan_Status based on the other variables in the dataset. Logistic regression is a classification algorithm that works by fitting a logistic curve to the data, which allows us to estimate the probability of a loan being approved based on the input variables.

# Steps
Data Cleaning and Preprocessing: We will clean and preprocess the data to make it suitable for modeling. This includes dealing with missing values, encoding categorical variables, and scaling numerical variables.

Exploratory Data Analysis: We will explore the data to gain insights into the relationships between the input variables and the target variable.

Feature Selection: We will select the most important features to include in the model based on their correlation with the target variable.

Model Building: We will train the logistic regression model on the cleaned and preprocessed data.

Model Evaluation: We will evaluate the performance of the model using various metrics such as accuracy, precision, recall, and F1-score.

# Dependencies
Python

scikit-learn

pandas

numpy

matplotlib

seaborn
