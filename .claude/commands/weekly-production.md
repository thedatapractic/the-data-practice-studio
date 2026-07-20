---
description: Torch's weekly production run — trend scan, topic pick, full script draft, self-review, notify
---

This is Torch's weekly production run. Runs unattended (scheduled), so be conservative about anything that needs Aji's judgment — when in doubt, propose rather than commit.

Steps:

1. Read `producer-persona.md`, `CLAUDE.md`, `producer-memory.md`, `production-log.md`, and `backlog.md` in full before doing anything else.
2. **Trend scan:** search for what's currently trending or newsworthy in data management, data governance, analytics, data careers, and AI-and-data — last 7–14 days. Look for: news stories (breaches, fines, regulation changes), search-trend shifts, recurring questions/pain points visible in forums or comments-adjacent sources. Note anything that could sharpen the hook of an already-planned video, and anything genuinely new worth a future video.
3. **Pick this week's video:**
   - Default to the next `New` item in `backlog.md`, following the existing pillar-rotation order.
   - If the trend scan surfaces a materially stronger angle or hook for that same topic, use it — this is Torch's call to make alone (log the reasoning).
   - If the trend scan surfaces a genuinely new topic not on the backlog, do **not** draft it this run. Instead add it to `backlog.md` as a new row with status `Proposed — awaiting Aji's approval`, with one line on why it's worth considering. Proceed with the default backlog pick instead.
4. **Draft the full script** for the chosen topic, following the same process as `/new-script` (standard structure, ten scripting rules, personal-example placeholders where needed — never invent an anecdote not already in `producer-memory.md`'s approved bank or `source/` material).
5. **Self-review** the draft using the same process as `/review-script` (ten rules, AI-voice test, runtime check). Fix what can be fixed automatically; leave a placeholder list for anything that needs Aji.
6. **Log the run** in `production-log.md`: date, topic chosen, trend evidence considered, reasoning, and current status. Update the video's row in `backlog.md` to `Drafted`.
7. **Update `producer-memory.md`** if this run revealed anything worth remembering going forward (e.g. a trend pattern, a pillar gap).
8. **Commit and push** all changes (drafts, backlog, log, memory) to the repo with a clear commit message, e.g. `Weekly production run: draft "<title>"`.
9. **Notify Aji** with a single PushNotification: lead with the video title and one thing that needs a decision, e.g. `Torch: drafted "<title>" — 2 placeholders need your input + 1 new topic proposed. Ready to review.` Keep it under 200 characters, no markdown.

Do not mark anything as `Reviewed`, `Filmed`, or `Published` — those states require Aji.
