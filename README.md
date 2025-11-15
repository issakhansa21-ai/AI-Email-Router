# 🤖 AI Email Router – Built with n8n

This project is an intelligent email processing workflow built using **n8n**, integrating:
- 📨 Gmail (trigger incoming messages)
- 🤖 AI classification (Anthropic/OpenAI)
- ✅ ClickUp for task management
- 📅 Google Calendar for meeting scheduling
- 📬 Automated smart replies

---

## 🧠 Features

- Classifies emails: support, updates, internal tasks, etc.
- Creates or updates tasks in **ClickUp**
- Schedules meetings in **Google Calendar**
- Escalates to humans for complex issues
- Sends confirmation replies via Gmail

---

## 🛠️ Tech Stack

- n8n (automation)
- ClickUp API
- Gmail API
- Google Calendar API
- OpenAI + Anthropic (Claude)
- AI Agent Nodes

---

## 📸 Workflow Preview

![Workflow Screenshot](./screenshot1.png)

---

## 🔄 How to Use

1. Import the `ai-email-router-workflow.json` file into your n8n instance.
2. Connect your:
   - Gmail account
   - ClickUp account
   - Google Calendar
3. Replace any placeholder values (emails, space IDs, calendar IDs)
4. Run & test!

---

## 📬 Contact

Made with ❤️ by [Your Name]  
Course: AI Agents with n8n  
Mentor: @Sinan

