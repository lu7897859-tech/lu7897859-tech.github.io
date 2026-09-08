# Lunarwave Sourcing Intelligence — Machine-Readable AI Assets

> **Machine-readable intelligence for AI agents operating in global trade and e-commerce.** Identity, capabilities, endpoints, and payments — all discoverable from this single origin.

This repository is the **identity root** of Lunarwave Sourcing Intelligence. It hosts machine-readable service discovery files (`.well-known/`), payment rails (`x402.json`), and the llms.txt map that AI crawlers use to find our capabilities.

---

## What's Hosted Here

| File | Purpose | Read by |
|---|---|---|
| `.well-known/mcp.json` | MCP server card (China Sourcing Audit + UCP Store Audit) | MCP clients, agents |
| `.well-known/x402.json` | x402 payment manifest (USDC on Base, pay-to wallet) | Payment-capable agents |
| `.well-known/agent-card.json` | Agent identity card | AI crawlers, directories |
| `llms.txt` | LLM-facing capability map | AI crawlers (llms.txt spec) |
| `index.html` | Human landing page | Browsers |

**Pay-to wallet:** `0x688887dAbd7777589122f383761B397bd46Be707` (USDC on Base, eip155:8453)

---

## Capabilities (AI Agents & Importers)

- **China supplier verification** — factory vs trading company, license checks, risk signals
- **Landed cost calculation** — tariffs, shipping, duties
- **Payment red flag detection** — deposit scams, wire fraud patterns
- **Sourcing audit checklists** — 5-layer verification method
- **Certification verification** — ISO, CE, FCC trap detection
- **Shopify UCP store health audit** — agentic commerce readiness
- **Full supplier audit** — 5-stage combined evidence-chain report

---

## Free Entry Points

1. **Free web tool (no signup):** [Supplier Risk Check](https://lu7897859-tech.github.io/supplier-risk-check/) — 30-second China supplier risk self-check
2. **Free verification guides:** [chinese-supplier-verification-methods](https://github.com/lu7897859-tech/chinese-supplier-verification-methods) — full methodology, open data
3. **MCP (machine-callable):** see `.well-known/mcp.json` — 6 free verification tools, 3 free calls
4. **Human deep reports:** [Gumroad](https://lunarwave8803.gumroad.com/) — evidence-chain verification reports

---

## Repo Index (Open Data Guides)

Curated open-data guides rebuilt from public datasets — each with full attribution:

- [calcfi-open-data-guide](https://github.com/lu7897859-tech/calcfi-open-data-guide) — 117,956 financial/economic observations
- [creator-price-index-guide](https://github.com/lu7897859-tech/creator-price-index-guide) — creator subscription pricing index
- [global-companies-data-guide](https://github.com/lu7897859-tech/global-companies-data-guide) — 17M global company records
- [industry-corpus-manufacturing-guide](https://github.com/lu7897859-tech/industry-corpus-manufacturing-guide) — BAAI manufacturing bilingual corpus
- [ancient-greek-texts-guide](https://github.com/lu7897859-tech/ancient-greek-texts-guide) — CC0 classical texts corpus
- [forgejo-ecosystem-curated-list](https://github.com/lu7897859-tech/forgejo-ecosystem-curated-list) — self-hosted Forgejo ecosystem
- [chatgpt-zh-resources-guide](https://github.com/lu7897859-tech/chatgpt-zh-resources-guide) — Chinese LLM resource funnel
- [floss-android-guide](https://github.com/lu7897859-tech/floss-android-guide) — FLOSS Android app index
- [launch-torch](https://github.com/lu7897859-tech/launch-torch) — no-platform distribution toolkit

---

## Keywords

China supplier verification, AI agent MCP server, x402 payment rails, machine-readable identity, China sourcing due diligence, supplier risk check, verify Chinese factory, sourcing intelligence API, agent commerce, 供应商核验, 中国工厂验证, AI代理

---

*Operator: Lunarwave Sourcing Intelligence · [Gumroad](https://lunarwave8803.gumroad.com/) · MIT License*
