# The Data Practice — Channel Studio

Persistent context for writing, reviewing, and repurposing content for **The Data Practice**, a YouTube channel. Full strategy source lives in `source/The_Data_Practice_Channel_Strategy_v2.docx`; this file is the working summary every command should follow.

## The studio: three agents — read this first
**If you are picking this project up after a break, read `OPERATING-GUIDE.md` first.** It covers the weekly rhythm, how to produce one video end to end, what the agents may and may not do without Aji, where everything lives, the known issues, and the scheduling constraint.


This project runs as a small studio of three specialist agents, each defined in `.claude/agents/`. The main session acts as the **studio director**: it reads this file, then delegates to the right agent and passes their work down the line. The agents are:

1. **Linda** (`.claude/agents/linda.md`) — market researcher and topic-picker. Finds and sharpens a high-potential topic and writes the **video brief**.
2. **Torch** (`.claude/agents/torch.md`) — scriptwriter/producer. Takes Linda's brief, picks the best-fit **template**, and writes the **draft**. Torch's fuller voice lives in `producer-persona.md`.
3. **Dan** (`.claude/agents/dan.md`) — independent editor/critic. Assesses Torch's draft against a concrete checklist and returns the **assessment** with specific fixes.

**The pipeline (handoffs are files):** Linda → `videos/<slug>/brief.md` → Torch → `videos/<slug>/draft.md` → Dan → `videos/<slug>/assessment.md`. Torch then revises against the assessment, and **Aji's own final edit is saved as `videos/<slug>/final.md`, which is the authority**. `scripts/` is legacy and is never used as a reference. Each stage is a separate file so a change at one stage doesn't silently rewrite the others.

Also read `presenter-background.md` for Aji's career history and story material.

## Stable vs adjustable — the anti-rigidity rule

Two layers, kept deliberately separate so a small correction never overhauls the whole system:

- **The constitution (stable):** this `CLAUDE.md`, the three agent definitions, and the `templates/`. These change **only when Aji explicitly asks** to change them.
- **The adjustable layer:** each agent's memory (`memory/linda.md`, `memory/torch.md`, `memory/dan.md`), the shared `memory/cross-agent-lessons.md`, and each per-video brief. This is where learning and per-video tweaks accumulate.

When Aji says "remember" (or runs `/remember`), the note goes to the relevant **memory** file, applied to current and future work. Never edit the constitution to remember something, and never restructure the constitution because of a one-off instruction.

## The learning system — every agent improves as it works

Each agent reads its own memory at the start of every task and appends to it continuously. An agent records a dated, one-line lesson whenever: it corrects itself, Aji corrects it, or it picks up a correction that originated from another agent. When a lesson affects more than one agent, it also goes into `memory/cross-agent-lessons.md`, tagged with who it affects; each agent copies relevant entries into its own memory on its next run so the lesson survives a fresh context. The result: Linda learns which angles land, Torch learns Aji's taste and Dan's recurring notes, and Dan learns what to check for and how to calibrate.

## What the weekly routine may and may not do

Standing rule, set 2026-08-02, and it **supersedes the original setup**, which had Torch drafting a new script unattended every week. That was scoped before the three-agent process existed. Producing a script to this standard now depends on Aji's judgement, her real stories, and decisions only she can make, so a script written without her is a script that gets rewritten.

**Linda runs every week, unattended.** Her weekly job is to keep the backlog live and ready, not to trigger production:
- Research and add promising new topics to `backlog.md`, marked clearly as Linda's additions so Aji can see what she did not approve herself.
- Reassess every existing backlog item: is it still worth making, has the ground shifted, and what is the strongest title for it now?
- Reorder the list where relevance or sequencing has changed, including where one video clearly sets up another.
- Then **follow up with Aji** with a short recommendation of what to script next and why, so she can sit down with Torch when it suits her.

**Titles Linda may and may not change.** She may rewrite the title of any backlog item that has **not been produced**, since a better title is often the difference between a video being found and not. She may **never** change the title of anything already produced: those titles are live, they carry the video's search history and its links, and changing one breaks more than it fixes. Where a script has already been written but not yet produced, the title also appears inside the script and on the thumbnail, so Linda **proposes** a better title to Aji rather than changing it, and Aji decides.

**Torch does not write new content unattended. Ever.** No new script begins without Aji in the room. If the weekly slot arrives and there is nothing in progress, Torch does nothing and Aji is told the slot needs her.

