# Linda — Memory (continuous learning)

Linda reads this file at the **start of every task**, and appends to it whenever:
- she corrects herself mid-task,
- Aji corrects her, or
- a correction reaches her from another agent (check `cross-agent-lessons.md`).

Write each lesson as a **dated, one-line rule for next time** ("Do X because Y"), newest at the top of the right section. This file is the *adjustable* layer: it grows continuously. It is **not** the constitution (`CLAUDE.md`, the agent definitions, the templates), which changes only when Aji explicitly asks.

## What makes a topic land
- 2026-08-10 — **A stable reorder (promote a few items, demote a few, leave the rest in relative order) is easier to audit and justify than a full bespoke reshuffle.** When resequencing a long backlog, pick the specific items with a clear trigger (map instruction, decay curve, natural cluster), move only those, and let everything else keep its existing relative order rather than redesigning the whole sequence from scratch. Full reshuffles are harder for Aji to sanity-check and more likely to silently break something that was working.
- 2026-08-10 — **A time-sensitive item left at the bottom of a long backlog effectively becomes evergreen-or-dead.** At one video/week, position 24 is six months away; a regulation's "just took effect" hook does not survive that. Check every item flagged time-sensitive against its actual queue position, not just whether it is flagged at all.
- 2026-08-10 — **Pillar coverage needs the same "named category, zero instances" check as subject coverage.** Subject gaps (Python) were already being watched; a pillar gap (only 2 of 28 videos are pillar-5/identity, against the "1 in 5–6" guidance) was sitting unflagged in plain sight because nobody had counted it. Count every named category on a fixed cadence, not just when something prompts a review.
- 2026-08-10 — **When a beat hasn't been scripted yet but the topic is thematically adjacent to a finished video (e.g. #10, "why nobody trusts your reports," next to Video 1's cost-of-bad-data material), flag the specific figures/analogies already spent as a forward note in the backlog entry**, not just at review time when the draft exists. Cheaper to prevent than to catch later.
- 2026-08-03 — **Two audiences, balanced across the library rather than inside each video.** Students/aspiring professionals and practising professionals. Not every video can serve both well, and forcing it weakens the video; what matters is the balance overall. Every backlog item carries an explicit audience judgement in `audience-map.md`, which I maintain and review weekly. If the library drifts to one audience, say so and propose what to add.
- 2026-08-03 — **The channel is not only for data managers.** Subject areas are **data management, data governance, data analytics, and SQL and Python** for practical data work. Tag every item so gaps are visible. Careers content cuts across all four and is currently how almost the entire student audience is reached, which is itself a risk.
- 2026-08-03 — **Gaps found in the first audience assessment:** Python is named as a subject area and has **zero** videos; data analytics has effectively one. Watch for a named subject area with no coverage; it is the easiest gap to miss because the backlog looks full.
- 2026-08-03 — **Reordering breaks tease chains.** Moving the data-manager video to position 3 left its closing tease pointing at a video that now publishes before it. **Whenever the order changes, check every finished script's closing tease against the new sequence.**
- 2026-08-02 — **Title authority.** I may rewrite the title of any backlog item **not yet produced**. I may **never** retitle anything already produced, because those titles are live and carry the video's search history and links. Where a script exists but the video is not produced, the title also sits inside the script and on the thumbnail, so I **propose** a better title to Aji rather than changing it.
- 2026-08-02 — **Backlog curation is now my weekly job**, and it is the main thing I do unattended: add new topics marked as mine for Aji's review, reassess every existing item for whether it is still worth making and what its strongest title is now, reorder on relevance and sequencing, check for beat collisions with finished scripts, log it, and recommend what to script next. I never trigger scripting; Torch does not write without Aji.
- 2026-08-02 — **Check every new brief for beat collisions against scripts already final.** Video 1 shared three beats with Video 2: the disputed word "active" in the hook, the vaccination-dates story, and "treat every record as if it belonged to your own mother". Consecutive videos drawing on the same examples makes the channel look like it has a thin bank of stories. The fix that worked: the later-written video moves, a shared story survives only as an explicit callback plus genuinely new material, and a signature line belongs to one video at a time.
- 2026-08-02 — Briefs must fit a **7–8 minute standalone video**. Scope the purpose to one question the video can fully answer in that time, and never propose an angle that depends on the viewer knowing a framework or book. If a topic needs more, split it into two videos.
- 2026-08-02 — For evergreen "what is X" foundations topics, keep the evergreen framing primary and add **one AI-era beat** (e.g. bad data → AI hallucination/drift) as seasoning. It adds 2026 urgency without narrowing the video's shelf life.

## Angles and hooks that worked or flopped
- 2026-08-02 — Refresh stale headline economics to a **current, per-organisation figure** (e.g. ~$12.9M/yr, Gartner) instead of a dated global "$3 trillion". A per-company number lands harder for a single viewer and reads as more credible.

## Research sources and signals worth reusing
_(none yet)_

## Corrections to remember
_(none yet)_
