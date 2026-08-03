# Operating guide

How to run this studio week to week. Written 2026-08-03, at the end of the session that built it, so nothing important is left living only in a chat window.

If you are returning to this project after a break, **read this file first**, then `CLAUDE.md`.

---

## What this is

A three-agent content studio. Each agent has its own definition in `.claude/agents/` and its own memory in `memory/`.

- **Linda** researches, curates the backlog, and writes the video brief. She runs unattended every week.
- **Torch** writes the script from Linda's brief. **He never starts a script without you.**
- **Dan** reviews the draft independently against a checklist and returns specific fixes. He does not rewrite.

Work moves between them as files, so every stage is inspectable and you can pick up mid-way:

```
videos/<slug>/brief.md  →  draft.md  →  assessment.md  →  final.md
        (Linda)            (Torch)        (Dan)          (yours)
```

---

## The weekly rhythm

**Unattended, every week: Linda only.** She researches new topics and adds them marked as hers, reassesses every backlog item for whether it is still worth making and what its strongest title is now, reorders on relevance and sequencing, logs it all to `production-log.md`, and recommends what to script next.

**She does not trigger scripting.** Her output is a recommendation for you.

**Torch writes nothing unattended.** The one exception is finishing a draft you have already worked on together, and only where he can get it to a full Dan pass using material already in the project. The moment it needs a decision from you, a story that is not in the approved bank, or a placeholder filled, he stops and says so. **A notification is the correct outcome, not a failure.**

Run it with `/weekly-production`.

---

## Producing one video

Budget **60 to 90 minutes of your time**, spread across these steps.

1. **`/research <topic or backlog number>`** — Linda produces `videos/<slug>/brief.md`: the topic, the purpose in one sentence, the angle, why it will perform, the audience it serves, and what must be included. **Read this and correct it before going further.** A wrong brief costs far more later than it does now.
2. **`/new-script <slug>`** — Torch drafts to the brief, picks one of the five templates, and states the template and the target audience at the top. This is the step to sit with, because it is where your judgement and your stories go in.
3. **`/review-script <slug>`** — Dan assesses against the full checklist and writes `assessment.md` with prioritised fixes and a verdict. Read his verdict before you read the script again; he is often right about the hook.
4. **Torch applies the fixes**, one pass, not a loop.
5. **Your edit.** Rewrite it in your own voice and rhythm. This is not optional polish, it is the step that makes the video yours, and it is also the raw material for step 6.
6. **`/learn-from-final <slug>`** — the most important command in the project. It diffs your final against the agent draft, works out what you changed and why, and writes it into `voice-profile.md` and the agents' memory. **Skip this and next month costs the same as this month.** Do it and the gap between their draft and your final shrinks every time.

---

## What they may and may not do without you

**They may:** research, add and retitle backlog items that are not yet produced, reorder the backlog, draft briefs, review, and finish a draft that can reach a Dan pass on existing material.

**They may not:** start a new script, retitle anything already produced, invent an anecdote or a statistic, fill a placeholder, mark anything Reviewed, Filmed or Published, or publish or send anything outside this project.

**When you say "remember":** it goes to the relevant `memory/` file, never to the constitution. If a note would actually change the rules, they must say so and ask you to confirm.

---

## Where everything lives

**The constitution, which changes only when you explicitly say so:**
- `CLAUDE.md` — mission, audiences, subject areas, runtime, the hook rule, voice rules, cutting discipline, creativity, domain expertise, and what the weekly routine may do
- `.claude/agents/` — the three agent definitions
- `templates/` — the five templates, one per file
- `domain-knowledge.md` — the field's verbs, disciplines, roles, quality dimensions and distinctions
- `voice-profile.md` — how you actually write, derived from your own edits

**The adjustable layer, which grows continuously:**
- `memory/linda.md`, `memory/torch.md`, `memory/dan.md` — each agent's own lessons
- `memory/cross-agent-lessons.md` — lessons affecting more than one, which they copy into their own memory
- `backlog.md`, `audience-map.md`, `production-log.md`

**Reference:** `presenter-background.md` (your career and story material), `producer-persona.md` (Torch's voice).

---

## Known issues, honestly

1. **The agents have never run as real subagents.** Everything built and "run" on 2026-08-03 was driven by hand in a chat, with full context in the room. A real subagent starts cold and reads only what its file lists. **Test the full pipeline once on a video that does not matter before trusting it on one that does.**
2. **Cross-references rot.** Two defects were found in Torch's brief during the final review of the day, both introduced by edits made hours earlier: he pointed at a superseded script as the voice reference, and listed two templates that no longer exist. Both would have degraded the next script. **After any structural change, check that every file path an agent is told to read still exists and is still current.**
3. **Two homes for scripts.** `scripts/drafts/` and `scripts/produced/` are legacy; `videos/<slug>/` is current. `scripts/produced/02-what-is-data-management.md` is marked superseded but still present. **Retire `scripts/` once every pre-process video has been rebuilt.**
4. **`CLAUDE.md` is long** (about 3,600 words) and every agent loads it on every task. When adding a rule, check whether it supersedes an existing one rather than sitting beside it.
5. **`memory/torch.md` is over 2,000 words** with no consolidation process. Prune it periodically.
6. **Dan's checklist is eleven items**, long enough that a shallow pass is possible. He passed one script on voice and you then made about forty edits. Treat his "pass" on voice as weaker evidence than his "fail".
7. **`audience-map.md` duplicates the backlog list.** When Linda retitles, both must be updated or they drift.
8. **The backlog was renumbered on 2026-08-03.** Older entries in `production-log.md` and in memory use the old numbering, where Video 1 was the data-manager video and Video 2 was the data management flagship.

---

## Scheduling: the honest constraint

**Nothing currently schedules the weekly run.** `/weekly-production` exists as a command, and memory says "Mondays, time TBC", but no scheduler fires it.

If you schedule it as a task on this machine, **it only runs when this machine is on and awake.** A laptop that is shut on Monday morning does not run Monday's routine. If you want it to fire regardless of your machine, it has to live somewhere that is not your laptop. Decide which you want rather than assuming it is handled.

---

## Monthly maintenance

- Prune `memory/torch.md`: merge duplicates, drop anything now in the constitution.
- Check every file path in the three agent definitions still resolves.
- Reconcile `audience-map.md` against `backlog.md`.
- Re-read the balance section of `audience-map.md` and check the library has not drifted to one audience.
- Ask whether any rule added that month has quietly superseded an older one in `CLAUDE.md`.
