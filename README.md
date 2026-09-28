<!--lint disable awesome-heading-->

<div align="center">
  <h1>Awesome Claude Code</h1>
  <p>
    <a href="https://awesome.re"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a>
    <a href="https://github.com/fix2015/awesome-claude-code/stargazers"><img src="https://img.shields.io/github/stars/fix2015/awesome-claude-code?style=flat-square&color=yellow" alt="Stars"></a>
    <a href="https://github.com/fix2015/awesome-claude-code/network/members"><img src="https://img.shields.io/github/forks/fix2015/awesome-claude-code?style=flat-square" alt="Forks"></a>
    <a href="#contributing"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"></a>
  </p>
  <p>A curated list of awesome resources, tools, plugins, MCP servers, hooks, and tips for <a href="https://github.com/anthropics/claude-code">Claude Code</a> — the agentic coding tool that lives in your terminal.</p>
  <p><sub>If you find this list useful, please consider giving it a star. It helps others discover it too!</sub></p>
</div>

---

## Contents

- [Official Resources](#official-resources)
- [Agent Harnesses & Frameworks](#agent-harnesses--frameworks)
- [MCP Servers](#mcp-servers)
  - [General Purpose](#general-purpose)
  - [Browser & Web](#browser--web)
  - [Database & Cloud](#database--cloud)
  - [Design & Creative](#design--creative)
  - [Code Intelligence](#code-intelligence)
  - [DevOps & Cloud Platforms](#devops--cloud-platforms)
  - [Productivity & Communication](#productivity--communication)
  - [Search & Research](#search--research)
  - [Security](#security)
- [Skills & Plugins](#skills--plugins)
- [Hooks & Automation](#hooks--automation)
- [Memory & Context Management](#memory--context-management)
- [CLAUDE.md Templates & Best Practices](#claudemd-templates--best-practices)
- [IDE Integrations](#ide-integrations)
- [UI & Desktop Clients](#ui--desktop-clients)
- [Token Optimization & Proxies](#token-optimization--proxies)
- [Configuration & Optimization](#configuration--optimization)
- [Community Resources](#community-resources)
- [Contributing](#contributing)

---

## Official Resources

- [Claude Code](https://github.com/anthropics/claude-code) - The official Claude Code repository by Anthropic.
- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code) - Official documentation and guides.
- [Model Context Protocol Specification](https://modelcontextprotocol.io/) - The official MCP spec that powers Claude Code's extensibility.
- [MCP Servers](https://github.com/modelcontextprotocol/servers) - Official collection of reference MCP server implementations.
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) - Visual testing and debugging tool for MCP servers.

## Agent Harnesses & Frameworks

- [claude-code-router](https://github.com/musistudio/claude-code-router) - Local control plane for AI agents: route across models, fuse capabilities, orchestrate tools.
- [agents](https://github.com/wshobson/agents) - Multi-harness agentic plugin marketplace for Claude Code, Codex, Cursor, and Gemini CLI.
- [claude-plugins-official](https://github.com/anthropics/claude-plugins-official) - Official Anthropic-managed directory of high-quality Claude Code plugins.
- [ECC](https://github.com/affaan-m/ECC) - Agent harness performance optimization system with skills, instincts, memory, and security for Claude Code and beyond.
- [gstack](https://github.com/garrytan/gstack) - Garry Tan's Claude Code setup with 23 opinionated tools serving as CEO, Designer, Eng Manager, and more.
- [get-shit-done](https://github.com/gsd-build/get-shit-done) - Meta-prompting, context engineering, and spec-driven development system for Claude Code.
- [ruflo](https://github.com/ruvnet/ruflo) - Multi-player swarm orchestration with adaptive memory, self-learning intelligence, and RAG integration.
- [Trellis](https://github.com/mindfold-ai/Trellis) - A high-performance agent harness for Claude Code.
- [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) - Teams-first multi-agent orchestration for Claude Code.
- [SuperClaude Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) - Configuration framework with specialized commands, cognitive personas, and dev methodologies.
- [FastMCP](https://github.com/PrefectHQ/fastmcp) - The fast, Pythonic way to build MCP servers and clients.

## MCP Servers

### General Purpose

- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - The definitive collection of MCP servers (90k+ stars).
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - Microsoft's official Playwright MCP server for browser automation.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub's official MCP server for repository operations.
- [DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) - Terminal control, file system search, and diff editing capabilities.
- [GitMCP](https://github.com/idosal/git-mcp) - Free, open-source remote MCP server for any GitHub project. Eliminates code hallucinations.
- [Activepieces](https://github.com/activepieces/activepieces) - AI workflow automation with 400+ MCP servers for AI agents.
- [mcp-use](https://github.com/mcp-use/mcp-use) - Fullstack MCP framework to develop MCP apps and servers for AI agents.
- [Spec Workflow MCP](https://github.com/Pimzino/spec-workflow-mcp) - Structured spec-driven development workflow with web dashboard and VSCode extension.
- [MCP Feedback Enhanced](https://github.com/Minidoracat/mcp-feedback-enhanced) - Interactive user feedback and command execution in AI-assisted development.
- [Microsoft Skills](https://github.com/microsoft/skills) - Microsoft's official skills, MCP servers, and custom agents for coding agents.

### Browser & Web

- [MCP Chrome](https://github.com/hangwin/mcp-chrome) - Chrome extension-based MCP server for browser automation and content analysis.
- [Mobile MCP](https://github.com/mobile-next/mobile-mcp) - MCP server for mobile automation and scraping on iOS, Android, emulators, and real devices.

### Database & Cloud

- [MCP Toolbox for Databases](https://github.com/googleapis/mcp-toolbox) - Google's open-source MCP server for databases.
- [AWS MCP Servers](https://github.com/awslabs/mcp) - Open-source MCP servers for AWS services.
- [DBHub](https://github.com/bytebase/dbhub) - Zero-dependency, token-efficient MCP server for Postgres, MySQL, SQL Server, MariaDB, and SQLite.

### Design & Creative

- [Figma Context MCP](https://github.com/GLips/Figma-Context-MCP) - Provides Figma layout information to AI coding agents.
- [Magic MCP](https://github.com/21st-dev/magic-mcp) - Frontend UI generation MCP server — like v0 in your editor.

### Code Intelligence

- [Codebase Memory MCP](https://github.com/DeusData/codebase-memory-mcp) - Indexes codebases into a persistent knowledge graph. 158 languages, sub-ms queries.
- [Graphify](https://github.com/Graphify-Labs/graphify) - Turn any folder of code, SQL schemas, docs into a queryable knowledge graph.
- [CodeGraph](https://github.com/colbymchenry/codegraph) - Pre-indexed code knowledge graph that auto-syncs on code changes.
- [Understand-Anything](https://github.com/Egonex-AI/Understand-Anything) - Turn any code into an interactive knowledge graph you can explore and search.
- [Serena](https://github.com/oraios/serena) - MCP toolkit for semantic code retrieval and editing — acts as an IDE for your agent.

### DevOps & Cloud Platforms

- [Cloudflare MCP Server](https://github.com/cloudflare/mcp-server-cloudflare) - Official Cloudflare MCP server for managing Cloudflare services.
- [Azure DevOps MCP](https://github.com/microsoft/azure-devops-mcp) - Official Microsoft MCP server for Azure DevOps.
- [Grafana MCP](https://github.com/grafana/mcp-grafana) - Official MCP server for Grafana dashboards and observability.

### Productivity & Communication

- [Notion MCP Server](https://github.com/makenotion/notion-mcp-server) - Official Notion MCP server for workspace operations.
- [MCP Atlassian](https://github.com/sooperset/mcp-atlassian) - MCP server for Jira and Confluence.
- [Google Workspace MCP](https://github.com/taylorwilsdon/google_workspace_mcp) - Gmail, Calendar, Docs, Sheets, Slides, Chat, Forms, Tasks, Search, and Drive.
- [WhatsApp MCP](https://github.com/lharries/whatsapp-mcp) - WhatsApp MCP server for messaging integration.

### Search & Research

- [Firecrawl MCP Server](https://github.com/firecrawl/firecrawl-mcp-server) - Official Firecrawl MCP server for web scraping and search.
- [Exa MCP Server](https://github.com/exa-labs/exa-mcp-server) - Exa-powered web search and crawling MCP server.
- [Perplexity MCP](https://github.com/perplexityai/modelcontextprotocol) - Official Perplexity API MCP server for AI-powered search.
- [arXiv MCP Server](https://github.com/blazickjp/arxiv-mcp-server) - Search and analyze arXiv papers via MCP.

### Security

- [GhidraMCP](https://github.com/LaurieWired/GhidraMCP) - MCP server for Ghidra reverse engineering.
- [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - 150+ cybersecurity tools for automated pentesting and vulnerability discovery.

## Skills & Plugins

- [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - AI skill for design intelligence — build professional UI/UX across platforms.
- [agent-skills](https://github.com/addyosmani/agent-skills) - Addy Osmani's production-grade engineering skills for AI coding agents.
- [ponytail](https://github.com/DietrichGebert/ponytail) - Makes your AI agent think like the laziest senior dev — the best code is code you never wrote.
- [taste-skill](https://github.com/Leonxlnx/taste-skill) - Gives your AI good taste; stops it from generating boring, generic slop.
- [last30days-skill](https://github.com/mvanhorn/last30days-skill) - Researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web.
- [Agent-Reach](https://github.com/Panniantong/Agent-Reach) - Give your agent eyes to read Twitter, Reddit, YouTube, GitHub, and more — zero API fees.
- [career-ops](https://github.com/santifer/career-ops) - AI job search: scan portals, score listings, tailor CV, track applications.
- [codex-plugin-cc](https://github.com/openai/codex-plugin-cc) - Use Codex from Claude Code to review code or delegate tasks (official OpenAI plugin).
- [claude-hud](https://github.com/jarrodwatts/claude-hud) - Plugin showing context usage, active tools, running agents, and todo progress.
- [compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) - Official Compound Engineering plugin for Claude Code, Codex, and Cursor.
- [Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) - Turn Claude Code into a full game dev studio with 49 AI agents and 72 workflow skills.
- [awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) - Collection of 100+ specialized Claude Code subagents.
- [huashu-design](https://github.com/alchaincyf/huashu-design) - HTML-native design skill for high-fidelity prototypes, slides, animation, and MP4 export.
- [hallmark](https://github.com/Nutlope/hallmark) - Anti-AI-slop design skill for Claude Code, Cursor, and Codex.
- [andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) - A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations.
- [caveman](https://github.com/JuliusBrussee/caveman) - Cuts 65% of tokens by compressing communication style.
- [humanizer](https://github.com/blader/humanizer) - Removes signs of AI-generated writing from text.
- [claude-skills](https://github.com/alirezarezvani/claude-skills) - 345+ skills and plugins for Claude Code across engineering, marketing, product, and more.
- [agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) - Installable library of 1,900+ agentic skills with installer CLI and bundles.
- [scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) - 148 ready-to-use skills for science covering biology, chemistry, medicine, and drug discovery.
- [book-to-skill](https://github.com/virgiliojr94/book-to-skill) - Turn any technical book PDF into a Claude Code skill.
- [android-reverse-engineering-skill](https://github.com/SimoneAvogadro/android-reverse-engineering-skill) - Claude Code skill for Android app reverse engineering.
- [Trail of Bits Skills](https://github.com/trailofbits/skills) - Security research, vulnerability detection, and audit workflow skills.
- [codebase-to-course](https://github.com/zarazhangrui/codebase-to-course) - Turns any codebase into a beautiful, interactive single-page HTML course.
- [agent-rules](https://github.com/steipete/agent-rules) - Rules and knowledge to work better with agents such as Claude Code or Cursor.
- [Claude-Red](https://github.com/SnailSploit/Claude-Red) - Curated library of offensive security skills for Claude Code.
- [Raptor](https://github.com/gadievron/raptor) - Turns Claude Code into a general-purpose AI offensive/defensive security agent.
- [NotFair](https://github.com/nowork-studio/NotFair) - Open-source SEO, GEO/AEO, and paid-ads skills for Claude Code; bundles Google Search Console MCP, Google Analytics (GA4) MCP, Google Ads MCP, and Meta Ads MCP servers for live account data.

- [lintlang](https://github.com/hermes-labs-ai/lintlang) - Static analysis for AI agent configs, tool descriptions, and system prompts — catches vague descriptions, missing stop conditions, and schema gaps before runtime; ships a Claude Code plugin, pre-commit hook, and GitHub Action.

## Hooks & Automation

- [claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) - Master Claude Code hooks with examples and patterns.
- [claude-code-hooks-multi-agent-observability](https://github.com/disler/claude-code-hooks-multi-agent-observability) - Real-time monitoring for Claude Code agents through hook event tracking.
- [claude-code-hooks](https://github.com/shanraisshan/claude-code-hooks) - Claude Code hooks adding voice feedback on each hook event.
- [Continuous-Claude-v3](https://github.com/parcadei/Continuous-Claude-v3) - Context management with hooks that maintain state via ledgers and handoffs.
- [ccproxy](https://github.com/starbaser/ccproxy) - Build mods for Claude Code: hook any request, modify any response, intelligent model routing.
- [claude-ip-guard](https://github.com/cso1z/claude-ip-guard) - Claude Code hook plugin for IP-based access control and account protection.
- [workout-gate](https://github.com/BotchetDig/workout-gate) - A fun hook that blocks your prompt until you do your push-ups, counted via webcam.

## Memory & Context Management

- [beads](https://github.com/gastownhall/beads) - A memory upgrade for your coding agent.
- [Engram](https://github.com/Gentleman-Programming/engram) - Persistent memory system for AI coding agents with SQLite + FTS5, HTTP API, CLI, and TUI.
- [claude-reflect](https://github.com/BayramAnnakov/claude-reflect) - Self-learning system that captures corrections and preferences, then syncs to CLAUDE.md and AGENTS.md.
- [claude-mem](https://github.com/thedotmack/claude-mem) - Persistent context across sessions. Captures, compresses, and injects relevant context into future sessions.
- [agentmemory](https://github.com/rohitg00/agentmemory) - Persistent memory for AI coding agents based on real-world benchmarks.
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Persistent file-based planning for long-running agentic tasks. Crash-proof markdown plans.
- [claude-code-memory-setup](https://github.com/lucasrosati/claude-code-memory-setup) - Up to 71.5x fewer tokens per session with Obsidian + Graphify integration.
- [claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian) - Self-organizing AI second brain for Obsidian + Claude Code.


## CLAUDE.md Templates & Best Practices

- [claude-howto](https://github.com/luongnv89/claude-howto) - Visual, example-driven guide to Claude Code from basics to advanced agents.
- [context-engineering-intro](https://github.com/coleam00/context-engineering-intro) - Complete guide to context engineering for AI coding assistants.
- [claude-code-templates](https://github.com/davila7/claude-code-templates) - CLI tool for configuring and monitoring Claude Code.
- [claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice) - From vibe coding to agentic engineering — practice makes Claude perfect.
- [claude-code-system-prompts](https://github.com/Piebald-AI/claude-code-system-prompts) - All parts of Claude Code's system prompt, 27 built-in tool descriptions, and sub-agent prompts.
- [claude-token-efficient](https://github.com/drona23/claude-token-efficient) - One CLAUDE.md file to keep responses terse and reduce output verbosity.
- [my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup) - Shared starter template configuration and CLAUDE.md memory bank system.
- [tweakcc](https://github.com/Piebald-AI/tweakcc) - Customize system prompts, create custom toolsets, themes, input highlighters, and unlock private features.
- [learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) - A nano Claude Code-like agent harness, built from scratch.

## IDE Integrations

- [claudecode.nvim](https://github.com/coder/claudecode.nvim) - Official Claude Code Neovim IDE extension.
- [claudian](https://github.com/YishenTu/claudian) - Obsidian plugin that embeds Claude Code as an AI collaborator in your vault.
- [CC Switch](https://github.com/farion1231/cc-switch) - Cross-platform desktop all-in-one assistant for Claude Code, Codex, OpenCode, and more.
- [Open Design](https://github.com/nexu-io/open-design) - Open-source Claude Design alternative. Local-first desktop app for prototypes, dashboards, and more.
- [pal-mcp-server](https://github.com/BeehiveInnovations/pal-mcp-server) - Use Claude Code with Gemini, OpenAI, OpenRouter, Azure, Grok, Ollama, and custom models.

## UI & Desktop Clients

- [AionUi](https://github.com/iOfficeAI/AionUi) - Free, local, open-source 24/7 cowork app for Claude Code, Codex, Gemini CLI, and 20+ CLIs.
- [cmux](https://github.com/manaflow-ai/cmux) - Ghostty-based macOS terminal with vertical tabs and notifications for AI coding agents.
- [happy](https://github.com/slopus/happy) - Mobile and web client for Codex and Claude Code with realtime voice and encryption.
- [Claude Code UI](https://github.com/siteboon/claudecodeui) - Free open-source web UI/GUI to manage Claude Code sessions and projects remotely.

## Token Optimization & Proxies

- [rtk](https://github.com/rtk-ai/rtk) - CLI proxy reducing LLM token consumption by 60–90% on common dev commands; single Rust binary.
- [Headroom](https://github.com/headroomlabs-ai/headroom) - Compress tool outputs and logs before they reach the LLM. 20–95% fewer tokens for coding agents.
- [free-claude-code](https://github.com/Alishahryar1/free-claude-code) - Use Claude Code for free from the terminal, IDE, or phone.

## Configuration & Optimization

### Token Optimization

- Use `--output-format stream-json` for programmatic integration.
- Set `CLAUDE_CODE_MAX_TURNS` to control autonomous operation length.
- Use `/compact` command regularly to reduce context window usage.
- Leverage `.claude/settings.json` for project-specific configurations.

### Useful Environment Variables

```bash
# Set max output tokens
export CLAUDE_CODE_MAX_OUTPUT_TOKENS=16384

# Enable extended thinking
export CLAUDE_CODE_USE_BEDROCK=1

# Custom API endpoint
export ANTHROPIC_BASE_URL=https://your-proxy.com

# Set max turns for headless mode
export CLAUDE_CODE_MAX_TURNS=25
```

### Recommended .claude/settings.json Structure

```json
{
  "permissions": {
    "allow": [
      "Bash(git *)",
      "Bash(npm run *)",
      "Bash(npx *)",
      "Read",
      "Write",
      "Edit",
      "Glob",
      "Grep"
    ],
    "deny": [
      "Bash(rm -rf /)",
      "Bash(curl * | bash)"
    ]
  }
}
```

## Community Resources

- [awesome-claude-skills (ComposioHQ)](https://github.com/ComposioHQ/awesome-claude-skills) - Curated list of awesome Claude Skills.
- [awesome-claude-skills (travisvn)](https://github.com/travisvn/awesome-claude-skills) - Curated list of awesome Claude Skills, resources, and tools.
- [awesome-claude-code (hesreallyhim)](https://github.com/hesreallyhim/awesome-claude-code) - Another well-maintained awesome list for Claude Code.
- [awesome-mcp-servers (punkpeye)](https://github.com/punkpeye/awesome-mcp-servers) - The largest collection of MCP servers.
- [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients) - A collection of MCP clients.
- [awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) - Ultimate guide to agent skills with quickstart and resources.
- [system-prompts-leaks](https://github.com/asgeirtj/system_prompts_leaks) - Extracted system prompts from Claude Code and other AI tools.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

If you find this list useful, a star on the repo would be greatly appreciated. It helps other developers discover these resources.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work. See [LICENSE](LICENSE) for details.
