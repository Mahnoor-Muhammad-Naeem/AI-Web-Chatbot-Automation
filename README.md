# 🤖 AI Website Chatbot Automation (n8n)

An **AI-powered website chatbot** built using **n8n** and **Google Gemini**, designed to automate real-time conversations, answer FAQs, fetch course details from Google Sheets, and log interactions for analytics.  
This project demonstrates intelligent workflow automation and web integration through n8n’s no-code/low-code environment.

---

## 🚀 Features

- 💬 **Conversational AI:** Powered by Google Gemini Chat Model for natural and context-aware responses.  
- 🧠 **Memory:** Retains short-term context during conversations using n8n’s memory node.  
- 📚 **Dynamic Responses:** Fetches FAQs and course details directly from Google Sheets.  
- 🧾 **Data Logging:** Automatically appends chat data to Google Sheets for reporting or CRM integration.  
- 🌐 **Website Integration:** Embeds into websites as a chat widget to assist visitors 24/7.  
- 🔄 **Completely Automated:** Handles triggers, data retrieval, and responses without manual input.

---

## 🧩 Tech Stack

| Tool / Service | Purpose |
|-----------------|----------|
| **n8n** | Workflow automation and orchestration |
| **Google Gemini** | Conversational AI / NLP model |
| **Google Sheets** | FAQ and course data storage |
| **JavaScript / Web Embed** | Chat UI on the website |

---

## 🖼️ Workflow Overview

The n8n flow connects multiple nodes for end-to-end automation:

- **Trigger:** Chat message received  
- **AI Agent:** Google Gemini Chat Model  
- **Memory:** Simple Memory Node  
- **Get Course Info / Get FAQ:** Read from Google Sheets  
- **Append Row:** Store chat logs in Google Sheets  

## 📸 Project Screenshots

### AI Web Chatbot Automation (Full Canvas)
![AI Web Chatbot Automation](./ai%20web%20chatbot%20automation.png)

### Chat Message (Trigger)
![Chat Message](./chat%20message.png)

### AI Agent
![AI Agent](./ai%20agent.png)

### Google Gemini Chat Model
![Google Gemini Chat Model](./google%20gemini.png)

### Simple Memory (Buffer Window)
![Simple Memory](./simple%20memory.png)

### Get Course Information
![Get Course Information](./get%20course%20information.png)

### Get Course Info (Alternate)
![Get Course Info](./get%20course%20info.png)

### Get FAQ
![Get FAQ](./get%20faq.png)

### Append Row in Sheet
![Append Row in Sheet](./append%20row.png)


---

## 🧠 AI Agent Prompt Configuration

### Prompt 1 – Initial System Message
![Prompt 1 – Initial System Message](./prompt%201.png)

### Prompt 2 – Multilingual Responses Test
![Prompt 2 – Multilingual Responses Test](./prompt%202.png)

### Prompt 3 – Course Information Flow
![Prompt 3 – Course Information Flow](./prompt%203.png)


## ⚙️ How to Use

### 1️⃣ Import Workflow
1. Open **n8n** (self-hosted or cloud).  
2. Navigate to **Workflows → Import from File**.  
3. Select `AI Web Chatbot Automation.json` from this repo.  

### 2️⃣ Configure Credentials
Create credentials in n8n for:
- **Google Sheets API**
- **Google Gemini API**

> ⚠️ Do not commit your real credentials — use n8n’s encrypted credential manager or a `.env` file.

### 3️⃣ Update Sheet IDs
Replace any sample Sheet IDs in the “Get FAQ” and “Get Course Info” nodes with your own.

### 4️⃣ Deploy
Activate the workflow and embed your chatbot iframe or script into your website.

---

## 🧠 Example Conversation

**User:** “Can you provide me some course details?”  
**Bot:** “We have the following courses:  
• AI for Freelancing – Learn how to use AI tools to find freelance work and generate content.  
• Photo Editing Basics – Beginner-friendly photo editing guide.”  

---

## 📁 Repository Structure

