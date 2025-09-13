# Multi-Agent-Chat-System-with-Autogen
This project demonstrates how to build a multi-agent chat system using Autogen, Autogen-AgentChat , and the Groq API (LLaMA3). It allows you to create AI agents (Assistants, User Proxies, Group Chat Managers) that can interact with each other or simulate conversations with a user.

---

## How It Works  

1. Install dependencies (`autogen`, `autogen-agentchat`, `autogen-ext`).  
2. Set your **Groq API key** in the script.  
3. Define the **LLM configuration** (model, base URL, temperature).  
4. Create agents:  
   - `AssistantAgent` (AI assistant powered by Groq LLaMA3).  
   - `UserProxyAgent` (acts as the user, can run without human input).  
   - `GroupChatManager` (to handle multiple assistants).  
5. Run the script to start a console-based chat between agents.  

---

## Features  

- Multi-agent conversations using Autogen.  
- Integration with **Groq LLaMA3** for fast inference.  
- Configurable model settings (temperature, model size, API key).  
- Console-based group chat simulation.  
- Extendable for autonomous AI-to-AI workflows.  

---

## Tech Used  

- Python  
- [Autogen](https://microsoft.github.io/autogen/) – Multi-agent orchestration  
- [Autogen-AgentChat](https://pypi.org/project/autogen-agentchat/) – Agent chat framework  
- [Groq API](https://groq.com/) – Fast LLaMA3 inference  
- Console UI – For interaction and debugging  

