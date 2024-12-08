# Cloud Kitchen Sales Analysis and Prediction
# Overview
This repository contains a comprehensive project on sales analysis and prediction for a cloud kitchen company. 
The project involves exploratory data analysis (EDA), data visualization, machine learning modeling, and hyperparameter optimization using Optuna. 
The dataset used in this project includes detailed sales records, making it an excellent resource for data-driven decision-making in the food delivery and restaurant industry.

# Dataset Information
The dataset, Sales Dataset.xlsx, contains sales data with 18 columns and several rows, detailing the following:

Restaurant Name: Name of the restaurant.
System Date: Date of the order.
Order Type: Type of the order (e.g., Dine-in, Delivery).
Sales Channel: Channel through which the order was placed (e.g., Online, Offline).
Order No: Unique identifier for each order.
Customer Name: Name of the customer.
Order Start Time: Start time of the order.
Order End Time: End time of the order.
Food ID: Unique identifier for each food item.
KSOP Recipe Name: Recipe associated with the order.
Food Name: Name of the food item.
Quantity: Number of units ordered.
Food Category: Category of the food item.
Food Type Name: Type of food (e.g., Vegetarian, Non-Vegetarian).
Net Price: Price of the food item before tax.
Tax Price: Tax applied to the order.
Total Price: Total price of the order.
Food Cost: Cost incurred for preparing the food item.

# Project Workflow
1. Exploratory Data Analysis (EDA)
Data cleaning and preprocessing.
Analysis of sales trends, popular food items, and restaurant performance.
Visualization of key insights using bar plots, histograms, and heatmaps.
2. Sales Prediction Model
Built a Random Forest Regressor to predict sales (Total Price) based on order details.
Evaluated the model using metrics like RMSE, MAE, and R-squared.
3. Hyperparameter Tuning
Used Optuna for hyperparameter optimization of the Random Forest model.
Improved model accuracy through automated optimization.
4. Deployment
Prepared the dataset and project files for sharing and reusability.

# Key Insights
Identified the top-performing restaurants based on total sales.
Analyzed customer preferences for food categories and order types.
Predicted sales with improved accuracy after hyperparameter tuning.

# Future Scope
Extend the model to include time-series forecasting using LSTM.
Develop a dashboard for real-time sales tracking and prediction.
Explore integration with business intelligence tools like Power BI.

# Contributing
Contributions are welcome! Please create a pull request with your changes or suggestions.

# License
This project is released under the MIT License.

# Author
Ansuman Choudhury
Feel free to reach out for any questions or collaboration opportunities!
