<!-- GENERATED FILE: do not edit directly -->
<h3 align="center">选择您喜欢的风格:</h3>
<p align="center">
<a href="https://github.com/hesreallyhim/awesome-claude-code/blob/main/"><img src="https://github.com/hesreallyhim/awesome-claude-code/blob/main/assets/badge-style-awesome.svg" alt="Awesome" height="28" style="border: 2px solid #cc3366; border-radius: 4px;"></a>
<a href="https://github.com/hesreallyhim/awesome-claude-code/blob/main/README_ALTERNATIVES/README_EXTRA.md"><img src="https://github.com/hesreallyhim/awesome-claude-code/blob/main/assets/badge-style-extra.svg" alt="Extra" height="28"></a>
<a href="https://github.com/hesreallyhim/awesome-claude-code/blob/main/README_ALTERNATIVES/README_CLASSIC.md"><img src="https://github.com/hesreallyhim/awesome-claude-code/blob/main/assets/badge-style-classic.svg" alt="Classic" height="28"></a>
<a href="https://github.com/hesreallyhim/awesome-claude-code/blob/main/README_ALTERNATIVES/README_FLAT_ALL_AZ.md"><img src="https://github.com/hesreallyhim/awesome-claude-code/blob/main/assets/badge-style-flat.svg" alt="Flat" height="28"></a>
</p>

<p align="center">
  <picture>
    <img src="https://github.com/hesreallyhim/awesome-claude-code/blob/main/assets/ACC-social-banner.png" alt="Awesome Claude Code" width="600">
  </picture>
</p>

