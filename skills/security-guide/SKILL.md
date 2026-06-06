---
name: security-guide
description: |
  Use when the user asks about FileMaker platform security — encryption,
  secure deployment, network hardening, authentication best practices,
  compliance, SSL/TLS, security checklists.
---

# Claris FileMaker Security Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker Security Guide covers comprehensive security practices for the Claris platform — encryption, authentication, network security, secure deployment, compliance, and hardening recommendations.

## How to use this skill

1. Read `references/security-guide.md` to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
