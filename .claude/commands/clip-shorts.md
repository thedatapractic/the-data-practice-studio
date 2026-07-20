---
description: Extract short-form clips from a finished long-form script
---

Extract short-form video clips (Shorts/Reels, 30–90 seconds each, ~70–210 words at 140wpm) from a finished long-form script, per `CLAUDE.md` → "Format".

Source script: $ARGUMENTS

Steps:

1. Read the source script.
2. Identify 3–5 candidate moments that work as standalone clips: the hook, any self-contained story with real stakes (rule 6), any single punchy statistic or reframe (e.g. "data is an asset" type lines), or a concrete rule/checklist a viewer could use immediately. A clip must make sense with zero context from the rest of the video.
3. For each candidate, produce:
   - A short-form title/on-screen hook line (first 1–2 seconds must stop the scroll — same "no greetings" rule as long-form, rule 1)
   - The trimmed script text, lightly edited so it stands alone (add one sentence of context if the original assumed prior setup; cut anything referencing "earlier in this video")
   - A closing line that either delivers a payoff or points to the full long-form video for more ("full breakdown linked/pinned")
   - Suggested on-screen text overlays per the production guide's "cut away from the face" triggers in `CLAUDE.md`-referenced strategy doc (definitions, numbers, lists)
4. Rank the candidates by how strong the opening line is — put the strongest first.
5. Save the output to `scripts/shorts/<source-filename-without-extension>-shorts.md`, creating the `scripts/shorts/` folder if it doesn't exist.

Do not invent new stories or statistics — only repackage what's already in the source script.
