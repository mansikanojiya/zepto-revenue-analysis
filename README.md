# zepto-revenue-analysis

End-to-End Data Analysis Project (SQL + Excel + Power BI)
📌 Project Overview
This project analyzes Zepto product data to generate business insights related to pricing, discounts, inventory management, and revenue performance.
The analysis was performed end-to-end using:
Excel – Data cleaning & preprocessing
SQL – Data exploration & business queries
Power BI – Data modeling, DAX measures & interactive dashboard
📂 Dataset Information
The dataset contains product-level information including:
Product Name
Category
MRP
Discount Percentage
Discounted Selling Price
Available Quantity
Out of Stock (True/False)
Weight in Grams
🔹 Step 1: Data Cleaning (Excel)
✔ Removed null values
✔ Standardized column names
✔ Checked data types
✔ Created calculated columns:
Discount Amount = MRP - Discounted Price
Price Per Gram = Discounted Price / Weight
Stock Value = Available Quantity × Discounted Price
🔹 Step 2: SQL Analysis
Performed business-level queries including:
🟢 Basic Analysis
Total revenue calculation
Average discount by category
Total stock value
🟡 Intermediate Analysis
Top 3 most expensive products per category
Products with MRP higher than category average
Category revenue contribution %
Out-of-stock revenue loss estimation
🔴 Advanced Analysis
Ranking products by highest discount
Running total of revenue
Price segmentation (Budget / Mid / Premium)
Anomaly detection (Extreme price per gram)
Revenue leaderboard per category
🔹 Step 3: Power BI Dashboard
Built an interactive dashboard with:
📊 Revenue by Category
📊 Discount vs Revenue Analysis
📊 Top & Bottom Performing Categories
📊 Slow Moving Product Identification
📊 Price Per Gram Analysis
📊 Revenue Contribution %
📊 Inventory Value
Key DAX Measures Created:
Total Revenue
Running Revenue
Category Revenue %
Total Inventory Value
Lost Revenue (Out-of-stock)
Slow Moving Product Count
📈 Key Business Insights
Cooking & Munchies categories generate the highest revenue.
Higher discounts do not always guarantee higher revenue.
Certain products show high stock but low sales potential.
Premium products significantly impact total revenue.
Inventory optimization opportunities identified.
🛠 Tools & Skills Used
SQL (Joins, Aggregations, Window Functions, CTEs)
Power BI (DAX, Data Modeling, Visualization)
Excel (Data Cleaning, Derived Columns)
Business Analysis & Insight Generation
🎯 Business Impact
This project demonstrates how pricing strategy, discount optimization, and inventory management can influence revenue performance in a quick-commerce business model.****
