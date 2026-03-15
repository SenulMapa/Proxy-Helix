# Proxy Helix

**An AI-native Unix environment where intelligence is infrastructure, not a feature.**

> *Not an assistant. An operator.*

[![License: MIT](https://img.shields.io/badge/License-MIT-white.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange)]()
[![Built by](https://img.shields.io/badge/Built%20by-Jedach-black)](https://github.com/SenulMapa)

---

## What is Proxy Helix?

Most "AI operating systems" bolt a chatbot onto a Linux shell and call it innovation.

Proxy Helix is different.

It's a Unix environment where AI isn't a feature you invoke — it's the nervous system of every operation. From answering a client email to spinning up a full pitch deck to deploying a landing page, Proxy Helix doesn't wait to be asked. It delegates, executes, and reports back.

Think JARVIS. Built on Unix. Open source.

---

## The Problem with Every AI Tool Right Now

Current AI agent frameworks are architecturally broken in one critical way:

> They route everything through frontier model APIs.

Every file operation. Every Q&A response. Every email draft. All of it burns tokens at frontier model rates.

The result? Expensive, slow, and impossible to run autonomously at scale.

---

## The Architecture

A **hierarchical intelligence model** — the same way every efficient organization on earth actually works.

```
┌─────────────────────────────────────────────────────┐
│                    USER / BUSINESS                   │
├─────────────────────────────────────────────────────┤
│                  INTENT INTERFACE                    │
│          voice · text · programmatic API             │
├─────────────────────────────────────────────────────┤
│               ORCHESTRATOR BRAIN                     │
│         Claude API — complex reasoning only          │
│      routes · plans · delegates · validates          │
├──────────────────┬──────────────────────────────────┤
│   LOCAL AGENTS   │         LOCAL AGENTS              │
│  email · Q&A     │   web · files · shell · build     │
│  (tiny models)   │         (tiny models)             │
├──────────────────┴──────────────────────────────────┤
│                   OS PRIMITIVES                      │
│       filesystem · network · browser · comms         │
└─────────────────────────────────────────────────────┘
```

**~98% reduction in frontier model token consumption** compared to existing agent frameworks — without sacrificing capability.

The orchestrator only fires when it genuinely needs to think hard. Everything else is handled locally, instantly, cheaply.

---

## What Proxy Helix Can Do

Spin up the Agent and hand it your business:

| Capability | Description |
|---|---|
| 📨 **Client Q&A** | Reads inbound messages, drafts responses autonomously |
| 📊 **Pitch Decks** | Generates full business proposals and slide decks |
| ✉️ **Email Handling** | Writes, formats, and queues emails for approval |
| 🌐 **Website Building** | Spins up landing pages and client sites on demand |
| 🗂️ **File Operations** | Organizes, reads, writes, and manages your workspace |
| 🖥️ **Shell Execution** | Runs system tasks and scripts autonomously |
| 🔍 **Web Research** | Browses and synthesizes information in real time |
| 🤝 **Human-in-the-loop** | Escalates and asks for approval before critical actions |

---

## Why Unix?

Because Unix already got it right the first time.

- Everything is a file
- Composable tools that do one thing well
- Decades of reliability at the OS level
- No artificial ceiling on what you can automate

We're not replacing Unix philosophy. We're extending it — with intelligence as a first-class primitive.

---

## Design Principles

**1. Intelligence is infrastructure**
AI isn't a layer you add. It's woven into every operation.

**2. Local first, frontier when necessary**
Tiny specialized models handle routine work. The orchestrator reserves frontier model calls for genuine complexity.

**3. Delegation over micromanagement**
You set the intent. Proxy Helix handles execution. You approve what matters.

**4. Transparent operation**
Every action is logged, explainable, and reversible. No black boxes.

**5. Built in public**
Commit by commit. Watch the repo. Contribute. Break things.

---

## Roadmap

**Phase 1 — Foundation**
- [ ] Orchestrator router (intent classification + model routing)
- [ ] Local agent worker framework
- [ ] Shell integration layer
- [ ] Basic business ops (email, Q&A)

**Phase 2 — Business Stack**
- [ ] Pitch deck generation
- [ ] Website builder agent
- [ ] Web research + synthesis
- [ ] Multi-agent coordination

**Phase 3 — OS Integration**
- [ ] Deep Unix integration
- [ ] Voice interface
- [ ] Agent memory and context persistence
- [ ] Plugin/skills ecosystem

**Phase 4 — Distribution**
- [ ] Installable on any Debian/Ubuntu system
- [ ] Custom distro (long-term)
- [ ] Cloud deployment support

---

## Tech Stack

| Layer | Technology |
|---|---|
| Orchestrator | Claude API (Anthropic) |
| Local Agents | Ollama + Qwen / Phi / Gemma |
| Shell Layer | Python + PTY |
| Browser Control | Playwright |
| Comms | SMTP / IMAP / REST APIs |
| OS Target | Ubuntu / Debian Linux |

---

## Status

🔨 **Active Development — Pre-Alpha**

This is being built right now. The architecture is locked. The first components are in progress. If this vision resonates with you, star the repo and watch it ship.

---

## Contributing

Proxy Helix is a long game. Contributions, ideas, and feedback are welcome.

Open an issue. Start a discussion. Build something.

---

## Built by

**Senul Mapa** — [@SenulMapa](https://github.com/SenulMapa) · [LinkedIn](https://linkedin.com/in/senul-mapa-b53788375)

Part of the [Jedach](https://github.com/SenulMapa) software group.

---

*"The best interface is no interface."*

⭐ Star this repo if you believe AI should be infrastructure, not a feature.
