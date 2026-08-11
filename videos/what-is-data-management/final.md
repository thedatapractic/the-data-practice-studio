# What Is Data Management? The Job Nobody Owns

**Status: FINAL — THIS IS THE AUTHORITY.** Agents do not rewrite this file; propose changes to Aji.
**Source:** Aji's own final edit of 2026-08-02, then reworked across six rounds on 10–11 August with Aji directing and a two-pass Dan review. Promoted into this filename on 2026-08-11. The 2026-08-02 state is preserved unedited as `superseded-final-2026-08-02.md`, which carries a do-not-film banner and is a historical record only.
**Runtime: 9:34. ~1,340 spoken words at 140 wpm.** About 60 words of headroom against the ~1,400 ceiling — the first real breathing room this script has had, freed by round nine's switch from a grouped-and-explained knowledge-area list to a plain one. **A timed read-aloud is still a blocker before filming** (see `pre-filming-checklist.md`), since your delivery is deliberately unhurried and slower than 140 wpm remains possible. Note the counting convention Dan established: a raw word count of this file gives 1,335, and the spoken figure adds five for "285,000" and "2020" being said aloud. For the record, because the figure was wrong three times earlier at different stages: `superseded-final-2026-08-02.md` is 1,398 written words despite its header claiming "~9.5 minutes", and three drafts of this file in turn inherited or briefly hit the ceiling before settling here. **Count, never inherit.**
**Playlist:** Data Foundations
**Serves:** **Both, written at professional altitude with student access points.** Aji's instruction 2026-08-10: keep the professional view, but make it something a student or aspiring professional can follow and learn from. Per `CLAUDE.md`, that means leading with the professional's problem and letting the student learn by watching it solved, and defining terms in passing. *Note: the closing exercise that served both audiences was removed in round eight, so the landing's takeaway is now the eleven knowledge areas — knowledge rather than action. The student access point in Part 3 ("you need no team and no job title for this one") now carries that job alone.*

---

### THE HOOK

So, what is data management?

I have sat in meetings where two people brought the same figure and the numbers did not match. Nobody had lied, nothing was broken, and each of them could show you exactly where their number came from. They were counting slightly different things, and nobody had ever written down which one was right.

No software was going to catch that, because the decision it depended on had never been made, and nobody was responsible for making it. That is the sort of gap data management exists to close.

So let me answer the question properly.

### WHO I AM

My name is Aji Saine, and I have over twelve years of combined experience in software development and data management. I looked after health records for more than 285,000 people across research sites in West Africa, where a single data error could affect a medical decision, and today I handle statutory data reporting for a UK university where the data we submit literally determines funding and regulation.

So when I tell you data management matters, I'm not quoting a textbook. I have lived it. That's why I am going to give you three things that help you understand what data management really is. The what, the why and the how about data management.

### PART 1 — WHAT IT ACTUALLY IS

Here is the plainest definition I can give you. Data management is the development, execution and supervision of the plans, policies, programs and practices that deliver, control, protect and enhance the value of data throughout its lifecycle, from the moment it is created to the day it is properly destroyed.

Notice what is missing from that sentence. There is no software in it and there are no servers, because the biggest misunderstanding about our profession is that managing data is the same thing as managing databases.

When I was managing health data, we recorded vaccination dates for children across three sites. One site recorded the date the vaccine was given. Another recorded the date it was entered into the register, which might be a fortnight later. And we had a third scenario, where a fieldworker recorded their best estimate, from a mother who could only remember it was around the rainy season.

Same field. Same format. Three completely different meanings.

Run a coverage analysis on that and you get a clean, confident and beautifully formatted answer that happens to be wrong, and you based your conclusion on that, but in public health a wrong conclusion is costly.

It is worth naming that failure precisely. Every one of those dates was a valid entry. They passed every format rule, and every range check but they were simply not accurate, because they did not all describe the same event. Validation catches data that is malformed but only knowing what a field means catches data that is wrong.

