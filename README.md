# CMPG-323-Project-5-29909538
# Eco Power Logistics Power BI Report README

## Overview

Welcome to the Eco Power Logistics Power BI report. This document will help you get started and navigate through the report to explore our logistics and eco-friendly power data.

## Table of Contents

- [Getting Started](#getting-started)
- [Report Structure](#report-structure)
- [Data Sources](#data-sources)
- [Filters and Interactions](#filters-and-interactions)
- [How to Use](#how-to-use)

## Getting Started

To access the Eco Power Logistics Power BI report, simply click on the following link: [Eco Power Logistics Power BI Report](https://app.powerbi.com/links/J-Sk3DF8CD?ctid=b14d86f1-83ba-4b13-a702-b5c0231b9337&pbi_source=linkShare)

## Report Structure

Our report is organized into four distinct pages, each designed to provide specific insights:

- **High-Level Metrics**: This page offers an overview of key performance metrics.
- **Order Monitoring**: Explore and monitor our order-related data.
- **Product Monitoring**: Dive into product-specific metrics and insights.
- **Customer Monitoring**: Get insights into our customer-related data.

## Data Sources

Our report relies on an Excel file that contains three sheets, providing essential data for Eco Power Logistics:

- **Orders**: This sheet contains information about orders placed, including OrderID, OrderDate, CustomerID, and DeliveryAddress.

- **Products**: The "Products" sheet provides details about the available products, including ProductID, ProductName, Category, and UnitsInStock.

- **OrderDetails**: This sheet contains data about the details of each order, including OrderDetailsID, OrderID, ProductID, Quantity, and Discount.

- **Customers**: The "Customers" sheet includes customer information, including CustomerID, CustomerName, and CustomerTitle (e.g., Mr., Mrs., Dr.).

These data sources are used to create the visuals and insights presented in the Eco Power Logistics Power BI report.

If you have any questions or need more details about our data sources, please feel free to reach out to us at [insert contact information].

## Filters and Interactions

You can interact with the report to explore the data in more depth. Here are the common filters available on all pages:
- **Category**: Filter data by product category.
- **Customer Title**: Filter data by customer title or honorific.
- **Customer Name**: Filter data by customer name and surname.
- **Order ID**: Search for specific orders by Order ID.
- **Product Name**: Filter data by product name.

## How to Use

### High-Level Metrics Page

**Page Introduction**:
   - When you first open the report, you'll land on the "High-Level Metrics" page. This page provides a snapshot of key performance metrics. Here's how to use it:

  
![Highl-level screenshot](https://github.com/DzunisaniBabane/CMPG-323-Project-5-29909538/assets/112667924/5f0cb95a-2361-4b02-8a2c-a1af799e77c8)

   - The "High-Level Metrics" page includes the following key visuals:

   - **Total Orders**:
     - The card visual labeled "Total Orders" displays the total number of orders in our system. This represents the count of distinct OrderIDs.

   - **Total Customers**:
     - The card visual labeled "Total Customers" shows the total number of unique customers in our database. It counts the distinct CustomerIDs.

   - **Average Discount**:
     - The card visual labeled "Average Discount" displays the average discount applied to orders. It provides insights into our discount strategies.

   - **Total Quantity Ordered**:
     - The card visual labeled "Total Quantity Ordered" shows the sum of quantities ordered, giving an overview of product demand.

   - **Number of Products Available**:
     - The card visual labeled "Number of Products Available" provides the count of unique products in our system.

   - **Units of Stock**:
     - The card visual labeled "Units of Stock" displays an overview of the total stock available in our inventory.

   - **Product Categories** (Pie Chart):
     - The pie chart visual labeled "Product Categories" shows the distribution of products by category. Click on slices to filter by category.

   - **Best Selling Products by Quantity Ordered** (Stacked Bar Chart):
     - The stacked bar chart visual illustrates the best-selling products by the quantity ordered. Hover over bars for more details.

   - **Number of Orders Over Time** (Line Chart):
     - The line chart visual labeled "Number of Orders Over Time" displays when orders were placed and the associated discounts over time. Use this to track trends.

   - **Customer Titles** (Donut Chart):
     - The donut chart visual shows the distribution of customer titles or honorifics. Explore the different titles in our customer base.

   - **Product Categories with Most Orders** (Clustered Column Chart):
     - The clustered column chart visual highlights which product categories have the most orders. It's a valuable insight for business decisions.

Feel free to interact with these visuals, use filters, and explore the "High-Level Metrics" page to gain insights into our eco-friendly logistics operations.

### Order Monitoring Page

**Page Introduction**:
   - Navigate to the "Order Monitoring" page to gain insights into our order-related data. Here's how to use it:

  ![Order Monitoring screenshot](https://github.com/DzunisaniBabane/CMPG-323-Project-5-29909538/assets/112667924/e2630ec3-6d20-40d7-8ca2-0152d3f29ae1)

   - The "Order Monitoring" page includes the following key visuals:

   - **Number of Products with At Least One Order**:
     - The card visual displays the count of products that have at least one order associated with them.

   - **Number of Orders**:
     - The card visual labeled "Number of Orders" shows the total number of orders in our system.

   - **Products in Inventory vs. Ordered** (KPI):
     - The KPI visual provides insights into the quantity of products in inventory and how many have been ordered. It's a valuable metric for managing stock.

   - **Number of Orders by Customers** (Stacked Bar Chart):
     - The stacked bar chart visual illustrates the number of orders each customer has placed. It helps identify our top customers.

   - **Orders Over Time by Month** (Line Chart):
     - The line chart visual labeled "Orders Over Time by Month" shows the distribution of orders over time. It's a useful tool for tracking trends.

   - **Average Discount by Month** (Stacked Bar Chart):
     - The stacked bar chart visual displays the average discount applied to orders each month. It's essential for analyzing discount trends.

   - **Number of Orders by Product** (Stacked Bar Chart):
     - The stacked bar chart visual reveals how many orders each product has received. It's valuable for product-specific insights.

![Products monitoring screenshot](https://github.com/DzunisaniBabane/CMPG-323-Project-5-29909538/assets/112667924/a6171ddd-9c2c-4220-a2d1-46ed6947a05a)


   - The "Product Monitoring" page includes the following key visuals:

   - **Products Available**:
     - The card visual displays the count of products available in our inventory.

   - **Product Categories**:
     - The card visual labeled "Product Categories" shows the total number of product categories in our system.

   - **Units of Stock**:
     - The card visual labeled "Units of Stock" provides an overview of the total stock available for all products.

   - **Total Units Ordered**:
     - The card visual labeled "Total Units Ordered" shows the sum of units ordered, providing insights into product demand.

   - **Quantity of Products Ordered by Category** (Clustered Column Chart):
     - The clustered column chart visual shows the quantity of products ordered for each product category. It's a valuable insight into category-specific demand.

   - **Units in Stock by Category** (Stacked Bar Chart):
     - The stacked bar chart visual illustrates the units in stock for each product category. Use this to monitor stock levels by category.

   - **Product Categories** (Pie Chart):
     - The pie chart visual displays the distribution of product categories. Click on slices to filter by category.

   - **Quantity Ordered by Product** (Stacked Bar Chart):
     - The stacked bar chart visual shows the quantity of each product that has been ordered. It provides insights into product-specific demand.

- Explore the "Customer Monitoring" page to gain insights into our customer-related data. Here's how to use it:

![Customer Monitoring screenshot](https://github.com/DzunisaniBabane/CMPG-323-Project-5-29909538/assets/112667924/17f7620c-15be-4b24-82c1-f8feaf6e2159)


   - The "Customer Monitoring" page includes the following key visuals:

   - **Number of Customers**:
     - The card visual displays the total number of unique customers in our database.

   - **List of Customers** (Table):
     - The table visual presents a list of our customers, providing detailed information about each customer.

   - **Customers with At Least One Order** (Gauge):
     - The gauge visual shows the percentage of customers who have placed at least one order. It's a crucial metric for customer engagement.

   - **Customer Titles Analysis** (Pie Chart):
     - The pie chart visual provides an analysis of customer titles or honorifics. Explore the distribution of customer titles in our database.
Feel free to interact with these visuals, use filters, and explore the "Order Monitoring" page to monitor and analyze our order data.

If you have any questions, feedback, or need support while using the report, please feel free to reach out to us at [insert contact information].

Thank you for using the Eco Power Logistics Power BI report. We hope you find it informative and valuable.

---

