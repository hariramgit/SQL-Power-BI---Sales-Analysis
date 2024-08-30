# SalesAnalysis_SQL_PowerBI


# Project Setup and Objectives

This project involves using SQL Server (SQL Express) and Power BI Desktop to analyze and visualize data. The primary focus will be on working with Data Warehouse (DW) data and Lightweight (LT) data. To get started, follow the provided instructions to obtain and restore the backup of both datasets.


## Objective: Enhancing Internet Sales Reporting with Interactive Dashboards

We are looking to transition from static reports to interactive visual dashboards to enhance our internet sales reporting. The primary goal is to provide a comprehensive view of sales performance by product, client, and sales over time. This shift will allow for more dynamic analysis and better decision-making. Here are the key objectives for this initiative:

#### Sales Analysis by Product and Client:

Provide detailed insights into sales performance by product, including quantities sold and revenue generated.
Analyze sales data by client to understand purchasing patterns, client preferences, and overall customer value.

#### Time-Based Sales Trends:

Visualize sales trends over time to identify seasonal patterns, growth rates, and market fluctuations.
Enable historical comparisons by focusing on a two-year analysis window, allowing us to review sales performance against historical data.

#### Salesperson Performance and Filtering:

Include the ability to filter sales data by salesperson, recognizing that each salesperson handles different products and clients. This functionality will help evaluate individual performance and tailor strategies accordingly.

#### Comparison Against Budget:

Integrate budget data from the provided 2021 spreadsheet to compare actual sales performance against budgeted targets.

Develop visual indicators to highlight variances from budgeted figures, assisting in performance assessments and financial planning.
By moving to a dynamic dashboard format, we aim to provide stakeholders with a more interactive and user-friendly platform for monitoring and analyzing internet sales. This will enhance our ability to make data-driven decisions, optimize sales strategies, and ultimately drive business growth




### Setup
- This project requires SQL Server (SQL Express), Power BI Desktop
- We will work with backup Data Warehouse (DW) data and Lightweight (LT) data. Obtain data and restore following instructions from [here.](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms)
- Compare DW and LT data to understand the difference between structured and unstructured data. We will primarily be working with Data Warehouse data.
- Update Data Warehouse data using [sql script.](https://github.com/hariramgit/SQL-Power-BI---Sales-Analysis/blob/main/Update_base_DB_SQL)

  

## Data Preparation and Update:

#### Data Restoration:
Restore the provided Data Warehouse (DW) and Lightweight (LT) data backups to your SQL Server instance.
#### Data Update:
Execute the provided SQL script to update the Data Warehouse data accordingly.
#### Business Requirements and User Stories:
Review the provided business request, demand overview, and user stories documentation. This will help you understand the problem we aim to solve through data analysis and what constitutes a successful solution.



## Data Cleaning and Transformation:

### Understand Key Concepts:

Differentiate between FACT tables and Dimension tables.
Use the Business Request form to identify the tables of interest.

### Data Preparation:

1.Select the relevant columns by preparing and transforming data using T-SQL. Key tasks include:
2.Renaming and combining columns
3.Adding comments in the SQL script
4.Formatting SQL statements for readability
5.Utilizing SQL functions and clauses such as WHERE, ORDER BY, LEFT JOIN, CASE(), and ISNULL()

### Clean the Data using T-SQL
- Understand the difference between FACT tables & Dimension tables.
- Identify which tables in the data are of interest with the help of the Business Request form.
- Choose which columns are of interest to export by preparing and transforming these columns in SQL using concepts such as: renaming columns, combining columns, commenting in SQL script, formatting of SQL statements, WHERE clause, ORDER BY, LEFT JOIN, CASE() function and ISNULL() function.

  

## Dashboard Development in Power BI:

### Data Loading:
Import the cleaned and prepared data into Power BI.

### Data Organization and Model Preparation:
Organize and prepare tables for analysis.
Establish relationships between tables to create a coherent data model.
Import the Fact_Budget table and calculate necessary measures.

### Dashboard Design:
Design a comprehensive dashboard that includes the following elements:

### Visual Elements:
-Import custom visuals where necessary.
-Create various charts and graphs, including pie charts, line charts, bar charts, map graphs, and Top 10 graphs.
-Utilize gradient color schemes in bar charts to enhance visual appeal.

### Data Representation:
Display customer details using pivot tables and other relevant visual formats.



### Dashboard
- [Download the file](https://github.com/hariramgit/SQL-Power-BI---Sales-Analysis/blob/main/Final%20Report.pbix) and open in Power BI Desktop for interactive viewing.



![Sales Dashboard Screenshot](https://github.com/hariramgit/SQL-Power-BI---Sales-Analysis/blob/main/Screenshot%202024-08-30%20153211.png)


