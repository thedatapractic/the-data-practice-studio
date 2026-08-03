---
description: The weekly production run — orchestrates Linda, Torch, and Dan to produce and self-review a script
---

The weekly production run. The main session acts as the **studio director** and runs the three agents in sequence. Runs unattended (scheduled), so be conservative about anything needing Aji's judgement — when in doubt, propose rather than commit.

Read `CLAUDE.md` first (the studio, the stable-vs-adjustable rule, the learning system).

Steps:

1. **Linda — research and brief.** Invoke the `linda` agent to scan the space, pick this week's video (default to the next `New` backlog item unless research surfaces a materially stronger angle; a genuinely new topic is added to `backlog.md` as `Proposed — awaiting Aji's approval`, not drafted this run), and write `videos/<slug>/brief.md`.
2. **Torch — draft.** Invoke the `torch` agent with Linda's brief. Torch chooses the best-fit template from `templates/`, writes the full script to `videos/<slug>/draft.md`, and states the template choice at the top.
3. **Dan — assess.** Invoke the `dan` agent to review the draft against the checklist and write `videos/<slug>/assessment.md` with prioritised fixes and a verdict.
4. **Torch — one revision pass.** Invoke `torch` again to apply Dan's fixes that can be applied automatically, leaving `[PLACEHOLDER: ...]` for anything only Aji can supply. Do not loop endlessly — one pass, then stop.
5. **Learning.** Ensure each agent recorded any lesson from this run in its own memory, and add cross-agent lessons to `memory/cross-agent-lessons.md` where relevant.
6. **Log the run** in `production-log.md`: date, topic, research evidence, template chosen, Dan's verdict, status. Update the video's row in `backlog.md` to `Drafted`.
7. **Notify Aji** with a single PushNotification, under 200 characters, no markdown: lead with the title and the one thing needing a decision, e.g. `Studio: drafted "<title>" — Dan says one more pass, 2 placeholders need you. Ready to review.`

Do not mark anything `Reviewed`, `Filmed`, or `Published` — those require Aji. Do not commit or push unless Aji has asked for it.
