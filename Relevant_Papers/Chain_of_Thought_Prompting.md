# Chain of Thought Prompting

Chain of Thought Prompting

Link to paper: https://arxiv.org/abs/2201.11903


## 📄 Paper 3: “Chain of Thought Prompting Elicits Reasoning in Large Language Models”
**Authors**: Wei et al., 2022

### 🔍 Simple Explanation:
This paper shows that large language models can solve **complex reasoning problems** much better if you ask them to **think step-by-step**. That’s the whole idea behind **Chain of Thought (CoT) prompting**.

Instead of jumping to an answer, the model is nudged to **explain its reasoning** along the way—just like how you’d walk through a math problem on paper.

### 🧠 Key Concepts:
- **CoT Prompting**: Ask the model to “think out loud” in steps.
- **Better for Complex Tasks**: Especially useful for math, logic, and multi-part questions.
- **Only Works in Big Models**: Smaller models don't benefit much—scale is key.

### ✍️ Example:
**Question**: If there are 5 apples and you eat 2, how many are left?  
**Standard Prompt**: "Answer: 3"  
**CoT Prompt**: "There are 5 apples. I eat 2. 5 minus 2 is 3. Answer: 3"

### 💡 Real-World Analogy:
Imagine asking a kid to do math in their head versus showing their work on paper. The second method helps you catch errors and builds better habits. That’s what CoT does for LLMs.

### 🧩 Why It Matters:
- Boosts performance in tasks that require **reasoning, not just pattern matching**
- Became foundational in **agent systems** and **tool use** where reasoning steps matter