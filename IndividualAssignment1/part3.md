# 📚 Week 3 Summary: Foundations of Information Extraction

## 🧠 Theme 1: Core Concepts in Information Extraction (IE)

Information Extraction (IE) involves **algorithms and systems that identify structured information from unstructured text**. At its foundation are tasks like tokenization and named entity recognition.

- **Information Extraction**: Techniques for pulling relevant data from raw text.
- **Named Entity Recognition (NER)**: Detects specific instances of entities (e.g., people, organizations, dates) relevant to a domain.
- **Tokenization**: Breaks text into discrete units (tokens) such as words, punctuation, or numbers. Token type classification is also often required.
- **Challenges in IE**:
  - Complexity and ambiguity of natural language.
  - Difficulty in adapting models across domains and styles (e.g., news vs. emails vs. academic text).
  - Evolution of ontologies and emergence of new concepts over time.

> 🧠 Key Idea: IE begins with foundational tools like tokenization and NER, but effective use requires grappling with the dynamic, diverse nature of language in the wild.

---

## 🤖 Theme 2: Sequence Modeling and Machine Learning Techniques

Because language unfolds sequentially, many IE tasks use **sequence-labeling models** that consider context and dependencies between words.

- **Sequence Labeling**: Assigns labels to tokens in a way that respects their order and relationships.
- **Conditional Random Fields (CRFs)**:
  - Output a sequence of tags (e.g., entity types) based on input features.
  - Use handcrafted or learned features: capitalization, digit presence, POS tags, surrounding context.
- **Recurrent Neural Networks (RNNs)**:
  - Neural models with loops that allow context from previous tokens to influence the current state.
  - Well-suited for tasks involving sequences.
- **Long Short-Term Memory (LSTM)**:
  - A type of RNN that solves the vanishing gradient problem.
  - Maintains long-range dependencies more effectively than standard RNNs.
  - Widely used in NLP for robust context modeling.

> 🧠 Key Idea: Modern IE systems rely on powerful sequence models like CRFs and LSTMs that can model contextual and sequential dependencies—crucial for handling the richness of language.

---

## 🚧 Theme 3: Adaptability and Limitations of IE Systems

Despite progress, **IE systems face serious challenges in generalizability and domain adaptation**.

- **Domain Dependence**:
  - IE systems often require retraining when moved across domains or ontologies.
  - Entity typing becomes complex as concepts grow more granular (e.g., from *Person* to *Politician*, *Actor*).
- **Retraining Costs**:
  - When extraction and typing are performed jointly, updating one aspect may necessitate reengineering the entire pipeline.
- **OpenIE and Unsupervised NER**:
  - These promise flexibility and reduced reliance on labeled data or ontologies.
  - However, they lag in performance when compared to supervised methods.

> 🧠 Key Idea: While OpenIE and unsupervised methods offer hope for scalable IE, the field still leans heavily on supervised, domain-specific models for high performance.

---
