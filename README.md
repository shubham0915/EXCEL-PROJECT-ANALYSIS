# CoffeePulse - Coffee Shop Sales Dashboard

## Project Overview
**CoffeePulse** is a B.Tech project developed by Shubham (Reg. No: 12310611) at Lovely Professional University under the guidance of Dr. Karan Bajaj, Assistant Professor, School of Computer Science and Engineering. The project, titled *Design and Analysis of Coffee Shop Sales: An Excel-Based Dashboard Approach*, analyzes a dataset of over 150,000 coffee shop transaction records to derive actionable insights for optimizing sales strategies. Using Microsoft Excel, the project focuses on creating an interactive dashboard to study sales trends across store locations, product categories, and time periods.

This repository contains the Excel dashboard and related files for the CoffeePulse project, completed by April 12, 2025, as part of the INT217 course.

## Declaration
The project report titled *CoffeePulse – Coffee Shop Sales Dashboard* is the original work of Shubham, conducted under the supervision of Dr. Karan Bajaj. It has not been submitted to any other institution for academic or non-academic purposes.

## Certificate
The project fulfills partial requirements for the Bachelor of Technology in Computer Science and Engineering at Lovely Professional University. It was certified as original work by Dr. Karan Bajaj on April 12, 2025.

## Acknowledgements
Sincere gratitude to:
- Dr. Karan Bajaj for invaluable guidance and support.
- The Department of Computer Science and Engineering, LPU, for providing necessary infrastructure.
- Peers and family for their encouragement and support throughout the project.

