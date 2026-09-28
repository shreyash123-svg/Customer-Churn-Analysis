# Customer Churn Analysis

## 1. Project Title

Customer Churn Analysis

## 2. Short Description / Purpose

A Python-based customer churn analysis project focused on understanding customer attrition, identifying churn-related patterns, and analyzing customer and subscription behavior.

The project includes data cleaning, feature engineering, exploratory data analysis, visualization, pivot table analysis, and SQL operations using Python.

## 3. Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite
- Jupyter Notebook

## 4. Data Source

The project uses customer, subscription, and support data containing information related to:

- Customer details
- Gender
- State and country
- Subscription dates
- Renewal and cancellation dates
- Plan type
- Subscription type
- Contract type
- Monthly charges
- Customer complaints
- Escalations
- Churn score

## 5. Features & Highlights

### Business Problem

Customer churn can lead to revenue loss and reduced customer retention. This project analyzes customer, subscription, and support data to understand churn patterns and identify factors associated with customer attrition.

### Key Analysis

- Overall churn rate
- Customer retention rate
- Churn rate by plan type
- Revenue and users by state
- Revenue and users by subscription type
- Average Revenue Per User (ARPU)
- Average customer tenure
- Revenue at risk from churned customers
- Escalation rate
- Average complaints per user
- Escalation vs churn correlation
- Churn risk segmentation using churn score

### Data Cleaning

- Renamed customer columns
- Removed unnecessary columns
- Converted date columns to appropriate datetime format
- Standardized gender values
- Handled missing country values
- Converted subscription and complaint dates
- Removed unnecessary support columns

### Feature Engineering

- Created Churn Flag based on cancellation status
- Created customer tenure in days
- Calculated complaint count per customer
- Created churn risk categories using churn score:
  - Low
  - Medium
  - High

### Data Visualization

- Monthly churn trend
- Churn by plan type
- Churn by state
- Correlation heatmap
- Pairplot
- Categorical analysis using Seaborn

### Additional Analysis

- Pivot table analysis by plan type
- SQL table creation using SQLite
- SQL data insertion
- SQL aggregation using GROUP BY
