# MeteGPT Evidence Log

The public, dated source record behind every competitor-tool and AI-detector claim published on **[metegpt.com](https://metegpt.com)**.

When an article on MeteGPT makes a claim about a named tool or detector, it carries a citation like `(EV-winston-ai-detector-01)`. **That id resolves to an entry in [`evidence-log.json`](./evidence-log.json)**  -  with the exact claim, a verbatim quote from the source, the source URL, and the source date. This repository is that log, published so any reader can audit the sourcing themselves.

- **Human-readable version:** <https://metegpt.com/evidence>
- **How the sourcing works (the protocol):** <https://metegpt.com/methodology>
- **Generated:** 2026-07-11 - **Protocol:** MeteGPT Evidence Protocol (MEP) v1.0 (adopted 2026-07-06)
- **Unique sources:** 105 - **Listings across 10 pages:** 119

## Why this exists

Most "best AI humanizer" and "is X detector accurate" content online cites nothing, or cites affiliate roundups with no disclosed method. The **MeteGPT Evidence Protocol (MEP)** requires the opposite: every third-party claim we publish must trace to a dated, primary, linkable source recorded here *before* it can pass our editorial gate. Publishing the log closes the loop  -  the claim, and its receipt, in the same place.

## What's in each entry

| field | meaning |
|---|---|
| `id` | the citation key used in articles, e.g. `EV-winston-ai-detector-01` |
| `claim` | the specific point the source supports |
| `quote` | a verbatim excerpt from the source |
| `source_url` | the primary source |
| `source_date` | when the source was published/dated |
| `platform` | source type (vendor page, Reddit thread, academic study, journalism, etc.) |
| `protocol_version` | `MEP-1.0`, or `pre-protocol` for the founding pages |
| `re_verified` | whether the source was re-checked live after first collection |

## What's *not* here, and why

Only sources screened **INCLUDED** appear. The protocol deliberately withholds:

- off-topic hits, duplicates, and sources that couldn't be verified on the collection run;
- affiliate roundups with **no disclosed methodology**;
- **vendor-seeded "astroturf" review content**  -  templated forum/subreddit posts funneling toward a fixed set of vendors.

To keep the screening auditable *without* republishing withheld material or naming any third party, each page's `collection_sweep` publishes the **counts**  -  including how many sources were screened out as astroturf. You can see the funnel; you don't get the discarded links.

## Per-page summary

| page | published entries | candidates swept | excluded | dual-coding agreement |
|---|---|---|---|---|
| [`/best-ai-humanizer`](https://metegpt.com/best-ai-humanizer) | 10 | 88 | 81 |  -  |
| [`/detect`](https://metegpt.com/detect) | 11 | 89 | 83 |  -  |
| [`/quetext-ai-detector`](https://metegpt.com/quetext-ai-detector) | 13 | 73 | 61 | 98.3% |
| [`/scribbr-ai-detector`](https://metegpt.com/scribbr-ai-detector) | 13 | 28 | 16 |  -  |
| [`/turnitin-ai-checker`](https://metegpt.com/turnitin-ai-checker) | 15 | 34 | 22 |  -  |
| [`/vs/duey-ai`](https://metegpt.com/vs/duey-ai) | 9 | 32 | 23 |  -  |
| [`/vs/gpthuman-ai`](https://metegpt.com/vs/gpthuman-ai) | 13 | 21 | 10 |  -  |
| [`/vs/grammarly-humanizer`](https://metegpt.com/vs/grammarly-humanizer) | 8 | 52 | 44 | 100% |
| [`/vs/quillbot-humanizer`](https://metegpt.com/vs/quillbot-humanizer) | 12 | 82 | 78 | 95.8% |
| [`/winston-ai-detector`](https://metegpt.com/winston-ai-detector) | 15 | 105 | 90 | 100% |

*"Candidates swept" and "excluded" describe each page's most recent collection run; a page's published entries can also include earlier verified sources re-checked in that run. Dual-coding agreement is the field-level match rate between two independent coders (MEP Section 5); " - " means not yet recorded for that page.*

## Provenance & use

Quotes are short excerpts reproduced for verification and commentary; each remains the property of its source, linked in `source_url`. This compilation is published so MeteGPT's claims can be independently checked. Corrections welcome via an issue.

Maintained by Firat Mihci - https://metegpt.com
