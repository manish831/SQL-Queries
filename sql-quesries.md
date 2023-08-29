-`SHOW DATABASES;`
// to show all the databases available in the system.

-`USE <database_name>;`
// to select a particular database to run queries on.

-`SHOW TABLES;` // to list down all the databases available in the selcted database.

-`CREATE <database_name>;` // to create a new database

```
CREATE TABLE <name>{
    <column_name 1> [datatype],
    <column_name 2> [datatype],
    .
    .
}
```

//to create a new table

-`DESC <table_name>;` // to show structure of the table

-`INSERT INTO <table_name> (col1, col2, ...) VALUES(<val1>, <val2>, ...);` // to insert value into a table

-`SELECT <col_name> FROM <table_name>;` // to get a data from the table.


-`SELECT * FROM <table_name> WHERE {conditions..};`

Conditions -> comparison of column data with your values
Examples ->
```
SELECT *FROM second WHERE DoB > '2020-01-01' OR Gender = 'Female';

SELECT _ FROM second WHERE NOT Gender = 'Female';
SELECT _ FROM second WHERE DoB > '2020-01-01' OR Gender = 'Female';
Select _FROM second WHERE DoB < '2020-01-01';
SELECT _ FROM second WHERE Name LIKE "_a%";
SELECT * FROM second WHERE Name LIKE "%a%";

SELECT * FROM second WHERE Gender = 'Female' ORDER BY DoB DESC Limit 2;
```
