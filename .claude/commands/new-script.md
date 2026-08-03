---
description: Run Torch to draft a script from a video brief
---

Video (brief path, slug, or backlog number/topic): $ARGUMENTS

Invoke the `torch` agent to draft a full long-form script.

- If a brief already exists at `videos/<slug>/brief.md`, Torch scripts from it.
- If there's no brief yet, run `/research` first (or Linda) so Torch has a topic and a purpose to focus on. Do not have Torch invent the brief himself.

Torch reads `CLAUDE.md`, `producer-persona.md`, the brief, `templates/`, the produced reference script, `memory/torch.md`, and `memory/cross-agent-lessons.md`. He **chooses the best-fit template** (stating which and why at the top), writes the full script to `videos/<slug>/draft.md` following the standard structure and the ten rules, and marks `[PLACEHOLDER: ...]` for any personal example not in the approved anecdotes bank or `source/`. He does not run the AI-voice test himself — that's Dan's job via `/review-script`.
