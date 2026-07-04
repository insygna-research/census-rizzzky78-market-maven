---
page: Shared Content
route: /share
root: ../../README.md
related:
  - "../chat/README.md"
  - "../history/README.md"
---

# Shared Content

**Route / access:** `/share?type=...&component-id=...&reff-id=...`, reached only via a public share link generated from inside the Chat app.
**Part of:** [Project root README](../../README.md)

## Purpose

Lets anyone with a share link view a Maven result — a product search, product details, a comparison, or a full chat — without needing an account.

## What the user sees

A "Shared Content" header card explaining that this is a read-only view, with a link to open the full App, followed by the shared content itself rendered in the same style as it appears inside a conversation (a product search list, product details panel, comparison table, or full chat transcript).

## What the user can do

Read the shared content and follow the link to the [Chat](../chat/README.md) app for the full feature set.

## States & feedback

If the link's parameters are missing, malformed, or point to content that no longer exists, a "page not found" state is shown instead, with links back to the app, Terms of Service, and Chat History.

## Flow

Only reachable via a link shared from inside [Chat](../chat/README.md). From here, visitors are directed into the app rather than [History](../history/README.md), which requires an authenticated session.
