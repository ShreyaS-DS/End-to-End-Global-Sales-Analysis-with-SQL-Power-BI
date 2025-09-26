# End-to-End-Global-Sales-Analysis-with-SQL-Power-BI


## 🔹 Introduction  
This project showcases an **end-to-end data analysis pipeline** using **SQL** for data cleaning, transformation, and querying, along with **Power BI** for interactive visualization.  
The goal was to analyze sales performance across **six countries** (Canada, China, India, Nigeria, UK, and US) and provide insights into revenue, profit, and customer behavior.  

---

## 🔹 Project Overview  
- **Tools Used:** SQL (PostgreSQL), Power BI, Excel  
- **Datasets:** 6 country-level transaction datasets (10K+ rows each)  
- **KPIs Measured:** Total Sales, Total Profit, Orders, Discounts, Avg Order Value  
- **Deliverables:** Clean dataset, SQL scripts, interactive Power BI dashboard, insights report  

---

## 🔹 STAR Method Report  

### ⭐ Situation  
The company operated in **6 countries** with fragmented sales data.  
They needed a **centralized sales view** to monitor performance and improve strategy.  

### 🎯 Task  
- Merge all datasets into a **consolidated sales database**.  
- Clean & preprocess missing/duplicate values.  
- Generate **SQL queries** for sales insights.  
- Build a **Power BI dashboard** for executives.  

### ⚡ Action  
- Merged datasets with SQL `UNION ALL`.  
- Added calculated columns:  
  - `Total Amount = (Price × Quantity) – Discount`  
  - `Profit = Total Amount – (Cost Price + Quantity)`  
- Wrote queries for:  
  - Revenue & profit by country  
  - Top products & sales reps  
  - Store performance  
  - Period-wise min/max/avg sales  
- Built Power BI dashboard with:  
  - **KPIs**: Sales (4.14M), Profit (959K), Orders (3K)  
  - **Geo Map**: Country-wise sales  
  - **Trend Analysis**: Monthly sales & day-wise profit  
  - **Customer Insights**: Sales by payment method, category, discount impact  

### 🚀 Result  
- **Unified sales view** across 6 countries.  
- Identified **Canada & US as top contributors**.  
- Found **Home & Kitchen + Clothing** as highest categories.  
- Discovered **Sunday generated highest profit (0.18M)**.  
- Delivered a **dashboard adopted by stakeholders** for decision-making.  

---

## 🔹 Dashboard Preview  
![Dashboard Screenshot](dashboard/dashboard_screenshot.png)  

---

## 🔹 Repository Contents  
- `data/` → Country-wise sales datasets  
- `sql/` → SQL scripts (data cleaning & analysis)  
- `dashboard/` → Power BI file & screenshots  
- `docs/` → Project report (STAR method)  
- `README.md` → Project overview & documentation  

---

## 🔹 Key Learnings  
- Handling **missing & duplicate values** in SQL  
- Creating **calculated fields** for business KPIs  
- Designing **interactive dashboards** in Power BI  
- Applying **STAR framework** to present data projects  

---

## 📌 Author  
👩‍💻 **Shreya S.**  
- Data Analyst | SQL | Power BI | Python | Excel  
 

---

