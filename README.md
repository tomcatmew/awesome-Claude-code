<a id="top"></a>
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Awesome Claude Code" src="assets/banner-light.svg" width="100%">
</picture>

# Awesome Claude Code

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![Resources](https://img.shields.io/badge/resources-556-d97757?style=flat-square)](#contents)
[![Website](https://img.shields.io/badge/website-online-2ea44f?style=flat-square)](https://tomcatmew.github.io/awesome-Claude-code/)
[![Updated](https://img.shields.io/badge/updated-2026--10--31-blue?style=flat-square)](https://github.com/tomcatmew/awesome-Claude-code/commits/main)
[![Stars](https://img.shields.io/github/stars/tomcatmew/awesome-Claude-code?style=flat-square&color=yellow)](https://github.com/tomcatmew/awesome-Claude-code/stargazers)
[![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey?style=flat-square)](LICENSE)

**English** · [简体中文](README.zh-CN.md)

**A curated, categorised and bilingual list of the best Claude Code & Claude ecosystem projects — tools, skills, subagents, plugins, MCP servers, apps, guides, videos and communities from around the world, including the Chinese community.**

### 🔎 [Browse the interactive website →](https://tomcatmew.github.io/awesome-Claude-code/)
<sub>search, filter by category, type or region, sort by stars</sub>

If this list saves you time, a ⭐ helps other Claude Code users find it. Spotted something missing? [Suggest it](https://github.com/tomcatmew/awesome-Claude-code/issues/new/choose).

</div>

> **556** resources · **41** categories · **364** GitHub repos with **9.0M** total stars · updated **2026-10-31**
>
> **Legend:** 🏆 top pick · ⭐ GitHub stars (refreshed weekly) · 🇨🇳 Chinese · 🇯🇵 Japanese · 🇰🇷 Korean · 🗄️ archived · 📘 docs · 📝 article · 🎓 course · 📺 video · 💬 community

## 🚀 Start here

New to Claude Code? These are the resources most people end up using.

| Resource | What it is | Category |
|---|---|---|
| [**Claude Code**](https://github.com/anthropics/claude-code) ⭐ 153k | Anthropic's agentic coding tool for terminal, IDE, desktop and web; repo hosts issues, changelog, plugins and example configs. | [Official Repositories](#official-repos) |
| [**Claude Code Documentation**](https://code.claude.com/docs/en/overview) | Official Claude Code docs: install, CLAUDE.md memory, skills, hooks, subagents, MCP, plugins, settings, CI, routines and every surface. | [Official Docs & Courses](#official-learning) |
| [**Best Practices for Claude Code**](https://code.claude.com/docs/en/best-practices) | Anthropic's canonical guide: give Claude verification, explore-plan-code, lean CLAUDE.md, context management, subagents, parallel sessions and fan-out. | [Official Docs & Courses](#official-learning) |
| [**Anthropic Agent Skills**](https://github.com/anthropics/skills) ⭐ 184k | Anthropic's public repository of Agent Skills, including document skills (docx, pptx, xlsx, pdf), examples and the skill-creator. | [Official Repositories](#official-repos) |
| [**Superpowers**](https://github.com/obra/superpowers) ⭐ 305k | Jesse Vincent's agentic skills framework and dev methodology: brainstorming, planning, TDD, debugging, subagent-driven development. Ships in the official plugin marketplace. | [Agent Skills](#skills) |
| [**Claude Code Plugins (Official Directory)**](https://github.com/anthropics/claude-plugins-official) ⭐ 44.6k | Anthropic-managed marketplace of curated Claude Code plugins bundling skills, subagents, hooks and MCP servers. | [Official Repositories](#official-repos) |
| [**Claude Code GitHub Action**](https://github.com/anthropics/claude-code-action) ⭐ 9.6k | Official GitHub Action that runs Claude Code on PRs and issues: responds to @claude mentions, reviews code and implements changes. | [Official Repositories](#official-repos) |
| [**ccusage**](https://github.com/ccusage/ccusage) ⭐ 19.2k | Zero-install CLI (npx ccusage) that analyzes local Claude Code JSONL logs for daily, monthly, session and 5-hour-block token usage and cost. | [Usage & Cost Monitoring](#usage-monitoring) |
| [**CC Switch**](https://github.com/farion1231/cc-switch) ⭐ 149k | Cross-platform desktop app for switching API providers and managing configs, MCP servers and skills for Claude Code, Codex, OpenCode and other CLI agents. | [Model Routers & Provider Switchers](#routers-proxies) |
| [**Spec Kit**](https://github.com/github/spec-kit) ⭐ 143k | GitHub's open-source spec-driven development toolkit: constitution, specify, plan, tasks and implement commands that work with Claude Code and other agents. | [Frameworks & Methodologies](#frameworks) |
| [**Context7**](https://github.com/upstash/context7) ⭐ 63.7k | Upstash's MCP server and platform that feeds up-to-date, version-specific library documentation and code examples into the agent's context. | [MCP Servers](#mcp-servers) |
| [**Learn Claude Code**](https://github.com/shareAI-lab/learn-claude-code) ⭐ 79.2k | Hands-on course building a nano Claude Code-like agent harness from scratch in Python, one mechanism per lesson; English, Chinese, Japanese. | [Guides & Tutorials](#guides) |

<a id="contents"></a>
## 📑 Contents

- 🏛️ [Official Resources](#official) <sub>36</sub>
  - [Official Repositories](#official-repos) <sub>13</sub> · [Official SDKs](#official-sdks) <sub>12</sub> · [Official Docs & Courses](#official-learning) <sub>11</sub>
- 🧩 [Extending Claude Code](#extending) <sub>74</sub>
  - [Agent Skills](#skills) <sub>23</sub> · [Subagents](#subagents) <sub>8</sub> · [Slash Commands](#commands) <sub>7</sub> · [Hooks](#hooks) <sub>13</sub> · [Plugins & Marketplaces](#plugins) <sub>11</sub> · [CLAUDE.md, Configs & Templates](#claude-md) <sub>12</sub>
- 🧭 [Workflows & Orchestration](#workflows) <sub>64</sub>
  - [Frameworks & Methodologies](#frameworks) <sub>19</sub> · [Multi-Agent & Parallel Sessions](#orchestration) <sub>26</sub> · [Memory & Context](#memory-context) <sub>19</sub>
- 🛠️ [Tooling](#tooling) <sub>79</sub>
  - [Usage & Cost Monitoring](#usage-monitoring) <sub>10</sub> · [Statuslines](#statusline) <sub>8</sub> · [GUI, Web & Mobile Clients](#gui-clients) <sub>10</sub> · [IDE & Editor Integrations](#ide) <sub>12</sub> · [Model Routers & Provider Switchers](#routers-proxies) <sub>12</sub> · [Sandboxing & Containers](#sandbox) <sub>9</sub> · [CI/CD & GitHub Automation](#ci-cd) <sub>6</sub> · [Logs, Transcripts & Observability](#observability) <sub>12</sub>
- 🔌 [Model Context Protocol (MCP)](#mcp) <sub>82</sub>
  - [MCP Servers](#mcp-servers) <sub>56</sub> · [MCP SDKs & Dev Tools](#mcp-dev) <sub>15</sub> · [MCP Directories & Registries](#mcp-directories) <sub>11</sub>
- 🤖 [Building with Claude](#building) <sub>73</sub>
  - [Agent SDK Projects](#agent-sdk) <sub>10</sub> · [Computer & Browser Use](#computer-use) <sub>10</sub> · [Coding Agents with Claude Support](#coding-agents) <sub>18</sub> · [Chat Clients & Apps](#chat-clients) <sub>18</sub> · [API Libraries & Dev Tools](#api-tools) <sub>17</sub>
- 📚 [Learning](#learning) <sub>70</sub>
  - [Guides & Tutorials](#guides) <sub>10</sub> · [Must-read Articles](#articles) <sub>21</sub> · [Courses](#courses) <sub>7</sub> · [Prompts & Prompt Engineering](#prompts) <sub>4</sub> · [Videos & Channels](#videos) <sub>22</sub> · [Newsletters, Podcasts & Blogs](#media) <sub>6</sub>
- 🇨🇳 [Chinese Community](#chinese) <sub>53</sub>
  - [Bilibili Videos & Creators](#cn-video) <sub>25</sub> · [Chinese Docs & Guides](#cn-guides) <sub>15</sub> · [Chinese Communities](#cn-community) <sub>5</sub> · [Domestic Models for Claude Code](#cn-providers) <sub>8</sub>
- 🌏 [Global Community](#community) <sub>25</sub>
  - [Communities & Events](#communities) <sub>13</sub> · [Japanese, Korean & Other Languages](#intl-community) <sub>8</sub> · [Related Awesome Lists](#awesome-lists) <sub>4</sub>

---

<a id="official"></a>
## 🏛️ Official Resources

_Repositories, SDKs, docs and courses published by Anthropic and the Model Context Protocol project._

<a id="official-repos"></a>
### Official Repositories

<sub>Claude Code itself, official actions, skills, cookbooks and quickstarts.</sub>

- 🏆 **[Anthropic Agent Skills](https://github.com/anthropics/skills)** ⭐ 184k — Anthropic's public repository of Agent Skills, including document skills (docx, pptx, xlsx, pdf), examples and the skill-creator.
- 🏆 **[Claude Code](https://github.com/anthropics/claude-code)** ⭐ 153k — Anthropic's agentic coding tool for terminal, IDE, desktop and web; repo hosts issues, changelog, plugins and example configs.
- 🏆 **[Claude Cookbooks](https://github.com/anthropics/claude-cookbooks)** ⭐ 53.8k — Official notebooks and recipes for building with Claude: tool use, RAG, agents, Agent SDK, Managed Agents, skills, evals, multimodal.
- 🏆 **[Claude Code Plugins (Official Directory)](https://github.com/anthropics/claude-plugins-official)** ⭐ 44.6k — Anthropic-managed marketplace of curated Claude Code plugins bundling skills, subagents, hooks and MCP servers.
- 🏆 **[Claude Code GitHub Action](https://github.com/anthropics/claude-code-action)** ⭐ 9.6k — Official GitHub Action that runs Claude Code on PRs and issues: responds to @claude mentions, reviews code and implements changes.
- [Claude for Financial Services](https://github.com/anthropics/financial-services) ⭐ 40.8k — Reference agents, skills and data connectors for finance workflows, installable as Cowork plugins or deployable via Managed Agents.
- [Knowledge Work Plugins](https://github.com/anthropics/knowledge-work-plugins) ⭐ 33.1k — Official open-source plugins for knowledge workers using Claude Cowork, covering sales, finance, legal, support, marketing and more.
- [Claude Quickstarts](https://github.com/anthropics/claude-quickstarts) ⭐ 19k — Deployable starter apps built on the Claude API, such as a customer support agent, financial analyst, computer-use and autonomous coding demos.
- [Model Context Protocol Specification](https://github.com/modelcontextprotocol/modelcontextprotocol) ⭐ 9.5k — Specification and documentation source for MCP, the open protocol Anthropic created for connecting AI apps to tools and data.
- [Defending Code Reference Harness](https://github.com/anthropics/defending-code-reference-harness) ⭐ 7.7k — Claude Code skills for threat modeling, scanning, triage and patching, plus an autonomous recon-find-verify-report-patch security harness.
- [Sandbox Runtime (srt)](https://github.com/anthropics/sandbox-runtime) ⭐ 6.6k — Lightweight OS-level sandbox enforcing filesystem and network restrictions on agents, MCP servers and commands without containers; built for Claude Code.
- [Claude Code Security Review](https://github.com/anthropics/claude-code-security-review) ⭐ 6.6k — GitHub Action that uses Claude to analyze code changes for security vulnerabilities and comment findings on pull requests.
- [Anthropic Dev Container Features](https://github.com/anthropics/devcontainer-features) ⭐ 314 — Official Dev Container Features for installing the Claude Code CLI into devcontainers and Codespaces.

<a id="official-sdks"></a>
### Official SDKs

<sub>First-party client libraries for the Claude API and the Claude Agent SDK.</sub>

- 🏆 **[MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)** ⭐ 24.7k — Official Python SDK for building Model Context Protocol servers and clients, including FastMCP-style server APIs.
- 🏆 **[Claude Agent SDK (Python)](https://github.com/anthropics/claude-agent-sdk-python)** ⭐ 8.4k — Python SDK exposing Claude Code's agent loop, built-in tools, hooks, subagents, MCP and permissions for building custom agents.
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) ⭐ 13.7k — Official TypeScript SDK for building Model Context Protocol servers and clients.
- [Anthropic Python SDK](https://github.com/anthropics/anthropic-sdk-python) ⭐ 4k — Official Python client library for the Claude API, with sync/async clients, streaming, tool use helpers and the beta tool runner.
- [Anthropic TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) ⭐ 2.2k — Official TypeScript/JavaScript client for the Claude API (@anthropic-ai/sdk), supporting Node, Deno, Bun and edge runtimes.
- [Claude Agent SDK (TypeScript)](https://github.com/anthropics/claude-agent-sdk-typescript) ⭐ 1.8k — TypeScript SDK for building production agents on the same harness, tools and context management that power Claude Code.
- [Anthropic Go SDK](https://github.com/anthropics/anthropic-sdk-go) ⭐ 1.2k — Official Go client library for the Claude API.
- [ant: Claude API CLI](https://github.com/anthropics/anthropic-cli) ⭐ 698 — Official Go-based `ant` command-line tool for the Claude Platform: send messages, manage agents, sessions and files, script every endpoint.
- [Anthropic Java SDK](https://github.com/anthropics/anthropic-sdk-java) ⭐ 386 — Official Java (and Kotlin-friendly) client library for the Claude API.
- [Anthropic Ruby SDK](https://github.com/anthropics/anthropic-sdk-ruby) ⭐ 377 — Official Ruby client library for the Claude API.
- [Anthropic C# SDK](https://github.com/anthropics/anthropic-sdk-csharp) ⭐ 339 — Official C#/.NET client library for the Claude API.
- [Anthropic PHP SDK](https://github.com/anthropics/anthropic-sdk-php) ⭐ 194 — Official PHP client library for the Claude API.

<a id="official-learning"></a>
### Official Docs & Courses

<sub>Documentation, Anthropic Academy and the engineering blog.</sub>

- 🏆 **[Claude Code Documentation](https://code.claude.com/docs/en/overview)** 📘 — Official Claude Code docs: install, CLAUDE.md memory, skills, hooks, subagents, MCP, plugins, settings, CI, routines and every surface.
- 🏆 **[Best Practices for Claude Code](https://code.claude.com/docs/en/best-practices)** 📘 — Anthropic's canonical guide: give Claude verification, explore-plan-code, lean CLAUDE.md, context management, subagents, parallel sessions and fan-out.
- 🏆 **[Agent Skills Open Standard](https://agentskills.io)** 🌐 — Specification and docs for Agent Skills, the SKILL.md folder format originated by Anthropic and adopted by many agents.
- 🏆 **[Model Context Protocol Docs](https://modelcontextprotocol.io)** 📘 — Official MCP website with concepts, architecture, server/client building guides, MCP Apps and security best practices.
- [Code with Claude Workshops](https://github.com/anthropics/cwc-workshops) ⭐ 2.2k — Materials from Anthropic's Code with Claude workshops: model selection, multi-agent systems with skills and MCP, Managed Agents, memory, evals.
- [Agent SDK Documentation](https://code.claude.com/docs/en/agent-sdk/overview) 📘 — Official guide to the Claude Agent SDK: agent loop, tools, hooks, subagents, sessions, permissions, plugins, plus Python and TypeScript references.
- [Claude Platform (API) Documentation](https://platform.claude.com/docs/en/home) 📘 — Official Claude Developer Platform docs: Messages API, models, tool use, prompt caching, structured outputs, Managed Agents, SDKs and release notes.
- [Anthropic Engineering Blog](https://www.anthropic.com/engineering) 🌐 — Anthropic's engineering blog with deep dives on agents, context engineering, tools, skills, harnesses, sandboxing, evals and postmortems.
- [claude.dev Blog](https://claude.dev) 🌐 — Anthropic developers' technical blog on building with Claude and Claude Code: tips, playbooks, harness design, effort settings, build logs.
- [Claude Status](https://status.claude.com) 🌐 — Official status page for claude.ai, Claude Console, Claude API, Claude Code and Cowork, with incident history and subscriptions.
- [Anthropic Discord](https://www.anthropic.com/discord) 💬 — Official Anthropic/Claude community Discord server for developers and users.

<div align="right"><a href="#top">↑ back to top</a></div>

---

<a id="extending"></a>
## 🧩 Extending Claude Code

_Drop-in content that teaches Claude Code new tricks: skills, subagents, slash commands, hooks, plugins and config templates._

<a id="skills"></a>
### Agent Skills

<sub>Folders of instructions, scripts and resources that Claude loads on demand.</sub>

- 🏆 **[Superpowers](https://github.com/obra/superpowers)** ⭐ 305k — Jesse Vincent's agentic skills framework and dev methodology: brainstorming, planning, TDD, debugging, subagent-driven development. Ships in the official plugin marketplace.
- 🏆 **[mattpocock/skills](https://github.com/mattpocock/skills)** ⭐ 304k — Matt Pocock's personal skills for real engineers, including grill-me, tdd, diagnosing-bugs and handoff; among the most-installed skills on skills.sh.
- 🏆 **[baoyu-skills](https://github.com/JimLiu/baoyu-skills)** 🇨🇳 ⭐ 27k — Baoyu's productivity skills for Claude Code and Codex: image generation, WeChat publishing, cover images, infographics, Xiaohongshu cards, slides and comics.
- 🏆 **[skills.sh](https://skills.sh)** 🌐 — Vercel's open Agent Skills directory and install leaderboard; browse skills and install them into Claude Code and other agents with npx skills add.
- [Ponytail](https://github.com/DietrichGebert/ponytail) ⭐ 176k — YAGNI skill and Claude Code plugin that makes your agent think like the laziest senior dev: write less code, avoid over-engineering.
- [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) ⭐ 141k — Design-intelligence skill that helps agents build professional UI/UX across multiple platforms and frameworks.
- [Caveman](https://github.com/JuliusBrussee/caveman) ⭐ 115k — Skill plus proxy that makes coding agents talk like a caveman to cut output tokens; author benchmarks about one-third fewer session tokens.
- [Agent Skills (addyosmani)](https://github.com/addyosmani/agent-skills) ⭐ 111k — Addy Osmani's production-grade engineering skills for AI coding agents: 24 lifecycle skills plus a using-agent-skills meta-skill.
- [Taste Skill](https://github.com/Leonxlnx/taste-skill) ⭐ 103k — Skills that give coding agents design taste: art direction, reference images and a browser check, steering away from generic AI-looking pages.
- [Humanizer](https://github.com/blader/humanizer) ⭐ 60.8k — Agent skill that detects and removes telltale signs of AI-generated writing from text.
- [i-have-adhd](https://github.com/ayghri/i-have-adhd) ⭐ 58.8k — Skill that stops coding agents from burying the answer, producing ADHD-friendly, answer-first output; packaged as a Claude Code plugin.
- [Marketing Skills](https://github.com/coreyhaines31/marketingskills) ⭐ 56.6k — Marketing skills for Claude Code and AI agents covering CRO, copywriting, SEO, analytics and growth engineering.
- [Scientific Agent Skills (K-Dense)](https://github.com/K-Dense-AI/scientific-agent-skills) ⭐ 54.7k — 177+ science skills and access to 100+ scientific databases that turn Claude or any agent into an AI scientist. Formerly Claude Scientific Skills.
- [Obsidian Skills](https://github.com/kepano/obsidian-skills) ⭐ 50.1k — Agent skills from Obsidian's CEO teaching agents the Obsidian CLI and open formats: Markdown, Bases and JSON Canvas.
- [vercel-labs/skills (npx skills)](https://github.com/vercel-labs/skills) ⭐ 36.6k — CLI for the open agent skills ecosystem: add, list, find, update and remove skills across Claude Code, Codex, Cursor, OpenCode and 75+ agents.
- [Awesome Agent Skills (VoltAgent)](https://github.com/VoltAgent/awesome-agent-skills) ⭐ 36.4k — Curated collection of 1,000+ agent skills from official dev teams and the community, compatible with Claude Code, Codex, Gemini CLI and Cursor.
- [Planning with Files](https://github.com/OthmanAdi/planning-with-files) ⭐ 27.7k — Persistent file-based planning skill for long-running agent tasks: plans live on disk to survive context loss, with session recovery and completion checks.
- [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) ⭐ 15.2k — Skill authoring tool that converts documentation websites, GitHub repos and PDFs into Claude skills with automatic conflict detection.
- [Trail of Bits Skills](https://github.com/trailofbits/skills) ⭐ 7.8k — Trail of Bits' Claude Code skills for security research, vulnerability detection and audit workflows.
- [Claude_skills_zh-CN](https://github.com/LeastBit/Claude_skills_zh-CN) 🇨🇳 ⭐ 599 — Chinese-localized study edition of Anthropic's official skills repo (docx/pdf/pptx/xlsx, frontend design, etc.).
- [SkillsMP](https://skillsmp.com) 🌐 — Community skills marketplace indexing millions of open-source agent skills from GitHub, searchable by category or occupation, with REST API and MCP server.
- [skill-creator (Anthropic)](https://github.com/anthropics/skills/tree/main/skills/skill-creator) — Anthropic's official meta-skill for creating, editing and evaluating new skills, bundled with scripts, references and an eval viewer.
- [Claude Code docs: Extend Claude with skills](https://code.claude.com/docs/en/skills) 📘 — Official guide to writing SKILL.md skills in Claude Code; custom slash commands are now merged into skills, while .claude/commands still works.

<a id="subagents"></a>
### Subagents

<sub>Specialised agents with their own prompt, tools and context window.</sub>

- 🏆 **[The Agency (agency-agents)](https://github.com/msitarzewski/agency-agents)** ⭐ 164k — 'complete AI agency' of 230+ specialist agent personas with defined processes and deliverables; native .md files that drop into ~/.claude/agents.
- 🏆 **[wshobson/agents](https://github.com/wshobson/agents)** ⭐ 41.7k — Multi-harness plugin marketplace with 200+ agents, 185 skills and 105 commands in 94 focused plugins for Claude Code, Codex, Cursor and more.
- 🏆 **[awesome-claude-code-subagents (VoltAgent)](https://github.com/VoltAgent/awesome-claude-code-subagents)** ⭐ 26.1k — 161+ specialized Claude Code subagents in 10 categories, installable by category via the plugin marketplace or an interactive script.
- [contains-studio/agents](https://github.com/contains-studio/agents) ⭐ 12.4k — 37 studio-style agents across engineering, design, marketing, product, testing and operations departments for rapid app development.
- [awesome-claude-agents (vijaythecoder)](https://github.com/vijaythecoder/awesome-claude-agents) ⭐ 4.4k — Orchestrated sub-agent dev team of 24 agents: orchestrators, framework specialists and universal experts that coordinate on features.
- [lst97/claude-code-sub-agents](https://github.com/lst97/claude-code-sub-agents) ⭐ 1.7k — 33 specialized subagents for full-stack development, including an agent-organizer that dispatches tasks to the right expert.
- [A List of Claude Code Agents](https://github.com/hesreallyhim/a-list-of-claude-code-agents) ⭐ 1.4k — Community-submitted index of Claude Code sub-agents from the awesome-claude-code maintainer; passively maintained and uncurated.
- [0xfurai/claude-code-subagents](https://github.com/0xfurai/claude-code-subagents) ⭐ 1k — 100+ production-ready development subagents, mostly per-language and per-framework experts.

<a id="commands"></a>
### Slash Commands

<sub>Reusable prompts invoked with /command.</sub>

- 🏆 **[SuperClaude Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework)** ⭐ 23.9k — Configuration framework adding 30 slash commands, 20 agents, cognitive personas and behavioral modes covering the dev lifecycle from brainstorming to deployment.
- [Claude Code Spec Workflow](https://github.com/Pimzino/claude-code-spec-workflow) ⭐ 3.9k — Slash-command workflows for spec-driven development (Requirements → Design → Tasks → Implementation) and structured bug fixing.
- [cc-sdd](https://github.com/gotalab/cc-sdd) 🇯🇵 ⭐ 3.7k — Kiro-style spec-driven development harness: slash-invoked /kiro-* skills that turn approved specs into long-running autonomous implementation.
- [TÂCHES CC Resources](https://github.com/glittercowboy/taches-cc-resources) ⭐ 2k — Commands and skills: meta-prompting, todo management, context handoff, /consider thinking models, and creators for skills, subagents and hooks.
- [Claude Command Suite](https://github.com/qdhenry/Claude-Command-Suite) ⭐ 1.4k — 216+ professional slash commands plus 50+ agents and 12 skills for code review, feature creation, security audits and architecture analysis.
- [Claude Code Tresor](https://github.com/alirezarezvani/claude-code-tresor) ⭐ 783 — Collection of Claude Code utilities: slash commands, autonomous skills, expert agents and prompts for development workflows.
- [Claude Code docs: Commands reference](https://code.claude.com/docs/en/commands) 📘 — Official reference for Claude Code built-in slash commands and bundled skills such as /help, /compact and /code-review.

<a id="hooks"></a>
### Hooks

<sub>Shell commands that run on Claude Code lifecycle events: guards, formatters, notifications.</sub>

- 🏆 **[Claude Code Hooks Mastery](https://github.com/disler/claude-code-hooks-mastery)** ⭐ 4k — IndyDevDan's hands-on reference implementing every hook event with uv Python scripts: TTS, logging, security guards, status lines and subagent control.
- 🏆 **[Claude Code docs: Hooks reference](https://code.claude.com/docs/en/hooks)** 📘 — Official hooks reference: 30+ lifecycle events (PreToolUse, Stop, SessionStart, PreCompact...) with command, HTTP, MCP, prompt and agent hook handlers.
- [Destructive Command Guard (dcg)](https://github.com/Dicklesworthstone/destructive_command_guard) ⭐ 6.2k — Fast Rust PreToolUse hook that blocks dangerous git and shell commands (rm -rf, hard resets, force pushes) before agents execute them.
- [peon-ping](https://github.com/PeonPing/peon-ping) ⭐ 5.1k — Warcraft III Peon (and 165+ other) voice-line notifications when Claude Code finishes, needs permission or errors; also Codex, Cursor and IDEs.
- [TDD Guard](https://github.com/nizos/tdd-guard) ⭐ 2.4k — Hook-based automated TDD enforcement for Claude Code: blocks implementation that skips failing tests or over-implements.
- [CC Safety Net](https://github.com/kenryu42/cc-safety-net) ⭐ 1.8k — Pre-execution guard hook blocking destructive git and filesystem commands and sensitive-file access before tool calls run; supports many coding CLIs.
- [Awesome Claude Code Mods](https://github.com/karanb192/awesome-claude-code-mods) ⭐ 762 — Community catalogue of public Claude Code mods (function hooks), scanned for what each can read, write, run or send over the network.
- [shanraisshan/claude-code-hooks](https://github.com/shanraisshan/claude-code-hooks) ⭐ 563 — Adds voice/sound feedback to every Claude Code hook event, tracking 30 hooks against recent Claude Code versions.
- [karanb192/claude-code-hooks](https://github.com/karanb192/claude-code-hooks) ⭐ 559 — Hook collection plus installable plugin marketplace: dangerous-command blocking, secret protection, git safety, instructions audit, cost tracking and session logs.
- [cchooks](https://github.com/GowayLee/cchooks) ⭐ 131 — Python SDK for writing Claude Code hooks: parses stdin JSON, supports all event types, simple exit-code or advanced JSON control.
- [Claude Code docs: Mods overview](https://code.claude.com/docs/en/plugins/mods/overview) 📘 — Docs for mods: plugins with in-process JavaScript/TypeScript hooks that can guard tool calls, add instant commands and draw panes in Claude Code's UI.
- [Official sample mods (claude-code-playground)](https://github.com/anthropics/claude-code-playground/tree/main/claude-code/mods) — Anthropic's sample mods: token-weather context forecast, blast-radius guard for risky commands, and replay-theater for stepping through last-turn edits.
- [hookify (official plugin)](https://github.com/anthropics/claude-code/tree/main/plugins/hookify) — Official plugin that creates custom hooks to prevent unwanted behaviors, from conversation patterns or explicit instructions.

<a id="plugins"></a>
### Plugins & Marketplaces

<sub>Installable bundles of commands, agents, skills, hooks and MCP servers.</sub>

- [Understand Anything](https://github.com/Egonex-AI/Understand-Anything) ⭐ 88.3k — Claude Code plugin using a multi-agent pipeline to turn codebases or docs into interactive, queryable knowledge graphs.
- [Compound Engineering Plugin](https://github.com/EveryInc/compound-engineering-plugin) ⭐ 25.7k — Every's official compound engineering plugin: plan, work, review, compound loops where each unit of work makes the next easier.
- [Claude Plugins Community](https://github.com/anthropics/claude-plugins-community) ⭐ 4.8k — Anthropic's read-only community marketplace mirror for Claude Code and Cowork; plugins submitted via web form and security-scanned before listing.
- [Build with Claude](https://github.com/davepoon/buildwithclaude) ⭐ 3.7k — Hub and marketplace for Claude skills, agents, commands, hooks and plugins, with a discovery site at buildwithclaude.com.
- [Claude Code Plugins Plus Skills (Tons of Skills)](https://github.com/jeremylongshore/tons-of-skills-marketplace) ⭐ 2.9k — Large marketplace of 400+ plugins and ~2,900 skills with the ccpi package manager; browsable at tonsofskills.com.
- [Awesome Claude Plugins (Composio)](https://github.com/composio-community/awesome-claude-plugins) ⭐ 2k — Curated list of Claude Code plugins that add custom commands, agents, hooks and MCP servers through the plugin system.
- [claude-plugins.dev](https://github.com/Kamalnrf/claude-plugins) ⭐ 562 — Lightweight registry and CLI to discover, install and manage public Claude plugins and agent skills; browse at claude-plugins.dev.
- [Claude Marketplace: Plugins](https://claude.com/marketplace/plugins) 🌐 — Anthropic's web catalog of 300+ plugins bundling tools, skills and integrations for Claude Code and claude.ai, e.g. Frontend Design, Superpowers, Context7.
- [Claude Code demo plugins](https://github.com/anthropics/claude-code/tree/main/plugins) — Anthropic's example plugins in the Claude Code repo: code-review, feature-dev, frontend-design, pr-review-toolkit, plugin-dev, security-guidance and more.
- [Ralph Wiggum plugin](https://github.com/anthropics/claude-code/tree/main/plugins/ralph-wiggum) — Official plugin for the 'Ralph Wiggum' loop: a Stop hook re-feeds the prompt so Claude iterates on a task until a completion promise.
- [Claude Code Marketplaces](https://claudemarketplaces.com) 🌐 — Independent directory of 2,700+ Claude Code plugin marketplaces, plus indexed skills and MCP servers.

<a id="claude-md"></a>
### CLAUDE.md, Configs & Templates

<sub>Starter kits, memory files, settings and output styles.</sub>

- 🏆 **[ECC (Everything Claude Code)](https://github.com/affaan-m/ECC)** ⭐ 289k — Massive harness config system: 71 agents, 300+ skills, hooks, rules, memory and AgentShield security scanning for Claude Code, Codex, Cursor and more.
- 🏆 **[Claude Code Templates (aitmpl)](https://github.com/davila7/claude-code-templates)** ⭐ 32.9k — CLI and aitmpl.com catalog to install agents, commands, settings, hooks, MCPs and skills, plus analytics, chat monitor and health check.
- [Claude Code Infrastructure Showcase](https://github.com/diet103/claude-code-infrastructure-showcase) ⭐ 10k — Reference examples of a real Claude Code infrastructure: skill auto-activation via hooks, specialized agents and supporting configuration.
- [Claude Code Showcase](https://github.com/ChrisWiles/claude-code-showcase) ⭐ 6.1k — Comprehensive example project configuration with hooks, skills, agents, commands and GitHub Actions workflows.
- [Agent Rules Books](https://github.com/ciembor/agent-rules-books) ⭐ 3.1k — AGENTS.md rules and skills distilled from classic engineering books (clean code, refactoring, DDD, clean architecture) for Claude Code, Codex and Cursor.
- [My Claude Code Setup (centminmod)](https://github.com/centminmod/my-claude-code-setup) ⭐ 2.7k — Shared starter template configuration and CLAUDE.md memory-bank system, regularly updated with new templates.
- [Trail of Bits Claude Code Config](https://github.com/trailofbits/claude-code-config) ⭐ 2.1k — Trail of Bits' opinionated security-minded defaults, documentation and workflows for Claude Code.
- [claude-code-settings (feiskyer)](https://github.com/feiskyer/claude-code-settings) 🇨🇳 ⭐ 1.7k — Curated settings, skills, sub-agents and config templates for Claude Code: research, image generation, GitHub automation and more.
- [Claude Code Development Kit](https://github.com/peterkrueck/Claude-Code-Development-Kit) ⭐ 1.4k — Structured workflow kit for beginner and intermediate users: tiered documentation, CLAUDE.md context, hooks and commands, with tutorial and installer.
- [Awesome CLAUDE.md](https://github.com/josix/awesome-claude-md) ⭐ 618 — Curated collection of exemplary CLAUDE.md files from public GitHub projects, with analyses, best practices and templates.
- [Claude Code docs: Output styles](https://code.claude.com/docs/en/output-styles) 📘 — Official guide to output styles: markdown files that change how Claude responds, with built-in styles and custom styles in .claude/output-styles.
- [AGENTS.md](https://agents.md) 🌐 — Open 'README for agents' instruction-file format stewarded by the Agentic AI Foundation; Claude Code can load AGENTS.md as project instructions.

<div align="right"><a href="#top">↑ back to top</a></div>

---

<a id="workflows"></a>
## 🧭 Workflows & Orchestration

_Methodologies and runners for working with Claude Code at scale: spec-driven development, parallel agents and long-term memory._

<a id="frameworks"></a>
### Frameworks & Methodologies

<sub>Opinionated systems for planning, specifying and shipping with agents.</sub>

- 🏆 **[Spec Kit](https://github.com/github/spec-kit)** ⭐ 143k — GitHub's open-source spec-driven development toolkit: constitution, specify, plan, tasks and implement commands that work with Claude Code and other agents.
- 🏆 **[BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD)** ⭐ 54.6k — Breakthrough Method for Agile AI-Driven Development: role-based agents (analyst, PM, architect, dev, QA) producing planning docs and stories across the SDLC.
- 🏆 **[GSD Core (Get Shit Done)](https://github.com/open-gsd/gsd-core)** ⭐ 10.9k — Lightweight meta-prompting, context-engineering and spec-driven development system guiding agents through a repeatable phase loop; continuation of get-shit-done.
- [OpenSpec](https://github.com/Fission-AI/OpenSpec) ⭐ 73k — Lightweight spec-driven development for AI coding assistants built around proposing, reviewing and archiving change deltas; strong fit for brownfield codebases.
- [Task Master](https://github.com/eyaltoledano/claude-task-master) ⭐ 28.3k — AI-powered task management that parses PRDs into dependency-aware tasks, usable via MCP or CLI in Claude Code, Cursor and other editors.
- [Archon](https://github.com/coleam00/Archon) ⭐ 23.8k — Workflow engine defining plan, implement, validate and PR steps in YAML so Claude Code, Codex or Pi runs are deterministic and repeatable.
- [Trellis](https://github.com/mindfold-ai/Trellis) 🇨🇳 ⭐ 15k — Team-oriented agent harness that splits giant CLAUDE.md into progressive specs, tasks, workflows and memory, injected via hooks for Claude Code, Cursor, Codex.
- [Plannotator](https://github.com/backnotprop/plannotator) ⭐ 9.6k — Visual tool to annotate and review agent plans and code diffs, sharing them with teammates and sending feedback back to the agent in one click.
- [Harness](https://github.com/revfactory/harness) ⭐ 9.3k — Claude Code meta-skill plugin that turns a plain-language request into a domain-specific agent team plus the skills and orchestration they need.
- [CCPM](https://github.com/automazeio/ccpm) ⭐ 8.4k — Project management system for Claude Code using GitHub Issues and git worktrees: PRDs become epics and tasks executed by parallel agents.
- [AI Dev Tasks](https://github.com/snarktank/ai-dev-tasks) ⭐ 7.8k — Simple markdown prompt set guiding agents from PRD creation to task lists to step-by-step, reviewable implementation.
- [Ouroboros](https://github.com/Q00/ouroboros) ⭐ 6.3k — Spec-first 'Agent OS' plugin running an interview, spec, execute, evaluate and evolve loop with staged evaluation, served over MCP.
- [Agent OS](https://github.com/buildermethods/agent-os) ⭐ 5.5k — Builder Methods' system for injecting codebase standards into agents and writing better specs for spec-driven development.
- [Spec Workflow MCP](https://github.com/Pimzino/spec-workflow-mcp) ⭐ 4.3k — MCP server providing structured spec-driven workflow tools, with a real-time web dashboard and VS Code extension for tracking progress.
- [Claude Code Harness](https://github.com/Chachamaru127/claude-code-harness) ⭐ 3.2k — Plan-work-review development harness for Claude Code that keeps specs in spec.md and tasks in Plans.md, driven by verb-based skills.
- [Advanced Context Engineering for Coding Agents](https://github.com/humanlayer/advanced-context-engineering-for-coding-agents) ⭐ 2.8k — HumanLayer's write-ups and benchmarks on context engineering for coding agents, covering research-plan-implement workflows for large codebases.
- [PRP (Product Requirement Prompts)](https://github.com/Wirasm/prp) ⭐ 2.3k — Prompts, commands and workflows for agentic engineering built on Product Requirement Prompts: context-rich specs that let Claude Code ship in one pass.
- [claude-code-cookbook](https://github.com/wasabeef/claude-code-cookbook) 🇯🇵 ⭐ 1.1k — Collection of Claude Code commands, roles and hooks settings, with docs in Japanese, English and six other languages.
- [tsumiki](https://github.com/classmethod/tsumiki) 🇯🇵 ⭐ 974 — Classmethod's AI-driven development framework, installed as a Claude Code plugin, from requirements through implementation.

<a id="orchestration"></a>
### Multi-Agent & Parallel Sessions

<sub>Run many Claude Code sessions side by side, in worktrees, in the background or as a swarm.</sub>

- 🏆 **[Orca](https://github.com/stablyai/orca)** ⭐ 106k — MIT-licensed desktop orchestrator with mobile companion for running fleets of Claude Code, Codex and other CLI agents side by side in worktrees.
- 🏆 **[Ruflo (formerly Claude Flow)](https://github.com/ruvnet/ruflo)** ⭐ 79.4k — Agent harness for deploying multi-agent swarms and autonomous workflows, with adaptive memory, federation and vector RAG; originally built around Claude Code.
- 🏆 **[Claude Squad](https://github.com/smtg-ai/claude-squad)** ⭐ 8.7k — Terminal app managing multiple Claude Code, Codex, OpenCode or Amp sessions in tmux, each isolated in its own git worktree.
- [Paperclip](https://github.com/paperclipai/paperclip) ⭐ 107k — Self-hosted platform that orchestrates Claude Code and other agents into a 'company' with org charts, ticket tracking, budgets and governance.
- [Multica](https://github.com/multica-ai/multica) ⭐ 53.8k — Self-hostable workspace where you assign issues to coding agents such as Claude Code, which report progress and blockers like teammates.
- [herdr](https://github.com/herdrdev/herdr) ⭐ 45.9k — Rust terminal runtime that keeps coding-agent sessions alive in the background, flags panes as working, blocked or idle, and lets agents control each other.
- [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) 🇰🇷 ⭐ 40.3k — Teams-first multi-agent orchestration layer for Claude Code with Team, Autopilot, Execute and Verify modes plus tmux workers for other CLIs.
- [Vibe Kanban](https://github.com/BloopAI/vibe-kanban) ⭐ 28.5k — Kanban board for planning, running and reviewing Claude Code, Codex and other coding agents, each working in an isolated worktree.
- [Paseo](https://github.com/getpaseo/paseo) ⭐ 22.1k — Apache-2.0 agentic development environment for running multiple coding agents, including Claude Code, in worktrees from desktop, mobile, web or CLI.
- [Ralph](https://github.com/snarktank/ralph) ⭐ 22.1k — Autonomous AI agent loop that runs a coding agent repeatedly with fresh context until every PRD item is complete.
- [Gas Town](https://github.com/gastownhall/gastown) ⭐ 18.5k — Steve Yegge's multi-agent workspace manager coordinating many Claude Code agents with git-backed work state, agent mail and a merge queue.
- [cc-connect](https://github.com/chenhg5/cc-connect) 🇨🇳 ⭐ 16.1k — Bridges local Claude Code and other coding agents to Feishu, DingTalk, Slack, Telegram, Discord, WeCom, LINE, QQ and other chat platforms.
- [Superset](https://github.com/superset-sh/superset) ⭐ 15.6k — Agentic IDE and terminal for orchestrating many Claude Code and Codex agents in parallel across git worktrees.
- [Aperant (formerly Auto Claude)](https://github.com/AndyMik90/Aperant) ⭐ 14.6k — Autonomous multi-session coding desktop app running up to 12 agent terminals with planning and a QA loop.
- [Agent Orchestrator](https://github.com/OrchestratorInc/agent-orchestrator) ⭐ 13.7k — Runs and supervises teams of coding agents, including Claude Code, from planning through merge across many harnesses and platforms.
- [Ralph for Claude Code](https://github.com/frankbria/ralph-claude-code) ⭐ 9.7k — Autonomous development loop for Claude Code with intelligent exit detection and safeguards against runaway iterations.
- [Worktrunk](https://github.com/max-sixty/worktrunk) ⭐ 9.5k — Rust CLI for git worktree management designed for parallel AI agent workflows.
- [Emdash](https://github.com/generalaction/emdash) ⭐ 6.1k — Open-source agentic development environment from a YC W26 team, running multiple coding agents in parallel across providers.
- [CCG Workflow](https://github.com/fengshao1227/ccg-workflow) 🇨🇳 ⭐ 5.9k — Multi-model workflow engine: Claude Code orchestrates Codex and Gemini (and others) via a single /ccg:go command, with zero-write safety for external models.
- [Background Agents](https://github.com/ColeMurray/background-agents) ⭐ 3.4k — Open-source background coding agent system: triggered agent sessions run in sandboxes and open attributed pull requests.
- [Claude Code Telegram](https://github.com/overwirehq/claude-code-telegram) ⭐ 2.8k — Telegram bot giving remote access to Claude Code with session persistence, so you can work on projects from any device.
- [MCP Agent Mail](https://github.com/Dicklesworthstone/mcp_agent_mail) ⭐ 2.2k — Asynchronous coordination layer for coding agents with identities, inboxes, threads and advisory file leases, exposed over MCP.
- [Nimbalyst (formerly Crystal)](https://github.com/nimbalyst/nimbalyst) ⭐ 2k — Open-source visual workspace for running Claude Code, Codex and OpenCode in parallel worktrees, with kanban, visual editing and an iOS companion.
- [CLI Agent Orchestrator](https://github.com/awslabs/cli-agent-orchestrator) ⭐ 1.5k — AWS Labs tool coordinating multiple coding CLIs such as Claude Code, Kiro and Codex as supervisor and workers in isolated tmux sessions.
- [CCManager](https://github.com/kbwo/ccmanager) 🇯🇵 ⭐ 1.3k — Session manager for running and switching between multiple Claude Code, Gemini CLI and Codex CLI sessions across git worktrees.
- [Conductor](https://www.conductor.build) 🌐 — Mac app from Melty Labs for running several Claude Code, Codex and Cursor agents at once in isolated workspaces, with review and merge.

<a id="memory-context"></a>
### Memory & Context

<sub>Persistent memory, codebase indexing and context engineering.</sub>

- 🏆 **[claude-mem](https://github.com/thedotmack/claude-mem)** ⭐ 103k — Persistent memory plugin that captures Claude Code session activity via hooks, compresses it with AI and injects relevant context into future sessions.
- 🏆 **[Serena](https://github.com/oraios/serena)** 🇩🇪 ⭐ 30.7k — MCP toolkit giving coding agents IDE-like semantic code retrieval and symbol-level editing via language servers; a popular Claude Code companion.
- 🏆 **[Beads](https://github.com/gastownhall/beads)** ⭐ 28.2k — Steve Yegge's git-backed issue tracker that gives coding agents durable memory of work items, dependencies and progress.
- [Graphify](https://github.com/Graphify-Labs/graphify) ⭐ 136k — Turns code, docs, SQL schemas, configs and PDFs into a queryable knowledge graph; installs a /graphify skill for Claude Code.
- [Headroom](https://github.com/headroomlabs-ai/headroom) ⭐ 77.9k — Compression layer that shrinks tool outputs, logs, files and RAG chunks before they reach the model, reducing token use for coding agents.
- [codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) ⭐ 47.5k — Code intelligence MCP server that indexes codebases into a persistent knowledge graph for fast, token-efficient structural queries.
- [code-review-graph](https://github.com/tirth8205/code-review-graph) ⭐ 32.4k — Local code-intelligence graph for MCP and CLI that helps AI tools read only the code that matters, cutting token use.
- [context-mode](https://github.com/mksglu/context-mode) ⭐ 32.3k — Claude Code plugin and MCP server that keeps bulky tool output out of context, persists session state in SQLite and restores it after compaction.
- [Repomix](https://github.com/yamadashy/repomix) 🇯🇵 ⭐ 29k — Packs an entire repository into a single AI-friendly file for feeding to LLMs, available as a CLI and MCP server.
- [Claude Obsidian](https://github.com/AgriciDaniel/claude-obsidian) ⭐ 15.8k — Obsidian plus Claude Code 'second brain' that files sources into a self-organizing, linked markdown knowledge graph.
- [Claude Context](https://github.com/zilliztech/claude-context) 🇨🇳 ⭐ 12.6k — Zilliz's semantic code-search MCP server that indexes an entire codebase into a vector database as context for coding agents.
- [Autoharness](https://github.com/tigerless-labs/autoharness) ⭐ 10.8k — Self-learning skill layer for Claude Code: hooks capture sessions and a background reflector distills, updates and prunes skills in .claude/skills.
- [Trail-Code](https://github.com/trailhq/Trail-Code) ⭐ 10.8k — Self-learning context layer pairing a tree-sitter code graph with saved team learnings, injected into Claude Code via hooks and an MCP server.
- [Engram](https://github.com/Gentleman-Programming/engram) ⭐ 7.6k — Agent-agnostic persistent memory system shipped as a single Go binary with SQLite storage and an MCP interface.
- [Continuous Claude v3](https://github.com/parcadei/Continuous-Claude-v3) ⭐ 3.9k — Context management for Claude Code using hooks, ledgers, handoffs and isolated agents to preserve state across compactions and sessions.
- [Ruler](https://github.com/intellectronica/ruler) ⭐ 3k — Applies one source of rules to all coding agents, generating and syncing CLAUDE.md, AGENTS.md and other agent instruction files.
- [Claude Supermemory](https://github.com/supermemoryai/claude-supermemory) ⭐ 2.8k — Plugin that lets Claude Code learn in real time and recall knowledge across sessions using Supermemory.
- [Claude Reflect](https://github.com/BayramAnnakov/claude-reflect) ⭐ 1.9k — Self-learning system that captures your corrections during sessions and syncs them into CLAUDE.md and AGENTS.md.
- [rulesync](https://github.com/dyoshikawa/rulesync) 🇯🇵 ⭐ 1.6k — CLI that generates and syncs rules and configuration files for Claude Code and other AI coding agents from a single source.

<div align="right"><a href="#top">↑ back to top</a></div>

---

<a id="tooling"></a>
## 🛠️ Tooling

_Everything around the CLI: usage tracking, statuslines, GUIs, editor integrations, model routing, sandboxes, CI and observability._

<a id="usage-monitoring"></a>
### Usage & Cost Monitoring

<sub>Track tokens, costs and rate-limit windows.</sub>

- 🏆 **[CodexBar](https://github.com/steipete/CodexBar)** ⭐ 22.8k — macOS menu bar app by Peter Steinberger showing usage stats and limits for Claude Code and OpenAI Codex without logging in.
- 🏆 **[ccusage](https://github.com/ccusage/ccusage)** 🇯🇵 ⭐ 19.2k — Zero-install CLI (npx ccusage) that analyzes local Claude Code JSONL logs for daily, monthly, session and 5-hour-block token usage and cost.
- [CodeBurn](https://github.com/getagentseal/codeburn) ⭐ 11.6k — Free local tool tracking token usage and cost across 37 AI coding tools, broken down by project, model and task, flagging token waste.
- [Claude Code Usage Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) ⭐ 8.8k — Real-time terminal monitor for Claude Code usage with burn-rate predictions, plan-limit warnings and session reset tracking.
- [Tokscale](https://github.com/junhoyeo/tokscale) 🇰🇷 ⭐ 5.7k — Terminal tool that tracks token usage across AI coding agents including Claude Code, with an optional global usage leaderboard.
- [Claude Usage Tracker](https://github.com/hamed-elfayome/Claude-Usage-Tracker) ⭐ 3.7k — Native Swift/SwiftUI macOS menu bar app that tracks Claude session and weekly usage limits in real time.
- [Clawdmeter](https://github.com/HermannBjorgvin/Clawdmeter) ⭐ 2.3k — ESP32-powered hardware display that shows your Claude Code usage on a small desk screen.
- [claude-usage](https://github.com/phuryn/claude-usage) ⭐ 2.3k — Local dashboard tracking Claude Code token usage, costs and session history, aimed at Pro and Max subscribers.
- [ClaudeBar](https://github.com/tddworks/ClaudeBar) ⭐ 1.6k — macOS menu bar app showing remaining quotas for Claude, Codex, Gemini, Copilot and other AI coding assistants, with burn-rate indicators.
- [Sniffly](https://github.com/chiphuyen/sniffly) ⭐ 1.3k — Claude Code dashboard by Chip Huyen showing usage stats, error analysis and shareable reports built from local logs.

<a id="statusline"></a>
### Statuslines

<sub>Custom status bars for the Claude Code terminal UI.</sub>

- 🏆 **[Claude HUD](https://github.com/jarrodwatts/claude-hud)** ⭐ 28.9k — Claude Code plugin that turns the statusline into a HUD showing context usage, active tools, running subagents and todo progress.
- 🏆 **[ccstatusline](https://github.com/sirmalloc/ccstatusline)** ⭐ 13.4k — Highly customizable Claude Code statusline with interactive TUI configurator, powerline themes and widgets for model, git, tokens, context and usage.
- [CCometixLine](https://github.com/Haleclipse/CCometixLine) 🇨🇳 ⭐ 3.5k — High-performance Rust statusline for Claude Code with git, model and context segments, TUI theme configuration and Claude Code enhancement utilities.
- [claude-powerline](https://github.com/Owloops/claude-powerline) ⭐ 1.2k — Vim-style powerline statusline for Claude Code with real-time usage and cost tracking, git integration and custom themes.
- [cc-statusline](https://github.com/chongdashu/cc-statusline) ⭐ 646 — Interactive setup tool that generates and installs an informative Claude Code statusline script showing model, directory, git, context and cost.
- [claude-code-statusline (rz1989s)](https://github.com/rz1989s/claude-code-statusline) ⭐ 480 — Feature-rich Claude Code statusline with flexible multi-line layouts, real-time cost tracking, MCP status and configurable themes.
- [claude-statusbar (claude-code-usage-bar)](https://github.com/leeguooooo/claude-code-usage-bar) ⭐ 384 — Lightweight statusline showing 5-hour and 7-day rate-limit usage with reset countdowns, context window, prompt-cache expiry and session cost.
- [Status line docs (official)](https://code.claude.com/docs/en/statusline) 📘 — Official guide to configuring Claude Code's custom status line via settings.json and scripts that receive session JSON on stdin.

<a id="gui-clients"></a>
### GUI, Web & Mobile Clients

<sub>Desktop apps, web UIs and phone clients that drive Claude Code.</sub>

- 🏆 **[AionUi](https://github.com/iOfficeAI/AionUi)** 🇨🇳 ⭐ 33.8k — Open-source cross-platform cowork desktop app that provides a GUI for Claude Code, Codex, OpenCode and 20+ other CLI agents.
- 🏆 **[Happy](https://github.com/slopus/happy)** ⭐ 24.3k — Open-source mobile and desktop client to run and control Claude Code and Codex sessions remotely, with end-to-end encryption, push notifications and voice.
- 🏆 **[opcode](https://github.com/winfunc/opcode)** ⭐ 22.4k — Desktop GUI and toolkit for Claude Code (formerly Claudia): manage sessions, create custom agents, track usage and configure MCP servers.
- 🏆 **[CloudCLI (Claude Code UI)](https://github.com/siteboon/claudecodeui)** ⭐ 14.3k — Web and mobile PWA for driving Claude Code, Codex, Cursor CLI and OpenCode remotely, with file explorer, git, shell and session management.
- 🏆 **[Claudable](https://github.com/anymorph-ai/Claudable)** ⭐ 4.1k — Open-source, Lovable-style web app builder that uses local CLI agents like Claude Code and Codex to generate and preview apps.
- [cmux](https://github.com/manaflow-ai/cmux) ⭐ 28.5k — Open-source Ghostty-based macOS terminal with vertical tabs and notifications, built for running AI coding agents like Claude Code.
- [CodePilot](https://github.com/op7418/CodePilot) 🇨🇳 ⭐ 6.5k — Multi-model AI agent desktop client (Electron + Next.js) with MCP and skills support and phone remote control, by AI blogger Guizang.
- [VibeTunnel](https://github.com/amantus-ai/vibetunnel) ⭐ 4.7k — Turns any browser into your terminal so you can monitor and command Claude Code and other agents from anywhere, including your phone.
- [Vibe Notch (formerly Claude Island)](https://github.com/farouqaldori/vibe-notch) ⭐ 2.5k — macOS notch app showing Dynamic Island-style Claude Code session status and letting you approve or deny tool permissions from an overlay.
- [claude-code-viewer](https://github.com/d-kimuson/claude-code-viewer) 🇯🇵 ⭐ 1.3k — Full-featured web client for browsing and interacting with Claude Code projects and sessions.

<a id="ide"></a>
### IDE & Editor Integrations

<sub>VS Code, JetBrains, Neovim, Emacs, Zed and more.</sub>

- 🏆 **[claudecode.nvim](https://github.com/coder/claudecode.nvim)** ⭐ 3.1k — Pure-Lua Neovim plugin implementing Claude Code's IDE protocol, giving Neovim the same diff, selection and context integration as the VS Code extension.
- 🏆 **[claude-agent-acp (Zed adapter)](https://github.com/agentclientprotocol/claude-agent-acp)** ⭐ 2.7k — Agent Client Protocol adapter that runs Claude Code via the Claude Agent SDK inside Zed and other ACP-compatible editors.
- [Claudian](https://github.com/YishenTu/claudian) ⭐ 15.8k — Obsidian plugin that embeds Claude Code (and Codex) as an AI collaborator inside your vault, able to read and edit notes.
- [jetbrains-cc-gui](https://github.com/zhukunpenglinyutong/jetbrains-cc-gui) 🇨🇳 ⭐ 7.3k — Community JetBrains IDE plugin that provides a graphical chat interface for Claude Code and Codex instead of the terminal.
- [claude-code.nvim](https://github.com/greggh/claude-code.nvim) ⭐ 2.1k — Neovim plugin that runs Claude Code in a terminal buffer with quick toggles, automatic file reload on changes and git-root awareness.
- [agent-shell](https://github.com/xenodium/agent-shell) ⭐ 2k — Native Emacs buffer interface for ACP agents including Claude Code, Codex and Gemini CLI, with familiar bindings and no terminal emulation.
- [claude-code-ide.el](https://github.com/manzaltu/claude-code-ide.el) ⭐ 1.7k — Emacs IDE integration for Claude Code over MCP, exposing diagnostics, ediff-based diff review and project context to Claude.
- [Claude Code Chat (VS Code)](https://github.com/andrepimenta/claude-code-chat) ⭐ 1.1k — VS Code extension providing a polished chat interface for Claude Code, with conversation history, checkpoints and MCP server management.
- [claude-code.el](https://github.com/stevemolitor/claude-code.el) ⭐ 747 — Emacs integration that runs Claude Code in a terminal buffer (eat or vterm) with commands for sending regions, files and errors.
- [Claude Code for VS Code (official)](https://marketplace.visualstudio.com/items?itemName=anthropic.claude-code) 🌐 — Anthropic's official VS Code extension with a native Claude Code panel, inline diffs, plan review and @-mentions; also installable in VS Code forks.
- [Claude Code JetBrains plugin (official)](https://plugins.jetbrains.com/plugin/27310-claude-code-beta-) 🌐 — Official Claude Code plugin for IntelliJ IDEA, PyCharm, WebStorm, GoLand and other JetBrains IDEs, with IDE diff viewing and selection context sharing.
- [Xcode 26.3 + Claude Agent SDK](https://www.anthropic.com/news/apple-xcode-claude-agent-sdk) 📝 — Anthropic announcement: Xcode 26.3 natively integrates the Claude Agent SDK, bringing Claude Code-style agentic coding to Xcode and exposing Xcode via MCP.

<a id="routers-proxies"></a>
### Model Routers & Provider Switchers

<sub>Point Claude Code at other backends or switch between providers and configs.</sub>

- 🏆 **[CC Switch](https://github.com/farion1231/cc-switch)** 🇨🇳 ⭐ 149k — Cross-platform desktop app for switching API providers and managing configs, MCP servers and skills for Claude Code, Codex, OpenCode and other CLI agents.
- 🏆 **[Claude Code Router](https://github.com/musistudio/claude-code-router)** 🇨🇳 ⭐ 37.9k — Routes Claude Code requests to other models and providers (DeepSeek, Gemini, OpenRouter, Ollama, etc.) with per-task routing rules and request transformers.
- [ZCF (Zero-Config Code Flow)](https://github.com/UfoMiao/zcf) 🇨🇳 ⭐ 6.1k — Zero-config CLI that sets up Claude Code and Codex in one command, including API providers, workflows, output styles, MCP services and statusline.
- [claude-code-proxy (1rgs)](https://github.com/1rgs/claude-code-proxy) ⭐ 3.8k — Proxy that lets Claude Code run on OpenAI or Gemini models by translating Anthropic API requests through LiteLLM.
- [Claude Code Local](https://github.com/nicedreamzapp/claude-code-local) ⭐ 3.4k — Runs Claude Code fully on-device on Apple Silicon via an MLX-native Anthropic-API server serving local Qwen, Gemma and Llama models.
- [claude-code-proxy (fuergaosi233)](https://github.com/fuergaosi233/claude-code-proxy) 🇨🇳 ⭐ 2.8k — Proxy that converts Claude Code's Anthropic API calls to any OpenAI-compatible API, with configurable big and small model mapping.
- [ccproxy](https://github.com/starbaser/ccproxy) ⭐ 355 — LiteLLM-based proxy for building Claude Code mods: hook any request, modify responses and route /model to custom models.
- [LLM gateway configuration (official)](https://code.claude.com/docs/en/llm-gateway) 📘 — Official guide to running Claude Code through LLM gateways such as LiteLLM for centralized authentication, usage tracking, cost control and routing.
- [LiteLLM: Claude Code Quickstart](https://docs.litellm.ai/docs/tutorials/claude_responses_api) 📘 — LiteLLM tutorial for using Claude Code through the LiteLLM proxy, including routing to non-Anthropic models and tracking spend.
- [OpenRouter: Claude Code Integration](https://openrouter.ai/docs/cookbook/coding-agents/claude-code-integration) 📘 — OpenRouter guide to pointing Claude Code at OpenRouter via ANTHROPIC_BASE_URL for access to many models with provider failover.
- [Ollama: Claude Code](https://docs.ollama.com/integrations/claude-code) 📘 — Ollama documentation for running Claude Code against local or Ollama cloud models through Ollama's Anthropic-compatible API.
- [Z.ai GLM Coding Plan for Claude Code](https://docs.z.ai/devpack/tool/claude) 📘 🇨🇳 — Z.ai guide to using GLM models in Claude Code through its Anthropic-compatible endpoint and the GLM Coding Plan.

<a id="sandbox"></a>
### Sandboxing & Containers

<sub>Isolated environments for running agents safely.</sub>

- 🏆 **[Container Use](https://github.com/dagger/container-use)** ⭐ 4.1k — Dagger's tool that gives each coding agent its own containerized environment and git branch, so multiple agents can work safely in parallel.
- [nono](https://github.com/nolabs-ai/nono) ⭐ 4.7k — Kernel-enforced agent sandbox (Landlock on Linux, Seatbelt on macOS) providing zero-trust, low-overhead isolation for coding agents like Claude Code.
- [Agent Safehouse](https://github.com/eugene1g/agent-safehouse) ⭐ 2.1k — macOS sandbox-exec wrapper that confines local AI agents like Claude Code so they can read and write only what they need.
- [VibeKit](https://github.com/superagent-ai/vibekit) ⭐ 1.9k — Runs Claude Code, Codex, Gemini or any coding agent in clean, isolated sandboxes with sensitive-data redaction and observability.
- [ClaudeBox](https://github.com/RchGrav/claudebox) ⭐ 1.2k — Docker-based Claude Code development environment with per-project isolation, prebuilt language profiles and network firewall controls.
- [Trail of Bits claude-code-devcontainer](https://github.com/trailofbits/claude-code-devcontainer) ⭐ 958 — Trail of Bits' sandboxed devcontainer for running Claude Code safely in bypass-permissions mode, built for security audits and untrusted code.
- [Code on Incus (coi)](https://github.com/coipond/coi) ⭐ 759 — Gives each AI coding agent its own isolated Incus machine with root, Docker and systemd, plus active threat detection.
- [Docker Sandboxes](https://docs.docker.com/ai/sandboxes) 📘 — Docker's microVM-based sandboxes for running coding agents like Claude Code autonomously with isolated filesystems and network policies.
- [Development containers (official)](https://code.claude.com/docs/en/devcontainer) 📘 — Official reference devcontainer with an allowlisting firewall for running Claude Code in isolation, including unattended --dangerously-skip-permissions use.

<a id="ci-cd"></a>
### CI/CD & GitHub Automation

<sub>Claude in pull requests, issues and pipelines.</sub>

- [Cyrus](https://github.com/cyrusagents/cyrus) ⭐ 873 — Self-hostable Claude Code background agent that picks up issues from Linear, Slack, GitHub and GitLab, works in isolation and opens PRs.
- [Claude Hub](https://github.com/claude-did-this/claude-hub) ⭐ 489 — Webhook service connecting Claude Code to GitHub repositories so @mentions in issues and pull requests trigger AI-powered code assistance.
- [Claude Code Gitea Action](https://github.com/markwylde/claude-code-gitea-action) ⭐ 165 — Gitea port of claude-code-action, enabling @claude-driven reviews and code changes in self-hosted Gitea repositories.
- [Claude Code Review (managed)](https://code.claude.com/docs/en/code-review) 📘 — Anthropic-managed multi-agent pull request review for GitHub on Team and Enterprise plans, posting verified, severity-ranked inline findings.
- [Claude Code GitHub Actions docs](https://code.claude.com/docs/en/github-actions) 📘 — Official guide to setting up Claude Code GitHub Actions and the Claude GitHub App, with workflow examples and Bedrock/Vertex authentication.
- [Claude Code GitLab CI/CD docs](https://code.claude.com/docs/en/gitlab-ci-cd) 📘 — Official guide to running Claude Code in GitLab CI/CD pipelines for creating merge requests, reviewing changes and handling @claude-triggered tasks.

<a id="observability"></a>
### Logs, Transcripts & Observability

<sub>Inspect, search, export and trace what your agents did.</sub>

- 🏆 **[claude-trace](https://github.com/badlogic/lemmy/tree/main/apps/claude-trace)** — Records every API request Claude Code makes, including system prompts and tool definitions, into a self-contained interactive HTML report.
- [Clawd on Desk](https://github.com/rullerzhou-afk/clawd-on-desk) ⭐ 6.5k — Pixel desktop pet that reacts in real time to Claude Code, Codex and Cursor sessions, showing whether agents are thinking, working or idle.
- [claude-devtools](https://github.com/matt1398/claude-devtools) ⭐ 4k — DevTools-style viewer for Claude Code session logs: tool calls, token usage, subagents, thinking and context-window consumption.
- [claude-tap](https://github.com/liaohch3/claude-tap) ⭐ 3.3k — Intercepts and inspects API traffic from Claude Code, Codex CLI, Gemini CLI and other coding agents for debugging and analysis.
- [Claude Code History Viewer](https://github.com/jhlee0409/claude-code-history-viewer) ⭐ 2.3k — Desktop app and web server to browse, search and analyze conversation history from Claude Code, Codex and other AI coding assistants.
- [claude-code-transcripts](https://github.com/simonw/claude-code-transcripts) ⭐ 1.7k — Simon Willison's tool for converting Claude Code sessions into detailed HTML pages and publishing them as shareable Gists.
- [Claude Code Hooks Multi-Agent Observability](https://github.com/disler/claude-code-hooks-multi-agent-observability) ⭐ 1.6k — Real-time dashboard capturing Claude Code hook events across concurrent agents, tracing tool calls and lifecycle events via a Bun server and Vue UI.
- [SpecStory](https://github.com/specstoryai/getspecstory) ⭐ 1.4k — Local-first extensions and CLI that save Claude Code and other AI assistant chat histories as searchable Markdown in your project.
- [claude-code-log](https://github.com/daaain/claude-code-log) ⭐ 1.2k — Python CLI converting Claude Code transcript JSONL files into readable HTML or Markdown, with project hierarchies, date filters and token stats.
- [Claude Code Agent Monitor](https://github.com/hoangsonww/Claude-Code-Agent-Monitor) ⭐ 1.1k — Self-hosted real-time dashboard monitoring Claude Code and Codex agent activity via hooks: live sessions, subagent trees and tool-call timelines.
- [Claude Code OTel stack](https://github.com/ColeMurray/claude-code-otel) ⭐ 513 — Docker Compose stack collecting Claude Code OpenTelemetry metrics and logs into Prometheus, Loki and Grafana dashboards for usage and cost.
- [Monitoring with OpenTelemetry (official)](https://code.claude.com/docs/en/monitoring-usage) 📘 — Official guide to exporting Claude Code metrics and events via OpenTelemetry for usage, cost and tool-activity monitoring.

<div align="right"><a href="#top">↑ back to top</a></div>

---

<a id="mcp"></a>
## 🔌 Model Context Protocol (MCP)

_The open protocol Claude uses to talk to tools and data. Popular servers, SDKs and where to find more._

<a id="mcp-servers"></a>
### MCP Servers

<sub>Widely used servers, grouped by what they connect Claude to.</sub>

**🧑‍💻 Developer tools & code**

- 🏆 **[MCP Reference Servers](https://github.com/modelcontextprotocol/servers)** ⭐ 91.6k — Official reference MCP servers (Everything, Fetch, Filesystem, Git, Memory, Sequential Thinking, Time) plus a large index of third-party servers.
- 🏆 **[GitHub MCP Server](https://github.com/github/github-mcp-server)** ⭐ 34k — GitHub's official MCP server for repos, issues, pull requests, Actions and code security; runs locally or as a hosted remote server.
- [XcodeBuildMCP (MobileBuildMCP)](https://github.com/getsentry/MobileBuildMCP) ⭐ 6.5k — MCP server and CLI that lets agents build, run, test and debug iOS and macOS projects with Xcode and simulators.
- [Atlassian MCP Server (Rovo MCP)](https://github.com/atlassian/atlassian-mcp-server) ⭐ 1.1k — Official remote MCP server connecting Jira, Confluence, Jira Service Management, Bitbucket, Compass and Loom to Claude.
- [Sentry MCP](https://github.com/getsentry/toolkit) ⭐ 947 — Sentry's official MCP server (hosted at mcp.sentry.dev) for investigating production errors, issues, traces and root causes from your agent.
- [GitLab MCP Server](https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server) 📘 — GitLab's built-in MCP server (beta) letting Claude and other AI tools access projects, issues, merge requests and pipelines.
- [Linear MCP Server](https://linear.app/docs/mcp) 📘 — Linear's official hosted remote MCP server with OAuth for finding, creating and updating issues, projects and comments.

**🌐 Browser automation**

- 🏆 **[Browser Use](https://github.com/browser-use/browser-use)** ⭐ 119k — Open-source Python library for AI browser agents that can also run as an MCP server for Claude Desktop and Claude Code.
- 🏆 **[Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp)** ⭐ 54.2k — Official Chrome DevTools MCP server letting coding agents control and inspect live Chrome: performance traces, network, console, screenshots.
- 🏆 **[Playwright MCP](https://github.com/microsoft/playwright-mcp)** ⭐ 38.6k — Microsoft's official browser automation MCP server using Playwright accessibility snapshots instead of screenshots for fast, deterministic control.
- [Chrome MCP Server (mcp-chrome)](https://github.com/hangwin/mcp-chrome) 🇨🇳 ⭐ 12.5k — Chrome extension that exposes your everyday browser, with logins and settings, as an MCP server for automation and semantic tab search.
- [agent-qa](https://vostride.com) 🌐 — MCP server for natural-language web, Android, and iOS testing, with persistent memory and validated self-improvement.

**🔍 Docs, search & web**

- 🏆 **[Context7](https://github.com/upstash/context7)** ⭐ 63.7k — Upstash's MCP server and platform that feeds up-to-date, version-specific library documentation and code examples into the agent's context.
- [GitMCP](https://github.com/idosal/git-mcp) ⭐ 8.5k — Free, open-source remote MCP server (gitmcp.io) that turns any GitHub project into a documentation source to curb code hallucinations.
- [Firecrawl MCP Server](https://github.com/firecrawl/firecrawl-mcp-server) ⭐ 7.7k — Official Firecrawl MCP server adding web scraping, crawling, search and structured extraction to Claude and other clients.
- [Exa MCP Server](https://github.com/exa-labs/exa-mcp-server) ⭐ 5.2k — Official Exa MCP server for AI-native web search, code search and page crawling; available locally or hosted.
- [arXiv MCP Server](https://github.com/blazickjp/arxiv-mcp-server) ⭐ 3.2k — Local MCP server for literature work: search arXiv, download papers, read LaTeX sections, export BibTeX and watch topics.
- [Tavily MCP](https://github.com/tavily-ai/tavily-mcp) ⭐ 2.5k — Official Tavily MCP server offering real-time web search, content extraction, site mapping and crawling for agents.
- [Brave Search MCP Server](https://github.com/brave/brave-search-mcp-server) ⭐ 1.5k — Brave's official MCP server for web, local, image, video and news search via the Brave Search API.

**🗄️ Databases & data**

- [MCP Toolbox for Databases](https://github.com/googleapis/mcp-toolbox) ⭐ 16.7k — Google's open-source MCP server for databases: BigQuery, AlloyDB, Cloud SQL, Spanner, Postgres, MySQL and more, with pooling and auth.
- [DBHub](https://github.com/bytebase/dbhub) ⭐ 3.7k — Token-efficient universal database MCP server by Bytebase for Postgres, MySQL, SQL Server, MariaDB, Oracle and SQLite.
- [Postgres MCP Pro](https://github.com/crystaldba/postgres-mcp) ⭐ 3.4k — Postgres MCP server with configurable read/write access plus index tuning, explain plans and database health analysis.
- [Supabase MCP](https://github.com/supabase/mcp) ⭐ 3k — Official Supabase MCP server to manage projects, design schemas, run SQL and migrations, and deploy edge functions from Claude.
- [EdgarTools](https://github.com/dgunning/edgartools) ⭐ 2.8k — Python library for SEC EDGAR filings (10-K, 8-K, XBRL financials, 13F) with a built-in MCP server for Claude.
- [Neon MCP Server](https://github.com/neondatabase/mcp-server-neon) ⭐ 655 — Official Neon MCP server for managing serverless Postgres projects, branches, queries and safe migrations in natural language.

**☁️ Cloud & infrastructure**

- [AWS MCP Servers](https://github.com/awslabs/mcp) ⭐ 9.8k — AWS Labs' suite of open-source MCP servers for AWS docs, APIs, CDK, EKS, serverless, cost analysis and many other services.
- [Google MCP](https://github.com/google/mcp) ⭐ 4.7k — Google's hub of official remote and open-source MCP servers for Google Cloud, Maps, Firebase, Workspace, databases and more.
- [Microsoft MCP (Azure MCP Server)](https://github.com/microsoft/mcp) ⭐ 3.8k — Microsoft's catalog of official MCP servers, including the Azure MCP Server for managing Azure resources from agents.
- [Kubernetes MCP Server](https://github.com/containers/kubernetes-mcp-server) ⭐ 2.2k — Native Go MCP server for Kubernetes and OpenShift that talks directly to the API server, no kubectl dependency.
- [Terraform MCP Server](https://github.com/hashicorp/terraform-mcp-server) ⭐ 1.6k — HashiCorp's official MCP server for Terraform Registry provider/module docs and HCP Terraform workspace operations.
- [Cloudflare API MCP Server](https://github.com/cloudflare/mcp) ⭐ 1k — Cloudflare's remote MCP server (mcp.cloudflare.com) exposing ~2,500 Cloudflare API endpoints through token-efficient Code Mode.

**🎨 Design, 3D & creative**

- 🏆 **[Blender MCP](https://github.com/ahujasid/mcp-for-blender)** ⭐ 32.4k — Connects Claude to Blender via an add-on so it can create, modify and inspect 3D scenes, materials and assets by prompt.
- 🏆 **[Figma MCP Server](https://developers.figma.com/docs/figma-mcp-server)** 📘 — Figma's official remote and desktop MCP server bringing design context, variables, components and Code Connect into coding agents.
- [Next AI Draw.io](https://github.com/DayuanJiang/next-ai-draw-io) ⭐ 36.4k — Draw and edit draw.io diagrams by chatting with AI; ships as web app, desktop app and MCP server for Claude Code.
- [Framelink Figma MCP (Figma-Context-MCP)](https://github.com/GLips/Figma-Context-MCP) ⭐ 16.1k — Community MCP server that simplifies Figma API layout data so coding agents can implement designs accurately in one shot.
- [MCP for Unity](https://github.com/CoplayDev/unity-mcp) ⭐ 15.4k — Bridge between AI assistants and the Unity Editor to manage assets, control scenes, edit scripts and automate game dev tasks.
- [Godot MCP](https://github.com/Coding-Solo/godot-mcp) ⭐ 6.4k — MCP server for the Godot engine: launch the editor, run projects, capture debug output and manipulate scenes.
- [draw.io MCP Server](https://github.com/jgraph/drawio-mcp) ⭐ 5.7k — Official draw.io MCP server from JGraph for creating and opening diagrams in the draw.io editor, including a hosted MCP App.
- [Excalidraw MCP App](https://github.com/excalidraw/excalidraw-mcp) ⭐ 5.6k — Official Excalidraw MCP App that streams editable hand-drawn diagrams directly inside Claude and other MCP Apps hosts.
- [Ableton MCP](https://github.com/ahujasid/ableton-mcp) ⭐ 3.2k — Lets Claude control Ableton Live to create tracks, load instruments, arrange clips and compose music.

**🗂️ Productivity & knowledge**

- [n8n-MCP](https://github.com/czlonkowski/n8n-mcp) ⭐ 23.1k — MCP server giving Claude deep knowledge of n8n nodes and APIs so it can design, validate and deploy n8n workflows.
- [Notion MCP Server](https://github.com/makenotion/notion-mcp-server) ⭐ 4.7k — Notion's official MCP server for searching, reading and editing pages and databases; hosted remote version recommended.
- [MCP Obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) ⭐ 4.5k — MCP server that reads, searches and edits notes in an Obsidian vault through the Local REST API community plugin.
- [Slack MCP Server](https://docs.slack.dev/ai/slack-mcp-server) 📘 — Slack's official hosted MCP server with OAuth for searching conversations, reading channels, sending messages and working with canvases.
- [Google Workspace MCP Servers](https://developers.google.com/workspace/guides/configure-mcp-servers) 📘 — Google's official remote MCP servers for Gmail, Drive, Calendar and Chat that respect each user's existing access controls.

**🖥️ Desktop & OS control**

- [Windows-MCP](https://github.com/CursorTouch/Windows-MCP) ⭐ 10.4k — Lightweight computer-use MCP server for Windows: launch apps, read UI trees, click, type and automate the desktop.
- [Desktop Commander MCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) ⭐ 10.1k — Gives Claude terminal control, process management, file system search and diff-based file editing on your local machine.
- [Mobile MCP](https://github.com/mobile-next/mobile-mcp) ⭐ 10k — Platform-agnostic MCP server for automating iOS and Android apps on emulators, simulators and real devices.
- [Peekaboo](https://github.com/openclaw/Peekaboo) ⭐ 5.4k — macOS CLI and optional MCP server that lets agents capture screenshots, analyze them and automate GUI interactions.

**🧠 Memory**

- [Knowledge Graph Memory Server](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) — Official reference server giving Claude persistent memory as a local knowledge graph of entities, relations and observations.
- [Graphiti MCP Server](https://github.com/getzep/graphiti/tree/main/mcp_server) — Zep's MCP server built on Graphiti temporal knowledge graphs, giving agents persistent, queryable long-term memory.

**🤝 Multi-model & AI**

- [PAL MCP Server (formerly Zen MCP)](https://github.com/BeehiveInnovations/pal-mcp-server) ⭐ 11.8k — Lets Claude Code consult Gemini, OpenAI, Grok, OpenRouter, Ollama and other CLIs for second opinions, consensus and code review.
- [CodexMCP](https://github.com/GuDaStudio/codexmcp) 🇨🇳 ⭐ 2k — MCP bridge letting Claude Code call Codex for implementation, debugging and review, with session persistence and parallel tasks.

**✨ Other**

- [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) 🇨🇳 ⭐ 16.6k — MCP server for Xiaohongshu (RedNote): log in, search, browse, comment and publish image or video notes from an agent.
- [IDA Pro MCP](https://github.com/mrexodia/ida-pro-mcp) ⭐ 13.2k — AI reverse-engineering assistant bridging IDA Pro with LLMs over MCP for decompilation, renaming and binary analysis.
- [mcp-feedback-enhanced](https://github.com/Minidoracat/mcp-feedback-enhanced) 🇨🇳 ⭐ 3.8k — Interactive human-in-the-loop feedback MCP server with Web UI and desktop app, letting you review and steer AI coding mid-task.

<a id="mcp-dev"></a>
### MCP SDKs & Dev Tools

<sub>Build, test, proxy and secure your own servers.</sub>

- 🏆 **[FastMCP](https://github.com/PrefectHQ/fastmcp)** ⭐ 28.2k — The fast, Pythonic framework for building MCP servers, clients and apps, with auth, proxying, composition and deployment tooling.
- [MCP for Beginners](https://github.com/microsoft/mcp-for-beginners) 🎓 ⭐ 17.5k — Microsoft's open-source MCP curriculum with hands-on lessons and examples in Python, TypeScript, Java, C#, Rust and more.
- [FastAPI-MCP](https://github.com/tadata-org/fastapi_mcp) ⭐ 12k — Expose existing FastAPI endpoints as MCP tools with minimal configuration and built-in authentication.
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) ⭐ 11.2k — Official visual testing and debugging tool for MCP servers; run with npx @modelcontextprotocol/inspector.
- [mcp-use](https://github.com/mcp-use/mcp-use) ⭐ 10.8k — Full-stack TypeScript/Python framework for building MCP servers, MCP Apps for Claude and ChatGPT, and MCP-powered agents.
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) ⭐ 8.6k — LastMile AI framework for building agents on MCP using composable workflow patterns from Anthropic's Building Effective Agents.
- [MCP Go SDK](https://github.com/modelcontextprotocol/go-sdk) ⭐ 5.3k — Official Tier 1 Go SDK for MCP servers and clients, maintained in collaboration with Google.
- [ContextForge MCP Gateway](https://github.com/IBM/mcp-context-forge) ⭐ 4.7k — IBM's open-source gateway, registry and proxy federating MCP servers, A2A agents and REST/gRPC APIs with governance and observability.
- [MCP C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) ⭐ 4.6k — Official Tier 1 C#/.NET SDK for MCP servers and clients, maintained in collaboration with Microsoft.
- [MCP Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) ⭐ 4.1k — Official Tier 1 Rust SDK (rmcp) for building MCP servers and clients on Tokio.
- [Snyk Agent Scan (formerly mcp-scan)](https://github.com/snyk/agent-scan) ⭐ 3.2k — Security scanner for MCP servers, agent configs and skills detecting tool poisoning, prompt injection and rug-pull attacks.
- [MCP Apps (ext-apps)](https://github.com/modelcontextprotocol/ext-apps) ⭐ 3k — Official spec and SDK for MCP Apps, the extension letting MCP servers render interactive UIs inside Claude, ChatGPT and other hosts.
- [MCPB (MCP Bundles)](https://github.com/modelcontextprotocol/mcpb) ⭐ 2.1k — Packaging format and CLI for one-click installable local MCP servers in Claude Desktop and other apps (formerly Desktop Extensions/DXT).
- [Official MCP SDKs (Java, Kotlin, Swift, Ruby, PHP...)](https://modelcontextprotocol.io/docs/sdk) 📘 — Index of all official MCP SDKs and their tiers, including Ruby (Tier 1), Java (Tier 2), Swift, PHP and Kotlin.
- [Docker MCP Catalog & Toolkit](https://docs.docker.com/ai/mcp-catalog-and-toolkit) 📘 — Docker's catalog of containerized MCP servers plus Toolkit and open-source MCP Gateway for securely running and connecting them to Claude.

<a id="mcp-directories"></a>
### MCP Directories & Registries

<sub>Find thousands more servers.</sub>

- 🏆 **[Awesome MCP Servers (punkpeye)](https://github.com/punkpeye/awesome-mcp-servers)** ⭐ 96.9k — Curated list of MCP servers, organized by category with language and deployment badges.
- 🏆 **[Official MCP Registry](https://registry.modelcontextprotocol.io)** 🌐 — The official, open MCP server registry with namespace-verified server.json metadata and an API that downstream registries build on.
- 🏆 **[Claude Connectors Directory](https://claude.com/connectors)** 🌐 — Anthropic's directory of Anthropic-reviewed remote MCP connectors and plugins installable across Claude, Claude Desktop and Claude Code.
- [Awesome-MCP-ZH](https://github.com/yzfly/Awesome-MCP-ZH) 🇨🇳 ⭐ 7.8k — Chinese-language curated collection of MCP resources, guides, servers and clients, including Claude MCP setup tips.
- [GitHub MCP Registry](https://github.com/mcp) 🌐 — GitHub's curated registry of MCP servers with one-click install into VS Code and other MCP clients.
- [Smithery](https://smithery.ai) 🌐 — Large MCP registry and marketplace with hosted servers, a CLI installer and managed auth connections; now part of Arcade.dev.
- [Glama MCP Servers](https://glama.ai/mcp/servers) 🌐 — Searchable MCP server directory with automated security, license and quality scoring, plus hosted gateway and inspection tools.
- [PulseMCP](https://www.pulsemcp.com) 🌐 — MCP directory and weekly newsletter tracking servers, clients and use cases with estimated usage-based popularity rankings.
- [mcp.so](https://mcp.so) 🌐 🇨🇳 — One of the largest community MCP server directories, with categories, rankings and an open-source codebase (chatmcp/mcpso).
- [MCP Market](https://mcpmarket.com) 🌐 — MCP server marketplace and directory with categories, daily leaderboards and client setup guides.
- [魔搭 ModelScope MCP 广场](https://modelscope.cn/mcp) 🌐 🇨🇳 — ModelScope's MCP marketplace: browse and host MCP servers usable from Claude and other clients, popular in China.

<div align="right"><a href="#top">↑ back to top</a></div>

---

<a id="building"></a>
## 🤖 Building with Claude

_Agents, apps and libraries built on the Claude API and the Claude Agent SDK, plus other coding agents where Claude is a first-class model._

<a id="agent-sdk"></a>
### Agent SDK Projects

<sub>Open-source agents, templates and products built on the Claude Agent SDK.</sub>

- 🏆 **[Craft Agents](https://github.com/craft-ai-agents/craft-agents-oss)** ⭐ 7.3k — Open-source desktop app and headless server from Craft for multitasking with AI agents, built on the Claude Agent SDK alongside the Pi SDK.
- [OpenClaw](https://github.com/openclaw/openclaw) ⭐ 393k — Self-hosted personal AI assistant you control from chat apps; started as 'Clawdbot' built around Claude, now multi-model.
- [Shannon](https://github.com/KeygraphHQ/shannon) ⭐ 49.4k — Autonomous AI pentester for web apps and APIs: analyzes source code, then runs real exploits to prove vulnerabilities; Anthropic is a built-in provider.
- [ArcReel](https://github.com/ArcReel/ArcReel) 🇨🇳 ⭐ 5.7k — Self-hosted, agent-driven video workspace turning novels and scripts into characters, storyboards and short videos, with cross-shot consistency and cost tracking.
- [Open Claude Cowork](https://github.com/composio-community/open-claude-cowork) ⭐ 4.3k — Open-source Claude Cowork-style desktop chat app powered by the Claude Agent SDK, automating work across 500+ SaaS apps via Composio.
- [Phantom](https://github.com/ghostwright/phantom) ⭐ 1.5k — Autonomous AI co-worker built on the Claude Agent SDK that runs on its own dedicated machine, with persistent memory, self-improvement and an MCP server.
- [Boop Agent](https://github.com/raroque/boop-agent) ⭐ 1.4k — Open-source template for a personal agent you text over iMessage, running on the Claude Agent SDK (or Codex) with memory, sub-agents and automations.
- [NekroAgent](https://github.com/KroMiose/nekro-agent) 🇨🇳 ⭐ 1.2k — Cross-platform agent framework for multi-user chat scenarios, combining Claude Code sandbox execution, workspace orchestration, long-term memory and MCP management.
- [claude-agent-server](https://github.com/dzhng/claude-agent-server) ⭐ 585 — Runs the Claude Agent SDK (Claude Code) inside a sandbox, such as an E2B template, and lets you control it remotely over WebSocket.
- [AI SDK Provider for Claude Code](https://github.com/ben-vargas/ai-sdk-provider-claude-code) ⭐ 370 — Community Vercel AI SDK provider that routes generateText/streamText calls through the Claude Agent SDK, reusing Claude Code's tools and authentication.

<a id="computer-use"></a>
### Computer & Browser Use

<sub>Agents that see the screen and drive a desktop or browser.</sub>

- 🏆 **[Anthropic Computer Use Demo](https://github.com/anthropics/claude-quickstarts/tree/main/computer-use-demo)** — Anthropic's reference implementation of Claude computer use: Dockerized Linux desktop, agent loop and Streamlit UI; works with the Claude API, Bedrock or Vertex.
- [Cua](https://github.com/trycua/cua) ⭐ 31k — Open-source computer-use infrastructure: cross-OS sandboxes and VMs, drivers and benchmarks, with an agent SDK supporting Claude computer-use models.
- [Stagehand](https://github.com/browserbase/stagehand) ⭐ 25.8k — Browserbase's SDK (TypeScript, Python, Go) for AI browser automation with act/extract/observe primitives and an agent mode that works with Claude models.
- [Skyvern](https://github.com/Skyvern-AI/skyvern) ⭐ 23.3k — Automates browser-based workflows using LLMs and computer vision; supports Claude models via Anthropic and AWS Bedrock.
- [Nanobrowser](https://github.com/nanobrowser/nanobrowser) ⭐ 14.2k — Open-source Chrome/Edge extension running AI web automation in your real, logged-in browser, with bring-your-own-key Anthropic, OpenAI and other models.
- [Agent S](https://github.com/simular-ai/Agent-S) ⭐ 12.7k — Simular's open agentic framework for GUI computer use (Agent S3, strong OSWorld results); Anthropic is a supported main-model provider.
- [Magnitude](https://github.com/magnitudedev/browser-agent) ⭐ 4.1k — Open-source, vision-first browser agent that acts on pixels rather than the DOM; recommends Claude Sonnet for best performance.
- [agent.exe](https://github.com/corbt/agent.exe) ⭐ 3.5k — Minimal Electron app that lets Claude computer use drive your own desktop directly instead of a sandboxed VM.
- [Computer Use OOTB](https://github.com/showlab/computer_use_ootb) ⭐ 2k — Out-of-the-box GUI agent for Windows and macOS from NUS Show Lab, running Claude computer use locally without a Docker VM.
- [mac_computer_use](https://github.com/deedy/mac_computer_use) ⭐ 890 — Fork of Anthropic's computer-use demo that runs natively on macOS, letting Claude control a Mac without a Docker Linux VM.

<a id="coding-agents"></a>
### Coding Agents with Claude Support

<sub>Other open-source coding agents and IDE extensions commonly run on Claude.</sub>

- 🏆 **[OpenCode](https://github.com/anomalyco/opencode)** ⭐ 222k — Open-source coding agent (terminal TUI, desktop, IDE) from the SST/Anomaly team; provider-agnostic with strong Claude support.
- 🏆 **[OpenHands](https://github.com/OpenHands/OpenHands)** ⭐ 91.9k — Open platform for autonomous software-development agents (formerly OpenDevin) with CLI, GUI, cloud and SDK; Claude models are among its recommended LLMs.
- 🏆 **[Cline](https://github.com/cline/cline)** ⭐ 70.9k — Autonomous coding agent for VS Code, JetBrains and the terminal, originally 'Claude Dev'; Claude is a first-class model, with plan/act modes and MCP.
- 🏆 **[Aider](https://github.com/Aider-AI/aider)** ⭐ 49.8k — AI pair-programming CLI that edits your git repo directly; long a top performer with Claude, and home of the Aider LLM leaderboards.
- [Pi](https://github.com/earendil-works/pi) ⭐ 118k — Minimal, extensible terminal coding agent plus agent toolkit (unified LLM API, agent loop, TUI) with Anthropic among its built-in providers.
- [Zed](https://github.com/zed-industries/zed) ⭐ 92.2k — High-performance Rust code editor with a built-in agent panel; runs Claude via API or Claude Code through the Agent Client Protocol.
- [goose](https://github.com/aaif-goose/goose) ⭐ 55.7k — Extensible open-source on-machine AI agent (desktop and CLI) that installs, edits, runs and tests code; supports Anthropic and Claude subscriptions via ACP.
- [Continue](https://github.com/continuedev/continue) ⭐ 36.3k — Open-source coding agent for VS Code, JetBrains and CI checks, with configurable models and rules; Claude is a popular first-class choice.
- [Crush](https://github.com/charmbracelet/crush) ⭐ 28.8k — Charm's glamorous terminal coding agent with LSP integration, MCP and multi-session support; works with Anthropic Claude among many providers.
- [Kilo Code](https://github.com/Kilo-Org/kilocode) ⭐ 27.8k — Open-source agentic engineering platform for VS Code, JetBrains and CLI, descended from Cline/Roo Code, with hundreds of models including Claude.
- [Dyad](https://github.com/dyad-sh/dyad) ⭐ 22.1k — Local, open-source AI app builder (v0/Lovable/Bolt alternative) that runs on your machine with your own API keys for Claude and other models.
- [avante.nvim](https://github.com/avante-corp/avante.nvim) 🇨🇳 ⭐ 18.2k — Neovim plugin emulating the Cursor AI IDE experience with chat, diffs and agentic edits applied in-buffer; Claude is the default provider.
- [bolt.new](https://github.com/stackblitz/bolt.new) ⭐ 16.6k — Open-source core of StackBlitz's bolt.new: prompt, run, edit and deploy full-stack apps in the browser via WebContainers, originally powered by Claude.
- [Claude Engineer](https://github.com/Doriandarko/claude-engineer) ⭐ 11.2k — Early, influential Claude-powered interactive CLI that creates and edits files, runs code and can even write new tools for itself.
- [CodeCompanion.nvim](https://github.com/olimorris/codecompanion.nvim) ⭐ 6.9k — AI coding plugin for Neovim with chat, inline edits and agents; supports Anthropic natively and Claude Code via the Agent Client Protocol.
- [Fragments by E2B](https://github.com/e2b-dev/fragments) ⭐ 6.4k — Open-source Next.js template for Claude Artifacts-style apps fully generated by AI, executing code safely in E2B sandboxes; supports Anthropic and other models.
- [Kode](https://github.com/shareAI-lab/Kode-CLI) 🇨🇳 ⭐ 5.2k — Open-source Claude Code-style terminal agent supporting 20+ model providers, compatible with CLAUDE.md files and .claude directories.
- [gptel](https://github.com/karthink/gptel) ⭐ 3.6k — Simple, extensible LLM client for Emacs that works in any buffer, with first-class Anthropic Claude support including tool use.

<a id="chat-clients"></a>
### Chat Clients & Apps

<sub>Desktop, web and CLI apps for chatting with Claude.</sub>

- 🏆 **[LobeHub](https://github.com/lobehub/lobehub)** 🇨🇳 ⭐ 83.5k — Open-source AI agent workspace (formerly LobeChat) with multi-provider chat, agent teams, MCP plugins and knowledge bases; supports Claude natively.
- 🏆 **[Cherry Studio](https://github.com/CherryHQ/cherry-studio)** 🇨🇳 ⭐ 53k — Cross-platform desktop AI productivity studio with unified access to Claude and other frontier models, autonomous agents, MCP and 300+ assistants.
- 🏆 **[LibreChat](https://github.com/LibreChat-AI/LibreChat)** ⭐ 46.3k — Self-hostable multi-provider ChatGPT-style interface with agents, MCP, skills and artifacts; native Anthropic endpoint for Claude, plus Bedrock and Vertex.
- [Open WebUI](https://github.com/open-webui/open-webui) ⭐ 157k — Self-hosted AI interface; connects to Claude via Anthropic's OpenAI-compatible endpoint, or pipe functions for full Messages API features.
- [NextChat](https://github.com/ChatGPTNextWeb/NextChat) 🇨🇳 ⭐ 88.9k — Lightweight cross-platform AI chat app (web, desktop, mobile) with one-click deployment; supports Claude alongside GPT, Gemini and others.
- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) ⭐ 67.6k — All-in-one, local-first AI app for chatting with documents, RAG and agent workflows; Anthropic Claude is a supported LLM provider.
- [Jan](https://github.com/janhq/jan) ⭐ 45.1k — Open-source, offline-first ChatGPT alternative for running local models, with optional remote providers including Anthropic Claude.
- [Chatbox](https://github.com/chatboxai/chatbox) 🇨🇳 ⭐ 42.1k — Desktop and mobile AI client supporting Claude, GPT, Gemini and local models, with knowledge bases, MCP tools and image generation.
- [Khoj](https://github.com/khoj-ai/khoj) ⭐ 37.8k — Self-hostable AI second brain that answers from the web or your documents, with custom agents and research mode; supports Claude models.
- [AIChat](https://github.com/sigoden/aichat) ⭐ 10.5k — All-in-one Rust LLM CLI with shell assistant, chat REPL, RAG, tools and agents; supports Claude among 20+ providers.
- [big-AGI](https://github.com/enricoros/big-AGI) ⭐ 7.2k — Power-user AI suite with multi-model 'Beam' comparisons, personas and voice, featuring first-class Anthropic Claude support.
- [DeepChat](https://github.com/ThinkInAIXYZ/deepchat) 🇨🇳 ⭐ 6.4k — Open-source desktop AI assistant connecting Claude, GPT, Gemini, DeepSeek and local models, with MCP tool calling and multi-window chats.
- [Claude Desktop for Linux (claude-desktop-debian)](https://github.com/aaddrick/claude-desktop-debian) ⭐ 5.5k — Unofficial Linux packaging of Claude Desktop, now repackaging Anthropic's official beta .deb into RPM, AppImage, AUR and Nix builds with Linux fixes.
- [5ire](https://github.com/nanbingxyz/5ire) 🇨🇳 ⭐ 5.4k — Cross-platform desktop AI assistant and MCP client compatible with major providers including Anthropic, with a local knowledge base and prompt library.
- [DeepReasoning](https://github.com/winfunc/deepreasoning) ⭐ 5.4k — High-performance Rust inference API and chat UI that feeds DeepSeek R1's chain-of-thought reasoning into Claude for the final answer.
- [Witsy](https://github.com/Kochava-Studios/witsy) ⭐ 2k — Desktop AI assistant and universal MCP client with bring-your-own-key access to Claude and other models, prompt-anywhere commands and agents.
- [llm-anthropic](https://github.com/simonw/llm-anthropic) ⭐ 252 — Plugin for Simon Willison's LLM command-line tool adding Claude models, extended thinking and server-side tools such as web search and code execution.
- [Claude for Raycast](https://github.com/raycast/extensions/tree/main/extensions/claude) — Raycast extension for asking Claude from the macOS command bar with your Anthropic API key: model picker, continued conversations, saved answers, selected-text input.

<a id="api-tools"></a>
### API Libraries & Dev Tools

<sub>Community SDKs, framework integrations, evals and helpers for the Claude API.</sub>

- 🏆 **[promptfoo](https://github.com/promptfoo/promptfoo)** ⭐ 26.4k — Open-source CLI for testing prompts, agents and RAG, plus AI red-teaming; ships first-class Anthropic and Claude Agent SDK providers.
- 🏆 **[Vercel AI SDK - Anthropic Provider](https://ai-sdk.dev/providers/ai-sdk-providers/anthropic)** 📘 — @ai-sdk/anthropic: TypeScript Claude provider for the Vercel AI SDK, covering prompt caching, thinking, batches, MCP connectors and server tools like web search.
- [LiteLLM](https://github.com/BerriAI/litellm) ⭐ 62k — AI gateway and Python SDK calling 100+ LLM APIs in OpenAI format, with Anthropic support, cost tracking, prompt-caching injection and load balancing.
- [aisuite](https://github.com/andrewyng/aisuite) ⭐ 16.4k — Andrew Ng's simple, unified Python interface to many generative AI providers, letting you swap Claude and other models by changing one string.
- [Instructor](https://github.com/567-labs/instructor) ⭐ 14.1k — Structured outputs for LLMs via Pydantic models with validation and retries; supports Anthropic Claude through tool-based extraction.
- [Rig](https://github.com/0xPlaygrounds/rig) ⭐ 9k — Modular Rust library for building LLM applications and agents, with an Anthropic Claude provider alongside OpenAI, Gemini and others.
- [RubyLLM](https://github.com/crmne/ruby_llm) ⭐ 4.5k — Elegant Ruby AI framework offering one API for chat, tools, vision, embeddings and Rails integration across Claude and other providers.
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) ⭐ 3.1k — UK AI Security Institute's framework for LLM evaluations, covering benchmarks, agentic tasks and sandboxes, with a native Anthropic provider.
- [Prism](https://github.com/prism-php/prism) ⭐ 2.4k — Unified Laravel/PHP interface for working with LLMs, including a full-featured Anthropic provider for Claude with tools and structured output.
- [tokencost](https://github.com/AgentOps-AI/tokencost) ⭐ 2k — Token counting and price estimation for 400+ LLMs, using Anthropic's token-counting API for newer Claude models.
- [Elixir LangChain](https://github.com/brainlid/langchain) ⭐ 1.2k — LangChain-style framework for integrating LLMs into Elixir apps, with ChatAnthropic support for Claude, extended thinking and AWS Bedrock.
- [ellmer](https://github.com/tidyverse/ellmer) ⭐ 620 — Tidyverse R package for calling LLM APIs, with chat_anthropic() for Claude, tool calling, structured data extraction and streaming.
- [SwiftAnthropic](https://github.com/jamesrochabrun/SwiftAnthropic) ⭐ 253 — Open-source Swift package for the Anthropic API, letting iOS and macOS apps use Claude messages, streaming, vision and tool use.
- [Anthropic.SDK (.NET)](https://github.com/tghamm/Anthropic.SDK) ⭐ 222 — Unofficial C#/.NET SDK for the Claude API with streaming, tool calling, batches and Microsoft.Extensions.AI integration.
- [LangChain - ChatAnthropic](https://docs.langchain.com/oss/python/integrations/chat/anthropic) 📘 — langchain-anthropic integration: ChatAnthropic with tool calling, structured output, PDF/image input, extended thinking, prompt caching and Claude's built-in tools.
- [LlamaIndex - Anthropic LLM](https://developers.llamaindex.ai/python/framework/integrations/llm/anthropic) 📘 — llama-index-llms-anthropic: use Claude in LlamaIndex with streaming, multimodal input, prompt caching, tool calling, structured prediction and citations.
- [anthropic_sdk_dart](https://pub.dev/packages/anthropic_sdk_dart) 🌐 — Pure Dart/Flutter client for the Anthropic API with streaming and tool use, from the langchain_dart / ai_clients_dart family.

<div align="right"><a href="#top">↑ back to top</a></div>

---

<a id="learning"></a>
## 📚 Learning

_Guides, must-read articles, courses, prompts, videos and newsletters._

<a id="guides"></a>
### Guides & Tutorials

<sub>Community handbooks, best practices and tip collections.</sub>

- 🏆 **[Learn Claude Code](https://github.com/shareAI-lab/learn-claude-code)** 🇨🇳 ⭐ 79.2k — Hands-on course building a nano Claude Code-like agent harness from scratch in Python, one mechanism per lesson; English, Chinese, Japanese.
- 🏆 **[Claude Code Best Practice (shanraisshan)](https://github.com/shanraisshan/claude-code-best-practice)** ⭐ 68.1k — Collection of Claude Code best practices, from prompting and CLAUDE.md to skills, subagents, hooks and debugging.
- [Claude HowTo](https://github.com/luongnv89/claude-howto) ⭐ 45.2k — Visual, example-driven Claude Code guide with a level-based learning path and copy-paste templates for commands, skills, hooks and MCP.
- [Context Engineering Intro](https://github.com/coleam00/context-engineering-intro) ⭐ 13.9k — Template and walkthrough for context engineering with Claude Code: INITIAL.md specs, PRP generation, examples and CLAUDE.md rules.
- [Claude Code Tips (ykdojo)](https://github.com/ykdojo/claude-code-tips) ⭐ 10.3k — 45+ practical Claude Code tips from basics to advanced, including a custom status line script and running Claude Code in containers.
- [Claude Code Ultimate Guide](https://github.com/FlorianBruniaux/claude-code-ultimate-guide) ⭐ 6.3k — Very comprehensive Claude Code guide covering agentic workflows, hooks, skills, MCP, quizzes and production-ready templates.
- [Claude Code Guide (zebbern)](https://github.com/zebbern/claude-code-guide) ⭐ 4.7k — Community guide to Claude Code setup, commands, workflows, agents, skills and tips, from beginner to power user.
- [claude-code-mastering](https://github.com/revfactory/claude-code-mastering) 🇰🇷 ⭐ 774 — Korean-language book-style guide to mastering Claude Code, published openly on GitHub Pages.
- [cc101](https://github.com/fivetaku/cc101) 🇰🇷 ⭐ 302 — Korean beginner guide to Claude Code (with English content), built as a Next.js site; also localized to Japanese.
- [ClaudeLog](https://claudelog.com) 🌐 — Independent community knowledge base of Claude Code docs, tutorials, mechanics and best practices drawn from real-world usage.

<a id="articles"></a>
### Must-read Articles

<sub>Long-form posts that shaped how people use Claude Code.</sub>

- 🏆 **[Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents)** 📝 — Anthropic's foundational essay on agent design: workflows vs agents, prompt chaining, routing, orchestrator-workers, evaluator-optimizer; favor simplicity.
- 🏆 **[Effective Context Engineering for AI Agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)** 📝 — Anthropic on curating the smallest high-signal context for agents: system prompts, tools, just-in-time retrieval, compaction, notes and subagents.
- 🏆 **[Ralph Wiggum as a "Software Engineer" (Geoffrey Huntley)](https://ghuntley.com/ralph)** 📝 — Origin of the "Ralph" technique: run a coding agent in a simple loop, one task per iteration, tuning prompts and validation.
- 🏆 **[How Claude Code is built (The Pragmatic Engineer)](https://newsletter.pragmaticengineer.com/p/how-claude-code-is-built)** 📝 · _by Gergely Orosz_ — Deep dive into Claude Code's origins, TypeScript/React/Ink/Bun stack, permissions system and shipping pace, based on team interviews.
- [Writing Effective Tools for Agents — with Agents](https://www.anthropic.com/engineering/writing-tools-for-agents) 📝 — How to design, evaluate and iteratively improve agent tools and MCP servers, using Claude itself to optimize tool descriptions.
- [Equipping Agents for the Real World with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) 📝 — Engineering announcement explaining Agent Skills: SKILL.md folders, progressive disclosure, bundled code, and how to author skills.
- [Effective Harnesses for Long-Running Agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) 📝 — Anthropic's patterns for agents working across many context windows: initializer agents, progress files, feature lists, incremental verified work.
- [Code Execution with MCP](https://www.anthropic.com/engineering/code-execution-with-mcp) 📝 — Presenting MCP tools as code APIs so agents write code to call them, cutting token usage and improving efficiency.
- [Building Agents with the Claude Agent SDK](https://claude.com/resources/articles/building-agents-with-the-claude-agent-sdk) 📝 — Why the Claude Code SDK became the Agent SDK, its gather-context/act/verify loop, and best practices for building agents.
- [A Harness for Every Task: Dynamic Workflows in Claude Code](https://claude.dev/blog/a-harness-for-every-task-dynamic-workflows-in-claude-code) 📝 — Claude Code team on dynamic workflows that spawn and coordinate subagents, with six patterns like fan-out, adversarial verification and tournaments.
- [How Anthropic Teams Use Claude Code](https://claude.com/resources/articles/how-anthropic-teams-use-claude-code) 📝 — Case study of how Anthropic's engineering, security, data, legal, marketing and other teams use Claude Code day to day.
- [Agentic Coding Recommendations (Armin Ronacher)](https://lucumr.pocoo.org/2025/6/12/agentic-coding) 📝 — Flask creator Armin Ronacher's practical Claude Code workflow: tool design, logging, language choice, simplicity and parallelizing agent work.
- [How I Use Every Claude Code Feature (Shrivu Shankar)](https://blog.sshh.io/p/how-i-use-every-claude-code-feature) 📝 — Reference-style tour of nearly every Claude Code feature — CLAUDE.md, context, hooks, skills, MCP, SDK, GitHub Actions — and which to avoid.
- [Writing a Good CLAUDE.md (HumanLayer)](https://www.humanlayer.dev/blog/writing-a-good-claude-md) 📝 — Widely cited guide: keep CLAUDE.md short and universal, point to docs instead of embedding them, leave style to linters.
- [What Makes Claude Code So Damn Good (MinusX)](https://minusx.ai/blog/decoding-claude-code) 📝 — Analysis of Claude Code's design — single control loop, small helper models, detailed prompts, LLM search over RAG, self-managed todos.
- [How I Use Claude Code: Separation of planning and execution](https://boristane.com/blog/how-i-use-claude-code) 📝 · _by Boris Tane_ — Workflow post: research the codebase, write a markdown plan, iterate on it with annotations, then let Claude implement.
- [The Emperor Has No Clothes: How to Code Claude Code in 200 Lines of Code](https://www.mihaileric.com/The-Emperor-Has-No-Clothes) 📝 · _by Mihail Eric_ — Builds a minimal Claude Code-style coding agent in about 200 lines of Python to demystify how agent loops work.
- [How I Use Claude Code to Ship Like a Team of Five](https://every.to/source-code/how-i-use-claude-code-to-ship-like-a-team-of-five-6f23f136-52ab-455f-a997-101c071613aa) 📝 · _by Kieran Klaassen (Every)_ — Every's Cora lead describes directing multiple Claude Code agents with the compound engineering approach.
- [First attempt will be 95% garbage: A staff engineer's 6-week journey with Claude Code](https://www.sanity.io/blog/first-attempt-will-be-95-garbage) 📝 · _by Vincent Quigley_ — Sanity staff engineer's candid account of using Claude Code in production: iterative feedback, careful review and shared context.
- [6 weeks of Claude Code](https://blog.puzzmo.com/posts/2025/07/30/six-weeks-of-claude-code) 📝 · _by Orta Therox (Puzzmo)_ — Puzzmo engineering lead's widely discussed retrospective on how six weeks of Claude Code changed a small team's output.
- [Using Claude Code to modernize a 25-year-old kernel driver](https://dmitrybrant.com/2025/09/07/using-claude-code-to-modernize-a-25-year-old-kernel-driver) 📝 · _by Dmitry Brant_ — Case study of porting the legacy ftape Linux driver to modern kernels with Claude Code over two evenings.

<a id="courses"></a>
### Courses

<sub>Structured courses from Anthropic, partners and the community.</sub>

- 🏆 **[Anthropic Academy (Claude Academy)](https://academy.claude.com)** 🎓 — Anthropic's free self-paced learning platform with courses on Claude, Claude Code, Cowork, MCP, skills, subagents, the API and AI fluency.
- [Anthropic Courses (archived)](https://github.com/anthropics/courses) ⭐ 22.9k 🗄️ archived — Anthropic's original notebook courses: API fundamentals, prompt engineering, real-world prompting, prompt evaluations and tool use.
- [Claude Code 101](https://academy.claude.com/courses/claude-code-101) 🎓 — Anthropic Academy's beginner course introducing Claude Code fundamentals and everyday workflows.
- [Claude Code in Action](https://academy.claude.com/courses/claude-code-in-action) 🎓 — Free official Anthropic Academy course on applying Claude Code to real-world development workflows.
- [Building with the Claude API](https://academy.claude.com/courses/building-with-the-claude-api) 🎓 — Anthropic Academy course on building applications with the Claude API, from first requests to advanced features.
- [Claude Code: A Highly Agentic Coding Assistant (DeepLearning.AI)](https://www.deeplearning.ai/courses/claude-code-a-highly-agentic-coding-assistant) 🎓 — DeepLearning.AI short course with Anthropic, taught by Elie Schoppik: CLAUDE.md, worktrees, hooks, GitHub and MCP across three projects.
- [Agent Skills with Anthropic (DeepLearning.AI)](https://www.deeplearning.ai/short-courses/agent-skills-with-anthropic) 🎓 — DeepLearning.AI short course on building SKILL.md skills and combining them with MCP and subagents across Claude apps, Code, API and SDK.

<a id="prompts"></a>
### Prompts & Prompt Engineering

<sub>Prompt libraries and techniques that work well with Claude.</sub>

- 🏆 **[Prompt Engineering Interactive Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial)** ⭐ 38.8k — Anthropic's interactive, exercise-filled notebook tutorial teaching prompt engineering fundamentals for Claude.
- [Awesome Claude Prompts](https://github.com/langgptai/awesome-claude-prompts) 🇨🇳 ⭐ 5.5k — Curated collection of Claude prompts and prompting techniques for getting better results from Claude.
- [Claude Prompting Best Practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) 📘 — Anthropic's living prompt-engineering reference for current Claude models: clarity, examples, XML, thinking, tool use, agentic systems, migration.
- [Claude System Prompts (Release Notes)](https://platform.claude.com/docs/en/release-notes/system-prompts/overview) 📘 — Anthropic's officially published claude.ai and app system prompts for each Claude model, with dated updates.

<a id="videos"></a>
### Videos & Channels

<sub>Talks, tutorials and YouTube channels.</sub>

- 🏆 **[Anthropic (YouTube)](https://www.youtube.com/@anthropic-ai)** 📡 · _by Anthropic_ — Anthropic's official channel: launch demos, Code w/ Claude conference sessions, and talks from the Claude Code team.
- 🏆 **[IndyDevDan](https://www.youtube.com/@indydevdan)** 📡 · _by IndyDevDan_ — Advanced agentic-engineering channel covering Claude Code hooks, subagents, CLAUDE.md, MCP and multi-agent workflows.
- 🏆 **[Claude Code best practices | Code w/ Claude](https://www.youtube.com/watch?v=gv0WHhKelSE)** 📺 · _by Anthropic_ — Official Code w/ Claude 2025 session (about 26 min) on getting the most out of Claude Code in daily development.
- [Claude (YouTube)](https://www.youtube.com/@claude) 📡 · _by Anthropic_ — Official Claude product channel with short Claude Code explainers and workflow videos such as "How Claude Code Works".
- [Cole Medin](https://www.youtube.com/@ColeMedin) 📡 · _by Cole Medin_ — AI agent builder channel on context engineering and plan-implement-validate workflows with Claude Code and other coding agents.
- [AI Jason](https://www.youtube.com/@AIJasonZ) 📡 · _by Jason Zhou_ — AI-builder channel with practical Claude Code tips, agent setups and design-workflow experiments.
- [AI Engineer](https://www.youtube.com/@aiDotEngineer) 📡 · _by AI Engineer_ — Conference channel of AI Engineer Summit and World's Fair, hosting talks and workshops by the Claude Code team.
- [Nate Herk | AI Automation](https://www.youtube.com/@nateherk) 📡 · _by Nate Herk_ — Automation channel with heavily viewed Claude Code courses, skill roundups and tips videos for beginners to production use.
- [Nick Saraev](https://www.youtube.com/@nicksaraev) 📡 · _by Nick Saraev_ — Channel known for long-form Claude Code courses on agent teams, git worktrees and building revenue-generating AI systems.
- [Matt Pocock](https://www.youtube.com/@mattpocockuk) 📡 · _by Matt Pocock_ — TypeScript educator's channel with concise Claude Code skills, CLAUDE.md and workflow tips for developers.
- [Net Ninja](https://www.youtube.com/@NetNinja) 📡 · _by Shaun Pelling_ — Coding-education channel with a free multi-part Claude Code tutorial series: setup, CLAUDE.md, MCP servers, subagents, GitHub.
- [Mastering Claude Code in 30 minutes](https://www.youtube.com/watch?v=6eBSHbLKuN0) 📺 · _by Boris Cherny (Anthropic)_ — Boris Cherny, creator of Claude Code, walks through his daily workflow: codebase Q&A, planning, verification, CLAUDE.md and claude -p.
- [Vibe coding in prod | Code w/ Claude](https://www.youtube.com/watch?v=fHWFF_pnqDk) 📺 · _by Anthropic_ — Anthropic talk on responsibly shipping agent-written code to production: choosing leaf nodes, verifiability and reviewing what matters.
- [How Claude Code Works](https://www.youtube.com/watch?v=6bs5b4FltCU) 📺 · _by Claude (Anthropic)_ — Official explainer of Claude Code's agent loop, tools and context handling; one of the most-viewed official Claude Code videos.
- [The Explore → Plan → Code → Commit workflow in Claude Code](https://www.youtube.com/watch?v=xJQuF02NAK8) 📺 · _by Claude (Anthropic)_ — Official short walkthrough of the recommended explore, plan, code and commit loop for working with Claude Code.
- [Claude Code & the evolution of agentic coding — Boris Cherny](https://www.youtube.com/watch?v=Lue8K2jqfKk) 📺 · _by Boris Cherny (Anthropic)_ — AI Engineer World's Fair 2025 keynote by Claude Code's creator on how agentic coding evolved and where it is heading.
- [Claude Agent SDK (Full Workshop) — Thariq Shihipar](https://www.youtube.com/watch?v=TqC1qOfiVcQ) 📺 · _by Thariq Shihipar (Anthropic)_ — Nearly two-hour AI Engineer workshop building an agent harness from scratch with the Claude Agent SDK, bash tool and file-system context.
- [Claude Fable, Claude Tag, and Anthropic's Culture — Cat Wu & Thariq Shihipar ft Simon Willison](https://www.youtube.com/watch?v=uU5Gv2h8-9g) 📺 · _by Cat Wu, Thariq Shihipar, Simon Willison_ — AI Engineer World's Fair 2026 fireside chat with Claude Code product and engineering leads, moderated by Simon Willison.
- [CLAUDE CODE FULL COURSE 4 HOURS: Build & Sell (2026)](https://www.youtube.com/watch?v=QoQBzR1NIqI) 📺 · _by Nick Saraev_ — Four-hour Claude Code course, among the most-viewed Claude Code videos, covering agent teams, worktrees and cloud deployment.
- [800+ hours of Learning Claude Code in 8 minutes](https://www.youtube.com/watch?v=Ffh9OeJ7yxw) 📺 · _by Edmund Yong_ — Dense, high-signal tips video condensing hundreds of hours of Claude Code use, including task-based subagents.
- [I'm HOOKED on Claude Code Hooks: Advanced Agentic Coding](https://www.youtube.com/watch?v=J5B9UGTuNoM) 📺 · _by IndyDevDan_ — Deep dive into Claude Code hooks: blocking dangerous commands, logging, TTS notifications and observability across the agent lifecycle.
- [5 Claude Code skills I use every single day](https://www.youtube.com/watch?v=EJyuu6zlQCg) 📺 · _by Matt Pocock_ — Matt Pocock shares the five Agent Skills he relies on daily in Claude Code and how he writes them.

<a id="media"></a>
### Newsletters, Podcasts & Blogs

<sub>Keep up with the ecosystem.</sub>

- 🏆 **[Latent Space: Claude Code, Anthropic's Agent in Your Terminal](https://www.latent.space/p/claude-code)** 🎙️ · _by swyx & Alessio_ — May 2025 Latent Space episode with Boris Cherny and Cat Wu on Claude Code's origins, design and how Anthropic uses it.
- 🏆 **[Simon Willison's Weblog: claude-code tag](https://simonwillison.net/tags/claude-code)** 🌐 — 130+ posts tracking Claude Code releases, experiments, security issues and team interviews from a leading independent AI blogger.
- [Lenny's Podcast: Head of Claude Code — What happens after coding is solved](https://www.lennysnewsletter.com/p/head-of-claude-code-what-happens) 🎙️ · _by Lenny Rachitsky_ — February 2026 interview with Boris Cherny on Claude Code's growth, product principles, productivity tips and the future of engineering.
- [The Pragmatic Engineer: Building Claude Code with Boris Cherny](https://newsletter.pragmaticengineer.com/p/building-claude-code-with-boris-cherny) 🎙️ · _by Gergely Orosz_ — March 2026 podcast on parallel agents, plan-first workflows, agentic search over indexes, code review automation and team practices.
- [AI & I: How to Use Claude Code Like the People Who Built It](https://every.to/source-code/how-to-use-claude-code-like-the-people-who-built-it) 🎙️ · _by Dan Shipper (Every)_ — Every's AI & I episode with Cat Wu and Boris Cherny: plan mode, shared settings, stop hooks, subagents and slash commands.
- [Behind the Craft: How I Plan, Build, and Run Loops with Claude Code — Thariq Shihipar](https://creatoreconomy.so/p/how-i-plan-build-and-run-loops-with-claude-code-thariq-shihipar) 🎙️ · _by Peter Yang_ — July 2026 episode where a Claude Code engineer demos goal-setting, planning and parallel-agent loop workflows.

<div align="right"><a href="#top">↑ back to top</a></div>

---

<a id="chinese"></a>
## 🇨🇳 Chinese Community

_Bilibili creators, Chinese guides, communities and the domestic model providers that offer Claude Code compatible endpoints. Chinese-made projects are also marked 🇨🇳 throughout the list._

<a id="cn-video"></a>
### Bilibili Videos & Creators

<sub>Tutorials and demos from Chinese creators on Bilibili.</sub>

- 🏆 **[全网最全！60分钟全面掌握Claude Code～【附完整文档】](https://www.bilibili.com/video/BV1NvRyBzEhq)** 📺 🇨🇳 · _by 秋芝2046_ — 60-minute Claude Code course from install to advanced usage, with companion docs; three weeks in the making.
- 🏆 **[Claude Code 从 0 到 1 全攻略：MCP / SubAgent / Agent Skill / Hook / 图片 / 上下文处理/ 后台任务](https://www.bilibili.com/video/BV14rzQB9EJj)** 📺 🇨🇳 · _by 马克的技术工作坊_ — Systematic, timestamped deep dive: install, plan mode, background tasks, MCP, context management, hooks, skills, subagents, plugins.
- 🏆 **[Agent Skill 从使用到原理，一次讲清](https://www.bilibili.com/video/BV1cGigBQE6n)** 📺 🇨🇳 · _by 马克的技术工作坊_ — Clear explainer of Agent Skills: what they are, usage, progressive disclosure mechanism, and how they differ from MCP.
- 🏆 **[技术爬爬虾 · Bilibili](https://space.bilibili.com/316183842)** 📡 🇨🇳 — Prolific Bilibili creator of practical Claude Code, Agent Skills and MCP tutorials, consistently 100k+ views.
- [从夯到拉，锐评 32 个 AI 编程工具！](https://www.bilibili.com/video/BV1cq5q6CEu3) 📺 🇨🇳 · _by 程序员鱼皮_ — Tier-list review of 32 AI coding tools including Claude Code, Cursor and Codex across ability, UX, barrier, value and ecosystem.
- [10分钟学会24个ClaudeCode使用技巧](https://www.bilibili.com/video/BV1SddcBFESs) 📺 🇨🇳 · _by Yin\_Code_ — Fast-paced beginner video packing 24 practical Claude Code tips into about 10 minutes.
- [MCP终极指南 - 从原理到实战，带你深入掌握MCP（基础篇）](https://www.bilibili.com/video/BV1uronYREWR) 📺 🇨🇳 · _by 马克的技术工作坊_ — Classic Chinese MCP primer: servers, tools, host setup, configuring and running uvx/npx MCP servers, interaction flow.
- [国内爽用 Claude Code + Codex，2分钟搞定！](https://www.bilibili.com/video/BV14JEj6uEdG) 📺 🇨🇳 · _by 程序员鱼皮_ — Two-minute setup showing how to use Claude Code and Codex in China with CC Switch and domestic models like DeepSeek.
- [Claude Code 零基础终极教程：安装、换模型、插件、Hooks、Skills、Subagents、实战项目一次讲透！](https://www.bilibili.com/video/BV1TTR8BaEnL) 📺 🇨🇳 · _by 木子不写代码_ — Zero-to-hero tutorial: install, third-party models, permissions, hooks, skills, subagents, then building a working AI web app.
- [Agent Skills (Claude Skills) 详细攻略，一期视频精通](https://www.bilibili.com/video/BV1HuiyBQE9G) 📺 🇨🇳 · _by 技术爬爬虾_ — Long-form guide to Agent Skills: concepts, mechanics, practical use cases, and how Skills and MCP complement each other.
- [用过上百款编程MCP，只有这15个真正好用，Claude Code与Codex配置MCP详细教程](https://www.bilibili.com/video/BV1ZJsBznEt3) 📺 🇨🇳 · _by 技术爬爬虾_ — After testing 100+ coding MCP servers, picks the 15 most useful and shows configuring them in Claude Code and Codex.
- [告别Vibe Coding！用Superpowers让Claude Code写出工程级代码](https://www.bilibili.com/video/BV11urFBrEc4) 📺 🇨🇳 · _by AI超元域_ — Walkthrough of the Superpowers workflow (brainstorm, plan, TDD execution with subagents, two-stage review) building an iOS app.
- [最火AI编程Claude Code详细攻略，一期视频精通](https://www.bilibili.com/video/BV1XGbazvEuh) 📺 🇨🇳 · _by 技术爬爬虾_ — Practical guide covering 30 advanced Claude Code tips and techniques.
- [Claude Code: 从零搭建你的 AI 工作团队（Skills + Agents）| 回到Axton](https://www.bilibili.com/video/BV1eADaBME5z) 📺 🇨🇳 · _by 回到Axton_ — Building an AI work team in Claude Code by combining Skills and subagents, from a well-known productivity creator.
- [2026 AI效率组合神器：Superpowers + Claude Code 保姆级教程](https://www.bilibili.com/video/BV1yaRQB9EeQ) 📺 🇨🇳 · _by 全栈斌少_ — Beginner-friendly step-by-step tutorial on installing and using the Superpowers framework with Claude Code.
- [Claude Opus 5.5：前端之王重回它的宝座 AI 前端能力全面测试](https://www.bilibili.com/video/BV1NRhp6XEiq) 📺 🇨🇳 · _by 无机酸-\_-_ — Frontend-focused benchmark of Claude Opus 5.5 via Claude Code and web, mixing subjective and objective scoring.
- [从 0 到 1：6小时掌握 Vibe Coding！Claude Code ＋ AI](https://www.bilibili.com/video/BV1ZjDYB7Eam) 📺 🇨🇳 · _by 李哈利Harry_ — Six-hour course: Claude Code core features, AI frontend design, RAG knowledge base, multimodal data, agent automation, data safety.
- [Hooks入门只需5分钟](https://www.bilibili.com/video/BV1yDLG6DE39) 📺 🇨🇳 · _by Yin\_Code_ — Five-minute intro to Claude Code hooks: what they are, how to configure them, and building a practical hook (materials on GitHub).
- [把Claude Code工作流程做成可交互动画，5分钟即可掌握Claude Code工作原理！](https://www.bilibili.com/video/BV1toQbBtEDg) 📺 🇨🇳 · _by 轩辕的编程宇宙_ — Explains Claude Code's agent loop through an interactive animation, with a companion online simulator.
- [Claude Code Workflow自动生成Harness！彻底抹平Harness Engineering技术鸿沟](https://www.bilibili.com/video/BV15UG16nEtz) 📺 🇨🇳 · _by AI超元域_ — Tutorial on Claude Code's Workflow feature auto-generating a harness and running multi-agent development.
- [Claude Code 插件选型指南：原生 vs 四大框架(superpowers, ECC, GSD, Ralph)](https://www.bilibili.com/video/BV1yvAzzkEek) 📺 🇨🇳 · _by 探索未至之境_ — Compares native Claude Code with Superpowers, ECC, GSD and Ralph frameworks, conflicts, and a decision tree for choosing.
- [Claude Code 为什么不会撑爆上下文？深入解析 Agent 上下文压缩与会话恢复机制](https://www.bilibili.com/video/BV1nJ396JEmC) 📺 🇨🇳 · _by 唐国梁Tommy_ — Deep technical dive into how Claude Code manages long tasks: context projection, compaction, prompt caching and session recovery.
- [马克的技术工作坊 · Bilibili](https://space.bilibili.com/1815948385) 📡 🇨🇳 — Known for rigorous principle-to-practice explainers on MCP, Agent Skills and Claude Code, several videos near or above 1M views.
- [程序员鱼皮 · Bilibili](https://space.bilibili.com/12890453) 📡 🇨🇳 — Major Chinese programming creator covering Claude Code setup in China, AI tool reviews, and building projects with Claude Code.
- [AI超元域 · Bilibili](https://space.bilibili.com/3493277319825652) 📡 🇨🇳 — Creator focused on hands-on Claude Code workflows: Superpowers, Ralph, workflows/harness, memory MCPs and comparisons with Codex.

<a id="cn-guides"></a>
### Chinese Docs & Guides

<sub>Translations, handbooks and articles in Chinese.</sub>

- 🏆 **[AI-Coding-Guide-Zh (Claude Code 中文教程)](https://github.com/KimYx0207/AI-Coding-Guide-Zh)** 🇨🇳 ⭐ 6.3k — Large Chinese tutorial series: 50 guides plus cheat sheet covering Claude Code, Codex, OpenClaw and WorkBuddy learning paths.
- 🏆 **[Claude Code 官方中文文档](https://code.claude.com/docs/zh-CN/overview)** 📘 🇨🇳 — Anthropic's official Simplified Chinese Claude Code documentation: install, CLAUDE.md, skills, hooks, MCP, subagents, Agent SDK.
- [鱼皮 AI 知识库 (ai-guide)](https://github.com/liyupi/ai-guide) 🇨🇳 ⭐ 21.6k — Programmer Yupi's free AI knowledge base and vibe-coding tutorial, with Claude Code topics, tips and 'build your own Claude Code'.
- [claude-howto-zh-cn](https://github.com/lhfer/claude-howto-zh-cn) 🇨🇳 ⭐ 2.3k — Localized Chinese rewrite of luongnv89/claude-howto for beginners, keeping command/config compatibility with learning paths.
- [everything-claude-code-zh](https://github.com/xu-xiang/everything-claude-code-zh) 🇨🇳 ⭐ 2k — Chinese translation of everything-claude-code: hackathon-winning agents, skills, hooks, commands, rules and MCP configs.
- [claude-code-guide（国内如何使用 Claude Code）](https://github.com/claude-code-chinese/claude-code-guide) 🇨🇳 ⭐ 689 — Beginner-friendly Chinese intro and teaching guide to Claude Code, including notes for users in mainland China.
- [awesome-claudcode-tutorial](https://github.com/xianyu110/awesome-claudcode-tutorial) 🇨🇳 ⭐ 619 — Comprehensive Chinese Claude Code tutorial from zero to enterprise use: 200+ articles plus a 29-chapter course.
- [Claude Code 橙皮书 (claude-code-orange-book)](https://github.com/alchaincyf/claude-code-orange-book) 🇨🇳 ⭐ 327 — 'Orange Book' complete practical guide to Claude Code by indie developer HuaShu, with Chinese edition.
- [菜鸟教程 Claude Code 教程](https://www.runoob.com/claude-code/claude-code-tutorial.html) 🎓 🇨🇳 — Runoob's multi-chapter Chinese Claude Code tutorial: install, DeepSeek/Coding Plan setup, CLAUDE.md, MCP, subagents, skills, hooks, SDK.
- [Claude Code 完全指南：使用方式、技巧与最佳实践（掘金）](https://juejin.cn/post/7592079304923824138) 📝 🇨🇳 · _by knqiufan_ — Long Juejin reference covering Claude Code install, Skills, Hooks, MCP, Subagents, CLAUDE.md, advanced modes and troubleshooting.
- [Claude Code 怎么学？推荐 4 个高质量开源教程（掘金）](https://juejin.cn/post/7646780600486412340) 📝 🇨🇳 · _by JavaGuide_ — JavaGuide's Juejin roundup recommending four high-quality open-source Chinese Claude Code tutorials.
- [看这一篇就够了！Claude Code 接入四大国产编程模型 DeepSeek、GLM、Qwen、Kimi 全指南（知乎）](https://zhuanlan.zhihu.com/p/1944667171704779382) 📝 🇨🇳 — Zhihu guide to plugging DeepSeek, GLM, Qwen and Kimi into official Claude Code via Anthropic-compatible endpoints, no router needed.
- [这可能是目前最全的 Claude Code 使用指南（2025 版）（知乎）](https://zhuanlan.zhihu.com/p/1954938233126381432) 📝 🇨🇳 — Widely shared Zhihu long-form guide to Claude Code usage and best practices (2025 edition).
- [最新 Agentic Coding：Claude Code 官方最佳实践（知乎）](https://zhuanlan.zhihu.com/p/1997843063482123604) 📝 🇨🇳 — Zhihu walkthrough of Anthropic's official Claude Code best practices plus Boris Cherny's real workflow tips.
- [Claude Code子代理完全指南：从0到1构建你的AI编程军团（腾讯云开发者社区）](https://cloud.tencent.com/developer/article/2553995) 📝 🇨🇳 · _by 前端达人_ — Tencent Cloud Developer article on Claude Code subagents: creating validator, frontend, API, review and research agents via /agents.

<a id="cn-community"></a>
### Chinese Communities

<sub>Forums and platforms where Chinese developers share Claude projects.</sub>

- 🏆 **[LINUX DO](https://linux.do)** 💬 🇨🇳 — Most active Chinese developer forum for AI coding; its dev-tuning and open-source categories host many Claude Code tools and tips.
- [V2EX · Claude 节点](https://www.v2ex.com/go/claude) 💬 🇨🇳 — V2EX's Claude node with 1,000+ topics discussing Claude and Claude Code usage, access issues and experiences.
- [WaytoAGI 通往AGI之路 · AI 编程](https://waytoagi.feishu.cn/wiki/Pxj8wsMmOii7ZSkN0mYc8xdtnHb) 💬 🇨🇳 — AI coding section of WaytoAGI, China's largest open AI knowledge base on Feishu, covering Claude Code and other tools.
- [哔哩哔哩 · Claude Code 搜索](https://search.bilibili.com/all?keyword=Claude+Code) 💬 🇨🇳 — Bilibili search for Claude Code: the main Chinese video hub for tutorials, reviews and demos.
- [科技爱好者周刊 (ruanyf/weekly)](https://github.com/ruanyf/weekly/issues) 💬 🇨🇳 — Ruan Yifeng's widely read Chinese tech weekly; developers submit their own projects, including many Claude tools, through its GitHub issues.

<a id="cn-providers"></a>
### Domestic Models for Claude Code

<sub>Official guides from Chinese model providers with Anthropic-compatible APIs.</sub>

- 🏆 **[智谱 GLM Coding Plan · Claude Code 接入文档](https://docs.bigmodel.cn/cn/coding-plan/tool/claude)** 📘 🇨🇳 — Zhipu's official guide to running Claude Code on GLM via the Anthropic-compatible endpoint open.bigmodel.cn/api/anthropic.
- 🏆 **[DeepSeek API 文档 · 使用 Anthropic API（接入 Claude Code）](https://api-docs.deepseek.com/zh-cn/guides/anthropic_api)** 📘 🇨🇳 — DeepSeek's official Anthropic-compatible API doc (api.deepseek.com/anthropic) with Claude Code setup and field-compatibility table.
- [Kimi 开放平台 · 在 Claude Code 中使用 Kimi](https://platform.kimi.com/docs/guide/claude-code-kimi) 📘 🇨🇳 — Moonshot's official guide to forwarding Claude Code requests to Kimi models via api.moonshot.cn/anthropic.
- [阿里云百炼 · Claude Code 接入](https://help.aliyun.com/zh/model-studio/claude-code) 📘 🇨🇳 — Alibaba Cloud Model Studio (Bailian) guide to using Qwen models in Claude Code via pay-as-you-go, Coding Plan or Token Plan endpoints.
- [MiniMax 开放平台 · Claude Code](https://platform.minimax.cn/docs/coding-plan/claude-code) 📘 🇨🇳 — MiniMax's official China-site guide for using MiniMax models in Claude Code via api.minimax.cn/anthropic.
- [火山方舟 Coding Plan · 接入 Claude Code](https://docs.volcengine.com/docs/82379/2406397) 📘 🇨🇳 — Volcengine Ark (ByteDance) Coding Plan docs for connecting Claude Code to Doubao, GLM, Kimi, DeepSeek and MiniMax models.
- [硅基流动 SiliconFlow · 在 Claude Code 中使用](https://docs.siliconflow.cn/cn/usercases/use-siliconcloud-in-ClaudeCode) 📘 🇨🇳 — SiliconFlow's official doc for using its hosted open models (Qwen, DeepSeek, GLM, Kimi) in Claude Code.
- [腾讯云 · DeepSeek Anthropic 兼容接口（接入 Claude Code）](https://cloud.tencent.cn/document/product/1772/126272) 📘 🇨🇳 — Tencent Cloud's official doc for its DeepSeek Anthropic-compatible endpoint, including Claude Code installation and env setup.

<a id="cn-projects"></a>
### Chinese-made projects at a glance

<sub>Projects by Chinese developers that appear in the functional categories above.</sub>

[CC Switch](https://github.com/farion1231/cc-switch) ⭐149k · [LobeHub](https://github.com/lobehub/lobehub) ⭐83.5k · [Learn Claude Code](https://github.com/shareAI-lab/learn-claude-code) ⭐79.2k · [Cherry Studio](https://github.com/CherryHQ/cherry-studio) ⭐53k · [Claude Code Router](https://github.com/musistudio/claude-code-router) ⭐37.9k · [AionUi](https://github.com/iOfficeAI/AionUi) ⭐33.8k · [baoyu-skills](https://github.com/JimLiu/baoyu-skills) ⭐27k · [NextChat](https://github.com/ChatGPTNextWeb/NextChat) ⭐88.9k · [Chatbox](https://github.com/chatboxai/chatbox) ⭐42.1k · [avante.nvim](https://github.com/avante-corp/avante.nvim) ⭐18.2k · [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) ⭐16.6k · [cc-connect](https://github.com/chenhg5/cc-connect) ⭐16.1k · [Trellis](https://github.com/mindfold-ai/Trellis) ⭐15k · [Claude Context](https://github.com/zilliztech/claude-context) ⭐12.6k · [Chrome MCP Server (mcp-chrome)](https://github.com/hangwin/mcp-chrome) ⭐12.5k · [Awesome-MCP-ZH](https://github.com/yzfly/Awesome-MCP-ZH) ⭐7.8k · [jetbrains-cc-gui](https://github.com/zhukunpenglinyutong/jetbrains-cc-gui) ⭐7.3k · [CodePilot](https://github.com/op7418/CodePilot) ⭐6.5k · [DeepChat](https://github.com/ThinkInAIXYZ/deepchat) ⭐6.4k · [ZCF (Zero-Config Code Flow)](https://github.com/UfoMiao/zcf) ⭐6.1k · [CCG Workflow](https://github.com/fengshao1227/ccg-workflow) ⭐5.9k · [ArcReel](https://github.com/ArcReel/ArcReel) ⭐5.7k · [Awesome Claude Prompts](https://github.com/langgptai/awesome-claude-prompts) ⭐5.5k · [5ire](https://github.com/nanbingxyz/5ire) ⭐5.4k · [Kode](https://github.com/shareAI-lab/Kode-CLI) ⭐5.2k · [mcp-feedback-enhanced](https://github.com/Minidoracat/mcp-feedback-enhanced) ⭐3.8k · [CCometixLine](https://github.com/Haleclipse/CCometixLine) ⭐3.5k · [claude-code-proxy (fuergaosi233)](https://github.com/fuergaosi233/claude-code-proxy) ⭐2.8k · [CodexMCP](https://github.com/GuDaStudio/codexmcp) ⭐2k · [claude-code-settings (feiskyer)](https://github.com/feiskyer/claude-code-settings) ⭐1.7k · [NekroAgent](https://github.com/KroMiose/nekro-agent) ⭐1.2k · [Claude_skills_zh-CN](https://github.com/LeastBit/Claude_skills_zh-CN) ⭐599 · [awesome-claude-code (LangGPT 中文版)](https://github.com/LangGPT/awesome-claude-code) ⭐272 · [Z.ai GLM Coding Plan for Claude Code](https://docs.z.ai/devpack/tool/claude) · [mcp.so](https://mcp.so) · [魔搭 ModelScope MCP 广场](https://modelscope.cn/mcp) · [awesome-agent-skills (Agent Skills 终极指南)](https://github.com/libukai/awesome-agent-skills)

<div align="right"><a href="#top">↑ back to top</a></div>

---

<a id="community"></a>
## 🌏 Global Community

_Where people hang out, plus resources in Japanese, Korean and other languages, and related awesome lists._

<a id="communities"></a>
### Communities & Events

<sub>Subreddits, Discord servers, accounts to follow and events.</sub>

- 🏆 **[r/ClaudeAI](https://www.reddit.com/r/ClaudeAI)** 💬 — Largest Claude subreddit, linked from Anthropic's community page; news, showcases, Claude Code discussion and usage-limit debates.
- 🏆 **[r/ClaudeCode](https://www.reddit.com/r/ClaudeCode)** 💬 — Dedicated subreddit for building, learning and sharing with Claude Code: workflows, tools, help requests and showcases.
- 🏆 **[Boris Cherny (@bcherny)](https://x.com/bcherny)** 💬 — Creator and head of Claude Code; his X threads on his own setup and team workflows are widely shared tip sources.
- [r/Anthropic](https://www.reddit.com/r/Anthropic) 💬 — Subreddit for news and discussion about Anthropic the company, its models, policies and products including Claude Code.
- [Claude Community](https://claude.com/community) 🌐 — Anthropic's community hub: Ambassadors and Campus programs, city meetups, Discord, Reddit, project submissions and a monthly newsletter.
- [Claude Community Events (Luma)](https://luma.com/claudecommunity) 💬 — Global calendar of ambassador-run Claude and Claude Code meetups, workshops and hackathons across dozens of cities.
- [Code with Claude](https://claude.com/code-with-claude) 🌐 — Anthropic's developer conference; 2026 edition ran in San Francisco, London and Tokyo with recorded Claude Code sessions.
- [@AnthropicAI on X](https://x.com/AnthropicAI) 💬 — Anthropic's official X account for company announcements, research, safety and major model releases.
- [@claudeai on X](https://x.com/claudeai) 💬 — Official Claude product account on X covering new features, Claude Code launches and usage tips.
- [@ClaudeDevs on X](https://x.com/ClaudeDevs) 💬 — Developer-focused X account launched in April 2026 for changelogs, API releases and technical deep dives.
- [Cat Wu (@_catwu)](https://x.com/_catwu) 💬 — Claude Code product lead at Anthropic; posts feature announcements and practical usage tips.
- [Thariq Shihipar (@trq212)](https://x.com/trq212) 💬 — Claude Code team engineer who posts workflows, internal philosophy and techniques such as using HTML artifacts with Claude Code.
- [Tell HN: I'm 60 years old. Claude Code has re-ignited a passion](https://news.ycombinator.com/item?id=47282777) 💬 — Landmark Hacker News thread (March 2026) with nearly 1,000 comments on how Claude Code changed people's relationship with programming.

<a id="intl-community"></a>
### Japanese, Korean & Other Languages

<sub>Very active non-English communities beyond Chinese.</sub>

- [Zenn: Claude Code topic](https://zenn.dev/topics/claudecode) 💬 🇯🇵 — Japan's main developer-blog hub for Claude Code, with over 11,000 articles plus books and scraps.
- [Qiita: ClaudeCode tag](https://qiita.com/tags/claudecode) 💬 🇯🇵 — Qiita tag with nearly 9,800 Japanese Claude Code articles and over 24,000 followers.
- [note: #ClaudeCode](https://note.com/hashtag/ClaudeCode) 💬 🇯🇵 — note.com hashtag with thousands of Japanese posts on Claude Code, many aimed at non-engineers and business automation.
- [実践Claude Code入門 (Gijutsu-Hyoronsha)](https://gihyo.jp/book/2026/978-4-297-15354-0) 📘 🇯🇵 — Japanese book (Dec 2025) on rethinking development with Claude Code: spec-driven development, MCP and Claude Code Action.
- [Claude CodeによるAI駆動開発入門 (Gijutsu-Hyoronsha)](https://gihyo.jp/book/2025/978-4-297-15275-8) 📘 🇯🇵 — 320-page Japanese beginner's book (Dec 2025) on AI-driven development with Claude Code.
- [Claude Code実践入門 (生成AI深掘りガイド) (SB Creative)](https://www.sbcr.jp/product/4815643119) 📘 🇯🇵 — Japanese practical guide to agentic coding with Claude Code, published August 2026.
- [【一人社長】Claude Codeで会社を作ってAI社員に仕事を任せてみよう！](https://www.youtube.com/watch?v=cfoE_8Llde0) 📺 🇯🇵 · _by プログラミングチュートリアル_ — One of the most-viewed Japanese Claude Code videos: running a one-person company with Claude Code "AI employees".
- [GeekNews (긱뉴스)](https://news.hada.io) 💬 🇰🇷 — Korea's leading developer news aggregator, with frequent Korean summaries and discussion of Claude Code news.

<a id="awesome-lists"></a>
### Related Awesome Lists

<sub>Other curated lists worth bookmarking.</sub>

- 🏆 **[Awesome Claude Code](https://github.com/hesreallyhim/awesome-claude-code)** ⭐ 56.6k — The leading hand-picked list of Claude Code skills, hooks, slash commands, orchestrators, applications and plugins.
- [Awesome Claude Skills (ComposioHQ)](https://github.com/ComposioHQ/awesome-claude-skills) ⭐ 78k — Curated list of Claude Skills, resources and tools for customizing Claude workflows.
- [awesome-claude-code (LangGPT 中文版)](https://github.com/LangGPT/awesome-claude-code) 🇨🇳 ⭐ 272 — Claude Code curated resource list by LangGPT (Yunzhong Jiangshu) with a Simplified Chinese edition: projects, prompts, agents, commands.
- [awesome-agent-skills (Agent Skills 终极指南)](https://github.com/libukai/awesome-agent-skills) 🇨🇳 — Chinese-first ultimate guide to Agent Skills: quick start, resources, curated skills and toolkits for Claude and other agents.

<div align="right"><a href="#top">↑ back to top</a></div>

---

## 🤝 Contributing

Found something awesome? Open an [issue](https://github.com/tomcatmew/awesome-Claude-code/issues/new/choose) or a pull request. All entries live in [`data/projects.json`](data/projects.json); run `python scripts/build.py` to regenerate the READMEs and the website. See [CONTRIBUTING.md](CONTRIBUTING.md).

## 📈 Star history

[![Star History Chart](https://api.star-history.com/svg?repos=tomcatmew/awesome-Claude-code&type=Date)](https://star-history.com/#tomcatmew/awesome-Claude-code&Date)

## 📄 License

[CC0 1.0](LICENSE) — to the extent possible under law, the curators have waived all copyright to this list.

<sub>This is a community project and is not affiliated with or endorsed by Anthropic. Claude and Claude Code are trademarks of Anthropic, PBC. Projects listed are owned by their respective authors — review code before running it, especially hooks, plugins and MCP servers that execute on your machine.</sub>
