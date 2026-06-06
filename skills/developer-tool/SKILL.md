---
name: developer-tool
description: |
  Use when the user asks about the FileMaker Developer Tool or FileMaker
  Developer Utilities (FM Developer Tool) — binding solutions for
  distribution, creating runtime databases, removing admin access, kiosk
  mode packaging. Always use this skill when the user asks about packaging
  or distributing a FileMaker solution, binding an FM file, or kiosk mode.
---

# Claris FileMaker Developer Tool Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker Developer Utilities bind solutions for runtime distribution, remove admin access, and create kiosk-mode databases.

## How to use this skill

1. Read `references/developer-tool.md` (relative to this skill's directory) to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
