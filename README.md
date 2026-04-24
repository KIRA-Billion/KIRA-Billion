<div align="center">

<!-- HEADER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Bitan%20Basu&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=AI%20Integration%20&%20Automation%20Specialist%20%7C%20CS%20Operations%20Lead&descColor=a78bfa&descAlignY=60&animation=fadeIn" />

<!-- TAGLINE -->
<h3>
  <em>Bridging ML model outputs → operational CS workflows → measurable ROI</em>
</h3>

<!-- BADGES -->
<p>
  <img src="https://img.shields.io/badge/Location-Kolkata%2C%20India-7c3aed?style=for-the-badge&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20To-Remote%20Global-10b981?style=for-the-badge&logo=remotework&logoColor=white" />
  <img src="https://img.shields.io/badge/Experience-8%2B%20Years%20CS%20Ops-f59e0b?style=for-the-badge" />
  <img src="https://img.shields.io/badge/IBM-Data%20Science%20Certified-0062ff?style=for-the-badge&logo=ibm&logoColor=white" />
</p>

<p>
  <a href="mailto:bitan1basu@gmail.com">
    <img src="https://img.shields.io/badge/Email%20Me-bitan1basu%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/KIRA-Billion">
    <img src="https://img.shields.io/github/followers/KIRA-Billion?label=Follow&style=flat-square&logo=github" />
  </a>
</p>

</div>

---

## 🧠 Who I Am

I am an **AI Integration & Automation Specialist** with **8+ years** building and running enterprise customer success operations at **HP Inc.** and **Replicon (Deltek)**.

My edge sits at a specific intersection the market is now actively naming: the **AI-Human Workflow Specialist** — someone who ensures AI actually improves how CS teams operate, rather than adding complexity on top of existing chaos. I take ML model outputs (sentiment scores, churn predictions, classification results), map them to real operational problems, and wire them into workflows that stakeholders can see, trust, and act on.

> **The market reality:** 90% of organisations now use AI in operations. Only 9% have reached AI maturity. That gap — between having the tools and actually operationalising them inside CX workflows — is exactly where I work.

---

## 🚀 Live Products & Projects

---

### QualityOS — AI-Powered QA Automation Platform *(Live B2B SaaS)*

<div align="center">

