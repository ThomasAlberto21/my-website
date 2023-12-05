---
sidebar_position: 11
---

# Table

## See Table

#### How to see table in database PostgreSQL in terminal linux?

you can type following command in terminal

```bash
\dt
```

#### How to see table in database PostgreSQL use DataGrip and terminal linux?

you can type following command

```sql
SELECT *
FROM pg_tables
WHERE schemaname = 'public';
```

## Create Table

#### How to create table in terminal linux or DataGrip?

you can type following command

```sql
CREATE TABLE barang
(
    kode   INT,
    nama   VARCHAR(100),
    harga  INT,
    jumlah INT
);
```

## See Structure Table

#### How to see structure table in terminal linux?

you can type following command in terminal

```bash
\d name_table;
```

## Alter Table

#### How to alter table in terminal linux or DataGrip?

you can type following command

```sql
-- Add Column
ALTER TABLE barang
    ADD COLUMN deskripsi text;

-- Delete Column
ALTER TABLE barang
    DROP COLUMN deskripsi;

-- Change Name Column
ALTER TABLE barang RENAME COLUMN kode TO kode_barang;
```

## Null Value

By default, when we create a column, the column can have a `NULL` value, if we don't want to receive a NULL value, we
can add `NOT NULL` when creating the column

you can type following command

```sql
CREATE TABLE barang
(
    kode   INT          NOT NULL,
    nama   VARCHAR(100) NOT NULL,
    harga  INT          NOT NULL,
    jumlah INT          NOT NULL
);
```

## Default Value

When we save data into a table, then we only save some columns (not all), the columns that we don't give a value to are
defaulted to NULL. If we want to change the default value, we can add the `DEFAULT` command when creating the column

you can type following command

```sql
CREATE TABLE barang
(
    kode         INT          NOT NULL,
    nama         VARCHAR(100) NOT NULL,
    harga        INT          NOT NULL DEFAULT 1000,
    jumlah       INT          NOT NULL DEFAULT 0,
    waktu_dibuat TIMESTAMP    NOT NULL DEFAULT CURRENT_TIMESTAMP
);
```

## Truncate Table

#### How to truncate table in terminal linux or DataGrip?

you can type following command

```sql
-- Delete data in the table
TRUNCATE TABLE barang;
```

## Drop Table

#### How to drop table in terminal linux or DataGrip?

you can type following command

```sql
-- Delete table
DROP TABLE barang;
```
