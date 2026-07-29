<div align="center"> <!-- HEADER BANNER --> <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Bitan%20Basu&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=AI%20Automation%20%26%20Implementation%20Specialist%20%7C%20Technical%20Solutions%20%26%20Consultation&descColor=a78bfa&descAlignY=60&animation=fadeIn" /> <!-- TAGLINE --> <h3> <em>I identify where AI creates measurable business value, build the system, and wire it into real workflows — from concept to live product.</em> </h3> <!-- BADGES --> <p> <img src="https://img.shields.io/badge/Location-Kolkata%2C%20India-7c3aed?style=for-the-badge&logo=googlemaps&logoColor=white" /> <img src="https://img.shields.io/badge/Open%20To-Remote%20Global%20%2F%20Bengaluru%20%2F%20Pune-10b981?style=for-the-badge&logo=remotework&logoColor=white" /> <img src="https://img.shields.io/badge/Experience-8%20Years%20Technical%20Solutions-f59e0b?style=for-the-badge" /> <img src="https://img.shields.io/badge/IBM-Data%20Science%20Certified-0062ff?style=for-the-badge&logo=ibm&logoColor=white" /> <img src="https://img.shields.io/badge/SOC%202-Master%20Implementer-6366f1?style=for-the-badge" /> </p> <p> <a href="mailto:bitan1basu@gmail.com"> <img src="https://img.shields.io/badge/Email%20Me-bitan1basu%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white" /> </a> &nbsp; <a href="https://bitanbasu.com"> <img src="https://img.shields.io/badge/Portfolio-bitanbasu.com-7c3aed?style=flat-square&logo=googlechrome&logoColor=white" /> </a> &nbsp; <a href="https://github.com/KIRA-Billion"> <img src="https://img.shields.io/github/followers/KIRA-Billion?label=Follow&style=flat-square&logo=github" /> </a> </p> </div>
🧠 Who I Am

I am an AI Automation & Implementation Specialist with 8 years as the technical bridge between enterprise clients and engineering teams at HP Inc. (SEA/AU region, 7 years) and Replicon/Deltek (Fortune 500 accounts, 1.5 years).

My background: gathering requirements, translating business problems into technical solutions, driving integrations with development teams, and communicating architecture decisions directly to client Directors and C-suite. The consistent thread — operating credibly on both sides of every technical conversation.

In 2025–26, I turned that depth into hands-on AI implementation. I founded QualityOS (live B2B SaaS), and built three further production systems demonstrating agentic AI, multi-agent orchestration, and enterprise workflow automation.

The role I occupy: Someone who identifies where AI creates measurable business value, scopes the implementation, builds the working system, and communicates the ROI to leadership in plain English — without needing a translator on either side.

🚀 Live Products & Projects
TriageOS — Agentic AI Ticket Triage & Routing Engine (Live Production)
<div align="center">

20-node n8n agentic workflow. Reads your SOPs. Classifies every ticket in under 2 seconds. Self-correcting: a second LLM diagnoses failures and retries — no silent wrong answers.

→ Live System → bitanbasu.com/triage (No login required)

</div>

Built with: n8n · ChromaDB · Groq Llama 3.3 70B · sentence-transformers · Flask · Supabase · Docker · Oracle Cloud · Slack

Dimension	Detail
🧠 Agentic RAG	Embeds tickets → retrieves top-5 SOP chunks via semantic search → classifies across 8 dimensions
🔄 Self-Correction	Confidence gate (LLM score × retrieval distance × citation check) → Critic LLM diagnoses failures and retries
⚡ Sub-2s latency	End-to-end including the agentic retry loop
📊 8-Dimension Output	Category · Urgency (P0–P3) · Sentiment · Routing team · Confidence score · SOP citations · Reasoning · Draft reply
🛡️ 6-Path Convergence	Success · Offtopic · Howto · Recovery · Human-review · Fallback — all converging into a single audit log
📋 Production Audit Trail	Every classification written to Supabase (Postgres) with full metadata · Conditional Slack alerting on P0/P1
🔒 Self-Hosted	ChromaDB + Flask embedder in Docker on Oracle Cloud — zero external data dependency

Business impact: At 200 tickets/day, automated classification at sub-2s latency saves the 30–60 seconds of manual triage per ticket — equivalent to 1–2 hours of senior agent time daily, compounding at scale.

QualityOS — AI-Powered QA & Coaching SaaS (Live B2B SaaS · Founder)
<div align="center">

Automatically audits 100% of support calls and tickets — not the 2–5% manual QA covers. Evidence-backed scorecards. One-click coaching packs. Zapier to 5,000+ platforms.

→ Live Product → getqualityos.com

</div>

Built with: Next.js 14 · FastAPI · Groq (Llama 3.3 70B + Whisper large-v3) · Supabase · Clerk · Railway · Vercel · Hybrid RAG (BM25 + LLM reranking) · Dodo Payments · Zapier

⚠️ Private repository — full codebase is proprietary. The live product is publicly accessible at getqualityos.com.

