# Assessment — What a Data Manager Actually Does All Day (2026-09-07 re-review)

*By Dan. This supersedes nothing in `assessment.md` (2026-08-02) as a historical record, but it is the current read: checked against the CURRENT `CLAUDE.md` (including the failure-mode, design-for-recall, audience-map-alignment and "keep the term, add the gloss" rules added since 2026-08-04, all of which postdate the 2026-08-02 pass), the CURRENT `backlog.md`, `audience-map.md`, `the-map.md`, `voice-profile.md`, `domain-knowledge.md`, and `memory/dan.md`.*

**The draft text itself has not changed since 2026-08-02.** I recounted it independently rather than trusting the header: **1,041 words, 7.4 minutes at 140 wpm** — matches the stated "1,042 words, 7.4 min" almost exactly, and sits comfortably inside the 7–8 minute target. No cut is needed for length.

---

## Checklist

**1. Hook — PASS, still the strongest opening the channel has produced.** "I built a system with a field on it called 'client'... It worked perfectly. The code was clean, the validation passed, and there was not a single bug anywhere in it... I could not fix that with better code." Visible object, real stakes (a career pivot), unresolved tension ("it turns out it has a job title"). Verified it is not recycled: `videos/what-is-data-management/final.md` does not use the client-field story, "no bug," or "cleanest code" — that phrasing only survives in the legacy, do-not-use `scripts/produced/02-what-is-data-management.md`. Confirmed unique to this video, as the brief intended.

**2. Creativity and engagement — PASS.** The three-chapter structure (developer → West Africa → UK university) carries a single pattern without repeating itself, and the imagery is concrete throughout: a form field with two different answers typed into it, a room where three sites each believed they were right, a team with "real depth in Access" facing a slipping go-live date. Not a flat explanation.

**3. Domain expertise in the language — PARTIAL.** Verbs are correct throughout (data is *recorded*, *captured*, *reported*, *held* — never "run"). But the script's own premise is "it turns out it has a job title," and it never actually cashes that in with the practitioner's names for what's happening:
- The vaccination-dates callback ("We built a data dictionary, we wrote standard operating procedures... before we had a definition anybody would stand behind") is a textbook description of **metadata management**, the exact term `final.md` already established for this same story ("That has a proper name in our profession and it's called metadata management"). This script never says the word. A first-time viewer gets the mechanics without the vocabulary; a returning viewer gets a callback with the label conspicuously missing.
- The data access policy ("state what you need, state why, we assess that against what you actually need, and you get exactly that and nothing more") is **data minimisation** applied through **data governance** — again, textbook, again unnamed.
- Fix, using only what's already established: one clause at each beat — e.g. "...before we had a definition anybody would stand behind. That's metadata management, and I'd already lived the small version of it in that client field," and "...you get exactly that and nothing more. That's data minimisation, and no policy enforces itself — someone has to own saying no." Costs about 15–20 words total, well inside the current headroom (7.4 of 8 minutes).

**4. Aji's voice — PASS.** No decorative sentences that fail to advance the argument (voice-profile §1). Restraint intact — "getting it wrong in either direction has real consequences for a public health programme" is her register, not "a child who never got a vaccine" (§2). "Different decades, different countries, same job underneath" is deliberate parallel repetition and should stay (§7, and the constitution's named exception). No canonical definition is paraphrased, and there are no statistics in this script to mis-cite (§4–5 not triggered). No sign this text has since been touched — it matches the 2026-08-02 "Fix applied" quotes verbatim.

**5. Audience fit — FAIL.** `audience-map.md` states this video "**Serves best: S** — Career exploration first: is this the job for me. Professionals enjoy the recognition but learn little new." The body genuinely earns that: three vicarious, watchable career stories a student can learn from without needing a job first. But the landing breaks it: **"Think about the last time two people in your organisation disagreed about a number."** That requires an organisation, which CLAUDE.md explicitly names as the failure mode to avoid for this audience ("never end on 'run a project' or 'get your team to'... does the closing exercise work for someone with no organisation?"). The project has already solved this exact problem once, in `final.md`'s intermediate fix (since superseded for other reasons): *"the last report you saw two people disagree about, whether that is at work or in a dataset you have been learning on."* The same move — add "or in a dataset you've been learning on" — fixes it here at no cost in words. This is the single highest-priority fix on the list.

