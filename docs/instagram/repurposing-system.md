# Repurposing system: one video becomes a week of Instagram

Every YouTube video produces an **Instagram pack**. Build it the same week the video is scripted so the belief and the language match.

## The pack (per video)

| # | Asset | Source in the script | Length |
|---|---|---|---|
| 1 | **Hook reel** | The hook, cut tight | 20 to 40 s |
| 2 | **Lesson reel** | The single strongest lesson or story | 45 to 75 s |
| 3 | **Carousel** | The lessons or the recap, one per slide | 6 to 8 slides |
| 4 | **Quote or number image** | One line from a team member or a number | 1 image |
| 5 | **Story set** | A poll, a question, the exercise | 3 to 5 frames |
| 6 | **Caption copy** | Atomic essay (150 to 200 words) | |

## Mapping from the sample script

For [How My Team Actually Uses AI](../../examples/2026-11-04-ai-team-lessons/script.md):

| Asset | Content |
|---|---|
| Hook reel | "While I was driving I asked my AI assistant which dentist I went to last week..." then "and I didn't open an app" |
| Lesson reel | Lesson 1: the finance lead who saves about 17 hours a month. Land on "the biggest benefit wasn't the time. It was her stress." |
| Carousel | "5 lessons from my team's AI huddle", one lesson per slide, last slide the exercise |
| Quote image | "AI is only as good as the data you give it. Verify three times." |
| Stories | Poll: "Do you have one repeated weekly job you'd hand to AI?" Question box: "What's yours?" |
| Caption | An atomic essay on "AI as a direct report, not a magic button" |

## Carousel structure (6 to 8 slides)

| Slide | Job | Rule |
|---|---|---|
| 1 | **Hook** | The title or cost line. 8 words max. Large type. |
| 2 | The problem or the moment | A scene, one sentence |
| 3 to 6 | One point per slide | One idea, one example, no paragraphs |
| 7 | The exercise or the takeaway | Something to do today |
| 8 | **The ask** | "Count your free years. Link in bio." (from the registry) |

Design: same type system and orange accent as the thumbnails ([thumbnails.md](../youtube/thumbnails.md)), a photo of Linh on slide 1 or 8, plain background elsewhere.

## Reel structure

| Second | Do |
|---|---|
| 0 to 2 | The hook on screen **and** spoken. A moment or a cost. |
| 2 to 10 | The setup, in one breath |
| 10 to 40 | One point with one example |
| Last 5 | The line that wraps it. Then the ask. |

Captions on, always. Large type. Cut dead air. The belief is **one** idea.

## Atomic essay (caption copy)

150 to 200 words. One belief. Written to be read as a post on its own.

1. First line: the hook (a moment or a cost)
2. The belief, flipped
3. One example (named, specific)
4. What it cost
5. One step to take today
6. The ask

The `belief-engineering` skill (if installed) is built for this. Otherwise the `instagram-repurpose` skill follows the same structure.

## Calendar of the pack

| Day | Post | |
|---|---|---|
| Wed (video day) | Hook reel + stories ("new video") | |
| Thu | Carousel | |
| Sat | Lesson reel | |
| Mon | Quote or number image + story poll | |
| Wed (next video) | Next pack | |

## Checklist

- [ ] One belief for the whole pack
- [ ] Facts match the fact sheet
- [ ] One ask per asset, from the registry
- [ ] Captions on every reel
- [ ] No team member featured without permission
- [ ] UTM on the link in bio for the week (or story link sticker)
- [ ] Logged in `videos/<video>/instagram.md`

## Folder

Save each pack at `videos/YYYY-MM-DD-slug/instagram.md` using [templates/instagram-carousel.md](../../templates/instagram-carousel.md) and [templates/instagram-reel.md](../../templates/instagram-reel.md).
