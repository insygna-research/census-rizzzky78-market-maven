---
page: Chat (Existing Conversation)
route: /chat/c/[id]
root: ../../../../README.md
related:
  - "../README.md"
  - "../../../history/README.md"
---

# Chat (Existing Conversation)

**Route / access:** `/chat/c/{id}`, reached by opening a chat from the [History](../../../history/README.md) list or the sidebar, or automatically once a new chat's first message has been sent.
**Part of:** [Project root README](../../../../README.md)

## Purpose

Resumes a specific past conversation with its full message history, so users can continue where they left off.

## What the user sees

The same chat interface as [`/chat`](../README.md) — sidebar, header (showing the conversation's title and a share button), message area, and input panel — but pre-loaded with every prior message in the conversation. The browser tab title reflects the chat's title.

## What the user can do

Continue the conversation (send new messages, attach products, request comparisons, respond to inquiries), and use the share button to generate a public link.

## States & feedback

If the chat ID doesn't exist, the user is redirected to [`/chat`](../README.md). If the chat exists but belongs to a different user, a not-found page is shown instead.

## Flow

Reached from [History](../../../history/README.md) or automatically after starting a chat at [`/chat`](../README.md). A shared, read-only view of the same conversation is available via [Share](../../../share/README.md).
