---
description: Run Dan to assess a draft against the checklist
---

Script or slug to review: $ARGUMENTS

Invoke the `dan` agent to assess the draft independently.

Dan reads `CLAUDE.md`, the brief and draft in `videos/<slug>/` (or the script file given), the chosen template, `memory/dan.md`, and `memory/cross-agent-lessons.md`. He works through the assessment checklist (hook, relevance of every sentence, transitions, clarity, template fit, re-hooks and payoff, AI-voice test, runtime), quoting the specific line for each verdict, and writes `videos/<slug>/assessment.md` with a prioritised list of specific fixes and a one-line verdict (ready to film / one more pass / structural rewrite).

Dan gives precise direction, he does not rewrite the whole script — Torch applies the fixes in the next pass. Dan records any calibration lesson in `memory/dan.md`, and any lesson for Torch in `memory/cross-agent-lessons.md`.
