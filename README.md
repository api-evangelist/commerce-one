# Commerce One

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
