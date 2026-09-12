<div align="center">

# Dinesh Gehlot

### Software Developer @ Propelius · I build LLM agents — and the tools to secure them

<p>
  <a href="https://www.linkedin.com/in/dinesh-gehlot-004418361">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/dinesh3000-htu">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="mailto:gehlotdinesh3000@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <img src="https://img.shields.io/badge/Surat,%20India-34A853?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location"/>
</p>

</div>

---

## About

I build AI applications for a living — at **Propelius Technologies** I work on an
agentic-AI e-commerce platform with **Python, LangChain, and LangGraph**, running LLM
workloads on Modal.

The more I build with LLM agents, the more the **security side** pulls at me. Agents read
untrusted content; tools get near-total trust from the model the moment they're connected.
There's a wide gap between shipping an AI agent and shipping one you can *trust* — and not
many people are working in that gap yet. So I build open-source tools there, and I like
finding the ways agents break as much as building them.

- 🔭 **Focus:** agentic AI, LLM tooling, and the security problems that come with them
- 🌱 **Also into:** network threat detection, applied ML, and clean backend architecture
- 🎓 B.Tech in Computer Science, Uka Tarsadia University
- 💬 Ask me about prompt injection, agent tool security, or LangGraph

---

## Featured projects

### 🛡️ [mcp-audit](https://github.com/dinesh3000-htu/mcp-audit) &nbsp;·&nbsp; security scanner for MCP servers
A tool an agent's tool metadata is inserted into the model's context with system-prompt
trust — so it's an instruction channel, not documentation. `mcp-audit` scans that channel
for hidden instructions, invisible Unicode payloads, cross-server interference, and
**definitions that change after you approve them** (the rug-pull case a one-time scan can't
catch). Console / HTML / SARIF output, 107 tests.
<br/>`Python` · `CLI` · `LLM security` · `static analysis`

### 🔀 [crosstalk](https://github.com/dinesh3000-htu/crosstalk) &nbsp;·&nbsp; a cross-tenant leak in agentic RAG, and its fix
A reproducible demo: when an agent's memory tool takes `user_id` as a *model-supplied*
argument, a prompt injection can read another tenant's private data. Same attack, two tool
designs — one leaks, one holds — because the secure design takes identity from the session,
not the model. Maps to **OWASP LLM06**.
<br/>`Python` · `LangChain` · `LangGraph` · `multi-tenancy`

### 🐺 [tracehound](https://github.com/dinesh3000-htu/tracehound) &nbsp;·&nbsp; threat hunting over packet captures
Reads a `.pcap`, reconstructs the conversations inside it, and flags the hostile ones —
port scans, C2 beaconing, cleartext credentials — each mapped to **MITRE ATT&CK**. Plus an
**IsolationForest anomaly layer with per-feature attribution** that says *why* a flow is
an outlier ("8σ above normal on inter-arrival"), not just a score.
<br/>`Python` · `dpkt` · `scikit-learn` · `MITRE ATT&CK`

<details>
<summary><b>More projects</b></summary>
<br/>

- **[ecommerce-api](https://github.com/dinesh3000-htu/ecommerce-api)** — a security-hardened C2C marketplace REST API (TypeScript, Express 5, Prisma 7, Stripe) with an authorization-focused test suite and OpenAPI docs.
- **[ytfetch](https://github.com/dinesh3000-htu/ytfetch)** — a clean command-line YouTube downloader built on yt-dlp: format/quality selection, URL validation, progress.

</details>

---

## Tech I work with

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</p>

---

<div align="center">

**Building in the open. If you're working on agentic AI or its security, let's talk.**

<a href="https://www.linkedin.com/in/dinesh-gehlot-004418361">LinkedIn</a> &nbsp;·&nbsp;
<a href="mailto:gehlotdinesh3000@gmail.com">Email</a>

</div>
