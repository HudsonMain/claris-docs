---
name: filemaker-go
description: |
  Use when the user asks about FileMaker Go — iOS/iPadOS client, mobile
  development, designing for touch, offline access, device sensors, iOS App
  SDK, building custom Xcode apps with FileMaker.
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
Designing solutions for mobile — layout considerations, scripts, device sensors, offline sync, best practices.
→ `references/go-development.md`

### iOS App SDK Guide
Building custom iOS apps with the FileMaker iOS App SDK — Xcode project setup, configuration, distribution.
→ `references/ios-app-sdk.md`

### Release notes
→ `references/go-release-notes.md`
