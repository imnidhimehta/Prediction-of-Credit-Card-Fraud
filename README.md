# Project Title : 
FindDefault (Prediction of Credit Card fraud)

## Overview:
This project aims to develop a machine learning model for detecting fraudulent credit card transactions using a dataset of transactions made by European cardholders in September 2013. The dataset is highly imbalanced, with only a small percentage of transactions labeled as fraud.

## Dataset:
The dataset contains transactions made in two days, with 492 frauds out of 284,807 transactions. The positive class (frauds) accounts for 0.172% of all transactions. The dataset file is named creditcard.csv

## Resources and Dependencies:
#### Python:
Jupyter Notebook (version 6.5.4)
#### Dependencies:
pandas

numpy

seaborn

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LogisticRegression

from sklearn.metrics import accuracy_score