# Awesome Claude Code

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 一个精心策划的技能、代理、插件、钩子和其他令人惊叹的工具列表，用于增强您的 [Claude Code](https://docs.anthropic.com/en/docs/claude-code) 工作流程。

<div align="center">

<img src="https://github.com/hesreallyhim/awesome-claude-code/blob/main/assets/repo-ticker-awesome.svg" alt="Featured Claude Code Projects" width="100%">

</div>



## 最新添加

- [claude-pace](https://github.com/Astro-Han/claude-pace) by [Astro-Han](https://github.com/Astro-Han) - 一个轻量级的 Bash + jq 状态栏工具，用于 Claude Code，显示速率限制节奏增量（消耗率与剩余时间）、5小时/7天使用百分比、上下文窗口使用情况、git 分支和差异统计。比较当前消耗率与每个速率限制窗口的剩余时间，以指示配额是否比窗口允许的更快或更慢使用。单个文件，除 jq 外无外部依赖。
- [Clawd on Desk](https://github.com/rullerzhou-afk/clawd-on-desk) by [Ruller_Lulu](https://github.com/rullerzhou-afk) - 一个桌面宠物，实时响应您的 Claude Code 会话——思考、打字、杂耍、睡觉等等。是的，它确实很可爱。归根结底，这不就是 Claude Code 的全部意义所在吗？
- [ccxray](https://github.com/lis186/ccxray) by [lis186](https://github.com/lis186) - 一个透明的 HTTP 代理和实时仪表板，位于 Claude Code 和 Anthropic API 之间。无需配置即可捕获每个请求和响应，并以 Miller 列界面呈现，具有会话分组、令牌/成本跟踪和上下文窗口可视化功能。
- [Encyclopedia of Agentic Coding Patterns](https://aipatternbook.com) by [Wolf McNally](https://github.com/wolfmcnally) - 一个免费可用的参考资源，涵盖 190+ 种 AI 辅助软件开发模式（实际上还有大量相关技术主题），从基础概念到代理构建模式、治理、测试和社会技术系统。每个条目遵循一致的模式语言格式，包括上下文、问题、力量、解决方案、后果和相关模式。观点鲜明且博学，这在某些方面对于"百科全书"来说实际上是好事。


## 目录

- [代理技能 🤖](#agent-skills-)
  - [通用](#general)
- [工作流程与知识指南 🧠](#workflows--knowledge-guides-)
  - [通用](#general-1)
  - [团队](#teams)
  - [Ralph Wiggum](#ralph-wiggum)
- [工具 🧰](#tooling-)
  - [通用](#general-2)
  - [IDE 集成](#ide-integrations)
  - [使用监控](#usage-monitors)
  - [编排器](#orchestrators)
  - [配置管理器](#config-managers)
- [状态栏 📊](#status-lines-)
  - [通用](#general-3)
- [钩子 🪝](#hooks-)
  - [通用](#general-4)
- [斜杠命令 🔪](#slash-commands-)
  - [通用](#general-5)
  - [版本控制与 Git](#version-control--git)
  - [代码分析与测试](#code-analysis--testing)
  - [上下文加载与预热](#context-loading--priming)
  - [文档与变更日志](#documentation--changelogs)
  - [CI / 部署](#ci--deployment)
  - [项目与任务管理](#project--task-management)
  - [其他](#miscellaneous)
- [CLAUDE.md 文件 📂](#claudemd-files-)
  - [语言特定](#language-specific)
  - [领域特定](#domain-specific)
  - [项目脚手架与 MCP](#project-scaffolding--mcp)
- [替代客户端 📱](#alternative-clients-)
  - [通用](#general-6)
- [官方文档 🏛️](#official-documentation-%EF%B8%8F)
  - [通用](#general-7)

## 代理技能 🤖

> 代理技能是由模型控制的配置（文件、脚本、资源等），使 Claude Code 能够执行需要特定知识或能力的专业任务。

### 通用

- [AgentSys](https://github.com/avifenesh/agentsys) by [avifenesh](https://github.com/avifenesh) - Claude 的工作流程自动化系统，包含一组有用的插件、代理和技能。自动化从任务到生产的工作流程、PR 管理、代码清理、性能调查、漂移检测和多代理代码审查。包含 [agnix](https://github.com/avifenesh/agnix) 用于检查代理配置。基于数千行代码和数千个测试构建。使用确定性检测（正则表达式、AST）和 LLM 判断以提高效率。在许多生产系统中使用。
- [AI Agent, AI Spy](https://youtu.be/0ANECpNdt-4) by [Whittaker & Tiwari](https://signalfoundation.org/) - Signal Foundation 的成员提供了一些关于如何将您的操作系统变成全面监控工具的绝佳技巧和窍门，以及为什么一些公司正在做这件非常棒的事情。[警告：YouTube 链接]。
- [Book Factory](https://github.com/robertguss/claude-skills) by [Robert Guss](https://github.com/robertguss) - 一个全面的技能管道，使用专业的 Claude 技能复制传统出版基础设施用于非虚构书籍创作。
- [cc-devops-skills](https://github.com/akin-ozer/cc-devops-skills) by [akin-ozer](https://github.com/akin-ozer) - 为 DevOps 工程师（或任何需要部署代码的人）提供的极其详细的技能集。与验证器、生成器、shell 脚本和 CLI 工具配合使用，为几乎所有您曾经痛苦工作的平台创建高质量的 IaC 代码。即使仅作为文档来源也值得下载。
- [Claude Code Agents](https://github.com/undeadlist/claude-code-agents) by [Paul - UndeadList](https://github.com/undeadlist) - 面向独立开发者的全面端到端开发工作流程，包含有用的 Claude Code 子代理提示。并行运行多个审计器，使用微检查点协议自动化修复周期，并进行基于浏览器的 QA。包含严格的协议以防止 AI 失控。
- [Claude Codex Settings](https://github.com/fcakyon/claude-codex-settings) by [fatih akyon](https://github.com/fcakyon) - 一组组织良好、编写精良的插件，涵盖核心开发活动，例如与 GitHub、Azure、MongoDB 等常见云平台以及 Tavily、Playwright 等流行服务配合使用。清晰、不过于主观化，并与几个其他提供商兼容。
- [Claude Mountaineering Skills](https://github.com/dreamiurg/claude-mountaineering-skills) by [Dmytro Gaivoronsky](https://github.com/dreamiurg) - 自动研究北美山峰登山路线的 Claude Code 技能。从 Mountaineers.org、PeakBagger.com 和 SummitPost.com 等 10 多个登山来源聚合数据，生成详细的路线 beta 报告，包括天气、雪崩条件和旅行报告。
- [Claude Scientific Skills](https://github.com/K-Dense-AI/claude-scientific-skills) by [K-Dense](https://github.com/K-Dense-AI/) - "一组用于研究、科学、工程、分析、金融和写作的即用型代理技能。"这是他们的描述——谦虚、简单。这就是为什么你可以看出这确实是 GitHub 上最好的技能仓库之一。如果你曾经想过攻读博士学位……只需阅读所有这些文档即可。另外我认为它确实是一个 AI 代理或其他东西？太棒了。
- [Codebase to Course](https://github.com/zarazhangrui/codebase-to-course) by [Zara Zhang](https://github.com/zarazhangrui) - 一个 Claude Code 技能，可将任何代码库转换为精美的交互式单页 HTML 课程，面向非技术氛围的编码者。
- [Codex Skill](https://github.com/skills-directory/skill-codex) by [klaudworks](https://github.com/klaudworks) - 使用户能够从 claude code 提示 codex。与原始的 codex mcp 服务器不同，此技能从您的提示中推断模型、推理努力、沙箱等参数，或要求您指定它们。它还简化了继续先前的 codex 会话，以便 codex 可以继续先前的上下文。
- [Compound Engineering Plugin](https://github.com/EveryInc/compound-engineering-plugin) by [EveryInc](https://github.com/EveryInc) - 一组非常实用的设计良好的代理、技能和命令，围绕将过去的错误和错误转化为未来增长和改进的经验和机会的纪律而构建。文档良好。
- [Context Engineering Kit](https://github.com/NeoLabHQ/context-engineering-kit) by [Vlad Goncharov](https://github.com/LeoVS09) - 手工制作的高级上下文工程技术和模式集合，具有最小的令牌占用，专注于提高代理结果质量。
- [Everything Claude Code](https://github.com/affaan-m/everything-claude-code) by [Affaan Mustafa](https://github.com/affaan-m/) - 顶级的、编写精良的资源，涵盖核心工程领域的"几乎所有内容"。这个"everything-"商店的好处是大多数资源具有显著的独立价值，与一些包罗万象的框架不同，虽然您可以选择加入作者自己的特定工作流程模式，但个别资源在（几乎）您可以找到的每个 Claude Code 功能中都提供了典范模式（向输出样式爱好者致歉）。
- [Fullstack Dev Skills](https://github.com/jeffallan/claude-skills) by [jeffallan](https://github.com/jeffallan) - 一个全面的 Claude Code 插件，具有 65 个专业技能，涵盖跨各种特定框架的全栈开发。具有 9 个用于 Jira/Confluence 集成的项目工作流程命令，值得注意的是，通过 `/common-ground` 命令采用有趣的上下文工程方法，该命令揭示 Claude 对您项目的隐藏假设。这是一个明智的做法。
- [read-only-postgres](https://github.com/jawwadfirdousi/agent-skills) by [jawwadfirdousi](https://github.com/jawwadfirdousi) - Claude Code 的只读 PostgreSQL 查询技能。在配置的数据库上执行 SELECT/SHOW/EXPLAIN/WITH 查询，具有严格的验证、超时和行限制。支持多个连接，并提供描述用于数据库选择。
- [Superpowers](https://github.com/obra/superpowers) by [Jesse Vincent](https://github.com/obra) - 一组强大的软件工程核心能力，很好地覆盖了 SDLC 的大部分——从规划、审查、测试、调试……编写良好、组织良好且适应性强。作者称它们为"超能力"，但其中许多只是整合了工程最佳实践——在使用 Claude Code 时，这有时确实感觉像是一种超能力。
- [Trail of Bits Security Skills](https://github.com/trailofbits/skills) by [Trail of Bits](https://github.com/trailofbits) - 一组非常专业的安全技能集合，包含十几个用于代码审计和漏洞检测的技能。包括使用 CodeQL 和 Semgrep 进行静态分析的技能、跨代码库的变体分析、修复验证和差异代码审查。
- [TÂCHES Claude Code Resources](https://github.com/glittercowboy/taches-cc-resources) by [TÂCHES](https://github.com/glittercowboy) - 一组平衡良好、"脚踏实地"的子代理、技能和命令，组织良好、易于阅读，并且健康地关注"元"技能/代理，如"skill-auditor"、钩子创建等——这是您可以适应您工作流程的东西，而不是相反。
- [Web Assets Generator Skill](https://github.com/alonw0/web-asset-generator) by [Alon Wolenitz](https://github.com/alonw0) - 从 Claude Code 轻松生成 Web 资产，包括网站图标、应用程序图标（PWA）和用于 Facebook、Twitter、WhatsApp 和 LinkedIn 的社交媒体元图像（Open Graph）。处理图像调整大小、文本到图像生成、表情符号，并提供适当的 HTML 元标签。

<br>

## 工作流程与知识指南 🧠

> 工作流程是一组紧密耦合的 Claude Code 原生资源，用于促进特定项目

### 通用

- [AB Method](https://github.com/ayoubben18/ab-method) by [Ayoub Bensalah](https://github.com/ayoubben18) - 一个基于原则、规范驱动的工作流程，使用 Claude Code 的专业子代理将大问题转化为专注的、渐进的任务。包括为 SDLC 的特定部分设计的斜杠命令、子代理和专业工作流程。
- [Agentic Workflow Patterns](https://github.com/ThibautMelen/agentic-workflow-patterns) by [ThibautMelen](https://github.com/ThibautMelen) - 来自 Anthropic 文档的代理模式的全面且文档齐全的集合，每个模式都有彩色的 Mermaid 图表和代码示例。涵盖子代理编排、渐进式技能、并行工具调用、主从架构、向导工作流程等。也与其他提供商兼容。
- [Blogging Platform Instructions](https://github.com/cloudartisan/cloudartisan.github.io/tree/main/.claude/commands) by [cloudartisan](https://github.com/cloudartisan) - 为发布和维护博客平台提供一组结构良好的命令，包括创建帖子、管理类别和处理媒体文件的命令。
- [Claude Code Documentation Mirror](https://github.com/ericbuess/claude-code-docs) by [Eric Buess](https://github.com/ericbuess) - Claude Code 的 Anthropic &copy; PBC 文档页面的镜像，每几小时更新一次。在试图跟上 Dr. Claw D. Code, Ph.D. 不断扩展的功能集时非常有用。
- [Claude Code Handbook](https://nikiforovall.blog/claude-code-rules/) by [nikiforovall](https://github.com/nikiforovall) - Claude Code 开发工作流程的最佳实践、提示和技巧的集合，通过可分发的插件增强。
- [Claude Code Infrastructure Showcase](https://github.com/diet103/claude-code-infrastructure-showcase) by [diet103](https://github.com/diet103) - 一种非常创新的技能使用方法，其核心是一种利用钩子的技术，确保 Claude 根据当前上下文智能地选择和激活适当的技能。文档齐全，可适应不同的项目和工作流程。
- [Claude Code PM](https://github.com/automazeio/ccpm) by [Ran Aroussi](https://github.com/ranaroussi) - 非常全面且功能丰富的 Claude Code 项目管理工作流程。众多专业代理、斜杠命令和强大的文档。
- [Claude Code Repos Index](https://github.com/danielrosehill/Claude-Code-Repos-Index) by [Daniel Rosehill](https://github.com/danielrosehill) - 这要么是多产天才的作品，要么是一个非常聪明的机器人（或两者兼而有之），但这并不重要，因为质量是如此之好——作者发布的 75+ 个 Claude Code 仓库的索引——我不是在说垃圾。CMS、系统设计、深度研究、物联网、代理工作流程、服务器管理、个人健康……如果你发现谎言，请告诉我，否则请查看这些。
- [Claude Code System Prompts](https://github.com/Piebald-AI/claude-code-system-prompts) by [Piebald AI](https://github.com/Piebald-AI) - Claude Code 系统提示的所有部分，包括内置工具描述、子代理提示（Plan/Explore/Task）、实用提示（CLAUDE.md、compact、Bash cmd、安全审查、代理创建等）。针对每个 Claude Code 版本更新。
- [Claude Code Tips](https://github.com/ykdojo/claude-code-tips) by [ykdojo](https://github.com/ykdojo) - 35 多个简短但信息密集的 Claude Code 提示的不错选择，涵盖语音输入、系统提示修补、风险任务的容器工作流程、对话克隆（!）、与 Gemini CLI 的多模型编排等。不错的演示、可工作的脚本、一个插件，我想这可能对每个人都有一些东西。
- [Claude Code Ultimate Guide](https://github.com/FlorianBruniaux/claude-code-ultimate-guide) by [Florian BRUNIAUX](https://www.linkedin.com/in/florian-bruniaux-43408b83/) - 一项令人印象深刻的文档工作，本指南涵盖了从初学者到高级用户的 Claude Code，具有 Claude Code 功能的生产就绪模板、代理工作流程指南以及大量优秀的学习材料，包括测验和方便的"备忘单"。它是否是 Claude Code 的"终极"指南将由读者决定，但无论如何都是有价值的资源（与所有文档站点一样，在全力以赴之前请确保它是最新的）。
- [Claude CodePro](https://github.com/maxritter/claude-codepro) by [Max Ritter](https://www.maxritter.net) - Claude Code 的专业开发环境，具有规范驱动的工作流程、TDD 强制执行、跨会话记忆、语义搜索、质量钩子和模块化规则集成。有点"重量级"但功能丰富且覆盖面广。
- [claude-code-docs](https://github.com/costiash/claude-code-docs) by [Constantin Shafranski](https://github.com/costiash) - Claude/Code 的 Anthropic&copy; PBC 文档站点的镜像，但具有全文搜索和查询时更新等额外功能——`claude-code-docs` 的不错伴侣，提供最新、完全索引的信息，以便 Claude Code 可以阅读关于自己的信息。
- [ClaudoPro Directory](https://github.com/JSONbored/claudepro-directory) by [ghost](https://github.com/JSONbored) - 精心制作、广泛选择的 Claude Code 钩子、斜杠命令、子代理文件等，涵盖一系列专业任务和工作流程。比普通的"Claude-template-for-everything"站点更好的资源。
- [Context Priming](https://github.com/disler/just-prompt/tree/main/.claude/commands) by [disler](https://github.com/disler) - 通过针对不同项目场景和开发上下文的专业命令，提供系统的方法来用全面的项目上下文预热 Claude Code。
- [Design Review Workflow](https://github.com/OneRedOak/claude-code-workflows/tree/main/design-review) by [Patrick Ellis](https://github.com/OneRedOak) - 用于启用自动化 UI/UX 设计审查的定制工作流程，包括专业子代理、斜杠命令、`CLAUDE.md` 摘录等。涵盖从响应式设计到可访问性的广泛标准。
- [Encyclopedia of Agentic Coding Patterns](https://aipatternbook.com) by [Wolf McNally](https://github.com/wolfmcnally) - 一个免费可用的参考资源，涵盖 190+ 种 AI 辅助软件开发模式（实际上还有大量相关技术主题），从基础概念到代理构建模式、治理、测试和社会技术系统。每个条目遵循一致的模式语言格式，包括上下文、问题、力量、解决方案、后果和相关模式。观点鲜明且博学，这在某些方面对于"百科全书"来说实际上是好事。
- [Laravel TALL Stack AI Development Starter Kit](https://github.com/tott/laravel-tall-claude-ai-configs) by [tott](https://github.com/tott) - 通过全面的 Claude Code 配置转换您的 Laravel TALL（Tailwind、AlpineJS、Laravel、Livewire）堆栈开发，提供智能协助、系统工作流程和领域专家咨询。
- [Learn Claude Code](https://github.com/shareAI-lab/learn-claude-code) by [shareAI-Lab](https://github.com/shareAI-lab/) - 对像 Claude Code 这样的编码代理如何设计的非常有趣的分析。它试图将代理分解为基本部分并用最少的代码重建它。优秀的学习资源。最终产品是一个具有技能、子代理和待办事项列表的基本代理，大约几百行 Python 代码。
- [learn-faster-kit](https://github.com/cheukyin175/learn-faster-kit) by [Hugo Lau](https://github.com/cheukyin175) - 一个创意的 Claude Code 教育框架，受"FASTER"自学方法的启发。附带各种代理、斜杠命令和工具，使 Claude Code 能够帮助您以自己的节奏进步，采用主动学习和间隔重复等既定的教学技术。
- [n8n_agent](https://github.com/kingler/n8n_agent/tree/main/.claude/commands) by [kingler](https://github.com/kingler) - 用于代码分析、QA、设计、文档、项目结构、项目管理、优化等的令人惊叹的综合注释集。
- [Project Bootstrapping and Task Management](https://github.com/steadycursor/steadystart/tree/main/.claude/commands) by [steadycursor](https://github.com/steadycursor) - 为引导和管理新项目提供一组结构化的命令，包括用于创建和编辑自定义斜杠命令的元命令。
- [Project Management, Implementation, Planning, and Release](https://github.com/scopecraft/command/tree/main/.claude/commands) by [scopecraft](https://github.com/scopecraft) - SDLC 所有方面的非常全面的命令集。
- [Project Workflow System](https://github.com/harperreed/dotfiles/tree/master/.claude/commands) by [harperreed](https://github.com/harperreed) - 一组命令，提供用于管理项目的综合工作流程系统，包括任务管理、代码审查和部署流程。
- [RIPER Workflow](https://github.com/tony/claude-code-riper-5) by [Tony Narlock](https://tony.sh) - 结构化开发工作流程，强制研究、创新、计划、执行和审查阶段之间的分离。具有用于上下文效率的整合子代理、分支感知记忆库和用于引导开发的严格模式强制执行。
- [Shipping Real Code w/ Claude](https://diwank.space/field-notes-from-shipping-real-code-with-claude) by [Diwank](https://github.com/creatorrr) - 一篇详细的博客文章，解释作者使用 Claude Code 发布产品的过程，包括 CLAUDE.md 文件和其他有趣的资源。
- [Simone](https://github.com/Helmi/claude-simone) by [Helmi](https://github.com/Helmi) - 一个更广泛的 Claude Code 项目管理工作流程，不仅包含一组命令，还包含文档、指南和流程系统，以促进项目规划和执行。

### 团队

- [Claude Code Agent Teams: Exercises](https://github.com/panaversity/claude-code-agent-teams-exercises) by [Panaversity](https://github.com/panaversity) - Claude Code 代理团队的实践练习——6 个练习 + 2 个综合项目，涵盖团队创建、任务协调、质量钩子和并行代码审查——优秀的学习资源。
- [Harness](https://github.com/revfactory/harness) by [revfactory](https://github.com/revfactory) - 一个元技能，用于设计特定领域的代理团队、定义专业代理并生成它们使用的技能。资源是韩语的，但可以产生高质量的英语输出。

### Ralph Wiggum

- [awesome-ralph](https://github.com/snwfdhmp/awesome-ralph) by [Martin Joly](https://github.com/snwfdhmp) - 关于 Ralph 的精选资源列表，Ralph 是一种 AI 编码技术，在自动化循环中运行 AI 编码代理，直到满足规范。
- [Ralph for Claude Code](https://github.com/frankbria/ralph-claude-code) by [Frank Bria](https://github.com/frankbria) - 一个自主 AI 开发框架，使 Claude Code 能够在项目上迭代工作直到完成。具有智能退出检测、速率限制、断路器模式和全面的安全防护，以防止无限循环和 API 过度使用。使用 Bash 构建，与 tmux 集成以进行实时监控，并包含 75+ 个综合测试。
- [Ralph Wiggum Marketer](https://github.com/muratcankoylan/ralph-wiggum-marketer) by [Muratcan Koylan](https://github.com/muratcankoylan) - 一个 Claude Code 插件，提供自主 AI 文案撰稿人，将 Ralph 循环与定制知识库集成用于市场研究代理。代理进行研究，Ralph 撰写文案，您留在床上。无论您是否实践 Ralph 驱动开发（RDD），我认为这些项目是对一般代理模式的有趣和创造性探索。
- [ralph-orchestrator](https://github.com/mikeyobrien/ralph-orchestrator) by [mikeyobrien](https://github.com/mikeyobrien) - Ralph Orchestrator 实现了简单但有效的"Ralph Wiggum"技术用于自主任务完成，持续运行 AI 代理对提示文件，直到任务标记为完成或达到限制。此实现为 AI 驱动的开发提供了强大、经过良好测试且功能完整的编排系统。也在 Anthropic Ralph 插件文档中被引用。
- [ralph-wiggum-bdd](https://github.com/marcindulak/ralph-wiggum-bdd) by [marcindulak](https://github.com/marcindulak) - 一个独立的 Bash 脚本，用于使用 Ralph Wiggum 循环的行为驱动开发。原则上，在无人值守运行时，脚本可以保持代码和需求同步，但在实践中仍然需要交互式人工监督，因此它支持两种模式。脚本是独立的，可以修改并提交到您的项目中。
- [The Ralph Playbook](https://github.com/ClaytonFarr/ralph-playbook) by [Clayton Farr](https://github.com/ClaytonFarr) - 关于 Ralph Wiggum 技术的非常详细和全面的指南，具有编写良好的理论评论以及实用的指南和建议。

<br>

## 工具 🧰

> 工具是指在 Claude Code 之上构建的应用程序，包含比斜杠命令和 `CLAUDE.md` 文件更多的组件

### 通用

- [cc-sessions](https://github.com/GWUDCAP/cc-sessions) by [toastdev](https://github.com/satoastshi) - 一种使用 Claude Code 进行高效开发的主观化方法。
- [cc-tools](https://github.com/Veraticus/cc-tools) by [Josh Symonds](https://github.com/Veraticus) - Claude Code 钩子和实用程序的高性能 Go 实现。提供智能 linting、测试和状态栏生成，开销最小。
- [ccexp](https://github.com/nyatinte/ccexp) by [nyatinte](https://github.com/nyatinte) - 用于发现和管理 Claude Code 配置文件和斜杠命令的交互式 CLI 工具，具有漂亮的终端 UI。
- [cchistory](https://github.com/eckardt/cchistory) by [eckardt](https://github.com/eckardt) - 类似于 shell 历史命令，但用于您的 Claude Code 会话。轻松列出 Claude Code 在会话中运行的所有 Bash 或"Bash 模式"（`!`）命令以供参考。
- [cclogviewer](https://github.com/Brads3290/cclogviewer) by [Brad S.](https://github.com/Brads3290) - 一个谦虚但实用的实用程序，用于在漂亮的 HTML UI 中查看 Claude Code `.jsonl` 对话文件。
- [Claude Code Templates](https://github.com/davila7/claude-code-templates) by [Daniel Avila](https://github.com/davila7) - 来自此列表每个类别的令人难以置信的精彩资源集合，以精美打磨的 UI 呈现，具有使用仪表板、分析等出色功能，以及从斜杠命令到钩子再到代理的所有内容。这个精彩列表的精彩伴侣。
- [Claude Composer](https://github.com/possibilities/claude-composer) by [Mike Bannister](https://github.com/possibilities) - 一个为 Claude Code 添加小增强的工具。
- [Claude Hub](https://github.com/claude-did-this/claude-hub) by [Claude Did This](https://github.com/claude-did-this) - 一个将 Claude Code 连接到 GitHub 仓库的 webhook 服务，通过拉取请求和问题直接启用 AI 驱动的代码协助。此集成允许 Claude 分析仓库、回答技术问题，并通过简单的 @mentions 帮助开发人员理解和改进他们的代码库。
- [Claude Session Restore](https://github.com/ZENG3LD/claude-session-restore) by [ZENG3LD](https://github.com/ZENG3LD) - 通过分析会话文件和 git 历史高效地从先前的 Claude Code 会话恢复上下文。具有跨众多 Claude Code 功能的多因素数据收集和时间过滤功能。使用基于 tail 的解析来高效处理高达 2GB 的大型会话文件。包括用于手动分析的 CLI 工具和用于自动会话恢复的 Claude Code 技能。
- [claude-code-tools](https://github.com/pchalasani/claude-code-tools) by [Prasad Chalasani](https://github.com/pchalasani) - 用于会话连续性的精心制作的工具集，具有技能/命令以避免压缩并跨会话恢复上下文，在 Claude Code 和 Codex CLI 之间进行跨代理交接。包括快速 Rust/Tantivy 驱动的全文会话搜索（面向人类的 TUI，面向代理的技能/CLI）、用于与脚本和 CLI 代理交互的 tmux-cli 技能 + 命令，以及阻止危险命令的安全钩子。
- [claude-devtools](https://github.com/matt1398/claude-devtools) by [matt1398](https://github.com/matt1398) - 一个设计良好的桌面应用程序，通过分析会话日志提供对 Claude Code 会话的详细可观察性。提供跨众多类别的基于轮次的上下文数据、压缩可视化、子代理执行树和自定义通知触发器。易于安装，视觉设计良好。
- [claude-toolbox](https://github.com/serpro69/claude-toolbox) by [serpro69](https://github.com/serpro69) - 这是一个启动模板仓库，旨在为 Claude-Code 提供完整的开发环境，具有用于 AI 驱动开发工作流程的预配置 MCP 服务器和工具。仓库故意最小化，仅包含三个主要系统的配置模板：Claude Code、Serena 和 Task Master。
- [claudekit](https://github.com/carlrannaberg/claudekit) by [Carl Rannaberg](https://github.com/carlrannaberg) - 令人印象深刻的 CLI 工具包，提供自动保存检查点、代码质量钩子、规范生成和执行，以及 20 多个专业子代理，包括 oracle (gpt-5)、code-reviewer（6 方面深度分析）、ai-sdk-expert（Vercel AI SDK）、typescript-expert 以及更多用于 Claude Code 工作流程的代理。
- [Container Use](https://github.com/dagger/container-use) by [dagger](https://github.com/dagger) - 编码代理的开发环境。使多个代理能够使用您喜欢的堆栈安全且独立地工作。
- [ContextKit](https://github.com/FlineDev/ContextKit) by [Cihat Gündüz](https://github.com/Jeehut) - 一个系统化的开发框架，将 Claude Code 转变为主动开发伙伴。具有 4 阶段规划方法、专业质量代理和结构化工作流程，帮助 AI 在第一次尝试时生成生产就绪的代码。
- [recall](https://github.com/zippoxer/recall) by [zippoxer](https://github.com/zippoxer) - 全文搜索您的 Claude Code 会话。在终端中运行 `recall`，键入搜索，按 Enter 恢复。`claude --resume` 的替代方案。
- [Rulesync](https://github.com/dyoshikawa/rulesync) by [dyoshikawa](https://github.com/dyoshikawa) - 一个 Node.js CLI 工具，自动为各种 AI 编码代理生成配置（规则、忽略文件、MCP 服务器、命令和子代理）。Rulesync 可以在 Claude Code 和其他 AI 代理之间双向转换配置。
- [run-claude-docker](https://github.com/icanhasjonas/run-claude-docker) by [Jonas](https://github.com/icanhasjonas/) - 一个独立的 Docker 运行器，将您当前的工作区转发到安全的隔离 docker 容器，在那里您仍然可以访问您的 Claude Code 设置、身份验证、ssh 代理、pgp，可选地还有 aws 密钥等。
- [stt-mcp-server-linux](https://github.com/marcindulak/stt-mcp-server-linux) by [marcindulak](https://github.com/marcindulak) - 使用 Python MCP 服务器的 Linux 按键通话语音转录设置。在 Docker 中本地运行，无外部 API 调用。您的语音被录制、转录为文本，然后发送到在 Tmux 会话中运行的 Claude。
- [SuperClaude](https://github.com/SuperClaude-Org/SuperClaude_Framework) by [SuperClaude-Org](https://github.com/SuperClaude-Org) - 一个多功能配置框架，通过专业命令、认知角色和开发方法论（如"内省"和"编排"）增强 Claude Code。
- [tweakcc](https://github.com/Piebald-AI/tweakcc) by [Piebald-AI](https://github.com/Piebald-AI) - 用于自定义 Claude Code 样式的命令行工具。
- [Vibe-Log](https://github.com/vibe-log/vibe-log-cli) by [Vibe-Log](https://github.com/vibe-log) - 在本地分析您的 Claude Code 提示（使用 CC），提供智能会话分析和可操作的战略指导——在状态栏中工作，并生成非常漂亮的 HTML 报告。易于安装和删除。
- [viwo-cli](https://github.com/OverseedAI/viwo) by [Hal Shin](https://github.com/hal-shin) - 在 Docker 容器中运行 Claude Code，使用 git worktrees 作为卷挂载，以更安全地使用 `--dangerously-skip-permissions` 进行无摩擦的一次性提示。允许用户轻松在后台启动多个 Claude Code 实例，减少权限疲劳。
- [VoiceMode MCP](https://github.com/mbailey/voicemode) by [Mike Bailey](https://github.com/mbailey) - VoiceMode MCP 为 Claude Code 带来自然对话。它支持任何与 OpenAI API 兼容的语音服务，并安装免费和开源的语音服务（Whisper.cpp 和 Kokoro-FastAPI）。

### IDE 集成

- [Claude Code Chat](https://marketplace.visualstudio.com/items?itemName=AndrePimenta.claude-code-chat) by [andrepimenta](https://github.com/andrepimenta) - 一个优雅且用户友好的 VS Code Claude Code 聊天界面。
- [claude-code-ide.el](https://github.com/manzaltu/claude-code-ide.el) by [manzaltu](https://github.com/manzaltu) - claude-code-ide.el 将 Claude Code 与 Emacs 集成，就像 Anthropic 的 VS Code/IntelliJ 扩展一样。它显示基于 ediff 的代码建议，拉取 LSP/flymake/flycheck 诊断，并跟踪缓冲区上下文。它添加了可扩展的 MCP 工具支持，用于符号引用/定义、项目元数据和 tree-sitter AST 查询。
- [claude-code.el](https://github.com/stevemolitor/claude-code.el) by [stevemolitor](https://github.com/stevemolitor) - Claude Code CLI 的 Emacs 接口。
- [claude-code.nvim](https://github.com/greggh/claude-code.nvim) by [greggh](https://github.com/greggh) - Claude Code AI 助手与 Neovim 之间的无缝集成。
- [Claudix - Claude Code for VSCode](https://github.com/Haleclipse/Claudix) by [Haleclipse](https://github.com/Haleclipse) - 一个 VSCode 扩展，通过交互式聊天界面、会话管理、智能文件操作、终端执行和实时流式响应将 Claude Code 直接带入您的编辑器。使用 Vue 3、TypeScript 构建。
- [Clawd on Desk](https://github.com/rullerzhou-afk/clawd-on-desk) by [Ruller_Lulu](https://github.com/rullerzhou-afk) - 一个桌面宠物，实时响应您的 Claude Code 会话——思考、打字、杂耍、睡觉等等。是的，它确实很可爱。归根结底，这不就是 Claude Code 的全部意义所在吗？

### 使用监控

- [CC Usage](https://github.com/ryoppippi/ccusage) by [ryoppippi](https://github.com/ryoppippi) - 用于管理和分析 Claude Code 使用的便捷 CLI 工具，基于分析本地 Claude Code 日志。展示关于成本信息、令牌消耗等的不错仪表板。
- [ccflare](https://github.com/snipeship/ccflare) by [snipeship](https://github.com/snipeship) - Claude Code 使用仪表板，具有让 Tableau 黯然失色的 Web UI。非常全面的指标、无摩擦的设置、详细的日志记录、非常非常好的 UI。
- [ccflare -> **better-ccflare**](https://github.com/tombii/better-ccflare/) by [tombii](https://github.com/tombii) - @snipeship 的光荣 `ccflare` 使用仪表板的一个维护良好且功能增强的分支（截至撰写本文时，该仪表板已有几个月未更新）。`better-ccflare` 在此基础上构建，具有一些性能增强、扩展的提供商支持、错误修复、Docker 部署等。
- [ccxray](https://github.com/lis186/ccxray) by [lis186](https://github.com/lis186) - 一个透明的 HTTP 代理和实时仪表板，位于 Claude Code 和 Anthropic API 之间。无需配置即可捕获每个请求和响应，并以 Miller 列界面呈现，具有会话分组、令牌/成本跟踪和上下文窗口可视化功能。
- [Claude Code Usage Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) by [Maciek-roboblog](https://github.com/Maciek-roboblog) - 一个基于终端的实时工具，用于监控 Claude Code 令牌使用情况。它显示实时令牌消耗、消耗率和令牌耗尽预测。功能包括视觉进度条、会话感知分析和对多个订阅计划的支持。
- [Claudex](https://github.com/kunwar-shah/claudex) by [Kunwar Shah](https://github.com/kunwar-shah) - Claudex - 一个基于 Web 的浏览器，用于跨项目探索您的 Claude Code 对话历史。为代码库建立全文搜索索引。不错、易于导航的 UI。用于高级分析的简单仪表板界面，以及多种导出选项。（而且完全本地，没有遥测！）.
- [viberank](https://github.com/sculptdotfun/viberank) by [nikshepsvn](https://github.com/nikshepsvn) - 一个社区驱动的排行榜工具，使开发人员能够根据他们的 Claude Code 使用统计数据进行可视化、跟踪和竞争。它具有强大的数据分析、GitHub OAuth、数据验证和用户友好的 CLI/Web 提交方法。

### 编排器

- [Auto-Claude](https://github.com/AndyMik90/Auto-Claude) by [AndyMik90](https://github.com/AndyMik90) - Claude Code (Claude Agent SDK) 的自主多代理编码框架，集成了完整的 SDLC——"为您规划、构建和验证软件"。具有时尚的看板式 UI 和设计良好但不过度工程的代理编排系统。
- [Claude Code Flow](https://github.com/ruvnet/claude-code-flow) by [ruvnet](https://github.com/ruvnet) - 此模式作为代码优先的编排层，使 Claude 能够在递归代理周期中自主编写、编辑、测试和优化代码。
- [Claude Squad](https://github.com/smtg-ai/claude-squad) by [smtg-ai](https://github.com/smtg-ai) - Claude Squad 是一个终端应用程序，在单独的工作区中管理多个 Claude Code、Codex（以及其他本地代理，包括 Aider），允许您同时处理多个任务。
- [Claude Swarm](https://github.com/parruda/claude-swarm) by [parruda](https://github.com/parruda) - 启动连接到 Claude Code 代理群的 Claude Code 会话。
- [Claude Task Master](https://github.com/eyaltoledano/claude-task-master) by [eyaltoledano](https://github.com/eyaltoledano) - 一个用于使用 Claude 进行 AI 驱动开发的任务管理系统，旨在与 Cursor AI 无缝协作。
- [Claude Task Runner](https://github.com/grahama1970/claude-task-runner) by [grahama1970](https://github.com/grahama1970) - 一个专用工具，用于使用 Claude Code 管理上下文隔离和专注任务执行，解决了在使用 Claude 处理复杂的多步骤项目时上下文长度限制和任务专注的关键挑战。
- [Happy Coder](https://github.com/slopus/happy) by [GrocerPublishAgent](https://peoplesgrocers.com/en/projects) - 从您的手机或桌面并行生成和控制多个 Claude Code。Happy Coder 在您的硬件上运行 Claude Code，当 Claude 需要更多输入或权限时发送推送通知，并且不花费任何费用。
- [Ruflo](https://github.com/ruvnet/ruflo) by [rUv](https://github.com/ruvnet) - 一个用于部署和协调多代理群的编排平台。如果我试图详细说明，可能会使我的浏览器崩溃。这是一项令人印象深刻的工程壮举，试图涵盖所有内容并且实际上做得很好。自学习、自主的多代理群、基于向量的多层记忆、系统规划、安全防护等等。这是一个不断发展的项目，YMMV，但即使只是研究模式也具有巨大的价值，而且显然设计精良。
- [sudocode](https://github.com/sudocode-ai/sudocode) by [ssh-randy](https://github.com/ssh-randy) - 轻量级代理编排开发工具，驻留在您的仓库中。与各种规范框架集成。它就像 Jira。
- [The Agentic Startup](https://github.com/rsmdt/the-startup) by [Rudolf Schmidt](https://github.com/rsmdt) - 又一个 Claude 编排器——一组用于发布生产代码的代理、命令等——但我喜欢这个，因为它全面、编写精良，并且是少数实际使用输出样式的资源之一！+10 分！
- [TSK - AI Agent Task Manager and Sandbox](https://github.com/dtormoen/tsk) by [dtormoen](https://github.com/dtormoen) - 一个 Rust CLI 工具，让您可以将开发任务委托给在沙盒化 Docker 环境中运行的 AI 代理。多个代理并行工作，返回 git 分支供人工审查。

### 配置管理器

- [agnix](https://github.com/agent-sh/agnix) by [agent-sh](https://github.com/agent-sh) - Claude Code 代理文件的综合 linter。验证 CLAUDE.md、AGENTS.md、SKILL.md、钩子、MCP 等。包含所有主要 IDE 的插件，具有自动修复功能。
- [claude-rules-doctor](https://github.com/nulone/claude-rules-doctor) by [nulone](https://github.com/nulone) - 通过检查 `paths:` glob 是否实际匹配仓库中的文件来检测死 `.claude/rules/` 文件的 CLI。捕获由于重命名的目录或 glob 模式中的拼写错误导致规则永不应用的静默规则失败。具有 CI 模式（死规则时退出 1）、JSON 输出和显示匹配文件的详细模式。
- [ClaudeCTX](https://github.com/foxj77/claudectx) by [John Fox](https://github.com/foxj77) - claudectx 让您可以使用单个命令切换整个 Claude Code 配置。

<br>

## 状态栏 📊

> 状态栏 - Claude Code 状态栏功能的配置和自定义

### 通用

- [CCometixLine - Claude Code Statusline](https://github.com/Haleclipse/CCometixLine) by [Haleclipse](https://github.com/Haleclipse) - 用 Rust 编写的高性能 Claude Code 状态栏工具，具有 Git 集成、使用跟踪、交互式 TUI 配置和 Claude Code 增强实用程序。
- [ccstatusline](https://github.com/sirmalloc/ccstatusline) by [sirmalloc](https://github.com/sirmalloc) - 一个高度可定制的 Claude Code CLI 状态行格式化程序，在终端中显示模型信息、git 分支、令牌使用情况和其他指标。
- [claude-code-statusline](https://github.com/rz1989s/claude-code-statusline) by [rz1989s](https://github.com/rz1989s) - Claude Code 的增强型 4 行状态栏，具有主题、成本跟踪和 MCP 服务器监控功能。
- [claude-pace](https://github.com/Astro-Han/claude-pace) by [Astro-Han](https://github.com/Astro-Han) - Claude Code 的轻量级 Bash + jq 状态栏，显示速率限制节奏增量（消耗率与剩余时间）、5h/7d 使用百分比、上下文窗口使用情况、git 分支和差异统计。比较当前消耗率与每个速率限制窗口的剩余时间，以指示配额是否比窗口允许的更快或更慢使用。单个文件，除 jq 外无外部依赖。
- [claude-powerline](https://github.com/Owloops/claude-powerline) by [Owloops](https://github.com/Owloops) - Claude Code 的 vim 风格 powerline 状态栏，具有实时使用跟踪、git 集成、自定义主题等。
- [claudia-statusline](https://github.com/hagan/claudia-statusline) by [Hagan Franks](https://github.com/hagan) - Claude Code 的高性能基于 Rust 的状态栏，具有持久统计跟踪、进度条和可选的云同步。具有 SQLite 优先的持久性、git 集成、上下文进度条、消耗率计算、XDG 兼容的主题支持（深色/浅色、NO_COLOR）。

<br>

## 钩子 🪝

> 钩子是 Claude Code 的强大 API，允许用户在 Claude 代理生命周期的不同点激活命令和运行脚本。

### 通用

- [Britfix](https://github.com/Talieisin/britfix) by [Talieisin](https://github.com/Talieisin) - Claude 默认输出美式拼写，这可能会影响：专业可信度、合规性、文档等。Britfix 转换为英式英语，具有 Claude Code 钩子，可在写入文件时自动转换。上下文感知：智能处理代码文件，仅转换注释和文档字符串，从不转换标识符或字符串字面量。
- [CC Notify](https://github.com/dazuiba/CCNotify) by [dazuiba](https://github.com/dazuiba) - CCNotify 为 Claude Code 提供桌面通知，提醒您需要输入或任务完成，具有一键跳回 VS Code 和任务持续时间显示功能。
- [cchooks](https://github.com/GowayLee/cchooks) by [GowayLee](https://github.com/GowayLee) - 一个轻量级 Python SDK，具有清晰的 API 和良好的文档；简化了编写钩子并将其集成到代码库的过程，为 JSON 配置文件提供了良好的抽象。
- [Claude Code Hook Comms (HCOM)](https://github.com/aannoo/claude-hook-comms) by [aannoo](https://github.com/aannoo) - 使用钩子在 Claude Code 子代理之间进行实时通信的轻量级 CLI 工具。通过 @-mention 定位、实时仪表板监控和零依赖实现启用多代理协作。[注意：发布时，此资源有点不稳定——我还是分享它，因为我认为它非常有前景和创意。希望您读到本文时，它已准备就绪。]。
- [claude-code-hooks-sdk](https://github.com/beyondcode/claude-hooks-sdk) by [beyondcode](https://github.com/beyondcode) - 一个受 Laravel 启发的 PHP SDK，用于使用清晰、流畅的 API 构建 Claude Code 钩子响应。此 SDK 使用富有表现力、可链接的界面轻松为 Claude Code 钩子创建结构化的 JSON 响应。
- [claude-hooks](https://github.com/johnlindquist/claude-hooks) by [John Lindquist](https://github.com/johnlindquist) - 一个基于 TypeScript 的系统，用于使用强大而灵活的界面配置和自定义 Claude Code 钩子。
- [Claudio](https://github.com/ctoth/claudio) by [Christopher Toth](https://github.com/ctoth) - 一个朴实无华的小型库，通过简单的钩子为 Claude Code 添加令人愉悦的操作系统原生声音。它确实能带来快乐。
- [Dippy](https://github.com/ldayton/Dippy) by [Lily Dayton](https://github.com/ldayton) - 使用基于 AST 的解析自动批准安全的 bash 命令，同时提示进行破坏性操作。在不禁用安全性的情况下解决权限疲劳。支持 Claude Code、Gemini CLI 和 Cursor。
- [parry](https://github.com/vaporif/parry) by [Dmytro Onypko](https://github.com/vaporif) - Claude Code 钩子的提示注入扫描程序。扫描工具输入和输出以查找注入攻击、机密和数据外泄尝试。[注意：早期开发阶段，但值得一看。]。
- [TDD Guard](https://github.com/nizos/tdd-guard) by [Nizar Selander](https://github.com/nizos) - 一个由钩子驱动的系统，实时监控文件操作并阻止违反 TDD 原则的更改。
- [TypeScript Quality Hooks](https://github.com/bartolli/claude-code-typescript-hooks) by [bartolli](https://github.com/bartolli) - Node.js TypeScript 项目的质量检查钩子，具有 TypeScript 编译、ESLint 自动修复和 Prettier 格式化功能。使用 SHA256 配置缓存，在实时编辑期间实现 < 5ms 的验证性能。

<br>

## 斜杠命令 🔪

> "斜杠命令是定制化的、经过精心优化的提示，用于控制 Claude 的行为以执行特定任务"

### 通用

- [/create-hook](https://github.com/omril321/automated-notebooklm/blob/main/.claude/commands/create-hook.md) by [Omri Lavi](https://github.com/omril321) - 用于创建钩子的斜杠命令——根据您的项目设置（TS、Prettier、ESLint...）通过智能建议智能地引导您完成创建过程。
- [/linux-desktop-slash-commands](https://github.com/danielrosehill/Claude-Code-Linux-Desktop-Slash-Commands) by [Daniel Rosehill](https://github.com/danielrosehill) - 专门用于促进 Linux 桌面环境上的常见和高级操作的斜杠命令库（尽管许多在 Linux 服务器上也很有用）。命令组包括硬件基准测试、文件系统组织和安全姿态验证。

### 版本控制与 Git

- [/analyze-issue](https://github.com/jerseycheese/Narraitor/blob/feature/issue-227-ai-suggestions/.claude/commands/analyze-issue.md) by [jerseycheese](https://github.com/jerseycheese) - 获取 GitHub 问题详细信息以创建全面的实现规范，分析需求并规划结构化方法，具有清晰的实现步骤。
- [/commit](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/commit.md) by [evmts](https://github.com/evmts) - 使用适当的表情符号按照常规提交格式创建 git 提交，遵循项目标准并创建描述性消息以解释更改的目的。
- [/commit-fast](https://github.com/steadycursor/steadystart/blob/main/.claude/commands/2-commit-fast.md) by [steadycursor](https://github.com/steadycursor) - 通过选择第一个建议的消息自动执行 git 提交过程，生成具有一致格式的结构化提交，同时跳过手动确认并删除 Claude 共同贡献者页脚。
- [/create-pr](https://github.com/toyamarinyon/giselle/blob/main/.claude/commands/create-pr.md) by [toyamarinyon](https://github.com/toyamarinyon) - 通过处理整个工作流程简化拉取请求创建：创建新分支、提交更改、使用 Biome 格式化修改的文件并提交 PR。
- [/create-pull-request](https://github.com/liam-hq/liam/blob/main/.claude/commands/create-pull-request.md) by [liam-hq](https://github.com/liam-hq) - 使用 GitHub CLI 提供全面的 PR 创建指导，强制执行标题约定，遵循模板结构，并提供具有最佳实践的具体命令示例。
- [/create-worktrees](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/create-worktrees.md) by [evmts](https://github.com/evmts) - 为所有打开的 PR 或特定分支创建 git worktrees，处理带斜杠的分支，清理过时的 worktrees，并支持自定义分支创建以进行开发。
- [/fix-github-issue](https://github.com/jeremymailen/kotlinter-gradle/blob/master/.claude/commands/fix-github-issue.md) by [jeremymailen](https://github.com/jeremymailen) - 使用结构化方法和 GitHub CLI 获取问题详细信息来分析和修复 GitHub 问题，实施必要的代码更改，运行测试并创建适当的提交消息。
- [/fix-issue](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-issue.md) by [metabase](https://github.com/metabase) - 通过将问题编号作为参数、分析上下文、实施解决方案并测试/验证修复以进行正确集成来解决 GitHub 问题。
- [/fix-pr](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-pr.md) by [metabase](https://github.com/metabase) - 通过自动检索反馈、解决审查者的关切、进行有针对性的代码改进并简化审查过程来获取和修复未解决的 PR 评论。
- [/husky](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/husky.md) by [evmts](https://github.com/evmts) - 通过配置预提交钩子、建立提交消息标准、与 linting 工具集成并确保提交时的代码质量来设置和管理 Husky Git 钩子。
- [/update-branch-name](https://github.com/giselles-ai/giselle/blob/main/.claude/commands/update-branch-name.md) by [giselles-ai](https://github.com/giselles-ai) - 使用适当的前缀和格式更新分支名称，强制执行命名约定，支持语义前缀并管理远程分支更新。

### 代码分析与测试

- [/check](https://github.com/rygwdn/slack-tools/blob/main/.claude/commands/check.md) by [rygwdn](https://github.com/rygwdn) - 执行全面的代码质量和安全检查，具有静态分析集成、安全漏洞扫描、代码样式强制执行和详细报告功能。
- [/code_analysis](https://github.com/kingler/n8n_agent/blob/main/.claude/commands/code_analysis.md) by [kingler](https://github.com/kingler) - 提供高级代码分析命令菜单以进行深度检查，包括知识图生成、优化建议和质量评估。
- [/optimize](https://github.com/to4iki/ai-project-rules/blob/main/.claude/commands/optimize.md) by [to4iki](https://github.com/to4iki) - 分析代码性能以识别瓶颈，提出具体的优化建议并提供实施指导以改进应用程序性能。
- [/repro-issue](https://github.com/rzykov/metabase/blob/master/.claude/commands/repro-issue.md) by [rzykov](https://github.com/rzykov) - 为 GitHub 问题创建可重现的测试用例，确保测试可靠失败并为开发人员记录清晰的重现步骤。
- [/tdd](https://github.com/zscott/pane/blob/main/.claude/commands/tdd.md) by [zscott](https://github.com/zscott) - 使用测试驱动开发原则指导开发，强制执行 Red-Green-Refactor 纪律，与 git 工作流程集成并管理 PR 创建。
- [/tdd-implement](https://github.com/jerseycheese/Narraitor/blob/feature/issue-227-ai-suggestions/.claude/commands/tdd-implement.md) by [jerseycheese](https://github.com/jerseycheese) - 通过分析功能需求、首先创建测试（红色）、实现最小通过代码（绿色）并在维护测试的同时进行重构来实现测试驱动开发。

### 上下文加载与预热

- [/context-prime](https://github.com/elizaOS/elizaos.github.io/blob/main/.claude/commands/context-prime.md) by [elizaOS](https://github.com/elizaOS) - 通过加载仓库结构、设置开发上下文、建立项目目标和定义协作参数，用全面的项目理解预热 Claude。
- [/initref](https://github.com/okuvshynov/cubestat/blob/main/.claude/commands/initref.md) by [okuvshynov](https://github.com/okuvshynov) - 使用标准文档模板、API 参考设置、文档约定和占位符内容生成初始化参考文档结构。
- [/load-llms-txt](https://github.com/ethpandaops/xatu-data/blob/master/.claude/commands/load-llms-txt.md) by [ethpandaops](https://github.com/ethpandaops) - 将 LLM 配置文件加载到上下文中，导入特定术语、模型配置并为 AI 讨论建立基准术语。
- [/load_coo_context](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_coo_context.md) by [Mjvolk3](https://github.com/Mjvolk3) - 引用稀疏矩阵操作的特定文件，解释转换用法，与先前方法进行比较，并为开发设置数据格式上下文。
- [/load_dango_pipeline](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_dango_pipeline.md) by [Mjvolk3](https://github.com/Mjvolk3) - 通过引用管道文件、建立工作上下文并使用相关文档准备管道工作来为模型训练设置上下文。
- [/prime](https://github.com/yzyydev/AI-Engineering-Structure/blob/main/.claude/commands/prime.md) by [yzyydev](https://github.com/yzyydev) - 通过查看目录结构和读取关键文件来设置初始项目上下文，创建具有目录可视化和关键文档焦点的标准化上下文。
- [/rsi](https://github.com/ddisisto/si/blob/main/.claude/commands/rsi.md) by [ddisisto](https://github.com/ddisisto) - 读取所有命令和关键项目文件以优化 AI 辅助开发，通过简化流程、加载命令上下文并为更好的开发工作流程进行设置。

### 文档与变更日志

- [/add-to-changelog](https://github.com/berrydev-ai/blockdoc-python/blob/main/.claude/commands/add-to-changelog.md) by [berrydev-ai](https://github.com/berrydev-ai) - 向变更日志文件添加新条目，同时保持格式一致性、正确记录更改并遵循既定的项目标准以进行版本跟踪。
- [/create-docs](https://github.com/jerseycheese/Narraitor/blob/feature/issue-227-ai-suggestions/.claude/commands/create-docs.md) by [jerseycheese](https://github.com/jerseycheese) - 分析代码结构和目的以创建全面的文档，详细说明输入/输出、行为、用户交互流程以及带有错误处理的边缘情况。
- [/docs](https://github.com/slunsford/coffee-analytics/blob/main/.claude/commands/docs.md) by [slunsford](https://github.com/slunsford) - 生成遵循项目结构的全面文档，使用一致的格式记录 API 和使用模式以更好地帮助用户理解。
- [/explain-issue-fix](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/explain-issue-fix.md) by [hackdays-io](https://github.com/hackdays-io) - 记录 GitHub 问题的解决方案方法，解释技术决策，详细说明克服的挑战，并提供实施上下文以更好地理解。
- [/update-docs](https://github.com/Consiliency/Flutter-Structurizr/blob/main/.claude/commands/update-docs.md) by [Consiliency](https://github.com/Consiliency) - 审查当前文档状态，更新实施进度，审查阶段文档，并在整个项目中保持文档一致性。

### CI / 部署

- [/release](https://github.com/kelp/webdown/blob/main/.claude/commands/release.md) by [kelp](https://github.com/kelp) - 通过更新变更日志、审查 README 更改、评估版本增量并记录发布更改以进行更好的版本跟踪来管理软件发布。
- [/run-ci](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/run-ci.md) by [hackdays-io](https://github.com/hackdays-io) - 激活虚拟环境，运行 CI 兼容的检查脚本，迭代修复错误，并确保在完成前所有测试通过。

### 项目与任务管理

- [/create-command](https://github.com/scopecraft/command/blob/main/.claude/commands/create-command.md) by [scopecraft](https://github.com/scopecraft) - 通过分析需求、按类别模板化命令、强制执行命令标准并创建支持文档，引导 Claude 创建具有适当结构的新自定义命令。
- [/create-plan](https://github.com/hesreallyhim/inkverse-fork/blob/preserve-claude-resources/.claude/commands/create-plan.md) by [taddyorg](https://github.com/taddyorg) - 生成全面的产品需求文档，概述遵循标准化文档结构和格式的详细规范、需求和功能。*（已从原处删除）*
- [/create-prp](https://github.com/Wirasm/claudecode-utils/blob/main/.claude/commands/create-prp.md) by [Wirasm](https://github.com/Wirasm) - 通过阅读 PRP 方法论、遵循模板结构、创建全面需求并为开发构建产品定义来创建产品需求计划。
- [/do-issue](https://github.com/jerseycheese/Narraitor/blob/feature/issue-227-ai-suggestions/.claude/commands/do-issue.md) by [jerseycheese](https://github.com/jerseycheese) - 使用手动审查点实现 GitHub 问题，遵循具有问题编号参数的结构化方法，并提供替代的自动化模式以提高效率。
- [/prd-generator](https://github.com/dredozubov/prd-generator) by [Denis Redozubov](https://github.com/dredozubov) - 一个 Claude Code 插件，从对话上下文生成全面的产品需求文档（PRD）。在讨论需求后调用 `/create-prd`，它将生成包含所有标准部分的完整 PRD，包括执行摘要、用户故事、MVP 范围、架构、成功标准和实施阶段。
- [/project_hello_w_name](https://github.com/disler/just-prompt/blob/main/.claude/commands/project_hello_w_name.md) by [disler](https://github.com/disler) - 创建带有名称输入的可自定义问候组件，演示参数传递、组件可重用性、状态管理和用户输入处理。
- [/todo](https://github.com/chrisleyva/todo-slash-command/blob/main/todo.md) by [chrisleyva](https://github.com/chrisleyva) - 一个便捷的命令，可快速管理项目待办事项而无需离开 Claude Code 界面，具有截止日期、排序、任务优先级和全面的待办事项列表管理功能。

### 其他

- [/fixing_go_in_graph](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/fixing_go_in_graph.md) by [Mjvolk3](https://github.com/Mjvolk3) - 专注于图数据库中的基因本体注释集成，处理多个数据源，解决图表示问题并确保正确的数据合并。
- [/review_dcell_model](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/review_dcell_model.md) by [Mjvolk3](https://github.com/Mjvolk3) - 审查旧的 Dcell 实现文件，与较新的 Dango 模型进行比较，注意随时间的变化，并分析重构方法以实现更好的代码组织。
- [/use-stepper](https://github.com/zuplo/docs/blob/main/.claude/commands/use-stepper.md) by [zuplo](https://github.com/zuplo) - 重新格式化文档以使用 React Stepper 组件，转换标题格式，应用适当的缩进，并保持与 admonition 格式的 markdown 兼容性。

<br>

## CLAUDE.md 文件 📂

> `CLAUDE.md` 文件是包含重要指南和上下文特定信息或说明的文件，帮助 Claude Code 更好地理解您的项目和编码标准

### 语言特定

- [AI IntelliJ Plugin](https://github.com/didalgolab/ai-intellij-plugin/blob/main/CLAUDE.md) by [didalgolab](https://github.com/didalgolab) - 为 IntelliJ 插件开发提供全面的 Gradle 命令，具有特定于平台的编码模式、详细的包结构指南和清晰的国际化标准。
- [AWS MCP Server](https://github.com/alexei-led/aws-mcp-server/blob/main/CLAUDE.md) by [alexei-led](https://github.com/alexei-led) - 具有多种 Python 环境设置选项、详细的代码风格指南、全面的错误处理建议以及 AWS CLI 交互的安全注意事项。
- [DroidconKotlin](https://github.com/touchlab/DroidconKotlin/blob/main/CLAUDE.md) by [touchlab](https://github.com/touchlab) - 为跨平台 Kotlin Multiplatform 开发提供全面的 Gradle 命令，具有清晰的模块结构和依赖注入的实用指导。
- [EDSL](https://github.com/hesreallyhim/awesome-claude-code/blob/main/resources/claude.md-files/EDSL/CLAUDE.md) by [expectedparrot](https://github.com/expectedparrot) - 提供详细的构建和测试命令，具有严格的代码样式强制执行、全面的测试要求以及使用 Black 和 mypy 的标准化开发工作流程。*（已从原处删除）*
- [Giselle](https://github.com/giselles-ai/giselle/blob/main/CLAUDE.md) by [giselles-ai](https://github.com/giselles-ai) - 使用 pnpm 和 Vitest 提供详细的构建和测试命令，具有严格的代码格式化要求和全面的命名约定以确保代码一致性。
- [HASH](https://github.com/hashintel/hash/blob/main/CLAUDE.md) by [hashintel](https://github.com/hashintel) - 具有全面的仓库结构分解，强烈强调编码标准、详细的 Rust 文档指南和系统的 PR 审查流程。
- [Inkline](https://github.com/inkline/inkline/blob/main/CLAUDE.md) by [inkline](https://github.com/inkline) - 使用 pnpm 构建开发工作流程，强调 TypeScript 和 Vue 3 Composition API、详细的组件创建过程和全面的测试建议。
- [JSBeeb](https://github.com/mattgodbolt/jsbeeb/blob/main/CLAUDE.md) by [mattgodbolt](https://github.com/mattgodbolt) - 为 JavaScript BBC Micro 模拟器提供开发指南，具有构建和测试说明、架构文档和调试工作流程。
- [Lamoom Python](https://github.com/LamoomAI/lamoom-python/blob/main/CLAUDE.md) by [LamoomAI](https://github.com/LamoomAI) - 作为生产提示工程库的参考，具有 AI 模型的负载均衡、API 文档和使用模式及示例。
- [LangGraphJS](https://github.com/langchain-ai/langgraphjs/blob/main/CLAUDE.md) by [langchain-ai](https://github.com/langchain-ai) - 提供全面的构建和测试命令，具有详细的 TypeScript 风格指南、分层库架构和使用 yarn workspaces 的 monorepo 结构。
- [Metabase](https://github.com/metabase/metabase/blob/master/CLAUDE.md) by [metabase](https://github.com/metabase) - 详细说明 Clojure/ClojureScript 中 REPL 驱动的开发工作流程，强调增量开发、测试和功能实现的分步方法。
- [SG Cars Trends Backend](https://github.com/sgcarstrends/backend/blob/main/CLAUDE.md) by [sgcarstrends](https://github.com/sgcarstrends) - 为 TypeScript monorepo 项目提供全面结构，具有开发、测试、部署和 AWS/Cloudflare 集成的详细命令。
- [SPy](https://github.com/spylang/spy/blob/main/CLAUDE.md) by [spylang](https://github.com/spylang) - 强制执行严格的编码约定，具有全面的测试指南、多种代码编译选项和用于目标过滤的后端特定测试装饰器。
- [TPL](https://github.com/KarpelesLab/tpl/blob/master/CLAUDE.md) by [KarpelesLab](https://github.com/KarpelesLab) - 详细说明 Go 项目约定，具有全面的错误处理建议、表驱动测试方法指南和最新 Go 功能的现代化建议。

### 领域特定

- [AVS Vibe Developer Guide](https://github.com/Layr-Labs/avs-vibe-developer-guide/blob/master/CLAUDE.md) by [Layr-Labs](https://github.com/Layr-Labs) - 构建辅助 AI 的 EigenLayer AVS 开发工作流程，具有提示文件的一致命名约定和区块链概念的既定术语标准。
- [Comm](https://github.com/CommE2E/comm/blob/master/AGENTS.md) by [CommE2E](https://github.com/CommE2E) - 作为 E2E 加密消息应用程序的开发参考，具有代码组织架构、安全实施细节和测试程序。
- [Cursor Tools](https://github.com/eastlondoner/cursor-tools/blob/main/CLAUDE.md) by [eastlondoner](https://github.com/eastlondoner) - 创建多功能 AI 命令界面，支持多个提供商和模型，具有灵活的命令选项和通过"Stagehand"功能的浏览器自动化。
- [Guitar](https://github.com/soramimi/Guitar/blob/master/CLAUDE.md) by [soramimi](https://github.com/soramimi) - 作为 Guitar Git GUI 客户端的开发指南，具有各种平台的构建命令、贡献的代码风格指南和项目结构说明。
- [Network Chronicles](https://github.com/Fimeg/NetworkChronicles/blob/legacy-v1/CLAUDE.md) by [Fimeg](https://github.com/Fimeg) - 呈现 AI 驱动游戏角色的详细实施计划，具有 LLM 集成的技术规范、角色指南和服务发现机制。
- [Pareto Mac](https://github.com/ParetoSecurity/pareto-mac/blob/main/CLAUDE.md) by [ParetoSecurity](https://github.com/ParetoSecurity) - 作为 Mac 安全审计工具的开发指南，具有构建说明、贡献指南、测试程序和工作流程文档。
- [pre-commit-hooks](https://github.com/aRustyDev/pre-commit-hooks) by [aRustyDev](https://github.com/aRustyDev) - 这个仓库通常是关于 pre-commit-hooks 的，但 `CLAUDE.md` 和相关的 `.claude/` 文档是典范的。全面但不冗长。与许多 `CLAUDE.md` 文件不同，它主要不是用全大写对 Claude 喊叫。优秀的学习资源。还有，钩子。
- [SteadyStart](https://github.com/steadycursor/steadystart/blob/main/CLAUDE.md) by [steadycursor](https://github.com/steadycursor) - 关于样式、权限、Claude 的"角色"、通信和 Claude Code 会话文档的清晰直接的指令，供其他团队成员了解最新情况。

### 项目脚手架与 MCP

- [Basic Memory](https://github.com/basicmachines-co/basic-memory/blob/main/CLAUDE.md) by [basicmachines-co](https://github.com/basicmachines-co) - 呈现创新的 AI 人类协作框架，具有模型上下文协议，用于双向 LLM-markdown 通信和复杂项目的灵活知识结构。
- [claude-code-mcp-enhanced](https://github.com/grahama1970/claude-code-mcp-enhanced/blob/main/CLAUDE.md) by [grahama1970](https://github.com/grahama1970) - 为 Claude 作为编码代理提供详细且强调的指令，具有测试指导、代码示例和合规性检查。

<br>

## 替代客户端 📱

> 替代客户端是用于与 Claude Code 交互的替代 UI 和前端，可以在移动设备或桌面上使用。

### 通用

- [Claudable](https://github.com/opactorai/Claudable) by [Ethan Park](https://www.linkedin.com/in/seongil-park/) - Claudable 是一个开源 Web 构建器，利用本地 CLI 代理（如 Claude Code 和 Cursor Agent）轻松构建和部署产品。
- [claude-esp](https://github.com/phiat/claude-esp) by [phiat](https://github.com/phiat) - 基于 Go 的 TUI，将 Claude Code 的隐藏输出（思考、工具调用、子代理）流式传输到单独的终端。同时观看多个会话，按内容类型过滤，并跟踪后台任务。非常适合调试或理解 Claude 在后台做什么，而不会中断您的主会话。
- [claude-tmux](https://github.com/nielsgroen/claude-tmux) by [Niels Groeneveld](https://github.com/nielsgroen) - 在 tmux 中管理 Claude Code。所有 Claude Code 实例的 tmux 弹出窗口，实现快速切换、状态监控、会话生命周期管理，具有 git worktree 和拉取请求支持。
- [crystal](https://github.com/stravu/crystal) by [stravu](https://github.com/stravu) - 一个功能齐全的桌面应用程序，用于编排、监控和与 Claude Code 代理交互。
- [Omnara](https://github.com/omnara-ai/omnara) by [Ishaan Sehgal](https://github.com/ishaansehgal99) - AI 代理的指挥中心，在终端、Web 和移动设备之间同步 Claude Code 会话。允许远程监控、人在回路交互和团队协作。

<br>

## 官方文档 🏛️

> 链接到 Anthropic 关于 Claude Code 的优秀文档和资源

### 通用

- [Anthropic Documentation](https://docs.claude.com/en/home) by [Anthropic](https://github.com/anthropics) - Claude Code 的官方文档，包括安装说明、使用指南、API 参考、教程、示例，大量我不会单独列出的信息。像 Claude Code 一样，文档经常更新。
- [Anthropic Quickstarts](https://github.com/anthropics/claude-quickstarts) by [Anthropic](https://github.com/anthropics) - 为三个不同的 AI 驱动演示项目提供全面的开发指南，具有标准化工作流程、严格的代码样式指南和容器化说明。
- [Claude Code GitHub Actions](https://github.com/anthropics/claude-code-action/tree/main/examples) by [Anthropic](https://github.com/anthropics) - Claude Code 的官方 GitHub Actions 集成，具有示例和文档，用于在 CI/CD 管道中自动化 AI 驱动的工作流程。


## 贡献 [🔝](#awesome-claude-code)

### **[在这里推荐新资源！](https://github.com/hesreallyhim/awesome-claude-code/issues/new?template=recommend-resource.yml)**

为列表推荐资源非常简单，自动化系统会为您处理所有事情。请不要打开 PR 来提交推荐 - 唯一允许向此仓库提交 PR 的人是 Claude。

在提交推荐之前，请确保您已阅读 CONTRIBUTING.md 文档和 CODE_OF_CONDUCT.md。

对于仓库本身的建议，请[打开仓库增强问题](https://github.com/hesreallyhim/awesome-claude-code/issues/new?template=repository-enhancement.yml)。

本项目发布了行为准则。通过参与，您同意遵守其条款。虽然我采取强有力的措施来维护此列表的质量和安全，但对于这些第三方资源可能导致的任何后果，我不承担任何责任或法律责任。

## 感谢您的支持而成长
[![Stargazers over time](https://starchart.cc/hesreallyhim/awesome-claude-code.svg?variant=adaptive)](https://starchart.cc/hesreallyhim/awesome-claude-code)

## 许可证

本列表采用 [Creative Commons CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) 许可 - 这意味着欢迎您分叉、克隆、复制和重新分发此列表，前提是您包含适当的归属；但是，您不得分发任何修改版本或将其用于任何商业目的。这是为了防止忽视此处列出的资源作者的许可证。请注意，此列表中包含的所有资源都有自己的许可证条款。


<!-- OBLIGATORY GUARD AGAINST SILLY END-OF-FILE PROBLEM -->
