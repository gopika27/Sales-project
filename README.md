Sales Data Analysis & Prediction
Project Overview

This project analyzes sales data to uncover business insights and builds a machine learning model to predict future sales. It also includes API deployment and visualization for real-world usage.

Tools & Technologies
Python
Pandas
Matplotlib
Scikit-learn
FastAPI
Tableau
Dataset

The dataset contains:

Orders
Customers
Products
Sales values
 Data Cleaning
Handled missing values in ADDRESSLINE2, STATE, TERRITORY
Treated missing values in POSTALCODE
Converted ORDERDATE to datetime format
 Exploratory Data Analysis (EDA)
Key Analysis:
Sales by Country
Sales by Product Line
Monthly Sales Trend
Top Customers
 Dashboard (Tableau)

 Sales Performance Dashboard

 Shows:

Country-wise sales
Sales trend over time
Top customers




 Machine Learning Model

Built a regression model to predict SALES

Features Used:
Quantity Ordered
Price Each
Product Line
Country
Deal Size
Techniques:
One-Hot Encoding
Train-Test Split
Evaluation:
MAE (Mean Absolute Error)
R² Score
 API Deployment

Built a REST API using FastAPI

Endpoint:
POST /predict
Input:
{
  "QUANTITYORDERED": 30,
  "PRICEEACH": 100,
  "PRODUCTLINE": "Classic Cars",
  "COUNTRY": "USA",
  "DEALSIZE": "Medium"
}
Output:
{
  "Predicted Sales": 3000
}
 Key Insights
Certain product lines generate higher revenue
Sales show seasonal trends
A small number of customers contribute significantly to revenue
 Future Improvements
Enhance model accuracy
Deploy API on cloud
Improve chatbot using advanced AI models
