# My Happy Hour — Public Showcase

**A source-linked local discovery tool for curated happy-hour offers in Brentwood/Burnaby and Downtown Vancouver.**

**Repository type:** Public project showcase  
**Project area:** Local discovery · data curation · consumer web product  
**Canonical source:** Private application repository  
**Status:** Active prototype

---

## Project overview

My Happy Hour was built around a practical data problem: restaurant happy-hour information is fragmented across web pages, location-specific menus, PDFs, and promotions that change over time.

The application brings those offers into a single searchable interface while keeping source links, verification dates, and record status visible.

## What I built

- Curated happy-hour listings for Brentwood/Burnaby and Downtown Vancouver
- Search across restaurants, neighbourhoods, menu highlights, tags, and promotions
- Open-now, geographic, price, late-night, vegetarian, and patio filters
- Sorting by opening status, price, and distance
- Device-local favourites
- Map and official menu links
- Verification and last-checked metadata
- Structured restaurant data separated from the user interface

## Data design

Each restaurant record can carry official-source links, update dates, verification status, neighbourhood, offer details, and menu references. The separation between data and interface makes it possible to review or update offers without rebuilding the product structure.

## Why it matters

The project treats local-offer discovery as a **data maintenance and provenance problem**, not only a search-interface problem. That matters because restaurant promotions change frequently and outdated information can quickly undermine user trust.

## Repository note

This repository is a curated public showcase. The canonical working application and maintenance workflow remain private.

## Author

**Arya Kia**  
Product development · data curation · local discovery
