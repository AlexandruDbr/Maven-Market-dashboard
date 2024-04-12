# Maven-Market-dashboard

This Power BI dashboard is for Maven Market, a business which owns a variety of grocery stores of differing sizes across multiple countries including the United States, Canada and Mexico. The purpose of this dashboard is to provide an overview and insights based on the data provided.

## Overview

### Data set

As mentioned above, Maven Market is a business which owns grocery stores of varying sizes and profitability in several different countries in North America.

The raw data came in form of CSV files which was then transformed and cleaned in Power BI into a more workable set and was then closed and applied. This process was repeated for each table/CSV file until all 8 tables had been brought in and transformed.

The cleaning process for this data set was generally straightforward, requiring mainly header promotion, data type checking and corrections as well as basic creation of additional columns, such as: 

  * extration of birth year from a full birth date column "Customers" table
  * creating a new column "average retail price" for each product brand in "Products" table 
  * area code after the second delimiter which would make working with the data set easier later on. 
  * imported, appended and conducted data verification to ensure the correct number of rows and columns using Data Preview PBI features for transaction tables from 1997 and 1998.

There are 8 csv files provided by the company, nevetheless, date table was only a record of dates, other information was added by myself. I have have also created a blank table whose role is to centralise all the measures created.

 Maven Market table names:

    calendar
    customers
    products
    regions
    stores
    return_data
 

