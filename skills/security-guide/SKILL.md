---
name: security-guide
description: |
  Reach for this skill when a FileMaker security question spans multiple
  concerns or requires a strategic view: securing an FM deployment
  end-to-end, HIPAA/SOC2/compliance requirements for FileMaker, pre-audit
  hardening checklists, authentication policy design for multi-user
  deployments, "how do I protect my FM solution from unauthorized access",
  or any request for a security overview across multiple layers (encryption,
  network, access control, etc.). This skill covers cross-cutting security
  guidance for the whole Claris platform. For single-task operational steps
  — SSL certificate installation, Admin Console configuration, OAuth setup
  walkthroughs — use filemaker-server instead.
---

# Claris FileMaker Security Guide

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker Security Guide covers comprehensive security practices for the Claris platform — encryption, authentication, network security, secure deployment, compliance, and hardening recommendations.

## How to use this skill

1. Read `references/security-guide.md` (relative to this skill's directory) to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
