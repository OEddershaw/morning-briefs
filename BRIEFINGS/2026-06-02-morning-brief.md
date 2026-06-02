# Morning Brief — 2026-06-02

## THE ONE THING

Anthropic filed a confidential S-1 with the SEC on 1 June, preparing for what could become one of the largest technology IPOs in history. The company's most recent valuation stands at $965 billion — inching toward a $1 trillion debut — with a revenue run rate of roughly $47 billion in May 2026, up from $10 billion the prior year. The filing follows a $65 billion Series H co-led by Altimeter, Sequoia, Coatue, and Dragoneer. For Owen's work: Claude sits at the centre of the AI tooling stack you and your clients are building on. An Anthropic IPO signals the company is transitioning from frontier lab to durable infrastructure provider — which changes how conservative enterprise clients should think about commitment risk when adopting Claude-based tooling.

---

## WHAT HAPPENED

- **Anthropic IPO filing (1 June)**: Anthropic confidentially filed its S-1 with the SEC, targeting a potential $1 trillion-plus public debut. No pricing or timeline set yet. Immediately catapults it into the most valuable listed companies in the world if it debuts near current valuation. [Fortune](https://fortune.com/2026/06/01/anthropic-confidentially-files-ipo-965-billion-valuation/) / [CNBC](https://www.cnbc.com/2026/06/01/anthropic-ipo-s1-prospectus.html)

- **Anthropic billing change, 15 June**: Programmatic Claude usage — Agent SDK, `claude -p`, Claude Code GitHub Actions, third-party agents — moves off subscription limits onto a separate monthly credit pool metered at full API rates ($20 Pro / $100 Max 5× / $200 Max 20×). Interactive terminal use of Claude Code is unaffected. If you're running automations or background agents, check your usage before the 15th.

- **Cursor: /loop and Teams updates (June)**: Cursor shipped `/loop` for long-running local agents — run a prompt on a schedule until a goal is met. Also: live canvas sharing in the browser, Bugbot moved to usage-based billing (cheaper for most), and increased Teams usage limits. Genuinely useful for anyone building agentic workflows on top of Cursor.

- **Google I/O 2026 — Gemini 3.5 Flash + CodeMender**: Google launched Gemini 3.5 Flash, described as their strongest agentic/coding model yet, with a new $100/month Developer tier and Ultra reduced from $250 to $200. Also shipping: CodeMender, an autonomous code security agent from DeepMind that identifies vulnerabilities as it works. DeepMind separately hired 20+ Contextual AI researchers in an $80–90M licensing deal, a significant talent consolidation move.

- **OpenAI: Rosalind Biodefense (1 June)**: OpenAI launched Rosalind, a GPT-based biodefence AI for vetted US government and allied partners covering public health and pandemic preparedness. Limited relevance to Owen's client base but notable as OpenAI's first domain-specific government AI product.

- **Handshake raises £2.5M seed (1 June, London)**: AI-native platform that replaces spreadsheet- and email-based commercial agreements between retailers, wholesalers, and suppliers with a single system to make, track, and execute deals. Backed by Triple Point Ventures, Bain & Company's Future Back Ventures, and Octopus Ventures. This is the gap between headline tech investment and the unglamorous plumbing of retail buying — worth watching for UK retail clients. [PR Newswire](https://www.prnewswire.com/news-releases/a-new-era-for-retail-buying-london-based-retail-technology-company-handshake-raises-3-2m-to-scale-ai-native-platform-302786504.html)

- **RADAR raises $170M Series B at $1B valuation (May)**: New York-based RADAR uses ceiling-mounted RFID sensors and AI to give brick-and-mortar retailers real-time inventory visibility at claimed 99% accuracy. Already deployed in 1,400+ stores for American Eagle and Old Navy. Series B led by Gideon Strategic Partners. This is the RFID + AI inventory story finally hitting scale — relevant for any fashion or apparel client exploring store operations. [Business Wire](https://www.businesswire.com/news/home/20260518349821/en/RADAR-Raises-$170-Million-Reaches-$1-Billion-Valuation-to-Bring-Physical-Retail-Into-the-AI-Era)

- **Dick's Sporting Goods: "Coach by Dick's" (June launch)**: Dick's is rolling out an agentic AI personal shopping assistant in its mobile app, built in partnership with Adobe. The assistant spans the full shopping journey. A concrete example of a major US sports retailer betting on agentic commerce rather than simple chatbots — more interesting than the typical "AI-powered search" story.

- **Supermemory trending on GitHub**: Open-source memory engine and API for LLMs — sits at #1 on LongMemEval, LoCoMo, and ConvoMem benchmarks. v2.0.0 ships unified API across AI SDK and Mastra, with memory saving on by default. Relevant for anyone building multi-session AI agents where context persistence matters (i.e., most serious agentic applications). 24k stars and rising.

- **markitdown (Microsoft) trending on GitHub**: Python tool for converting files and Office documents to Markdown. 139k stars, gaining 3k today. Underrated utility for knowledge workflows — particularly relevant for feeding enterprise document archives into RAG or LLM pipelines.

---

## RETAIL & CONSUMER TECH

**Freshest funding (this week):**
- **Handshake** (London, seed $3.2M, 1 June): AI-native commercial agreements platform for retailers and suppliers. Bain/Octopus-backed. [See above]
- **Replenit** (Warsaw, pre-seed $2.5M, April): Real-time AI decision engine for retail personalisation — interprets behavioural signals to take in-the-moment actions. Backed by ElevenLabs CEO Mati Staniszewski. L'Occitane reported a 235% increase in post-purchase revenue after deployment. 30+ enterprise retailer clients in year one.
- **Corvera** (YC, seed $4.2M): Agentic AI automating operational workflows for CPG brands; integrates with existing ERP and supply chain tools.

**Notable from May:**
- **Vori** ($22M Series B, Cherryrock Capital): Building what it calls the "self-driving operating system for supermarkets" — focused on helping independent grocers compete with Walmart and Amazon.
- **ReFiBuy** ($13.6M seed, NewRoad Capital): Agentic commerce optimisation platform for brands and retailers managing unsold and excess inventory.
- **RADAR** ($170M Series B): See above.

**Retailer moves:**
- Dick's Sporting Goods rolling out "Coach by Dick's" agentic AI assistant (Adobe, June).
- Iceland Foods trialling StrongPoint's SaaS-based order picking for grocery e-commerce fulfilment.
- Lidl GB officially becomes Britain's fifth largest supermarket (8.6% share, +8.8% sales).

---

## COMPETITIVE WATCH

Nothing significant today.

---

## READING LIST

1. [Anthropic confidentially files for IPO after $65B raise at $965B valuation](https://fortune.com/2026/06/01/anthropic-confidentially-files-ipo-965-billion-valuation/) — Fortune. The core facts on Anthropic's IPO filing, revenue run rate, and investor lineup.

2. [A new era for retail buying: Handshake raises $3.2M to scale AI-native platform](https://www.prnewswire.com/news-releases/a-new-era-for-retail-buying-london-based-retail-technology-company-handshake-raises-3-2m-to-scale-ai-native-platform-302786504.html) — PR Newswire. London-based, Bain-backed, solving the unsexy but pervasive problem of spreadsheet-driven commercial agreements in retail buying.

3. [RADAR Raises $170 Million, Reaches $1 Billion Valuation to Bring Physical Retail Into the AI Era](https://www.businesswire.com/news/home/20260518349821/en/RADAR-Raises-$170-Million-Reaches-$1-Billion-Valuation-to-Bring-Physical-Retail-Into-the-AI-Era) — Business Wire. Best summary of where RFID + AI inventory is now and what RADAR's deployment footprint looks like.
