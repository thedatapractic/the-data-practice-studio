---
description: The weekly run — Linda curates the backlog, and Torch finishes an in-progress draft only if it can be completed without Aji
---

The weekly routine. It runs unattended, so read `CLAUDE.md` first, in particular **"What the weekly routine may and may not do"**, and stay inside it.

**This routine does not normally produce a script.** Its job is to keep the backlog live and ready so that when Aji sits down with Torch, the thinking is already done. Writing a new script without her produces work that gets rewritten, so it is not attempted.

## Step 1 — Linda curates the backlog (every week, always)

Invoke the `linda` agent to:

1. **Research new topics.** Look at what is working in the data space now, and what questions and pain points are recurring. Add promising topics to `backlog.md`, each marked **`Added by Linda — for Aji's review`** with one line on why it is worth making, so Aji can always see what she did not choose herself.
2. **Reassess every existing item.** For each, ask whether it is still worth making, whether the ground has shifted under it, and **what the strongest title would be now**. Update titles where there is a clearly better one, and note the previous title so nothing is lost silently.
3. **Reorder where it helps.** Re-sequence on relevance for the coming weeks and on how videos set each other up: if one video obviously earns its audience from another, put them together in the right order and say so.
4. **Log what changed** in `production-log.md`: added, retitled, reordered, dropped, and why.

## Step 2 — Is there an in-progress draft, and is the slot due?

Look for a video in `videos/<slug>/` with a draft that Aji and Torch have already worked on substantially together and that is not yet finished.

**If there is none:** stop. Go to step 4.

**If there is one:** invoke `dan` to assess it against the full checklist, then decide honestly:

- **Can it be brought to a state that passes Dan's checklist using only what is already in the project** — the brief, `voice-profile.md`, `domain-knowledge.md`, `presenter-background.md`, and the approved anecdotes in `memory/torch.md`? If yes, invoke `torch` to apply the fixes, then `dan` once more to confirm it passes. Update the status and log it.
- **Does finishing it need anything from Aji** — a decision she has not made, a story that is not in the approved bank, a `[PLACEHOLDER: ...]`, or anything Dan flags as hers? Then **stop and notify her.** Do not guess, do not invent, and do not fill a placeholder to get it over the line. Stopping here is the correct outcome.

## Step 3 — Never do these unattended

- Start a new script.
- Mark anything `Reviewed`, `Filmed` or `Published`.
- Invent an anecdote, a statistic or a personal example.
- Publish, post or send anything outside this project.

## Step 4 — Report to Aji

Send a single PushNotification, under 200 characters, no markdown. Lead with the recommendation, not the process. For example:

- `Linda: backlog updated, 2 new topics + 3 retitled. Suggest "<title>" next — ready when you are.`
- `Torch: finished "<title>", passes Dan. Backlog updated. Ready for your read-aloud.`
- `Torch: "<title>" needs your input to finish — 2 placeholders only you can fill. Backlog updated.`

Then write the fuller version to `production-log.md`: what Linda changed, what Torch did or did not do and why, and the recommended next item with the reason.
