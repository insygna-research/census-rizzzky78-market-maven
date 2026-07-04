---
page: Chat History
route: /history
root: ../../README.md
related:
  - "../chat/README.md"
  - "../chat/c/[id]/README.md"
---

# Chat History

**Route / access:** `/history`, reached from the "Chat History" link in the app sidebar or navigation.
**Part of:** [Project root README](../../README.md)

## Purpose

Gives the user a single place to browse and jump back into their past conversations with Maven.

## What the user sees

A header card labeled "User Chat History" with a hint to "click to go to chat", above a responsive grid of chat cards — one per past conversation.

## What the user can do

Click any chat card to reopen that conversation at [`/chat/c/[id]`](../chat/c/[id]/README.md).

## States & feedback

If the user has no past chats, the grid renders empty (no chats to show).

## Flow

Reached from the sidebar inside [Chat](../chat/README.md). Selecting a card returns the user to that specific [conversation](../chat/c/[id]/README.md).
