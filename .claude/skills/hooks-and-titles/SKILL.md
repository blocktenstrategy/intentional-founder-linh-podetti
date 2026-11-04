---
name: hooks-and-titles
description: Generate and gate-test YouTube titles and opening hooks for Linh Podetti's channel using the S/A/P gate, the cost-title evidence from the channel audit and the first-60-seconds rules. Use when the user asks for titles, title ideas, a hook, an opening, "rewrite this title", or wants options to A/B test for a video or slot.
---

# Hooks and titles

## Load

`brand-guardrails`, `docs/youtube/titles.md`, `docs/youtube/hooks-and-retention.md`, `docs/strategy/competitor-playbook.md`, and the roadmap row for the video.

## Titles

1. **Start from the problem keyword**, not the brand. Keywords: delegate, bottleneck, remote team, virtual assistant, automate, doing everything yourself. "Intentional founder" is the identity, never the lead keyword.
2. **Write 8 candidates** across these patterns: cost, first person + business-size number, number + villain, "I stopped" confession, identity question, contrarian, a system you can copy.
3. **Gate each** with S (number, name, result or villain), A (can act tomorrow), P (a tired founder would stop scrolling). Fix a failing title before listing it.
4. **Rank the best three.** Name the one to recommend and why. Prefer a title that names a cost, since cost titles pulled 3.5% to 3.8% CTR against 1.8% to 1.9% for delegation titles (small sample).
5. **Check the promise.** The hook must pay it off in the first minute. If the video cannot, rewrite the title.
6. **Length.** About 60 characters or fewer so it shows in full on mobile.
7. **Never:** "freedom" as the hook word, emojis, clickbait the video cannot deliver, facts not in the fact sheet.

## Hooks

1. **Choose a type:** Moment, Cost, Confession, Contrarian, Number, Villain. Prefer Moment, Cost, Confession.
2. **Write 5 hooks** of about 25 seconds each (about 60 to 120 words including the promise). Each opens with a person, a place, a number or a result.
3. **No** welcome, subscribe, definition or credential list.
4. **Confirm the title by second 10** and open one loop to pay off later.
5. **Gate each hook:** specific first line, title confirmed, loop open, one breath.
6. **Sources:** only moments Linh or the team supplied. If none exist, write the hook with a `[CONFIRM WITH LINH: the real moment]` slot rather than invent a scene.

## Output

```
TITLES
| # | Title | Pattern | S | A | P | Chars | Note |
Recommended: #N because ...

HOOKS
1. [Type] ... (first 25 seconds)
...
Recommended: #N because ...

Promise check: the title is paid off at [time] by [line].
Brand check: ...
```

Pair the winners with a thumbnail by calling `thumbnail-brief`.

## Related (outside this repo, if installed)

`hook-writer` for 20+ hook variations and a template library. Run its output through the gates above.
