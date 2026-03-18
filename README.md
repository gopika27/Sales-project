# Sales Data Analysis & Prediction

## Project Overview
This project analyzes sales data to uncover business insights and builds a machine learning model to predict future sales.

---

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Scikit-learn

---

## Dataset
The dataset contains information about:
- Orders
- Customers
- Products
- Sales values

---

## Data Cleaning
- Handled missing values in ADDRESSLINE2, STATE, TERRITORY
- Removed/handled missing POSTALCODE values
- Converted ORDERDATE to datetime format

---

## Exploratory Data Analysis (EDA)

### Key Analysis Performed:
- Sales by Country
- Sales by Product Line
- Monthly Sales Trend
- Top Customers

---

## Visualizations

### Sales by Product Line
![Sales](images/sales_by_product.png)



### Top Customers
![Customers](images/top_customer_name.png)

---

## Machine Learning Model

- Built a regression model to predict SALES
- Features used:
  - Quantity Ordered
  - Price Each
  - Product Line
  - Country
  - Deal Size

- Techniques used:
  - One-Hot Encoding
  - Train-Test Split

- Evaluation Metrics:
  - MAE (Mean Absolute Error)
  - R² Score

---

## Key Insights

- Certain product lines generate higher revenue
- Sales show seasonal trends
- A small number of customers contribute significantly to revenue

---

## Future Improvements

- Build API using Flask
- Create Dashboard using Tableau / Power BI
- Add GenAI chatbot for insights

---

## Conclusion
This project demonstrates data analysis, visualization, and machine learning skills to solve real-world business problems.
