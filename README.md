# ⚡ AI Automation Engineering Portfolio

<div align="center">

[![GitHub](https://img.shields.io/badge/Author-Your%20Name-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username)
[![n8n Certified](https://img.shields.io/badge/Orchestration-n8n%20Enterprise-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io)
[![Google Gemini](https://img.shields.io/badge/LLM-Gemini%202.0%20Flash-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)
[![OpenAI](https://img.shields.io/badge/LLM-OpenAI%20GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com)
[![Pinecone](https://img.shields.io/badge/Vector%20Store-Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)](https://pinecone.io)
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL%20%2F%20Supabase-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)

**Production-grade AI agentic workflows, conversational RAG pipelines, data intelligence systems, and enterprise e-commerce automations.**

[Explore Projects](#-portfolio-projects) • [Architecture Philosophy](#-engineering-principles) • [Quickstart Guide](#-how-to-import-and-run) • [Connect](#-contact--connect)

---

</div>

## 📂 Repository Structure

ai-automation-engineering-portfolio/
│
├── README.md                               # Master Portfolio Overview
│
├── 01-ai-receptionist/                     # 24/7 AI Receptionist & Appointment Booking
│   ├── README.md                           # Deep-dive documentation
│   ├── workflow.json                       # Production n8n workflow file
│   ├── architecture.png                    # High-resolution system architecture
│   └── screenshots/                        # Canvas executions & screenshots
│
├── 02-ai-content-automation/               # Multi-Channel AI Content & Voice Engine
│   ├── README.md                           # Deep-dive documentation
│   ├── workflow.json                       # Production n8n workflow file
│   ├── architecture.png                    # High-resolution system architecture
│   └── screenshots/                        # Canvas executions & screenshots
│
├── 03-ai-intelligence-reporting/           # B2B Lead Intelligence & Automated Reporting
│   ├── README.md                           # Deep-dive documentation
│   ├── workflow.json                       # Production n8n workflow file
│   ├── architecture.png                    # High-resolution system architecture
│   └── screenshots/                        # Canvas executions & screenshots
│
├── 04-rag-ingestion/                       # Enterprise RAG Document & Vector Ingestion
│   ├── README.md                           # Deep-dive documentation
│   ├── workflow.json                       # Production n8n workflow file
│   └── architecture.png                    # High-resolution system architecture
│
└── 05-ecommerce-automation/               # Shopify Fulfillment, COD Filter & Retention
├── README.md                           # Deep-dive documentation
├── workflow.json                       # Production n8n workflow file
└── architecture.png                    # High-resolution system architecture



## 🚀 Portfolio Projects

| # | Project | Business Problem Solved | Core Stack | Architecture & Docs |
|---|---------|-------------------------|------------|---------------------|
| **01** | [**AI Receptionist & Booking Agent**](./01-ai-receptionist) | Recovers lost after-hours leads, eliminates manual appointment scheduling, and synchronizes customer CRM records. | `n8n` · `Gemini 2.0 Flash` · `PostgreSQL` · `Pinecone` · `Google Calendar` | [View Project](./01-ai-receptionist) |
| **02** | [**AI Content Automation Engine**](./02-ai-content-automation) | Eliminates high agency costs and repurposes brand URLs into multi-platform LinkedIn, Twitter/X, and video scripts. | `n8n` · `OpenAI GPT-4o` · `ElevenLabs` · `JavaScript` · `Airtable` | [View Project](./02-ai-content-automation) |
| **03** | [**AI Lead Intelligence & Reporting**](./03-ai-intelligence-reporting) | Filters competitor noise with regex gates, classifies leads into niches with GPT-4o-mini, and generates executive reports. | `n8n` · `GPT-4o-mini` · `Regex Gate` · `Swiftia API` · `Slack` | [View Project](./03-ai-intelligence-reporting) |
| **04** | [**Enterprise RAG Vector Ingestion**](./04-rag-ingestion) | Solves context fragmentation with sentence-aware semantic chunking and automated Pinecone vector indexing. | `n8n` · `OpenAI Embeddings` · `Pinecone` · `Supabase` | [View Project](./04-rag-ingestion) |
| **05** | [**E-Commerce Fulfillment Suite**](./05-ecommerce-automation) | Cuts Cash-on-Delivery (COD) Return-to-Origin rates via phone normalization, automated courier dispatch, and WhatsApp updates. | `n8n` · `Shopify API` · `Courier Logistics` · `WhatsApp API` | [View Project](./05-ecommerce-automation) |

---

## 🎯 Project Deep Dives

### [01 — AI Receptionist & Booking Agent](./01-ai-receptionist)
> **Problem**: Businesses lose up to 62% of inbound leads due to delayed message responses and manual scheduling friction.  
> **Solution**: An autonomous agent combining RAG FAQ retrieval, PostgreSQL session memory, dynamic Google Calendar CRUD scheduling, and human escalation.  
> **Key Decisions**: Sub-second Gemini 2.0 Flash reasoning, persistent database session keys, deterministic calendar parameter guards.  
> **Stack**: `n8n` · `Gemini 2.0 Flash` · `PostgreSQL` · `Pinecone` · `Google Calendar` · `WhatsApp`  
> 👉 [Read full documentation & view workflow](./01-ai-receptionist)

---

### [02 — Multi-Channel AI Content Automation Engine](./02-ai-content-automation)
> **Problem**: Repurposing articles and website updates into platform-native formats takes 4–6 hours per asset and lacks brand consistency.  
> **Solution**: Scrapes live URLs, strips boilerplate HTML, extracts brand DNA, and synthesizes LinkedIn carousels, Twitter threads, video scripts, and voiceover audio.  
> **Key Decisions**: Pre-LLM HTML cleansing reducing input tokens by 68%, parallel channel-specific prompts, strict JSON formatting.  
> **Stack**: `n8n` · `OpenAI GPT-4o` · `ElevenLabs API` · `JavaScript` · `Airtable / Webhooks`  
> 👉 [Read full documentation & view workflow](./02-ai-content-automation)

---

### [03 — AI Lead Intelligence & Executive Reporting](./03-ai-intelligence-reporting)
> **Problem**: Raw B2B scrape lists contain 30–50% competitor noise, wasting high-cost LLM API credits and manual SDR time.  
> **Solution**: Zero-cost deterministic regex gate filters competitors before passing qualified leads to low-temperature GPT-4o-mini for niche and pain-point classification.  
> **Key Decisions**: >40% API cost reduction through pre-LLM regex filtering, schema-enforced temperature 0.15 outputs, asynchronous polling queues.  
> **Stack**: `n8n` · `OpenAI GPT-4o-mini` · `LangChain` · `Regex Gate` · `Slack API`  
> 👉 [Read full documentation & view workflow](./03-ai-intelligence-reporting)

---

### [04 — Enterprise RAG Document & Vector Ingestion](./04-rag-ingestion)
> **Problem**: Arbitrary character-count chunking cuts off critical sentences, leading to poor vector recall and hallucinated RAG responses.  
> **Solution**: Production ETL pipeline featuring recursive semantic chunking (800-char window, 150-char overlap), OpenAI 1536-dim embeddings, and Pinecone namespace isolation.  
> **Key Decisions**: Sentence-boundary preservation, tenant/category namespace partitioning, rich metadata injection (`doc_id`, `created_at`).  
> **Stack**: `n8n` · `OpenAI text-embedding-3-small` · `Pinecone Serverless` · `PostgreSQL`  
> 👉 [Read full documentation & view workflow](./04-rag-ingestion)

---

### [05 — E-Commerce Order Fulfillment & Customer Retention](./05-ecommerce-automation)
> **Problem**: High Cash-on-Delivery (COD) Return-to-Origin rates caused by invalid phone formatting and manual courier dispatch friction.  
> **Solution**: Real-time Shopify order routing, custom phone number regex normalization, automated courier dispatch, and automated WhatsApp tracking.  
> **Key Decisions**: Deterministic phone formatting engine, conditional payment method branching, post-delivery review triggers.  
> **Stack**: `n8n` · `Shopify API` · `Courier Logistics REST API` · `WhatsApp Business API`  
> 👉 [Read full documentation & view workflow](./05-ecommerce-automation)

---

## 🛠️ Engineering Principles

1. **Deterministic Gates Before Generative Models**:
   Rule-based regex nodes and validation filters eliminate noise early, slashing token costs by 40–70% before invoking LLM calls.
2. **Schema-Enforced Outputs**:
   All LLM completions are bound to strict JSON schemas with low temperatures (0.0–0.2), guaranteeing seamless downstream data flow without parsing errors.
3. **Stateful Multi-Turn Persistence**:
   Conversational workflows leverage PostgreSQL database backends rather than volatile in-memory storage, preserving context across days and channels.
4. **Resilient Error Trapping & Idempotency**:
   Every HTTP endpoint and 3rd-party integration is equipped with retries, timeout bounds, and human-in-the-loop escalation paths.

---

## 💻 How to Import and Run

1. **Clone or download this repository**:
   ```bash
   git clone [https://github.com/MohammadAnasss/ai-automation-portfolio.git](https://github.com/MohammadAnasss/ai-automation-portfolio.git)
