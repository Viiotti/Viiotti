<div align="center">

<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=220&section=header&text=Rafael%20Viotti&fontSize=42&fontColor=f0f6fc&fontAlignY=35&desc=AI%20Engineer%20%C2%B7%20Infrastructure%2C%20RAG%20%26%20LLMOps&descSize=18&descColor=8b949e&descAlignY=55&animation=fadeIn" width="100%" alt="header"/>

[![Portfolio](https://img.shields.io/badge/Portfolio-viiotti.github.io-1f6feb?style=for-the-badge&logo=google-chrome&logoColor=white)](https://viiotti.github.io/portifolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rafael%20Viotti-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafael-viotti-86364b1a1)
[![Email](https://img.shields.io/badge/Email-rafaelviotti@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rafaelviotti@gmail.com)

</div>

---

## 🧠 About

```
$ whoami
```

**AI Engineer** anchored in a **Systems & Reliability Foundation** — arriving at AI infrastructure from mission-critical operations rather than purely academic research.

Over **~46 months** of hands-on IT and engineering experience, I progressed through hardware repair → N2 field support (Feluma) → **NOC Network Monitoring Analyst (Contracted to SADA Transportes)** at Hyti → Observability and Integrity Security Analyst at Ana Gaming (*Developed Python/Bash automations for observability routines, log processing, and L1/L2 operational incident mitigation*) → **Senior AI Engineer (Contract)** for **6 months** at MaxStartup as the **Sole architect and developer** of the company's AI integrations and multi-agent platform.

Today I design and operate **self-hosted retrieval and multi-agent infrastructure** end to end — thinking about **latency, failure modes, and deterministic recovery** before model choice.

```python
class RafaelViotti:
    role       = "AI Engineer · Infrastructure, RAG & LLMOps"
    location   = "Belo Horizonte, MG 🇧🇷"
    foundation = "Systems & Reliability Foundation (~46 months IT & AI)"

    focus = [
        "Retrieval-Augmented Generation (RAG)",
        "Self-hosted AI Infrastructure",
        "Bounded Multi-Agent Orchestration & MCP Protocols",
        "LLM Observability & Tracing",
    ]

    philosophy = "Operations first, models second."
```

---

## 🔭 Focus & Engineering Philosophy

- **Operational Reliability First:** Grounded in a **Systems & Reliability Foundation** across NOC monitoring and operational integrity. Agentic systems are engineered around recoverability, telemetry, and strict network boundaries.
- **Recoverable Vector State:** Treating vector databases not as fragile state, but as derived, rebuildable indexes backed by authoritative filesystem knowledge tiers (`raw` / `reviewed` / `canonical`).
- **Cost & Boundary Control:** Zero external API cost for local embedding pipelines via Ollama (`nomic-embed-text`, `768d`) paired with bounded subagent execution (depth-one delegation, isolated child contexts, fail-closed design).

---

## 🛠 Flagship Architecture: Mother / Hermes & Tanya Public Showcase

**Mother / Hermes** is a self-hosted subagentic RAG platform built and operated end to end on dedicated Linux infrastructure:

- **Bounded Multi-Agent Orchestration:** LangGraph-based execution engine with depth-one subagent delegation, isolated child contexts, centralized validation, and **MCP protocols** for read-only semantic memory bridges.
- **Multi-Domain Vector Retrieval:** Self-hosted Qdrant deployment featuring a **Multi-Domain** collection architecture with per-domain isolation and local vector generation via Ollama (`nomic-embed-text`, `768d`).
- **Self-Hosted LangFuse Observability:** Full **Self-hosted LangFuse** stack (web, worker, ClickHouse, Postgres, MinIO, and Redis) instrumenting end-to-end trace latency, token utilization, and retrieval evaluation.
- **Hardened Host Boundary:** Dedicated Linux server managed via systemd services with access restricted behind a WireGuard-only nginx boundary and rehearsed index/state recovery drills.

<table>
<tr>
<td width="50%" valign="top">

### 🏛️ [`tanya-showcase`](https://github.com/Viiotti/portifolio/tree/main/tanya-showcase)
**Mother / Hermes Architecture**
Sanitized public architectural documentation, bounded delegation contracts, Multi-Domain Qdrant schemas, and engineering changelog for the Tanya host.
<br><br>
`Mother / Hermes` `Qdrant` `Ollama 768d` `Self-hosted LangFuse` `MCP`

</td>
<td width="50%" valign="top">

### 🏠 [`local-ai-stack`](https://github.com/Viiotti/local-ai-stack)
**Self-Hosted AI Infrastructure**
Production-oriented Docker stack for local LLM inference (Ollama), vector retrieval (Qdrant), observability (Self-hosted LangFuse), and Nginx edge routing.
<br><br>
`Docker` `Qdrant` `Ollama` `LangFuse` `Nginx`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌐 [`portifolio`](https://github.com/Viiotti/portifolio)
**Interactive Portfolio & Terminal**
Zero-dependency dark-mode SPA featuring an interactive terminal emulator, engineering case studies, and ATS-ready resume view.
<br><br>
`JavaScript` `CSS Grid` `HTML5` `Cloudflare Pages`

</td>
<td width="50%" valign="top">

### 🖥️ [`MainProject`](https://github.com/Viiotti/MainProject)
**Dev Environment & Dotfiles**
Automated idempotent bootstrap for Linux environments with Git-aware Bash prompts, custom Tmux splits, and sane developer defaults.
<br><br>
`Bash` `Tmux` `Linux` `Automation`

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

### Languages & Core
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### AI, RAG & LLMOps
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-6B4FBB?style=for-the-badge&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![LangFuse](https://img.shields.io/badge/LangFuse-000000?style=for-the-badge&logoColor=white)

### Infrastructure & Systems Reliability
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🎓 Education & Systems Foundation

- **B.S. (Tecnólogo) in Systems Analysis and Development (ADS)** — **PUC Minas** (*Jan 2026 – Jun 2028, in progress*)
- **Technical Degree in Computer Science** — **Cotemig** (*2018 – 2020*)
- **Systems & Reliability Foundation:** **~46 months** of documented IT operations, network monitoring, operational integrity, and AI engineering experience (plus ongoing independent work and CKA preparation in progress).

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Viiotti&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=1f6feb&icon_color=1f6feb&ring_color=1f6feb"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Viiotti&layout=compact&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=1f6feb"/>

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Viiotti&theme=github-dark-blue&hide_border=true&background=0d1117&ring=1f6feb&fire=1f6feb&currStreakLabel=1f6feb)](https://git.io/streak-stats)

</div>

---

## 📈 Contribution Graph

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Viiotti&theme=github-compact&hide_border=true&bg_color=0d1117&color=8b949e&line=1f6feb&point=f0f6fc&area=true&area_color=1f6feb)](https://github.com/ashutosh00710/github-readme-activity-graph)

---

## 🐍 Contributions

<div align="center">

![Snake animation](https://raw.githubusercontent.com/Viiotti/Viiotti/output/github-contribution-grid-snake-dark.svg)

</div>

---

<div align="center">

### 💬 *"I treat a vector index as derived, rebuildable state — not something precious."*

---

![Profile Views](https://komarev.com/ghpvc/?username=Viiotti&color=1f6feb&style=for-the-badge&label=PROFILE+VIEWS)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=120&section=footer" width="100%" alt="footer"/>

</div>
