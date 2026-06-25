# 📊 Exploratory Data Analysis (EDA) of Retail Sales Dataset

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)

## DecodeLabs Data Analytics Internship – Project 2

### Project Overview

This project was completed as part of the **DecodeLabs Data Analytics Internship**. The objective was to perform **Exploratory Data Analysis (EDA)** on a cleaned retail sales dataset to uncover meaningful patterns, identify trends, analyze customer purchasing behavior, and generate actionable business insights to support informed decision-making.

Building upon the cleaned dataset from Project 1, this project focuses on statistical exploration, visualization, and interpretation of business data.

---

## Project Objectives

* Perform descriptive statistical analysis.
* Explore distributions of numerical variables.
* Analyze categorical variables.
* Examine product performance.
* Identify sales trends over time.
* Detect potential outliers.
* Investigate relationships among numerical variables.
* Generate business insights and strategic recommendations.

---

## Dataset Information

| Attribute    | Value                     |
| ------------ | ------------------------- |
| Dataset Type | Retail Sales Transactions |
| Records      | 1,200                     |
| Features     | 14                        |
| Format       | Microsoft Excel (.xlsx)   |

### Dataset Features

* Order ID
* Order Date
* Customer ID
* Product
* Quantity
* Unit Price
* Total Price
* Payment Method
* Order Status
* Shipping Address
* Tracking Number
* Coupon Code
* Referral Source
* Items in Cart

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* GitHub

---

## Project Workflow

1. Data Loading
2. Dataset Overview
3. Descriptive Statistics
4. Missing Value Verification
5. Univariate Analysis
6. Categorical Analysis
7. Product Sales Analysis
8. Monthly Sales Trend Analysis
9. Correlation Analysis
10. Outlier Detection
11. Business Insights
12. Recommendations
13. Conclusion


---

# Visualizations

## Distribution of Numerical columns


![Distribution of Quantity](images\histro-plot_quantity_distribution_quantity.png)

![Distribution of Itemsincart](images\histro-plot_quantity_distribution_itemsincart.png)

![Distribution of Total Price](images\histro-plot_quantity_distribution_totalprice.png)

---

## Payment Method Analysis

![Payment Method](images\orders by payment method plot.png)

---

## Order Status Distribution

![Order Status](images\order status plot.png)

---

## Referral Source Analysis

![Referral Source](images\Referral source plot.png)

---

## Product Sales Analysis

![Sales by Product](images\Total sales by products.png)

---

## Monthly Sales Trend

![Monthly Sales Trend](images\monthly sales plot.png)

---

## Correlation Matrix

![Correlation Matrix](images\correlation check plot.png)

---

# Business Insights

The exploratory data analysis produced several valuable insights into the retail sales dataset:

* Customer purchases are primarily composed of small-quantity orders, while a small number of high-value transactions contribute significantly to total revenue.
* Product performance varies considerably, with a limited number of products generating the majority of sales revenue.
* Credit Card transactions recorded the highest average order values, suggesting that customers making larger purchases tend to prefer card payments.
* Monthly sales fluctuate across the analysis period, indicating possible seasonal demand and promotional effects.
* Positive relationships were observed between Quantity, Unit Price, and Total Price, demonstrating that increases in purchase quantity generally lead to higher transaction values.
* Following the cleaning process completed in Project 1, the dataset is complete, consistent, and suitable for analytical and business intelligence applications.

---

# Business Recommendations

Based on the analysis, the following recommendations are proposed:

* Maintain adequate inventory levels for high-performing products to prevent stock shortages.
* Develop targeted marketing campaigns to improve sales of lower-performing products.
* Leverage customer payment preferences by providing incentives for electronic payment methods.
* Prepare inventory and promotional strategies ahead of anticipated peak sales periods.
* Investigate unusually large transactions to distinguish legitimate premium purchases from possible anomalies.
* Continue implementing regular data quality validation procedures to ensure accurate reporting and analysis.

---

# Conclusion

This Exploratory Data Analysis successfully transformed transactional retail data into meaningful business information.

The analysis demonstrates how descriptive statistics and visualization techniques can reveal customer purchasing behavior, sales trends, product performance, and relationships among business variables. These findings provide valuable support for inventory planning, marketing strategy, operational efficiency, and future predictive analytics.

Overall, this project demonstrates the practical application of Exploratory Data Analysis (EDA) using Python and highlights the importance of transforming raw business data into actionable insights that support data-driven decision-making.

---

# Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Descriptive Statistics
* Data Visualization
* Business Insight Generation
* Trend Analysis
* Correlation Analysis
* Outlier Detection
* Python Programming
* Pandas
* NumPy
* Matplotlib
* Git & GitHub

---

# Future Improvements

Future work may include:

* Interactive Power BI Dashboard
* Sales Forecasting using Machine Learning
* Customer Segmentation
* Customer Lifetime Value Analysis
* Market Basket Analysis
* Sales Prediction Models

---

# Author

**Isaiah Tolulope Tola**

**Aspiring Data Analyst**

**GitHub:** https://github.com/Tolaisaiah


---

# Acknowledgements

This project was completed as part of the **DecodeLabs Data Analytics Internship – Project 2 (Exploratory Data Analysis)** and demonstrates industry-standard practices for analyzing retail sales data using Python.
