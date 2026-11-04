---
name: topic-validation
description: Validate a proposed YouTube topic or title for Linh Podetti against the S/A/P gate, the one-belief rule, cluster fit, LP vs Outsourcing Angel separation, competitor evidence and the existing roadmap, and recommend a verdict with a fix. Use when the user proposes a video idea, asks "should we make this", "is this topic good", "where does this fit", or wants to add or reorder a slot on the roadmap.
---

# Topic validation

## Load

`brand-guardrails`, `docs/strategy/roadmap.md`, `docs/strategy/content-pillars.md`, `docs/strategy/competitor-playbook.md`, `docs/strategy/channel-audit-findings.md`, `docs/process/story-bank.md`.

## Checks

| # | Check | Question |
|---|---|---|
| 1 | **Cluster fit** | Which cluster and funnel step (Count it, Free it, Live it)? Does the mix still balance? |
| 2 | **One belief** | What single logical agreement and emotion does it plant toward "Build a successful life, intentionally"? If you need two, split the topic. |
| 3 | **S/A/P** | Does a working title pass Specificity, Action and Phone-feed? Propose a fix if not. |
| 4 | **Evidence** | A search phrase, a competitor breakout (views ÷ subs), or a first-party data point (CTR or retention from the audit)? |
| 5 | **LP vs OA** | Is it why Linh believes it or how she thinks, not OA's process? |
| 6 | **Story available?** | A real story or number from Linh or the team, not used in 8 weeks? |
| 7 | **Hook available?** | A real moment to open on, or a cost to name? |
| 8 | **Overlap** | Does it repeat a published or scheduled video within 4 weeks? |
| 9 | **Dependencies** | Needs a number, a permission or a date from Linh? |
| 10 | **CTA fit** | Is the live CTA a natural next step for this viewer? |

## Verdicts

- **GO:** all checks pass or have clear fixes. Place it in a slot.
- **GO WITH CHANGES:** a title, angle or cluster fix is needed. State the fix.
- **HOLD:** a dependency is missing (story, number, permission). Name it and add it to `docs/OPEN-QUESTIONS.md`.
- **NO:** it is an OA topic, a standalone case study, fails the belief rule, or duplicates a recent video.

## Process

1. Read the idea and any source given.
2. Run every check. Look at the roadmap for overlap and dates.
3. Suggest a better title if the gate fails (S, A or P).
4. Suggest the slot (week and date) and what it should replace or follow.
5. List what is needed from Linh.

## Output

```
Verdict: GO | GO WITH CHANGES | HOLD | NO
Topic: ...
Cluster / step: ...
Belief: [logical] · [emotion]
Suggested title: ... (S _ A _ P _)
Slot: W## [date] · after [video] · before [video]
Evidence: ...
Needs: ...
Why: ...
```

Do not edit the roadmap unless the user approves the slot.

## Related (outside this repo, if installed)

`youtube-topic-validator` for an independent keyword and demand check.
