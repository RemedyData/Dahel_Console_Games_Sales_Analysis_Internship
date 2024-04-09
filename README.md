# Dahel_Console_Games_Sales_Analysis_Internship
Dahel Consultant and Techies: Sales Analysis; A deep dive into Console Sales data, aimed at extracting valuable  insights to enhance strategic decision-making.
(*The picture below is gotten from SVET Website*). 



![image](https://github.com/RemedyData/Dahel_Console_Games_Sales_Analysis_Internship/assets/137626163/8f3bdeb7-9ef7-454d-9259-797fb88487a1)





***Disclaimer:*** This is not a real company as we know this is a dataset compiled by Dahel Consultant Techies for Internship purposes. 


## Introduction

This is a console game performance analysis. It is done by analyzing data from  two tables namely Consolegames and Consoledates. The formaer table consist of 10 fileds while the later consist of 5 fields. I used SQL to analyse the entire dataset throughout the project. 

## Problem Statement

The goal of this analysis is to:

- Calculate what % of local sales were made in North America
- Extract a view of the console game titles ordered by platform name in ascending order and year of release in descending order.
- Extract the first four letters of the publisher’s name for each game title
- Display all console platforms which were released either just before Black Friday or just before Christmas ( in any year).
- Order the platforms by their longevity in ascending order (i.e the platform which was available for the longest at the bottom).
- Demonstrate how to deal with the Game_Year column if the client wants to convert it to a different data type.
- Provide recommendations on how to deal with missing data in the file. 



## Skills and Concepts Demonstrated:

Data Retrieval:
- SQL queries to retrieve data from one or more database tables based on specified criteria.
- Use of the SELECT statement and its various clauses such as WHERE, ORDER BY, and LIMIT.

Data Filtering and Sorting:
- Filtering data based on specific conditions using the WHERE clause.
- Sorting data using the ORDER BY clause to organize results in ascending or descending order based on specified columns.

Data Aggregation:
- Proficiency in using SQL aggregate functions (e.g., SUM, AVG, COUNT, MAX, MIN) to perform calculations on groups of data.
- Knowledge of the GROUP BY clause to group rows with similar characteristics together for aggregate function calculations.

Data Transformation:
- Ability to manipulate and transform data using SQL functions such as DATE functions, string functions, and mathematical functions.
- Understanding of how to convert data types and format data for analysis.

Data Joining:
- Skill in joining data from multiple tables using various types of JOIN operations (e.g., INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN).
- Knowledge of how to specify join conditions and handle NULL values when joining tables.

Subquerying and CTEs:
- Proficiency in using subqueries (nested queries) to filter or aggregate data based on the results of another query.
- Understanding of Common Table Expressions (CTEs) to create temporary result sets for use within a larger query.

Window Functions:
- Ability to utilize window functions to perform calculations across a set of rows related to the current row.
- Skills in ranking data, calculating moving averages, and computing cumulative sums using window functions.

Data Analysis and Interpretation:
- Competency in analyzing SQL query results to derive insights and make data-driven decisions.
- Interpretation of query results in the context of business requirements and objectives.

Optimization and Performance Tuning:
- Knowledge of SQL query optimization techniques to improve query performance, such as indexing, query restructuring, and using appropriate join strategies.

Error Handling and Debugging:
- Skill in identifying and resolving errors in SQL queries, including syntax errors, logic errors, and data-related issues.



   ---


  ## Data Source:
  
The dataset for the work is gotten from Dahel Consultant Techies. It consists of two tables namely Consolegames and Consoledates. The formaer table consist of 10 fileds and 15,980 records while the later consist of 5 fields and 31 records. I studied the dataset well to gain proper insight into the dataset. You can find a link to download the Consolegames dataset [here:](https://docs.google.com/spreadsheets/d/1XUU8BoYPHLIiyqI9_kYFIsfWXM_7SQitscClUK3rQNo/edit?usp=drive_link) As for the consoledates dataset, you can download it [here](https://docs.google.com/spreadsheets/d/1XUU8BoYPHLIiyqI9_kYFIsfWXM_7SQitscClUK3rQNo/edit?usp=drive_link)

   ---

## Data Transformation:

**Step 1:**
- After downloading the dataset, I imported it into POWERBI.

**Step 2:**
- It loaded the dataset authomatically in Power Query Editor but there was no cleaning needed because it was already a cleaned data.

**Step 3:**
- For the column cost I assumed it was the cost of production  because I wasn’t sure if It was the selling price or the cost of production 

**Step 4:**
- After checking the columns, it was loaded into POWERBI for visualization.

---


## Data Analysis:

Several expressions and functions were made to arrive at the desired KPI or Metrics.
I arrived at a report with a single dashboard consisting of different visuals such as bar chart, doughnut chart, line chart, slicer, and KPIs, giving the summary of the insights gained into the company's performance.

## :
The dashboard conveys information about the following key areas:
- Total number of orders
- The total number of pies produced
- Flavor with the highest order
- Means of order (pre order or in store purchase)
- Relationship between the cost and quantity 
- The total cost per year and month


![Dahel_Pie_Bakery](https://github.com/RemedyData/Dahel_Techies_Pie_Day_Sales_Analysis_Internship/assets/137626163/f52b6f58-09fc-4689-be80-52c050396006)



## Analysis

Summary of the insights gained into the chess Game performance: 

- A total of 2,773 orders were placed between 1st of June, 2019 – 1st of November 2021.
- A total of 8333 pie was produced during that period. The total cost it took to produce the 8333 pie was $96,922.50
- 51.21% of the pie produced was pre-order while 48.79% of the pie were purchased in store.
- There were over 6 flavors of pie and the Apple flavor had the highest cost of production followed by Strawberry Rhubarb
- About 52.51% of pie ordered where whole pie and 47.49% were sliced.
- The higher the quantity, the higher the cost.


## Recommendation

- Due to the uncertainty whether the cost provided is the selling price or the cost of production much recommendation can't really be given. 
- There’s no way to know which pie flavor generates more profit or the one with the most profit.
- The Apple flavor is the most ordered pie and it should always be made available. 
- The PIE should still be made available as both pre-order and in store purchase because there’s no much difference in how customer choose to purchase their price. 
- Both whole pie and sliced pie should also made available since customers placed other for both and the margin between both isn’t much. About 52.51% of pie ordered where whole pie and 47.49% were sliced.


---

### Thank you for reading.

I am open for entry-level to mid_level data analyst role.
