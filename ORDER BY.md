The `ORDER BY` keyword is used to sort the result-set in ascending or descending order.

The `ORDER BY` keyword sorts the records in ascending order by default. To sort the records in descending order, use the `DESC` keyword

```SQL
SELECT * FROM Customers  
ORDER BY Country DESC;
```

```SQL

SELECT 
    customer_number
FROM
    orders
GROUP BY 
    customer_number -- grouping
ORDER BY
    count(customer_number) DESC -- Order by aggregation
```