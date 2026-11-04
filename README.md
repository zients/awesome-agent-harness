# Awesome Agent Harness

A curated list of skills, workflows, tools, and harnesses for coding agents. Check each project's setup and agent compatibility; model usage and external services may incur charges. Entries note required accounts, hosted dependencies, and notable license restrictions.

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

- [Addy Osmani's Agent Skills](https://github.com/addyosmani/agent-skills) - Engineering skills for specifications, planning, implementation, testing, code review, web performance, and release.
- [Agent Desktop](https://github.com/vercel-labs/agent-desktop) - CLI and skills for desktop automation through native accessibility APIs on macOS, Windows, and Linux. Requires OS permissions/services; the optional JEV helper sends screen descriptions to a configured model.
- [caveman](https://github.com/JuliusBrussee/caveman) - Reply and writing style skill that reduces verbosity while preserving technical details. Supports Claude Code and Codex.
- [Karpathy-Inspired Guidelines](https://github.com/multica-ai/andrej-karpathy-skills) - Coding guidelines for stating assumptions, keeping changes small, avoiding unnecessary complexity, and verifying outcomes.
- [Matt Pocock Skills](https://github.com/mattpocock/skills) - Engineering skills for requirements interviews (`grill-me`, `grill-with-docs`), TDD, debugging, architecture, planning, and handoffs.
- [OpenSpec](https://github.com/Fission-AI/OpenSpec) - Specification workflows for proposals, design, tasks, spec validation, and change archiving. Requires the OpenSpec CLI; integrates with Claude Code, Codex, and other agents.
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Persistent file-based planning for long-running agent tasks, with plans, findings, and progress kept in the project.
- [ponytail](https://github.com/DietrichGebert/ponytail) - Coding guidelines focused on YAGNI, reuse, standard libraries, and simpler implementations.
- [Superpowers](https://github.com/obra/superpowers) - Development workflow for brainstorming, planning, TDD, debugging, code review, and verification.
- [Waza](https://github.com/tw93/Waza) - Engineering playbooks for planning, UI work, debugging, review, writing, research, and agent setup audits.
- [Worktrunk](https://github.com/max-sixty/worktrunk) - Git worktree CLI and skills for parallel coding workflows, lifecycle hooks, status views, and merge support. Requires Git; optional commit generation uses a model.

### Codebase Understanding

- [Graphify](https://github.com/Graphify-Labs/graphify) - CLI and skill for querying code and documents as a knowledge graph, with HTML and Obsidian views. Multimodal extraction uses Claude vision.

### Frontend & Design

- [baoyu-design](https://github.com/JimLiu/baoyu-design) - UI mockups, prototypes, wireframes, decks, and design systems as HTML, with Figma import and visual iteration.
- [Diagram Design](https://github.com/cathrynlavery/diagram-design) - Technical diagrams as HTML/SVG, with visual templates, brand onboarding, and theme support. No build step.
- [Impeccable](https://github.com/pbakaus/impeccable) - Frontend workflows built around product context, with critique, audit, and polish commands plus deterministic checks via CLI or browser extension.
- [Taste Skill](https://github.com/Leonxlnx/taste-skill) - Frontend design skills for landing pages, redesigns, image-to-code workflows, brand kits, and visual direction.
- [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - Web and mobile interface guidance covering styles, palettes, typography, layouts, accessibility, and implementation patterns.

### Presentations & Video

- [HyperFrames](https://github.com/heygen-com/hyperframes) - HTML/CSS video rendering with agent skills for authoring, preview, validation, and MP4 export.
- [open-slide](https://github.com/open-slide/open-slide) - React slide framework and agent skills for fixed-canvas authoring, preview comments, presentation mode, and HTML/PDF export.

### Product Management

- [PM Skills](https://github.com/phuryn/pm-skills) - Product workflows for discovery, strategy, PRDs, prioritization, research, analytics, launches, and growth.

### Marketing & Growth

- [Claude SEO](https://github.com/AgriciDaniel/claude-seo) - Claude Code SEO/GEO audits with local crawling, rendering, schema checks, drift tracking, and reports. Requires Python 3.11–3.14; browser checks need Chromium. External SEO APIs are optional.
- [Marketing Skills](https://github.com/coreyhaines31/marketingskills) - Marketing workflows for copywriting, SEO, analytics, advertising, lifecycle messaging, pricing, launches, and conversion optimization.
- [NotFair](https://github.com/nowork-studio/notfair-plugin) - SEO/GEO and marketing workflows. Local Google helpers use gcloud credentials; hosted integrations require a NotFair account. Includes a configurable update checker.

### Research

- [Academic Research Skills](https://github.com/Imbad0202/academic-research-skills) - Claude Code pipeline for literature review, writing, peer review, revision, and citation checks; a [Codex adapter](https://github.com/Imbad0202/academic-research-skills-codex) is also available.
- [last30days](https://github.com/mvanhorn/last30days-skill) - Research recent discussion, sentiment, and trends across social platforms, developer communities, GitHub, and the web.
- [World Monitor](https://github.com/koala73/worldmonitor) - Global news, conflict, infrastructure, and market research through agent skills, CLI/MCP, and APIs. AGPL-3.0; hosted MCP tool calls require an API key or OAuth.

### Security

- [clawsec](https://github.com/prompt-security/clawsec) - Security workflows for OpenClaw and Hermes, including drift checks, audits, and skill integrity verification. AGPL-3.0.
- [Cloudflare Security Audit Skill](https://github.com/cloudflare/security-audit-skill) - Security audits with parallel investigation, adversarial validation, and structured findings. Requires an agent with subagent support and Node.js for validation.
- [Codex Security](https://github.com/openai/codex-security) - Official CLI and TypeScript SDK for finding, validating, and fixing code vulnerabilities. Requires supported Node.js/Python runtimes and Codex authentication; some access needs Trusted Access for Cyber.
- [Community Cybersecurity Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) - Community workflows for threat hunting, incident response, malware analysis, cloud security, and penetration testing. Not affiliated with Anthropic.
- [Reverse Engineer Anything (REA)](https://github.com/morluto/rea/tree/main/.agents/skills/reverse-engineer-anything) - Skill and local CLI/MCP for binary and JavaScript/Electron investigation with source-linked evidence. Requires [REA/Node.js setup](https://github.com/morluto/rea/blob/main/docs/installation.md); deep native analysis needs an engine such as Ghidra, Hopper, IDA, or Kuna.
- [reverse-skill](https://github.com/zhaoxuya520/reverse-skill) - Router for reverse engineering, authorized testing, and security research. Requires Java, Node.js 22.12+, Python, and local analysis tools; some helpers require PowerShell.
- [SkillSpector](https://github.com/NVIDIA/SkillSpector) - NVIDIA scanner for vulnerabilities and malicious patterns in agent skills, with static checks, optional model analysis, and SARIF output.
- [Trail of Bits Skills](https://github.com/trailofbits/skills) - Security analysis, testing, and audit workflows for Claude Code and Codex. CC BY-SA 4.0.

### Official Platform Skills

- [Cursor Team Skills](https://github.com/cursor/plugins) - Cursor team's skills and plugins for development workflows, including strict maintainability and code-quality reviews.
- [Gemini API Skills](https://github.com/google-gemini/gemini-skills) - Skills for Gemini APIs, SDKs, Live API, and model integration.
- [Google Skills](https://github.com/google/skills) - Skills for Google products, including Google Cloud, Firebase, BigQuery, Cloud Run, and GKE.
- [Google Workspace CLI](https://github.com/googleworkspace/cli) - Discovery-based CLI and agent skills for Google Workspace APIs, including Gmail, Drive, Docs, Calendar, Sheets, and Chat. Requires Google authentication.
- [Microsoft Skills](https://github.com/microsoft/skills) - Skills, MCP servers, and custom agents for Microsoft products, SDKs, and cloud services.
- [.NET Agent Skills](https://github.com/dotnet/skills) - Official .NET/C# skills and host-specific custom agents maintained by the .NET team.
- [Obsidian Skills](https://github.com/kepano/obsidian-skills) - Skills for Obsidian Markdown, properties, Bases, Canvas, CLI workflows, and web-to-Markdown extraction.
- [Supabase Agent Skills](https://github.com/supabase/agent-skills) - Postgres and backend development guidance for agents working with Supabase.
- [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills) - React, Next.js, composition, performance, and web design guidance from Vercel.

## Skill Collections

- [AAS Core](https://github.com/sickn33/agentic-awesome-skills) - Skill catalog with a local CLI/MCP for search, agent-owned selection, validation, and plan previews. Apply and recovery remain experimental.
- [Agency Agents](https://github.com/msitarzewski/agency-agents) - Cross-domain specialist role library with installation and conversion scripts for multiple coding agents.
- [Claude Code Skills & Plugins](https://github.com/alirezarezvani/claude-skills) - Cross-domain skills, plugins, and agent templates for engineering, operations, marketing, security, leadership, and research.
- [Suede AI Skills](https://github.com/JasonColapietro/suede-creator-skills) - Orchestration, graded reviews, CI gates, and marketing skills with a local MCP server. Includes [adapted upstream material](https://github.com/JasonColapietro/suede-creator-skills/blob/main/NOTICE.md), including [Marketing Skills](https://github.com/coreyhaines31/marketingskills).

## Agent Systems & Harnesses

- [Agent QA](https://github.com/vostride/agent-qa) - Web/mobile QA harness with natural-language tests, persistent memory, evidence, and CLI/MCP access. Requires Node.js 24+ and a model provider. FSL-1.1-ALv2 (source-available).
- [ECC](https://github.com/affaan-m/ECC) - Integrated skills, agents, hooks, memory, security checks, and cross-platform configuration for coding-agent workflows.
- [gstack](https://github.com/garrytan/gstack) - Claude Code setup with product, engineering, design, review, and QA workflows.
- [OpenMontage](https://github.com/calesthio/OpenMontage) - Agent skills, tools, and pipelines for video research, scripting, assets, editing, and rendering. AGPL-3.0; optional generation services require separate credentials.
- [SandBase Harness](https://github.com/sandbaseai/sandbase-harness) - Self-hosted agent runtime with persistent sessions, tool governance, memory, approvals, and audit/replay. Requires a model provider; isolation depends on the configured backend.
- [Sandcastle](https://github.com/mattpocock/sandcastle) - TypeScript SDK and CLI for agent orchestration, sandbox providers, Git branches, hooks, and merges. Requires Git and a configured agent; isolation depends on the backend.
- [T3 Code](https://github.com/pingdotgg/t3code) - Web, desktop, and mobile control surface for existing coding agents. Requires installed, authenticated agents; remote access exposes their file and command permissions.

## Standards & References

- [Agent Skills Specification](https://github.com/agentskills/agentskills) - Specification and documentation for portable Agent Skills.
- [Anthropic Skills Reference](https://github.com/anthropics/skills) - Anthropic's reference skills and implementation examples.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for scope, placement, and entry guidelines.

## License

[MIT](LICENSE)
