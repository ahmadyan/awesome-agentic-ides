# Awesome Agentic IDEs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of agentic IDEs, multi-agent development environments, agent terminals, and apps for supervising coding agents.

An agentic IDE is an editor or workspace where software agents, not only people, plan and make changes. This list covers AI-first editors, agentic development environments (ADEs) that run many command-line agents in parallel, terminals built for agent sessions, first-party apps from agent makers, and phone or browser clients for checking in on running agents. Entries are alphabetical within each section. Tools that only run on a Mac are marked macOS.

## Contents

- [Agentic IDEs](#agentic-ides)
- [Multi-agent IDEs and ADEs](#multi-agent-ides-and-ades)
- [Agent orchestration apps](#agent-orchestration-apps)
- [Agent terminals](#agent-terminals)
- [First-party agent apps](#first-party-agent-apps)
- [Mobile and remote control](#mobile-and-remote-control)
- [Standards](#standards)
- [Reading](#reading)
- [Related lists](#related-lists)

## Agentic IDEs

Editors built around agents that read, plan, and change a codebase.

- [Cursor](https://cursor.com) - Anysphere's AI-first editor, with an Agents Window for running agents across repositories, worktrees, remote machines, and the cloud. Proprietary.
- [Devin Desktop](https://devin.ai/desktop) - Cognition's editor for planning, delegating, and reviewing work from local and cloud agents; it was formerly Windsurf, and windsurf.com now redirects here. Proprietary.
- [Google Antigravity](https://antigravity.google) - Google's agentic development platform, with a desktop IDE for macOS, Windows, and Linux plus a CLI and an SDK. Proprietary.
- [JetBrains Air](https://www.jetbrains.com/air/) - JetBrains' workspace for building software with agents, designed to host the agents you already use and any agent that speaks ACP. Proprietary.
- [Kiro](https://kiro.dev) - AWS's spec-driven IDE, which turns prompts into executable specs and runs parallel agents across large codebases. Proprietary.
- [Qoder](https://qoder.com) - Agentic IDE with autonomous development modes and plugins for VS Code and JetBrains. Proprietary.
- [TRAE](https://www.trae.ai) - ByteDance's AI coding IDE, TraeCode, offered alongside a general work assistant. Proprietary.
- [Visual Studio Code](https://code.visualstudio.com/docs/agents/overview) - Microsoft's editor, now with an Agents Window, a choice of agent harnesses, subagents, and remote agent sessions. Open source core (MIT).
- [Zed](https://zed.dev) - Fast Rust editor with a native agent, external agents such as Claude Code and Codex over ACP, and parallel agent threads in linked worktrees. Open source (GPL-3.0 and others).

## Multi-agent IDEs and ADEs

Desktop workspaces that run several command-line agents at once, usually one Git worktree per task, and bring terminals, diffs, and review into one window.

- [Agentastic](https://www.agentastic.dev/multi-agent-ide) - Native multi-agent IDE that runs Claude Code, Codex, Gemini CLI, and dozens of other agent CLIs in isolated worktrees or containers, with an editor, browser, and diff review. macOS. Proprietary.
- [bb](https://github.com/get-bb/bb) - Agentic IDE that can drive and customize itself, with desktop, web, CLI, and HTTP API surfaces for steering agent threads. Open source (MIT).
- [CodeNomad](https://github.com/NeuralNomadsAI/CodeNomad) - Desktop and browser workspace for OpenCode that keeps long conversations and worktrees organized across projects. Open source (MIT).
- [Conductor](https://www.conductor.build) - Mac app that gives each Claude Code, Codex, Cursor, or OpenCode task its own worktree-backed workspace, with setup scripts, checks, and pull requests, plus optional cloud workspaces. macOS. Proprietary.
- [Emdash](https://github.com/generalaction/emdash) - Agentic development environment for running coding agents in parallel, scheduling agent work, and reviewing changes, on macOS, Windows, and Linux. Open source (Apache-2.0).
- [Ghostex](https://github.com/maddada/Ghostex) - Native Rust app that pairs Ghostty terminals with an editor and a browser for each agent CLI. macOS. Open source (MIT).
- [Jean](https://github.com/coollabsio/jean) - Opinionated Tauri workspace from Coolify's team that runs Claude, Codex, Cursor, OpenCode, Pi, and other agents in parallel worktrees on a laptop or your own server. Open source (Apache-2.0).
- [Nimbalyst](https://github.com/nimbalyst/nimbalyst) - Visual workspace, formerly Crystal, that puts Claude Code, Codex, and OpenCode sessions next to editable docs, diagrams, mockups, and a task board. Open source (MIT).
- [OpenChamber](https://github.com/openchamber/openchamber) - Workspace built on OpenCode for starting and reviewing agent work from a desktop app, the web, VS Code, or a phone. Open source (MIT).
- [Orca](https://github.com/stablyai/orca) - Cross-platform ADE that gives any CLI agent its own worktree, with terminals, an editor, a browser, annotated diffs, SSH worktrees, and mobile apps. Open source (MIT).
- [Parallel Code](https://github.com/johannesjo/parallel-code) - Desktop app that dispatches Claude Code, Codex, and Gemini CLI into separate worktrees and lets you merge the diffs you keep. Open source (MIT).
- [Paseo](https://github.com/getpaseo/paseo) - Self-hosted daemon that runs agent CLIs on your machine or server, with desktop, web, CLI, and phone clients and an optional end-to-end encrypted relay. Open source (Apache-2.0).
- [Prowl](https://github.com/onevcat/Prowl) - Native command center that lays out live agent terminals on a canvas and surfaces the ones waiting for you. macOS. Source-available (FSL-1.1-ALv2).
- [Sculptor](https://github.com/imbue-ai/sculptor) - Imbue's desktop app for running coding agents in parallel containers, released as an experimental research preview. Open source (MIT).
- [Supacode](https://github.com/supabitapp/supacode) - Native command center that gives each task its own worktree and real terminal, with sessions that survive quitting the app. macOS. Source-available (FSL-1.1-ALv2).
- [Superset](https://github.com/superset-sh/superset) - Desktop workspace for Claude Code, Codex, and other CLI agents, with a worktree per task, code review, browser previews, a CLI, and an MCP server. macOS, with experimental Linux builds. Source-available (Elastic License 2.0).
- [T3 Code](https://github.com/pingdotgg/t3code) - Control surface for the agents on your machine, with desktop, web, iOS, and Android apps that work with existing Claude and Codex subscriptions. Open source (MIT).
- [Waku](https://github.com/egoist/waku) - Native Rust desktop app for local coding agents that keeps projects, sessions, and transcripts on your machine; runs on macOS and Linux. Open source (GPL-3.0).
- [Xum](https://github.com/coder/xum) - Coder's desktop app for isolated, parallel agentic development, renamed from Mux. Open source (AGPL-3.0).

## Agent orchestration apps

Task-first tools that plan work, assign it to agents, and track it through review and merge.

- [Agent Orchestrator](https://github.com/OrchestratorInc/agent-orchestrator) - Plans, runs, and supervises teams of coding agents from planning to merge, with any agent harness and a worktree per task. Open source (Apache-2.0).
- [Kandev](https://github.com/kdlbs/kandev) - Kanban board and development environment for running tasks in parallel, orchestrating agents, and reviewing their changes. Open source (AGPL-3.0).
- [Traycer](https://github.com/traycerai/traycer) - Orchestration app that runs several agents in parallel on your existing provider subscriptions, with shared memory between them. Open source (MIT).
- [Vibe Kanban](https://github.com/BloopAI/vibe-kanban) - Kanban board that hands each card to Claude Code, Codex, or another agent in its own worktree. The project has announced that it is sunsetting. Open source (Apache-2.0).
- [Zeron](https://github.com/zeronsh/zeron) - Local-first control plane for Claude Code, Codex, Cursor, Devin, Hermes Agent, Pi, and other agents, with optional multi-device sync and a headless mode. Open source (MIT).

## Agent terminals

Terminals, multiplexers, and TUIs for keeping many agent sessions alive and visible.

- [Agent Deck](https://github.com/asheshgoplani/agent-deck) - Go TUI that manages Claude Code, Gemini CLI, and other agent sessions from one screen. Open source (MIT).
- [Agent of Empires](https://github.com/agent-of-empires/agent-of-empires) - Session manager for Linux and macOS that runs agents in persistent sessions across branches, with optional worktree or container isolation and a web view. Open source (MIT).
- [Claude Squad](https://github.com/smtg-ai/claude-squad) - Terminal app that pairs each Claude Code, Codex, OpenCode, or Aider session with a tmux session and a Git worktree. Open source (AGPL-3.0).
- [cmux](https://github.com/manaflow-ai/cmux) - Ghostty-based terminal with vertical tabs that show each workspace's branch and ports, notifications when an agent needs you, and a scriptable browser. macOS. Open source (GPL-3.0-or-later).
- [dmux](https://github.com/standardagents/dmux) - Multiplexer that opens tmux panes for coding agents, each in its own Git worktree, and helps merge the results. Open source (MIT).
- [herdr](https://github.com/herdrdev/herdr) - Terminal runtime that keeps agent sessions running in a background server after you disconnect and restores them after a restart. Open source (Apache-2.0).
- [Warp](https://github.com/warpdotdev/warp) - Terminal-born agentic development environment with a built-in agent that also hosts Claude Code, Codex, and other CLI agents. Open source (AGPL-3.0).

## First-party agent apps

Desktop apps that agent makers ship for their own agents.

- [Amp for macOS and iOS](https://ampcode.com/docs/macos-and-ios) - Amp's native apps for starting threads, following remote runs, and using a Mac as a runner. Proprietary.
- [Claude Code Desktop](https://code.claude.com/docs/en/desktop) - The Code tab of Anthropic's Claude app, with parallel sessions in isolated worktrees, an integrated terminal and editor, visual diff review, and app previews. Proprietary.
- [Codex in the ChatGPT desktop app](https://learn.chatgpt.com/docs/app) - OpenAI's Codex view inside the ChatGPT desktop app, where the standalone Codex app was merged on July 9, 2026. Proprietary.
- [Factory App](https://docs.factory.com/factory-app/overview) - Factory's visual workspace for Droid sessions, with local machine access, project switching, and reviewable sessions. Proprietary.
- [goose Desktop](https://goose-docs.ai/docs/quickstart) - Desktop edition of goose, the extensible agent now hosted by the Agentic AI Foundation, for macOS, Windows, and Linux. Open source (Apache-2.0).
- [OpenCode Desktop](https://opencode.ai/download) - Beta desktop app for the OpenCode agent on macOS, Windows, and Linux. Open source (MIT).

## Mobile and remote control

Phone and browser clients for starting, steering, and approving agents that run on your own machines.

- [Claude Code Remote Control](https://code.claude.com/docs/en/remote-control) - Connects the Claude mobile app to a Claude Code session running on your computer, so you can continue it from your phone. Proprietary.
- [CloudCLI](https://github.com/siteboon/claudecodeui) - Self-hosted desktop and mobile web UI, also known as Claude Code UI, for Claude Code, Cursor CLI, and Codex sessions. Open source (AGPL-3.0).
- [Codex Remote](https://learn.chatgpt.com/docs/remote) - Lets the ChatGPT mobile app start, approve, and review Codex chats on a Mac or Windows PC that runs the ChatGPT desktop app. Proprietary.
- [Happy](https://github.com/slopus/happy) - End-to-end encrypted iOS, Android, and web client that wraps Claude Code and Codex so you can take over a session from your phone. Open source (MIT).
- [Moshi](https://getmoshi.app) - Mobile terminal for iOS and Android built for agent sessions, with Mosh, push notifications, and voice input. Proprietary.
- [omg.dev](https://github.com/BennyKok/omg.dev) - Self-hostable harness for giving Claude Code, Codex, and other agents tasks from a phone and getting notified when they finish. Open source (MIT).
- [VibeTunnel](https://github.com/amantus-ai/vibetunnel) - Mac app that proxies your terminals into any browser so you can check on agents away from your desk. macOS. Open source (MIT).

## Standards

Open formats that let editors and agents work together.

- [Agent Client Protocol](https://agentclientprotocol.com/get-started/introduction) - JSON-RPC protocol, started by Zed, for connecting any editor to any coding agent. Open source (Apache-2.0).
- [AGENTS.md](https://agents.md) - Plain Markdown file format for project instructions that many agents and editors read. Open source (MIT).

## Reading

Definitions, guides, and essays about working with many agents at once.

- [Agentic Engineering](https://addyosmani.com/blog/agentic-engineering/) - Addy Osmani separates agent-driven engineering with human oversight from unreviewed vibe coding.
- [Best agentic IDEs compared](https://www.agentastic.dev/compare/best-agentic-ide) - Agentastic's comparison of agentic IDEs and multi-agent workspaces, written by a vendor in this category.
- [Embracing the parallel coding agent lifestyle](https://simonwillison.net/2025/Oct/5/parallel-coding-agents/) - Simon Willison on which tasks he hands to several agents at once and how he keeps up with them.
- [Git worktree documentation](https://git-scm.com/docs/git-worktree) - Reference for the Git feature most multi-agent IDEs use to give each agent its own checkout.
- [The Orchestration Tax](https://addyosmani.com/blog/orchestration-tax/) - Addy Osmani on why more agents running does not mean more human attention to review them.
- [Welcome to Gas Town](https://steve-yegge.medium.com/welcome-to-gas-town-4f25ee16dd04) - Steve Yegge's long introduction to running 20 or more coding agents through an orchestrator he calls a new take on the IDE.
- [What is an agentic development environment?](https://www.agentastic.dev/blog/what-is-an-agentic-development-environment) - Agentastic's definition of the ADE category and how it differs from AI editors and CLI agents.
- [Your parallel Agent limit](https://addyosmani.com/blog/cognitive-parallel-agents/) - Addy Osmani on the cognitive cost of supervising several agents and how to size the number you run.

## Related lists

- [Awesome Coding Agents](https://github.com/ahmadyan/awesome-coding-agents) - Command-line coding agents and harnesses, with makers, licenses, and install commands.
- [Awesome Personal Agents](https://github.com/ahmadyan/awesome-personal-agents) - Always-on personal agents, memory layers, runtimes, and messaging bridges.
- [Awesome Software Factory](https://github.com/ahmadyan/awesome-software-factory) - Tools, patterns, and essays for taking work from issue to merged pull request with coding agents.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.

---

Maintained by [Adel Ahmadyan](https://github.com/ahmadyan), who builds [Agentastic.dev](https://www.agentastic.dev).
