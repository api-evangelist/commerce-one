# Commerce One

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

Commerce One, Inc. was a Pleasanton, California B2B e-commerce software company and one of the defining names of the dot-com era, running the MarketSite marketplace and the Global Trading Web trading network. Founded in 1994 as DistriVision, renamed Commerce One in 1997, it IPO'd in July 1999 and peaked in 2000 at a $21.5B market capitalization. It filed for bankruptcy in October 2004.

**Status: defunct.** `commerceone.com` is registered but publishes no DNS A record. There is no live API, developer portal, SDK, or support surface.

## What survives

`xcbl.org` is still online — a static, HTTP-only archival site that continues to serve **xCBL 4.0**, the XML Common Business Library: a royalty-free library of 44 XML business documents across 9 namespaces, released March 2003 as the first xCBL version to use W3C XML Schema (XSDL) instead of Commerce One's own SOX schema language. Commerce One's SOX influenced W3C XML Schema and JAXB.

The full distribution (1.8 MB, 846 files, 709 `.xsd` modules plus sample instances) is still downloadable from <http://xcbl.org/xcbl40/downloads/xcbl40.zip> under a perpetual, royalty-free license.

## Artifacts in this repo

| Path | What |
|---|---|
| `vocabulary/commerce-one-xcbl-vocabulary.yml` | The 9 xCBL namespaces and all 44 business documents |
| `vocabulary/xsd/` | The 9 namespace root schemas, verbatim from the official archive |
| `examples/` | 18 valid xCBL 4.0 sample XML instances, verbatim, plus `_index.yml` |
| `errors/commerce-one-problem-types.yml` | The `ErrorResponse` envelope and its enumerated code lists |
| `conformance/commerce-one-conformance.yml` | XSDL / OASIS UBL / EDI / RosettaNet / SOX posture |
| `lifecycle/commerce-one-lifecycle.yml` | Version history 2.0 → 4.0 and the company wind-down |
| `changelog/commerce-one-changelog.yml` | Per-version release notes |
| `well-known/commerce-one-well-known.yml` | Discovery probe results (none found) |
| `security/commerce-one-domain-security.yml` | DNS/TLS posture — no TLS, no SPF/DMARC/DNSSEC/CAA |
| `llms/commerce-one-llms.txt` | Agent-facing summary of everything above |

Backed by: canaan-partners
