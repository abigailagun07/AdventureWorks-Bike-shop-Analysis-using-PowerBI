# Adventure Works Bike Shop Power BI Project

In this project, I utilised Power BI to visualise revenue, profit, orders, and returns data of the hypothetical bike shop, Adventure Works. Through the techniques learned during the course provided by Mavern Analytics, I created insightful visualisations that showcase global data trends across various time periods, products, and customers.

## Project Overview

### The Data
The data used for this project is sourced from Maven Analytics and is purely hypothetical, as stated earlier. The data was organised into three distinct tables: sales data (56,046 rows), returns data (1,809 rows), and product data (293 rows). Please note that the raw data is provided exclusively for this course and is accessible within the context of the course materials.

### Key Insights and Techniques Learned
My journey with this project involved several crucial steps and concepts:

1. **Data Transformation and Shaping**: I began by connecting and shaping the data, performing data quality checks, and structuring the tables. Working in the Power BI query editor was a new experience for me and laid the foundation for the subsequent steps.

2. **Creating the Data Model**: I built my first data model, delving into concepts like relational models, cardinality, and filter flow. This step was particularly fascinating as these concepts can easily be underestimated, but they play a vital role in effective Power BI usage.

3. **Mastering DAX**: One of the highlights was learning Data Analysis Expressions (DAX). This powerful feature of Power BI empowers users to perform complex calculations and analyses. Notable tools/functions/formulas I explored include:
   - Measures: Leveraging measures in visualisations enhances Power BI's capabilities compared to Excel.
   - Switch: A function that simplifies logic, offering a practical way to manage data.
   - Related: This function takes the logic of VLOOKUPs to a whole new level, elevating data retrieval.

4. **Building Dashboards**: Armed with DAX knowledge, I proceeded to construct four main dashboards, along with decomposition tree and key influencers tabs. These detailed dashboards are best experienced in Power BI Service, where their full functionality comes to life.

## Dashboards

### 1. Executive Dashboard
A high-level summary of the entire dataset with key highlights:
- Top 10 products table featuring associated orders, revenue, and return rate.
- Drill-through functionality: Clicking on a product leads to the Product Detail Dashboard.
- Cards displaying monthly revenue, orders, and returns with dynamic conditional formatting based on targets.
- Slicer Panel for filtering by continent and year, enabling diverse analyses.

### 2. Map Dashboard
A simple yet informative geospatial visualization with tooltips for geographic insights.

### 3. Product Details Dashboard
Focusing on product-specific KPIs, this dashboard includes:
- Drill-through capability from the Executive Dashboard, showing detailed data for selected products.
- Use of numerical field parameters for real-time scenario analysis.
- Gauges demonstrating KPI performance against targets.

### 4. Customer Details Dashboard
Similar to the Product Details Dashboard but centered around customer-specific KPIs:
- Chart-specific filters for versatile data representation.
- Line chart showcasing customer count or revenue per customer over time.

### Additional Visualisations

### 5. Decomposition Tree
A powerful visualisation allowing user-driven analysis across categories and subcategories. Useful for dissecting total revenue breakdowns, identifying revenue-driving products, and their categories or subcategories.

### 6. Key Influencers
The Key Influencer visual assists in comprehending factors influencing specific metrics or outcomes. I explored customer attributes influencing AdventureWorks customers to be home owners and factors impacting retail prices.

## Conclusion
The Adventure Works Bike Shop Power BI project showcases a comprehensive journey through data transformation, model building, DAX mastery, and dashboard creation. This project serves as a testament to the capabilities of Power BI in visualising and deriving insights from complex datasets. Please note that the data used is fictional and accessible exclusively within the context of this course and that the dashboards are better viewed on PowerBI destop 

Feel free to explore the dashboards and enjoy the visual insights! If you have any questions or feedback, don't hesitate to reach out. Happy exploring!
