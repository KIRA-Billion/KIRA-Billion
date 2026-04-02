<div align="center">

<!-- HEADER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Bitan%20Basu&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=AI%20CX%20Automation%20Specialist%20%7C%20CS%20Operations%20Lead&descColor=a78bfa&descAlignY=60&animation=fadeIn" />

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

I'm an **AI CX Automation Specialist** with **8+ years** building and running enterprise customer success operations at **HP Inc.** and **Replicon (Deltek)**.

My edge sits at a specific intersection the market is now actively naming: the **AI-Human Workflow Specialist** — someone who ensures AI actually improves how CS teams operate, rather than adding complexity on top of existing chaos. I take ML model outputs (sentiment scores, churn predictions, classification results), map them to real operational problems, and wire them into workflows that stakeholders can see, trust, and act on.

> **The market reality:** 90% of organisations now use AI in operations. Only 9% have reached AI maturity. That gap — between having the tools and actually operationalising them inside CX workflows — is exactly where I work.

**What drove me here:**
After leaving Replicon in late 2024, I sustained a serious accident (three disc herniations) that extended a planned upskilling period. During recovery I completed the IBM Data Science Professional Certificate, learned Python and LangChain from scratch, and built three working AI systems — NexusCS, ClarityCS, and QualityOS — as concrete demonstrations of the AI-Human Workflow capability. Fully recovered and available immediately.

---

## 🚀 Featured Projects

### NexusCS — AI CS Operations Intelligence Platform

<div align="center">

