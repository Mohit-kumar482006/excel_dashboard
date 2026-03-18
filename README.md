# 📊 Excel Sales Dashboard Project

An interactive Excel dashboard built on a full year of sales data (2023) for a multi-product, multi-region business. The project includes raw data, pivot table analysis, and a visual dashboard — all in one workbook.

---

## Workbook Structure

| Sheet | Description |
|---|---|
| `data` | Raw sales data — 1,000 transactions across 2023 |
| `All reports` | Pivot table summaries by region, product, salesperson, and month |
| `dashboard` | Visual dashboard built from the pivot reports |

---

## Dataset Overview (`data` sheet)

| Column | Description |
|---|---|
| `Date` | Transaction date (Jan–Dec 2023) |
| `Region` | East, West, North, South |
| `Product` | Laptop, Mobile, Tablet, Printer, Monitor |
| `Salesperson` | Riya, Kunal, Amit, John, Sneha, Rahul |
| `Quantity` | Units sold per transaction |
| `Unit_Price` | Price per unit |
| `Total_Sales` | Quantity × Unit Price |

**Dataset size:** 1,000 rows | **Period:** Full year 2023

---

## Reports & Analysis (`All reports` sheet)

| Report | Insight |
|---|---|
| Sales by Region | Breakdown of total revenue across East, West, North, South |
| Sales by Product | Revenue contribution of each product category |
| Sales by Salesperson | Individual performance across 6 sales reps |
| Monthly Sales | Month-by-month quantity sold and revenue |
| KPI Summary | Total Revenue, Total Units Sold, Total Orders |

---

## Key Numbers

| Metric | Value |
|---|---|
| Total Revenue | ₹40,15,85,960 |
| Total Units Sold | 10,012 |
| Total Orders | 1,000 |
| Top Region | West (₹11.05 Cr) |
| Top Product | Printer (₹8.74 Cr) |
| Top Salesperson | Kunal (₹7.42 Cr) |

---

## Excel Features Used

| Feature | Where Used |
|---|---|
| Pivot Tables | Summarizing sales by region, product, salesperson, month |
| Slicers | Interactive filters on the dashboard |
| Charts | Visual representation of pivot data |
| KPI Cards | Summary metrics (Total Revenue, Units, Orders) |
| Formulas | `SUM`, calculated fields in pivot tables |
| Data formatting | Date, currency, and number formatting |

---

## How to Use

1. Open `excel_dashboard_project.xlsx` in Microsoft Excel
2. Go to the **dashboard** sheet to view the visual summary
3. Use the **slicers** to filter by Region, Product, or Salesperson
4. Check the **All reports** sheet for detailed pivot breakdowns
5. Raw data is available in the **data** sheet for any custom analysis
