# Coke-Sales-Analysis-Excel
# Coke-Sales-Analysis-Excel

## Overview
This project analyzes Coca-Cola retail sales across US regions and retailers in 2021. Goal is to identify sales trends, regional performance, and profitability optimization.

## Problem Statement
Which retailer, region and beverage brand drives total sales? How can we optimize inventory and profitability for seasonal peaks? Dataset has 5 regions, 4 retailers, 6 brands with metrics like Units Sold, Total Sales, Operating Profit and Operating Margin. I chose Excel because it's best for quick cleaning, pivot analysis and visual storytelling.

## Dataset
- 3744+ rows, 2021 transactions
- Columns: Retailer, Invoice Date, Region, State, City, Beverage Brand, Price Per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin
- Sheets: Data, Beginner, Intermediate, Advanced

## Tools Used
Excel: TRIM, IFERROR, MONTH(), YEAR(), SUMIFS(), AVERAGEIFS(), VLOOKUP(), IF, Pivot Tables, Slicers, Conditional Formatting, Charts (Pie, Bar, Line)

## EDA
1. Cleaning: TRIM for names, MONTH/YEAR for date, IFERROR for nulls.
2. Feature: Created Month, Quarter, Profit Per Unit columns.
3. Exploration: Pivot Tables - Found West $2.83M (33%) top region, Sodapop $4.4M (51%) top retailer.

## Visualizations
- Pie Chart Sales by Retailer: Sodapop 51% ($4.4M/$8.6M) - high dependency.
- Pie Chart Sales by Region: West $2.83M highest.
- Pie Chart Sales by Brand: Coca-Cola $2.01M leader.
- Line Chart Sales Trend: West peaks 497,000 units in July, 477,500 in Dec - seasonality.
- Bar Chart Units by Retailer: Sodapop 6,153,850 vs DreamCo 620,500.

## Key Insights & Recommendations
1. Seasonality: June-July and Dec peak - increase inventory in May/Nov.
2. Risk: Sodapop 51% dependency - grow FizzySip (4.1M units).
3. Profit: Push Diet Coke (35% margin) vs Dasani (25%) in West/Northeast.
4. Regional: Focus marketing in South region.
