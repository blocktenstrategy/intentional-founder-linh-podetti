---
name: thumbnail-brief
description: Turn a YouTube video into three thumbnail concepts for Linh Podetti's channel using the established visual system (Linh on the right, one prop, 2 to 3 words, one burnt-orange word) and the CTR evidence. Use when the user asks for thumbnail ideas, a thumbnail brief, "what should the thumbnail say", or wants to improve or A/B test a thumbnail.
---

# Thumbnail brief

## Load

`docs/youtube/thumbnails.md` (the system), `thumbnails/reference/analysis.md` (the 11 current thumbnails and CTR), `templates/thumbnail-brief.md`, and `brand-guardrails`.

## Process

1. **Get the facts:** final or recommended title, the hook, the cluster, and the emotion the script earns.
2. **Do not repeat the title.** The title carries the specific. The thumbnail carries the emotion or the cost in 2 to 3 words.
3. **Prefer a cost word.** The two highest CTR thumbnails ("Not worth it" 3.82%, "WORKING TOO MUCH" 3.48%) name a cost. The weaker ones name a feeling only. Treat this as a hypothesis to test.
4. **Pick the template:**
   - A: Emotion + Cost (a cost, mistake or warning)
   - B: Concept on whiteboard (a framework or model)
   - C: Proof with the team (team, ownership, scale)
   - D: Story and identity (origin, Intentional Founder)
   - Split frame (accidental vs intentional, identity videos only)
5. **Write 3 concepts:** the recommended one, an alternative template, and a wildcard that tests a different idea. Each has: template, text (2 to 3 words, caps), the one orange word, optional serif-italic word, Linh's expression (and what in the script earns it), one prop, background, layout.
6. **Check each concept:** phone-size legibility (168×94 px), one orange word, one prop, face and key words clear of the bottom-right badge, no fake UI or invented numbers, the hook can confirm it by second 10.
7. **Add shoot notes:** which expression to film, which prop to bring, which wardrobe.

## Rules

- Max 3 words. One orange word.
- Linh on the right, text on the left over a dark gradient.
- Use real objects from Linh's world. No stock-photo feel.
- Do not promise something the video delivers late.
- For identity videos, use "ACCIDENTAL" or "INTENTIONAL" as the orange word. Do not add a logo bug.
- The orange hex is an estimate until the designer confirms it ([open question 9](../../../docs/OPEN-QUESTIONS.md)). Say "burnt orange", not a hex, in briefs.
- An expression must match the story. Do not ask for a shocked face on a calm video.

## Output

Fill `templates/thumbnail-brief.md`. If a video folder exists, write `videos/YYYY-MM-DD-slug/thumbnail.md`. Then give a short recommendation:

```
Recommended: Concept N because [cost word / clear prop / matches hook].
Test: if CTR < 2% at 72 hours, swap to Concept M.
```
