# BM25 A Non-Learning Baseline for Information Retrieval
[View on Reference Site](https://www.nowpublishers.com/article/Details/INR-019)

## 📄 Paper 18: “BM25: A Non-Learning Baseline for Information Retrieval”
📜 Originally described in Robertson et al., 1995–2009  
**BM25 = Best Matching 25**

### 🔍 Simple Explanation:
**BM25** is a **classic, non-ML algorithm** used for **ranking documents based on relevance** to a search query. Despite being decades old, it’s still a strong baseline for modern retrieval systems—and often used as a benchmark against newer neural methods like vector embeddings.

It’s based on how often query words appear in documents, and how common those words are overall.

### 🧠 Key Concepts:
- **TF (Term Frequency)**: How often a word shows up in a document.
- **IDF (Inverse Document Frequency)**: How rare a word is across all documents.
- **BM25 Formula**: Scores documents using a clever combination of TF and IDF, plus length normalization.

### 🧮 Scoring Intuition:
- Frequent query terms in a document = higher score
- Common terms across many docs (like “the”) are downweighted
- Long documents don’t get unfairly rewarded

### 💡 Real-World Analogy:
It’s like Google search in the 1990s: matching based on keyword frequency and adjusting for how common the words are. Surprisingly, it still holds up remarkably well—even compared to fancy neural models.

### 🧩 Why It Matters:
- **Extremely fast and simple to implement**
- Still used in modern search engines as a **fallback or hybrid** with vector search
- Commonly paired with embedding models for **re-ranking or fusion methods**
- Forms the **baseline comparison in most retrieval benchmarks**, including RAG and LangChain apps