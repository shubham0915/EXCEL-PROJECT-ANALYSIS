# ☕ CoffeePulse - Coffee Shop Sales Dashboard ☕

Welcome to **CoffeePulse**, an exciting B.Tech project that brews data-driven insights for coffee shop success! This Excel-based sales dashboard, developed by Shubham (Reg. No: 12310611) at **Lovely Professional University**, transforms over 150,000 transaction records into vibrant visualizations to optimize business strategies. Conducted under the guidance of **Dr. Karan Bajaj**, Assistant Professor, this project was finalized on April 12, 2025, for the **INT217** course in the School of Computer Science and Engineering.

<p align="center">
  <img src="https://raw.githubusercontent.com/shubham0915/EXCEL-PROJECT-ANALYSIS/main/CoffeePulse Dashboard Preview.png" alt="CoffeePulse Dashboard Preview" width="600"/>
</p>

## 🌟 Project Overview
*CoffeePulse* is a dynamic tool designed to empower coffee shop management with actionable insights. By leveraging **Microsoft Excel**, this project analyzes a massive dataset to uncover sales trends, customer preferences, and operational opportunities. The interactive dashboard, built with **pivot tables**, **macros**, and **slicers**, offers a visually engaging way to explore sales by store location, product categories, and time periods, helping managers optimize inventory, staffing, and marketing.

---

## 📜 Declaration
I, **Shubham**, a B.Tech Computer Science and Engineering student, declare that *CoffeePulse – Coffee Shop Sales Dashboard* is my original work, developed under the mentorship of **Dr. Karan Bajaj**. This project has not been submitted elsewhere for academic or non-academic purposes.

---

## ✅ Certificate
This project, certified on **April 12, 2025**, fulfills partial requirements for the **Bachelor of Technology in Computer Science and Engineering** at Lovely Professional University. Dr. Karan Bajaj, the project supervisor, verifies the originality of this work.

---

## 🙏 Acknowledgements
A heartfelt thank you to:
- **Dr. Karan Bajaj** for his unwavering guidance and expertise.
- The **Department of Computer Science and Engineering, LPU**, for providing state-of-the-art infrastructure.
- My **peers and family** for their constant encouragement and support throughout this journey.

---

