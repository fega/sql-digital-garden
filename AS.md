The `AS` [[command]] is used to rename a [[column]] or [[table]] with an [[alias]].

An [[alias]] only exists for the duration of the [[query]].


```sql
SELECT CustomerID AS ID, CustomerName AS Customer  
FROM Customers;
```
