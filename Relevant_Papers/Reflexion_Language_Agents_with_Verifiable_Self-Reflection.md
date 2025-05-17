# Reflexion Language Agents with Verifiable Self-Reflection
[View on arXiv](https://arxiv.org/abs/2303.11366)

## 📄 Paper 24: “Reflexion: Language Agents with Verifiable Self-Reflection”
**Authors**: Shinn et al., 2023  
**Core Idea**: Agents that **learn from their past mistakes** and improve over time.

### 🔍 Simple Explanation:
This paper introduces **Reflexion**, a technique where LLM-based agents keep a **memory of past actions and errors**, reflect on what went wrong, and use that reflection to **adapt future behavior**.

It builds on the idea of **Self-Refine**, but applied across multiple episodes—like trial and error over time, with memory.

### 🧠 Key Concepts:
- **Reflection Memory**: The agent keeps track of successes, failures, and explanations for both.
- **Behavioral Update**: Reflections are injected into the prompt for future attempts.
- **Performance Boost**: Helps agents solve **harder tasks faster** with fewer retries.

### 🔁 Example Use Case:
Imagine a coding agent that keeps failing to use the right syntax. After each failed run:
1. Logs what it tried
2. Reflects on what likely caused the issue
3. Stores the insight
4. Applies the insight on the next run

It literally gets smarter with each attempt.

### 💡 Real-World Analogy:
It’s like keeping a work journal where you note what went wrong each day and make a plan to avoid repeating the same mistakes. Over time, you improve not just through practice—but through *deliberate reflection*.

### 🧩 Why It Matters:
- **Turns LLMs into learning agents** (without fine-tuning)
- Reduces retries and hallucinations in **task-based apps**
- Inspired **LangGraph retry+reflection flows** and **learning loops** in agentic frameworks