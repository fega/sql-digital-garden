A field with a NULL value is a field with no value.

If a field in a table is optional, it is possible to insert a new record or update a record without adding a value to this field. Then, the field will be saved with a NULL value.

It is not possible to test for NULL values with comparison operators, such as [[=]], [[<]], or [[<>]].

We will have to use the `IS NULL` and `IS NOT NULL` operators instead.