Feature	Detail
🎙️ Call QA	Upload .mp3 / .wav / .m4a → Groq Whisper transcribes → 8-parameter AI scoring with evidence quotes
🎫 Ticket QA	Analyse support tickets via Zapier — categorisation, SOP adherence, resolution accuracy scored automatically
📚 KB-Grounded Scoring	Upload your SOPs — Resolution & Compliance scored against your actual standards, not generic best practices
🟢 Pass / Coach / Flag	Automated verdicts (≥85 / 70–84 / <70) with action recommendations for team leads
📋 Coaching Pack PDF	One click generates a 6-page coaching session pack — evidence cards, wins, talking points, action items
⚡ Zapier Integration	Connects to 5,000+ platforms (Zendesk, Aircall, Freshdesk, Intercom, Salesforce) — zero manual triggering
👥 Team System	Shared KB, role-based access, team overview dashboard, per-agent trend tracking
💳 Full SaaS Infrastructure	Subscription billing · 14-day free trial · Production auth · Custom domain — complete, revenue-ready product

Market gap: Competitors (Klaus, MaestroQA, Scorebuddy) charge $500–2,000/month and cover only sampled interactions. QualityOS automates 100% coverage at a fraction of the price.

ClarityCS — LangChain Multi-Agent CX Intelligence System (Live)
<div align="center">

Five specialized agents. Pre-briefing + quality analysis + churn risk — all from one ticket ID.

→ View Repository · Live Demo

</div>

Built with: LangChain · ChromaDB · Groq / Llama 3.1 · HuggingFace Embeddings · Streamlit · Python

Agent 1 — Pre-Briefing Pipeline: Ticket ID → full customer history retrieval → churn risk analysis via ChromaDB RAG → structured 30-second agent brief before ticket open. Targets 3–5 minutes of AHT reduction per ticket at scale.

Agent 2 — Resolution Quality Analyser: Closed ticket → scores resolution 1–10 against policy standards → flags churn risk → recommends one specific action. Catches bad resolutions before customers escalate.

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

Business case: At 200 tickets/day, the pre-briefing agent alone saves 10–16 hours of senior agent capacity daily.

NexusCS — AI Operations Intelligence Platform + RAG Chatbot (Live)
<div align="center">

12-module AI platform. Role-based views for VP → L1 Agent. Conditional action engine. RAG ops assistant. Zero backend.

→ View Repository · Live Demo

</div>

Built with: RAG · OpenAI API · Sentiment ML · JavaScript · 183KB single file · Zero backend

Module	Description
📊 Executive Dashboard	Revenue-at-risk, Automation ROI — built for C-suite readability in 30 seconds
🎫 Ticket Queue	AI-prioritised with 6-filter sentiment scoring and SLA breach prediction
💚 Client Health Scoring	Composite scores from CSAT, sentiment, SLA compliance, and engagement signals
🔀 AI Triage Engine	ML-powered ticket classification with confidence scoring
⚙️ Workflow Builder	Visual automation builder with live Simulator for CS playbooks
📈 ML Pipeline Viewer	Live 5-step architecture: Ingest → Features → Model → Score → Action
🧠 Ops Assistant (RAG)	Role-aware chatbot — VP, CSM, CS Manager, L1 Agent views
🔬 Conditional Action Engine	Cross-signals sentiment × priority × churn risk → specific recommended action
💼 Career Highlights
2016 ──────────────────────────────────────────────────────► 2026
HP Inc. (7 Years)                  Replicon / Deltek      Founder · AI Builder
Technical Solutions Rep III        Sr. Support Services   QualityOS (SaaS)
SEA / AU Enterprise Accounts       Fortune 500 Accounts   TriageOS · ClarityCS
                                                          NexusCS
▼ Outcomes                         ▼ Outcomes             ▼ Now
- 4.7★ CSAT sustained              • 98% SLA compliance   • Remote-global
- 25% AHT improvement              • CEO-level escalations• AI Implementation
- Process standardisation          • RFC & technical      • Available immediately
  across 10+ person team             documentation
                                   • Architecture to C-suite
Metrics That Matter
<div align="center">
Metric	Result
✅ SLA Compliance	98% sustained across US enterprise accounts — Replicon
⏱️ Efficiency Improvement	25% via workflow redesign and process standardisation — HP Inc.
🎯 QA Automation	100% coverage — Pass/Coach/Flag in <30 seconds — QualityOS
⚡ Triage Latency	Sub-2 seconds end-to-end including agentic retry — TriageOS
🔄 First-Attempt Success	~80% correct classification on first pass — TriageOS
💰 SaaS Live	Complete revenue-ready product shipped solo — QualityOS
🤝 Enterprise Accounts	Fortune 500 clients · Director & C-suite communication — Replicon/HP
</div>
🛠️ Tech Stack
<div align="center">

AI & Agents

Show Image Show Image Show Image Show Image Show Image Show Image

Automation & Integration

Show Image Show Image Show Image Show Image

Backend & Data

Show Image Show Image Show Image Show Image

Product & Infrastructure

Show Image Show Image Show Image Show Image

</div>
📜 Certifications
🛡️ SOC 2 Master Implementer — Scytale Academy, May 2026 · Verify
🎓 IBM Data Science Professional Certificate — Coursera, 2025–26 · Verify
🎓 B.Tech — Electronics & Communication Engineering — Dr. Sudhir Chandra Sur Institute, 2016
<div align="center"> <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&animation=fadeIn" />

Available immediately · Open to AI Implementation, Automation, and Technical Solutions roles · Remote (Global) or Bengaluru / Pune

</div>