## Table of Contents
1. [Introduction](#introduction)
2. [Source of Dataset](#source-of-dataset)
3. [Dataset Preprocessing](#dataset-preprocessing)
4. [Analysis Objectives](#analysis-objectives)
5. [Insights from Analysis](#insights-from-analysis)
6. [Conclusion](#conclusion)
7. [Future Scope](#future-scope)
8. [References](#references)
9. [Downloadable File](#downloadable-file)

## Introduction
The *CoffeePulse* project analyzes coffee shop sales data to uncover trends and provide actionable insights for management. The dataset, containing over 150,000 transaction records with 11 columns, was processed in Excel to create an interactive dashboard. The project addresses five key objectives:
- Total sales by store location.
- Monthly sales trends.
- Top-selling product categories.
- Sales breakdown by category.
- Comprehensive, filterable sales analysis.

Using pivot tables, macros, and slicers, the dashboard transforms raw data into visualizations like bar, line, pie, and stacked bar charts to support data-driven decision-making for optimizing inventory, staffing, and marketing.

## Source of Dataset
The dataset, sourced from Maven Analytics, includes over 150,000 transaction records with the following columns:
- `transaction_id`
- `transaction_date`
- `transaction_time`
- `transaction_qty`
- `store_id`
- `store_location`
- `product_id`
- `unit_price`
- `product_category`
- `product_type`
- `product_detail`

The data was processed in Excel and finalized by April 12, 2025, enabling a multi-dimensional analysis of sales trends.

## Dataset Preprocessing
The dataset was cleaned and prepared in Excel to ensure data quality:
- **Missing Values**: Filled with median values using the `MEDIAN` function for columns like `unit_price` and `transaction_qty`.
- **Standardization**: Unified text formats (e.g., "Lower Manhattan" vs. "lower manhattan") using Find and Replace.
- **Duplicates**: Removed using `Remove Duplicates` on `transaction_id`.
- **Text Cleaning**: Applied `TRIM` to clean text columns like `product_detail`.
- **Outliers**: Capped outliers in `unit_price` via conditional formatting.
- **New Column**: Added a `Total Sales` column (`transaction_qty * unit_price`) for analysis.
- **Date Conversion**: Converted `transaction_date` from Excel serial numbers (e.g., 44927) to readable dates using `DATEVALUE` for monthly trend analysis.
- **Table Formatting**: Formatted the dataset as an Excel table for dashboard integration.

## Analysis Objectives
The project developed an interactive Excel dashboard to meet five objectives:

### Objective 1: Total Sales by Store Location
- **Outcome**: Displays total sales for each store (e.g., Lower Manhattan, Hell's Kitchen, Astoria).
- **Method**: Used a pivot table to aggregate `Total Sales` by `store_location`, visualized with a bar chart.

### Objective 2: Monthly Sales Trends
- **Outcome**: Shows sales trends over time.
- **Method**: Grouped data by month using a pivot table on converted `transaction_date`, visualized with a line chart to identify seasonal patterns.

### Objective 3: Top-Selling Product Categories
- **Outcome**: Lists sales by `product_category` (e.g., Coffee, Tea, Drinking Chocolate).
- **Method**: Aggregated `Total Sales` by `product_category` using a pivot table, visualized with a pie chart.

### Objective 4: Sales by Category
- **Outcome**: Provides a detailed breakdown of sales by `product_category` and `product_type`.
- **Method**: Created a pivot table for `Total Sales` by `product_category` and `product_type` (e.g., Gourmet brewed coffee, Brewed Chai tea), visualized with a stacked bar chart.

### Objective 5: Comprehensive Sales Analysis
- **Outcome**: Offers a multi-dimensional, filterable sales breakdown.
- **Method**: Used pivot tables to analyze `Total Sales` across `store_location`, `product_category`, `product_type`, and `transaction_date` (monthly), with slicers for filtering and multiple charts (e.g., bar, line) for visualization.

## Insights from Analysis
The analysis revealed the following insights:
1. **Total Sales by Store Location**: Lower Manhattan outperforms Hell's Kitchen and Astoria, suggesting higher demand or foot traffic.
2. **Monthly Sales Trends**: Sales peak in specific months (e.g., around January 2023, inferred from date range 44927–44938), indicating seasonal influences.
3. **Top-Selling Product Categories**: Coffee leads sales, followed by Tea and Drinking Chocolate, highlighting customer preference for coffee-based products.
4. **Sales by Category**: Gourmet brewed coffee is the top performer within the Coffee category, suggesting a focus on premium offerings.
5. **Comprehensive Sales Analysis**: Lower Manhattan excels in Coffee sales during peak months, emphasizing the need for location- and time-specific strategies.

## Conclusion
The *CoffeePulse* project demonstrates the power of Excel-based data analysis for real-world business solutions. By cleaning a dataset of over 150,000 records and building an interactive dashboard, the project achieved its five objectives, providing insights into store performance, product popularity, and seasonal trends. The use of pivot tables, macros, and visualizations showcases the ability to transform raw data into actionable strategies for coffee shop management, enhancing inventory, staffing, and marketing decisions.

## Future Scope
Potential enhancements for the project include:
- Integrating real-time sales data for dynamic tracking.
- Applying machine learning (e.g., Python or R) to predict monthly sales trends.
- Incorporating customer demographics for broader analysis.
- Developing a recommendation system for high-margin products.
- Transitioning to Power BI or SQL for scalability and advanced visualizations.

## References
- Microsoft Corporation. (2024). *Microsoft Excel Documentation*. Retrieved from [https://support.microsoft.com/en-us/excel](https://support.microsoft.com/en-us/excel)
- Smith, J. (2023). *Data Analysis Techniques for Beginners*. New York, NY: Tech Press.
- Kumar, R. (2022). *Practical Dashboard Design with Excel*. Journal of Computer Science Applications, 15(3), 45-52.

## Downloadable File
The interactive Excel dashboard for *CoffeePulse* can be downloaded from:  
[https://drive.google.com/file/d/1L94kZTpknb6SO18Cv-XC4CCP71mWO7R4/view?usp=sharing](https://drive.google.com/file/d/1L94kZTpknb6SO18Cv-XC4CCP71mWO7R4/view?usp=sharing)

## Contact
For inquiries, contact Dr. Karan Bajaj at [er.kbajaj@gmail.com](mailto:er.kbajaj@gmail.com).