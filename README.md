# 📊 Store Data Analysis — Vrinda Store (Excel Project)

## Overview
This project analyzes Vrinda Store sales data for the year **2022** using **Microsoft Excel**.  
It uncovers sales trends, customer behavior, top geographies and channels, and provides actionable recommendations to grow revenue.

---

## Table of Contents
- [Overview](#overview)  
- [Objectives](#objectives)  
- [Tools & Skills](#tools--skills)  
- [Dataset](#dataset)  
- [Analysis Questions](#analysis-questions)  
- [Sample Insights](#sample-insights)  
- [Final Recommendations](#final-recommendations)  
- [How to Use](#how-to-use)  
- [Folder Structure (suggested)](#folder-structure-suggested)  
- [Author / Contact](#author--contact)

---

## Objectives
- Compare **sales vs orders** over time and in a single visual.
- Identify **highest sales & order months**.
- Analyze **gender** and **age-group** purchasing patterns.
- List **top states**, **order statuses**, and **top channels**.
- Find **highest selling categories** and other business insights.
- Provide recommendations to improve sales for Vrinda Store.

---

## Tools & Skills
- Microsoft Excel (recommended: Excel 2016 / 2019 / 365)
  - Data cleaning and transformation
  - Pivot Tables & Pivot Charts
  - Slicers & Filters
  - Conditional Formatting
  - Basic formulas (SUMIFS, COUNTIFS, TEXT, VLOOKUP/XLOOKUP or INDEX+MATCH)
- Analytical techniques: trend analysis, ranking, percentage contribution, segmentation

---

## Dataset (example fields)
- `Order ID`  
- `Order Date` (format: YYYY-MM-DD)  
- `Customer ID`  
- `Gender` (Male / Female / Other)  
- `Age` or `Age Group` (e.g., 18-29, 30-49, 50+)  
- `State`  
- `Order Status` (Delivered, Cancelled, Returned, Pending, etc.)  
- `Sales Channel` (Amazon, Flipkart, Myntra, Website, etc.)  
- `Category` (Apparel, Electronics, Home, etc.)  
- `Quantity`  
- `Sales Amount` (numeric currency)

---

## Analysis Questions (examples)
1. Compare **Sales** and **Orders** using a single chart (dual-axis column + line).  
2. Which **month** had the highest sales and orders?  
3. Who purchased more in 2022: **Men or Women**?  
4. What were the different **order statuses** in 2022 and their counts?  
5. List **Top 10 states** by sales contribution.  
6. Relationship between **age group** and **gender** (by order count).  
7. Which **channel** contributes the most to sales?  
8. Which **category** has the highest sales and volume?

---

## Sample Insights (example results)
- **Women** are more likely to buy compared to men — *~65%* of orders.  
- **Maharashtra, Karnataka, Uttar Pradesh** are the top 3 states — *~35%* of sales.  
- **Adults (30–49 yrs)** contribute the most — *~50%* of sales.  
- **Amazon, Flipkart, Myntra** together contribute ~*80%* of sales.  

> _These numbers are illustrative — compute exact percentages from your dataset._

---

## Final Recommendations
To improve Vrinda Store sales:
- **Target women customers aged 30–49** with focused campaigns.  
- Prioritize **Maharashtra, Karnataka, and Uttar Pradesh** for geo-targeted ads and inventory.  
- Run promotions and coupons on **Amazon, Flipkart, and Myntra** where majority of customers buy.  
- Create category-specific deals for the **highest selling categories** and expand assortments there.  
- Monitor order statuses to reduce cancellations/returns (optimize UX, delivery and product descriptions).

---

## How to Use (step-by-step)
1. Place your raw CSV/Excel data in the `data/` folder (or `input/`).  
2. Open `Vrinda_Store_Analysis.xlsx`. Enable editing if required.  
3. Go to the **Data Clean** sheet (if present) and ensure date columns are parsed correctly.  
4. Use the **Pivot Tables** sheets to explore:
   - `Pivot_Sales_vs_Orders` — monthly sales and order counts (single chart).  
   - `Pivot_Gender_Age` — segmentation by gender and age group.  
   - `Pivot_State_Sales` — top states ranking.  
   - `Pivot_Channel` — channel-wise contribution.  
5. Use **Slicers** (Year, Month, Channel, State, Category) to filter the dashboard.  
6. Export final charts/tables to PDF or presentable PowerPoint if needed.

---

## Folder Structure (suggested)
