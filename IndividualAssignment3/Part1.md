# Part 1: Summary of Week 6 Readings – Structured Querying

---

## 🔑 Key Ideas

### 1. Structured Querying and SPARQL

Structured querying uses a formal language to retrieve patterns and subgraphs from a knowledge graph. The most well-known example is **SPARQL**, which is the W3C standard for querying RDF graphs. It allows queries to match sets of triple patterns (subject, predicate, object), and supports logical operations like conjunctions and disjunctions. SPARQL is used in semantic web and linked data contexts.

### 2. NoSQL and Key-Value Stores

**NoSQL** refers to non-relational database systems that are highly scalable and flexible, often used in Big Data contexts. Rather than relying on fixed schemas and tables, NoSQL systems include formats like key-value stores, document databases, and wide-column stores.

Key-value stores associate unique keys with values (which could be anything from a file to a JSON object). This model is especially popular for flexible, large-scale applications.

### 3. JSON and Flexible Data Formats

**JSON** (JavaScript Object Notation) is widely used in NoSQL environments as a data format because it is human-readable, lightweight, and easy to parse in programming languages like Python. JSON allows for deep nesting and is well-suited for representing unstructured or semi-structured data.

### 4. Graph Database Models

In **graph databases**, both schemas and data are represented as nodes and edges. These databases allow queries that follow the graph structure directly. Modern graph databases support **hypernodes** and **hypergraphs**, which allow nesting and better visual organization of complex relationships.

### 5. Big Data Platforms: Apache Cassandra and HBase

- **Apache Cassandra** is a distributed NoSQL database built for large-scale, high-throughput environments. It supports replication, high availability, and fault tolerance, making it ideal for Big Data applications.
  
- **Apache HBase** is a NoSQL database built to provide random access to massive tables on top of Hadoop clusters. It is optimized for compression, fast read/write, and large-scale data storage.
