# Building, Breaking, and Becoming: My First 7 Weeks in the AI Engineering Bootcamp

## What It Felt Like to Start From Scratch

When I joined the AI Engineering Bootcamp, I wasn’t “AI-ready". I wasn’t even Python-ready.

I was a software engineer with a solid understanding of systems, APIs, and infrastructure, but very little exposure to machine learning. The first few weeks felt like landing in a foreign country where the locals speak in tokens, attention heads, and embeddings. And then ... they expect you to build something useful with it, quickly.

But that’s exactly what made it work.

---

## Week 1: From Vibe Check to Version Control

Our first assignment wasn’t to read a paper. It was to **ship something**.

We built our first LLM app using a template called *Beyond ChatGPT*, deployed it to Hugging Face, and learned how to vibe check the quality of model outputs. It wasn’t theoretical. It was a live, end-to-end product on day one.

I set up my dev environment, API keys, and started making changes to a codebase I barely understood. But I got my app deployed, and that made it real. Fast.

---

## Week 2: RAG From Scratch

In Week 2, we built our first **Retrieval-Augmented Generation (RAG)** pipeline. We learned what embeddings are, how similarity search works, and how to glue it all together with the OpenAI API.

What surprised me most was how little you need to get a basic RAG app working, and how much room there is to improve it.

By the end of the week, I had a working app, but more importantly, I had a list of questions:

- How do I improve retrieval quality?  
- What if the context is wrong?  
- How do I measure success?

That was the point, not to get it right, but to start building **judgment**.

---

## Week 3: Production-Grade Thinking

This week shifted the tone from *“can I build it?”* to *“would I ship this?”*

We explored production-ready architecture: FastAPI backends, Docker deployment, embedding storage, and retrieval orchestration. This was the first time the bootcamp felt like a true engineering discipline.

It forced me to slow down and think like a product owner:
- What am I building?  
- Who’s it for?  
- Can it scale?

At the same time, we began prepping for **Demo Day**, and I started to feel the pressure.

---

## Week 4: LangChain, LangGraph, and the Agent Awakening

This was the week everything broke, in a good way.

We transitioned from simple RAG pipelines to **LangChain**, **LangGraph**, and **LangSmith**. The complexity exploded. We weren’t just calling APIs anymore, we were orchestrating flows of behavior with graphs, memory, retries, and multi-agent systems.

I had to rewire how I thought about application architecture. A lot of the comfort I had in classic OOP, APIs, and request-response logic didn’t apply. These systems were interactive, stateful, and uncertain.

I spent more time debugging nodes in a LangGraph than I had debugging code in years. But I finally understood what an **agentic application** really is.

---

## Week 5: Agentic RAG and the Real Work

This week was all about combining everything: agents, retrieval, tool use, and monitoring.

The assignment was to build an **agentic RAG application** that could plan, act, and self-evaluate. Mine flopped several times before it started to work, and when it did, it felt like magic.

More than that, I learned to build **metrics-driven workflows** using **LangSmith**. I could now test my app’s answers against real metrics, grounding, faithfulness, correctness, and debug them with visual traces.

It started to feel less like hacking and more like **engineering**.

---

## Week 6: Certification Challenge + Demo Day Pitches

This was a shift from *“build to learn”* to *“build to show.”*

We had to define our own product problem, choose an audience, and start designing a real solution using what we’d learned. The **Certification Challenge** wasn’t a test. It was a call to ship something meaningful; with test data, fine-tuned embeddings, and RAG evaluation built in.

I started pitching ideas to other students and iterating in public. It was the first time I’d used the language of **product, audience, and value** in an AI project.

---

## Week 7: Retrieval and Reasoning - The Real Work Begins

Week 7 focused on advanced retrieval techniques (like **RAG Fusion** and **contextual reranking**) and reasoning agents. It introduced planning agents that could reflect, revise, and retry, all without retraining.

What really stuck with me wasn’t the code. It was the **mindset**:

- More compute at inference time can mean better answers  
- Better retrieval beats bigger models  
- Self-evaluation and planning loops unlock true reasoning

For the first time, I felt like I wasn’t just *“building LLM apps”*, I was **engineering systems that think**.

---

## The Engineer I Was vs. The Engineer I’m Becoming

I came in thinking this would be a crash course in APIs and ML jargon.

What I got was a hands-on masterclass in **system design, evaluation, debugging, and user-centered product thinking**, but in a world where the “functions” are stochastic, the “components” talk back, and the “compiler” is a neural network in the cloud.

It didn’t feel like studying AI.  
It felt like **building the future**.