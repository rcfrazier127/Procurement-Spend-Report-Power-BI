# For the fully interactive Power BI report, please view my portfolio on https://www.novypro.com/project/procurement-spend-report-power-bi
-------------------------------------------------------------------------------------------------------------------------------------------

# Procurement-Spend-Report in Power BI

### Introduction

The Procurement Spend Report is intended to provide a breakdown of an organization's spend, savings, and purchase orders, and the top drivers that influence those trends. 

### Data Preparation

The dataset required minimal preprocessing measures apart from standardization and formatting of data and the removal of irrelevant columns. 

<img width="755" alt="image" src="https://github.com/rcfrazier127/Procurement-Spend-Report-Power-BI/assets/63532077/98917195-77c0-4fb9-ac22-076a75903d70">

The column profiling shows no instance of errors and all data within the dataset is 100% valid with no blanks, mismatches, or irrelevant data.


### Data Model

<img width="1281" alt="image" src="https://github.com/rcfrazier127/Procurement-Spend-Report-Power-BI/assets/63532077/ea7e26a8-0997-4196-ae45-41c14e0d99be">

The star schema format was used to model the data and contains a central fact table Purchase Orders containing observational data and dimension tables Purchase Details, Accounts, Vendors, and a custom Date table. A main measure table and 2 additional measure tables, Cards/Arrows, and Metric Selection are also included.


# Report Pages

### Overview Page

<img width="816" alt="image" src="https://github.com/rcfrazier127/Procurement-Spend-Report-Power-BI/assets/63532077/a911ae92-9d99-4f36-8bd0-71a5fe02dba3">

The first report page features a structured breakdown of spend, savings, and orders. Custom KPI cards at the top of the page display individual trends, MoM/QoQ % change, and YTD actuals. Bar charts accompany the trend line visuals to display the month-to-month data in a columnar format. For the three metrics being measured, the top 5 procurement vendors are shown to highlight which entities are the greatest contributors. The data is then broken down by locale to view the distributions between domestic and international savings, spend, and orders. Domestic and international metric trends can also be filtered by date granularity to view and make further comparisons.

This page utilizes a number of tooltips to provide the user with as much context as possible while also avoiding redundancy. The KPI card trend tooltips allow for a more granular view of how metrics compare at a weekly basis during the selected time period. The dual-line chart tooltips are more dynamic in that they update visual context based on metric selection and also allow for columnar comparison of domestic/international data on the fly. 


### Details Page

<img width="816" alt="image" src="https://github.com/rcfrazier127/Procurement-Spend-Report-Power-BI/assets/63532077/8803e9d8-5f54-4316-80f2-cbb1e58d6074">

The second report page breaks down spend, savings, and orders by vendor account type and provides a tabular view of each individual vendor with the accompanying metrics. The tooltips on this page provide a view of monthly trends and a breakdown of how spend, savings, and orders are distributed across these categories. 
