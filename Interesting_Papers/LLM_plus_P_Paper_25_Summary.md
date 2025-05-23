
## 📄 Paper 25: **“LLM+P: Boosting Large Language Model Planning with PDDL”**

[🔗 arXiv Link](https://arxiv.org/abs/2403.13187)  
**Authors**: Ruizhe Wang, Sitao Luan, Yu Zhang, Hang Ma  
**Published**: March 2024

**Core Idea**: Combine **LLMs** with **symbolic planning (PDDL)** to achieve **accurate, verifiable planning** without requiring domain fine-tuning.

---

### 🔍 Simple Explanation:

This paper introduces **LLM+P**, a framework that fuses Large Language Models (LLMs) with symbolic planners using **PDDL (Planning Domain Definition Language)** to perform **long-horizon task planning**. LLMs generate candidate plans, and symbolic planners verify or correct them.

It offers the **flexibility and creativity of LLMs** while enforcing the **formal correctness of symbolic AI**.

---

### 🧠 Key Concepts:

- **LLM Proposal**: LLMs are prompted to generate high-level plans as sequences of actions.
- **Symbolic Verification**: These plans are validated against PDDL domain models to ensure they’re feasible.
- **Feedback Loop**: If a plan fails validation, the symbolic planner provides feedback, and the LLM adjusts its proposal accordingly.
- **No Fine-Tuning Needed**: Uses off-the-shelf LLMs like GPT-4 with zero-shot prompting.

---

### 🔁 Example Use Case:

Imagine a robot that needs to clean a house with several constraints (e.g., don’t vacuum before picking up objects). The LLM+P system:

1. Prompts the LLM to propose a plan.
2. Validates the steps using symbolic rules.
3. Rejects or revises plans that break the rules.
4. Ensures the final plan is **goal-directed and executable**.

---

### 💡 Real-World Analogy:

It’s like a creative intern writing a to-do list (LLM), and a supervisor (symbolic planner) checking it to make sure no steps are skipped or out of order—then handing back corrections until the plan is solid.

---

### 📊 Results:

- **Benchmarks**: Tested on ALFWorld, BabyAI, and CALM datasets.
- **Performance**: Outperforms LLM-only baselines by up to **+30%** in success rate.
- **Interpretability**: Plans are more **transparent**, **verifiable**, and **correct-by-construction**.

---

### 🧩 Why It Matters:

* Bridges **neuro-symbolic reasoning** and **classical planning**
* Provides **explainable** and **robust** planning capabilities
* Reduces errors from LLMs by grounding them in **formal logic**
