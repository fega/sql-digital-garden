The `DELETE` [[statement]] is used to delete existing records in a [[table]].

```sql
DELETE FROM _table_name_ WHERE _condition_;
```

```sql
DELETE p1 -- Notice that I mention p1, which is the one I want to delete

FROM person p1, person p2 -- use same table twice to do comparisons
WHERE
    p1.email = p2.email AND p1.id < p2.id

```

https://leetcode.com/problems/delete-duplicate-emails/