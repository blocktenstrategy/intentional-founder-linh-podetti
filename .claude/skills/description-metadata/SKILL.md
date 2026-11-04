---
name: description-metadata
description: Write the YouTube description, viewer-friendly chapters, pinned comment, tags and UTM links for a Linh Podetti video, with the one live CTA above the fold. Use when the user asks for a description, chapters, tags, a pinned comment, "metadata", or "package this video for upload".
---

# Description and metadata

## Load

`brand-guardrails`, `docs/youtube/description-and-metadata.md`, `templates/description-template.md`, `docs/funnel/cta-registry.md`, `docs/funnel/funnel-map.md` (UTM convention), and the video's `script.md`.

## Process

1. **Line 1:** one-sentence promise matching the title, then the one CTA with its link and UTM.
2. **Next video line.** Name the next video in the same playlist.
3. **Summary:** 2 to 3 sentences. The first sentence answers the title's question in plain words. Use problem keywords naturally.
4. **Chapters:** build from the script's timestamps. Write each as a reason to keep watching, not a label. Start at `0:00`, at least three.
5. **About Linh:** one line using the fact sheet wording. Tenure "nearly 15 years" if mentioned.
6. **Links:** the CTA and the book. Maximum three links.
7. **P.S.:** only if the registry says so (Intentional Year in Nov and Dec).
8. **Hashtags:** three maximum, `#IntentionalFounder` plus two topic tags.
9. **Pinned comment:** the exercise as a question plus the CTA.
10. **Tags:** problem keywords first, "intentional founder" as one tag, not first. Never "Freedom Builder" after the rebrand.
11. **UTM:** `utm_source=youtube&utm_medium=video&utm_campaign=YYYY-MM-DD-slug`.

## Rules

- One CTA. Never two links asking for two actions.
- Chapters use real timestamps from the final cut. If the cut is not final, mark them `[TIME TBC]` and say so.
- No invented numbers, no claims not in the fact sheet.
- Australian/UK spelling. No em dashes.
- If the CTA link is not in the registry, use `[ADD LINK]` and flag it.

## Output

Write `videos/YYYY-MM-DD-slug/description.md` using the template, with the description, the pinned comment, tags and the metadata checklist. Report any placeholders left.
