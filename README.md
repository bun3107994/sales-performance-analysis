# 📊 Sales Performance Analysis & Forecasting

![Python](https://img.shields.io/badge/Python-3.14-blue?logo=python&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-Public-orange?logo=tableau&logoColor=white)
![Google](https://img.shields.io/badge/Google-Data%20Analytics%20Certificate-red?logo=google&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Google Data Analytics Certificate — Capstone Project**  
> A full end-to-end data analysis of 4 years of retail sales data, including cleaning, analysis, forecasting, and an interactive Tableau dashboard.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Business Task](#-business-task)
- [Dataset](#-dataset)
- [Tools Used](#-tools-used)
- [Project Structure](#-project-structure)
- [Key Findings](#-key-findings)
- [Sales Forecast](#-sales-forecast)
- [Dashboard](#-dashboard)
- [Recommendations](#-recommendations)
- [How to Run](#-how-to-run)
- [Contact](#-contact)

---

## 🎯 Project Overview

This capstone project analyzes **9,800 retail transactions** spanning **4 years (2015–2018)** to uncover sales trends, identify top-performing products and regions, and forecast future sales performance.

The project follows the **6-phase Google Data Analytics process:**

| Phase | Description |
|-------|-------------|
| **Ask** | Defined business task and key questions |
| **Prepare** | Downloaded and reviewed dataset from Kaggle |
| **Process** | Cleaned data, fixed dates, created new columns |
| **Analyze** | Explored trends by category, region, time, and product |
| **Share** | Built Python visualizations and Tableau dashboard |
| **Act** | Formulated 4 data-driven business recommendations |

---

## 💼 Business Task

> *Analyze historical retail sales data to identify top-performing products and regions, uncover seasonal trends, and forecast future sales to support data-driven business decisions.*

### Key Questions:
1. Which product categories and regions generate the most sales?
2. What monthly and seasonal trends exist in sales performance?
3. What are the projected sales for the next 6 months?

---

## 📂 Dataset

| Attribute | Details |
|-----------|---------|
| **Source** | [Kaggle — Sales Forecasting Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting) |
| **Period** | January 2015 — December 2018 |
| **Records** | 9,800 rows |
| **Fields** | 18 columns (19 after feature engineering) |
| **Missing Data** | 11 missing postal codes (not used in analysis) |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Python — Pandas** | Data loading, cleaning & transformation |
| **Python — Matplotlib** | Static data visualizations |
| **Python — Scikit-learn** | Linear Regression forecasting model |
| **Tableau Public** | Interactive dashboard |
| **Jupyter Notebooks** | Development & documentation |
| **GitHub** | Version control & portfolio hosting |

---

## 📁 Project Structure

```
sales-performance-analysis/
│
├── 📁 data/
│   ├── raw/
│   │   └── train.csv                         # Original dataset
│   └── cleaned/
│       ├── clean_sales.csv                   # Cleaned CSV
│       └── clean_sales.xlsx                  # Excel for Tableau
│
├── 📁 notebooks/
│   ├── 01_exploration.ipynb                  # Data exploration
│   ├── 02_cleaning.ipynb                     # Data cleaning
│   ├── 03_analysis.ipynb                     # Sales analysis
│   └── 04_forecast.ipynb                     # Sales forecasting
│
├── 📁 visualizations/
│   ├── 01_sales_by_category.png
│   ├── 02_sales_by_region.png
│   ├── 03_monthly_sales_trend.png
│   ├── 04_top10_products.png
│   └── 05_sales_forecast.png
│
├── 📁 dashboard/
│   └── tableau_link.txt                      # Tableau Public link
│
├── 📁 report/
│   └── case_study_report.docx                # Full case study
│
└── 📄 README.md
```

---

## 📊 Key Findings

### 1. Sales by Product Category
| Rank | Category | Total Sales | % of Total |
|------|----------|------------|------------|
| 🥇 1 | Technology | $827,456 | 36.6% |
| 🥈 2 | Furniture | $728,659 | 32.2% |
| 🥉 3 | Office Supplies | $705,422 | 31.2% |

> **Technology leads all categories** — 16% higher than second-ranked Furniture.

---

### 2. Sales by Region
| Rank | Region | Total Sales | Insight |
|------|--------|------------|---------|
| 1 | West | $710,220 | Top performer |
| 2 | East | $669,519 | Strong market |
| 3 | Central | $492,647 | Growth potential |
| 4 | **South** | **$389,151** | **⚠️ Underperforming — 45% below West** |

---

### 3. Monthly & Seasonal Trends
- 📈 **Consistent year-over-year growth** from 2015 to 2018
- 🎄 **Q4 (Oct–Dec) spikes every year** — strongest sales period
- 🏆 **November 2018** = all-time best month at ~$120,000
- 📉 **Q1 (Jan–Feb) consistently weakest** — opportunity for promotions

---

### 4. Top 5 Products
| Rank | Product | Sales |
|------|---------|-------|
| 1 | Canon imageCLASS 2200 Advanced Copier | $61,600 |
| 2 | Fellowes PB500 Electric Punch Machine | $27,453 |
| 3 | Cisco TelePresence System EX90 | $22,638 |
| 4 | HON 5400 Series Task Chairs | $21,871 |
| 5 | GBC DocuBind TL300 Electric Binding | $19,823 |

---

## 🔮 Sales Forecast

Using **Linear Regression** trained on 48 months of historical data:

- **Monthly growth trend:** $888 per month
- **Model:** Scikit-learn LinearRegression

| Month | Forecasted Sales |
|-------|----------------|
| January 2019 | $68,879 |
| February 2019 | $69,767 |
| March 2019 | $70,656 |
| April 2019 | $71,544 |
| May 2019 | $72,432 |
| June 2019 | $73,321 |

---

## 📈 Dashboard

> 🔗 **[View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/alhagie.kijera/viz/SalesPerformanceAnalysisGoogleCapstoneproject/SalesPerformanceAnalysisDashboard?publish=yes)**

The dashboard includes:
- 📊 Sales by Category (bar chart)
- 🗺️ Sales by State (map chart)
- 📈 Monthly Sales Trend (line chart)
- 🏆 Top 10 Products (horizontal bar)
- 📍 Sales by Region (bar chart)
- 🎛️ Interactive Year & Segment filters
- KPIs

---

## 💡 Recommendations

| # | Recommendation | Impact |
|---|---------------|--------|
| 1 | **Invest in South Region** — currently 45% below West | High |
| 2 | **Capitalize on Q4** — plan promotions & inventory ahead of October | High |
| 3 | **Expand Technology portfolio** — add accessories & warranties | Medium |
| 4 | **Address Q1 dip** — launch January/February bundle promotions | Medium |

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/sales-performance-analysis.git
cd sales-performance-analysis

# 2. Install required libraries
pip install pandas matplotlib scikit-learn openpyxl jupyter

# 3. Open Jupyter Notebook
jupyter notebook

# 4. Run notebooks in order:
#    01_exploration.ipynb
#    02_cleaning.ipynb
#    03_analysis.ipynb
#    04_forecast.ipynb
```

---

## 📬 Contact

**Alhagie Kijera**  
📧 bunkijera7@gmail.com 
💼 
🌐 

---

*Completed as part of the Google Data Analytics Certificate Program — 2026*
