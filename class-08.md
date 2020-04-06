# SQL:

**Structured Query Language** 

- is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. And due to its simplicity, SQL databases provide safe and scalable storage for millions of websites and mobile applications.

**SELECT queries**

- They are often colloquially refered to as queries. A query in itself is just a statement which declares what data we are looking for, where to find it in the database, and optionally, how to transform it before it is returned. 

- It has a specific syntax though, which is what we are going to learn in the following exercises.

**table in SQL**

- type of an entity (ie. Dogs), and each row in that table as a specific instance of that type

- This means that the columns would then represent the common properties shared by all instances of that entity 

- `SELECT column, another_column,`

**Queries with constraints**

- In order to filter certain results from being returned, we need to use a WHERE clause in the query. 

- The clause is applied to each row of data by checking specific column values to determine whether it should be included in the results or not.

**Filtering and sorting Query results**

- SQL provides a convenient way to discard rows that have a duplicate column value by using the DISTINCT keyword.

- DISTINCT keyword will blindly remove duplicate rows, we will learn in a future lesson how to discard duplicates based on specific columns using grouping and the GROUP BY clause.
