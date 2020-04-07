# read 8

## data base

SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. And due to its simplicity, SQL databases provide safe and scalable storage for millions of websites and mobile applications.

## SELECT queries

To retrieve data from a SQL database, we need to write SELECT statements, which are often colloquially refered to as queries. A query in itself is just a statement which declares what data we are looking for, where to find it in the database, and optionally, how to transform it before it is returned. It has a specific syntax though

### to selesct specifec

SELECT column, another_column, …
FROM mytable;

### to select all

SELECT * 
FROM mytable;

### to filter

WHERE condition
    AND/OR another_condition
    AND/OR …; 

### to order

ORDER BY column ASC/DESC

### to selecet 

LIMIT num_times OFFSET start from;

### to join another table

INNER/LEFT/RIGHT/FULL JOIN another_table 
    ON mytable.id = another_table.matching_id