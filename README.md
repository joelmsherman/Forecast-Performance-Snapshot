# Forecast Performance Monitoring and Next Year Outlook
![image](https://github.com/joelmsherman/Forecast-Performance-Snapshot/blob/master/Images/image.jpg)

## Background
The finance team of XYZ Holdings, LLC has been using a variety of manual methods and spreadsheets to track variances among its key performance indicators (KPIs).  The team uses one process and spreadsheet to manually input data from its finance system in order to assess actual trends over time. They use another process and spreadsheet to store data from their budgeting system, alongside an archive of forecasts from their financial planning group.  They combine these two spreadsheets into a third spreadsheet in order to look at variances between actuals, budgets for the current year, and new forecasts as they are available.  A team of 4 people run this process on a monthly basis, and it takes several days to complete.     

## Objective
The analysis seeks to provide XYZ finance managers with an on-demand, monthly view of KPI trends, as well as a full year assessment of how actuals have performed relative to previous year, and what the most current forecast shows for the following year.  

## Methods
The analysis is conducted in the following steps.

### Data Extraction and Prep
Actual and forecast data from XYZ's finance and forecast databases, respectively, was extracted and transformed using KPI definition logic provided by the team.  The data was landed in a SQL Server database optimized for analytical loads, and set to refresh nightly. Data was validated by finance team staff. The tool connects directly to the SQL Server warehouse, and is refreshed on a monthly basis.    

### Data Analysis
The tool is coded in python and sql and available as an interactive notebook.   

## Results
The interactive notebook is available [here](https://app.hex.tech/5b266aaf-b343-4ae7-bdea-218e8fe3001f/app/06857f32-ee38-46ce-b830-2793dca8cc9c/latest)

## Value Proposition
The data integration and interactive notebook significantly streamlines the process of moving from raw data to insight for the XYZ finance team.  KPI variances between previous year, current year actuals, and next year forecasts are readily available on-demand.  This work has significantly reduced the opportunity costs for finance team staff, freeing them up for higher value work at XYZ.  