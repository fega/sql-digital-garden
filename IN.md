The `IN` [[operator]] allows you to specify multiple values in a [[WHERE]] clause.
The `IN` operator is a shorthand for multiple [[OR]] conditions.

```SQL
WHERE _column_name_ IN (_value1_, _value2_, ...);
```

```SQL
SELECT _column_name(s)_  
FROM _table_name_  
WHERE _column_name_ IN (SELECT ...);
```