---
name: data-migration-tool
description: |
  Use when the user asks about the FileMaker Data Migration Tool (FM DMT or
  DMT) — migrating data between FileMaker files, command-line usage,
  transferring data to an updated clone, container data handling. Always use
  this skill when the user wants to migrate or transfer FM data to a new file
  version, even if they don't name the tool explicitly.
---

# Claris FileMaker Data Migration Tool Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker Data Migration Tool (DMT) migrates data from one FileMaker file to another, preserving data while applying structural changes from an updated clone.

## How to use this skill

1. Read `references/data-migration-tool.md` (relative to this skill's directory) to find the relevant page URL(s) for the user's question.
2. Fetch the page(s) with `WebFetch` from the URL(s) listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.py` to refresh references.

## Note on multi-page answers

Pre-migration steps are split across two pages: fetch both `before-you-begin.md` (prerequisites: accounts, encryption, extended privileges) and `migrate-data.md` (procedure: creating the clone, closing the source file, running the tool) for complete coverage of setup questions.
