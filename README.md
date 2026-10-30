<p align="center">
  <img src="assets/banner.svg" alt="Mohamed A. Ali — software engineering, backend systems and web applications" width="100%">
</p>

I build backend services and web applications, mainly with **Python, SQL and TypeScript**.
My projects explore what happens when requests overlap, a service goes down, or a payment is retried.
I also work with **Java and Spring Boot** for transactional applications.

**Looking for graduate and junior software engineering roles.**

[Portfolio](https://mohamedajab.com) &nbsp; / &nbsp; [LinkedIn](https://www.linkedin.com/in/mohamed-aj/) &nbsp; / &nbsp; [Accepted contributions](https://github.com/pulls?q=is%3Apr+author%3AMohamedajab+is%3Amerged+-user%3AMohamedajab)

## Four projects to start with

<table>
<tr>
<td width="50%" valign="top">
<p><code>01 / BACKEND</code></p>
<h3><a href="https://github.com/Mohamedajab/relayforge">RelayForge</a></h3>
<p><strong>Webhook delivery through receiver failures.</strong></p>
<p>Events are stored, requests are signed, and failed deliveries are retried. Expiring worker leases let another worker recover abandoned jobs.</p>
<p>Python · FastAPI · PostgreSQL · Docker</p>
<p><a href="https://relayforge-demo.vercel.app">Live Python recovery demo</a> · <a href="https://github.com/Mohamedajab/relayforge">Code</a> · <a href="https://github.com/Mohamedajab/relayforge/blob/main/tests/test_postgres_integration.py">Concurrency test</a></p>
</td>
<td width="50%" valign="top">
<p><code>02 / FULL STACK</code></p>
<h3><a href="https://github.com/Mohamedajab/pressroom">Pressroom</a></h3>
<p><strong>Write, review, approve. Keep unfinished edits private.</strong></p>
<p>A publishing workspace with author/editor roles, revision history and a REST API. Public pages serve the approved version while the next draft stays private.</p>
<p>Python · Django · PostgreSQL · Playwright</p>
<p><a href="https://pressroom-demo-mohamedajab.vercel.app/demo/">Live demo — no signup</a> · <a href="https://github.com/Mohamedajab/pressroom">Code</a> · <a href="https://github.com/Mohamedajab/pressroom/blob/main/tests/test_concurrency.py">Edit-conflict tests</a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><code>03 / CLOUD</code></p>
<h3><a href="https://github.com/Mohamedajab/backstop">Backstop</a></h3>
<p><strong>One origin fetch. Many waiting requests.</strong></p>
<p>A public JSON cache that shares concurrent origin fetches and serves recent cached content during slow responses or outages. Includes repeatable concurrency and outage experiments.</p>
<p>TypeScript · Cloudflare Workers · Durable Objects</p>
<p><a href="https://backstop.backstop.workers.dev">Live demo</a> · <a href="https://github.com/Mohamedajab/backstop">Code</a> · <a href="https://github.com/Mohamedajab/backstop/blob/main/docs/benchmarks/README.md">Benchmark method and results</a></p>
</td>
<td width="50%" valign="top">
<p><code>04 / JAVA</code></p>
<h3><a href="https://github.com/Mohamedajab/clearledger">ClearLedger</a></h3>
<p><strong>A retried transfer should not become a second payment.</strong></p>
<p>A React operations console and Java API for account transfers. Balances, balanced journal entries and outgoing events commit in one PostgreSQL transaction.</p>
<p>Java · Spring Boot · React · PostgreSQL · Kafka</p>
<p><a href="https://clearledger-demo.backstop.workers.dev">Live UI — sample data</a> · <a href="https://github.com/Mohamedajab/clearledger">Code</a> · <a href="https://github.com/Mohamedajab/clearledger/blob/main/docs/local-development.md">Run the authenticated backend</a></p>
</td>
</tr>
</table>

## Fixes merged upstream

Changes reviewed and merged by the projects' maintainers:

| Project | My contribution | Merged PR |
| :--- | :--- | :--- |
| **Black** | Fixed formatting of long quoted return annotations on functions with parameters; added regression tests. | [#5427](https://github.com/psf/black/pull/5427) |
| **urllib3** | Fixed gzip cleanup raising an error that decoding had already ignored. | [#5271](https://github.com/urllib3/urllib3/pull/5271) |
| **Sotto** | Announced search-result updates to screen readers while preserving keyboard focus. | [#509](https://github.com/getsotto/sotto/pull/509) |
| **NASA / OpenMDAO Aviary** | Added regression coverage for alphabetical ordering of dynamic-variable metadata. | [#1320](https://github.com/OpenMDAO/Aviary/pull/1320) |

## Data tools and research

- **[SplitCheck](https://github.com/Mohamedajab/splitcheck)** — a Python CLI for finding exact text matches and shared groups across ML dataset splits. Includes streaming checks and an algorithm/memory comparison.
- **[MSc LLM benchmark](https://github.com/Mohamedajab/msc-llm-psychosis-benchmark)** — a completed synthetic multi-turn evaluation project with experiment tooling, annotation workflows and offline checks. Public demonstration data is separate from private study evidence.

## What I work with

**Backend:** Python, FastAPI, Django, Java, Spring Boot, REST APIs<br>
**Web:** TypeScript, JavaScript, React, HTML, CSS<br>
**Data & delivery:** SQL, PostgreSQL, Kafka, Docker, GitHub Actions, Cloudflare Workers<br>
**Verification:** pytest, JUnit, Playwright, database integration tests

---

For a quick look, [try Pressroom](https://pressroom-demo-mohamedajab.vercel.app/demo/).
For the engineering details, [start with RelayForge](https://github.com/Mohamedajab/relayforge).
To get in touch, [message me on LinkedIn](https://www.linkedin.com/in/mohamed-aj/).
