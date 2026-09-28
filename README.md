## Antonio Blago

SEO Freelancer & AI Engineer

Building tools that connect SEO with AI -- from MCP servers and agent workflows to LLM visibility tracking.

[![LinkedIn](https://img.shields.io/static/v1?color=2f72ac&label=%20&labelColor=396899&logo=linkedin&logoColor=ffffff&message=LinkedIn&style=for-the-badge)](https://linkedin.com/in/antonioblago)
[![Website](https://img.shields.io/static/v1?color=f6571e&label=%20&labelColor=d44d1a&logo=google-chrome&logoColor=ffffff&message=DE:antonioblago.de&style=for-the-badge)](https://antonioblago.de)
[![Website](https://img.shields.io/static/v1?color=f6571e&label=%20&labelColor=d44d1a&logo=google-chrome&logoColor=ffffff&message=EN:antonioblago.com&style=for-the-badge)](https://antonioblago.com)
---

### Visibly AI -- SEO Copilot Platform

**[visibly-ai.com](https://visibly-ai.com)**

SEO analysis platform with AI copilot, built for SEO freelancers and agencies. Connects Google Search Console, GA4 and DataForSEO into one interface with chat-based workflows.

- SEO skills for analysis, optimization, technical SEO, content and reporting
- 6 specialized agents (Crawling, SEO Analyst, Strategist, Copywriter, Chief Editor, Consultant)
- Automated PDF/HTML reports with Plotly charts
- E-E-A-T tracking, keyword classification, revenue attribution
- 84 MCP tools for Claude Code, OpenAI Codex, GitHub Copilot and other MCP clients, with local (PyPI) or remote transport
- Article optimization skill: your agent writes, Visibly measures [NSS (Neuro-SEO Score)](https://www.visibly-ai.com/nss-score), the agent improves the draft toward your target and returns the editor link
- NSS builds on my [Neuro-SEO System®](https://www.antonioblago.com/de/neuro-seo-system/) (German overview), combining search engine optimization with buying psychology
- Free [AI visibility check](https://app.visibly-ai.com/check): how often AI models name your brand, and what it costs you

| Repo | What it does |
|------|-------------|
| [visiblyai-mcp-server](https://github.com/AntonioBlago/visiblyai-mcp-server) | MCP server v0.13.0 with 84 tools for SEO analysis, project data and content workflows. Available on [PyPI](https://pypi.org/project/visiblyai-mcp-server/). |
| [Visibly AI CMS Connector](https://github.com/AntonioBlago/visibly-ai-cms-connector) | Python SDK connecting your CMS to Visibly through signed webhooks, the Pull API and publication confirmation. Install with `pip install ai-content-autopilot`. |
| [anyCMS](https://github.com/AntonioBlago/anycms) | Concrete CMS use cases for WordPress, Astro, Next.js and Flask. |

The plugins connect **your AI assistant to Visibly**; the CMS connector connects
**your application to Visibly's article API**; anyCMS demonstrates the CMS-side
implementations. Saving a draft and publishing it are separate steps.
[How they work together](https://github.com/AntonioBlago/visibly-ai-cms-connector/blob/master/docs/INTEGRATION_DE.md).

### Download the Visibly plugins

| Client | Download | Installation |
| --- | --- | --- |
| Claude Code | [Plugin ZIP](https://github.com/AntonioBlago/visiblyai-mcp-server/releases/download/plugins-v1.0.1/visibly-claude-1.0.1.zip) | [Claude setup](https://github.com/AntonioBlago/visiblyai-mcp-server/blob/master/PLUGINS.md#claude-code) |
| OpenAI Codex | [Plugin ZIP](https://github.com/AntonioBlago/visiblyai-mcp-server/releases/download/plugins-v1.0.1/visibly-codex-1.0.1.zip) | [Codex setup](https://github.com/AntonioBlago/visiblyai-mcp-server/blob/master/PLUGINS.md#openai-codex) |
| GitHub Copilot CLI | [Skill plugin ZIP](https://github.com/AntonioBlago/visiblyai-mcp-server/releases/download/plugins-v1.0.1/visibly-copilot-1.0.1.zip) | [Plugin + MCP setup](https://github.com/AntonioBlago/visiblyai-mcp-server/blob/master/PLUGINS.md#github-copilot-cli) |

Install through the **public Visibly plugin marketplace** hosted in the repository,
or download a ZIP from the [plugin releases](https://github.com/AntonioBlago/visiblyai-mcp-server/releases/tag/plugins-v1.0.1).
The agent writes with its own model; existing analysis, NSS scoring and draft saving
use 0 Visibly credits. Agent usage and any new paid analysis are billed separately.
These are community-distributed integrations, not listings in the providers' curated
stores. Direct ChatGPT sign-in requires additional OAuth integration.

---

### SkillMind -- Memory Layer for AI Assistants

**[skill-mind.com](https://skill-mind.com)**

Structured memory and skill learning system for AI coding assistants. Instead of losing context between sessions, SkillMind captures patterns, decisions and knowledge from your workflow and makes them retrievable.

- 14 MCP tools for memory management
- 5 vector DB backends (ChromaDB, Pinecone, Qdrant, Weaviate, in-memory)
- YouTube/video learning -- extract skills from tutorials automatically
- Auto-sanitizer removes sensitive data before storing
- Works with Claude Code, Cursor, Windsurf, any MCP-compatible client

| Repo | What it does |
|------|-------------|
| [skillmind](https://github.com/AntonioBlago/skillmind) | Core package -- MCP server, memory management, vector search, video learning pipeline. Published on [PyPI](https://pypi.org/project/skillmind/). |

---

### LLM Visibility Framework

How visible is your brand when people ask ChatGPT, Gemini or Claude? This framework measures it statistically.

- Prompt-based brand mention tracking across multiple LLMs
- Ranking position extraction and comparison
- Statistical significance testing for visibility changes
- CSV/JSON export for further analysis

| Repo | What it does |
|------|-------------|
| [llm-visibility-framework](https://github.com/AntonioBlago/llm-visibility-framework) | Python framework for measuring brand visibility and rankings across LLMs (Claude, GPT-4o, Gemini). |

---

### Focus Areas

- **AI-powered SEO** -- MCP tools, agent workflows, automated audits with PDF reporting
- **LLM Visibility (GEO)** -- Measuring and optimizing how brands appear in AI search
- **SEO Data Engineering** -- CTR models from 1.3M real keywords, intent classification, revenue attribution
- **Agent Architecture** -- Git-native agent definitions, skill registries, orchestrated multi-agent workflows

### Tech Stack

`Python` `Flask` `FastAPI` `React` `MCP` `Claude API` `DataForSEO` `PostgreSQL` `Pinecone` `FalkorDB` `Playwright` `Docker` `Tailwind`

### Keyword Study 2026

CTR benchmarks from 1.3M keywords across 94 domains (real Google Search Console data). Intent-specific CTR models for realistic traffic projections.

[Read the study](https://antonioblago.com/keyword-study-2026-organic-search-ctr)
