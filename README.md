# Power BI Dashboard Project

This repository contains a Power BI dashboard project that demonstrates my skills in data analysis, visualization, and dashboard design. The project showcases a comprehensive process of building an interactive and insightful Power BI dashboard, highlighting key steps like data preparation, modeling, and visualization.

---

## Features

### 📊 **Data Sources**
Simulated real-world datasets including:
- Sales metrics
- Customer demographics
- Regional performance statistics

### 🔍 **Data Cleaning**
Using Power Query, the data was cleaned and transformed:
- Removed duplicates and inconsistencies.
- Standardized formats and create calculated columns.
- Enhanced datasets to ensure analytical accuracy.

### 🧩 **Data Modeling**
Built a robust data model by:
- Establishing relationships between tables.
- Optimizing for performance and clarity in analysis.

### 🧮 **DAX Measures**
Developed dynamic measures for in-depth analysis:
- **Total Sales:** `Total Sales = SUM(Sales[Amount])`
- **Year-to-Date Sales:** `YTD Sales = TOTALYTD(SUM(Sales[Amount]), Sales[Date])`
- **Sales Growth:** `Sales Growth = (SUM(Sales[Amount]) - [Previous Sales]) / [Previous Sales]`
- **Customer Retention:** `Customer Retention = DIVIDE(COUNTROWS(RETURNED_CUSTOMERS), COUNTROWS(TOTAL_CUSTOMERS))`

### 🎨 **Visualizations**
Designed engaging and interactive visuals:
- KPIs for high-level performance tracking.
- Bar, line, and pie charts for data trends and comparisons.
- Slicers and filters for user-driven exploration.

---

## Dashboard Screenshots

![image](https://github.com/user-attachments/assets/87c81c4a-2b9f-46af-acfb-317d984f6437)

![image](https://github.com/user-attachments/assets/ea581f36-304d-4edd-9179-2184eb24e74d)


---


## Key Learnings

- Advanced proficiency in Power Query for data cleaning and transformation.
- Developed DAX skills to create powerful and dynamic calculations.
- Gained expertise in designing intuitive and professional dashboards.
- Learned the importance of data storytelling in creating actionable insights.

