# Torch — Memory (continuous learning)

Torch reads this file at the **start of every task**, and appends to it whenever:
- he corrects himself mid-draft,
- Aji corrects a draft or states a preference, or
- Dan (or Linda) flags something that Torch then fixes (check `cross-agent-lessons.md`).

Write each lesson as a **dated, one-line rule for next time**, newest at the top of the right section. This is the *adjustable* layer and grows continuously. It is **not** the constitution (`CLAUDE.md`, the agent definitions, the templates), which changes only when Aji explicitly asks. `/remember` writes here, never to the constitution.

*(Migrated 2026-07-22 from the old `producer-memory.md`.)*

## Style and voice preferences
- 2026-07-20 — **Five-template system locked** (now one file per template in `templates/`): flagship teaching / search-intent direct-answer / career-thread multi-chapter reflection / transformation-origin-story / listicle. Replaces the old "standard structure + identity structure" split, and replaces my earlier proposed "day-in-the-life (time-anchored)" slot after Aji pushed back. Video 1's reviewed draft (multi-chapter, framework-driven) IS an official template now, not a one-off hybrid. **Every script picks one before drafting and states which and why; never default to the last video's template.**
- 2026-07-20 — **Identity videos frame around the role and the work itself** (what a data manager does, the decisions, the craft), **not around a specific employer or location**. Personal workplace details are supporting examples, never the organising frame. Applies to Video 1 and likely videos 7 and 13. *(I overcorrected once by proposing a literal "day-in-the-life" template; this preference is why that was wrong.)*
- 2026-08-02 — **`voice-profile.md` now exists and outranks my instincts about good prose.** Built from Aji's own final edit of the data management script. Read it before drafting, every time.
- 2026-08-02 — **The five things she changed most, so write them right first time:**
  1. **Cut the flourish.** She deleted nearly every decorative phrase I was pleased with ("the server humming away in the cupboard nobody ever opens", "someone would write you a cheque", "That agreement is the work"). If a sentence only sounds good, it goes.
  2. **Be restrained, not dramatic.** She replaced "it is a child who never got a vaccine" with "in public health a wrong conclusion is costly", and "criticised a month later" with "having to redo them". Her authority comes from being measured.
  3. **Do not replace her existing lines.** She restored several from the earlier produced script, including "I'm not quoting a textbook. I have lived it." Default to her wording; flag a proposed change rather than making it.
  4. **Canonical definitions verbatim.** She restored "development, execution and supervision", "programs and practices", "enhance the value". Never paraphrase the discipline's formal definition.
  5. **Statistics carry source, year and the exact figure, written for the ear.** "According to the Gartner research from 2020... twelve point nine million dollars a year."
- 2026-08-02 — Smaller preferences: name the actual department ("that's finance, it's people, HR") rather than describing it; join clauses with "but"/"and" so they flow, except deliberate parallel repetition; open a section with the question it answers; signpost callbacks ("those vaccination dates I mentioned earlier"); "our profession" not "my profession"; "consequences" not "harm"; "health data" not "clinical data"; "today" not "on Monday".
- 2026-08-02 — When quoting a statistic on camera, name the source inline and keep the figure consistent across title, thumbnail, and script (Dan flagged a title/body mismatch: "$12 Million" vs "twelve to thirteen million"). Aji fact-checks, so never present a number as settled without attribution.
- 2026-08-02 — Watch runs of very short punchy fragments; one or two per section is punch, a whole section of them reads as written cadence, not speech. Let some breathe.

## Scripting lessons
- 2026-08-02 — **Domain precision costs runtime, so budget for it from the first draft.** Adding proper domain language to the data management script (lifecycle and destruction, valid vs accurate, business metadata, data owner vs data steward, business glossary, personal data) added about 150 words and took it from 9.1 to the 10-minute ceiling. Do not write a script to length and then add expertise; write it expert from the start and cut elsewhere. Where a distinction needs more room than the video can spare, propose it as its own video instead of compressing it.
- 2026-08-02 — **The domain-language gap, and the fix.** Aji caught "the most expensive way to **run** anything" and expected "the most expensive way to **manage** data", because *we manage data, we do not run data*. Root cause: Torch's original definition said his job was packaging, not domain authority, so he wrote like a producer. That has been corrected: Torch now has **data management and governance as an explicit second skill**, with `domain-knowledge.md` as the reference to read before drafting. **Run the verb check on every draft**: for each verb attached to data, would a practitioner use that word for that thing?
- 2026-08-02 — **Aji's editorial preferences, confirmed on the data management script:**
  - Open with **"Let me ask you a question."** It makes the viewer brace rather than settle.
  - Keep **"But what about your data?"** followed by the concrete list: twenty years of customer records, patient histories, student records, transactions. Each item catches a different part of the audience.
  - Prefer a **direct question aimed at the viewer's own workplace** over an observation they can nod at ("So who in your organisation manages the data?" beats the furniture line).
  - Define data management with **plans, policies, procedures and practices** in it. She wants procedure and practice named explicitly, because that is what actually improves and secures data.
  - **Name the specific discipline** a story illustrates, not just the general principle. The vaccination case is a **metadata management** failure, and saying so is what makes it expert rather than explanatory.
  - Restore **"Data is like water in a river. If it is polluted at the source, everybody downstream drinks polluted water."** as written.
  - **Use parallel repetition deliberately.** "Same field. Same format. Three completely different meanings." is wanted: it rhymes, and a group of three gives the brain a pattern to hold. This is rhetoric, not fragment-stacking; the rule was revised to say so.
  - Avoid compound questions that blur two ideas. "Ask five people what counts as an active customer and you will get five answers" beats "what exactly counts as an active customer, and at what point is a student enrolled?"
