# sales-performance-dashboard
An end-to-end sales analytics project that transforms messy, inconsistent records into a clean, interactive Power BI dashboard, giving sales, marketing, and product teams a clear view of revenue, profit, and performance across channels, regions, and product lines.
## 🏆 Key Results

| Metric | Value |
|---|---|
| Total Revenue | £4.97M |
| Total Profit | £2.25M |
| Average Order Value (AOV) | £414.48 |
| Profit Margin | 45.24% |

> **£2.25M profit generated across 4 sales channels, multiple regions, and a full product catalogue — from a single, unified data model.**

---
## 🔧 What Was Built

### Data Transformation
- Resolved duplicates, aligned product IDs, and standardised regional and channel naming conventions
- Unified scattered sales records across channels, regions, and product lines into a single coherent model
- Applied Power Query (M) transformations: type casting, null handling, column renaming, and date table creation

### Data Modelling
- Built a star schema with a central fact table and supporting dimension tables (Product, Region, Channel, Date)
- Established relationships optimised for cross-filtering across all slicers and visuals

### DAX Measures
Custom DAX measures created for:
- **Total Revenue** — `SUM(Sales[Revenue])`
- **Total Profit** — `SUM(Sales[Profit])`
- **AOV (Average Order Value)** — `DIVIDE([Total Revenue], [Order Count])`
- **Profit Margin** — `DIVIDE([Total Profit], [Total Revenue])`
- **Channel Contribution %** — revenue share per sales channel
- **Month-over-Month Revenue & Profit trends**

### Dashboard Design
- KPI summary cards: Total Revenue, Total Profit, AOV, and Profit Margin
- Monthly trend line: revenue and profit across all 12 months
- Channel comparison: Website, Instagram Shop, Facebook Shop, and Email Campaign
- Regional performance breakdown with profitability differences highlighted
- Top product analysis: leading SKUs by both revenue and profit (P0057, P0027, P0026)
- Interactive slicers for dynamic filtering by channel, region, product, and month

---

## 💡 Business Questions This Dashboard Answers

- Which months generate the highest revenue and profit?
- How do sales channels compare in total revenue contribution?
- Which regions are performing strongest — and where do growth opportunities exist?
- Which products are the top revenue and profit drivers?
- How does profit margin trend across the year?
- Where should marketing and sales efforts be focused to maximise returns?

---

## 📈 Key Insights

- **Revenue is evenly distributed** across Website, Instagram Shop, Facebook Shop, and Email Campaign — no single channel dominates, suggesting a healthy multi-channel mix
- **July and August are the strongest revenue months**, with clear mid-year peaks that present an opportunity for targeted campaign planning
- **Top products P0057, P0027, and P0026** consistently lead in both revenue and profit — prime candidates for increased inventory and marketing investment
- **EU and Africa regions** show strong performance, with notable differences in profitability that warrant region-specific strategy
- **45.24% profit margin** indicates strong cost efficiency across the product catalogue

---

## 🛠 Tools & Technologies

| Tool | Usage |
|---|---|
| Power BI Desktop | Dashboard design and publishing |
| DAX | Custom KPI and trend measures |
| Power Query (M) | Data cleaning and transformation |
| CSV / Excel | Raw data source |
| Data modelling | Star schema with dimension/fact tables |

---

## 📄 Licence

This project is for portfolio and educational purposes. Data has been anonymised and does not represent any real organisation.

---

## 🙋 Author

**Akinlolu Oyetakin**  
Data and Business Intelligence Analyst  


---

*Built with Power BI · DAX · Power Query*
