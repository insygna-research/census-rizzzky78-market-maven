---
page: Reviews
route: /reviews
root: ../../../../README.md
related:
  - "../../rate-app/README.md"
---

# Reviews

**Route / access:** `/reviews`, reached from the "Public Reviews" link in the footer.
**Part of:** [Project root README](../../../../README.md)

## Purpose

Displays public user feedback and ratings to build social proof for prospective users.

## What the user sees

A "Public Reviews" heading (flagged as still under construction) above a paginated grid of review cards. Each card shows a reviewer avatar, name, a 1–5 star rating, a comment, and a relative timestamp (e.g. "3 days ago"). Pagination controls sit below the grid.

## What the user can do

Page through reviews using the previous/next arrows or numbered page buttons.

## States & feedback

Shows a loading spinner while ratings are being fetched; falls back to sample review data if the ratings API is unavailable.

## Flow

Reached from the site footer. Related to [Rate App](../../rate-app/README.md), where users submit the ratings shown here.

## Notes

The section is explicitly marked "under construction" in the UI, and the displayed reviews currently fall back to bundled sample data rather than exclusively live submissions.
