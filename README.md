📊 Supplement Sales Analytics and Performance Insights (Jan 2020 – Mar 2025)
Tools: Power BI | DAX | Data Modeling | Power Query
Domain: Retail | Sales Analytics | E-Commerce
📊 Supplement Sales Analytics and Performance Insights (Jan 2020 – Mar 2025)
Tools: Power BI | DAX | Data Modeling | Power Query
Domain: Retail | Sales Analytics | E-Commerce
Show Image
Show Image
Show Image

🧩 Project Overview
This project analyses supplement sales data (January 2020 – March 2025) across 16 products sold in USA, UK, and Canada on iHerb, Amazon, and Walmart.
Using Power BI, the data was cleaned, modeled, and visualized across two interactive dashboards — a Sales Overview Dashboard and a Revenue Forecast Dashboard — to uncover key sales trends, platform performance, category insights, and future revenue projections.
The dataset contains 4,385 rows (1 header + 4,384 records) with a total net revenue of $19,867,732 across 658,478 units sold.

🎯 Project Objectives

Analyse Sales Performance
Study overall trends in supplement sales (2020–Mar 2025), focusing on net revenue, units sold, discounts, and returns across categories, platforms, and locations.
Evaluate Category Performance
Assess which supplement categories — Vitamin, Mineral, Performance, Protein, Herbal, Omega, Sleep Aid, Fat Burner, Hydration, Amino Acid — generate the highest net revenue.
Understand Platform & Location Behavior
Identify how revenue is distributed across iHerb, Amazon, and Walmart and across USA, UK, and Canada.
Forecast Future Revenue
Project revenue trends for 2026–2030 using scenario-based forecasting (Conservative, Base, Optimistic) with a ~10% CAGR, reaching ~$6M by 2030.


📂 Data Source
SourcePeriodArun_Mini_Project.xlsx (Supplement Sales sheet)January 2020 – March 2025
Domain: Retail Sales Analytics

❓ Problem Statement

Analyse supplement sales performance across 16 products, 10 categories, 3 platforms, and 3 locations.
Understand revenue distribution by category, platform, and geography.
Track year-wise net revenue trends to identify peak and low periods.
Evaluate discount impact on actual selling price and net revenue.
Identify which platforms generate the most revenue and transactions.
Forecast projected revenue from 2026 to 2030 under multiple growth scenarios.
Compare actual net revenue trends vs projected revenue year over year.


🧾 Attribute Details
Attribute NameData TypeDescriptionDateDateReporting date (weekly)CategoryTextSupplement category (Vitamin, Mineral, Protein, etc.)Sub CategoryTextSpecific product name (Whey Protein, Zinc, BCAA, etc.)LocationTextCountry of sale — USA, UK, CanadaPlatformTextSales channel — iHerb, Amazon, WalmartUnitsWhole NumberTotal units sold in the periodCost PriceCurrencyOriginal price per unit (₹ not applicable — USD)DiscountDecimalDiscount percentage appliedDiscount AmountCurrencyDiscount Amount = Cost Price × Discount %Actual Selling PriceCurrencyActual Selling Price = Cost Price − Discount AmountRevenueCurrencyRevenue = Units × Actual Selling PriceU.ReturnedWhole NumberNumber of units returned by customersU.Returned AmountCurrencyValue of returned unitsNet RevenueCurrencyNet Revenue = Revenue − U.Returned AmountActual Units SoldWhole NumberActual Units Sold = Units − U.Returned

🧹 Data Preprocessing Steps
Data Collection:
Sourced from the cleaned Supplement Sales sheet in Arun_Mini_Project.xlsx covering January 2020 to March 2025.
Data Cleaning (Power Query):
Filled missing values, standardized text formats (Category, Platform, Location), and corrected data types for date and currency columns.
Data Transformation:
Added calculated columns — Discount Amount, Actual Selling Price, Net Revenue, and Actual Units Sold — using DAX and Power Query.
Data Modeling:
Established relationships between date, category, and sales tables for accurate cross-filtering and drill-through.
Data Integration:
Unified records across 2020–2025 into a single clean dataset for consistent visualization across both dashboards.

