# Database Normalization

**Database normalization**

- process used to organize a database into tables and columns.  The main idea with this is that a table should be about a specific topic and only supporting topics included.

**Reasons for Database Normalization**

- minimize duplicate data

- minimize or avoid data modification issues

- simplify queries

**Data Duplication and Modification Anomalies**

- Duplicated information problems:

* It increases storage and decrease performance.
* It becomes more difficult to maintain data changes.

**Forms of database normalization:**

- First Normal Form:

The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.

- Second Normal Form:

The table is in first normal form and all the columns depend on the table’s primary key.

- Third Normal Form:

the table is in second normal form and all of its columns are not transitively dependent on the primary key

**Insert Anomaly**

- There are facts we cannot record until we know information for the entire row.  

- In our example we cannot record a new sales office until we also know the sales person.  Why?  Because in order to create the record, we need provide a primary key.  
