# 🍕 Pizza Sales SQL Analysis Project

## Project Overview
This project analyzes a pizza sales database using SQL to answer important business questions related to orders, revenue, pizza categories, customer preferences, and sales trends.

The analysis is performed using four CSV files:
- orders.csv
- order_details.csv
- pizzas.csv
- pizza_types.csv

The project demonstrates practical SQL skills commonly required for Data Analyst roles, including:
- Joins
- Aggregate Functions
- GROUP BY
- Subqueries
- Window Functions
- CTE-like nested queries
- Ranking Functions
- Revenue Analysis

## Business Problem
The pizza store wants to understand:
- How many orders were placed
- Which pizzas generate the most revenue
- Which pizza sizes and categories are most popular
- Revenue trends over time
- Top-performing pizza types in each category

## Dataset Description

### 1. orders.csv
Contains basic order information.

| Column | Description |
|---------|-------------|
| order_id | Unique ID for each order |
| order_date | Date of order |
| order_time | Time of order |

### 2. order_details.csv
Contains the details of each pizza ordered.

| Column | Description |
|---------|-------------|
| order_details_id | Unique ID for each order detail |
| order_id | Related order ID |
| pizza_id | Pizza purchased |
| quantity | Number of pizzas ordered |

### 3. pizzas.csv
Contains pizza size and price information.

| Column | Description |
|---------|-------------|
| pizza_id | Unique pizza ID |
| pizza_type_id | Pizza type reference |
| size | Pizza size (S, M, L, XL, XXL) |
| price | Price of pizza |

### 4. pizza_types.csv
Contains pizza category and ingredient information.

| Column | Description |
|---------|-------------|
| pizza_type_id | Unique pizza type ID |
| name | Pizza name |
| category | Pizza category |
| ingredients | Ingredients used |

## SQL Questions Solved

1. Retrieve total number of orders placed
2. Calculate total revenue generated
3. Find the highest-priced pizza
4. Identify the most common pizza size ordered
5. Find the top 5 most ordered pizza types
6. Find quantity ordered by pizza category
7. Analyze order distribution by hour
8. Find category-wise pizza distribution
9. Calculate average pizzas ordered per day
10. Find top 3 pizza types by revenue
11. Calculate percentage contribution of each category to revenue
12. Analyze cumulative revenue over time
13. Find top 3 pizzas by revenue within each category

## Key Insights

- Large-sized pizzas are the most frequently ordered.
- Classic category contributes the highest number of orders.
- A small number of pizza types generate most of the revenue.
- Evening hours have the highest number of orders.
- Revenue consistently increases over time with visible peak days.

## Skills Demonstrated

- SQL Joins
- Multi-table Analysis
- Aggregate Functions
- Window Functions
- Ranking with RANK()
- Revenue Calculation
- Trend Analysis
- Business Insight Extraction

## Tools Used
- MySQL
- SQL Workbench 
- GitHub
- CSV Datasets

## How to Run the Project

1. Create a database in MySQL
2. Import all CSV files into their respective tables
3. Run the queries from `pizza_sales_queries.sql`
4. Review the output and insights


