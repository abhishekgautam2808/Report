

 # **Report on Solr , Lucene and Elastic Search**

 ### Full Text Search
 - This search is done on whole of a database comprising full text of document.
 - Overcominng from serial scanning and its low speed and performance

### **Lucene**

- Lucene is a powerful programmatic libarary that lets us add search capability to our application by creating search indexers.
- It present results with better performance than RDBMS
- It is an ideal
library to index over huge amount of data and carry out a
search. 

### **Solr and ElasticSearch**
- They uses lucene under the hood
- Lucene is used to create a search index and Solr, ElasticSearch use this index to perform searches.

**Advantages to consider Solr**

---
##### Solr Search platform in the following layers from bottom to top:**
  - Data -> 
  Represent various data types and sources
  - Document building -> Build document information for indexing
  - Indexing and searching -> Build and query a document index
  - Logic enhancement->  Additional logic for processing search queries and results
  - Search platform service-> Add additional functionalities of search engine core to provide a service platform.
  - UI application-> End-user search interface or applications
  
    [Reference](http://manmustbecool.github.io/MyWiki/papers/Enterprise%20search%20with%20development%20for%20network%20management%20system.pdf)

**Advantages to consider Elastic Search**

---


  * ElasticSearch is distributed. No separate project required. Replicas are near real-time too, which is called "Push replication".
  * ElasticSearch fully supports the near real-time search of Apache Lucene.
  * Handling multitenancy is not a special configuration, where with Solr a more advanced setup is necessary.
  * ElasticSearch introduces the concept of the Gateway, which makes full backups easier.











