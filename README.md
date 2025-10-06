# Data-Analysis-using-Excel-
This analysis focuses on examining sales data to identify total sales, profits, and performance trends. Using Microsoft Excel, raw data was cleaned, organized, and analyzed through formulas, Pivot Tables, and charts.

# Sales Revenue & Profit Analysis Dashboard (Excel)

**Project Type:** Excel-based Data Analysis & Dashboard  
**Tools Used:** Power Query, Power Pivot, Pivot Tables, Excel Charts  

---

## 📘 Project Overview
This project is a complete **Sales Data Analysis** built using Microsoft Excel to analyze and visualize **Revenue, Cost, and Profit** performance.

The goal of this dashboard is to provide clear insights into:
- Total Sales and Profit trends  
- Profit margins by product and region  
- Top-performing products and customers  
- Areas of high cost or low profitability  

The project demonstrates the full Excel analytics workflow — from **data cleaning** to **modeling and visualization** — using only Excel features (Power Query, Data Model, Pivot Tables).

---

## ⚙️ Workflow Summary

### 1️⃣ Data Preparation — *Power Query*
- Imported raw sales data from multiple Excel sheets / CSV files.  
- Removed duplicates and unnecessary columns.  
- Fixed data types (dates, numbers, text).  
- Created calculated columns:
  - **Revenue = Quantity × Unit Price**
  - **Cost = Quantity × Unit Cost**
  - **Profit = Revenue − Cost**
- Standardized date format and created a “Year-Month” column for time analysis.

### 2️⃣ Data Modeling — *Power Pivot (Data Model)*
- Built a **Calendar Table** to support time-based analysis.
- Created **relationships** between:
  - Sales Table ↔ Products Table  
  - Sales Table ↔ Customers Table  
  - Sales Table ↔ Regions Table
- Defined measures using DAX / Calculated Fields:
  - `Total Revenue`
  - `Total Cost`
  - `Total Profit`
  - `Profit Margin %`

### 3️⃣ Pivot Tables & Dashboards
- Built Pivot Tables for key metrics:
  - Revenue by Month / Region / Product
  - Profit by Product Category
  - Top 10 Customers by Profit
- Created interactive charts (Column, Line, and Donut).
- Added **Slicers** for Year, Region, and Product Category for dynamic filtering.

---

## 📊 Dashboard Insights

| Metric | Description |
|--------|-------------|
| 💰 **Total Sales** | Overall revenue generated |
| 📈 **Total Profit** | Net profit after cost deduction |
| 📊 **Profit Margin %** | Overall profitability indicator |
| 🏆 **Top Products** | Highest revenue and profit contributors |
| 🌍 **Regional Performance** | Breakdown of revenue and profit by region |

The dashboard allows decision-makers to quickly identify trends, top performers, and areas for improvement in profitability.

---



## 🧭 How to Use
1. Download the Excel file from `/excel/` folder.  
2. Open in **Microsoft Excel (Office 365 / Excel 2019+)**.  
3. Go to `Data` → `Queries & Connections` → **Refresh All** to load data.  
4. Navigate to the “Dashboard” sheet to explore:
   - Revenue trend charts  
   - Profit margin visuals  
   - Interactive filters and KPIs  

---

## 🧠 Key Learnings
- End-to-end business analysis using Excel only.  
- Applying Power Query for ETL (Extract, Transform, Load).  
- Building data models and creating relationships.  
- Using DAX / calculated measures in Power Pivot.  
- Designing clear and interactive dashboards.

---



## 👥 Project Team

| Name | Role |
|------|------|
| **Hamed Gebril** | Data Analyst – Dashboard Design & Power Query |
| **Asem Fareed** | Data Analyst – Data Modeling & Visualization |

---




 

