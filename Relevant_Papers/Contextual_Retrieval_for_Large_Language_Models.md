# Contextual Retrieval for Large Language Models
[View on Anthropic](https://www.anthropic.com/news/contextual-retrieval)

## 📄 Paper 20: “Contextual Retrieval for Large Language Models”
**Authors**: Anthropic Team, 2023  
**AKA**: The *“Claude gets smart about what to read”* technique

### 🔍 Simple Explanation:
This paper describes **how to make retrieval smarter** by focusing not just on keyword matching or embeddings—but on **contextual relevance**. That means dynamically selecting the **most useful** passages for a specific question, using the **model itself to guide retrieval**.

### 🧠 Key Concepts:
- **Context-Aware Retrieval**: Tailor results based on where in the conversation the question appears.
- **Semantic Relevance over Similarity**: Move beyond vector closeness to actual task relevance.
- **Model-in-the-Loop Filtering**: Use the LLM to score and filter what’s worth reading.

### 📊 Key Insight:
Embedding similarity is helpful, but not enough—especially in complex or multi-turn tasks. Use the **LLM’s judgment** to decide which results will help answer a question well.

### 💡 Real-World Analogy:
It’s like a librarian who doesn’t just pull books that “mention your topic,” but understands your actual question and finds **exactly the parts that help you answer it**.

### 🧩 Why It Matters:
- Makes RAG **more accurate, less noisy**
- Enables models to be **more grounded and trustworthy**
- Core technique behind Claude 2’s ability to work with **long documents and chat history**