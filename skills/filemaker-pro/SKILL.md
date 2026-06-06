---
name: filemaker-pro
description: |
  Use when the user asks about FileMaker Pro — scripting, script steps,
  functions, calculations, layouts, relationships, fields, security, data
  entry, import/export, charts, reporting, printing, developer tools, AI
  features, or any general FileMaker Pro development question.
---

# Claris FileMaker Pro Help

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

FileMaker Pro is a cross-platform relational database application for building custom apps. This skill covers scripting, functions, layouts, relationships, fields, security, import/export, and all other Pro Help topics. Also includes installation guides, SVG grammar for button icons, and release notes.

## How to use this skill

1. Identify the topic area below that matches the user's question.
2. Read the corresponding `references/` file to find the relevant page URL(s).
3. Fetch the page with `WebFetch` from the URL listed there.
4. If a fetch returns 404, tell the user the page may have moved and suggest running `update.sh` to refresh references.

## Topic areas

### Functions

Calculation functions organized by Claris's categories:

- **Get functions** (140) — Get(AccountName), Get(FileName), Get(FoundCount), etc. → `references/pro-func-get.md`
- **Text functions** — Char, Left, Middle, Substitute, Trim, etc. → `references/pro-func-text.md`
- **Text formatting functions** — RGB, TextColor, TextFont, TextSize, TextStyleAdd, etc. → `references/pro-func-text-formatting.md`
- **Number functions** — Abs, Ceiling, Floor, Mod, Round, Sqrt, etc. → `references/pro-func-number.md`
- **Date functions** — Date, Day, DayName, Month, Year, etc. → `references/pro-func-date.md`
- **Time functions** — Hour, Minute, Seconds, Time → `references/pro-func-time.md`
- **Timestamp functions** — Timestamp → `references/pro-func-timestamp.md`
- **Container functions** — Base64Encode, CryptDigest, GetThumbnail, HexEncode, etc. → `references/pro-func-container.md`
- **Japanese functions** — Furigana, Hiragana, Katakana, KanjiNumeral, etc. → `references/pro-func-japanese.md`
- **JSON functions** — JSONGetElement, JSONSetElement, JSONListKeys, etc. → `references/pro-func-json.md`
- **Aggregate functions** — Average, Count, List, Max, Min, Sum, etc. → `references/pro-func-aggregate.md`
- **Repeating functions** — Extend, GetRepetition, Last → `references/pro-func-repeating.md`
- **Financial functions** — FV, NPV, PMT, PV → `references/pro-func-financial.md`
- **Trigonometric functions** — Acos, Asin, Atan, Cos, Sin, Tan, etc. → `references/pro-func-trigonometric.md`
- **Logical functions** — Case, If, Let, While, Evaluate, IsEmpty, Lookup, etc. → `references/pro-func-logical.md`
- **AI functions** — AddEmbeddings, GetEmbedding, PredictFromModel, CosineSimilarity, etc. → `references/pro-func-ai.md`
- **Design functions** — FieldNames, LayoutNames, TableNames, ValueListItems, etc. → `references/pro-func-design.md`
- **Mobile functions** — GetSensor, Location, RangeBeacons, etc. → `references/pro-func-mobile.md`
- **Miscellaneous functions** — ConvertFromFileMakerPath, GetAddonInfo, GetLayoutObjectAttribute, etc. → `references/pro-func-miscellaneous.md`
- **Functions reference & overview** — category pages, custom functions, formulas → `references/pro-func-reference.md`

### Script steps

Script steps organized by Claris's categories:

