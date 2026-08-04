# Imperative Execution

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Imperative Execution is a New York financial technology company and the parent of IntelligentCross, an SEC-registered US equities Alternative Trading System (ATS) that applies machine learning to order matching and price discovery. IntelligentCross operates a non-displayed Midpoint book and ASPEN, a full limit order book with optional displayed capability split into three independent books by fee model (Fee/Fee, Maker/Taker, Taker/Maker), all under MPID INCR, with primary matching engines in the Equinix NY4 data center in Secaucus, New Jersey.

## Interfaces

- **IntelligentCross IQX Market Data Feed** — a binary, multicast-UDP full depth-of-book and execution feed for the ASPEN books. The message specification, the recovery/rerequest specification, the daily symbol mapping file and a full-day sample PCAP capture are all published openly. — https://www.imperativex.com/market-data
- **IntelligentCross FIX Order Entry API** — FIX 4.2 over private cross-connects at Equinix NY4. Subscribers must be registered US broker-dealers; the FIX specification is released to subscribers on request from ops@intelligentcross.com. — https://www.imperativex.com/faq

There is no public HTTP/REST API, OpenAPI document, GraphQL endpoint, MCP server or A2A agent card on any Imperative Execution host — every probe is recorded in `well-known/imperative-execution-well-known.yml` and `conformance/imperative-execution-conformance.yml`.

## Links

- Website — https://www.imperativex.com/
- Market Data — https://www.imperativex.com/market-data
- FAQ — https://www.imperativex.com/faq
- News — https://www.imperativex.com/news
- Form ATS-N (SEC EDGAR, CIK 0001746102) — https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001746102&type=ATS-N&dateb=&owner=include&count=40
- Forge Global secondary-market listing — https://forgeglobal.com/imperative-execution_stock/
