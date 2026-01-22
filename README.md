# 📊 Sales Performance Dashboard (2023 vs 2024)

**Excel Dashboard Project | KPI, YoY Analysis & Business Insights**

An end-to-end Excel data analysis project that transforms raw sales data into a clean, interactive, and business-focused dashboard using **Pivot Tables, formulas, and professional dashboard design techniques**.

---

## 📌 Project Overview

Businesses often have access to large volumes of sales data but struggle to extract meaningful insights.  
This project demonstrates how raw sales data can be converted into **clear KPIs, year-over-year comparisons, and actionable business insights** using Microsoft Excel.

The dashboard is designed to be **interactive, intuitive, and decision-focused**, making it suitable for stakeholders and business users.

---

## 🎯 Business Problem

Organizations commonly face challenges such as:
- Difficulty tracking key sales metrics in one place  
- No clear year-over-year performance comparison  
- Limited visibility into trends across time, products, and regions  
- Static reports that are hard to explore  

This dashboard solves these issues by presenting **dynamic visuals and KPIs** in a single Excel interface.

---

## 🎯 Key Objectives

- Track core KPIs: **Sales, Quantity, Cost, and Profit**
- Perform **Year-on-Year (YoY)** performance comparison (2023 vs 2024)
- Analyze **monthly trends, regions, and product categories**
- Build an **interactive and user-friendly Excel dashboard**

---

## ✨ Key Features

- 📈 **Dynamic KPI cards** for Sales, Quantity, Cost, and Profit  
- 🔁 **Year-on-Year (YoY) growth analysis** (2023 vs 2024)  
- 🎯 **Interactive slicers** to filter the entire dashboard by Category  
- 🔼🔽 **Visual performance indicators** showing increase or decrease  
- 🧭 **Navigation bar** to move between Data, Calculations, and Dashboard sheets  
- 📅 **Live date display** using Excel formulas  

---

## 🛠 Tools & Skills Used

- **Microsoft Excel**
- Excel Tables (`Ctrl + T`)
- Pivot Tables & Pivot Charts
- Calculated Fields
- Excel Functions:
  - `TEXT`
  - `IF`
  - `ABS`
  - `TODAY`
- `GETPIVOTDATA`
- Slicers & Report Connections
- Dashboard wireframing and layout design

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation & Cleaning
- Converted raw sales data into **Excel Tables** to ensure dynamic updates  
- Extracted **Month** and **Year** from the Date column for time-based analysis  

```excel
=TEXT(Date,"mmm")   // Extract Month
=TEXT(Date,"yyyy")  // Extract Year
2️⃣ KPI & Metric Calculation
Created Pivot Tables to calculate:

Total Sales

Total Quantity

Total Cost

Added a Calculated Field inside Pivot Tables to compute Profit:

ini
Copy code
Profit = Sales - Cost
3️⃣ Year-on-Year (YoY) Growth Logic
Compared 2024 performance against 2023

Used the YoY formula:

sql
Copy code
(Current Year - Previous Year) / Previous Year
Displayed results as percentages for easy interpretation

4️⃣ Dynamic Performance Indicators
Used conditional logic to show growth or decline with arrows:

excel
Copy code
=IF(YoY>0,
"▲ " & TEXT(ABS(YoY),"0%") & " vs last year",
"▼ " & TEXT(ABS(YoY),"0%") & " vs last year")
This allows users to instantly understand whether performance improved or declined.

5️⃣ Charts & Interactivity
📈 Line charts for monthly sales trends (2023 vs 2024)

📊 Bar charts for product-wise and region-wise performance

🎯 Category-based slicers

🔗 Connected slicers to all Pivot Tables using Report Connections

6️⃣ Live Date Feature
Displayed the current date dynamically on the dashboard:

excel
Copy code
=TODAY()
📈 Key Insights
📊 Sales increased by 30%

💰 Profit increased by 34%

📦 Quantity increased by 24%

💸 Costs increased by only 11%

💡 Business Insight
Profit grew faster than sales because costs were well controlled, resulting in improved profit margins in 2024.
This indicates better operational efficiency and pricing strategies.

🧠 What I Learned
How to clean and structure raw business data effectively

How to calculate KPIs and YoY growth metrics

How to use Pivot Tables for professional business reporting

How to design interactive Excel dashboards

How to communicate insights clearly using visuals and KPIs

👤 Author
Seema Kumari
Aspiring Data Analyst | Excel, SQL & Python Learner


⭐ If you found this project helpful, feel free to star the repository and share feedback!

markdown
Copy code
