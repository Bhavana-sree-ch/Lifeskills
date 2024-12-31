## 1. MongoDB

####    Type: 
        Document-oriented
####   Key Features:
 * Stores data in flexible, JSON-like documents, making it easy to work with dynamic schemas.
 * Supports indexing, aggregation, and ad-hoc queries, enabling efficient data retrieval.
* Horizontal scaling via sharding, which divides data across multiple servers.
* Strong community support and extensive tooling.
#### Use Cases:
* Applications requiring fast iteration and schema flexibility (e.g., content management systems, e-commerce platforms).
* Real-time analytics and cataloging systems.

## 2. Cassandra

####    Type: 
        Wide-column store
####    Key Features:
* Distributed and highly available with no single point of failure.
* Optimized for high write and read throughput.
* Supports linear scalability for massive amounts of data across many nodes.
* Tunable consistency settings allow developers to balance between consistency and availability.
####    Use Cases:
* Time-series data (e.g., IoT, log processing).
* Large-scale applications with global distribution, such as social media and messaging platforms.

## 3. Redis

####   Type:
         Key-value store
####   Key Features:
* In-memory data storage ensures extremely low latency.
* Offers data structures like lists, sets, sorted sets, and hashes.
* Supports pub/sub messaging, streams, and Lua scripting.
* Persistence options for durability (e.g., snapshots, append-only files).
####   Use Cases:
* Caching to reduce load on primary databases.
* Real-time applications like leaderboards, chat systems, and session management.
* Analytics pipelines and queue management.

## 4. Couchbase

####    Type: 
         Document-oriented
####    Key Features:
* Combines the flexibility of a document store with the scalability and high availability of a distributed system.
* Integrated full-text search and built-in support for SQL-like queries via N1QL.
* Memory-first architecture for high performance.
* Cross-datacenter replication for disaster recovery and global data distribution.
####    Use Cases:
* Mobile and IoT applications requiring offline-first capabilities.
* High-performance applications in retail, finance, and healthcare.

## 5. Neo4j

####    Type: 
        Graph database
####    Key Features:
* Designed for managing and querying highly connected data.
* Provides a native graph storage engine and query language (Cypher) for efficient traversal.
* Optimized for relationships and complex queries.
* Scales well for graph-based data structures.
####    Use Cases:
* Social networks and recommendation engines.
* Fraud detection and network analysis.
* Knowledge graphs and hierarchical data systems.


#### References

https://www.geeksforgeeks.org/types-of-nosql-databases/