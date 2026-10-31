# Mini-Project-Retail-Sales-Customer-Behaviour-Analytics
# Retail Sales & Customer Behaviour Analytics

## 1. Project Overview

Retail Sales & Customer Behaviour Analytics is a data analysis project developed using Microsoft Excel and Power BI to explore retail sales performance and customer purchasing behaviour.

The project uses a Myanmar supermarket sales dataset containing 1,000 transactions across three branches. The analysis focuses on overall sales performance, product category analysis, branch comparisons, customer segmentation and payment preferences.

The objective is to transform raw transactional data into meaningful business insights through data cleaning, data preparation, analytical calculations and interactive visualisation.

## 2. Dataset Description

**Dataset:** Myanmar Supermarket Sales Dataset  
**Source:** [Hugging Face – SalesData](https://huggingface.co/datasets/AbhayBhan/SalesData/blob/main/s1.csv)  
**Dataset Format:** CSV  
**Number of Records:** 1,000 transactions

The dataset contains retail transaction information from three branches located in:

- Yangon
- Mandalay
- Naypyitaw

### Key Dataset Columns

| Column | Description |
|---|---|
| Invoice ID | Unique transaction identifier |
| Branch | Branch identification (A, B, C) |
| City | City where the transaction occurred |
| Customer Type | Member or Normal |
| Gender | Customer gender |
| Product Line | Product category |
| Unit Price | Price per unit |
| Quantity | Number of units purchased |
| Tax 5% | Tax amount |
| Total | Transaction amount including tax |
| Date | Transaction date |
| Time | Transaction time |
| Payment | Payment method |
| Gross Income | Recorded gross income |
| Rating | Customer rating |

## 3. Tools & Technologies

- **Microsoft Excel:** Data cleaning, preprocessing and initial data validation.
- **Power Query:** Data loading and preparation in Power BI.
- **Microsoft Power BI Desktop:** Dashboard development and data visualisation.
- **DAX (Data Analysis Expressions):** Creating measures and performing analytical calculations.

## 4. Data Cleaning & Preparation

The raw CSV dataset was initially cleaned and prepared using Microsoft Excel before being imported into Power BI.

### Data Cleaning in Excel

The data preparation process included:

- Inspecting the dataset structure and columns.
- Checking for missing and duplicate values.
- Reviewing column names and data consistency.
- Verifying numerical and categorical fields.
- Checking date, time and numerical data formats.
- Preparing the dataset for analysis and visualisation.

### Data Preparation in Power BI

After the initial cleaning process, the dataset was imported into Power BI.

The following activities were performed:

- Verifying column data types.
- Preparing fields for analysis.
- Creating DAX measures for key performance indicators.
- Organising data for different analytical views.
- Developing interactive charts, tables and KPI cards.

## 5. Dashboard Development

The project consists of three interactive dashboard pages.

### Page 1: Retail Sales Performance Dashboard

This page provides an overview of the supermarket's overall sales performance.

**Key Performance Indicators:**

| KPI | Value |
|---|---:|
| Total Sales (Including Tax) | 322.97K |
| Total Revenue (Before Tax) | 307.59K |
| Total Gross Income | 15.38K |
| Total Tax Collected | 15.38K |
| Total Transactions | 1,000 |

**Visualisations:**

- Monthly Sales Trend (Including Tax)
- Sales Distribution by City and Branch
- Product Line Performance Table
- Product Line Ranking
- Average Customer Rating by Product Line
- Payment Method Distribution
- Total Sales by Branch

### Page 2: Product & Branch Analysis

This page focuses on product-level performance and branch comparisons.

**Key Performance Indicators:**

- Total Quantity
- Total Unit Price

**Visualisations:**

- Quantity by Branch and Product Line
- Average Unit Price by Product Line
- Branch Filter
- Monthly Filter

This page allows users to explore product quantities across branches and compare average unit prices across different product categories.

### Page 3: Customer & Payment Analysis

This page examines customer segmentation and payment preferences.

**Visualisations:**

- Total Revenue by Customer Type and Gender
- Payment Method Distribution
- Quantity by Branch and Customer Type

The analysis provides insights into purchasing patterns between Member and Normal customers, revenue distribution by gender and payment preferences.

## 6. Key Findings

Based on the current dashboard analysis, the following observations were identified:

- Food and beverages recorded the highest product-line sales at approximately 56.14K.
- Sports and travel ranked second, with approximately 55.12K in sales.
- Health and beauty recorded the lowest product-line sales at approximately 49.19K.
- Yangon contributed approximately 34.24% of total sales.
- Mandalay and Naypyitaw each contributed approximately 32.88% of total sales.
- The average customer rating across product lines was approximately 6.97.
- Cash, Ewallet and Credit Card are the payment methods represented in the dataset.

## 7. Business Questions Addressed

The dashboard is designed to explore the following business questions:

1. How are sales performing over time?
2. Which city and branch contribute the most to total sales?
3. Which product categories generate the highest sales?
4. How do product quantities vary across branches?
5. Which product categories have higher average unit prices?
6. How does revenue differ between Member and Normal customers?
7. How is revenue distributed by gender?
8. Which payment methods are used by customers?
9. How do customer purchasing patterns differ across branches?

## 8. Important Dataset Note

The source dataset contains a column named `COGS`,Cost of Goods Sold, but its values correspond to `Unit Price × Quantity`. Therefore, it behaves like pre-tax sales rather than conventional cost of goods sold.

For this project, revenue before tax is calculated using:

`Unit Price × Quantity`

The `Gross Income` field is treated as recorded gross income from the source dataset and is not presented as independently verified business profit.

## 9. Conclusion

The Retail Sales & Customer Behaviour Analytics project demonstrates the practical application of Microsoft Excel and Power BI in retail data analysis.

By combining data cleaning, data preparation, DAX calculations and interactive visualisations, the project transforms raw transaction records into meaningful business insights.

The three dashboard pages provide an overview of sales performance, product and branch comparisons, and customer purchasing behaviour.

This project demonstrates practical skills in data preprocessing, analytical thinking, business intelligence, data visualisation and dashboard development.

---

### Project Information

| Category | Details |
|---|---|
| Project Name | Retail Sales & Customer Behaviour Analytics |
| Project Type | Data Analytics Mini Project |
| Domain | Retail / Sales Analytics |
| Dataset | Myanmar Supermarket Sales |
| Records | 1,000 |
| Data Cleaning | Microsoft Excel |
| Visualisation | Power BI |
| Calculations | DAX |
| Dashboard Pages | 3 |
