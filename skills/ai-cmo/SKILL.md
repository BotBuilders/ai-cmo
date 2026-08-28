---
name: ai-cmo
description: Reads this account's AI CMO marketing library from the BotBuilders skills server and works from it. Use for any marketing task — strategy, positioning, budget and planning, paid ads on any platform, SEO, GEO and AI search visibility, copywriting for email, landing pages, ads, SMS and social, PR and influencer and affiliate programs, conversion optimization, attribution, retention, and client reporting.
---

# AI CMO

This account has a marketing library on the server. It is the source of truth for how the work
gets done here, and it is more specific than general marketing knowledge.

## Get the right chapter before you answer

1. `list_skills` with `path: "ai-cmo"` — this lists the library's chapters. A plain `list_skills`
   with no path will **not** show them.
2. `get_skill` on the chapter that matches the ask, and read it before you produce anything.
3. If a chapter names another chapter, fetch that one too.

Long bodies come back paginated with an instruction to continue. Follow it — a half-read chapter
is worse than none, because the part you skipped is usually the constraints.

## When the library comes back empty

Say so plainly and stop. An empty list means this account is not switched on for AI CMO yet,
which is a billing question for BotBuilders support — not something to work around by answering
from general knowledge.

## Two standing rules from the library

These hold even when a chapter does not repeat them:

- **Never invent a fact about the business.** No made-up metrics, testimonials, case studies,
  reviews, journalists, outlets, follower counts, or quotes. Where a number or a name is needed
  and missing, name the gap in the output instead of filling it.
- **Draft; never launch.** Do not spend, publish, post, send, or pitch. Every output is something
  the user reviews first.

## Red flags

- Answering a marketing question without calling `list_skills` with the path
- Calling `list_skills` with no path and concluding the library is empty
- Filling a missing number with a plausible one
- Acting on a chapter you only read the first page of