And here is the part that took me years to properly appreciate. There was nothing wrong with our database. It did its job perfectly, because a database has no opinion about meaning. What was missing was the business metadata, the agreed and written-down definition of what that column actually meant. That has a proper name in our profession and it's called metadata management.

Data management is somebody deciding what a field means, who owns the data, what quality looks like and what happens when it goes wrong, and then writing those decisions down as policy and procedure so they outlive the person who made them.

Every organisation has someone managing its money, that's finance, it's people, HR, and it's buildings and equipment. So who manages the data?

Which brings me to the question I get asked most often. If nobody is doing this, what are the consequences?

### PART 2 — WHY YOU NEED IT

Imagine there is a factory operating inside your building that nobody ever told you about. It runs all day, every day, it quietly employs a surprising number of your colleagues, and everything it produces goes straight in the bin.

That factory is real. It is the analyst rebuilding a report because she does not trust the last one, and the two managers I described at the start, arguing about whose figure is correct instead of making the decision they came into the room to make. You are already paying for data quality, you are simply paying for the absence of it. According to the Gartner research from 2020, this is costing the average organisation around twelve point nine million dollars a year.

And the second reason has nothing to do with money. Most of the data your organisation holds is not really theirs. It is personal data, about people who handed it over and assumed somebody sensible was looking after it. Who may see it, how long you keep it, and when you destroy it, are all data management decisions. That part of the work has a name. Data protection is the half with the law behind it, and data ethics is the half that still matters when the law is silent. I used to tell my team to treat every record as though it belonged to their own mother, because somewhere, it belongs to somebody's.

But caring about them is not a method.

### PART 3 — HOW YOU ACTUALLY DO IT

So how do we manage data? I'll give you three moves you could genuinely begin this month.

The first is to put a name against the data, and I mean a person's name rather than a department. For anything that matters, somebody needs to answer who decides what this means, and whether it is right. When the honest answer is that everybody does, what you mean is, it's nobody. But naming an owner is not an email you send, and the people who create your data usually do not report to you.

The second move is to write down what things mean. Ask five people what counts as an active customer and you will often get five answers. Get those definitions agreed to and written down, stored beside the data itself, and you have started doing metadata management. What you are building is a business glossary. Think back to those vaccination dates I mentioned earlier, because that entire mess was one sentence nobody had written down. You need no team and no job title for this one.

The third is to fix problems where they start rather than where you happen to notice them. Data is like water in a river. If it is polluted at the source, everybody downstream drinks polluted water, and cleansing it separately at every point is the most expensive way to manage data. So put the validation where the data is created, and write it into the procedure people follow, rather than leaving it to a monthly tidy-up. When I moved our checks upstream in my own team, processing time fell by around sixty percent, and the people entering the data were noticeably happier, because they were corrected in the moment rather than having to redo them all over a month later.

### THE LANDING

So let me pull this together. Data management is the deliberate work of making data trustworthy, through plans, policies and practices that name an owner, write down what things mean, and catch problems at the source. It runs the whole length of your data's journey, and it is far wider than the three moves I have given you. DAMA, our professional body, groups the work into eleven knowledge areas: data governance, data architecture, data modelling and design, data storage and operations, data security, data integration and interoperability, document and content management, reference and master data, data warehousing and business intelligence, metadata, and data quality. Every video I make sits somewhere on that map.

Next time I want to show you the data mistake that has cost companies hundreds of millions in fines, and almost nobody who made it saw it coming.

Which of those eleven is your mess? Tell me in the comments. If this was useful, subscribe and send it to the colleague who needs it more than you do. I will see you in the next one.

---

## Production notes

**The five changes from `superseded-final-2026-08-02.md`, and nothing else:**

