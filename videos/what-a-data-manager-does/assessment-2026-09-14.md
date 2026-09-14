# Assessment — What a Data Manager Actually Does All Day (draft, re-review)

*By Dan, 2026-09-14. This is a fresh, independent pass on `videos/what-a-data-manager-does/draft.md`, done as part of the weekly unattended run. The 2026-08-02 `assessment.md` is prior context only — I have re-derived every verdict below rather than inheriting it. Reviewed against `CLAUDE.md`, `templates/career-thread.md`, `voice-profile.md`, `domain-knowledge.md`, `audience-map.md`, `presenter-background.md`, `the-map.md`, `backlog.md`, and `memory/torch.md`.*

Word count independently recounted section by section: **1,041 words ≈ 7.4 minutes at 140 wpm.** This matches the draft's own header (1,042 words / 7.4 min), so for once the stated figure and my count agree — but I counted it myself rather than trusting the header, per standing rule.

---

## The specific check requested: the closing tease

Draft's closing line: *"Next time I want to show you the data mistake that has cost companies hundreds of millions in fines, and almost nobody who made it saw it coming."*

Cross-checked against the **current** `backlog.md`:

- This video is position **3**.
- Position **2** is "The Data Mistake That Cost Companies Hundreds of Millions (And Nobody Saw It Coming)" — status **"NEXT TO SCRIPT — confirmed by Aji 2026-08-03,"** i.e. scheduled to be produced and published **before** position 3.
- `backlog.md` itself already flags this, verbatim: *"Broken tease, needs fixing before filming: `videos/what-a-data-manager-does/draft.md` (now position 3) ends by teasing the data-mistake video, which under the new order publishes before it. That closing tease has to be rewritten to point forward, not back."*

**Plainly: yes, it's broken, and it is not a borderline call.** The tease promises a "next time" video that, under the current roadmap, will already be sitting on the channel by the time this one publishes. A viewer who watched the videos in order will get a tease for something they've already seen; a viewer who hasn't will click through and find it already live, which reads as a scheduling mistake rather than a hook.

**This is fixable without Aji.** The natural forward target is whatever currently sits at position 4 — "Why nobody trusts your reports (and how to fix it)" — which is itself a problem-led title that a tease can point at cleanly (e.g. something like: *"Next time, why nobody trusts your reports, and what actually breaks the trust first."*). Torch can retarget this using `backlog.md` alone; no new story, decision, or placeholder from Aji is required. Flag for whoever does this: if the backlog order shifts again before filming, this tease is exactly the kind of cross-reference that rots silently (see `memory/cross-agent-lessons.md`, 2026-08-03 entry on rotting cross-references) — recheck it once more immediately before filming.

---

## Checklist

**1. Hook — PASS.** The "client" field story is a genuinely strong opening for this template. *"It worked perfectly. The code was clean, the validation passed, and there was not a single bug anywhere in it... Nobody had ever agreed what 'client' actually meant before the form went live. I could not fix that with better code."* It opens on something visible (a form field, two different kinds of answer typed into it), it has real stakes (a live system quietly recording two different things as one), and it reaches a tension the viewer wants resolved: if better code can't fix it, what does? The turn earns the promise. This is a career-thread hook doing exactly what the template asks — a small, sharp, real moment, not a rhetorical question.

