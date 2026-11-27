# 🍰 Sweet Crumbs – Day 3: Your First AI Agent

## Project Overview
Sweet Crumbs is a bakery assistant project developed as part of the One Person Company – AI Agents Workshop.

On Day 3, I built a bakery assistant using LangChain. It answers customer questions, follows bakery instructions, maintains conversation history, and handles basic bakery-related queries.

## Topics Learned
- Chatbot vs AI Agent
- Four components of an AI Agent:
  - Brain (LLM)
  - Instructions (System Prompt)
  - Tools (Python Functions)
  - Memory (Conversation History)
- Agent Loop: Think → Act → Observe → Repeat
- Three levels of AI: Traditional AI, Generative AI, and Agentic AI
- LangChain basics
- Prompt Templates and Chains
- Testing AI assistant responses

## Technologies Used
- Python
- Google Colab
- LangChain
- LangChain-Groq
- Groq API
- CSV

## Sweet Crumbs Bakery Details

| Product | Price |
|---|---:|
| Plum Cake | ₹500 |
| Chocolate Cake | ₹650 |
| Cupcake | ₹80 |

### Business Rules
- Orders require 24 hours' notice.
- All cakes have eggless versions.
- Never promise an unconfirmed delivery time or location.
- If information is unavailable, respond: "I'll check with the owner."
- Keep responses friendly and concise.

## Implementation

### 1. Model Setup
- Installed LangChain and LangChain-Groq.
- Connected the Groq API using Google Colab Secrets.
- Initialized the language model.

### 2. Assistant Creation
- Created a system prompt with bakery facts and rules.
- Built a LangChain prompt template.
- Connected the prompt, language model, and output parser using a chain.

### 3. Conversation Memory
Implemented conversation history to remember previous messages during a conversation.

### 4. Testing
Created `tests.csv` containing customer questions and expected keywords.

Tested the assistant's responses using PASS/FAIL results and calculated the pass percentage.

### 5. Temperature Experiment
Changed the model temperature to compare response consistency and creativity.

### 6. Python Functions
Created bakery-related functions:
- `get_price(item, quantity)`
- `check_order_notice(hours_notice)`

### 7. LangChain Agent
Explored LangChain's `create_agent` and tested the assistant with bakery-related questions.

## Project Files

| File | Description |
|---|---|
| `Sweet_Crumbs_Day3.ipynb` | Day 3 Google Colab notebook |
| `tests.csv` | Customer questions and expected keywords |

## How to Run
1. Open Google Colab.
2. Upload `Sweet_Crumbs_Day3.ipynb`.
3. Add your Groq API key in Colab Secrets as `GROQ_API_KEY`.
4. Run all notebook cells in order.
5. Check the assistant responses and test results.

## Learning Outcomes
- Understood the difference between chatbots and AI agents.
- Learned the four components of an AI agent.
- Understood the agent loop.
- Built a bakery assistant using LangChain.
- Implemented conversation memory.
- Created CSV-based tests.
- Experimented with model temperature.
- Practised Python functions with type hints and docstrings.

## Next Step – Day 4
The next step is to give the Sweet Crumbs assistant tools to perform bakery operations, such as checking product prices and order availability.

---

**Workshop:** One Person Company – AI Agents Workshop  
**Project:** Sweet Crumbs Home Bakery  
**Day:** 3 – Your First Agent: What an Agent Is, and LangChain
