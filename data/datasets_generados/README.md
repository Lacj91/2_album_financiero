# Explanation of different documents





USED IN THE POWER BI SOLUTION:

ds\_tables and dim\_tables: Contains the final version of the tables used to feed the Power BI solution. These tables were designed to support relationships following a Star Schema approach and to provide only the data required for the correct functioning of visuals and DAX measures.



CREATED FOR THE ANALYST VIEW ONLY:

v\_ds\_tables: Contains extended versions of the ds\_tables, created to provide additional contextual information. These tables are intended to support data analysis, validation, and troubleshooting, making it easier to understand the underlying data and resolve queries. They are designed for analyst use and are not intended for final-user consumption.



