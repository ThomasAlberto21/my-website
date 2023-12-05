---
sidebar_position: 9
---

# Date & Time Data Type

The `DATE` data type in PostgreSQL is used to store date values (year, month, and day). The values that can be stored in this data type are in the format 'YYYY-MM-DD', where YYYY is the year (in four digits), MM is the month (in two digits), and DD is the day (in two digits).

`TIME` data type is used to store time values in 'HH:MM:SS' format in PostgreSQL. Stored values include hours (in two digits), minutes (in two digits), and seconds (in two digits).

When used together, the `DATE` and `TIME` data types can also be combined into the `TIMESTAMP` data type, which includes date and time information with details down to fractions of a second.

This data type is very useful for various database applications where time and date information is important to store, such as transaction records, activity schedules, or historical data. In PostgreSQL, manipulation of date and time data is also supported by a variety of built-in functions and operations that allow users to perform various operations, such as duration calculation, formatting, or grouping data by time.

### Documentation

https://www.postgresql.org/docs/current/datatype-datetime.html
