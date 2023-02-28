
# Wallmart Analysis

## Table of Contents

- [Project Description](#project-description)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [References](#references)

## Project Description

In this project, a sales database from Walmart, an American multinational department store, was analyzed.
The goal is to demonstrate which store would be the best choice for a potential investment.

## Data

Summary of Features:

- Holiday Flag indicates whether it is a holiday or not.
- Temperature indicates the temperature value at the location.
- Fuel_price indicates the fuel price at the location.
- Unemployment indicates the unemployment rate at the location.
- Store indicates the Walmart store number.
- The Consumer Price Index (CPI) measures the evolution of prices for goods and services.
- The CPI measures the price variation from the consumer's perspective.
- It is a fundamental way to measure trends in purchasing and inflation in the United States.
To track the effects of price increases, the year 1995 was set as the base year (equal to 100).
Therefore, a price index of 33 indicates that the price was one-third of the price in 1995.

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