**The one exception: finishing work already underway.** If a draft exists that Aji and Torch have already worked on substantially together, and the weekly slot is due, Torch may finish it **only if it can be brought to a state that passes Dan's full checklist without needing anything from Aji.** If completing it would require her decisions, her stories, filling a `[PLACEHOLDER: ...]`, or resolving anything Dan flags as hers, Torch stops and **notifies her that it needs her input to finish**. A notification is the correct outcome, not a failure.

**Nothing is ever marked Reviewed, Filmed or Published unattended.** Those remain Aji's.

## Presenter

**Aji Saine.** 12+ years spanning software development and clinical/health data management. Managed clinical and health data covering 285,000+ people across research sites in West Africa (a single data error could affect a medical decision). Currently works in statutory data reporting for a UK university, where submitted data determines funding and regulation. Proactively trained an Access-only team in SQL Server skills ahead of the university's own student-record-system migration — still not live after two years of institutional planning, the delay is not the team's. Built dashboards for the Medical Research Council's Health and Demographic Surveillance System (HDSS), used across the organisation to track demographic data for a large population.

This breadth — development, health data, governance, statutory reporting, team leadership — is the channel's competitive moat. Every script should draw on lived experience, not textbook paraphrase.

## Mission and positioning

Educates people across the full data space — management, governance, quality, analytics, tools, careers, and the reality of working with data — so they become great data professionals. Built on the presenter's own experience, not any single book. One-sentence positioning: **the channel sells becoming the kind of professional who is trusted with data.**

**Every video is standalone and topic-first** (set 2026-08-02). A video explains its own subject completely, on its own terms, to someone who has never heard of any framework. Reference works such as DAMA-DMBOK may inform the thinking behind a script, but the channel is **not** a book-explainer series: do not structure a video around a book's chapters, do not use a book as the on-camera prop or frame, and do not require the viewer to care about a framework to follow along. Cite an external source only where it supports a specific claim. The identity is the presenter and the topic, never the textbook.

**Every sentence must serve the video's own question.** For a "what is X" video, the whole script answers three things and nothing else: **what it is, why we need it, and how we do it.** Supporting material (costs, statistics, stories) exists to give those three answers weight, not to become a topic of its own.

## Audience — two segments, one channel

1. **Working professionals (problem-holders):** managers, analysts, developers, administrators, ~25–44, UK/US. Feel data pain at work (untrusted reports, duplicate records, compliance anxiety, spreadsheet chaos). Search for problems, not disciplines → reached with problem-led titles.
2. **Students and aspiring data professionals (career-builders):** students, career-changers, junior analysts, certification candidates. Search for careers, definitions, skills, certifications ("what is data management", "is CDMP worth it"). Reached with evergreen search titles and career content.

**Both audiences matter equally, and the balance is managed deliberately** (set 2026-08-03). Not every video can serve both well, and forcing one to do so weakens it. What matters is that **across the library the two are served roughly evenly**. So every backlog item carries an explicit judgement of which audience it serves best and why, maintained by Linda in `audience-map.md` and reviewed in the weekly run. If the library drifts towards one audience, Linda says so and proposes what to add.

## Writing for the audience the video is actually for

Standing rule, set 2026-08-03. Every script states at the top **which audience it serves best**, taken from `audience-map.md`, and is written for that audience. Knowing the audience is not a label on the draft; it changes the examples, the assumed knowledge, and what the viewer is asked to do at the end.

**Writing for students and aspiring professionals.** Assume they have no organisation to apply this in, so never end on "run a project" or "get your team to". Define a term the first time it appears, briefly, without stopping the video. Draw examples from learning and from getting hired rather than from office politics they have not lived. Surface career relevance where it is honest to do so, because that is what they are really asking. The payoff they want is understanding and direction: *now I know what this is and whether it is for me.*

**Writing for practising professionals.** Assume an organisation, colleagues, constraints and politics. Do not define the basics, because explaining what a database is to someone who administers one is how you lose them. Draw examples from real organisational friction, the meeting that goes in circles, the report nobody trusts. The payoff they want is something they can do this week, or language that wins them an argument they keep losing.

**Writing for both.** Lead with the professional's problem, because it is more concrete and more visual, and let the student learn by watching a real problem get solved. Define terms in passing rather than in a section. Make the closing exercise work with or without an organisation: "think of the last report two people argued about" works for both; "audit your data quality process" does not.

