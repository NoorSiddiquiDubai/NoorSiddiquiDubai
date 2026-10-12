# Noor Siddiqui

**Dubai · B2B trade × AI automation**

I build self-hosted, human-in-the-loop AI systems for B2B trade: lead intake, CRM, compliance screening and deal workflows. They run on my own servers, and a person approves every message that leaves.

### Background
- 13 years in B2B digital strategy and trade compliance (Aramco India, New Delhi)
- Director, Agro National Chemical Fertilizer Trading Co. LLC, Dubai (agri-fertilizer trade)
- Founder, IZN AI — consent-based AI mediation and digital identity

### What I build
- **Trade CRM:** one intake for email, web forms and WhatsApp; lead dedupe; SLA tracking; an approval queue; compliance flags
- **Agent workflows** with human-in-the-loop approvals, on local LLMs (Ollama)
- **Self-hosted infrastructure:** blue-green deploys with review gates, encrypted backups with restore tests, read-only audits
- **Trade documents:** quotations and LOI/ICPO drafts with QR verification

### How I work with AI agents
I don't write most of my code by hand; AI agents do. My job is to define the task, approve the plan and check the evidence. Every agent on my projects works under one rule: no evidence, no "done". The contract and the review routine I use are public: **[ai-agent-working-contract](https://github.com/NoorSiddiquiDubai/ai-agent-working-contract)**.

### Case study (private code, no client data)
**B2B agri-trade CRM** — about 1,000 leads unified from email, web forms and WhatsApp. Replies are drafted by AI and approved by the owner. Releases ship through staging, automated review and a blue-green switch.

### Stack
Node.js · Express · MongoDB · Redis · Python · FastAPI · Ollama · Nginx · systemd · Docker · Playwright

### Open source
- [ai-agent-working-contract](https://github.com/NoorSiddiquiDubai/ai-agent-working-contract) — the contract every AI coding agent on my projects follows, plus the reviewer playbook

Next up, extracted from my own production systems: IMAP-safe ingest · blue-green promote kit · read-only server audit · B2B lead dedupe

### Work with me
Available for freelance projects: AI automation, CRM and agent workflows for trading and B2B companies. Reach me on [LinkedIn](https://www.linkedin.com/in/nooruddinsiddiqui).
