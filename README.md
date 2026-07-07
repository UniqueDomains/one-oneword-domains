# Available .ONE One-Word Domains (8,912)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C912%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .one one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **8,912 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 8,912 domains · **Median ask:** $250.52 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
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

- `one.csv`, public CSV extract (1,000 rows)
- `one.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/one-oneword-domains/main/one.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                               |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------- |
| ages.one      | available | $3.49     | $24.75        | medium         | low    | 4      | namesilo                                |
| streetart.one | resell    | $3.99     | —             | medium         | low    | 10     | Spaceship, Inc.                         |
| cot.one       | premium   | $625      | —             | high           | low    | 3      | name.com                                |
| DSLR.one      | available | $3.49     | $24.75        | high           | low    | 4      | namesilo                                |
| aaa.one       | resell    | —         | —             | high           | medium | 3      | PDR Ltd. d/b/a PublicDomainRegistry.com |
| gay.one       | premium   | $6,250    | —             | high           | medium | 3      | name.com                                |
| ISBN.one      | available | $3.49     | $24.75        | high           | low    | 4      | namesilo                                |
| aug.one       | resell    | —         | —             | high           | low    | 3      | Porkbun                                 |
| saw.one       | premium   | $625      | —             | high           | low    | 3      | name.com                                |
| Jody.one      | available | $3.99     | —             | high           | low    | 4      | name.com                                |
| feb.one       | resell    | —         | —             | high           | low    | 3      | Porkbun                                 |
| sex.one       | premium   | $6,250    | —             | high           | medium | 3      | name.com                                |
| mere.one      | available | $30.98    | —             | medium         | low    | 4      | namecheap                               |
| led.one       | resell    | —         | —             | high           | low    | 3      | Spaceship, Inc.                         |
| was.one       | premium   | $625      | —             | low            | low    | 3      | name.com                                |
| sued.one      | available | $3.49     | $24.75        | low            | low    | 4      | namesilo                                |
| yum.one       | resell    | —         | —             | high           | low    | 3      | GoDaddy.com, LLC                        |
| wet.one       | premium   | $625      | —             | high           | low    | 3      | name.com                                |
| whom.one      | available | $3.49     | $24.75        | low            | low    | 4      | namesilo                                |
| babe.one      | resell    | —         | —             | high           | low    | 4      | Dynadot Inc                             |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 8,912 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/one?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/one?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=related_pricing)

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

This list gathers .one domain names built around short, memorable phrases rather than dictionary words alone. Names like becalled.one, letitbe.one, keepfit.one, and getready.one show how the extension favors compact, sayable combinations that read as a single brandable term. With a median ask near $251 across 8,912 names, the .one namespace stays accessible for early-stage founders and selective investors comparing pricing without committing to premium legacy extensions.

- 8,912 .one domain names available across this selection
- Median asking price near $251 per domain
- Short, phrase-based names read as single brandable words
- Updated daily to reflect current .one domain pricing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ONE One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ONE page](https://unique.domains/domains/tld/one?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
