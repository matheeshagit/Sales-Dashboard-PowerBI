# Sales Dashboard Project – Power BI + Excel

## Project Overview
This project demonstrates an **end-to-end business intelligence system** using Power BI and Excel.  
It analyzes Superstore sales data to provide actionable business insights for executives and managers.

## Dataset
- **Source:** Superstore Sample Dataset (Excel)
- **Raw file:** `raw/Superstore.xls`
- **Cleaned file:** `cleaned/Superstore_Cleaned.xls`

## Project Steps
1. **Data Cleaning:**  
   - Handled missing values, removed duplicates, formatted dates  
   - Calculated derived columns: Profit Margin, Discount %, Sales per Customer  

2. **Power BI Modeling:**  
   - Created a **star schema**: Fact_Sales, Dim_Customer, Dim_Product, Dim_Date  
   - Defined **DAX measures**: Total Sales, Total Profit, Total Orders, Profit Margin  

3. **Dashboard Pages:**
   - **Executive Summary:** KPI cards, Sales Trend, Category Performance  
   - **Product Insights:** Top 10 products, category profitability, return rate  
   - **Customer Insights:** RFM metrics, customer segmentation  
   - **Forecasting:** 3–6 month sales forecast with confidence interval  

## Key Insights
- Total sales peaked in Q4 with top-performing products in Technology  
- Furniture category has the lowest profit margin  
- Top customers (Champions) generate high frequency and monetary value  
- Forecast indicates a steady sales growth trend for the next 3 months  

## Deliverables
- Power BI file: `powerbi/SalesDashboard.pbix`  
- Cleaned dataset: `cleaned/Superstore_Cleaned.xls`  
- Dashboard screenshots: `screenshots/`  

---

