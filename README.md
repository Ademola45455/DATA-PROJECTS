## ADEMOLA'S PROJECTS ON DATA ANALYSIS
## Table of Contents
- [Company Database](SQL)
- [Project Overview](#project-overview)
- [Tools](tools)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Data Analysis](data-analysis)
- [Summary](summary)
- [References](references)

### Project Overview (SQL)

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

#### Data Sources

Car Sales Data: The primary dataset used for this analysis is in the "Car-Salesdata.xlsx" file, containing detailed information about each cars.

 ### Tools
- Excel - Data Cleaning
  - [Download here](https://docs.google.com/spreadsheets/d/1uNPGZN58_9hA1N50murs20e4zpQ6z-hx/edit?usp=drive_link&ouid=118278122332705089450&rtpof=true&sd=true)
- PowerBi - Creating reports

 ### Data Cleaning/Preparation:
  In the initial data preparation phase, I performed the following tasks:
  1. Data loading and inspection.
  2. Handling missing values.
  3. Data cleaning and formatting.

 ## Problem Statement 1: KPI’s Requirement :
i.	Sales Overview :
.	Year-to-Date (YTD) Total Sales
•	Month-to-Date (MTD) Total Sales
•	Year-over-year (YOY) Growth in Total Sales
•	Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales


ii.	Average Price Analysis :	
.	YTD Average Price
•	MTD Average Price
•	YOY Growth in Average Price
•	Difference between YTD Average Price and PTYD Average Price

iii.	Cars Sold Metrics :
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

   
![CAR ](https://github.com/user-attachments/assets/32f40bec-1bb7-407e-804e-372ffc167bd5)

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

You can interact with the report [here] (https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/6b3af657-224f-4262-bf13-8a172b87507b/ReportSection?experience=power-bi&clientSideAuth=0)

Conclusion / Recommendations :
YTD Sales are growing with a growth rate of 23.59%
YTD sales for each car was 28k and were reduced compared to last year by 220$ with MTD Avg Price of 28.6k$ 
There was a significant growth in the YTD Cars sold

### Limitations
I had to remove all zero values from my data columns they would have affected the accuracy of my conclusion from the analysis.


## Call Center Analysis
***
![](https://github.com/Ademola45455/DATA-PROJECTS/blob/main/calll.jfif)
***
## Objective:
To provide comprehensive insights into call center operations by analyzing key metrics. This analysis aims to help call center management identify trends, optimize resource allocation, improve customer service efficiency, and make data-driven decisions.

#### Data Source [download here](https://drive.google.com/file/d/15wcdUhtT0q7WfU84p2RVl_VPZTD36k_N/view?usp=drive_link)

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


![CALL CENTER](https://github.com/user-attachments/assets/fa8fcd20-f4b8-451f-8d39-fc051e51da22)

You can also interact with the report [here] (https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/6b3af657-224f-4262-bf13-8a172b87507b/ReportSection?experience=power-bi&clientSideAuth=0)
![](https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/9f9c7ccd-be49-491b-9e78-21b0e9db8267/ReportSection?experience=power-bi)


Conclusion / Recommendations :
Los Angeles had the highest calls
Denver recorded the lowest calls
***

## Road Accident Analysis
---
![](https://github.com/Ademola45455/DATA-PROJECTS/blob/main/road%20accident.jfif)
***
## Objective:
To provide detailed insights into road accidents by analyzing important key metrics. This analysis aims to support road safety initiatives, inform policy decisions, and enhance public awareness by identifying trends and risk factors associated with road accidents.

   ## Problem Statement 
   - Total Accidebts and Casaulties by location
   - CY Fatal Casaulties by Road type for Current year
   - CY Casaulties by Area / Location & by Day / Night
   - Monthly Trend showing comparison for Current year and Previous year

     

![ROAD ACCIDENT](https://github.com/user-attachments/assets/a44fc4fb-28c2-4efc-94a1-87b2804d737b)

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


You can also interact with the report [here] (https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/e5db7c8f-87b7-4d7d-94db-1720d27eb8f4/ReportSection?experience=power-bi&clientSideAuth=0)
![](https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/9f9c7ccd-be49-491b-9e78-21b0e9db8267/ReportSection?experience=power-bi)




# Electric Vehicle Analysis
---
![](https://github.com/Ademola45455/DATA-PROJECTS/blob/main/electric%20car%20iamge.png)
***
## Objective:
To provide detailed insights into electric vehicle adoption and performance by analyzing key metrics. This analysis aims to analyze the technological advancements and efficiency of electric vehicles by determining the average electric range, identifying and comparing the prevalence of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs), and assessing BEV dominance in the dataset.

   ## Problem Statement 
   - Determine the average electric range of the electric vehicles to gauge the technological advancements and efficiency of the EVs.
   - Identify and analyze the total number of Battery Electric Vehicles (BEVs) in the dataset.
   - The percentage of BEVs relative to the total number of electric vehicles, providing insights into the dominance of fully electric models.
   - Identify and analyze the total number of Plug-in Hybrid Electric Vehicles (PHEVs) in the dataset.


Skills / Concepts Demonstrated :
The following PowerBi features were incorporated :
- DAX
- Statistical analysis
- Data cleaning and transformation
- Power Query
- Time Intelligence Fxn
- Modelling
- Trend analysis


![ELECTRIC](https://github.com/user-attachments/assets/92ab1ee8-136a-4b6b-8b60-636c5b46bb33)

## Modelling
The dimension tables joined the fact table with a one-to-one relationship.

Model Used :

![](https://github.com/Ademola45455/DATA-PROJECTS/blob/main/electric%20modelling.png)
***


You can also interact with the report [here] (https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/a43b8408-0c15-4835-8ae3-624412bb7333/ReportSection?experience=power-bi)
![](https://app.powerbi.com/groups/75189acb-9b13-476a-8c6b-283daf4d96bc/reports/9f9c7ccd-be49-491b-9e78-21b0e9db8267/ReportSection?experience=power-bi)



    





  


  


