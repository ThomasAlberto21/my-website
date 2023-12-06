---
sidebar_position: 19
---

# Limit Clause

`LIMIT` clause is used to limit the data amount returned by the `SELECT` statement. `LIMIT` clause is used with the `SELECT` statement to restrict the number of rows in the result set returned by the `SELECT` statement.

#### How to use limit in PostgreSQL?

you can type following command like this

```sql
-- Example limit
SELECT *
FROM products
WHERE price > 0
ORDER BY price DESC
LIMIT 2;
```
