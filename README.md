<h1 align="center">Pranjal Jain</h1>

<p align="center">
  <b>Founding Engineer · Backend &amp; Distributed Systems</b><br>
  <sub>Bengaluru, India</sub>
</p>

<p align="center">
  <a href="https://pranjaljain.work"><img src="https://img.shields.io/badge/Portfolio-pranjaljain.work-0A0A0A?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/pranjaljn97/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:pranjal.jn97@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About

Backend engineer, **7+ years** building high-throughput, transaction-heavy distributed systems across **fintech, blockchain intelligence, and high-growth startups**.

I shipped a real-time **prediction market terminal 0 → 1** as a founding engineer — owning order management, portfolio tracking, and live market data — and I've designed and operated **petabyte-scale ingestion** in production on GCP and AWS.

I deliberately moved from engineering management back to hands-on IC work, because owning hard systems end to end is what I do best.

```text
order lifecycle · position state · reconciliation · reorg handling · replay & backfill
exactly-once sinks · schema evolution · back-pressure · freshness SLOs · multi-tenant lakehouse
```

- 🔭 Currently: order management, on-chain indexing, and low-latency streaming at **Fireplace**
- ⚙️ Comfortable at the layer where **correctness under concurrency** actually matters — no double-fills, no drift
- 💬 Ask me about **Kafka, ClickHouse, reorg-safe indexing, ingestion SLOs**, or why your pipeline is silently dropping rows
- ⚡ Fitness nerd, AI enthusiast, and long-term markets observer

---

### Tech

**Languages**
<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
</p>

**Backend & Services**
<p>
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django">
  <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSockets">
  <img src="https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white" alt="gRPC">
</p>

**Data & Storage**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black" alt="ClickHouse">
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka">
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white" alt="BigQuery">
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" alt="Airflow">
  <img src="https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Spark">
</p>

**Cloud & Infra**
<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform">
</p>

**Agentic**
<p>
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph">
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="MCP">
</p>

---

### Systems I've Built

**Prediction market terminal — 0 → 1** · *Founding Engineer*
Order management system covering order lifecycle, position state, and reconciliation against on-chain settlement, handling **concurrent writes without double-fills or drift**. Low-latency TypeScript backend serving the web app and a conversational agentic bot — REST, auth, and **WebSocket streaming** for live market and portfolio updates. Backed by a **Rust + ClickHouse** on-chain indexing service for position tracking, wallet-level PnL, search, and global leaderboards, with **reorg handling, replay, and backfill** keeping downstream state consistent.

**Petabyte-scale blockchain ingestion** · *TRM Labs*
Batch and streaming ingestion on GCP (BigQuery, Dataflow, Airflow) sustaining **10,000+ events/sec** across Aptos, ZKSync, and Hyperliquid — unlocking roughly **$2M in enterprise revenue**. Owned the keystone asset-transfer datasets behind AML and compliance detection models used by financial institutions and government agencies. Cut infrastructure spend **30% (~$100K/yr)** via storage tiering and containerized compute.

**Fulcrum — in-house data integration platform** · *Postman*
Scaled to **60+ integrations and 20+ internal contributors**, defining the connector interface and extension model the rest of engineering built against. Also built the near-real-time EL, server events, and clickstream pipelines underpinning company-wide analytics, and architected a multi-tenant **lakehouse** that raised downstream developer productivity **40%**.

---

### Open Source & Side Projects

| Project | What it is | Stack |
| --- | --- | --- |
| [**thea-agent**](https://github.com/pranjaljn97/thea-agent) | Personal AI agent on a free-tier GCP `e2-micro` — live on Telegram + WhatsApp. Config-in-git, secrets in Secret Manager, daily GCS backups. | `Terraform` `GCP` `Gemini` |
| [**dbt-monitor**](https://github.com/pranjaljn97/dbt-monitor) | Observability for dbt projects — run history, freshness, and failure surfacing. | `Python` `dbt` `Flask` |
| [**service-monitor**](https://github.com/pranjaljn97/service-monitor) | Service health monitoring API with pluggable checks and alerting. | `Python` `Flask` |
| [**insider-trade-scan**](https://github.com/pranjaljn97/insider-trade-scan) | Trade detection engine surfacing unusual activity on Polymarket by correlating live flows against historical baselines. | `Python` |
| [**optexity**](https://github.com/pranjaljn97/optexity) | Self-repairing automation cache for browser agents — compiles agentic runs into deterministic replays. **93% token reduction** measured. | `Python` `Playwright` |
| [**portfolio**](https://github.com/pranjaljn97/pranjaljn97.github.io) | Zero-dependency site at [pranjaljain.work](https://pranjaljain.work), on GitHub Pages. | `HTML` `CSS` |

Contributor to [browser-use](https://github.com/browser-use/browser-use) · [optexity](https://github.com/Optexity/optexity) · [hive](https://github.com/aden-hive/hive) · [airbyte](https://github.com/airbytehq/airbyte)

---

### GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=pranjaljn97&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=transparent&title_color=6E56CF&icon_color=6E56CF" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pranjaljn97&layout=compact&langs_count=8&hide_border=true&theme=transparent&title_color=6E56CF" alt="Top languages">
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=pranjaljn97&hide_border=true&area=true&color=6E56CF&line=6E56CF&point=FFFFFF&bg_color=00000000" alt="Contribution graph">
</p>

> Most of my work ships in private and org-owned repositories, so the public graph reflects only a slice of it.

---

### Experience

| Role | Company | When |
| --- | --- | --- |
| **Founding Engineer** | Fireplace | Feb 2026 — Present · Remote |
| **Senior Software Engineer** | TRM Labs | Sep 2024 — Jan 2026 · Remote |
| **Engineering Lead** | Zluri | Mar 2024 — Sep 2024 · Bengaluru |
| **Data Engineer → Technical Lead → Engineering Manager** | Postman | Jan 2019 — Apr 2024 · Bengaluru |
| **Co-Founder** | Eatopedia | Nov 2016 — Dec 2017 · Dehradun |

<sub>Promoted twice in five years at Postman; grew and led a team of 7 engineers.</sub>

---

### Achievements

- 🏆 **Airbyte Hackathon Winner** — Airbyte, Oct 2023
- 🚀 **Best Startup** — Google Startup Weekend, TechStars, Feb 2017
- 🌍 **Open Source Contributor** — Fluid, AChecker, Jan 2018

**Education** — B.Tech, Computer Science (Cloud Computing & Virtualization), University of Petroleum & Energy Studies, 2015–2019

---

<p align="center">
  <a href="https://pranjaljain.work">pranjaljain.work</a> ·
  <a href="https://www.linkedin.com/in/pranjaljn97/">LinkedIn</a> ·
  <a href="mailto:pranjal.jn97@gmail.com">pranjal.jn97@gmail.com</a>
</p>
