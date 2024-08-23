# Optimizing Target's Brazilian Operations

## Project Overview

This project focuses on analyzing Target's operations in Brazil based on an extensive dataset of 100,000 orders placed between 2016 and 2018. The dataset provides a comprehensive view of various dimensions including order status, price, payment, and freight performance, as well as customer location, product attributes, and customer reviews.

By performing detailed analyses, this project aims to uncover valuable insights into Target's business operations in Brazil. Key areas of focus include order processing efficiency, pricing strategies, payment and shipping performance, customer demographics, product characteristics, and customer satisfaction levels.

## Objectives

1. **Economic Impact Analysis**:
   - Calculate the percentage increase in order costs from 2017 to 2018.
   - Analyze total and average order prices and freight values by state.

2. **Delivery Time Analysis**:
   - Compute the number of days taken to deliver each order.
   - Determine the difference between the estimated and actual delivery dates.
   - Identify the top states with the highest and lowest average freight values, delivery times, and fastest delivery performances.

3. **Payment Analysis**:
   - Track the month-on-month number of orders placed using different payment types.
   - Analyze the number of orders based on payment installments.

## Dataset

The dataset includes the following CSV files:

- **`customers.csv`**: Customer information such as ID, unique ID, zip code, city, and state.
- **`sellers.csv`**: Seller details including ID, zip code, city, and state.
- **`order_items.csv`**: Order item details including order ID, item ID, product ID, seller ID, shipping limit date, price, and freight value.
- **`geolocation.csv`**: Geolocation data including zip code, latitude, longitude, city, and state.
- **`payments.csv`**: Payment information including order ID, sequential payment details, payment type, installments, and payment value.
- **`orders.csv`**: Order details including order ID, customer ID, order status, timestamps, and estimated delivery dates.
- **`reviews.csv`**: Customer reviews including review ID, order ID, score, comment title, message, creation timestamp, and answer timestamp.
- **`products.csv`**: Product information including ID, category name, name length, description length, photo quantity, weight, and dimensions.

