# Assessment — What a Data Manager Actually Does All Day (fresh pass)

*By Dan, 2026-08-31. Full checklist rerun against the current state of `draft.md`, `templates/career-thread.md`, `voice-profile.md`, `domain-knowledge.md`, `domain-map.md`/`the-map.md`, `audience-map.md`, `presenter-background.md`, `memory/torch.md` and `backlog.md`. This supersedes `assessment.md` (2026-08-02) for judging whether the draft is ready to film — that file is left untouched as the historical record.**

## Why a fresh pass, not a reuse of the old one

`assessment.md` (2026-08-02) checked the draft against an **eleven-item checklist that predates several standing rules now in force**: audience fit as a pass/fail item (added 2026-08-03), "how it goes wrong in practice" (added 2026-08-04), recall (added 2026-08-04), and the map locating line (added 2026-08-04, `the-map.md` confirmed same day). It also predates the substantial rework of `videos/what-is-data-management/final.md` between 2026-08-10 and 2026-08-11, which changed the hook this draft has to avoid colliding with. None of that was checkable on 2026-08-02. Treat the old file as "passed the checklist that existed then," not as still current.

---

## Checklist

**1. Hook — PASS, unchanged from the prior pass and still the strongest opening the channel has produced.** "It worked perfectly. The code was clean, the validation passed, and there was not a single bug anywhere in it... I could not fix that with better code." Small, visible, real stakes, genuine tension (a system with no bug that is still wrong). Nothing has degraded here.

**2. Creativity and engagement — PASS, with one fresh overlap flag (see item 6/12 below).** The reconciliation meeting ("Every single site believed they were the ones doing it correctly, and they each had a reasonable argument") is genuinely fresh material — negotiation, not technique. The dashboard-request refusal beat ("if it would blur a definition or quietly change what a number meant, it did not go in... That held even when the request came from management") is a strong, specific, unglamorous scene of real authority. However: the closing exercise now duplicates the flagship's hook scenario almost exactly — see the dedicated note below. That is a genuine defect in an otherwise strong script, not a reason to fail the item outright.

**3. Domain expertise in the language — PASS, with a specificity gap worth closing.** Verbs check out: data is *recorded, captured, built* (a dictionary), *written* (procedures), *trained against*, *assessed*, *held*. No generic "run"/"handle". Terms are used correctly: "personal data," "data access request policy." **The gap:** `domain-knowledge.md` and Dan's checklist item 3 both ask the script to *name the discipline a problem belongs to*, not just describe it. The vaccination-dates callback ("we built a data dictionary, we wrote standard operating procedures... and we trained every site against both") never names **metadata management** — the exact discipline `final.md` names for this same story ("That has a proper name in our profession and it's called metadata management"). Since this is an explicit callback to that story, the omission reads as a missed connective beat rather than a hedge, but a viewer who has seen video 1 will notice the term dropped. Similarly, the data-access-policy story is a **data governance** story (decision rights over who may see data) and is never named as such. Neither omission makes the script read like an outsider wrote it — the operational detail throughout is too specific and lived for that — so this stays a PASS, but it is the one place the language could carry more of the discipline's own vocabulary.

**4. Aji's voice — PASS.** Restrained throughout: "getting it wrong in either direction has real consequences for a public health programme" (voice-profile §2 register, not escalated). No decorative flourish sitting outside the argument (voice-profile §1). Deliberate parallel repetition is used correctly and should stay: "Different decades, different countries, same job underneath" (§7 exception). "Consequences" is used, not "harm" (§9). No canonical definition is paraphrased here since none is being stated. Flows as spoken sentences with no fragment-stacking defect.

**5. Audience fit — PARTIAL.** `audience-map.md` (2026-08-03) states this video "Serves best: **S**" — "Career exploration first: is this the job for me. Professionals enjoy the recognition but learn little new" — and the brief confirms: "primarily career-builders deciding whether this is their path." Two places the draft is written above that altitude:
   - **The closing exercise assumes an organisation.** "Think about the last time two people **in your organisation** disagreed about a number." CLAUDE.md is explicit: for students, "never end on 'run a project' or 'get your team to'" and the exercise must "work for someone with no organisation." A student with no job cannot do this exercise as written. `final.md`'s own superseded exercise shows the achievable fix in the same project: *"the last report you saw two people disagree about, whether that is at work or in a dataset you have been learning on."*
   - **Two terms are used without a gloss for a first-time viewer**: "data dictionary" and "standard operating procedures" are named and used but never explained in the simple-form-without-replacing-the-term way `final.md` models for "business metadata" ("the agreed and written-down definition of what that column actually meant"). This is the exact "keep the term, add the gloss" rule (CLAUDE.md, cross-agent-lessons 2026-08-04), and it is precisely the move that lets one video serve both audiences at once.
   Both are fixable with a sentence or a clause each, not a rewrite, and both are demonstrated elsewhere in the project already (see fixes below).

