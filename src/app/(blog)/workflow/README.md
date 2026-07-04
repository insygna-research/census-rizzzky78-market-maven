---
page: Workflow
route: /workflow
root: ../../../../README.md
related:
  - "../cookbook/README.md"
  - "../features/README.md"
---

# Workflow

**Route / access:** `/workflow`, reached from the "Workflow" / "How_its_Works" link in the navigation menu and footer.
**Part of:** [Project root README](../../../../README.md)

## Purpose

Gives technically curious visitors a detailed, end-to-end explanation of how Maven processes a request, from user input to rendered result.

## What the user sees

A long scroll-tracked article (with a "tracing beam" progress line down the left) walking through seven stages: **User Input Initiation** (text input, product attachment, product comparison, inquiry response — each with an example), **Orchestrator Processing** (message unification, intent determination, tool selection, state management), **Agentic Tool Execution** (tabbed detail cards for each of the five tools — Recommendator, Search Product, Product Details, Comparison, Inquire User — each showing input/output and a process-flow list), **State Mutation**, **UI Update and Rendering** (the set of UI components Maven can render), **Error Handling** (a filterable list of error categories: external, processing, data, user), and **Final Output**. Illustrative code blocks show simplified TypeScript type definitions throughout, plus a diagram image of the overall workflow.

## What the user can do

Scroll through the article, switch between agent-tool tabs to read details for each tool, and filter the error-handling list by category (All, External, Processing, Data, User).

## Flow

Reached from the navigation bar or footer. Complements [Features](../features/README.md) (what the tools do) and [Cookbook](../cookbook/README.md) (how to use them).