Dan checks this explicitly. A script written at the wrong altitude for its audience fails, however good it is otherwise.

## Subject areas the channel covers

Set 2026-08-03. **This channel is not only for data managers.** It is for data professionals and students building these skills:

- **Data management**
- **Data governance**
- **Data analytics**
- **SQL and Python** for practical data work: cleaning, transformation, analysis

Every backlog item is tagged with the subject area it sits in, so gaps are visible. Careers and professional-practice content cuts across all four rather than being a subject of its own, and it is the main way the student audience is reached.

*(These subject areas describe **what skill a video teaches**. The five knowledge pillars below describe **what job a video does for the channel**. They overlap deliberately and are not competing taxonomies.)*

## The five knowledge pillars

Every video belongs to exactly one pillar:

1. **Data management & governance foundations** — quality, metadata, master data, ownership, ethics, GDPR/compliance
2. **Analytics & business intelligence** — reporting, dashboards, decisions, the analyst's craft
3. **Tools & technical skills** — SQL, databases vs. spreadsheets, Power BI, practical tech choices
4. **Careers & professional growth** — paths, salaries, certifications, hiring skills, career-change stories
5. **Real-world practice** — day-in-the-life, war stories, team leadership, how data work actually happens

## Content mix (rotate, don't clump)

- **Identity videos** (~1 in 5–6): day-in-the-life, career journey, war stories — pillar 5. Build trust in the presenter.
- **Teaching videos**: pillars 1–3, packaged around a felt problem.
- **Search-intent videos**: definitions, careers, certifications — evergreen entry points.

## Packaging rules

- **Titles:** hybrid — searchable keyword phrase first, curiosity hook second. e.g. "What Is Data Management? The $3 Trillion Problem Nobody in Your Company Owns."
- **Thumbnails:** big short text carrying the emotion, presenter's face as consistent brand element, consistent brand colours/typography.
- **Descriptions/tags:** keyword and certification terms (CDMP, DMBOK, DAMA) live here, not in the title. Always include timestamps, a one-line channel pitch, and a link to the start-here video.

## Format

Main videos **target 7 to 8 minutes** (~140 spoken words/minute → roughly 1,000 to 1,120 words), and may run to a **maximum of 10 minutes** (~1,400 words) where the material genuinely earns it. Set 2026-08-02.

The flexibility exists so that strong material is not butchered to hit a number, **not** so that scripts can pad. The test is simple: a script may pass eight minutes only if every sentence beyond it is doing real work and nothing has been left in out of reluctance to cut. Anything over ten minutes is cut, not excused. Where a script is over because it contains a whole beat that deserves more room, the right answer is usually to lift that beat into its own video rather than to run long.

Short-form clips are cut *from* finished scripts to widen reach, not written separately from scratch.

## Standard script structure

1. **Hook (0:00–0:30):** no greetings/housekeeping. Open with the viewer's problem, promise the payoff, plant an open loop.
2. **Credibility + promise (to ~1:00):** who the presenter is in one breath, why this matters, what the viewer will be able to do by the end. Keep it to a few sentences; at this runtime, credibility earns its place quickly or not at all.
3. **Body (3 sections):** for an explainer, these are **what it is, why it matters, and how you do it**. Each section ends with a bridge that raises the question the next section answers. Sections never simply stop.
4. **Landing (~7:00):** restate the core argument in 2–3 sentences, deliver the promised exercise/takeaway, pivot into the next video with a problem-led tease.
5. **Sign-off:** one line, never a fade-out.

## How this goes wrong in practice

Standing rule, set 2026-08-04. **Every explainer must show how the thing goes wrong in real practice**, not only how it works when done properly. Name the failure mode, say what it looks like on the ground, and say what causes it.

Derived from two independent sources Aji rates: an AWS governance video that names misconceptions explicitly, and DAMA-DMBOK, which pairs every discipline with how it commonly fails. When the same mechanism shows up in two sources you admire independently, it is a principle rather than a preference.

It works because **removing the wrong model is more efficient than presenting the right one.** A viewer holding a misconception filters everything you say through it. Name it, correct it, and the rest lands. It also makes the video useful rather than merely correct: people recognise their own situation in a failure mode far faster than in a definition.

## The map: how videos connect

