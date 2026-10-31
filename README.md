# PiggyVest

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

PiggyVest is a Lagos-based Nigerian fintech (operated by Piggytech Global Limited, RC 1405222) running the country's largest online savings and investment platform, with 6M+ registered users as of 2026. Founded in January 2016 by Somto Ifezue, Odunayo Eweniyi, and Joshua Chibueze as Piggybank.ng and rebranded to PiggyVest in April 2019, the company digitizes the traditional Nigerian "kolo" piggy-bank, layering automated savings, fixed-term safe-locks, naira and dollar wallets, and curated investments on top of licensed banking partners (originally United Bank for Africa) and a PCI-DSS-compliant payment stack. The consumer product family includes Piggybank (automated daily/weekly/monthly savings), SafeLock (fixed-tenor savings with up-front interest), Target Savings (goal-based saving, solo or group), Flex Naira (flexible wallet with free transfers), Flex Dollar / SafeLock Dollar (USD savings), HouseMoney (rent wallet), Investify (curated investment opportunities), GetIT (lifestyle purchase plans), Piggy Points (rewards), and an Accountability Partner feature, all delivered through iOS, Android, and web apps published by Piggytech Global. On the developer side, PiggyVest operates a separate B2B brand — PiggyVest Business — at piggyvest.business and exposes the PiggyVest Business API at api.piggyvest.business, documented at www.piggyvestbusiness.com/docs. The Business API is a Bearer-token authenticated REST API (secret key in Authorization header) covering customer creation and retrieval, customer wallets (create / retrieve / list, accrued-interest tracking, reserved account numbers, funding accounts), wallet-to-wallet and bank transfers (with name inquiry and bank lookup), transactions (status, history, T+1 settlement), scheduled payments (create / cancel / reactivate), webhooks for real-time event notifications, and a "Pay with Pocket" SDK / hosted-checkout integration that lets merchants accept payments funded from a Piggyvest user's Pocket balance. Default rate limits are approximately 100 requests per minute. No public OpenAPI specification, official SDK packages, or open-source client libraries are currently published; access is gated by signing up for a PiggyVest Business dashboard account. Alongside the API, PiggyVest Business offers Invoicing, Customizable Accounts, Business Safelock, Investify for Business, and business savings earning up to 18% per annum. Public engineering presence is limited — the Piggytech Global GitHub org (github.com/PiggyTech) hosts a small set of community wrappers (react-paystack, Smile Identity Node.js and React Native wrappers) and the consumer brand maintains a static piggyvest.github.io site, but there is no developer org publishing official Piggyvest Business SDKs.

**Areas:** Fintech · Savings · Investment · Digital Wallet · Micro Savings · Goal Based Savings · Fixed Deposit · Dollar Savings · Consumer Finance · Personal Finance · Mobile Banking · Business Banking

## PiggyVest on APIs.io

Everything profiled for PiggyVest is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/piggyvest/](https://apis.io/providers/piggyvest/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [PiggyVest Business API](https://apis.io/apis/piggyvest/business-api/) — The PiggyVest Business API is a Bearer-token-authenticated REST API hosted at api.piggyvest.business that lets Nigerian businesses programmatically create…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Piggyvest Domain Security](https://apis.io/security/piggyvest/piggyvest-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.piggyvest.com)
- [Documentation](https://www.piggyvestbusiness.com/docs)
- [Support](https://www.piggyvest.com/support)
- [Blog](https://blog.piggyvest.com)

## API Evangelist rating

**Kin Score 14.8** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 67.0 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 5.3 |
| Developer ergonomics | 23.8 |
| Access clarity | 17.1 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 14.3** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/piggyvest/](https://apis.io/providers/piggyvest/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for PiggyVest: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/piggyvest/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
