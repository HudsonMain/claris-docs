---
name: data-api
description: |
  Use when the user asks about the FileMaker Data API (FM Data API) — REST
  endpoints, authentication, session tokens, CRUD operations, running scripts
  via API, container data, error responses, URL format. Always use this skill
  when the user wants to access FM data from an external app via REST, even
  if they don't explicitly name the "Data API".
---

# Claris FileMaker Data API Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker Data API is a REST API for accessing data hosted by FileMaker Server or FileMaker Cloud. It uses JSON for requests/responses and token-based session authentication.

## How to use this skill

1. Read `references/data-api.md` (relative to this skill's directory) to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