1. **New hook**, rewritten twice. The fire and insurance opening is retired at Aji's request. Also gone with it: *"Twenty years of customer records, patient histories, student records, transactions."* See the hook note below for what the second rewrite fixed.
2. **Owner-versus-steward lifted out of Part 3 into backlog #15** (Aji's instruction, 2026-08-10, on Dan's recommendation). 66 words, and it is preserved verbatim in the #15 backlog entry, not deleted. **Stakeholder engagement deliberately stayed**, against Dan's bundled recommendation, because Aji's rule of 2026-08-02 is that it belongs inside the ownership move rather than as a separate beat. Removing the paragraph also improved the flow: "put a name against the data" now runs straight into "But naming an owner is not an email you send", which the lifted paragraph had been interrupting.
3. **The finance/HR line moved to the end of Part 1**, as the bridge into Part 2, with three words changed and three sentences of Aji's kept intact. `Your organisation has` → **`Every organisation has`**, and `So, who in your organisation manages the data?` → **`So who manages the data?`** Both changes remove the assumption that the viewer has an organisation, so a student learns how organisations are structured instead of being asked about one they do not have. **Nothing was added around it** — a follow-up sentence was drafted and then cut on the read-aloud, because it put "nobody" in two consecutive sentences and Aji's *"If nobody is doing this"* already answers the question the line raises.
4. ~~**Landing exercise made to work with or without a workplace.**~~ *(SUPERSEDED in round eight — the exercise was removed entirely. Kept for the record.)* `the one report your organisation argues about most` → **`the last report you saw two people disagree about, whether that is at work or in a dataset you have been learning on`**. The professional thinks of a meeting; the student thinks of a dataset. Same exercise, same three questions.
5. **`Ask five people in your organisation` → `Ask five people`.** Removes an assumption at no cost in words.

**The hook, and what the second rewrite fixed.** Dan passed the first V2 hook on the fabrication rule but failed it on two counts: **96 words containing no object a camera could point at**, which pushed the script's first concrete image from 0:03 to 2:08, and compliance bought partly with hedging (two conditionals and a "probably" in 51 words), which spends force that has to be won back with an image rather than a louder claim. Three fixes, at 97 words:

- **The wrong explanation is now the visible thing** — *"every explanation points you the same way, towards a database, or somebody in IT who will sort it out."* Concrete by about second twelve, and it describes what other explanations say rather than asserting anything about the viewer, so the fabrication rule still holds by construction.
- **The hedging is gone.** `If you have already looked it up, you were probably given...` → **`Look it up and you will get...`** That is a claim about the world, which is checkable, not a claim about the viewer, which would not be. The validation the research calls for now sits in *"never be told what this job really is"* — passive, restrained, and doing the same work as an explicit reassurance without reaching for one.
- **The altitude seam is closed and the loop is stronger.** The hook named a beginner's wrong model ("something the software takes care of") against a body that names a practitioner's conflation ("managing data is the same thing as managing databases"), so it read as one point twice. Naming *somebody in IT* puts both at the same altitude. The close moved from `So if it is not the software, what is it?` to **`So whose job is it?`**, which raises altitude, pulls the hook towards the "Nobody Owns" half of the title, and lands on Aji's credibility beat as an implicit answer — *it is the job of someone like me.*
- **New setup it creates:** *"It is done by a person making decisions"* now sets up Part 1's *"Data management is somebody deciding what a field means, who owns the data..."* And the hook's *"So whose job is it?"* is answered in stages rather than circularly: Part 1 says what the work is, the new bridge asks who does it in a real organisation, Part 2 prices the answer.

**Why this hook shape at all:** researched live on YouTube 2026-08-10. Every top performer on data-management queries opens by validating a feeling the viewer already holds, and none opens on stakes, cost or consequence.

**Round three, 2026-08-10 — the three items Dan left open are now closed:**