**6. Relevance — PASS.** Every passage serves the decide/translate/foresee thesis; nothing drifts into a tangent.

**7. Transitions — PASS, with a minor observation.** The template (`career-thread.md`) carries retention through chronological markers and the assembling framework rather than through explicit forward-pointing questions, and that's what this script does ("Different decades, different countries, same job underneath" → "Translating is the part that happens..."). It's a legitimate mechanism for this template, distinct from — and slightly looser than — `final.md`'s explicit bridge questions ("So who manages the data?"). Not a fail, just worth naming so it isn't mistaken for the flagship's bridging style.

**8. Template fit — PASS.** Chronological markers throughout, no ordinal labels (the 2026-08-02 fix holds), framework assembled piece by piece and only named in full at the landing, matching `templates/career-thread.md` exactly.

**9. Payoff — PASS on the framework, FAIL on the exercise** (see item 5). "Decide, translate, foresee. That is the actual job description, and none of it fits on a business card" pays off the hook's "it turns out it has a job title" cleanly.

**9b. How it goes wrong in practice — PARTIAL.** Part 1 (decide) and Part 3 (foresee) both show the failure mode vividly and causally: "Every single site believed they were the ones doing it correctly" and "a date that has already slipped once tends to slip again, and the day it finally arrives is the worst possible day to discover your team does not have the skills for it." Part 2 (translate) shows only prevention — every beat is about a bad change *not* getting through — and never shows one that did, or what it cost. "The moment they drift apart is the moment a report stops being trusted and nobody can explain why" gestures at the failure abstractly rather than picturing it. **Fix, without inventing anything attributed to a real organisation:** a generalised illustration is explicitly permitted under the narrowed 2026-08-10 attribution rule ("a generalised scenario very likely true across most institutions" is fine). E.g. "When that check doesn't happen, somebody quietly renames what a metric means to make a chart land better in a meeting, and months later two teams are reporting different numbers for what they think is the same thing, with no idea why." This is a content decision, not a pure mechanical fix — see verdict below.

**9c. Recall — PASS on the framework, one gap.** "Decide, translate, foresee" is nameable, three parallel verbs, and it's given a redrawable image (a business card with no room for any of it). The client-field story is the kind of picture a viewer could resketch. **Gap:** no locating line against `the-map.md` (standing rule since 2026-08-04, so it postdates the 2026-08-02 pass and wasn't checked then). This video sits under "The people" on the map. A single sentence — something like "None of this sits at one point on the data's journey. It's the person standing at every point of it" — would satisfy the convention at no real cost.

**10. AI-voice test — PASS.** No "delve/crucial/furthermore." The two triads present ("the code was clean, the validation passed, and there was not a single bug"; "Different decades, different countries, same job underneath") are both concrete or architectural, not decorative padding.

**11. Runtime — PASS.** 1,041 words independently counted, 7.4 minutes at 140 wpm. Inside target; nothing needs to come out.

---

## Reordering-caused issues (checked per this task's brief)

**Confirmed and worse than the backlog note implies: the closing tease is not just pointing the wrong way, it is word-for-word identical to `final.md`'s own tease.** Both scripts end on the exact sentence: *"Next time I want to show you the data mistake that has cost companies hundreds of millions in fines, and almost nobody who made it saw it coming."* Under the current order (1 → 2 "data mistake" → 3 this video), that video will have already published and been teased once by the time this one airs. A viewer reaching this video will hear a promise for something they've already seen. `backlog.md` flags this and says explicitly: *"needs Aji and Torch."* I'm treating that as decisive rather than as a fixable technicality — see verdict.

**Header/status line is stale.** The draft still reads "**Status:** Draft v2 — Dan's ordinal-label fix applied. Ready to film." `backlog.md`'s current, authoritative status for this video is "**Drafted — NOT yet approved**... this one goes back through review with her rather than proceeding to film." The draft's own header contradicts the project's live record of its state. This should be corrected regardless of what else happens to the script, so nobody reading `draft.md` in isolation is misled.

