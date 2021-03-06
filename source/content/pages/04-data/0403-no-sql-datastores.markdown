title: NoSQL Data Stores
category: page
slug: no-sql-datastore
sort-order: 042
choice1url: /databases.html
choice1icon: fa-hdd-o
choice1text: Tell me more about standard relational databases.
choice2url: /cascading-style-sheets.html
choice2icon: fa-css3 fa-inverse
choice2text: My app is running but looks awful. How do I style the interface?
choice3url: /javascript.html
choice3icon: fa-html5 fa-inverse
choice3text: How do I create a better browser experience with JavaScript?
choice4url:
choice4icon:
choice4text:


# NoSQL Data Stores
Relational databases store the vast majority of web application 
persistent data. However, there are several alternative classifications of 
storage representations.

1. Key-value pair
2. Document-oriented
3. Column-family table
4. Graph

These persistent data storage representations are commonly used to augment,
rather than completely replace, relational databases.

## Document-Oriented
A document-oriented database provides a semi-structured representation for
nested data. 


## Key-Value Pair
Key-value pair data stores are based
on [hash map](http://en.wikipedia.org/wiki/Hash_table) data structures.


## Column-family table
A the column-family table class of NoSQL data stores builds on the key-value
pair type. Each key-value pair is considered a row in the store while the
column family is similar to a table in the relational database model.


### Column-family table data stores
* Apache [HBase](https://hbase.apache.org/)

* Apache [Cassandra](http://cassandra.apache.org/)


## Graph
A graph database represents and stores data in three aspects: nodes, edges,
and properties. 

A *node* is an entity, such as a person or business. 

An *edge* is the relationship between two entities. For example, an 
edge could represent that a node for a person entity is an employee of a 
business entity. 

A *property* represents information about nodes. For example, an entity 
representing a person could have a property of "female" or "male".

[Neo4j](http://www.neo4j.org/) is one of the most widely used graph 
databases and runs on the Java Virtual Machine stack.


## NoSQL third-party services
[MongoHQ](http://www.mongohq.com/home) provides MongoDB as a service. It's
easy to set up with either a standard LAMP stack or on Heroku.


## NoSQL data stores resources
* [CAP Theorem overview](http://natishalom.typepad.com/nati_shaloms_blog/2010/10/nocap.html)

* [NoSQL Weekly](http://www.nosqlweekly.com/) is a free curated email 
  newsletter that aggregates articles, tutorials, and videos about 
  non-relational data stores.

* [NoSQL comparison](http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis)
  is a large list of popular, BigTable-based, special purpose, and other
  datastores with attributes and the best use cases for each one.

* [MongoDB for startups](http://www.optinidus.com/blogs/guide-to-mongodb-for-startups/) 
  is a guide about using non-relational databases in green field environments.


### What's next?
