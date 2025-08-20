# The Intelligent Customer Feedback Processor

## 📖 Overview
The **Intelligent Customer Feedback Processor** is an automation workflow built with **n8n** that helps businesses quickly process customer feedback submitted through a website form.  
It uses AI-powered sentiment analysis to classify feedback as **Positive, Negative, or Neutral**, and routes it accordingly to improve customer support and team engagement.

---

## 🚀 Features
- **Webhook Trigger** – Captures new customer feedback submissions.
- **AI Sentiment Analysis** – Leverages an LLM to determine if the feedback is positive, negative, or neutral.
- **Smart Routing with Switch Node**:
  - 📉 **Negative Feedback** → Creates a task in Google Sheets (or any project management tool).
  - 🎉 **Positive Feedback** → Sends a celebratory message to Slack/Discord/Email for team motivation.
  - 😐 **Neutral Feedback** → Logs the entry in a Google Sheet for review.
- **Fully Automated** – No manual sorting required.

---

## 🖼️ Screenshots
<img width="1354" height="645" alt="1" src="https://github.com/user-attachments/assets/1da9a28b-7ea4-4c01-bf27-310d07353a7b" />
<img width="1354" height="645" alt="1" src="https://github.com/user-attachments/assets/27a20fbb-6daa-475c-a17e-f7c36c47fcd4" />
<img width="1354" height="645" alt="1" src="https://github.com/user-attachments/assets/2f96fbe6-0ea7-4fde-b014-2e1e305bc4dc" />

---

## 🛠️ Tech Stack
- [n8n](https://n8n.io/) – Workflow automation
- Webhook – Trigger point for feedback
- LLM – Sentiment analysis
- Google Sheets – Data storage
- Slack/Discord/Email – Notifications

---

## 📂 Workflow
1. Customer submits feedback via a form.
2. Workflow triggers via Webhook.
3. Feedback is analyzed by AI for sentiment.
4. Depending on sentiment:
   - Negative → Task created in Google Sheets.
   - Positive → Celebration message sent to team.
   - Neutral → Logged in Google Sheets for review.

---

## 🌟 Use Case
Perfect for businesses that want:
- Faster response to **unhappy customers**.
- Celebrating **positive experiences** internally.
- Organizing **neutral feedback** for later analysis.


