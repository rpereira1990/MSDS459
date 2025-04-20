# Part 1 – Knowledge Graphs Week 1 Summary

## Summary of Readings

This week’s readings introduce the foundational concepts behind knowledge graphs, including their structure, representation using RDF, and key components like classes, properties, domains, ranges, datatypes, and constraints.

## Key Ideas

### 1. What is a Knowledge Graph?

A knowledge graph is a practical and machine-readable way of representing information about the world. It includes:

- Entities
- Relationships
- Attributes
- Facts
- Beliefs
- Provenance (including justifications and uncertainty)

Structurally, a knowledge graph is a **labeled, multidirectional, directed graph**, meaning:

- Both nodes and edges have labels
- Edges are directional

### 2. What is the Resource Description Framework (RDF)?

While not strictly a knowledge graph model, RDF is a key framework for representing information on the web.

- RDF uses **triples** to represent data:  
  **Subject → Predicate → Object**
- A set of triples forms an **RDF graph**
- These triples are visually represented as **node–arc–node** diagrams
- The **arc direction** is important, always going from subject to object

### 3. What is an RDFS Class?

- `rdfs:Class` is the primary unit used to declare **classes** (or **concepts**)
- Classes represent groups (e.g. `Country`)
- **Instances** are members of classes (e.g. `United States`, `Germany`)

### 4. What is a Subproperty?

- A **property** is a relationship between subject and object resources
- `rdfs:subPropertyOf` allows one property to be a **subproperty** of another
- Subproperties inherit characteristics from their superproperties

### 5. What are Domain and Range of Properties?

- **Domain**: the set of values that can be used as a property’s **subject**
- **Range**: the set of values that can be used as a property’s **object**

Example:
- A property like `bornIn` might have a domain of `Person` and a range of `Location`

### 6. What are Datatypes and Constraints?

- **Datatypes** specify the kind of values allowed:
  - e.g. `educated at` must point to another **item**
  - `start time` and `end time` must be of type **Time**
- **Constraints**:
  - Provide rules for valid data entry
  - Help guide editors
  - Enable **automated validators** to flag incorrect statements

## References

Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. 2021. *Knowledge Graphs: Fundamentals, Techniques, and Applications*. Cambridge, MA: MIT Press.  
