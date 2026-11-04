# CLAUDE.md

This repo guides the content team for **Linh Podetti**, "The Intentional Founder". Read this file first, then load the skill that fits the task.

## Always do

1. **Use the brand skill first.** Before writing any script, title, caption or description, apply `brand-guardrails`. It points to `docs/brand/`.
2. **Follow the script template.** Scripts use `templates/script-template.md`. `examples/2026-11-04-ai-team-lessons/script.md` is the reference for how it reads.
3. **One belief, one CTA per video.** Each video plants exactly one logical agreement and one emotional agreement toward the umbrella belief. It ends on one primary ask, taken from `docs/funnel/cta-registry.md`.
4. **Use only approved facts.** Numbers, tenure, titles and stories come from `docs/brand/fact-sheet.md`. If a fact is missing, write `[CONFIRM WITH LINH: ...]`. Never invent a statistic, a client result or a quote.
5. **Disclosure before diagnosis.** Linh names the pattern in herself first, then invites the viewer to see themselves in it. Never open by telling the viewer they are the problem.
6. **Open on a person, not a claim.** The first line is a moment, a name or a result, never "Welcome to the channel".
7. **Check the story bank.** Before using an example or a team story, check `docs/process/story-bank.md` and log it after.
8. **Keep Linh's channel separate from Outsourcing Angel's.** See `docs/brand/lp-vs-oa.md`.

## Voice rules

- Write as Linh speaks: first person, plain words, short sentences, contractions.
- Use Australian/UK spelling (summarising, favourite, mum, organise). Dates read "Tue 3 Nov 2026".
- No em dashes. Use a colon, a full stop or a comma. The sample script has none.
- No filler openers ("In today's video", "Welcome back"), no hype words (game-changer, unlock, supercharge, leverage as a verb).
- Every claim a viewer could act on is followed by a concrete step they can do tomorrow.

## Where to look

| Question | File |
|---|---|
| Who is the viewer? | `docs/brand/audience.md` |
| What makes Linh credible? | `docs/brand/edge.md` |
| What is the next step we ask for? | `docs/funnel/funnel-map.md`, `docs/funnel/cta-registry.md` |
| What video is next? | `docs/strategy/roadmap.md` |
| How do thumbnails look? | `docs/youtube/thumbnails.md` |
| How does Instagram support YouTube? | `docs/instagram/strategy.md` |

## Related skills outside this repo

If these are installed in your Claude setup, use them alongside the repo skills. They are complements, never replacements for `brand-guardrails`:

- `copy-scribe-youtube`: full package generator and channel auditor (the framework the audit was built on)
- `hook-writer`: 20+ hook variations for one angle
- `belief-engineering`: atomic essays, reels and carousels built on one belief
- `youtube-topic-validator`: external validation of a topic
- `humanizer`: strip AI-sounding phrasing from a finished draft (run it last, then re-run `script-qa`)

## Conventions

- New video: copy the folder pattern in `videos/README.md`.
- Dates in file names: `YYYY-MM-DD`. Slugs: lowercase, hyphens.
- Do not edit `examples/`. It is a fixed reference. Add new reference scripts as new folders.
- Do not commit video files, raw footage or exported thumbnails. Keep text, briefs and links.
- When sources conflict, add the conflict to `docs/OPEN-QUESTIONS.md` and flag it to the user instead of choosing silently.
