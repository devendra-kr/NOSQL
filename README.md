# NOSQL

Type of NoSQL DB:-

1. Graph-oriented NoSQL: Graph databases tend to solve the problems that arise out of relationships formed among unstructured entities at runtime, which can be bidirectional. As compared to this, RDBMS also has a concept of ationships called table joins, but these relationships are on structured data and cannot be bidirectional. Ex. Neo4i, FlockDB, OrientDB, and so on.

2. Document-oriented NoSQL:  Document-oriented datastores are designed to store data with the philosophy of storing a document. To understand this simplistically, the data here is arranged in the form of a book. A book can be divided into any number of chapters, where each chapter can be divided into any number of topics, and each topic is further divided into subtopics and so on and so forth. Like a book, which has indexes for faster searches, these datastores also have the indexes of keys stored in memory for faster searches. Document-oriented datastores have data stored in the XML, JSON, and other formats. Ex. MongoDB and CouchDB (Couchbase)

3. Column-oriented NoSQL: Column-oriented NoSQL is designed with the philosophy to store data in columns rather than rows.  HBase and Cassandra are a few of the well-known products that are columnar in nature and can store a huge amount of data.

4. Key-value oriented NoSQLL: Key-value datastores are probably one of the fastest and simplest NoSQL databases. In their most simplistic form, they can be understood as a big hash table. Ex.  Redis, Riak, Amazon's DynamoDB, project voldermort, and more.
