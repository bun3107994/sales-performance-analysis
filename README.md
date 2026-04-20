---

## 📊 Key Findings

### 1. Sales by Product Category
| Rank | Category | Total Sales | % of Total |
|------|----------|------------|------------|
| 🥇 1 | Technology | $827,456 | 36.6% |
| 🥈 2 | Furniture | $728,659 | 32.2% |
| 🥉 3 | Office Supplies | $705,422 | 31.2% |

> **Technology leads all categories** — 16% higher than Furniture.

---

### 2. Sales by Region
| Rank | Region | Total Sales | Insight |
|------|--------|------------|---------|
| 1 | West | $710,220 | Top performer |
| 2 | East | $669,519 | Strong market |
| 3 | Central | $492,647 | Growth potential |
| 4 | **South** | **$389,151** | **⚠️ 45% below West** |

---

### 3. Monthly & Seasonal Trends
- 📈 Consistent year-over-year growth from 2015 to 2018
- 🎄 Q4 (Oct–Dec) spikes every year — strongest sales period
- 🏆 November 2018 = all-time best month at ~$120,000
- 📉 Q1 (Jan–Feb) consistently weakest — opportunity for promotions

---

### 4. Top 10 Products
| Rank | Product | Sales |
|------|---------|-------|
| 1 | Canon imageCLASS 2200 Advanced Copier | $61,600 |
| 2 | Fellowes PB500 Electric Punch Machine | $27,453 |
| 3 | Cisco TelePresence System EX90 | $22,638 |
| 4 | HON 5400 Series Task Chairs | $21,871 |
| 5 | GBC DocuBind TL300 Electric Binding | $19,823 |
| 6 | GBC Ibimaster 500 ProClick System | $19,025 |
| 7 | Hewlett Packard LaserJet 3310 Copier | $18,840 |
| 8 | HP Designjet T520 Inkjet Printer | $18,375 |
| 9 | GBC DocuBind P400 Electric Binding | $17,965 |
| 10 | High Speed Electric Letter Opener | $17,030 |

---

## 🔮 Sales Forecast

Using **Linear Regression** trained on 48 months of data:

- **Monthly growth trend:** $888 per month
- **Tool:** Python Scikit-learn

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
- 🎛️ Interactive Year & Category filters
- 📌 KPI Summary (Total Orders, Total Sales, Avg Order Value)

---

## 💡 Recommendations

| # | Recommendation | Impact |
|---|---------------|--------|
| 1 | **Invest in South Region** — 45% below West | High |
| 2 | **Capitalize on Q4** — plan promotions ahead of October | High |
| 3 | **Expand Technology portfolio** — add accessories & warranties | Medium |
| 4 | **Address Q1 dip** — launch January/February bundle deals | Medium |

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/bun3107994/sales-performance-analysis.git
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
💼 [LinkedIn](https://www.linkedin.com/in/alhagiekijera)  
📊 [Tableau Public](https://public.tableau.com/app/profile/alhagie.kijera)

---

*Completed as part of the Google Data Analytics Certificate Program — April 2026*
