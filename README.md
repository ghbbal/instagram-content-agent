# Instagram Content Agent

A privacy-safe, Markdown-based workspace for turning a creator's real experiences, content history, and ideas into stronger Instagram Reel concepts.

## Problem

Generic idea generators produce generic posts. Creators need suggestions that fit their voice, schedule, audience, proven formats, and actual life—without inventing stories or chasing every trend.

## What I built

I built a lightweight content-strategy agent that uses editable Markdown files as transparent memory. It reviews a creator profile, content pillars, publishing history, and idea bank before recommending what to film next.

This public version is a reusable template. Personal profile details, account information, private analytics, and unpublished creator data are intentionally excluded.

## How it works

1. Add only the creator context you are comfortable storing locally.
2. Give `AGENT_PROMPT.md` to an AI assistant as project instructions.
3. Ask for ideas based on a real situation, available footage, and editing time.
4. Move concepts from **Seed** to **Ready**, **Scheduled**, and **Published**.
5. Record consistent post-performance measurements so the agent can identify patterns without treating one viral post as proof.

```text
Creator context + content pillars + post history + idea bank
                              ↓
                 filter, score, and rank ideas
                              ↓
             filmable concepts with hooks and shots
                              ↓
                 publish, measure, and learn
```

## Technologies

- Markdown for portable, human-readable memory
- Git for versioning the public template
- Any AI assistant that supports project instructions and local files
- Instagram Insights as an optional source of manually entered metrics

No Instagram password, API token, scraping tool, or account connection is required.

## Key features

- Ideas grounded in the creator's real life and constraints
- Scoring for specificity, authenticity, audience value, brand fit, and effort
- Publishing-history checks that reduce repetitive concepts
- Structured idea statuses from initial seed through publication
- Analysis of shares, saves, comments, follows, and production effort—not views alone
- Guardrails against fabricated stories, forced trends, and private information

## What I learned

- Useful creative automation needs context, not just a longer prompt.
- Plain-text files can act as transparent, editable agent memory.
- Consistent measurement windows matter more than collecting every possible metric.
- Authenticity improves when the system asks which true detail must be supplied instead of inventing one.
- Public templates and private working data should be separated from the start.

## Screenshots / demo

No real account screenshots are included because they could expose usernames, private analytics, messages, or identifying details.

> **Prompt:** Give me three Reels I can film tomorrow using commute, workout, and study clips. Keep editing under 30 minutes and avoid topics from my last five posts.
>
> **Output:** Ranked concepts with a hook, shot list, on-screen text, why each idea fits, the real detail the creator must add, and an effort estimate.

```text
1. "My day started before most alarms went off"
   Hook: Show the final morning clip first, then rewind.
   Clips: alarm → commute → training detail → breakfast → study.
   Authenticity check: add one true moment that made this morning different.
   Effort: Low
```

## Privacy

Keep personalized working files out of Git. Never store passwords, session cookies, access tokens, private messages, raw account exports, or personally identifying information in this repository. Review every staged file and run a secret scanner before publishing.

## License

MIT
