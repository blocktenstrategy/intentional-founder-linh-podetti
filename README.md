# The Intentional Founder: YouTube & Instagram Playbook

The working repo for the content team behind **Linh Podetti's** YouTube channel and Instagram. It holds the strategy, the script template, the thumbnail system and the Claude skills that make a consistent, on-brand video package quick to produce.

> **The brand:** Linh Podetti is **The Intentional Founder**. She helps founders design the life they want first, then build a business that makes room for it.

## Where things are

| I need to... | Go to |
|---|---|
| Understand the strategy in 10 minutes | [docs/00-start-here.md](docs/00-start-here.md) |
| Write a script | [templates/script-template.md](templates/script-template.md) + [docs/youtube/script-anatomy.md](docs/youtube/script-anatomy.md) |
| See a finished script that follows the template | [examples/2026-11-04-ai-team-lessons/](examples/2026-11-04-ai-team-lessons/) |
| Pick a topic | [docs/strategy/roadmap.md](docs/strategy/roadmap.md) |
| Write a title or hook | [docs/youtube/titles.md](docs/youtube/titles.md), [docs/youtube/hooks-and-retention.md](docs/youtube/hooks-and-retention.md) |
| Brief a thumbnail | [docs/youtube/thumbnails.md](docs/youtube/thumbnails.md) + [templates/thumbnail-brief.md](templates/thumbnail-brief.md) |
| Know what the CTA is this week | [docs/funnel/cta-registry.md](docs/funnel/cta-registry.md) |
| Check a fact about Linh | [docs/brand/fact-sheet.md](docs/brand/fact-sheet.md) |
| Grow Instagram from a video | [docs/instagram/](docs/instagram/) |
| Publish a video | [docs/youtube/publishing-checklist.md](docs/youtube/publishing-checklist.md) |
| Review last month's numbers | [docs/process/analytics-review.md](docs/process/analytics-review.md) |

## How the system works

```
Topic (roadmap) -> Brief -> Title + Thumbnail + Hook -> Script -> QA -> Film -> Publish -> Instagram pack -> Review numbers
```

Every video lives in its own folder under [`videos/`](videos/), named `YYYY-MM-DD-short-slug`. That folder holds the brief, script, thumbnail brief, description and Instagram pack, so anyone on the team can pick up where someone else stopped.

## Working with Claude

This repo ships with Claude Code skills in [`.claude/skills/`](.claude/skills/). Open the repo in Claude Code and ask in plain language, or call a skill by name.

| Skill | Use it to |
|---|---|
| `video-package` | Go from a topic to a full package: titles, thumbnail concepts, script, description, Instagram pack |
| `write-script` | Draft a script in the house template |
| `script-qa` | Audit a script against the checklist before filming |
| `hooks-and-titles` | Generate and gate-test hooks and titles |
| `thumbnail-brief` | Turn a video into 3 thumbnail concepts in the channel's visual system |
| `description-metadata` | Write the description, chapters, pinned comment and tags |
| `topic-validation` | Test a topic idea against the S/A/P gate and the one-belief rule |
| `instagram-repurpose` | Turn a finished video into reels, a carousel and stories |
| `instagram-growth-plan` | Plan a weekly Instagram schedule tied to the funnel |
| `analytics-review` | Read a YouTube Studio export and recommend the next three actions |
| `story-bank` | Log and check the stories and examples already used, so they don't repeat |
| `brand-guardrails` | Apply voice, facts and the Linh Podetti / Outsourcing Angel split (the other skills call it) |

See [CLAUDE.md](CLAUDE.md) for the rules Claude follows in this repo.

## Source material

This repo was built from the channel audit, the brand and content strategy report, the website wireframes and the sample script. Where those sources disagree, the conflict is logged in [docs/OPEN-QUESTIONS.md](docs/OPEN-QUESTIONS.md) and not silently resolved.

## Channels

- YouTube: [Linh Podetti | Founder Freedom](https://www.youtube.com/@FounderFreedomwithLinhPodetti) (planned rename: see [rebrand checklist](docs/strategy/rebrand-checklist.md))
- Instagram: [@linh.podetti](https://www.instagram.com/linh.podetti/)