📉 Dashboard 1 — Sales Overview
The Sales Overview Dashboard provides a complete picture of actual sales performance from January 2020 to March 2025.
Slicers: Category · Location · Platform
VisualDescriptionKPI Card — Net RevenueTotal net revenue across the full dataset periodKPI Card — Selling PriceAverage actual selling price after discountKPI Card — Units SoldTotal actual units sold (after returns)KPI Card — DiscountTotal discount amount applied across all salesClustered Column ChartCategory vs Net Revenue — compare all 10 supplement categoriesFunnel ChartPlatform vs Revenue — iHerb, Amazon, Walmart revenue funnelColumn ChartLocation vs Net Revenue — USA, UK, Canada breakdownPie ChartYear-wise Net Revenue — revenue share by yearRibbon ChartYear vs Total Sales — trend of total sales across years

📈 Dashboard 2 — Revenue Forecast
The Revenue Forecast Dashboard projects supplement sales revenue from 2026 to 2030 using scenario-based modelling.
Slicers: Category · Platform · Year · Location
VisualDescriptionClustered Column ChartProjected Total Sales by Year — bar comparison 2026–2030Line ChartProjected Revenue by Year — smooth trend line of forecastLine ChartNet Revenue by Year — actual historical trend for comparisonFunnel ChartProjected Revenue by Scenario — Conservative vs Base vs Optimistic
Forecast Basis: 2024 full-year net revenue ($3,831,019) as baseline · +7% for 2026 · +10% CAGR from 2027–2030
YearProjected RevenueGrowth2026~$4,099,190+7%2027~$4,509,110+10%2028~$4,960,020+10%2029~$5,456,023+10%2030~$6,001,625+10%

📊 Performance Insights
🟢 Vitamins were the top-grossing category with $3,721,089 in net revenue.
📅 2023 recorded peak net revenue at $3,863,855 among all full years.
💹 iHerb generated the highest platform net revenue at $6,809,349 across 1,499 transactions.
🌍 Canada led location revenue at $6,806,528, closely followed by UK at $6,690,210.
📈 Year-over-year unit growth (124,657 in 2020 → 127,707 in 2024) indicates steady market demand.
🔻 2025 (Jan–Mar only) recorded 31,208 units and $882,966 — on pace with prior years when annualised.
💰 Minerals were the second-highest revenue category at $3,697,924, led by Zinc and Magnesium.
📦 Total returns across the entire period: 6,714 units — a healthy low return rate.

🧠 Conclusion
The integration of Power Query and Power BI enabled a comprehensive analysis of supplement sales (January 2020 – March 2025) across two interactive dashboards.
Key findings include:

Vitamins and Minerals dominate revenue, accounting for over 37% of total net revenue.
iHerb is the leading platform by total net revenue, while Canada leads by geography.
2023 was the peak revenue year at $3,863,855 net revenue.
Forecast projects ~$6M revenue by 2030 at a ~10% CAGR based on the 2024 baseline.
Low return rate (6,714 units out of 658,478 sold) reflects strong product-market fit and customer satisfaction.

This project transformed 4,385 rows of raw sales data into clear, actionable insights on supplement market performance, platform efficiency, and future revenue potential.

🗂️ Files in This Repository
FileDescriptionPowerBI_Mini_Project.pbixPower BI report — 2 dashboards (Sales Overview + Revenue Forecast)Arun_Mini_Project.xlsxSource data — cleaned Supplement Sales sheetREADME.mdProject documentation

🛠️ Requirements

Power BI Desktop (free — microsoft.com/power-bi)
Microsoft Excel 2016 / Microsoft 365 (for data source refresh)


🚀 How to Use

Open PowerBI_Mini_Project.pbix in Power BI Desktop
Update the data source path to your local Arun_Mini_Project.xlsx if prompted
Click Refresh in the Home ribbon to load data
Navigate between Sales Overview and Revenue Forecast pages using the page tabs
Use slicers (Category, Platform, Location, Year) to filter dynamically
Click any chart element to cross-filter all other visuals instantly


