---
description: Collaboratively build or rework a script with Aji, one section at a time
---

Build or rework a script for The Data Practice **with** Aji, not **for** Aji — this is the section-by-section counterpart to `/new-script`, which drafts a full script in one pass. Use this whenever Aji wants to co-write, or wants an existing draft sent back into the pipeline for targeted rework instead of a full regenerate.

Target: $ARGUMENTS (a topic/backlog number for a fresh build, or a path to an existing script file for a rework)

**The one rule that makes this different from `/new-script`: never produce more than one section's worth of content before stopping and waiting for Aji's response.** Propose, then stop. Do not draft the hook and the credibility beat and part 1 in the same turn "to save time" — that defeats the entire point of this command.

## Determine mode

- **Fresh build:** $ARGUMENTS is a topic or backlog number with no existing draft. Go to "Setup phase."
- **Rework:** $ARGUMENTS is a path to an existing script. Read it in full, identify its template and section boundaries, and go to "Rework phase" instead of drafting from zero.

## Setup phase (fresh build only — do this once, up front)

1. Read `CLAUDE.md` (script templates, "Content generation process," "Citing real facts," the ten rules) and `backlog.md`/`producer-memory.md`/`production-log.md` for context, same as `/new-script`.
2. Research real, verifiable facts and case studies for this topic (per "Citing real facts, companies, and cases" — name real, settled cases where they exist).
3. **Agree the purpose sentence before anything else** (CLAUDE.md → "One purpose per video") — propose one sentence saying what this video exists to make the viewer understand, and get Aji to confirm or sharpen it. Everything proposed afterwards gets justified against it, and in rework mode it's the standard any existing section has to survive. Then propose a template (state which of the six and why) and a rough section outline — hook angle, credibility angle, what each body section will cover, the landing's core takeaway — as a **short outline, not prose**. Ask Aji to approve or redirect the outline before any section gets written in full. This is the first stop-and-wait point.
4. Once the outline's approved, ask explicitly whether Aji has a fresh, specific personal story for this topic — ask first, don't default to `producer-memory.md`'s bank just because something in it could fit; repeating the same stories across videos is exactly what Aji wants avoided. Stop and wait.
5. Only after outline + material are settled, move into "Walk the sections."

## Rework phase (existing draft)

1. Read the full existing draft and note its declared template, section boundaries, and current status.
2. Do **not** propose a full rewrite. Instead, go section by section through the existing structure (hook, credibility, each body section, landing, sign-off) and for each one:
   - Give a one-line honest read: what's working, what's weak, referencing the ten rules / AI-voice test / raw-material check from CLAUDE.md where relevant — and whether it survives the purpose sentence agreed in step 1. A section that's well-written but doesn't serve the purpose is a cut, not a keep.
   - If it's weak, propose a specific, concrete fix or alternative — not "this needs work," an actual suggested replacement or a pointed question (e.g. "this hook uses a composite — is there a real, settled case we could name instead?").
   - If it's already strong, say so and move on — don't manufacture a change for the sake of touching every section.
   - **Stop after each section** and wait for Aji to approve, redirect, or supply their own material before touching the next one.
3. Sections Aji doesn't ask to change stay exactly as they are. This is targeted rework, not a silent full regenerate.

## Walk the sections (both modes)

For each section, in order:
1. Propose the content for that section only — a full draft of that section, or (for the hook, or any section with a real creative fork) two short alternative angles when there's a genuine choice worth Aji picking between, not just one to rubber-stamp.
2. **Run the sentence-chain check on your own draft before Aji sees it** (CLAUDE.md → "The sentence-chain check"). Read it one sentence at a time: resolve every pronoun and demonstrative, test each join with "and therefore" rather than "and also," check nothing steps out of a scene to make a general point and steps back, check every number is anchored to something the viewer just saw, and check the section delivers what the previous section's closing line promised. This is a drafting step, not a review step — a backwards causal chain is far cheaper to catch here than after Aji has read it. Where it breaks, reorder rather than adding connective words.
3. Flag anything you're uncertain about as a direct question rather than guessing or placeholdering silently.
4. Stop. Wait for Aji's response.
5. **If Aji likes elements of more than one proposed option rather than picking a single winner, don't force a choice — look for how they integrate.** Different options often do different jobs (one paints a picture, one proves the stakes, one gives structure) and can be sequenced so each does its own job, rather than being alternatives competing for the same slot. First case of this: backlog #3's hook combined a sensory analogy with a real-facts passage rather than picking one (see CLAUDE.md → "Signature style," point 1).
6. Incorporate feedback — revise, swap in Aji's own material, integrate multiple approved options as above, or lock it in as approved — before moving to the next section.

Keep a running note (in your own reasoning, not necessarily written to Aji each time) of which sections are locked, so you don't re-litigate an approved section without being asked to.

## Assembly + final check

Once every section is approved:
1. Assemble the full script file in the standard format (title, template declaration, status, runtime, thumbnail/description/tags/playlist, timestamped sections).
2. Run a **light** consistency pass across the assembled whole — transitions between sections, overall pacing, runtime — rather than a full `/review-script` rebuild, since each section was already approved individually. Flag anything that reads oddly now that it's assembled, but don't silently rewrite an approved section to fix it — ask.
3. Run the **principle-consistency check** in full, not lightly (CLAUDE.md → "Leaving the viewer with ethics, principles, and practice," point 4; same step as `/review-script`'s step 6). State the script's core argument in one sentence, then check every piece of advice it gives — takeaway, exercise, any "here's how you'd fix it" beat, the CTA — against that sentence. This check matters *more* in collaborative mode, not less: sections get approved one at a time, and a recommendation that contradicts the argument three sections earlier reads as perfectly sensible in isolation. Both times this has been caught on this channel, it was in a section that had already been individually approved.
4. Save to `scripts/drafts/`, update `backlog.md` status, and log the session in `production-log.md` (what was built/reworked, key decisions made along the way, per the usual reasoning-log format).
