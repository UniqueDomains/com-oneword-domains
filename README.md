# Available .COM One-Word Domains (8,234)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C234%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .com one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **8,234 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 8,234 domains · **Median ask:** $176,408.29 · **High-demand under $2,500:** 156

**Last updated:** 2026-09-29
**Canonical page:** `https://unique.domains/domains/tld/com`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./com.csv">CSV</a> / <a href="./com.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .COM search](https://unique.domains/domains/tld/com?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .COM search](https://unique.domains/domains/tld/com?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .COM one-word domain catalog.

### Files

- `com.csv`, public CSV extract (1,000 rows)
- `com.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/com-oneword-domains/main/com.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price     | renewal_price | attractiveness | demand | length | registrar                                   |
| ------------- | --------- | ------------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| cononie.com   | available | $16.98        | —             | high           | high   | 7      | namecheap                                   |
| achy.com      | resell    | $57,385       | $19.99        | medium         | low    | 4      | Dynadot Inc                                 |
| darned.com    | premium   | $11,949.24    | $19.99        | medium         | low    | 6      | Annulet LLC                                 |
| acinetae.com  | available | $16.98        | —             | low            | low    | 8      | namecheap                                   |
| yank.com      | resell    | $1,149,999.99 | $17.99        | high           | low    | 4      | GoDaddy Online Services Cayman Islands Ltd. |
| towards.com   | premium   | $207,287.50   | —             | high           | low    | 7      | GoDaddy.com, LLC                            |
| contrazy.com  | available | $16.98        | —             | high           | high   | 8      | namecheap                                   |
| amici.com     | resell    | $253,000      | $19.99        | high           | medium | 5      | Sea Wasp, LLC                               |
| dolorous.com  | premium   | $6,737.44     | $19.99        | medium         | low    | 8      | Annulet LLC                                 |
| kongfuze.com  | available | $12.99        | $17.99        | high           | high   | 8      | name.com                                    |
| curie.com     | resell    | $1,149,999.99 | $19.99        | high           | low    | 5      | Dynadot Inc                                 |
| merciful.com  | premium   | $77,096.74    | $19.99        | high           | low    | 8      | Annulet LLC                                 |
| prefaded.com  | available | $10.98        | $18.48        | high           | medium | 8      | namecheap                                   |
| dovish.com    | resell    | $38,178.85    | $19.99        | medium         | low    | 6      | GoDaddy.com, LLC                            |
| runproof.com  | premium   | $1,184.50     | $19.99        | medium         | low    | 8      | Megazone Corp., dba HOSTING.KR              |
| catarrhal.com | available | $11.28        | $18.48        | medium         | low    | 9      | namecheap                                   |
| prisms.com    | resell    | $281,750      | $17.99        | medium         | low    | 6      | GoDaddy.com, LLC                            |
| faithless.com | premium   | $29,553.28    | $19.99        | medium         | low    | 9      | Spaceship, Inc.                             |
| catkinate.com | available | $11.28        | $18.48        | medium         | low    | 9      | namecheap                                   |
| existing.com  | resell    | $57,385       | $17.99        | high           | low    | 8      | Dynadot Inc                                 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 8,234 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 156 high-demand names under $2,500         |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/com?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/com?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set covers one-word .com domain names only — the most recognized and trusted domain extension. It ranges from ultra-short names like xix.com to descriptive words like keepfaith.com and asyouwish.com, giving a clear view of how pricing scales with length, clarity, and brand potential across the .com namespace.

- 18,322 one-word .com domains tracked in this set
- Median ask near $143,958 across the selection
- Mix of short brandables and descriptive one-word names
- Updated daily for accurate pricing and availability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .COM One-Word Domains*. Version 2026-09-29. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .COM page](https://unique.domains/domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
