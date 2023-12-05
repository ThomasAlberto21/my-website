---
sidebar_position: 13
---

# Primary Key

Primary key is a most important key in a table. It is a unique key in a table. It can not be null and duplicate,
Function of primary key is to identify each row in a table and relation between tables.

How to create primary key in PostgreSQL?

you can type following command

```sql

-- Create table with primary key
CREATE TABLE products
(
    id          VARCHAR(10)  NOT NULL,
    name        VARCHAR(100) NOT NULL,
    description TEXT,
    price       INT          NOT NULL,
    quantity    INT          NOT NULL DEFAULT 0,
    created_at  TIMESTAMP    NOT NULL DEFAULT CURRENT_TIMESTAMP
        PRIMARY KEY (id)
);

-- Add primary key when table already created
ALTER TABLE products
    ADD PRIMARY KEY (id);
```