# MongoDB

## QC Agenda
- RDBMS:
    - DML, DDL, DQL
    - Basic SQL queries
    - Aggregate functions
    - Multiplicity
- NoSQL
- MongoDB:
    - Scala Mongo Driver
    - Connection Strings
    - Schemas and Relations
    - Mongo Collections
    - Mongo Documents
    - Insert, Find
    - Query, Sort, Limit
    - Update, Delete
    - Indexing

## Extra topics worth researching
- Docker
- JSON
- CAP Theorem
- ACID Transactions

## Resources
- [MongoDB Manual](https://docs.mongodb.com/manual/)
    - [mongo Shell Quick Reference](https://docs.mongodb.com/manual/reference/mongo-shell/)
    - [MongoDB CRUD Operations](https://docs.mongodb.com/manual/crud/)
- [MongoDB Scala Driver](https://index.scala-lang.org/mongodb/mongo-java-driver/mongo-scala-driver/4.1.1?target=_2.13)
- [MongoDB Scala Driver Docs](https://docs.mongodb.com/drivers/scala/)
- [Official MongoDB Docker Image](https://hub.docker.com/_/mongo)
- [SQL Zoo - Practical SQL exercises](https://sqlzoo.net/wiki/SQL_Tutorial)
- [SQLBolt - Intro to SQL & exercises](https://sqlbolt.com/)
- [SQL Query Order of Operations](https://www.eversql.com/sql-order-of-operations-sql-query-order-of-execution/)

## Review
- How do we specify dependencies using sbt?
- Why do we use databases instead of just writing to file?
- What is a port number?
- What's the default port for MongoDB?
- What is a database?
- What is a collection?
- What is a document?
- What rules does Mongo enforce about the structure of documents inside a collection?
- What is JSON?
- What are JSON data types?
- What is BSON?
- What are some of the data types included in BSON?
- What is an ObjectId?
- What is the _id field for in mongo?
- What does find() do?
- What is a filter in a mongodb query?
- What are some examples of filters?
- What do sort and limit do?
- What is a projection in a mongodb query?

- What is multiplicity?  Examples of 1-to-1, 1-to-N, N-to-N?
- What is cardinality?
- What are some advantages of handling document relationships by embedding documents?
- Disadvantages of the same?
- What about handling document relationships using references -- advantages and disadvantages?
- What is an Index?  
- What advantages does creating an Index give us? Disadvantages?
- What is CRUD?
- Some example CRUD methods for Mongo? (The Scala methods mostly match mongo shell syntax)
- What is a distributed application?  A distributed data store?
- What is High Availability? How is it achieved in Mongo?
- What is Scalability? How is it achieved in Mongo?
- Explain replica sets and sharding
- What is the CAP Theorem?
- What does CAP mean for our distributed data stores when they have network problems?
- What does it mean that an operation or transaction on a data store is atomic?
- In Mongo, are operations on embedded documents atomic?  What about operations on referenced documents?
- What does RDBMS stand for?
- What about SQL?
- Do SQL databases have embedded records like mongo has embedded documents?
- Can we freely store any data we like in an RDBMS table the same way we store any data in a mongo collection?
- What does ACID stand for?
- What does BASE stand for?

- What is a SQL dialect?
- What are DML, DDL, DQL?
- What does SELECT do?
- FROM?
- WHERE?
- What is a primary key?
- What is a foreign key?