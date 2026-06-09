---
name: filemaker-webdirect
description: |
  FileMaker WebDirect skill — use for any question about WebDirect
  specifically: which browsers are supported, customizing or branding the
  WebDirect login page, fixing session disconnections or instability,
  deploying WebDirect on FileMaker Server, performance tuning, or enabling
  users to open a FileMaker database from a web browser without installing
  FileMaker Pro. Do not use for general FileMaker layout design, FileMaker
  Go (iOS/iPad), or building custom web apps against FileMaker data via the
  Data API.
---

# Claris FileMaker WebDirect Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

FileMaker WebDirect provides browser-based access to FileMaker databases without requiring FileMaker Pro. It renders layouts in a web browser with configuration options for deployment, theming, and performance.

## How to use this skill

1. Read `references/webdirect.md` (relative to this skill's directory) to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.py` to refresh references.

## Note on browser compatibility

The WebDirect Guide pages only state "most modern browsers." The definitive versioned browser compatibility matrix lives in the **Claris FileMaker Technical Specifications**, not in the WebDirect Guide. If the user asks which specific browser versions are supported, fetch the WebDirect index page first (`https://help.claris.com/markdown/en/webdirect-guide/index.md`) — it links to the Claris Technical Specifications where the full browser support matrix is documented.
