# Power BI 'AdventureWorks' Sales Performance Dashboard

Overview

This repository contains a Power BI project that analyzes and visualizes sales performance data for a fictional retail company. The dashboard provides insights into sales trends, top-performing products, and regional performance, helping stakeholders make data-driven decisions.T he data used to create this dashboard is not real and is intended for educational purposes only.
Features

    Sales Overview: A high-level view of total sales, number of transactions, and revenue trends.
    Product Performance: Insights into top-selling products, sales by category, and profit margins.
    Regional Sales: Geographical analysis showing sales performance across different regions and cities.
    Customer Segmentation: Analysis of customer demographics, buying patterns, and lifetime value.
    Time Analysis: Year-over-year and month-over-month sales comparison to track growth.

📁 Files in the Repository

    Sales_Performance_Dashboard.pbix - The Power BI file containing the data model and dashboard.
    sales_data.xlsx - Raw data used for the analysis, including sales transactions, customer details, and product information.
    dashboard_screenshot.png - A screenshot of the main dashboard.
    documentation/ - Contains additional project documentation, including methodology, data cleaning steps, and Power BI setup guide.

📊 Data Sources

The data used in this project comes from the attached csv files:

    Sales Data: Contains details of sales transactions, including product, quantity, price, and date of purchase.
    Customer Data: Information about customers such as demographics, purchase history, and loyalty program status.
    Product Data: List of all products, including category, subcategory, and cost information.

📋 Requirements

    Power BI Desktop (latest version)
    Microsoft Excel (for reviewing raw data)
    Basic understanding of DAX and Power BI visuals

▶️ Getting Started

To run this Power BI project locally:

    Clone the repository:

    bash

    git clone https://github.com/YourUsername/Power-BI-Sales-Dashboard.git

    Open the Sales_Performance_Dashboard.pbix file in Power BI Desktop.

    Ensure that the data source paths are correct. If needed, modify the data connections in the Transform Data tab to point to the correct file locations.

    Refresh the data to load the latest data from sales_data.xlsx.

    Explore the dashboard and interact with the visualizations.

⚙️ Dashboard Walkthrough

    Sales Overview:
        Total sales, transactions, and profit margin.
        Sales trend by month with dynamic filters for year and region.

    Product Performance:
        Breakdown of top-selling products by revenue and units sold.
        Filter products by category and subcategory to analyze performance in detail.

    Regional Sales:
        Map visualization showing sales by state and city.
        Drill down into regional performance and compare sales across locations.

    Customer Insights:
        Analyze customer segmentation by demographics, average purchase value, and lifetime value.
        Visualize customer distribution by region and product preferences.

    Time Analysis:
        Year-over-year sales comparison to track growth.
        Heatmap of sales by day and month to identify trends and seasonality.

🚀 Project Methodology

    Data Cleaning: The raw data was cleaned using Power BI's Power Query Editor, ensuring that all records are complete and formatted properly.
    Data Modeling: Relationships were created between sales, customers, and product tables to allow for effective slicing and dicing of the data.
    DAX Calculations: Custom measures were created using DAX (Data Analysis Expressions) to compute KPIs like total revenue, profit margin, and average customer value.
    Visualization: Multiple Power BI visualizations were used, including bar charts, line graphs, maps, and tables to represent different facets of the data.
