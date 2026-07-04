---
page: Rate App
route: /rate-app
root: ../../README.md
related:
  - "../(blog)/reviews/README.md"
  - "../chat/README.md"
---

# Rate App

**Route / access:** `/rate-app` — a standalone feedback page, not linked from the main navigation.
**Part of:** [Project root README](../../README.md)

## Purpose

Collects star ratings and optional written feedback from users to support the developer's portfolio and professional growth.

## What the user sees

A centered card titled "Rate MAVEN AI" with a five-star picker. Selecting a star reveals a sentiment badge (from "Very Dissatisfied" to "Very Satisfied") and a short motivational note about the developer's journey, plus an optional comment textarea and a submit button. A minimal footer with the developer's GitHub link, portfolio label, and year sits below.

## What the user can do

Pick a 1–5 star rating, optionally write a comment, and submit the form.

## States & feedback

Submitting shows a "Submitting..." state on the button; after a successful submission the form is replaced by a "Thank You for Your Support!" card with a "Go back to App" button. If the user already submitted a rating previously (tracked via cookie), the thank-you card is shown immediately on page load.

## Flow

A standalone page not reached through in-app navigation. After submitting, users can return to [Chat](../chat/README.md). Ratings collected here feed the [Reviews](../(blog)/reviews/README.md) page.
