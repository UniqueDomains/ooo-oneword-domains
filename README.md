# Available .OOO One-Word Domains (14,698)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-14%2C698%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .ooo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **14,698 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 14,698 domains · **Median ask:** $5,582.03 · **High-demand under $2,500:** 31

**Last updated:** 2026-08-14
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

- `ooo.csv`, public CSV extract (1,000 rows)
- `ooo.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/ooo-oneword-domains/main/ooo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar     |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------- |
| ana.ooo    | available | $24.99    | $24.99        | high           | low    | 3      | namesilo      |
| DIY.ooo    | resell    | —         | —             | high           | low    | 3      | Dynadot LLC   |
| act.ooo    | premium   | $250,000  | —             | high           | low    | 3      | name.com      |
| bow.ooo    | available | $24.99    | $24.99        | high           | low    | 3      | namesilo      |
| data.ooo   | resell    | —         | —             | medium         | medium | 4      | Porkbun LLC   |
| bad.ooo    | premium   | $26,325   | —             | high           | medium | 3      | name.com      |
| clv.ooo    | available | $24.99    | $24.99        | medium         | low    | 3      | namesilo      |
| only.ooo   | resell    | —         | —             | high           | medium | 4      | NameSilo, LLC |
| dip.ooo    | premium   | $87.49    | $34.99        | high           | low    | 3      | name.com      |
| coy.ooo    | available | $34.99    | $34.99        | medium         | low    | 3      | name.com      |
| post.ooo   | resell    | —         | —             | high           | medium | 4      | Porkbun, LLC  |
| dog.ooo    | premium   | $13,290   | —             | high           | low    | 3      | name.com      |
| ilx.ooo    | available | $24.99    | $24.99        | low            | low    | 3      | namesilo      |
| order.ooo  | resell    | —         | —             | high           | medium | 5      | NameSilo, LLC |
| don.ooo    | premium   | $83.29    | $23.59        | high           | low    | 3      | namesilo      |
| nor.ooo    | available | $34.99    | —             | high           | low    | 3      | name.com      |
| office.ooo | resell    | —         | —             | high           | medium | 6      | Name.com, Inc |
| flu.ooo    | premium   | $22,500   | —             | medium         | low    | 3      | name.com      |
| tow.ooo    | available | $24.99    | $24.99        | medium         | low    | 3      | namesilo      |
| talent.ooo | resell    | —         | —             | high           | medium | 6      | Porkbun, LLC  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 14,698 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 31 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/ooo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/ooo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list gathers one-word .ooo domain names currently available across a single, distinctive extension. The .ooo TLD leans modern and playful, making it a fit for consumer brands, events, and short punchy names. Pricing varies widely: the majority sit under $500, while a smaller tier climbs into premium territory above $10,000. Whether you're comparing entry costs or scanning for a memorable name to launch under, this set gives a full view of what's currently ownable in .ooo.

- 9,642 domains priced under $500
- 2,034 listed as premium status
- 7,582 names flagged as easy to spell
- 436 considered launch-ready by naming fit

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .OOO One-Word Domains*. Version 2026-08-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .OOO page](https://unique.domains/domains/tld/ooo?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ooo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
