# Adidas-Dashboard
This is a adidas sales analysis interactive dashboard using power bi.

1. Project Title / Headline
   
👟 Adidas Sales Pulse:
   US Performance Insights Dashboard
   An interactive Power BI dashboard that analyzes Adidas sales across the United States from 2020–2021, highlighting revenue,               profitability, regional trends, product performance, and retailer contribution.
​

2. Short Description / Purpose


   This dashboard provides a consolidated view of Adidas’s US sales performance, enabling users to explore how total sales, operating        profit, units sold, price per unit, and operating margin vary by month, region, state, product category, and retailer.

​
   It is intended for business stakeholders, data analysts, and strategy teams who want to quickly identify high‑performing products,       locations, and channels and uncover opportunities to optimize pricing, assortment, and partnerships.
​

3. Tech Stack
   Power BI Desktop – Primary platform for building the interactive report, cards, charts, and slicers.


   Power Query – Used for importing, cleaning, and shaping the Adidas US sales table (dates, regions, retailers, and numeric fields such     as Total Sales and Operating Profit).


   DAX (Data Analysis Expressions) – Measures for KPIs like Total Sales, Operating Profit, Units Sold, Average Price per Unit, and          Operating Margin, plus dynamic filtering across visuals.

​
   Data Modeling – Single fact table with attributes such as Retailer, Region, State, City, Product, Sales Method, and Invoice Date          linked through date and categorical relationships to support cross‑filtering by time and geography.


   File Formats – .pbix for the Power BI report and .xlsx/.csv exports for the underlying sales data.
​

4. Data Source

   
   Primary Source: Adidas US Sales Datasets on Kaggle – a transactional dataset containing retailer‑level sales across US regions,          states, and cities between 2020 and 2021.

​
   Dataset Structure: Single table with columns such as Retailer, Retailer ID, Invoice Date, Region, State, City, Product, Price per         Unit, Units Sold, Total Sales, Operating Profit, Operating Margin, and Sales Method, enabling granular analysis of both revenue and       profitability.

​
   Dataset Link: Adidas US Sales Datasets – Kaggle: https://www.kaggle.com/datasets/bcnishantreddy/adidas-us-sales-datasets[data]


5. Features / Highlights

   
Business problem
Adidas operates through multiple retailers, channels, and regions across the US, making it difficult for decision‑makers to quickly understand where revenue and profit are concentrated and which combinations of products, locations, and partners drive the best margins.

​
Raw rows of transactional data cannot easily answer questions like which states generate the highest sales, which retailers are most profitable, or how seasonality impacts units sold, especially when data spans 2020 and 2021.

​
Goal of the dashboard
Provide a single, interactive view of Adidas US sales and profitability KPIs, enabling users to slice performance by time, region, product category, and retailer.

​
Support data‑driven decisions around marketing focus, inventory allocation, retailer partnerships, and product assortment by exposing trends in sales volume, margins, and geographic distribution.

​
Walkthrough of key visuals
KPI Cards (Top Row)


Total Sales: around 900M USD summarizing all transactional revenue in the dataset.


Operating Profit: about 332M USD, highlighting profitability after operating costs at an aggregate level.

​
Units Sold: roughly 2M units across all categories, retailers, and regions.


Price per Unit: average selling price of 45 USD, giving a quick sense of overall pricing.


Operating Margin: approximately 42%, summarizing profit efficiency across the portfolio.

​
Date and Region Slicers (Top Right)


A date range slicer lets users filter the entire report between January 2020 and December 2021 to focus on specific months or years.
A region slicer (e.g., West, Midwest, Northeast, Southeast, South) enables quick comparison of performance across US regions, updating all visuals contextually.
​

Total Sales by Month (Line/Area Chart)
Displays monthly sales trends for 2020–2021, highlighting peaks and dips that may correspond to promotions, holidays, or broader market events.
Helps identify seasonality in Adidas sales and evaluate whether campaigns or product launches improved revenue during specific periods.

​
Total Sales by State (Treemap)
A treemap visual breaks sales down by US state, with larger rectangles indicating higher total sales (e.g., New York, California, Florida).
This enables users to quickly see which states contribute most to revenue and where there may be under‑penetrated markets.

​
Total Sales by Region (Donut Chart)
Shows the share of total sales contributed by regions like West, Northeast, Southeast, South, and Midwest.
Useful for identifying concentration risk and planning regional growth strategies.

​
Total Sales by Product (Horizontal Bar Chart)
Breaks sales into product categories: Men’s Street Footwear, Men’s Athletic Footwear, Women’s Street Footwear, Women’s Athletic Footwear, Men’s Apparel, and Women’s Apparel.
Highlights which categories are top revenue generators, guiding merchandising and marketing priorities.

​
Total Sales by Retailer (Horizontal Bar Chart)
Ranks retailers such as West Gear, Foot Locker, Sports Direct, Kohl’s, Amazon, and Walmart by total sales contribution.
Helps identify strategic partners that deliver the highest sales and profit, as well as under‑performing retailers where improvement actions may be needed.
​

Business impact & insights


Channel and retailer strategy


The breakdown by retailer and sales method (Online vs. Outlet) reveals which partners and channels yield stronger sales and margins, supporting negotiation strategies and investment in digital or physical touchpoints.
Focusing on consistently high‑performing retailers while optimizing others can increase overall revenue and profitability.

​
Regional and product optimization


Regional and state‑level visuals show where Adidas has strong presence and where there is room to grow, influencing regional marketing and distribution plans.
Product‑level insights highlight profitable categories, guiding assortment planning, promotion design, and inventory allocation.

​
Seasonality and planning


Monthly sales trends allow planners to anticipate demand surges and allocate inventory, campaigns, and staffing around high‑volume months.
Comparing patterns across 2020 and 2021 helps evaluate recovery and refine forecasts for future years


6. Screenshots / Demos

   
https://github.com/ushaaaa33/Adidas-Dashboard/blob/main/Screenshot%20of%20the%20Dashboard.png