6. **Bridge from Part 2 into Part 3.** Part 2 ended on the "own mother" line and Part 3 opened with its own question, so the sections abutted rather than connected. Added, eight words: **"But caring about them is not a method."** It turns the ethical beat forward and creates the gap that Aji's existing *"So how do we manage data?"* then fills, rather than duplicating that question.
7. **Student access in Part 3.** Moves one and three are organisational by nature and stay that way, because Aji's instruction was to keep the professional view. **Move two is the access point** — writing down what a field means needs no authority at all — so it now closes with **"You need no team and no job title for this one."** Eleven words, and the professional loses nothing.
8. **Map locating line**, in the landing per the convention in `the-map.md`: **"It runs the whole length of your data's journey, and every video I make sits on that line."** Video 1 sits at **"the whole journey"** on the map, which is why the line names the length rather than a stage. It also leans on the canonical definition's *"from the moment it is created to the day it is properly destroyed"*, so the journey is already established and the line does not have to spend words building it.

**Paid for by the cut that was already recommended twice:** *"and ask them when a student is properly enrolled and you will get five more"* (15 words), removed as repetition of the first half of that line. That is the first category in Aji's cut order, and it funded 37 words of additions for a net of +22.

**Round four, 2026-08-10 — Aji's two structural corrections.**

9. **The hook was incoherent and is rebuilt around a problem.** Her diagnosis, which is right: it opened on "what is data management?", spent its whole length saying what it is **not**, closed on a different question ("So whose job is it?"), answered neither, and then the body doubled back to the first question after the credibility beat. Two questions, no answers, and a contradiction. The previous close came from Dan and was adopted because it strengthened the loop; the defence offered for it was that the body answered it "in stages", which is precisely the *having to argue for it* tell.

   **The new shape, per her instruction to open on a problem that leads to why an organisation needs this:** a real dispute over a figure → nothing was broken and nobody lied → the decision it depended on had never been made → that gap exists in every organisation → so let me answer the question properly. The negation ("no software was going to catch that") survives as **one clause earned by the story**, rather than being the whole hook. The close now points back at the question the hook opened with and the body actually answers.

   **The problem is a recollection of Aji's, not a claim about the viewer's workplace.** It is written as a general recollection rather than a specific incident, deliberately, so the cross-site reconciliation meeting stays available for Part 1's vaccination story instead of being spent twice.

   **Aji narrowed the attribution rule on 2026-08-10, and this note previously overstated it.** Her clarification: the rule bars saying *"this is happening in your organisation"*; it is **not** a ban on storytelling, and generalised scenarios that are very likely true across most institutions are fine. So the hook did not need to be sourced to her experience to be permissible — that was one valid option among several, and the earlier claim that it was "the only way" was wrong.

10. **The personal-data beat now names its discipline.** Her diagnosis: the passage made an important point — most of the data an organisation holds is not really its own — but never said what part of data management it belonged to, so it floated as a standalone moral observation. Fixed with the pattern the script already uses successfully for the vaccination story: **name the discipline.** Added: *"Who may see it, how long you keep it, and when you destroy it, are all data management decisions. That part of the work has a name, data ethics and data protection, and it is the part with the law behind it."* Retention and destruction also call back to the canonical definition's *"to the day it is properly destroyed"*, so the beat now sits inside the video's own frame instead of beside it.

    **The "own mother" line was kept.** Aji offered to drop it. It stays because the problem was never the line — it was that the line was carrying the whole beat alone, with no analysis around it. With the disciplines named, it does what it is good at: being the thing the viewer still remembers next week. `voice-profile.md` §2 also records it as the single deliberate exception to her restraint rule, because she really said it to a real team.

11. **Callback signposted.** Part 2's factory beat now reads "the two managers **I described at the start**", since the hook plants them.

