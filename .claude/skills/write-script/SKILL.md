---
name: write-script
description: Write a YouTube script for Linh Podetti's channel in the house template: hook, intro, numbered lessons each with a story, quote, own version and exercise, recap and CTA. Use when the user asks to draft, write, outline or restructure a video script, or turns a transcript, huddle recording, notes or topic into a script. Always follows the sample script in examples/.
---

# Write script

## Load first

1. Apply `brand-guardrails`.
2. Read `templates/script-template.md` (the structure).
3. Read `examples/2026-11-04-ai-team-lessons/script.md` and `annotated-breakdown.md` (how it reads).
4. Read `docs/youtube/script-anatomy.md` and `docs/youtube/hooks-and-retention.md`.
5. Read `docs/process/story-bank.md` (do not reuse a story inside 8 weeks).

## Inputs to confirm (ask only for what is missing)

- Topic and roadmap slot
- Source material (transcript, notes, recording). **Only use what is in it.**
- The viewer scene (one real person)
- The CTA (default: `docs/funnel/cta-registry.md`)
- Length (default 8 to 12 minutes, 1,500 to 1,800 words)

## Process

1. **Fill the header.** Titles (3, gated by S/A/P), thumbnail text (3), source, format, belief (logical + emotional), cluster and funnel step, CTA, next video.
2. **Write the hook last or first, then rewrite it last.** Real moment, result, widen, promise. 25 seconds, about 120 words. No welcome, no pitch.
3. **Intro:** "Hey, I'm Linh..." with the brand line, the two camps, why it is credible, "Here are N lessons." About 35 seconds.
4. **Lessons.** Each one has seven beats: action-framed title with timestamp, named person with a before and after and a number, the emotion under the benefit, a direct quote, Linh's own version, a plain synthesis line, "Your exercise:". Include one honest-limit lesson if the source supports it.
5. **Recap:** numbered imperative lines, then a thesis line that uses "intentionally".
6. **CTA:** one ask, an optional soft line only if it fits LP vs OA, a comment question tied to the exercise, the named next video, "See you in the next one."
7. **Cues:** `[ON SCREEN TEXT: ...]` for the line to land, `[B-ROLL: ...]` for visuals. One or two per lesson.
8. **Timestamps** from words at about 160 words per minute.
9. **Count words** and state the estimated length.
10. **Run `script-qa`** and fix failures before returning.

## Hard rules

- Never invent a number, a name, a quote, a result or a timeline. If the source does not say it, write `[CONFIRM WITH LINH: ...]` or drop the line.
- Quotes from team members come only from the source, in their words.
- Linh speaks about herself first. The viewer is invited, never diagnosed.
- No em dashes. Australian/UK spelling. Short sentences. Contractions.
- No channel pitch in the first three minutes.
- Do not add a lesson to hit a count. Fewer, stronger lessons beat more.
- Do not copy phrases from the sample script. Match its structure and voice, not its sentences.

## Output

Write to `videos/YYYY-MM-DD-slug/script.md` if a folder exists, otherwise return the script. After it, show:

```
Words: N · Estimated: M min · Lessons: N
Belief: ...
Open confirms: ...
Brand check: ...
```
