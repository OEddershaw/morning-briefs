# Morning Brief — 2026-06-01

## THE ONE THING

**Handshake raises $3.2M to build the AI-native OS for retail buying — today's most actionable early-stage find.**

Handshake, a UK-backed startup co-led by Triple Point Ventures and Bain & Company's Future Back Ventures (with Octopus Ventures participating), announced a $3.2M seed round today to build what it calls the "AI-native operating system for retail buying." The platform gives retailers, wholesalers, and suppliers a single system to make, track, and execute commercial agreements — replacing the spreadsheets and disconnected systems that still dominate most buying teams. At $3.2M, this is early enough that almost none of your clients will have seen it. The Bain backing (Future Back Ventures) gives it institutional credibility without the profile. For any client struggling with buying process digitisation — particularly in grocery, fashion, or general merch — this is worth a closer look now.

---

## WHAT HAPPENED

- **Anthropic Opus 4.8 (28 May)**: Meaningful step up from 4.7 — stronger agentic coding (64% → 69%), four times less likely to miss flaws in its own code, and a new "dynamic workflows" feature in Claude Code for large-scale multi-step problems. Fast mode is now 3× cheaper, priced the same as 4.7. More honest: flags uncertainties and makes fewer unsupported claims than prior versions.

- **Anthropic self-hosted sandboxes & ant CLI**: Launched at Code with Claude London (May), Anthropic now lets enterprises keep tool execution in their own infrastructure while Claude handles orchestration. The `ant` CLI is a new command-line API client with native Claude Code integration. Significant for enterprise clients concerned about data residency — the agent loop stays on Anthropic's side; tool execution stays inside the customer perimeter. In public beta.

- **Anthropic billing change from 15 June**: Agent SDK and `claude -p` usage will draw from a separate monthly credit pool ($20/Pro, $100/Max 5×, $200/Max 20×) at full API rates. Interactive Claude.ai and Claude Code terminal sessions are unaffected. Worth planning around if you're running agents programmatically at scale.

- **Cursor 3.1**: Shipped a tiled Agents Window — multiple AI agents running in draggable side-by-side panes, with layout persistence. Also adds branch selection for cloud agents and batch speech-to-text. Useful for parallel workstreams in longer sessions.

- **Vercel Open Agents**: Vercel open-sourced a reference platform for building background coding agents that run indefinitely in the cloud — zero timeouts, no local machine needed, supports hundreds of parallel agents. Built on their AI SDK and Sandbox tools. The obvious complement to Cursor Cloud Agents, offering the deployment surface for autonomous coding workflows.

- **PewDiePie's Odysseus goes viral on HN**: The YouTuber-turned-developer released Odysseus, a fully self-hosted AI workspace (chat, autonomous agents, email, docs, research, multi-model comparison). Hit the top of Hacker News with 10k+ GitHub stars in under 24 hours. Local-first, completely open source, no vendor lock-in. Interesting signal for the "sovereign AI workspace" category beyond just power-user curiosity.

- **Dick's Sporting Goods Coach AI launching June**: Dick's is rolling out an agentic AI adviser in its mobile app, built with Adobe Brand Concierge and trained on Dick's own product catalogue and sport expertise. Recommends gear by sport and skill level, offers training tips, personalised to shopping history and stated goals. A concrete, consumer-facing example of agentic AI in retail — not just automation, but a branded intelligence layer.

---

## RETAIL & CONSUMER TECH

- **Handshake — $3.2M seed (today, 1 June)**: AI-native OS for retail buying. Single platform for commercial agreements between retailers, wholesalers, and suppliers. Backed by Triple Point Ventures, Bain's Future Back Ventures, and Octopus Ventures. Co-founder Alex Lindsay describes it as solving the problem that "retail buying still runs largely on spreadsheets, disconnected systems, and anecdotal memory." Very early-stage — exactly the kind of find to bring to buying or procurement-focused clients before the market catches up.

- **Radar — $170M Series B, $1B valuation (19 May)**: New York-based Radar hit unicorn status, round co-led by Gideon Strategic Partners and Nimble Partners. Its overhead RFID sensors capture a full inventory snapshot every eight seconds with 99% item-level accuracy. Already deployed in 1,400+ stores including American Eagle and Old Navy. Plans to expand to EMEA and Latin America. For clients asking about real-time in-store inventory intelligence, Radar is now the clear market leader at scale.

- **ZyG — $60M Series A (May, $500M valuation)**: Agentic DTC ecommerce OS from former ironSource founders raised $60M from Accel, Bessemer, Felix Capital, and Lightspeed — weeks after a $58M seed, taking total funding to $118M. Deploys 60+ specialised AI agents across the full DTC lifecycle (storefront creation, user acquisition, logistics, retention, financing). No public case studies yet. Worth tracking for clients building or evaluating DTC and marketplace capabilities.

- **Lowe's Material Lists**: New AI tool converts handwritten notes, photos, and spreadsheets into quote-ready purchase orders using in-house SKU matching. Supports English and Spanish. Unglamorous but practical — the type of AI application that drives real productivity in operations and trade teams rather than making headlines at conferences.

- **Lidl GB — scan & go expansion**: Lidl extended its Lidl & Go trial (scan items as you shop, monitor spend in real time via Lidl Plus app) to seven stores. Quiet but steady progress toward frictionless checkout in value grocery — a segment where even incremental friction reduction has meaningful throughput impact.

---

## COMPETITIVE WATCH

Nothing significant today.

---

## READING LIST

- [Radar raises $170M Series B — BusinessWire](https://www.businesswire.com/news/home/20260518349821/en/RADAR-Raises-$170-Million-Reaches-$1-Billion-Valuation-to-Bring-Physical-Retail-Into-the-AI-Era) — Full announcement with deployment stats and EMEA expansion plans. Good briefing material for clients evaluating in-store inventory intelligence.
- [Anthropic self-hosted sandboxes and MCP tunnels — The Decoder](https://the-decoder.com/anthropic-adds-self-hosted-sandboxes-and-mcp-tunnels-to-claude-managed-agents/) — Clear technical explainer on the enterprise infrastructure play; useful context for advising clients building AI agents with data residency requirements.
- [Handshake $3.2M seed — Retail Technology Innovation Hub](https://retailtechinnovationhub.com/home/2026/6/1/ai-powered-startup-handshake-bags-32-million-in-funding-from-various-retail-technology-investors) — Today's most relevant early-stage raise. Worth reading in full for the product framing before meeting any buying or commercial team client.
