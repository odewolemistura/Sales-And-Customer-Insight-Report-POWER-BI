# ☕ Coffee Shop Sales & Customer Insight Report

## 📘 Table of Contents
1. [📄 Project Overview](#project-overview)  
2. [📊 Dataset Summary](#dataset-summary)  
3. [🛠 Tools & Technologies Used](#tools--technologies-used)  
4. [🧹 Data Cleaning & Preparation](#data-cleaning--preparation)  
5. [📌 Key KPIs](#key-kpis)  
6. [🔍 Analysis Findings](#analysis-findings)  
7. [✅ Business Recommendations](#business-recommendations)  

---

## 📄 Project Overview

The **Coffee Shop Sales & Customer Insight Report** helps stakeholders understand and optimize performance across products, customer segments, and regional markets. Built with **Power BI**, this report enables data-driven decision-making focused on profitability, loyalty program effectiveness, and strategic growth.

---

## 📊 Dataset Summary

The dataset consists of three main tables:

| Table     | Description |
|-----------|-------------|
| **Product** | Coffee details including type, roast, size, unit price, and profit |
| **Order**   | Transaction records with order date, quantity, and customer/product IDs |
| **Customer** | Customer details with location and loyalty program status |

---

## 🛠 Tools & Technologies Used

- Power BI Desktop  
- Power Query (M Language)  
- DAX (Data Analysis Expressions)  
  
---

## 🧹 Data Cleaning & Preparation

Performed using **Power Query**:
- Removed duplicates  
- Dropped irrelevant columns  
- Cleaned categorical values (e.g., `L` → `Light Roast`)  
- Created a **Date Table** for time intelligence  
- Established relationships:
  - `Order` → `Product` (via Product ID)  
  - `Order` → `Customer` (via Customer ID)

---

## 📌 Key KPIs

| KPI | Description |
|-----|-------------|
| **Total Revenue** | Unit Price × Quantity |
| **Total Profit** | Profit × Quantity |
| **Monthly Trends** | Sales and profit tracked over time |
| **Average Order Value** | Revenue ÷ Number of Orders |
| **Order Frequency** | Orders per customer |
| **Customer Segmentation** | Loyalty vs non-loyalty performance |
| **Revenue Breakdown** | By roast type, coffee type, size, and country |

---

## Dashboard
![image alt](https://github.com/odewolemistura/Sales-And-Customer-Insight-Report-POWER-BI/blob/52ee28b48742d06cb39cae029c3b758c2f351025/Dashboard1.png)
![image alt](https://github.com/odewolemistura/Sales-And-Customer-Insight-Report-POWER-BI/blob/05d7929d7105f00ac3a6112aa07e50a34ac08d68/Dashboard2.png)
![image alt](https://github.com/odewolemistura/Sales-And-Customer-Insight-Report-POWER-BI/blob/e8f8c0506174232b2b043e4edd96bc9ba81a8525/Dashboard3.png)

## 🔍 Analysis Findings

### 💰 Sales & Profit Trends
- Highest monthly revenue: **June ($4,843)**  
- Lowest monthly revenue: **August ($2,326)**  
- Noticeable summer drop from July to September  

### 🌍 Regional Insights
- **United States** dominates with $35,638 in revenue  
- **Ireland** outperforms UK despite fewer customers  

### ☕ Product Insights
- **Light Roast** and **Excelsa/Arabica** are top performers  
- **2.5kg size** generates over **50% of total revenue**

### 🎯 Loyalty Program Insights
- Loyalty members: **more profit** but **lower order value**  
  - Profit: **$685 (Yes)** vs **$616 (No)**  
  - AOV: **$45.08 (Yes)** vs **$49.12 (No)**  
- Loyalty customers: **48% of actives**, **46% of revenue**

---

## ✅ Business Recommendations

### 📌 1. Optimize Loyalty Program
- Launch **tiered loyalty levels** and exclusive perks  
- Encourage higher spending with volume-based discounts  

### 📌 2. Promote High-Margin Products
- Focus on **Light Roast**, **Excelsa**, and **Arabica** in **2.5kg size**  
- Bundle high-value SKUs with loyalty offers

### 📌 3. Address Seasonal Sales Drop
- Launch **"Summer Chill"** campaign in July–August  
- Promote **cold brew and iced coffee products**

### 📌 4. Expand in the US Market
- Develop **localized US campaigns**  
- Explore growth potential in **Ireland**

### 📌 5. Improve Customer Engagement
- Use **Power BI segmentation** to identify low-engagement users  
- Personalize retention campaigns based on customer behavior


