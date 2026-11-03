<div align="center">

# Derrick Mutugi
### **Systems & Full-Stack Software Engineer**
*Nairobi, Kenya | Available for Global Remote & High-Impact Engineering Roles*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/derrick-mutugi-54118027a/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mutugimaina1@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Mutugi--dev-181717?style=flat&logo=github&logoColor=white)](https://github.com/Mutugi-dev)

<p align="center">
  <b>Building resilient event-driven backends, fintech rails, and low-latency web systems.</b><br/>
  Passionate about clean systems design, decoupled architectures, and production-grade engineering standards.
</p>

</div>

---

### 🏛️ Executive Summary

I am a Software Engineer focused on architecting and shipping **scalable event-driven architectures**, **mission-critical financial integrations**, and **real-time web applications**. My engineering approach emphasizes:

- **Resilient Distributed Flows:** Decoupling producers and consumers using asynchronous message queues (RabbitMQ, event streams) to withstand traffic spikes and guarantee delivery under load.
- **Fintech & Payment Reliability:** Architecting fail-safe webhook ingestion, idempotency controls, and automated OAuth token rotation across high-throughput payment rails (e.g., Safaricom Daraja / M-Pesa).
- **End-to-End Type Safety & Observability:** Enforcing strict TypeScript/Python contracts, automated lint/commit gating (Husky, lint-staged), and real-time operational telemetry.

---

### 🏆 Key Recognitions & Hackathons

- 🥇 **1st Place Winner** — **SquareSense AI** Hackathon: Architected full-stack enterprise analytics platform with Next.js, Radix UI, and TanStack Table.
- 🥈 **2nd Place Winner** — **xStocks / STRC** Hackathon: Built **Stretch by Spreads**, a structured savings & leveraged yield protocol deployed live on **Ink L2 Mainnet** (Chain ID `57073`).

---

### 🚀 Flagship Engineering Projects

#### 1. [Real-Time Fraud Detection Engine](https://github.com/Mutugi-dev/fraud-detection-system)
> **Domain:** Distributed Stream Processing • Anomaly Detection • Event-Driven Microservices

* **The Problem:** Traditional batch fraud analysis introduces latency windows that expose payment processors to consecutive unauthorized transactions before detection triggers.
* **The Solution:** Engineered a decoupled, event-driven streaming pipeline capable of scoring transactions at sub-second latency.
* **Architecture & Highlights:**
  - Decoupled ingestion layer producing synthetic high-velocity transaction streams.
  - **RabbitMQ message broker** buffering spikes to eliminate backpressure on inference workers.
  - Hybrid scoring engine pairing **Scikit-Learn Isolation Forest (ML)** with custom heuristic rule matrices.
  - **PostgreSQL** structured audit store with real-time operational telemetry powered by **Streamlit**.
* **Stack:** `Python` • `RabbitMQ` • `Scikit-Learn` • `PostgreSQL` • `Streamlit` • `Docker`

---

#### 2. [xStream Markets & Stretch Protocol](https://github.com/Mutugi-dev/xStream_crypto)
> **Domain:** DeFi Infrastructure • Tokenized Real-World Assets (RWA) • Structured Yield

* **The Problem:** Tokenized equities lock yield and capital appreciation into a single instrument, forcing yield investors to absorb volatility risk and active traders to purchase unwanted dividend rights.
* **The Solution:** Deployed smart contract infrastructure that splits tokenized equities into independent dividend (`dx`) and principal (`px`) tokens.
* **Architecture & Highlights:**
  - **Live on Ink L2 Mainnet** (Chain ID `57073`). Awarded **2nd Place** in STRC competition ([stretch-leveraged-yield](https://github.com/Mutugi-dev/xstocks-strc_2nd)).
  - Non-custodial dual-token minting and burn-to-redeem vault contracts.
  - Monorepo containing core smart contracts, automated deployment scripts, and responsive trading interface.
* **Stack:** `Solidity / EVM` • `TypeScript` • `Next.js` • `Foundry / Hardhat` • `Monorepo Workspaces`

---

#### 3. [M-Pesa STK Real-Time Settlement Engine](https://github.com/Mutugi-dev/mpesa-stk-push-system)
> **Domain:** Fintech Rails • Asynchronous Webhooks • Real-Time Duplex Communication

* **The Problem:** Mobile payment gateways frequently drop transactions or degrade UX due to client polling bottlenecks, stale OAuth tokens, and unhandled network timeouts.
* **The Solution:** A production-hardened settlement microservice handling Daraja STK Push callbacks with zero-polling, instant UI state updates.
* **Architecture & Highlights:**
  - Automated preemptive OAuth 2.0 token rotation with memory caching to eliminate token expiry latencies.
  - Idempotent webhook receiver with strict payload validation and phone number sanitization.
  - Real-time client push via **Socket.IO WebSockets**, replacing polling with sub-100ms UI state transitions.
* **Stack:** `Node.js` • `Express` • `Socket.IO` • `React 19` • `MongoDB` • `Tailwind CSS`

---

#### 4. [SquareSense AI Enterprise Dashboard](https://github.com/Mutugi-dev/squaresense-ai_1st-place)
> **Domain:** Enterprise Frontend Architecture • 1st Place Hackathon Winner

* **Architecture & Highlights:**
  - High-performance dashboard built with **Next.js App Router** and accessible headless **Radix UI** primitives.
  - Virtualized, high-throughput data tables driven by **TanStack Table v8**.
  - Strict CI/CD quality engineering enforcing Husky pre-commit hooks, ESLint, and lint-staged checks.
* **Stack:** `Next.js` • `TypeScript` • `Radix UI` • `TanStack Table` • `Tailwind CSS`

---

### 🛠️ Core Competencies & Technical Capabilities

```
┌─────────────────────────┬────────────────────────────────────────────────────────┐
│ Area                    │ Technologies & Concepts                                │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Distributed & Real-Time │ RabbitMQ, WebSockets (Socket.IO), Event-Driven Systems │
│ Backend & APIs          │ Node.js, Express, Python, REST API Design, Webhooks    │
│ Frontend Architecture   │ React 19, Next.js, TypeScript, TanStack Table, Tailwind│
│ Data & Persistence      │ PostgreSQL, MongoDB, Schema Design, Anomaly Modeling   │
│ Security & Integrations │ OAuth 2.0, Daraja API / Fintech Rails, Idempotency     │
│ DevOps & Quality Gates  │ Docker, Git, Husky, Lint-Staged, CI/CD Workflows       │
└─────────────────────────┴────────────────────────────────────────────────────────┘
```

<details>
<summary><b>🔍 Detailed Breakdown of Technologies</b></summary>

<br/>

* **Languages:** TypeScript, JavaScript (ESNext), Python 3.x, Solidity, PHP, SQL
* **Backend Frameworks:** Node.js, Express.js, FastAPI / Flask, Laravel
* **Frontend Engineering:** React 19, Next.js (App Router), Radix UI, TanStack Query & Table, Tailwind CSS
* **Messaging & Real-Time:** RabbitMQ (AMQP), Socket.IO, WebSockets, Event-Driven Ingestion
* **Databases & Stores:** PostgreSQL, MongoDB, Prisma / Mongoose ORM
* **Tooling & Engineering Standards:** Git, Docker, Linux/Bash, Postman, ESLint, Prettier, Husky, Vite

</details>

---

### 📈 Engineering Philosophy

> *"Make it work, make it right, make it fast — and ensure it is observable, idempotent, and resilient to failure."*

1. **Idempotency by Default:** In financial and distributed workflows, any network call can fail or be retried. State transitions must remain deterministic.
2. **Decouple Bottlenecks:** Message queues turn sudden traffic spikes from outages into steady, orderly processing.
3. **Ergonomic DX & High Testing Standards:** Clear type boundaries, pre-commit enforcement, and clean repository structures lead to maintainable long-term software.

---

### 📬 Connect With Me

Whether you want to discuss distributed architectures, fintech integrations, or potential engineering opportunities:

- 💼 **LinkedIn:** [linkedin.com/in/derrick-mutugi-54118027a](https://www.linkedin.com/in/derrick-mutugi-54118027a/)
- 📧 **Direct Email:** [mutugimaina1@gmail.com](mailto:mutugimaina1@gmail.com)
- 🐙 **GitHub:** [@Mutugi-dev](https://github.com/Mutugi-dev)
