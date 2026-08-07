# Shreyas Gurav

<p align="center">
  <!-- Drag-and-drop your banner into any GitHub issue comment, copy the generated
       user-attachments URL, and paste it here to replace this placeholder. -->
  <img width="400" alt="Shreyas Gurav" src="https://github.com/Shreyas1015.png" />
</p>

<p align="center"><sub><em>
I build the boring layer under the impressive demo.<br />
Retrieval that returns the right chunk, endpoints that hold under load, pipelines that fail loudly instead of quietly — the parts nobody screenshots.<br />
Somewhere along the way I stopped trying to out-prompt the drift and started encoding the standard into the repo itself: a gate that fails the build, an import matrix that can't be violated, a spec that has to exist before the code does. That became <a href="https://github.com/Shreyas1015/create-rigel">rigel</a>.<br />
Now I do the same thing at work: put AI inside real financial infrastructure, then put guardrails around the AI.<br />
If I had one piece of advice: ship the measurement before you ship the model. Accuracy you can't reproduce is a rumour.
</em></sub></p>

**[shreyas-full-stack-portfolio.vercel.app →](https://shreyas-full-stack-portfolio.vercel.app)** · Mumbai, India

---

## Now

**SDE 1 @ [Aerem Solutions](https://www.aerem.co)** — India's solar-focused fintech group (Aerem, [NetZero Finance](https://www.aerem.co/about-us) — the only RBI-licensed solar NBFC — and Sunstore Solar). ~350 MW of rooftop solar enabled across 12 states, 2,000+ verified installers, $15M pre-Series B led by SMBC Asia Rising Fund. I work across the core products:

| Product | What it is | What I work on |
|---|---|---|
| **[SunStore](https://www.aerem.co)** | B2B solar equipment marketplace with embedded supply-chain finance (90–120 day credit) | Catalogue + procurement APIs, pricing and order flows, credit-line integration |
| **[Partner Portal](https://partner.aerem.co)** | All-in-one console for EPCs — loan leads, applications, design, procurement, monitoring | Lead → application → disbursal pipeline, dashboards, partner-facing services |
| **AeROC** | Inverter-agnostic remote operations centre — monitor, manage and diagnose every plant in one place | Telemetry ingestion, generation reporting, alerting and diagnostics surfaces |

**Integrating AI into the stack** — LLM + RAG workflows over solar documentation, partner queries and operational data, so the people running EPC businesses get answers instead of dashboards to interpret.

**Introduced the agent harness** — brought agent-first development into the team: written repo rules, path-scoped constraints, specialist review agents, and a mechanical gate that has to pass before anything merges. The same idea I open-sourced as [rigel](https://github.com/Shreyas1015/create-rigel).

**Creator of [rigel](https://github.com/Shreyas1015/create-rigel)** — `create-next-app` for teams building *with* coding agents. Scaffolds a repo that constrains the agent instead of trusting it.

```bash
npm create rigel@latest my-app   # Next.js · Express+TS · NestJS · FastAPI
```

Every template ships a layered architecture with a strict import matrix, a `.claude/` workflow, and a gate — typecheck, zero-warning lint, circular-dep check, architecture tests, coverage thresholds — that blocks the commit when the code is wrong.

**AWS Certified Developer – Associate** (Feb 2026 – Feb 2029).

---

## Open Source

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Shreyas1015/create-rigel"><b>create-rigel</b></a><br />
      <sub>Agent-first, gate-enforced project scaffolding for Claude Code · <a href="https://www.npmjs.com/package/create-rigel">npm</a></sub><br />
      <img src="https://img.shields.io/static/v1?style=for-the-badge&label=focus&message=agents%20%7C%20scaffolding%20%7C%20gates&labelColor=0ea5e9&color=111827" alt="focus agents scaffolding gates" /><br />
      <img src="https://img.shields.io/github/stars/Shreyas1015/create-rigel?style=flat-square&label=stars&color=f59e0b" alt="create-rigel stars" />
      <img src="https://img.shields.io/npm/dm/create-rigel?style=flat-square&label=downloads&color=60a5fa" alt="create-rigel downloads" />
      <img src="https://img.shields.io/npm/v/create-rigel?style=flat-square&label=version&color=22c55e" alt="create-rigel version" />
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Shreyas1015/starter-template"><b>starter-template</b></a><br />
      <sub>Production-grade Node.js starter · Docker, k8s, CI/CD, linting, testing</sub><br />
      <img src="https://img.shields.io/static/v1?style=for-the-badge&label=focus&message=node%20%7C%20infra%20%7C%20ci%2Fcd&labelColor=22c55e&color=111827" alt="focus node infra cicd" /><br />
      <img src="https://img.shields.io/github/stars/Shreyas1015/starter-template?style=flat-square&label=stars&color=f59e0b" alt="starter-template stars" />
      <img src="https://img.shields.io/github/forks/Shreyas1015/starter-template?style=flat-square&label=forks&color=60a5fa" alt="starter-template forks" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Shreyas1015/agentic-rag"><b>agentic-rag</b></a><br />
      <sub>Retrieval-augmented generation with agentic routing · Python</sub><br />
      <img src="https://img.shields.io/static/v1?style=for-the-badge&label=focus&message=rag%20%7C%20retrieval%20%7C%20llm&labelColor=a855f7&color=111827" alt="focus rag retrieval llm" /><br />
      <img src="https://img.shields.io/github/stars/Shreyas1015/agentic-rag?style=flat-square&label=stars&color=f59e0b" alt="agentic-rag stars" />
      <img src="https://img.shields.io/github/forks/Shreyas1015/agentic-rag?style=flat-square&label=forks&color=60a5fa" alt="agentic-rag forks" />
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Shreyas1015/Tripto-Client"><b>Tripto</b></a><br />
      <sub>B2B outstation travel platform · 3 stakeholder tiers · <a href="https://tripto-web.vercel.app">tripto-web.vercel.app</a></sub><br />
      <img src="https://img.shields.io/static/v1?style=for-the-badge&label=focus&message=b2b%20%7C%20full-stack&labelColor=fb923c&color=111827" alt="focus b2b full-stack" /><br />
      <img src="https://img.shields.io/github/stars/Shreyas1015/Tripto-Client?style=flat-square&label=stars&color=f59e0b" alt="Tripto stars" />
      <img src="https://img.shields.io/github/forks/Shreyas1015/Tripto-Client?style=flat-square&label=forks&color=60a5fa" alt="Tripto forks" />
    </td>
  </tr>
</table>

<sub>
Also: <a href="https://github.com/Shreyas1015/rigel-bookmarks-api">rigel-bookmarks-api</a> / <a href="https://github.com/Shreyas1015/rigel-bookmarks-web">rigel-bookmarks-web</a> (rigel dogfood builds), <a href="https://github.com/Shreyas1015/docker-setup-node">docker-setup-node</a>, <a href="https://github.com/Shreyas1015/ml-exps">ml-exps</a>, <a href="https://github.com/Shreyas1015/event-link-client">event-link</a>, <a href="https://github.com/Shreyas1015/apna-bharat-client">apna-bharat</a>, <a href="https://github.com/Shreyas1015/shreyas-portfolio">shreyas-portfolio</a>
</sub>

---

## Previously

**Software Engineer – Full Stack @ Schbang (Schbang Labs)** · Mumbai

| Built | Outcome |
|---|---|
| **Second Brain** — end-to-end production RAG pipeline (FastAPI + vector DB): chunking, embedding, semantic search over 200+ brand assets | Client onboarding cut from 2–3 weeks to 2–3 days (**70%**) |
| **LLM resume screening** — parsing, scoring, output-quality metrics and regression checks, wired to an ElevenLabs voice-interview step | 500+ candidates/cycle at **92%** scoring accuracy; hiring cycle 21 days → 2–3 days |
| **Meet transcription orchestration** — event-driven AWS (SQS/SNS/Lambda) chaining Whisper ASR, Recall AI dedup, LLM summarisation | **95%** transcription accuracy; 2 hours → **<5 min**; ~₹1 Cr/yr saved vs. the commercial alternative |
| **Latency work** — Redis (ElastiCache), RDS read replicas, indexed query tuning on LLM-serving endpoints | 500–800 ms → **sub-200 ms**; avg DB query time **−60%** |
| **8-microservice AWS architecture** — EC2, RDS, S3, SQS, SNS, ElastiCache, CloudWatch | Independent deploy boundaries, structured logging + alerting |
| **Cost optimisation** — EC2 right-sizing, S3 lifecycle policies, ElastiCache tiering, validated against a 3-month billing baseline | **~20%** AWS spend reduction with latency SLOs preserved |

12 production features owned end-to-end — requirements, schema, API, evaluation, deployment — with **zero unplanned rollbacks** across a 9-month window.

---

## Stack

| | |
|---|---|
| **AI / ML** | LLM APIs, RAG, vector DBs (pgvector, Pinecone), semantic search, prompt engineering, evaluation & quality metrics, agent harnesses |
| **Languages** | Python, TypeScript, JavaScript (ES6+) |
| **Backend** | FastAPI, Node.js, Express, NestJS, REST design, async processing, microservices |
| **Data** | PostgreSQL, MongoDB, Redis (ElastiCache), query optimisation, indexing |
| **Cloud** | AWS (EC2, RDS, S3, SQS, SNS, Lambda, ElastiCache, CloudWatch, SES), Docker, GitHub Actions, CI/CD |
| **Architecture** | Event-driven systems, multi-step LLM orchestration, production NLP serving, system design |

---

## Highlights

| Highlight | Detail |
|---|---|
| **Building fintech infrastructure** | SunStore, Partner Portal and AeROC at [Aerem](https://www.aerem.co) — the marketplace, lending and monitoring layer behind India's rooftop solar buildout |
| **Open-source tooling** | [create-rigel](https://github.com/Shreyas1015/create-rigel) on [npm](https://www.npmjs.com/package/create-rigel) — agent-first scaffolding across four stacks, with a mechanical quality gate |
| **Production RAG at scale** | Second Brain: retrieval over 200+ brand assets, 70% onboarding reduction |
| **Evaluated LLM systems** | 92% scoring accuracy on 500+ candidates/cycle, with defined output-quality metrics and regression checks |
| **AWS Certified Developer – Associate** | Serverless, CI/CD automation, IAM, service integration (Feb 2026 – Feb 2029) |
| **B.E. Computer Engineering** | Vasantdada Patil College of Engineering, Mumbai University · CGPA 7.75/10 |

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Shreyas1015/Shreyas1015/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Shreyas1015/Shreyas1015/output/github-snake.svg" />
    <img alt="github contribution snake" src="https://raw.githubusercontent.com/Shreyas1015/Shreyas1015/output/github-snake.svg" />
  </picture>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Shreyas1015&theme=transparent&hide_border=true&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=adbac7&dates=adbac7&currStreakNum=adbac7&sideNums=adbac7" alt="GitHub streak stats for Shreyas1015" height="165" />
</p>

<p align="center"><sub>Most production work lives in private org repos — public activity reflects personal projects only.</sub></p>

---

<p align="center">
  <a href="https://linkedin.com/in/shreyasgurav1015">LinkedIn</a> ·
  <a href="https://github.com/Shreyas1015">GitHub</a> ·
  <a href="https://www.npmjs.com/package/create-rigel">npm</a> ·
  <a href="mailto:shreyasss15.10@gmail.com">Email</a>
</p>
