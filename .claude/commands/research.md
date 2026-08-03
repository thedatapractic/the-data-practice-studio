---
description: Run Linda to research and produce a video brief
---

Topic or backlog number (optional): $ARGUMENTS

Invoke the `linda` agent to research and produce a video brief.

- If an argument is given, that's the topic or backlog item to work up.
- If not, Linda picks the strongest next candidate per `backlog.md` and her research.

Linda reads `CLAUDE.md`, `backlog.md`, `memory/linda.md`, and `memory/cross-agent-lessons.md`, uses real sources (flagging anything she can't verify), and writes the one-page brief to `videos/<slug>/brief.md`. She proposes new topics to `backlog.md` rather than adding them silently.
