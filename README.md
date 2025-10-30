# 🎓 TutorFlow

> A LangFlow-powered AI tutor that explains computer-science concepts using retrieval-augmented reasoning, Astra DB memory, and IBM watsonx.ai.

---

### Overview

**TutorFlow** is a personal experiment in building an intelligent, domain-specific tutoring agent - not just another chatbot.  
It began as a simple multi-tool prototype and evolved into a **context-aware tutor** capable of explaining code, algorithms, and problem-solving steps in natural language.  

The project’s goal was to understand how **LangFlow**, **vector databases**, and **large language models** can work together to create an agent that *thinks in steps* — retrieving relevant material, reasoning with it, and generating adaptive, conversational feedback.

This repository reflects that journey: learning to build modular agent workflows, connecting external tools, and structuring reasoning chains for more human-like explanations.

---

### Features

- **LangFlow Modular Design** – Built with visual node-based orchestration for clarity and scalability.  
- **Conversational Context** – Retains memory across sessions for personalized explanations.  
- **Retrieval-Augmented Generation (RAG)** – Uses **Astra DB** vector store and **IBM watsonx embeddings** for fact-grounded responses.  
- **Tool-Calling Logic** – Integrates calculator and parser nodes for technical questions.  
- **Pedagogical Prompting** – Tuned for step-by-step reasoning and tutor-style answers.

---


### Getting Started

1. **Import into LangFlow**
   - Open LangFlow
   - Click **“Import Flow”**
   - Upload the provided `CS Tutor.json`

2. **Set Environment Variables**
   - `ASTRA_DB_APPLICATION_TOKEN`
   - `ASTRA_DB_ID`
   - `WATSONX_API_KEY`

3. **Run the Flow**
   - Start your LangFlow workspace
   - Use the **Chat Input** node to begin a conversation
   - Try asking:  
     > “Explain how AVL tree rotations work.”  
     > “What is time complexity for merge sort?”  

---

### Tech Stack

| Component | Technology |
|------------|-------------|
| **LLM & Embeddings** | IBM watsonx.ai |
| **Memory Store** | DataStax Astra DB |
| **Framework** | LangFlow 1.6 |
| **Language** | Python 3.11 |
| **Architecture** | Retrieval-Augmented Generation (RAG) |

---

---

### ✨ Reflection

> This isn’t just a project — it’s where I learned how *agents actually reason*.

TutorFlow taught me that building with AI isn’t about generating text — it’s about **designing systems that connect context, logic, and communication**.  
From debugging vector store connections to tuning educational prompts, every iteration brought me closer to understanding how intelligent tutoring systems can actually scale.

---