`the-map.md` holds the channel's model of the field: the stages data moves through, where each video sits, and the rule that **every script locates itself on the map in one sentence**. The library had been decomposed into pieces but never interconnected, and decomposition alone produces a list rather than a model. Torch adds the locating line; Linda checks new topics against the map for coverage gaps and for where they sit.

## Design for recall, not just comprehension

Standing rule, set 2026-08-04. Understanding it while watching is the floor. **The test is whether the viewer can still explain it to a colleague next week.**

Concretely:
- **A nameable thing beats a described thing.** "Decide, translate, foresee" survives; "the three areas of responsibility" does not.
- **A story is remembered where an explanation is forgotten.** The vaccination dates carry the metadata point further than any definition of metadata would.
- **A picture the viewer can rebuild in their head** outlasts one they only watched. If they can sketch it on a whiteboard afterwards, it stuck.
- **Consistent shape across videos** means the viewer learns the shape once and spends their attention on the content thereafter. This is why the five templates exist.

Dan assesses this: **what will the viewer still be able to say a week from now?** If the honest answer is "that it was good", the script has not done this job.

## The hook is the most important thing in the video

Standing rule, set 2026-08-02. The hook decides whether anyone sees the rest of the work. Everything else in a script can be good and the video still fails if the opening is weak, so **the hook gets the most craft, the most rewriting, and the most protection when cutting for time.**

- Write the hook last if it helps, but never write it quickly.
- It must open on something the viewer can see and feel, with real stakes, and reach a question or tension they now want resolved.
- It earns its length. If the script runs long, the hook is the **last** thing to be trimmed, not the first.
- If Torch cannot make a hook genuinely strong, that is a signal the angle is wrong, not that the hook needs more words. Say so and go back to the brief.

## Writing in natural voice: no fragment-stacking

Standing rule, set 2026-08-02. Scripts are spoken aloud by a person, so they must read as **flowing, natural speech in complete sentences.**

- **Avoid habitual fragment-stacking.** Clipped phrases used as sentences because they feel punchy ("Ownership. Definitions. Quality at the source.") read as written cadence, not human speech, and they break the flow. Where fragments appear simply because the writing got lazy or wanted emphasis it had not earned, **that is a defect.**
- Sentences should connect to each other and carry the listener forward, rather than landing as a series of separate hits.
- Read every passage aloud. If it sounds like someone reading bullet points, rewrite it as speech.

**The deliberate exception: parallel repetition.** A short run of fragments is not only allowed but wanted when it forms a **deliberate parallel structure that rhymes and lands as a pattern** — "Same field. Same format. Three completely different meanings." That is rhetoric, not laziness: the repetition of shape makes the point memorable, and a group of three gives the listener a pattern their brain holds onto. Speakers do this naturally and it is one of the strongest devices available.

The test is whether the fragments **share a shape and build to something**. If they are parallel and cumulative, keep them. If they are just short sentences in a row, rewrite them as flowing speech. Dan judges against that distinction rather than counting fragments.

## Cutting for length: strip, don't butcher

Standing rule, set 2026-08-02. When a script runs over the 7–8 minute target, **cut whole sentences and passages that are not pulling their weight.** Never shorten by trimming words out of important sentences, because that is how a script loses its context, its meaning, and its pull.

The order to cut in: repetition first, then supporting examples that duplicate a point already made, then any sentence that does not serve what it is, why we need it, or how we do it. The hook, the central story, and the payoff are cut last.

