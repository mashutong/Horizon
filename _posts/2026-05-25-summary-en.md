---
layout: default
title: "Horizon Summary: 2026-05-25 (EN)"
date: 2026-05-25
lang: en
---

> From 27 items, 7 important content pieces were selected

---

1. [Memory Now Accounts for Nearly Two-Thirds of AI Chip Costs](#item-1) ⭐️ 8.0/10
2. [Armin Ronacher Slams AI-Generated Bug Reports](#item-2) ⭐️ 8.0/10
3. [Understand-Anything Turns Code into Interactive Knowledge Graphs](#item-3) ⭐️ 8.0/10
4. [Anthropic Releases Official Claude Code Plugins Repository](#item-4) ⭐️ 8.0/10
5. [GitHub repo maps 754 cybersecurity skills for AI agents](#item-5) ⭐️ 8.0/10
6. [CloakBrowser: Stealth Chromium Fork Evades Bot Detection](#item-6) ⭐️ 7.0/10
7. [Jane Street's magic-trace Gains 76 Stars in 24 Hours](#item-7) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Memory Now Accounts for Nearly Two-Thirds of AI Chip Costs](https://epoch.ai/data-insights/ai-chip-component-cost-shares) ⭐️ 8.0/10

According to Epoch AI, memory's share of AI chip component costs has risen to nearly two-thirds, driven by supply constraints and surging demand for HBM and DRAM. Total component spending on AI chips grew from $22 billion in 2024 to $52 billion in 2025. This cost shift has major implications for AI hardware pricing and availability, potentially slowing AI adoption and increasing costs for data centers and end users. It also highlights the growing importance of memory supply chains in the AI ecosystem. HBM memory alone accounts for roughly 30–45% of total AI accelerator costs, with each stack costing $200–$500 and 6–8 stacks per accelerator. The global memory shortage, sometimes called 'RAMmageddon,' began in 2024 and is expected to persist into 2027.

hackernews · intelkishan · May 24, 16:31 · [Discussion](https://news.ycombinator.com/item?id=48258684)

**Background**: AI chips like NVIDIA's H100 and H200 rely heavily on high-bandwidth memory (HBM) to handle large models. Memory prices have surged as AI demand outpaces supply, while consumer DRAM prices have also risen sharply, affecting PCs and smartphones.

<details><summary>References</summary>
<ul>
<li><a href="https://epoch.ai/data-insights/ai-chip-component-cost-shares">AI Chip Component Costs: Memory at 63% | Epoch AI | Epoch AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/2024–present_global_memory_supply_shortage">2024–present global memory supply shortage - Wikipedia</a></li>
<li><a href="https://www.cnbc.com/2025/11/17/ai-fuels-memory-chip-shortage-that-could-hit-phones-and-cars.html">AI fuels memory chip shortage that could hit phones and cars</a></li>

</ul>
</details>

**Discussion**: Commenters note that AI inference/training costs could drop ~3x once DRAM supply catches up, but current price hikes frustrate gamers and PC enthusiasts. Some users report RAM prices doubling or tripling, and many are delaying upgrades until prices normalize.

**Tags**: `#AI hardware`, `#memory`, `#cost analysis`, `#semiconductors`, `#market trends`

---

<a id="item-2"></a>
## [Armin Ronacher Slams AI-Generated Bug Reports](https://simonwillison.net/2026/May/24/armin-ronacher/#atom-everything) ⭐️ 8.0/10

Armin Ronacher, creator of Flask and Jinja, published a blog post criticizing AI-generated bug reports as verbose, inaccurate, and frustrating for open-source maintainers, advocating for concise human-observed reports. This critique highlights a growing problem in open-source maintenance where AI tools produce low-quality bug reports, wasting maintainers' time and potentially harming project health. It sparks debate on the proper role of AI in software development workflows. Ronacher specifically calls out reports that are not in the user's own voice, contain fake-minimal repros, and suggest incorrect root causes. He proposes a simple four-point format: command run, expected behavior, actual behavior, and exact error/log.

rss · Simon Willison · May 24, 18:46

**Background**: AI-powered coding assistants and chatbots are increasingly used to generate bug reports, but they often produce verbose, confident-sounding but inaccurate analyses. Open-source maintainers like Ronacher face a flood of such 'slop' issues, reducing productivity and increasing burnout.

**Tags**: `#open-source`, `#AI`, `#bug reports`, `#software maintenance`, `#developer experience`

---

<a id="item-3"></a>
## [Understand-Anything Turns Code into Interactive Knowledge Graphs](https://github.com/Lum1104/Understand-Anything) ⭐️ 8.0/10

Lum1104/Understand-Anything is a new open-source tool that converts any codebase into an interactive knowledge graph, allowing developers to explore, search, and ask questions about the code structure. It gained over 650 stars on GitHub in its first 24 hours. This tool addresses the common challenge of understanding large, unfamiliar codebases by providing a visual, queryable map of code dependencies and components. Its compatibility with major AI coding assistants like Claude Code, Codex, and Cursor makes it broadly applicable for developer onboarding and daily development. The tool uses a multi-agent pipeline to analyze projects and build a knowledge graph of every file, function, class, and dependency, then provides an interactive dashboard. It is written in TypeScript and works with Claude Code, Codex, Cursor, Copilot, Gemini CLI, and more.

ossinsight · Lum1104 · May 25, 00:43

**Background**: Knowledge graphs are structured representations of information that show entities and their relationships, making them useful for visualizing complex codebases. AI coding assistants like Claude Code and Cursor help developers write code but often lack deep understanding of existing code structure. Tools like Understand-Anything bridge this gap by providing a visual map that both humans and AI tools can query.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Lum1104/Understand-Anything">GitHub - Lum1104/Understand-Anything: Graphs that teach ...</a></li>
<li><a href="https://www.geeky-gadgets.com/claude-code-plugin-repo-maps/">How to Turn Code Repositories Into Interactive Knowledge ...</a></li>
<li><a href="https://marketplace.visualstudio.com/items?itemName=NicoLlorens.knowledge-graph-visualizer">Knowledge Graph Visualizer - Visual Studio Marketplace How to Turn Code Repositories Into Interactive Knowledge ... GitHub - Lum1104/Understand-Anything: Graphs that teach ... Knowledge Graphs for Codebases: A Complete Guide to Graphify Understand-Anything: Code to Interactive Knowledge Graphs Understand Anything: Turn Any Codebase Into an Interactive ... Graphify — Open-Source Knowledge Graph Skill for AI Coding ...</a></li>

</ul>
</details>

**Tags**: `#knowledge-graph`, `#code-visualization`, `#developer-tools`, `#TypeScript`, `#AI-assisted-coding`

---

<a id="item-4"></a>
## [Anthropic Releases Official Claude Code Plugins Repository](https://github.com/anthropics/claude-plugins-official) ⭐️ 8.0/10

Anthropic has launched an official GitHub repository, anthropics/claude-plugins-official, hosting high-quality plugins for Claude Code and Claude Cowork, which gained 250 stars in its first 24 hours. This official plugin marketplace lowers the barrier for developers and knowledge workers to extend Claude's capabilities, signaling Anthropic's commitment to building an ecosystem around its AI models. Plugins can be installed directly via Claude Code's plugin system using commands like /plugin install, and the repository is written in Python. A related repository, anthropics/knowledge-work-plugins, also gained 88 stars in the same period.

ossinsight · anthropics · May 25, 00:43

**Background**: Claude is a series of large language models developed by Anthropic, used in AI chatbots and software development. Claude Code is an AI-assisted coding tool, while Claude Cowork is an AI agent for non-technical tasks like file management and office automation.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/anthropics/claude-plugins-official">anthropics/claude-plugins-official - GitHub</a></li>
<li><a href="https://claude.com/plugins">Plugins for Claude Code and Cowork | Anthropic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Cowork">Claude Cowork</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Claude`, `#plugins`, `#Python`, `#developer-tools`

---

<a id="item-5"></a>
## [GitHub repo maps 754 cybersecurity skills for AI agents](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) ⭐️ 8.0/10

Mukul975 released a GitHub repository that maps 754 structured cybersecurity skills to five major frameworks (MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND, and NIST AI RMF) for use with AI agents across 20+ platforms, including Claude Code and GitHub Copilot. This repository bridges the gap between cybersecurity expertise and AI agent capabilities, enabling developers to integrate security skills directly into AI workflows. It addresses a critical need for structured, multi-framework security knowledge in the rapidly growing AI agent ecosystem. The repository covers 26 security domains and uses the agentskills.io standard, supporting platforms like Claude Code, GitHub Copilot, Codex CLI, Cursor, and Gemini CLI. It is licensed under Apache 2.0 and has gained 150 stars in 24 hours.

ossinsight · mukul975 · May 25, 00:43

**Background**: MITRE ATT&CK is a widely used knowledge base of adversary tactics and techniques, while NIST CSF 2.0 provides a framework for managing cybersecurity risk. MITRE ATLAS extends ATT&CK to AI-specific threats, D3FEND catalogs defensive countermeasures, and NIST AI RMF addresses AI risk management. This repository combines these frameworks into a unified skill set for AI agents.

<details><summary>References</summary>
<ul>
<li><a href="https://www.vectra.ai/topics/mitre-atlas">MITRE ATLAS : AI security framework with 16 tactics and 84 techniques</a></li>
<li><a href="https://d3fend.mitre.org/">D3FEND Matrix | MITRE D3FEND™</a></li>
<li><a href="https://orca.security/resources/blog/nist-ai-risk-management-framework-ai-rmf/">NIST AI RMF Explained: Framework & Adoption | Orca Security</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#AI agents`, `#MITRE ATT&CK`, `#NIST CSF`, `#agent-skills`

---

<a id="item-6"></a>
## [CloakBrowser: Stealth Chromium Fork Evades Bot Detection](https://github.com/CloakHQ/CloakBrowser) ⭐️ 7.0/10

CloakBrowser, a stealth Chromium fork with source-level fingerprint patches, has gained 148 stars on GitHub in the past 24 hours, claiming to pass all 30 bot detection tests as a drop-in Playwright replacement. This addresses a critical pain point in web automation and scraping, where bot detection systems increasingly block headless browsers, by providing a practical solution that maintains compatibility with existing Playwright scripts. The project applies 33 C++ patches at the Chromium source level to modify browser fingerprints, and it also supports Puppeteer as an alternative automation framework, with a reported 0.9 reCAPTCHA v3 score.

ossinsight · CloakHQ · May 25, 00:43

**Background**: Web automation tools like Playwright and Puppeteer are widely used for testing and scraping, but websites employ bot detection services (e.g., reCAPTCHA, Cloudflare Turnstile) that analyze browser fingerprints to block automated scripts. CloakBrowser modifies Chromium's source code to mimic a real user's browser environment, making it harder to detect.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/CloakHQ/CloakBrowser">GitHub - CloakHQ/CloakBrowser: Stealth Chromium that passes every bot detection test. Drop-in Playwright replacement with source-level fingerprint patches. 30/30 tests passed. · GitHub</a></li>
<li><a href="https://cloakbrowser.dev/">CloakBrowser — Stealth Chromium for Browser Automation</a></li>
<li><a href="https://github.com/microsoft/playwright">GitHub - microsoft/playwright: Playwright is a framework for Web Testing and Automation. It allows testing Chromium, Firefox and WebKit with a single API. · GitHub</a></li>

</ul>
</details>

**Tags**: `#web-automation`, `#bot-detection`, `#chromium`, `#playwright`, `#python`

---

<a id="item-7"></a>
## [Jane Street's magic-trace Gains 76 Stars in 24 Hours](https://github.com/janestreet/magic-trace) ⭐️ 7.0/10

Jane Street's magic-trace, a high-resolution tracing tool for performance analysis, gained 76 stars on GitHub in the past 24 hours, indicating growing interest. This tool enables developers to capture and visualize detailed execution traces at the hardware level, making it easier to diagnose performance bottlenecks in complex systems. magic-trace leverages Intel Processor Trace technology to capture precise execution information, and it is written in OCaml.

ossinsight · janestreet · May 25, 00:43

**Background**: High-resolution tracing tools record the sequence of instructions executed by a program at a very fine granularity. Intel Processor Trace is a hardware feature that efficiently captures this data with low overhead. Jane Street is a quantitative trading firm known for its open-source contributions.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/janestreet/magic-trace">GitHub - janestreet/magic-trace: magic-trace collects and displays high-resolution traces of what a process is doing · GitHub</a></li>
<li><a href="https://sourceforge.net/projects/magic-trace.mirror/">magic-trace download | SourceForge.net</a></li>

</ul>
</details>

**Tags**: `#tracing`, `#performance`, `#debugging`, `#OCaml`, `#systems`

---