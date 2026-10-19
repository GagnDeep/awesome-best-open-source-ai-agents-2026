---
title: "best-open-source-ai-agents-2026"
description: "Best open source AI agents in 2026: a verified GitHub awesome list of self-hosted frameworks, coding agents, browser agents, and production-ready tools."
icon: 📋
category: ai
---

# Best Open Source AI Agents 2026

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@main/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Topics](https://img.shields.io/github/stars/GagnDeep/awesome-best-open-source-ai-agents-2026?style=social)

> Best open source AI agents 2026 is a curated GitHub awesome list of public repositories for agent frameworks, coding agents, browser agents, and self-hosted AI stacks. Every entry points to a `github.com` repository, excludes proprietary SaaS-only tools, and includes practical metadata so developers can compare open source options faster.

## Table of Contents
- [TL;DR](#tldr)
- [Why This List](#why-this-list)
- [Open Source Tools](#open-source-tools)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)

## TL;DR
- `google/adk-python`, `VoltAgent/voltagent`, and `TEN-framework/ten-framework` are strong starting points if you want a general-purpose agent framework.
- `langchain-ai/open-swe`, `block/goose`, and `plandex-ai/plandex` are notable open source coding-agent options for engineering teams.
- `bytebot-ai/bytebot`, `nanobrowser/nanobrowser`, and `bytedance/UI-TARS-desktop` stand out for browser automation and computer-use workflows.
- `danny-avila/LibreChat`, `mudler/LocalAI`, `eosphoros-ai/DB-GPT`, and `botpress/botpress` are useful when you need self-hosted UI or agent infrastructure.
- Some narrower subcategories still show gaps; when a cluster had fewer than 5 strong GitHub repos, that limitation is called out instead of padded.

## Why This List
The best open source AI agents 2026 trend is not just about cost. Open repositories let teams inspect prompts, tool wiring, orchestration logic, deployment patterns, and licensing before they commit to a stack. That matters when you need self-hosting, compliance, extensibility, or the ability to fork and adapt an agent for your own workflows.

This list is intentionally GitHub-first. Every tool here has a public `github.com` URL, and the focus stays on repositories that are clearly useful for agent building, agent operations, coding assistance, browser automation, or self-hosted deployment.

## Open Source Tools

### Agent Frameworks & SDKs

#### [Agent Development Kit for Python](https://github.com/google/adk-python)
> **Description:** Google ADK is a code-first Python toolkit for building, evaluating, and deploying sophisticated AI agents. Its README emphasizes modular agent composition, reusable tools, MCP and OpenAPI integrations, human-in-the-loop confirmations, and multi-agent hierarchies that scale from small assistants to larger orchestrated systems. It is model-agnostic even though it is optimized for Gemini, and the project documentation highlights deployment flexibility, built-in evaluation flows, and a development UI for testing and debugging agent behavior. License information is published directly on GitHub. Last-commit dates were reviewed from the March 29, 2026 GitHub snapshot used to assemble this list.

- **GitHub:** [github.com/google/adk-python](https://github.com/google/adk-python)
- **Stars:** 18,653 ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** framework, multi-agent, sdk
- **Best for:** teams that want a structured Python agent framework with evaluation and deployment support

---

#### [Agent Development Kit for Go](https://github.com/google/adk-go)
> **Description:** ADK Go brings the same code-first agent-building approach to Go. The README positions it as an open source toolkit for building, evaluating, and deploying sophisticated AI agents while keeping strong control over orchestration and tooling. It is useful for Go-heavy teams that want typed services, backend-friendly deployment, and an official agent SDK that aligns with the broader ADK ecosystem. GitHub metadata shows an Apache-2.0 license and a growing contributor base, while the repository description makes it clear that this is not a demo project but an actively developed toolkit for production-oriented agent applications.

- **GitHub:** [github.com/google/adk-go](https://github.com/google/adk-go)
- **Stars:** 7,277 ⭐
- **Language:** Go
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** framework, sdk, go
- **Best for:** Go teams building backend-native AI agents

---

#### [TEN Framework](https://github.com/TEN-framework/ten-framework)
> **Description:** TEN Framework is an open source Python framework for real-time multimodal and agentic applications. Its README focuses on orchestration for voice, realtime interaction, and composable pipelines that connect models, tools, and runtime services. The project is relevant when agents need more than simple text completion, because the framework is designed around structured components and runtime flexibility for interactive AI systems. GitHub shows a large star count and sustained community interest, making it one of the more visible open repositories in the real-time agent infrastructure segment. The license is listed as `Other` on GitHub, so adopters should review the repository license text directly before production use.

- **GitHub:** [github.com/TEN-framework/ten-framework](https://github.com/TEN-framework/ten-framework)
- **Stars:** 10,376 ⭐
- **Language:** Python
- **License:** Other
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** framework, realtime, multimodal
- **Best for:** multimodal or realtime agent systems

---

#### [VoltAgent](https://github.com/VoltAgent/voltagent)
> **Description:** VoltAgent presents itself as an AI agent engineering platform built on an open source TypeScript framework. The README highlights memory, RAG, guardrails, tools, MCP support, workflows, and built-in observability rather than treating orchestration as a thin wrapper around API calls. That makes it a good fit for teams that want modern TypeScript ergonomics and a more opinionated platform feel. The repository also benefits from a broader ecosystem of examples and companion repos, which helps when you want to move from experimentation to a repeatable project structure. GitHub lists the project under the MIT license.

- **GitHub:** [github.com/VoltAgent/voltagent](https://github.com/VoltAgent/voltagent)
- **Stars:** 7,117 ⭐
- **Language:** TypeScript
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** framework, typescript, observability
- **Best for:** TypeScript teams that want framework plus platform-style agent tooling

---

#### [agentic](https://github.com/transitive-bullshit/agentic)
> **Description:** `agentic` is a TypeScript project focused on giving developers an API-driven way to build agentic systems. The repository description and README position it around composable agent behavior, integrations, and developer-friendly primitives for building applications that can call tools, reason across steps, and connect external systems. It is especially relevant for developers who want a lighter-weight library rather than a full visual platform. GitHub lists the license as `Other`, so the repo is public and useful for research and experimentation, but production teams should confirm whether the exact terms match their legal requirements before adoption.

- **GitHub:** [github.com/transitive-bullshit/agentic](https://github.com/transitive-bullshit/agentic)
- **Stars:** 18,130 ⭐
- **Language:** TypeScript
- **License:** Other
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** api, framework, typescript
- **Best for:** developers who want an agent library rather than a full platform

---

### Coding Agents & Developer Tools

#### [Open SWE](https://github.com/langchain-ai/open-swe)
> **Description:** Open SWE is an open source asynchronous coding agent built for internal engineering workflows. The README describes an architecture with planning, sandboxed execution, subagent orchestration, human feedback during execution, and automatic pull-request creation. It is less a toy CLI and more a reference implementation for how teams can build internal coding agents that connect to issue trackers, chat systems, and repositories. The project is MIT-licensed on GitHub and is particularly useful if you want to study how modern coding agents separate planning, execution, safety boundaries, and repo automation inside a production-style stack.

- **GitHub:** [github.com/langchain-ai/open-swe](https://github.com/langchain-ai/open-swe)
- **Stars:** 8,805 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** coding-agent, software-engineering, automation
- **Best for:** internal coding-agent experiments and engineering workflow automation

---

#### [Goose](https://github.com/block/goose)
> **Description:** Goose is Block's open source agent for developers, implemented in Rust and published under Apache-2.0. The project is widely referenced as a practical coding assistant that can operate with tools and local context while remaining self-hostable and inspectable. It is appealing for users who want a serious open source alternative in the developer-agent space without handing core workflows to a closed hosted product. GitHub metadata shows strong community attention, and the repository is especially useful as a reference point for agent UX, terminal-centric interactions, and the systems concerns that appear once a coding assistant moves beyond simple chat.

- **GitHub:** [github.com/block/goose](https://github.com/block/goose)
- **Stars:** 33,737 ⭐
- **Language:** Rust
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** coding-agent, cli, rust
- **Best for:** developers who want a serious open source coding assistant

---

#### [Qwen Code](https://github.com/QwenLM/qwen-code)
> **Description:** Qwen Code is a TypeScript coding-agent project from QwenLM. The repository is popular because it combines a developer-focused interface with agentic code assistance, automation hooks, and open implementation details on GitHub. It is relevant for users evaluating open coding agents in 2026 because it sits between framework and end-user tool: developers can use it directly, but they can also inspect how the agent handles prompts, tools, and coding tasks. GitHub lists the code under Apache-2.0, which is friendlier for many teams than source-available or custom-license alternatives in the same segment.

- **GitHub:** [github.com/QwenLM/qwen-code](https://github.com/QwenLM/qwen-code)
- **Stars:** 21,266 ⭐
- **Language:** TypeScript
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** coding-agent, typescript, cli
- **Best for:** teams comparing open coding-agent UX and architecture

---

#### [Plandex](https://github.com/plandex-ai/plandex)
> **Description:** Plandex is an open source AI coding engine written in Go. Its README centers on long-running coding tasks, larger-context planning, and workflows where the agent can keep track of files and goals over time instead of responding to isolated prompts. That makes it useful for developers who want more structured project-level assistance than a single chat turn can provide. GitHub lists the repository under MIT, and the project has enough community attention to serve as a meaningful option rather than an experimental side project. It is a strong candidate when you want open source code generation with a bias toward multi-step engineering work.

- **GitHub:** [github.com/plandex-ai/plandex](https://github.com/plandex-ai/plandex)
- **Stars:** 15,166 ⭐
- **Language:** Go
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** coding-agent, planning, go
- **Best for:** long-running code tasks and project-aware coding assistance

---

#### [Gemini CLI](https://github.com/google-gemini/gemini-cli)
> **Description:** Gemini CLI is a TypeScript command-line agent interface from Google Gemini. The repository is open source and useful for understanding how a major model provider exposes agentic command-line flows, tool usage, and developer workflows through a public GitHub repo instead of a hosted-only product. The README positions it as a practical interface for local use, automation, and developer productivity. GitHub lists the project under Apache-2.0. Even if you do not adopt it directly, it is a strong benchmark repo for comparing developer-agent ergonomics, setup patterns, and the balance between CLI simplicity and more advanced agent capabilities.

- **GitHub:** [github.com/google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)
- **Stars:** 99,460 ⭐
- **Language:** TypeScript
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** cli, coding-agent, developer-tools
- **Best for:** developers who prefer command-line agent workflows

---

### Browser & Computer-Use Agents

#### [Bytebot](https://github.com/bytebot-ai/bytebot)
> **Description:** Bytebot is a self-hosted AI desktop agent with strong browser and computer-use positioning. The repository README and GitHub description make it clear that the project focuses on controlling a user interface rather than only generating text, which is important if your automation target lives inside a browser or desktop workflow. It is Apache-2.0 licensed and uses TypeScript, which lowers the barrier for web teams that want to inspect or extend it. Bytebot is one of the clearer GitHub-native options for people searching for an open source alternative to proprietary computer-use agents.

- **GitHub:** [github.com/bytebot-ai/bytebot](https://github.com/bytebot-ai/bytebot)
- **Stars:** 10,691 ⭐
- **Language:** TypeScript
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** browser-agent, computer-use, self-hosted
- **Best for:** self-hosted computer-use and browser automation

---

#### [NanoBrowser](https://github.com/nanobrowser/nanobrowser)
> **Description:** NanoBrowser is an Apache-2.0 browser-agent project aimed at automating browser tasks through an agentic interface. The repository is appealing because it sits squarely in the practical automation layer: browsing, clicking, navigating, and operating web apps. It is not just a UI wrapper around chat; the repo is oriented toward browser behavior as a first-class capability. GitHub metadata shows strong momentum, and the project is one of the more visible open repositories for teams that want to self-host or customize browser automation logic while keeping the full implementation on GitHub and under a permissive license.

- **GitHub:** [github.com/nanobrowser/nanobrowser](https://github.com/nanobrowser/nanobrowser)
- **Stars:** 12,572 ⭐
- **Language:** TypeScript
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** browser-agent, automation, typescript
- **Best for:** browser task automation with open source control

---

#### [Steel Browser](https://github.com/steel-dev/steel-browser)
> **Description:** Steel Browser is an open source browser-focused infrastructure project for AI agents. The README and GitHub description emphasize making browser environments more reliable and usable for agents that need controlled execution, reproducibility, and tooling around web interaction. It is Apache-2.0 licensed, TypeScript-based, and useful both as a direct dependency and as a reference for the browser-runtime side of agent systems. Teams evaluating browser agents often need more than a wrapper around Playwright; Steel Browser is notable because it treats the browser itself as part of the agent stack.

- **GitHub:** [github.com/steel-dev/steel-browser](https://github.com/steel-dev/steel-browser)
- **Stars:** 6,752 ⭐
- **Language:** TypeScript
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** browser-agent, infra, runtime
- **Best for:** teams building reliable browser infrastructure for agents

---

#### [Browser Agent](https://github.com/magnitudedev/browser-agent)
> **Description:** Browser Agent is an Apache-2.0 TypeScript repository focused on autonomous browser usage. The project is relevant for developers who want a direct, inspectable implementation of agent-driven browsing without relying on a proprietary orchestration layer. Its GitHub presence, agent-specific framing, and browser focus make it a practical addition for this list, especially for readers comparing open browser operators, research prototypes, and production-ready automation tooling. It fits well when the core requirement is web navigation and action execution rather than a general-purpose multi-agent framework.

- **GitHub:** [github.com/magnitudedev/browser-agent](https://github.com/magnitudedev/browser-agent)
- **Stars:** 4,007 ⭐
- **Language:** TypeScript
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** browser-agent, web-automation, operator
- **Best for:** focused browser automation agents

---

#### [UI-TARS Desktop](https://github.com/bytedance/UI-TARS-desktop)
> **Description:** UI-TARS Desktop is a multimodal AI agent stack from ByteDance that combines GUI agents, browser operators, and local computer control. The README highlights natural-language control, screenshot-based perception, keyboard and mouse actions, cross-platform support, and privacy-friendly local processing. This makes it more ambitious than a simple browser macro tool; it is designed for computer-use workflows where visual context matters. GitHub lists an Apache-2.0 license, and the project is one of the strongest public repos for teams exploring open multimodal agents that bridge vision models with actual desktop and browser actions.

- **GitHub:** [github.com/bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)
- **Stars:** 29,160 ⭐
- **Language:** TypeScript
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** gui-agent, multimodal, browser-agent
- **Best for:** multimodal desktop and browser automation

---

### Self-Hosted Platforms & Assistants

#### [LibreChat](https://github.com/danny-avila/LibreChat)
> **Description:** LibreChat is a widely used self-hosted chat and agent interface. Its README presents it as an extensible platform for running LLM-powered assistants with support for multiple providers, plugins, and developer control over deployment. The project matters in an awesome list like this because many teams do not need a low-level framework first; they need a deployable open source interface that can host assistants and agent-like workflows today. GitHub lists the repository under MIT, and the strong star count reflects that it has moved well beyond hobby status into a serious self-hosted option.

- **GitHub:** [github.com/danny-avila/LibreChat](https://github.com/danny-avila/LibreChat)
- **Stars:** 35,046 ⭐
- **Language:** TypeScript
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** self-hosted, assistant-ui, platform
- **Best for:** teams that want a polished self-hosted assistant frontend

---

#### [LocalAI](https://github.com/mudler/LocalAI)
> **Description:** LocalAI is a self-hosted inference and application layer that lets teams run AI workloads locally and connect open models to practical agent use cases. The project is not limited to agents, but it is highly relevant for open source agent stacks because it removes dependence on external inference APIs and gives builders a local serving layer. The README emphasizes local deployment, compatibility, and open infrastructure. GitHub lists the project under MIT and shows strong adoption. If your priority is building private or offline-friendly agents, LocalAI is one of the most important infrastructure repos in the ecosystem.

- **GitHub:** [github.com/mudler/LocalAI](https://github.com/mudler/LocalAI)
- **Stars:** 44,564 ⭐
- **Language:** Go
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** self-hosted, inference, local-models
- **Best for:** private or offline-friendly agent stacks

---

#### [DB-GPT](https://github.com/eosphoros-ai/DB-GPT)
> **Description:** DB-GPT is an MIT-licensed project that combines database-oriented AI workflows with agentic capabilities. The repository is useful when you need assistants or agents that can reason over enterprise data, connect to data systems, and provide more than generic chat. Its GitHub presence, strong star count, and practical orientation make it one of the better-known open source options in the data-agent segment. It belongs on this list because many production agent use cases are actually data access and analysis problems, and DB-GPT is designed with that reality in mind rather than treating databases as an afterthought.

- **GitHub:** [github.com/eosphoros-ai/DB-GPT](https://github.com/eosphoros-ai/DB-GPT)
- **Stars:** 18,391 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** data-agent, self-hosted, analytics
- **Best for:** database-connected assistants and enterprise data workflows

---

#### [Botpress](https://github.com/botpress/botpress)
> **Description:** Botpress is an open source conversational AI and agent platform written in TypeScript and licensed under MIT on GitHub. While it historically focused on chatbots, its open tooling and workflow orientation make it relevant for builders who want structured conversation flows, integrations, and deployable assistant experiences under their own control. It is especially attractive for teams that value a more application-centric path to agents instead of starting with a low-level SDK. The GitHub repo is mature, widely known, and practical for production scenarios where UX and workflow management matter as much as raw prompting.

- **GitHub:** [github.com/botpress/botpress](https://github.com/botpress/botpress)
- **Stars:** 14,621 ⭐
- **Language:** TypeScript
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** platform, chatbot, workflow
- **Best for:** conversational AI products with workflow-heavy UX

---

#### [Khoj](https://github.com/khoj-ai/khoj)
> **Description:** Khoj is an AGPL-3.0 self-hosted personal AI assistant with search, retrieval, and agent-style capabilities across your own data. The project stands out because it emphasizes ownership and privacy while still exposing a practical assistant interface. It is well suited to people who want a personal or team knowledge agent that can be deployed on their own infrastructure without giving up access to the code. On GitHub, Khoj has strong adoption and a clear focus on retrieval-heavy use cases, making it a good option when you want a self-hosted assistant that behaves more like an active workspace companion.

- **GitHub:** [github.com/khoj-ai/khoj](https://github.com/khoj-ai/khoj)
- **Stars:** 33,677 ⭐
- **Language:** Python
- **License:** AGPL-3.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** self-hosted, knowledge-agent, search
- **Best for:** personal or team knowledge assistants over private data

---

### Specialized & Domain-Specific Agents

#### [R2R](https://github.com/SciPhi-AI/R2R)
> **Description:** R2R is an MIT-licensed Python project for retrieval-centered AI systems that increasingly overlap with agent behavior. The repository is useful when your agent stack depends on high-quality retrieval, document grounding, and structured pipelines around enterprise knowledge. It is not marketed as a generic agent framework first, which is exactly why it belongs in this category: many real agents are only as good as their retrieval backbone. GitHub shows a healthy star count and a clear open source footprint, making R2R a credible option for teams building retrieval-heavy assistants or domain agents that need strong context handling.

- **GitHub:** [github.com/SciPhi-AI/R2R](https://github.com/SciPhi-AI/R2R)
- **Stars:** 7,747 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** retrieval, rag, data-agent
- **Best for:** retrieval-heavy agents and grounded assistants

---

#### [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot)
> **Description:** FinRobot is a finance-oriented open source agent project maintained by the AI4Finance Foundation. The repository focuses on domain-specific financial workflows rather than generic assistant demos, which makes it more useful for practitioners who need a concrete vertical example of agent design. GitHub lists an Apache-2.0 license and shows that the repo is active enough to matter in the finance-agent niche. If you are comparing open source AI agents by industry applicability, FinRobot is one of the clearer examples of a verticalized agent repo that goes beyond simple prompt templates.

- **GitHub:** [github.com/AI4Finance-Foundation/FinRobot](https://github.com/AI4Finance-Foundation/FinRobot)
- **Stars:** 6,508 ⭐
- **Language:** Jupyter Notebook
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** finance, vertical-agent, research
- **Best for:** finance-specific AI agent experimentation

---

#### [Agent-E](https://github.com/EmergenceAI/Agent-E)
> **Description:** Agent-E is an MIT-licensed Python repository focused on autonomous web and task execution. The project is interesting because it aims at full task completion rather than only response generation, and the GitHub repo gives developers a public implementation to inspect. That makes it useful for readers who want an agent that sits somewhere between workflow automation and browser-based autonomy. It is not the largest repo in this list, but it is clearly on-topic and fills the practical niche of task-oriented web agents with public source code and an inspectable architecture.

- **GitHub:** [github.com/EmergenceAI/Agent-E](https://github.com/EmergenceAI/Agent-E)
- **Stars:** 1,230 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** task-agent, web-agent, python
- **Best for:** task-completion agents that act across web workflows

---

#### [NVIDIA NeMo Agent Toolkit](https://github.com/NVIDIA/NeMo-Agent-Toolkit)
> **Description:** NVIDIA's NeMo Agent Toolkit is an Apache-2.0 Python project for building agent systems with stronger enterprise and infrastructure alignment. The repo is valuable because it reflects how a large infrastructure vendor thinks about agent composition, tools, orchestration, and deployment patterns. For builders evaluating open source AI agents in 2026, it is useful both as a tool and as a design reference. GitHub shows a moderate but meaningful star count, and the project is especially relevant for teams already working in the NVIDIA ecosystem or those who want to compare framework design choices across major open source agent stacks.

- **GitHub:** [github.com/NVIDIA/NeMo-Agent-Toolkit](https://github.com/NVIDIA/NeMo-Agent-Toolkit)
- **Stars:** 2,108 ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** enterprise, framework, toolkit
- **Best for:** enterprise-oriented agent development and infrastructure evaluation

---

#### [LocalAGI](https://github.com/mudler/LocalAGI)
> **Description:** LocalAGI is an MIT-licensed Go project aimed at running agent-like systems on local infrastructure. It complements repositories such as LocalAI by focusing more directly on local agent workflows, self-hosting, and keeping control of the execution environment. It is particularly relevant for privacy-sensitive use cases, homelab experimentation, and edge deployments where a cloud-only agent platform is the wrong fit. The project also fills an important gap in this list: there are fewer mature local-first agent repos than many marketing roundups imply, so LocalAGI remains a notable open source option despite its smaller star count than the biggest general platforms.

- **GitHub:** [github.com/mudler/LocalAGI](https://github.com/mudler/LocalAGI)
- **Stars:** 1,692 ⭐
- **Language:** Go
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** local-first, self-hosted, agent-runtime
- **Best for:** local and privacy-sensitive agent deployments

---

### Additional GitHub-Verified Repositories Worth Reviewing

#### [Agent Payment Node](https://github.com/nuanu-ai/agent-payment-node)
> **Description:** Local macOS CLI and stdio MCP payments with foreground owner approval for signing. Supports x402 purchases and EVM, Solana and TRON transfers; runs on Apple Silicon macOS with Node 24. The software is MIT licensed; network and third-party fees may apply.

- **GitHub:** [github.com/nuanu-ai/agent-payment-node](https://github.com/nuanu-ai/agent-payment-node)
- **Stars:** 0 (verified 2026-10-19)
- **Language:** TypeScript
- **License:** MIT
- **Last Commit:** [2026-10-18T04:14:13Z](https://github.com/nuanu-ai/agent-payment-node/commit/48a62d4e91ea4dcfb450701b5a2b85d2f9f42e7f)
- **Category:** agent infrastructure, payments, MCP
- **Best for:** builders who need local agent payments with foreground owner approval

---

#### [IntentKit](https://github.com/crestalnetwork/intentkit)
> **Description:** IntentKit is a Python project under MIT that focuses on self-hosted agent workflows and intent-driven automation. It is a practical supplemental repo for teams comparing workflow-heavy agents and execution systems.

- **GitHub:** [github.com/crestalnetwork/intentkit](https://github.com/crestalnetwork/intentkit)
- **Stars:** 6,500 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** automation, self-hosted, workflow
- **Best for:** intent-driven automations

---

#### [GPTeam](https://github.com/101dotxyz/GPTeam)
> **Description:** GPTeam is an MIT-licensed Python repo for team-style multi-agent workflows. It is useful as a simpler open source example of role-based agent collaboration.

- **GitHub:** [github.com/101dotxyz/GPTeam](https://github.com/101dotxyz/GPTeam)
- **Stars:** 1,717 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** multi-agent, collaboration, python
- **Best for:** role-based multi-agent experiments

---

#### [SuperAGI](https://github.com/TransformerOptimus/SuperAGI)
> **Description:** SuperAGI is a well-known MIT-licensed Python repository for autonomous and multi-step agent workflows. It remains a useful comparative repo when evaluating orchestration-heavy open source agents.

- **GitHub:** [github.com/TransformerOptimus/SuperAGI](https://github.com/TransformerOptimus/SuperAGI)
- **Stars:** 17,385 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** autonomous-agent, platform, orchestration
- **Best for:** comparing classic autonomous-agent frameworks

---

#### [E2B](https://github.com/e2b-dev/E2B)
> **Description:** E2B provides sandbox infrastructure for AI agents and agent tooling. It is Apache-2.0 licensed and useful when your stack needs isolated execution environments instead of direct host access.

- **GitHub:** [github.com/e2b-dev/E2B](https://github.com/e2b-dev/E2B)
- **Stars:** 11,495 ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** sandbox, infra, execution
- **Best for:** safe execution environments for agents

---

#### [DocsGPT](https://github.com/arc53/DocsGPT)
> **Description:** DocsGPT is an MIT-licensed Python project for documentation assistants and retrieval workflows. It is relevant when your "agent" is mainly a domain expert over private docs and knowledge bases.

- **GitHub:** [github.com/arc53/DocsGPT](https://github.com/arc53/DocsGPT)
- **Stars:** 17,792 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** Reviewed from GitHub activity snapshot on 2026-03-29
- **Category:** docs-agent, rag, assistant
- **Best for:** documentation-centric assistants

---

## Gap Notes
- `Free AI agents` as a search cluster was weak in the supplied research snapshot, with only 3 clear GitHub hits. That is not enough for a trustworthy standalone category.
- `MIT-only AI agents` was also thin in the supplied snapshot, with only 2 direct search hits under that exact query. This list therefore mixes MIT, Apache-2.0, AGPL-3.0, GPL-3.0, MPL-2.0, and `Other` where relevant.
- Browser/computer-use and coding-agent categories are much stronger than narrow database-agent or API-only categories if you apply strict GitHub-only filtering.

## FAQ

### What are the best open source AI agents in 2026 for developers?
For general development, the strongest starting points in this list are [adk-python](https://github.com/google/adk-python), [voltagent](https://github.com/VoltAgent/voltagent), [open-swe](https://github.com/langchain-ai/open-swe), [goose](https://github.com/block/goose), and [plandex](https://github.com/plandex-ai/plandex). They cover different layers of the stack, from frameworks to full coding-agent workflows.

### Which open source AI agents can I self-host?
Many entries here are self-hostable, but the most obvious self-hosted options are [LibreChat](https://github.com/danny-avila/LibreChat), [LocalAI](https://github.com/mudler/LocalAI), [Khoj](https://github.com/khoj-ai/khoj), [DB-GPT](https://github.com/eosphoros-ai/DB-GPT), and [LocalAGI](https://github.com/mudler/LocalAGI). Always review each repository's deployment docs and license before production use.

### Are there open source AI agents on GitHub that work for coding tasks?
Yes. [Open SWE](https://github.com/langchain-ai/open-swe), [Goose](https://github.com/block/goose), [Qwen Code](https://github.com/QwenLM/qwen-code), [Plandex](https://github.com/plandex-ai/plandex), and [Gemini CLI](https://github.com/google-gemini/gemini-cli) are the clearest coding-oriented repos in this list.

### What is the best open source AI agent for browser automation?
For browser-specific use cases, start with [Bytebot](https://github.com/bytebot-ai/bytebot), [NanoBrowser](https://github.com/nanobrowser/nanobrowser), [Steel Browser](https://github.com/steel-dev/steel-browser), [Browser Agent](https://github.com/magnitudedev/browser-agent), and [UI-TARS Desktop](https://github.com/bytedance/UI-TARS-desktop). They vary from runtime infrastructure to full multimodal operators.

### How do I verify an AI agent repo is truly open source?
Check four things on GitHub: public repository visibility, a readable license file, active code rather than only marketing assets, and whether the core runtime is actually in the repo instead of hidden behind a hosted API. This list filtered out non-GitHub tools and proprietary SaaS-only products for that reason.

### Why are some licenses listed as `Other`?
That value comes directly from GitHub metadata in the supplied research snapshot. When GitHub marks a repository license as `Other`, treat it as a review-required repo rather than assuming it is permissive open source in the same way as MIT or Apache-2.0.

## GitHub Search Queries Used
The repository research snapshot for this list was based on GitHub search-style queries like these:

```bash
gh search repos "open source ai agents stars:>20" --limit 50 --json name,owner,url,stargazersCount,primaryLanguage,licenseInfo,updatedAt
gh search repos "self-hosted ai agents stars:>20" --limit 50 --json name,owner,url,stargazersCount,primaryLanguage,licenseInfo,updatedAt
gh search repos "free ai agents github stars:>20" --limit 50 --json name,owner,url,stargazersCount,primaryLanguage,licenseInfo,updatedAt
gh search repos "ai agents MIT license stars:>20" --limit 50 --json name,owner,url,stargazersCount,primaryLanguage,licenseInfo,updatedAt
gh search repos "ai agents API stars:>20" --limit 50 --json name,owner,url,stargazersCount,primaryLanguage,licenseInfo,updatedAt
gh search repos "ai agents database stars:>20" --limit 50 --json name,owner,url,stargazersCount,primaryLanguage,licenseInfo,updatedAt
gh search repos "ai agents alternative stars:>20" --limit 50 --json name,owner,url,stargazersCount,primaryLanguage,licenseInfo,updatedAt
gh search repos "ai agents workflow automation stars:>20" --limit 50 --json name,owner,url,stargazersCount,primaryLanguage,licenseInfo,updatedAt
```

## Contributing
Contributions are welcome, but submissions must meet the repo rules:

- The tool must have a public `github.com` repository URL.
- The repository must be relevant to open source AI agents, agent frameworks, agent infrastructure, coding agents, browser agents, or self-hosted assistant stacks.
- Include current GitHub metadata when you submit: stars, primary language, license, and a public repo URL.
- If a license is unclear or GitHub marks it as `Other`, mention that explicitly.
- Do not submit proprietary SaaS tools without a public GitHub repository.

For full contribution details, see [CONTRIBUTING.md](./CONTRIBUTING.md).

## License
Released under the MIT License. See [LICENSE](./LICENSE).
