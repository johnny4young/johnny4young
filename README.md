
![Profile views](https://komarev.com/ghpvc/?username=johnny4young&label=Profile%20views&color=0e75b6&style=flat)

<div align="center">

# johnny4young

**Senior Software Engineer** &nbsp;·&nbsp; Backend Systems &nbsp;·&nbsp; Developer Tooling &nbsp;·&nbsp; AI Engineering

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)](https://nodejs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)](https://golang.org)
[![AI Engineer](https://img.shields.io/badge/AI%20Engineering-FF6F00?style=flat&logo=openai&logoColor=white)](#)

</div>

---

## About

Backend engineer specialized in **Node.js**, **TypeScript**, and **Go**, with deep focus on **distributed systems**, **developer tooling**, and **production-grade LLM applications**.

I design APIs and platforms that survive real traffic — clean boundaries, strong observability, and the kind of architecture that lets teams ship fast without breaking things. Lately, much of my work sits where **backend engineering meets AI**: agent workflows, retrieval pipelines, and LLM systems wired into production codebases.

I value pragmatism over hype, fewer abstractions over clever ones, and tools that get out of the developer's way.

---

## What I'm Building

**Open Source**

- 🐹 **[gos](https://github.com/johnny4young/gos)** — Install and switch Go versions in seconds. One Bash script. Zero dependencies. macOS · Linux · Windows. &nbsp; ![Shell](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) [![Stars](https://img.shields.io/github/stars/johnny4young/gos?style=flat-square&label=★)](https://github.com/johnny4young/gos)
- 🎭 **[electron-stagewright](https://github.com/electron-stagewright/electron-stagewright)** — Drive Electron apps the way Playwright drives browsers — an **MCP server built agent-first** for AI coding agents (Claude Code, Cursor, Codex, Cline). Launch apps, query the accessibility tree semantically, assert with retrying `expect_*` primitives, and replay session traces with per-tool token budgets. [Docs](https://electron-stagewright.github.io/electron-stagewright/) &nbsp; ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square) [![Stars](https://img.shields.io/github/stars/electron-stagewright/electron-stagewright?style=flat-square&label=★)](https://github.com/electron-stagewright/electron-stagewright)
- 🖼️ **[vitrine](https://github.com/johnny4young/vitrine)** — Turn code into beautiful images, straight from your macOS menu bar. Native, instant, fully local — no account, no network. [Website](https://johnny4young.github.io/vitrine/) &nbsp; ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) ![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
- 🌐 **[lingua-marketing](https://github.com/johnny4young/lingua-marketing)** — Public marketing site for **Lingua** ([linguacode.dev](https://www.linguacode.dev/)). Built with Astro 6, Tailwind v4, and deployed to Cloudflare Pages. &nbsp; ![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare%20Pages-F38020?style=flat-square&logo=cloudflare&logoColor=white)
- 🍺 **[homebrew-gos](https://github.com/johnny4young/homebrew-gos)** — Homebrew tap for distributing `gos` across macOS and Linux. &nbsp; ![Homebrew](https://img.shields.io/badge/Homebrew-FBB040?style=flat-square&logo=homebrew&logoColor=white)

**Currently Building** *(private)*

- 🤖 **Janusly** — An **AI operator for business workflows**: a DAG runtime where AI is part of the loop, not glued on top. The differentiator is the **failure-recovery loop** — AI patch suggestions with self-rated confidence, sandbox replay before commit, cluster apply across DLQ entries sharing a failure signature, and one-click rollback. Generic workflow execution (durable retries, decision engine, RL adjustments, NL run explanations) is the table-stakes layer underneath. With an Anthropic key, it becomes end-to-end: *prompt → workflow → execution → decision → learning → recovery → rollback → conversational explainability*. Without one, every deterministic path still works. &nbsp; ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-CC785C?style=flat-square&logo=anthropic&logoColor=white)
- 🛒 **Puntovivo** — Full-stack **POS platform (v3)**. TypeScript + tRPC, multi-vertical (retail, restaurants, delivery), offline-capable, with AI assistants (invoice OCR, in-app copilot), thermal-print receipt rules, and a custom design system for operator-grade UI. &nbsp; ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![tRPC](https://img.shields.io/badge/tRPC-2596BE?style=flat-square&logo=trpc&logoColor=white)
- 🧠 **Lingua** — [linguacode.dev](https://www.linguacode.dev/) · **Multi-language desktop code runner** — JavaScript, TypeScript, Python, Go, and Rust in one offline-first, Monaco-powered app. Combines Monaco Editor, a project file tree, inline console output, and language-specific execution backends for both desktop and web builds. The multi-language answer to RunJS: same "open, write, run" ergonomics, but with Go, Rust, and Python as first-class citizens instead of JavaScript-only. The marketing site is open source; the core product is private and in active development. &nbsp; ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
- 📋 **Gancho** — **Smart Clipboard** for the Apple ecosystem: clipboard history + a searchable snippet library for Mac, iPhone & iPad. Private by design — your data stays on your devices. &nbsp; ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) ![Apple](https://img.shields.io/badge/macOS%20·%20iOS%20·%20iPadOS-000000?style=flat-square&logo=apple&logoColor=white)

**Areas of ongoing client / contract work** *(generic)*

- High-throughput **Node.js / NestJS** APIs and queue-driven workers with strong observability.
- **Go** microservices where concurrency, latency, and footprint actually matter.
- Production **LLM systems** — Claude / OpenAI agents with tool use, structured outputs, and grounded retrieval.
- Internal **developer tooling** — CLIs, scripts, and platform glue that compresses friction across engineering teams.

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Backend & APIs**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=google&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![REST](https://img.shields.io/badge/REST%20APIs-005571?style=flat-square)

**AI & LLM Engineering**

![Anthropic](https://img.shields.io/badge/Anthropic%20Claude-CC785C?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square)
![Agents](https://img.shields.io/badge/Agentic%20Systems-7C3AED?style=flat-square)

**Data & Storage**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Infra, DevOps & Observability**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

## Featured Projects

### 🎭 [electron-stagewright](https://github.com/electron-stagewright/electron-stagewright) — Agent-Native Electron Automation

> Drive Electron apps the way Playwright drives browsers — but designed for AI agents, not adapted for them.

An MCP server that lets AI coding agents operate real Electron desktop apps. Agent-first from the primitive level up: errors carry recovery hints and similar-ref alternatives, every response reports its own token cost, composite `wait_for_state` predicates collapse multi-call chains, and retrying `expect_*` tools replace read-compare-retry loops. Ships replayable session traces with per-tool token budgets.

```bash
claude mcp add electron-stagewright --scope user -- \
  npx -y --package @electron-stagewright/core --package playwright electron-stagewright
```

![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![Docs](https://img.shields.io/badge/docs-online-success?style=flat-square)
![Stars](https://img.shields.io/github/stars/electron-stagewright/electron-stagewright?style=flat-square&label=★)

---

### 🐹 [gos](https://github.com/johnny4young/gos) — Go Version Switcher

> Install and switch Go versions in seconds. One script. Zero dependencies.

A single Bash script that replaces the manual pain of managing Go installations. Auto-detects OS and CPU architecture. Available via `curl | bash`, Homebrew, and more.

```bash
gos latest        # install latest stable Go
gos install 1.21  # pin a specific version
gos current       # show what's running
```

![Shell](https://img.shields.io/badge/shell-bash-green?style=flat-square)
![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Linux%20%7C%20Windows-blue?style=flat-square)
![License](https://img.shields.io/github/license/johnny4young/gos?style=flat-square)
![Stars](https://img.shields.io/github/stars/johnny4young/gos?style=flat-square&label=★)

---

### 🖼️ [vitrine](https://github.com/johnny4young/vitrine) — Code → Beautiful Images

> Turn code into beautiful images, straight from your macOS menu bar.

A native macOS menu-bar app that turns snippets into share-ready images. Native, instant, and fully local — no account, no network, nothing leaves your machine. [Visit the website →](https://johnny4young.github.io/vitrine/)

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Website](https://img.shields.io/badge/website-live-success?style=flat-square)
![Stars](https://img.shields.io/github/stars/johnny4young/vitrine?style=flat-square&label=★)

---

## How I Build

- **Boring tech, sharp execution.** Pick proven tools. Spend the novelty budget where it actually matters.
- **Observability is not optional.** If you can't see it in production, you don't own it.
- **Small interfaces, composable parts.** Most complexity comes from premature abstractions, not missing ones.
- **Type the boundaries.** TypeScript and Go aren't religions — they're contracts that catch bugs before users do.
- **AI is a system, not a prompt.** Real LLM apps live or die by retrieval, evals, guardrails, and observability — not the model name.
- **Ship, then sharpen.** A merged PR teaches more than a perfect plan.

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=johnny4young&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=johnny4young&layout=compact&theme=dark&hide_border=true&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com?user=johnny4young&theme=dark&hide_border=true)

</div>

---

<div align="center">
  <sub>Built for engineers who'd rather ship than manage installations.</sub>
</div>
