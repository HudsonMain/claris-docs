---
name: claris-connect
description: |
  This is the Claris Connect reference skill. Claris Connect is Claris's
  iPaaS/workflow automation platform (like Zapier or Make) for connecting
  FileMaker to external services. Invoke when a user asks about Claris
  Connect by name, wants to automate FileMaker workflows via an external
  automation platform, needs to set up flows, triggers, or actions, or asks
  about connectors: Slack, Stripe, Salesforce, Google, Microsoft, Outlook,
  Teams, AWS, Twilio, and 80+ others. Also covers Apple School Manager
  integration. Do not use for native FileMaker scripting, calculations, or
  HTTP requests made directly from within FileMaker scripts.
---

# Claris Connect Help

> Navigator skill — routes to reference files, then fetches live Claris documentation on demand.

Claris Connect is a workflow automation platform that connects FileMaker with third-party services via flows (triggers + actions). It supports 80+ connectors and built-in data processing utilities.

## How to use this skill

1. Identify the topic area below that matches the user's question.
2. Read the corresponding `references/` file to find the relevant page URL(s).
3. Fetch the page with `WebFetch` from the URL listed there.
4. If a fetch returns 404, tell the user the page may have moved and suggest running `update.py` to refresh references.

## Topic areas

### Connect Help
Creating flows, triggers, actions, managing projects, user settings, general usage.
→ `references/connect-help.md`

### Connector Reference — Built-in Utilities
Calculations, Cryptography, Dates, Documents, HTTP, Images, JSON, Lists, Schedules, Text, Variable, Webhooks, Approvals.
→ `references/connect-ref-utilities.md`

### Connector Reference — Claris Ecosystem
FileMaker, FileMaker Cloud, FileMaker Server, Server Admin API, Cloud Admin API, Claris Studio.
→ `references/connect-ref-claris.md`

### Connector Reference — Cloud & Storage
AWS (Lambda, S3, SES), Azure AD, Box, Dropbox, Dropbox Sign, FTP, SFTP, Google Drive, SharePoint.
→ `references/connect-ref-cloud-storage.md`

### Connector Reference — Communication & Messaging
Chatwork, Mailchimp, Mailgun, Mailparser, Media SMS, Microsoft Outlook, Microsoft Teams, PubNub, Sendgrid, Slack, Twilio, Twitter.
→ `references/connect-ref-communication.md`

### Connector Reference — Business Apps
CRM, e-commerce, project management, finance, surveys, forms: HubSpot, Jira, Pipedrive, QuickBooks, Shopify, Stripe, Trello, WooCommerce, Xero, Zoom, Google Sheets/Calendar, and more.
→ `references/connect-ref-business-apps.md`

### Connector Reference — AI & Specialized Services
Clarifai, OpenAI, MonkeyLearn, Smmry, Jamf Pro, OneRoster, Particle, and Japan-specific services (CloudSign, Ekispert, iTrust, SmartHR, NAVITIME, PostcodeJP).
→ `references/connect-ref-ai-specialized.md`

### Apple School Manager Guide
Using Claris Connect with Apple School Manager for education workflows.
→ `references/connect-apple-school-manager.md`

### Release notes
→ `references/connect-release-notes.md`
