# SALES ANALYSIS

## Business Request 

The business request of this project is to develop a sales analysis dashboard that can be used by sales representatives and sales manager. Below are the objectives by 
both parties as well as the solution that I provided:

Role  | Objectives   |  To be developed
------------- | ------------- | ------------------
Sales Manager  | To follow better which customers and products sells the best  | Dashboard overview of internet sales which updates data once a day
Sales Manager  | To follow up the customers that purchased the most and to who we can sell more  | Dashboard that allows to filter data for each customer
Sales Representatives  | Identify best selling product  | Dashboard that allows to filter data for each product
Sales Representatives  | To identify sales overtime against budget | Dashboard with graphs and KPIs comparing against budget


## Data Cleansing & Transformation (SQL)

To create the necessary data model for analysis and fulfilling the business objectives defined above. Tables were extracted using SQL. One data source (Sales Budget) were provided in Excel format and were connected in the data model in a later step of the process.

Below are the SQL statements for cleansing and transforming the data.

[Click here for SQL Statement](https://github.com/munirauni/Sales_Analysis/blob/8342d846f0ba38719f62d001df728dc065f8ead1/SQL%20Statement.sql)


## Data Model

The cleaned datasets were then loaded into Power BI in order to develop data model. This data model shows how FACT_Budget has been connected to FACT_InternetSales and other necessary DIM tables.

![](/Docs/Assets/Data%20Model%20Sales.png   


## Sales Analysis Dashboard

Below is the finished sales analysis dashboard with necessary details and visualization which help in fulfilling business objectives stated by sales manager and sales representatives.

![](/Docs/Assets/Sales%20Management%20Dashboard.png)   

[Click here to access dashboard (PBIX file)](https://drive.google.com/drive/folders/1qvx3o1HbQ9uEvH0-qA_84OCWRxiF6yvA?usp=sharing)  
