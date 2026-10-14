![Mohamed A. Ali — backend systems, data tools and open-source fixes](assets/banner.svg)

I build Python services and data tools, with a focus on reliable behaviour and clear tests.
My work includes webhook delivery, dataset checks and language-model evaluation.
I've also contributed accepted fixes to **[Black](https://github.com/psf/black/pull/5427)**
and **[urllib3](https://github.com/urllib3/urllib3/pull/5271)**.

**[Portfolio](https://mohamedajab.com)** &nbsp; / &nbsp;
**[LinkedIn](https://www.linkedin.com/in/mohamed-aj/)** &nbsp; / &nbsp;
**[Merged contributions](https://github.com/pulls?q=is%3Apr+author%3AMohamedajab+is%3Amerged+-user%3AMohamedajab)**

## Selected projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Mohamedajab/relayforge"><img src="assets/relayforge.svg" alt="RelayForge: an API stores events, workers deliver them, and failed attempts are retried." width="100%"></a>
<h3><a href="https://github.com/Mohamedajab/relayforge">RelayForge</a></h3>
<p>A webhook service that keeps track of deliveries, signs requests and retries when a receiver is unavailable. Workers can recover unfinished jobs after a crash.</p>
<p><code>Python</code> <code>FastAPI</code> <code>PostgreSQL</code></p>
<p><a href="https://github.com/Mohamedajab/relayforge/blob/main/docs/evaluation-guide.md">Try the failure-and-recovery demo →</a></p>
</td>
<td width="50%" valign="top">
<a href="https://github.com/Mohamedajab/splitcheck"><img src="assets/splitcheck.svg" alt="SplitCheck: index training rows, stream evaluation rows, and report shared text or groups." width="100%"></a>
<h3><a href="https://github.com/Mohamedajab/splitcheck">SplitCheck</a></h3>
<p>A command-line tool that catches repeated text and shared groups across ML dataset splits. Streaming reads and hash-based lookups avoid loading both full files into memory.</p>
<p><code>Python</code> <code>Data structures</code> <code>pytest</code></p>
<p><a href="https://github.com/Mohamedajab/splitcheck/blob/main/docs/ALGORITHM.md">Read the algorithm and memory benchmark →</a></p>
</td>
</tr>
</table>

### [Pressroom](https://github.com/Mohamedajab/pressroom) · Django publishing app

Authors draft, editors review, and only approved revisions go live. Includes revision
history, scheduled publishing, a REST API and PostgreSQL concurrency tests.

[![Pressroom's editorial dashboard](https://raw.githubusercontent.com/Mohamedajab/pressroom/main/docs/screenshots/dashboard.png)](https://github.com/Mohamedajab/pressroom)

[Run it locally](https://github.com/Mohamedajab/pressroom#run-locally) ·
[Explore the architecture](https://github.com/Mohamedajab/pressroom/blob/main/docs/architecture.md)

## Accepted upstream contributions

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
