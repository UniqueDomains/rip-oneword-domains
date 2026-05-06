# Available .RIP One-Word Domains (11,832)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C832%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rip one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,832 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,832 domains · **Median ask:** $11.50 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/rip`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/rip?utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./rip.csv">CSV</a> / <a href="./rip.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .RIP search](https://unique.domains/domains/tld/rip?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .RIP search](https://unique.domains/domains/tld/rip?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .RIP one-word domain catalog.

### Files

- `rip.csv` — public CSV extract (1,000 rows)
- `rip.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rip-oneword-domains/main/rip.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| matcha.rip       | available | $7.99     | —             | 86             | 39     | 6      | name.com  |
| SanDiego.rip     | premium   | $118.80   | $118.80       | 74             | 29     | 9      | namesilo  |
| whynot.rip       | available | $7.99     | —             | 74             | 39     | 7      | name.com  |
| designs.rip      | premium   | $500      | —             | 72             | 21     | 7      | name.com  |
| aliens.rip       | available | $7.99     | —             | 56             | 35     | 6      | name.com  |
| breastcancer.rip | premium   | $123.75   | —             | 58             | 9      | 13     | name.com  |
| trends.rip       | available | $7.99     | —             | 60             | 32     | 6      | name.com  |
| letsgo.rip       | available | $7.99     | —             | 57             | 31     | 7      | name.com  |
| solutions.rip    | available | $7.99     | —             | 56             | 31     | 9      | name.com  |
| blocks.rip       | available | $7.99     | —             | 53             | 29     | 6      | name.com  |
| forms.rip        | available | $7.99     | —             | 54             | 28     | 5      | name.com  |
| systems.rip      | available | $7.99     | —             | 46             | 27     | 7      | name.com  |
| destination.rip  | available | $7.99     | —             | 90             | 25     | 11     | name.com  |
| drops.rip        | available | $7.99     | —             | 52             | 25     | 5      | name.com  |
| gamers.rip       | available | $7.99     | —             | 62             | 24     | 6      | name.com  |
| reports.rip      | available | $7.99     | —             | 58             | 24     | 7      | name.com  |
| echoes.rip       | available | $7.99     | —             | 56             | 24     | 6      | name.com  |
| coupons.rip      | available | $7.99     | —             | 52             | 24     | 7      | name.com  |
| superhero.rip    | available | $7.99     | —             | 84             | 23     | 9      | name.com  |
| holidays.rip     | available | $7.99     | —             | 78             | 23     | 8      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,832 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/rip?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rip?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of .rip domains. The names range from clean single words such as water.rip, motion.rip, and scotch.rip to longer or more specific constructions like midJanuary.rip and inspirational.rip. With a median ask of 11.5, the key question is not headline price but whether the exact word works with the .rip ending. When comparing these domains, favor names where the extension adds meaning or memorability, and be more cautious with trademark-sensitive words such as matisse.rip. For buyers, the strongest candidates are usually short, clear words that stay readable, intentional, and easy to explain out loud.

- All names in this selection use the .rip extension
- Median ask is 11.5 across 11,832 listed domains
- Best fit is usually short words with natural .rip meaning
- Check trademark exposure on names tied to brands or people

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RIP One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RIP page](https://unique.domains/domains/tld/rip?utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rip_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
