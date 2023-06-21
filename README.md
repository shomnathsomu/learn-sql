# SQL Tutorial

### What is SQL?
1. SQL stands for Structured Query Language
2. SQL lets you access and manipulate databases
3. SQL became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987

### What Can SQL Do?
1. SQL can execute queries against a database
2. SQL can retrieve data from a database
3. SQL can insert records into a database
4. SQL can update records in a database
5. SQL can delete records from a database
6. SQL can create new databases
7. SQL can create new tables in a database
8. SQL can create stored procedures in a database
9. SQL can create views in a database
10. SQL can set permissions on tables, procedures, and views

### The SQL SELECT Statement
- The SELECT statement is used to select data from a database.
- The data returned is stored in a result table, called the result set.
- SELECT Syntax
  <pre> SELECT column1, column2, ...
   FROM table_name; </pre> 
- If you want to select all the fields available in the table, use the following syntax:
  <pre> SELECT * FROM table_name; </pre>

### The SQL SELECT DISTINCT Statement
- The SELECT DISTINCT statement is used to return only distinct (different) values.
- SELECT DISTINCT Syntax
  <pre> SELECT DISTINCT column1, column2, ...
   FROM table_name; </pre>
- The following SQL statement lists the number of different (distinct) customer countries:
  <pre> SELECT COUNT(DISTINCT Country) FROM Customers; </pre>



