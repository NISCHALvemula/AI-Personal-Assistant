# AI Personal Assistant 

A personal AI assistant built using **LangChain** to demonstrate agent development, tool calling, conversation memory, middleware, and human-in-the-loop workflows.

## Features

-  Calculator Agent
-  Unit Converter
-  Contact Management
-  Email Tool (Human Approval)
-  Conversation Memory
-  Streaming Responses

---

## LangChain Concepts Demonstrated

This project demonstrates the following LangChain capabilities:

- Agent Creation (`create_agent`)
-  Tool Calling
-  Custom Python Tools
-  HumanMessage
-  System Prompt
-  Middleware
  - SummarizationMiddleware
  - HumanInTheLoopMiddleware
-  Conversation Memory (`InMemorySaver`)
-  Checkpointing
-  Streaming Responses
-  Multi-turn Conversations
-  Tool Messages
-  Configuration using Thread IDs

---

## Tech Stack

- Python
- LangChain
- LangGraph Checkpointer
- Pydantic
- Groq API

---

## Project Structure

AI-personal-assistant/
│── personal-assistant.ipynb
│── README.md
│── requirements.txt
└── .gitignore

---

## Future Improvements

- LangGraph workflow implementation
- Persistent database for contacts
- RAG integration
- Multi-agent architecture
- Web interface using Streamlit/Next.js

---

## Learning Outcome

This project was built while learning LangChain fundamentals. It combines multiple LangChain concepts into one practical AI assistant and serves as the foundation for future LangGraph-based agentic systems.
