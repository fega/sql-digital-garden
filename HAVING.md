The `HAVING` [[clause]] was added to [[SQL]] because the [[WHERE]] keyword cannot be used with [[aggregate functions]].

```sql
SELECT column_name(s) 
FROM table_name 
WHERE condition 
GROUP BY column_name(s) 
	HAVING condition 
ORDER BY column_name(s);
```

```sql
-- Write your MySQL query statement below
select email 
    from person 
    group by email 
        having count(email) > 1;
```