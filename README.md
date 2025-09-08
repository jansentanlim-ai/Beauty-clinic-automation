# 🚀 Automation Portfolio – AI & Workflow Integrations

This repository showcases my **automation portfolio**, where I design and build workflows that integrate **Airtable**, **OpenAI**, **VAPI Voice Agent**, and **Google Email**.  

The goal of these projects is to demonstrate my ability to create **AI-driven automations** that improve business processes, reduce manual work, and scale efficiently.  

---

## 📂 Workflows Included

### 1. Airtable → Google Email Automation  
📌 File: `Integration_Airtable_CLEAN.blueprint.json`  
- Automates email follow-ups to qualified leads stored in Airtable.  
- Ensures every lead gets a personalized response.  
- Lightweight and simple, perfect for entry-level automation.  

👉 [View details](airtable-email/README.md)  

---

### 2. Airtable → OpenAI → VAPI Voice Agent Automation → Panda  
📌 File: `airtable-openai-vapi-panda.blueprint.json`  
- An advanced workflow combining AI-powered analysis and automated voice calls.  
- Uses OpenAI to summarize company data, then VAPI makes personalized calls.  
- Follows up with emails and updates Airtable records.  

👉 [View details](airtable-openai-voice/README.md)  

---

## ⚙️ How to Use  
1. Import the `.blueprint.json` file into your automation platform (e.g., **n8n** or **Make**).  
2. Replace placeholders with your real credentials:  
   - `{AIRTABLE_BASE_ID}`  
   - `{AIRTABLE_TABLE_ID}`  
   - `{API_KEY}`  
   - `{GOOGLE_ACCOUNT_ID}`  
3. Run locally and test before moving to production.  

---

## 📸 Workflow Screenshots

### Airtable → Google Email  
![Airtable Email Workflow](docs/airtable-email-workflow.png)

### Airtable → OpenAI → Voice Agent  
![Airtable OpenAI Voice Workflow](docs/airtable-openai-voice-workflow.png)

---

## 📌 Notes
- All secrets (API keys, emails, phone numbers) are replaced with **placeholders**.  
- This repo is published as a **portfolio showcase**.  
- Each workflow includes a dedicated README with detailed explanation.  

---

## 🚀 About Me
I design and build **AI-driven automation workflows** to help businesses:  
- Save time  
- Scale outreach  
- Improve process efficiency  

This portfolio demonstrates my ability to integrate multiple platforms into end-to-end solutions.
