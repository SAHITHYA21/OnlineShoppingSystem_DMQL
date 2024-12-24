# Online Shopping System

This project focuses on developing a complete database system for online shopping that discharges the complexity of contemporary electronic commerce. With the ever-growing need for easy to access and effortless shopping experience, online shopping has become very popular. But, whilst online marketplaces have become dependent on vast amounts of data for user and product maintenance, and transactions and ‘data junkies’ exist within, most companies utilize a simple database that does not fulfill the volume of data. The goal of this project, therefore, is to solve the problems of online traders through the development of a safe, flexible and equally effective database management system that ensures proper performance, maximization of customer satisfaction, and achievement of business goals.

## Overview
The data used in this project was generated programmatically using the `Faker` Python module. The `Faker` module provides a robust framework for creating realistic test data based on predefined schemas, ensuring a comprehensive dataset for testing and analysis.

## Data Generation Steps
1. Users: Generated 3,500 user profiles with attributes such as usernames, passwords, email addresses, physical addresses, and phone numbers.
2. Categories: Created 200 unique product categories with descriptions.
3. Products: Developed 1,000 products with attributes such as names, descriptions, prices, stock quantities, associated users, and categories.
4. Shopping Carts: Assigned 6,964 shopping carts randomly distributed among users with timestamps for creation and updates.
5. Cart Items: Populated each shopping cart with 1-5 items, linking products to carts.
6. Orders: Generated 500-1,000 orders with attributes like order status, total amount, order date, shipping address, and payment method.
7. Order Items: Linked products to orders with quantities and prices for each order item.
8. Payments: Created payment records linked to orders with details such as payment method, status, amount, and date.
9. Reviews: Randomly assigned 1,000-2,000 reviews to products with ratings, comments, and review dates.

## Tools Used
- Faker: For generating realistic synthetic data.
- Pandas: For data manipulation and saving outputs in CSV format.
- Random Module: For introducing variability in data attributes such as quantities, prices, and date ranges.

## Final Output
The data was saved as CSV files corresponding to each table in the schema:
- `users.csv`
- `categories.csv`
- `products.csv`
- `shopping_carts.csv`
- `cart_items.csv`
- `orders.csv`
- `order_items.csv`
- `payments.csv`
- `reviews.csv`
- `payment_methods.csv`

## Integration
All individual tables were merged to create a unified dataset (`final_table.csv`) suitable for Tableau visualization and comprehensive analysis.

## Purpose
The dataset provides a realistic framework for testing database queries, building visualizations, and validating system performance under various scenarios.

## Disclaimer
The data generated is entirely synthetic and does not represent real individuals, products, or transactions.

