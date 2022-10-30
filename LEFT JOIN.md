The `LEFT JOIN` keyword returns all records from the left [[table]] (table1), and the matching records from the right table (table2). The result is 0 records from the right side, if there is no match.

```sql
SELECT column_name(s)
FROM table1  
LEFT JOIN table2  
ON table1.column_name = table2.column_name;

-- In some databases LEFT JOIN is called LEFT OUTER JOIN.

-- Write your MySQL query statement below
SELECT
 firstName,
 lastName,
 Address.city,
 Address.state
FROM
        Person
    LEFT JOIN 
        Address
ON
 Person.personId = Address.personId;
 

```

https://leetcode.com/problems/customers-who-never-order/