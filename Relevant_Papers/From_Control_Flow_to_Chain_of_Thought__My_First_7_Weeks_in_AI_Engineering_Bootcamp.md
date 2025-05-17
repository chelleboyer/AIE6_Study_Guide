# 🚧 From Control Flow to Chain of Thought: My First 7 Weeks in AI Engineering Bootcamp

## 🧑‍💻 A Software Engineer Walks Into a Bootcamp...

I didn’t come to this bootcamp with a machine learning background. I came from a world of compiled code, databases, and production systems — where things either work or they don’t. Where stack traces are your enemies and unit tests are your saviors.

So when I entered the AI Engineering Bootcamp, I was stepping into the strange world of language models — systems that "reason," "hallucinate," and get better by "thinking more." It sounded like magic. And sometimes, like madness.

But now, seven weeks in, I’ve been reshaped by 25 foundational papers that taught me not only how these systems work, but how to *build with them*. What follows is what I learned, and what it felt like.

---

## 🔎 Week 1–2: Building Blocks of Intelligence

It all began with **Transformers** — courtesy of "Attention is All You Need". This wasn’t just a clever name. It *is* all you need. I used to think RNNs were how machines read; turns out Transformers read like speed readers who absorb everything at once and highlight the important parts.

Then came **GPT-3** and its shocking realization: you don’t have to fine-tune a model — you can just *show it a few examples*, and it picks up the pattern. That paper cracked open my old assumptions about models as rigid, task-specific tools. These things generalize.

**Chain of Thought prompting** added another surprise: you can get better answers by *just asking the model to explain itself*. And with **RAG** — Retrieval-Augmented Generation — I learned you could plug the model into a knowledge base and build something that knows its limits.

---

## 🧠 Week 3–4: Agents, Fusion, and Feedback Loops

Week 3 introduced **agents** — models that reason, act, observe, and repeat. The **ReAct** and **MRKL** papers showed that a language model could call functions, reflect on results, and make decisions. This wasn’t just a chatbot. This was a software system.

In Week 4, we explored **RAG evaluation** with **RAGAS**, and added tricks like **RAG-Fusion** (ask the question multiple ways!) and **Reciprocal Rank Fusion** (combine results smartly). The precision I missed in earlier RAG projects was now measurable — and fixable.

Then came **Self-Refine** and **Reflexion** — feedback loops that reminded me of how great engineers work: write code, reflect on the bugs, improve the logic. Except now, the model was doing that *to itself*.

---

## 🧮 Week 5–6: Fine-Tuning, Embeddings, and Data at Scale

This part felt like hacking — but on a different axis. Papers like **LoRA** and **QLoRA** showed me how to fine-tune massive models with limited compute. I wasn’t training GPT-4 — I was training *my own version* of a model, to understand *my own data*.

I met **MTEB**, the benchmark that finally made embedding models feel less mysterious. I learned that **BM25** still holds its own — and sometimes, the simplest tools are the most reliable.

By this point, I’d built RAG pipelines, tracked KPIs, and deployed apps. But I was still thinking like a software engineer. What changed was how I reasoned about **compute** — thanks to **Scaling Laws** and **Scaling Test-Time Compute**. Bigger isn’t always better. Smarter *use* of compute is.

---

## 🧱 Week 7: Systems That Think, Evaluate, and Evolve

The final stretch introduced **planning agents** powered by Chain of Thought, and retrieval systems that weren’t just "semantic" — they were **contextual**. Claude’s retrieval paper taught me that *how* you fetch documents matters as much as *what* you fetch.

We explored models like **DeepSeekMath** and **DeepSeek-R1**, which turned reasoning into a pretraining goal, not just a side effect. These weren’t just language models — they were logic engines in disguise.

By the time we hit **LangGraph**, we weren’t just prompting anymore. We were building agents with retries, retries that *learned* from themselves, and multi-agent flows that argued, reflected, and refined each other’s work.

---

## 🧭 What’s Changed

This bootcamp didn’t just teach me about AI. It reframed what engineering can be.

I came in expecting to learn about models. What I learned was how to *work with models* — how to design workflows that involve uncertainty, partial knowledge, and learned behavior. I learned to evaluate like a scientist, iterate like a developer, and architect like an optimizer of compute.

I now understand what it means to *engineer with AI* — not just code it, but compose it.