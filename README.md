# 🧾 Vendor Performance Analysis – Power BI & Python Project

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

```
Projects/
├── data/                       # Raw CSV files
│   ├── sales.csv
│   ├── purchases.csv
│   └── ...
├── notebooks/                 # Analysis and reports
│   ├── Vendor Performance Analysis.ipynb
│   ├── Exploratory Data Analysis.ipynb
│   ├── get_vendor_summary.py
│   ├── ingestion_db.py
│   └── Vendor Performance Report.pdf
├── images/                    # Dashboard screenshots
│   └── Vender performance dashboard.png
├── vendor_performance.pbix    # Power BI report
└── README.md
```

## 🛠 Tools & Technologies

- **Python** – pandas, seaborn, matplotlib
- **Power BI** – Interactive dashboard creation
- **Jupyter Notebook** – Exploratory data analysis
- **SQL / DAX** – Backend queries and metrics
- **Excel/CSV** – Raw data source

## 📸 Sample Visuals

![Vendor Dashboard](images/Vender%20performance%20dashboard.png)

## 🚀 How to Run This Project

1. **Python Analysis**
   - Open Jupyter notebooks inside `/notebooks`
   - Run `Vendor Performance Analysis.ipynb` or `Exploratory Data Analysis.ipynb`

2. **Power BI Dashboard**
   - Open `vendor_performance.pbix` in Power BI Desktop
   - Interact with filters and visuals

3. **Data Files**
   - All located in `data/` folder in `.csv` format

## 📬 Contact

**Santhosh Kumar Errolla**  
📧 santhoshkumarerrolla@gmail.com  
📱 +1 (314) 629-8490  
🔗 [LinkedIn](www.linkedin.com/in/santhosh-kumar570)

---

> 📝 _This project is for educational and portfolio purposes. Data is anonymized or simulated._
