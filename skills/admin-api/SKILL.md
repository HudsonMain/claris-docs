---
name: admin-api
description: |
  Use when the user asks about the FileMaker Admin API (also called FM Admin
  API) — REST API for administering FileMaker Server or Cloud, managing
  databases, schedules, clients, backups, and server configuration
  programmatically. Always use this skill when the user mentions Admin API,
  automating server management, or controlling FileMaker Server via REST,
  even if they don't explicitly name the "Admin API".
---

# Claris FileMaker Admin API Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker Admin API is a REST API for administering FileMaker Server and FileMaker Cloud. It allows managing databases, schedules, clients, and server configuration programmatically.

## How to use this skill

1. Read `references/admin-api.md` (relative to this skill's directory) to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.py` to refresh references.
