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

[English](README.md) · **简体中文**

**精心整理、分类清晰的中英双语 Claude Code 与 Claude 生态资源合集 —— 工具、技能、子代理、插件、MCP 服务器、应用、教程、视频与全球社区（含中文社区与 B 站）。**

### 🔎 [浏览交互式网站 →](https://tomcatmew.github.io/awesome-Claude-code/)
<sub>支持搜索、按分类/类型/地区筛选、按 Star 排序</sub>

如果这份列表帮你节省了时间，点个 ⭐ 能让更多 Claude Code 用户发现它。发现遗漏？欢迎[推荐项目](https://github.com/tomcatmew/awesome-Claude-code/issues/new/choose)。

</div>

> 共 **556** 个资源 · **41** 个分类 · **364** 个 GitHub 仓库，合计 **9.0M** Star · 更新于 **2026-10-31**
>
> **图例：** 🏆 精选 · ⭐ GitHub Star（每周自动更新）· 🇨🇳 国人/中文 · 🇯🇵 日本 · 🇰🇷 韩国 · 🗄️ 已归档 · 📘 文档 · 📝 文章 · 🎓 课程 · 📺 视频 · 💬 社区

## 🚀 从这里开始

刚接触 Claude Code？以下是大多数人最终都会用到的资源。

| 资源 | 简介 | 分类 |
|---|---|---|
| [**Claude Code**](https://github.com/anthropics/claude-code) ⭐ 153k | Anthropic 官方智能体编程工具，支持终端、IDE、桌面与网页；仓库包含问题反馈、更新日志、插件和示例配置。 | [官方仓库](#official-repos) |
| [**Claude Code Documentation**](https://code.claude.com/docs/en/overview) | Claude Code 官方文档：安装、CLAUDE.md 记忆、技能、钩子、子代理、MCP、插件、设置、CI、定时任务及各使用端。 | [官方文档与课程](#official-learning) |
| [**Best Practices for Claude Code**](https://code.claude.com/docs/en/best-practices) | Anthropic 权威实践指南：为 Claude 提供验证手段、先探索再计划后编码、精简 CLAUDE.md、管理上下文、子代理与并行会话。 | [官方文档与课程](#official-learning) |
| [**Anthropic Agent Skills**](https://github.com/anthropics/skills) ⭐ 184k | Anthropic 官方 Agent Skills 公共仓库，包含文档类技能（docx、pptx、xlsx、pdf）、示例及 skill-creator。 | [官方仓库](#official-repos) |
| [**Superpowers**](https://github.com/obra/superpowers) ⭐ 305k | Jesse Vincent 打造的智能体技能框架与开发方法论，涵盖头脑风暴、规划、TDD、调试和子智能体驱动开发，已上架官方插件市场。 | [Agent Skills 技能](#skills) |
| [**Claude Code Plugins (Official Directory)**](https://github.com/anthropics/claude-plugins-official) ⭐ 44.6k | Anthropic 官方维护的 Claude Code 插件市场，收录集成技能、子代理、钩子与 MCP 服务器的精选插件。 | [官方仓库](#official-repos) |
| [**Claude Code GitHub Action**](https://github.com/anthropics/claude-code-action) ⭐ 9.6k | 官方 GitHub Action，在 PR 和 Issue 中运行 Claude Code：响应 @claude 提及、审查代码并实现修改。 | [官方仓库](#official-repos) |
| [**ccusage**](https://github.com/ccusage/ccusage) ⭐ 19.2k | 免安装 CLI（npx ccusage），分析本地 Claude Code JSONL 日志，按日、月、会话和 5 小时窗口统计 token 用量与费用。 | [用量与成本监控](#usage-monitoring) |
| [**CC Switch**](https://github.com/farion1231/cc-switch) ⭐ 149k | 跨平台桌面应用，为 Claude Code、Codex、OpenCode 等 CLI 代理一键切换 API 服务商，并管理配置、MCP 服务器和技能。 | [模型路由与供应商切换](#routers-proxies) |
| [**Spec Kit**](https://github.com/github/spec-kit) ⭐ 143k | GitHub 官方开源的规格驱动开发（SDD）工具包，提供 constitution、specify、plan、tasks、implement 等命令，适用于 Claude Code 及其他代理。 | [框架与方法论](#frameworks) |
| [**Context7**](https://github.com/upstash/context7) ⭐ 63.7k | Upstash 推出的 MCP 服务器与平台，为智能体上下文提供最新、按版本区分的库文档和代码示例。 | [MCP 服务器](#mcp-servers) |
| [**Learn Claude Code**](https://github.com/shareAI-lab/learn-claude-code) ⭐ 79.2k | 动手课程：用 Python 从零构建迷你版 Claude Code 智能体框架，每课新增一个机制；提供英/中/日文版。 | [指南与教程](#guides) |

<a id="contents"></a>
## 📑 目录

- 🏛️ [官方资源](#official) <sub>36</sub>
  - [官方仓库](#official-repos) <sub>13</sub> · [官方 SDK](#official-sdks) <sub>12</sub> · [官方文档与课程](#official-learning) <sub>11</sub>
- 🧩 [扩展 Claude Code](#extending) <sub>74</sub>
  - [Agent Skills 技能](#skills) <sub>23</sub> · [子代理 Subagents](#subagents) <sub>8</sub> · [斜杠命令](#commands) <sub>7</sub> · [钩子 Hooks](#hooks) <sub>13</sub> · [插件与插件市场](#plugins) <sub>11</sub> · [CLAUDE.md、配置与模板](#claude-md) <sub>12</sub>
- 🧭 [工作流与编排](#workflows) <sub>64</sub>
  - [框架与方法论](#frameworks) <sub>19</sub> · [多代理与并行会话](#orchestration) <sub>26</sub> · [记忆与上下文](#memory-context) <sub>19</sub>
- 🛠️ [工具链](#tooling) <sub>79</sub>
  - [用量与成本监控](#usage-monitoring) <sub>10</sub> · [状态栏 Statusline](#statusline) <sub>8</sub> · [图形界面、Web 与移动端](#gui-clients) <sub>10</sub> · [IDE 与编辑器集成](#ide) <sub>12</sub> · [模型路由与供应商切换](#routers-proxies) <sub>12</sub> · [沙箱与容器](#sandbox) <sub>9</sub> · [CI/CD 与 GitHub 自动化](#ci-cd) <sub>6</sub> · [日志、会话记录与可观测性](#observability) <sub>12</sub>
- 🔌 [模型上下文协议 MCP](#mcp) <sub>82</sub>
  - [MCP 服务器](#mcp-servers) <sub>56</sub> · [MCP SDK 与开发工具](#mcp-dev) <sub>15</sub> · [MCP 目录与注册表](#mcp-directories) <sub>11</sub>
- 🤖 [基于 Claude 构建](#building) <sub>73</sub>
  - [Agent SDK 项目](#agent-sdk) <sub>10</sub> · [电脑与浏览器操控](#computer-use) <sub>10</sub> · [支持 Claude 的编程代理](#coding-agents) <sub>18</sub> · [聊天客户端与应用](#chat-clients) <sub>18</sub> · [API 库与开发工具](#api-tools) <sub>17</sub>
- 📚 [学习资源](#learning) <sub>70</sub>
  - [指南与教程](#guides) <sub>10</sub> · [必读文章](#articles) <sub>21</sub> · [课程](#courses) <sub>7</sub> · [提示词与提示工程](#prompts) <sub>4</sub> · [视频与频道](#videos) <sub>22</sub> · [资讯、播客与博客](#media) <sub>6</sub>
- 🇨🇳 [中文社区](#chinese) <sub>53</sub>
  - [B 站视频与 UP 主](#cn-video) <sub>25</sub> · [中文文档与教程](#cn-guides) <sub>15</sub> · [中文社区平台](#cn-community) <sub>5</sub> · [国内模型接入 Claude Code](#cn-providers) <sub>8</sub>
- 🌏 [全球社区](#community) <sub>25</sub>
  - [社区与活动](#communities) <sub>13</sub> · [日语、韩语及其他语言](#intl-community) <sub>8</sub> · [相关 Awesome 列表](#awesome-lists) <sub>4</sub>

---

<a id="official"></a>
## 🏛️ 官方资源

_Anthropic 与 Model Context Protocol 项目官方发布的仓库、SDK、文档与课程。_

<a id="official-repos"></a>
### 官方仓库

<sub>Claude Code 本体、官方 Action、Skills、Cookbook 与快速上手项目。</sub>

- 🏆 **[Anthropic Agent Skills](https://github.com/anthropics/skills)** ⭐ 184k — Anthropic 官方 Agent Skills 公共仓库，包含文档类技能（docx、pptx、xlsx、pdf）、示例及 skill-creator。
- 🏆 **[Claude Code](https://github.com/anthropics/claude-code)** ⭐ 153k — Anthropic 官方智能体编程工具，支持终端、IDE、桌面与网页；仓库包含问题反馈、更新日志、插件和示例配置。
- 🏆 **[Claude Cookbooks](https://github.com/anthropics/claude-cookbooks)** ⭐ 53.8k — 官方 Notebook 与示例集，涵盖工具调用、RAG、智能体、Agent SDK、Managed Agents、技能、评测与多模态。
- 🏆 **[Claude Code Plugins (Official Directory)](https://github.com/anthropics/claude-plugins-official)** ⭐ 44.6k — Anthropic 官方维护的 Claude Code 插件市场，收录集成技能、子代理、钩子与 MCP 服务器的精选插件。
- 🏆 **[Claude Code GitHub Action](https://github.com/anthropics/claude-code-action)** ⭐ 9.6k — 官方 GitHub Action，在 PR 和 Issue 中运行 Claude Code：响应 @claude 提及、审查代码并实现修改。
- [Claude for Financial Services](https://github.com/anthropics/financial-services) ⭐ 40.8k — 面向金融业务的参考智能体、技能和数据连接器，可作为 Cowork 插件安装或通过 Managed Agents 部署。
- [Knowledge Work Plugins](https://github.com/anthropics/knowledge-work-plugins) ⭐ 33.1k — 面向知识工作者的官方开源插件集，用于 Claude Cowork，覆盖销售、财务、法务、客服、市场等场景。
- [Claude Quickstarts](https://github.com/anthropics/claude-quickstarts) ⭐ 19k — 基于 Claude API 的可部署入门项目，如客服智能体、金融分析、Computer Use 与自主编程演示。
- [Model Context Protocol Specification](https://github.com/modelcontextprotocol/modelcontextprotocol) ⭐ 9.5k — MCP 规范与文档源码；MCP 是 Anthropic 发起、用于连接 AI 应用与工具和数据的开放协议。
- [Defending Code Reference Harness](https://github.com/anthropics/defending-code-reference-harness) ⭐ 7.7k — 用于威胁建模、漏洞扫描、分诊与修补的 Claude Code 技能，以及自主化的安全扫描参考框架。
- [Sandbox Runtime (srt)](https://github.com/anthropics/sandbox-runtime) ⭐ 6.6k — 轻量级系统级沙箱，无需容器即可对智能体、MCP 服务器和命令施加文件系统与网络限制；为 Claude Code 打造。
- [Claude Code Security Review](https://github.com/anthropics/claude-code-security-review) ⭐ 6.6k — 使用 Claude 分析代码变更安全漏洞并在 PR 中评论结果的 GitHub Action。
- [Anthropic Dev Container Features](https://github.com/anthropics/devcontainer-features) ⭐ 314 — 官方 Dev Container Features，可将 Claude Code CLI 安装到开发容器与 Codespaces 中。

<a id="official-sdks"></a>
### 官方 SDK

<sub>Claude API 与 Claude Agent SDK 的官方客户端库。</sub>

- 🏆 **[MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)** ⭐ 24.7k — 构建 MCP 服务器与客户端的官方 Python SDK，包含 FastMCP 风格的服务器 API。
- 🏆 **[Claude Agent SDK (Python)](https://github.com/anthropics/claude-agent-sdk-python)** ⭐ 8.4k — Python 版 Agent SDK，提供 Claude Code 的智能体循环、内置工具、钩子、子代理、MCP 与权限控制，用于构建自定义智能体。
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) ⭐ 13.7k — 构建 MCP 服务器与客户端的官方 TypeScript SDK。
- [Anthropic Python SDK](https://github.com/anthropics/anthropic-sdk-python) ⭐ 4k — Claude API 官方 Python 客户端库，支持同步/异步、流式输出、工具调用辅助及 beta 版 tool runner。
- [Anthropic TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) ⭐ 2.2k — Claude API 官方 TypeScript/JavaScript 客户端（@anthropic-ai/sdk），支持 Node、Deno、Bun 与边缘运行时。
- [Claude Agent SDK (TypeScript)](https://github.com/anthropics/claude-agent-sdk-typescript) ⭐ 1.8k — TypeScript 版 Agent SDK，基于驱动 Claude Code 的同一套框架、工具与上下文管理构建生产级智能体。
- [Anthropic Go SDK](https://github.com/anthropics/anthropic-sdk-go) ⭐ 1.2k — Claude API 官方 Go 客户端库。
- [ant: Claude API CLI](https://github.com/anthropics/anthropic-cli) ⭐ 698 — 官方 Go 语言编写的 `ant` 命令行工具：在终端发送消息、管理智能体/会话/文件，并脚本化调用所有 API 端点。
- [Anthropic Java SDK](https://github.com/anthropics/anthropic-sdk-java) ⭐ 386 — Claude API 官方 Java 客户端库（亦适用于 Kotlin）。
- [Anthropic Ruby SDK](https://github.com/anthropics/anthropic-sdk-ruby) ⭐ 377 — Claude API 官方 Ruby 客户端库。
- [Anthropic C# SDK](https://github.com/anthropics/anthropic-sdk-csharp) ⭐ 339 — Claude API 官方 C#/.NET 客户端库。
- [Anthropic PHP SDK](https://github.com/anthropics/anthropic-sdk-php) ⭐ 194 — Claude API 官方 PHP 客户端库。

<a id="official-learning"></a>
### 官方文档与课程

<sub>官方文档、Anthropic Academy 课程与工程博客。</sub>

- 🏆 **[Claude Code Documentation](https://code.claude.com/docs/en/overview)** 📘 — Claude Code 官方文档：安装、CLAUDE.md 记忆、技能、钩子、子代理、MCP、插件、设置、CI、定时任务及各使用端。
- 🏆 **[Best Practices for Claude Code](https://code.claude.com/docs/en/best-practices)** 📘 — Anthropic 权威实践指南：为 Claude 提供验证手段、先探索再计划后编码、精简 CLAUDE.md、管理上下文、子代理与并行会话。
- 🏆 **[Agent Skills Open Standard](https://agentskills.io)** 🌐 — Agent Skills 规范与文档：由 Anthropic 发起、被众多智能体采用的 SKILL.md 文件夹格式开放标准。
- 🏆 **[Model Context Protocol Docs](https://modelcontextprotocol.io)** 📘 — MCP 官方网站，包含概念、架构、服务器/客户端构建指南、MCP Apps 与安全最佳实践。
- [Code with Claude Workshops](https://github.com/anthropics/cwc-workshops) ⭐ 2.2k — Anthropic “Code with Claude” 工作坊资料：模型选择、基于技能与 MCP 的多智能体、Managed Agents、记忆与评测驱动开发。
- [Agent SDK Documentation](https://code.claude.com/docs/en/agent-sdk/overview) 📘 — Claude Agent SDK 官方指南：智能体循环、工具、钩子、子代理、会话、权限、插件，以及 Python/TypeScript 参考。
- [Claude Platform (API) Documentation](https://platform.claude.com/docs/en/home) 📘 — Claude 开发者平台官方文档：Messages API、模型、工具调用、提示缓存、结构化输出、Managed Agents、SDK 及发布说明。
- [Anthropic Engineering Blog](https://www.anthropic.com/engineering) 🌐 — Anthropic 工程博客，深入探讨智能体、上下文工程、工具、技能、运行框架、沙箱、评测与事故复盘。
- [claude.dev Blog](https://claude.dev) 🌐 — Anthropic 开发者技术博客，分享使用 Claude 与 Claude Code 构建的技巧、实战手册、框架设计与构建日志。
- [Claude Status](https://status.claude.com) 🌐 — 官方服务状态页，覆盖 claude.ai、Console、Claude API、Claude Code 与 Cowork，含故障历史与订阅通知。
- [Anthropic Discord](https://www.anthropic.com/discord) 💬 — Anthropic/Claude 官方社区 Discord 服务器，面向开发者与用户。

<div align="right"><a href="#top">↑ 返回顶部</a></div>

---

<a id="extending"></a>
## 🧩 扩展 Claude Code

_即插即用的扩展内容：技能、子代理、斜杠命令、钩子、插件与配置模板。_

<a id="skills"></a>
### Agent Skills 技能

<sub>按需加载的指令、脚本与资源包。</sub>

- 🏆 **[Superpowers](https://github.com/obra/superpowers)** ⭐ 305k — Jesse Vincent 打造的智能体技能框架与开发方法论，涵盖头脑风暴、规划、TDD、调试和子智能体驱动开发，已上架官方插件市场。
- 🏆 **[mattpocock/skills](https://github.com/mattpocock/skills)** ⭐ 304k — Matt Pocock 分享的个人工程技能集，包括 grill-me、tdd、diagnosing-bugs 和 handoff，是 skills.sh 上安装量最高的技能之一。
- 🏆 **[baoyu-skills](https://github.com/JimLiu/baoyu-skills)** 🇨🇳 ⭐ 27k — 宝玉分享的效率技能集，适用于 Claude Code 和 Codex：AI 生图、发布公众号、封面图、信息图、小红书卡片、幻灯片和知识漫画。
- 🏆 **[skills.sh](https://skills.sh)** 🌐 — Vercel 推出的开放 Agent Skills 目录和安装量排行榜，可浏览技能并通过 npx skills add 安装到 Claude Code 等智能体。
- [Ponytail](https://github.com/DietrichGebert/ponytail) ⭐ 176k — 遵循 YAGNI 原则的技能兼 Claude Code 插件，让智能体像最“懒”的资深工程师一样少写代码、避免过度设计。
- [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) ⭐ 141k — 提供设计智能的技能，帮助智能体在多平台、多框架下构建专业的 UI/UX。
- [Caveman](https://github.com/JuliusBrussee/caveman) ⭐ 115k — 一个爆红的技能加代理，让编程智能体用“原始人”式简短语言说话以节省输出 token，作者实测整个会话约少用三分之一。
- [Agent Skills (addyosmani)](https://github.com/addyosmani/agent-skills) ⭐ 111k — Addy Osmani 为 AI 编程智能体编写的生产级工程技能集，包含 24 个软件生命周期技能和一个 using-agent-skills 元技能。
- [Taste Skill](https://github.com/Leonxlnx/taste-skill) ⭐ 103k — 为编程智能体赋予设计品味的技能集：艺术指导、参考图和浏览器检查，避免生成千篇一律的 AI 风格页面。
- [Humanizer](https://github.com/blader/humanizer) ⭐ 60.8k — 识别并去除文本中 AI 生成痕迹的智能体技能。
- [i-have-adhd](https://github.com/ayghri/i-have-adhd) ⭐ 58.8k — 让编程智能体不再把答案埋在长篇大论里的技能，输出先给结论、对 ADHD 友好，已打包为 Claude Code 插件。
- [Marketing Skills](https://github.com/coreyhaines31/marketingskills) ⭐ 56.6k — 面向 Claude Code 和 AI 智能体的营销技能集，涵盖转化率优化、文案、SEO、数据分析和增长工程。
- [Scientific Agent Skills (K-Dense)](https://github.com/K-Dense-AI/scientific-agent-skills) ⭐ 54.7k — 提供 177 个以上科研技能并接入 100 多个科学数据库，把 Claude 或任意智能体变成 AI 科学家。原名 Claude Scientific Skills。
- [Obsidian Skills](https://github.com/kepano/obsidian-skills) ⭐ 50.1k — Obsidian CEO 发布的智能体技能，教智能体使用 Obsidian CLI 及 Markdown、Bases、JSON Canvas 等开放格式。
- [vercel-labs/skills (npx skills)](https://github.com/vercel-labs/skills) ⭐ 36.6k — 开放智能体技能生态的命令行工具，可在 Claude Code、Codex、Cursor、OpenCode 等 75 款以上智能体中添加、查找、更新和移除技能。
- [Awesome Agent Skills (VoltAgent)](https://github.com/VoltAgent/awesome-agent-skills) ⭐ 36.4k — 精选 1000 多个来自官方团队和社区的智能体技能，兼容 Claude Code、Codex、Gemini CLI 和 Cursor。
- [Planning with Files](https://github.com/OthmanAdi/planning-with-files) ⭐ 27.7k — 面向长时间运行智能体任务的文件式持久规划技能：计划保存在磁盘上以应对上下文丢失，支持会话恢复和完成检查。
- [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) ⭐ 15.2k — 技能生成工具，可将文档网站、GitHub 仓库和 PDF 转换为 Claude 技能，并自动检测冲突。
- [Trail of Bits Skills](https://github.com/trailofbits/skills) ⭐ 7.8k — Trail of Bits 发布的 Claude Code 技能集，用于安全研究、漏洞检测和代码审计工作流。
- [Claude_skills_zh-CN](https://github.com/LeastBit/Claude_skills_zh-CN) 🇨🇳 ⭐ 599 — Anthropic 官方 skills 仓库的中文学习版，汉化了 Word/PDF/PPT/Excel 处理、前端设计等官方技能，便于中文用户理解与改造。
- [SkillsMP](https://skillsmp.com) 🌐 — 社区技能市场，索引 GitHub 上数百万开源智能体技能，可按类别或职业搜索，并提供 REST API 和 MCP 服务器。
- [skill-creator (Anthropic)](https://github.com/anthropics/skills/tree/main/skills/skill-creator) — Anthropic 官方元技能，用于创建、修改和评估新技能，附带脚本、参考资料和评测查看器。
- [Claude Code docs: Extend Claude with skills](https://code.claude.com/docs/en/skills) 📘 — Claude Code 官方技能编写指南；自定义斜杠命令现已并入技能体系，.claude/commands 目录仍可继续使用。

<a id="subagents"></a>
### 子代理 Subagents

<sub>拥有独立提示词、工具与上下文窗口的专用代理。</sub>

- 🏆 **[The Agency (agency-agents)](https://github.com/msitarzewski/agency-agents)** ⭐ 164k — 爆红的“完整 AI 代理公司”项目，包含 230 多个职责、流程和交付物明确的专家智能体角色，原生 .md 文件可直接放入 ~/.claude/agents。
- 🏆 **[wshobson/agents](https://github.com/wshobson/agents)** ⭐ 41.7k — 跨平台插件市场，以 94 个细分插件提供 200 多个智能体、185 个技能和 105 个命令，支持 Claude Code、Codex、Cursor 等。
- 🏆 **[awesome-claude-code-subagents (VoltAgent)](https://github.com/VoltAgent/awesome-claude-code-subagents)** ⭐ 26.1k — 收录 10 大类、161 个以上专业 Claude Code 子智能体，可通过插件市场按类别安装，也可用交互式脚本安装。
- [contains-studio/agents](https://github.com/contains-studio/agents) ⭐ 12.4k — 按工作室部门组织的 37 个智能体，覆盖工程、设计、营销、产品、测试和运营，用于快速开发应用。
- [awesome-claude-agents (vijaythecoder)](https://github.com/vijaythecoder/awesome-claude-agents) ⭐ 4.4k — 由 24 个子智能体组成的协同开发团队，包括编排者、框架专家和通用专家，分工协作完成功能开发。
- [lst97/claude-code-sub-agents](https://github.com/lst97/claude-code-sub-agents) ⭐ 1.7k — 面向全栈开发的 33 个专业子智能体，包含可将任务分派给合适专家的 agent-organizer。
- [A List of Claude Code Agents](https://github.com/hesreallyhim/a-list-of-claude-code-agents) ⭐ 1.4k — awesome-claude-code 维护者整理的社区投稿 Claude Code 子智能体索引，被动维护、未经筛选。
- [0xfurai/claude-code-subagents](https://github.com/0xfurai/claude-code-subagents) ⭐ 1k — 100 多个可用于生产的开发子智能体，多为针对具体语言和框架的专家。

<a id="commands"></a>
### 斜杠命令

<sub>通过 /命令 调用的可复用提示词。</sub>

- 🏆 **[SuperClaude Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework)** ⭐ 23.9k — 为 Claude Code 增加 30 个斜杠命令、20 个智能体、认知角色和行为模式的配置框架，覆盖从头脑风暴到部署的开发全流程。
- [Claude Code Spec Workflow](https://github.com/Pimzino/claude-code-spec-workflow) ⭐ 3.9k — 用于规格驱动开发（需求→设计→任务→实现）和结构化修 bug 的斜杠命令工作流。
- [cc-sdd](https://github.com/gotalab/cc-sdd) 🇯🇵 ⭐ 3.7k — Kiro 风格的规格驱动开发工具，通过 /kiro-* 斜杠技能把已批准的规格转化为长时间自主实现。
- [TÂCHES CC Resources](https://github.com/glittercowboy/taches-cc-resources) ⭐ 2k — 热门命令与技能合集：元提示、待办管理、上下文交接、/consider 思维模型，以及技能、子智能体和钩子的生成器。
- [Claude Command Suite](https://github.com/qdhenry/Claude-Command-Suite) ⭐ 1.4k — 200 多个专业斜杠命令，另附 50 多个智能体和 12 个技能，用于代码审查、功能开发、安全审计和架构分析。
- [Claude Code Tresor](https://github.com/alirezarezvani/claude-code-tresor) ⭐ 783 — Claude Code 实用工具合集，包含斜杠命令、自主技能、专家智能体和开发工作流提示词。
- [Claude Code docs: Commands reference](https://code.claude.com/docs/en/commands) 📘 — Claude Code 内置斜杠命令及捆绑技能（如 /help、/compact、/code-review）的官方参考。

<a id="hooks"></a>
### 钩子 Hooks

<sub>在 Claude Code 生命周期事件上运行的命令：安全防护、格式化、通知等。</sub>

- 🏆 **[Claude Code Hooks Mastery](https://github.com/disler/claude-code-hooks-mastery)** ⭐ 4k — IndyDevDan 的实战参考项目，用 uv Python 脚本实现所有钩子事件：语音播报、日志、安全防护、状态栏和子智能体控制。
- 🏆 **[Claude Code docs: Hooks reference](https://code.claude.com/docs/en/hooks)** 📘 — 官方钩子参考：30 多个生命周期事件（PreToolUse、Stop、SessionStart、PreCompact 等），支持 command、HTTP、MCP、prompt 和 agent 等处理器。
- [Destructive Command Guard (dcg)](https://github.com/Dicklesworthstone/destructive_command_guard) ⭐ 6.2k — 基于 Rust 的高速 PreToolUse 钩子，在智能体执行前拦截 rm -rf、hard reset、强制推送等危险 Git 和 Shell 命令。
- [peon-ping](https://github.com/PeonPing/peon-ping) ⭐ 5.1k — Claude Code 任务完成、请求权限或出错时，用魔兽争霸 III 苦工等 165 多套游戏语音提醒你，也支持 Codex、Cursor 和各类 IDE。
- [TDD Guard](https://github.com/nizos/tdd-guard) ⭐ 2.4k — 基于钩子的 Claude Code 自动化 TDD 约束工具，阻止跳过失败测试或过度实现的代码改动。
- [CC Safety Net](https://github.com/kenryu42/cc-safety-net) ⭐ 1.8k — 在工具调用执行前拦截破坏性 Git、文件系统命令和敏感文件访问的防护钩子，支持多种编程 CLI。
- [Awesome Claude Code Mods](https://github.com/karanb192/awesome-claude-code-mods) ⭐ 762 — 公开 Claude Code Mods（函数钩子）的社区目录，逐一扫描每个 Mod 能读取、写入、执行或联网发送的内容。
- [shanraisshan/claude-code-hooks](https://github.com/shanraisshan/claude-code-hooks) ⭐ 563 — 为每个 Claude Code 钩子事件添加语音/音效反馈，跟进最新 Claude Code 版本的 30 个钩子。
- [karanb192/claude-code-hooks](https://github.com/karanb192/claude-code-hooks) ⭐ 559 — 钩子合集兼可安装的插件市场：拦截危险命令、保护密钥、Git 安全、指令审计、成本追踪和会话日志。
- [cchooks](https://github.com/GowayLee/cchooks) ⭐ 131 — 用于编写 Claude Code 钩子的 Python SDK：解析 stdin JSON，支持全部事件类型，可用简单退出码或高级 JSON 控制。
- [Claude Code docs: Mods overview](https://code.claude.com/docs/en/plugins/mods/overview) 📘 — Mods 文档：Mods 是带有进程内 JavaScript/TypeScript 钩子的插件，可拦截工具调用、添加即时命令，并在 Claude Code 界面中绘制面板。
- [Official sample mods (claude-code-playground)](https://github.com/anthropics/claude-code-playground/tree/main/claude-code/mods) — Anthropic 官方示例 Mods：token-weather 上下文预报、拦截危险命令的 blast-radius，以及逐步回放上一轮编辑的 replay-theater。
- [hookify (official plugin)](https://github.com/anthropics/claude-code/tree/main/plugins/hookify) — 官方插件，可根据对话模式或明确指令生成自定义钩子，阻止不希望出现的行为。

<a id="plugins"></a>
### 插件与插件市场

<sub>打包命令、代理、技能、钩子与 MCP 服务器的可安装插件。</sub>

- [Understand Anything](https://github.com/Egonex-AI/Understand-Anything) ⭐ 88.3k — Claude Code 插件，借助多智能体流水线把代码库或文档转化为可交互、可查询的知识图谱。
- [Compound Engineering Plugin](https://github.com/EveryInc/compound-engineering-plugin) ⭐ 25.7k — Every 官方的复利工程插件：以“规划—执行—评审—沉淀”循环让每次工作都让下一次更轻松。
- [Claude Plugins Community](https://github.com/anthropics/claude-plugins-community) ⭐ 4.8k — Anthropic 面向 Claude Code 和 Cowork 的只读社区插件市场镜像，插件经网页表单提交并通过安全扫描后上架。
- [Build with Claude](https://github.com/davepoon/buildwithclaude) ⭐ 3.7k — Claude 技能、智能体、命令、钩子和插件的聚合中心兼插件市场，配套 buildwithclaude.com 发现站点。
- [Claude Code Plugins Plus Skills (Tons of Skills)](https://github.com/jeremylongshore/tons-of-skills-marketplace) ⭐ 2.9k — 大型插件市场，提供 400 多个插件和约 2900 个技能，配套 ccpi 包管理器，可在 tonsofskills.com 浏览。
- [Awesome Claude Plugins (Composio)](https://github.com/composio-community/awesome-claude-plugins) ⭐ 2k — 精选 Claude Code 插件清单，收录通过插件系统添加自定义命令、智能体、钩子和 MCP 服务器的插件。
- [claude-plugins.dev](https://github.com/Kamalnrf/claude-plugins) ⭐ 562 — 轻量级注册表与 CLI，用于发现、安装和管理公开的 Claude 插件与智能体技能，可在 claude-plugins.dev 浏览。
- [Claude Marketplace: Plugins](https://claude.com/marketplace/plugins) 🌐 — Anthropic 的网页插件目录，收录 300 多个集成工具、技能和连接器的插件，适用于 Claude Code 和 claude.ai，如 Frontend Design、Superpowers、Context7。
- [Claude Code demo plugins](https://github.com/anthropics/claude-code/tree/main/plugins) — Claude Code 仓库中的 Anthropic 示例插件：code-review、feature-dev、frontend-design、pr-review-toolkit、plugin-dev、security-guidance 等。
- [Ralph Wiggum plugin](https://github.com/anthropics/claude-code/tree/main/plugins/ralph-wiggum) — 实现“Ralph Wiggum”循环的官方插件：通过 Stop 钩子反复投喂同一提示，让 Claude 持续迭代任务直到输出完成标记。
- [Claude Code Marketplaces](https://claudemarketplaces.com) 🌐 — 独立的 Claude Code 插件市场目录，收录 2700 多个插件市场，并索引技能和 MCP 服务器。

<a id="claude-md"></a>
### CLAUDE.md、配置与模板

<sub>入门套件、记忆文件、设置与输出风格。</sub>

- 🏆 **[ECC (Everything Claude Code)](https://github.com/affaan-m/ECC)** ⭐ 289k — 超大型智能体配置体系：71 个智能体、300 多个技能、钩子、规则、记忆以及 AgentShield 安全扫描，支持 Claude Code、Codex、Cursor 等。
- 🏆 **[Claude Code Templates (aitmpl)](https://github.com/davila7/claude-code-templates)** ⭐ 32.9k — 命令行工具及 aitmpl.com 模板目录，可一键安装智能体、命令、设置、钩子、MCP 和技能，并提供数据分析、会话监控和健康检查。
- [Claude Code Infrastructure Showcase](https://github.com/diet103/claude-code-infrastructure-showcase) ⭐ 10k — 真实 Claude Code 基础设施的参考示例：通过钩子自动激活技能、专业智能体及配套配置。
- [Claude Code Showcase](https://github.com/ChrisWiles/claude-code-showcase) ⭐ 6.1k — 完整的项目配置示例，涵盖钩子、技能、智能体、命令和 GitHub Actions 工作流。
- [Agent Rules Books](https://github.com/ciembor/agent-rules-books) ⭐ 3.1k — 从经典工程书籍（整洁代码、重构、DDD、整洁架构等）提炼的 AGENTS.md 规则与技能，适用于 Claude Code、Codex 和 Cursor。
- [My Claude Code Setup (centminmod)](https://github.com/centminmod/my-claude-code-setup) ⭐ 2.7k — 共享的入门模板配置与 CLAUDE.md 记忆库体系，持续更新新模板。
- [Trail of Bits Claude Code Config](https://github.com/trailofbits/claude-code-config) ⭐ 2.1k — Trail of Bits 出品的注重安全的 Claude Code 默认配置、文档和工作流。
- [claude-code-settings (feiskyer)](https://github.com/feiskyer/claude-code-settings) 🇨🇳 ⭐ 1.7k — 精选的 Claude Code 设置、技能、子智能体和配置模板，涵盖研究、图像生成、GitHub 自动化等。
- [Claude Code Development Kit](https://github.com/peterkrueck/Claude-Code-Development-Kit) ⭐ 1.4k — 面向初中级用户的结构化工作流套件：分层文档体系、CLAUDE.md 上下文、钩子和命令，附教程与安装器。
- [Awesome CLAUDE.md](https://github.com/josix/awesome-claude-md) ⭐ 618 — 精选公开 GitHub 项目中优秀的 CLAUDE.md 文件，附分析、最佳实践和模板。
- [Claude Code docs: Output styles](https://code.claude.com/docs/en/output-styles) 📘 — 官方输出风格指南：通过 Markdown 文件改变 Claude 的回复方式，包含内置风格和放在 .claude/output-styles 中的自定义风格。
- [AGENTS.md](https://agents.md) 🌐 — 由 Agentic AI Foundation 托管的开放“智能体 README”指令文件格式；Claude Code 可将 AGENTS.md 作为项目指令加载。

<div align="right"><a href="#top">↑ 返回顶部</a></div>

---

<a id="workflows"></a>
## 🧭 工作流与编排

_规模化使用 Claude Code 的方法论与运行器：规格驱动开发、并行代理与长期记忆。_

<a id="frameworks"></a>
### 框架与方法论

<sub>用于规划、编写规格与交付的成套代理开发体系。</sub>

- 🏆 **[Spec Kit](https://github.com/github/spec-kit)** ⭐ 143k — GitHub 官方开源的规格驱动开发（SDD）工具包，提供 constitution、specify、plan、tasks、implement 等命令，适用于 Claude Code 及其他代理。
- 🏆 **[BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD)** ⭐ 54.6k — 敏捷 AI 驱动开发方法论：由分析师、产品经理、架构师、开发、QA 等角色代理贯穿软件生命周期，产出规划文档与用户故事。
- 🏆 **[GSD Core (Get Shit Done)](https://github.com/open-gsd/gsd-core)** ⭐ 10.9k — 轻量级元提示、上下文工程与规格驱动开发系统，引导代理按可重复的阶段循环工作；get-shit-done 的延续项目。
- [OpenSpec](https://github.com/Fission-AI/OpenSpec) ⭐ 73k — 面向 AI 编程助手的轻量级规格驱动开发，以变更提案的提出、评审与归档为核心，尤其适合存量项目。
- [Task Master](https://github.com/eyaltoledano/claude-task-master) ⭐ 28.3k — AI 任务管理系统，把 PRD 拆解为带依赖关系的任务，可通过 MCP 或 CLI 在 Claude Code、Cursor 等工具中使用。
- [Archon](https://github.com/coleam00/Archon) ⭐ 23.8k — 工作流引擎，用 YAML 定义计划、实现、验证、提交 PR 等步骤，让 Claude Code、Codex 或 Pi 的运行确定且可重复。
- [Trellis](https://github.com/mindfold-ai/Trellis) 🇨🇳 ⭐ 15k — 面向团队的 AI 编码框架，把臃肿的 CLAUDE.md 拆成渐进加载的规范、任务、工作流与记忆，通过 hooks 自动注入，支持 Claude Code/Cursor/Codex，有中文文档。
- [Plannotator](https://github.com/backnotprop/plannotator) ⭐ 9.6k — 可视化工具，用于批注和审阅代理的计划与代码差异，可与团队共享，并一键把反馈发回代理。
- [Harness](https://github.com/revfactory/harness) ⭐ 9.3k — Claude Code 元技能插件，把自然语言需求转化为特定领域的代理团队及其所需的技能与编排。
- [CCPM](https://github.com/automazeio/ccpm) ⭐ 8.4k — 基于 GitHub Issues 与 git worktree 的 Claude Code 项目管理系统：PRD 转化为史诗与任务，由并行代理执行。
- [AI Dev Tasks](https://github.com/snarktank/ai-dev-tasks) ⭐ 7.8k — 简洁的 Markdown 提示集，引导代理从编写 PRD 到生成任务清单，再到逐步、可审查的实现。
- [Ouroboros](https://github.com/Q00/ouroboros) ⭐ 6.3k — 规格优先的“代理操作系统”插件，执行访谈、规格、执行、评估、演进循环，带分阶段评估，通过 MCP 提供服务。
- [Agent OS](https://github.com/buildermethods/agent-os) ⭐ 5.5k — Builder Methods 推出的系统，为代理注入代码库规范，并帮助编写更好的规格以进行规格驱动开发。
- [Spec Workflow MCP](https://github.com/Pimzino/spec-workflow-mcp) ⭐ 4.3k — 提供结构化规格驱动工作流工具的 MCP 服务器，附带实时 Web 仪表盘和 VS Code 扩展用于跟踪进度。
- [Claude Code Harness](https://github.com/Chachamaru127/claude-code-harness) ⭐ 3.2k — 面向 Claude Code 的计划—执行—评审开发框架，规格存于 spec.md、任务存于 Plans.md，由动词式技能驱动。
- [Advanced Context Engineering for Coding Agents](https://github.com/humanlayer/advanced-context-engineering-for-coding-agents) ⭐ 2.8k — HumanLayer 关于编程代理上下文工程的文章与基准测试，涵盖面向大型代码库的“调研—计划—实现”工作流。
- [PRP (Product Requirement Prompts)](https://github.com/Wirasm/prp) ⭐ 2.3k — 基于产品需求提示（PRP）的代理式工程提示、命令与工作流：用富上下文规格让 Claude Code 一次成型交付。
- [claude-code-cookbook](https://github.com/wasabeef/claude-code-cookbook) 🇯🇵 ⭐ 1.1k — Claude Code 命令、角色和 hooks 配置合集，文档提供日文、英文等八种语言。
- [tsumiki](https://github.com/classmethod/tsumiki) 🇯🇵 ⭐ 974 — Classmethod 推出的 AI 驱动开发框架，以 Claude Code 插件形式安装，覆盖从需求定义到实现。

<a id="orchestration"></a>
### 多代理与并行会话

<sub>在 worktree、后台或集群中并行运行多个 Claude Code 会话。</sub>

- 🏆 **[Orca](https://github.com/stablyai/orca)** ⭐ 106k — MIT 许可的桌面编排器（附移动端），可在 git worktree 中并排运行大量 Claude Code、Codex 等 CLI 代理。
- 🏆 **[Ruflo (formerly Claude Flow)](https://github.com/ruvnet/ruflo)** ⭐ 79.4k — 用于部署多代理集群与自主工作流的代理框架，具备自适应记忆、联邦与向量 RAG；最初围绕 Claude Code 构建。
- 🏆 **[Claude Squad](https://github.com/smtg-ai/claude-squad)** ⭐ 8.7k — 终端应用，在 tmux 中管理多个 Claude Code、Codex、OpenCode 或 Amp 会话，每个会话隔离在独立的 git worktree 中。
- [Paperclip](https://github.com/paperclipai/paperclip) ⭐ 107k — 自托管平台，把 Claude Code 等代理编排成一家“公司”，提供组织架构、工单跟踪、预算与治理。
- [Multica](https://github.com/multica-ai/multica) ⭐ 53.8k — 可自托管的工作区，把 issue 分配给 Claude Code 等编程代理，它们会像同事一样汇报进度与阻塞。
- [herdr](https://github.com/herdrdev/herdr) ⭐ 45.9k — Rust 编写的终端运行时，让编程代理会话在后台持续运行，标记各窗格为工作、阻塞或空闲，并允许代理互相控制。
- [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) 🇰🇷 ⭐ 40.3k — 以团队为先的 Claude Code 多代理编排层，提供 Team、Autopilot、Execute、Verify 等模式，并可用 tmux 调度其他 CLI。
- [Vibe Kanban](https://github.com/BloopAI/vibe-kanban) ⭐ 28.5k — 看板工具，用于规划、运行和审阅 Claude Code、Codex 等编程代理，每个代理在独立 worktree 中工作。
- [Paseo](https://github.com/getpaseo/paseo) ⭐ 22.1k — Apache-2.0 许可的代理式开发环境，可在桌面、移动端、Web 或 CLI 上于 worktree 中运行包括 Claude Code 在内的多个代理。
- [Ralph](https://github.com/snarktank/ralph) ⭐ 22.1k — 自主 AI 代理循环，以全新上下文反复运行编程代理，直到 PRD 中的所有条目完成。
- [Gas Town](https://github.com/gastownhall/gastown) ⭐ 18.5k — Steve Yegge 打造的多代理工作区管理器，用 git 持久化工作状态，通过代理邮件和合并队列协调大量 Claude Code 代理。
- [cc-connect](https://github.com/chenhg5/cc-connect) 🇨🇳 ⭐ 16.1k — 将本地 Claude Code 等编程代理接入飞书、钉钉、Slack、Telegram、Discord、企业微信、LINE、QQ 等聊天平台的桥接工具。
- [Superset](https://github.com/superset-sh/superset) ⭐ 15.6k — 代理式 IDE 与终端，可跨 git worktree 并行编排大量 Claude Code 与 Codex 代理。
- [Aperant (formerly Auto Claude)](https://github.com/AndyMik90/Aperant) ⭐ 14.6k — 自主多会话编程桌面应用，可同时运行最多 12 个代理终端，并带有规划与 QA 循环。
- [Agent Orchestrator](https://github.com/OrchestratorInc/agent-orchestrator) ⭐ 13.7k — 运行并监督编程代理团队（含 Claude Code），覆盖从规划到合并的全过程，支持多种代理框架与平台。
- [Ralph for Claude Code](https://github.com/frankbria/ralph-claude-code) ⭐ 9.7k — 面向 Claude Code 的自主开发循环，具备智能退出检测和防止失控迭代的保护机制。
- [Worktrunk](https://github.com/max-sixty/worktrunk) ⭐ 9.5k — Rust 编写的 git worktree 管理 CLI，专为并行 AI 代理工作流设计。
- [Emdash](https://github.com/generalaction/emdash) ⭐ 6.1k — 来自 YC W26 团队的开源代理式开发环境，可跨提供商并行运行多个编程代理。
- [CCG Workflow](https://github.com/fengshao1227/ccg-workflow) 🇨🇳 ⭐ 5.9k — 多模型协作工作流：以 Claude Code 为总指挥，编排 Codex、Gemini 等协同开发，一条 /ccg:go 命令自动分析意图与执行，外部模型只返回补丁。
- [Background Agents](https://github.com/ColeMurray/background-agents) ⭐ 3.4k — 开源后台编程代理系统：被触发的代理会话在沙箱中运行，并提交带署名的 Pull Request。
- [Claude Code Telegram](https://github.com/overwirehq/claude-code-telegram) ⭐ 2.8k — Telegram 机器人，提供带会话持久化的 Claude Code 远程访问，可在任意设备上处理项目。
- [MCP Agent Mail](https://github.com/Dicklesworthstone/mcp_agent_mail) ⭐ 2.2k — 编程代理的异步协作层，提供身份、收件箱、线程与建议性文件租约，通过 MCP 暴露。
- [Nimbalyst (formerly Crystal)](https://github.com/nimbalyst/nimbalyst) ⭐ 2k — 开源可视化工作区，可在并行 worktree 中运行 Claude Code、Codex 与 OpenCode，提供看板、可视化编辑和 iOS 配套应用。
- [CLI Agent Orchestrator](https://github.com/awslabs/cli-agent-orchestrator) ⭐ 1.5k — AWS Labs 工具，以主管与工作者模式在隔离的 tmux 会话中协调 Claude Code、Kiro、Codex 等多个编程 CLI。
- [CCManager](https://github.com/kbwo/ccmanager) 🇯🇵 ⭐ 1.3k — 会话管理器，可在多个 git worktree 间运行并切换 Claude Code、Gemini CLI 与 Codex CLI 会话。
- [Conductor](https://www.conductor.build) 🌐 — Melty Labs 出品的 Mac 应用，可在隔离工作区中同时运行多个 Claude Code、Codex 与 Cursor 代理，并审阅、合并其成果。

<a id="memory-context"></a>
### 记忆与上下文

<sub>持久记忆、代码库索引与上下文工程。</sub>

- 🏆 **[claude-mem](https://github.com/thedotmack/claude-mem)** ⭐ 103k — 持久记忆插件，通过钩子捕获 Claude Code 会话活动，用 AI 压缩后在后续会话中注入相关上下文。
- 🏆 **[Serena](https://github.com/oraios/serena)** 🇩🇪 ⭐ 30.7k — MCP 工具包，借助语言服务器为编程代理提供类 IDE 的语义代码检索与符号级编辑，是 Claude Code 的热门搭档。
- 🏆 **[Beads](https://github.com/gastownhall/beads)** ⭐ 28.2k — Steve Yegge 开发的基于 git 的问题跟踪器，为编程代理提供工作项、依赖与进度的持久记忆。
- [Graphify](https://github.com/Graphify-Labs/graphify) ⭐ 136k — 把代码、文档、SQL 模式、配置与 PDF 转为可查询的知识图谱，并为 Claude Code 安装 /graphify 技能。
- [Headroom](https://github.com/headroomlabs-ai/headroom) ⭐ 77.9k — 压缩层，在工具输出、日志、文件和 RAG 片段送达模型前进行压缩，降低编程代理的 token 消耗。
- [codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) ⭐ 47.5k — 代码智能 MCP 服务器，把代码库索引为持久知识图谱，支持快速且节省 token 的结构化查询。
- [code-review-graph](https://github.com/tirth8205/code-review-graph) ⭐ 32.4k — 本地代码智能图谱，支持 MCP 与 CLI，让 AI 工具只读取相关代码，从而减少 token 消耗。
- [context-mode](https://github.com/mksglu/context-mode) ⭐ 32.3k — Claude Code 插件与 MCP 服务器，把庞大的工具输出挡在上下文之外，用 SQLite 持久化会话状态并在压缩后恢复。
- [Repomix](https://github.com/yamadashy/repomix) 🇯🇵 ⭐ 29k — 把整个仓库打包成单个 AI 友好的文件供大模型读取，可作为 CLI 或 MCP 服务器使用。
- [Claude Obsidian](https://github.com/AgriciDaniel/claude-obsidian) ⭐ 15.8k — Obsidian 与 Claude Code 组合的“第二大脑”，把资料归档为自组织、相互链接的 Markdown 知识图谱。
- [Claude Context](https://github.com/zilliztech/claude-context) 🇨🇳 ⭐ 12.6k — Zilliz 推出的语义代码搜索 MCP 服务器，把整个代码库索引进向量数据库，作为编程代理的上下文。
- [Autoharness](https://github.com/tigerless-labs/autoharness) ⭐ 10.8k — Claude Code 自学习技能层：钩子记录会话，后台反思器提炼、更新并清理 .claude/skills 中的技能。
- [Trail-Code](https://github.com/trailhq/Trail-Code) ⭐ 10.8k — 自学习上下文层，将 tree-sitter 代码图谱与团队保存的经验结合，通过钩子和 MCP 服务器注入 Claude Code。
- [Engram](https://github.com/Gentleman-Programming/engram) ⭐ 7.6k — 与代理无关的持久记忆系统，以单个 Go 二进制文件发布，使用 SQLite 存储并提供 MCP 接口。
- [Continuous Claude v3](https://github.com/parcadei/Continuous-Claude-v3) ⭐ 3.9k — Claude Code 上下文管理方案，借助钩子、账本、交接文档与隔离代理，在上下文压缩和会话之间保留状态。
- [Ruler](https://github.com/intellectronica/ruler) ⭐ 3k — 用同一份规则源统一管理所有编程代理，自动生成并同步 CLAUDE.md、AGENTS.md 等代理指令文件。
- [Claude Supermemory](https://github.com/supermemoryai/claude-supermemory) ⭐ 2.8k — 让 Claude Code 实时学习并借助 Supermemory 跨会话调用知识的插件。
- [Claude Reflect](https://github.com/BayramAnnakov/claude-reflect) ⭐ 1.9k — 自学习系统，捕获你在会话中的纠正，并同步写入 CLAUDE.md 与 AGENTS.md。
- [rulesync](https://github.com/dyoshikawa/rulesync) 🇯🇵 ⭐ 1.6k — CLI 工具，从单一来源为 Claude Code 及其他 AI 编程代理生成并同步规则与配置文件。

<div align="right"><a href="#top">↑ 返回顶部</a></div>

---

<a id="tooling"></a>
## 🛠️ 工具链

_围绕 CLI 的周边工具：用量统计、状态栏、图形界面、编辑器集成、模型路由、沙箱、CI 与可观测性。_

<a id="usage-monitoring"></a>
### 用量与成本监控

<sub>统计 Token、费用与限额窗口。</sub>

- 🏆 **[CodexBar](https://github.com/steipete/CodexBar)** ⭐ 22.8k — Peter Steinberger 开发的 macOS 菜单栏应用，无需登录即可显示 Claude Code 和 OpenAI Codex 的用量统计与额度。
- 🏆 **[ccusage](https://github.com/ccusage/ccusage)** 🇯🇵 ⭐ 19.2k — 免安装 CLI（npx ccusage），分析本地 Claude Code JSONL 日志，按日、月、会话和 5 小时窗口统计 token 用量与费用。
- [CodeBurn](https://github.com/getagentseal/codeburn) ⭐ 11.6k — 免费本地工具，追踪 37 种 AI 编程工具的 token 用量和费用，按项目、模型和任务细分，并找出 token 浪费。
- [Claude Code Usage Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) ⭐ 8.8k — 实时终端监控 Claude Code 用量，提供消耗速率预测、套餐额度预警和会话重置跟踪。
- [Tokscale](https://github.com/junhoyeo/tokscale) 🇰🇷 ⭐ 5.7k — 终端工具，追踪 Claude Code 等 AI 编程智能体的 token 用量，并提供可选的全球用量排行榜。
- [Claude Usage Tracker](https://github.com/hamed-elfayome/Claude-Usage-Tracker) ⭐ 3.7k — 基于 Swift/SwiftUI 的原生 macOS 菜单栏应用，实时追踪 Claude 会话与每周用量额度。
- [Clawdmeter](https://github.com/HermannBjorgvin/Clawdmeter) ⭐ 2.3k — 基于 ESP32 的硬件显示屏，在桌面小屏幕上实时显示你的 Claude Code 用量。
- [claude-usage](https://github.com/phuryn/claude-usage) ⭐ 2.3k — 本地仪表盘，追踪 Claude Code 的 token 用量、费用和会话历史，面向 Pro 和 Max 订阅用户。
- [ClaudeBar](https://github.com/tddworks/ClaudeBar) ⭐ 1.6k — macOS 菜单栏应用，显示 Claude、Codex、Gemini、Copilot 等 AI 编程助手的剩余额度，并提供消耗速率指示。
- [Sniffly](https://github.com/chiphuyen/sniffly) ⭐ 1.3k — Chip Huyen 开发的 Claude Code 仪表盘，基于本地日志展示用量统计、错误分析和可分享的报告。

<a id="statusline"></a>
### 状态栏 Statusline

<sub>Claude Code 终端界面的自定义状态栏。</sub>

- 🏆 **[Claude HUD](https://github.com/jarrodwatts/claude-hud)** ⭐ 28.9k — Claude Code 插件，把状态栏变成 HUD，显示上下文占用、正在使用的工具、运行中的子代理和待办进度。
- 🏆 **[ccstatusline](https://github.com/sirmalloc/ccstatusline)** ⭐ 13.4k — 高度可定制的 Claude Code 状态栏，带交互式 TUI 配置器、powerline 主题，以及模型、git、token、上下文和用量等组件。
- [CCometixLine](https://github.com/Haleclipse/CCometixLine) 🇨🇳 ⭐ 3.5k — 用 Rust 编写的高性能 Claude Code 状态栏，包含 git、模型和上下文等分段，支持 TUI 主题配置和 Claude Code 增强工具。
- [claude-powerline](https://github.com/Owloops/claude-powerline) ⭐ 1.2k — Vim 风格的 Claude Code powerline 状态栏，支持实时用量与费用追踪、git 集成和自定义主题。
- [cc-statusline](https://github.com/chongdashu/cc-statusline) ⭐ 646 — 交互式配置工具，生成并安装信息丰富的 Claude Code 状态栏脚本，显示模型、目录、git、上下文和费用。
- [claude-code-statusline (rz1989s)](https://github.com/rz1989s/claude-code-statusline) ⭐ 480 — 功能丰富的 Claude Code 状态栏，支持灵活的多行布局、实时费用追踪、MCP 状态和可配置主题。
- [claude-statusbar (claude-code-usage-bar)](https://github.com/leeguooooo/claude-code-usage-bar) ⭐ 384 — 轻量级状态栏，显示 5 小时和 7 天限额用量及重置倒计时、上下文窗口、提示缓存过期时间和会话费用。
- [Status line docs (official)](https://code.claude.com/docs/en/statusline) 📘 — 官方指南：通过 settings.json 和从 stdin 接收会话 JSON 的脚本来配置 Claude Code 自定义状态栏。

<a id="gui-clients"></a>
### 图形界面、Web 与移动端

<sub>驱动 Claude Code 的桌面应用、Web 界面与手机客户端。</sub>

- 🏆 **[AionUi](https://github.com/iOfficeAI/AionUi)** 🇨🇳 ⭐ 33.8k — 开源跨平台协作桌面应用，为 Claude Code、Codex、OpenCode 及 20 多种 CLI 代理提供图形界面。
- 🏆 **[Happy](https://github.com/slopus/happy)** ⭐ 24.3k — 开源移动端与桌面客户端，可远程运行和控制 Claude Code 与 Codex 会话，支持端到端加密、推送通知和语音。
- 🏆 **[opcode](https://github.com/winfunc/opcode)** ⭐ 22.4k — Claude Code 桌面 GUI 与工具集（前身为 Claudia）：管理会话、创建自定义代理、追踪用量并配置 MCP 服务器。
- 🏆 **[CloudCLI (Claude Code UI)](https://github.com/siteboon/claudecodeui)** ⭐ 14.3k — Web 与移动端 PWA，可远程驱动 Claude Code、Codex、Cursor CLI 和 OpenCode，内置文件浏览、git、终端和会话管理。
- 🏆 **[Claudable](https://github.com/anymorph-ai/Claudable)** ⭐ 4.1k — 开源的类 Lovable 网页应用构建器，借助 Claude Code、Codex 等本地 CLI 代理生成并预览应用。
- [cmux](https://github.com/manaflow-ai/cmux) ⭐ 28.5k — 基于 Ghostty 的开源 macOS 终端，带垂直标签页和通知，专为运行 Claude Code 等 AI 编程代理而设计。
- [CodePilot](https://github.com/op7418/CodePilot) 🇨🇳 ⭐ 6.5k — AI 博主歸藏（op7418）开发的多模型 Agent 桌面客户端，支持 MCP 与 Skills，可用手机远程控制，基于 Electron + Next.js。
- [VibeTunnel](https://github.com/amantus-ai/vibetunnel) ⭐ 4.7k — 把任意浏览器变成你的终端，随时随地（包括手机上）监控和操控 Claude Code 等代理。
- [Vibe Notch (formerly Claude Island)](https://github.com/farouqaldori/vibe-notch) ⭐ 2.5k — macOS 刘海应用，以灵动岛风格显示 Claude Code 会话状态，并可在浮层中批准或拒绝工具权限请求。
- [claude-code-viewer](https://github.com/d-kimuson/claude-code-viewer) 🇯🇵 ⭐ 1.3k — 功能完整的 Web 客户端，用于浏览和操作 Claude Code 项目与会话。

<a id="ide"></a>
### IDE 与编辑器集成

<sub>VS Code、JetBrains、Neovim、Emacs、Zed 等。</sub>

- 🏆 **[claudecode.nvim](https://github.com/coder/claudecode.nvim)** ⭐ 3.1k — 纯 Lua 实现的 Neovim 插件，实现 Claude Code 的 IDE 协议，让 Neovim 获得与 VS Code 扩展相同的差异、选区和上下文集成。
- 🏆 **[claude-agent-acp (Zed adapter)](https://github.com/agentclientprotocol/claude-agent-acp)** ⭐ 2.7k — Agent Client Protocol（ACP）适配器，基于 Claude Agent SDK 让 Claude Code 在 Zed 及其他兼容 ACP 的编辑器中运行。
- [Claudian](https://github.com/YishenTu/claudian) ⭐ 15.8k — Obsidian 插件，将 Claude Code（以及 Codex）作为 AI 协作者嵌入你的知识库，可读取并编辑笔记。
- [jetbrains-cc-gui](https://github.com/zhukunpenglinyutong/jetbrains-cc-gui) 🇨🇳 ⭐ 7.3k — 社区开发的 JetBrains IDE 插件，为 Claude Code 和 Codex 提供图形化聊天界面，替代终端操作。
- [claude-code.nvim](https://github.com/greggh/claude-code.nvim) ⭐ 2.1k — Neovim 插件，在终端缓冲区中运行 Claude Code，支持快速切换、文件变更自动重载和 git 根目录识别。
- [agent-shell](https://github.com/xenodium/agent-shell) ⭐ 2k — 原生 Emacs 缓冲区界面，支持 Claude Code、Codex、Gemini CLI 等 ACP 代理，沿用熟悉的快捷键且无需终端模拟。
- [claude-code-ide.el](https://github.com/manzaltu/claude-code-ide.el) ⭐ 1.7k — 基于 MCP 的 Emacs 版 Claude Code IDE 集成，向 Claude 提供诊断信息、基于 ediff 的差异审阅和项目上下文。
- [Claude Code Chat (VS Code)](https://github.com/andrepimenta/claude-code-chat) ⭐ 1.1k — VS Code 扩展，为 Claude Code 提供精致的聊天界面，支持对话历史、检查点和 MCP 服务器管理。
- [claude-code.el](https://github.com/stevemolitor/claude-code.el) ⭐ 747 — Emacs 集成，在终端缓冲区（eat 或 vterm）中运行 Claude Code，并提供发送选区、文件和错误信息的命令。
- [Claude Code for VS Code (official)](https://marketplace.visualstudio.com/items?itemName=anthropic.claude-code) 🌐 — Anthropic 官方 VS Code 扩展，提供原生 Claude Code 面板、内联差异、计划审阅和 @ 引用，也可安装在 VS Code 衍生编辑器中。
- [Claude Code JetBrains plugin (official)](https://plugins.jetbrains.com/plugin/27310-claude-code-beta-) 🌐 — 官方 Claude Code 插件，支持 IntelliJ IDEA、PyCharm、WebStorm、GoLand 等 JetBrains IDE，可在 IDE 中查看差异并共享选区上下文。
- [Xcode 26.3 + Claude Agent SDK](https://www.anthropic.com/news/apple-xcode-claude-agent-sdk) 📝 — Anthropic 公告：Xcode 26.3 原生集成 Claude Agent SDK，将 Claude Code 式的智能体编程带入 Xcode，并通过 MCP 开放 Xcode 能力。

<a id="routers-proxies"></a>
### 模型路由与供应商切换

<sub>让 Claude Code 接入其他模型后端，或在不同供应商与配置间切换。</sub>

- 🏆 **[CC Switch](https://github.com/farion1231/cc-switch)** 🇨🇳 ⭐ 149k — 跨平台桌面应用，为 Claude Code、Codex、OpenCode 等 CLI 代理一键切换 API 服务商，并管理配置、MCP 服务器和技能。
- 🏆 **[Claude Code Router](https://github.com/musistudio/claude-code-router)** 🇨🇳 ⭐ 37.9k — 将 Claude Code 请求路由到其他模型和服务商（DeepSeek、Gemini、OpenRouter、Ollama 等），支持按任务路由规则和请求转换器。
- [ZCF (Zero-Config Code Flow)](https://github.com/UfoMiao/zcf) 🇨🇳 ⭐ 6.1k — 零配置 CLI，一条命令完成 Claude Code 与 Codex 的初始化，包括 API 服务商、工作流、输出风格、MCP 服务和状态栏。
- [claude-code-proxy (1rgs)](https://github.com/1rgs/claude-code-proxy) ⭐ 3.8k — 代理工具，通过 LiteLLM 转换 Anthropic API 请求，让 Claude Code 使用 OpenAI 或 Gemini 模型运行。
- [Claude Code Local](https://github.com/nicedreamzapp/claude-code-local) ⭐ 3.4k — 通过 MLX 原生的 Anthropic API 兼容服务器，在 Apple Silicon 上完全本地运行 Claude Code，使用本地 Qwen、Gemma 和 Llama 模型。
- [claude-code-proxy (fuergaosi233)](https://github.com/fuergaosi233/claude-code-proxy) 🇨🇳 ⭐ 2.8k — 代理工具，将 Claude Code 的 Anthropic API 调用转换为任意 OpenAI 兼容 API，并可配置大小模型映射。
- [ccproxy](https://github.com/starbaser/ccproxy) ⭐ 355 — 基于 LiteLLM 的代理，用于构建 Claude Code 扩展：拦截任意请求、修改响应，并把 /model 路由到自定义模型。
- [LLM gateway configuration (official)](https://code.claude.com/docs/en/llm-gateway) 📘 — 官方指南：通过 LiteLLM 等 LLM 网关运行 Claude Code，实现统一认证、用量追踪、成本控制和路由。
- [LiteLLM: Claude Code Quickstart](https://docs.litellm.ai/docs/tutorials/claude_responses_api) 📘 — LiteLLM 教程：通过 LiteLLM 代理使用 Claude Code，包括路由到非 Anthropic 模型以及追踪花费。
- [OpenRouter: Claude Code Integration](https://openrouter.ai/docs/cookbook/coding-agents/claude-code-integration) 📘 — OpenRouter 指南：通过 ANTHROPIC_BASE_URL 将 Claude Code 接入 OpenRouter，以使用多种模型并获得服务商故障切换。
- [Ollama: Claude Code](https://docs.ollama.com/integrations/claude-code) 📘 — Ollama 文档：通过 Ollama 的 Anthropic 兼容 API，让 Claude Code 使用本地模型或 Ollama 云端模型。
- [Z.ai GLM Coding Plan for Claude Code](https://docs.z.ai/devpack/tool/claude) 📘 🇨🇳 — Z.ai（智谱）指南：通过其 Anthropic 兼容端点和 GLM Coding Plan 在 Claude Code 中使用 GLM 模型。

<a id="sandbox"></a>
### 沙箱与容器

<sub>安全运行代理的隔离环境。</sub>

- 🏆 **[Container Use](https://github.com/dagger/container-use)** ⭐ 4.1k — Dagger 推出的工具，为每个编程代理提供独立的容器环境和 git 分支，让多个代理安全地并行工作。
- [nono](https://github.com/nolabs-ai/nono) ⭐ 4.7k — 内核级强制的代理沙箱（Linux 用 Landlock，macOS 用 Seatbelt），为 Claude Code 等编程代理提供零信任、低开销的隔离。
- [Agent Safehouse](https://github.com/eugene1g/agent-safehouse) ⭐ 2.1k — 基于 macOS sandbox-exec 的封装工具，限制 Claude Code 等本地 AI 代理只能读写其所需的文件。
- [VibeKit](https://github.com/superagent-ai/vibekit) ⭐ 1.9k — 在干净、隔离的沙箱中运行 Claude Code、Codex、Gemini 或任意编程代理，支持敏感数据脱敏和可观测性。
- [ClaudeBox](https://github.com/RchGrav/claudebox) ⭐ 1.2k — 基于 Docker 的 Claude Code 开发环境，支持按项目隔离、预置语言配置和网络防火墙控制。
- [Trail of Bits claude-code-devcontainer](https://github.com/trailofbits/claude-code-devcontainer) ⭐ 958 — Trail of Bits 出品的沙箱化 devcontainer，可安全地以跳过权限模式运行 Claude Code，专为安全审计和不可信代码设计。
- [Code on Incus (coi)](https://github.com/coipond/coi) ⭐ 759 — 为每个 AI 编程代理分配独立的 Incus 隔离机器，具备 root、Docker 和 systemd，并提供主动威胁检测。
- [Docker Sandboxes](https://docs.docker.com/ai/sandboxes) 📘 — Docker 推出的基于微虚拟机的沙箱，可在隔离的文件系统和网络策略下自主运行 Claude Code 等编程代理。
- [Development containers (official)](https://code.claude.com/docs/en/devcontainer) 📘 — 官方参考 devcontainer，带白名单防火墙，用于隔离运行 Claude Code，包括无人值守的 --dangerously-skip-permissions 模式。

<a id="ci-cd"></a>
### CI/CD 与 GitHub 自动化

<sub>在 PR、Issue 与流水线中使用 Claude。</sub>

- [Cyrus](https://github.com/cyrusagents/cyrus) ⭐ 873 — 可自托管的 Claude Code 后台代理，从 Linear、Slack、GitHub 和 GitLab 领取任务，在隔离环境中工作并提交 PR。
- [Claude Hub](https://github.com/claude-did-this/claude-hub) ⭐ 489 — Webhook 服务，将 Claude Code 接入 GitHub 仓库，在 issue 和 PR 中 @ 提及即可触发 AI 代码协助。
- [Claude Code Gitea Action](https://github.com/markwylde/claude-code-gitea-action) ⭐ 165 — claude-code-action 的 Gitea 移植版，在自托管 Gitea 仓库中支持通过 @claude 进行审查和代码修改。
- [Claude Code Review (managed)](https://code.claude.com/docs/en/code-review) 📘 — Anthropic 托管的多代理 PR 审查服务，面向 GitHub 上的 Team 与 Enterprise 套餐，发布经验证并按严重程度排序的行内问题。
- [Claude Code GitHub Actions docs](https://code.claude.com/docs/en/github-actions) 📘 — 官方指南：配置 Claude Code GitHub Actions 与 Claude GitHub App，附工作流示例以及 Bedrock/Vertex 认证方式。
- [Claude Code GitLab CI/CD docs](https://code.claude.com/docs/en/gitlab-ci-cd) 📘 — 官方指南：在 GitLab CI/CD 流水线中运行 Claude Code，用于创建合并请求、审查变更和处理 @claude 触发的任务。

<a id="observability"></a>
### 日志、会话记录与可观测性

<sub>查看、搜索、导出与追踪代理的所作所为。</sub>

- 🏆 **[claude-trace](https://github.com/badlogic/lemmy/tree/main/apps/claude-trace)** — 记录 Claude Code 发出的每个 API 请求（包括系统提示词和工具定义），生成独立的交互式 HTML 报告。
- [Clawd on Desk](https://github.com/rullerzhou-afk/clawd-on-desk) ⭐ 6.5k — 像素风桌面宠物，实时响应 Claude Code、Codex 和 Cursor 会话，直观显示代理正在思考、工作还是空闲。
- [claude-devtools](https://github.com/matt1398/claude-devtools) ⭐ 4k — 类 DevTools 的 Claude Code 会话日志查看器，可检查工具调用、token 用量、子代理、思考内容和上下文窗口占用。
- [claude-tap](https://github.com/liaohch3/claude-tap) ⭐ 3.3k — 拦截并检查 Claude Code、Codex CLI、Gemini CLI 等编程代理的 API 流量，用于调试和分析。
- [Claude Code History Viewer](https://github.com/jhlee0409/claude-code-history-viewer) ⭐ 2.3k — 桌面应用与 Web 服务，用于浏览、搜索和分析 Claude Code、Codex 等 AI 编程助手的对话历史。
- [claude-code-transcripts](https://github.com/simonw/claude-code-transcripts) ⭐ 1.7k — Simon Willison 开发的工具，把 Claude Code 会话转换为详细的 HTML 页面，并可发布为可分享的 Gist。
- [Claude Code Hooks Multi-Agent Observability](https://github.com/disler/claude-code-hooks-multi-agent-observability) ⭐ 1.6k — 实时仪表盘，捕获多个并发 Claude Code 代理的钩子事件，通过 Bun 服务端和 Vue 界面追踪工具调用与生命周期事件。
- [SpecStory](https://github.com/specstoryai/getspecstory) ⭐ 1.4k — 本地优先的扩展和 CLI，将 Claude Code 等 AI 助手的聊天记录保存为项目内可搜索的 Markdown。
- [claude-code-log](https://github.com/daaain/claude-code-log) ⭐ 1.2k — Python CLI，将 Claude Code 对话 JSONL 文件转换为易读的 HTML 或 Markdown，支持项目层级、日期筛选和 token 统计。
- [Claude Code Agent Monitor](https://github.com/hoangsonww/Claude-Code-Agent-Monitor) ⭐ 1.1k — 可自托管的实时仪表盘，通过钩子监控 Claude Code 与 Codex 代理活动：实时会话、子代理树和工具调用时间线。
- [Claude Code OTel stack](https://github.com/ColeMurray/claude-code-otel) ⭐ 513 — Docker Compose 方案，将 Claude Code 的 OpenTelemetry 指标和日志汇集到 Prometheus、Loki 和 Grafana 仪表盘，监控用量与费用。
- [Monitoring with OpenTelemetry (official)](https://code.claude.com/docs/en/monitoring-usage) 📘 — 官方指南：通过 OpenTelemetry 导出 Claude Code 的指标和事件，用于监控用量、费用和工具活动。

<div align="right"><a href="#top">↑ 返回顶部</a></div>

---

<a id="mcp"></a>
## 🔌 模型上下文协议 MCP

_Claude 连接工具与数据的开放协议：热门服务器、SDK 与目录。_

<a id="mcp-servers"></a>
### MCP 服务器

<sub>常用 MCP 服务器，按连接对象分组。</sub>

**🧑‍💻 开发工具与代码**

- 🏆 **[MCP Reference Servers](https://github.com/modelcontextprotocol/servers)** ⭐ 91.6k — 官方 MCP 参考服务器合集（Everything、Fetch、Filesystem、Git、Memory、Sequential Thinking、Time），并收录大量第三方服务器索引。
- 🏆 **[GitHub MCP Server](https://github.com/github/github-mcp-server)** ⭐ 34k — GitHub 官方 MCP 服务器，支持仓库、Issue、PR、Actions 和代码安全等操作，可本地运行或使用托管远程服务。
- [XcodeBuildMCP (MobileBuildMCP)](https://github.com/getsentry/MobileBuildMCP) ⭐ 6.5k — 让智能体通过 Xcode 和模拟器构建、运行、测试和调试 iOS 与 macOS 项目的 MCP 服务器及 CLI。
- [Atlassian MCP Server (Rovo MCP)](https://github.com/atlassian/atlassian-mcp-server) ⭐ 1.1k — Atlassian 官方远程 MCP 服务器，将 Jira、Confluence、Jira Service Management、Bitbucket、Compass 和 Loom 接入 Claude。
- [Sentry MCP](https://github.com/getsentry/toolkit) ⭐ 947 — Sentry 官方 MCP 服务器（托管于 mcp.sentry.dev），可在智能体中排查生产错误、Issue、链路追踪与根因。
- [GitLab MCP Server](https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server) 📘 — GitLab 内置的 MCP 服务器（Beta），让 Claude 等 AI 工具访问项目、Issue、合并请求和流水线。
- [Linear MCP Server](https://linear.app/docs/mcp) 📘 — Linear 官方托管远程 MCP 服务器，支持 OAuth，可查找、创建和更新 Issue、项目与评论。

**🌐 浏览器自动化**

- 🏆 **[Browser Use](https://github.com/browser-use/browser-use)** ⭐ 119k — 流行的开源 Python AI 浏览器智能体库，也可作为 MCP 服务器供 Claude Desktop 和 Claude Code 使用。
- 🏆 **[Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp)** ⭐ 54.2k — Chrome DevTools 官方 MCP 服务器，让编码智能体控制并检查真实 Chrome：性能追踪、网络、控制台和截图。
- 🏆 **[Playwright MCP](https://github.com/microsoft/playwright-mcp)** ⭐ 38.6k — 微软官方浏览器自动化 MCP 服务器，基于 Playwright 无障碍快照而非截图，实现快速、确定性的控制。
- [Chrome MCP Server (mcp-chrome)](https://github.com/hangwin/mcp-chrome) 🇨🇳 ⭐ 12.5k — Chrome 扩展，将你日常使用的浏览器（保留登录态与设置）暴露为 MCP 服务器，支持自动化和语义标签页搜索。
- [agent-qa](https://vostride.com) 🌐 — 支持 Web、Android 和 iOS 自然语言测试的 MCP 服务器，具备持久记忆引擎与经验证的自我改进。

**🔍 文档、搜索与网页**

- 🏆 **[Context7](https://github.com/upstash/context7)** ⭐ 63.7k — Upstash 推出的 MCP 服务器与平台，为智能体上下文提供最新、按版本区分的库文档和代码示例。
- [GitMCP](https://github.com/idosal/git-mcp) ⭐ 8.5k — 免费开源的远程 MCP 服务器（gitmcp.io），可将任意 GitHub 项目变为文档来源，减少代码幻觉。
- [Firecrawl MCP Server](https://github.com/firecrawl/firecrawl-mcp-server) ⭐ 7.7k — Firecrawl 官方 MCP 服务器，为 Claude 等客户端提供网页抓取、爬取、搜索和结构化提取。
- [Exa MCP Server](https://github.com/exa-labs/exa-mcp-server) ⭐ 5.2k — Exa 官方 MCP 服务器，提供面向 AI 的网页搜索、代码搜索与网页抓取，支持本地或托管使用。
- [arXiv MCP Server](https://github.com/blazickjp/arxiv-mcp-server) ⭐ 3.2k — 用于文献研究的本地 MCP 服务器：搜索 arXiv、下载论文、阅读 LaTeX 章节、导出 BibTeX 并订阅主题。
- [Tavily MCP](https://github.com/tavily-ai/tavily-mcp) ⭐ 2.5k — Tavily 官方 MCP 服务器，为智能体提供实时网页搜索、内容提取、站点地图与爬取功能。
- [Brave Search MCP Server](https://github.com/brave/brave-search-mcp-server) ⭐ 1.5k — Brave 官方 MCP 服务器，通过 Brave Search API 提供网页、本地、图片、视频和新闻搜索。

**🗄️ 数据库与数据**

- [MCP Toolbox for Databases](https://github.com/googleapis/mcp-toolbox) ⭐ 16.7k — 谷歌开源的数据库 MCP 服务器，支持 BigQuery、AlloyDB、Cloud SQL、Spanner、Postgres、MySQL 等，内置连接池与认证。
- [DBHub](https://github.com/bytebase/dbhub) ⭐ 3.7k — Bytebase 推出的省 token 通用数据库 MCP 服务器，支持 Postgres、MySQL、SQL Server、MariaDB、Oracle 和 SQLite。
- [Postgres MCP Pro](https://github.com/crystaldba/postgres-mcp) ⭐ 3.4k — Postgres MCP 服务器，支持可配置的读写权限，并提供索引调优、执行计划和数据库健康分析。
- [Supabase MCP](https://github.com/supabase/mcp) ⭐ 3k — Supabase 官方 MCP 服务器，可在 Claude 中管理项目、设计表结构、执行 SQL 与迁移并部署 Edge Functions。
- [EdgarTools](https://github.com/dgunning/edgartools) ⭐ 2.8k — 用于 SEC EDGAR 文件（10-K、8-K、XBRL 财务数据、13F）的 Python 库，内置可供 Claude 使用的 MCP 服务器。
- [Neon MCP Server](https://github.com/neondatabase/mcp-server-neon) ⭐ 655 — Neon 官方 MCP 服务器，用自然语言管理 Serverless Postgres 项目、分支、查询和安全迁移。

**☁️ 云与基础设施**

- [AWS MCP Servers](https://github.com/awslabs/mcp) ⭐ 9.8k — AWS Labs 开源 MCP 服务器套件，覆盖 AWS 文档、API、CDK、EKS、Serverless、成本分析等众多服务。
- [Google MCP](https://github.com/google/mcp) ⭐ 4.7k — 谷歌官方 MCP 服务器汇总，涵盖 Google Cloud、地图、Firebase、Workspace、数据库等远程与开源服务器。
- [Microsoft MCP (Azure MCP Server)](https://github.com/microsoft/mcp) ⭐ 3.8k — 微软官方 MCP 服务器目录，包括可让智能体管理 Azure 资源的 Azure MCP Server。
- [Kubernetes MCP Server](https://github.com/containers/kubernetes-mcp-server) ⭐ 2.2k — 原生 Go 实现的 Kubernetes/OpenShift MCP 服务器，直接调用 API Server，无需依赖 kubectl。
- [Terraform MCP Server](https://github.com/hashicorp/terraform-mcp-server) ⭐ 1.6k — HashiCorp 官方 MCP 服务器，提供 Terraform Registry Provider/模块文档查询及 HCP Terraform 工作区操作。
- [Cloudflare API MCP Server](https://github.com/cloudflare/mcp) ⭐ 1k — Cloudflare 远程 MCP 服务器（mcp.cloudflare.com），通过省 token 的 Code Mode 开放约 2500 个 Cloudflare API 端点。

**🎨 设计、3D 与创意**

- 🏆 **[Blender MCP](https://github.com/ahujasid/mcp-for-blender)** ⭐ 32.4k — 通过插件将 Claude 连接到 Blender，用提示词创建、修改和查看 3D 场景、材质与资源。
- 🏆 **[Figma MCP Server](https://developers.figma.com/docs/figma-mcp-server)** 📘 — Figma 官方远程及桌面版 MCP 服务器，将设计上下文、变量、组件和 Code Connect 带入编码智能体。
- [Next AI Draw.io](https://github.com/DayuanJiang/next-ai-draw-io) ⭐ 36.4k — 通过与 AI 对话绘制和编辑 draw.io 图表，提供 Web 应用、桌面应用以及可供 Claude Code 使用的 MCP 服务器。
- [Framelink Figma MCP (Figma-Context-MCP)](https://github.com/GLips/Figma-Context-MCP) ⭐ 16.1k — 社区 MCP 服务器，精简 Figma API 布局数据，帮助编码智能体一次性准确还原设计稿。
- [MCP for Unity](https://github.com/CoplayDev/unity-mcp) ⭐ 15.4k — 连接 AI 助手与 Unity 编辑器的桥梁，可管理资源、控制场景、编辑脚本并自动化游戏开发任务。
- [Godot MCP](https://github.com/Coding-Solo/godot-mcp) ⭐ 6.4k — Godot 引擎 MCP 服务器：可启动编辑器、运行项目、捕获调试输出并操作场景。
- [draw.io MCP Server](https://github.com/jgraph/drawio-mcp) ⭐ 5.7k — JGraph 推出的 draw.io 官方 MCP 服务器，可在 draw.io 编辑器中创建和打开图表，并提供托管 MCP App。
- [Excalidraw MCP App](https://github.com/excalidraw/excalidraw-mcp) ⭐ 5.6k — Excalidraw 官方 MCP App，可在 Claude 等支持 MCP Apps 的客户端中直接流式生成可编辑的手绘风格图表。
- [Ableton MCP](https://github.com/ahujasid/ableton-mcp) ⭐ 3.2k — 让 Claude 控制 Ableton Live，创建音轨、加载乐器、编排片段并进行作曲。

**🗂️ 效率与知识管理**

- [n8n-MCP](https://github.com/czlonkowski/n8n-mcp) ⭐ 23.1k — 让 Claude 深入了解 n8n 节点与 API 的 MCP 服务器，可设计、校验并部署 n8n 工作流。
- [Notion MCP Server](https://github.com/makenotion/notion-mcp-server) ⭐ 4.7k — Notion 官方 MCP 服务器，可搜索、读取和编辑页面与数据库，推荐使用托管远程版本。
- [MCP Obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) ⭐ 4.5k — 通过 Local REST API 社区插件读取、搜索和编辑 Obsidian 笔记库的 MCP 服务器。
- [Slack MCP Server](https://docs.slack.dev/ai/slack-mcp-server) 📘 — Slack 官方托管 MCP 服务器，支持 OAuth，可搜索对话、读取频道、发送消息和处理 Canvas。
- [Google Workspace MCP Servers](https://developers.google.com/workspace/guides/configure-mcp-servers) 📘 — 谷歌官方远程 MCP 服务器，覆盖 Gmail、Drive、Calendar 和 Chat，并沿用用户现有的访问权限。

**🖥️ 桌面与系统控制**

- [Windows-MCP](https://github.com/CursorTouch/Windows-MCP) ⭐ 10.4k — 轻量级 Windows 计算机操控 MCP 服务器：可启动应用、读取 UI 树、点击、输入并自动化桌面操作。
- [Desktop Commander MCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) ⭐ 10.1k — 让 Claude 在本地机器上控制终端、管理进程、搜索文件系统并以 diff 方式编辑文件。
- [Mobile MCP](https://github.com/mobile-next/mobile-mcp) ⭐ 10k — 跨平台 MCP 服务器，可在模拟器和真机上自动化操作 iOS 与 Android 应用。
- [Peekaboo](https://github.com/openclaw/Peekaboo) ⭐ 5.4k — macOS 命令行工具及可选 MCP 服务器，让智能体截取屏幕、分析画面并自动化 GUI 操作。

**🧠 记忆**

- [Knowledge Graph Memory Server](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) — 官方参考服务器，以实体、关系和观察组成的本地知识图谱，为 Claude 提供持久记忆。
- [Graphiti MCP Server](https://github.com/getzep/graphiti/tree/main/mcp_server) — Zep 基于 Graphiti 时序知识图谱构建的 MCP 服务器，为智能体提供可查询的持久长期记忆。

**🤝 多模型与 AI**

- [PAL MCP Server (formerly Zen MCP)](https://github.com/BeehiveInnovations/pal-mcp-server) ⭐ 11.8k — 让 Claude Code 调用 Gemini、OpenAI、Grok、OpenRouter、Ollama 及其他 CLI，获取第二意见、达成共识并进行代码审查。
- [CodexMCP](https://github.com/GuDaStudio/codexmcp) 🇨🇳 ⭐ 2k — 让 Claude Code 通过 MCP 调用 Codex 的桥接工具：Claude 负责规划与架构，Codex 负责实现、排错与审查，支持会话持久化与并行任务。

**✨ 其他**

- [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) 🇨🇳 ⭐ 16.6k — 小红书 MCP 服务器：智能体可登录、搜索、浏览、评论并发布图文或视频笔记。
- [IDA Pro MCP](https://github.com/mrexodia/ida-pro-mcp) ⭐ 13.2k — 通过 MCP 连接 IDA Pro 与大模型的 AI 逆向工程助手，支持反编译、重命名和二进制分析。
- [mcp-feedback-enhanced](https://github.com/Minidoracat/mcp-feedback-enhanced) 🇨🇳 ⭐ 3.8k — 交互式反馈 MCP 服务器，提供 Web 与桌面界面，让你在 AI 编码过程中随时确认、反馈和纠偏，减少无效请求；README 含简繁中文。

<a id="mcp-dev"></a>
### MCP SDK 与开发工具

<sub>构建、测试、代理与加固你自己的 MCP 服务器。</sub>

- 🏆 **[FastMCP](https://github.com/PrefectHQ/fastmcp)** ⭐ 28.2k — 快速、Pythonic 的 MCP 服务器、客户端与应用开发框架，提供认证、代理、组合与部署工具。
- [MCP for Beginners](https://github.com/microsoft/mcp-for-beginners) 🎓 ⭐ 17.5k — 微软开源的 MCP 课程，提供 Python、TypeScript、Java、C#、Rust 等语言的实操课程和示例。
- [FastAPI-MCP](https://github.com/tadata-org/fastapi_mcp) ⭐ 12k — 以极少配置将现有 FastAPI 接口暴露为 MCP 工具，并内置认证支持。
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) ⭐ 11.2k — 官方 MCP 服务器可视化测试与调试工具，可通过 npx @modelcontextprotocol/inspector 运行。
- [mcp-use](https://github.com/mcp-use/mcp-use) ⭐ 10.8k — 全栈 TypeScript/Python 框架，用于构建 MCP 服务器、面向 Claude 与 ChatGPT 的 MCP Apps 以及基于 MCP 的智能体。
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) ⭐ 8.6k — LastMile AI 的智能体框架，基于 MCP 并采用 Anthropic《Building Effective Agents》中的可组合工作流模式。
- [MCP Go SDK](https://github.com/modelcontextprotocol/go-sdk) ⭐ 5.3k — 官方 Tier 1 级 Go SDK，用于构建 MCP 服务器和客户端，与谷歌合作维护。
- [ContextForge MCP Gateway](https://github.com/IBM/mcp-context-forge) ⭐ 4.7k — IBM 开源网关、注册表与代理，统一接入 MCP 服务器、A2A 智能体及 REST/gRPC API，并提供治理与可观测性。
- [MCP C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) ⭐ 4.6k — 官方 Tier 1 级 C#/.NET SDK，用于构建 MCP 服务器和客户端，与微软合作维护。
- [MCP Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) ⭐ 4.1k — 官方 Tier 1 级 Rust SDK（rmcp），基于 Tokio 构建 MCP 服务器和客户端。
- [Snyk Agent Scan (formerly mcp-scan)](https://github.com/snyk/agent-scan) ⭐ 3.2k — 面向 MCP 服务器、智能体配置和技能的安全扫描器，可检测工具投毒、提示词注入和 rug pull 攻击。
- [MCP Apps (ext-apps)](https://github.com/modelcontextprotocol/ext-apps) ⭐ 3k — MCP Apps 官方规范与 SDK，该扩展让 MCP 服务器在 Claude、ChatGPT 等客户端中渲染交互式界面。
- [MCPB (MCP Bundles)](https://github.com/modelcontextprotocol/mcpb) ⭐ 2.1k — 将本地 MCP 服务器打包为可在 Claude Desktop 等应用中一键安装的格式及 CLI（原 Desktop Extensions/DXT）。
- [Official MCP SDKs (Java, Kotlin, Swift, Ruby, PHP...)](https://modelcontextprotocol.io/docs/sdk) 📘 — 所有官方 MCP SDK 及其分级的索引，包括 Ruby（Tier 1）、Java（Tier 2）、Swift、PHP 和 Kotlin。
- [Docker MCP Catalog & Toolkit](https://docs.docker.com/ai/mcp-catalog-and-toolkit) 📘 — Docker 的容器化 MCP 服务器目录，配合 Toolkit 和开源 MCP Gateway，安全地运行这些服务器并接入 Claude。

<a id="mcp-directories"></a>
### MCP 目录与注册表

<sub>发现更多 MCP 服务器。</sub>

- 🏆 **[Awesome MCP Servers (punkpeye)](https://github.com/punkpeye/awesome-mcp-servers)** ⭐ 96.9k — 星标最多的 MCP 服务器精选列表，按类别整理并标注语言与部署方式。
- 🏆 **[Official MCP Registry](https://registry.modelcontextprotocol.io)** 🌐 — 官方开放的 MCP 服务器注册中心，采用命名空间验证的 server.json 元数据，并提供供下游注册表使用的 API。
- 🏆 **[Claude Connectors Directory](https://claude.com/connectors)** 🌐 — Anthropic 的连接器目录，收录经其审核的远程 MCP 连接器与插件，可在 Claude、Claude Desktop 和 Claude Code 中安装。
- [Awesome-MCP-ZH](https://github.com/yzfly/Awesome-MCP-ZH) 🇨🇳 ⭐ 7.8k — 中文 MCP 资源精选合集，涵盖指南、服务器、客户端以及 Claude MCP 配置技巧。
- [GitHub MCP Registry](https://github.com/mcp) 🌐 — GitHub 精选的 MCP 服务器注册表，支持一键安装到 VS Code 等 MCP 客户端。
- [Smithery](https://smithery.ai) 🌐 — 大型 MCP 注册与市场平台，提供托管服务器、CLI 安装器和托管认证连接，现已并入 Arcade.dev。
- [Glama MCP Servers](https://glama.ai/mcp/servers) 🌐 — 可搜索的 MCP 服务器目录，提供自动化的安全、许可证和质量评分，以及托管网关和检测工具。
- [PulseMCP](https://www.pulsemcp.com) 🌐 — MCP 目录与每周通讯，追踪服务器、客户端和用例，并按估算使用量给出热度排名。
- [mcp.so](https://mcp.so) 🌐 🇨🇳 — 规模最大的社区 MCP 服务器目录之一，提供分类与排行，代码开源（chatmcp/mcpso）。
- [MCP Market](https://mcpmarket.com) 🌐 — MCP 服务器市场与目录，提供分类、每日排行榜和客户端配置指南。
- [魔搭 ModelScope MCP 广场](https://modelscope.cn/mcp) 🌐 🇨🇳 — 魔搭社区 MCP 广场：国内最大的 MCP 服务聚合与托管平台之一，可在 Claude 等客户端中直接接入。

<div align="right"><a href="#top">↑ 返回顶部</a></div>

---

<a id="building"></a>
## 🤖 基于 Claude 构建

_基于 Claude API 与 Claude Agent SDK 构建的代理、应用与库，以及将 Claude 作为一等模型的其他编程代理。_

<a id="agent-sdk"></a>
### Agent SDK 项目

<sub>基于 Claude Agent SDK 的开源代理、模板与产品。</sub>

- 🏆 **[Craft Agents](https://github.com/craft-ai-agents/craft-agents-oss)** ⭐ 7.3k — Craft 出品的开源桌面应用与无头服务器，用于多任务协同 AI 智能体；基于 Claude Agent SDK 与 Pi SDK 构建。
- [OpenClaw](https://github.com/openclaw/openclaw) ⭐ 393k — 极受欢迎的自托管个人 AI 助手，可通过聊天应用操控；最初以围绕 Claude 打造的「Clawdbot」起家，现已支持多模型。
- [Shannon](https://github.com/KeygraphHQ/shannon) ⭐ 49.4k — 面向 Web 应用和 API 的自主 AI 渗透测试工具：先分析源码，再执行真实漏洞利用来验证漏洞；内置 Anthropic 模型支持。
- [ArcReel](https://github.com/ArcReel/ArcReel) 🇨🇳 ⭐ 5.7k — 自托管的智能体驱动视频工作台，可将小说和剧本转化为角色、分镜与短视频，支持跨镜头一致性与费用追踪。
- [Open Claude Cowork](https://github.com/composio-community/open-claude-cowork) ⭐ 4.3k — 开源的类 Claude Cowork 桌面聊天应用，基于 Claude Agent SDK，通过 Composio 在 500+ SaaS 应用间自动化工作。
- [Phantom](https://github.com/ghostwright/phantom) ⭐ 1.5k — 基于 Claude Agent SDK 的自主 AI 同事，运行在独立的专用机器上，具备持久记忆、自我改进能力并提供 MCP 服务器。
- [Boop Agent](https://github.com/raroque/boop-agent) ⭐ 1.4k — 可通过 iMessage 发消息交互的个人智能体开源模板，基于 Claude Agent SDK（或 Codex）运行，具备记忆、子智能体与自动化能力。
- [NekroAgent](https://github.com/KroMiose/nekro-agent) 🇨🇳 ⭐ 1.2k — 面向多人互动场景的跨平台智能体框架，集成 Claude Code 沙盒执行、工作区编排、长期记忆与 MCP 管理。
- [claude-agent-server](https://github.com/dzhng/claude-agent-server) ⭐ 585 — 在沙箱（如 E2B 模板）中运行 Claude Agent SDK（Claude Code），并通过 WebSocket 远程控制。
- [AI SDK Provider for Claude Code](https://github.com/ben-vargas/ai-sdk-provider-claude-code) ⭐ 370 — 社区版 Vercel AI SDK 提供程序，将 generateText/streamText 调用经由 Claude Agent SDK 执行，复用 Claude Code 的工具与认证。

<a id="computer-use"></a>
### 电脑与浏览器操控

<sub>能够看屏幕并操控桌面或浏览器的代理。</sub>

- 🏆 **[Anthropic Computer Use Demo](https://github.com/anthropics/claude-quickstarts/tree/main/computer-use-demo)** — Anthropic 官方的 Claude 计算机使用参考实现：Docker 化的 Linux 桌面、智能体循环与 Streamlit 界面，支持 Claude API、Bedrock 或 Vertex。
- [Cua](https://github.com/trycua/cua) ⭐ 31k — 开源的计算机使用基础设施：跨操作系统的沙箱与虚拟机、驱动与基准测试，并提供支持 Claude 计算机使用模型的智能体 SDK。
- [Stagehand](https://github.com/browserbase/stagehand) ⭐ 25.8k — Browserbase 推出的 AI 浏览器自动化 SDK（TypeScript/Python/Go），提供 act/extract/observe 原语及可搭配 Claude 模型的智能体模式。
- [Skyvern](https://github.com/Skyvern-AI/skyvern) ⭐ 23.3k — 结合大模型与计算机视觉自动化浏览器工作流；通过 Anthropic 与 AWS Bedrock 支持 Claude 模型。
- [Nanobrowser](https://github.com/nanobrowser/nanobrowser) ⭐ 14.2k — 开源的 Chrome/Edge 扩展，在你已登录的真实浏览器中运行 AI 网页自动化，可自带 Anthropic、OpenAI 等模型的密钥。
- [Agent S](https://github.com/simular-ai/Agent-S) ⭐ 12.7k — Simular 推出的开放式 GUI 计算机使用智能体框架（Agent S3，OSWorld 成绩突出）；主模型可选用 Anthropic。
- [Magnitude](https://github.com/magnitudedev/browser-agent) ⭐ 4.1k — 开源、以视觉为先的浏览器智能体，基于像素而非 DOM 进行操作；官方推荐使用 Claude Sonnet 以获得最佳效果。
- [agent.exe](https://github.com/corbt/agent.exe) ⭐ 3.5k — 极简的 Electron 应用，让 Claude 计算机使用功能直接操控你自己的桌面，而非沙箱虚拟机。
- [Computer Use OOTB](https://github.com/showlab/computer_use_ootb) ⭐ 2k — 新加坡国立大学 Show Lab 推出的开箱即用 Windows/macOS GUI 智能体，无需 Docker 虚拟机即可在本地运行 Claude 计算机使用。
- [mac_computer_use](https://github.com/deedy/mac_computer_use) ⭐ 890 — Anthropic 计算机使用演示的分支，可在 macOS 上原生运行，让 Claude 无需 Docker Linux 虚拟机即可操控 Mac。

<a id="coding-agents"></a>
### 支持 Claude 的编程代理

<sub>常与 Claude 搭配使用的其他开源编程代理与 IDE 扩展。</sub>

- 🏆 **[OpenCode](https://github.com/anomalyco/opencode)** ⭐ 222k — 极受欢迎的开源编程智能体（终端 TUI、桌面端与 IDE），由 SST/Anomaly 团队打造；不绑定模型服务商，对 Claude 支持良好。
- 🏆 **[OpenHands](https://github.com/OpenHands/OpenHands)** ⭐ 91.9k — 面向自主软件开发智能体的开放平台（前身 OpenDevin），提供 CLI、GUI、云端与 SDK；Claude 系列是其推荐使用的模型之一。
- 🏆 **[Cline](https://github.com/cline/cline)** ⭐ 70.9k — 适用于 VS Code、JetBrains 与终端的自主编程智能体，前身为「Claude Dev」；Claude 是其一等支持模型，具备 Plan/Act 模式与 MCP 支持。
- 🏆 **[Aider](https://github.com/Aider-AI/aider)** ⭐ 49.8k — 开创性的终端 AI 结对编程工具，可直接编辑 git 仓库；长期搭配 Claude 表现出色，并维护 Aider 大模型排行榜。
- [Pi](https://github.com/earendil-works/pi) ⭐ 118k — 极简、可扩展的终端编程智能体及智能体工具包（统一 LLM API、智能体循环、TUI），内置 Anthropic 等服务商支持。
- [Zed](https://github.com/zed-industries/zed) ⭐ 92.2k — 高性能 Rust 代码编辑器，内置智能体面板；可通过 API 使用 Claude，或借助 Agent Client Protocol 运行 Claude Code。
- [goose](https://github.com/aaif-goose/goose) ⭐ 55.7k — 可扩展的开源本地 AI 智能体（桌面端与 CLI），能安装、编辑、运行与测试代码；支持 Anthropic API，也可通过 ACP 使用 Claude 订阅。
- [Continue](https://github.com/continuedev/continue) ⭐ 36.3k — 面向 VS Code、JetBrains 与 CI 检查的开源编程智能体，模型与规则可配置；Claude 是常用的一等支持模型。
- [Crush](https://github.com/charmbracelet/crush) ⭐ 28.8k — Charm 出品的精美终端编程智能体，集成 LSP、MCP 并支持多会话；兼容 Anthropic Claude 等众多服务商。
- [Kilo Code](https://github.com/Kilo-Org/kilocode) ⭐ 27.8k — 开源的智能体工程平台，支持 VS Code、JetBrains 与 CLI，源自 Cline/Roo Code，可使用包括 Claude 在内的数百种模型。
- [Dyad](https://github.com/dyad-sh/dyad) ⭐ 22.1k — 本地运行的开源 AI 应用构建器（v0/Lovable/Bolt 替代品），使用你自己的 API 密钥调用 Claude 等模型。
- [avante.nvim](https://github.com/avante-corp/avante.nvim) 🇨🇳 ⭐ 18.2k — 在 Neovim 中复刻 Cursor AI IDE 体验的插件，支持对话、差异预览与智能体式编辑；默认提供商为 Claude。
- [bolt.new](https://github.com/stackblitz/bolt.new) ⭐ 16.6k — StackBlitz bolt.new 的开源核心：基于 WebContainers 在浏览器中通过提示词运行、编辑并部署全栈应用，最初由 Claude 驱动。
- [Claude Engineer](https://github.com/Doriandarko/claude-engineer) ⭐ 11.2k — 早期颇具影响力的 Claude 驱动交互式 CLI，能创建和编辑文件、运行代码，甚至为自身编写新工具。
- [CodeCompanion.nvim](https://github.com/olimorris/codecompanion.nvim) ⭐ 6.9k — Neovim 的 AI 编程插件，提供聊天、行内编辑与智能体功能；原生支持 Anthropic，并可通过 ACP 接入 Claude Code。
- [Fragments by E2B](https://github.com/e2b-dev/fragments) ⭐ 6.4k — 开源 Next.js 模板，可构建类似 Claude Artifacts、完全由 AI 生成的应用，并在 E2B 沙箱中安全执行代码；支持 Anthropic 等模型。
- [Kode](https://github.com/shareAI-lab/Kode-CLI) 🇨🇳 ⭐ 5.2k — 开源的 Claude Code 风格终端智能体，支持 20+ 模型服务商，兼容 CLAUDE.md 文件与 .claude 目录。
- [gptel](https://github.com/karthink/gptel) ⭐ 3.6k — 简洁、可扩展的 Emacs 大模型客户端，可在任意缓冲区使用，原生支持 Anthropic Claude（含工具调用）。

<a id="chat-clients"></a>
### 聊天客户端与应用

<sub>与 Claude 对话的桌面、Web 与命令行应用。</sub>

- 🏆 **[LobeHub](https://github.com/lobehub/lobehub)** 🇨🇳 ⭐ 83.5k — 开源 AI 智能体工作空间（前身 LobeChat），支持多服务商聊天、智能体团队、MCP 插件与知识库，原生支持 Claude。
- 🏆 **[Cherry Studio](https://github.com/CherryHQ/cherry-studio)** 🇨🇳 ⭐ 53k — 跨平台桌面 AI 生产力工作室，统一接入 Claude 等前沿模型，提供自主智能体、MCP 与 300+ 助手。
- 🏆 **[LibreChat](https://github.com/LibreChat-AI/LibreChat)** ⭐ 46.3k — 可自托管的多服务商 ChatGPT 风格界面，支持智能体、MCP、Skills 与 Artifacts；原生 Anthropic 端点支持 Claude，并支持 Bedrock 与 Vertex。
- [Open WebUI](https://github.com/open-webui/open-webui) ⭐ 157k — 星标数最多的自托管 AI 界面；可通过 Anthropic 的 OpenAI 兼容端点接入 Claude，或借助 Pipe 函数使用完整的 Messages API 功能。
- [NextChat](https://github.com/ChatGPTNextWeb/NextChat) 🇨🇳 ⭐ 88.9k — 轻量级跨平台 AI 聊天应用（Web、桌面与移动端），支持一键部署；兼容 Claude 以及 GPT、Gemini 等模型。
- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) ⭐ 67.6k — 一体化、本地优先的 AI 应用，支持文档对话、RAG 与智能体工作流；可选择 Anthropic Claude 作为模型服务商。
- [Jan](https://github.com/janhq/jan) ⭐ 45.1k — 开源、离线优先的 ChatGPT 替代品，可运行本地模型，也可选接入 Anthropic Claude 等远程服务商。
- [Chatbox](https://github.com/chatboxai/chatbox) 🇨🇳 ⭐ 42.1k — 流行的桌面与移动端 AI 客户端，支持 Claude、GPT、Gemini 与本地模型，具备知识库、MCP 工具与图像生成功能。
- [Khoj](https://github.com/khoj-ai/khoj) ⭐ 37.8k — 可自托管的 AI「第二大脑」，基于网络或个人文档作答，支持自定义智能体与研究模式；可使用 Claude 模型。
- [AIChat](https://github.com/sigoden/aichat) ⭐ 10.5k — 一体化 Rust 大模型命令行工具，提供 Shell 助手、聊天 REPL、RAG、工具与智能体；支持 Claude 等 20+ 服务商。
- [big-AGI](https://github.com/enricoros/big-AGI) ⭐ 7.2k — 面向高级用户的 AI 套件，支持多模型「Beam」对比、角色与语音，并一等支持 Anthropic Claude。
- [DeepChat](https://github.com/ThinkInAIXYZ/deepchat) 🇨🇳 ⭐ 6.4k — 开源桌面 AI 助手，连接 Claude、GPT、Gemini、DeepSeek 与本地模型，支持 MCP 工具调用和多窗口对话。
- [Claude Desktop for Linux (claude-desktop-debian)](https://github.com/aaddrick/claude-desktop-debian) ⭐ 5.5k — Claude Desktop 的非官方 Linux 打包项目，现基于 Anthropic 官方测试版 .deb 重新打包为 RPM、AppImage、AUR 与 Nix 等格式，并附带 Linux 修复。
- [5ire](https://github.com/nanbingxyz/5ire) 🇨🇳 ⭐ 5.4k — 跨平台桌面 AI 助手与 MCP 客户端，兼容 Anthropic 等主流服务商，内置本地知识库与提示词库。
- [DeepReasoning](https://github.com/winfunc/deepreasoning) ⭐ 5.4k — 高性能 Rust 推理 API 与聊天界面，将 DeepSeek R1 的思维链推理输入 Claude 以生成最终答案。
- [Witsy](https://github.com/Kochava-Studios/witsy) ⭐ 2k — 桌面 AI 助手与通用 MCP 客户端，可自带密钥使用 Claude 等模型，支持随处调用的提示命令与智能体。
- [llm-anthropic](https://github.com/simonw/llm-anthropic) ⭐ 252 — Simon Willison 的 LLM 命令行工具插件，加入 Claude 模型、扩展思考以及网页搜索、代码执行等服务端工具。
- [Claude for Raycast](https://github.com/raycast/extensions/tree/main/extensions/claude) — Raycast 扩展，使用你的 Anthropic API 密钥在 macOS 命令栏中向 Claude 提问：支持模型选择、继续对话、保存回答与读取选中文本。

<a id="api-tools"></a>
### API 库与开发工具

<sub>社区 SDK、框架集成、评测工具与 Claude API 辅助工具。</sub>

- 🏆 **[promptfoo](https://github.com/promptfoo/promptfoo)** ⭐ 26.4k — 开源 CLI，用于测试提示词、智能体与 RAG 并进行 AI 红队测试；提供一等支持的 Anthropic 与 Claude Agent SDK 提供程序。
- 🏆 **[Vercel AI SDK - Anthropic Provider](https://ai-sdk.dev/providers/ai-sdk-providers/anthropic)** 📘 — @ai-sdk/anthropic：Vercel AI SDK 中的 Claude TypeScript 提供程序，支持提示缓存、思考、批处理、MCP 连接器以及网页搜索等服务端工具。
- [LiteLLM](https://github.com/BerriAI/litellm) ⭐ 62k — AI 网关与 Python SDK，以 OpenAI 格式调用 100+ 大模型 API，支持 Anthropic、成本追踪、提示缓存注入与负载均衡。
- [aisuite](https://github.com/andrewyng/aisuite) ⭐ 16.4k — 吴恩达推出的简洁统一 Python 接口，可对接多家生成式 AI 服务商，只需修改一个字符串即可切换 Claude 等模型。
- [Instructor](https://github.com/567-labs/instructor) ⭐ 14.1k — 基于 Pydantic 模型为大模型提供结构化输出，带校验与重试；通过工具调用方式支持 Anthropic Claude。
- [Rig](https://github.com/0xPlaygrounds/rig) ⭐ 9k — 用于构建大模型应用与智能体的模块化 Rust 库，提供 Anthropic Claude 以及 OpenAI、Gemini 等提供程序。
- [RubyLLM](https://github.com/crmne/ruby_llm) ⭐ 4.5k — 优雅的 Ruby AI 框架，以统一 API 提供聊天、工具、视觉、嵌入与 Rails 集成，支持 Claude 等服务商。
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) ⭐ 3.1k — 英国 AI 安全研究所推出的大模型评测框架，涵盖基准测试、智能体任务与沙箱，原生支持 Anthropic。
- [Prism](https://github.com/prism-php/prism) ⭐ 2.4k — 面向 Laravel/PHP 的统一大模型接口，包含功能完善的 Anthropic Claude 提供程序，支持工具与结构化输出。
- [tokencost](https://github.com/AgentOps-AI/tokencost) ⭐ 2k — 为 400+ 大模型提供 token 计数与费用估算，较新的 Claude 模型使用 Anthropic 的 token 计数 API。
- [Elixir LangChain](https://github.com/brainlid/langchain) ⭐ 1.2k — LangChain 风格的 Elixir 框架，用于在 Elixir 应用中集成大模型，支持 ChatAnthropic（Claude）、扩展思考与 AWS Bedrock。
- [ellmer](https://github.com/tidyverse/ellmer) ⭐ 620 — Tidyverse 出品的 R 语言大模型 API 调用包，提供 chat_anthropic() 接入 Claude，支持工具调用、结构化数据提取与流式输出。
- [SwiftAnthropic](https://github.com/jamesrochabrun/SwiftAnthropic) ⭐ 253 — 开源 Swift 包，让 iOS 与 macOS 应用对接 Anthropic API，使用 Claude 消息、流式输出、视觉与工具调用。
- [Anthropic.SDK (.NET)](https://github.com/tghamm/Anthropic.SDK) ⭐ 222 — 流行的非官方 C#/.NET Claude API SDK，支持流式输出、工具调用、批处理及 Microsoft.Extensions.AI 集成。
- [LangChain - ChatAnthropic](https://docs.langchain.com/oss/python/integrations/chat/anthropic) 📘 — langchain-anthropic 集成：ChatAnthropic 支持工具调用、结构化输出、PDF/图像输入、扩展思考、提示缓存及 Claude 内置工具。
- [LlamaIndex - Anthropic LLM](https://developers.llamaindex.ai/python/framework/integrations/llm/anthropic) 📘 — llama-index-llms-anthropic：在 LlamaIndex 中使用 Claude，支持流式输出、多模态输入、提示缓存、工具调用、结构化预测与引用。
- [anthropic_sdk_dart](https://pub.dev/packages/anthropic_sdk_dart) 🌐 — 纯 Dart/Flutter 的 Anthropic API 客户端，支持流式输出与工具调用，属于 langchain_dart / ai_clients_dart 系列。

<div align="right"><a href="#top">↑ 返回顶部</a></div>

---

<a id="learning"></a>
## 📚 学习资源

_指南、必读文章、课程、提示词、视频与资讯。_

<a id="guides"></a>
### 指南与教程

<sub>社区手册、最佳实践与技巧合集。</sub>

- 🏆 **[Learn Claude Code](https://github.com/shareAI-lab/learn-claude-code)** 🇨🇳 ⭐ 79.2k — 动手课程：用 Python 从零构建迷你版 Claude Code 智能体框架，每课新增一个机制；提供英/中/日文版。
- 🏆 **[Claude Code Best Practice (shanraisshan)](https://github.com/shanraisshan/claude-code-best-practice)** ⭐ 68.1k — 极受欢迎的 Claude Code 最佳实践合集，涵盖提示、CLAUDE.md、技能、子代理、钩子与调试。
- [Claude HowTo](https://github.com/luongnv89/claude-howto) ⭐ 45.2k — 图文并茂、示例驱动的 Claude Code 指南，提供分级学习路径以及命令、技能、钩子、MCP 的可复制模板。
- [Context Engineering Intro](https://github.com/coleam00/context-engineering-intro) ⭐ 13.9k — 用于 Claude Code 上下文工程的模板与教程：INITIAL.md 需求、PRP 生成、示例与 CLAUDE.md 规则。
- [Claude Code Tips (ykdojo)](https://github.com/ykdojo/claude-code-tips) ⭐ 10.3k — 45 条以上从入门到进阶的 Claude Code 实用技巧，含自定义状态栏脚本和在容器中运行 Claude Code。
- [Claude Code Ultimate Guide](https://github.com/FlorianBruniaux/claude-code-ultimate-guide) ⭐ 6.3k — 非常全面的 Claude Code 指南，涵盖智能体工作流、钩子、技能、MCP、测验与可用于生产的模板。
- [Claude Code Guide (zebbern)](https://github.com/zebbern/claude-code-guide) ⭐ 4.7k — 社区版 Claude Code 指南，覆盖安装、命令、工作流、智能体、技能与技巧，适合新手到高阶用户。
- [claude-code-mastering](https://github.com/revfactory/claude-code-mastering) 🇰🇷 ⭐ 774 — 韩文的书籍式 Claude Code 进阶指南，通过 GitHub Pages 公开发布。
- [cc101](https://github.com/fivetaku/cc101) 🇰🇷 ⭐ 302 — 韩文 Claude Code 入门指南（含英文内容），基于 Next.js 构建，并已有日文本地化版本。
- [ClaudeLog](https://claudelog.com) 🌐 — 独立社区知识库，汇集源于实战的 Claude Code 文档、教程、机制解析与最佳实践。

<a id="articles"></a>
### 必读文章

<sub>深刻影响 Claude Code 用法的长文。</sub>

- 🏆 **[Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents)** 📝 — Anthropic 智能体设计奠基文章：区分工作流与智能体，介绍提示链、路由、编排-执行、评估-优化等模式，强调简洁。
- 🏆 **[Effective Context Engineering for AI Agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)** 📝 — Anthropic 谈如何为智能体打造精简高信号的上下文：系统提示、工具、即时检索、压缩、笔记与子代理。
- 🏆 **[Ralph Wiggum as a "Software Engineer" (Geoffrey Huntley)](https://ghuntley.com/ralph)** 📝 — “Ralph” 技巧的出处：让编程智能体在简单循环中运行，每轮完成一个任务，并不断调整提示与校验。
- 🏆 **[How Claude Code is built (The Pragmatic Engineer)](https://newsletter.pragmaticengineer.com/p/how-claude-code-is-built)** 📝 · _作者 Gergely Orosz_ — 基于团队访谈的深度文章，剖析 Claude Code 的起源、TypeScript/React/Ink/Bun 技术栈、权限系统和发布节奏。
- [Writing Effective Tools for Agents — with Agents](https://www.anthropic.com/engineering/writing-tools-for-agents) 📝 — 如何设计、评测并迭代优化智能体工具与 MCP 服务器，并借助 Claude 自身改进工具描述。
- [Equipping Agents for the Real World with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) 📝 — 介绍 Agent Skills 的工程文章：SKILL.md 文件夹、渐进式披露、附带代码以及如何编写技能。
- [Effective Harnesses for Long-Running Agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) 📝 — Anthropic 关于跨多个上下文窗口持续工作的智能体框架模式：初始化代理、进度文件、功能清单与增量验证。
- [Code Execution with MCP](https://www.anthropic.com/engineering/code-execution-with-mcp) 📝 — 将 MCP 工具呈现为代码 API，让智能体编写代码调用，从而大幅减少 token 消耗、提升效率。
- [Building Agents with the Claude Agent SDK](https://claude.com/resources/articles/building-agents-with-the-claude-agent-sdk) 📝 — 解释 Claude Code SDK 更名为 Agent SDK 的原因、“收集上下文-行动-验证”循环以及构建智能体的最佳实践。
- [A Harness for Every Task: Dynamic Workflows in Claude Code](https://claude.dev/blog/a-harness-for-every-task-dynamic-workflows-in-claude-code) 📝 — Claude Code 团队介绍动态工作流：生成并协调子代理，含扇出汇总、对抗验证、锦标赛等六种模式。
- [How Anthropic Teams Use Claude Code](https://claude.com/resources/articles/how-anthropic-teams-use-claude-code) 📝 — 案例研究：Anthropic 的工程、安全、数据、法务、市场等团队如何在日常工作中使用 Claude Code。
- [Agentic Coding Recommendations (Armin Ronacher)](https://lucumr.pocoo.org/2025/6/12/agentic-coding) 📝 — Flask 作者 Armin Ronacher 分享的 Claude Code 实战工作流：工具设计、日志、语言选择、保持简单与并行化。
- [How I Use Every Claude Code Feature (Shrivu Shankar)](https://blog.sshh.io/p/how-i-use-every-claude-code-feature) 📝 — 参考手册式长文，逐一讲解几乎所有 Claude Code 功能（CLAUDE.md、上下文、钩子、技能、MCP、SDK、GitHub Actions）及应避免的用法。
- [Writing a Good CLAUDE.md (HumanLayer)](https://www.humanlayer.dev/blog/writing-a-good-claude-md) 📝 — 广受引用的指南：保持 CLAUDE.md 简短通用，用指向文档代替内嵌内容，把代码风格交给 linter。
- [What Makes Claude Code So Damn Good (MinusX)](https://minusx.ai/blog/decoding-claude-code) 📝 — 剖析 Claude Code 的设计：单一主循环、小模型辅助、详尽提示、以 LLM 搜索替代 RAG、模型自维护待办列表。
- [How I Use Claude Code: Separation of planning and execution](https://boristane.com/blog/how-i-use-claude-code) 📝 · _作者 Boris Tane_ — 热门工作流文章：先调研代码库、写 markdown 计划、通过批注反复修订，然后再让 Claude 实现。
- [The Emperor Has No Clothes: How to Code Claude Code in 200 Lines of Code](https://www.mihaileric.com/The-Emperor-Has-No-Clothes) 📝 · _作者 Mihail Eric_ — 用约 200 行 Python 实现一个极简的 Claude Code 式编程智能体，揭示智能体循环的工作原理。
- [How I Use Claude Code to Ship Like a Team of Five](https://every.to/source-code/how-i-use-claude-code-to-ship-like-a-team-of-five-6f23f136-52ab-455f-a997-101c071613aa) 📝 · _作者 Kieran Klaassen (Every)_ — Every 旗下 Cora 负责人讲述如何用“复利工程”方法指挥多个 Claude Code 智能体。
- [First attempt will be 95% garbage: A staff engineer's 6-week journey with Claude Code](https://www.sanity.io/blog/first-attempt-will-be-95-garbage) 📝 · _作者 Vincent Quigley_ — Sanity 资深工程师坦率讲述在生产中使用 Claude Code 的经历：反复反馈、仔细审查和共享上下文。
- [6 weeks of Claude Code](https://blog.puzzmo.com/posts/2025/07/30/six-weeks-of-claude-code) 📝 · _作者 Orta Therox (Puzzmo)_ — Puzzmo 工程负责人广受讨论的复盘：六周的 Claude Code 使用如何改变小团队的产出。
- [Using Claude Code to modernize a 25-year-old kernel driver](https://dmitrybrant.com/2025/09/07/using-claude-code-to-modernize-a-25-year-old-kernel-driver) 📝 · _作者 Dmitry Brant_ — 案例：两个晚上用 Claude Code 把老旧的 ftape Linux 驱动移植到现代内核。

<a id="courses"></a>
### 课程

<sub>来自 Anthropic、合作伙伴与社区的系统课程。</sub>

- 🏆 **[Anthropic Academy (Claude Academy)](https://academy.claude.com)** 🎓 — Anthropic 免费自学平台，提供 Claude、Claude Code、Cowork、MCP、技能、子代理、API 及 AI 素养等课程。
- [Anthropic Courses (archived)](https://github.com/anthropics/courses) ⭐ 22.9k 🗄️ 已归档 — Anthropic 早期 Notebook 课程：API 基础、提示工程、真实场景提示、提示评测与工具调用。
- [Claude Code 101](https://academy.claude.com/courses/claude-code-101) 🎓 — Anthropic Academy 入门课程，介绍 Claude Code 基础知识与日常工作流。
- [Claude Code in Action](https://academy.claude.com/courses/claude-code-in-action) 🎓 — Anthropic Academy 官方免费课程，讲解如何在真实开发工作流中运用 Claude Code。
- [Building with the Claude API](https://academy.claude.com/courses/building-with-the-claude-api) 🎓 — Anthropic Academy 课程，讲解如何使用 Claude API 构建应用，从首次调用到高级功能。
- [Claude Code: A Highly Agentic Coding Assistant (DeepLearning.AI)](https://www.deeplearning.ai/courses/claude-code-a-highly-agentic-coding-assistant) 🎓 — DeepLearning.AI 与 Anthropic 合作短课程，由 Elie Schoppik 讲授：通过三个项目学习 CLAUDE.md、worktree、钩子、GitHub 与 MCP。
- [Agent Skills with Anthropic (DeepLearning.AI)](https://www.deeplearning.ai/short-courses/agent-skills-with-anthropic) 🎓 — DeepLearning.AI 短课程：构建 SKILL.md 技能，并在 Claude 应用、Claude Code、API 和 SDK 中结合 MCP 与子代理使用。

<a id="prompts"></a>
### 提示词与提示工程

<sub>适用于 Claude 的提示词库与技巧。</sub>

- 🏆 **[Prompt Engineering Interactive Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial)** ⭐ 38.8k — Anthropic 交互式 Notebook 教程，通过大量练习讲授 Claude 提示工程基础。
- [Awesome Claude Prompts](https://github.com/langgptai/awesome-claude-prompts) 🇨🇳 ⭐ 5.5k — 精选 Claude 提示词与提示技巧合集，帮助更好地使用 Claude。
- [Claude Prompting Best Practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) 📘 — Anthropic 持续更新的提示工程参考，适用于当前 Claude 模型：清晰表达、示例、XML、思考、工具调用、智能体系统与迁移。
- [Claude System Prompts (Release Notes)](https://platform.claude.com/docs/en/release-notes/system-prompts/overview) 📘 — Anthropic 官方公开的 claude.ai 及移动应用各模型系统提示词，附带按日期的更新记录。

<a id="videos"></a>
### 视频与频道

<sub>演讲、教程与 YouTube 频道。</sub>

- 🏆 **[Anthropic (YouTube)](https://www.youtube.com/@anthropic-ai)** 📡 · _作者 Anthropic_ — Anthropic 官方频道：发布演示、Code w/ Claude 大会专场，以及 Claude Code 团队的分享。
- 🏆 **[IndyDevDan](https://www.youtube.com/@indydevdan)** 📡 · _作者 IndyDevDan_ — 进阶智能体工程频道，深入讲解 Claude Code 的 hooks、子代理、CLAUDE.md、MCP 和多智能体工作流。
- 🏆 **[Claude Code best practices | Code w/ Claude](https://www.youtube.com/watch?v=gv0WHhKelSE)** 📺 · _作者 Anthropic_ — Code w/ Claude 2025 官方专场（约 26 分钟），讲解如何在日常开发中充分发挥 Claude Code。
- [Claude (YouTube)](https://www.youtube.com/@claude) 📡 · _作者 Anthropic_ — Claude 官方产品频道，发布简短的 Claude Code 讲解和工作流视频，例如《How Claude Code Works》。
- [Cole Medin](https://www.youtube.com/@ColeMedin) 📡 · _作者 Cole Medin_ — AI 智能体构建频道，讲解上下文工程，以及用 Claude Code 等编程智能体做“计划-实现-验证”工作流。
- [AI Jason](https://www.youtube.com/@AIJasonZ) 📡 · _作者 Jason Zhou_ — 人气 AI 构建者频道，分享实用的 Claude Code 技巧、智能体配置和设计工作流实验。
- [AI Engineer](https://www.youtube.com/@aiDotEngineer) 📡 · _作者 AI Engineer_ — AI Engineer Summit 和 World's Fair 大会频道，收录 Claude Code 团队的演讲和工作坊。
- [Nate Herk | AI Automation](https://www.youtube.com/@nateherk) 📡 · _作者 Nate Herk_ — 自动化频道，提供播放量很高的 Claude Code 课程、技能盘点和技巧视频，覆盖入门到生产使用。
- [Nick Saraev](https://www.youtube.com/@nicksaraev) 📡 · _作者 Nick Saraev_ — 以长篇 Claude Code 课程著称，讲解智能体团队、git worktree 和构建能赚钱的 AI 系统。
- [Matt Pocock](https://www.youtube.com/@mattpocockuk) 📡 · _作者 Matt Pocock_ — TypeScript 讲师的频道，为开发者提供简明的 Claude Code 技能、CLAUDE.md 和工作流技巧。
- [Net Ninja](https://www.youtube.com/@NetNinja) 📡 · _作者 Shaun Pelling_ — 编程教学频道，提供免费的多集 Claude Code 教程系列：安装、CLAUDE.md、MCP 服务器、子代理、GitHub。
- [Mastering Claude Code in 30 minutes](https://www.youtube.com/watch?v=6eBSHbLKuN0) 📺 · _作者 Boris Cherny (Anthropic)_ — Claude Code 创造者 Boris Cherny 演示其日常工作流：代码库问答、先计划、自我验证、CLAUDE.md 和 claude -p。
- [Vibe coding in prod | Code w/ Claude](https://www.youtube.com/watch?v=fHWFF_pnqDk) 📺 · _作者 Anthropic_ — Anthropic 演讲：如何负责任地把智能体写的代码上线，包括选择叶子模块、可验证性和聚焦关键审查。
- [How Claude Code Works](https://www.youtube.com/watch?v=6bs5b4FltCU) 📺 · _作者 Claude (Anthropic)_ — 官方讲解视频，介绍 Claude Code 的智能体循环、工具和上下文处理，是播放量最高的官方视频之一。
- [The Explore → Plan → Code → Commit workflow in Claude Code](https://www.youtube.com/watch?v=xJQuF02NAK8) 📺 · _作者 Claude (Anthropic)_ — 官方短视频，演示使用 Claude Code 时推荐的“探索-计划-编码-提交”循环。
- [Claude Code & the evolution of agentic coding — Boris Cherny](https://www.youtube.com/watch?v=Lue8K2jqfKk) 📺 · _作者 Boris Cherny (Anthropic)_ — AI Engineer World's Fair 2025 主题演讲，Claude Code 创造者讲述智能体编程的演进与未来方向。
- [Claude Agent SDK (Full Workshop) — Thariq Shihipar](https://www.youtube.com/watch?v=TqC1qOfiVcQ) 📺 · _作者 Thariq Shihipar (Anthropic)_ — 近两小时的 AI Engineer 工作坊，用 Claude Agent SDK、bash 工具和文件系统上下文从零搭建智能体框架。
- [Claude Fable, Claude Tag, and Anthropic's Culture — Cat Wu & Thariq Shihipar ft Simon Willison](https://www.youtube.com/watch?v=uU5Gv2h8-9g) 📺 · _作者 Cat Wu, Thariq Shihipar, Simon Willison_ — AI Engineer World's Fair 2026 炉边对谈，Claude Code 产品与工程负责人参与，Simon Willison 主持。
- [CLAUDE CODE FULL COURSE 4 HOURS: Build & Sell (2026)](https://www.youtube.com/watch?v=QoQBzR1NIqI) 📺 · _作者 Nick Saraev_ — 四小时 Claude Code 完整课程，是播放量最高的 Claude Code 视频之一，涵盖智能体团队、worktree 和云端部署。
- [800+ hours of Learning Claude Code in 8 minutes](https://www.youtube.com/watch?v=Ffh9OeJ7yxw) 📺 · _作者 Edmund Yong_ — 信息密度很高的技巧视频，浓缩数百小时 Claude Code 使用经验，包括按任务划分的子代理。
- [I'm HOOKED on Claude Code Hooks: Advanced Agentic Coding](https://www.youtube.com/watch?v=J5B9UGTuNoM) 📺 · _作者 IndyDevDan_ — 深入讲解 Claude Code hooks：拦截危险命令、日志记录、语音通知，以及覆盖智能体生命周期的可观测性。
- [5 Claude Code skills I use every single day](https://www.youtube.com/watch?v=EJyuu6zlQCg) 📺 · _作者 Matt Pocock_ — Matt Pocock 分享他每天在 Claude Code 中使用的五个 Agent Skills 及其编写方法。

<a id="media"></a>
### 资讯、播客与博客

<sub>跟进生态动态。</sub>

- 🏆 **[Latent Space: Claude Code, Anthropic's Agent in Your Terminal](https://www.latent.space/p/claude-code)** 🎙️ · _作者 swyx & Alessio_ — Latent Space 2025 年 5 月一期，Boris Cherny 和 Cat Wu 讲述 Claude Code 的起源、设计以及 Anthropic 内部用法。
- 🏆 **[Simon Willison's Weblog: claude-code tag](https://simonwillison.net/tags/claude-code)** 🌐 — 知名独立 AI 博主的 130 多篇文章，持续追踪 Claude Code 发布、实验、安全问题和团队访谈。
- [Lenny's Podcast: Head of Claude Code — What happens after coding is solved](https://www.lennysnewsletter.com/p/head-of-claude-code-what-happens) 🎙️ · _作者 Lenny Rachitsky_ — 2026 年 2 月对 Boris Cherny 的访谈，谈 Claude Code 的增长、产品原则、效率技巧和工程职业的未来。
- [The Pragmatic Engineer: Building Claude Code with Boris Cherny](https://newsletter.pragmaticengineer.com/p/building-claude-code-with-boris-cherny) 🎙️ · _作者 Gergely Orosz_ — 2026 年 3 月播客，讨论并行智能体、先计划后实现、以智能体搜索替代索引、代码审查自动化和团队实践。
- [AI & I: How to Use Claude Code Like the People Who Built It](https://every.to/source-code/how-to-use-claude-code-like-the-people-who-built-it) 🎙️ · _作者 Dan Shipper (Every)_ — Every 的 AI & I 节目，Cat Wu 与 Boris Cherny 分享计划模式、共享设置、stop hooks、子代理和斜杠命令。
- [Behind the Craft: How I Plan, Build, and Run Loops with Claude Code — Thariq Shihipar](https://creatoreconomy.so/p/how-i-plan-build-and-run-loops-with-claude-code-thariq-shihipar) 🎙️ · _作者 Peter Yang_ — 2026 年 7 月一期，Claude Code 工程师演示目标设定、计划和并行智能体循环工作流。

<div align="right"><a href="#top">↑ 返回顶部</a></div>

---

<a id="chinese"></a>
## 🇨🇳 中文社区

_B 站 UP 主、中文教程、社区平台，以及提供 Claude Code 兼容接口的国内模型厂商。列表中所有国人开发的项目均以 🇨🇳 标记。_

<a id="cn-video"></a>
### B 站视频与 UP 主

<sub>B 站上的 Claude 教程与实战演示。</sub>

- 🏆 **[全网最全！60分钟全面掌握Claude Code～【附完整文档】](https://www.bilibili.com/video/BV1NvRyBzEhq)** 📺 🇨🇳 · _UP主 秋芝2046_ — B 站爆款 60 分钟 Claude Code 全面教程，从安装上手到高级用法，附完整文档，UP 主耗时三周制作。
- 🏆 **[Claude Code 从 0 到 1 全攻略：MCP / SubAgent / Agent Skill / Hook / 图片 / 上下文处理/ 后台任务](https://www.bilibili.com/video/BV14rzQB9EJj)** 📺 🇨🇳 · _UP主 马克的技术工作坊_ — 系统讲解 Claude Code：安装与交互、规划模式、后台任务、图片与 MCP、会话与上下文管理，以及 Hook、Agent Skill、SubAgent、Plugin。
- 🏆 **[Agent Skill 从使用到原理，一次讲清](https://www.bilibili.com/video/BV1cGigBQE6n)** 📺 🇨🇳 · _UP主 马克的技术工作坊_ — 一次讲清 Agent Skill 的本质、用法、渐进式披露机制，以及与 MCP 的区别与选型建议。
- 🏆 **[技术爬爬虾 · Bilibili](https://space.bilibili.com/316183842)** 📡 🇨🇳 — B 站高产 AI 编程 UP 主，Claude Code 进阶技巧、Agent Skills、MCP 配置等视频播放量常破十万，同步更新博客园。
- [从夯到拉，锐评 32 个 AI 编程工具！](https://www.bilibili.com/video/BV1cq5q6CEu3) 📺 🇨🇳 · _UP主 程序员鱼皮_ — 程序员鱼皮横评 32 款 AI 编程工具（含 Claude Code、Cursor、Codex），从能力、体验、门槛、性价比、生态排出夯到拉。
- [10分钟学会24个ClaudeCode使用技巧](https://www.bilibili.com/video/BV1SddcBFESs) 📺 🇨🇳 · _UP主 Yin\_Code_ — 10 分钟快速掌握 24 个 Claude Code 实用技巧，节奏紧凑，适合入门后提效。
- [MCP终极指南 - 从原理到实战，带你深入掌握MCP（基础篇）](https://www.bilibili.com/video/BV1uronYREWR) 📺 🇨🇳 · _UP主 马克的技术工作坊_ — 中文圈经典 MCP 入门：讲解 MCP Server 与 Tool 概念、Host 配置、uvx/npx 类服务器的使用与交互流程。
- [国内爽用 Claude Code + Codex，2分钟搞定！](https://www.bilibili.com/video/BV14JEj6uEdG) 📺 🇨🇳 · _UP主 程序员鱼皮_ — 2 分钟教你在国内用开源工具 CC Switch 配置 Claude Code 与 Codex，并接入 DeepSeek 等国产模型。
- [Claude Code 零基础终极教程：安装、换模型、插件、Hooks、Skills、Subagents、实战项目一次讲透！](https://www.bilibili.com/video/BV1TTR8BaEnL) 📺 🇨🇳 · _UP主 木子不写代码_ — 零基础终极教程：安装、第三方模型接入、权限，再到 Hooks、Skills、Subagents，最后实战做出一个 AI 网页应用。
- [Agent Skills (Claude Skills) 详细攻略，一期视频精通](https://www.bilibili.com/video/BV1HuiyBQE9G) 📺 🇨🇳 · _UP主 技术爬爬虾_ — 一期视频精通 Agent Skills：概念、原理、多个实用案例，以及 Skills 与 MCP 的区别与配合。
- [用过上百款编程MCP，只有这15个真正好用，Claude Code与Codex配置MCP详细教程](https://www.bilibili.com/video/BV1ZJsBznEt3) 📺 🇨🇳 · _UP主 技术爬爬虾_ — 实测上百款编程类 MCP 后精选 15 个真正好用的，并演示在 Claude Code 与 Codex 中的配置方法。
- [告别Vibe Coding！用Superpowers让Claude Code写出工程级代码](https://www.bilibili.com/video/BV11urFBrEc4) 📺 🇨🇳 · _UP主 AI超元域_ — 详解 Superpowers 工作流：头脑风暴、编写计划、子代理 TDD 执行与两阶段代码审查，以开发 iOS 应用为例演示。
- [最火AI编程Claude Code详细攻略，一期视频精通](https://www.bilibili.com/video/BV1XGbazvEuh) 📺 🇨🇳 · _UP主 技术爬爬虾_ — Claude Code 详细攻略，讲解 30 个进阶使用技巧，一期视频精通。
- [Claude Code: 从零搭建你的 AI 工作团队（Skills + Agents）| 回到Axton](https://www.bilibili.com/video/BV1eADaBME5z) 📺 🇨🇳 · _UP主 回到Axton_ — 知名效率博主回到Axton 演示如何用 Skills + Agents 在 Claude Code 中从零搭建 AI 工作团队。
- [2026 AI效率组合神器：Superpowers + Claude Code 保姆级教程](https://www.bilibili.com/video/BV1yaRQB9EeQ) 📺 🇨🇳 · _UP主 全栈斌少_ — 保姆级教程：在 Claude Code 中安装并使用开源 AI 编程工作流框架 Superpowers。
- [Claude Opus 5.5：前端之王重回它的宝座 AI 前端能力全面测试](https://www.bilibili.com/video/BV1NRhp6XEiq) 📺 🇨🇳 · _UP主 无机酸-\_-_ — Claude Opus 5.5 前端能力全面实测，在 Claude Code 与网页端结合主客观评分，评估其是否重回前端第一。
- [从 0 到 1：6小时掌握 Vibe Coding！Claude Code ＋ AI](https://www.bilibili.com/video/BV1ZjDYB7Eam) 📺 🇨🇳 · _UP主 李哈利Harry_ — 约 6 小时的 Vibe Coding 长课：Claude Code 核心功能、AI 前端设计、RAG 知识库、多模态资料处理、Agent 自动化与数据安全。
- [Hooks入门只需5分钟](https://www.bilibili.com/video/BV1yDLG6DE39) 📺 🇨🇳 · _UP主 Yin\_Code_ — 5 分钟入门 Claude Code Hooks：是什么、怎么配置，并手把手做一个实用 Hook，配套素材已开源到 GitHub。
- [把Claude Code工作流程做成可交互动画，5分钟即可掌握Claude Code工作原理！](https://www.bilibili.com/video/BV1toQbBtEDg) 📺 🇨🇳 · _UP主 轩辕的编程宇宙_ — 用可交互动画讲解 Claude Code 的工作流程与原理，并提供配套模拟器可在线体验。
- [Claude Code Workflow自动生成Harness！彻底抹平Harness Engineering技术鸿沟](https://www.bilibili.com/video/BV15UG16nEtz) 📺 🇨🇳 · _UP主 AI超元域_ — 保姆级演示 Claude Code 新 Workflow 功能：自动生成 Harness 并运行多智能体开发。
- [Claude Code 插件选型指南：原生 vs 四大框架(superpowers, ECC, GSD, Ralph)](https://www.bilibili.com/video/BV1yvAzzkEek) 📺 🇨🇳 · _UP主 探索未至之境_ — 对比 Claude Code 原生能力与 superpowers、ECC、GSD、Ralph 四大插件框架，分析冲突并给出选型决策树。
- [Claude Code 为什么不会撑爆上下文？深入解析 Agent 上下文压缩与会话恢复机制](https://www.bilibili.com/video/BV1nJ396JEmC) 📺 🇨🇳 · _UP主 唐国梁Tommy_ — 深入解析 Claude Code 如何通过上下文投影、历史压缩、Prompt Cache 与会话恢复维持长时间 Agent 任务。
- [马克的技术工作坊 · Bilibili](https://space.bilibili.com/1815948385) 📡 🇨🇳 — 以“从原理到实战”著称的 UP 主，MCP 终极指南、Agent Skill、Claude Code 全攻略等视频多次接近或突破百万播放。
- [程序员鱼皮 · Bilibili](https://space.bilibili.com/12890453) 📡 🇨🇳 — 头部编程 UP 主，持续产出国内使用 Claude Code、AI 编程工具横评、用 Claude Code 开发项目等内容。
- [AI超元域 · Bilibili](https://space.bilibili.com/3493277319825652) 📡 🇨🇳 — 专注 Claude Code 实战工作流的 UP 主：Superpowers、Ralph、Workflow/Harness、记忆类 MCP 以及与 Codex 的对比等。

<a id="cn-guides"></a>
### 中文文档与教程

<sub>中文翻译、手册与文章。</sub>

- 🏆 **[AI-Coding-Guide-Zh (Claude Code 中文教程)](https://github.com/KimYx0207/AI-Coding-Guide-Zh)** 🇨🇳 ⭐ 6.3k — 体量最大的中文 AI 编程教程之一：50 篇完整教程 + 速查卡，覆盖 Claude Code、Codex、OpenClaw、WorkBuddy 四条学习路径。
- 🏆 **[Claude Code 官方中文文档](https://code.claude.com/docs/zh-CN/overview)** 📘 🇨🇳 — Anthropic 官方 Claude Code 简体中文文档，覆盖安装、CLAUDE.md、Skills、Hooks、MCP、子代理、Agent SDK 等，权威首选。
- [鱼皮 AI 知识库 (ai-guide)](https://github.com/liyupi/ai-guide) 🇨🇳 ⭐ 21.6k — 程序员鱼皮的免费 AI 知识库与 Vibe Coding 教程，包含 Claude Code 专题、神级技巧、用 AI 手搓 Claude Code 等内容。
- [claude-howto-zh-cn](https://github.com/lhfer/claude-howto-zh-cn) 🇨🇳 ⭐ 2.3k — 基于 luongnv89/claude-howto 本土化重写的 Claude Code 中文上手指南，面向小白，保留命令与配置兼容并附学习路径。
- [everything-claude-code-zh](https://github.com/xu-xiang/everything-claude-code-zh) 🇨🇳 ⭐ 2k — everything-claude-code 中文翻译：源自 Anthropic 黑客松获胜者的完整配置集合（agents、skills、hooks、commands、rules、MCP）。
- [claude-code-guide（国内如何使用 Claude Code）](https://github.com/claude-code-chinese/claude-code-guide) 🇨🇳 ⭐ 689 — 通俗易懂的 Claude Code 中文介绍与教学指南，包含国内环境使用说明（2026 版）。
- [awesome-claudcode-tutorial](https://github.com/xianyu110/awesome-claudcode-tutorial) 🇨🇳 ⭐ 619 — 最全面的 Claude Code 中文教程之一：200+ 篇文章与 29 章课程，从零基础到企业级应用。
- [Claude Code 橙皮书 (claude-code-orange-book)](https://github.com/alchaincyf/claude-code-orange-book) 🇨🇳 ⭐ 327 — 独立开发者花叔的「橙皮书」系列之 Claude Code 完全指南，AI 编程实战路线，提供中文版。
- [菜鸟教程 Claude Code 教程](https://www.runoob.com/claude-code/claude-code-tutorial.html) 🎓 🇨🇳 — 菜鸟教程的 Claude Code 系列教程，章节齐全：安装、DeepSeek/Coding Plan 配置、CLAUDE.md、MCP、子代理、Skills、Hooks、Agent SDK 等。
- [Claude Code 完全指南：使用方式、技巧与最佳实践（掘金）](https://juejin.cn/post/7592079304923824138) 📝 🇨🇳 · _作者 knqiufan_ — 掘金长文参考手册：安装、Skills、Hooks、MCP、子代理、CLAUDE.md、高级模式、技巧与排错一网打尽。
- [Claude Code 怎么学？推荐 4 个高质量开源教程（掘金）](https://juejin.cn/post/7646780600486412340) 📝 🇨🇳 · _作者 JavaGuide_ — JavaGuide 在掘金推荐的 4 个高质量 Claude Code 开源教程（AI-Coding-Guide-Zh、AIGuide、awesome-claudcode-tutorial、橙皮书）。
- [看这一篇就够了！Claude Code 接入四大国产编程模型 DeepSeek、GLM、Qwen、Kimi 全指南（知乎）](https://zhuanlan.zhihu.com/p/1944667171704779382) 📝 🇨🇳 — 知乎指南：无需 CCR 中转，直接用 Anthropic 兼容接口把 DeepSeek、GLM、通义 Qwen、Kimi 接入官方 Claude Code。
- [这可能是目前最全的 Claude Code 使用指南（2025 版）（知乎）](https://zhuanlan.zhihu.com/p/1954938233126381432) 📝 🇨🇳 — 知乎上流传较广的 Claude Code 全面使用指南（2025 版），系统梳理用法与最佳实践。
- [最新 Agentic Coding：Claude Code 官方最佳实践（知乎）](https://zhuanlan.zhihu.com/p/1997843063482123604) 📝 🇨🇳 — 知乎解读 Claude Code 官方最佳实践，穿插 Claude Code 之父 Boris Cherny 分享的真实工作流，强调为 Claude 提供验证手段。
- [Claude Code子代理完全指南：从0到1构建你的AI编程军团（腾讯云开发者社区）](https://cloud.tencent.com/developer/article/2553995) 📝 🇨🇳 · _作者 前端达人_ — 腾讯云开发者社区文章：讲解 Claude Code 子代理概念，演示用 /agents 创建代码验证、前端、API、审查、调研等专用代理。

<a id="cn-community"></a>
### 中文社区平台

<sub>中文开发者分享 Claude 项目的论坛与平台。</sub>

- 🏆 **[LINUX DO](https://linux.do)** 💬 🇨🇳 — 国内最活跃的开发者社区之一，“开发调优”“资源荟萃”等板块大量分享 Claude Code 工具、工作流与开源项目（如 Trellis、CCG）。
- [V2EX · Claude 节点](https://www.v2ex.com/go/claude) 💬 🇨🇳 — V2EX 的 Claude 节点，1000+ 主题，讨论 Claude / Claude Code 使用经验、可用性与踩坑。
- [WaytoAGI 通往AGI之路 · AI 编程](https://waytoagi.feishu.cn/wiki/Pxj8wsMmOii7ZSkN0mYc8xdtnHb) 💬 🇨🇳 — 国内最大的开源 AI 知识库 WaytoAGI（飞书）中的 AI 编程板块，收录 Claude Code 等工具介绍与社区教程。
- [哔哩哔哩 · Claude Code 搜索](https://search.bilibili.com/all?keyword=Claude+Code) 💬 🇨🇳 — B 站 Claude Code 搜索页，中文 Claude Code 教程、评测与实战视频的主要聚集地。
- [科技爱好者周刊 (ruanyf/weekly)](https://github.com/ruanyf/weekly/issues) 💬 🇨🇳 — 阮一峰的《科技爱好者周刊》，开发者可通过 GitHub Issue 自荐项目，许多 Claude 相关工具都在这里被推荐。

<a id="cn-providers"></a>
### 国内模型接入 Claude Code

<sub>提供 Anthropic 兼容接口的国内模型厂商官方接入文档。</sub>

- 🏆 **[智谱 GLM Coding Plan · Claude Code 接入文档](https://docs.bigmodel.cn/cn/coding-plan/tool/claude)** 📘 🇨🇳 — 智谱官方文档：通过 Anthropic 兼容接口 open.bigmodel.cn/api/anthropic 在 Claude Code 中使用 GLM Coding Plan，含模型映射与一键配置。
- 🏆 **[DeepSeek API 文档 · 使用 Anthropic API（接入 Claude Code）](https://api-docs.deepseek.com/zh-cn/guides/anthropic_api)** 📘 🇨🇳 — DeepSeek 官方 Anthropic 格式兼容文档（api.deepseek.com/anthropic），含接入 Claude Code 说明与字段兼容性表。
- [Kimi 开放平台 · 在 Claude Code 中使用 Kimi](https://platform.kimi.com/docs/guide/claude-code-kimi) 📘 🇨🇳 — 月之暗面官方文档：通过环境变量把 Claude Code 请求转发到 Kimi（api.moonshot.cn/anthropic），推荐 kimi-k3 等模型。
- [阿里云百炼 · Claude Code 接入](https://help.aliyun.com/zh/model-studio/claude-code) 📘 🇨🇳 — 阿里云百炼官方文档：按量计费、Coding Plan、Token Plan 三种方式在 Claude Code 中使用千问模型，含 CC Switch 配置。
- [MiniMax 开放平台 · Claude Code](https://platform.minimax.cn/docs/coding-plan/claude-code) 📘 🇨🇳 — MiniMax 中国站官方文档：通过 api.minimax.cn/anthropic 在 Claude Code 中使用 MiniMax 模型（Coding Plan）。
- [火山方舟 Coding Plan · 接入 Claude Code](https://docs.volcengine.com/docs/82379/2406397) 📘 🇨🇳 — 字节跳动火山方舟 Coding Plan 官方文档“接入 AI 工具 - Claude Code”，可用豆包及 GLM、Kimi、DeepSeek、MiniMax 等模型。
- [硅基流动 SiliconFlow · 在 Claude Code 中使用](https://docs.siliconflow.cn/cn/usercases/use-siliconcloud-in-ClaudeCode) 📘 🇨🇳 — 硅基流动官方文档：在 Claude Code 中使用 SiliconCloud 托管的开源模型（通义、DeepSeek、GLM、Kimi 等）。
- [腾讯云 · DeepSeek Anthropic 兼容接口（接入 Claude Code）](https://cloud.tencent.cn/document/product/1772/126272) 📘 🇨🇳 — 腾讯云官方文档：DeepSeek Anthropic 兼容接口（api.lkeap.cloud.tencent.com/anthropic），含接入 Claude Code 的安装与环境变量配置。

<a id="cn-projects"></a>
### 国人开发项目速览

<sub>以下为上方各功能分类中由中国开发者创建的项目汇总。</sub>

[CC Switch](https://github.com/farion1231/cc-switch) ⭐149k · [LobeHub](https://github.com/lobehub/lobehub) ⭐83.5k · [Learn Claude Code](https://github.com/shareAI-lab/learn-claude-code) ⭐79.2k · [Cherry Studio](https://github.com/CherryHQ/cherry-studio) ⭐53k · [Claude Code Router](https://github.com/musistudio/claude-code-router) ⭐37.9k · [AionUi](https://github.com/iOfficeAI/AionUi) ⭐33.8k · [baoyu-skills](https://github.com/JimLiu/baoyu-skills) ⭐27k · [NextChat](https://github.com/ChatGPTNextWeb/NextChat) ⭐88.9k · [Chatbox](https://github.com/chatboxai/chatbox) ⭐42.1k · [avante.nvim](https://github.com/avante-corp/avante.nvim) ⭐18.2k · [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) ⭐16.6k · [cc-connect](https://github.com/chenhg5/cc-connect) ⭐16.1k · [Trellis](https://github.com/mindfold-ai/Trellis) ⭐15k · [Claude Context](https://github.com/zilliztech/claude-context) ⭐12.6k · [Chrome MCP Server (mcp-chrome)](https://github.com/hangwin/mcp-chrome) ⭐12.5k · [Awesome-MCP-ZH](https://github.com/yzfly/Awesome-MCP-ZH) ⭐7.8k · [jetbrains-cc-gui](https://github.com/zhukunpenglinyutong/jetbrains-cc-gui) ⭐7.3k · [CodePilot](https://github.com/op7418/CodePilot) ⭐6.5k · [DeepChat](https://github.com/ThinkInAIXYZ/deepchat) ⭐6.4k · [ZCF (Zero-Config Code Flow)](https://github.com/UfoMiao/zcf) ⭐6.1k · [CCG Workflow](https://github.com/fengshao1227/ccg-workflow) ⭐5.9k · [ArcReel](https://github.com/ArcReel/ArcReel) ⭐5.7k · [Awesome Claude Prompts](https://github.com/langgptai/awesome-claude-prompts) ⭐5.5k · [5ire](https://github.com/nanbingxyz/5ire) ⭐5.4k · [Kode](https://github.com/shareAI-lab/Kode-CLI) ⭐5.2k · [mcp-feedback-enhanced](https://github.com/Minidoracat/mcp-feedback-enhanced) ⭐3.8k · [CCometixLine](https://github.com/Haleclipse/CCometixLine) ⭐3.5k · [claude-code-proxy (fuergaosi233)](https://github.com/fuergaosi233/claude-code-proxy) ⭐2.8k · [CodexMCP](https://github.com/GuDaStudio/codexmcp) ⭐2k · [claude-code-settings (feiskyer)](https://github.com/feiskyer/claude-code-settings) ⭐1.7k · [NekroAgent](https://github.com/KroMiose/nekro-agent) ⭐1.2k · [Claude_skills_zh-CN](https://github.com/LeastBit/Claude_skills_zh-CN) ⭐599 · [awesome-claude-code (LangGPT 中文版)](https://github.com/LangGPT/awesome-claude-code) ⭐272 · [Z.ai GLM Coding Plan for Claude Code](https://docs.z.ai/devpack/tool/claude) · [mcp.so](https://mcp.so) · [魔搭 ModelScope MCP 广场](https://modelscope.cn/mcp) · [awesome-agent-skills (Agent Skills 终极指南)](https://github.com/libukai/awesome-agent-skills)

<div align="right"><a href="#top">↑ 返回顶部</a></div>

---

<a id="community"></a>
## 🌏 全球社区

_社区聚集地、日语/韩语等其他语言资源，以及相关的 Awesome 列表。_

<a id="communities"></a>
### 社区与活动

<sub>Reddit、Discord、值得关注的账号与活动。</sub>

- 🏆 **[r/ClaudeAI](https://www.reddit.com/r/ClaudeAI)** 💬 — 规模最大的 Claude 子版块，Anthropic 社区页面也有链接；涵盖新闻、作品展示、Claude Code 讨论和用量限制争论。
- 🏆 **[r/ClaudeCode](https://www.reddit.com/r/ClaudeCode)** 💬 — Claude Code 专属子版块，用于构建、学习和分享：工作流、工具、求助与作品展示。
- 🏆 **[Boris Cherny (@bcherny)](https://x.com/bcherny)** 💬 — Claude Code 创造者兼负责人；他在 X 上分享个人配置和团队工作流的帖子被广泛转发。
- [r/Anthropic](https://www.reddit.com/r/Anthropic) 💬 — 讨论 Anthropic 公司及其模型、政策和产品（含 Claude Code）的子版块。
- [Claude Community](https://claude.com/community) 🌐 — Anthropic 社区中心：大使计划和校园计划、城市聚会、Discord、Reddit、项目提交和月度通讯。
- [Claude Community Events (Luma)](https://luma.com/claudecommunity) 💬 — 全球日历，汇集由大使组织的 Claude 与 Claude Code 线下聚会、工作坊和黑客松，覆盖数十个城市。
- [Code with Claude](https://claude.com/code-with-claude) 🌐 — Anthropic 开发者大会；2026 年在旧金山、伦敦和东京举办，Claude Code 专场提供录像。
- [@AnthropicAI on X](https://x.com/AnthropicAI) 💬 — Anthropic 官方 X 账号，发布公司公告、研究、安全进展和重大模型发布。
- [@claudeai on X](https://x.com/claudeai) 💬 — Claude 产品官方 X 账号，发布新功能、Claude Code 上线消息和使用技巧。
- [@ClaudeDevs on X](https://x.com/ClaudeDevs) 💬 — 2026 年 4 月上线的开发者 X 账号，发布更新日志、API 发布和技术深度解读。
- [Cat Wu (@_catwu)](https://x.com/_catwu) 💬 — Anthropic 的 Claude Code 产品负责人，发布功能公告和实用技巧。
- [Thariq Shihipar (@trq212)](https://x.com/trq212) 💬 — Claude Code 团队工程师，分享工作流、内部理念以及在 Claude Code 中使用 HTML 等技巧。
- [Tell HN: I'm 60 years old. Claude Code has re-ignited a passion](https://news.ycombinator.com/item?id=47282777) 💬 — Hacker News 标志性帖子（2026 年 3 月），近千条评论讨论 Claude Code 如何改变人们与编程的关系。

<a id="intl-community"></a>
### 日语、韩语及其他语言

<sub>中文以外同样活跃的非英语社区。</sub>

- [Zenn: Claude Code topic](https://zenn.dev/topics/claudecode) 💬 🇯🇵 — 日本主要的 Claude Code 开发者博客聚集地，拥有 11,000 多篇文章以及书籍和笔记。
- [Qiita: ClaudeCode tag](https://qiita.com/tags/claudecode) 💬 🇯🇵 — Qiita 上的 Claude Code 标签，有近 9,800 篇日文文章和超过 24,000 名关注者。
- [note: #ClaudeCode](https://note.com/hashtag/ClaudeCode) 💬 🇯🇵 — note.com 上的标签，收录数千篇日文 Claude Code 文章，许多面向非工程师和业务自动化。
- [実践Claude Code入門 (Gijutsu-Hyoronsha)](https://gihyo.jp/book/2026/978-4-297-15354-0) 📘 🇯🇵 — 日文书籍（2025 年 12 月），讲解如何用 Claude Code 重塑开发流程：规格驱动开发、MCP 和 Claude Code Action。
- [Claude CodeによるAI駆動開発入門 (Gijutsu-Hyoronsha)](https://gihyo.jp/book/2025/978-4-297-15275-8) 📘 🇯🇵 — 320 页的日文入门书（2025 年 12 月），讲解如何用 Claude Code 进行 AI 驱动开发。
- [Claude Code実践入門 (生成AI深掘りガイド) (SB Creative)](https://www.sbcr.jp/product/4815643119) 📘 🇯🇵 — 日文 Claude Code 智能体编程实战指南，2026 年 8 月出版。
- [【一人社長】Claude Codeで会社を作ってAI社員に仕事を任せてみよう！](https://www.youtube.com/watch?v=cfoE_8Llde0) 📺 🇯🇵 · _作者 プログラミングチュートリアル_ — 播放量最高的日文 Claude Code 视频之一：用 Claude Code 的“AI 员工”经营一人公司。
- [GeekNews (긱뉴스)](https://news.hada.io) 💬 🇰🇷 — 韩国主要的开发者新闻聚合站，经常发布 Claude Code 新闻的韩文摘要和讨论。

<a id="awesome-lists"></a>
### 相关 Awesome 列表

<sub>其他值得收藏的精选列表。</sub>

- 🏆 **[Awesome Claude Code](https://github.com/hesreallyhim/awesome-claude-code)** ⭐ 56.6k — 最具代表性的 Claude Code 精选清单，收录技能、钩子、斜杠命令、编排器、应用与插件。
- [Awesome Claude Skills (ComposioHQ)](https://github.com/ComposioHQ/awesome-claude-skills) ⭐ 78k — 精选 Claude Skills、资源与工具清单，用于定制 Claude 工作流。
- [awesome-claude-code (LangGPT 中文版)](https://github.com/LangGPT/awesome-claude-code) 🇨🇳 ⭐ 272 — LangGPT 社区（云中江树）整理的 Claude Code 精选资源列表，提供简体中文版，收录项目、提示词、智能体与命令。
- [awesome-agent-skills (Agent Skills 终极指南)](https://github.com/libukai/awesome-agent-skills) 🇨🇳 — 中文为主的 Agent Skills 终极指南：快速入门、资源推荐、精选技能与实用工具，聚焦 Claude 生态。

<div align="right"><a href="#top">↑ 返回顶部</a></div>

---

## 🤝 参与贡献

发现了好项目？欢迎提交 [Issue](https://github.com/tomcatmew/awesome-Claude-code/issues/new/choose) 或 Pull Request。所有条目存放在 [`data/projects.json`](data/projects.json)，运行 `python scripts/build.py` 即可重新生成 README 与网站数据。详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 📈 Star 趋势

[![Star History Chart](https://api.star-history.com/svg?repos=tomcatmew/awesome-Claude-code&type=Date)](https://star-history.com/#tomcatmew/awesome-Claude-code&Date)

## 📄 许可证

[CC0 1.0](LICENSE) —— 在法律允许的范围内，整理者放弃本列表的全部版权。

<sub>本项目为社区项目，与 Anthropic 无隶属或背书关系。Claude 与 Claude Code 是 Anthropic, PBC 的商标。所列项目归各自作者所有——运行前请先审阅代码，尤其是会在本机执行的钩子、插件与 MCP 服务器。</sub>
