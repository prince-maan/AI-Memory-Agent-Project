![Ai](https://github.com/prince-maan/AI-Memory-Agent-Project/blob/main/ffmfmf.png)

  This is a Main [Kaggle Project](https://kaggle.com/competitions/agents-intensive-capstone-project/writeups/new-writeup-1764739147251). 

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



---

## ✌️ Watch the Demo & Learn More

Want to see this AI Memory Agent in action? Or understand the full architecture in simple terms?


🎥 **Watch the Full Video Demo Here:** [View Video](https://youtu.be/8P2snkB7HYo?si=57rwEmyhNrBdjlvE)

🔊 **Watch the Full Demo Podcast Here:** [View Pocast](https://youtu.be/gSn2uq5ug4U?si=cgXrjvtZRJ3eInP7)


⚒️ How does to it work and how to ues it: [View PDF](https://github.com/prince-maan/AI-Memory-Agent-Project/blob/main/How%20does%20to%20it%20work%20and%20-how%20to%20ues%20it.pdf)


👾  Project Code: [---View Now---](https://github.com/prince-maan/AI-Memory-Agent-Project/blob/main/AI-Memory-Agent-Project.ipynb)


---

🤺 This project is also available on [Kaggle Notebook](https://kaggle.com/competitions/agents-intensive-capstone-project/writeups/new-writeup-1764739147251):

---

Join the 5-Day AI Agents Intensive Course: I was participating in the Join the 5-Day AI Agents Intensive Course , and this project was assigned to me.


> **Quick Summary:** This project demonstrates how to give an AI "Long-Term Memory." Unlike standard chatbots that forget everything after a refresh, this agent uses Google ADK to remember user details (like your name or birthday) forever. It's a proof-of-concept for building smarter Personal Assistants.

---












---

