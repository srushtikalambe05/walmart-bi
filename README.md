Walmart Sales Analysis – Power BI Dashboard

This project analyzes Walmart’s weekly sales data using Power BI to uncover key business insights, seasonal trends, store-level performance, and the impact of economic indicators. The dashboard provides a clear view of sales behavior across time, helping identify growth opportunities and factors influencing revenue.

Dataset:

The dataset (walmart.csv) includes:

Weekly_Sales

Store

Date

Holiday_Flag

CPI (Consumer Price Index)

Unemployment

Fuel_Price

Temperature

Project Objectives:

Analyze weekly and monthly sales trends

Identify best and worst performing stores

Explore the impact of CPI, unemployment, fuel price & temperature

Compare holiday vs non-holiday performance

Build interactive visuals and slicers

Forecast future sales using time-series patterns

Perform store segmentation (High / Medium / Low categories)

Key Features of the Dashboard:

* Time Series Analysis 
* Forecasting using trend & seasonality
* Store Ranking and category segmentation
* Sales vs CPI, Unemployment, Fuel Price
* Holiday Impact Analysis
* Interactive filters (Store, Year, Category, Holiday)

Tools & Technologies

Power BI

DAX

Python (for monthly aggregation)

Pandas

File: /mnt/data/walmart.csv

Methodology

Data cleaning and preprocessing

Creating additional columns (Month, Category, CPI Class, Temp Class, etc.)

Generating monthly aggregates for forecasting

Building visuals for time series, economic factors, and store performance

Adding analytics (trend lines, forecasting, segmentations)

Validating insights and business impact

Insights

Sales show strong seasonal trends around holidays

Higher CPI and unemployment correlate with lower sales

Some stores consistently outperform others

Temperature and fuel price show weak correlation with sales

Forecasting reveals steady sales patterns with seasonal peaks