## 📋 Table of Contents
1. [Introduction](#introduction)
2. [Source of Dataset](#source-of-dataset)
3. [Dataset Preprocessing](#dataset-preprocessing)
4. [Analysis Objectives](#analysis-objectives)
5. [Insights from Analysis](#insights-from-analysis)
6. [Conclusion](#conclusion)
7. [Future Scope](#future-scope)
8. [References](#references)
9. [Downloadable File](#downloadable-file)

---

## 🚀 Introduction
The coffee shop industry thrives on understanding customer preferences and optimizing operations. *CoffeePulse* tackles this challenge by analyzing a dataset of **over 150,000 transaction records** with **11 columns**, including transaction ID, date, time, quantity, store location, product details, and unit price. Using **Excel**, the dataset was cleaned and transformed into an **interactive dashboard** that addresses five key objectives:
- 📍 **Total sales by store location** to identify top-performing stores.
- 📅 **Monthly sales trends** to uncover seasonal patterns.
- ☕ **Top-selling product categories** to highlight customer favorites.
- 📊 **Sales breakdown by category** for granular insights.
- 🔍 **Comprehensive, filterable sales analysis** for multi-dimensional trends.

The dashboard uses **pivot tables**, **macros**, and **slicers**, visualized with colorful **bar**, **line**, **pie**, and **stacked bar charts**, making data exploration intuitive and impactful.

---

## 📊 Source of Dataset
The dataset, sourced from **Maven Analytics**, contains **over 150,000 transaction records** with the following columns:
- `transaction_id`: Unique transaction identifier
- `transaction_date`: Date of transaction
- `transaction_time`: Time of transaction
- `transaction_qty`: Quantity sold
- `store_id`: Unique store identifier
- `store_location`: Store location (e.g., Lower Manhattan, Hell's Kitchen)
- `product_id`: Unique product identifier
- `unit_price`: Price per unit
- `product_category`: Category (e.g., Coffee, Tea)
- `product_type`: Specific product type (e.g., Gourmet brewed coffee)
- `product_detail`: Detailed product description

Processed in Excel and finalized by **April 12, 2025**, this dataset enables a robust analysis of sales trends across multiple dimensions.

---

## 🧹 Dataset Preprocessing
To ensure data quality, the dataset underwent rigorous preprocessing in Excel:
- **Missing Values**: Filled with median values using the `MEDIAN` function for columns like `unit_price` and `transaction_qty`.
- **Standardization**: Unified text formats (e.g., "Lower Manhattan" vs. "lower manhattan") using **Find and Replace**.
- **Duplicates**: Removed using `Remove Duplicates` on `transaction_id`.
- **Text Cleaning**: Applied `TRIM` to clean text columns like `product_detail`.
- **Outliers**: Capped outliers in `unit_price` with **conditional formatting**.
- **New Column**: Added `Total Sales` (`transaction_qty * unit_price`) for analysis.
- **Date Conversion**: Converted `transaction_date` from Excel serial numbers (e.g., 44927) to readable dates using `DATEVALUE`.
- **Table Formatting**: Formatted the dataset as an Excel table for seamless dashboard integration.

---

## 🎯 Analysis Objectives
The *CoffeePulse* dashboard addresses five objectives, each with tailored visualizations:

### 📍 Objective 1: Total Sales by Store Location
- **Outcome**: Displays total sales for each store (e.g., Lower Manhattan, Hell's Kitchen, Astoria).
- **Method**: Aggregated `Total Sales` by `store_location` using a **pivot table**, visualized with a **vibrant bar chart** in shades of blue and green.

### 📅 Objective 2: Monthly Sales Trends
- **Outcome**: Tracks sales trends over time.
- **Method**: Grouped data by month using a **pivot table** on converted `transaction_date`, visualized with a **smooth line chart** in warm tones to highlight seasonal patterns.

### ☕ Objective 3: Top-Selling Product Categories
- **Outcome**: Identifies sales by `product_category` (e.g., Coffee, Tea, Drinking Chocolate).
- **Method**: Summed `Total Sales` by `product_category` using a **pivot table**, visualized with a **colorful pie chart** in reds, yellows, and blues.

### 📊 Objective 4: Sales by Category
- **Outcome**: Provides a detailed breakdown by `product_category` and `product_type`.
- **Method**: Analyzed `Total Sales` by `product_category` and `product_type` (e.g., Gourmet brewed coffee, Brewed Chai tea) with a **pivot table**, visualized with a **stacked bar chart** in gradient hues.

### 🔍 Objective 5: Comprehensive Sales Analysis
- **Outcome**: Offers a multi-dimensional, filterable sales breakdown.
- **Method**: Used **pivot tables** to analyze `Total Sales` across `store_location`, `product_category`, `product_type`, and `transaction_date` (monthly), with **slicers** for interactive filtering and **multiple charts** (bar, line) in a cohesive color palette.

---

## 💡 Insights from Analysis
The dashboard revealed key insights:
1. **Total Sales by Store Location**: **Lower Manhattan** leads in sales, surpassing Hell's Kitchen and Astoria, indicating higher demand or foot traffic.
2. **Monthly Sales Trends**: Sales peak around **January 2023** (inferred from date range 44927–44938), suggesting seasonal influences, visualized in a striking line chart.
3. **Top-Selling Product Categories**: **Coffee** dominates, followed by Tea and Drinking Chocolate, highlighted in a vibrant pie chart.
4. **Sales by Category**: **Gourmet brewed coffee** outperforms other Coffee types, per a stacked bar chart, suggesting a focus on premium products.
5. **Comprehensive Sales Analysis**: Lower Manhattan excels in Coffee sales during peak months, with slicers enabling targeted strategy exploration.

---

## 🏁 Conclusion
*CoffeePulse* showcases the power of Excel for real-world business solutions. By cleaning a dataset of over 150,000 records and building an interactive dashboard, the project delivers insights into store performance, product popularity, and seasonal trends. The use of **pivot tables**, **macros**, and **colorful visualizations** empowers coffee shop management to make data-driven decisions for inventory, staffing, and marketing, proving Excel’s versatility in solving complex business challenges.

---

## 🔮 Future Scope
The project offers exciting opportunities for enhancement:
- 🌐 Integrate **real-time sales data** for dynamic dashboard updates.
- 🤖 Apply **machine learning** (Python or R) to predict monthly sales trends.
- 👥 Add **customer demographics** for deeper analysis.
- 📈 Develop a **recommendation system** to promote high-margin products.
- 🚀 Transition to **Power BI** or **SQL** for enhanced scalability and advanced visualizations.

---

## 📚 References
- Microsoft Corporation. (2024). *Microsoft Excel Documentation*. [https://support.microsoft.com/en-us/excel](https://support.microsoft.com/en-us/excel)
- Smith, J. (2023). *Data Analysis Techniques for Beginners*. New York, NY: Tech Press.
- Kumar, R. (2022). *Practical Dashboard Design with Excel*. Journal of Computer Science Applications, 15(3), 45-52.

---

## 📥 Downloadable File
Explore the interactive *CoffeePulse* Excel dashboard:  
[Download Here]([https://drive.google.com/file/d/1L94kZTpknb6SO18Cv-XC4CCP71mWO7R4/view?usp=sharing](https://drive.google.com/file/d/1j3L68rf8YIS1G4IvZA6G6lYhWrjlBXO6/view?usp=sharing))

---

## 📧 Contact
For inquiries, reach out to **Shubham** at [shubhamkuya@gmail.com](mailto:shubhamkuya@gmail.com).

---

<p align="center">
  <strong>☕ Brew insights, sip success with CoffeePulse! ☕</strong>
</p>
