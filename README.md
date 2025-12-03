# 🧠 AI Agent with Long-Term Memory

This project demonstrates an intelligent **AI Agent** built using Google's Agent Development Kit (ADK) and Gemini models. Unlike standard chatbots that forget context after a conversation ends, this agent possesses **Long-Term Memory**.

## 🚀 Key Features

* **Session Management:** Handles short-term conversation threads seamlessly.
* **Long-Term Memory:** Can store user preferences, facts, and details across completely different sessions.
* **Automatic Ingestion:** Uses callbacks to automatically save important conversation details into memory without manual intervention.
* **Contextual Recall:** The agent can answer questions like "What is my favorite color?" in a new chat based on information given days ago.

## 🛠️ Tech Stack

* **Language:** Python
* **Framework:** Google ADK (Agent Development Kit)
* **Model:** Google Gemini (gemini-2.5-flash-lite)
* **Storage:** InMemorySessionService & InMemoryMemoryService

## 📂 How It Works

1.  **Initialization:** The system initializes a Runner with both Session and Memory services.
2.  **Learning:** When a user shares a detail (e.g., "My birthday is March 15th"), the agent stores this in the session.
3.  **Memorizing:** The session data is transferred to the Memory Service (either manually or automatically via callbacks).
4.  **Retrieving:** In a future conversation, if the user asks "When is my birthday?", the agent searches its memory bank and retrieves the correct date.

## 📸 Project Structure

* `day-3b-agent-memory.ipynb`: The main Jupyter Notebook containing the agent logic, memory implementation, and testing workflow.
* `requirements.txt`: List of dependencies required to run the project.

---

