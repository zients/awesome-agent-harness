# Awesome Agent Harness

A curated list of practical resources for AI coding-agent harnesses, including skills and skill collections, agent systems and harness configurations, workflow systems, supporting tools, standards, and reference implementations. Covers Claude Code, Codex, Gemini CLI, OpenClaw, Hermes, and other coding-agent environments. Compatibility and installation requirements are project-specific; verify them in each linked repository.

## Skills

### Development Workflow

- [Superpowers](https://github.com/obra/superpowers) - Agentic software development methodology with skills for brainstorming, planning, TDD, debugging, code review, verification, and subagent-driven development.
- [Agent Skills](https://github.com/addyosmani/agent-skills) - Production-grade engineering skills for AI coding agents.
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Persistent file-based planning for long-running agentic tasks across Claude Code, Codex, Hermes, and other SKILL.md-compatible agents.
- [Karpathy-Inspired Claude Code Guidelines](https://github.com/multica-ai/andrej-karpathy-skills) - Lightweight coding-agent guidelines for clearer assumptions, simpler code, surgical changes, and goal-driven execution.
- [Matt Pocock Skills](https://github.com/mattpocock/skills) - Practical engineering workflow skills for coding agents. Standout skills include **grill-me** / **grill-with-docs** (relentless one-question-at-a-time interviewing to sharpen plans, clarify requirements, extract domain language, and eliminate ambiguity before implementation; widely praised on X as a "secret sauce" that dramatically improves results for both coding and real-world tasks) plus TDD, debugging, PRDs, architecture reviews, and handoffs. Actively maintained with npx installer.
- [Waza](https://github.com/tw93/Waza) - Engineering habits packaged as skills that AI agents can run.
- [three-man-team](https://github.com/russelleNVy/three-man-team) - Structured Architect, Builder, and Reviewer workflow for AI-assisted development.
- [.NET Agent Skills](https://github.com/dotnet/skills) - Curated .NET and C# skills for AI coding agents.
- [ponytail](https://github.com/DietrichGebert/ponytail) - Forces AI coding agents to think like the laziest (most efficient) senior dev: simplest working solution via YAGNI, reuse, stdlib and native features first (benchmarks show ~54% less code on average, up to 94%).
- [caveman](https://github.com/JuliusBrussee/caveman) - Claude Code / Codex-compatible skill and plugin that compresses agent replies, commit messages, review comments, and memory files to reduce verbosity and token usage while preserving technical content.

### Codebase Understanding

- [Graphify](https://github.com/safishamsi/graphify) - CLI-backed Agent Skill that turns codebases, docs, schemas, papers, images, and videos into a queryable knowledge graph for Claude Code, Codex, OpenCode, Cursor, Gemini CLI, OpenClaw, Hermes, and more.

### Frontend & Design

- [Taste Skill](https://github.com/Leonxlnx/taste-skill) - Anti-slop frontend and design skills for AI agents, covering landing pages, redesigns, image-to-code workflows, brand kits, and visual direction.
- [baoyu-design](https://github.com/JimLiu/baoyu-design) - Brings Claude's powerful design engine to local agents (Cursor, Claude Code, Codex, etc.). Generates polished UI mockups, interactive prototypes, wireframes, decks, design systems and more as self-contained HTML. Supports Figma import, design system binding, and visual iteration in preview. Best with Opus.
- [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - High-star UI/UX design intelligence skill for AI agents building professional interfaces across multiple platforms.

### Presentations

- [open-slide](https://github.com/1weiho/open-slide) - Agent-native React slide framework with scaffolded skills for creating decks, fixed-canvas authoring, inspector comments, present mode, and static HTML/PDF export.

### Product Management

- [PM Skills](https://github.com/phuryn/pm-skills) - Product management skill marketplace for AI agents, covering discovery, product strategy, PRDs, prioritization, market research, analytics, go-to-market, growth, and AI shipping workflows.

### Marketing & Growth

- [Marketing Skills](https://github.com/coreyhaines31/marketingskills) - Marketing and growth skills for AI agents, covering CRO, copywriting, SEO, analytics, paid ads, lifecycle messaging, pricing, launch, and revenue operations.
- [NotFair](https://github.com/nowork-studio/NotFair) - Open-source marketing skill collection with 16 `SKILL.md` workflows for SEO, GEO, Google Ads, and Meta Ads. The repository provides the installable skills; optional live audits and account operations require connected NotFair-hosted accounts.

### Research

- [last30days](https://github.com/mvanhorn/last30days-skill) - Research recent discussion, sentiment, and trends across Reddit, X, YouTube, TikTok, Hacker News, GitHub, Polymarket, and the web.
- [Academic Research Skills](https://github.com/Imbad0202/academic-research-skills) - Claude Code academic research pipeline for literature review, paper writing, peer review, revision, citation integrity checks, and publication workflows, with a [Codex-native adapter](https://github.com/Imbad0202/academic-research-skills-codex).

### Security

- [Anthropic Cybersecurity Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) - Large community library of 800+ structured cybersecurity skills for AI agents. Covers 29 security domains (threat hunting, DFIR, malware analysis, cloud security, pentesting, SOC operations, etc.) with detailed workflows mapped to MITRE ATT&CK, NIST CSF 2.0, D3FEND, ATLAS, AI RMF, and F3. Install via `npx skills add mukul975/Anthropic-Cybersecurity-Skills` or git clone. Works with Claude Code and other SKILL.md-compatible agents. (Community project, not affiliated with Anthropic.)
- [Trail of Bits Skills](https://github.com/trailofbits/skills) - Security research, vulnerability detection, and audit workflow skills for Claude Code.
- [Cloudflare Security Audit Skill](https://github.com/cloudflare/security-audit-skill) - Official Cloudflare coding-agent skill for multi-phase security audits. Orchestrates parallel recon and vulnerability-hunting agents, adversarial validation, structured `findings.json`, and an independent verification pass to focus on exploitable vulnerabilities with real impact. Requires an agent with subagent/parallel execution support and Node.js for schema validation.
- [SkillSpector](https://github.com/NVIDIA/SkillSpector) - NVIDIA's open-source security scanner for AI agent skills. Detects vulnerabilities, malicious patterns, and risks (including prompt injection, data exfiltration, MCP tool poisoning, and dangerous code) in SKILL.md-based skills before installation. Supports static analysis with optional LLM semantic analysis and SARIF reports.
- [clawsec](https://github.com/prompt-security/clawsec) - Security skill suite for OpenClaw and Hermes with drift detection, audits, and skill integrity verification.

### Skill Collections

- [Antigravity Awesome Skills](https://github.com/sickn33/antigravity-awesome-skills) - Installable library of 1,500+ agentic skills with specialized plugins, bundles, workflows, and npx installer for Claude Code, Cursor, Gemini CLI, and more.
- [Claude Code Skills & Plugins](https://github.com/alirezarezvani/claude-skills) - Large cross-agent library of skills, agents, personas, and commands for Claude Code, Codex, Gemini CLI, OpenClaw, Hermes, and more.
- [Suede Creator Skills](https://github.com/JasonColapietro/suede-creator-skills) - MIT-licensed collection of 71 skills for Claude Code and Codex. Original work covers agent orchestration (Full Send, ship DAG, Codex worker fleets), A-F code review grading, AI evals, and CI gates; ships a dependency-free stdio MCP server. Note: 38 of the marketing skills are rebranded near-copies of [Marketing Skills](https://github.com/coreyhaines31/marketingskills), also listed above.
- [Awesome Agent Skills](https://github.com/VoltAgent/awesome-agent-skills) - Large curated collection of Agent Skills compatible with Claude Code, Codex, Gemini CLI, Cursor, and more.

### Official Platform Skills

- [Microsoft Skills](https://github.com/microsoft/skills) - Skills, MCP servers, custom agents, and `AGENTS.md` resources for grounding coding agents.
- [Google Skills](https://github.com/google/skills) - Agent Skills for Google products and technologies, including Google Cloud, Firebase, BigQuery, Cloud Run, and GKE.
- [Google Workspace CLI](https://github.com/googleworkspace/cli) - One CLI for Gmail, Drive, Docs, Calendar, Sheets, Chat and more Workspace APIs. Dynamically built from Discovery Service. Ships with 100+ Agent Skills (SKILL.md files), per-API service skills, helper commands (e.g. +send, +agenda), and curated workflow recipes. Install via `npx skills add https://github.com/googleworkspace/cli`.
- [Gemini API Skills](https://github.com/google-gemini/gemini-skills) - Skills for building Gemini API, SDK, Live API, and model interaction workflows.
- [Supabase Agent Skills](https://github.com/supabase/agent-skills) - Official Postgres best practices and Supabase platform skills for accurate database and backend code.
- [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills) - Official React, Next.js best practices, web design guidelines, composition patterns, and performance optimization skills.
- [Cursor Team Skills](https://github.com/cursor/plugins) - Cursor team skills. Standout: **thermo-nuclear-code-quality-review** (extremely strict maintainability review focused on abstraction quality, ambitious "code judo" structural simplifications, removing complexity instead of relocating it, file size discipline, and blocking spaghetti growth). Widely regarded as one of the most powerful and heavily-used internal skills at Cursor.
- [Obsidian Skills](https://github.com/kepano/obsidian-skills) - Official agent skills by Obsidian's creator for Obsidian Flavored Markdown (wikilinks, embeds, callouts, properties), Bases (`.base`), JSON Canvas, CLI (including plugin/theme development), and vault workflows.

## Agent Systems & Harnesses

- [OpenMontage](https://github.com/calesthio/OpenMontage) - Open-source agentic video production system with 12 pipelines, 52 tools, and 500+ agent skills. Turns AI coding assistants (Claude Code, Cursor, Codex, etc.) into a full video studio for animated explainers, documentaries, cinematic trailers, animations, and more.
- [Agency Agents](https://github.com/msitarzewski/agency-agents) - Multi-tool agent setup with 200+ specialized roles across 16+ divisions, integration-generation and installation scripts, and a companion native app for Claude Code, Cursor, Codex, Gemini CLI, OpenClaw, and more. Install selectively by team or agent.
- [ECC](https://github.com/affaan-m/ECC) - Massive agent harness performance optimization system with 260+ skills, subagents, memory, security tools, and cross-platform orchestration for Claude Code, Cursor, Codex, and more.
- [gstack](https://github.com/garrytan/gstack) - Garry Tan's personal Claude Code setup with 23 opinionated agent skills/tools serving roles like CEO, Engineer, Designer, QA, and more.

## Standards & References

- [Agent Skills](https://github.com/agentskills/agentskills) - Specification and documentation for portable Agent Skills.
- [Anthropic Skills](https://github.com/anthropics/skills) - Reference repository for Anthropic's Agent Skills implementation.
