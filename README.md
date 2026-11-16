# -Sales-MIS-Executive-Dashboard-Excel-
An executive MIS report built in Excel that turns raw sales data into clear business insights across month, product, salesperson and category.
## 🎯 Problem Statement
Management needs one report to answer:
- How much revenue and how many units did we sell?
- How did sales change from October to November?
- Which products and salespeople perform best?
- How much discount is given in each category?

## 📁 Dataset
- **Source:** [source / sample dataset / company data (anonymised)]
- **Rows:** [number]
- **Period:** October – November [year]
- **Columns:** Row ID, Product ID, Product Name, Category, Salesperson, Units, Price per Unit, Discount, Total Revenue

## 🛠️ Tools Used
- Microsoft Excel
- Pivot Tables and Pivot Charts
- Slicers
- Formulas: SUMIFS, RANK, [XLOOKUP]

## 🧹 Data Cleaning Steps
- Removed duplicate rows
- Fixed blank and incorrect values
- Standardised column names and product names
- Recalculated revenue: `Units × Price per Unit − Discount`
- Built all pivots from a single clean table so totals match across sheets

## 📑 Report Sheets
| # | Sheet | What it shows |
|---|-------|---------------|
| 1 | Sales Summary | Total units, revenue, discount, average price |
| 2 | Monthly Sales Trend | October vs November units and revenue |
| 3 | Brand and Model Performance | Top 10 products by revenue |
| 4 | Salesperson Performance | Revenue and units per salesperson |
| 5 | Discount Analysis | Discount amount and discount % by category |

## 💡 Key Insights
- Total revenue was **₹[1.16 cr]** from **[23,26,534]** units.
- **[Elecronics]** has the highest discount rate (**616**).
- **[Yogesh ]** is the top performer with ₹[500] in revenue.
- Top product: **[product Electrocics]** (₹[135831]).

## 🖼️ Screenshots
![Sales Summary](screenshots/1_sales_summary.png)
![Monthly Trend](screenshots/2_monthly_trend.png)
![Top Products](screenshots/3_top_products.png)
![Salesperson Performance](screenshots/4_salesperson_performance.png)
![Discount Analysis](screenshots/5_discount_analysis.png)
