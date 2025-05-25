# 🌤️ Task 2: The Rise of the WeatherMind - AI Assistant Project

Here is my submission for **Task 2** of the IIT Guwahati Coding Club Machine Learning Challenge — a creative project to build an intelligent AI assistant that can reason, remember, make decisions, and use tools. This project shows how a Language Model can be turned into a goal-driven AI system using **LangGraph** and tool integration.

---

## 📌 Task Summary

The goal was to create an **agentic AI** — a smart system that not only understands natural language but also plans, decides, and carries out tasks using external tools.

The requirements were:
- Build a chatbot with a large language model.
- Add tools like a calculator, weather info, and fashion advice.
- Enable smart decision-making to choose the right tool.
- Add memory to keep track of the conversation.
- Finally, create a **multi-agent system** that works together.

---

## ⚙️ Installation

To install all needed libraries, run this command:

```bash
pip install langchain langgraph openai google-generativeai duckduckgo-search pydantic matplotlib networkx
```
## 🧠 My Strategy & Approach

### 🌟 Level 1: Core Activation

- I created a simple chatbot using a Language Model (like Google Gemini or OpenAI).
- I added a calculator tool that can do basic math (following BODMAS rules).
- I used **LangGraph** to connect everything like a flowchart and also showed the graph.

✅ **Result**: My AI can now talk and do maths. I also made its structure visible as a graph.

---

### 🌐 Level 2: Senses of the World

- I added a **Weather Tool** to get current weather using a weather API.
- I also made a **Fashion Tool** that shows trending clothes in places like Tokyo using search.

✅ **Result**: Now my AI can check real-world data like weather and fashion trends.

---

### 🧭 Level 3: Judgement & Memory

- I made the AI smart enough to decide: "Should I calculate? Or show weather? Or fashion?"
- I also added **memory**, so the chatbot remembers previous messages and chats.

✅ **Result**: Now the AI can think better and have real conversations with memory.

---

### 🤖 Level 4: Multi-Agent System

- I created multiple mini AIs (agents) like:
  - One for weather
  - One for fashion
  - One for calculations
- I made a system that sends the question to the right agent, and all agents work together smoothly.

✅ **Result**: My AI system is now a team that talks and solves tasks together.

---

## 🧰 Tools & Libraries I Used

- `langchain` – to connect language models and tools  
- `langgraph` – to build smart flows between tools  
- `google-generativeai` – for using Google Gemini model  
- `Tomorrow Weather API` – to forcast weather
- `networkx` and `matplotlib` – to show the AI flow as a graph  
- `pydantic` – to handle data structures safely  

---

## 📒 About the Notebook

All the code and steps are in the Jupyter Notebook I uploaded:

- ✅ Each level has its own clear heading  
- ✅ I wrote comments and simple explanations  
- ✅ I also added some graphs to explain how my AI works  

---

