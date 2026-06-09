---
name: filemaker-server
description: |
  Use when the user asks about FileMaker Server (FM Server or FMS) — Admin
  Console, hosting databases, backups, schedules, SSL certificates, external
  authentication, web publishing, ODBC/JDBC, monitoring, logs, AI model
  hosting, performance. Always use this skill for operational server
  questions (how to configure, host, schedule, or monitor FM Server). For
  holistic security best-practice checklists spanning the whole platform,
  use the security-guide skill instead.
---

# Claris FileMaker Server Help

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

FileMaker Server hosts FileMaker databases for multi-user access, providing the Admin Console, scheduling, backups, web publishing, ODBC/JDBC sharing, and AI model hosting.

## How to use this skill

1. Identify the topic area below that matches the user's question.
2. Read the corresponding `references/` file to find the relevant page URL(s).
3. Fetch the page with `WebFetch` from the URL listed there.
4. If a fetch returns 404, tell the user the page may have moved and suggest running `update.py` to refresh references.

## Topic areas

### Admin Console & settings
Startup, general settings, server info, licensing, Admin Console access, clients, command line interface.
→ `references/server-admin-settings.md`

### Databases & hosting
Hosting databases, uploading, verifying, opening/closing/pausing files, web publishing settings, ODBC/JDBC, container data.
→ `references/server-databases-hosting.md`

### Backups & schedules
Backup options, creating schedules, schedule types, restoring, saving/loading schedule settings.
→ `references/server-backups-schedules.md`

### Monitoring & logs
Dashboard, system overview, log files (access, event, client stats, server stats, API logs), Event Viewer.
→ `references/server-monitoring-logs.md`

### Security & authentication
SSL certificates, Let's Encrypt, external authentication, OAuth, permissions, restricting access.
→ `references/server-security.md`

### AI services
Configuring AI services, creating API keys, downloading models, fine-tuning, enabling the model server.
→ `references/server-ai.md`

### Troubleshooting & maintenance
General/network/client problems, Admin Console issues, performance, plug-ins, testing, uninstall.
→ `references/server-troubleshooting.md`

### Installation & configuration
→ `references/server-installation.md`

### Network install setup
→ `references/server-network-install.md`

### Release notes
→ `references/server-release-notes.md`
