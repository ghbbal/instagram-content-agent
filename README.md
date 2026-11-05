# Instagram Content System

A privacy-safe, Markdown-based workflow for researching, testing, publishing, and improving authentic Instagram Reels.

The system separates three jobs that are often blurred together:

1. **Content Intelligence** finds evidence-backed audience questions, current conversations, competitor patterns, seasonal timing, and content gaps.
2. **Trial Reel Creative** turns suitable opportunities into quick, low-risk tests—usually simple talking-head videos designed to test a hook, question, or audience tension.
3. **Main Account Creative** develops stronger original, story-led, personality-led, visual, or recurring-series concepts that build a recognizable creator identity.

This public repository is a reusable template. Personal profile details, account information, schedules, private analytics, partnership terms, and unpublished creator data are intentionally excluded.

## The three agents

### Content Intelligence Agent

This role turns current evidence into a focused creative brief. It researches audience questions, competitor patterns, seasonal timing, repeated conversations, and gaps without copying another creator's execution.

Its output is a short list of evidence-backed opportunities. Each receives an ID such as `O-YYYYMMDD-01`, a best-fit publishing lane, a clear hypothesis, and any risks or missing facts. Observed facts stay separate from interpretation and speculation.

### Instagram Content Agent — Trial Reels

This role develops quick, low-risk tests—usually simple seated or talking-head videos that can be filmed with minimal setup. Each Trial Reel isolates a hook, question, misconception, or audience tension so its result is useful even when the video does not become a winner.

It also owns the publishing history and records consistent performance measurements. Trial Reel evidence can inform stronger creative work, but it does not automatically justify posting the same treatment to the main account.

### Main Account Creative Agent

This role develops the more original concepts intended to strengthen the creator's recognizable identity. It favors real stories, personality, visible action, meaningful stakes, transformation, collaboration, investigations, challenges, and repeatable series.

It selects the strongest realistic concept for the day and turns it into an exact hook, story structure, practical shot list, filming order, editing direction, and privacy check. It also uses performance evidence to create meaningful variations without repeating the original.

## Why three roles?

A trend is not automatically a concept, and a successful low-effort test is not automatically a strong main-account post.

Separating research, Trial Reels, and main-account creative keeps each decision honest:

- research must cite observable evidence;
- Trial Reels test one clear hypothesis with minimal production;
- main-account concepts must earn their place through originality, visual action, story, personality, or series potential;
- measured results feed the next round of research and creative decisions.

## How it works

```text
current evidence + creator context + performance history
                         ↓
             evidence-backed opportunity ID
                         ↓
          classify: Trial Reel or main account
                   ↙                 ↘
       quick hypothesis test    stronger creative concept
                   ↘                 ↙
               publish and measure
                         ↓
                update what we know
```

Each research opportunity receives an ID such as `O-YYYYMMDD-01`. That ID stays attached to the idea, filming plan, published Reel, and performance record so the system can learn which hypotheses actually worked.

## Lane classification

Use the **Trial Reel lane** for low-production, fast-to-film talking-head tests.

Use the **main-account lane** for original, story-led, personality-led, challenge, investigation, collaboration, visual-action, and recurring-series concepts.

A Trial Reel can inform a main-account concept, but it should not be copied or promoted automatically. Its evidence should be transformed into a stronger creative treatment.

## Recommended private workspace

Keep personalized working files local and out of the public repository:

```text
AGENTS.md
agents/
  content-intelligence-agent.md
  instagram-content-agent.md
  main-account-creative-agent.md
profile.md
content-pillars.md
content-history.md
idea-bank.md
intelligence/
  intelligence-brief.md
  research-log.md
  source-watchlist.md
main-account/
  creative-brief.md
  idea-pipeline.md
  active-production.md
  road-to-growth.md
  partnership-briefs.md
```

The root instructions should route each request to the appropriate role and define file ownership. History should be appended or narrowly corrected, never overwritten.

## Start

1. Copy `AGENT_PROMPT.md` into your AI assistant's project instructions.
2. Create only the local context files you actually need.
3. Add truthful creator context and clear privacy boundaries.
4. Ask for research, a Trial Reel, or a main-account concept.
5. Log published results at consistent measurement windows.
6. Use opportunity IDs to connect research hypotheses to outcomes.

No Instagram password, API token, scraping tool, or account connection is required. Instagram Insights can be entered manually.

## Example prompts

### Research

- “Find the three strongest evidence-backed opportunities for the next seven days.”
- “Research the questions my audience is asking, but only recommend opportunities that fit my approved content territory.”

### Trial Reels

- “Turn opportunity O-YYYYMMDD-01 into a low-effort talking-head Trial Reel.”
- “Give me three quick tests that each isolate a different hook or audience tension.”

### Main account

- “Give me today's strongest original main-account concept and a realistic filming plan.”
- “Transform this proven audience tension into a visual story instead of repeating the Trial Reel.”

### Performance

- “Log these 24-hour results and preserve the opportunity ID.”
- “Review my recent results and tell me which hypotheses were supported, contradicted, or still uncertain.”

## Core safeguards

- Preserve the creator's authentic voice and real experiences.
- Never fabricate conversations, conflicts, accomplishments, statistics, opinions, or results.
- Separate observed facts from interpretation and speculation.
- Verify time-sensitive claims against current sources.
- Do not copy another creator's wording, script, visual sequence, or distinctive concept.
- Do not expose private schedules, messages, analytics, partnership terms, or people who have not agreed to appear.
- Prefer a few strong recommendations over a long generic list.
- Ask for information only when the missing fact would materially change the result.

## Performance learning

Measure more than views. When available, record shares, saves, comments, follows, non-follower reach, retention, and production effort at consistent time windows.

Useful derived metrics include:

- `follows per 1,000 views = follows ÷ views × 1,000`
- `share rate = shares ÷ views × 100`

Preserve the raw inputs and leave calculations blank when a required input is unavailable. Do not infer private metrics from public engagement.

## Privacy

Keep personalized working files out of Git. Never store passwords, session cookies, access tokens, recovery codes, private messages, raw account exports, precise schedules, or personally identifying information in this repository.

Review every staged file and run a secret scanner before publishing.

## License

MIT
