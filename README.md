# 📊 NYKAA Performance Dashboard – Power BI Project

## 📌 Project Overview

The NYKAA Performance Dashboard is an interactive Power BI project designed to analyze marketing campaign performance across different channels and campaign types. The dashboard helps in tracking revenue, cost, profit, conversions, ROI, and click-through rate to evaluate marketing effectiveness and support data-driven decision making.

This project demonstrates data visualization, data analysis, and DAX skills using Power BI.

---

## 📂 Dataset Information

The dataset used in this project contains marketing campaign data with the following columns:

* Campaign Type
* Channel
* Date
* Revenue
* Cost
* Profit
* Conversions
* Clicks
* Impressions

---

## 📊 Dashboard Features

The Power BI dashboard includes the following visualizations:

* KPI Cards:

  * Total Revenue
  * Total Cost
  * Total Profit
  * Total Conversions
  * Average ROI
  * Click-Through Rate (CTR)

* Charts:

  * Revenue by Campaign Type (Column Chart)
  * Revenue by Channel (Bar Chart)
  * Revenue Trend Over Time (Line Chart)
  * Conversions by Campaign Type (Donut Chart)
  * ROI by Campaign Type (Column Chart)

* Slicers:

  * Campaign Type
  * Channel
  * Date

---

## 🧮 DAX Measures Used

The following DAX measures were created in this project:

```DAX
Total Revenue = SUM(Data[Revenue])

Total Cost = SUM(Data[Cost])

Total Profit = [Total Revenue] - [Total Cost]

Total Conversions = SUM(Data[Conversions])

Avg ROI = DIVIDE([Total Profit], [Total Cost], 0) * 100

CTR = DIVIDE(SUM(Data[Clicks]), SUM(Data[Impressions]), 0) * 100
```

---

## 🎯 Key Insights

* Social media campaigns generated higher revenue compared to other campaign types.
* Email campaigns showed strong conversion performance.
* Some campaigns had high costs but lower ROI.
* ROI and CTR varied significantly across different marketing channels.
* Revenue trend analysis helped identify peak performance periods.

---

## 🛠 Tools & Technologies Used

* Power BI
* DAX (Data Analysis Expressions)
* Data Visualization
* Data Cleaning
* Excel / CSV Dataset

---

## 📷 Dashboard Preview

(Add dashboard screenshot here)

---

## 🚀 How to Use This Project

1. Download the `.pbix` file from this repository.
2. Open the file in Power BI Desktop.
3. Explore the dashboard using slicers and filters.
4. Review DAX measures and visualizations used in the report.

---

## 📁 Project Files

* NYKAA Performance Dashboard.pbix
* Dataset (Excel/CSV)
* Dashboard Screenshot
* <img width="835" height="493" alt="image" src="https://github.com/user-attachments/assets/701685cb-0489-446f-9d89-6db52afc486f" />

* README.md

---

## 👩‍💻 Author

**Payal Mitra**
Aspiring Data Analyst | Power BI | SQL | Python

This project is part of my Data Analytics Portfolio.
