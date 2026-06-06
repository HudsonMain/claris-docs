---
name: developer-tool
description: |
  Use when the user asks about FileMaker Developer Utilities — binding
  solutions, creating runtime databases, removing admin access, kiosk mode
  packaging.
---

# Claris FileMaker Developer Tool Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker Developer Utilities bind solutions for runtime distribution, remove admin access, and create kiosk-mode databases.

## How to use this skill

1. Read `references/developer-tool.md` to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