**What paid for it: stakeholder engagement lifted to #15** (~96 words, preserved verbatim there). The two fixes came to +39 words against zero headroom, so something had to go. Dan recommended this cut a pass ago and it was declined then on the grounds that Aji's rule of 2026-08-02 puts stakeholder engagement inside the ownership move of a governance topic. **#15 is that topic**, and owner-versus-steward is already there, so the rule is now satisfied rather than broken. It was also the least student-accessible passage in the script and the deepest "how" material in a video whose job is introductory what/why/how.

**Consequence Aji should weigh: Part 3's first move is now thin.** It has lost both owner-versus-steward and stakeholder engagement, leaving one paragraph of about 55 words against roughly 90 for move two and 120 for move three. It still lands on a strong line ("what you mean is, it's nobody"), but the ownership move is now the lightest of the three when it is arguably the most important. There are 55 words of headroom, so a compressed version could come back, for example: *"But naming an owner is not an email you send. You win them over by making their job easier, training them properly, and crediting them publicly when the data gets better. That is stakeholder engagement."* Her call.

**Round seven, 2026-08-11 — the scope of the field named in the landing.**

19. **Aji: "the script seems to limit what data management really is to only few area. I want you to adjust the landing to mention the 11 domain covered by the DAMA wheel."** Her diagnosis is right and it was a genuine defect in a definitional flagship: the script taught metadata, quality, ownership, ethics and protection, and a viewer could reasonably have concluded that is the whole field. Added to the landing:

    > It runs the whole length of your data's journey, and **it is wider than the three moves I have given you. DAMA, the professional body for our field, maps eleven knowledge areas, from data architecture and security to master data and warehousing, with governance running through all of them.** Every video I make sits somewhere on that map.

    **The tension with the constitution, stated rather than glossed over.** `CLAUDE.md` requires videos to be standalone and topic-first, and `brief.md` lists the DAMA wheel as explicitly **out**. The defensible reading, and the basis on which this was done: the same rule permits citing an external source "where it supports a specific claim", and the claim here is precisely that the field is wider than what the video covered. It is one sentence of citation, not a frame — the video is not structured on the wheel, does not use the book as a prop, and does not ask the viewer to care about DAMA to follow along. **If Aji disagrees on reflection, this is the one line to pull.**

    **Terminology corrected against the source:** DMBOK2 calls them **knowledge areas**, not domains, and there are eleven with **data governance at the hub** rather than beside the others — hence "running through all of them", which is also consistent with `the-map.md`, where governance runs the length of the journey rather than being a stage.

20. **What paid for it: 39 words, and both cuts were made redundant by the addition itself.**
    - *"It is one of the core disciplines inside data management"* (10 words), which followed the metadata-management naming in Part 1. The landing now states the disciplines question explicitly and better.
    - *"None of that is a five-year transformation programme. It is a start you could make today."* (16 words). Dan had defended this a pass earlier as pre-empting an objection nothing else answers, and that was fair at the time — but the exercise in the landing does the same reassurance work, and this was the last non-load-bearing passage available. **Aji's line, so say if you want it back;** it would need 16 words from somewhere else.
    - The rest came from tightening the new sentence and the landing's restatement.

**Round nine, 2026-08-11 — corrected to a plain list.** Aji: *"I said to just list not to group and explain."* Round eight had grouped the eleven areas into six clusters with a gloss on what each cluster does, which was not the ask. Replaced with a single flat list in DAMA's own order, no glosses:

> DAMA, our professional body, groups the work into eleven knowledge areas: data governance, data architecture, data modelling and design, data storage and operations, data security, data integration and interoperability, document and content management, reference and master data, data warehousing and business intelligence, metadata, and data quality.

This is a considered exception to the no-fragment-stacking rule rather than a violation of it: the rule targets clipped sentences used as sentences, and this is a proper-noun list inside one flowing sentence, which is a different thing from the parallel-repetition device the rule already carves out. **Net effect: 60 words shorter than round eight's version** and well under what round eight's grouped explanation cost, which recovers real headroom for the first time in this script's history. The graphic recommendation added to `pre-filming-checklist.md` in round eight stands regardless of grouped-vs-plain — eleven names in about twenty seconds is still a lot to hold by ear.

