# Available .ONE One-Word Domains (6,438)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-6%2C442%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-6%2C438%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .one one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 6,442 rows · **Live catalog:** 6,438 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/tld/one`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/one?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./one.csv">CSV</a> / <a href="./one.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ONE search](https://unique.domains/domains/tld/one?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ONE search](https://unique.domains/domains/tld/one?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ONE one-word domain catalog.

### Files

- `one.csv` — public CSV extract (6,442 rows)
- `one.json` — public JSON extract (6,442 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/one-oneword-domains/main/one.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                               |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------- |
| cooked.one    | available | $30.98    | —             | 70             | 14     | 6      | namecheap                               |
| developed.one | resell    | $30.98    | —             | 72             | 8      | 9      | NameCheap, Inc.                         |
| easy.one      | premium   | $6,250    | $6,250        | 128            | 68     | 4      | name.com                                |
| creepy.one    | available | $30.98    | —             | 60             | 13     | 6      | namecheap                               |
| detailed.one  | resell    | $30.98    | —             | 68             | 8      | 8      | Dynadot Inc                             |
| free.one      | premium   | $6,250    | $6,250        | 88             | 57     | 4      | name.com                                |
| cleared.one   | available | $30.98    | —             | 74             | 12     | 7      | namecheap                               |
| shot.one      | resell    | —         | —             | 116            | 98     | 4      | Spaceship, Inc.                         |
| live.one      | premium   | $6,250    | $6,250        | 108            | 56     | 4      | name.com                                |
| composed.one  | available | $30.98    | —             | 71             | 12     | 8      | namecheap                               |
| ancient.one   | resell    | —         | —             | 92             | 98     | 7      | Key-Systems LLC                         |
| good.one      | premium   | $6,250    | $6,250        | 82             | 55     | 4      | name.com                                |
| sideways.one  | available | $30.98    | —             | 70             | 12     | 8      | namecheap                               |
| fan.one       | resell    | —         | —             | 88             | 98     | 3      | Dynadot Inc                             |
| true.one      | premium   | $6,250    | $6,250        | 86             | 52     | 4      | name.com                                |
| confirmed.one | available | $30.98    | —             | 69             | 12     | 9      | namecheap                               |
| canadian.one  | resell    | —         | —             | 88             | 98     | 8      | Dynadot Inc                             |
| fast.one      | premium   | $6,250    | $6,250        | 82             | 52     | 4      | name.com                                |
| satanic.one   | available | $30.98    | —             | 48             | 12     | 7      | namecheap                               |
| taiwan.one    | resell    | —         | —             | 66             | 93     | 6      | PDR Ltd. d/b/a PublicDomainRegistry.com |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 6,442-row public sample | 6,438 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/one?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/one?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .ONE One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ONE page](https://unique.domains/domains/tld/one?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
