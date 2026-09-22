# Customer Churn Analysis

## Project Overview

This project analyzes customer churn patterns using Python and exploratory data analysis (EDA).

The objective is to identify customer segments with higher observed churn rates, understand the factors associated with customer churn, and derive practical business insights.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Dataset

The analysis uses the `Churn_Modelling.csv` dataset containing customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card
- Active Membership
- Estimated Salary
- Customer Churn (`Exited`)

## Project Workflow

1. Data Loading
2. Data Inspection
3. Data Cleaning
4. Exploratory Data Analysis
5. Customer Segmentation
6. Churn Rate Analysis
7. Data Visualization
8. Correlation Analysis
9. Key Insights
10. Business Recommendations
11. Conclusion

## Key Findings

- Overall customer churn rate is approximately **20.37%**.
- Germany has the highest observed churn rate among the three countries at approximately **32.44%**.
- The **51–65 age group** has the highest observed churn rate at approximately **52.96%**.
- Inactive members show a higher observed churn rate than active members.
- Customers with different numbers of products show substantial differences in observed churn rates.
- Age has the strongest positive correlation with churn among the analyzed numerical variables.

## Business Recommendations

- Focus on customer engagement and retention for high-risk age groups.
- Develop strategies to re-engage inactive customers.
- Investigate the factors contributing to higher churn in Germany.
- Monitor customer segments with unusually high churn rates.
- Use customer segmentation to support targeted retention strategies.

## Project Scope

This project focuses on:

- Data Cleaning
- Exploratory Data Analysis
- Customer Segmentation
- Data Visualization
- Correlation Analysis
- Business Insights
- Business Recommendations

This project does **not** include machine-learning prediction.

## Repository Structure

```text
Customer-Churn-Analysis/
│
├── Customer_churn_Analysis.ipynb
├── Churn_Modelling.csv
└── README.md
