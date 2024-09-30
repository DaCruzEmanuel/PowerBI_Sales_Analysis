# Maven Toys Sales Analysis - Power BI Project


## Project Overview

This project leverages Power BI to conduct an in-depth analysis of sales data from Maven Toys, a fictional toy store chain in Mexico, with data covering product sales and store performance across multiple locations. The analysis highlights sales trends, profitability, and store performance over 2022 and 2023.

- **Tool used:**
    - *Power BI*

- **Dataset:**
    - *The project is based on datasets imported from Maven Analytics[Mexico Toy Sales]( https://mavenanalytics.io/data-playground?dataStructure=Multiple%20tables&order=date_added%2Cdesc&search=toy).*
    - *Data from 4  .csv files, with the fact table covering transactions from years 2022 and 2023*
Note: Although having imported the Inventory table, for the purpose of this projects, I decided to essentially focus the analysis on Product and Store sales performance.

## Problem statement

### Problem/Question to be Solved: 

1.	Monthly Sales Trends (2022 vs. 2023): How do sales trends compare between 2022 and 2023, and what factors contributed to these changes?
   
3.	Top-Contributing Categories: Which product categories drive the most sales and profitability?
   
5.	Store Performance: Which stores are the most and least profitable, and how do their performances differ across various store locations?


## Main Steps in Report Creation

### 1. Data Import

Downloaded the following  `".csv"` files  from [Maven Analytics](https://mavenanalytics.io/data-playground?dataStructure=Multiple%20tables&order=date_added%2Cdesc&search=toy)

•	Product.ch

•	Sales.csv

•	Stores.csv

•	Inventory.csv

### 2. Data Exploration and Organisation

### 3. Data transformation and cleaning in Power Query Editor

**On Power Query from Power BI:**
- Changed Data types of columns IDs to numeric on all tables.

### 4. Loaded data into Power BI Desktop

### 5. Creating a Calendar Table using DAX
•	Marked the calendar table as Date table

[View the all DAX measures]()

### 6. Data modelling
•	Created relationships between the Fact Table, Dimension Tables, and Calendar Table




### 7. DAX Calculations
•	Created a measures table called “Calculation” to stores all measures.
[View the all DAX measures]()

### 8. Report Visualizations and analysis

The analysis is based on the following 3 reports:
•	Sales Overview
•	Products Analysis
•	Stores Analysis

## Report Visualization and Analysis

This analysis focuses on the sales analysis of Maven Toys stores between 2022 and 2023. For a more comprehensive review, and project interaction, please refer to the .pbix file available in this project repository.
[Access to .pbix file]()

### Key Insights
## Sales Overview
<img src="https://i.imgur.com/LJmFJqG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

•	**Total Units Sold (2022-2023):** 829K units
•	**Total Revenue (2022-2023):** $14.44M
•	**Total Profit Margin (2022-2023):** $4M
**Sales Trends (2022 vs. 2023):**

While sales and profitability have grown significantly in 2023, the sales trend remains relatively consistent between the two years. The first peak of sales came earlier in 2023 (March) compared to 2022 (May). The strongest sales month in 2023 is expected to be December, driven by holiday shopping.

##Products and Category Analysis
<img src="https://i.imgur.com/jhZc16D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Maven Toys offers 35 products across five categories:
•	Art & Crafts
•	Electronics
•	Games
•	Sports & Outdoors
•	Toys
**Top Sellers & Revenue Drivers:**
•	**Top Sellers:** "Colorbuds" (2022), "Barrel O'Slime" (2023)
•	**Revenue Driver:** Despite higher sales volume for "Colorbuds," "Lego Bricks" consistently generated the highest revenue.

##Stores Analysis
<img src="https://i.imgur.com/jhZc16D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Maven Toys operates 50 stores across 29 cities in the following locations:
•	**Downtown**
•	**Commercial**
•	**Residential**
•	**Airport**

**Store Performance:**
•	Stores in **Downtown** areas contributed the most to overall sales.
•	**Ciudad de Mexico 2** emerged as the most profitable store for both years.

