# Maven Toys Sales Analysis - Power BI Project

---
## Project Overview

This project leverages Power BI to conduct an in-depth analysis of sales data from Maven Toys, a fictional toy store chain in Mexico, with data covering product sales and store performance across multiple locations. The analysis highlights sales trends, profitability, and store performance over 2022 and 2023.

**Tool used:**

- Power BI

**Dataset:**
    
- The project is based on datasets imported from Maven Analytics [Mexico Toy Sales]( https://mavenanalytics.io/data-playground?dataStructure=Multiple%20tables&order=date_added%2Cdesc&search=toy)

- Data from 4  .csv files, with the fact table covering transactions from years 2022 and 2023

<br />

***Note:** Although the Inventory table was imported, this project focuses primarily on Product and Store sales performance.*

---
## Problem statement

### Problem/Question to be Solved: 

1.	Monthly Sales Trends (2022 vs. 2023): How do sales trends compare between 2022 and 2023, and what factors contributed to these changes?
   
3.	Top-Contributing Categories: Which product categories drive the most sales and profitability?
   
5.	Store Performance: Which stores are the most and least profitable, and how do their performances differ across various store locations?

---
## Main Steps in Report Creation

### 1. Data Import

Downloaded the following  `".csv"` files  from [Maven Analytics](https://mavenanalytics.io/data-playground?dataStructure=Multiple%20tables&order=date_added%2Cdesc&search=toy)

- Product.ch

- Sales.csv

- Stores.csv

- Inventory.csv

<br />

*The files are also available in this repository, and you can download them using the link below:*

[View downloaded files](https://github.com/DaCruzEmanuel/PowerBI_Sales_Analysis/tree/main/Datasets)

### 2. Data Exploration and Organisation

Exploring a dataset before importing it into Power BI is crucial for some of the folllowing reasons:

**•	Data Quality Assessment**

Early cleaning and preparation ensure reliable and accurate data.

**•	Understanding Data Structure**

Familiarize with the relationships between tables, data types and field ensure correct modeling, relationship optimization and effective report structure design.

**•	Optimization of Data Load**

Exploring the dataset beforehand allows you to identify unnecessary columns or rows that can be excluded from the import process, reducing data load size. This optimizes Power BI performance, especially for large datasets, ensuring faster report generation and analysis.


### 3. Data transformation and cleaning in Power Query Editor

**On Power Query from Power BI:**

•	Changed Data types of columns IDs to numeric on all tables.
•	Loaded data into Power BI Desktop

### 4. Created a Calendar Table using DAX

•	Marked the calendar table as Date table

### 5. Data modelling

•	Created relationships between the Fact Table, Dimension Tables, and Calendar Table as shown below:

<img src="https://i.imgur.com/X974bYl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

### 6. DAX Calculations
•	Created a measures table called “Calculation” to stores all measures.

[View all DAX measures](https://github.com/DaCruzEmanuel/PowerBI_Sales_Analysis/tree/main/DAX%20-%20Measures%20and%20Calendar%20table)

### 7. Report Visualizations and analysis

The analysis is based on the following 3 reports:

•	Sales Overview

•	Products Analysis

•	Stores Analysis

---
## Report Visualization and Analysis

This analysis focuses on the sales analysis of Maven Toys stores between 2022 and 2023. 

## Key Insights
**______________________________**
#### 1. Sales Overview

<img src="https://i.imgur.com/BURl2IH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

The overall sales overview shows:

<br />

**KPIs**

•	Total Units Sold (2022-2023): 829K units

•	Total Revenue (2022-2023): $14.44M

•	Total Profit Margin (2022-2023): $4M

<br />

**Sales Trends (2022 vs. 2023):**

While sales and profitability have grown significantly in 2023, the sales trend remains relatively consistent between the two years. The first peak of sales came earlier in 2023 (March) compared to 2022 (May). The strongest sales month in 2023 is expected to be December, driven by holiday shopping.


**______________________________**

#### 2. Products and Category Analysis

<img src="https://i.imgur.com/lj7tnFs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

As shown on the visual above, Maven Toys offers 35 products across five categories.

<br />

**Product Categories**

•	Art & Crafts

•	Electronics

•	Games

•	Sports & Outdoors

•	Toys

<br />

**Top Sellers & Revenue Drivers:**

•	**Top Sellers:** "Colorbuds" (2022), "Barrel O'Slime" (2023)

•	**Revenue Driver:** Despite higher sales volume for "Colorbuds," "Lego Bricks" consistently generated the highest revenue.


**______________________________**
#### 3. Stores Analysis

<img src="https://i.imgur.com/QDRX2Pc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

This dashboard shows that Maven Toys operates 50 stores across 29 cities accros four location types.

<br />

**Stores locations type**

•	Downtown

•	Commercial

•	Residential

•	Airport

<br />

**Stores performance:**

•	Stores in **Downtown** areas contributed the most to overall sales.

•	**Ciudad de Mexico 2** emerged as the most profitable store for both years.

## Recommendations

1.	**Focus on Downtown Stores:** Given the strong sales performance in Downtown locations, investing in these areas may yield higher profitability.
   
3.	**Product Focus:** Consider increasing inventory for Lego Bricks as it is the top revenue driver, despite not being the highest seller.
   
5.	**Seasonal Promotions:** Implement targeted promotions in March, as it showed early peak sales in 2023, potentially boosting mid-year revenue.

7.	**Inventory Optimization:** Adjust inventory levels to align with demand trends, particularly for high-selling products like "Colorbuds."

## Interactive Dashboard

For a more comprehensive review and to interact with the full dashboard, please click the link below:

[View Maven Toys Sales Dashboards](https://app.powerbi.com/view?r=eyJrIjoiNmFlNjZiNTgtMmZlOC00ODkwLWExMjYtZmZiZTlkOTk5ZDg0IiwidCI6IjIwNWMxNjI0LTg0YWEtNGU3Yy05NjhmLTlkYzM2NDAzNmFjZSJ9)



