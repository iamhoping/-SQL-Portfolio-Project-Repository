# SQL Portfolio Projects
## Description
This repository contains all of my SQL, data analytics, and database projects.  
It includes portfolio projects focused on data cleaning, data exploration, reporting, and database management using SQL and PostgreSQL
# Data Cleaning - layoffs
## Description
This project focuses on cleaning and preparing a layoffs dataset using SQL.  
The workflow includes removing duplicate records, standardizing inconsistent data, handling null values, formatting dates, and optimizing the dataset for further analysis.
### File name
- layoffs.csv
- layoffs_data_cleaning.sql
## SQL Concepts Used
- Data Cleaning
- Window Functions
- ROW_NUMBER()
- Common Table Expressions (CTEs)
- Temporary / Staging Tables
- DELETE Statements
- UPDATE Statements
- ALTER TABLE
- JOIN Operations
- NULL Handling
- String Functions
- Date Formatting
- Data Standardization
 ## Data Cleaning Processes
- Created backup and staging tables
- Identified duplicate records using ROW_NUMBER()
- Removed duplicate entries
- Standardized company and country names
- Trimmed unnecessary spaces and characters
- Converted text dates into DATE format
- Replaced blank values with NULL values
- Updated missing industry values using self joins
- Removed incomplete records with missing layoff data
- Dropped unnecessary columns after cleaning
# Employee Salary Analysis
## Description
This project contains SQL queries focused on employee salary analysis.
### File name
- queries-of-parks_and_recreation.sql
- Parks_and_Create_db.sql
## SQL Concepts Used
- SELECT
- GROUP BY
- ORDER BY
- JOIN
- Subqueries
- Aggregate Functions
- cte
- temp table
- events
- trigger
- procedure
- windows function
# Restaurant Sales & Customer Behavior Analysis
## Description
This project focuses on analyzing restaurant menu and order data using SQL to uncover customer ordering behavior, spending patterns, and menu performance.
### File name
- Restaurant_Orders.zip
- Queries_Restaurant_Orders.sql
## SQL Concepts Used
- SQL Concepts Used
- SELECT statements
- Aggregate Functions (COUNT, AVG, SUM, MIN, MAX)
- GROUP BY and ORDER BY
- Filtering with WHERE and HAVING
- JOIN operations (LEFT JOIN)
- Window Functions (MAX() OVER)
- DISTINCT keyword
- Subqueries with IN
- LIMIT clause for Top-N analysis
- Data exploration and customer behavior analysis

# Walmart Sales Data Analysis
## Description
This project analyzes Walmart sales data using SQL to uncover business insights related to sales performance, customer behavior, product trends, branch performance, and revenue generation. The dataset contains transaction records including customer information, product details, sales amounts, taxes, ratings, and payment methods.

The project also includes data cleaning and feature engineering by creating new columns such as time_of_day, day_name, and month_name to enable deeper analysis.
### File name
- WalmartSalesData.csv
- walmartsales-queries
  # Purpose of the Project
The main objectives of this project are to:
Practice SQL data cleaning and data exploration techniques.
Analyze sales trends and customer purchasing behavior.
Identify top-performing products, branches, and cities.
Evaluate revenue, VAT, and customer satisfaction metrics.
Generate business insights that can support decision-making.

# SQL Concepts Used
## Data Definition Language (DDL)
- CREATE DATABASE
- CREATE TABLE
- ALTER TABLE
 ## Data Manipulation Language (DML)
- UPDATE
- Data Querying
 - SELECT
- DISTINCT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
## Aggregate Functions
- COUNT()
- SUM()
- AVG()
- ROUND()
## Date & Time Functions
- DAYNAME()
- MONTHNAME()
## Conditional Logic
- CASE WHEN
## Subqueries
- Nested SELECT statements
## Data Cleaning & Feature Engineering
- Creating new analytical columns:
-- time_of_day
-- day_name
-- month_name
