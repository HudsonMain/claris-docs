---
name: odata
description: |
  Use when the user asks about OData with FileMaker (FM OData) — OData
  protocol, connecting Tableau or Power BI to FileMaker, OData API
  endpoints, filtering, querying, and configuration. Always use this skill
  when the user mentions connecting a BI tool like Tableau or Power BI to
  FM data, even if they don't name "OData" explicitly.
---

# Claris FileMaker OData Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker OData API exposes FileMaker data via the OData protocol, enabling integration with business intelligence tools like Tableau, Power BI, and other OData-compatible clients.

## How to use this skill

1. Read `references/odata.md` (relative to this skill's directory) to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
