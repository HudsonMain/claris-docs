---
name: app-upgrade-tool
description: |
  Use when the user asks about FMUpgradeTool or the FileMaker App Upgrade Tool —
  applying patch files to databases, command-line parameters, patch XML format,
  automated schema and script upgrades.
---

# Claris FileMaker App Upgrade Tool Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker App Upgrade Tool (FMUpgradeTool) applies patch files to FileMaker databases, enabling automated schema and script changes via command-line parameters.

## How to use this skill

1. Read `references/app-upgrade-tool.md` to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
