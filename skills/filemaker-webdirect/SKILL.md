---
name: filemaker-webdirect
description: |
  Use when the user asks about FileMaker WebDirect — browser-based access to
  FileMaker databases, WebDirect deployment, configuration, theming,
  performance optimization, supported browsers.
---

# Claris FileMaker WebDirect Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

FileMaker WebDirect provides browser-based access to FileMaker databases without requiring FileMaker Pro. It renders layouts in a web browser with configuration options for deployment, theming, and performance.

## How to use this skill

1. Read `references/webdirect.md` to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
