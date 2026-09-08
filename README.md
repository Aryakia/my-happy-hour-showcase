# My Happy Hour — Public Showcase

**A source-linked local discovery product for curated happy-hour offers in Brentwood/Burnaby and Downtown Vancouver.**

| | |
|---|---|
| **Project type** | Local discovery · data curation · consumer web product |
| **Role** | Creator and developer |
| **Status** | Active prototype |
| **Geographic scope** | Brentwood/Burnaby + Downtown Vancouver |
| **Canonical source** | Private application repository |
| **Public disclosure** | Aggregate catalogue metrics, product design, verification method, and non-sensitive technology |

---

## Executive summary

My Happy Hour was built around a practical data problem: restaurant happy-hour information is fragmented across websites, PDFs, location-specific menus, and promotions that can change without notice.

A useful discovery product therefore needs more than a polished interface. It needs **source provenance, verification status, update dates, and a maintainable data model**.

## Current catalogue snapshot

As of the working snapshot checked on **August 23, 2026**:

- **15 source-linked restaurant locations**
- **6** locations in Brentwood/Burnaby
- **9** locations in Downtown Vancouver
- **14 of 15** records verified against an official source
- **1** record marked partial because a location-specific source could not be confirmed at the time of review

The catalogue is intentionally focused rather than pretending to provide exhaustive city-wide coverage.

## What I built

### Searchable local discovery

Search spans:

- restaurant names
- neighbourhoods
- menu highlights
- tags
- promotions

### Decision-oriented filters

The interface includes practical filters for:

- open now
- geography
- price
- late-night offers
- vegetarian options
- patio availability

Users can also sort by opening status, price, and distance.

### Source-linked records

Each restaurant record can carry:

- official source links
- last-checked / updated date
- verification status
- neighbourhood and location context
- offer details
- menu references

Official restaurant PDFs are linked where appropriate rather than copied into the project.

### Useful consumer features

The working product includes:

- device-local favourites
- map links
- direct menu links
- official PDF links where available
- a project-authored printable linked guide

## Data architecture

The restaurant catalogue is maintained separately from the interface. This separation means a promotion can be reviewed, corrected, or marked stale without restructuring the product UI.

Conceptually, the record lifecycle is:

**discover → verify against source → structure → publish → date-stamp → recheck**

That workflow is central to the product because happy-hour data has a short practical shelf life.

## Verification philosophy

The project distinguishes among records that are:

- verified against an official source
- partially verified / missing a location-specific confirmation
- due for re-check

A missing official source is not silently replaced with an assumption.

## Technology

The working application uses:

- React 19
- TypeScript
- Next-compatible App Router architecture
- Vite/Vinext-compatible tooling
- Cloudflare-compatible output
- automated catalogue and rendered-output tests

## Why this project matters

My Happy Hour is a small consumer product, but it demonstrates a broader product principle: **discovery quality depends on data maintenance**. For time-sensitive local information, provenance and freshness are product features—not back-office details.

## Public/private boundary

This showcase does **not** expose the private working application, unpublished maintenance tooling, internal notes, credentials, environment configuration, or any private operational data. It publishes only deliberately selected catalogue-level metrics, product architecture, verification methodology, and feature scope.

## Author

**Arya Kia**  
Product development · data curation · local discovery
