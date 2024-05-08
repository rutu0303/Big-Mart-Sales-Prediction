# Big Mart Sales Prediction 

## Overview
The retail industry relies heavily on data analysis and forecasting to optimize operations and maximize profits. In this project, we aim to predict the sales of various products across different stores of BigMart using machine learning techniques. Accurate sales prediction can help BigMart optimize inventory management, devise targeted marketing strategies, and enhance overall business performance.  

## Objectives
The primary objective of this project is to build a machine learning model that can accurately predict the sales of each product in BigMart stores. Specifically, we aim to:

   - Analyze the dataset to understand the underlying patterns and relationships between different features.
   - Preprocess the data by handling missing values, encoding categorical variables, and scaling numerical features.
   - Select and train appropriate machine learning models to predict sales, considering regression techniques suitable for this task.
   - Evaluate the performance of the models using relevant metrics such as Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).

## Data Source
The dataset used in this project is from kaggle - https://www.kaggle.com/datasets/shivan118/big-mart-sales-prediction-datasets.
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined.

Variable Description
- Item_Identifier -----> Unique product ID
- Item_Weight ----> Weight of product
- Item_Fat_Content -----> Whether the product is low fat or not
- Item_Visibility ----> The % of the total display area of all products in a store allocated to the particular product
- Item_Type ----> The category to which the product belongs
- Item_MRP -----> Maximum Retail Price (list price) of the product
- Outlet_Identifier -----> Unique store ID
- Outlet_Establishment_Year -----> The year in which store store was established
- Outlet_Size -----> The size of the store in terms of ground area covered
- Outlet_Location_Type ----> The type of city in which the store is located
- Outlet_Type ----> whether the outlet is just a grocery store or some sort of supermarket

## Project Methodology
1) Data Exploration and Visualization:

    - Explore the dataset to understand the distribution of features and identify any outliers or anomalies.
2) Data Preprocessing:

    - Handle missing values by imputation techniques such as mean, median, or mode.
    - Encode categorical variables using techniques like one-hot encoding or label encoding.
    - Scale numerical features to ensure uniformity and facilitate model convergence.
3) Model Selection and Training:

    - Experiment with various regression algorithms such as Random Forest and xtreme Gradient Boosting random forest.
4) Implementation

   - Making a GUI for the project for user to input the required data for predicitng the sales.
## Conclusion
In conclusion, this project demonstrates the effectiveness of machine learning techniques in predicting sales for BigMart stores. By leveraging historical sales data and advanced regression models, we can accurately forecast future sales, enabling BigMart to make informed decisions regarding inventory management, pricing strategies, and resource allocation. The insights gained from this project can assist BigMart in optimizing its operations and enhancing overall business performance.
