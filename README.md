# Available .BOUTIQUE One-Word Domains (12,110)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C110%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .boutique one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,110 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,110 domains · **Median ask:** $12.26 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
**Canonical page:** `https://unique.domains/domains/tld/boutique`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/boutique?utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./boutique.csv">CSV</a> / <a href="./boutique.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BOUTIQUE search](https://unique.domains/domains/tld/boutique?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BOUTIQUE search](https://unique.domains/domains/tld/boutique?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BOUTIQUE one-word domain catalog.

### Files

- `boutique.csv` — public CSV extract (1,000 rows)
- `boutique.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/boutique-oneword-domains/main/boutique.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| Acup.boutique     | available | $41.98    | —             | 80             | 5      | 5      | namecheap         |
| Trex.boutique     | available | $41.98    | —             | 80             | 24     | 5      | namecheap         |
| barup.boutique    | available | $6.99     | —             | 82             | 2      | 6      | name.com          |
| Apples.boutique   | available | $41.98    | —             | 90             | 16     | 6      | namecheap         |
| dogsit.boutique   | available | $6.99     | —             | 96             | 2      | 6      | name.com          |
| edamame.boutique  | available | $6.99     | —             | 80             | 9      | 7      | name.com          |
| playin.boutique   | available | $6.99     | —             | 80             | 10     | 7      | name.com          |
| toneup.boutique   | available | $6.99     | —             | 80             | 5      | 7      | name.com          |
| pierogi.boutique  | available | $6.99     | —             | 82             | 7      | 7      | name.com          |
| impress.boutique  | available | $6.99     | —             | 86             | 18     | 7      | name.com          |
| Snickers.boutique | available | $41.98    | —             | 80             | 10     | 8      | namecheap         |
| Ryan.boutique     | available | $41.98    | —             | 60             | 44     | 4      | namecheap         |
| pussy.boutique    | resell    | —         | —             | 50             | 37     | 5      | Spaceship, Inc.   |
| etc.boutique      | premium   | $250      | —             | 58             | 34     | 3      | name.com          |
| whynot.boutique   | available | $6.99     | —             | 74             | 39     | 7      | name.com          |
| brands.boutique   | resell    | —         | —             | 62             | 28     | 6      | Sav.com, LLC - 23 |
| jewels.boutique   | premium   | $250      | —             | 80             | 15     | 6      | name.com          |
| spectra.boutique  | available | $6.99     | —             | 62             | 34     | 7      | name.com          |
| prints.boutique   | resell    | —         | —             | 54             | 18     | 6      | Spaceship, Inc.   |
| dresses.boutique  | premium   | $82.50    | —             | 58             | 10     | 7      | name.com          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,110 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/boutique?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/boutique?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=related_pricing)

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

This selection is made up of one-word .boutique domains only. The set ranges from plain dictionary-style terms like tips.boutique and finals.boutique to shorter invented or compressed forms such as Acup.boutique and barup.boutique. For founders, the main question is whether the word is memorable, easy to say, and specific enough to support a premium retail or niche commerce brand. For investors, the key check is whether the ask leaves room for realistic resale demand in a non-mainstream extension. The median ask is 12.26, but the better names in this set still need careful review for renewal cost, trademark exposure, and how naturally the word fits the .boutique ending.

- One-word .boutique names only
- Includes 12,104 domains in this selection
- Median ask is 12.26 across the set
- Check word fit, renewal cost, and trademark risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BOUTIQUE One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BOUTIQUE page](https://unique.domains/domains/tld/boutique?utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_boutique_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
