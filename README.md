# 🛍️ Madhav E-Commerce Sales Dashboard (Power BI Project)

## 📌 Objective

The owner of Madhav Store wants a centralized dashboard to track and analyze their **online sales performance across India**. This dashboard helps them make better business decisions by identifying top-performing states, customers, and categories, along with tracking revenue, quantity, and profit trends over time.

## 📊 Dataset Information

- **Source**: https://drive.google.com/file/d/16hFCFB9gHuRrM0hfkSFVPnqL27l2H40p/view?usp=drive_link ,
             https://drive.google.com/file/d/1_jXpOs3fODRluEWJOgiEV2N0ONuyvtr5/view?usp=drive_link
- **Files Used**: 
  - `Order Details` table: Contains `Order ID`, `Amount`, `Profit`, `Quantity`, `Category`, `Sub-Category`, `Payment Mode`
  - `Order Table`: Contains `Order ID`, `Order Date`, `Customer Name`, `State`, `City`
- **Total Rows**: ~1500

## 🧮 KPIs Tracked

- **Total Amount (₹)**
- **Total Profit (₹)**
- **Total Quantity Sold**
- **Average Order Value (AOV)**

## 📈 Visualizations

- **Clustered Bar Chart**: Sum of Amount by State
- **Donut Chart**: Sum of Quantity by Payment Mode
- **Stacked Column Chart**: Profit by Month
- **Bar Chart**: Sum of Amount by Customer Name
- **Donut Chart**: Sum of Quantity by Category
- **Stacked Bar Chart**: Profit by Sub-Category

### 🎛️ Filters and Slicers
- **Quarter Buttons**: Q1, Q2, Q3, Q4
- **State Name Filter**: To view regional performance

## 🔧 Process Overview

1. **Data Preparation**:
   - Imported two tables: Order Details and Order Table
   - Cleaned and transformed the data in Power Query
   - Merged tables based on `Order ID`
   - Handled missing values, verified data types, and removed duplicates

2. **Data Modeling**:
   - Built relationships between tables
   - Created calculated fields using **DAX** (for KPIs like AOV)

3. **Dashboard Design**:
   - Clean layout with KPIs at the top
   - Visuals aligned by use-case (sales, profit, quantity, customer behavior)
   - Interactive slicers for better user experience

## 📂 Project Structure

- `dataset/` – Contains raw CSV files
- `E-Commerce-Sales-Dashboard /` – Screenshots of the dashboard
- `MadhavStoreDashboard.pbix` – Power BI file

## 📌 Conclusion

### 🔍 Key Insights:
- **Maharashtra** leads in total sales amount, showing strong regional performance.
- **COD (Cash on Delivery)** is the most preferred payment method (44%).
- **Clothing** is the top-selling category, contributing 63% of total quantity sold.
- **Harivansh** and **Madhav** are among the top customers in terms of purchase amount.
- **Sales and profits show seasonal variation** — June and December had negative profits.
- The dashboard provides **real-time insights** to support faster and smarter business decisions.
- Overall, the dashboard **simplifies performance monitoring** across key KPIs and segments.

### 💡 Recommendations:
- **Focus Marketing on High-Performing States**: Maharashtra and Madhya Pradesh show strong sales — doubling down on these regions may increase ROI.
- **Diversify Payment Options**: COD still leads — promotions for digital payments may reduce handling costs.
- **Expand Popular Categories**: Clothing and Electronics dominate — consider expanding product range in these segments.
- **Investigate Low-Profit Months**: Months like June and December show negative profits — review campaign spend, discount policies, or fulfillment issues during those periods.
- **Reward Loyal Customers**: High-spending customers like Harivansh and Madhav could be engaged through loyalty programs.

---
