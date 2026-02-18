<h1 align="center">Hi 👋, I'm Abhinav Shrivastav</h1>
<h3 align="center">Aspiring AI Product Manager | Full-Stack Developer | Python & UI/UX Design | 365 Days of AI & Robotics | Python & LLMs | Ex-IEEE Chairperson
</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=22&duration=3000&color=36BCF7&center=true&vCenter=true&width=600&lines=Building+with+Code;Learning+Every+Day;Focused+on+Consistency" />
</p>

---

# 📂 Project 01: Stateful Personal Assistant (v1.0)

This is the first production-ready module of my AI Automation Lab. It focuses on solving the challenge of "contextual memory" in automated chat interfaces.

### 📝 Project Narrative

While many basic AI implementations are "stateless" (forgetting the user immediately), this version (v1.0) introduces **Window Buffer Memory**. I designed this to ensure that complex technical discussions—such as debugging Data Structures (e.g., Binary Trees)—can be handled over multiple exchanges without losing context.

### The Workflow

<img src = "https://github.com/abhinavshrivastavgit/AI-Automation-Lab/blob/main/minor/image_folder/01-stateful-ai-assistant_logic_workflow.png " alt ="The Workflow" width = "720px" >

### 🛠️ Technical Specifications

- **Orchestration:** n8n (using the "AI Agent" node for modularity)
- **LLM Engine:** Google Gemini 1.5 Flash
- **Memory Logic:** Window Buffer Memory (configured for a 5-exchange rolling window)
- **Trigger Type:** Synchronous "On Chat Message" (for zero-latency response)

### OUTPUT

<img src = "https://github.com/abhinavshrivastavgit/AI-Automation-Lab/blob/main/minor/image_folder/01-stateful-ai-assistant_logic_chat_preveiw01.png" alt = "Chat screenshot" width = "720px">

### 🚀 Future Roadmap for this Module

I have structured this project as **v1.0** to allow for the following future upgrades:

- **v1.1:** Implementation of Tool-calling (e.g., Google Search or Calculator).
- **v2.0:** Transition to Vector Database (RAG) for long-term knowledge retention beyond the session window.

### ⚙️ Installation

1. Download the `v1_assistant_engine.json` file from this folder.
2. Import it into n8n and connect your Gemini API credentials.
3. Test using the n8n Chat Hub.

---
