# Credit Card Fraud Detection

This repository contains the implementation of a credit card fraud detection system using machine learning models, namely Logistic Regression and Random Forest. The goal of this project is to develop robust models capable of accurately identifying fraudulent transactions in credit card datasets.

# Dataset:

The dataset used in this project contains transactions made by credit cards in September 2013 by European cardholders. It includes features such as transaction amount, time of transaction, etc. The dataset consists of 31 columns, out of which V1-V28 are the result of PCA dimensionality reduction to protect user identities. The 'Time' column represents the number of seconds elapsed between each transaction and the first transaction in the dataset, the 'Amount' column indicates the transaction amount, and the 'Class' column represents 1 for fraudulent transactions and 0 otherwise.

# Implementation:

The implementation is done in a Jupyter Notebook, providing a step-by-step walkthrough of the entire process from data preprocessing to model evaluation.
Two machine learning models, Logistic Regression and Random Forest, are trained and evaluated for their effectiveness in fraud detection.
Data preprocessing techniques such as data cleaning and addressing imbalanced data using random under sampling are applied.
Exploratory data analysis (EDA) is conducted to gain insights into the dataset's characteristics and identify potential fraud indicators.
Model training is performed using the preprocessed dataset, and model performance is evaluated using key metrics such as accuracy and F1-score.
The results of the analysis, including insights gained and recommendations for further optimization, are documented in the notebook.


# Instructions**:

# Clone the repository to your local machine:

git clone https://github.com/abhusal101/credit-card-fraud-detection


# Dependencies:

Python 3
Jupyter Notebook
pandas
numpy
scikit-learn
matplotlib
seaborn

# Acknowledgments:

The dataset used in this project is sourced from Kaggle: [Credit Card Fraud Detection.](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/code)

# License:

This project is licensed under the MIT License. See the LICENSE file for details.
