# Assessment — What a Data Manager Actually Does All Day (draft)

*By Dan, 2026-08-02. Reviewed against `templates/career-thread.md`, `voice-profile.md`, `domain-knowledge.md` and `CLAUDE.md`.*

## Checklist

1. **Hook — PASS, and it is a real improvement on the previous version.** Opening on the "client" field is the right call: it is a small, specific, real moment rather than a rhetorical device, which is exactly what this template asks for. "It worked perfectly. The code was clean, the validation passed, and there was not a single bug anywhere in it" earns the turn that follows, and "I could not fix that with better code" is the line that makes a viewer stay. It also solves the collision with Video 2, which had opened on the same disputed word.
2. **Creativity and engagement — PASS.** The material is inherently strong and it is not over-written. The strongest beat is the reconciliation meeting where every site believed it was right, because it shows the work is negotiation rather than technique.
3. **Domain expertise in the language — PASS.** Data dictionary, standard operating procedures, definitions, personal data, all used in the sense a practitioner would recognise. Verbs check out: data is recorded, captured, assessed, held. No generic verb standing in for the domain's own.
4. **Aji's voice — PASS.** Economical, and noticeably free of the decorative sentences she cut out of the last script. Restraint is right: the previous draft escalated to "a wrong medical picture on a clinician's screen", and this one says "real consequences for a public health programme", which is her register. "Different decades, different countries, same job underneath" is deliberate parallel repetition and should stay.
5. **Relevance — PASS.** Every passage serves the question of what the job actually is.
6. **Transitions — PASS.** Chronological markers are used properly: "years ago, back when I was writing software", "years later, in my clinical data years", "and it's still happening now", "happening to me right now rather than a tidy story from the past".
7. **Template fit — PARTIAL, and this is the fix that matters.** The template is explicit that this format uses chronological narrative markers and **never ordinal labels**. The draft opens each thread with "The first is...", "The second is...", "The third is...". That is precisely the construction the template rules out, and it also weakens the ending, because the framework should be *assembled* and then named, not announced three times before it arrives.

   **Fix:** cut the ordinals and let each section open on the thread itself. "Deciding what the data means usually happens before anyone writes a line of code." / "Translating happens almost entirely outside a database." / "Foreseeing is the one that is happening to me right now." The payoff line, "decide, translate, foresee", then lands as a discovery rather than a recap.
8. **Payoff — PASS.** The exercise ties back to the hook well: the viewer is asked to remember the last time two people disagreed about what a number *was*, which is the same argument the client field started.
9. **AI-voice test — PASS.**
10. **Runtime — PASS. 1,051 words, 7.5 minutes**, inside the 7–8 minute target. Down from 14.1 minutes without butchering: whole beats were removed rather than sentences thinned.
11. **Overlap with Video 2 — RESOLVED.** Vaccination dates now appear as a one-line callback plus genuinely new material (what was done about it). "Treat every record as if it belonged to your own mother" has been dropped from this script so Video 2 keeps it. The disputed-word hook is gone.

## Remaining fixes

1. **Remove the ordinal labels** (item 7). This is the only substantive change.
2. **Hook length.** At 158 words it runs about 68 seconds against a 45-second slot. The constitution protects the hook and cuts it last, so I am not asking for it to be trimmed, but it should be a deliberate choice rather than an accident. If anything goes, it is the sentence beginning "I could not fix that with better code" — though that is also the best line in the section, so my recommendation is to leave it and accept a longer opening.
3. **Watch the employer framing in Part 3.** The rule is that identity videos frame around the role, not a specific employer. The SQL upskilling story leans on "the university" as the actor twice. It stays the right side of the line, but keep the emphasis on the judgement she made rather than on the institution's delay.

## Fix applied (2026-08-02)

Torch removed the ordinal labels. Each thread now opens on itself ("Deciding what the data means is where it starts" / "Translating is the part that happens almost entirely outside a database" / "Seeing it coming is the one that is happening to me right now"), so "decide, translate, foresee" lands as a discovery rather than a recap. Runtime 1,042 words, **7.4 minutes**. The other two items were advisory and left as they are, both deliberately.

## Verdict

**Ready to film.** Fix the ordinals and this is the strongest identity script the channel has. The story about the client field with no bug in it is the best opening the channel has produced, because it makes an abstract argument concrete in about fifteen seconds.

