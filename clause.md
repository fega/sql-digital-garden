https://stackoverflow.com/a/15629633

The following statement:

```sql
SELECT foo FROM bar JOIN quux WHERE x = y;
```

is made up of the following clauses:

-   WHERE x = y
-   SELECT foo
-   FROM bar
-   JOIN quux