**2. Creativity and engagement — PASS.** The three-chapter structure gives genuinely different textures (a software bug that isn't a bug, a reconciliation meeting between three research sites who each believe they're right, a live skills gap she's closing before the deadline forces it). *"Every single site believed they were the ones doing it correctly, and they each had a reasonable argument"* is a good image of the work as negotiation, not technique. Nothing here recycles the channel's existing analogies (fire, garden, river). The vaccination-dates material is handled correctly as a callback-plus-new-resolution rather than a re-run of Video 1's version.

**3. Domain expertise in the language — PARTIAL.** Verbs and terms are mostly precise (*data dictionary, standard operating procedures, personal data, data access request policy*), and the valid-but-wrong distinction underneath the client-field story is implicit and correct. Two specific gaps:

- **The vaccination/data-dictionary passage never names the discipline it is an example of.** *"We built a data dictionary, we wrote standard operating procedures for how the data was captured, and we trained every site against both."* This is a **metadata management** failure and fix, and saying so is exactly the instruction already recorded in `memory/torch.md` (2026-08-02): *"Name the specific discipline a story illustrates... The vaccination case is a metadata management failure, and saying so is what makes it expert rather than explanatory."* This draft doesn't apply its own established lesson.
- **The data access request passage never names its discipline either.** *"We introduced a data access request policy: state what you need, state why, we assess that against what you actually need... It is the difference between an organisation that hands out personal data because somebody asked nicely, and one that can account for who holds what."* This is **data governance** in action (an access-control decision right, close to `domain-knowledge.md`'s data minimisation — "collecting and supplying only what is adequate, relevant and necessary"), and it floats without the word.

Fix: one clause each. E.g. *"That's metadata management — deciding what a field means before the data gets trusted"* after the data dictionary sentence, and *"That's data governance — deciding who gets to see what, and being able to say why"* after the access-policy sentence.

**4. Aji's voice — PARTIAL, one real finding.** The restraint register is right throughout (*"getting it wrong in either direction has real consequences for a public health programme"* matches her established preference for measured stakes over dramatisation). But the credibility beat has a problem voice-profile rule 3 exists to catch:

> *"My name is Aji Saine, and I have over twelve years of combined experience in software development and data management. I looked after health records for more than 285,000 people across research sites in West Africa, and today I handle statutory data reporting for a UK university."*

I checked this against `videos/what-is-data-management/final.md` (the live, approved Video 1), which contains, almost word for word:

> *"I looked after health records for more than 285,000 people across research sites in West Africa, **where a single data error could affect a medical decision**, and today I handle statutory data reporting for a UK university **where the data we submit literally determines funding and regulation**."*

This draft has copied that sentence and **cut exactly the two clauses that carry its stakes**, without flagging the reuse or improving on it — which is the precise thing voice-profile rule 3 says not to do ("never drop a line she has already written... a change genuinely improves it, flag the change rather than making it silently"). As it stands the line is a weaker echo of a sentence a viewer of Video 1 will recognise. Two acceptable fixes, either is fine: restore the stakes clauses (they are true and already hers), or write this beat fresh for this video, since here the three career chapters are the whole subject of the body rather than a one-line credential — the body already re-tells West Africa and the university in far more depth, so the credibility beat doesn't need to duplicate Video 1's exact phrasing at all. I'd lean toward the second: a fresh, shorter credibility line here, since the chapters get properly unpacked seconds later.

**5. Audience fit — PARTIAL, one specific, fixable defect.** `audience-map.md` states this video's stated audience correctly: *"Serves best: S... Career exploration first: is this the job for me."* The body is genuinely well-pitched for that: it teaches by showing the career, not by requiring the viewer to have one, and it surfaces career relevance honestly throughout. The one place it breaks the rule is the closing exercise:

> *"Think about the last time two people in your organisation disagreed about a number."*

`CLAUDE.md`'s own worked example for this exact failure mode says: *"'think of the last report two people argued about' works for both; 'audit your data quality process' does not"* — the model phrasing deliberately avoids the word "organisation." This draft's version puts it back in, which asks a student with no employer to imagine one. Fix is small and precise: drop "in your organisation" — *"Think about the last time two people disagreed about what a number actually was"* — which works in a group project, a part-time job, a student society, or an office, and still calls back to the hook's client-field dispute just as well.

**6. Relevance — PASS.** Every passage serves the decide/translate/foresee argument; nothing drifts into a side topic.

**7. Transitions — PARTIAL.** Within each part, the chronological markers are used correctly and are genuinely good (*"Years later, in my clinical data years..."*, *"And it's still happening now"*, *"is the one that is happening to me right now, rather than being a tidy story from the past"*). But `templates/career-thread.md` also requires, explicitly: *"Each section ends on a bridge."* None of the three part-endings does this — each closes on a summary of its own point rather than raising the question the next part answers:

- Part 1 ends: *"Different decades, different countries, same job underneath. Decide what the data means before anyone is asked to trust what it says."* — restates Part 1, doesn't open a door to translating.
- Part 2 ends: *"Saying no is part of the job. Nobody writes that down anywhere."* — same pattern; doesn't open a door to foreseeing.

Fix example for Part 1→2: something like *"But agreeing what something means only holds if it survives contact with the people who weren't in the room when you decided it."* Fix example for Part 2→3: *"Deciding and translating both happen because somebody brought you a problem. The last one is the part where nobody brings you anything at all."* These are illustrative, not prescriptive — the point is that a genuine forward-pointing bridge is currently missing at both joints, which is a template-fit requirement, not a nice-to-have.

**8. Clarity — PASS.** Reads cleanly for the ear throughout; nothing stumbles aloud.

**9. Template fit — PARTIAL**, tracking the transitions finding above (career-thread explicitly requires bridges at the end of each section, and this draft doesn't have them) but otherwise strong: chronological markers used correctly (the ordinal-label defect from the 2026-08-02 pass has stayed fixed), the framework is assembled piece by piece and named only at the end (*"Decide, translate, foresee"*), and the credibility beat correctly states the breadth of chapters before the body draws on them.

**9a. Payoff — PASS**, with the audience-fit caveat above. The landing correctly recaps the argument in three sentences and the exercise calls back to the hook's dispute. Fix the "in your organisation" phrase (item 5) and this is clean.

**9b. How it goes wrong in practice — PASS.** Every beat shows a real failure, not just the fix: the client field silently recording two different things, three sites each certain they were right, requests for "all of it, no scope and no stated purpose" being granted because saying yes was quicker than asking why, and a migration timeline that "keeps slipping" while the team's skills stand still. This is a script full of failure modes, which is exactly what the standing rule asks for.

**9c. Recall — PASS.** "Decide, translate, foresee" is nameable and quotable to a colleague next week. The client-field story is a picture a viewer could redraw (a form, one field, two different kinds of answer typed into it). The reconciliation meeting where three sites are each certain they're right is a strong secondary image.

**10. AI-voice test — PARTIAL, minor.** One sentence stacks two rule-of-three lists back to back: *"You stand between the language of a system, its **tables and keys and fields**, and the language people actually use in a meeting: **the student, the return, the case**."* Individually each triad is fine and concrete, but two in one sentence reads as classic list-cadence. Recommend cutting one — the "student, the return, the case" triad is the more vivid of the two and should stay; consider flattening "tables and keys and fields" to "its tables and its fields." No other AI tells found (no delve/crucial/furthermore, no relentless smoothness).

**11. Runtime — PASS.** 1,041 words independently recounted, 7.4 minutes at 140 wpm — comfortably inside the 7–8 minute target, no cutting required.

**Map locating line — MISSING.** The standing rule (`CLAUDE.md`, set 2026-08-04, after this draft's last review on 2026-08-02) requires every script to locate itself on `the-map.md` in one sentence. This draft predates that rule and has no such line. Per `the-map.md`, position 3 sits under "The people" — the video could locate itself with one line near the top or the landing, e.g. *"Everything so far has been about the data itself — this is the same journey, seen through the person actually doing the work."* This needs adding; it costs no real runtime.

---

## Prioritised fixes for Torch

1. **Fix the broken closing tease.** Retarget from the data-mistake video (position 2, publishes first) to whatever currently sits next in `backlog.md` (position 4 at the time of writing). Recheck immediately before filming in case the order has shifted again.
2. **Rewrite the credibility-beat sentence** so it isn't a stakes-stripped copy of Video 1's approved line. Either restore the two stakes clauses or write it fresh for this video (recommended, since the body unpacks both chapters properly seconds later).
3. **Name the discipline in two Part 1 beats:** metadata management (data dictionary/vaccination story) and data governance (access request policy story). One clause each.
4. **Add a genuine bridge to the end of Part 1 and Part 2**, per the template's explicit requirement, so each section raises the question the next one answers instead of just closing.
5. **Fix the closing exercise**: drop "in your organisation" so it works for a viewer with no workplace.
6. **Add the one-sentence map locator**, anywhere near the top or the landing.
7. **Minor: de-stack the two back-to-back triads** in the translating section.

None of these require a new story, a placeholder, or a judgement call that only Aji can make — every fix draws on material already in the project (`presenter-background.md`, `domain-knowledge.md`, `voice-profile.md`, `backlog.md`, `the-map.md`, and the anecdotes already approved in `memory/torch.md`).

## Verdict

**One more pass — not ready to film, and not a structural rewrite.** The hook, the core material, the framework, and the runtime are all genuinely strong and none of that needs to change. **This draft does NOT need anything from Aji to reach a full pass** — no unresolved decision, no missing story, no placeholder, nothing Dan is flagging as hers to call. Every fix above can be made by Torch using files already in the project. Recommend Torch takes this straight through a revision pass against the list above and returns it for a second look before it goes anywhere near filming.
