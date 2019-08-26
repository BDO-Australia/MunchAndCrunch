## Scenario

VanArsdel is a company that manufactures and sells sporting goods. The company has offices in the United States (US) and several other countries. Its sales comprise of US sales and International sales. VanArsdel’s sales come from its owned manufactured products, as well as other manufacturers’ products.

VanArsdel's US office stores the sales data on an Access database. VanArsdel International sales transactions are available as comma separated (CSV) files. They could be generated daily, either manually by someone, or automatically by an automated process. They are available in a dedicated folder. These CSV files have the same column structure as the sales table for the US sales that comes from the SQL Database.

You want to perform analysis on VanArsdel's worldwide sales data for the year 2000 to 2015. You need to bring all these data into Power BI Desktop before you can perform any analysis. Finally, you want to compare VanArsdel's country sales with the country population. You need to import the country population data from a less structured Excel report to Power BI.

## Lab Overview

This lab comprises of three exercises:

1. import data to Power BI Desktop from an SQL database running on Microsoft Azure.
2. import data from CSV files which resides in a file folder. You will append this new data to the corresponding existing data that comes from the SQL Database.
3. import data to Power BI Desktop from an Excel file that is less structured.


## WHAT YOU'LL NEED

- A computer with the latest version of Power BI Desktop installed on it.

- Access to the SQL Database containing VanArsdel's US sales data.

- 4 CSV files, containing VanArsdel’s international sales data:

    - CA Sales.csv
    - FR Sales.csv
    - DE Sales.csv
    - MX Sales.csv

- An Excel file containing country population data.