> Automatically scores 100% of support calls and tickets against your SOPs.
> Evidence-backed scorecards, verbatim coaching briefs, and one-click coaching pack generation.
>
> → [**Live Product → getqualityos.com**](https://getqualityos.com)

</div>

**Built with:** Next.js 14 · FastAPI · Groq (Llama 3.3 70B + Whisper large-v3) · Supabase · Clerk · Railway · Vercel · Hybrid RAG (BM25 + LLM reranking) · Dodo Payments

> ⚠️ This is a **private repository** — full codebase is proprietary. The live product is publicly accessible at [getqualityos.com](https://getqualityos.com).

| Feature | Detail |
|---|---|
| 🎙️ **Call QA** | Upload `.mp3 / .wav / .m4a` → Groq Whisper transcribes → 8-parameter AI scoring with evidence quotes |
| 🎫 **Ticket QA** | Analyse support tickets via Zapier — categorisation, SOP adherence, resolution accuracy scored automatically |
| 📚 **KB-grounded scoring** | Upload your SOPs and policy docs — Resolution & Compliance scored against your actual standards, not generic best practices |
| 🟢 **Pass / Coach / Flag** | Automated verdicts (≥85 / 70–84 / <70) with action recommendations for team leads |
| 📋 **Coaching Pack PDF** | One click generates a 6-page coaching session pack — evidence cards, wins, talking points, action items |
| ⚡ **Zapier Integration** | Connects to 5,000+ platforms (Zendesk, Aircall, Freshdesk, Intercom, Salesforce) — fully automated, zero manual triggering |
| 👥 **Team System** | Shared KB, role-based access (admin/member), team overview dashboard, per-agent trend tracking |
| 📈 **Agent Trends** | Score history, verdict distribution, weakest parameter tracking across interactions |
| 💳 **Full SaaS Infrastructure** | Subscription billing, 14-day free trial, persistent database, production auth, custom domain |

**Pricing:** Starter $79/month · Team $199/month · Enterprise custom · Founding member pricing active

---

### ClarityCS — LangChain Multi-Agent CX Intelligence System *(Live)*

<div align="center">

> A working LangChain agent system solving two of the most expensive hidden problems in enterprise CS operations.
>
> → [View Repository](https://github.com/KIRA-Billion/claritycs) · [Live Demo](https://claritycs.streamlit.app)

</div>

**Built with:** LangChain · ChromaDB · Groq / Llama 3.1 · HuggingFace Embeddings · Streamlit · Python

**Agent 1 — Pre-Briefing Pipeline:**
Takes a ticket ID → retrieves full customer history → runs churn risk analysis against CS policy via RAG → generates a structured 30-second agent brief before the ticket is opened. Targets 3–5 minutes of AHT reduction per ticket.

**Agent 2 — Resolution Quality Analyser:**
Takes a closed ticket → scores resolution quality 1–10 against policy standards → flags churn risk based on pattern signals → recommends one specific team lead action. Catches bad resolutions before customers escalate.

```
User Input (Ticket ID)
      │
      ▼
LangChain Agent (orchestrator)
      │
      ├── Tool 1: get_ticket_details()
      ├── Tool 2: get_ticket_history()
      ├── Tool 3: check_churn_risk_signals()
      ├── Tool 4: search_knowledge_base()    ← ChromaDB RAG
      └── Tool 5: score_resolution_quality()
      │
      ▼
Structured Brief / Quality Analysis
```

**Business case:** At 200 tickets/day, the pre-briefing agent alone saves 10–16 hours of senior agent capacity daily. One Enterprise account caught before churn covers months of salary.

---

### NexusCS — AI CS Operations Intelligence Platform *(Live)*

<div align="center">

> A full CS Operations platform — **not a chatbot.**
> A **manager and stakeholder visibility layer** with AI triage, ML pipelines, and real-time SLA intelligence.
>
> → [View Repository](https://github.com/KIRA-Billion/nexuscs) · [Live Demo](https://kira-billion.github.io/nexuscs)

</div>

**Built with:** RAG · OpenAI API · Sentiment ML · JavaScript · 183KB single file · Zero backend

| Module | Description |
|--------|-------------|
| 📊 **Executive Dashboard** | KPIs, health signals, revenue-at-risk — built for C-suite readability in 30 seconds |
| 🎫 **Ticket Queue** | AI-prioritised queue with sentiment scoring and SLA breach prediction |
| 💚 **Client Health Scoring** | Composite scores from CSAT, sentiment, SLA compliance, and engagement signals |
| 🔀 **Routing Rules Engine** | Conditional rule-based ticket routing — no code required |
| ⚙️ **Workflow Builder** | Visual automation builder for CS playbooks and escalation paths |
| 🤖 **AI Triage Engine** | ML-powered ticket classification with confidence scoring |
| 📅 **SLA Tracker** | Real-time SLA monitoring with breach risk alerts |
| 📈 **Analytics Suite** | Trend analysis, volume forecasting, agent performance |
| 📥 **Data Import** | CSV ingestion from Zendesk / Freshdesk / Salesforce / HubSpot |
| 📡 **API Documentation** | Reference architecture for webhook and REST integration patterns |
| 🧠 **Ops Assistant (RAG)** | Role-aware RAG chatbot — VP, CSM, CS Manager, L1 Agent views |
| 🔬 **ML Pipeline Viewer** | Live 5-step architecture: Ingest → Features → Model → Score → Action |

---

## 💼 Career Highlights

```
2016 ──────────────────────────────────────────────────────► 2026

HP Inc. (7 Years)                  Replicon / Deltek      AI Upskilling +
Senior Tech Support L2             Service Analyst        3 Live Products
Team Captain                       Fortune 500 CS Ops     Built & Shipped

▼ Outcomes                         ▼ Outcomes             ▼ Now
• 25% AHT reduction                • 98% SLA compliance   • Remote-global
• 50+ agents mentored              • CEO-level accounts   • AI/Ops roles
• Multiple MVP Awards              • Workflow design       • Open immediately
```

### Metrics That Matter

<div align="center">

| Metric | Result |
|--------|--------|
| ⏱️ AHT Reduction | **25%** via process redesign and workflow standardisation — HP Inc. |
| ✅ SLA Compliance | **98%** sustained across US/EMEA enterprise accounts — Replicon |
| 🎫 Ticket Deflection | **65%** via RAG-based Ops Assistant — NexusCS |
| ⏰ Time Saved | **~47 hrs/month** for a 5-agent team — NexusCS simulation |
| 🎯 QA Automation | **100% coverage** — Pass/Coach/Flag in <30 seconds — QualityOS |
| 👥 Team Scale | **12+ agents** led · **50+ new joiners** mentored — HP Inc. |
| 💰 SaaS Live | **$79–199/month** product shipped solo — QualityOS |

</div>

---

## 🛠️ Technical Stack

```yaml
AI Orchestration & Agents:
  - LangChain            # Multi-tool agent orchestration — built ClarityCS
  - RAG Architecture     # Deployed in NexusCS, ClarityCS, and QualityOS
  - ChromaDB             # Local vector store for KB retrieval
  - Hybrid RAG           # BM25 + LLM reranking — production approach in QualityOS
  - Groq / Llama 3.1/3.3 # Free-tier LLM — ClarityCS and QualityOS
  - Groq Whisper large-v3 # Audio transcription — QualityOS
  - OpenAI API           # GPT integration — NexusCS Ops Assistant
  - HuggingFace Embeddings # Local embeddings — ClarityCS

Automation & Workflow:
  - N8N                  # Self-hosted automation — workflow design
  - Make.com             # SOC 2 Type II compliant — enterprise deployments
  - Zapier               # 5,000+ platform integration — QualityOS
  - Webhook Design       # Event-driven automation patterns
  - REST API Integration # Freshdesk, Zendesk, JIRA, Salesforce connectors

SaaS Infrastructure (QualityOS):
  - Next.js 14 + TypeScript  # Frontend
  - FastAPI on Railway       # Backend
  - Supabase (PostgreSQL)    # Database
  - Clerk                    # Production auth
  - Dodo Payments            # Subscription billing (works from India)
  - Vercel                   # Frontend deployment
  - Cloudflare               # Domain + DNS

Data & Analytics:
  - Python (Pandas · NumPy · Scikit-learn · Matplotlib)
  - SQL
  - Power BI
  - Jupyter Notebooks

CS/CX Platforms:
  - JIRA Service Management  # Primary depth — 7 years live experience
  - Freshdesk / Freddy AI    # Automation, triggers, SLA policies
  - Zendesk                  # Triggers, automations, SLA
  - Salesforce               # Agentforce awareness
  - Replicon                 # Deep — data extraction, API, auth, integrations
```

> **On Make.com vs n8n:** Make.com deliberately chosen for SOC 2 Type II compliance — a real procurement requirement in Fortune 500 CS environments. Not a default; a defensible architectural decision.

---

## 📜 Certifications

🏅 **IBM Data Science Professional Certificate** — Coursera · Aug 2025 – Jan 2026
*6 courses: Machine Learning with Python · Data Science Methodology · Python for AI & Development · Databases & SQL for Data Science · Tools for Data Science · Python Project for Data Science*

🎓 **B.Tech, Electronics & Communication Engineering** — Dr. Sudhir Chandra Sur Institute · 2016

---

## 🌐 The Gap I Fill

The 2026 AI job market has a well-documented structural problem:

```
┌──────────────────────┐     ┌──────────────────────┐     ┌──────────────────────┐
│    ML Engineers      │     │    CS Operations     │     │     Executives       │
│                      │     │                      │     │                      │
│  Build the models    │     │  Run the workflows   │     │  Want the outcomes   │
│  Can't translate to  │──►  │  Can't read model    │──►  │  Currently see       │
│  operational teams   │     │  outputs or ROI      │     │  neither layer       │
└──────────────────────┘     └──────────────────────┘     └──────────────────────┘
                                        ▲
                                        │
                               ┌────────┴────────┐
                               │   I live here   │
                               │ AI-Human CX     │
                               │ Workflow Spec.  │
                               └─────────────────┘
```

**What this looks like in practice:**

- Sentiment model scores a ticket as high-distress → LangChain pipeline routes it with context already attached → CSM receives an alert with suggested action, not just a raw ticket number
- Churn risk score crosses threshold → Make.com multi-step workflow fires → executive health dashboard flags the account → report is generated before the QBR
- RAG assistant handles tier-1 query → deflection is logged → cost-to-serve reduction is quantified → finance gets a number they can act on

Most CS Ops professionals can execute step one. Most ML engineers don't track what happens after step one. The person who architects all three steps and presents the outcome in a board meeting is what the market now calls an **AI-Human Workflow Specialist.**

QualityOS, NexusCS, and ClarityCS are working demonstrations of exactly that capability.

---

## 📬 Let's Connect

Open to **remote-first** senior roles in:
- AI CX Automation Specialist
- CS Operations Lead with AI mandate
- AI Workflow & Integration Architecture
- AI Platform Implementation / Agent Ops

**Target regions:** Remote First · Global · Australia · India (senior bands)

<div align="center">

[![Email](https://img.shields.io/badge/bitan1basu%40gmail.com-Send%20a%20Message-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bitan1basu@gmail.com)

</div>

---

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer&animation=fadeIn" />
<sub>Built with clarity of purpose. Open to the right opportunity.</sub>
</div>
