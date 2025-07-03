# 🧾 Vendor Performance Analysis  

## 📊 Project Overview

This project provides a deep-dive analysis into vendor performance using both Python (for data cleaning and exploration) and Power BI (for visualization). It’s designed to uncover insights that support data-driven decisions in retail procurement and inventory management.

## 🎯 Business Problem

Retail and wholesale businesses often face inefficiencies due to:
- Poor vendor performance tracking
- High inventory holding costs
- Limited visibility into profitability per vendor
- Pricing and ordering inefficiencies

This project addresses these pain points with data-backed insights and dashboards.

## ✅ Objectives

- Identify underperforming vendors and brands
- Analyze how bulk purchasing affects unit costs
- Evaluate inventory turnover and its effect on profitability
- Measure statistical differences between vendor groups
- Deliver interactive reports for stakeholder use

## 🔍 Key Insights

- 📉 **Profit Leakage**: Found infinite negative margins due to discounts or missing revenue.
- 💼 **Vendor Concentration**: Top 10 vendors represent 65.69% of total purchase volume — risky.
- 💸 **Economies of Scale**: Bulk buying yields 72% lower unit prices on average.
- 🛑 **Inventory Inefficiencies**: $2.71M of inventory still unsold.
- 📊 **Significant Differences**: Profitability between vendors statistically validated.

## 🧠 Actionable Recommendations

- Reprice/promote high-margin, low-volume items
- Reduce vendor dependence by diversifying procurement
- Leverage bulk purchasing for better cost control
- Address unsold stock via clearance or better planning
- Improve vendor relations with poor performance metrics

## 🗂 Project Structure

## Project Structure
```text
vendor-performance-analysis/
│
├── data/                    # drive link for full data : https://drive.google.com/drive/folders/1xSpIhQw73KCVSQgR4Y_yYYCJX5TF8YSl?usp=sharing
│   ├── sales_sample.csv
│   └── ...
│
├── notebooks/               # Jupyter analysis
│   ├── Exploratory_Data_Analysis.ipynb
│   └── Vendor_Performance_Analysis.ipynb
│
├── scripts/                 # Re‑usable Python modules
│   ├── ingestion_db.py
│   └── get_vendor_summary.py
│
├── reports/                 # Final deliverables
│   ├── Vendor_Performance_Report.pdf
│   └── vendor_performance.pbix   
│
└── README.md

## 🛠 Tools & Technologies

- **Python** – pandas, seaborn, matplotlib
- **Power BI** – Interactive dashboard creation
- **Jupyter Notebook** – Exploratory data analysis
- **SQL / DAX** – Backend queries and metrics
- **Excel/CSV** – Raw data source

## 📸 Sample Visuals

![Vendor Dashboard](dashboard/Vender%20performance%20dashboard.png)

## 🚀 How to Run This Project

1. **Python Analysis**
   - Open Jupyter notebooks inside `/notebooks`
   - Run `Vendor Performance Analysis.ipynb` or `Exploratory Data Analysis.ipynb`

2. **Power BI Dashboard**
   - Open `vendor_performance.pbix` in Power BI Desktop
   - Interact with filters and visuals

3. **Data Files**
   - All located in `data/` folder in `.csv` format

 