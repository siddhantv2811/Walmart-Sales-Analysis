# Walmart Sales Data Analysis: Data-Driven Business Insights

## Tools Used
**SQL (PostgreSQL), Python**

## 1. Project Overview
Retail businesses operate in a highly competitive landscape where understanding customer preferences, sales trends, and operational efficiency is critical to success. This project provides a **data-driven approach** to analyzing Walmart’s sales data using **SQL and Python**, enabling the identification of key business patterns and opportunities for optimization.

### Key Highlights:
- **Comprehensive Data Analysis:** Evaluating transaction patterns, payment trends, and customer feedback.
- **Advanced SQL Queries:** Extracting insights related to revenue, sales trends, and customer behavior.
- **Optimized Data Handling:** Structured storage in **PostgreSQL** for scalability.
- **Business-Oriented Problem Solving:** Addressing key operational and sales-related questions.
- **Future-Ready Framework:** Scalable to integrate **real-time data ingestion** and **dashboard visualizations**.

## 2. Project Objectives
### Business Objectives
- **Sales & Revenue Optimization:** Identifying top-performing product categories and peak sales periods.
- **Customer Insights & Behavior Analysis:** Understanding payment trends and customer satisfaction.
- **Operational Efficiency:** Optimizing staffing and inventory based on sales trends.
- **Technical & Data Processing Goals:** Implementing SQL for structured business intelligence reporting.

## 3. Dataset Description
### 3.1 Data Overview
- **Total Records:** 10,051 transactions  
- **Storage Format:** CSV file  
- **Database Integration:** PostgreSQL  

### 3.2 Key Attributes
```bash
invoice_id      Unique transaction identifier
Branch          Store branch code (e.g., WALM003, WALM048)
City           Location of the store branch
category       Product category (e.g., Health & Beauty, Electronics)
unit_price     Price per unit (converted from currency format)
quantity       Number of units purchased per transaction
date           Date of transaction (MM/DD/YY format)
time           Time of transaction (HH:MM:SS format)
payment_method Payment type used (E-wallet, Credit Card, Cash)
rating         Customer satisfaction rating (1-10 scale)
profit_margin  Profitability ratio per transaction
```

### 3.3 Data Cleaning & Preparation
- Converted `date` and `time` to proper formats
- Removed currency symbols from `unit_price`
- Filled missing values in `quantity` and `unit_price`
- Created `Total Revenue` = `unit_price` * `quantity`
- Categorized transactions into Morning, Afternoon, and Evening shifts

### 3.4 Why This Matters for Walmart
- **Enhance revenue forecasting** for better financial planning.
- **Identify store-specific trends** to optimize sales strategies.
- **Improve customer experience** by analyzing buying patterns.
- **Optimize operations** by aligning with peak sales hours.
