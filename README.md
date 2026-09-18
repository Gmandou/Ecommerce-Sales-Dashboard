# Ecommerce Sales Dashboard (Excel)

## What this is

An interactive sales dashboard built entirely in Excel using PivotTables, PivotCharts, and slicers, on a dataset of ~49,000 e-commerce orders.

## Dashboard Screenshot

![Ecommerce Sales Dashboard](Screenshot%202026-09-18%20at%2012.45.57.png)

## Dataset

Order-level e-commerce data covering order details, customer info, product info, and sales values: OrderID, CustomerID, OrderDate, ProductID, Quantity, Discount, PaymentMethod, Status, Age, City, SignupDate, CustomerSegment, ProductName, Category, UnitPrice, Sales, OrderValue.

## Dashboard

**What's on it:**
- Total Sales Over Time (line chart, broken out by product)
- Sales By City (bar chart)
- Top 5 Customers (bar chart)
- Slicers: OrderDate (with a timeline slicer), Status, ProductName, Category, CustomerSegment, City

**Key findings:**
- Tehran is by far the top city by sales ($963,907), more than double the next closest city, Mashhad ($438,112).
- The top 5 customers by spend are all clustered closely together (roughly $2,050–$2,470), rather than one customer dominating — suggesting a broad base of high-value repeat buyers rather than a single outlier.
- Sales activity is spread across a wide product range, with no single product consistently dominating month to month based on the trend chart.

## Supporting tabs

- `data` — the full raw dataset (49,223 rows)
- `Total_Sales`, `City_bar`, `Top_Customers` — PivotTables feeding the dashboard charts
- `Product_Lookup` — enter a Product ID and it pulls back the Product Name, Category, and Unit Price automatically, using INDEX/MATCH (the XLOOKUP-equivalent formula is noted on the sheet too)

## Skills used

- PivotTables and PivotCharts
- Slicers, including a timeline slicer for date filtering
- INDEX/MATCH lookups (XLOOKUP-equivalent)
- Dashboard layout and design

## A note on scope

I built this using an e-commerce dataset, which overlaps in industry with my SQL retail project. I made that trade-off deliberately to focus on demonstrating strong Excel skills (PivotTables, slicers, lookups) rather than rebuilding around a different dataset for the sake of industry variety.

## How to use

Open the file and click into the Dashboard tab. Use the slicers on the right and top to filter by date, status, product, category, customer segment, or city — all charts update automatically. Use the Product_Lookup tab to pull details for any Product ID in the dataset.

## Author

**Godwill Mandou**

Part of my data analytics portfolio, built to practice Excel for dashboard design and business reporting.
