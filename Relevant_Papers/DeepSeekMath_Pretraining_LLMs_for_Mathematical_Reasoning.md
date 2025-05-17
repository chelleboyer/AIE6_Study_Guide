# DeepSeekMath Pretraining LLMs for Mathematical Reasoning
[View on arXiv](https://arxiv.org/abs/2402.03300)

## 📄 Paper 13: “DeepSeekMath: Pretraining LLMs for Mathematical Reasoning”
**Authors**: DeepSeek Team, 2024  
**Notable for**: Introducing **GRPO** — Guided Reward Preference Optimization

### 🔍 Simple Explanation:
This paper focuses on improving a model’s **math reasoning skills** by training it on a massive, high-quality math dataset—**DeepSeekMath**. It also introduces a new training method called **GRPO**, which fine-tunes models using a more structured reward signal than traditional RLHF.

### 🧠 Key Concepts:
- **DeepSeekMath Dataset**: A large collection of math problems across a wide range of difficulty, designed for LLM pretraining and fine-tuning.
- **GRPO (Guided Reward Preference Optimization)**:
  - Improves alignment via *multi-turn, structured feedback*.
  - Outperforms RLHF on structured tasks like math.
- **Reasoning Over Memorization**: The model learns patterns and problem-solving processes, not just answers.

### ✍️ Example Use Case:
Train a model to not just say “the derivative of x² is 2x,” but to explain **why** and **how** it got that result.

### 💡 Real-World Analogy:
It’s like giving a student not just the textbook and test answers, but also an experienced tutor who gives **step-by-step feedback** based on their reasoning style.

### 🧩 Why It Matters:
- Pushes math-capable models closer to **human-level explanation and reasoning**  
- Introduces GRPO, an innovative method now influencing **reasoning-aligned fine-tuning**  
- Inspires new directions in LLM alignment using structured preference feedback