**6. Relevance — PASS.** Every passage serves "what the job actually is." Nothing drifts into unrelated material.

**7. Transitions — PASS.** Chronological markers hold throughout and read as speech: "Years later, in my clinical data years in West Africa..." / "And it's still happening now..." / "Seeing it coming is the one that is happening to me right now, rather than being a tidy story from the past." Each section ends on a bridge into the pattern, not a hard stop.

**8. Clarity — PASS.** Reads for the ear; nothing stumbles on a read-aloud pass.

**9. Template fit — PARTIAL.** `templates/career-thread.md` requirements: hook on a small real moment (met), credibility beat naming the range of chapters (met, brief and proportionate at this runtime), body pulling one thread through career chapters with chronological markers and no ordinals (met — the 2026-08-02 fix holds), landing recapping the framework and delivering a takeaway (met: "Decide, translate, foresee" lands as a discovery, and the exercise is present, albeit needing the audience-fit fix above). **What fails the structure as delivered: the landing's "pivot into the next video with a problem-led tease" is broken** (see the dedicated section below), and **the map locating line required by CLAUDE.md and `the-map.md` (standing rule since 2026-08-04) is absent.** `the-map.md` places this video under "The people" — "career change (7), which path pays (8), certifications (19), jobs disappearing (26), what a data manager does (3)" — and the convention is one sentence, near the top or in the landing, naming that this video is about the people who do the work rather than a stage of the data journey itself. Nothing in the draft does this. This postdates the 2026-08-02 assessment, which could not have caught it.

**9b. How it goes wrong in practice — PASS, and one of the script's real strengths.** The client-field story shows the failure mode with its cause named plainly: "Nobody had ever agreed what 'client' actually meant before the form went live." The data-access story shows a live organisational failure and its mechanism: "no scope and no stated purpose, handed over because saying yes was quicker than asking why." The SQL-upskilling story shows the failure mode being pre-empted rather than narrated after the fact: "the day it finally arrives is the worst possible day to discover your team does not have the skills for it." This is exactly what the standing rule asks for and it is not padded on top — it is structural to all three parts.

**9c. Recall — PASS.** Nameable framework: "Decide, translate, foresee." A redrawable picture: one field, two meanings, no bug. A story that carries the point further than a definition would: the reconciliation meeting where every site believed it was right. This is a script a viewer could repeat to a colleague a week later.

**10. AI-voice test — PASS.** No "delve/crucial/furthermore." No relentless smoothness. The triads present ("decide, translate, foresee"; "different decades, different countries, same job underneath") are architectural and parallel, not decorative padding — consistent with the "count, then judge shape" calibration in `memory/dan.md`.

**11. Runtime — PASS, independently recounted, not inherited.** Section-by-section manual count: hook ≈158 words, credibility ≈64, Part 1 ≈309, Part 2 ≈190, Part 3 ≈161, landing ≈162. **Total ≈1,044 words ≈ 7.46 minutes at 140 wpm**, consistent with the header's stated 1,042/7.4 and inside the 7–8 minute target with no cuts required.

---

## 12. The closing tease — dedicated analysis (this is the item that actually decides the verdict)

**Current text:** *"Next time I want to show you the data mistake that has cost companies hundreds of millions in fines, and almost nobody who made it saw it coming."*

**Two separate defects, not one:**

1. **It is a duplicate, not just misordered.** `videos/what-is-data-management/final.md` (position 1, live and approved) already closes on this **exact same sentence, word for word**, teasing the same video. That was correct when it was written — position 2 genuinely is next after position 1. But this draft has copied that line into a second video rather than writing its own tease. Even setting the ordering problem aside, no two videos should promise the same "next time" beat; whichever one the viewer sees second will feel recycled.
2. **Under the current backlog order (1 → 2 → 3), it also points backward.** By the time a viewer reaches this video (position 3), the data-mistake video (position 2) has already published. "Next time I want to show you..." then promises something already seen. This is the defect Linda flagged in `backlog.md`.

**Can this be fixed with only what's already in the project? No — not honestly, and not durably.**

