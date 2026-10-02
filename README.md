# Available .ONE One-Word Domains (21,434)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-21%2C434%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .one one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **21,434 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 21,434 domains · **Median ask:** $127.33 · **High-demand under $2,500:** 6

**Last updated:** 2026-10-02
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

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| inventive.one | resell    | —         | —             | high           | low    | 9      | Dynadot Inc     |
| ftc.one       | available | $7.99     | $24.75        | medium         | low    | 3      | namesilo        |
| ein.one       | resell    | —         | —             | high           | low    | 3      | NameCheap, Inc. |
| bay.one       | premium   | $625      | $625          | high           | low    | 3      | name.com        |
| akan.one      | available | $7.99     | $24.75        | high           | low    | 4      | namesilo        |
| let.one       | resell    | —         | —             | high           | low    | 3      | —               |
| deb.one       | premium   | $1,035.20 | $1,035.20     | medium         | low    | 3      | spaceship       |
| anoa.one      | available | $9.48     | $30.98        | medium         | low    | 4      | namecheap       |
| osa.one       | resell    | —         | —             | high           | low    | 3      | —               |
| eat.one       | premium   | $550      | $550          | high           | low    | 3      | dynadot         |
| ards.one      | available | $7.99     | $24.75        | medium         | low    | 4      | namesilo        |
| pea.one       | resell    | —         | —             | medium         | low    | 3      | —               |
| ill.one       | premium   | $640      | $640          | high           | low    | 3      | namesilo        |
| biol.one      | available | $6.41     | $19.87        | high           | low    | 4      | spaceship       |
| poe.one       | resell    | —         | —             | high           | low    | 3      | —               |
| lp.one        | premium   | $1,107    | $1,107        | high           | low    | 3      | namesilo        |
| bitt.one      | available | $9.48     | $30.98        | medium         | low    | 4      | namecheap       |
| cana.one      | resell    | —         | —             | medium         | low    | 4      | —               |
| nyc.one       | premium   | $6,250    | —             | high           | medium | 3      | name.com        |
| cues.one      | available | $5.99     | $24.75        | medium         | low    | 4      | namesilo        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 21,434 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 6 high-demand names under $2,500           |
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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

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
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ONE One-Word Domains*. Version 2026-10-02. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ONE page](https://unique.domains/domains/tld/one?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_one_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
