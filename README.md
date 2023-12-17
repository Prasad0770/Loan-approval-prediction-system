Loan Approval Prediction Project
Overview
This project focuses on predicting loan approval status based on various features such as applicant's income, loan amount, credit history, etc. Several machine learning classifiers are employed to make predictions and evaluate their performance.

Dataset
The dataset (loan.csv) used in this project contains information about loan applicants, including features such as gender, marital status, income, loan amount, and credit history.

Data Preprocessing
Handling Missing Values: Null values in the dataset were addressed by filling them with appropriate values, such as mean or mode.
Feature Engineering: New features like log transformations of loan amount and total income were created to improve model performance.
Label Encoding: Categorical variables were encoded using LabelEncoder to convert them into numerical values.
Data Splitting: The dataset was split into training and testing sets for model evaluation.
Exploratory Data Analysis (EDA)
EDA was performed to understand the distribution of key features:

Marital Status: Explored the distribution of married and unmarried applicants.
Dependents: Analyzed the number of dependents for each applicant.
Self-Employment: Examined the count of self-employed applicants.
Loan Amount: Explored the distribution of loan amounts.
Credit History: Investigated the distribution of credit history.
