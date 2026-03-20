📊 Retail Sales & Profit Dashboard (Power BI)
📌 Project Overview

This project focuses on analyzing retail sales data using Power BI to generate meaningful business insights.
The dashboard provides a clear view of revenue, profit, customer behavior, and regional performance.

The main objective is to transform raw transactional data into an interactive and insightful dashboard that supports better decision-making.

📂 Dataset Description

The dataset consists of four main tables:

Transactions
Contains sales-level data such as Transaction ID, Date, Customer ID, Product ID, Store ID, Quantity, Discount, and Payment Method.

Products
Includes product details like Product Name, Category, Subcategory, Unit Price, and Cost Price.

Customers
Contains customer information such as Name, Gender, Birth Date, City, and Join Date.

Stores
Includes store-related details like Store Name, City, and Region.
🧱 Data Modeling

Built a star schema data model

Transactions table used as the fact table

Products, Customers, and Stores used as dimension tables

Established relationships using:

ProductID

CustomerID

StoreID

This structure ensures efficient filtering and accurate analysis.

Key Calculations (DAX Measures)

The following business metrics were created:

Total Revenue = Quantity × Unit Price × (1 - Discount)

Total Profit = (Unit Price - Cost Price) × Quantity

Total Orders = Count of Transaction ID

Total Customers = Distinct count of Customer ID

Total Quantity Sold

Average Order Value (AOV) = Revenue / Orders
🎨 Dashboard Design

Used a consistent purple-based color theme

Applied clean layout with proper alignment and spacing

Grouped related visuals for better readability

Used minimal and clear titles for a professional look

🔍 Key Insights

A small number of products contribute significantly to total revenue

Some categories have high revenue but relatively lower profit

The East region generates the highest profit among all regions

Higher discounts tend to reduce overall profitability

Revenue shows fluctuations across months, indicating possible seasonal trends

Customer segments contribute differently to overall profit

✅ Conclusion

This dashboard provides a comprehensive view of retail performance by combining sales, profitability, and customer insights.

It helps in:

Identifying top-performing products

Understanding regional profitability

Evaluating the impact of discounts

Supporting data-driven business decisions
