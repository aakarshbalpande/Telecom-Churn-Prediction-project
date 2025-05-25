# Telecom-Churn-Prediction-project
Overview

This code provides a complete workflow for analyzing customer churn data, from data acquisition and preprocessing to training and evaluating a machine learning model.

Here's a step-by-step overview:

Import Libraries: Essential libraries for data manipulation (pandas, numpy), visualization (matplotlib.pyplot, seaborn), machine learning (sklearn), and data downloading (kagglehub, os) are imported.

Download and Load Data: The Telco Customer Churn dataset is downloaded directly from Kaggle using kagglehub and loaded into a pandas DataFrame.

Data Preprocessing: Missing values in the dataset are handled using forward fill, and categorical features are converted into a numerical format suitable for machine learning using one-hot encoding.

Explore Churn Distribution: A bar plot is generated to visualize the proportion of customers who churned versus those who did not, providing an initial understanding of the target variable distribution.

Split Data: The dataset is divided into features (input variables) and the target variable (churn status). Then, the data is split into training and testing sets to train and evaluate the model on unseen data.

Train Model: A Random Forest Classifier, a powerful ensemble learning method, is initialized and trained on the training data.

Evaluate Model: The trained model is used to make predictions on the test data. The performance of the model is then evaluated using a classification report (showing metrics like precision, recall, and F1-score) and a confusion matrix (visualizing the breakdown of correct and incorrect predictions).
