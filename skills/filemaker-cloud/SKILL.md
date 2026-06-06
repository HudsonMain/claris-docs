---
name: filemaker-cloud
description: |
  Use when the user asks about FileMaker Cloud (FM Cloud) — Claris-hosted
  cloud service, team setup, Claris ID authentication, cloud administration,
  uploading databases to cloud. Always use this skill for questions about the
  Claris-managed cloud hosting option, even if the user just says "FM Cloud"
  or "hosting my FM file on Claris."
---

# Claris FileMaker Cloud Help

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

FileMaker Cloud is the Claris-managed cloud hosting service for FileMaker databases, providing team management, Claris ID authentication, and cloud-specific administration features.

## How to use this skill

1. Identify the topic area below that matches the user's question.
2. Read the corresponding `references/` file to find the relevant page URL(s).
3. Fetch the page with `WebFetch` from the URL listed there.
4. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.

## Topic areas

### Getting started
Initial setup, creating a team, inviting users, uploading databases, connecting from FileMaker Pro.
→ `references/cloud-getting-started.md`

### Administration
Managing databases, users, groups, settings, backups, Data API/OData configuration, SSL, logs.
→ `references/cloud-administration.md`

### Release notes
→ `references/cloud-release-notes.md`
