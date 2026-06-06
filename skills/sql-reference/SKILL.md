---
name: sql-reference
description: |
  Use when the user asks about SQL in FileMaker (FM SQL) — ExecuteSQL
  function syntax, ODBC/JDBC SQL queries, supported SQL statements (SELECT,
  INSERT, UPDATE, DELETE), data types, reserved words, SQL expressions.
  Always use this skill for any FM SQL question, including ExecuteSQL calc
  syntax, even if the user doesn't mention "SQL Reference" by name.
---

# Claris FileMaker SQL Reference

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

The FileMaker SQL Reference covers SQL query syntax supported by FileMaker via ExecuteSQL, ODBC/JDBC, and the OData API — including SELECT, INSERT, UPDATE, DELETE statements, supported data types, and reserved words.

## How to use this skill

1. Read `references/sql-reference.md` (relative to this skill's directory) to find the relevant page URL(s) for the user's question.
2. Fetch the page with `WebFetch` from the URL listed there.
3. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.
