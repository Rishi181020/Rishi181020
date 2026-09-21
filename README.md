<h1 align="center">Hi, I'm Rishi 👋</h1>

<p align="center">
  <b>MS CS student at Santa Clara University · Systems Developer Intern at the Miller Center · Building RAG systems, agents, and AI that stays grounded in real sources</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rishi-dixit1810/"><img src="https://img.shields.io/badge/LinkedIn-Rishi%20Dixit-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:rdixit@scu.edu"><img src="https://img.shields.io/badge/Email-rdixit%40scu.edu-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/github/followers/Rishi181020?style=flat&logo=github&label=Followers" alt="GitHub followers">
</p>

---

## About me

I'm a Master's student in Computer Science & Engineering at **Santa Clara University** (2025–2027) and a Systems Developer Intern at the **Miller Center for Global Impact**, where I build org-scoped RAG and memory systems that answer only from cited, verified documents. Before grad school I spent nearly two years at **Jio Platforms** as a Software Development Engineer, building Angular micro-frontends and dashboards used by 100+ clients.

I'm most interested in the parts of AI that have to work in production: retrieval you can trust, agents that know when to escalate to a human, and pipelines that hold up on large document sets. I also like hackathons, because they force you to ship.

## 🏆 Hackathons

- **Winner (5th Place)**, Beta Fund AI Super Hackathon: **Vanity**, an agentic AI driving coach
- **2nd Place**, Apify × Scalekit Hackathon: **Relaynt**, a swarm-based DevOps pipeline agent

## 💼 Experience

**Systems Developer Intern, Miller Center for Global Impact (Santa Clara University)** · Jan 2026 – Present
- Built an org-scoped RAG/memory system (OCR, embeddings, context packs, metric and impact memories) with a GPT-4o chat layer that answers only from grounded, cited context
- Designed human-in-the-loop verification so reviewers resolve fiscal-year conflicts once, and verified facts override conflicting excerpts
- Tuned retrieval and generation policy (full-context vs. RAG, citation-aligned sources) to stop invented years and keep answers document-faithful
- Productionized the pipeline on FastAPI, Postgres/pgvector, and Redis/ARQ with multi-tenant isolation, cached metric snapshots, and reprocessing workers

**Software Development Engineer 1, Jio Platforms** · Dec 2023 – Aug 2025
- Built custom data-visualization dashboards with C3.js and Angular for 100+ clients, and planned the app architecture with Micro Frontend capabilities
- Integrated 100+ REST APIs with Angular Reactive Forms, improving customer onboarding by 15% and UI stability by 35%

**Full Stack Developer Intern, Cordiso Technologies** · Jan – May 2023
- Led the full development lifecycle with Angular, .NET, and MSSQL, building a searchable catalog with real-time pricing that ensured 99%+ quote accuracy and cut quote creation time by 30%

## 🚀 Projects

| Project | What it does | Built with |
|---|---|---|
| **Recognize** | Browser-native meeting intelligence. A Manifest V3 Chrome extension streams live audio to a FastAPI WebSocket server for real-time ASR and speaker diarization. People, decisions, and action items go into a Neo4j knowledge graph (92–95% extraction accuracy at 276 tok/sec), searchable across meetings in natural language, with a 3D interactive graph view. | Groq (Llama 3.3 70B), Neo4j, FastAPI, React, React Three Fiber, Chrome Extension |
| **[FrameChat](https://devpost.com/software/framechat)** | Multi-modal video RAG. Parallel processing cut analysis time by 60% (7-minute videos in under 2 minutes), and delta-based frame sampling cut inference costs by 85% versus brute force. | Python, AWS Bedrock (Nova), AWS Transcribe, OpenCV |
| **Relaynt** 🥈 | A swarm of 4 specialized LLM agents (build, test, deploy, infra) running in parallel. An orchestrator scores failure severity from 1 to 5, retries recoverable failures, and escalates critical ones to a human-approval dashboard. | FastAPI, Claude, asyncio, Scalekit, Apify |
| **Vanity** 🏆 | A personalized driver-training simulation with an agentic AI coach that gives adaptive coaching and real-time feedback. | Agentic AI |
| **[HealinMotion](https://github.com/Rishi181020/AI-Driven-Parkinsons-Actvity-Recommendation)** | Detects freezing-of-gait severity for Parkinson's patients from wearable sensor data and recommends activities, with a MedGemma-4B chatbot explaining each one. | Bi-LSTM, MedGemma-4B, vLLM on AMD MI300X, FastAPI, React Native |

## 🛠️ Tech I work with

**AI & LLM systems:** RAG & GraphRAG · vector search & embeddings · context engineering · human-in-the-loop verification · agentic & multi-agent orchestration · MCP servers · prompt & generation policy design · OCR · ASR & speaker diarization · multimodal pipelines

**Models & serving:** GPT-4o · Claude (Anthropic SDK) · Llama 3.3 70B (Groq) · Llama Nemotron NIM · MedGemma-4B · AWS Bedrock (Nova) · Ollama · vLLM · HuggingFace · LiteLLM · ROCm / AMD MI300X

**ML & frameworks:** PyTorch (PPO, reinforcement learning) · Bidirectional LSTM · LangChain · sentence-transformers · NetworkX · OpenCV

**Data & stores:** PostgreSQL/pgvector · ChromaDB · Neo4j (Cypher, vector index) · Redis/ARQ · MySQL · SQLite · SQLModel

**Engineering:** Python · TypeScript · JavaScript · SQL · FastAPI · Uvicorn · async Python · WebSockets · React · React Native (Expo) · Streamlit · Docker · AWS · Azure · Git · GitHub Actions

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white" alt="Angular">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat&logo=neo4j&logoColor=white" alt="Neo4j">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white" alt="Azure">
</p>

## 🎓 Education

- **M.S. Computer Science & Engineering**, Santa Clara University (Sep 2025 – Jun 2027), GPA 3.62
- **B.E. Information Technology**, Vishwakarma Institute of Information Technology, Pune (Aug 2019 – May 2023), GPA 3.82

## 🔭 Currently

- Building RAG and memory infrastructure at the Miller Center
- Taking AI/ML coursework at SCU
- Working on a portfolio site (coming soon)

## 📫 Reach me

The best way to reach me is [LinkedIn](https://www.linkedin.com/in/rishi-dixit1810/) or [rdixit@scu.edu](mailto:rdixit@scu.edu). I'm always up for talking about RAG, agents, or hackathon ideas.

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Rishi181020&label=Profile%20views&style=flat" alt="Profile views">
</p>
