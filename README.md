**MongoDB introduction**
=====================
---
**Content:**
-----------------------------------
---
1. What is MongoDB?
2. Features
3. Advantages
4. MongoDB architecture 
5. Starting to work with MongoDB
6. Playing with commands
7.  Conclusion


**What is MongoDB?**
-----------------------------------
---
MongoDB is a source-available cross-platform document-oriented database program. 
Classified as a NoSQL database program, MongoDB uses JSON-like documents with optional schemas. 

**Features of MongoDB**
### 
1. Ad-hoc queries for optimized, real-time analytics
2. Indexing appropriately for better query executions
3. Replication for better data availability and stability
4. Sharding
5. Load balancing

**Advantages of MongoDB**
###
1. Full cloud-based application data platform.
2. Flexible document schemas.
3. Widely supported and code-native data access.
4. Change-friendly design.
5. Powerful querying and analytics.
6. Easy horizontal scale-out with sharding.
7. Simple installation.
8. Cost-effective.

**MongoDB architecture**
-----------------------------------
---
It is an architecture that is built on collections and documents. The basic unit of data in this database consists of a set of key-value pairs. It allows documents to have different fields and structures. This database uses a document storage format called BSON which is a binary style of JSON documents.

![picture](https://intellipaat.com/blog/wp-content/uploads/2021/06/image-26.png)

**Starting to work with MongoDB**
-----------------------------------
---
1. Download the mongodb.
2. Follow normal setup instructions.
3. Create the following folder. C:\data\db.
4. cd to C:\Program Files\MongoDB\Server\3.2\bin> enter command mongod. ...
5. (optionally) download RoboMongo and follow normal setup instructions.
6. Start RoboMongo and create a new connection on localhost:27017.


**Playing with commands**
-----------------------------------
---
1. Create a new database using the command: use my_database
![picture](https://pacificsky.ru/uploads/posts/2020-01/1579260693_create-new-database-in-mongo.png)
2. Let's create a collection.
To create a collection, run the following command in cmd:db.createCollection("posts")
![picture](https://pacificsky.ru/uploads/posts/2020-01/1579260803_create-new-collection-in-mongo.png)
3. Let's delete the collection.
To drop a collection, you must execute a command specifying the collection name after db and using the drop method:(db.posts.drop()
In case of successful deletion of the collection, an informational message will be displayed - "true".
![picture](https://pacificsky.ru/uploads/posts/2020-01/1579261029_drop-collection-in-mongo.png)
4. To get a list of all databases, there is a query (show dbs)
5. Created database is not in the list. In order for it to be displayed, at least one entry must be made to it: db.projectdb.insert({"name":"proselyte.net"})


**Conclusion**
-----------------------------------
---
MongoDB is built on a scale-out architecture that has become popular with developers of all kinds for developing scalable applications with evolving data schemas. As a document database, MongoDB makes it easy for developers to store structured or unstructured data. It uses a JSON-like format to store documents.
