# CREDIT CARD CHURN PREDICTION
This project focuses on predicting whether a customer will leave the bank using a basic Artificial Neural Network (ANN). The model is trained on a dataset containing various customer-related features and labels indicating whether the customer has churned or not.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Requirements](#requirements)
## Introduction

Customer churn prediction is an essential task for businesses, helping them retain customers and reduce revenue loss. In this project, we use an ANN to predict customer churn based on historical data from a bank's credit card customers.

## Dataset
Dataset used->
[Churn_Modelling.csv](https://github.com/user-attachments/files/19039302/Churn_Modelling.csv)//paste the following URL and get it downloaded.

The dataset used for this project includes the following features
- Customer ID
- Surname
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target Variable)

## Model Architecture

The ANN model consists of the following layers:
1. Input Layer: Takes in customer features.
2. Hidden Layer 1: Fully connected layer with Sigmoid activation.
3. Hidden Layer 2: Fully connected layer with Sigmoid activation.
4. Output Layer: Single node with sigmoid activation to predict churn probability.

## Requirements

To run this project, you will need the following packages:
- Python 3.x
- TensorFlow 2.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
