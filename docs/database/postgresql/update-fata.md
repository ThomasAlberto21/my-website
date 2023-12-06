---
sidebar_position: 15
---

# Update Data

How to update data table use PostgreSQL?

you can type following command like this

```sql
-- Example 1
UPDATE products
SET category = 'Makanan'
WHERE id = 'P0001';

-- Example 2
UPDATE products
SET category    = 'Makanan',
    name        = 'Bakso',
    description = 'Bakso Enak',
    price       = 10000
WHERE id = 'P0001';

-- Example make changes to existing values
UPDATE products
SET price = price + 1000
WHERE id = 'P0001';
```
