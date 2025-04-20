# 📚 Week 5 Summary: Information Extraction and Knowledge Graphs

## 🧩 Theme 1: From Text to Structured Knowledge

This chapter explores the transformation of raw text into structured knowledge through Information Extraction (IE) and its role in building Knowledge Graphs (KGs).

- **Information Extraction (IE)**: The process of identifying and structuring key facts from unstructured text, such as entities, relationships, and events.
- **Named Entity Recognition (NER)**: Recognizes predefined categories such as people, organizations, and locations.
- **Relation Extraction**: Identifies the relationships between entities, e.g., (Barack Obama, born_in, Hawaii).

> *Key Insight*: IE converts unstructured data into structured triples (subject, predicate, object), forming the foundation of knowledge graphs.

---

## 🧠 Theme 2: Building and Using Knowledge Graphs

Knowledge Graphs represent interconnected facts and are increasingly used in modern applications for reasoning and answering complex queries.

- **Structure**: A KG is a graph where nodes represent entities and edges represent relationships.
- **Construction**: KGs can be built manually (e.g., Wikipedia’s infoboxes), automatically (via IE), or semi-automatically (with human-in-the-loop/reinforcement-style techniques).
- **Applications**: Used in search engines, recommender systems, digital assistants, and fraud detection.

> *Key Insight*: Knowledge graphs enable machines to "understand" the world by storing facts in a searchable and extensible form.

---

## ⚙️ Theme 3: Tools and Techniques for IE and KG Construction

The chapter introduces real-world tools and methods used to extract and connect knowledge.

- **Spacy & Hugging Face Transformers**: Used for NER and relationship extraction using pretrained language models.
- **OpenIE Systems**: Tools exist to allow extraction without a predefined schema, though often with less accuracy.
- **Embedding-Based KGs**: Techniques to embed entities and relations into vector space to support reasoning and link prediction.
- **Challenges**:
  - Ambiguity in language (e.g., "Paris" as a person or a place)
  - Scalability and performance when processing large corpora
  - Maintaining up-to-date and accurate knowledge

> *Key Insight*: Combining traditional NLP with modern transformer-based models enables more scalable and accurate knowledge extraction pipelines.

---
