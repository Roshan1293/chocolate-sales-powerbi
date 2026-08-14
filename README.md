# 🍫 Chocolate Sales Analysis - Excel Dashboard

[![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)]
[![Data Visualization](https://img.shields.io/badge/Skill-Data%20Visualization-FF9900?style=for-the-badge&logo=databricks&logoColor=white)]
[![Pivot Tables](https://img.shields.io/badge/Feature-Pivot%20Tables%20%2B%20Slicers-0078D4?style=for-the-badge)]

Interactive dashboard built in **Microsoft Excel** analyzing chocolate product sales across multiple countries from **January 2025 to April 2026**.


    ![Chocolate Sales Dashboard](chocolate-dashboard.png)
## 📊 Project Overview

| Metric | Value |
| --- | --- |
| **💰 Total Sales Amount** | $21.53 Million |
| **📦 Total Boxes Sold** | ~2 Million |
| **📅 Date Range** | 02 Jan 2026 – 30 Apr 2026 |
| **📝 Records** | 4,998 transactions |

### 📈 Key Visuals Created in Excel

1. **📉 Monthly Revenue Trend**  
   Area chart showing monthly sales performance from Jan 2025 – Mar 2026.
2. **🏆 Top Products by Revenue**  
   Horizontal bar chart. Top performers: Orange Choco, 99% Dark & Pure, Drinking Coco, Peanut Butter Cubes.
3. **🌍 Revenue by Country**  
   Donut chart showing country-wise share:  
   - 🇬🇧 UK – 26.18%  
   - 🇺🇸 USA – 22.93%  
   - 🇮🇳 India – 16.63%  
   - 🇨🇦 Canada, 🇦🇺 Australia, 🇳🇿 New Zealand
4. **👨‍💼 Sales Person Performance**  
   Table ranking top sales reps. Brien Boise leading at ~$1.67M.

---

## 🗂️ Project Structure

---

## 📚 Data Dictionary

| Column | Description | Type |
| --- | --- | --- |
| Sales Person | Name of the sales representative | Text |
| Product | Chocolate product name | Text |
| Country | Sales country | Text |
| Date | Order date | Date |
| Amount | Sales amount | Decimal |
| Boxes | Number of boxes sold | Integer |
| Order Status | Delivered / Shipped / Cancelled / Placed | Text |

**Order Status distribution:**
- ✅ Delivered: 4,138
- 🚚 Shipped: 433 
- ❌ Cancelled: 227
- 🛒 Placed: 200

---

## 🛠️ How to Recreate the Dashboard in Excel

1. Open **Microsoft Excel**.
2. Go to `Data > Get Data > From File` → select `data/chocolate_sales_data.csv`.
3. Load data into a Table and create a **Pivot Table**.
4. Insert the following visuals:
   - KPI Cards: `SUM of Amount`, `SUM of Boxes`
   - Area Chart: `Month of Date` vs `SUM of Amount`
   - Bar Chart: `Product` vs `SUM of Amount`
   - Donut Chart: `Country` vs `SUM of Amount`
   - Table: `Sales Person` + `SUM of Amount`
5. Add **Slicers** for Date and Country to make it interactive.

---

## 💡 Key Insights

- 🥇 Brien Boise is one of the top performers.
- 🍊 Orange Choco and dark chocolate variants generate the highest revenue.
- 🌍 UK and USA dominate the market share.
- 📈 Clear seasonal peaks are visible in the monthly revenue chart.

---

## 🧰 Tools Used

- **Microsoft Excel** - Data Cleaning, Pivot Tables, Charts, Slicers
- **Excel Data Visualization** - Area Chart, Bar Chart, Donut Chart

**Data period:** January 2025 – April 2026
