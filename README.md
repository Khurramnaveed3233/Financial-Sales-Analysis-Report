#  Financial Sales Analysis Report: 2013–2014 

> **Role:** Data Analyst | **Tools:** Power BI · DAX · Power Query · Excel | **Domain:** FMCG · Retail · Sales Analytics


![Financial Sales Analysis](https://github.com/user-attachments/assets/b1e7e468-0bdf-465d-835d-b2dcd331f2d2)

---

##  Project Overview

Delivered a comprehensive **Power BI sales analysis dashboard** covering $128M in gross sales across multiple product segments, geographies, and discount structures for 2013–2014. The report simulates the work of a **Sales or Business Analyst in the FMCG sector** — providing stakeholders with clear visibility into product profitability, discount impact, and segment performance to drive smarter pricing and marketing decisions.

---

##  Business Problem

Sales leadership lacked structured visibility into:

- How **discounts were affecting product profitability** across the portfolio
- Which **products and segments** were truly driving profit vs just volume
- Where **geographic sales concentration** was creating over-reliance risk
- Which segments required **repositioning or phase-out planning**
- How to **align inventory and marketing** with actual demand patterns

---

## 📊 Key KPIs

| Metric | Value |
|---|---|
| Gross Sales | $128M |
| Total Net Sales | $119M |
| Total Profit | $17M |
| Units Sold | 1.1M |
| Top Profit Product | Paseo — $5M (28.4% of total profit) |
| Highest Discount Product | Velo — 28.3% of total discount spend |
| Top Segment Revenue | $53M |
| Lowest Segment Revenue | $2M |

---

## 🔍 Key Findings

### Sales by Segment
- **Top segment generates $53M** — followed by $42M and $20M segments
- Bottom segments generate just **$2M** — indicating niche or low-impact markets requiring review
- Clear **segment performance disparity** — top 3 segments dominate while bottom segments underperform

### Product Profitability
- **Paseo leads profit** at $5M (28.4% of total) — strongest candidate for increased marketing investment
- **Carretera** contributes $3M — second highest profit with strong margin potential
- **Montana and VTT** each contribute $2M — solid mid-tier performers

### Discount Analysis
| Product | Discount Share |
|---|---|
| Velo | 28.3% — highest discount receiver |
| Amarilla | 17.1% |
| Montana | 15.8% |

- **Velo receives the most discounting but returns disproportionately low profit** — discount-to-margin ratio requires immediate review
- High discounting is eroding margins without generating proportional revenue uplift

### Units Sold by Product
- Highest-selling product moved **0.17M units** — closely followed by competitors at 0.15–0.16M
- **Volume is evenly distributed** — profitability differences are driven by pricing and discounting, not volume alone

### Geographic Performance
- **North America and Europe** are the dominant markets
- Geographic concentration creates over-reliance risk — expansion into underrepresented markets is a growth opportunity

---

##  Strategic Recommendations

| Area | Recommendation |
|---|---|
| Discount Policy | Review and reduce discounting on Velo — high discount, low profit return |
| Product Strategy | Increase marketing investment in Paseo and Carretera — highest profit contributors |
| Segment Strategy | Evaluate bottom segments ($2M) for targeted promotions, rebranding, or phase-out |
| Market Expansion | Use country-level data to identify and enter underserved markets |
| Inventory Planning | Align stock levels with high-selling SKUs to reduce overstock on low performers |
| Reporting Cadence | Adopt this dashboard as a **recurring monthly sales health check** for leadership |

---

## 🛠️ Technical Approach

### Power BI
- **Star schema** data model connecting products, segments, geographies, and time dimensions
- **DAX measures** for gross sales, net sales, profit margin, discount share, and segment contribution
- **Segment revenue waterfall** showing descending performance from $56M → $46M → $21M → $2M
- **Geospatial map visual** for country-level sales distribution
- **Discount vs profit comparison** charts for product-level margin analysis
- **Interactive slicers** for year, product, segment, and country filtering

### Power Query
- ETL pipeline for data cleaning and transformation from CSV/Excel source
- Handling null values, data type standardization, and discount field normalization
- Year and segment dimension table creation for accurate filtering

---

##  Dashboard Visuals

| Visual | Business Question Answered |
|---|---|
| Sales by Segment | Which segments drive the most revenue? |
| Units Sold by Product | Which products move the most volume? |
| Discounts by Product | Which products receive the most discounting? |
| Profit by Product | Which products actually generate the most profit? |
| Units Sold by Country | Where are our strongest and weakest geographic markets? |
| Gross Sales Trend by Segment | How does revenue concentrate across the segment hierarchy? |

---

##  Repository Structure
```
📂 Financial-Sales-Analysis-Report
├── 📊 FinancialSales_Dashboard.pbix    — Interactive Power BI dashboard
├── 📄 SalesData_2013_2014.csv          — Simulated FMCG sales dataset
├── 🖼️  Financial Sales Analysis Dashboard.jpg — Dashboard preview
└── 📄 README.md                        — Project documentation
```

---


## 👤 About

**Khurram Naveed** — Data Analyst specializing in Power BI, SQL, and business intelligence.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/khurramnaveed3233)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)](https://github.com/Khurramnaveed3233)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:khurramnaveed4545@gmail.com)

---

> 💼 *This project demonstrates real-world FMCG sales analysis techniques — using Power BI and DAX to translate $128M in sales data into clear pricing strategy, discount optimization, and product portfolio recommendations that directly impact profitability.*

---

⭐ *If you found this useful, feel free to fork, star, or suggest improvements.*
