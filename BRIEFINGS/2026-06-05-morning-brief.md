# Morning Brief — 2026-06-05

## THE ONE THING

OpenAI officially turned ChatGPT into a performance advertising channel today. The launch of conversion-optimised campaigns — cost-per-action bidding, self-serve, no minimum spend — closes the gap between ChatGPT and Google/Meta for brand performance budgets. Early data from Criteo (integrated with 1,000+ live brands) shows AI-referred conversion rates approaching twice those of traditional search in consumer electronics, home and garden, and lifestyle categories. Retail and grocery brands are currently the dominant ad category on the platform. With 50 million shopping queries a day and $100M annualised ad run rate already in the system, this is no longer a brand awareness experiment — it is a live channel where FMCG and consumer clients will need a considered position on budget allocation.

---

## WHAT HAPPENED

- **OpenAI launches ChatGPT conversion-optimised campaigns (5 June)**: The ChatGPT Ads Manager now supports cost-per-action campaign objectives, backed by a JavaScript Pixel and Conversions API measurement stack. Advertisers pay only when a defined downstream action — purchase, sign-up, click-through — is completed. The $50,000 minimum spend threshold is gone entirely; self-serve is open to US businesses. US programmatic CPMs rose 34% in the immediate run-up to launch. OpenAI targets $2.5B in ad revenue for 2026 and $100B by 2030. For FMCG and retail brand clients: the question is no longer whether ChatGPT is an advertising channel, but how it fits into a performance mix alongside Google Shopping and Meta.

- **GitHub trending dominated by Claude Code tools today (5 June)**: Five of the ten most-trending GitHub repositories today are Claude Code–based tools. The standout is **last30days-skill** (#1 trending): an AI agent skill that researches any topic across Reddit, X, YouTube, Hacker News, Polymarket, and the wider web, scores results by engagement, and synthesises a grounded summary in one pass. Supports 50+ AI coding harnesses including Claude Code, Cursor, GitHub Copilot, and Gemini CLI. The broader signal is that the Claude Code plugin/skill ecosystem is having a genuine growth moment — the tooling surface is expanding faster than the core product releases.

- **GitHub trending: headroom — LLM context compression (5 June, 3,142 new stars today)**: Open-source tool that compresses everything an AI agent reads — tool outputs, logs, RAG chunks, files, conversation history — by 60–95% before it reaches the model, while preserving answer quality. Works as a Python library, transparent proxy (zero code changes), or MCP server. Cross-agent memory and shared compressed context for multi-agent workflows also included. Practically relevant for anyone building RAG pipelines or high-volume agentic systems where inference cost compounds at scale.

---

## RETAIL & CONSUMER TECH

Nothing new in the last 24 hours. The ChatGPT conversion advertising launch (above) is the most directly actionable development for consumer brands and FMCG clients this week — specifically for teams thinking about performance marketing channel strategy. Retail and grocery brands are already the leading ad category on ChatGPT, and the move to CPA pricing makes budget reallocation from Google and Meta a practical near-term decision rather than a speculative one.

---

## PKM & KNOWLEDGE GRAPHS

- **open-notebook v1.9.0 gaining traction (June 2 release, trending today)**: Open-source NotebookLM alternative built on Next.js, FastAPI, and SurrealDB. Fully self-hosted — documents never leave your infrastructure. Supports 18+ AI providers (Anthropic, OpenAI, Ollama, LM Studio, and others), multi-modal inputs (PDFs, video, audio, web pages), and multi-speaker podcast generation. The key differentiator over Google's NotebookLM is provider flexibility and data sovereignty. At 25k GitHub stars with active momentum, this is worth evaluating for any knowledge workflow where enterprise data sensitivity rules out cloud-hosted tools.

---

## COMPETITIVE WATCH

Nothing significant today.

---

## READING LIST

- [ChatGPT launches conversion ads June 5. US programmatic CPMs up 34%](https://ppc.land/chatgpt-launches-conversion-ads-june-5-us-programmatic-cpms-up-34/) — PPC.land. The clearest summary of today's launch mechanics, eligibility window, and immediate market reaction from the media buying side.
- [Retail and grocery brands dominate ChatGPT ads](https://www.marketingdive.com/news/retail-and-grocery-brands-dominate-chatgpt-ads/814024/) — Marketing Dive. Useful context on which categories are leading adoption and early conversion data from Criteo's integration — good briefing material for brand clients.
- [headroom — GitHub](https://github.com/chopratejas/headroom) — The README is the best explainer: benchmark numbers, integration patterns, and practical notes on where 60–95% compression holds vs. breaks. Worth reading before building any token-heavy agent pipeline.
