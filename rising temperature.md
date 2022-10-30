https://leetcode.com/problems/rising-temperature/

```sql
# Write your MySQL query statement below
SELECT 
    w1.id as id -- tell how to return the id 
FROM 
    weather as w1 -- rename table for easier reference
WHERE
    w1.temperature > 
    ( -- subquery, that goes to the same table
        SELECT 
	        temperature 
	    FROM 
		    weather as w2 --required renaming to reference w2
	    WHERE 
		    DATEDIFF(w1.recordDate, w2.recordDate) = 1 -- comparator should only return 1 element
	) 


```
[[DATEDIFF]]
