# MRKL: Modular Reasoning, Knowledge and Language
[View on arXiv](https://arxiv.org/abs/2205.00445)

## 📄 Paper 10: “MRKL: Modular Reasoning, Knowledge and Language”
**Authors**: Andreas et al., 2022  
**Pronounced**: “miracle”

### 🔍 Simple Explanation:
This paper proposes that **language models shouldn't do everything alone**. Instead, we can build **modular systems** where the LLM knows when to answer, when to delegate to tools, and how to combine results from different modules.

It’s a framework for making LLMs more powerful by **connecting them to external knowledge and reasoning systems.**

### 🧠 Key Concepts:
- **Router Model**: The LLM decides which module (calculator, search, database, etc.) to send the question to.
- **Tool Modules**: Specialized components that handle specific types of queries.
- **End-to-End Inference**: The LLM integrates the module outputs to deliver a final answer.

### ✍️ Example:
Imagine asking a question like “What’s the capital of France plus 7 squared?”  
- The model uses its own knowledge for “capital of France = Paris”
- Delegates “7 squared” to a math module → 49
- Final answer: “Paris and 49”

### 💡 Real-World Analogy:
Like a smart assistant who knows when to answer directly, when to use a calculator, and when to call a friend—MRKL empowers LLMs to *collaborate* with tools.

### 🧩 Why It Matters:
- A key building block for modern **agentic systems**  
- Emphasizes **tool use**, which became central in LangChain, LangGraph, and ReAct  
- Led to **modular, extensible architectures** for LLM-based apps