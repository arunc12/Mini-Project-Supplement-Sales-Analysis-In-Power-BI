# Mini-Project-Supplement-Sales-Analysis-In-Power-BI
📊 Power BI dashboard on 4,385 rows of supplement sales data (Jan 2020 – Mar 2025) | 16 products across USA, UK &amp; Canada on iHerb, Amazon &amp; Walmart | 10 categories | Total net revenue $19.87M across 658,478 units sold | DAX KPIs, cross-filtering, drill-through &amp; interactive map visual | 5-year forecast: ~$6M by 2030 at ~10% CAGR | Arun 📈
# Supplement Sales Analytics — Power BI Dashboard

Interactive enterprise BI dashboard built on a real-world supplement
sales dataset of 4,385 rows (1 header + 4,384 data records) covering
January 2020 to March 2025.

---

## File

| File | Description |
|------|-------------|
| PowerBI_Mini_Project.pbix | Power BI Desktop report |
| Arun_Mini_Project.xlsx | Source data (required for refresh) |

---

## Dataset Overview

| Field | Detail |
|-------|--------|
| Total Rows | 4,385 (1 header + 4,384 data records) |
| Period | January 2020 – March 2025 |
| Products | 16 supplement types |
| Categories | Protein, Vitamin, Mineral, Performance, Herbal, Omega, |
|            | Sleep Aid, Fat Burner, Hydration, Amino Acid |
| Locations | USA · UK · Canada |
| Platforms | iHerb · Amazon · Walmart |
| Total Net Revenue | $19,867,732 |
| Total Units Sold | 658,478 |
| Total Returns | 6,714 |

---

## Dashboard Visuals

| Visual | Description |
|--------|-------------|
| KPI Cards | Total Revenue, Net Revenue, Units Sold, Return Rate % |
| Bar Chart | Net Revenue by Category |
| Line Chart | Year-wise Revenue & Units trend (2020–Mar 2025) |
| Donut Chart | Platform share — iHerb / Amazon / Walmart |
| Map Visual | Geographic revenue — USA / UK / Canada |
| Slicers | Year · Category · Sub-Category · Platform · Location |
| Cross-filtering | Click any visual to filter all others instantly |
| Drill-through | Sub-category / product-level deep dive |

---

## DAX Measures

```dax
Total Net Revenue  = SUM([Net Revenue])
Return Rate %      = DIVIDE(SUM([U.Returned]), SUM([Actual Units Sold])) * 100
YoY Growth %       = ([This Year Rev] - [Last Year Rev]) / [Last Year Rev] * 100
Avg Net Rev / Txn  = AVERAGEX(SupplementSales, [Net Revenue])
```

---

## How to Use

1. Open PowerBI_Mini_Project.pbix in Power BI Desktop
2. Update data source path to your local Excel file if prompted
3. Click Refresh in the Home ribbon
4. Use slicers to filter by Year, Category, Platform, or Location
5. Click any chart element to cross-filter all other visuals
6. Right-click any data point > Drill-through for product-level details

---

## Sales Summary (January 2020 – March 2025)

| Year | Units Sold | Net Revenue | Returns | Note |
|------|-----------|-------------|---------|------|
| 2020 | 124,657 | $3,760,344 | 1,282 | Full Year |
| 2021 | 124,701 | $3,747,700 | 1,251 | Full Year |
| 2022 | 125,167 | $3,781,849 | 1,241 | Full Year |
| 2023 | 125,038 | $3,863,855 | 1,278 | Full Year |
| 2024 | 127,707 | $3,831,019 | 1,332 | Full Year |
| 2025 | 31,208  | $882,966   | 330   | Jan–Mar Only |
| **TOTAL** | **658,478** | **$19,867,732** | **6,714** | |

Top Categories : Vitamin $3.72M · Mineral $3.70M · Performance $2.53M
Top Location   : Canada $6.81M · UK $6.69M · USA $6.37M
Top Platform   : iHerb $6.81M · Amazon $6.65M · Walmart $6.40M

---

## 5-Year Revenue Forecast (2026–2030)

Baseline: 2024 full-year net revenue = $3,831,019
Growth: +7% for 2026, then +10% CAGR from 2027–2030

| Year | Revenue | Growth | Key Driver |
|------|---------|--------|------------|
| 2026 | ~$4,099,190 | +7%  | Post-pandemic health demand |
| 2027 | ~$4,509,110 | +10% | Protein & Herbal surge |
| 2028 | ~$4,960,020 | +10% | International expansion |
| 2029 | ~$5,456,023 | +10% | Platform scaling |
| 2030 | ~$6,001,625 | +10% | New categories & DTC |

---

## Requirements

- Power BI Desktop (free — microsoft.com/power-bi)
- Microsoft Excel 2016 / Microsoft 365

---

## Author

Arun — Power BI Mini Project · Jan 2020 – Mar 2025
