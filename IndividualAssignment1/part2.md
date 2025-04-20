# 📚 Week 2 Summary: Focused Crawling & Web Information Extraction

## 🌟 Theme 1: Intelligent & Targeted Web Crawling

Focused crawling represents a shift from general-purpose crawling to **goal-directed exploration** of the web. Unlike traditional crawlers, which indiscriminately fetch content, focused crawlers prioritize relevance and efficiency.

- **Crawl Strategy**: Best-first search prioritizes high-relevance pages using term frequency vectors.
- **Domain Specification**: Begins with seed URLs and a topic definition (keywords or training examples).
- **Semantic & Learning Enhancements**:
  - *Semantic Crawlers* use ontologies to identify conceptually related content.
  - *Learning Crawlers* apply supervised ML models (Naive Bayes, SVMs, etc.) to predict page relevance.
- **Performance Metric**: *Harvest Rate* measures the proportion of relevant pages downloaded.

> 🧠 Key Idea: A crawler’s intelligence lies in its ability to discern not just structure, but **semantic relevance** in the context of a topic.

---

## 🧱 Theme 2: Structure-Aware Information Extraction (IE)

Web information extraction transforms unstructured HTML into **structured, machine-readable data**. This process leverages the semi-structured nature of web content—especially HTML tables and repeated patterns.

- **Granularity of Extraction**:
  - *Record-level*: Extract specific data fields (e.g., prices, titles).
  - *Page-level*: Extract all relevant info from a page.
  - *Site-level*: Learn site-wide patterns for large-scale data collection.
- **Wrappers**: Tools that identify consistent HTML patterns to extract structured data. Can be:
  - Manual
  - Supervised
  - Semi-supervised
  - Unsupervised
- **Tables**: Distinction between:
  - *Relational tables* (data listings, matrices, forms).
  - *Layout tables* (used for formatting/navigation).

> 🧠 Key Idea: Web data is noisy and inconsistent, but with the right pattern-recognition techniques, **structure can be recovered and exploited**.

---

## ⚖️ Theme 3: Practical Challenges & Tradeoffs in Web-Scale Extraction

Deploying web crawlers and extractors in real-world settings involves tradeoffs between **accuracy, scalability, speed, and ethical considerations**.

- **Human Effort vs. Accuracy**:
  - Fully supervised systems are accurate but require labeled data.
  - Unsupervised methods scale better but may need postprocessing.
- **Adaptability**:
  - Web pages evolve, requiring continuous wrapper maintenance.
- **Velocity & Volume**:
  - Real-time data (e.g., social media) demands fast, adaptive systems.
- **Ethical Issues**:
  - Concerns around privacy, bias, misinformation, and scraping policies.

> 🧠 Key Idea: The “intelligence” of a system isn't just in how well it extracts. It’s also in how well it **adapts to change and respects constraints**.

---

