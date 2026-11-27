<div align="center">

# ⚡ Bright Onwe
### **AI Systems & Autonomous Agentic Engineer | Distributed Systems & Inference Infrastructure**
*Architecting resilient multi-agent platforms, formal state machine verifiers, and high-throughput inference runtimes.*

<p align="center">
  <a href="https://www.gaussianlabs.dev"><img src="https://img.shields.io/badge/Gaussian%20Labs-gaussianlabs.dev-EA580C?style=for-the-badge&logo=vercel&logoColor=white" alt="Gaussian Labs" /></a>
  <a href="https://www.skills.google/public_profiles/d2470d05-5fd4-4d76-8998-8ca626a42eba"><img src="https://img.shields.io/badge/Google%20Skills-Diamond%20League%20(6000%2B%20pts)-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Skills Diamond League" /></a>
  <a href="https://www.skills.google/public_profiles/d2470d05-5fd4-4d76-8998-8ca626a42eba"><img src="https://img.shields.io/badge/GEAR-Enterprise%20Agent%20Ready-34A853?style=for-the-badge&logo=google&logoColor=white" alt="GEAR Enterprise Agent Ready" /></a>
  <a href="https://g.dev/brightonwe"><img src="https://img.shields.io/badge/Google%20Developer-Profile-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Developer Profile" /></a>
  <a href="https://devpost.com/brightonwe30"><img src="https://img.shields.io/badge/Devpost-Portfolio-003E54?style=for-the-badge&logo=devpost&logoColor=white" alt="Devpost Portfolio" /></a>
  <a href="https://x.com/bladeofshanghai"><img src="https://img.shields.io/badge/Twitter/X-@bladeofshanghai-000000?style=for-the-badge&logo=x&logoColor=white" alt="Twitter/X" /></a>
  <a href="mailto:bright@gaussianlabs.dev"><img src="https://img.shields.io/badge/Email-bright@gaussianlabs.dev-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

---

## 🚀 About Me

I am an **AI Systems & Autonomous Agentic Engineer** and Electrical & Electronics Engineering student at the University of Ibadan, dedicated to architecting resilient, production-grade **autonomous multi-agent systems**, **distributed systems coordination**, **formal software verification**, and **high-throughput inference runtimes**.

