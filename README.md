
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

The Pandas, Numpy, and Matplotlib libraries were used for exploratory analysis. Based on the business perspective, some features were highlighted, especially weekly sales and fuel prices by region.

## Results
Stores with sales above average were analyzed and a table was created with information on fuel prices for each store's region.

| Store | Max  | Min  | Mean     | Variation of fuel price % |
|-------|------|------|----------|------------|
| 13    | 3.845| 2.654| 3.286147 | 44.875659  |
| 4     | 3.881| 2.540| 3.216972 | 52.795276  |
| 10    | 4.468| 2.825| 3.575923 | 58.159292  |
| 28    | 4.468| 2.825| 3.606420 | 58.159292  |

***Store 4 was selected as the best investment since it has the best results regarding sales and local fuel price.***

## Usage

To run this project, you will need to have Python installed on your computer. You will also need to install the following libraries:

- pandas
- numpy
- matplotlib

You can install these libraries via pip, a package-management system used to install and manage software packages written in Python.

## References

https://www.kaggle.com/datasets/yasserh/walmart-dataset