- **Control** — If, Loop, Perform Script, Set Variable, Exit Script, transactions, etc. → `references/pro-steps-control.md`
- **Navigation** — Go to Layout, Go to Record, Go to Field, Enter Browse/Find/Preview Mode, etc. → `references/pro-steps-navigation.md`
- **Editing** — Copy, Cut, Paste, Clear, Undo/Redo, Set Selection, etc. → `references/pro-steps-editing.md`
- **Fields** — Set Field, Insert from URL, Insert Picture, Replace Field Contents, etc. → `references/pro-steps-fields.md`
- **Records** — New/Delete/Duplicate Record, Import/Export Records, Save Records as PDF, etc. → `references/pro-steps-records.md`
- **Found Sets** — Perform Find, Sort Records, Constrain/Extend Found Set, Omit Record, etc. → `references/pro-steps-found-sets.md`
- **Windows** — New Window, Close Window, Adjust Window, Refresh Window, Set Zoom Level, etc. → `references/pro-steps-windows.md`
- **Files** — Open/Close File, Save a Copy, Print, Read/Write Data File, etc. → `references/pro-steps-files.md`
- **Accounts** — Add Account, Delete Account, Change Password, Re-Login, etc. → `references/pro-steps-accounts.md`
- **AI** — Configure AI Account, Generate Response from Model, Insert Embedding, Perform RAG Action, etc. → `references/pro-steps-ai.md`
- **Spelling** — Check Record, Check Found Set, Select Dictionaries, etc. → `references/pro-steps-spelling.md`
- **Open Menu Item** — Open Manage Database, Open Script Workspace, Open Sharing, etc. → `references/pro-steps-open-menu-item.md`
- **Miscellaneous** — Show Custom Dialog, Open URL, Send Mail, Beep, Execute SQL, etc. → `references/pro-steps-miscellaneous.md`
- **Script steps reference & overview** — category pages, disabling steps → `references/pro-steps-reference.md`

### Script triggers

OnLayoutEnter, OnObjectModify, OnRecordCommit, file/layout/object triggers, actions that don't activate triggers.
→ `references/pro-script-triggers.md`

### Layouts & objects

Creating layouts, layout types and parts, buttons, popovers, tab/slide controls, web viewers, formatting, conditional formatting, styles, themes, arranging objects, auto-resize.
→ `references/pro-layouts.md`

### Fields & data entry

Field types, defining fields, data entry, validation, indexing, value lists, container fields, repeating fields, calculation fields, global fields, tables.
→ `references/pro-fields-data.md`

### Relationships & portals

Creating relationships, relationship types (one-to-many, many-to-many), relationship graph, portals, lookups, related fields.
→ `references/pro-relationships.md`

### Security & accounts

Accounts, privilege sets, extended privileges, encryption, password protection, OAuth, Claris ID, record-level access.
→ `references/pro-security.md`

### Finding & sorting records

Perform Find, Quick Find, find requests, find criteria, omitting records, sorting, constraining/extending found sets.
→ `references/pro-finding-sorting.md`

### Import, export & data exchange

File formats (XML, Excel, CSV, etc.), ODBC/JDBC, external data sources, SQL queries, recurring imports, importing themes/scripts.
→ `references/pro-import-export.md`

### Scripting concepts

Creating and editing scripts, managing scripts, debugging, running scripts on server, script examples, scripting with AppleScript/ActiveX.
→ `references/pro-scripting.md`

### Charts & reporting

Chart types, creating charts, subtotals, summary fields, dynamic reports, sorting for reports.
→ `references/pro-charting-reporting.md`

### Sharing & publishing

Sharing files, peer-to-peer, publishing to web, uploading to server, sending email/URLs.
→ `references/pro-sharing.md`

### File management & developer tools

Creating files, backup, recovery, developer utilities, add-ons, kiosk mode, converting files.
→ `references/pro-file-management.md`

### Printing & previewing

Printing records, labels, envelopes, print setup, page margins, previewing.
→ `references/pro-printing.md`

### Keyboard shortcuts

Shortcuts for macOS and Windows — general, mode, script workspace, text editing, manage database.
→ `references/pro-shortcuts.md`

### General

Preferences, operators, modes, plug-ins, custom menus, planning databases, error codes, new features, miscellaneous topics.
→ `references/pro-general.md`

### Installation & setup

→ `references/pro-installation.md` (installation guide)
→ `references/pro-network-install.md` (network install setup)

### SVG grammar for button icons

→ `references/pro-svg-grammar.md`

### Release notes

→ `references/pro-release-notes.md`
