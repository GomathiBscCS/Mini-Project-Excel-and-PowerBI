# E-Commerce Customer Behaviour & Sales Analysis
## 1. Project Overview
This Project focuses on analysing e-commerce customer behaviour and sales performance using Excel and Power BI.
The main objective of this project is to understand customer purchasing behaviour, sales performance, customer types, product categories, cities, age groups, and sales trends.
Excel was used for data cleaning, pre-processing, transformation, and analysis. Power BI was used for data modelling, DAX calculations, interactive visualizations, and dashboard creation.
The final dashboard provides an interactive view of the sales and customer behaviour data to support better business decision-making.
## 2. Project Objective
The main objective of this project are:
- To analyse e-commerce sales performance.
- To understand customer purchasing behaviour.
- To compare new and returning customers.
- To analyse sales across product categories and cities.
- To analyse sales trends over time.
- To compare purchasing behaviour across different age groups.
- To identify useful patterns that can support data-driven business decisions.
## 3.Problem Statement
To analyse e-commerce customer behaviour and sales data to understand purchasing patterns, sales performance, customer types, product categories, cities, and age group. The analysis aims to identify useful trends and patterns that can support better business decision-making.
## 4. Dataset Description
The dataset contains e-commerce transaction and customer behaviour information. It includes details about customers, products, sales, discounts, payment methods, devices, delivery, and customer ratings.
### Dataset Details
- **Number of records:** 699
- **Original number of columns:** 18
- **Columns after transformation and calculated fields:** 24
- **Time Period:** 2023-2024
- **Product categories:** Beauty, Books, Electronics, Fashion, Food, Home & Garden, Sports, Toys
- **Gender:** Male, Female, Other
- **Payment methods:** Bank Transfer, Cash on Delivery, Credit Card, Debit Card, Digital Wallet
- **Device types:** Desktop, Mobile, Tablet
- **Customer types:** New Customer, Returning Customer
The dataset was used to analyse sales performance and customer purchasing behaviour using Excel and Power BI.
## 5. Excel Data Pre-Processing 
Excel was used as the first step to clean, check, and prepare the dataset for further analysis.
The following pre-processing steps were performed:
- Checked the dataset for blank or null values.
- Checked for duplicate records.
- Checked and corrected data types where required.
- Standardized the date format from MM/DD/YYYY to DD/MM/YYYY.
- Checked categorical values such as product category, Gender, City, Payment method, and device type.
- Used filtering and sorting to validate the data without deleting or modifying valid records.
- Created calculated columns to support further analysis.
- Checked the calculation values by comparing them with the original data.
### Calculated Columns
- **Gross Sales:** Calculated using quantity multiplied by unit price to identify the original sales value before discount.
- **Discount Percentage:** Created to understand the discount given relative to the original sales value and analyse the impact of discounts.
- **Age Group:** Created to compare purchasing behaviour across different age groups.
- **Customer Type:** Created from the returning-customer information to make it easier to identify new and returning customers.
- **Delivery Speed Category:** Created to analyse whether delivery speed is associated with customer rating and other customer behaviour.
- ## 6. Power Query & Data Transformation
Power Query in Power BI was used to transform and prepare the data for data modelling and analysis.
The Main transformation steps included:
- Loaded the cleaned Excel dataset into Power BI.
- Reviewed the data types and column values.
- Created separate tables from the main transaction data using Power Query.
- Created a Sales Transaction fact table containing transaction-level information.
- Created a Customer Details dimension table containing customer-related information.
- Created a Date Details dimension table for time-based analysis.
- Checked Customer IDs to ensure that they were unique in the Customer Details table.
- Removed unnecessary columns where required .
- Renamed tables and columns to make the data model easier to understand.
- Prepared the tables for creating relationships in the Power BI data model.
## 7. Data Model & Relationships
A structured data model was created in Power BI to organize the transaction, customer, and date information.
The model contains:
- **Sales Transaction** - Fact table containing transaction-level sales information.
- **Customer Details** - Dimension table containing customer-related information.
- **Date Details** - Dimension table containing date-related information for time-based analysis.
### Relationships
- Customer ID was used to connect **Customer Details** with **Sales Transaction**.
- Date was used to connect **Date Details** with **Sales Transaction**.
- Customer IDs were checked to ensure that they were unique in the Customer Details table.
- The relationships were reviewed to ensure that the tables could work together correctly for filtering and analysis.
The date table includes fields such as Year, Month Name, Month Number, and Quarter to support time-based analysis.
## 8. DAX Measures
DAX measures were created in Power BI 
