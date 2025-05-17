# Attention Is All You Need

Attention Is All You Need

Link to paper: https://arxiv.org/abs/1706.03762


## 📄 Paper 1: “Attention Is All You Need”
**Authors**: Vaswani et al., 2017

### 🔍 Simple Explanation:
This paper introduces the **Transformer**, the foundational architecture behind almost all modern LLMs like GPT, BERT, and Claude.

Instead of processing words one at a time like older models (e.g., RNNs), Transformers **look at all words in a sentence at once** and decide how much attention to pay to each word. This allows them to **understand meaning better and faster**.

### 🧠 Key Concepts:
- **Self-Attention**: The ability to look at other words in the sentence and decide which ones matter most.
- **Positional Encoding**: Since the Transformer doesn’t read words in order, it adds signals to tell the model where each word is in the sentence.
- **No Recurrence**: Unlike older models, Transformers don’t loop through words—making training faster and more parallelizable.

### 🧩 Why It Matters:
- Nearly every LLM you interact with today (GPT-4, Claude, Llama 3, etc.) is based on this idea.
- It made it feasible to train large models on massive datasets—leading to the current AI boom.

### 💡 Real-World Analogy:
Imagine reading a paragraph and instantly understanding the key words and how they relate to each other, all at once, without reading word-by-word. That’s what self-attention allows models to do.