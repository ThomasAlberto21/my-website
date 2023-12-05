---
sidebar_position: 7
---

# Number Data Type

The INTEGER data type in PostgreSQL is a representation for integers. This data type stores integers without decimals, both positive and negative, with a range of values depending on the size of the specific data type, such as `smallint`, `integer`, and `bigint`. The `smallint` data type stores small integers with a value range of approximately -32,768 to 32,767. The `integer` data type stores integers with a value range of around -2 billion to 2 billion, while `bigint` can hold larger integers, ranging from -9 quintillion to 9 quintillion.

Meanwhile, the FLOATING POINT data type in PostgreSQL is used to represent numbers with decimals, both positive and negative, and can accommodate values with commas (decimal points). This data type stores fractional numbers with floating point precision, such as `real` which uses 4 bytes to store floating point values with certain precision, and `double precision` which uses 8 bytes for higher precision. The `real` data type has a precision of approximately six decimal digits, while `double precision` has a precision of approximately 15 decimal digits.

### Documentation

https://www.postgresql.org/docs/current/datatype-numeric.html
