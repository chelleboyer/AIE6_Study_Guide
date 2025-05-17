# Low-Rank Adaptation (LoRA)

Low-Rank Adaptation (LoRA)

Link to paper: https://arxiv.org/abs/2106.09685


## 📄 Paper 7: “LoRA: Low-Rank Adaptation of Large Language Models”
**Authors**: Hu et al., 2021

### 🔍 Simple Explanation:
LoRA lets you **fine-tune large models** cheaply by **freezing most weights** and just updating a few small adapter layers.

### 🧠 Key Concepts:
- **Low-Rank Matrices**: Smaller matrices that approximate big ones
- **Adapters**: Extra layers trained on your data
- **Parameter-Efficient**: Updates fewer weights, reducing compute cost

### 💡 Real-World Analogy:
It’s like customizing a suit by adding a few patches, not re-stitching the whole thing.

### 🧩 Why It Matters:
- Makes fine-tuning **affordable and accessible**
- Used widely with Hugging Face’s `peft` library