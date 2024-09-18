# Power BI 'AdventureWorks' Sales Performance Dashboard

## Overview

This repository contains a Power BI project that analyzes and visualizes sales performance data for a fictional bike retail company. The dashboard provides insights into sales trends, top-performing products, and regional performance, helping stakeholders and executives to make data-driven decisions.

![Power BI Exec page](https://github.com/user-attachments/assets/28415283-f1f5-4fdc-9174-9e52fa8d28b2)

## Features

* Executive Overview: A high-level view of total revenue, number of transactions, and return trends with additional product category detail.
  
* Regional Sales: Geographical analysis showing order performance across different regions and countries.
*	Product Performance: Insights into product revenue, order and profit margins. Adjustable product metric charts over time.
*	Customer Insights: Analysis of customer demographics, buying patterns, and revenue value.
*	Year-over-year and month-over-month sales comparison to track growth.

## 📁 Files in the Repository

*	<a href="https://github.com/Polyee99/Power-BI-Online-Store-Dashboards/blob/main/AdventureWorks%20Bike%20Store%20Dashboard_2024_09.pbix">AdventureWorks Bike Store Dashboard_2024_09.pbix</a> - The Power BI file containing the data model and dashboard.
  
*   <a href="https://github.com/Polyee99/Power-BI-Online-Store-Dashboards/tree/main/AdventureWorks%2BRaw%2BData">AdventureWorks+Raw+Data</a> - Raw data used for the analysis, including sales transactions, customer details, and product information.
*   <a href="https://github.com/Polyee99/Power-BI-Online-Store-Dashboards/tree/main/AdventureWorks%2BImages">AdventureWorks+Images</a> - Images used for additional button icons.

## 📊 Data Sources 

The data used in this project comes from the attached csv files:

*	Sales Data: Contains details of sales transactions, including product/customer keys, quantity and date of purchase.
  
*	Return Data: Includes date of return and different foreign keys related to products.
*	Lookup Data: Information about customers, products, dates and territory features.

## 📋 Requirements

*	Power BI Desktop (latest version)
  
*	Microsoft Excel (for reviewing raw data)
*	Basic understanding of DAX and Power BI visuals

## ▶️ Getting Started

To run this Power BI project locally:

1. Clone the repository:
```
git clone https://github.com/YourUsername/Power-BI-Sales-Dashboard.git
```
3. Open the <a href="https://github.com/Polyee99/Power-BI-Online-Store-Dashboards/blob/main/AdventureWorks%20Bike%20Store%20Dashboard_2024_09.pbix">Sales_Performance_Dashboard.pbix</a> file in Power BI Desktop.

4. Ensure that the data source paths are correct. If needed, modify the data connections in the Transform Data tab to point to the correct file locations.

5. Refresh the data to load the latest data from sales_data.xlsx.

6. Explore the dashboard and interact with the visualizations.

## ⚙️Dashboard Walkthrough
*	Navigation panel on the left side of every page
### Executive Overview:
*	Total revenue, profit, sales, and return rate.
*	Revenue trend by week with dynamic filters for year.
*	Orders by product Category with custom tooltip.
*	Monthly KPIs
*	Product detail table with additional metrics.
*	Top performed products.
### Regional Sales:
*	Map visualization showing sales by state and city.
*	Custom slicer for continents.
### Product Performance:
*	Breakdown of specific product by revenue, order and profit gauge chart.
*	Filter profit by price and price adjustments to analyze performance over the years.
*	Interactive metric-over-year comparison to track growth.
### Customer Insights:
*	Some customer related information with additional line chart to measure trends over the years.
*	Analyze customer segmentation by name, total orders and revenue.
*	Additional detail about top customer.
*	Visualize sales by income and occupation on donut chart. 
## 🚀 Project Methodology

1. Data Cleaning: The raw data was cleaned using Power BI's Power Query Editor, ensuring that all records are complete and formatted properly.
2. Data Modeling: Relationships were created between sales, customers, and product tables to allow for effective slicing and dicing of the data.
3. DAX Calculations: Custom measures were created using DAX (Data Analysis Expressions) to compute KPIs like total revenue, profit margin, and average customer value.
4. Visualization: Multiple Power BI visualizations were used, including bar charts, line graphs, maps, and tables to represent different facets of the data.
