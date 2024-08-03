# Bank Customer Churn Prediction Model

This repository contains the code and resources for predicting customer churn in a banking dataset using various machine learning techniques. The aim is to identify customers who are likely to leave the bank, allowing the bank to take proactive measures to retain them.

## Project Overview

Customer churn is a significant issue for banks, leading to loss of revenue and increased customer acquisition costs. By predicting which customers are likely to churn, banks can implement targeted retention strategies to improve customer loyalty and reduce churn rates.

## Key Features

- **Data Preprocessing:** Steps to clean and prepare the dataset for modeling, handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
- **Sampling Techniques:** Implements Random Undersampling and Random Oversampling to address class imbalance in the dataset.
- **Model Training:** Utilizes Support Vector Machine (SVM) with radial basis function (RBF) kernel for training the model on balanced datasets.
- **Hyperparameter Tuning:** Performs hyperparameter tuning using GridSearchCV to optimize the model's parameters for better performance.
- **Model Evaluation:** Evaluates the model using confusion matrix, classification report, and other metrics to assess its performance.

## Technologies Used

- **Python:** For data preprocessing, model training, and evaluation.
- **Pandas:** For data manipulation and analysis.
- **Scikit-learn:** For implementing machine learning algorithms and evaluation metrics.
- **Imbalanced-learn:** For handling class imbalance through sampling techniques.
