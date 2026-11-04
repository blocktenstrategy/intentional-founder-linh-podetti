# Thumbnails

How Linh's thumbnails are made. Built from reviewing all 11 current thumbnails on the channel (4 Nov 2026) and matching them to the CTR data in the audit.

Brief template: [templates/thumbnail-brief.md](../../templates/thumbnail-brief.md). Reference review: [thumbnails/reference/analysis.md](../../thumbnails/reference/analysis.md).

## The system in one sentence

**Linh on the right, big and emotional. A single prop that proves the idea on the left. Two or three words of heavy type. One word in burnt orange.**

## The recurring anatomy

| Element | Rule | Seen in |
|---|---|---|
| **Format** | 1280×720, 16:9, under 2 MB | all |
| **Linh** | Right half of the frame, head and shoulders, face fills about 40 to 50% of the height. Eyes to camera or an obvious reaction. | all |
| **Expression** | One emotion, big. Shock (hand over mouth), frustration (hands in hair), worry (hands together), confident (direct, smiling). | "You'll REGRET THIS", "I DO EVERYTHING", "CAN'T KEEP UP?", "My Business runs without me" |
| **Prop** | One concrete object that shows the idea without words: a phone with messages, sticky notes and chat, a laptop dashboard, an exhausted man asleep on papers, a whiteboard sketch, a team in name tags | "TRUST THEM?", "I DO EVERYTHING", "CAN'T KEEP UP?", "WORKING TOO MUCH", "They Act Like CEOs" |
| **Text** | **2 to 3 words**, heavy sans-serif, white, on the left, large enough to read at the size of a phone-feed thumbnail. | all |
| **Accent** | One key word in **burnt orange**, either as a filled label (white text on orange) or as an orange underline bar under the text | all |
| **Serif italic** | An italic serif for the soft word, heavy sans for the hard word | "You'll **REGRET** THIS", "My Business *runs* WITHOUT ME", "*They Act Like* **CEOs**" |
| **Background** | Dark, warm, simple or blurred. A dark gradient behind the text for legibility. | all |

## Four templates (use these)

| Template | When | Look | Example |
|---|---|---|---|
| **A. Emotion + Cost** | Titles that name a cost or a mistake | Linh's reaction face (shock, worry, frustration) + a short question or statement in caps + one orange word | "You'll REGRET THIS", "CAN'T KEEP UP?", "WORKING TOO MUCH" |
| **B. Concept on whiteboard** | A framework or a mental model | Linh beside a whiteboard sketch with 3 to 4 simple icons + "The best ROI", "Not worth it" | "The best ROI", "Not worth it", "THIS REPLACED ME" (AI brain) |
| **C. Proof with the team** | Team, ownership, 100+ team videos | The team in a frame with a prop (name tags) + serif-italic and bold-sans text | "They Act Like CEOs" |
| **D. Story and identity** | Origin and Intentional Founder videos | Linh alone, warm light, a smile or a calm look, text as a statement | "My Business runs WITHOUT ME" |

**Pair thumbnails for pair videos.** "TRUST THEM?" and "DITCH THEM!" share a template: an orange label with white text, a different prop, the same face placement. Use it for A/B pairs and series.

## What worked (the evidence)

| Video | Thumbnail | CTR |
|---|---|---|
| 4 Hidden Costs | "Not worth it" (whiteboard icons) | **3.82%** |
| Costly Mistake | "WORKING TOO MUCH" (man asleep on paperwork) | **3.48%** |
| Is an expense worth it | "The best ROI" (whiteboard sketch) | 2.16% |
| 5 Delegation Steps | "I DO EVERYTHING" (frustration) | 1.87% |
| Brutal Truth | "CAN'T KEEP UP?" (worried) | 1.87% |
| Don't Hire More People | "You'll REGRET THIS" (shock) | 1.80% |

**Read:** the two highest CTR thumbnails both name a **cost** in two or three words ("Not worth it", "WORKING TOO MUCH"). The emotional-face thumbnails without a cost word ("I DO EVERYTHING", "You'll REGRET THIS") sat lower, probably because the words name a feeling but not a price. Small sample, so test, don't assume.

## The Intentional Founder update

The current thumbnails say nothing about the new brand. As the channel rebrands:

1. **Keep the system.** Face right, prop left, 2 to 3 words, one orange word. It is recognisable and it works.
2. **Add the identity through words, not logos.** Use the words "ACCIDENTAL" or "INTENTIONAL" as the orange word in identity videos ("ACCIDENTAL FOUNDER?", "BUILT BY ACCIDENT").
3. **A split device for the identity cluster.** For identity videos only: a split frame, the accidental scene on the left (phone under the table, overflowing calendar) and the intentional scene on the right (Linh at ease). Use sparingly.
4. **Do not add a logo bug to every thumbnail.** It costs space and the face already signals the channel.
5. Introduce the pattern with the W14 video (2 Dec) so it lands with the rename.

## Rules

1. **Max 3 words on the image.** The title carries the detail.
2. **The thumbnail and the title say different things.** Thumbnail: the emotion or the cost. Title: the specific.
3. **One orange word.** More than one word in orange removes the emphasis.
4. **Check it at phone size.** Shrink to 168×94 px. Can you read it? Can you see the face? If not, enlarge.
5. **One focal prop.** Two props is clutter.
6. **No stock-photo feel.** Use real objects from Linh's world (a phone with a real-looking chat, a real whiteboard, a real team).
7. **Show the expression the script earns.** A shocked face needs a regret story. Do not fake it.
8. **Mismatch kills retention.** The hook must confirm the thumbnail within 10 seconds.
9. **Readable contrast.** White on dark, or white on orange. Never orange text on a light background.
10. **No fake UI, fake numbers or invented results** on the image.

## Fixed spec (to confirm with the designer)

| Item | Value |
|---|---|
| Size | 1280×720 px, JPG or PNG, under 2 MB |
| Accent colour | Burnt orange, close to `#C8502A` (**estimate from the live thumbnails. Sample the real hex from the source files.** [Open question 9](../OPEN-QUESTIONS.md)) |
| Text | Heavy sans-serif caps (white) + italic serif (soft word) |
| Text zone | Left 45% of the frame, with a dark gradient behind |
| Face zone | Right 50% of the frame |
| Safe margin | 5% on all sides. The duration badge covers the bottom-right corner. Keep the face and key words out of it. |

## Process

1. Write the brief with the `thumbnail-brief` skill (3 concepts: A, B and one wildcard).
2. Choose one. Shoot the expression during filming, not after.
3. Design, then run the phone-size test.
4. Upload as thumbnail A. Keep concept 2 ready as the A/B or swap after 48 to 72 hours if CTR is under 2%.
5. Log the result in the video folder and the [analytics review](../process/analytics-review.md).

## Common mistakes to fix

| Mistake | Where | Fix |
|---|---|---|
| Two text styles with no rule (orange label vs underline bar) | Mixed across videos | Pick the label for questions and A/B pairs, the underline for statements. Document it in the brief. |
| Text names a feeling, not a cost | "You'll REGRET THIS" | Name the cost: "REGRET THIS?" with the cost in the title |
| Words that need the title to make sense | "The best ROI" | Add the object: "BEST ROI?" with a cost icon |
| A thumbnail promising a result the video delivers late | "Costly Mistake" | Match the hook to the thumbnail by second 10 |
