# Awesome Agent Harness

A curated list of practical resources for AI coding-agent harnesses, including skills and skill collections, agent systems and harness configurations, workflow systems, supporting tools, standards, and reference implementations. Covers Claude Code, Codex, Gemini CLI, OpenClaw, Hermes, and other coding-agent environments. Compatibility and installation requirements are project-specific; verify them in each linked repository.

## Contents

- [Skills](#skills)
  - [Development Workflow](#development-workflow)
  - [Codebase Understanding](#codebase-understanding)
  - [Frontend & Design](#frontend--design)
  - [Presentations & Video](#presentations--video)
  - [Product Management](#product-management)
  - [Marketing & Growth](#marketing--growth)
  - [Research](#research)
  - [Security](#security)
  - [Official Platform Skills](#official-platform-skills)
- [Skill Collections](#skill-collections)
- [Agent Systems & Harnesses](#agent-systems--harnesses)
- [Standards & References](#standards--references)

## Skills

### Development Workflow

- [Superpowers](https://github.com/obra/superpowers) - Agentic software development methodology with skills for brainstorming, planning, TDD, debugging, code review, verification, and subagent-driven development.
- [Agent Skills](https://github.com/addyosmani/agent-skills) - Production-grade engineering skills for AI coding agents.
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Persistent file-based planning for long-running agentic tasks across Claude Code, Codex, Hermes, and other SKILL.md-compatible agents.
- [Karpathy-Inspired Claude Code Guidelines](https://github.com/multica-ai/andrej-karpathy-skills) - Lightweight coding-agent guidelines for clearer assumptions, simpler code, surgical changes, and goal-driven execution.
- [Matt Pocock Skills](https://github.com/mattpocock/skills) - Practical engineering workflow skills for coding agents, including **grill-me** / **grill-with-docs** (one-question-at-a-time interviewing to sharpen plans, clarify requirements, and extract domain language before implementation), TDD, debugging, PRDs, architecture reviews, and handoffs. Installs via npx.
- [Waza](https://github.com/tw93/Waza) - Engineering habits packaged as skills that AI agents can run.
- [.NET Agent Skills](https://github.com/dotnet/skills) - Curated .NET and C# skills for AI coding agents.
- [ponytail](https://github.com/DietrichGebert/ponytail) - Pushes coding agents toward the simplest working solution: YAGNI, reuse, and stdlib or native features first. The project's benchmarks report ~54% less code on average.
- [caveman](https://github.com/JuliusBrussee/caveman) - Claude Code / Codex-compatible skill and plugin that compresses agent replies, commit messages, review comments, and memory files to reduce verbosity and token usage while preserving technical content.

### Codebase Understanding

- [Graphify](https://github.com/Graphify-Labs/graphify) - CLI-backed Agent Skill that turns codebases, docs, PDFs, screenshots, and diagrams into a queryable knowledge graph, with a persistent graph JSON, an interactive HTML view, and Obsidian vault export. Uses Claude vision for multimodal extraction. Documented for Claude Code, Cursor, Codex, and Gemini CLI.

### Frontend & Design

- [Taste Skill](https://github.com/Leonxlnx/taste-skill) - Anti-slop frontend and design skills for AI agents, covering landing pages, redesigns, image-to-code workflows, brand kits, and visual direction.
- [Impeccable](https://github.com/pbakaus/impeccable) - Design skill for AI coding agents that builds on Anthropic's `frontend-design`. Records product context in `PRODUCT.md`, then exposes 24 `/impeccable` commands (`shape`, `craft`, `critique`, `audit`, `polish`, `harden`, and more) plus 60 deterministic detector rules for common AI-generated design tells that run via CLI or browser extension without an LLM or API key. Install with `npx impeccable install`.
- [baoyu-design](https://github.com/JimLiu/baoyu-design) - Design skill for local agents (Claude Code, Cursor, Codex, and others) that generates UI mockups, interactive prototypes, wireframes, decks, and design systems as self-contained HTML. Supports Figma import, design system binding, and visual iteration in preview. Works best with Claude Opus.
- [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - UI/UX design intelligence skill for AI agents building interfaces across multiple platforms and frameworks.
- [Diagram Design](https://github.com/cathrynlavery/diagram-design) - Editorial-quality diagrams as self-contained HTML/SVG with no build step or external dependencies. Ships 27 visual types (architecture, flowchart, sequence, ER, timeline, swimlane, Gantt, and more) in light, dark, and editorial variants, with brand-token onboarding from a website and redrawing of draw.io or Mermaid sources. Installs as a plugin marketplace for Claude Code, Codex, and Pi.

### Presentations & Video

- [open-slide](https://github.com/open-slide/open-slide) - Agent-native React slide framework with scaffolded skills for creating decks, fixed-canvas authoring, inspector comments, present mode, and static HTML/PDF export.
- [HyperFrames](https://github.com/heygen-com/hyperframes) - HeyGen's open-source framework for rendering HTML, CSS, media, and seekable animations into deterministic MP4 videos. Ships 21 agent skills with a `/hyperframes` router that guides planning, authoring, linting, preview, and rendering, plus a Claude Code plugin marketplace and standalone `npx skills add` install for Codex, Cursor, Gemini CLI, and others.

### Product Management

- [PM Skills](https://github.com/phuryn/pm-skills) - Product management skill marketplace for AI agents, covering discovery, product strategy, PRDs, prioritization, market research, analytics, go-to-market, growth, and AI shipping workflows.

### Marketing & Growth

- [Marketing Skills](https://github.com/coreyhaines31/marketingskills) - Marketing and growth skills for AI agents, covering CRO, copywriting, SEO, analytics, paid ads, lifecycle messaging, pricing, launch, and revenue operations.
- [NotFair](https://github.com/nowork-studio/notfair-plugin) - Open-source marketing skill collection with 45 `SKILL.md` workflows: 20 SEO/GEO skills that run locally via the user's own gcloud credentials, plus paid-ads planning. Live Google Ads, Meta Ads, X Ads, LinkedIn Ads, GA4, and Search Console MCP skills go through NotFair-hosted endpoints and require a connected NotFair account (OAuth). The plugin also self-updates from its GitHub repo unless `update_check` is disabled.

### Research

- [last30days](https://github.com/mvanhorn/last30days-skill) - Research recent discussion, sentiment, and trends across Reddit, X, YouTube, TikTok, Hacker News, GitHub, Polymarket, and the web.
- [World Monitor](https://github.com/koala73/worldmonitor) - Agent-native real-time global intelligence platform with 25 packaged agent skills covering country briefs, conflict events, maritime and flight tracking, supply-chain disruption, internet outages, cyber threats, and markets. Ships an MCP server, REST API, CLI, and Python/Ruby/Go SDKs. AGPL-3.0 and self-hostable via docker-compose; most feeds need free-tier signups. The packaged skills target the hosted `api.worldmonitor.app` endpoints and require a WorldMonitor API key.
- [Academic Research Skills](https://github.com/Imbad0202/academic-research-skills) - Claude Code academic research pipeline for literature review, paper writing, peer review, revision, citation integrity checks, and publication workflows, with a [Codex-native adapter](https://github.com/Imbad0202/academic-research-skills-codex).

### Security

- [reverse-skill](https://github.com/zhaoxuya520/reverse-skill) - Skill router for reverse engineering, authorized penetration testing, and security research. Routes tasks across 85 `SKILL.md` modules for Android, iOS, binaries, .NET, frontend JS, malware, firmware, exploit development, APIs, supply chain, LLM security, and CTF workflows, with a scope and authorization gate before acting on a target. Client-neutral (Claude Code, Codex, Cursor, OpenCode). Requires Java, Node.js 22.12+, Python 3, and local security tooling; several helper scripts are PowerShell-only.
- [Anthropic Cybersecurity Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) - Large community library of 800+ structured cybersecurity skills for AI agents. Covers 29 security domains (threat hunting, DFIR, malware analysis, cloud security, pentesting, SOC operations, etc.) with detailed workflows mapped to MITRE ATT&CK, NIST CSF 2.0, D3FEND, ATLAS, AI RMF, and F3. Install via `npx skills add mukul975/Anthropic-Cybersecurity-Skills` or git clone. Works with Claude Code and other SKILL.md-compatible agents. (Community project, not affiliated with Anthropic.)
- [Trail of Bits Skills](https://github.com/trailofbits/skills) - Security research, vulnerability detection, and audit workflow skills for Claude Code.
- [Cloudflare Security Audit Skill](https://github.com/cloudflare/security-audit-skill) - Official Cloudflare coding-agent skill for multi-phase security audits. Orchestrates parallel recon and vulnerability-hunting agents, adversarial validation, structured `findings.json`, and an independent verification pass to focus on exploitable vulnerabilities with real impact. Requires an agent with subagent/parallel execution support and Node.js for schema validation.
- [Codex Security](https://github.com/openai/codex-security) - OpenAI's official CLI and TypeScript SDK for defining security policy and finding, validating, and fixing vulnerabilities in a codebase (`npx @openai/codex-security scan <dir>`). Requires Node.js 22.13+, Python 3.10+, and a Codex login; some cybersecurity requests and protected findings require approval through OpenAI's Trusted Access for Cyber program.
- [SkillSpector](https://github.com/NVIDIA/SkillSpector) - NVIDIA's open-source security scanner for AI agent skills. Detects vulnerabilities, malicious patterns, and risks (including prompt injection, data exfiltration, MCP tool poisoning, and dangerous code) in SKILL.md-based skills before installation. Supports static analysis with optional LLM semantic analysis and SARIF reports.
- [clawsec](https://github.com/prompt-security/clawsec) - Security skill suite for OpenClaw and Hermes with drift detection, audits, and skill integrity verification.
- [reverse-engineer-anything (REA)](https://github.com/morluto/rea/tree/main/skill-src/reverse-engineer-anything) - Skill and local CLI/MCP workflows for investigating shipped binaries and JavaScript/Electron apps with source-linked evidence and explicit unknowns. Install REA separately; deep native analysis requires your own Hopper, Ghidra, or IDA. REA is MIT, with no REA account or hosted API requirement; analysis-engine licenses and the connected agent's model costs are separate.

### Official Platform Skills

- [Microsoft Skills](https://github.com/microsoft/skills) - Skills, MCP servers, custom agents, and `AGENTS.md` resources for grounding coding agents.
- [Google Skills](https://github.com/google/skills) - Agent Skills for Google products and technologies, including Google Cloud, Firebase, BigQuery, Cloud Run, and GKE.
- [Google Workspace CLI](https://github.com/googleworkspace/cli) - One CLI for Gmail, Drive, Docs, Calendar, Sheets, Chat and more Workspace APIs. Dynamically built from Discovery Service. Ships with 100+ Agent Skills (SKILL.md files), per-API service skills, helper commands (e.g. +send, +agenda), and curated workflow recipes. Install via `npx skills add https://github.com/googleworkspace/cli`.
- [Gemini API Skills](https://github.com/google-gemini/gemini-skills) - Skills for building Gemini API, SDK, Live API, and model interaction workflows.
- [Supabase Agent Skills](https://github.com/supabase/agent-skills) - Official Postgres best practices and Supabase platform skills for accurate database and backend code.
- [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills) - Official React, Next.js best practices, web design guidelines, composition patterns, and performance optimization skills.
- [Cursor Team Skills](https://github.com/cursor/plugins) - Skills and plugins from the Cursor team, including **thermo-nuclear-code-quality-review**, a strict maintainability review focused on abstraction quality, structural simplification, removing complexity instead of relocating it, and file size discipline.
- [Obsidian Skills](https://github.com/kepano/obsidian-skills) - Official agent skills by Obsidian's creator for Obsidian Flavored Markdown (wikilinks, embeds, callouts, properties), Bases (`.base`), JSON Canvas, CLI (including plugin/theme development), vault workflows, and Defuddle web-to-markdown extraction.

## Skill Collections

- [AAS Core (Agentic Awesome Skills)](https://github.com/sickn33/agentic-awesome-skills) - Local, agent-first control plane over a catalog of 2,000+ agentic skills for Claude Code and Codex. Ships a read-only stdio MCP server and an `aas` CLI for catalog search, agent-owned skill selection, manifest validation, and reproducible stack plans (`aas-stack.json`). Apply and recovery are experimental and outside the supported preview path. Formerly published as Antigravity Awesome Skills.
- [Claude Code Skills & Plugins](https://github.com/alirezarezvani/claude-skills) - Large cross-agent library of skills, agents, personas, and commands for Claude Code, Codex, Gemini CLI, OpenClaw, Hermes, and more.
- [Suede Creator Skills](https://github.com/JasonColapietro/suede-creator-skills) - MIT-licensed collection of 71 skills for Claude Code and Codex. Original work covers agent orchestration (Full Send, ship DAG, Codex worker fleets), A-F code review grading, AI evals, and CI gates; ships a dependency-free stdio MCP server. Note: 38 of the marketing skills are rebranded near-copies of [Marketing Skills](https://github.com/coreyhaines31/marketingskills), also listed above.

## Agent Systems & Harnesses

- [OpenMontage](https://github.com/calesthio/OpenMontage) - Open-source agentic video production system with 12 pipelines, 52 tools, and 500+ agent skills. Turns AI coding assistants (Claude Code, Cursor, Codex, etc.) into a full video studio for animated explainers, documentaries, cinematic trailers, animations, and more.
- [Agency Agents](https://github.com/msitarzewski/agency-agents) - Multi-tool agent setup with 200+ specialized roles across 16+ divisions, integration-generation and installation scripts, and a companion native app for Claude Code, Cursor, Codex, Gemini CLI, OpenClaw, and more. Install selectively by team or agent.
- [ECC](https://github.com/affaan-m/ECC) - Large agent harness optimization system with 260+ skills, subagents, memory, security tools, and cross-platform orchestration for Claude Code, Cursor, Codex, and more.
- [gstack](https://github.com/garrytan/gstack) - Garry Tan's personal Claude Code setup with 23 opinionated agent skills/tools serving roles like CEO, Engineer, Designer, QA, and more.
- [Agent QA](https://github.com/vostride/agent-qa) - TypeScript application-QA harness for natural-language web/mobile tests with persistent test memory, self-healing flows, structured evidence, CLI/dashboard access, and an official MCP server. Requires Node.js 24+ and a configured model provider; provider usage may incur charges. The current FSL-1.1-ALv2 release is source-available.
- [SandBase Harness](https://github.com/sandbaseai/sandbase-harness) - Local-first, self-hosted TypeScript agent runtime and MCP bridge with persistent sessions, governed tool access, approvals, credentials, memory, audit/replay, and Docker/Kubernetes/worker execution backends. Configure a supported model provider as described in the installation guide; isolation depends on the selected backend and deployment configuration.
- [T3 Code](https://github.com/pingdotgg/t3code) - Open-source control surface for coding agents already installed and signed in on your machine (Claude Code, Codex, Cursor, Grok Build, OpenCode, and Antigravity), with web, desktop, iOS, and Android clients. Remote access works over LAN, Tailscale, SSH, or the hosted T3 Connect relay; exposing it remotely grants control of an agent that can edit files and run commands. Early-stage project.

## Standards & References

- [Agent Skills](https://github.com/agentskills/agentskills) - Specification and documentation for portable Agent Skills.
- [Anthropic Skills](https://github.com/anthropics/skills) - Reference repository for Anthropic's Agent Skills implementation.

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) for scope, placement, and submission requirements.

## License

[MIT](LICENSE)
