---
name: script-qa
description: Audit a YouTube script for Linh Podetti against the house template, retention rules, brand voice, fact sheet and CTA registry, and return a pass/fail table with exact fixes. Use before a script goes to Linh or to filming, when the user says "check this script", "QA", "review the script", "is this ready", or pastes or points to a script file.
---

# Script QA

Review only. Do not rewrite the whole script. Return findings with line-level fixes. Apply fixes only if the user asks.

## Load

`brand-guardrails` (and the files it lists), `docs/youtube/script-anatomy.md`, `docs/youtube/hooks-and-retention.md`, `docs/process/story-bank.md`, `docs/OPEN-QUESTIONS.md`.

## Checks

| # | Check | Pass when |
|---|---|---|
| 1 | **Hook** | Opens on a person, a moment or a result in line 1. No welcome, no pitch, no definition. Promise by second 25. |
| 2 | **First 60 seconds** | No channel pitch or credential list. Brand line appears once. Title confirmed within 10 seconds. |
| 3 | **Title promise** | The promised thing is delivered in the first minute, not after minute 5 |
| 4 | **S/A/P** | The recommended title passes Specificity, Action and Phone-feed |
| 5 | **Structure** | Header, Hook, Intro, Lessons, Recap, CTA all present. Timestamps present. |
| 6 | **Lessons** | Each has an action-framed title, a named person with a number, an emotional benefit, a quote, Linh's own version, a synthesis line and an exercise |
| 7 | **Honest limit** | At least one place shows what went wrong or what it cost |
| 8 | **One belief** | One logical agreement and one emotion are stated and the lessons serve them |
| 9 | **Disclosure before diagnosis** | Linh names the pattern in herself before describing the viewer. No accusation. |
| 10 | **Facts** | Every number, title and tenure matches `docs/brand/fact-sheet.md` ("nearly 15 years"). Nothing invented. 🟡 items flagged. |
| 11 | **Stories** | None reused inside 8 weeks. All sourced. Anyone named is cleared. |
| 12 | **CTA** | Exactly one primary ask, matching the registry. A comment question and a named next video. No "thanks for watching, subscribe". |
| 13 | **LP vs OA** | No standalone case study. No OA process walkthrough. OA mention is one soft line at most. |
| 14 | **Length** | 1,500 to 1,800 words and 8 to 12 minutes (state the count) |
| 15 | **Voice** | First person, short sentences, contractions, Australian/UK spelling, no em dashes, no hype words, no fear lists |
| 16 | **Recap** | Imperative lines, thesis uses "intentionally" |
| 17 | **Open items** | No unresolved `[CONFIRM WITH LINH]`. List any that remain. |

## How to find the issues

- Count words with a script or by section.
- Search for em dashes, "welcome", "in today's video", "subscribe", "game-changer", "unlock", "supercharge", "leverage".
- Search numbers and compare with the fact sheet.
- Search names against the story bank.

## Output

```
Verdict: READY | READY WITH EDITS | NOT READY
Words: N · Est. M min

| # | Check | Result | Where | Fix |
|---|---|---|---|---|
...

Top three fixes (in order of retention impact):
1. ...
2. ...
3. ...

Open confirms for Linh: ...
Conflicts with OPEN-QUESTIONS: ...
```

**READY** means all checks pass. **READY WITH EDITS** means no fact, belief or CTA failure, only small fixes. **NOT READY** means any failure on 1, 2, 8, 10, 12 or 13.

Name the sample script as the reference when explaining a fix.
