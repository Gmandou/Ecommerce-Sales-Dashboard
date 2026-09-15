# Ecommerce Sales Dashboard (Excel)

## What this is

An interactive sales dashboard built in Excel using PivotTables, PivotCharts, and slicers, on a dataset of 49,000 e-commerce orders.

## Dataset

Order-level e-commerce data covering order details, customer info, product info, and sales values (OrderID, CustomerID, OrderDate, ProductID, Quantity, Discount, PaymentMethod, Status, City, CustomerSegment, ProductName, Category, UnitPrice, Sales, OrderValue).

## What's on it

**Dashboard tab:**
- Total Sales Over Time (line chart, broken out by product)
- Sales By City (bar chart)
- Top 5 Customers (bar chart)
- Slicers: OrderDate (with a timeline slicer), Status, ProductName, Category, CustomerSegment, City — all interactive and linked to the charts

**Supporting tabs:**
- `data` — the full raw dataset
- `Total_Sales`, `City_bar`, `Top_Customers` — PivotTables feeding the dashboard charts
- `Product_Lookup` — a small tool where you enter a Product ID and it pulls back the Product Name, Category, and Unit Price automatically, using INDEX/MATCH (the same result as XLOOKUP, both formulas noted on the sheet)

## Skills used

- PivotTables and PivotCharts
- Slicers, including a timeline slicer for date filtering
- INDEX/MATCH lookups (XLOOKUP-equivalent)
- Dashboard layout and design


## How to use

Open the file and click into the Dashboard tab. Use the slicers on the right and top to filter by date, status, product, category, customer segment, or city — all charts update automatically.

## Author

**Godwill Mandou**

Part of my portfolio, built to practice Excel for dashboard design and business reporting.
