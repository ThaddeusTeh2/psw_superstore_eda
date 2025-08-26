# 📊 Superstore Sales & Profit Analysis (EDA + Feature Engineering)

## Overview

This project explores sales, discounting, and profitability patterns in a **Superstore dataset** using **Exploratory Data Analysis (EDA)** and **Feature Engineering**.  
The dataset includes transactional details such as order dates, shipping modes, customer segments, locations, product categories, sales, quantity, discount, and profit.

The primary goal is to identify **factors affecting profit**, uncover **regional/category-level trends**, and highlight the impact of **discounting strategies** on profitability.

---

## Dataset

Key columns after feature engineering:

- **Order Date, Ship Date, Shipping Duration, Is_Weekend_Order, Is_Holiday_Season**
- **Ship Mode, Segment, Region, State, City, Category, Sub-Category**
- **Sales, Quantity, Discount, Profit**
- **Price_Per_Unit, Profit_Margin, Profit_Per_Unit, Sales_Per_Quantity**
- **Discount_x_Quantity, Discount_x_Sales**
- **Category_Avg_Profit, SubCategory_Avg_Sales, Region_Avg_Discount**

---

## EDA Questions

1. Which **categories, sub-categories, and segments** drive the most profit?
2. How do **regions and states** differ in profitability?
3. What is the impact of **discounting** on profit margins?
4. How do **sales and quantity** relate to profitability?
5. What are the **time-based patterns** (year, month, quarter, day of week, holiday season)?
6. Which combinations of **region and category** are most profitable?

---

## Visualizations

- **Profit vs Categories/Segments/Regions/States**
- **Discount vs Profit (scatter, boxplots, interaction with quantity and sales)**
- **Sales vs Profit and Quantity vs Profit (log-scaled)**
- **Profit over Time (yearly, monthly, quarterly, weekly)**
- **Profitability Metrics (profit margin distributions, violin plots)**
- **Correlation Heatmap of Sales, Discount, Profit, and Derived Metrics**

---

## Tools & Libraries

- **Python**
- **Pandas, NumPy** (data wrangling & feature engineering)
- **Matplotlib, Seaborn** (data visualization)
- **Jupyter Notebook** (analysis workflow)

---

## Files

- `superstore_parsed_dates.csv` → cleaned dataset with engineered features
- `EDA_Feature_Engineering.ipynb` → notebook with transformations and EDA
- `README.md` → project summary (this file)

---

## Key Insights (Preview)

- High discounts often **erode profits**, especially in technology-related categories.
- **Furniture** generates high sales but lower margins compared to **Office Supplies**.
- **Regional performance varies** significantly, with some states consistently unprofitable.
- Seasonal effects are visible, with **holiday months showing spikes in both sales and discounts**.

---
