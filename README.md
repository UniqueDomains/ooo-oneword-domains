# Available .OOO One-Word Domains (11,816)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C816%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .ooo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,816 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,816 domains · **Median ask:** $4,718.41 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-15  
**Canonical page:** `https://unique.domains/domains/tld/ooo`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/ooo?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./ooo.csv">CSV</a> / <a href="./ooo.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .OOO search](https://unique.domains/domains/tld/ooo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .OOO search](https://unique.domains/domains/tld/ooo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .OOO one-word domain catalog.

### Files

- `ooo.csv` — public CSV extract (1,000 rows)
- `ooo.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/ooo-oneword-domains/main/ooo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar             |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------- |
| geton.ooo         | available | $34.99    | —             | 82             | 10     | 6      | name.com              |
| popup.ooo         | available | $34.99    | —             | 84             | 29     | 6      | name.com              |
| Apples.ooo        | premium   | —         | —             | 90             | 16     | 6      | —                     |
| edamame.ooo       | available | $24.99    | $24.99        | 80             | 9      | 7      | namesilo              |
| playon.ooo        | available | $34.99    | —             | 80             | 14     | 7      | name.com              |
| QandA.ooo         | premium   | —         | —             | 80             | 10     | 7      | —                     |
| toneup.ooo        | available | $34.99    | —             | 80             | 5      | 7      | name.com              |
| hangon.ooo        | available | $34.99    | —             | 82             | 6      | 7      | name.com              |
| pierogi.ooo       | available | $34.99    | —             | 82             | 7      | 7      | name.com              |
| stirup.ooo        | available | $34.99    | —             | 82             | 3      | 7      | name.com              |
| watches.ooo       | available | $34.99    | —             | 84             | 19     | 7      | name.com              |
| Snickers.ooo      | premium   | —         | —             | 80             | 10     | 8      | —                     |
| rumcake.ooo       | available | $34.99    | —             | 81             | 3      | 8      | name.com              |
| FabFour.ooo       | available | $24.99    | $24.99        | 82             | 3      | 8      | namesilo              |
| lightup.ooo       | available | $34.99    | —             | 82             | 15     | 8      | name.com              |
| makers.ooo        | available | $24.99    | $24.99        | 62             | 67     | 6      | namesilo              |
| letsgo.ooo        | resell    | —         | —             | 57             | 31     | 7      | 101domain GRS Limited |
| robots.ooo        | premium   | $20,000   | —             | 62             | 47     | 6      | name.com              |
| keepthechange.ooo | available | $34.99    | —             | 46             | 59     | 15     | name.com              |
| maps.ooo          | resell    | —         | —             | 56             | 31     | 4      | Dynadot LLC           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,816 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/ooo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/ooo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

These domains are one-word names on the .ooo extension. The set includes short verb-led options such as geton.ooo, getup.ooo, and useit.ooo, plus broader dictionary-style terms like emoji.ooo, popup.ooo, and forces.ooo. For founders, the main question is whether the word is memorable enough to offset a less familiar extension. For investors, the key issue is pricing discipline against uncertain resale depth. With a median ask of 4,718, stronger picks tend to be simple to say, easy to recall, and commercially flexible. Weaker picks often depend too heavily on the novelty of .ooo rather than on the word itself.

- Prioritize words that stay clear without relying on the extension
- Short verbs and common nouns usually read better in .ooo
- Use the 4,718 median ask as a reality check on pricing
- Treat niche or awkward plurals as higher-risk brandability bets

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .OOO One-Word Domains*. Version 2026-05-15. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .OOO page](https://unique.domains/domains/tld/ooo?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
