![Mohamed A. Ali — backend systems, data tools and open-source fixes](assets/banner.svg)

I build backend services and data tools in Python. I care about what happens when
requests fail, workers stop, or the data is wrong — and writing tests for those cases.

[Portfolio](https://mohamedajab.com) · [Merged open-source PRs](https://github.com/pulls?q=is%3Apr+author%3AMohamedajab+is%3Amerged+-user%3AMohamedajab)

## Start here

| Project | What it does | A good place to look |
| --- | --- | --- |
| [RelayForge](https://github.com/Mohamedajab/relayforge) | Delivers webhooks with signed requests, retries and recoverable worker jobs. | [Five-minute walkthrough](https://github.com/Mohamedajab/relayforge/blob/main/docs/evaluation-guide.md) |
| [SplitCheck](https://github.com/Mohamedajab/splitcheck) | Finds repeated text and shared groups across ML dataset splits using streaming reads and hash-based lookups. | [Algorithm and memory benchmark](https://github.com/Mohamedajab/splitcheck/blob/main/docs/ALGORITHM.md) |
| [Pressroom](https://github.com/Mohamedajab/pressroom) | A Django publishing app with editorial approval, revision history and scheduled publishing. | [Screenshots and setup](https://github.com/Mohamedajab/pressroom#screens) |

These are personal projects. Their READMEs explain how to run them, what is tested,
and where the limits are.

## Open source

A few changes accepted by other projects:

- **[Black](https://github.com/psf/black/pull/5427):** fixed how long stringified return annotations are split when a function has parameters; added regression cases.
- **[urllib3](https://github.com/urllib3/urllib3/pull/5271):** fixed a gzip decoder error that could return during cleanup after trailing garbage had already been ignored.
- **[Sotto](https://github.com/getsotto/sotto/pull/509):** added accessible search-result announcements and tests that check focus stays in the search field.
- **[OpenMDAO Aviary](https://github.com/OpenMDAO/Aviary/pull/1320):** added ordering checks for dynamic-variable metadata.

## Research

My [MSc research project](https://github.com/Mohamedajab/msc-llm-psychosis-benchmark)
contains a multi-turn language-model evaluation workflow, annotation tools and
offline verification. The repository separates demonstration data from private
research evidence.

## Tools I use

Python · SQL · PostgreSQL · FastAPI · Django · pytest · Docker · GitHub Actions

I also work with JavaScript and TypeScript for web interfaces and their tests.
