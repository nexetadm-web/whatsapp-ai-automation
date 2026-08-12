# WhatsApp AI Automation with n8n

An AI-powered WhatsApp customer automation workflow built with **n8n, WhatsApp Cloud API, Google Gemini, and Supabase**.

This project automates incoming WhatsApp messages, processes them through an AI Agent, maintains customer context, extracts customer information, and sends intelligent responses back through WhatsApp.

---


## 🚀 Key Features

- WhatsApp Cloud API integration
- Automated incoming message processing
- AI-powered customer responses
- Google Gemini integration
- n8n workflow automation
- AI Agent with conversation context
- Customer name extraction
- Customer information storage
- Supabase database integration
- Conversation memory
- Automated WhatsApp responses
- Webhook-based message processing
- Error handling and fallback responses

---

## 🧠 How It Works

```text
Customer
   │
   ▼
WhatsApp
   │
   ▼
WhatsApp Cloud API
   │
   ▼
n8n Webhook
   │
   ▼
Message Processing
   │
   ├── Customer Information
   │
   ├── Conversation Memory
   │
   └── Supabase Database
   │
   ▼
Google Gemini AI Agent
   │
   ▼
AI Generated Response
   │
   ▼
WhatsApp Cloud API
   │
   ▼
Customer