- The video that actually comes next in the current order is **#4, "Why nobody trusts your reports (and how to fix it)"** (backlog.md, Foundations/data quality). But #4 has **no brief and no draft** — `videos/` contains only folders for #1 and #3. Writing a specific, problem-led tease for #4 (which scripting rule 9 and the template both require — a vague, non-committal sign-off is not the same device and is not what the structure asks for) means inventing the content of a video nobody has written yet. That is exactly the kind of judgement call reserved for Linda's brief and Aji's input, not something Torch or Dan should originate to make a checklist pass.
- **The order itself is not stable.** It has already changed once since this draft was written (the exact fact that broke the tease in the first place), and `backlog.md`'s own note for #1 records live re-ordering and re-titling decisions happening currently, with Aji "rebuilding every pre-process video through the pipeline step by step with her own input." Locking a new specific promise onto #4 today carries a real risk of the same failure recurring before this video is filmed.
- `backlog.md` says so directly: *"That closing tease has to be rewritten to point forward, not back. Flagged by Linda; needs Aji and Torch."* That is Linda's own assessment that this is a two-person fix, not a Torch-only one.

**What would make it fixable without Aji:** if a brief already existed for whatever is confirmed to be genuinely next, Torch could write a compliant tease unattended. That condition is not currently met.

---

## 13. Does this draft still need Aji, beyond the tease — per `backlog.md`'s note on #3

`backlog.md`'s live entry for #3 states plainly: *"Drafted — NOT yet approved... Aji is rebuilding every pre-process video through the pipeline step by step with her own input, so this one goes back through review with her rather than proceeding to film."*

Take this at face value rather than reading past it. This is not a statement about a specific defect — it is a **process decision**: every pre-process video (anything drafted before the three-agent pipeline's current form, or before her personal review at each stage) goes through her hands before it can be marked ready, independent of whether Dan's checklist otherwise passes it. `memory/cross-agent-lessons.md` (2026-08-03) records the same thing generally: *"Only one video is approved and complete: position 1... treat nothing produced before 2026-08-02 as approved... Position 3 (the data-manager video) is drafted but not approved."*

So even setting the tease aside, **my judgement is that this draft needs Aji's own pass before it can be marked ready**, for two independent reasons, not one:
1. The content-level defect (the tease) cannot be closed without either her decision on what's genuinely next, or her explicit sign-off to write a different kind of close.
2. The governance note is a standing instruction that this video is in the batch she is personally reworking, which is a decision about *process*, not about *quality* — and it isn't Dan's or Torch's to waive on the strength of a checklist pass.

This matches the weekly-production protocol precisely: Torch may only finish unattended work that "can be brought to a state that passes Dan's full checklist **without needing anything from Aji**." This draft does not meet that bar.

---

## Fixes, prioritised, each marked mechanical or needs-Aji

1. **[NEEDS AJI] The closing tease.** Cannot be honestly rewritten to point at a stable "next" video without either (a) her confirming what genuinely publishes next and letting Torch draft a tease once that video has at least a brief, or (b) her explicit permission to close some other way (e.g. a tease that doesn't name specific content). Recommend flagging this to her directly rather than guessing.
2. **[NEEDS AJI, per backlog's own governance note] Overall sign-off.** Independent of point 1, `backlog.md` states this video "goes back through review with her" as a matter of process. Do not mark Reviewed/Filmed without her.
3. **[MECHANICAL] Closing exercise duplicates the flagship's hook scenario.** "Think about the last time two people in your organisation disagreed about a number. Not about what to do, about what the number actually was" is materially the same scenario as `final.md`'s hook ("two people brought the same figure and the numbers did not match... they were counting slightly different things"), which the viewer will have already seen in the video that plays before this one. Torch should write a different closing prompt — the material already exists in this draft to pull from (e.g. something tied to the "decide, translate, foresee" framework directly, asking the viewer to spot which of the three they last did).
4. **[MECHANICAL] Fix audience-fit on the closing exercise.** Remove the dependency on "your organisation" so it also works for a viewer with none, following the pattern already used and approved in this project (`final.md`'s superseded exercise: "whether that is at work or in a dataset you have been learning on"). This can be combined with fix 3.
5. **[MECHANICAL] Add the map locating line.** One sentence, near the top or in the landing, per `the-map.md`'s "The people" placement — e.g. something like "this one isn't a stage in the data's journey, it's about the people who do the work at every stage of it."
6. **[MECHANICAL] Name the disciplines.** Add "metadata management" to the vaccination-dates callback (matching `final.md`'s own naming of the same story) and consider naming "data governance" for the access-policy story. A clause each, not a rewrite.
7. **[MECHANICAL, minor] Gloss "data dictionary" and "standard operating procedures"** on first use for the student audience, in the "keep the term, add the gloss" style already established in `final.md`.

---

## Verdict

**Not ready to film — needs Aji, not a Torch-only pass.** The script itself is strong: hook, creativity, domain grounding, voice, transitions, "how it goes wrong," and recall all hold up, and the runtime is fine. But the closing tease is broken in a way that cannot be closed with material currently in the project, and `backlog.md`'s own governance note independently requires her review before this proceeds. The mechanical fixes (map line, discipline naming, exercise wording, glosses) should be applied by Torch in the same pass, but the two items above are hers.
