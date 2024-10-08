Data Analysis Sales project

This project focuses on performing data analysis using SQL and Power BI, with a focus on sales transactions. The data includes customer information, transactions, and date-related details. The analysis is done to extract insights such as total revenue, customer count, and specific transactions filtered by criteria like market location, currency, and time periods.

SQL Queries
The SQL queries in this project cover the following operations:

Customer Data Retrieval: Display all customer records and count the total number of customers.
Market-Specific Transactions: Filter transactions specific to the Chennai market (market code Mark001), and identify distinct product codes sold in that market.
Currency-Specific Transactions: Retrieve transactions conducted in US dollars.
Date-Based Analysis: Analyze transactions that occurred in 2020 by joining with a date table.
Revenue Calculation: Calculate total revenue for the year 2020, further filtering by specific months and markets.
Power BI
In Power BI, a custom column norm_amount is created to standardize sales amounts across different currencies. The normalization accounts for currency differences, converting USD amounts to INR using a conversion rate of 75.
Technologies Used
SQL: For querying and analyzing data from the database.
Power BI: For creating calculated columns and further data analysis.
