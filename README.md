# Global Superstore Sales Dashboard

An interactive Power BI report that analyses the sales transactions of a retail store with branches all over the world. It helps stakeholders understand sales by market, region, country, state and city, and the share of each shipping mode.

## Files in this repository
| File | Description |
|---|---|
| `dashboard2.pbix` | Power BI dashboard (open with Power BI Desktop) |
| `dashboard2pdf.pdf` | PDF export of the report |
| `Global Superstore.xlsx` | Dataset (51,290 order lines, 24 columns) |
| Screenshots (`.png`) | Preview of Page 1 and Page 2 |

## Data Cleaning (Power Query)
- Removed duplicate rows using Row ID
- Applied Trim and Clean on all text columns
- Checked and corrected data types (dates, numbers, text)
- Removed the Postal Code column (mostly empty, not needed for the analysis)

## Report Contents

**Page 1 – Dashboard**
- Sales by Country and Market (map)
- Sales by Market and Sales by Region (bar charts)
- Shipping percentage by Ship Mode (donut chart)
- Top 5 Cities and Top 5 States by Sales
- Slicers: Market, Region, Country

**Page 2 – Data Tables**
- A table for every visualization on Page 1

## Key Insights
- APAC is the largest market by sales, followed by EU and US.
- Central is the top region by sales.
- Standard Class is used for 60% of orders, while Same Day is only 5.27%.
- New York City is the top city and England is the top state by sales.

## Screenshots
### Page 1
![Page 1](Screenshot%202026-11-11%20145225.png)

### Page 2
![Page 2](Screenshot%202026-11-11%20145243.png)

## How to open
Download `dashboard2.pbix` and open it in Power BI Desktop. Use the slicers to filter by Market, Region and Country.

## Tools Used
Power BI Desktop, Power Query, DAX
