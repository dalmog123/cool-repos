<div align="center">

# 🧰 Open-Source Toolkit

### Self-Hosted & Clone-Based Solutions for Professional Services

A curated collection of open-source repositories that can be evaluated, self-hosted, extended, or integrated into an enterprise environment.

**Focus areas:** Knowledge Management · AI & Agents · Automation · Development · Collaboration · Media · CRM · Marketing

</div>

---

## 📋 Repository Overview

| # | Category                                                                | Repos | Focus                                                 |
| - | ----------------------------------------------------------------------- | :---: | ----------------------------------------------------- |
| 1 | [🧠 Knowledge Management](#1--knowledge-management)                     |   7   | Wikis, knowledge bases, research & documentation      |
| 2 | [🗂️ Productivity & Collaboration](#2--productivity--collaboration)     |   4   | Notion/Miro alternatives, whiteboards & presentations |
| 3 | [🛠️ Development Tools](#3--development-tools)                          |   3   | SDKs, vector databases & search                       |
| 4 | [🤖 AI Agents, Automation & MCP](#4--ai-agents-automation--mcp)         |   7   | Agents, workflows, automation & MCP                   |
| 5 | [💻 Coding Agents & AI Dev Skills](#5--coding-agents--ai-dev-skills)    |   3   | Coding agents, skills & development infrastructure    |
| 6 | [🎬 Video, Media & Screen Recording](#6--video-media--screen-recording) |   6   | Video editing, recording & transcription              |
| 7 | [📞 Sales, CRM & Outreach](#7--sales-crm--outreach)                     |   6   | CRM, scheduling & email campaigns                     |
| 8 | [📣 Social Media & Marketing](#8--social-media--marketing)              |   3   | Social scheduling & email marketing                   |

> **39 repositories** are included in the main categories, with an additional **13 repositories** listed under Quick Install.

---

# 1 · 🧠 Knowledge Management

Solutions for building internal knowledge bases, documentation systems, research repositories, and organizational wikis.

| Repository                                           | Description                                                                                                                                                                                                              | Deployment     |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- |
| [Docmost](https://github.com/docmost/docmost)        | Collaborative wiki and document hub. An open-source alternative to Confluence/Notion with real-time editing, permissions, and workspaces. Suitable for internal knowledge bases or client-facing knowledge environments. | Docker         |
| [Wiki.js](https://github.com/requarks/wiki)          | Modern Node.js-based wiki with Markdown/WYSIWYG editing, permissions management, and enterprise authentication/SSO capabilities.                                                                                         | Docker         |
| [TriliumNext](https://github.com/TriliumNext/Notes)  | Hierarchical note-taking and knowledge management application designed for large personal or team knowledge bases, with bidirectional links, Web Clipper, and scripting.                                                 | Clone / Docker |
| [Outline](https://github.com/outline/outline)        | Clean and fast team knowledge base and wiki with powerful search and integrations such as Slack. Particularly useful for procedures, documentation, and onboarding.                                                      | Docker         |
| [SiYuan](https://github.com/siyuan-note/siyuan)      | Block-based personal knowledge management platform with a local-first architecture, Markdown/WYSIWYG editing, and bidirectional linking. Strong privacy focus.                                                           | Docker         |
| [Memos](https://github.com/usememos/memos)           | Lightweight and fast knowledge capture platform for ideas, links, notes, and activity logs, with Markdown, tagging, and search. Useful as a lightweight knowledge layer.                                                 | Docker         |
| [Karakeep](https://github.com/karakeep-app/karakeep) | Self-hosted system for saving links, notes, and images with AI-powered automatic tagging and intelligent search. Particularly useful as a research repository.                                                           | Docker         |

---

# 2 · 🗂️ Productivity & Collaboration

Tools for collaborative work, ideation, documentation, visual collaboration, and content creation.

| Repository                                             | Description                                                                                                                                                                          | Deployment        |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)    | Open-source alternative to Notion with documents, databases, task boards, and AI capabilities. Built with Flutter/Rust with a strong privacy focus.                                  | Clone / Download  |
| [AFFiNE](https://github.com/toeverything/AFFiNE)       | All-in-one workspace combining documents, whiteboards, and databases — effectively a Notion + Miro alternative. Local-first architecture.                                            | Docker            |
| [Excalidraw](https://github.com/excalidraw/excalidraw) | Virtual whiteboard for sketches, diagrams, and architecture visualization with a hand-drawn style. Particularly useful for workshops and solution design in consulting environments. | Docker            |
| [Presenton](https://github.com/presenton/presenton)    | AI-powered presentation generator and alternative to Gamma/Beautiful.ai, supporting PPTX/PDF export, custom templates, BYOK, and built-in MCP support.                               | Docker / Download |

---

# 3 · 🛠️ Development Tools

Core infrastructure and developer tools that can support internal applications, AI systems, and data-driven workflows.

| Repository                                    | Description                                                                                                                                                       | Deployment     |
| --------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| [Flutter](https://github.com/flutter/flutter) | Google's cross-platform SDK for building mobile, web, and desktop applications from a single codebase.                                                            | SDK / Clone    |
| [Qdrant](https://github.com/qdrant/qdrant)    | High-performance vector database used as infrastructure for semantic search, embeddings, and RAG applications.                                                    | Docker / Clone |
| [SearXNG](https://github.com/searxng/searxng) | Privacy-focused, self-hosted metasearch engine aggregating results from multiple search providers. Useful as a search layer for AI agents and research workflows. | Docker         |

---

# 4 · 🤖 AI Agents, Automation & MCP

Platforms and infrastructure for building AI-powered applications, autonomous agents, workflows, and tool integrations.

| Repository                                                     | Description                                                                                                                                                                   | Deployment        |
| -------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [n8n](https://github.com/n8n-io/n8n)                           | Visual workflow automation platform with hundreds of integrations and support for AI workflows and agents. Recommended for self-hosted enterprise deployments.¹               | Docker            |
| [Activepieces](https://github.com/activepieces/activepieces)   | Open-source automation platform and Zapier alternative with built-in support for MCP and AI agents.                                                                           | Docker            |
| [Dify](https://github.com/langgenius/dify)                     | Platform for building LLM applications and AI agents with RAG, workflows, tools, and a visual interface accessible to non-developers.                                         | Docker            |
| [LibreChat](https://github.com/danny-avila/LibreChat)          | ChatGPT-style AI interface supporting multiple models, agents, tools, and MCP. Designed for self-hosted and controlled enterprise environments.                               | Docker            |
| [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)   | All-in-one application for running AI chat and RAG over organizational documents, with support for agents and tools. Available as a desktop application or Docker deployment. | Docker / Download |
| [Firecrawl](https://github.com/mendableai/firecrawl)           | Web scraping and crawling infrastructure that converts websites into LLM-ready Markdown/JSON. Can be self-hosted as an input layer for agents and research systems.¹          | Docker            |
| [MCP Servers](https://github.com/modelcontextprotocol/servers) | Official repository of example MCP servers and implementations from Anthropic and the community. Useful for learning MCP and developing customized internal servers.          | Clone             |

---

# 5 · 💻 Coding Agents & AI Dev Skills

Repositories that extend coding agents or provide infrastructure and skills for AI-assisted software development.

| Repository                                             | Description                                                                                                                                                                                                                           | Deployment |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| [gstack](https://github.com/garrytan/gstack)           | Collection of skills for Claude Code that turns an AI coding agent into a virtual engineering team covering roles such as engineering management, design, code review, QA, and security.                                              | Clone      |
| [ponytail](https://github.com/DietrichGebert/ponytail) | Rule/skill for coding agents that encourages minimal solutions — effectively a "lazy senior engineer" approach designed to reduce unnecessary code, cost, and complexity. Can be loaded from a checkout into agents such as OpenCode. | Clone      |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | Autonomous coding-agent platform capable of writing, running, debugging, and modifying code. Designed to run through Docker for controlled deployments.                                                                               | Docker     |

---

# 6 · 🎬 Video, Media & Screen Recording

Tools for creating training materials, client communications, demonstrations, webinars, and other visual content.

| Repository                                                   | Description                                                                                                                                                | Deployment        |
| ------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [OBS Studio](https://github.com/obsproject/obs-studio)       | Professional and free screen recording and live-streaming software. A de facto industry standard for webinars, demonstrations, and training.               | Download / Clone  |
| [ShareX](https://github.com/ShareX/ShareX)                   | Windows screenshot and screen-recording utility with OCR, annotation, sharing, and hotkey-based automation capabilities.                                   | Download / Clone  |
| [OpenCut](https://github.com/OpenCut-app/OpenCut)            | Open-source video editor positioned as a CapCut alternative for web/desktop, without watermarks or subscriptions.                                          | Docker / Clone    |
| [Cap](https://github.com/CapSoftware/Cap)                    | Open-source Loom alternative for quickly recording, editing, and sharing screen recordings. Available as a desktop application and self-hosted deployment. | Download / Docker |
| [Open Recorder](https://github.com/imbhargav5/open-recorder) | Lightweight macOS screen recorder, screenshot tool, and editor built with Swift and Rust, supporting backgrounds, zoom, and framing.                       | Clone             |
| [whisper.cpp](https://github.com/ggml-org/whisper.cpp)       | Fast C/C++ implementation of Whisper for local speech-to-text transcription, capable of running locally without requiring a GPU.                           | Clone             |

---

# 7 · 📞 Sales, CRM & Outreach

Open-source infrastructure for customer relationship management, sales operations, scheduling, customer communication, and outreach.

| Repository                                       | Description                                                                                                                                                         | Deployment     |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| [Twenty](https://github.com/twentyhq/twenty)     | Modern open-source CRM and Salesforce/HubSpot alternative with a flexible data model, pipelines, and automation.                                                    | Docker         |
| [EspoCRM](https://github.com/espocrm/espocrm)    | Mature full-featured CRM for managing leads, contacts, opportunities, campaigns, and support. Can serve as a foundation for an internal or customized sales system. | Docker / Clone |
| [Cal.com](https://github.com/calcom/cal.com)     | Open-source scheduling infrastructure and Calendly alternative for coordinating meetings, discovery calls, and demos.                                               | Docker         |
| [Chatwoot](https://github.com/chatwoot/chatwoot) | Omnichannel communication platform supporting live chat, email, WhatsApp, Telegram, and other channels. Open-source alternative to Intercom.                        | Docker         |
| [Listmonk](https://github.com/knadh/listmonk)    | High-performance mailing-list and email campaign manager implemented as a single Go binary. Open-source Mailchimp alternative.                                      | Docker / Clone |
| [Mautic](https://github.com/mautic/mautic)       | Mature marketing automation platform supporting email campaigns, lead scoring, landing pages, and nurture sequences.                                                | Docker / Clone |

---

# 8 · 📣 Social Media & Marketing

Tools for managing social channels, publishing content, newsletters, and marketing communications.

| Repository                                        | Description                                                                                                                                                   | Deployment     |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| [Postiz](https://github.com/gitroomhq/postiz-app) | Social media management and scheduling platform with AI capabilities. Buffer alternative supporting numerous platforms, analytics, and an API for automation. | Docker         |
| [Mixpost](https://github.com/inovector/mixpost)   | Self-hosted social media management platform built with Laravel. Supports scheduling, publishing, and analytics without a subscription.                       | Docker / Clone |
| [Keila](https://github.com/pentacent/keila)       | Open-source, self-hosted newsletter and email campaign platform built with Elixir, supporting multiple SMTP providers.                                        | Docker / Clone |

---

# ⚡ Quick Install

The following repositories are **not included in the main tables** because they are primarily consumed through package managers or CLI installation rather than requiring the repository itself to be cloned or self-hosted.

They are still listed here for convenience.

| Repository                                                | Description                                                                                                         | Quick Install                           |
| --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| [LangChain](https://github.com/langchain-ai/langchain)    | Framework for building LLM applications, chains, and AI agents.                                                     | `pip install langchain` / npm           |
| [LangGraph](https://github.com/langchain-ai/langgraph)    | Agent orchestration framework for building stateful, graph-based LLM applications and agents.                       | `pip install langgraph`                 |
| [Agno](https://github.com/agno-agi/agno)                  | Lightweight framework for building multi-model AI agents with memory and tools.                                     | `pip install agno`                      |
| [browser-use](https://github.com/browser-use/browser-use) | Library enabling AI agents to control browsers and perform web-based tasks.                                         | `pip install browser-use`               |
| [Whisper](https://github.com/openai/whisper)              | Speech-to-text transcription model. The main list uses `whisper.cpp` instead because it is clone/build oriented.    | `pip install openai-whisper`            |
| [Slidev](https://github.com/slidevjs/slidev)              | Developer-focused presentation framework based on Markdown and Vue.                                                 | `npm init slidev@latest`                |
| [OpenCode](https://github.com/sst/opencode)               | Open-source terminal-based AI coding agent and Claude Code alternative.                                             | `npm i -g opencode-ai` / brew           |
| [Strix](https://github.com/usestrix/strix)                | Autonomous AI agents for application security testing and penetration testing workflows.                            | `pipx install strix-agent`              |
| [Graphify](https://github.com/Graphify-Labs/graphify)     | Skill for coding agents that builds a knowledge graph from code and documentation to improve project understanding. | `pip install graphifyy`                 |
| [HyperFrames](https://github.com/heygen-com/hyperframes)  | Framework for creating video from HTML, designed for AI-agent workflows.                                            | `npx skills add heygen-com/hyperframes` |
| [Aider](https://github.com/Aider-AI/aider)                | AI pair-programming tool that works with existing codebases, Git, tests, and linters.                               | `pip install aider-chat`                |
| [Crush](https://github.com/charmbracelet/crush)           | Terminal-based AI coding agent from Charm.                                                                          | brew / npm / winget                     |
| [Playwright](https://github.com/microsoft/playwright)     | Browser automation and testing framework useful for both traditional automation and AI agents.                      | npm / pip / .NET / Java                 |

---

# ⭐ Recommended Starting Stack

For an initial deployment, these repositories provide a strong combination of **automation, AI, knowledge management, customer operations, and content creation**.

| Priority | Repository                  | Why                                                                                         |
| :------: | --------------------------- | ------------------------------------------------------------------------------------------- |
|   ⭐⭐⭐⭐⭐  | **n8n**                     | Core automation layer applicable to a wide range of organizational processes.               |
|   ⭐⭐⭐⭐⭐  | **Dify**                    | Enables teams to build AI applications and agents with limited development effort.          |
|   ⭐⭐⭐⭐⭐  | **Docmost / Outline**       | Strong foundation for organizational knowledge, procedures, and client knowledge.           |
|   ⭐⭐⭐⭐⭐  | **Twenty**                  | Flexible foundation for internal or customized CRM and sales workflows.                     |
|   ⭐⭐⭐⭐   | **Qdrant + Firecrawl**      | Infrastructure for RAG, semantic search, web intelligence, and research agents.             |
|   ⭐⭐⭐⭐   | **LibreChat / AnythingLLM** | Enterprise-oriented AI interfaces for interacting with organizational models and knowledge. |
|   ⭐⭐⭐⭐   | **Presenton**               | Automates presentation creation and client-facing deliverables.                             |
|   ⭐⭐⭐⭐   | **Postiz + Cap**            | Supports social content, training materials, and client communications.                     |

---

# 📝 Evaluation Checklist

Before adopting any repository into an enterprise environment, evaluate the following:

### 1. License

Confirm that the license permits:

* Commercial use
* Internal deployment
* Modification
* Redistribution where relevant

Pay particular attention to **AGPL, BSL, and Fair-Code** licensing models.

Examples include repositories such as n8n, Firecrawl, AFFiNE, Cap, and Postiz.

### 2. Security

Review:

* Security policy
* Known CVEs
* Dependency vulnerabilities
* Container security
* Secrets management
* Supply-chain risks
* Authentication implementation

### 3. Data Residency & Deployment

Determine whether the solution can operate:

* On-premises
* In a private cloud
* Within an approved enterprise environment
* Without sending sensitive client data to third-party services

This is particularly important for professional-services organizations handling confidential client information.

### 4. Authentication & Authorization

Evaluate support for:

* SSO
* SAML
* OAuth/OIDC
* RBAC
* SCIM
* Enterprise identity providers

### 5. Extensibility

Assess available:

* APIs
* Webhooks
* Plugins
* SDKs
* MCP support
* Custom integrations
* Database access

### 6. Maintenance & Community

Review:

* Commit activity
* Release frequency
* Number of active contributors
* Issue resolution
* Community size
* Documentation quality
* Project governance

### 7. Operational Complexity

Estimate the actual infrastructure and operational requirements:

* Number of services
* Databases
* Redis/queues
* Storage
* GPU requirements
* Reverse proxy
* Monitoring
* Backup requirements
* Upgrade complexity

---

# 📌 Notes

### ¹ Platform Classification

**n8n** and **Firecrawl** also have package/SDK installation options, but they remain in the main tables because their enterprise use case commonly involves running the platform as a self-hosted service using Docker or a cloned deployment.

The same principle applies to **Excalidraw** and **AnythingLLM**.

### Quick-Install Classification

From the original repository list, the following were moved to Quick Install because they are primarily package/CLI-based:

* `strix` — pipx
* `graphify` — pip
* `hyperframes` — npx/npm

They remain listed for reference rather than being removed.

### Additional Repositories

The following repositories were added to the main catalog because they meet the clone/self-hosting criteria:

* **Memos**
* **EspoCRM**
* **Keila**

The following remained in Quick Install because they are primarily package-first tools:

* **Aider** — pip
* **Crush** — brew/npm
* **Playwright** — npm/pip
* **Cline / Roo Code** — IDE extensions
* **Continue** — archived

### Whisper

`openai/whisper` was replaced in the main list by **whisper.cpp**, since the latter better fits the clone/build-oriented criteria used for the main repository catalog.

---

<div align="center">

## 🚀 Purpose

This repository is intended as a **starting point for evaluating open-source technology that can be adopted, self-hosted, customized, or integrated into professional-services workflows**.

**Explore → Evaluate → Pilot → Secure → Integrate**

</div>
