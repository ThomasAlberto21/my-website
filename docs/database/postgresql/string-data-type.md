---
sidebar_position: 8
---

# String Data Type

The STRING data type in PostgreSQL is a data type used to store text or character data. This STRING data type has several variations, such as:

`CHAR(n)` : Stores a text string of fixed length n. If the length of the entered string is shorter than n, it will be padded with spaces to reach the specified length.

`VARCHAR(n)` : Stores a variable length text string of up to n characters. This data type is more efficient in using storage space because it only stores as much as is needed for each value.

`TEXT` : Stores a variable length text string with no specific length restrictions. This data type is suitable for storing long text or text that varies in length.

This STRING data type allows storing various types of text data, such as plain text, JSON format text, XML, or even binary data in hexadecimal text form. They can be used to store information such as names, descriptions, addresses, and other text data.
