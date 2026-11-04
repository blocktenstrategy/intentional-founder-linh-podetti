---
name: analytics-review
description: Read a YouTube Studio export or pasted numbers for Linh Podetti's channel, compare each video to the previous three and the audit baseline, and return what is winning, where viewers leave and the three actions to take next, plus Instagram notes if supplied. Use when the user shares analytics, a CSV, a screenshot of numbers, or asks "how did the video do", "what should we change", "weekly or monthly review".
---

# Analytics review

## Load

`docs/process/analytics-review.md` (metrics, decision rules, the scoreboard), `docs/strategy/channel-audit-findings.md` (the baseline), `docs/strategy/roadmap.md`, `docs/youtube/thumbnails.md`, `brand-guardrails`.

## Inputs

A Studio export (CSV or table), a screenshot or pasted numbers. Ideally: impressions, CTR, views, average view duration, % viewed, subscribers, traffic sources, and the retention cliff time per video.

## Process

1. **Parse the data.** State which videos and which date window. Flag missing columns.
2. **Join to the roadmap:** cluster, length, title pattern, thumbnail template, CTA.
3. **Compare each video** to the previous three and to the audit baseline (CTR 2.33% overall, cost titles 3.5% to 3.8%, delegation 1.8% to 1.9%, average view 30 to 131 s).
4. **Diagnose using the decision rules:**
   - CTR under 2% at 72 hours: thumbnail then title
   - Average view under 60 s: rewrite the first 60 seconds
   - Watch time up and subs flat: move the ask after a payoff
   - Subs per 1K views up: more of that cluster
5. **Check the retention graph** if given. A cliff between 0:45 and 1:10 means the intro or a pitch.
6. **Check traffic sources.** Outside spikes leave early. Do not read a spike as a win.
7. **Check the CTA:** clicks per 1,000 views, if tracked.
8. **Instagram:** if numbers are supplied, review shares, saves, profile visits and sign-ups by post.
9. **Choose three actions**, ranked by impact. Only one change to packaging or format at a time.

## Rules

- **Small sample.** The channel has about 52 subscribers and 11 videos. Say "direction, not proof" and avoid certainty.
- Never judge before day 7 for a video, and note the age of each.
- Do not compare against large channels. Compare to the previous three videos.
- Quote numbers exactly as given. If something is missing, say so.
- Update the scoreboard in `docs/process/analytics-review.md` only when the user asks.

## Output

```
WINDOW: dates · videos: N

WINNING
- ...

LEAKING
- ... (where, how much)

BY VIDEO
| Video | CTR | Avg view | % | Subs | vs prev 3 | Diagnosis |

THREE ACTIONS
1. ... (why, owner)
2. ...
3. ...

NEXT TEST: one change, how to measure.
QUESTIONS: ...
```

Save as `videos/<video>/results.md` or `docs/process/` notes if asked.
