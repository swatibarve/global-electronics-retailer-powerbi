# Global Electronics Retailer — Power BI Dashboard

## Project Overview
Interactive Power BI dashboard analyzing sales performance 
for a global electronics retailer across 11 countries (2016–2021).

## Tools Used
Power BI | DAX | SQL | Excel | 5-Table Star Schema

## Dataset
Source: Maven Analytics | 62,884 transactions | 37 fields

## Data Model
Star schema with 5 tables: Sales (fact), Products, 
Customers, Stores, Exchange Rates (dimensions)
+ DateTable created in DAX

## Key DAX Measures
- Multi-currency revenue consolidation (LOOKUPVALUE)
- YoY Revenue Growth % (SAMEPERIODLASTYEAR)
- Revenue per Square

## Dashboard Pages
1. Executive Overview — KPIs, revenue trend, category analysis
2. Store & Channel Analysis — Online vs In-store, delivery trends
3. Product Performance — Category, brand, top 5 products
4. Customer Demographics — Geographic and gender analysis

## Key Findings
1. Revenue peaked in 2019, declined in 2020-2021 (COVID impact)
2. Computers = highest revenue category at $19.1M (35% share)
3. Delivery time improved 48% from 7.3 days to 3.8 days
4. In-store revenue is 79% of total — but online growing
5. Canada stores outperform USA on revenue per sq.m.

## Live Dashboard
https://app.powerbi.com/links/isIw9IJleF?ctid=0d77b7c5-e242-4138-ac4f-84df54febf02&pbi_source=linkShare&bookmarkGuid=df76ca89-ffad-4bf0-8a13-c57b49b874ce

## Author
Swati Barve | M.Econ | Data & Financial Analyst
LinkedIn: linkedin.com/in/swatibarve 
