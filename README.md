# StoresSalesForecasting
The project consists of forecasting sales at the department level for 45 Walmart shops in different regions, also considering seasonal down periods such as Thanksgiving and Christmas.

## Table of Contents

- [Overview](#overview)
- [Origin](#origin)
- [Installation](#installation)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Results](#results)

## Overview

The goal of this project is to accurately predict future sales at the department level for Walmart stores. Seasonal periods like Thanksgiving and Christmas are taken into account, as these affect the sales trends.


## Origin 
The dataset and the inspiration for this project come from the Walmart Recruiting Store Sales Forecasting competition on Kaggle:
- **Walmart Competition Admin, Will Cukierski. (2014). Walmart Recruiting - Store Sales Forecasting.**  
  Kaggle. [Walmart Recruiting - Store Sales Forecasting](https://kaggle.com/competitions/walmart-recruiting-store-sales-forecasting)

## Installation

To run this notebook, ensure you have Python installed and the libraries listed in requirements.txt

You can install these libraries using the following command:

```bash
pip install -r requirements.txt
```

## Dataset
The dataset used for this project consists of historical sales data at the department level for 45 Walmart stores. It includes various features such as:
* Date
* Sales amount
* Store location
* Department information
* Promotional data
* Seasonal indicators (e.g., Thanksgiving, Christmas)

## Models Used
The following machine learning models were implemented to forecast sales:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. XGBoost Regressor
5. Deep Learning Model 

Each model is evaluated using the Mean Squared Error (MSE) metric.

## Results

The notebook provides a performance comparison of the models based on their Mean Squared Error (MSE) on the data. The goal is to select the most effective model for forecasting sales, potentially incorporating more advanced techniques in future iterations.