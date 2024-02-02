# SALES INSIGHT DASHBOARD USING POWERBI




## Retail Business Dashboard

A Real Time Project with problem statements based on Business / Functional Requirement Document. 
## PROBLEM STATEMENT

 ### Task 1
Calculate Total Revenue in Sales table.
### Task 2
 Calculate Total Cost in Sales table.
 ### Task 3
Calculate Gross Profit in Sales
### Task 4
Calculate Top 5 Sales Rep. who generated Gross Profit most
### Task 5
Breakdown Analysis by Product (drop or increase)
### Task 6
Calculate a Gross profit based on MoM growth Change (%)
### Task 7
Calculate a Gross profit based on QOQ growth Change (%)
### Task 8
Calculate a measure for AVG sales per day 



## Steps Followed in Project
####	Data Gathering / Requirement

1.	Sales (folder by year)
2.	Categories (Excel)
3.	Geography (Excel)
4.	Product (CSV / Excel)
5.	SalesRep (Excel)
6.	SubCategories (Excel)

•	Created a mechanism to load all the files from the sales folder in a single Sales fact table.

•	The mechanism needs to be resilient as:

	Removing a file from the sales folder does not create an error for missing files.

	Adding a new yearly sales file will automatically be loaded in the fact query upon refresh.
##	Data Transformations / Data Computations
•	Split the Country form the City in field “Location.

•	Created unique key (GeoKey) in Sales and Geography table

•	The Dimensional queries SalesRep and Sub Category need additional treatment. 
 
•	Created a small function that removes the “ID - ” part of the columns that we invoke and reuse for these two queries to clean the IDs.

•	Created a Date Calender for just to make work easier.
•   Used DAX function to calculate required measures and tables.
## Data Modeling
•	Created the Data Model by connecting all  the tables.
## 	Final Results
•	Uses the measures and calculations to assemble a sales report with different visuals to best show the Sales Insights.
![Screenshot (22)](https://github.com/RahulRayProject/Sales_Project/assets/158586581/aebfc983-4653-4853-aa91-a14ed5958d36)
