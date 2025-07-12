# 🧠 Customer Support AI Workflow – n8n + Pinecone + OpenAI

This repository contains an automated **customer support workflow** built in **n8n**, using Gmail integration, AI-based text classification, contextual document retrieval from **Pinecone**, and intelligent response generation via **OpenAI GPT models**.

---

## 📌 Features

- ✅ **Gmail Trigger**: Listens for incoming emails using Gmail.
- ✅ **Text Classifier**: Categorizes the query (e.g., Tech, Other).
- ✅ **AI Agent**: Responds to messages using OpenAI, based on classification.
- ✅ **Pinecone Integration**: Searches pre-embedded project documents for accurate, context-rich replies.
- ✅ **Reply Automation**: Sends a response back via Gmail and marks it as `IMPORTANT`.

---

## 🧩 Workflow Overview

```plaintext
Gmail Trigger ➜ Text Classifier ➜ AI Agent ➜ Pinecone (if needed) ➜ Gmail Reply

