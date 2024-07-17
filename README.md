## COMPANY DATABASE ANALYSIS
## Table of Contents

- [Project Overview](#project-overview)
- [Tools](tools)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Data Analysis](data-analysis)
- [Summary](summary)
- [References](references)

### Project Overview

This project demonstrates my work on a company database, utilizing SQL for various data operations and analysis. The primary objective was to efficiently manage and analyze the company's data, ensuring data integrity, optimizing queries, and providing actionable insights.

### Tools

- Excel
- SQL - Data Analysis [Download here](https://popsql.com/queries/-NgTdKFsQALBG4yFGr8s/company-employees-table?access_token=032290a9335c86f70fa06c1c65499958)

  ### Exploratory Data Analysis
  
  EDA involved exploring the database to answer key questions, such as:
  - What is the total employees in the company?
  - Top highest paid employees?
  - Average salary of the employees?
  - Employees who earned more than a particular amount?
 
### Data Analysis
Include some interesting code worked with

``` SQL
SELECT *
FROM employeess
WHERE salary > 50000;
```
``` SQL
SELECT
	employee_id,
	first_name,
	last_name,
	salary
FROM employeess
WHERE salary BETWEEN 35000 AND 50000;
```

``` SQL
SELECT 
	email,
	COALESCE(email, 'NO EMAIL PROVIDED')
FROM employeess;
```

### Summary
This project showcases my ability to design, manage, and analyze employee data using SQL. It demonstrates essential skills in database management, query optimization, and data analysis, resulting in actionable insights that support business decisions and HR strategies.

### References
- SQL By Giraffe Academy
- [freecode camp](freecodecamp.org)
- [W3 Schools](https://www.w3schools.com/sql/sql_top.asp)



# Car Sales Analysis
***
![](https://github.com/Ademola45455/DATA-PROJECTS/blob/main/INTRO.jfif)
***
## Objective:
This project aims to design and develop a dynamic and interactive Car Sales Dashboard using Power BI. The dashboard visualizes critical KPIs related to  car sales, helping  understand sales performance over time and make data-driven decisions.

****Disclaimer_****: All datasets and reports do not represent a company, institution, or country, but just a dummy dataset to demonstrate the capabilities of _PowerBi

## Problem Statement 1: KPI’s Requirement :
1.	Sales Overview :
.	Year-to-Date (YTD) Total Sales
•	Month-to-Date (MTD) Total Sales
•	Year-over-year (YOY) Growth in Total Sales
•	Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales


2.	Average Price Analysis :	
.	YTD Average Price
•	MTD Average Price
•	YOY Growth in Average Price
•	Difference between YTD Average Price and PTYD Average Price

3.	Cars Sold Metrics :
•	YTD Cars Sold
•	MTD Cars Sold
•	YOY Growth in Cars Sold
•	Difference between YTD Cars Sold and PTYD Cars Sold


## Problem Statement 2: Charts Requirement :
1.	YTD Sales Weekly Trend
2.	YTD Total Sales by Body Style
3.	YTD Total Sales by Color
4.	YTD Cars Sold by Dealer Region
5.	Company-Wise Sales Trend in Grid Form
6.	Details Grid Showing All Car Sales Information

Skills / Concepts Demonstrated :
The following PowerBi features were incorporated :
- Bookmarking
- DAX
- Formatting Visuals
- Page navigation
- Time Intelligence Fxn
- Modelling
- Quick Measures
- YTD, MTD, PYTD

## Modelling
The dimension tables joined the fact table with a many-to-one relationship.

Model Used :

![](https://github.com/Ademola45455/DATA-PROJECTS/blob/main/modelling.png)

You can interact with the report here (https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/6b3af657-224f-4262-bf13-8a172b87507b/ReportSection?experience=power-bi&clientSideAuth=0)

Conclusion / Recommendations :
YTD Sales are growing with a growth rate of 23.59%
YTD sales for each car was 28k and were reduced compared to last year by 220$ with MTD Avg Price of 28.6k$ 
There was a significant growth in the YTD Cars sold


# Call Center Analysis
***
![](https://github.com/Ademola45455/DATA-PROJECTS/blob/main/calll.jfif)
***
## Objective:
To provide comprehensive insights into call center operations by analyzing key metrics. This analysis aims to help call center management identify trends, optimize resource allocation, improve customer service efficiency, and make data-driven decisions.

   ## Problem Statement 
   - Total calls by Reason
   - Total calls by Sentiment
   - Total calls by State
   - Total calls by Calls_Centres

     


Skills / Concepts Demonstrated :
The following PowerBi features were incorporated :
- Bookmarking
- DAX
- Date Fxn
- Custom Charts
- SUM/SUMX
- Page navigation
- Time Intelligence Fxn
- Modelling
- Navigations


You can interact with the report here (https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/6b3af657-224f-4262-bf13-8a172b87507b/ReportSection?experience=power-bi&clientSideAuth=0)
![](https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/9f9c7ccd-be49-491b-9e78-21b0e9db8267/ReportSection?experience=power-bi)


Conclusion / Recommendations :
Los Angeles had the highest calls
Denver recorded the lowest calls
***
# Road Accident Analysis

![](https://github.com/Ademola45455/DATA-PROJECTS/blob/main/road%20accident.jfif)
***
## Objective:
To provide detailed insights into road accidents by analyzing important key metrics. This analysis aims to support road safety initiatives, inform policy decisions, and enhance public awareness by identifying trends and risk factors associated with road accidents.

   ## Problem Statement 
   - Total Accidebts and Casaulties by location
   - CY Fatal Casaulties by Road type for Current year
   - CY Casaulties by Area / Location & by Day / Night
   - Monthly Trend showing comparison for Current year and Previous year

     


Skills / Concepts Demonstrated :
The following PowerBi features were incorporated :
- DAX
- Filters and Slicers
- Custom Charts
- Power Query
- Time Intelligence Fxn
- Modelling

## Modelling
The dimension tables joined the fact table with a many-to-one relationship.

Model Used :

![](https://github.com/Ademola45455/DATA-PROJECTS/blob/main/road%20accident%20modelling%20.png)
***


You can interact with the report here (https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/e5db7c8f-87b7-4d7d-94db-1720d27eb8f4/ReportSection?experience=power-bi&clientSideAuth=0)
![](https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/9f9c7ccd-be49-491b-9e78-21b0e9db8267/ReportSection?experience=power-bi)







    





  


  


