# 📊 Tableau Superstore Case Study – Delivery, Seasonality, and Expansion Analysis

## 📌 Project Overview
This Tableau project analyzes customer complaints, seasonal trends, and global profitability for a multinational superstore. The analysis is performed in three different cases using interactive dashboards in Tableau, aimed at uncovering key insights and driving data-backed decisions.

## 🎯 Objective
The objective of this project is to:

1. Analyze and resolve customer delivery-related complaints.
2. Identify seasonal product trends for targeted sales.
3. Recommend profitable regions for expansion based on sales and profit data.

## 📁 Dataset
**Source**: [Tableau Superstore Sample Dataset]([https://public.tableau.com/app/sample-data/superstore](https://github.com/Sanchitsingh05/Tableau-Superstore-Case-Study-Delivery-Seasonality-and-Expansion-Analysis/blob/main/Tableau%20Case%20Study%20Dataset.xlsx))
* **Records**: 51,290 Orders
* **Fields Include**:

  * Order ID, Customer ID, Product Name, Category
  * Order Date, Ship Mode, Shipping Days
  * Sales, Profit, Quantity, Region, Country, Market
  * Order Priority, Segment, and more.

# 🔍 Case 1: Customer Delivery Feedback Analysis

## 📝 Problem:

Customers are dissatisfied with product deliveries. The goal is to investigate if their delivery preferences and priorities are being met, and whether delivery issues correlate with product returns or specific regions.

## 📊 Dashboard Insights:
### ✅ i. Are customers getting their products delivered in the same mode as they selected?

* **Yes.**
* Delivery is consistent with selected ship mode.

  * **First Class**: 2,925 deliveries
  * **Second Class**: 2,188 deliveries
  * **Same Day**: 1,013 deliveries

### ✅ ii. Are customers' priority levels being considered?

* **Partially Yes.**
* Higher priority orders (Critical & High) are delivered faster.

  * Critical orders: Avg. 2 shipping days
  * Low-priority orders: Avg. 6 shipping days

### ✅ iii. How many times customers faced delivery delays?

* Most delays occurred in **Standard Class**, where over 9,000 orders took 4+ days.
* Heatmap shows delays are more frequent in low-priority orders.

### ✅ iv. Do late deliveries lead to returns?

* **Inconclusive from dashboard.**
* Additional data on return rates would be required to verify this.

### ✅ v. Do specific regions/states face more delivery problems?

* **Not addressed in this dashboard.**
* Regional delivery breakdown would be needed for deeper insights.

## 📌 Recommendations:
* Improve **Standard Class logistics**.
* Consider offering **Same Day/First Class options** for **High and Critical** orders only.
* Include a new KPI to track **on-time vs late deliveries per region** in future dashboards.


# ❄️ Case 2: Product Sales Seasonality

## 📝 Problem:
The ecommerce company wants to identify seasonal trends to adjust inventory and marketing.

## 📊 Dashboard Insights:

### 🌞 Summer vs Other Seasons

* **Sales in "Other" season**: ₹6.8M
* **Sales in Summer**: ₹3.3M

### 📉 Seasonal Product Sales Fluctuation:

* **High Speed Internet** and **Hewlett Packard Products** show highest **sales differences**.

  * High Speed Internet: Difference of 8,188
  * Hewlett Packard: Difference of 8,060
* These products should be stocked more in high-performing seasons and promoted during dips.

## 📌 Recommendations:
* Focus promotional efforts on **High Speed Internet** and **HP products** during low seasons.
* Use seasonality trend data to optimize **stock levels**, **ads**, and **delivery**.

# 🌍 Case 3: Global Sales and Expansion Strategy

## 📝 Problem:
A global superstore wants to expand geographically and needs insights on where to invest for higher profitability.

## 📊 Dashboard Insights:

### 🌎 Global Overview:

* **Total Orders**: 51,290
* **Countries Covered**: 165
* **Markets**: USCA, Europe, Asia Pacific, LATAM, Africa

### 💰 Market vs Profit:

* **Europe**: Highest profit — ₹449,552
* **Asia Pacific**: ₹403,176
* **LATAM & Africa**: Lowest profits

### 📈 Growth Over Years:

* Steady rise in profits from 2012 to 2015.
* **Europe and Asia Pacific** show consistent yearly growth in sales and profit.

### 🌍 Estimation of Future Sales:

* Projected growth in **Europe** and **Asia Pacific** makes them best choices for investment.

## 📌 Recommendations:
* Expand further in **Europe** and **Asia Pacific**.
* Limit investment in **LATAM** and **Africa** until performance improves.
* Consider regional campaigns in **USCA** to boost stagnant profits.

## 📌 Tools Used

* **Tool**: Tableau Desktop
* **Skills Applied**: Dashboard Design, Data Cleaning, Visualization, Heatmaps, Seasonal Analysis, Geo Analysis, Profit Estimation

## 👤 Author
**Sanchit Singh**
