The `SELECT DISTINCT` [[statement]] is used to return only distinct (different) values.

Inside a table, a column often contains many duplicate values; and sometimes you only want to list the different (distinct) values.

```sql
SELECT DISTINCT Country FROM Customers;
```

you can also use combinatorial uniqueness by passing several arguments to DISTINCT

```sql
SELECT DISTINCT 
	column_name1, 
	column_name2
FROM 
	table_name;
```


SQL [[COUNT]] function with [[DISTINCT]] clause eliminates the repetitive appearance of the same data. The [[DISTINCT]] can come only once in a given select statement.

https://www.w3resource.com/sql/aggregate-functions/count-with-distinct.php


https://www.tutorialspoint.com/sql/sql-distinct-keyword.htm