**Round eight, 2026-08-11 — the eleven knowledge areas named, and the exercise removed to pay for it.**

21. **Aji removed the closing exercise entirely and gave its runtime to the knowledge areas.** Her reasoning: *"Yes this is a stand alone video and it is not a reference to the DMBOK. But I want the viewers to know the knowledge areas within data management."* So the landing now names all eleven rather than counting them. **This supersedes the quote in item 19 above.**

    The list is **grouped rather than recited**, because a run of eleven names read aloud is exactly the "sounds like someone reading bullet points" failure the fragment-stacking rule exists to prevent. Six groups, each with a short gloss saying what that cluster is *for*: governance at the centre; architecture with modelling and design; storage and operations with security and integration; document and content management with reference and master data; warehousing and business intelligence; and metadata with data quality last, because those two are what the video has just spent nine minutes on. That ordering means the list **lands on the viewer's own experience of the video** rather than trailing off.

    **What was removed:** the whole "Here is something to try this week" paragraph — 91 words, including the three diagnostic questions and the comments prompt.

    **What that costs, stated plainly.** The standard script structure lists "deliver the promised exercise/takeaway" as part of the landing, so the video no longer has one. It is defensible: the credibility beat promises "the what, the why and the how", never an exercise, so no stated promise is broken, and for a definitional flagship a viewer who can name the eleven areas has arguably got more than one who did a homework task. But **the takeaway is now knowledge rather than action**, which is a real change of character in the landing, and it is Aji's call to have made.

    **The comments prompt was preserved in shorter form**, because losing it would have cost the video its only engagement ask: **"Which of those eleven is your mess? Tell me in the comments."** Eleven words instead of the original's longer version, and it now points at the new list. Say if you would rather it went too.

    **Attribution kept deliberately light and book-free.** Aji's note that this is not a DMBOK reference is reflected in the wording: it credits **DAMA, the professional body**, not the book, in one clause — *"DAMA, our professional body, groups the work into eleven knowledge areas worth knowing by name."* Naming the body rather than the publication is what keeps this a citation rather than a frame, while still not presenting one organisation's taxonomy as neutral fact.

    **Runtime: still 10:00 exactly.** The 91 words freed paid for a 94-word list plus the shortened prompt, with the balance found by tightening the scope sentence and the group glosses.

**Note on these production notes:** they now run longer than the script and contain several entries superseded by later rounds (items 4 and 19 in particular). Worth pruning to a short changelog plus the open items — say the word and I will do it.

**Still open, needs Aji:**
1. **Runtime is at exactly 10:00 with zero headroom.** This is now the binding constraint on everything. Dan's standing structural read — that a whole beat should move into its own video rather than the script being shaved each pass — has gone from advisable to overdue. **The timed read-aloud before filming is critical, not optional:** the channel's delivery style is deliberately unhurried, and anything slower than 140 wpm puts this over ten minutes.
2. **CLOSED 2026-08-11 by Aji — the subtitle is now "The Job Nobody Owns"**, replacing "The Million-Dollar Problem Nobody Owns". Keyword phrase unchanged. The script earns it end to end: the hook opens on a decision nobody made, the Part 1 bridge asks "So who manages the data?", Part 3's first move puts a name against the data and lands on "what you mean is, it's nobody", and the landing asks who owns the report **by name**. It also removes the title/thumbnail/script figure-consistency risk Dan flagged on two drafts, since the title no longer has to agree with the Gartner number — the money stays in Part 2 with its source and year. **The thumbnail needs updating to match.** The old subtitle deliberately still stands in `brief.md`, `draft.md` and `superseded-final-2026-08-02.md`, which are point-in-time stage records. **The time-box idea is withdrawn:** it only works as a *short* promise, and at 10:00 advertising the duration would deter rather than attract.
3. ~~**`coverage analysis` has no gloss.**~~ **CLOSED as not-a-defect, 2026-08-11 by Aji.** It stays unglossed deliberately — it is an incidental term, not one of the video's taught terms, and glossing it interrupted the vaccination story to define something the viewer does not need. See item 16 below.
4. **Production tasks have moved out of this file to `pre-filming-checklist.md`** (created 2026-08-11). The Gartner on-screen credit rode along in three consecutive assessments because a script note is where a production task goes to die — Dan's point, and he was right. The checklist now holds: the Gartner credit, the thumbnail update, chapters and description, the timed read-aloud and the closing-tease check. Do not re-add production tasks here.