👨‍💻 Author
Arun
Data Analyst | Power BI Developer
📧 Email: (your email)
💼 LinkedIn: (your LinkedIn)
🌐 GitHub: (your GitHub)
If you found this project useful or have any feedback, feel free to reach out!

🧩 Project Overview
This project analyses supplement sales data (January 2020 – March 2025) across 16 products sold in USA, UK, and Canada on iHerb, Amazon, and Walmart.
Using Power BI, the data was cleaned, modeled, and visualized across two interactive dashboards — a Sales Overview Dashboard and a Revenue Forecast Dashboard — to uncover key sales trends, platform performance, category insights, and future revenue projections.
The dataset contains 4,385 rows (1 header + 4,384 records) with a total net revenue of $19,867,732 across 658,478 units sold.

🎯 Project Objectives

Analyse Sales Performance
Study overall trends in supplement sales (2020–Mar 2025), focusing on net revenue, units sold, discounts, and returns across categories, platforms, and locations.
Evaluate Category Performance
Assess which supplement categories — Vitamin, Mineral, Performance, Protein, Herbal, Omega, Sleep Aid, Fat Burner, Hydration, Amino Acid — generate the highest net revenue.
Understand Platform & Location Behavior
Identify how revenue is distributed across iHerb, Amazon, and Walmart and across USA, UK, and Canada.
Forecast Future Revenue
Project revenue trends for 2026–2030 using scenario-based forecasting (Conservative, Base, Optimistic) with a ~10% CAGR, reaching ~$6M by 2030.


📂 Data Source
SourcePeriodArun_Mini_Project.xlsx (Supplement Sales sheet)January 2020 – March 2025
Domain: Retail Sales Analytics

❓ Problem Statement

Analyse supplement sales performance across 16 products, 10 categories, 3 platforms, and 3 locations.
Understand revenue distribution by category, platform, and geography.
Track year-wise net revenue trends to identify peak and low periods.
Evaluate discount impact on actual selling price and net revenue.
Identify which platforms generate the most revenue and transactions.
Forecast projected revenue from 2026 to 2030 under multiple growth scenarios.
Compare actual net revenue trends vs projected revenue year over year.


🧾 Attribute Details
Attribute NameData TypeDescriptionDateDateReporting date (weekly)CategoryTextSupplement category (Vitamin, Mineral, Protein, etc.)Sub CategoryTextSpecific product name (Whey Protein, Zinc, BCAA, etc.)LocationTextCountry of sale — USA, UK, CanadaPlatformTextSales channel — iHerb, Amazon, WalmartUnitsWhole NumberTotal units sold in the periodCost PriceCurrencyOriginal price per unit (₹ not applicable — USD)DiscountDecimalDiscount percentage appliedDiscount AmountCurrencyDiscount Amount = Cost Price × Discount %Actual Selling PriceCurrencyActual Selling Price = Cost Price − Discount AmountRevenueCurrencyRevenue = Units × Actual Selling PriceU.ReturnedWhole NumberNumber of units returned by customersU.Returned AmountCurrencyValue of returned unitsNet RevenueCurrencyNet Revenue = Revenue − U.Returned AmountActual Units SoldWhole NumberActual Units Sold = Units − U.Returned

🧹 Data Preprocessing Steps
Data Collection:
Sourced from the cleaned Supplement Sales sheet in Arun_Mini_Project.xlsx covering January 2020 to March 2025.
Data Cleaning (Power Query):
Filled missing values, standardized text formats (Category, Platform, Location), and corrected data types for date and currency columns.
Data Transformation:
Added calculated columns — Discount Amount, Actual Selling Price, Net Revenue, and Actual Units Sold — using DAX and Power Query.
Data Modeling:
Established relationships between date, category, and sales tables for accurate cross-filtering and drill-through.
Data Integration:
Unified records across 2020–2025 into a single clean dataset for consistent visualization across both dashboards.

