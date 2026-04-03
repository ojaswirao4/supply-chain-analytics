# 🏭 Supply Chain Intelligence Platform

> End-to-end data analytics platform built with Apache Spark, dbt, Prophet ML, SQL and Power BI — modelled after real Big 4 consulting deliverables.

## 📊 Dashboard
[→ View Power BI Dashboard PDF](supply_chain_project.pdf)

## 🏗️ Architecture
Raw CSV → PySpark (Bronze/Silver/Gold) → SQL Analysis → Prophet ML → Power BI Dashboard

## 📈 Key Results
- Processed **1M+ retail transactions** using Apache Spark distributed computing
- Built **Bronze/Silver/Gold medallion architecture** for data lake management
- Discovered **37% revenue surge in September** through SQL window function analysis
- Demand forecasting model using **Facebook Prophet** with yearly seasonality
- **4-page executive Power BI dashboard** with slicers and KPI cards
- SQL analysis revealing **November as peak revenue month** (Q4 holiday surge)
- Delivered **multi-sheet Excel workbook** with MoM growth and customer retention insights

## 🛠️ Tech Stack
| Layer | Technology |
|-------|-----------|
| Distributed Processing | Apache Spark / PySpark |
| Data Lake | Bronze / Silver / Gold Architecture |
| SQL Analysis | DuckDB (window functions, LAG, CTEs) |
| ML Forecasting | Facebook Prophet |
| Business Intelligence | Power BI Desktop |
| Data Storage | Parquet + CSV |
| Notebook | Google Colab |

## 📁 Repository Structure
supply-chain-analytics/
│
├── supply_chain_analytics.ipynb  ← Main Colab notebook (Spark + ML)
├── supply_chain_project.pbix     ← Power BI dashboard file
├── supply_chain_project.pdf      ← Dashboard PDF export
├── gold_sales.csv                ← Gold layer aggregated data
├── sql_analysis.xlsx             ← SQL analysis (4 sheets)
└── forecast_data.csv             ← Prophet ML forecast output

## 🔍 Key Business Insights
1. **UK dominates revenue** — £15M+ out of £17.74M total (85% concentration risk)
2. **Q4 seasonal surge** — Revenue jumps 37% from August to September every year
3. **November is peak month** — Consistently highest revenue across all years
4. **Customer growth** — Unique customers grew from 955 (2009) to 12,476 (2010)
5. **Revenue per customer declining** — From £719 (2009) to £685 (2011) — retention opportunity

## 📊 Dashboard Pages
- **Page 1 — Executive Summary:** KPI cards, revenue trend, country analysis
- **Page 2 — Growth Analysis:** MoM growth %, best performing months
- **Page 3 — Customer Intelligence:** Customer behaviour and retention metrics
- **Page 4 — Demand Forecast:** 6-month Prophet ML forecast

## 💼 Business Recommendations
1. **Stock up inventory by August** to capture Q4 surge
2. **Diversify beyond UK** to reduce geographic revenue concentration
3. **Launch retention program** to reverse declining revenue per customer trend
4. **Target September promotions** to amplify natural demand surge

## 🚀 How to Run
1. Open `supply_chain_analytics.ipynb` in Google Colab
2. Upload `online_retail_II.csv` when prompted
3. Run all cells top to bottom
4. Open `supply_chain_project.pbix` in Power BI Desktop to view dashboard

## 📋 Resume Bullets
- Engineered Bronze/Silver/Gold data lakehouse using Apache Spark/PySpark processing 1M+ retail transactions
- Performed advanced SQL analysis (LAG, window functions) uncovering 37% Q4 revenue surge and November peak demand
- Built Facebook Prophet demand forecasting model capturing holiday retail seasonality patterns
- Delivered 4-page executive Power BI dashboard with KPI cards, slicers and country-level drill-through analysis
- Packaged findings into multi-sheet Excel workbook replicating Big 4 client deliverable format
