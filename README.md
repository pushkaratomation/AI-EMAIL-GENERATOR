# AI-EMAIL-GENERATOR
# 🚀 AI Email Generator & Document Automation Workflow

An automated workflow built with **n8n**, **OpenAI**, and **Google Workspace**. It captures a user-submitted email topic via a web form, uses AI to draft a professional email, generates a Google Doc in Google Drive, and sends the output via email as cleanly formatted HTML.

---

## 📌 Features

- 📝 **Web Form Interface:** Built-in public n8n form trigger to collect email topics and context from users.
- 🤖 **AI Email Generation:** Integrates OpenAI (ChatGPT) to draft structured, professional, and context-aware emails.
- 📄 **Google Docs Integration:** Automatically creates a designated Google Doc file in Google Drive and updates the document body with the email draft.
- ✉️ **Formatted Email Dispatch:** Sends the resulting email cleanly using HTML formatting to maintain paragraph structure, bold text, and lists.

---

## ⚙️ Workflow Architecture

```text
[ 🌐 n8n Form Trigger ] ──► [ 🤖 OpenAI Node ] ──► [ 📄 Google Docs (Create) ] ──► [ 📝 Google Docs (Update Body) ] ──► [ ✉️ Send Email (HTML) ]
