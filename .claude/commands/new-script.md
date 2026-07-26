---
description: Draft a new long-form video script for The Data Practice
---

Write a full long-form script for The Data Practice.

Topic/video: $ARGUMENTS

If the argument is a number, look it up in `backlog.md` for the title and pillar. If it's a free-text topic, decide which of the five pillars (see `CLAUDE.md`) it belongs to and note that.

Steps:

1. Read `CLAUDE.md` for mission, audience, packaging rules, the script templates, "Content generation process," the ten scripting rules, and the voice/AI-test guidance.
2. Read `scripts/produced/02-what-is-data-management.md` as the voice and structure reference — match its register, pacing, and use of concrete personal examples.
3. Check `backlog.md` to confirm the pillar and purpose of this video, and to avoid duplicating ground already covered by other backlog entries.
4. **Pick a template** from CLAUDE.md's six (state which one and why, one line) — treat it as a structural skeleton only. It governs hook length, section count, and where the framework lands; it never caps how rich the content inside it gets.
5. **Research.** Search the web for real, verifiable facts, numbers, and case studies relevant to this specific topic. Apply "Citing real facts, companies, and cases" from CLAUDE.md: officially concluded, publicly documented cases can and should be named with real numbers — don't default to an anonymised composite when a real, settled case exists.
6. **Ask Aji** whether there's a fresh, specific, vivid personal story, rule, or practice tied to *this* topic. Ask first, every time — don't default to `producer-memory.md`'s existing anecdote bank just because something in it could technically fit; reusing the same handful of stories across videos is exactly the repetition Aji wants avoided. Only fall back to the bank if Aji confirms there's nothing new for this one.
7. **Find one fresh analogy** for this topic specifically — don't just reach for an already-used signature device.
8. Draft the full script in the chosen template's shape, pouring in what steps 5–7 produced. Target ~140 words/minute for the stated runtime (default 15 minutes / ~2,150 words unless the template calls for shorter).
9. Apply all ten scripting rules as you write, not just at review time — especially rule 6 (concrete beats abstract) and rule 9 (momentum into the next video).
10. Where a personal example is needed but step 6 didn't surface anything and it's not already in the anecdote bank, insert a clearly marked placeholder: `[PLACEHOLDER: presenter's own example of ...]` rather than inventing a fake anecdote.
11. Save the draft to `scripts/drafts/<next-available-number>-<slug>.md`, matching the format of the produced reference script (title, status, runtime, thumbnail text, description/tags, playlist, template used, then the timestamped sections).
12. Update the video's row in `backlog.md` status to `Drafted`.

Do not run the full AI-voice test yourself — that's what `/review-script` is for. Just write a strong first draft, built from real material, not a structurally-correct draft built from thin material.
