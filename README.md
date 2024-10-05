This project is based on a computer hardware business facing challenges in a dynamically changing market.
Data consists of tables related to sales, date, markets, products and transactions.
I have used data from a dummy SQL file to load in MySQL workbench and then further connected it to PowerBI to create visualizations.

After uploading the data into MySQL Workbench I have done some basic data check using SQL queries in order to check data quality.
Then I have loaded the data into PowerBI and done some data cleaning
Example:
1. In Markets table - I have removed rows where the value of the zone was blank
2. In the sales transaction table - I have Removed all the rows where the sales amount is less than 0 or equal to 0.
   Also there were some records with sales in USD so I have converted the sales amount from USD to INR for those records.
3. Created a new measure - Sales QTY and Revenue.

Here's the final Dashboard
![Alt text](https://github.com/kaur-b76/Sales-Insights/blob/main/Screenshot%202024-10-05%20at%2018.42.04.png)



