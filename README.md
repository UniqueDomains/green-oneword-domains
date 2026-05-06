# Available .GREEN One-Word Domains (12,257)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C257%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .green one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,257 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,257 domains · **Median ask:** $77.52 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/green`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/green?utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./green.csv">CSV</a> / <a href="./green.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GREEN search](https://unique.domains/domains/tld/green?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GREEN search](https://unique.domains/domains/tld/green?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GREEN one-word domain catalog.

### Files

- `green.csv` — public CSV extract (1,000 rows)
- `green.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/green-oneword-domains/main/green.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                           |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------- |
| howto.green    | available | $11.99    | —             | 76             | 35     | 6      | name.com                                            |
| makeit.green   | resell    | —         | —             | 82             | 22     | 7      | Chengdu West Dimension Digital Technology Co., Ltd. |
| Tools.green    | premium   | $350      | $350          | 56             | 40     | 5      | namecheap                                           |
| payments.green | available | $11.99    | —             | 58             | 33     | 8      | name.com                                            |
| homes.green    | premium   | $1,250    | —             | 86             | 34     | 5      | name.com                                            |
| SanDiego.green | available | $11.99    | —             | 74             | 29     | 9      | name.com                                            |
| etc.green      | premium   | $1,875    | —             | 58             | 34     | 3      | name.com                                            |
| quotes.green   | available | $11.99    | —             | 58             | 29     | 6      | name.com                                            |
| gems.green     | premium   | $1,875    | —             | 70             | 28     | 4      | name.com                                            |
| blocks.green   | available | $11.99    | —             | 53             | 29     | 6      | name.com                                            |
| comics.green   | premium   | $625      | —             | 68             | 24     | 6      | name.com                                            |
| forms.green    | available | $11.99    | —             | 54             | 28     | 5      | name.com                                            |
| girls.green    | premium   | $625      | —             | 83             | 23     | 5      | name.com                                            |
| photos.green   | available | $11.99    | —             | 54             | 28     | 6      | name.com                                            |
| products.green | premium   | $312.50   | —             | 60             | 23     | 8      | name.com                                            |
| backyard.green | available | $11.99    | —             | 80             | 27     | 9      | name.com                                            |
| Alexis.green   | premium   | $1,107    | $1,107        | 72             | 21     | 6      | namesilo                                            |
| KFC.green      | available | $102.98   | —             | 74             | 27     | 3      | namecheap                                           |
| webs.green     | premium   | $625      | —             | 56             | 21     | 4      | name.com                                            |
| drops.green    | available | $11.99    | —             | 52             | 25     | 5      | name.com                                            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,257 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/green?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/green?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of one-word .green domains. The strongest names tend to pair a clear dictionary word with an obvious environmental, sustainable, natural, or modern brand angle. Examples such as campus.green, traction.green, install.green, snack.green, and alabaster.green show the range: some feel commercial and practical, while others are more conceptual. When comparing these domains, start with word quality, then test whether the .green ending adds meaning or creates friction. The median ask is 77.52, which keeps entry cost modest, but selection quality matters more than volume in a niche extension.

- Prefer words that gain meaning from the .green ending
- Check whether the word is easy to say and spell
- Low ask can help, but renewal fit still matters
- Avoid words with obvious trademark exposure

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GREEN One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GREEN page](https://unique.domains/domains/tld/green?utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_green_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
