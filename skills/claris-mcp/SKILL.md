---
name: claris-mcp
description: |
  Use when the user asks about Claris MCP — Model Context Protocol integration
  with FileMaker (FM), enabling AI assistants to read data, run scripts, and
  perform operations on FileMaker databases via MCP tools. Always use this
  skill when the user asks how to connect an AI assistant or LLM to
  FileMaker, set up MCP with FM, or use Claude/AI tools with FileMaker data.
---

# Claris MCP Help

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

Claris MCP (Model Context Protocol) enables AI assistants to interact with FileMaker databases — reading data, running scripts, and performing operations through MCP-compatible tools.

## How to use this skill

1. Read `references/mcp-help.md` (relative to this skill's directory) to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.py` to refresh references.
