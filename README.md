# Loan Approval Prediction Project

## Overview

This project focuses on predicting loan approval status based on various features such as applicant's income, loan amount, credit history, etc. Several machine learning classifiers are employed to make predictions and evaluate their performance.

## Table of Contents
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)
- [Conclusion](#conclusion)
-

## Data Collection

The Kaggle dataset used in this project contains information about loan applicants, including features such as gender, marital status, income, loan amount, and credit history.

## Data Preprocessing

- **Handling Missing Values:** Null values in the dataset were addressed by filling them with appropriate values, such as mean or mode.
- **Feature Engineering:** New features like log transformations of loan amount and total income were created to improve model performance.
- **Label Encoding:** Categorical variables were encoded using LabelEncoder to convert them into numerical values.
- **Data Splitting:** The dataset was split into training and testing sets for model evaluation.

## Exploratory Data Analysis (EDA)

EDA was performed to understand the distribution of key features:

- **Marital Status:** Explored the distribution of married and unmarried applicants.
- **Dependents:** Analyzed the number of dependents for each applicant.
- **Self-Employment:** Examined the count of self-employed applicants.
- **Loan Amount:** Explored the distribution of loan amounts.
- **Credit History:** Investigated the distribution of credit history.

## Machine Learning Models Results
- Trained a Decision Tree Classifier, K-Nearest Neighbors (KNN), Naive Bayes, and Random Forest.
- **Decision Tree Classifier Accuracy**: 73.983%
  **K-Nearest Neighbors (KNN) Accuracy**: 79.674%
  **Naive Bayes Accuracy**: 82.926%
  **Random Forest Accuracy**: 77.235%

## Conclusion

This project explores the use of different machine learning algorithms to predict loan approval status. The performance of each model was evaluated, providing insights into their effectiveness for this specific task.
Feel free to explore the Jupyter Notebook (`loan_prediction.ipynb`) for a detailed walkthrough of the code and analysis.
