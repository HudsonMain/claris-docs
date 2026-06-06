---
name: claris-studio
description: |
  Use when the user asks about Claris Studio — web-based app platform, views
  (forms, spreadsheets, kanbans), Studio field types, Studio calculation
  functions, data sources, teams, identity providers.
---

# Claris Studio Help

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

Claris Studio is a web-based app platform for building views (forms, spreadsheets, kanbans), working with data sources, and collaborating in teams — with its own calculation engine and field types.

## How to use this skill

1. Identify the topic area below that matches the user's question.
2. Read the corresponding `references/` file to find the relevant page URL(s).
3. Fetch the page with `WebFetch` from the URL listed there.
4. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.

## Topic areas

### Functions
Claris Studio calculation functions — ABS, IF, CONCATENATE, DATE, SUM, REGEXMATCH, etc.
→ `references/studio-functions.md`

### Fields
Field types — short text, number, date, attachment, calculation, related data, signature, etc.
→ `references/studio-fields.md`

### Views & objects
Views (forms, spreadsheets, kanbans, hubs), chart/card list/spreadsheet/button/group objects, frames, automation, data sources, data filters, importing data.
→ `references/studio-views-objects.md`

### Administration
User roles, team management, licensing, external identity providers (OIDC/SAML with Okta, Microsoft Entra, Google, Amazon Cognito, ADFS).
→ `references/studio-administration.md`