**Round five, 2026-08-11 — Dan's second pass applied.** His verdict: ten of thirteen items pass, everything he had failed the script on is genuinely closed, and what remained was bookkeeping rather than judgement. He recounted the runtime by hand and confirmed it for the first time.

12. **Dan's diff found four unlisted changes to Aji's wording. Resolved 2026-08-11: two were Aji's own.** She confirmed she changed `what good looks like` → **`what quality looks like`** and `my profession` → **`our profession`**. Both stand as hers. (Note she deliberately went the *opposite* way to Dan's pass-one flag on the profession inconsistency, and towards what `voice-profile.md` §9 already records as her preference.) These were briefly reverted in error on a wrong inference about their source, and have been restored.
    - **One was Torch's** — see item 14.
    - **One is still unexplained and is a question for Aji:** `isn't really yours` had become `is not really theirs`. That reverses a dictation fix `superseded-final-2026-08-02.md` records making ("aren't really theirs" → "isn't really yours"), and it trips read aloud against "your organisation" earlier in the same sentence, so it is currently restored to **`isn't really yours`**. If that change was deliberate, say so and it goes back.
    - **Standing correction: the script is Aji's and she edits it whenever she likes, with no changelog owed.** The value of diffing against `superseded-final-2026-08-02.md` is to surface unlisted changes *for her confirmation*, never to attribute them.
13. **Domain precision fixed — a real defect Torch introduced.** *"data ethics and data protection, and it is the part with the law behind it"* attached the law to both, when data ethics is precisely the part **without** it. Now: **"That part of the work has a name. Data protection is the half with the law behind it, and data ethics is the half that still matters when the law is silent."** This teaches the distinction rather than blurring it, which is what the domain-expertise rule asks for.
14. **The one unlisted change that WAS Torch's, now recorded:** `Then there is the part that has nothing to do with money at all.` → **`And the second reason has nothing to do with money.`** Made while rewriting that paragraph and not listed at the time. Dan calls it arguably better because it signals the structure; **Aji should see it and decide**, and reverting costs nothing.
15. **Part 3's ownership move got its failure mode back, in Aji's own words** (~23 words): **"But naming an owner is not an email you send, and the people who create your data usually do not report to you."** Dan's diagnosis was sharper than the earlier one: the move was not merely *short* after the two lifts, it had **lost the two sentences that explained why naming an owner fails**, which the standing "show how it goes wrong in practice" rule requires. His recommendation was explicitly to restore the **cause** in her words rather than the 35-word method version drafted earlier, which would have re-imported #15's material and added an eleventh triad. Taken as given.
16. ~~**`coverage analysis` glossed.**~~ **Added, then removed on Aji's instruction 2026-08-11. Correct call, and the reasoning is worth keeping.** The gloss *"meaning how many children we had actually reached"* was added because Dan raised the term and there were words spare — even though this file had twice recorded that it was **not** a comprehension blocker, since the sentence lands without knowing the term. **"Keep the term, add the gloss" applies to the terms the video is teaching** — metadata, business metadata, metadata management, data owner, data steward, business glossary, data ethics, data protection — and every one of those is glossed. **`coverage analysis` is incidental**: the viewer does not need to leave with it, and explaining it interrupts the story at its most dramatic point to define something nobody asked about. **Do not gloss incidental terms, and never spend words simply because headroom exists.**

