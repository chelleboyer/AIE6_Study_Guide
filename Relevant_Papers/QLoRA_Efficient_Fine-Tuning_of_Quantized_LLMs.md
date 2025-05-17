# QLoRA Efficient Fine-Tuning of Quantized LLMs

QLoRA: Efficient Fine-Tuning of Quantized LLMs

Link to paper: https://arxiv.org/abs/2305.14314


## 📄 Paper 8: “QLoRA: Efficient Fine-Tuning of Quantized LLMs”
**Authors**: Dettmers et al., 2023

### 🔍 Simple Explanation:
QLoRA makes it possible to fine-tune **massive models on small GPUs** by combining **quantization** and **LoRA**.

### 🧠 Key Concepts:
- **Quantization**: Shrinking model weights to use less memory
- **LoRA + Quantization**: Train adapters on a smaller, compressed model
- **Page Migration**: Smart memory handling across CPU and GPU

### 💡 Real-World Analogy:
It’s like shrinking a giant textbook and writing notes in the margins—customized, fast, and portable.

### 🧩 Why It Matters:
- Fine-tune 13B+ models on consumer-grade GPUs
- Pushed LLM fine-tuning into the mainstream