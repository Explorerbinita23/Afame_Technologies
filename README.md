# Customer Churn Prediction for a US Bank

This project aims to predict customer churn for a US bank using machine learning. It involves training a model on customer data, scaling the input features, and using a script to input customer information and predict whether they will churn.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Model and Scaler Creation](#model-and-scaler-creation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Customer churn prediction is crucial for banks to retain their customers and improve their services. This project utilizes a machine learning model to predict whether a customer will churn based on various features such as credit score, age, tenure, balance, number of products, and more.

## Dataset
The dataset used in this project contains customer information with the following columns:
- `RowNumber`: Index of the row
- `CustomerId`: Unique identifier for the customer
- `Surname`: Surname of the customer
- `CreditScore`: Credit score of the customer
- `Geography`: Geography of the customer (1=Germany, 2=Spain, 3=France)
- `Gender`: Gender of the customer (1=Male, 0=Female)
- `Age`: Age of the customer
- `Tenure`: Number of years the customer has been with the bank
- `Balance`: Balance of the customer
- `NumOfProducts`: Number of products the customer has with the bank
- `HasCrCard`: Whether the customer has a credit card (1=Yes, 0=No)
- `IsActiveMember`: Whether the customer is an active member (1=Yes, 0=No)
- `EstimatedSalary`: Estimated salary of the customer
- `Exited`: Whether the customer exited the bank (1=Yes, 0=No)

## Prerequisites
- Python 3.6+
- pandas
- scikit-learn
- joblib



