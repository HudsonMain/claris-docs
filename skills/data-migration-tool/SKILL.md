---
name: data-migration-tool
description: |
  Use when the user asks about the FileMaker Data Migration Tool (DMT) —
  migrating data between FileMaker files, command-line usage, transferring
  data to an updated clone, container data handling.
---

# Claris FileMaker Data Migration Tool Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker Data Migration Tool (DMT) migrates data from one FileMaker file to another, preserving data while applying structural changes from an updated clone.

## How to use this skill

1. Read `references/data-migration-tool.md` to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
