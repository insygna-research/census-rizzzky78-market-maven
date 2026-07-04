---
page: Chat
route: /chat
root: ../../README.md
related:
  - "c/README.md"
  - "c/[id]/README.md"
  - "../history/README.md"
  - "../share/README.md"
---

# Chat

**Route / access:** `/chat`, reached after logging in, from "Go to App" buttons across the marketing pages, or by clicking "New Chat" in the sidebar.
**Part of:** [Project root README](../../README.md)

## Purpose

The core product experience: a conversational interface where users ask Maven to search for, detail, recommend, or compare electronic products.

## What the user sees

A collapsible sidebar listing the user's past chats and navigation, a header bar showing the current chat's title (once one exists) with a share button, a scrolling message area, and a chat input panel pinned to the bottom of the screen for typing messages, attaching a product, or requesting a comparison.

## What the user can do

Type a message and send it to start a new conversation, attach a product to a message, request a product comparison, respond to Maven's clarifying questions, and open the sidebar to jump into a previous chat or start a new one. Once a share button is available, users can generate a public link to the conversation.

## States & feedback

The browser URL updates in place to `/chat/c/{id}` once the first message is sent, without a page reload. Results stream in progressively as Maven's tools run.

## Flow

Entered directly after login/registration or via "New Chat." Once messages exist, the same experience continues at [`/chat/c/[id]`](c/[id]/README.md). Past conversations are listed on the [History](../history/README.md) page, and completed chats can be viewed read-only via [Share](../share/README.md).
