# 🤖 BIGWave Digital Automation — QA & Testing Ecosystem for AI Agents

## 🚀 Project Overview
BIGWave Digital Automation focuses on engineering and validating multi-channel B2B AI-driven conversational agents (SDRs). This repository documents the complete Quality Assurance lifecycle—combining manual exploratory test strategies with automated web regression testing.

## 🎯 The Core System (Lopo)
The main product, **"Lopo"**, is an AI assistant orchestrated via **n8n workflows**, **OpenAI GPT-4o**, and messaging APIs (Evolution API). It automates lead qualification, business data entry, and CRM scheduling in production.

## 🛠️ Testing Methodologies & Structure

### 🧠 1. Manual & Conversational QA (From Field Logs)
Before automation, extensive field logs were simulated in production with real users to challenge the AI's natural language processing (NLP):
* **30+ Functional Test Cycles:** Covering memory retention, intent ambivalence, and API payload deliveries.
* **Defect Triage:** Documented **15+ structured Test Cases and Bug Reports** mapping conversational drift and boundary validation rules (achieving a **90% assertiveness rate**).
* *Artifacts location:* Checked inside the `/test-cases` directory.

### 💻 2. Automated Regression Testing (Cypress)
To secure product delivery and prevent user interface regressions, end-to-end (E2E) automated test scripts were deployed.
* **Framework:** Cypress & Node.js
* **Scope:** Automating web flows, contact forms, response metrics, and multi-language element verification on the live corporate site.

## ⚙️ Tech Stack Used
* **AI & Integration:** OpenAI GPT-4o | n8n Core | Evolution API | WhatsApp Business
* **QA & Automation:** Cypress | JavaScript (Node.js) | SelectorsHub | GitHub Workflows
* **Management:** Jira | ClickUp | Scrum Sprints

## 📬 Contact & Portfolio
* **LinkedIn:** [linkedin.com/in/iandra-morais](https://www.linkedin.com/in/iandra-morais/)
* **Live Product View:** [bigwaveautomacaodigital.com](https://bigwaveautomacaodigital.com/)
* **Email**: [iandramorais.gaia@gmail.com]
