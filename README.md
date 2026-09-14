# Inventory Management Analytics

## Engineers' Day Hackathon 2026 — Project 08

### Inventory Performance & Replenishment Dashboard

An Excel-based business analytics project focused on analyzing inventory levels, sales movement, stock value, replenishment requirements, and operational performance.

## Business Problem

Inventory teams need to balance product availability with the cost of holding excess stock. The project addresses the following business challenges:

- Identifying products requiring replenishment
- Monitoring inventory levels across regions and warehouses
- Understanding inventory and sales performance
- Evaluating supplier performance
- Identifying potential inventory exposure

### Business Question

**Which products require immediate replenishment and which products are overstocked?**

## Objective

To analyze inventory levels, stock value, sales movement, reorder requirements, and operational performance to support better inventory management decisions.

## Dataset

**Source:** Kaggle — High-Dimensional Supply Chain Inventory Dataset  
**Creator:** Ziya  
**License:** CC0 Public Domain  
**Records:** 91,250 rows  
**Columns:** 15  
**Date Range:** 2024-01-01 to 2024-12-30

### Key Data Fields

- Date
- SKU ID
- Warehouse ID
- Supplier ID
- Region
- Units Sold
- Inventory Level
- Supplier Lead Time
- Reorder Point
- Order Quantity
- Unit Cost
- Unit Price
- Promotion Flag
- Stockout Flag
- Demand Forecast

## Tools & Technologies

- Microsoft Excel
- Excel Tables
- Power Query
- PivotTables
- PivotCharts
- Slicers
- Timeline
- Excel formulas
- Conditional Formatting

## Data Preparation

The dataset was prepared in Excel by:

- Checking for missing values
- Checking duplicate records
- Verifying numerical fields
- Checking categorical consistency
- Standardizing data formats
- Preparing calculated fields
- Creating PivotTables for analysis

## Key KPIs

| KPI | Value |
|---|---:|
| Total Units Sold | 1,829,979 |
| Total Inventory | 43,026,411 |
| Total Stock Value | 525,243,991.1 |
| Total Order Quantity | 1,758,615 |
| Reorder Alerts | 5,041 |
| Stockout Count | 0 |
| Stock Cover | 44.69 days |
| Average Supplier Lead Time | 7.984 days |

## Dashboard

The Excel dashboard provides an interactive view of:

- Inventory and sales performance by region
- Warehouse performance
- Supplier performance
- Stock value by SKU
- Replenishment alerts
- KPI summary
- Date, region, and supplier filtering

## Key Insights

1. **Replenishment Risk:** 5,041 records were identified at or below the reorder point.
2. **Inventory Position:** Total inventory is approximately 43.03 million units compared with 1.83 million units sold.
3. **Stockout Status:** No stockout events were recorded in the dataset.
4. **Inventory Coverage:** Overall stock cover is approximately 44.69 days.
5. **Supplier Variation:** Supplier-level sales performance varies significantly across suppliers.

## Recommendations

- Prioritize replenishment for items identified by the reorder analysis.
- Monitor high inventory levels to reduce excess stock exposure.
- Improve inventory allocation across warehouses and regions.
- Monitor supplier performance and lead times.
- Use stock-cover information to support inventory planning.
- Review inventory levels regularly using the interactive dashboard.

## Project Files

- `Final_Inventory_Management_Analytics.xlsx` — Complete Excel workbook and dashboard
- `INVENTORY-MANAGEMENT-ANALYTICS.pptx` — Project presentation
- `supply_chain_dataset1.csv` — Source dataset

## Project Structure

This repository contains the complete Excel analytics project, source dataset, and presentation prepared for Engineers' Day Hackathon 2026.

## Author

**Vinayak Arote**

### Project

**Inventory Management Analytics — Optimizing Stock Levels, Replenishment & Inventory Efficiency**

**Track:** Track 1 — Excel Business Analytics  
**Project:** 08  
**Event:** Engineers' Day Hackathon 2026
