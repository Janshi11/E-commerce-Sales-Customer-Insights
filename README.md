# E-commerce-Sales-Customer-Insights



---

## 📌 Project Overview

This project analyzes an **E-commerce transaction dataset** to uncover key business insights related to:

- Sales performance  
- Customer behavior  
- Product performance  
- Geographic trends  

The goal is to simulate a **real-world business analytics workflow** using Python, where raw data is cleaned, analyzed, and visualized to support data-driven decisions.

---

## 🗂 Dataset Description

The dataset contains transactional-level e-commerce data with the following columns:

- `InvoiceNo` – Unique identifier for each order  
- `StockCode` – Product code  
- `Description` – Product name  
- `Quantity` – Number of items purchased  
- `InvoiceDate` – Date and time of purchase  
- `UnitPrice` – Price per item  
- `CustomerID` – Unique customer identifier  
- `Country` – Country of the customer  

---

## 🛠 Tools & Technologies Used

- Python  
- Pandas – Data cleaning and analysis  
- Matplotlib – Data visualization  
- Google Colab – Development environment  

---

## 🔍 Key Business Questions Answered

- What is the **total revenue** generated?
- What is the **Average Order Value (AOV)**?
- Who are the **top 10 customers by total spend**?
- Which are the **top 10 products by revenue**?
- Which **countries contribute the most to sales**?
- How does **sales trend over time (monthly)**?

---

## 🧹 Data Cleaning & Preparation

- Handled encoding issues using `latin1`
- Removed records with missing:
  - `CustomerID`
  - `Description`
- Converted `InvoiceDate` to datetime format
- Converted `CustomerID` to integer
- Created a new feature:
  - `TotalSales = Quantity × UnitPrice`

---

## 📈 Analysis & Visualizations

### 🔹 Customer Analysis
- Identified **top 10 high-value customers** based on total spending
- Insight:
  - A small group of customers contributes a significant portion of total revenue

### 🔹 Product Analysis
- Identified **top 10 products by total revenue**
- Insight:
  - Revenue is concentrated among a limited number of best-selling products

### 🔹 Geographic Analysis
- Analyzed **country-wise revenue contribution**
- Insight:
  - Sales are geographically concentrated, helping prioritize key markets

### 🔹 Time-Based Analysis
- Analyzed **monthly sales trends**
- Insight:
  - Sales show clear fluctuations over time, indicating seasonality

---

## 📊 Visualizations Included

- Top 10 Customers by Total Spend (Bar Chart)
- Top 10 Products by Revenue (Bar Chart)
- Top 10 Countries by Revenue (Bar Chart)
- Monthly Sales Trend (Line Chart)

> All charts include **data labels**, formatted in **K (thousands)** for readability.

---

## 💡 Key Insights

- Average Order Value highlights customer spending behavior per order
- High-value customers drive a large share of revenue
- A small set of products dominates overall sales
- Revenue varies significantly by country
- Monthly trends suggest seasonal patterns

---