---

# Reassessment — 2026-08-17 (Dan)

*Full checklist re-run from scratch against the current file (unchanged since 2026-08-02), the current `backlog.md`, current `audience-map.md`, current `voice-profile.md`, current `domain-knowledge.md`, and the current `videos/what-is-data-management/final.md`, which did not exist in this form on 2026-08-02. This supersedes the 2026-08-02 verdict; that record is kept above rather than deleted.*

## The finding I was asked to check: the closing tease is broken, and it is worse than a scheduling mismatch

`backlog.md` now confirms explicitly: position 2 (**"The Data Mistake That Cost Companies Hundreds of Millions"**) is *"NEXT TO SCRIPT — confirmed by Aji 2026-08-03"* and has not been drafted yet. Position 3 is this video, and its own backlog row says outright: *"Its closing tease also points at a video that now publishes before it and must be rewritten."* There is a separate note under "Notes" that says the same thing in more detail and ends: *"Flagged by Linda; needs Aji and Torch."*

Checking the draft against that: the landing currently reads —

> "Next time I want to show you the data mistake that has cost companies hundreds of millions in fines, and almost nobody who made it saw it coming."

This is confirmed broken, and on inspection it is a worse defect than the backlog note describes. **That sentence is not just pointing at the wrong video — it is word-for-word identical to the tease already sitting at the end of `videos/what-is-data-management/final.md`** (line 73: *"Next time I want to show you the data mistake that has cost companies hundreds of millions in fines, and almost nobody who made it saw it coming."*). Given #1 publishes before #2, and #2 publishes before #3, by the time this video airs:

- The video being teased will have **already been published** for the audience following the channel in order (temporal defect, as flagged).
- A returning viewer will hear the **identical sentence** they already heard at the end of Video 1, now pointing at something they have already watched. This is a cross-video duplication of exactly the kind the standing rule on de-duplication exists to catch (`memory/cross-agent-lessons.md`, 2026-08-02: *"Cross-video de-duplication is now part of the job... Dan flags any beat that has appeared in a finished video."*) — it just wasn't visible on 2026-08-02 because Video 1's tease line hadn't been finalised yet.

**This is a real defect, confirmed, and it fails item 9 (payoff/landing) on its own.**

### Why I am not treating this as a fix Torch can make alone

Rewriting the sentence itself is mechanical. The problem is **what it should point to**. The only video confirmed to publish after #3 in the current order is #4, *"Why nobody trusts your reports (and how to fix it)"* — but #4's backlog status is **"New"**: no brief, no draft, not yet approved as the next thing to be made. Committing this script's tease to a specific forthcoming title is an editorial sequencing call, and the backlog's own note on this exact defect says it *"needs Aji and Torch"*, not Torch alone. That instruction is already in the project; I am not inventing a reason to escalate it. Separately, this video's backlog row already states Aji is *"rebuilding every pre-process video through the pipeline step by step with her own input, so this one goes back through review with her rather than proceeding to film"* — a standing instruction that predates and is broader than the tease problem.

## Full checklist, re-run