**Missing the post-2026-08-03 audience header.** `final.md` carries a `**Serves:**` line taken from `audience-map.md`; this draft doesn't. Mechanical, no judgement call — should be added citing audience-map's "S — career exploration first."

---

## Fixes, in priority order

1. **Landing exercise altitude (item 5).** Add "...or in a dataset you've been learning on" (or equivalent) so a student with no workplace can still do it. Highest priority — this is the one item that fails the video's own primary audience.
2. **Fix the closing tease.** Do not reuse `final.md`'s tease. Needs a decision on what this video should point to next under the current order (see verdict — flagged as Aji's).
3. **Name the disciplines** at the vaccination-dictionary beat (metadata management) and the access-policy beat (data minimisation / data governance) — quoted insertions above, ~15–20 words, within budget.
4. **Give Part 2 a failure-mode beat**, generalised rather than attributed to a real organisation, per item 9b.
5. **Mechanical, no judgement needed:** add the `Serves:` audience line, add a one-sentence map-locating line, correct the stale "Ready to film" status line.
6. **Unchanged advisory from 2026-08-02, still true, not urgent:** hook runs ~68 seconds against a 45-second slot — acceptable, the hook is protected and cut last. Watch the "university" framing in Part 3 stays a supporting detail rather than the organising frame — currently on the right side of the line.

---

## Verdict on the one question that matters

**No — this cannot be finished to a passing state using only what's already in the project. It needs Aji.**

To be precise about what does and doesn't need her, because the checklist above contains both kinds:

**Torch can pre-stage these now, from material already in the project, with no new judgement call:** the `Serves:` header, the map-locating line, correcting the stale status line, and naming "metadata management" / "data minimisation" at the two beats identified in item 3 (both terms and both stories are already fully established elsewhere in the project).

**These need Aji, and I'd flag all four as hers even though some look mechanical on the surface:**

1. **The closing tease.** `backlog.md` says this explicitly — "needs Aji and Torch," not Torch alone. It isn't just a copy-paste fix: it's a decision about what promise this video makes to the next one, which is exactly the kind of sequencing call she has made personally every other time it's come up in this project (the subtitle decisions, the tease-to-#2 wording itself in `final.md`). Whatever Torch proposes to point at instead should go to her before it's treated as settled.
2. **The landing exercise rewrite.** There is a clean precedent (`final.md`'s now-superseded version), but every audience-altitude fix of this kind in this project's history was made under her direct instruction, not invented unilaterally by Torch. Given this whole video is explicitly parked pending "review with her," I'd rather Torch propose the fix and get her sign-off than have it silently applied.
3. **Whether and how much practitioner terminology to add (item 3).** This is a genuine tone call for an identity/career video, which is a more personal, narrative register than the flagship explainer. She has directed this exact kind of decision before — including telling Torch *not* to add a gloss he thought was warranted ("not necessary to add," on `coverage analysis` in `final.md`). I can name the gap and propose the wording; whether it's the right amount of vocabulary for this particular video's voice is hers to call.
4. **The Part 2 failure-mode beat.** Adding new content, even generalised and unattributed, to a script that's otherwise been frozen since 2026-08-02 and is explicitly pending her review is a content decision, not a formatting one.

This lines up with `backlog.md`'s own framing, which I'm taking as authoritative rather than overriding on the technical argument that some of these fixes are achievable without her: **"Aji is rebuilding every pre-process video through the pipeline step by step with her own input, so this one goes back through review with her rather than proceeding to film."** Video 1 shows what that review actually looks like in practice — eleven rounds of her personally directing hook shape, wording, landing structure and terminology density, several of which Torch or Dan could have "solved" alone but which she wanted to decide herself. I'd expect the same here. The right outcome this week is what CLAUDE.md calls the correct outcome, not a failure: **notify Aji that this draft needs a session with her before it can pass**, with the prioritised fix list above ready for that session.

**One-line verdict: structural rewrite of the landing and closing tease, both requiring Aji — not ready to film, and not finishable unattended this week.**
