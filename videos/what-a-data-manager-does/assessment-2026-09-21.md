# Assessment — What a Data Manager Actually Does All Day (fresh review)

*By Dan, 2026-09-21. This supersedes `assessment.md` (2026-08-02) for judgement purposes; that file is kept as history. Reviewed against `templates/career-thread.md`, `voice-profile.md`, `domain-knowledge.md`, `the-map.md`, `audience-map.md`, and `CLAUDE.md` in full, including standing rules added after the 2026-08-02 pass (map locating line, audience-line-at-top, term-gloss rule). Also diffed line by line against `videos/what-is-data-management/final.md`, the now-live authority for #1, which did not exist in its current form when this draft or the 2026-08-02 assessment were written.*

## Headline finding not caught before

**This draft now duplicates the live `final.md` (#1) in two places, one of them word for word.**

- **Bio paragraph, near-verbatim.** Draft: *"My name is Aji Saine, and I have over twelve years of combined experience in software development and data management. I looked after health records for more than 285,000 people across research sites in West Africa, and today I handle statutory data reporting for a UK university."* `final.md` line 23 is the same sentence with two extra clauses ("where a single data error could affect a medical decision" / "where the data we submit literally determines funding and regulation"). A viewer who watches both videos back to back hears the presenter introduce herself in almost identical words twice.
- **Closing tease, 100% identical.** Draft: *"Next time I want to show you the data mistake that has cost companies hundreds of millions in fines, and almost nobody who made it saw it coming."* `final.md` line 73: the exact same sentence, word for word. This is the same broken tease `backlog.md` already flags ("its closing tease also points at a video that now publishes before it"), but it is worse than "backwards": it is a verbatim duplicate of a tease **already used and already delivered** in the video that plays immediately before this one under the current order (#1 → #2 → #3). By the time a viewer reaches #3, #2 has already published, so the line is neither a fresh tease nor an accurate one.

Neither duplication existed when this draft or the 2026-08-02 assessment were written — `final.md` was reworked into its current form on 2026-08-10/11, after this draft was last touched. This is exactly the kind of drift `cross-agent-lessons.md`'s de-duplication rule exists to catch, and it only becomes visible on a fresh diff against the current live script, not the one that existed when the draft was approved-in-principle.

## Checklist

1. **Hook — PASS.** The "client" field story is still the strongest opening the channel has produced: a small, sharp, real moment with a visible object (a form, a typed field) and genuine stakes reached in one line — *"I could not fix that with better code."* Matches the template's requirement exactly.

2. **Creativity and engagement — PASS.** The cross-site reconciliation meeting ("every single site believed they were the ones doing it correctly, and they each had a reasonable argument") is fresh, and the SQL-upskilling story is the only beat in the channel currently happening in the present tense. Not flat.

3. **Domain expertise in the language — PARTIAL.**
   - Part 2 ("translate") describes metadata/glossary work in full — *"you stand between the language of a system, its tables and keys and fields, and the language people actually use in a meeting"* — without ever naming the discipline. `domain-knowledge.md` and Torch's own memory (2026-08-02: "name the specific discipline a story illustrates, not just the general principle") both call for this, and `final.md` does it for its own version of the same idea ("that has a proper name in our profession and it's called metadata management"). Part 2 should name what it is describing.
   - "We built a data dictionary" (Part 1) is a taught term used with no gloss. Per the standing "keep the term, add the gloss" rule, a first-time viewer — and this video's primary audience is students, see item 5 — does not learn what a data dictionary is, only that Aji built one. One clause fixes it ("a data dictionary, the document that fixes what a field is allowed to mean").
   - Verbs are otherwise accurate throughout: recorded, captured, trained, reported, assessed, held. "handle statutory data reporting" appears in Part "Who I Am" — this is a generic verb `domain-knowledge.md` names explicitly as a tell, but it is not a fresh slip: it is lifted verbatim from Aji's own approved wording in `final.md`. I am not flagging the verb choice itself as a defect (voice-profile rule 3: do not silently replace her approved wording), only noting it travels with the duplication above — if the bio line is reworded to stop duplicating #1, the verb should be revisited too.

4. **Aji's voice — PASS.** Economical, restrained (compare "getting it wrong in either direction has real consequences for a public health programme" to the register `voice-profile.md` §2 documents). "Different decades, different countries, same job underneath" is a single deliberate line, not a stacked run of fragments — fine. No flourish that doesn't earn its place.

5. **Audience fit — PARTIAL, and this is a real fix, not a nitpick.** `audience-map.md` names this video's best audience as **S** (students): *"Career exploration first: is this the job for me."* Two problems against that:
   - The draft has **no audience line at the top**, which the constitution requires explicitly: *"Every script states at the top which audience it serves best."* `brief.md` has it; the draft dropped it.
   - The closing exercise: *"Think about the last time two people in your organisation disagreed about a number."* This presumes the viewer has an organisation. CLAUDE.md's own worked example draws the line precisely here: *"'think of the last report two people argued about' works for both; 'audit your data quality process' does not."* This draft's version is the failing shape — it names "your organisation" where the passing version wouldn't have to. A student with no workplace cannot do this exercise as written. Easy fix: drop "in your organisation."

6. **Relevance — PASS.** Every passage serves what the job actually is.

7. **Transitions — PASS, minor note.** Chronological markers are used correctly throughout. The end-of-section bridges ("Different decades, different countries, same job underneath" / "Saying no is part of the job. Nobody writes that down anywhere.") are closes rather than forward-pointing questions — serviceable, not sharp. Not a blocker.

8. **Template fit — PARTIAL.** The chronological-marker rule and the "assemble the framework, don't announce it" rule are both honoured (the ordinal-label fix from the 2026-08-02 pass has held). Missing: the **map locating line**, standing rule since 2026-08-04, added after this draft was last substantively written. `the-map.md` places this video under "The people," not a stage on the journey — one sentence is needed, e.g. "This one isn't a stage on the data journey, it's about who does the work at every stage of it." Say so rather than pass silently, per my own standing instruction.

9. **Payoff — PASS internally, FAIL on the next-video tease.** The closing exercise mirrors the hook well (a disagreement over what a number *is*, the same shape as the client-field dispute) — that half of the payoff lands. The next-video tease does not: see headline finding above. This is the item that decides whether the video can end as written.

9b. **How it goes wrong in practice — PASS.** The whole script is built from failure moments, not tidy successes: the undefined field, the unscoped "give me everything" access requests, the dashboard request that would have blurred a definition, the migration a team wasn't ready for. Real and specific throughout.

9c. **Recall — PASS.** "Decide, translate, foresee" is a genuinely nameable, three-word framework, assembled piece by piece rather than announced up front, which is exactly what the recall rule wants. Multiple stories carry it (the client field, the reconciliation meeting, the SQL upskilling).

10. **AI-voice test — PASS.** No delve/crucial/furthermore. Triads present ("Decide, translate, foresee"; the hook's "clean / validation passed / no bug") are architectural, not decorative, and there are only two of note — well under the ceiling.

11. **Runtime — PASS.** Recounted independently rather than trusting the header's "1,042 words, 7.4 min": section-by-section count comes to roughly 995–1,040 words depending on how contractions are counted, landing at **7.1–7.4 minutes at 140 wpm**. Comfortably inside the 7–8 minute target, nowhere near the ceiling.

## Fixes, prioritised

1. **Rewrite the closing tease.** It cannot stay as written: it is both a verbatim duplicate of a line already delivered in the video before it, and it is chronologically backwards. This is a sequencing decision, not a wording one — see the report back to the studio director for why it needs Aji/Linda rather than a mechanical swap.
2. **Vary the "Who I Am" bio paragraph** so it is not near-identical to `final.md`'s. Keep the facts (twelve-plus years, 285,000 people, statutory reporting), change the sentence.
3. **Drop "in your organisation" from the closing exercise** so it works for a viewer with no workplace, per the audience this video is written for.
4. **Add the audience line at the top of the draft** ("Serves best: S, per `audience-map.md`").
5. **Add the one-sentence map locating line.**
6. **Name the discipline in Part 2** (metadata management / definitional work — Torch's call on exact wording, avoiding #1's specific phrasing).
7. **Gloss "data dictionary"** on first use.

Items 2–7 are mechanical: they can be done entirely from material already in the project (CLAUDE.md's own audience example, `the-map.md`, `domain-knowledge.md`, `audience-map.md`) and need no story, decision or stat that isn't already approved. Item 1 is the exception — see below.

## Verdict

**Not ready to film, and not a simple one-more-pass either.** Six of the seven fixes are mechanical and Torch can make them unattended. The seventh — the closing tease — is a content decision about what actually publishes after this video, which nothing currently in the project settles, and `backlog.md` already says this one "goes back through review with her rather than proceeding to film." Recommend: Torch applies fixes 2–7, then the draft goes to Aji specifically for the tease decision and her own pass, consistent with how #1 was handled.
