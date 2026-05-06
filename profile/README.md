# Voidleap Code

> A harness, not a wrapper. An IDE, not a black box. Every agent in one view.

**Status:** Early access. Founding subscribers only. Desktop app for macOS and Windows, signed auto-updates.

This org hosts public bundles, plugins, and marketplaces for **Voidleap Code**, a local-first IDE for agentic coding. The app itself is closed-source for now.

🌐 [voidleap.com](https://voidleap.com) · 💸 [pricing](https://voidleap.com/pricing) · ✉️ [waitlist](https://voidleap.com)

---

## What it is

A coding IDE built around agents instead of bolted onto them. Runs on your machine. Bring your own provider keys, or run a local model and skip providers entirely. Prompts and code go directly to whichever provider you picked. Nothing routes through Voidleap servers. There is no Voidleap inference, no token markup, no telemetry pipeline reading your repo.

If you've been renting a black box, this is the opposite of that.

[![Voidleap Code Screenshot](https://github.com/voidleap/.github/blob/eb1990b8fb81830566033537b5b81bc1882990aa/profile/screenshot_running.png)](https://voidleap.com/)

## Why it exists

Most agent coding tools are free because they create lock-in, collect your data, or bundle inference subscriptions. We didn't want any of that. The good engineers we know spend half their time fighting their tools: invisible context, opaque pricing, frozen prompts, no way to tell why an agent did the wrong thing. So we built the IDE we wanted: visible, configurable, and ours.

## What's in the box

- **Local-first architecture.** All state in `~/.voidleap/`. Optional macOS Seatbelt sandbox. Per-project browser sessions so cookies don't leak between clients.
- **Bring any model.** Nine providers out of the box: Anthropic, OpenAI, Google Gemini, GitHub Copilot, Ollama, LMStudio, OpenRouter, Azure, Bedrock. Switch per thread, per agent, per turn. Local models get full tool-call parity (Harmony, Gemma, Qwen, Hermes formats).
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

Download links go out with your invite when a slot opens.

## Pricing

| Tier | Price | Status |
| --- | --- | --- |
| Early Access | €50/mo or €450/yr (3 months free) | Open to founding subscribers |
| Standard | TBA | When the product leaves early access |
| Enterprise | Custom | [Contact us](https://voidleap.com/contact) |

14-day money-back guarantee. Cancel anytime. You bring the tokens, we don't mark them up.

Full breakdown: [voidleap.com/pricing](https://voidleap.com/pricing).

## Get on the waitlist

We're letting people in a few at a time. Sign up at [voidleap.com](https://voidleap.com) for the standard waitlist, or fill out [this 3-question survey](https://tally.so/r/xXaAvv) to jump the queue.

We only email about your invite. No newsletter, no marketing.

## Links
- 😸 [Product Hunt](https://producthunt.com/products/voidleap)
- 𝕏 [X](https://x.com/voidleapcom)
- 💼 [LinkedIn](https://www.linkedin.com/company/voidleap/)
- 📺 [YouTube](https://www.youtube.com/@voidleap-com)
- 👥 [Facebook](https://www.facebook.com/voidleapcom)
- 

## Legal

Voidleap Code is proprietary, closed-source software. This GitHub organization hosts open assets only: public plugin bundles, marketplace samples, and integration code. The desktop app itself is distributed via signed installers to subscribers.

Built by self-funded developers, for developers.
