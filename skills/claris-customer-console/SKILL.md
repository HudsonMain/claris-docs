---
name: claris-customer-console
description: |
  Use when the user asks about the Claris Customer Console — managing Claris
  accounts, teams, users, groups, subscriptions, licensing, team settings.
  Always use this skill for questions about Claris ID accounts, managing FM
  Cloud team members, or license/subscription management in the Claris portal.
---

# Claris Customer Console Help

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The Claris Customer Console is the web portal for managing Claris accounts, teams, subscriptions, users, groups, and licensing.

## How to use this skill

1. Read `references/customer-console.md` (relative to this skill's directory) to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
