# Backend System for distributed Systems
Two types of databases - SQL nad NoSQL

SQL Pros:
- SQL used in RDBMS by maintaining relationship between tables.
- SQL used normalisation to store the data just once.

SQL Cons:
- The number of fields is fixed in table.
- In case of queries using multiple relation tables, the opertion becomes costly.

It is where NoSQL comes into picture which doesn't require a fixed schema and needn't maintain multiple tables with foreign keys for relationship between the data. Types of NoSQL
- Key value Database
- Document Databse
- Graph Database


CAP Theorem:
- Consistency, Availability and Partition tolerance
- Of the three, any database system can only cater 2 features.


Sharding:
Process of splitting up the database(horizontal scaling) accross machines to improve scalability, performance, availability and load balancing of an application.

Sharding techniques:
- Horizontal partitioning: range based
- Vertical partitioning: feature based
- Directory based partioning: Uses look up server
- Hash based partioning

Problems with sharding:
- Joins and denormalization
- Referential integrity - foreign keys in different servers
- Rebalacing - data load on sharded database
