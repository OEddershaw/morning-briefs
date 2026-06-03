# Morning Brief — 2026-06-03

## THE ONE THING

Anthropic filed confidentially for an IPO on 1 June at a ~$965 billion valuation — above OpenAI ($852B) — after closing a $65 billion Series H led by Altimeter, Dragoneer, Greenoaks, and Sequoia. The target window is October–November 2026. The revenue story is the real signal: Anthropic is running at $47B ARR, with Claude Code alone hitting $2.5B ARR by February — roughly $1B in six months from a single CLI tool. For advisory work with large corporates, this matters because it confirms AI coding infrastructure is a category, not a feature: clients who haven't thought about developer tooling as a strategic input are already behind.

---

## WHAT HAPPENED

- **Claude Code Week 22 — Opus 4.8 and "ultracode" workflows**: Claude Opus 4.8 is now the default model across Max, Team Premium, and Enterprise accounts. The bigger change: dynamic workflows (triggered by the keyword "ultracode") let Claude write a script and orchestrate tens to hundreds of background subagents to complete a task. This is a qualitative step in what agentic coding can do. Note: the trigger keyword changed from "workflow" — a breaking change if you have existing prompts.

- **Anthropic billing split on 15 June**: Programmatic usage via subscription plans (Claude Code, Agent SDK) moves to a separate monthly credit pool from 15 June. Worth flagging if you run heavy agent workloads on a subscription.

- **Cursor v3.1 — tiled Agents Window**: Cursor ships a redesigned agents interface with draggable, tiled panes for running multiple AI agents side-by-side. Layouts persist between sessions. Batch speech-to-text and cloud agent branch selection also added. Small but meaningful UX shift in how multi-agent work gets managed.

- **Kroger plots biggest price cuts in years**: New CEO Greg Foran (former Walmart) is laying the groundwork for sweeping price reductions across categories, aiming to close the 10% price gap vs Walmart. Funding mechanism: direct imports and technology-driven cost reduction. The move signals a structural shift in US grocery competitive dynamics — Kroger choosing to compete on price rather than differentiation.

- **Amazon confirms Prime Day dates for June 2026**: Amazon announced dates for this year's Prime Day event, accompanied by a grocery-linked sweepstakes ($1M in free groceries for customers spending $15+ on an online grocery order). Tactical signal for retail teams watching promotional calendar.

---

## RETAIL & CONSUMER TECH

- **Handshake — $3.2M seed (1 June)**: AI-powered platform for commercial agreements between retailers, wholesalers, and suppliers — replacing fragmented email and spreadsheet negotiation with a tracked, accountable deal management system. Backed by Triple Point, Future Back Ventures (Bain & Company), and Octopus Ventures. Squarely in the "under-digitised middle of the retail supply chain" category and worth flagging to FMCG and wholesale clients.

- **Radar — $170M Series B, unicorn**: RFID-based inventory AI platform deployed across 1,400+ stores (Old Navy, American Eagle). Ceiling-mounted sensors update item-level location every 8 seconds at claimed 99% accuracy. One client saw shrink fall 60%; another's BOPIS cancellation rate dropped from 25% to 3%. Backed by Gideon Strategic Partners and Nimble Partners, founded by a former Thiel Fellow. This is now a credible scaled platform — worth including in tech vendor briefings for large-format fashion or general merchandise clients.

- **Corvera — $4.2M seed (YC-backed)**: London-origin, now SF-based. Agentic AI platform automating operational workflows for CPG brands — covering supply chain, retail relationship management, and compliance overhead. Very early, but YC backing and CPG focus makes it relevant to watch for FMCG clients.

- **Limy — $10M seed**: Stealth startup (Flybridge-led) building infrastructure to help brands get discovered by AI agents and LLM-powered shopping environments, rather than traditional search. The "brand visibility in the agentic web" category is nascent, but structurally serious — as AI shopping agents increasingly mediate product discovery, brands that optimise for agent discoverability rather than SEO gain an edge.

---

## PKM & KNOWLEDGE GRAPHS

- **GraphRAG vs vector RAG — the accuracy gap is significant**: Benchmarks from practitioners circulating this week show GraphRAG implementations scoring 90%+ on schema-bound, multi-hop queries where vector RAG scores near zero. The distinction matters: vector RAG retrieves relevant passages; a knowledge graph traverses explicit entity relationships to answer questions that require joining multiple facts. For complex knowledge domains — startup landscapes, market maps, client relationship graphs — graph-structured retrieval is worth the additional build cost. Neo4j remains the reference implementation; Microsoft's GraphRAG library provides a practical starting point.

---

## COMPETITIVE WATCH

Nothing significant today.

---

## READING LIST

- [Anthropic raises $65B, nears $1T valuation ahead of IPO — TechCrunch](https://techcrunch.com/2026/05/28/anthropic-raises-65-billion-nears-1t-valuation-ahead-of-ipo/)
- [RADAR raises $170M, reaches $1B valuation to bring physical retail into the AI era — BusinessWire](https://www.businesswire.com/news/home/20260518349821/en/RADAR-Raises-$170-Million-Reaches-$1-Billion-Valuation-to-Bring-Physical-Retail-Into-the-AI-Era)
- [Claude Code — What's new, Week 22 (Opus 4.8 + dynamic workflows)](https://code.claude.com/docs/en/whats-new/2026-w22)
