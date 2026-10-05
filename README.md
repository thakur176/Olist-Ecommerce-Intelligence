# Olist E-Commerce Intelligence & Customer Analytics

An end-to-end Business Intelligence and Data Analytics project built using **SQL Server and Microsoft Power BI** to analyze e-commerce sales, customers, products, reviews, and delivery performance.

The project uses the Brazilian Olist E-Commerce dataset containing approximately **100K+ orders** and multiple related business tables.

---

## 📌 Project Overview

This project was developed as a practical, end-to-end Data Analyst / Business Intelligence project.

The objective was to transform raw e-commerce data into a structured analytical solution that can help business users understand:

- Overall sales and order performance
- Customer purchasing behavior
- Repeat customer and retention patterns
- Product and category performance
- Customer review and satisfaction
- Delivery performance
- Geographic performance

The project combines **SQL-based data preparation and validation** with an interactive **Power BI analytical dashboard**.

---

## 📈 Power BI Dashboard
https://app.powerbi.com/links/jc7FW2jjw7?ctid=427724da-dffb-4358-92a7-ead02d6f2f03&pbi_source=linkShare

The final Power BI report contains four main analytical dashboards plus a dedicated Product Detail drill-through page.



### 1️⃣ Executive Performance Overview
Provides a high-level view of overall e-commerce performance.

<img width="1322" height="732" alt="Dashboard page 1" src="https://github.com/user-attachments/assets/fcbe787a-df16-4342-943f-4fe6317c4bfd" />

### 2️⃣ Customer Intelligence & Retention
Analyzes customer purchasing behavior and repeat-customer patterns.

<img width="1318" height="736" alt="Dashboard page 2" src="https://github.com/user-attachments/assets/fa097465-546a-4eee-8d04-12eb663aa158" />

### 3️⃣ Product Intelligence
Analyzes product and category-level sales performance.

<img width="1322" height="736" alt="Dashboard page 3" src="https://github.com/user-attachments/assets/2055e090-5197-4e55-a95a-d159a1b2ba30" />

### 4️⃣ Customer Experience
Evaluates customer satisfaction and delivery performance.

<img width="1318" height="732" alt="Dashboard page 4" src="https://github.com/user-attachments/assets/35290989-f581-4a98-88b1-9c1f56258cdd" />

---

## 🎯 Business Objectives

The main business questions addressed in this project include:

### Sales & Executive Performance
- How is overall revenue performing?
- How many orders and customers are being served?
- Which states contribute the most revenue?
- How does revenue change over time?

### Customer Intelligence
- How many unique customers are there?
- How many customers are repeat customers?
- What percentage of customers make repeat purchases?
- How many orders does an average customer place?
- Which states generate the highest customer revenue?

### Product Performance
- Which product categories generate the highest revenue?
- Which products generate the most revenue?
- Which categories have the highest sales volume?
- How does category revenue change over time?

### Customer Experience
- What is the average customer review score?
- What percentage of reviews are positive?
- What percentage of reviews are negative?
- How well are orders being delivered on time?
- What is the average delivery time?
- How does customer satisfaction vary across categories and states?

---

# 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **SQL Server** | Data storage, staging, validation and analysis |
| **SQL** | Data preparation, quality checks and business analysis |
| **Power BI** | Interactive dashboards and business intelligence |
| **DAX** | KPI calculations and analytical measures |
| **Power Query** | Data transformation and preparation |
| **Excel** | Initial data understanding and analysis |
| **GitHub** | Project documentation and portfolio presentation |

---

# 📊 Dataset

The project uses the **Brazilian E-Commerce Public Dataset by Olist**.

The dataset contains multiple related tables covering customers, orders, products, sellers, payments, reviews and geographic information.

### Main datasets used

- Customers
- Orders
- Order Items
- Order Payments
- Order Reviews
- Products
- Sellers
- Geolocation
- Category Translation

### Dataset Source

[Kaggle – Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

> The raw dataset files are not included in this repository. Please download the original dataset from the source above.

---

# 🗄️ SQL Server Data Preparation

The raw Olist data was imported into SQL Server and organized into a staging layer for analytical preparation.

### Staging tables

```text
stg.Customers
stg.Orders
stg.Order_Items
stg.Order_Payments
stg.Order_Reviews
stg.Products
stg.Sellers
stg.Geolocation
stg.Category_Translation
