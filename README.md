# Santiago Cione

AI Automation Specialist | Building production systems that eliminate manual work

Currently: AI Automation Engineer @ [Desorbitante](https://desorbitante.com) (remote, Madrid) | Co-Founder & CTO @ [Gercio](https://gercio.site)  
Buenos Aires, Argentina | Computer Engineering @ ITBA | Open to remote opportunities

---

## About

I build AI-powered automation workflows that run in production. From restaurant order systems to multi-client data pipelines, I focus on solutions that deliver measurable business impact.

Currently running automation infrastructure for 6+ clients while building Gercio, a SaaS that automates restaurant operations using conversational AI.

---

## 📦 Repositories

- **[job-assistant](https://github.com/sancoders/job-assistant)** — Chrome extension + n8n + Claude for AI cover letters & screening answers
- **[n8n-automations](https://github.com/sancoders/n8n-automations)** — production n8n workflows (Gercio ordering + job-search pipeline)
- **[OrdenesRestGercio](https://github.com/sancoders/OrdenesRestGercio)** — Gercio real-time kitchen display (Next.js + Supabase Realtime)
- **[gercio-landing](https://github.com/sancoders/gercio-landing)** — Gercio marketing landing (Next.js + Tailwind)

---

## Featured Projects

### [Gercio](https://gercio.site) - Restaurant Automation SaaS

Full-stack QR-based ordering system with AI conversational assistant, payment processing, and kitchen automation. Serving real customers in Buenos Aires.

**Tech Stack:**  
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Key Features:**
- AI agent handling customer orders via WhatsApp/web (GPT-4o-mini)
- Automated payment processing with Mercado Pago
- Real-time kitchen display system (WebSocket-based)
- Google Sheets CMS for menu management (non-technical friendly)
- Telegram notifications for waiters

**Impact:**
- Order processing: 5 min → <30 sec
- Payment reconciliation: 100% automated
- Menu updates: No developer needed (self-service via Sheets)

**Infrastructure:** Production deployment on Vercel (frontend) + self-hosted n8n on VPS + Supabase cloud database

**Code:** [Kitchen Display repo](https://github.com/sancoders/OrdenesRestGercio) · [Landing repo](https://github.com/sancoders/gercio-landing) · [n8n automations](https://github.com/sancoders/n8n-automations)

[Live Site](https://gercio.site) | [Demo App](https://v0-gercio.vercel.app) | [Kitchen Display](https://v0-real-time-kitchen-display.vercel.app)

---

### AI-Powered Job Search & Application Toolkit

Two connected projects I built to speed up my own job search and demonstrate the exact stack these roles ask for:

- **[job-assistant](https://github.com/sancoders/job-assistant)** — a Chrome extension + n8n workflow that turns any job posting into a tailored cover letter and answers to screening questions, with an LLM (Claude). Two modes: fast fit-scoring, and full application generation.
- **[n8n-automations → job-search](https://github.com/sancoders/n8n-automations)** — an n8n pipeline that pulls remote listings, filters by keywords/seniority, scores each 0–100 against my profile with an LLM, stores them in Supabase and pushes matches to Telegram.

**Tech Stack:**  
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude%20AI-191919?style=flat-square&logo=anthropic&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)

**Flow:**
```
Job posting → extension / n8n
  → keyword + seniority filter
  → LLM fit-scoring (0-100) + cover letter + screening answers
  → Supabase storage
  → Telegram notification
```

---

### Desorbitante - Multi-Client Data Pipeline

End-to-end data automation infrastructure for digital marketing agency supporting 6+ active clients.

**Tech Stack:**  
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![BigQuery](https://img.shields.io/badge/-BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

**Key Projects:**
- Multi-source data pipeline (Meta Ads API, SalesRobot, Instantly → BigQuery → Looker Studio)
- CRM standardization (Instantly → GoHighLevel integration across all client accounts)
- AI-powered lead classification and deduplication
- Real-time Slack notifications for LinkedIn responses

**Impact:**
- Client onboarding: 8 hours → 2 hours (standardized templates)
- Manual CRM review: Reduced ~60% (AI filtering)
- Dashboard updates: Manual → Real-time (hourly sync)
- Data consolidation: Eliminated for 6 clients

Production reliability: Systems running 24/7 with SLA requirements, OAuth2 flows, rate limit handling, comprehensive error monitoring.

---

## Technical Skills

### Core Automation & Integration
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![APIs](https://img.shields.io/badge/-REST%20APIs-009688?style=flat-square&logo=fastapi&logoColor=white)
![OAuth2](https://img.shields.io/badge/-OAuth2-EB5424?style=flat-square&logo=auth0&logoColor=white)
![Webhooks](https://img.shields.io/badge/-Webhooks-FF6B6B?style=flat-square)

Advanced n8n: Self-hosted production workflows, custom node understanding, complex error handling

### AI & LLMs
![Claude](https://img.shields.io/badge/-Claude%20AI-191919?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/-Prompt%20Engineering-FF6B6B?style=flat-square)

Production AI agents: Conversational flows, guardrails, cost optimization, evaluation

### Backend & Databases
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/-BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

### Frontend & Full-Stack
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

### APIs & Integrations
Meta Ads API • Mercado Pago • GoHighLevel • SalesRobot • Instantly • Telegram Bot API • Slack API • Google Sheets API

### DevOps & Infrastructure
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![VPS](https://img.shields.io/badge/-VPS%20Management-5C5C5C?style=flat-square&logo=linux&logoColor=white)

Self-hosted n8n on production VPS, cloud deployment, workflow monitoring

---

## By the Numbers

- 6+ clients supported via automation infrastructure
- 2+ production systems running 24/7
- Order processing cut from ~5 min to <30 sec (Gercio)
- ~60% reduction in manual CRM work (Desorbitante)
- ~1.5 years of production automation experience
- 20 years old (founded a company while studying engineering)

---

## Education & Certifications

**ITBA - Instituto Tecnológico de Buenos Aires**  
Computer Engineering (in progress, started Mar 2025)

**Key Certifications:**
- Databases and SQL for Data Science with Python - IBM (Jan 2025)
- Introduction to Programming with Python and Java - University of Pennsylvania (Oct 2023)
- Data Analysis Using Python - University of Pennsylvania (May 2023)
- Salesforce Administrator Training - Trailhead (Nov 2024)
- Version Control - Meta (May 2024)

---

## Currently Working On

- Acquiring first paying customers for Gercio
- Building reusable n8n workflow templates for common integrations
- Exploring multi-agent AI orchestration patterns
- Deepening knowledge in distributed systems and cloud architecture

---

## Let's Connect

I'm currently open to remote opportunities in:
- AI Automation Engineering
- n8n/Make/Zapier Specialist
- Integration Engineering
- AI Agent Development

**Contact:** [santiagocione9@gmail.com](mailto:santiagocione9@gmail.com)  
**LinkedIn:** [linkedin.com/in/santiago-cione-7b3a50173](https://linkedin.com/in/santiago-cione-7b3a50173)  
**Location:** Buenos Aires, Argentina | Remote, full-time or part-time

Looking for someone who can build automation systems that actually work in production? Let's talk.
