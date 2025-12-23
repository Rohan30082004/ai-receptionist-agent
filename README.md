# 🤖 AI Chatbot Receptionist

An AI-powered chatbot receptionist built using an automation workflow that can:
- Handle incoming chat messages
- Respond intelligently using an AI agent
- Book and fetch calendar events
- Store and update user data in Google Sheets
- Act as a 24/7 virtual receptionist for businesses

---

## 🚀 Features

- 💬 **Real-time Chat Handling**
- 🧠 **AI Agent with Memory**
- 📅 **Calendar Event Creation & Retrieval**
- 📊 **Google Sheets Integration**
- 🔁 **Conditional Flow Logic**
- 🌐 **Webhook-Based Responses**
- 🏢 **Perfect for Receptionist / Assistant Use-Cases**

---

## 🛠️ Tech Stack

- **Automation Platform:** (Make / Flow-based Automation)
- **AI Model:** Groq Chat Model
- **Memory:** Persistent conversation memory
- **Integrations:**
  - Google Calendar
  - Google Sheets
- **Trigger:** Webhook / Chat Message Event

---

## 🧩 Workflow Overview

1. **Chat Message Received**
2. **Condition Check (If Node)**
3. **Initial Greeting (First-time users)**
4. **AI Agent Processing**
5. **Optional Tool Calls**
   - Create calendar event
   - Fetch existing events
   - Append or update Google Sheet
6. **Respond via Webhook**

---

## 📸 Workflow Diagram

![Workflow Diagram](./assets/workflow.png)

---

## 🧪 Use Cases

- Business website receptionist
- Appointment booking assistant
- Lead capture chatbot
- Internal team assistant
- Customer support automation

---

## 📂 Project Structure

```text
ai-chatbot-receptionist/
│
├── README.md
├── assets/
│   └── workflow.png
├── workflows/
│   └── ai_receptionist_flow.json
└── docs/
    └── setup.md

