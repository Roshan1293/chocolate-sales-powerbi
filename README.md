# Chocolate Sales Analysis - Power BI Report

Interactive Power BI dashboard analyzing chocolate product sales across multiple countries from **January 2025 to September 2026**.

![Power BI Report](images/powerbi-report.jpg)

## Report Overview

| Metric                | Value                          |
|-----------------------|--------------------------------|
| Total Sales Amount    | $21.53 Million                 |
| Total Boxes Sold      | ~2 Million                     |
| Date Range            | 02 Jan 2025 – 30 Apr 2026      |
| Records               | 4,998 transactions             |

### Key Visuals

1. **How much money we make every month?**  
   Area chart showing monthly revenue trends (Jan 2025 – Mar 2026).

2. **Sum of Amount by Product**  
   Horizontal bar chart ranking products by revenue.  
   Top performers: Orange Choco, 99% Dark & Pure, Drinking Coco, Peanut Butter Cubes.

3. **Sum of Amount by Country**  
   Donut chart showing revenue share:  
   - UK – 26.18%  
   - USA – 22.93%  
   - India – 16.63%  
   - Canada, Australia, New Zealand

4. **Sales Person Performance**  
   Table of top sales representatives by total amount (e.g. Brien Boise leading at ~1.67M).

---

## Project Structure

```
chocolate-sales-powerbi/
├── data/
│   ├── chocolate_sales_data.csv           # Clean CSV version
│   └── sample-chocolate-sales-data-1.xlsx # Original Excel source
├── images/
│   ├── powerbi-report-desktop.jpg
│   └── powerbi-report-filtered.jpg
└── README.md
```

---

## Data Dictionary

| Column         | Description                              | Type    |
|----------------|------------------------------------------|---------|
| Sales Person   | Name of the sales representative         | Text    |
| Product        | Chocolate product name                     | Text    |
| Country        | Sales country                            | Text    |
| Date           | Order date                               | Date    |
| Amount         | Sales amount                             | Decimal |
| Boxes          | Number of boxes sold                     | Integer |
| Order Status   | Delivered / Shipped / Cancelled / Placed | Text    |

**Order Status distribution:**
- Delivered: 4,138
- Shipped: 433
- Cancelled: 227
- Placed: 200

---

## How to Recreate the Report in Power BI

1. Open **Power BI Desktop**.
2. Get Data → Excel or CSV → select `data/chocolate_sales_data.csv`.
3. Load the data.
4. Create the following visuals:
   - Card: Sum of Amount
   - Card: Sum of Boxes
   - Area Chart: Date (Month) vs Sum of Amount
   - Bar Chart: Product vs Sum of Amount
   - Donut Chart: Country vs Sum of Amount
   - Table: Sales Person + Sum of Amount
5. Add a Date slicer (02/01/2025 to 30/04/2026).

---

## Sample Insights

- Brien Boise is one of the top performers.
- Orange Choco and dark chocolate variants generate the highest revenue.
- UK and USA dominate the market share.
- Clear seasonal peaks are visible in the monthly revenue chart.

---

## Tools Used

- Microsoft Power BI Desktop
- Excel / CSV
- Data period: January 2025 – September 2026

---

**Created for GitHub portfolio**
