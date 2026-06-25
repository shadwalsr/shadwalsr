<div align="center">

![Header Banner](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,8,12,14&height=220&section=header&text=Shadwal%20Singh&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20Engineer%20%7C%20Full-Stack%20Builder%20%7C%20Founder%20%40LitKit&descAlignY=55&descSize=18)

<a href="https://github.com/shadwalsr">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Building+production-grade+AI+systems;Founder+%40+LitKit+%7C+Founding+Team+%40+WhySchool;Architecting+RAG+pipelines+%26+multi-agent+systems;Always+shipping.+Always+building+in+public." alt="Typing SVG" />
</a>

<br/>
<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shadwalsr)
[![Email](https://img.shields.io/badge/Email-Reach%20Out-5B21B6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shadwalsr@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-6D28D9?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shadwalsr)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=shadwalsr&style=for-the-badge&color=8B5CF6&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/shadwalsr?style=for-the-badge&color=7C3AED&labelColor=4C1D95)
![Stars](https://img.shields.io/github/stars/shadwalsr?style=for-the-badge&color=A78BFA&labelColor=4C1D95)

</div>

---

## 🟣 About Me

I'm a **B.Tech Computer Science student at KIIT University** who builds production systems instead of waiting for permission to call himself an engineer. I architect full RAG pipelines, hybrid retrieval, RRF fusion, three-layer reranking, LLM-as-judge verification, and ship them as live platforms with real users, not toy demos.

**Founder of LitKit**, a literary social platform with 200+ early users and zero paid marketing. **Founding Team Member at WhySchool Academy.** I move across the full stack: backend APIs, vector databases, containerized deployment, and frontend UI, with a product engineer's instinct for what actually ships versus what just looks good in a demo.

- 🔭 Currently building autonomous multi-agent systems, graph-based RAG, and election data-science tooling
- ⚡ Proficient across prompt engineering, embeddings, LangChain/LangGraph orchestration, and MCP server architecture
- 🌱 Active open-source contributor, GSoC 2026 applicant to Honeynet's IntelOwl
- 🎯 **Open to:** AI/ML engineering internships, full-stack + AI roles, and GSoC / open-source collaboration

---

## 🟣 Tech Stack

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=python,ts,js,c,html,css&theme=dark" />

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=react,vite,tailwind&theme=dark" />

**Backend & Databases**
<br/>
<img src="https://skillicons.dev/icons?i=fastapi,supabase,redis,postgres&theme=dark" />

**Cloud, DevOps & Tooling**
<br/>
<img src="https://skillicons.dev/icons?i=docker,git,github,vscode,npm&theme=dark" />

</div>

> Also working daily with **Neo4j, ChromaDB, BM25/RRF hybrid retrieval, LangChain, LangGraph, CrewAI, AutoGen, Gemini 2.0 Flash, Groq (Llama-3), spaCy, Sentence Transformers, and MCP.**

---

## 🟣 AI / ML Expertise

| Domain | Proficiency | Details |
|---|---|---|
| **RAG Architecture** | ⭐⭐⭐⭐⭐ | Hybrid retrieval, BM25 + vector RRF fusion, three-layer Gemini reranking, LLM-as-judge citation verification |
| **Graph-Based Retrieval** | ⭐⭐⭐⭐ | Neo4j knowledge graphs, persistent graph memory, multi-hop relational query resolution |
| **Vector Databases** | ⭐⭐⭐⭐⭐ | ChromaDB, pgvector, FAISS, HNSW indexing, Sentence Transformers (`bge-small-en-v1.5`) |
| **LLM Orchestration** | ⭐⭐⭐⭐ | LangChain, LangGraph, CrewAI, AutoGen, function calling, structured Pydantic schemas |
| **Multi-Agent Systems** | ⭐⭐⭐⭐ | Autonomous ingestion pipelines, agent-based curation, MCP server integration |
| **Model Fine-Tuning & Optimization** | ⭐⭐⭐ | DistilBERT fine-tuning, ONNX INT8 quantization, low-latency inference (sub-20ms P95 target) |
| **Prompt Engineering** | ⭐⭐⭐⭐⭐ | Multi-model orchestration across Gemini, Groq (Llama-3), and Claude |

---

## 🟣 Featured Projects

<details>
<summary><b>🔭 GlaceX.ai - Autonomous AI Research Intelligence Platform</b></summary>
<br/>

An autonomous multi-agent system that crawls engineering blogs, arXiv papers, and RSS feeds, curates them through an NLP/LLM pipeline, and compiles automated technical digests, surfaced through a real-time telemetry dashboard.

| | |
|---|---|
| **Stack** | Python, HTTPX, Playwright, Supabase/PostgreSQL, spaCy, Sentence Transformers, Groq (Llama-3), Gemini, Pydantic, React, Vite, Tailwind CSS |
| **Scale** | Concurrent ingestion engine across dynamic engineering blogs, arXiv, and RSS feeds |
| **Performance** | Token-bucket rate limiting and persistent circuit breakers for safe high-volume ingestion |
| **Security** | Custom Supabase PostgreSQL transactional RPC functions to safely resolve unique-constraint conflicts |
| **Impact** | Automated Daily Digests with technical-depth scoring (0-100); real-time ops console tracking pipeline health, API latency, and circuit breaker status |
| **Repository** | [shadwalsr/glacex-ai](https://github.com/shadwalsr/glacex-ai) |

Built a semantic deduplication layer combining spaCy NER with vector embeddings to filter noise before it reaches curation, then wired the whole system into a glassmorphism dashboard with persistent "Saved Signals" bookmarking and UMAP-style visualizations.

</details>

<details>
<summary><b>🕸️ RAG-View - Graph-Based RAG Pipeline</b></summary>
<br/>

A graph-based retrieval-augmented generation pipeline built as the next installment after RAGRead, combining Neo4j knowledge graphs with hybrid BM25/vector retrieval and persistent graph memory.

| | |
|---|---|
| **Stack** | Neo4j, ChromaDB, BM25, RRF Fusion, Gemini 2.0 Flash, FastAPI, Redis, Docker Compose |
| **Scale** | Full graph-based RAG pipeline with persistent graph memory across sessions |
| **Performance** | 104% improvement on multi-hop relational queries over flat RAG; graph memory persistence cut API calls by up to 40% |
| **Security** | Fully containerized, isolated service architecture via Docker Compose |
| **Impact** | Documented across 24 engineering reports and a 20-slide LinkedIn carousel |
| **Repository** | 🔒 Private |

</details>

<details>
<summary><b>📚 RAGRead - Hybrid RAG Pipeline for LitKit</b></summary>
<br/>

The predecessor to RAG-View: a production-grade hybrid retrieval pipeline built to power semantic search across LitKit's literary content.

| | |
|---|---|
| **Stack** | Semantic + structure-aware chunking, dual-index HybridStore, BM25 + vector RRF fusion, Gemini Flash (three-layer reranking), FastAPI, Streamlit |
| **Scale** | Dual-index retrieval store serving LitKit's live content base |
| **Performance** | Empirically found structure-aware chunking outperformed semantic chunking on resume-style data |
| **Security** | LLM-as-judge citation verification layer to guard against hallucinated sources |
| **Impact** | Documented as a 12-part LinkedIn engineering series |
| **Repository** | 🔒 Private |

</details>

<details>
<summary><b>✍️ LitKit - Literary Social Platform</b></summary>
<br/>

A dark-aesthetic literary social platform where writing takes center stage: Masked Posts, Marginalia, LitChains, Digital Chapbooks, and live writing duels.

| | |
|---|---|
| **Stack** | React/TypeScript, FastAPI, Supabase/PostgreSQL |
| **Scale** | 200+ early users, live platform with multiple community forks |
| **Performance** | Strong organic engagement with zero paid marketing |
| **Security** | Supabase-managed auth and row-level access control |
| **Impact** | Pitch deck built for Antler India, 100X.VC, and Y Combinator outreach |
| **Repository** | 🔒 Private |

</details>

<details>
<summary><b>📩 SMS Spam Classifier - Low-Latency NLP Inference Service</b></summary>
<br/>

A production-style spam classification service built to demonstrate end-to-end model optimization, from fine-tuning to deployment.

| | |
|---|---|
| **Stack** | DistilBERT (fine-tuned), ONNX INT8 quantization, FastAPI, Docker |
| **Scale** | Single-model inference service, containerized for deployment |
| **Performance** | Targeting sub-20ms P95 latency post-quantization |
| **Security** | Containerized isolation via Docker |
| **Impact** | Portfolio piece benchmarking fine-tuning and quantization tradeoffs |
| **Repository** | 🔒 Private |

</details>

<details>
<summary><b>🧩 Other Builds</b></summary>
<br/>

- **ConstituencyIQ** - Bihar Assembly Election constituency-level voter segmentation and messaging recommendation engine. Full PRD and 14-phase build plan completed.
- **Sentry** - Automated conjunction risk triage copilot for small satellite operators, using CelesTrak TLEs and SOCRATES for backtesting.
- **Vault** - Personal web-based password manager built with Supabase auth and React/TypeScript.
- **Wordle Solver** - Autonomous Wordle solver with a three-layer architecture; entropy-based solver validated at 3.12 avg guesses and a 100% win rate.
- **LocalLoop** - Local business directory platform built during a hackathon sprint.

</details>

---

## 🟣 Experience

**Founder** · LitKit
`March 2026 - Present · 4 months`

Building LitKit, a focused platform where words take center stage: post anonymously, compete in live writing duels, and build a literary legacy one piece at a time.

- Architected the full product vision, tech stack, and engineering roadmap from zero to 200+ early users
- Built and shipped core features: Masked Posts, Marginalia, LitChains, Digital Chapbooks, live writing duels
- Drove investor outreach and pitch deck development (Antler India, 100X.VC, Y Combinator)

`React` `TypeScript` `FastAPI` `Supabase` `Product Strategy`

<br/>

**Founders Office, Production Lead** · WhySchool Academy
`February 2026 - June 2026 · 5 months · Bhubaneswar`

Founding team member at an edtech platform, operating directly out of the founders' office on production and execution.

- Owned production-side execution across the platform's core workflows
- Worked cross-functionally with founders to translate product vision into shipped output

`Product Execution` `EdTech` `Cross-Functional Leadership`

<br/>

**Team Lead** · Takshila Rural Immersion Programme, Takshila Educational Society
`October 2024 · 1 month · Siwan, Bihar, India`

A 5-day, on-site immersion into rural livelihood research and field data collection.

- Led on-ground data collection and analysis of rural lifestyle patterns
- Connected directly with local communities to surface actionable findings
- Presented recommendations on the programme's closing day

`Field Research` `Data Collection` `Leadership`

---

## 🟣 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🌍 **WHO Model United Nations** | Represented South Africa on the pandemic treaty and psychosocial health preparedness committee |
| 🛰️ **GSoC 2026 Applicant** | Applied to Honeynet's IntelOwl project |
| 🏆 **InnoVateX 2025 (Omega 5.0), FedKIIT** | Certificate of Participation, PPT Submission Round (via Unstop) |
| 💡 **Hackathon Build, LocalLoop** | Designed and shipped a local business directory platform end-to-end during a hackathon sprint |
| 📜 **IBM RAG and Agentic AI Professional Certificate** | Completed all 10 courses, capped with a multimodal AI capstone project |

</div>

---

## 🟣 Certifications

**IBM**

![IBM RAG and Agentic AI](https://img.shields.io/badge/IBM-RAG%20%26%20Agentic%20AI%20Professional%20Certificate-052FAD?style=flat-square&logo=ibm&logoColor=white)
![Advanced RAG](https://img.shields.io/badge/IBM-Advanced%20RAG%20with%20Vector%20DBs-052FAD?style=flat-square&logo=ibm&logoColor=white)
![Build RAG Applications](https://img.shields.io/badge/IBM-Build%20RAG%20Applications-052FAD?style=flat-square&logo=ibm&logoColor=white)

**Anthropic**

![Claude Code 101](https://img.shields.io/badge/Anthropic-Claude%20Code%20101-2D2D2D?style=flat-square)
![MCP Advanced Topics](https://img.shields.io/badge/Anthropic-MCP%3A%20Advanced%20Topics-2D2D2D?style=flat-square)

**Google**

![Google AI Essentials](https://img.shields.io/badge/Google-AI%20Essentials%20Specialization-4285F4?style=flat-square&logo=google&logoColor=white)

**LangChain**

![Intro to LangChain](https://img.shields.io/badge/LangChain-Intro%20to%20LangChain%20(Python)-1C3C3C?style=flat-square)

**Hugging Face**

![AI Agents Fundamentals](https://img.shields.io/badge/Hugging%20Face-AI%20Agents%20Fundamentals-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Udemy**

![C Programming](https://img.shields.io/badge/Udemy-C%20Programming%20for%20Beginners-A435F0?style=flat-square&logo=udemy&logoColor=white)

**Unstop / FedKIIT**

![InnoVateX 2025](https://img.shields.io/badge/Unstop-InnoVateX%202025%20(Omega%205.0)-8B5CF6?style=flat-square)

---

## 🟣 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=shadwalsr&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9D1D9" width="49%" />
<img src="https://streak-stats.demolab.com?user=shadwalsr&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" width="49%" />

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shadwalsr&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" width="60%" />

</div>

---

## 🟣 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=shadwalsr&theme=darkhub&no-frame=true&row=1&column=7&margin-w=8" />

</div>

---

## 🟣 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shadwalsr&theme=react-dark&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C9D1D9&hide_border=true" width="100%" />

</div>

---

## 🟣 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/shadwalsr/shadwalsr/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>

---

## 🟣 Current Focus

```yaml
current_focus:
  learning:
    - Multi-agent orchestration (LangGraph, CrewAI, AutoGen)
    - MCP server architecture and advanced retrieval systems
    - Applied NLP for political and space-tech data
  building:
    - GlaceX.ai - autonomous AI research intelligence platform
    - ConstituencyIQ - Bihar Assembly Election voter segmentation engine
    - Sentry - satellite conjunction risk triage copilot
  exploring:
    - Graph-based knowledge retrieval at scale
    - Election data science and political NLP
    - Space-tech risk analytics
  open_to:
    - AI/ML engineering internships
    - Full-stack + AI engineering roles
    - GSoC and open-source collaboration
```

---

## 🟣 Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-shadwalsr%40gmail.com-5B21B6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shadwalsr@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shadwalsr-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shadwalsr)
[![GitHub](https://img.shields.io/badge/GitHub-shadwalsr-6D28D9?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shadwalsr)

</div>

---

<div align="center">

*"Build in public, ship in silence, let the work speak."*

![Footer Banner](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,8,12,14&height=120&section=footer)

</div>