> A full-stack CS Operations platform — **not a chatbot.**
> A **manager and stakeholder visibility layer** with AI triage, ML pipelines, and real-time SLA intelligence.
>
> → [View Repository](https://github.com/KIRA-Billion/nexuscs) · [Live Demo](https://kira-billion.github.io/nexuscs)

</div>

| Module | Description |
|--------|-------------|
| 📊 **Executive Dashboard** | KPIs, health signals, revenue-at-risk — built for C-suite readability |
| 🎫 **Ticket Queue** | AI-prioritised queue with sentiment scoring and SLA breach prediction |
| 💚 **Client Health Scoring** | Composite scores from usage, CSAT, sentiment, and engagement signals |
| 🔀 **Routing Rules Engine** | Conditional rule-based ticket routing — no code required |
| ⚙️ **Workflow Builder** | Visual automation builder for CS playbooks and escalation paths |
| 🤖 **AI Triage Engine** | ML-powered ticket classification with confidence scoring |
| 📅 **SLA Tracker** | Real-time SLA monitoring with breach risk alerts |
| 📈 **Analytics Suite** | Trend analysis, volume forecasting, agent performance |
| 📥 **Data Import** | CSV/API ingestion layer with field mapping |
| 📡 **API Documentation** | Self-documenting REST API reference |
| 🧠 **Ops Assistant (RAG)** | Retrieval-Augmented AI for instant CS policy lookup |
| 🔬 **ML Pipeline Viewer** | Live 5-step architecture: Ingest → Features → Model → Score → Action |

---

### ClarityCS — LangChain Multi-Agent CX Intelligence System

<div align="center">

> A working LangChain agent system solving two of the most expensive hidden problems in enterprise CS operations.
>
> → [View Repository](https://github.com/KIRA-Billion/claritycs) · [Live Demo](https://claritycs.streamlit.app)

</div>

**Built with:** LangChain · ChromaDB · Groq / Llama 3.1 · HuggingFace Embeddings · Streamlit

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

### QualityOS — AI-Powered QA Automation Platform for CS Teams

<div align="center">

> Eliminates manual call QA — audio in, structured scorecard out.
> Evidence-backed scores, verbatim coaching briefs, and company KB grounding for resolution accuracy.
>
> → [View Repository](https://github.com/KIRA-Billion/QualityOS) · [Live Demo](https://qualityos.streamlit.app)

</div>

**Built with:** Groq Llama 3.3 70B · Groq Whisper large-v3 · Streamlit · ReportLab · pdfplumber · Plotly · Python · **100% free to run**

| Feature | Detail |
|---|---|
| 🎙️ **Audio transcription** | Upload `.mp3 / .wav / .m4a` → transcribed via Groq Whisper large-v3 |
| 🤖 **LLM QA scoring** | 8-parameter rubric scored with evidence quotes from the transcript |
| 📚 **KB grounding** | Upload SOPs / policy docs → Resolution & Compliance scored against your actual standards |
| 🟢 **Pass / Coach / Flag** | Automated verdicts with action recommendations for team leads |
| 💬 **Coaching briefs** | Specific, verbatim-ready notes — not generic feedback |
| 📈 **Agent trend tracking** | Score history, radar charts, AI-generated coaching summaries across interactions |
| 📄 **PDF export + Slack** | Professional report with KB audit trail + webhook integration |

**Why this project matters for CS Ops roles:**  
This is the direct operationalisation of what I did manually at Replicon — scoring agent interactions against policy, identifying coaching moments, and escalating systemic issues. QualityOS automates that entire layer, adds KB grounding so scores are verifiable against company standards, and produces output a team lead can use in a 1:1 without editing. Built end-to-end in 2 weeks.

---

## 💼 Career Highlights

```
2016 ──────────────────────────────────────────────────────► 2026

HP Inc. (7 Years)                  Replicon / Deltek      Recovery +
Senior Tech Support L2             Service Analyst        Upskilling
Team Captain (informal)            Fortune 500 CS Ops     NexusCS + ClarityCS

▼ Outcomes                         ▼ Outcomes              ▼ Now
• 25% AHT reduction                • 98% SLA compliance    • Remote-global
• 50+ agents mentored              • CEO-level accounts    • AI/Ops roles
• Multiple MVP Awards              • Workflow design
```

### Metrics That Matter

<div align="center">

| Metric | Result |
|--------|--------|
| ⏱️ AHT Reduction | **25%** via process redesign and workflow standardisation |
| ✅ SLA Compliance | **98%** sustained across US/EMEA enterprise accounts |
| 🎫 Ticket Deflection | **65%** via RAG-based Ops Assistant (NexusCS) |
| ⏰ Time Saved | **~47 hrs/month** for a 5-agent team (NexusCS simulation) |
| 🎯 QA Automation | **8-parameter** scored rubric — Pass/Coach/Flag in <30 seconds (QualityOS) |
| 👥 Team Scale | **12+ agents** led, **50+ new joiners** mentored |

</div>

---

## 🛠️ Technical Stack

```yaml
AI Orchestration & Agents:
  - LangChain            # Multi-tool agent orchestration — built ClarityCS with this
  - LangGraph            # Stateful agent workflows (concepts)
  - CrewAI               # Multi-agent frameworks (concepts)
  - AutoGen              # Microsoft multi-agent framework (concepts)
  - RAG Architecture     # Built and deployed in both NexusCS and ClarityCS
  - ChromaDB             # Local vector store for knowledge base retrieval
  - Groq / Llama 3.1     # Free-tier LLM — used in ClarityCS
  - OpenAI API           # GPT-4 integration for triage and classification

Automation & Workflow:
  - Make.com             # Enterprise-grade, SOC 2 compliant — deliberate choice over n8n
  - Zapier
  - Voiceflow
  - AI Agentic Workflows

Data & Analytics:
  - Python (Pandas · NumPy · Scikit-learn · Matplotlib)
  - SQL
  - Power BI
  - HuggingFace Embeddings
  - Jupyter Notebooks

CS/CX Platforms:
  - JIRA Service Management   # Primary platform depth
  - Freshdesk                 # Active study focus
  - Zendesk                   # Awareness level
  - Salesforce                # Awareness level
  - ServiceNow

Infrastructure:
  - Git / GitHub
  - Streamlit Cloud (deployment)
  - AWS (Cloud Basics)
  - REST API Design
```

> **On Make.com vs n8n:** Deliberately chosen for SOC 2 Type II compliance — a real requirement in Fortune 500 CS environments. Not a default; a defensible architectural decision.

---

## 📜 Certifications

🏅 **IBM Data Science Professional Certificate** — Coursera · Aug 2025 – Jan 2026
*6 courses: Machine Learning with Python · Data Science Methodology · Python for AI & Development · Databases & SQL for Data Science · Tools for Data Science · Python Project for Data Science*
→ **[View All Credentials & Verify Links](/certifications)**

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

Both NexusCS and ClarityCS are working demonstrations of exactly that capability.

---

## 📬 Let's Connect

Open to **remote-first** senior roles in:
- AI / CX Automation Specialist
- CS Operations Lead with AI mandate
- AI Workflow & Integration Architecture
- AI Platform Implementation / Agent Ops

**Target regions:** Remote First . Global · Australia · India (senior bands)

<div align="center">

[![Email](https://img.shields.io/badge/bitan1basu%40gmail.com-Send%20a%20Message-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bitan1basu@gmail.com)

</div>

---

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer&animation=fadeIn" />
<sub>Built with clarity of purpose. Open to the right opportunity.</sub>
</div>
