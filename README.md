# SQL-Queries

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

### Interview Questions:

## 1: Diffrenece between `BETWEEN` and `IN`
`BETWEEN` operator is used to fetch rows based on range of values
```
For example,
SELECT * FROM Students 
WHERE ROLL_NO BETWEEN 20 AND 30;
```

The `IN` operator is used to check for values contained in specific sets. 
```
For example, 
SELECT * FROM Students 
WHERE ROLL_NO IN (20,21,23);
```