**Round six, 2026-08-11 — Aji's last two corrections, then promotion.**

17. **`"That is the gap, and every organisation has it somewhere."` is gone.** Aji's challenge: *"Is this supposed to be true? and in a way it sound ambiguous."* Both halves were right. **Untrue as stated** — "every organisation has it somewhere" is an unverifiable universal, and it quietly undercuts the video's own argument, because if data management works then organisations that do it well *do not* have the gap. **Ambiguous** — "the gap" had no clear referent: the gap between the two numbers, the missing decision, or a gap in capability. Replaced with:

    > No software was going to catch that, because the decision it depended on had never been made, **and nobody was responsible for making it. That is the sort of gap data management exists to close.**

    Three things this fixes. The gap is now **named** rather than gestured at — an unmade decision with nobody accountable for it. **"the sort of gap"** keeps it accurate, because closing decision gaps is one thing data management does, not a definition of the whole discipline. And **"nobody was responsible for making it"** lands the subtitle, "The Job Nobody Owns", inside the hook for the first time. It also gives the hook a line of positive content about what data management is *for*, which answers Aji's earlier objection that the hook only ever said what it was not.

    **Cost: +7 words, taking the script from 9:52 to 9:56.** Spent deliberately on a correction Aji asked for, which is what banked headroom is for — as distinct from the coverage-analysis gloss, which was words spent simply because room existed.

18. **Promoted to the authority, then renamed into this filename on Aji's instruction.** The 2026-08-02 script was archived as `superseded-final-2026-08-02.md` with a do-not-film banner, and this file took the name `final.md`. Her choice also **resolves a convention problem rather than creating one**: `CLAUDE.md` states that `videos/<slug>/final.md` is the authority, which was briefly untrue while the live script was called `final-v2.md`, and is now true again with no constitution change needed. `git mv` was used for the archive so its history survives. Every internal reference in this file that pointed at the old `final.md` was repointed to the archive name, because after the rename they would otherwise have read as self-references.

**Dan withdrew two of his own earlier findings** rather than re-running them: the Part 1 signpost (the sentence needing it no longer exists, and the remaining echo now reads as deliberate), and cutting *"None of that is a five-year transformation programme"* (it pre-empts an objection nothing else in the script answers).

**Transcription slips corrected in this copy** (carried over from `superseded-final-2026-08-02.md`, all dictation artefacts rather than voice choices): "coting" → quoting · "is literally determine" → literally determines · "we had third senior" → we had a third scenario · "what is the consequences" → what are the consequences · "who's name" → whose name · "somebody needs answer" → somebody needs to answer · "what you means is" → what you mean is · "buildings and equipment's" → buildings and equipment · "for the." → sentence completed.

**One item removed from that list on 2026-08-11, and it matters.** `superseded-final-2026-08-02.md` recorded **"aren't really theirs" → "isn't really yours"** as a corrected dictation slip. **It was not a slip.** Aji has confirmed "theirs" is deliberate, and the script now reads *"Most of the data your organisation holds is not really theirs."* An earlier pass had classified a deliberate word choice as a transcription artefact and overwritten it.

Her wording is also the more precise of the two. "Yours" tells the viewer they do not own the data, which was never in question personally; **"theirs" says the organisation does not own it**, which is the actual claim, and it sets up the sentence that follows — the data belongs to the people who handed it over. `superseded-final-2026-08-02.md`'s own note still lists this as a correction; it has been left alone because that file is Aji's.

**The distinction worth carrying forward: a genuine dictation slip fixes grammar; anything that changes meaning is a voice choice, not an artefact.** Every other entry above is grammatical. This one changed who the sentence was about, which is what should have flagged it.

**Still outstanding:** on-screen source credit for the Gartner figure (2020).
