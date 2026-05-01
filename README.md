# Available .COM One-Word Domains (18,320)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-18%2C320%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .com one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **18,320 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 18,320 domains

**Last updated:** 2026-05-01  
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

- `com.csv` — public CSV extract (1,000 rows)
- `com.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/com-oneword-domains/main/com.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status    | ask_price   | renewal_price | attractiveness | demand | length | registrar                                   |
| -------------------- | --------- | ----------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| affricative.com      | available | $12.99      | $17.99        | 66             | 72     | 11     | name.com                                    |
| partial.com          | resell    | $575,000    | $17.99        | 100            | 88     | 7      | GoDaddy.com, LLC                            |
| compound.com         | premium   | $5,685,600  | —             | 77             | 27     | 8      | GoDaddy Online Services Cayman Islands Ltd. |
| abigailship.com      | available | $12.99      | $17.99        | 64             | 72     | 11     | name.com                                    |
| saviour.com          | resell    | $64,630     | $17.99        | 68             | 88     | 7      | GoDaddy.com, LLC                            |
| whats.com            | premium   | $592,250    | —             | 58             | 24     | 5      | GoDaddy Online Services Cayman Islands Ltd. |
| cottageorchard.com   | available | $12.99      | $17.99        | 60             | 72     | 15     | name.com                                    |
| reproduce.com        | resell    | $343,447.50 | $17.99        | 66             | 84     | 9      | Network Solutions, LLC                      |
| stepup.com           | premium   | $177,779.24 | —             | 78             | 19     | 7      | Annulet LLC                                 |
| airbrasion.com       | available | $12.99      | $17.99        | 58             | 72     | 10     | name.com                                    |
| bingeable.com        | resell    | $172,500    | $17.99        | 68             | 80     | 9      | NameCheap, Inc.                             |
| stronger.com         | premium   | $710,700    | —             | 67             | 19     | 8      | GoDaddy.com, LLC                            |
| linearpair.com       | available | $12.99      | $17.99        | 58             | 72     | 11     | name.com                                    |
| literaryfiction.com  | resell    | $10,580     | $19.99        | 60             | 72     | 16     | GoDaddy.com, LLC                            |
| truthordare.com      | premium   | $236,900    | —             | 69             | 18     | 13     | GoDaddy Online Services Cayman Islands Ltd. |
| dativecase.com       | available | $12.99      | $17.99        | 58             | 72     | 11     | name.com                                    |
| apartmentcomplex.com | resell    | $224,250    | $17.99        | 54             | 72     | 17     | GoDaddy.com, LLC                            |
| distribution.com     | premium   | $2,961,250  | —             | 68             | 18     | 12     | GoDaddy.com, LLC                            |
| hornedadder.com      | available | $12.99      | $17.99        | 58             | 72     | 12     | name.com                                    |
| publiclyheld.com     | resell    | $2,758.85   | $19.99        | —              | 72     | 13     | Sav.com, LLC                                |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 18,320 live domains                              |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/com?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/com?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .COM One-Word Domains*. Version 2026-05-01. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .COM page](https://unique.domains/domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_com_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
