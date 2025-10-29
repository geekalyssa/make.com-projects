# Outbound Automation Suite
### Make.com + Airtable + Claude + Lemlist

A 3-stage automation system that turns raw leads into enriched, qualified prospects — automatically assigned to the right outbound campaign with AI-powered first-touch messaging synced to Lemlist.

---

## 🚀 What This Suite Does

| Stage | Purpose | Tech |
|-------|---------|------|
| **01 — Data Enrichment** | Research company activity & signals using Perplexity → score intelligence | Make.com + Airtable + Perplexity + Claude |
| **02 — Campaign Assignment & Message Generation** | Balance leads across active campaigns → generate personalized first message | Make.com + Airtable + Claude |
| **03 — Lemlist Sync** | Approved messages → dynamic variables → auto-sync into Lemlist sequences | Make.com + Airtable + Lemlist |

---

## 🧩 Problems Solved

- No more manual research or messaging
- Scales outreach without scaling cost
- Every lead gets a relevant, personalized angle
- Eliminates duplicates & bad data early
- Connects enrichment → messaging → outreach in one flow

---

## 🔍 Key Capabilities (Technical)

✅ Dynamic campaign routing based on volumes  
✅ Strict data validation + dedupe guardrails  
✅ Retry protection + controlled rate limiting  
✅ Modular AI messaging (custom prompt mapping per campaign)  
✅ JSON parsing + cleanup for messy LLM responses  
✅ Production-safe fallbacks (auto-default when missing signals)

---

## 🛠️ Files Included

| File | Description |
|------|-------------|
| `01_enrich.json` | Data enrichment via Perplexity → normalized intelligence score |
| `02_campaign_assign_and_generate_ai.json` | Assign to best campaign + generate first message using Claude |
| `03_sync_to_lemlist.json` | On approval → sync contact + variables to Lemlist |

All identifiers replaced with **Hybrid CamelCase placeholders**.  
Airtable + Lemlist **connections not included** — add your own before use.

---

## 🔐 Confidentiality & License

- No API keys, client names, or proprietary identifiers included  
- Generic field labels + placeholders for all table/view/field IDs  
- Demo data only — for portfolio demonstration and evaluation

📜 **License:** CC BY-NC 4.0  
Commercial use requires permission.

---