- 2026-08-02 — **Stakeholder engagement belongs in the "how" of any governance topic**, inside the ownership move rather than as a separate one. Naming an owner achieves nothing if the people who create the data were never brought along, and Aji's real material here (reduce their workload, train them, credit them publicly) is stronger than any textbook version.
- 2026-08-02 — **The hook gets the most craft and is cut last.** Aji's standing rule: it decides whether anyone sees the rest. Follow the opening image through rather than dropping it (the fire that insures everything except the data), and close the hook on a question the viewer wants answered, not on a summary of the video.
- 2026-08-02 — **No stacked fragments.** Write flowing complete sentences that carry the listener forward. One deliberate fragment is fine; two or three in a row is a defect. Aji confirmed this after Dan flagged it independently.
- 2026-08-02 — **Cut by stripping whole sentences that repeat a point already made**, never by trimming words out of load-bearing ones. Draft with the ~1,000–1,120 word budget in view: the richer v3 draft came in at 9.9 minutes and needed 300 words removed.
- 2026-08-02 — **Creativity is a pass/fail item, not a bonus**, and scripts must read as a domain expert: specific, opinionated, and willing to say what other explainers skip. Details like "a database has no opinion about meaning" and "upstream checks made the team happier, not just faster" are what separate expert from generalist.
- 2026-08-02 — **Runtime is 7–8 minutes (~1,000–1,120 words), not 15.** Constitution change, agreed with Aji. Count the words before handing to Dan; do not hand over a long script expecting it to be trimmed later.
- 2026-08-02 — **Videos are standalone and topic-first.** Do not frame a script around DAMA-DMBOK or any book, do not use it as an on-camera prop, and do not require the viewer to care about a framework. Reference works can inform thinking; they never provide the structure.
- 2026-08-02 — For an explainer, the whole script answers **what it is, why we need it, how we do it**, and nothing else. Costs, statistics, and stories exist to give those three answers weight, never to become topics of their own.
- 2026-08-02 — Prefer a **picture or story over a statistics run** when making the "why" land (the hidden data factory beat worked better than a list of figures). At most two figures, sourced.
- 2026-08-02 — Watch cumulative **triads**: three moves, three questions, three sites in one script starts to read as the "lists of three" AI tell even when each is individually justified. Vary one.
- 2026-08-02 — State Aji's own results as hers ("in my own team, processing time dropped by about sixty percent"), never as a general finding.
- 2026-08-02 — For a foundations flagship, an AI-era beat works best as a **mid-video re-hook** (bad data → untrustworthy AI), not as the whole frame. Keeps the video evergreen.

## Topics/angles that landed well
_(none logged yet — populate after videos publish and Aji reports performance)_

## Topics/angles to avoid or that underperformed
_(none logged yet)_

## Personal anecdotes bank (approved, reusable)

Stories Aji has confirmed are usable in scripts, so Torch doesn't need to re-ask each time:

- Vaccination dates across three research sites, full resolution (data dictionary + SOPs + cross-site reconciliation meeting where every site believed they were right) — from Video 1
- "Treat every record as if it belonged to your own mother" — from Video 2
- **Access-to-SQL Server: Aji proactively trained an Access-only team in SQL Server skills, ahead of the university's own student-record-system migration (still not live after 2 years of planning — the delay is institutional, not the team's). This is NOT a completed migration Aji led; never frame it that way.** Bio corrected 2026-07-20.
- Early dev-career "client" field ambiguity (organisation vs. individual staff member typed into the same field, no bug, just no agreed definition) — from Video 1
- University data access request policy: team was fielding "give me everything" requests with no scope; Aji introduced a formal request + needs-assessment policy — from Video 1
- Team's data dictionary exists but most of the team didn't know it existed until Aji checked — noted but NOT used in Video 1, good candidate for a future governance/metadata video
- Built dashboards for the Medical Research Council's HDSS (Health and Demographic Surveillance System) — demographic data displays, large population; Aji had standing to assess/reject change requests, including from management — from Video 1
- 285,000+ people across West African research sites — background credibility line

## Scheduling and workflow preferences

- Weekly production run: Mondays (time TBC) — set 2026-07-20
- Full scripts are auto-drafted (not just outlines) per Aji's instruction 2026-07-20 — still flag anything uncertain rather than invent it

## Open questions for Aji
_(add anything you need Aji to answer before it blocks a draft)_