📉 Dashboard 1 — Sales Overview
The Sales Overview Dashboard provides a complete picture of actual sales performance from January 2020 to March 2025.
Slicers: Category · Location · Platform
VisualDescriptionKPI Card — Net RevenueTotal net revenue across the full dataset periodKPI Card — Selling PriceAverage actual selling price after discountKPI Card — Units SoldTotal actual units sold (after returns)KPI Card — DiscountTotal discount amount applied across all salesClustered Column ChartCategory vs Net Revenue — compare all 10 supplement categoriesFunnel ChartPlatform vs Revenue — iHerb, Amazon, Walmart revenue funnelColumn ChartLocation vs Net Revenue — USA, UK, Canada breakdownPie ChartYear-wise Net Revenue — revenue share by yearRibbon ChartYear vs Total Sales — trend of total sales across years

📈 Dashboard 2 — Revenue Forecast
The Revenue Forecast Dashboard projects supplement sales revenue from 2026 to 2030 using scenario-based modelling.
Slicers: Category · Platform · Year · Location
VisualDescriptionClustered Column ChartProjected Total Sales by Year — bar comparison 2026–2030Line ChartProjected Revenue by Year — smooth trend line of forecastLine ChartNet Revenue by Year — actual historical trend for comparisonFunnel ChartProjected Revenue by Scenario — Conservative vs Base vs Optimistic
Forecast Basis: 2024 full-year net revenue ($3,831,019) as baseline · +7% for 2026 · +10% CAGR from 2027–2030
YearProjected RevenueGrowth2026~$4,099,190+7%2027~$4,509,110+10%2028~$4,960,020+10%2029~$5,456,023+10%2030~$6,001,625+10%

📊 Performance Insights
🟢 Vitamins were the top-grossing category with $3,721,089 in net revenue.
📅 2023 recorded peak net revenue at $3,863,855 among all full years.
💹 iHerb generated the highest platform net revenue at $6,809,349 across 1,499 transactions.
🌍 Canada led location revenue at $6,806,528, closely followed by UK at $6,690,210.
📈 Year-over-year unit growth (124,657 in 2020 → 127,707 in 2024) indicates steady market demand.
🔻 2025 (Jan–Mar only) recorded 31,208 units and $882,966 — on pace with prior years when annualised.
💰 Minerals were the second-highest revenue category at $3,697,924, led by Zinc and Magnesium.
📦 Total returns across the entire period: 6,714 units — a healthy low return rate.

🧠 Conclusion
The integration of Power Query and Power BI enabled a comprehensive analysis of supplement sales (January 2020 – March 2025) across two interactive dashboards.
Key findings include:

Vitamins and Minerals dominate revenue, accounting for over 37% of total net revenue.
iHerb is the leading platform by total net revenue, while Canada leads by geography.
2023 was the peak revenue year at $3,863,855 net revenue.
Forecast projects ~$6M revenue by 2030 at a ~10% CAGR based on the 2024 baseline.
Low return rate (6,714 units out of 658,478 sold) reflects strong product-market fit and customer satisfaction.

This project transformed 4,385 rows of raw sales data into clear, actionable insights on supplement market performance, platform efficiency, and future revenue potential.

🗂️ Files in This Repository
FileDescriptionPowerBI_Mini_Project.pbixPower BI report — 2 dashboards (Sales Overview + Revenue Forecast)Arun_Mini_Project.xlsxSource data — cleaned Supplement Sales sheetREADME.mdProject documentation

🛠️ Requirements

Power BI Desktop (free — microsoft.com/power-bi)
Microsoft Excel 2016 / Microsoft 365 (for data source refresh)


🚀 How to Use

Open PowerBI_Mini_Project.pbix in Power BI Desktop
Update the data source path to your local Arun_Mini_Project.xlsx if prompted
Click Refresh in the Home ribbon to load data
Navigate between Sales Overview and Revenue Forecast pages using the page tabs
Use slicers (Category, Platform, Location, Year) to filter dynamically
Click any chart element to cross-filter all other visuals instantly


👨‍💻 Author
Arun
Data Analyst | Power BI Developer
📧 Email: (your email)
💼 LinkedIn: (your LinkedIn)
🌐 GitHub: (your GitHub)
If you found this project useful or have any feedback, feel free to reach out!
