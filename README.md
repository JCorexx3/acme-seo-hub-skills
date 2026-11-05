# ACME SEO Hub skills

SEO workflows for AI agents that use the ACME SEO Hub MCP server. Each folder under `skills/` is one skill: an agent reads `SKILL.md` and follows that workflow (research, audits, competitors, local SEO, AI visibility, reports, and project setup).

The skills need the ACME SEO Hub MCP server connected to return data.

## Install

Install all skills:

```bash
npx skills add JCorexx3/acme-seo-hub-skills
```

Install all skills explicitly:

```bash
npx skills add JCorexx3/acme-seo-hub-skills --skill '*'
```

Install for Claude Code:

```bash
npx skills add JCorexx3/acme-seo-hub-skills --agent claude-code
```

Install for Codex:

```bash
npx skills add JCorexx3/acme-seo-hub-skills --agent codex
```

Or copy each skill folder by hand:

```bash
cp -R skills/* ~/.claude/skills/
cp -R skills/* ~/.codex/skills/
```

## Skills

| Skill | Description | SKILL.md | Raw |
| --- | --- | --- | --- |
| `ai-prompt-research` | Find the questions people ask about a market, how ChatGPT answers them, and which sites get cited in the answers. Use when the user asks what people ask AI about their niche, wants prompt ideas, or wants to know where their brand is missing before choosing prompts to track. Research only; it never saves tracking or starts answer collection. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/ai-prompt-research/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/ai-prompt-research/SKILL.md |
| `ai-visibility-audit` | Audit how a brand shows up in AI answers about its market and deliver a short report on the few changes most likely to get it mentioned or cited, such as a third-party page to get onto, an owned page to improve, or an access problem to fix. Use when the user asks for an AI visibility audit, a GEO or AEO audit, why AI recommends competitors instead of them, or how to show up in ChatGPT, Gemini or Google AI answers. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/ai-visibility-audit/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/ai-visibility-audit/SKILL.md |
| `competitive-landscape` | Map SEO market leaders, winning content themes, keyword coverage, backlinks, and strategic gaps. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/competitive-landscape/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/competitive-landscape/SKILL.md |
| `competitor-analysis` | Analyze one competitor's organic footprint, ranking keywords, content themes, backlinks, and gaps. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/competitor-analysis/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/competitor-analysis/SKILL.md |
| `keyword-clustering` | Cluster keywords by intent and map them to existing or proposed pages. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/keyword-clustering/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/keyword-clustering/SKILL.md |
| `keyword-research` | Discover keyword opportunities, evaluate metrics and SERPs, and save/tag promising terms. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/keyword-research/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/keyword-research/SKILL.md |
| `link-prospecting` | Find link prospects, discover contact paths, and draft outreach from SERPs and backlink signals. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/link-prospecting/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/link-prospecting/SKILL.md |
| `local-seo` | Audit a Google Business Profile, compare it to local competitors, and map Maps visibility around a location. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/local-seo/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/local-seo/SKILL.md |
| `seo-audit` | Audit a website, investigate its real search opportunities, and deliver a short data-backed report on the few changes most likely to grow organic traffic that converts. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/seo-audit/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/seo-audit/SKILL.md |
| `seo-coach` | Enter a friendly ACME SEO Hub coach mode that explains workflows, recommends next steps, and helps users use agents, web search, scraping, and MCP data effectively. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/seo-coach/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/seo-coach/SKILL.md |
| `seo-project-setup` | Populate a project's shared ACME SEO Hub context — site scope, goals, positioning, competitors, key pages, and preferences — plus MCP checks and Search Console intake. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/seo-project-setup/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/seo-project-setup/SKILL.md |
| `seo-report` | Write and save an ACME SEO Hub report as one self-contained HTML page. Use when a skill has finished its research, and whenever the user asks for a report, check-in, or summary, or names a report template. | [SKILL.md](https://github.com/JCorexx3/acme-seo-hub-skills/blob/main/skills/seo-report/SKILL.md) | https://raw.githubusercontent.com/JCorexx3/acme-seo-hub-skills/main/skills/seo-report/SKILL.md |
