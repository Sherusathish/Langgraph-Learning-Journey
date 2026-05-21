#  LangGraph + Gemini AI Projects

##  Core Concepts (Important)

###  State
State is a shared data object that flows through the graph.  
It stores and updates information between nodes during execution.

 Official Docs:  
https://docs.langchain.com/oss/python/langgraph/graph-api

---

### 🔷 Node
A node is a function that performs a task in the workflow.  
Each node takes state as input and returns updated state.

---

### 🔁 Edge
An edge defines the connection between nodes.  
It controls the flow of execution from one node to another.

---

## 📚 For More Details
👉 https://docs.langchain.com/oss/python/langgraph/graph-api  
👉 https://python.langchain.com/docs/

---

#  Projects in This Repository

### 1️⃣ Basic Graph
- START → Node → END execution flow

### 2️⃣ Conditional Routing
- Dynamic branching logic

### 3️⃣ Gemini Chatbot
- LLM-based chatbot using Gemini

### 4️⃣ Tool Calling Agent
- Stock price tool integration with LLM

### 5️⃣ Memory Chatbot
- Multi-turn conversation support

### 6️⃣ Human-in-the-loop System
- interrupt() + manual approval workflow

### 7️⃣ LangSmith Tracing
- Execution tracking using @traceable

### 8️⃣ Final Project: Candidate Screening System
- Resume classification (Entry / Mid / Senior)
- Skill matching (Python-based)
- Automated decision routing:
  - HR Interview
  - Recruiter Escalation
  - Reject

---

## Tech Stack
- Python
- LangChain
- LangGraph
- Google Gemini API
- dotenv

---

## Installation
```bash
pip install langgraph langchain langchain-google-genai python-dotenv