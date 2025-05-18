# Part 2: Summary of Week 7 Readings – Instance Matching and Statistical Relational Learning  

## 🔑 Key Ideas

### 1. Instance Matching

Instance Matching (IM) is the process of identifying and clustering nodes in a knowledge graph that refer to the same real-world entity. This is needed because KGs often contain duplicate, similar, or ambiguous entries.

IM is challenging due to three main reasons:
- Duplicate entries may differ for many subtle reasons that are hard to encode with rules.
- Human intuition plays a role in matching, making automation difficult.
- Naive methods are computationally expensive (the textbook notes that these are quadratic in complexity).

A two-step pipeline is typically used:
- **Blocking**: Reduces complexity by grouping similar entities into overlapping "blocks" using blocking keys or schemes.
- **Similarity Scoring**: Computes how likely two entries are duplicates, often using thresholds or rankings to decide matches.

"Swoosh" is a framework that applies instance matching efficiently using black-box merging and comparison functions.

Other important data cleaning tasks include handling naming conflicts, missing values, inconsistent formats, and schema-level mismatches (among others).

---

### 2. Statistical Relational Learning (SRL)

SRL combines logic and probability to model uncertainty in relational data. It allows for reasoning over noisy or incomplete knowledge graphs.

- **Markov Logic Networks (MLNs)**: Combine first-order logic with probabilistic weights. Each formula has a weight, and worlds that violate these formulas become less probable (but noteably, not impossible).
  
- **First-Order Logic (FOL)**: The formal language used in MLNs, built from constants, variables, functions, and predicates.

- **Probabilistic Soft Logic (PSL)**: A variation of SRL that uses "soft truth" values (between 0 and 1) instead of strict true/false logic. This helps model similarity between entities more effectively.

---

### 3. Knowledge Graph Identification (KGI) and Link Prediction

**KGI** refers to the process of identifying the "true" knowledge graph from noisy or incomplete inputs. It aims to clean up inaccurate facts, resolve entity references, and complete missing links.

**Link Prediction** is a related task where the system predicts whether a relation exists between two entities, based on known attributes and relationships. This is especially useful for discovering new facts or suggesting additions to a KG.
