# 📊 Superstore Sales Analysis — Power BI Dashboard

An interactive Power BI dashboard analyzing sales and profit performance for a retail superstore, built to identify profitability gaps, seasonal trends, and regional opportunities.

## 📁 Dataset

The **Superstore Sales** dataset — a widely used retail sample dataset containing order-level records with the following key fields:

- **Order Date, Region, State** — time and geography
- **Category, Sub-Category, Product Name** — product hierarchy
- **Sales, Profit** — core performance metrics

Source: [Kaggle - Sales Forecasting Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)

## 🛠️ Tools Used

- **Power BI Desktop** — data modeling, visualization, and dashboard design
- Native Power BI aggregations (Sum, Top N filtering) — no custom DAX measures required

## 📈 Dashboard Overview

A single-page interactive report with **11 visuals**:

| Visual | Purpose |
|---|---|
| Gauge — Total Sales | Actual sales vs. target (2.5M, range 1.5M–3M) |
| Gauge — Total Profit | Actual profit vs. target (275K, range 200K–350K) |
| Pie Chart — Sales by Category | Revenue share across Technology, Furniture, Office Supplies |
| Pie Chart — Profit by Category | Profit share across the same categories |
| Column Chart — Top 5 Sub-Categories | Best-selling sub-categories by sales |
| Column Chart — Bottom 5 Sub-Categories | Weakest-selling sub-categories by sales |
| Stacked Area Chart | Monthly Sales and Profit trend |
| Map (Bubble) | Sales concentration by U.S. state |
| Smart Narrative Textbox | Auto-generated natural-language insights |
| Slicers | Filter by Category and Region |

## 🔍 Key Insights

- **Technology** leads in both sales and profit (~51% of profit share).
- **Furniture** ranks second in sales but yields only ~6% profit — a margin problem, not a demand problem.
- **Office Supplies** has the lowest sales but a strong ~43% profit contribution.
- **Q4 (Oct–Dec)** shows the strongest sales-to-profit margin, suggesting a seasonal growth opportunity.
- **California and New York** are the top-performing states by sales volume.

## ✅ Recommendations

1. Reassess Furniture pricing/costs to improve margins despite strong sales volume.
2. Double down on top-performing sub-categories; reevaluate or discontinue the bottom 5.
3. Build a targeted Q4 sales strategy to capitalize on peak-margin season.
4. Direct marketing spend toward high-potential, currently underperforming states.

## 📂 Files

- `SalesAnalysis.pbix` — Power BI report file
- `AnalysisWriteup.md` — Written analysis and recommendations
- `README.md` — This file

## ⚠️ Disclaimer

This analysis is exploratory and intended to support, not replace, a comprehensive business strategy.
