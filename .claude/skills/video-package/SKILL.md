---
name: video-package
description: Take one YouTube topic or roadmap slot for Linh Podetti and produce the full package in a new video folder: brief, three titles with gate results, thumbnail concepts, hook options, script, description with chapters and pinned comment, and an Instagram pack. Use when the user says "start the next video", "build the package for [topic or week]", "new video", or gives a roadmap slot or a topic idea and wants everything prepared.
---

# Video package

The orchestrator. It runs the other skills in order and fills a video folder.

## Inputs

A roadmap slot (e.g. "W11") or a topic idea. Optional: source material (recording, transcript, notes), the filming date.

## Steps

1. **Load context.** Apply `brand-guardrails`. Read `docs/strategy/roadmap.md` for the slot, `docs/strategy/content-pillars.md` for the cluster, `docs/process/story-bank.md` for stories.
2. **Validate the topic** with the `topic-validation` skill. If it fails a gate, stop and propose the fix. Do not carry on with a failing topic.
3. **Create the folder** `videos/YYYY-MM-DD-slug/` (the Wednesday date). Copy `templates/video-brief.md` to `brief.md` and fill it.
4. **Titles and hooks** with `hooks-and-titles`: three titles, gated, one recommended, three hook options.
5. **Thumbnails** with `thumbnail-brief`: three concepts in `thumbnail.md`.
6. **Script** with `write-script`: `script.md` from the template. If source material was given, use only what is in it.
7. **QA** with `script-qa`. Fix what fails. Do not hand over a script with open fails.
8. **Description** with `description-metadata`: `description.md` with chapters, pinned comment and tags.
9. **Instagram pack** with `instagram-repurpose`: `instagram.md`.
10. **Story bank.** Propose rows for `docs/process/story-bank.md` with `story-bank`. Do not write them until the script is approved.
11. **Folder README.** Create `README.md` with the status line and the publishing checklist from `docs/youtube/publishing-checklist.md`.
12. **Update** `videos/README.md` index with the new row.

## Rules

- Do the steps in order. Each step uses the output of the one before.
- Never invent facts, numbers, quotes or client results. Missing information becomes `[CONFIRM WITH LINH: ...]`.
- If the slot needs a number from Linh (W15, W22), produce the folder and the brief, mark the script blocked, and list the question.
- If the user gives a transcript or recording notes, quote only what is there and cite the source in the script header.
- Ask at most one question, and only if the topic is missing. Otherwise proceed and state assumptions.

## Output to the user

1. The folder path and the files created
2. The recommended title and thumbnail concept in one line each
3. The belief line and the CTA
4. A list of every `[CONFIRM WITH LINH]` and every open question touched
5. The next action for each person (Linh, designer, editor)

Do not paste the whole script into the reply. Point to the file.
