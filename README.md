## Customer Churn Prediction Using Artificial Neural Networks

### Project Overview

Customer retention is one of the most important challenges faced by businesses, especially in the banking and financial sectors. This project leverages Artificial Neural Networks (ANN) to predict whether a customer is likely to leave (churn) or remain with the organization based on demographic, account, and behavioral information.

The model helps businesses proactively identify at-risk customers and implement retention strategies to reduce customer attrition and improve customer lifetime value.

### Problem Statement

Customer churn directly impacts business revenue and growth. Acquiring new customers is often more expensive than retaining existing ones. Therefore, accurately predicting customer churn is essential for improving customer retention and optimizing marketing efforts.

The objective of this project is to develop a deep learning model capable of predicting customer churn using historical customer data.

###Project Objectives
Analyze customer behavior and account information.
Perform data preprocessing and feature engineering.
Build and train an Artificial Neural Network (ANN).
Evaluate model performance using classification metrics.
Predict customer churn probability.
Deploy the model through a user-friendly web application.
Dataset Information

The dataset contains customer demographic, banking, and account-related information.

### Features
Credit Score
Geography
Gender
Age
Tenure
Balance
Number of Products
Has Credit Card
Is Active Member
Estimated Salary
Target Variable
Exited (0 = Customer Retained, 1 = Customer Churned)
### Technology Stack
Programming Language
Python
### Deep Learning Framework
TensorFlow
Keras
### Data Processing Libraries
Pandas
NumPy
### Visualization
Matplotlib
Seaborn
### Machine Learning Utilities
Scikit-learn
### Deployment
Streamlit
Flask
### Project Workflow
1. Data Collection
Load customer churn dataset.
Explore data structure and quality.
2. Data Preprocessing
Handle missing values.
Encode categorical variables.
Perform feature scaling.
Split data into training and testing sets.
3. Exploratory Data Analysis (EDA)
Analyze customer demographics.
Identify churn patterns.
Study feature relationships.
4. Feature Engineering
Transform categorical variables.
Create model-ready datasets.
Standardize numerical features.
5. ANN Model Development

### The Artificial Neural Network consists of:

Input Layer
Hidden Layers with ReLU Activation
Output Layer with Sigmoid Activation
Adam Optimizer
Binary Cross-Entropy Loss Function
6. Model Training
Forward Propagation
Backpropagation
Weight Optimization
Validation Monitoring
7. Model Evaluation

### Performance metrics used:

Accuracy Score
Precision Score
Recall Score
F1 Score
Confusion Matrix
ROC-AUC Score
8. Deployment

The trained model is deployed using Streamlit/Flask, allowing users to enter customer details and predict churn probability in real time.

### Results

The ANN model effectively learns customer behavior patterns and predicts churn with high accuracy. The solution enables businesses to identify customers at risk of leaving and take preventive actions to improve retention.
