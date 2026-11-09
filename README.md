# Awesome Agent Harness

A curated list of skills, workflows, tools, and harnesses for coding agents. Check each project's setup and agent compatibility; model usage and external services may incur charges. Entries note required accounts, hosted dependencies, and notable license restrictions.

## Contents

- [Skills](#skills)
  - [Development Workflow](#development-workflow)
  - [Codebase Understanding](#codebase-understanding)
  - [Frontend & Design](#frontend--design)
  - [Presentations & Video](#presentations--video)
  - [Product & Marketing](#product--marketing)
  - [Research](#research)
  - [Security](#security)
  - [Official Platform Skills](#official-platform-skills)
- [Skill Collections](#skill-collections)
- [Agent Systems & Harnesses](#agent-systems--harnesses)
- [Standards & References](#standards--references)

## Skills

### Development Workflow

- [Addy Osmani's Agent Skills](https://github.com/addyosmani/agent-skills) - Engineering skills for specifications, planning, implementation, testing, code review, web performance, and release.
- [Agent Desktop](https://github.com/vercel-labs/agent-desktop) - CLI and skills for native desktop automation on macOS, Windows, and Linux. Requires OS permissions; the optional JEV helper sends screen descriptions to a configured model.
- [caveman](https://github.com/JuliusBrussee/caveman) - Reply and writing style skill that reduces verbosity while preserving technical details, with an optional local proxy.
- [Matt Pocock Skills](https://github.com/mattpocock/skills) - Engineering skills for requirements interviews (`grill-me`, `grill-with-docs`), TDD, debugging, architecture, planning, and handoffs.
- [OpenSpec](https://github.com/Fission-AI/OpenSpec) - Specification workflows for proposals, design, tasks, validation, and change archiving. Requires the OpenSpec CLI.
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Persistent file-based planning for long-running agent tasks, with plans, findings, and progress kept in the project.
- [ponytail](https://github.com/DietrichGebert/ponytail) - Coding guidelines focused on YAGNI, reuse, standard libraries, and simpler implementations.
- [Superpowers](https://github.com/obra/superpowers) - Development workflow for brainstorming, planning, TDD, debugging, code review, and verification.
- [Waza](https://github.com/tw93/Waza) - Engineering playbooks for planning, UI work, debugging, review, writing, research, and agent setup audits.
- [Worktrunk](https://github.com/max-sixty/worktrunk) - Git worktree CLI and skills for parallel coding workflows, with lifecycle hooks and merge support. Optional commit generation uses a model.

### Codebase Understanding

- [Graphify](https://github.com/Graphify-Labs/graphify) - CLI and skill for querying code and documents as a knowledge graph, with HTML and Obsidian views. Non-code extraction uses your agent's model or an API key.

### Frontend & Design

- [Diagram Design](https://github.com/cathrynlavery/diagram-design) - Technical diagrams as HTML/SVG, with visual templates, brand onboarding, and theme support. No build step.
- [Hallmark](https://github.com/Nutlope/hallmark) - Design skill for building, redesigning, and auditing pages, with themes and lint checks for generic AI patterns. Requires Node.js; browser checks need `puppeteer-core` and Chrome, and optional image generation needs a Together AI API key.
- [Impeccable](https://github.com/pbakaus/impeccable) - Frontend workflows built around product context, with critique, audit, and polish commands plus deterministic checks via CLI or browser extension.
- [Jakub Krehel Skills](https://github.com/jakubkrehel/skills) - Interface skills for reviewing accessibility, layout, typography, color, UI polish, and product copy, plus component-state and design-to-code tools. Figma builds require a Figma MCP server.
- [Taste Skill](https://github.com/Leonxlnx/taste-skill) - Frontend design skill for company websites, with art direction, reference images, and real-browser checks.
- [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - Web and mobile interface guidance covering styles, palettes, typography, layouts, accessibility, and implementation patterns.

### Presentations & Video

- [HyperFrames](https://github.com/heygen-com/hyperframes) - HTML/CSS video rendering with agent skills for authoring, preview, validation, and MP4 export.
- [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) - Agent skills, tools, and pipelines for video research, scripting, assets, editing, and rendering. AGPL-3.0; optional generation services require separate credentials.
- [open-slide](https://github.com/open-slide/open-slide) - React slide framework and agent skills for fixed-canvas authoring, preview comments, presentation mode, and HTML/PDF export.

### Product & Marketing

- [Claude SEO](https://github.com/AgriciDaniel/claude-seo) - Claude Code SEO/GEO audits with local crawling, rendering, schema checks, drift tracking, and reports. Requires Python; browser checks need Chromium, and external SEO APIs are optional.
- [Marketing Skills](https://github.com/coreyhaines31/marketingskills) - Marketing workflows for copywriting, SEO, analytics, advertising, lifecycle messaging, pricing, launches, and conversion optimization.
- [NotFair](https://github.com/nowork-studio/notfair-plugin) - SEO/GEO and marketing workflows. Local Google helpers use gcloud credentials; hosted integrations require a NotFair account. Includes a configurable update checker.
- [PM Skills](https://github.com/phuryn/pm-skills) - Product workflows for discovery, strategy, PRDs, prioritization, research, analytics, launches, and growth.

### Research

- [Academic Research Skills](https://github.com/Imbad0202/academic-research-skills) - Claude Code pipeline for literature review, writing, peer review, revision, and citation checks; a [Codex adapter](https://github.com/Imbad0202/academic-research-skills-codex) is also available. CC BY-NC 4.0.
- [last30days](https://github.com/mvanhorn/last30days-skill) - Research recent discussion, sentiment, and trends across social platforms, developer communities, GitHub, and the web.

### Security

- [clawsec](https://github.com/prompt-security/clawsec) - Security workflows for OpenClaw and Hermes, including drift checks, audits, and skill integrity verification. AGPL-3.0.
- [Cloudflare Security Audit Skill](https://github.com/cloudflare/security-audit-skill) - Security audits with parallel investigation, adversarial validation, and structured findings. Requires an agent with subagent support and Node.js for validation.
- [Codex Security](https://github.com/openai/codex-security) - Official CLI and TypeScript SDK for finding, validating, and fixing code vulnerabilities. Requires Codex authentication; some access needs Trusted Access for Cyber.
- [Reverse Engineer Anything (REA)](https://github.com/morluto/rea/tree/main/.agents/skills/reverse-engineer-anything) - Skill and local CLI/MCP for binary and JavaScript/Electron investigation with source-linked evidence. Requires Node.js; deep native analysis needs an engine such as Ghidra or IDA.
- [reverse-skill](https://github.com/zhaoxuya520/reverse-skill) - Router for reverse engineering, authorized testing, and security research. Requires Java, Node.js, Python, and local analysis tools.
- [SkillSpector](https://github.com/NVIDIA/SkillSpector) - NVIDIA scanner for vulnerabilities and malicious patterns in agent skills, with static checks, optional model analysis, and SARIF output.
- [Trail of Bits Skills](https://github.com/trailofbits/skills) - Security analysis, testing, and audit workflows for Claude Code and Codex. CC BY-SA 4.0.

### Official Platform Skills

- [Cursor Team Skills](https://github.com/cursor/plugins) - Cursor team's skills and plugins for development workflows, including strict maintainability and code-quality reviews.
- [Gemini API Skills](https://github.com/google-gemini/gemini-skills) - Skills for Gemini APIs, SDKs, Live API, and model integration.
- [Google Skills](https://github.com/google/skills) - Skills for Google products, including Google Cloud, Firebase, BigQuery, Cloud Run, and GKE.
- [Microsoft Skills](https://github.com/microsoft/skills) - Skills, MCP servers, and custom agents for Microsoft products, SDKs, and cloud services.
- [.NET Agent Skills](https://github.com/dotnet/skills) - Official .NET/C# skills and host-specific custom agents maintained by the .NET team.
- [Obsidian Skills](https://github.com/kepano/obsidian-skills) - Skills for Obsidian Markdown, properties, Bases, Canvas, CLI workflows, and web-to-Markdown extraction.
- [Supabase Agent Skills](https://github.com/supabase/agent-skills) - Postgres and backend development guidance for agents working with Supabase.
- [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills) - React, Next.js, composition, performance, and web design guidance from Vercel.

## Skill Collections

- [AAS Core](https://github.com/sickn33/agentic-awesome-skills) - Skill catalog with a local CLI/MCP for search, agent-owned selection, validation, and plan previews. Apply and recovery remain experimental.
- [Agency Agents](https://github.com/msitarzewski/agency-agents) - Cross-domain specialist role library with installation and conversion scripts for multiple coding agents.
- [Claude Code Skills & Plugins](https://github.com/alirezarezvani/claude-skills) - Cross-domain skills, plugins, and agent templates for engineering, operations, marketing, security, leadership, and research.

## Agent Systems & Harnesses

- [Agent QA](https://github.com/vostride/agent-qa) - Web/mobile QA harness with natural-language tests, persistent memory, evidence, and CLI/MCP access. Requires a model provider. FSL-1.1-ALv2 (source-available).
- [ECC](https://github.com/affaan-m/ECC) - Integrated skills, agents, hooks, memory, security checks, and cross-platform configuration for coding-agent workflows.
- [gstack](https://github.com/garrytan/gstack) - Claude Code setup with product, engineering, design, review, and QA workflows.
- [Orbi](https://github.com/orbi-build/orbi) - Self-hosted GitHub delivery loop that turns labeled Issues into independently reviewed, merged PRs and on-request releases. Runs on the Pi coding agent; requires GitHub authentication and a model provider. Sessions have unrestricted shell access; isolation depends on the deployment. AGPL-3.0.
- [SandBase Harness](https://github.com/sandbaseai/sandbase-harness) - Self-hosted agent runtime with persistent sessions, tool governance, memory, approvals, and audit/replay. Requires a model provider; isolation depends on the configured backend.
- [Sandcastle](https://github.com/mattpocock/sandcastle) - TypeScript SDK and CLI for orchestrating sandboxed coding agents across Git branches. Isolation depends on the configured backend.
- [T3 Code](https://github.com/pingdotgg/t3code) - Web, desktop, and mobile control surface for existing coding agents. Requires installed, authenticated agents; remote access exposes their file and command permissions.

## Standards & References

- [Agent Skills Specification](https://github.com/agentskills/agentskills) - Specification and documentation for portable Agent Skills.
- [Anthropic Skills Reference](https://github.com/anthropics/skills) - Anthropic's reference skills and implementation examples.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for scope, placement, and entry guidelines.

## License

[MIT](LICENSE)
