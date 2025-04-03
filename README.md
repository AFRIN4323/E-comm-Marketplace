# 🛍️ E-commerce Marketplace Analysis Project  

![Project Banner](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/E-comm%20banner.avif)

## 🔍 Project Overview  
In the fast-growing e-commerce industry, data-driven decision-making is essential for business success. This project explores Fecom Inc.'s e-commerce data using SQL to extract valuable insights into sales performance, customer behavior, order fulfillment, and payment trends.Through advanced SQL queries, this analysis provides actionable insights that can help optimize sales strategies, improve logistics, and enhance customer satisfaction.  

## 🎯 Project Objectives  
- 📊 Perform **data exploration** on database of e-commerce marketplace.  
- 🛍️ Identify **top-selling products categories, high-value customers, and profitable sellers**.  
- 🚚 Analyze **order delivery performance** and detect **late deliveries**.  
- 💰 Evaluate **revenue trends and payment methods**.  
- 🏆 Detect potential **VIP customers**.  

## 📂 Dataset Information  
The project uses multiple tables related to e-commerce transactions:  

| **Table Name**           | **Description** |  
|-------------------------|--------------------------------|  
| `Orders`               | Order details, timestamps, and status. |  
| `Order_Items`          | Products purchased in each order. |  
| `Customers`            | Customer details and geolocation. |  
| `Sellers`              | Seller information. |  
| `Order_Payments`       | Payment methods and transaction amounts. |  
| `Products`             | Product categories and attributes. |  
| `Order_Reviews`        | Customer ratings and feedback. |  

## 🔥 Insights  

### ✅ Revenue Analysis  

- Calculate **total revenue generated** from all orders.  
- Identify the **most profitable products and sellers**.  

### ✅ Customer Behavior  

- Find the **customer with the highest number of orders**.  
- Identify **VIP customers** based on total spending.   

### ✅ Order Performance & Logistics  

- Retrieve the number of **late deliveries**.   
- Find the **most commonly purchased product category**.  

### ✅ Payment & Fraud Detection  

- Calculate the **percentage contribution of each payment method** to revenue.  
- Determine most-used **payment methods**.    
 
## 🛠️ Technologies Used  
- **SQL (MySQL Workbench)** for querying and data analysis.  
- **E-commerce Marketplace Database** for Source of data.
- **GitHub** for version control and documentation.

### 🛍️E-commerce Marketplace Data Queries
This repository contains SQL queries and corresponding visualizations for analyzing the E-comm Marketplace dataset.

## Queries and Visualizations

### 1. Retrieve all customer IDs and their corresponding city and gender.

![Customer Info](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Customer_ID_city_gender.png)

### 2. Fetch the total number of unique products available in the products table.

![Unique Products](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Unique_products.png)

### 3. List all the canceled orders along with customer ID.

![Cancelled Orders](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Cancelled_orders.png)

### 4. Extract all unique payment types used.

![Unique Paymenttype](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/unique_payment_types.png)

### 5. Fetch all orders where the payment value exceeds \$100.

![Payment Value](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Payment%20value%20above%20%24100.png)

### 6. Find the top 5 most expensive product categories based on price from the products table.

![Expensive Products](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Top%205%20exp%20product%20c.png)


### 7. Calculate the total revenue generated from all orders.

![Total Revenue](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Total_revenue.png)

### 8. Retrieve the number of orders placed per payment type.

![Order Per Paymenttype](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/order_count_per_paymenttype.png)

### 9. Retrieve the total number of orders placed by each customer.

![Order by each customer](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Order_count_per_customer.png)

### 10. Find the average review score for each product

![AVG Review Score](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Average_review_score.png)

### 11. Retrieve the top 5 country with the highest number of customers.

![Top 5 country](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/top_5_country.png)

### 12. Retrive the number of orders that were delivered late based on estimated and actual delivery dates.

![Late Delivery](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Late_deliveries.png)

### 13. Identify the percentage contribution of each payment type to total revenue.

![Percentage contribution](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Percentage_contribution.png)

### 14. Find the customer who has placed the highest number of orders.

![Highest order customer](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/Customer%20with%20highest%20order.png)

### 15. Detect high value customer.

![High value customer](https://github.com/AFRIN4323/E-comm-Marketplace/blob/main/E-comm%20output/High_value_customer.png)


