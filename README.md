# 📊 Business Insight 360 — Power BI Dashboard

[🔗 Live Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODU5M2M2MjMtMDZlYi00ZmI4LTlkNjctNzNkYmUxZjE2NTAyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=c6318227e04035cc6654)

## 🧭 Overview
**Business Insight 360** is an end-to-end Power BI project that provides a consolidated view of business performance across sales, customers, products, and markets. It’s designed for executives and analysts to monitor KPIs, explore trends, and drill down into drivers of growth and profitability.

## 🎯 Key Questions This Dashboard Answers
- How are **Revenue**, **Profit**, and **Gross Margin %** trending over time?
- Which **markets, segments, and products** contribute most to performance?
- What are our **Top/Bottom performers** (products, customers, markets)?
- Where are we seeing **YoY growth/declines** and **variance to target**?

## 🔑 Highlights (Features)
- Executive summary with high-level KPIs and quick filters
- Trend analysis with **YoY** deltas
- **Top N** insights for products, customers, and markets
- Decomposition via cross-filtering


## 🧱 Data Model (Conceptual)
- **Fact**: Sales/Transactions (date, product, customer, market, revenue, cost, profit, discount)
- **Dimensions**: Date, Product, Customer, Market, Fiscal Year
- Star schema with few Snowflake schemas and one-to-many relationships

## 🗺️ Pages (Typical Navigation)
- **Home Page** — Information about Report and Other Page navigation to start
- **Finance Report** — Major KPIs, P&L statements with Dynamic year filter
- **Sales** — Performance Matrix
- **Marketing** — Product & Customer performance with Unit Economics
- **Supply Chain** — Forecast Accuracy with Net error Trend
- **Executive** — Accumulating all the Key metrics for one stop analysis 

## 🖼️ Screenshots 
<img width="1256" height="706" alt="image" src="https://github.com/user-attachments/assets/5bc00798-40b5-42fe-869d-14e3f4a2818c" />
<img width="967" height="548" alt="image" src="https://github.com/user-attachments/assets/7c8f0f64-8c8c-4255-a436-86c829a1401a" />
<img width="971" height="541" alt="image" src="https://github.com/user-attachments/assets/c0183e00-9992-4a33-b3f8-d67c5585c0e3" />
<img width="967" height="546" alt="image" src="https://github.com/user-attachments/assets/b16e1b6a-8ee7-4e6c-aa8f-2141fb9dc515" />
<img width="965" height="547" alt="image" src="https://github.com/user-attachments/assets/62c36b69-ace6-45e5-8fda-4bcab87f4567" />

Embed in README:
```markdown
![Overview](Screenshots/dashboard_overview.png)
```

## 🗂️ Repository Structure
```
.
├─ Business Insight 360.pbix
├─ Data/                # sample CSV/Excel or SQL scripts (if shareable)
├─ Docs/
│  └─ Data_Dictionary.md   # optional metadata documentation
├─ Screenshots/
└─ README.md
```

## 🚀 How to Use
   **View online** (no install): open the **Live Interactive Dashboard** link at the top.  
## 🔒 Data & Privacy
- The shared report is for demonstration/portfolio purposes.
- Sensitive data has been removed or anonymized (if applicable).

## ⚙️ Versioning & Tech
- Power BI Desktop
- Power Query, Star Schema modeling, Snoflake Schema modeling
- GitHub for version control  

## 📬 Contact
**Author:** Pallab Saha  