- 🧠 **Enterprise Agentic Architectures & Distributed Systems:** Multi-agent asynchronous DAGs, actor-model concurrency, finite state machines (FSM), deterministic state transition guards, and idempotency keys to eliminate context poisoning and circular delegation deadlocks.
- 🛡️ **Formal Verification & Reliability:** Deterministic verification boundaries outside stochastic LLMs, Abstract Syntax Tree (AST) mutation analysis, and rigorous pre/post-condition assertion kernels (e.g., [Linus](https://github.com/Tony-Stark2025/linus) with 268 automated tests).
- ⚡ **Inference Engineering & Post-Training:** Profiling KV-cache memory pressure, continuous batching, chunked prefill, speculative decoding, time-to-first-token (TTFT) latency tuning, and test-time compute scaling.
- 🔌 **Model Context Protocol (MCP):** Authoring custom `stdio` and `SSE` MCP servers & clients interfacing real-time observability telemetry (Grafana, GitHub, Jira, Slack).
- ☁️ **Google Cloud & Vertex AI:** Vertex AI Reasoning Engines, Agent Engine, Cloud Run serverless microservices, Cloud Build CI/CD, and GCP IAM.
- 🏆 **Honors & Certifications:** **Google Developer Diamond League** status (6,045+ points) and **17+ verified credentials** across Google Cloud, DeepMind, and the Gemini Enterprise Agent Ready (GEAR) curriculum.

---

## 🌟 Flagship Projects & Systems

### 🔒 [Piton — Lockfile & Supply-Chain Firewall for MCP Servers & AI Coding Agents](https://github.com/Tony-Stark2025/piton)
[![PyPI](https://img.shields.io/pypi/v/piton-cli?color=f97316&label=PyPI)](https://pypi.org/project/piton-cli/)
[![Release](https://img.shields.io/github/v/release/Tony-Stark2025/piton?color=0ea5e9)](https://github.com/Tony-Stark2025/piton/releases)
[![GHCR](https://img.shields.io/badge/GHCR-piton--sidecar-2563eb?logo=docker&logoColor=white)](https://github.com/Tony-Stark2025/piton/pkgs/container/piton-sidecar)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e.svg)](https://github.com/Tony-Stark2025/piton/blob/main/LICENSE)

> **The `package-lock.json` & supply-chain scanner for AI coding agents** (`Claude Code`, `Cursor`, `OpenCode`) — deterministic split SHA-256 MCP pinning, coding-agent hook RCE linting, offline shadow replay (`CEL`/`Cedar`), and a distroless Go Envoy v3 `ext_proc` sidecar. Built at [Gaussian Labs](https://www.gaussianlabs.dev).

- **Key Highlights:**
  - 📦 **Slim 2-Dependency CLI (`pydantic` + `pyyaml`):** Zero-install scan via `uvx piton-cli scan --repo .` and 5-line GitHub Action (`Tony-Stark2025/piton@v0.4.2`).
  - 🔐 **Split-Hash MCP Lockfiles:** Hard-blocks structural `inputSchema` drift everywhere and third-party description rug pulls, while keeping internal docstring edits warning-only.
  - 🕸️ **Coding-Agent RCE Lint:** Catches `.claude/settings.json` `curl|sh` hooks & `Bash(*)` wildcards, `.vscode/tasks.json` `folderOpen` autorun, malicious `.mcp.json` STDIO commands, and bidi Unicode smuggling in `.cursor/rules`.
  - 🚀 **Production Go Envoy Sidecar & Control Plane:** Multi-arch distroless GHCR image (`ghcr.io/tony-stark2025/piton-sidecar:0.4.2`) with live `tools/list` blocking, OIDC JWKS / RFC 8693 OBO, response projection, and Slack/Web MRTR approvals.
- **Tech Stack:** `Python 3.10+`, `Go 1.26`, `Envoy v3 ext_proc (gRPC)`, `CEL`, `Cedar`, `OpenTelemetry`, `Kubernetes / Helm`.
- **Links:** [Docs](https://tony-stark2025.github.io/piton/) · [PyPI (`piton-cli`)](https://pypi.org/project/piton-cli/) · [Try Vulnerable Demo Repo](https://github.com/Tony-Stark2025/piton-vuln-demo) · [Gaussian Labs](https://www.gaussianlabs.dev)

---

### 🛡️ [Prometheus — Enterprise Workstream Observability Platform](https://github.com/Tony-Stark2025/prometheus)
[![Status](https://img.shields.io/badge/Status-Active_Live_Deployment-success.svg)]()
[![Model](https://img.shields.io/badge/Model-Gemini_3.7_Flash-4285F4.svg)]()
[![Protocol](https://img.shields.io/badge/Protocol-Model_Context_Protocol-00C7B7.svg)]()

> **Autonomous AI Chief of Staff** correlating cross-functional engineering telemetry (GitHub PRs, Jira epics, Slack discussions) via ABAC security perimeters to proactively diagnose delivery blockers.

- **Key Highlights:**
  - 🌐 **Live Cloud Run Deployment:** High-availability web application & Vertex AI Agent Engine (`us-central1`).
  - 🔌 **Hybrid MCP Protocol:** Dual `stdio` and Server-Sent Events (`SSE`) MCP servers.
  - 🛡️ **Enterprise Security & ABAC:** Fine-grained Attribute-Based Access Control ($P(U, R)$) and inline PII sanitization.
  - 🧪 **Hermetic Quality:** Complete 5-tier test matrix with **157 hermetic automated tests**.
- **Tech Stack:** `Python 3.11`, `FastAPI`, `Gemini 3.7 Flash`, `Google Vertex AI`, `Model Context Protocol`, `OpenTelemetry`, `Docker`, `Cloud Run`.
- **Repository:** [Tony-Stark2025/prometheus](https://github.com/Tony-Stark2025/prometheus)

---

### 🎬 [Showrunner — Autonomous Studio Operations Copilot](https://github.com/Tony-Stark2025/showrunner)
[![Repository](https://img.shields.io/badge/GitHub-Showrunner-181717?logo=github&logoColor=white)](https://github.com/Tony-Stark2025/showrunner)
[![Vertex AI](https://img.shields.io/badge/Vertex%20AI-Gemini%203.7%20Flash-4285F4?logo=googlecloud&logoColor=white)]()
[![Grafana MCP](https://img.shields.io/badge/Grafana%20Cloud-MCP%20Server-F46800?logo=grafana&logoColor=white)]()

> **Enterprise VFX & Virtual Production Ops Copilot** built for the **Agentic Cinema Hackathon (Grafana Labs Track)**. Autonomously monitors, diagnoses, and self-heals VFX 3D render farms (Blender Cycles, Unreal Engine 5.4 Nanite) and virtual production LED volumes.

- **Key Highlights:**
  - 🤖 **Specialized Multi-Agent Crew:** Sentinel, Diagnostic, Remediation, and Executive agents with role-tailored reasoning budgets.
  - 📊 **Grafana MCP Integration:** Direct natural language tool querying for Loki logs, Tempo distributed traces, and Mimir telemetry.
  - 🖥️ **Cinematic Command Center:** High-density dark-mode operational UI with real-time incident simulators.
- **Tech Stack:** `TypeScript`, `Next.js 14`, `Vertex AI (Gemini 3.7 Flash)`, `Grafana MCP`, `TailwindCSS`, `Google Cloud Run`.
- **Repository:** [Tony-Stark2025/showrunner](https://github.com/Tony-Stark2025/showrunner)

---

### 🔍 [Linus — Deterministic AST & Agentic Dual Verifier](https://github.com/Tony-Stark2025/linus)
[![AWS Hackathon](https://img.shields.io/badge/Hackathon-AWS%20Agents%20for%20Humans-FF9900?logo=amazonaws&logoColor=white)]()
[![Bedrock](https://img.shields.io/badge/Runtime-Amazon%20Bedrock%20AgentCore-232F3E?logo=amazonaws&logoColor=white)]()
[![Tests](https://img.shields.io/badge/Automated%20Tests-268%20Passed-brightgreen.svg)]()

> **Deterministic AST & Agentic Intelligence Engine** built for the **AWS Agents for Humans Hackathon (Track 2: Professional Agents)**. Automatically catches catastrophic runtime failure modes in PRs before they reach production.

- **Key Highlights:**
  - ⚡ **Two-Tier Verification:** Combines zero-latency deterministic Python AST inspection (`linus.tools.ast_inspector`) with Claude 3.7 Sonnet reasoning.
  - 🛡️ **Subprocess Sandbox & Dual Verifier:** Synthesizes defensive boundary checks and commits permanent regression test suites.
  - 🧪 **Comprehensive Quality:** Tested and verified with **268 automated unit, integration, and stress tests**.
- **Tech Stack:** `Python 3.11+`, `Amazon Bedrock AgentCore`, `Strands Agents SDK`, `FastAPI`, `SSE Telemetry`, `Pytest`.

---

### 🛠️ [Agent DevKit — Automated Prompt Engineering & Synthetic Evaluator](https://github.com/Tony-Stark2025/Agent_DevKit)
> Command-line tool automating prompt generation, synthetic evaluation, and iterative refinement using Google's Agent Development Kit (ADK) and Gemini models.
- **Tech Stack:** `Python`, `Google Gemini SDK`, `CLI System Design`, `Evaluation Frameworks`.

---

### 🥗 [PlatePledge — AI-Powered Surplus Food Redistribution Platform](https://github.com/Tony-Stark2025/PlatePledge)
> Real-time surplus food redistribution system matching local restaurants and event donors with food banks and shelters using Gemini multimodal classification and geolocation routing.
- **Tech Stack:** `Angular 20`, `TypeScript`, `Google GenAI SDK`, `TailwindCSS`.

---

## 🛠️ Technical Skills & Ecosystem

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Agentic AI & Distributed Systems** | Model Context Protocol (MCP), Multi-Agent DAG Orchestration, Actor-Model Concurrency, Finite State Machines (FSM), Google ADK, Vertex AI Agent Engine, Gemini 3.7 Flash Hybrid Reasoning, Amazon Bedrock AgentCore, Tool Calling, Idempotent Execution |
| **Formal Verification & Reliability** | Deterministic Boundary Verifiers, AST Mutation Analysis, Invariant Assertions, OpenTelemetry, Grafana Stack (Loki, Tempo, Mimir, LogQL), `pytest` (Hermetic Suites), Opik LLM Tracing |
| **Inference Engineering & Post-Training** | KV-Cache Paging & Optimization, Continuous Batching, Chunked Prefill, Speculative Decoding, Time-to-First-Token (TTFT) Latency Tuning, Test-Time Compute Scaling, Model Distillation, DPO/RLHF Alignment Curation |
| **Cloud & Deployment** | Google Cloud Platform (Cloud Run, Vertex AI, Cloud Build, Secret Manager, IAM, ADC, GKE), AWS Bedrock, Docker |
| **Backend & APIs** | Python (`FastAPI`, `AsyncIO`, `Pydantic`, `Uvicorn`), Node.js, Express, REST APIs, Server-Sent Events (SSE) |
| **Frontend & UI** | TypeScript, React, Next.js 14, Angular 20, Tailwind CSS, Vite |
| **Databases & State** | Google Cloud Firestore, SQLite Checkpointing, Vector Stores |

---

## 📬 Connect & Collaborate

I am open to **AI Systems / Inference Infrastructure roles**, **distributed multi-agent systems consulting**, and **high-impact engineering collaborations**.

- 🚀 **Gaussian Labs:** [gaussianlabs.dev](https://www.gaussianlabs.dev)
- 📧 **Email:** [bright@gaussianlabs.dev](mailto:bright@gaussianlabs.dev) · [brightonwe30@gmail.com](mailto:brightonwe30@gmail.com)
- 🐦 **Twitter / X:** [@bladeofshanghai](https://x.com/bladeofshanghai)
- 🌐 **Google Developer:** [g.dev/brightonwe](https://g.dev/brightonwe)
- 🎓 **Google Skills Profile:** [skills.google/public_profiles/d2470d05...](https://www.skills.google/public_profiles/d2470d05-5fd4-4d76-8998-8ca626a42eba)
- 💻 **Devpost:** [devpost.com/brightonwe30](https://devpost.com/brightonwe30)
- 🏅 **Credly:** [credly.com/users/bright-onwe](https://www.credly.com/users/bright-onwe)
