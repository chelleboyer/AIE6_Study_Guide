# Retrieval-Augmented Generation (RAG)

Retrieval-Augmented Generation (RAG)

Link to paper: https://arxiv.org/abs/2005.11401


## 📄 Paper 5: “Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks”
**Authors**: Lewis et al., 2020

### 🔍 Simple Explanation:
This paper introduced **RAG**, a method that **combines a language model with a search engine**. Instead of making the model memorize everything, RAG lets it **look up relevant facts** before answering a question.

### 🧠 Key Concepts:
- **Retriever + Generator**:
  - **Retriever** finds relevant documents using embeddings (semantic search)
  - **Generator** uses those docs as context to produce a response

### 🛠️ Why Use RAG?
- LLMs have limited memory (“context window”) and may hallucinate facts.
- RAG lets you inject **real, updated information** into the response.

### 💡 Real-World Analogy:
Imagine an open-book test. Instead of memorizing every detail, you teach the student how to find the answer in the textbook. RAG turns your LLM into a smart, resourceful student.

### 🧩 Why It Matters:
- Core to most **LLM apps in production** today
- Powers everything from **customer service bots** to **internal knowledge assistants**