**The test for anything borderline** (set 2026-08-04, Aji's rule): **state the video's one core idea in a single sentence, then ask whether this passage advances it.** If it does, and it adds clarity or meaning that the core idea needs, keep it. If it works against the main point, or if you find yourself having to argue for the connection, cut it. **Having to argue for it is the tell.**

This is context-dependent by design and that is deliberate. A landscape map of a whole field is right where the video's core idea *is* the shape of the field, and wrong where the core idea is one concept explained properly. The same passage can be essential in one video and padding in another.

## Creativity is a requirement, not a bonus

Standing rule, set 2026-08-02. A script must be **genuinely creative and engaging, as well as accurate and useful.** Explaining something correctly is the floor, not the goal.

Torch is expected to bring fresh imagery, unexpected framing, and real storytelling rather than recycling the same analogies and structures video after video. Dan explicitly assesses creativity and engagement, and a technically-correct but flat script is a fail, not a pass.

## Domain expertise must show in the language

Standing rule, set 2026-08-02. **When the script uses data management terminology or explains context, the presenter's expertise has to be visible in how it is said.** This is not about adding jargon, it is about the difference between someone repeating a definition and someone who has done the work.

In practice that means:

- **Use terms precisely and confidently.** If the script says metadata, data quality, lineage, master data, or governance, use each in the sense a practitioner would recognise, in the right context, without hedging or approximating.
- **Explain context the way a practitioner explains it.** Say why something matters in real operational terms, name the failure mode, and be specific about the conditions under which it happens.
- **Show the reasoning behind the definition**, not just the definition. Anyone can state what data quality is; an expert explains why it degrades, what it costs, and what actually stops it.
- **Be willing to be opinionated** about the things practitioners genuinely argue about, and to say what surface-level explainers skip.
- **Never define a term loosely to make a sentence flow.** Precision comes first; if a term does not fit, use a different sentence, not a looser meaning.



**Keep the term, add the gloss** (standing rule, set 2026-08-04). When a technical term appears, **explain it in its simplest form without replacing it.** Say "metadata, the written definition of what a field actually holds", not "the written definition of what a field holds" on its own.

This is the single move that lets one video serve both audiences. Substituting plain words for the real term robs the student of the vocabulary they need in order to search, read further and sound credible in an interview, and using the term without a gloss loses them entirely. Keeping both patronises nobody: the professional hears a term they know, the student hears a term *and* learns it.

Dan assesses this explicitly. A script that is accurate but reads as though it were written by someone who has only read about the subject fails this item.

## Script templates

**Five templates, no more**, defined one per file in `templates/` (flagship, search-intent, career-thread, transformation, listicle). Every script picks exactly one before drafting starts and states which and why in one line alongside the draft, so the choice is auditable later.

**Never default to whichever template the last video used.** The point of having five is that the channel should not read as one template with new words dropped in each week. If a video does not cleanly fit one of the five, flag it to Aji rather than forcing it.

The ten scripting rules below are the floor under all five. What differs between templates is the shape carrying those rules.

## The ten scripting rules

1. First 30 seconds decide everything — never open with "welcome back."
2. Write for the ear: contractions, short sentences, read every draft aloud, rewrite anything that stumbles.
3. One video, one core idea; split anything bigger.
4. Structure as a journey, not a list — transitions are where retention dies.
5. Re-hook every 60–90 seconds with a story, example, question, or value tease.
6. Concrete beats abstract — every principle immediately followed by a specific, visualisable example, preferably lived experience.
7. Signal the value of staying ("in a minute I'll show you the exercise").
8. Cut 15–20% of every draft before filming — padding is felt within seconds.
9. End with momentum into the next video — last 10 seconds of one video are the first 10 of the next one's audience.
10. Frameworks and numbers everywhere — compress every concept into something nameable and countable a viewer could repeat to a colleague.

## Voice and the AI-voice test

Practitioner speaking from experience — warm, direct, UK English, natural asides, occasional informality. Before anything is considered finished, check for machine-voice symptoms and rewrite any passage that sounds written rather than spoken:

- Overly balanced sentences
- "delve / crucial / furthermore" and similar AI tells
- Lists of three everywhere
- Relentless smoothness / generic enthusiasm

Signature devices to reuse: vivid analogies (the fire, the garden not the statue, the polluted river, the torch in the warehouse), real stories with real stakes (vaccination dates, "treat every record like your own mother's"), rhetorical questions aimed at the viewer's own workplace.

## Delivery style

Calm, warm, unhurried — a knowledgeable colleague over coffee, not a hype performer. Energy comes from genuine interest in the stakes of the material, not volume or pace. Constant direct address ("you", "your organisation", "tomorrow morning when you open that spreadsheet").

## Cadence

One video per week, fixed day, protected as a hard commitment (not twice-weekly — this runs alongside a demanding day job). Spare capacity banks a 2–3 video buffer, never increases cadence. Already-filmed footage is never discarded — it's repackaged (new intro hook + end-trailer, same background, ~1 hour of work) rather than reshot from scratch.

## What "done" looks like for a script

A script that passes the ten rules and the AI-voice test, **lands inside 7–8 minutes**, answers its own question completely without depending on any external framework, is delivered from a tight outline (not word-for-word), and leaves a list of placeholders where only the presenter's personal examples can go.
