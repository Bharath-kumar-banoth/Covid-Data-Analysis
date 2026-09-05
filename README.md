# Analyzing COVID-19 Data: Insights with Excel, SQL, and Tableau

In a challenging era, technology and public health convergence take center stage. In this data analytics project, we delve into COVID-19 data using practical tools such as Excel, SQL, and Tableau. Our dataset includes information about COVID-19 deaths, vaccination rates, and related metrics. It highlights the pandemic's impact on lives and vaccination efficacy. 


To import Excel tables into a new database in SQL Server Management Studio (SSMS), follow these step-by-step instructions: 

1.	Open SQL Server Management Studio: Launch SQL Server Management Studio and connect to your SQL Server instance if you haven't already.
  
2.	Create a New Database: If you haven't already created the "SQL project 1 Covid" database, you can do so by right-clicking on "Databases" in the Object Explorer and selecting "New         Database." Name it "SQL project 1 Covid" and click "OK" to create the new database.
	
3.	Prepare Your Excel File: Make sure your Excel file (e.g., "covid_vaccines.xlsx" and "covid_deaths.xlsx") is well-structured with clear column names. Save it in a location accessible     to the SQL Server.
  
4.	Import Excel Tables: Now, you'll use the SQL Server Import and Export Wizard to import the Excel tables into your new database.
   
    a. In SQL Server Management Studio, right-click on your "SQL project 1 Covid" database in the Object Explorer, select "Tasks," and then choose "Import Data."
  
    b. The SQL Server Import and Export Wizard will open. Click "Next" to begin.
  
    c. Choose a Data Source:
  
        •	Select "Microsoft Excel" as the data source.
    
        •	Click "Browse" to locate your Excel file (e.g., "covid_vaccines.xlsx").
    
        •	Choose the appropriate version of Excel (Excel 97-2003 or Excel 2007 or later).
    
        •	Click "Next."
  
    d. Choose a Destination:
        •	In the "Destination" dropdown, select "SQL Server Native Client 11.0" (or the appropriate SQL Server version).
    
        •	In the "Server Name" field, enter your SQL Server instance name.
    
        •	Select "Use Windows Authentication" or provide the necessary SQL Server credentials.
    
        •	In the "Database" dropdown, select "SQL project 1 Covid."
    
        •	Click "Next."
      
    e. Specify Table Copy or Query:
  
        •	Choose "Copy data from one or more tables or views" and click "Next."
    
    f. Select Source Tables and Views:
  
        •	Choose the Excel worksheet (table) you want to import (e.g., "covid_vaccines$").
    
        •	Click "Next."
    
    g. Review Mapping:
  
        •	Confirm that the columns from your Excel table are correctly mapped to the columns in your SQL table.
      
        •	Click "Next."
    
    h. Specify Table Copy Options:
    
        •	Choose whether to run the package immediately or save it as an SSIS package.
    
        •	Click "Next."
    
    i. Complete the Wizard:
  
        •	Review your selections and click "Finish" to start the import process.
    
     j. The Wizard will execute the package and import the Excel data into your "SQL project 1 Covid" database.
  
5.	Repeat for Other Excel Table: Follow the same process to import the other Excel table (e.g., "covid_deaths.xlsx") into the same database.
   
  
6.	Verify Data: Once both tables are imported, you can verify the data by querying them in SSMS.

   
That's it! You have successfully imported Excel tables into your "SQL project 1 Covid" database in SQL Server Management Studio.