1. **Hook — PASS, unchanged, and the strongest opening on the channel.** "It worked perfectly. The code was clean, the validation passed, and there was not a single bug anywhere in it. But some people typed the name of the organisation into that field, and other people typed the name of a particular member of staff... Nobody had ever agreed what 'client' actually meant before the form went live." Visible, small, stakes-bearing, and it reaches real tension ("I could not fix that with better code") before promising the payoff. Confirmed still unique against the current `videos/what-is-data-management/final.md` — no shared hook, no shared disputed word ("active" appears only in the flagship's Part 3, not here), no shared story.

2. **Creativity and engagement — PASS.** The client-field image remains the standout: a system with no bug that is still wrong. The reconciliation-meeting detail ("Every single site believed they were the ones doing it correctly, and they each had a reasonable argument") is genuine storytelling, not just an explanation with an anecdote bolted on.

3. **Domain expertise in the language — PARTIAL.** The verbs and terms used are correct — "recorded", "captured", "assessed", "reported", "personal data" all sit where a practitioner would put them, and nothing is loosened to make a sentence flow. But the **specificity** sub-check fails on the two strongest beats. The vaccination/dictionary passage —

   > "We built a data dictionary, we wrote standard operating procedures for how the data was captured, and we trained every site against both."

   — is a textbook description of **metadata management**, and the word never appears. This matters because the *sibling* video already sets the pattern for this exact material: `final.md`'s version of the same underlying story explicitly names it — *"That has a proper name in our profession and it's called metadata management."* Torch's own memory records this as a deliberate, learned move (`memory/torch.md`, 2026-08-02: *"Name the specific discipline a story illustrates, not just the general principle. The vaccination case is a metadata management failure, and saying so is what makes it expert rather than explanatory"*), and this draft doesn't carry it through, likely because it predates that lesson being fixed into the flagship's final edit.

   The same gap sits in the access-policy beat: "you get exactly that and nothing more" is **data minimisation** (`domain-knowledge.md` §8), and "Nobody outside the team ever sees that policy being applied... one that can account for who holds what" is a **data governance / accountability** point. Neither discipline is named. This is the difference between a script that uses the right words and one that shows it knows what field they belong to — the standing rule in `CLAUDE.md`: *"does the script name the discipline a problem belongs to... rather than gesturing at the general idea?"*

   **Fix (Torch can do this unattended, from `domain-knowledge.md` alone):** add the term with a gloss at the natural point in each beat, e.g. "...before we had a definition anybody would stand behind. That's metadata management — deciding what a field means and writing it down so it outlives the person who decided it," and "...and you get exactly that and nothing more. That's data minimisation, and it's a data governance decision, not a courtesy." Keep it to a clause each; do not spend more than a handful of words per beat.

4. **Aji's voice — PARTIAL.** Mostly clean and restrained, consistent with `voice-profile.md` rule 2 (no dramatized stakes — "real consequences for a public health programme" is the right register, not "a wrong medical picture on a clinician's screen"). One specific inconsistency: `voice-profile.md` §9 records **"health data" rather than "clinical data"** as her preference for the general audience, and the credibility beat in this very script gets it right ("I looked after health records for more than 285,000 people"), but Part 1 then says —

   > "Years later, in my clinical data years in West Africa, I hit that same 'client' problem..."

   — reverting to "clinical data" a few sentences after "health records" was used correctly. Small, cheap fix, no judgement call needed: "in my health data years."

   No stacked fragments, no replaced canonical wording (there is no canonical definition to paraphrase in this template), no statistics without a source (there are no statistics in this script at all — correctly, since none of the anecdotes need one). "Different decades, different countries, same job underneath" is deliberate parallel repetition and should stay, per the standing exception.

5. **Audience fit — PARTIAL.** `audience-map.md` marks this video **S** (student/career-builder) primary: *"Career exploration first: is this the job for me. Professionals enjoy the recognition but learn little new."* The body genuinely serves that: three chapters of Aji's own career let a student watch the work without needing an organisation of their own, which is the right move for an identity video aimed at "is this job for me." But the landing exercise breaks the rule for a student-primary video —

   > "Think about the last time two people **in your organisation** disagreed about a number."

   A viewer with no workplace cannot do this literally, which is exactly what `CLAUDE.md`'s student-writing rule warns against (*"never end on 'run a project' or 'get your team to'"* — the same failure mode, an assumed organisation). Video 1's own now-superseded landing hit this same problem and was rewritten to *"the last report you saw two people disagree about, whether that is at work or in a dataset you have been learning on"* before that whole exercise was cut in a later round. **Fix (mechanical, no Aji decision required):** widen the frame the same way — "in your organisation, in a group project, or in a dataset you were both looking at" — so it works with or without a job.

6. **Relevance — PASS.** Every passage serves "what does this job actually consist of." Nothing drifts into pillar-5 territory that isn't in service of the decide/translate/foresee argument.

7. **Transitions — PASS, with one soft spot.** The chronological markers do real work: "Years later, in my clinical data years", "And it's still happening now", "Seeing it coming is the one that is happening to me right now, rather than being a tidy story from the past." But the template's specific instruction is that *"each section ends on a bridge"* that raises the next section's question, and Part 2's close — "Saying no is part of the job. Nobody writes that down anywhere." — is a strong closing line but doesn't point forward into "foresee" the way Part 1's close arguably could have ("Decide what the data means before anyone is asked to trust what it says" doesn't set up "translate" either — it's a recap, not a hinge). This is minor and the video does not lose retention over it, but it is worth naming rather than passing silently, since three sections in a row landing on a summary rather than a forward-pointing question is a pattern, not a one-off.

8. **Clarity — PASS.** Reads as spoken sentences throughout; no jargon without support once item 3's fix is applied.

9. **Template fit — PASS.** Career-thread requirements are all met: hook is a small sharp real moment, not a rhetorical question; credibility beat is short and states the range of chapters; three body sections pull one thread each through different career chapters using chronological markers, never ordinals (the 2026-08-02 fix is still in place); framework assembled and named at the close of Part 3, not announced up front; landing recaps in a line and pivots to next video; sign-off is one line.

10. **Payoff — FAIL, because of the tease.** The exercise itself pays off the hook well — the viewer is asked to notice the same kind of unresolved-meaning argument the client field started. But "deliver... pivot into the next video with a problem-led tease" is a structural requirement of the landing (`CLAUDE.md` §Standard script structure, point 4), and the tease currently fails on both timing and duplication, as detailed above. A landing cannot pass while its final beat points at content the returning viewer has already watched, word for word.

11. **How it goes wrong in practice — PASS.** All three sections show a failure mode with a cause, not just the discipline done properly: the client field (no bug, still wrong, because meaning was never agreed), the three sites (each one confident it was correct), the access requests (handed over "because saying yes was quicker than asking why"), the SQL upskilling (waiting for the go-live date is "the worst possible day to discover your team does not have the skills for it"). This is a genuine strength of the draft.

12. **Recall — PASS.** "Decide, translate, foresee" is nameable and short enough to repeat to a colleague. The client-field image ("clean code, no bug, still wrong") is a picture a viewer could redraw. This is one of the stronger recall scripts reviewed so far.

13. **AI-voice test — PASS.** No delve/crucial/furthermore, no relentless smoothness. "Decide, translate, foresee" and "Different decades, different countries, same job underneath" are the script's only real triads/parallel runs and both are structural rather than decorative — well under the ceiling of concern.

14. **Runtime — PASS. Independently recounted at ~1,041 words (header claims 1,042 — consistent), 7.4 minutes at 140 wpm.** Section breakdown: hook 158, credibility 61, Part 1 (decide) 309, Part 2 (translate) 190, Part 3 (foresee) 161, landing 162. Comfortably inside the 7–8 minute target with no need to discuss the 8–10 minute justification test.

## Prioritised fixes

1. **Rewrite the closing tease.** Cannot be resolved without Aji — see verdict below. Do not let Torch invent a target video or its wording unattended.
2. **Name the discipline in two beats** (item 3): metadata management for the data-dictionary/SOP passage, data minimisation/data governance for the access-policy passage. Mechanical, from `domain-knowledge.md`, Torch can do this alone.
3. **"clinical data years" → "health data years"** (item 4, `voice-profile.md` §9). One word.
4. **Widen the landing exercise so it doesn't require "your organisation"** (item 5). Follow the pattern already used and then retired in Video 1's own edit history.
5. *(Optional, low priority)* Consider whether Part 1 and Part 2's closing lines could point forward rather than only summarise (item 7). Not blocking.

## Verdict: (b) — needs Aji. Torch is not clear to finish this unattended this week.

Fixes 2, 3 and 4 above are all things Torch could make using only material already in the project — `domain-knowledge.md`, `voice-profile.md`, and the precedent already set in `videos/what-is-data-management/final.md`'s own edit history. None of them requires a new decision, a new story, or a placeholder only Aji can fill.

**Fix 1 is the blocker, for two independent reasons, either of which is sufficient on its own:**

- **The tease's target is genuinely undecided.** The only confirmed next-published video is #4, which has no brief and is not yet approved to be scripted. Committing this script to teasing it is a sequencing decision, and `backlog.md`'s own note on this exact defect says it *"needs Aji and Torch"* — that instruction already exists in the project, this assessment is not inventing it.
- **This video's own backlog entry states it is not proceeding to film without Aji regardless**: *"Aji is rebuilding every pre-process video through the pipeline step by step with her own input, so this one goes back through review with her rather than proceeding to film."* That is a standing instruction wider than the tease problem, and it means even a script that passed every other item on this checklist would still route through her before being marked Reviewed.

**One-line verdict: not ready to film, and not a script Torch should finish alone this week — the closing tease needs Aji's decision on what comes next and how to word it; everything else is a fixable one-more-pass.**
