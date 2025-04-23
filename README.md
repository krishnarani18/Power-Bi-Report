Introduction to Power BI

Power BI is a Data Visualization and Business Intelligence tool that converts data from different data sources to interactive dashboards and BI reports. Power BI suite provides multiple software, connector, and services - Power BI desktop, Power BI service based on Saas, and mobile Power BI apps available for different platforms. 

Power BI Desktop

Dynamic reports and data models may be made with Power BI Desktop. Power BI is available in both 32-bit and 64-bit versions. It is free to download and not reliant on Microsoft Office. It is enriched with extensive visuals, built-in DAX functions, and numerous libraries. To download the latest version, you can use the following link: " https://powerbi.microsoft.com/en-us/downloads/ "

Power BI Desktop can handle multiple tasks, such as −

ETL(Extract, Transform, and Load) processes are implemented.
Fetch the data from numerous sources like Excel, Sharepoint, SQL Server, Azure, etc.
Generating a Data Model.
Examine the compiled data in a table or single report.
Develop a visual with your data in the report and publish the report.

Power BI Service

Power BI Service (Software as a Service - SaaS) is used to develop and publish the reports executed on Microsoft Azure. It can be accessed at the website https://app.powerbi.com

Power BI can be used for multiple tasks such as −

Developing interactive Dashboard
Viewing and modifying reports
Mutual collaboration and report distribution to others
Creation of apps and their subscription from Power BI service
The Power BI mobile app is used to view the reports and dashboards.


Major Components of Power BI

1. Power Query
   
It is the process of cleansing and transforming data and permits users to access datasets connecting from multiple sources. It is included on the Power BI desktop. Business users may view the data from distinct databases like MySQL, SQL servers, DB2, and many more.

2. Power View
   
It is a data visualization tool that assists users in developing stunning charts, and colorful maps, that turn data into a story.

3. Power Map
 
It is a 3D map visualization tool to identify geospatial data on Map visuals. It seamlessly helps organizations to examine the maximum sales production geographically, visualizing the demographic populations of specific regions.

4. Power Pivot

It is a Data Modelling technique that is used to create relationships between datasets. It performs complex computations by utilizing DAX functions.

5. Power Q & A
   
When dealing with giant datasets, it becomes crucial to get to know the in-depth details of the data. Luckily, it is done through natural language where users may ask questions and obtain the answer through Power Q & A.

Views in Power BI Desktop

Report View

You may add several pages while working on Report View. The bottom line shows three pages and if you are willing to add more pages then click on the + sign. A report must have a minimum single page where frequent visualization of data is achievable by selecting the fields onto the canvas.

Data View

You can traverse, delve into data, and recognize the data structure in the Data View. The simplest way is to load the data first into this tool and then select the Data View icon to inspect the table. Data manipulation like new measures, formatting, summarization, altering data types, and modifying field names can be employed in the Data View. Sorting and Number filters can also be applied to individual fields of the table.

Model View

You can view the relationship between tables, measures, and columns. The simple data model is understandable and easily refreshed by the users. On the other hand, the complex data model is difficult to construct and generalize. It would be recommended to develop the more complicated relationships using the Power query editor to filter the data and reshape the existing model.


DAX Introduction

DAX (Data Analysis Expressions) is a formula expression language and can be used in different BI and visualization tools. DAX is also known as function language, where the full code is kept inside a function. DAX programming formula contains two data types: Numeric and Other. Numeric includes - integers, currency, and decimals, while Other includes: string and binary objects.

DAX function can also include other functions, conditional statements, and value references.

DAX Functions

In Power BI, you can use different function types to analyze data and create new columns and measures. It includes functions from different categories such as −

Aggregate
Text
Date
Logical
Counting
Information

Power BI provides an easy way to see the list of all functions. When you start typing your function in the formula bar, you can see the list of all functions starting with that alphabet.

DAX Aggregate Functions

DAX has several aggregate functions, such as −

MIN
MINA
MINX
MAX
MAXA
SUM
SUMX
PRODUCT
PRODUCTX

DAX TEXT Functions


LEFT
RIGHT
UPPER
LOWER
CONCATENATE
CONCATENATEX

DAX DATE Functions

DATE
DATEDIFF
DATEVALUE
CALENDER
YEAR
YEARFRAC
HOUR
WEEKDAY

DAX Logical Functions

AND
OR
NOT
IF
SWITCH
TRUE
FALSE

DAX Counting Functions

DISTINCTCOUNT
COUNT
COUNTA
COUNTROWS
COUNTBLANK

DAX INFORMATION Functions

CONTAINS
CONTAINSSTRING
CONTAINSROW
COLUMNSTATISTICS
CONTAINSSTRINGEXACT

DAX Calculation Types

In Power BI, you can create two primary calculations using DAX −

Calculated columns
Calculated measures

When you navigate to the Modeling tab, you can see a New Column option at the top of the screen. This also opens the formula bar where you can enter DAX formula to perform the calculation. DAX - Data Analysis Expression is a powerful language used in Excel to perform calculations. You can also rename the column by changing the Column text in the formula bar.


