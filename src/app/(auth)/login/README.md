---
page: Login
route: /login
root: ../../../../README.md
related:
  - "../register/README.md"
  - "../../(tos)/terms-of-service/README.md"
  - "../../(tos)/privacy-policy/README.md"
---

# Login

**Route / access:** `/login`, reached from the "Go to Login" links in the navigation menu, footer, and the Privacy Policy / Terms of Service pages.
**Part of:** [Project root README](../../../../README.md)

## Purpose

Lets a visitor authenticate with an OAuth provider so they can access the chat application.

## What the user sees

A two-column card: on the left, a "Login to MAVEN AI" heading, a note that login uses OAuth, a stack of provider buttons (Google and GitHub are active; Twitter/X, TikTok, and Instagram are shown but disabled), and a required "accept terms and conditions" checkbox with links to Terms of Service and Privacy Policy. On the right (desktop only), a decorative login illustration. If the user is already signed in, this is replaced by a redirect notice.

## What the user can do

Check the terms checkbox and click an enabled provider button (Google or GitHub) to sign in. Attempting to sign in without checking the box shows a toast asking the user to accept the terms first. Users can also follow the Terms of Service or Privacy Policy links before continuing.

## States & feedback

Shows a toast error if the terms checkbox isn't checked. If a session already exists, the page swaps to a redirect card with a progress bar that sends the user to `/chat` automatically.

## Flow

Reached from [Register](../register/README.md), the navigation bar, or the legal pages. On successful sign-in the user is sent to the [Chat](../../chat/README.md) app.
