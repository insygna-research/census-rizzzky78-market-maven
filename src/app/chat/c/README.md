---
page: Chat (Seeded Query)
route: /chat/c
root: ../../../README.md
related:
  - "../README.md"
  - "[id]/README.md"
---

# Chat (Seeded Query)

**Route / access:** `/chat/c?query=...` — not linked directly in navigation; reached when something elsewhere in the app (such as a suggested or related query) opens a new chat pre-filled with a specific question.
**Part of:** [Project root README](../../../README.md)

## Purpose

Starts a brand-new conversation that is immediately seeded with a specific query, skipping the empty chat-input step.

## What the user sees

The same chat interface as [`/chat`](../README.md) — sidebar, header, message area, and input panel — except the conversation begins processing the provided query right away instead of waiting for the user to type.

## What the user can do

Continue the conversation exactly as on the main Chat page: reply, attach products, request comparisons, and use the sidebar to navigate elsewhere.

## States & feedback

If no `query` parameter is present, the page redirects to [`/chat`](../README.md) instead of rendering.

## Flow

Reached only via a link that includes a `query` parameter. Behaves identically to [`/chat`](../README.md) once loaded, and continues at [`/chat/c/[id]`](<[id]/README.md>) as the conversation progresses.
