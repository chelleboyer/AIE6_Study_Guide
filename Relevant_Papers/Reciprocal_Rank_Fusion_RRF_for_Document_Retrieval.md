# Reciprocal Rank Fusion RRF for Document Retrieval
[View Paper](https://plg.uwaterloo.ca/~gvcormac/cormacksigir09-rrf.pdf)

## 📄 Paper 19: “Reciprocal Rank Fusion (RRF): Simple Yet Effective Fusion for Document Retrieval”
**Authors**: Cormack, Clarke, and Buettcher, 2009

### 🔍 Simple Explanation:
RRF is a **super simple method for combining multiple ranked lists** (like from different search engines or models) into a single, stronger ranked result.

It turns out that just **averaging the ranks** in a clever way gives you a huge performance boost—no machine learning required.

### 🧠 Key Concepts:
- **Reciprocal Rank**: If an item is ranked #1, its score is `1/(k + rank)`, where `k` is a small constant (usually 60).
- **Fusion**: Combine scores from multiple ranked lists by summing these reciprocal ranks.
- **Robust to Noise**: Even if one list is bad, good signals from other lists dominate.

### 📊 Example:
Suppose three models return a document ranked:
- #2 in list A → `1 / (60 + 2)`  
- #5 in list B → `1 / (60 + 5)`  
- Not in list C → 0  

Add the scores, and now you have a smart combined ranking.

### 💡 Real-World Analogy:
Imagine asking three friends to recommend restaurants. One says “go to Bento,” another says “maybe try Ramen,” and the third is indecisive. You don’t just pick one—you consider the **consensus**, weighted by enthusiasm. That’s RRF.

### 🧩 Why It Matters:
- **Extremely effective**—often outperforms individual retrieval models
- **Used in modern hybrid search pipelines** (e.g. vector + keyword fusion)
- Great baseline and component for **retrieval systems**, **search engines**, and **RAG pipelines**