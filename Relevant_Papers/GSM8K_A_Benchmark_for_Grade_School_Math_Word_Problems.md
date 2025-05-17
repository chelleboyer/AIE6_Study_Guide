# GSM8K: A Benchmark for Grade School Math Word Problems
[View on arXiv](https://arxiv.org/abs/2110.14168)

## 📄 Paper 12: “GSM8K: A Benchmark for Grade School Math Word Problems”
**Authors**: Cobbe et al., 2021

### 🔍 Simple Explanation:
This paper introduces **GSM8K**, a dataset of **grade-school-level math word problems** designed to **test an LLM’s ability to reason step-by-step**.

It became one of the most popular benchmarks to measure how well models handle **multi-step arithmetic and logical reasoning**.

### 🧠 Key Concepts:
- **High-Quality Dataset**: 8,500 problems curated and written by professional math educators.
- **Focus on Reasoning**: Problems require step-by-step logic, not just recall or single-step math.
- **Evaluates Chain-of-Thought**: Ideal for testing models that use CoT prompting.

### ✍️ Example Problem:
> “Tom has 3 boxes of pencils. Each box contains 12 pencils. He gives 10 pencils to his friend. How many pencils does he have left?”

This requires:
1. Multiplication
2. Subtraction
3. Understanding of a narrative setup

### 💡 Real-World Analogy:
It’s like giving a student a word problem quiz—not just math facts, but comprehension, planning, and multi-step execution.

### 🧩 Why It Matters:
- **Stress-tests reasoning** in a measurable, structured way  
- Used in almost every **LLM reasoning evaluation**, including GPT-4, Claude, and PaLM  
- Helped inspire work on **Chain of Thought prompting**, **reasoning agents**, and **fine-tuned reasoning models**