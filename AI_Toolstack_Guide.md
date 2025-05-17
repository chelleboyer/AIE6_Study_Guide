# 🧰 AI Engineering Toolstack Guide

This document summarizes the essential tools used in building, deploying, evaluating, and optimizing LLM-based applications. It's organized by function, with a brief explanation of what each tool is and how it fits into the development lifecycle.

---

## ✅ Development & Deployment

| **Tool** | **Description** |
|---------|-----------------|
| **GitHub** | Industry-standard platform for version control, collaboration, issue tracking, and CI/CD. Think of it as your code's home base. |
| **Cursor** | An AI-enhanced IDE built for fast iteration. It helps you write, refactor, and debug code with GPT-based assistance baked right in. |
| **Colab / Jupyter** | Interactive notebook environments ideal for prototyping, data exploration, and training/testing models. Also great for sharing demos. |
| **Docker** | Containerization tool that lets you package your app (and all its dependencies) so it runs exactly the same everywhere—your laptop, the cloud, or a toaster (ok, maybe not a toaster). |
| **FastAPI** | A blazing fast Python web framework for building APIs. Supports async, OpenAPI docs, and plays really well with modern tooling. |
| **Hugging Face Spaces** | Hosting and deployment platform for ML demos and applications. Drag, drop, deploy—without the DevOps headaches. |

---

## 🧠 LLMs & Models

| **Tool** | **Description** |
|---------|-----------------|
| **OpenAI GPT Models** | High-performance general-purpose LLMs for text generation, reasoning, and chat. The Swiss Army knife of language AI. |
| **Claude** | An LLM by Anthropic tuned for helpful, honest, and harmless outputs. Great for safe interactions and complex reasoning. |
| **Llama 3.1–8B Instruct** | Meta's open-source model optimized for following instructions. Ideal for fine-tuning and on-prem use. |
| **Snowflake Arctic** | Fast, compact embeddings model designed for enterprise-grade performance and search. Think: lean, mean vector machine. |
| **MTEB** | Massive Text Embedding Benchmark – your go-to suite for comparing and stress-testing embedding models across tasks. |

---

## 🔧 Frameworks & Libraries

| **Tool** | **Description** |
|---------|-----------------|
| **LangChain** | The de facto standard for building RAG pipelines and chaining together LLM tools, prompts, and agents. |
| **LangGraph** | A graph-based framework for defining and executing agent flows. Less spaghetti, more clarity. |
| **LangSmith** | Evaluation and observability platform to track what your app is doing, where it’s breaking, and how to fix it. |
| **Chainlit** | A front-end UI framework designed for LLM apps. Instantly makes your backend look like a product. |
| **Unsloth** | Speedy fine-tuning library that supports LoRA with lightning-fast training. Because nobody likes waiting. |
| **RAGAS** | Framework for scoring RAG pipeline outputs using realistic metrics and synthetic data. Built for iteration and insight. |

---

## 🧭 Embedding & Retrieval

| **Tool** | **Description** |
|---------|-----------------|
| **OpenAI Embeddings** | Converts text to high-dimensional vectors for similarity search. Plug-and-play for RAG. |
| **QDrant** | High-performance vector database built for scalability and blazing fast retrieval. Also plays nicely with LangChain. |
| **Sentence Transformers** | Hugely popular library for training and using sentence-level embeddings with high accuracy. |

---

## ⚙️ Quantization & Optimization

| **Tool** | **Description** |
|---------|-----------------|
| **LoRA / QLoRA** | Techniques for parameter-efficient fine-tuning. Save GPU, time, and your sanity. |
| **AWQ / GPTQ** | Quantization methods that reduce model size and speed up inference without major performance drops. |
| **vLLM** | Inference-optimized server that runs LLMs like a boss—ideal for production-scale apps. |
| **ollama** | Run open-source LLMs on your local machine. On-premise, private, and no GPU? No problem. |

---

## 📏 Evaluation & Data

| **Tool** | **Description** |
|---------|-----------------|
| **RAGAS** | (Yes, again!) This time used specifically for evaluating RAG outputs: factuality, context use, hallucination rate, etc. |
| **Synthetic Data Generation (SDG)** | Generate fake-but-useful data to test and evaluate models. Critical when real data is scarce or private. |
| **LangGraph Studio** | A visual interface to debug and test LangGraph-based apps, making invisible agent logic visible. |
