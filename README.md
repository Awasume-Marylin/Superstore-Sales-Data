# Superstore-Sales-Data
### Superstore Sales Data has 3 datasets which include Orders, Returns, and People.
---
### Table of contents
---

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning Preparations](#data-cleaning-preparations)
- [Exploratory Analysis](#exploratory-analysis)
- [Data Analysis](data-analysis)
- [Finding](#findings)
- [Recommendations](#recommendations)
- [References](#references)

## Project Overview
This project analysis is aimed at gaining insights on sales in different regions and the highest selling category. Through this insights i will be able to discover trends and make data driven decisions and also give recommendation.
 ![alt](https://github.com/Awasume-Marylin/Superstore-Sales-Data/blob/48fef12876fd652828aff5fb24e792bd71080056/Output/Total_profit.png)
 
 ### Data Sources
 
The datasets used for this analysis came from the SUPERSTORE_SALES.csv file which contains information of the different categories of products, the regions and their managers.

 ### Tools
 - Microsoft Excel - For data cleaning
 - Big Query - For analysis
   
 ### Data Cleaning Preparations
 1. Sorted data by profit
 2. Filtered to show only furniture category sales
 3. Changed data type of date using text to columns

### Exploratory Analysis

It involved exploring and manipulating the data of the superstore to answer the following;
- A cleaned dataset with standardized dates.
- SQL results showing regional profit, returns, and managers.
- Spreadsheet summary with
  - Total profit and average margin.
  - Furniture sales and regional return rates
    
 ### Data Analysis
 Includes some interesting commands like;
 ```sql
SELECT
 Region,
 SUM(Profit) AS Total_Profit,
FROM superstore.orders_dataset
GROUP BY Region
```
### Findings

From my analysisi, i made the following findings 
- The total profit made by each region
- The region with the highest profit
- The highest selling category
- Total orders that where returned in the regions

### Recommendations

Based on my analysis i would recommend the following;
-  Sales promotion and discounts in regions where there is low profit to maximize sales
-  checking products before they are sold to customers so any issues can be fixed to reduce the return rate
-  Enroll the managers of the regions who have low sales revenue in Sales bootcamps and trainings so that they can better 
  improve on their sales revenue and increase profit

### References
1. Tableau 

 


 

  

  
  

 








    

   


