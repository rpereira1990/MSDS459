# Part 2: Review of Gel (AKA EdgeDB)

## Overview

Gel graph-relational database built on top of PostgreSQL. It combines the flexibility of a graph database with the structure of a relational database. Gel utilizes EdgeQL, and tools for schema design, authentication, and AI integration.

---

## 🔑 Key Features

### 1. **Graph-Relational Model**
Gel allows users to define entities and their relationships in a way that feels more akin to working with objects in code. This makes it easier to represent complex data (like a KGs)

### 2. **EdgeQL Query Language**
EdgeQL is a new query language designed to be simpler and more powerful than SQL for querying connected data. It removes the need for repetitive syntax and is optimized for relationship-heavy queries.

### 3. **Built-In Developer Tools**
Gel includes a suite of developer tools out of the box — like a schema editor, visual query builder, etc. — all designed to make database design and querying easier and faster.

---

## ✅ Advantages for a Knowledge Base Project

- **Suited entity-relationship data:** The graph-relational model aligns closely with how knowledge bases are structured.
- **Simpler queries:** EdgeQL makes it easy to ask complex questions about connected data.
- **Fast development:** Tools help users model schemas and test queries without needing to set up extra tooling.

---

## ⚠️ Disadvantages and Considerations

- **Learning curve:** Teams familiar with SQL will need time to learn EdgeQL and familiarize themselves with the object-oriented approach.
- **Younger ecosystem:** Fewer third-party tools and plugins, esp. when compared to more mature databases like PostgreSQL.
- **Migration quirks:** Schema migration system is less flexible than traditional systems.

---
