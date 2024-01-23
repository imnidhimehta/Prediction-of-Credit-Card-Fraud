# Project : Prediction of Credit Card Fraud

## Overview:
This project aims to develop a machine learning model for detecting fraudulent credit card transactions using a dataset of transactions made by European cardholders in September 2013. The dataset is highly imbalanced, with only a small percentage of transactions labeled as fraud.

## Dataset:
The dataset contains transactions made in two days, with 492 frauds out of 284,807 transactions. The positive class (frauds) accounts for 0.172% of all transactions. The dataset file is named creditcard.csv([kagle.com](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud))

## Resources and Dependencies:
#### Python: Jupyter Notebook (version 6.5.4)
#### Dependencies: pandas, numpy, seaborn,from sklearn.model_selection import train_test_split, from sklearn.linear_model import LogisticRegression, from sklearn.metrics import accuracy_score.

## Project Details:
#### Exploratory Data Analysis (EDA):
Checked for missing values in the dataset. Checked the imbalance in the class in the dataset. Descriptive Statistics done for Legit and Fraud transactions.How the fraud and the legit occurs with respect to the transaction amount and distribution of the amount for positive(frauds) and negative(legit) is shown in a graph. Distribution of time  does not affect the dataset.

#### Data Preprocessing :
As the dataset is highly unbalanced hence Under sampling has been done and sample dataset has been created containing similar distribution of legit and fraud transation. As the fraud transation is 492 hence a sample of 492 legit transation has been taken.

#### Split the data into features and targets and then further Segregated the data into training data and test data.

#### Model Training :
The machine learning model used for this project is Logistic Regression. Training data is used to train the logistic regression model and model evaluation has been performed and accuracy of training data is 0.9415501905972046.

#### Result:
Result achieved by Logistic Regression model on test dataset:

Accuracy score of Test data: 0.9390862944162437

## Conclusion:
As the data was highly imbalanced hence under sampling is used to solve the imbalance dataset. Logistic Regression model gives almost perfect accuracy in both trainning data and Test data. 
