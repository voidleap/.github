# Voidleap Code

> A full coding environment for developers building software with AI agents. A harness, not a wrapper. Every agent in one view. Your machine, your keys or local models. Nothing routes through us.

**Status:** Voidleap Code 1.0 is available for macOS and Windows.
[voidleap.com](https://voidleap.com)

This org hosts public bundles, plugins, and marketplaces for **Voidleap Code**, a local-first agentic IDE. The app itself is closed-source for now.

***

## What it is

An agentic IDE built around agents instead of bolted onto them. It runs on your machine. Voidleap Code uses bring your own key. Connect a [supported provider](https://voidleap.com/models-and-providers/) subscription or API key, or use a local model. Inference runs between your machine and the provider or endpoint you choose. 

We don't sell inference. No token markup.

Your code and prompts do not pass through Voidleap servers. No telemetry pipeline reading your repo.

If you've been renting a black box, this is the opposite of that.

[![Voidleap Code Screenshot](https://github.com/voidleap/.github/blob/eb1990b8fb81830566033537b5b81bc1882990aa/profile/screenshot_running.png)](https://voidleap.com/)

## Why it exists

Most agent coding tools are free because they create lock-in, collect your data, or bundle inference subscriptions. We didn't want any of that. The good engineers we know spend half their time fighting their tools: invisible context, opaque pricing, frozen prompts, no way to tell why an agent did the wrong thing. So we built the IDE we wanted: visible, configurable, and ours.

## What's in the box

- **Local-first architecture.** All state in `~/.voidleap/`. Optional macOS Seatbelt sandbox. Per-project browser sessions so cookies don't leak between clients.
- **Use any model.** Nine providers out of the box: Anthropic, OpenAI, Google Gemini, GitHub Copilot, Ollama, LMStudio, OpenRouter, Azure, Bedrock. Switch per thread, per agent, per turn. Local models get full tool-call parity (Harmony, Gemma, Qwen, Hermes formats).
- **Visual context manager.** Click any message, tool call, or file and tell the agent to forget it. Slash commands `/context`, `/trim`, `/prune`, `/compact`. AI-assisted prune in suggest mode so you review before anything is removed. Last three user turns protected from auto-compact.
- **Observability dashboard.** 30+ charts: cost trend, per-model, per-agent, per-thread, per-tool, latency, cache hit rate. Filter, expand, export. Same event stream the agent runs on, so the numbers match reality.
- **Control center.** Live LLM call feed across every running thread. Pause, resume, stop, jump in. Grouped by Running, Needs Input, Idle, Errored.
- **Multi-panel dockview.** Chat, file view, browser, terminal, subagent timelines, artifacts. Drag, split, pin. Layouts persist per project.
- **Multi-agent orchestration.** Build and Plan as primary agents, swap with Shift+Tab. Subagents for deep reasoning (Oracle), parallel code search (Explorer), web research (Librarian), screenshots/PDFs (Looker), history recovery, and more. All authorable with rich frontmatter: per-agent model, effort, tool allowlist, isolation mode.
- **Symbol-level code index.** SearchSymbols, FindReferences, FileOutline, GetSymbol. 15 languages (TypeScript, JavaScript, Python, Go, Rust, Java, C, C++, C#, Ruby, PHP, Kotlin, Swift, Scala). BM25-ranked, drift-safe via signature-hash re-scan, persistent across sessions. No grep fallbacks.
- **Built-in browser.** Real DOM tools (Open, Navigate, Click, Type, Screenshot, Evaluate JS, Get Content, Get Logs). The agent drives, you watch. Solve a 2FA prompt yourself and it picks up where it left off.
- **Worktrees, checkpoints, thread fork.** Each thread gets its own working copy. `/undo` to any prior turn restores files and context. Fork off any point: context inherits, worktree is shared.
- **Granular security.** Four execution modes: Default, Read-only, Careful (approve every action), Yolo. AST-aware command parsing handles paths, redirects, pipes, subshells, heredocs. Sensitive-path defaults block `.ssh`, `.env*`, `.aws`, `.gnupg` out of the box. Read-before-write enforced. Three scopes (Global, Workspace, Project) with merged-result preview.
- **Marketplace and bundle editor.** Build and publish your own. Install community plugins. Static analyzer flags binaries, symlinks, reverse shells, credential exfiltration, prompt injection, and unpinned refs before install. On-demand AI auditor for deep review.
- **Custom everything.** Agents, skills, hooks, MCP servers, slash commands, keybindings, security rules, automations, quick actions. Visual editors and raw markdown both. Three-scope inheritance: author once globally, override per workspace, refine per project.

## Install

Desktop app, macOS and Windows. No bun, no npm, no build step. Signed releases, auto-updates.

[**Download Free**](https://voidleap.com/download)

Free for macOS and Windows. Free account required. No credit card. No trial clock.

## Start with Free

Judge for yourself.

Run Voidleap Code on your own work. Inspect the result, then decide whether it belongs in your workflow.

Additional tier exists when you need even more.

| Tier | Status |
| --- | --- |
| Free | The agentic IDE on your machine, free for as long as you like. Your projects, your keys, your hardware. |
| Pro | Full functionality for the solo developer. Optionally host a server, so agents keep running with the client closed. |
| Team | Built for working together. Shared servers and threads, real-time collaboration, up to 50 managed seats. |
| Enterprise | For organisations that set their own rules. On-premises runtime, central policy, SSO, unlimited seats. |

See [plan comparison](https://voidleap.com/pricing) for more details.

## Links

- 🌐 [Website](https://voidleap.com)
- 😸 [Product Hunt](https://producthunt.com/products/voidleap)
- 𝕏 [X](https://x.com/voidleapcom)
- 💼 [LinkedIn](https://www.linkedin.com/company/voidleap/)
- 📺 [YouTube](https://www.youtube.com/@voidleap-com)
- 👥 [Facebook](https://www.facebook.com/voidleapcom)

## Legal

Voidleap Code is proprietary, closed-source software. This GitHub organization hosts open assets only: public plugin bundles, marketplace samples, and integration code. The desktop app itself is distributed via signed installers.

Built by self-funded developers, for developers.
