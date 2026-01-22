# 📊 Sales Performance Dashboard (2023 vs 2024)
Excel Dashboard Project | KPI, YoY Analysis & Business Insights
An end-to-end Excel data analysis project that transforms raw sales data into a clean, interactive,
and business-focused dashboard using Pivot Tables, formulas, and professional dashboard design techniques.

---

## 🎯 Business Problem
Businesses often have large amounts of sales data but struggle to:
- Track key performance metrics clearly
- Compare performance year-over-year
- Identify trends across time, products, and regions
- Present insights in a simple and interactive way

This dashboard solves those problems by converting raw data into clear visual insights.

---

## 📌 Key Objectives
- Track core KPIs: Sales, Quantity, Cost, and Profit  
- Perform Year-on-Year (YoY) performance comparison  
- Analyze monthly trends, regions, and product categories  
- Build an interactive and easy-to-use Excel dashboard  

---

## ✨ Key Features
- 📈 Dynamic KPI cards for Sales, Quantity, Cost, and Profit  
- 🔁 Year-on-Year (YoY) growth analysis (2023 vs 2024)  
- 🎯 Interactive slicers to filter the entire dashboard by Category  
- 🔼🔽 Visual indicators showing performance increase or decrease  
- 🧭 Navigation bar to move between Data, Calculations, and Dashboard sheets  

---

## 🛠 Tools & Skills Used
- Microsoft Excel  
- Excel Tables (Ctrl + T)  
- Pivot Tables & Pivot Charts  
- Calculated Fields  
- Excel Functions:  
  - TEXT  
  - IF  
  - ABS  
  - TODAY  
- GETPIVOTDATA  
- Slicers & Report Connections  
- Dashboard wireframing and layout design  

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation & Cleaning
- Converted raw sales data into **Excel Tables** to make the analysis dynamic  
- Extracted Month and Year from the Date column for time-based analysis  

```excel
=TEXT(Date,"mmm")    // Extract Month
=TEXT(Date,"yyyy")   // Extract Year
---
###2️⃣ KPI & Metric Calculation
Created Pivot Tables to calculate:
-Total Sales
-Quantity
-Cost
-Added a Calculated Field inside Pivot Tables to calculate Profit
-Profit = Sales - Cost
---
###3️⃣ Year-on-Year (YoY) Growth Logic
-Compared 2024 performance against 2023
-(Current Year - Previous Year) / Previous Year
-Displayed results as percentages for easy interpretation
---
###4️⃣ Dynamic Performance Indicators
-Used conditional logic to show growth or decline with arrows
-=IF(YoY>0,
-"▲ " & TEXT(ABS(YoY),"0%") & " vs last year",
-"▼ " & TEXT(ABS(YoY),"0%") & " vs last year")
This helps users quickly understand whether performance improved or declined.
---
###6️⃣ Charts & Interactivity
-Line charts for monthly sales trends (2023 vs 2024)
-Bar charts for product-wise and region-wise performance
-Added slicers for Category filtering
-Connected slicers to all Pivot Tables using Report Connections
---
###7️⃣ Live Date Feature
-Displayed the current date automatically on the dashboard
-=TODAY()
-📈 Key Insights
-📊 Sales increased by 30%
-💰 Profit increased by 34%
-📦 Quantity increased by 24%
-💸 Costs increased by only 11%
---
###Business Insight
-Profit grew faster than sales because costs were well controlled, leading to improved margins in 2024.
###🧠 What I Learned
-How to clean and structure raw business data
-How to calculate KPIs and YoY growth
-How to use Pivot Tables for business reporting
-How to design interactive Excel dashboards
-How to communicate insights clearly through visuals

---
👤 Author

Seema Kumari
Aspiring Data Analyst | Excel, SQL & Python Learner
