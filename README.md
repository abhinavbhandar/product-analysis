# Awesome Chocolates: PRODUCT & SALES ANALYTICS REPORT

This project focuses on creating an advanced sales analytics dashboard in Power BI for a fictional chocolate company. It highlights insights into sales trends, product and employees performance, helping stakeholders make data-driven decisions.  
The analysis aims to uncover sales patterns, top-performing regions, and key product categories while identifying opportunities for growth and customer retention.

---

## Table of Contents
1. [Tools and Platforms Used](#tools-and-platforms-used)
2. [Data](#data)
3. [Analysis & Findings](#analysis--findings)
4. [Steps and Process](#steps-and-process)
5. [Dashboard](#report)

---

## Tools and Platforms Used
**Power Bi**  
- purpose: For creating interactive dashboards and data visualization to analyze supply chain trends and performance metrics.
- Key Features Used: Data import, transformation, DAX calculations, and custom visualization creation.

**Microsoft Excel**  
- Purpose: For preliminary data exploration and manual data cleaning for creating dataset for predictive modeling.
- Key Features Used: Functions, conditional formatting, and simple visualizations.

**Git Hub**  
Purpose: Used for hosting project documentation, versioning, and sharing notes related to the project.

---

## Data

### Dataset
- A fictional dataset of sales data for Awesome Chocolates, including product categories, regions, sales representatives, and time-based sales records.

### Meta Data
- **Columns**: Date, Region, Product Category, Sales Representative, Quantity Sold, Revenue, Discount Applied.
- **Timeframe**: 13 months of sales data.

---

## Analysis & Findings

### Subject
The client, Awesome Chocolate, seeks to reduce costs by identifying and eliminating low-profit areas in production and sales. Specifically, the aim is to streamline operations by focusing on profitable products and high-performing sales personnel, ultimately enhancing the company's overall profitability.

### Task
Develop a Power BI dashboard to effectively visualize product and sales data, enabling the identification of key trends and supporting data-driven decision-making to:  
* Identify high-performing product categories.
* Analyze geographical sales distribution.
* Segment employees based on sales contribution.
* Examine seasonal trends in sales data.


### Action
- Created a Power BI dashboard to visualize key metrics such as total sales, sales by region, and product performance.
- Built DAX measures for total revenue, growth rate, and sales trends.
- Applied slicers and filters for interactive analysis.

### Result
- **Sales Trends**: Identified a 15% spike in sales during the holiday season.
- **Product Analysis**: Dark chocolates emerged as the highest contributor, accounting for 40% of revenue.
- **Regional Insights**: The East Coast region contributed 35% of total sales, outperforming other regions.
- **Customer Retention**: Repeat customers constituted 25% of the customer base but contributed 60% of revenue.

### Solution
- Focus marketing efforts on high-performing regions like the East Coast.
- Launch promotional campaigns for top products (e.g., dark chocolates) during the holiday season.
- Implement loyalty programs targeting repeat customers.

---

## Steps and Process

### Data Modeling
- Designed a star schema in Power BI with a fact table for sales and dimension tables for products, regions, and empolyees.

### Data Cleaning
- Ensured consistent formatting of dates and product categories using Power Query.
- Removed duplicates and handled missing values.

### Exploratory Data Analysis (EDA)  

|Analysis|Chart|
|---|---|
|**Employee Analysis:** Dynamic Table illustrating the performance of sales representatives, highlighting top performers. | ![image](https://github.com/user-attachments/assets/96a5e08d-0168-428e-be48-a3e4b9982693) |
|**Sales Analysis:** Line charts showing monthly revenue trends and a KPI card for year-over-year sales growth. | ![image](https://github.com/user-attachments/assets/c7c5ef66-6b3e-49f5-9df3-182289613f31) |
|**Geo Analysis:** Pie chart displaying sales distribution across regions. | ![image](https://github.com/user-attachments/assets/4a7bc2f4-6273-4722-83c2-488c9ff9ea57) |
|**Shipment Analysis:** Bar chart displaying relation between shipments and number of boxes shipped. | ![image](https://github.com/user-attachments/assets/ff43365f-f90f-492e-ac2b-15b3835ac119) |
|**Product Analysis:**  A table chart displaying revenue contribution by product categories. | ![image](https://github.com/user-attachments/assets/4ee90f62-90aa-4c31-a002-c94d0a0dcdbe) |

### Report  

**Power BI Setup**  
  - Loading data into Power BI from Excel dataset.
  - Introduction to the dataset's main tables, including Shipment and People tables.
  - Initial table connections and manual adjustments for unlinked tables.

**Data Modeling**  
  - Setting up relationships between tables using common columns.
  - Calculations to analyze shipment data, including "Low Box Shipment Count" and "Low Box Percentage."
  - Formatting for profit and sales metrics to enhance readability.
     **Star Schema data model**   
  
  ![image](https://github.com/user-attachments/assets/5cbfb4cb-085e-4578-b724-5de7caf00390)  

**DAX Calculations**  
  - Month-on-month and year-on-year calculations.
  - Dynamic measures for sales trends and latest month-over-month sales changes.
  - Designing a new DAX measure to track profit targets, enabling goal-tracking visuals on the dashboard.  

**Dashboard Design and Layout**  
  - designed strategies for arranging high-level summary metrics and detailed data.
  - Creating a summary bar for KPIs.
  - Structuring the dashboard for intuitive navigation.

  ![image](https://github.com/user-attachments/assets/a2a48d8e-f16b-4552-af2e-9cdd8172f8ef)  
  ![image](https://github.com/user-attachments/assets/98c8976d-1458-4c01-9065-a5d9fe8b86a8)  

**Visualization Techniques**  
  - Implementing advanced visuals, including KPI cards, slicers, and histograms.
  - Using grouping and conditional formatting to enhance data readability.
  - Adding company branding through logos and color themes for a polished look.

**Dynamic Measures and Interactivity**  
  - Building interactive elements using bookmarks to switch between different views (e.g., People and Product Details).
  - Setup for custom buttons and image icons to toggle views.
  - Enhancing visual hierarchy with conditional formatting based on monthly targets.

**Publishing the Dashboard**  
  - Preparing the dashboard for publication, including setting up final bookmarks and exporting options.
  - Publishing on GitHub

---

## How to Run
1. Open the Power BI file Link: [*Dashboard link*](https://app.powerbi.com/view?r=eyJrIjoiNjg1MTA0MTEtMjgyMS00YTdkLWI3Y2EtY2EwMWVhN2NlMmI3IiwidCI6IjRjMzMwZTYyLWY1YWEtNDQ4MS04YzVlLTIxZmU0MmFlZDgxYyJ9)   
2. Explore the visuals and use slicers/filters for deeper insights.
3. Customize as required for your analysis.

---

## Conclusion
The dashboard provided actionable insights, enabling stakeholders to identify key revenue drivers and optimize sales strategies.
