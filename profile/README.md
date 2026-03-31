# Digital Crew Technologies

**Crew OS : The open-source operating system for AI agents.**

Linux gave everyone a free OS. Ubuntu made it usable. Mozilla gave the web back to people. The App Store let anyone ship software.

**Crew OS is that moment for AI.**

An open-source operating system where AI agents work alongside humans handling sales, HR, marketing, intelligence, operations, support, and automation. Not a chatbot. Not a copilot. A full crew of digital workers with their own identity, memory, and skills, orchestrated to execute real business goals.

MIT-licensed. Fork it. Run it. Build on it. Own it.

🌐 [digitalcrew.tech](https://www.digitalcrew.tech) 
---

## Why this matters

Every business today rents its intelligence. You pay thousands for SaaS tools that lock you in, harvest your data, and train their models on your workflows. When the vendor raises prices or changes terms, you have no choice your data is already hostage.

AI is making this worse, not better. The current generation of AI agent platforms charges $2K–$15K/month, keeps your data, and gives you nothing back.

**We're building the alternative.**

---

## What is Crew OS?

Crew OS is four things in one:

**🖥️ Applications** 7 specialized AI agents that handle real work. Each has its own identity, memory, skills, and tools. They collaborate, learn, and escalate to humans when judgment matters.

**🔌 Digital Crew API** A single API gateway that connects your agents to **50+ SaaS integrations** and **all major AI models** (via OpenRouter). One key, one endpoint no more stitching together dozens of APIs.

**🌐 Crew Network** The **Internet of Action**. A marketplace of 100+ vetted human partners (designers, lawyers, accountants, developers, translators) that your agents can call on when a task needs human expertise. AI handles the 80%. Humans handle the 20% that matters.

**🔒 Data Privacy** Self-host on your own hardware or private cloud. Your data, your rules, full sovereignty. We also offer managed cloud services (hosting, backups, monitoring) for teams that don't want to manage infrastructure.

---

## Meet the Crew

Crew OS ships with **7 AI agents**:

| Agent | Role | What it does |
|-------|------|-------------|
| **Max** | Sales | Multi-channel outreach, lead enrichment, pipeline management, follow-ups |
| **Sophie** | HR | Voice interviews, resume screening, candidate vetting, hiring workflows |
| **Claire** | Intelligence | Market research, competitive analysis, strategic briefs, deep research |
| **André** | Operations & Finance | Debt recovery, financial reporting, investor decks, process automation |
| **Kate** | Marketing | SEO content, social media scheduling, growth campaigns |
| **Jeanne** | Automation | Landing pages, workflow builders, no-code automation setup |
| **Camille** | Customer Support | Ticket management, knowledge base, customer service, escalation flows |

Every agent is open-source. Fork one, adapt it, make it yours that's exactly how Sophie and André were born from Max. The `digitalcrew-template` repo gives you a blank agent to start from scratch.

---

## Digital Crew API

Stop stitching together dozens of APIs. The Digital Crew API gateway gives your agents (and your apps) a **single endpoint** to access:

- **All major AI models** GPT-4, Claude, Mistral, Llama, Gemini and more via OpenRouter
- **50+ SaaS integrations** CRMs, email, calendars, payment, storage, communication tools
- **MCP connectors** plug into any Model Context Protocol-compatible service

One API key. One SDK. One billing. Built for developers who want to ship agents, not manage vendor sprawl.

---

## How we're shipping

We ship, learn, iterate. No roadmap theater:

```
 ✅  Max           → Sales agent live, battle-tested
 ✅  Agent SDK     → Open-source toolkit to build and fork agents
 🔧  Sophie        → HR agent forked from Max, adapted for hiring
 🔧  Crew Network  → Vetted human partners connected to your agents
 📋  Claire        → Intelligence deep research & competitive analysis
 📋  André         → Ops & Finance debt recovery, reporting, decks
 📋  Jeanne        → Automation landing pages & workflow builders
 📋  Camille       → Support customer service & knowledge base
```

---

## Architecture

Every Crew OS agent shares a **5-layer cognitive architecture**:

1. **Identity** A `SOUL.md` defines who the agent is, how it behaves, and what it won't do
2. **Knowledge** Domain-specific skill graphs loaded per role
3. **Short-term memory** Active task context
4. **Long-term memory** Persistent recall across sessions
5. **Sleep consolidation** Background processing that organizes learnings and prunes noise

Agents connect to external tools via **MCP** and the **Digital Crew API**, and coordinate through the Crew OS orchestrator.

---

## Tech Stack

- **Runtime**: Next.js + TypeScript (MIT-clean, no proprietary dependencies)
- **Database**: PostgreSQL + Drizzle ORM *(migrating from Supabase)*
- **Auth**: Better Auth *(migrating from Supabase Auth)*
- **AI**: OpenRouter via Digital Crew API all models, one gateway
- **Infra**: Docker Compose (runs on a single machine or scales to clusters)
- **Tooling**: MCP + Digital Crew API for 50+ SaaS integrations

---

## Repositories

| Repo | Description |
|------|-------------|
| [`digitalcrew-orchestrator`](https://github.com/Digital-Crew-Technologies/digitalcrew-orchestrator) | Crew OS core routes goals to agents, manages coordination |
| [`max-agent`](https://github.com/Digital-Crew-Technologies/max-agent) | Sales agent the first agent, foundation for forks |
| [`sophie-agent`](https://github.com/Digital-Crew-Technologies/sophie-agent) | HR agent forked from Max, built for hiring |
| [`claire-agent`](https://github.com/Digital-Crew-Technologies/claire-agent) | Intelligence agent research, analysis, strategy |
| [`digitalcrew-template`](https://github.com/Digital-Crew-Technologies/digitalcrew-template) | Starter template fork this to build your own agent |
| [`digitalcrew-roadmap`](https://github.com/Digital-Crew-Technologies/digitalcrew-roadmap) | Public roadmap what we're building and when |

---

## Why open source?

Because the AI agent layer should not be owned by one company. Just like the OS layer wasn't, the browser layer wasn't, and the app distribution layer wasn't.

Every major shift in computing had an open-source inflection point that unlocked an entire ecosystem. Crew OS is that inflection point for AI agents.

We're MIT-licensed because:
- **Devs should build on infrastructure they can inspect, fork, and own**
- **Businesses should control their data and their AI workers**
- **Communities should capture the value they create not hand it to a platform**

Early contributors earn **Contribution Points (CP)** with era multipliers. The earlier you build with us, the more your work is worth.

---

## Contributing

1. **Fork** the repo you want to contribute to
2. **Branch**: `git checkout -b feat/your-feature`
3. **Commit** using [Conventional Commits](https://www.conventionalcommits.org/)
4. **Open a PR** with a clear description

Check `CONTRIBUTING.md` in each repo for project-specific guidelines.

---

## Contact

- **Website**: [digitalcrew.tech](https://www.digitalcrew.tech)
- **Email**: mario@digitalcrew.tech
- **GitHub**: [github.com/Digital-Crew-Technologies](https://github.com/Digital-Crew-Technologies)
- **Discussions**: [Join the conversation](https://github.com/orgs/Digital-Crew-Technologies/discussions)
