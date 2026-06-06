---
name: filemaker-go
description: |
  Use when the user asks about FileMaker Go (FM Go) — iOS/iPadOS client,
  mobile development, designing for touch, offline access, device sensors,
  iOS App SDK, building custom Xcode apps with FileMaker. Always use this
  skill for any question about using FileMaker on iPhone or iPad, or building
  a custom iOS app with FM, even if the user just says "FM Go" or "FileMaker
  on my iPad."
---

# Claris FileMaker Go Help

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

FileMaker Go is the iOS/iPadOS client for FileMaker databases. This skill also covers the Go Development Guide (designing for mobile), the iOS App SDK (building custom Xcode apps), and release notes.

## How to use this skill

1. Identify the topic area below that matches the user's question.
2. Read the corresponding `references/` file to find the relevant page URL(s).
3. Fetch the page with `WebFetch` from the URL listed there.
4. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.

## Topic areas

### Go Help
Using FileMaker Go — opening files, entering data, working offline, device features, touch gestures.
→ `references/go-help.md`

### Go Development Guide
Designing solutions for mobile — scripts, device sensors, offline sync, Go vs Pro feature differences, best practices.
→ `references/go-development.md`

**Note on layout design for mobile:** The Go Development Guide does not include layout design pages. For questions about designing FileMaker layouts for iPhone/iPad screens (Screen Stencils, Touch themes, auto-resize, best practices), use the FileMaker Pro skill's `references/pro-layouts.md` — specifically `screen-stencils.md` and `best-practices-designing-layouts.md`.

### iOS App SDK Guide
Building custom iOS apps with the FileMaker iOS App SDK — Xcode project setup, configuration, distribution.
→ `references/ios-app-sdk.md`

### Release notes
→ `references/go-release-notes.md`
