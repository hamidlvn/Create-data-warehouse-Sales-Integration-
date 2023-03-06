# Create-data-warehouse-Sales-Integration-
In this project, we created a data warehouse and integrated all data sources with a different types of sources. We had a lot of challenges like integration of data and Date problem (Shamsi Date is not supported with Power BI) This project has 3 goals consist of:

- Get data from two sources (xlsvx,Acess)
- Data cleaning
- Modify the data structure
- Data integration
- How we can get data from a folder with unpredictable number of files
- create data warehouse
- Data Modeling
- Create Date Dimension

Main step of Transformation:
- get data from 1389 xlsvx (Transform data to power query)
- Clean data and unpivot it
- Add year column to table
- Change type
- Add 1390 xlsvx with based on 1389 xlsvx transformation step
- Append table 1389 and 1390 and disable enable load for 1389 and 1390 for performance reasons
- Create a template for the 1391-4 folder (It enables us to add many files to the folder and power BI load automatically to our data)
- Combine files in power query and select sample file for combining and doing some transformation like unpivot, create year column and..
- Append all previous tables with each other
- do same steps for 1395 folder
- Add Customer, Product and Geo tables to Power BI
- Do some transodrmation like cleaning these tables, merge these tables to sale table.
- for finding region of each customer we should join Geo table to Customer table and after that sale table to customer table
- Transfer Integrated data to Power BI environment
- Now we have a Integrated data!

Notice: At first we had 20 MB data (Not Integrated) and after that our data was integrated and we had just 88 KB power bi file. It is Awsome
