# Noor Siddiqui

**Dubai, UAE · Founder, IZN AI & Director, Agro National · DevOps & Self-Hosted AI Infrastructure · 16+ Years in B2B Systems**

[Linktree Hub](https://linktr.ee/noorsiddiqui) · [Medium](https://medium.com/@N_Siddiqui555) · [Contra](https://contra.com/noorsiddiqui) · [LinkedIn](https://www.linkedin.com/in/nooruddinsiddiqui) · [GitHub](https://github.com/NoorSiddiquiDubai) · [X](https://x.com/N_Siddiqui555)

I build and run self-hosted, human-in-the-loop AI systems for B2B trade, regulatory compliance and enterprise workflows. They run on infrastructure I operate myself — bare metal and cloud — with CI gates, health checks and an authenticated person approving every action that leaves the gate.

### Background
- **Founder, IZN AI** ([al-izn.com](https://al-izn.com)) — private AI search, verified professional directory & AI-assisted mediation for the UAE and GCC (2025–Present)
- **Director, Agro National Chemical & Fertilizer Trading Co. LLC** ([agronational.ae](https://agronational.ae)), Dubai — GCC & Africa agri-fertilizer trade and B2B CRM automation (2023–Present)
- **Director, Aramco India** ([aramcoindia.com](https://aramcoindia.com)), Dubai — IT, SEO and digital marketing: setting up and promoting companies online (2010–Present)
- **Executive Director, Delhi branch, Roshan Accountax Pvt. Ltd.** ([roshantax.com](https://roshantax.com)) — company formation, taxation, government liaison, NGO / FCRA / CSR and project reports (2010–2020)
- **Author, eTaxDial** ([etaxdial.com](https://etaxdial.com)) — authority blog on taxation, legal and company setup across India, the UAE and international markets (2013–Present)

### DevOps & Reliability — What I Run in Production
- **CI/CD:** GitHub Actions on a self-hosted runner under a dedicated non-root user. Every pull request runs syntax checks, unit fixture suites and a Playwright end-to-end suite against a staging instance before it can merge.
- **Zero-downtime releases:** blue/green deployment behind Nginx, with a live health-check script that detects a dead colour and fails traffic over to the healthy one.
- **Secret hygiene:** repository-wide secret scanning (gitleaks) before any push, `.env`/credential files kept out of Git, and leaked credentials revoked rather than just deleted.
- **Incident response:** recovered a locked-out bare-metal production server through rescue mode — assembled the RAID6 array, traced the root cause from `sshd` logs, applied a minimal fix and brought every service back on a clean reboot.
- **Cloud migration:** moved a SaaS dashboard from shared hosting to AWS EC2 behind Caddy (automatic HTTPS), with an Elastic IP, low-TTL DNS cutover and a temporary fallback path so nothing broke during propagation.
- **Hardening:** key-only SSH, fail2ban, least-privilege service users, systemd-managed services and backups taken before every change.

### What I Build
- **Trade & B2B CRM:** unified intake across email, web forms and WhatsApp; lead deduplication; SLA tracking; approval queues; compliance verification.
- **Multimodal Regulatory Compliance Engines:** deterministic artwork and label validation enforcing US FDA (21 CFR Part 101) and UAE MoIAT (GSO 9:2013) standards.
- **Agent Workflows:** multi-agent intake pipelines with human-in-the-loop approvals, running on self-hosted models (Ollama / vLLM).

### Open Source Projects
- **[multimodal-compliance-auditor](https://github.com/NoorSiddiquiDubai/multimodal-compliance-auditor)** — regulatory packaging & label compliance auditor for US FDA 21 CFR and UAE MoIAT (FastAPI + Vision + Docker, with tests).
- **[sovereign-ai-agent-engine](https://github.com/NoorSiddiquiDubai/sovereign-ai-agent-engine)** — multi-agent intake engine with deterministic human-in-the-loop release gates, SHA-256 audit hashing and local Ollama orchestration.
- **[ai-agent-working-contract](https://github.com/NoorSiddiquiDubai/ai-agent-working-contract)** — the governance contract and review routine I give every AI coding agent ("No evidence, no done").
- **[projects](https://github.com/NoorSiddiquiDubai/projects)** — live websites and products I have built and run, with screenshots.

### Published Technical Articles
- **[Deterministic Multimodal Vision Auditing for FDA & UAE Regulatory Compliance](https://medium.com/@N_Siddiqui555/deterministic-multimodal-vision-auditing-for-fda-uae-regulatory-compliance-why-llm-probabilities-c04719dc3739)** — why probabilistic LLM vision fails in statutory labelling, and how hybrid deterministic rule engines remove recall risk.
- **[Building Sovereign AI Architectures in Dubai](https://medium.com/@N_Siddiqui555/building-sovereign-ai-architectures-in-dubai-why-enterprise-ai-needs-deterministic-governance-d63b8450ec9f)** — moving beyond public API wrappers to self-hosted models, human-in-the-loop gates and verified execution on GCC soil.

### Live Systems
| Platform | Overview |
|---|---|
| [al-izn.com](https://al-izn.com) | IZN AI — private AI search, verified professional directory and mediation platform for the UAE & GCC |
| [agronational.ae](https://agronational.ae) | Agro National — B2B fertilizer and agri-chemical trading across the Middle East and Africa |
| [etaxdial.com](https://etaxdial.com) | eTaxDial — corporate, tax and legal compliance guides for India, the UAE and the US |
| [roshantax.com](https://roshantax.com) | Legal, tax and corporate compliance services |
| [aramcoindia.com](https://aramcoindia.com) | Aramco India — company setup, IT, SEO and digital marketing services |
| [vsjksb.world](https://vsjksb.world) | Community development, vocational training and welfare initiative portal |

### Technical Stack
**Infra & DevOps:** Linux (Ubuntu) · Docker · systemd · Nginx · Caddy · GitHub Actions (self-hosted runners) · AWS EC2 · Hetzner bare metal · mdadm RAID · fail2ban · gitleaks · Playwright

**Backend & AI:** Python · FastAPI · Pydantic v2 · Node.js · Express · MongoDB · Redis · Ollama

### Work With Me
DevOps hardening, CI/CD setup, self-hosted AI deployments and B2B automation — fixed-price packages.
- **Central Directory:** [linktr.ee/noorsiddiqui](https://linktr.ee/noorsiddiqui)
- **Direct WhatsApp:** [+971 50 726 4928](https://wa.me/971507264928)
- **Fixed-Price Packages:** [Contra Services](https://contra.com/noorsiddiqui)
