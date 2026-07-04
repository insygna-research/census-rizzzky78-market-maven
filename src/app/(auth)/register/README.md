---
page: Register
route: /register
root: ../../../../README.md
related:
  - "../login/README.md"
  - "../../(blog)/cookbook/README.md"
---

# Register

**Route / access:** `/register`, reached from the "Get Started" button on the homepage.
**Part of:** [Project root README](../../../../README.md)

## Purpose

Sets expectations before a new visitor signs up, making clear that Maven is a portfolio demo rather than a production product, and previews what access includes.

## What the user sees

A page framed by the navigation bar and footer. A hero heading "Register to MAVEN AI", followed by a "Demo Application" notice card explaining the app's limitations (limited conversation length, a daily request cap, a preview-only experience, developer-showcase framing), and a "What to Expect" checklist (access to all agentic tools, ability to explore the system, a look at modern AI assistant tech, fair usage limits). If the user already has a session, this page redirects to `/chat` instead.

## What the user can do

Click **Continue to Registration** to proceed to [Login](../login/README.md), or **Learn More** to read the [Cookbook](../../(blog)/cookbook/README.md) before signing up.

## Flow

Arrived at from the homepage CTA. Continues to [Login](../login/README.md) for actual OAuth sign-in, since there is no separate credential-based signup form.
