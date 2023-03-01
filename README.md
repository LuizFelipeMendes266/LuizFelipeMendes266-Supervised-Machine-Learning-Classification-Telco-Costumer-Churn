
# Supervised Machine Learning Classification : Telco Costumer Churn

## Table of Contents

- [Project Description](#project-description)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [References](#references)

## Project Description

Each row represents a customer, and each column contains a customer's attributes. Therefore, the project is about predicting customer churn for a customer base.

## Data

Summary of Features:

| Field            | Description                                                                                  |
|------------------|----------------------------------------------------------------------------------------------|
| customerID       | Unique identifier of the customer                                                            |
| gender           | Whether the customer is a male or a female                                                   |
| SeniorCitizen    | Whether the customer is a senior citizen or not (1, 0)                                        |
| Partner          | Whether the customer has a partner or not (Yes, No)                                           |
| Dependents       | Whether the customer has dependents or not (Yes, No)                                          |
| tenure           | Number of months the customer has stayed with the company                                     |
| PhoneService     | Whether the customer has a phone service or not (Yes, No)                                     |
| MultipleLines    | Whether the customer has multiple lines or not (Yes, No, No phone service)                     |
| InternetService  | Customer’s internet service provider (DSL, Fiber optic, No)                                   |
| OnlineSecurity   | Whether the customer has online security or not (Yes, No, No internet service)                |
| OnlineBackup     | Whether the customer has online backup or not (Yes, No, No internet service)                  |
| DeviceProtection | Whether the customer has device protection or not (Yes, No, No internet service)              |
| TechSupport      | Whether the customer has tech support or not (Yes, No, No internet service)                   |
| StreamingTV      | Whether the customer has streaming TV or not (Yes, No, No internet service)                   |
| StreamingMovies  | Whether the customer has streaming movies or not (Yes, No, No internet service)               |
| Contract         | The contract term of the customer (Month-to-month, One year, Two year)                         |
| PaperlessBilling | Whether the customer has paperless billing or not (Yes, No)                                   |
| PaymentMethod    | The customer’s payment method (Electronic check, Mailed check, Bank transfer, Credit card)    |
| MonthlyCharges   | The amount charged to the customer monthly                                                   |
| TotalCharges     | The total amount charged to the customer                                                      |
| Churn            | Whether the customer churned or not (Yes or No)                                               |


## Methodology

Pandas, Numpy, and Sklearn were the libraries used. The exploratory and descriptive analysis was all produced by the pandas_profile library, and considerations for the features are in the notebook itself. Regarding classifiers, the data was tested on SVM, Logistic Regression, and Random Forest. To evaluate the classifier's performance, the main metrics such as Recall, F1 Score, Accuracy, and ROC AUC curve were used.
I chose to use the BayerSearchCV to optimize the hyperparameters.

## Results



***Store 4 was selected as the best investment since it has the best results regarding sales and local fuel price.***

## Usage

To run this project, you will need to have Python installed on your computer. You will also need to install the following libraries:

- pandas
- numpy
- matplotlib

You can install these libraries via pip, a package-management system used to install and manage software packages written in Python.

## References

https://www.kaggle.com/datasets/yasserh/walmart-dataset
