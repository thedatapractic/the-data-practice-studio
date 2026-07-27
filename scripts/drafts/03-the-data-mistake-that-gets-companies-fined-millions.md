# The Data Mistake That Gets Companies Fined Millions (GDPR Explained by a Data Manager)

**Template:** 6 — Myth vs. mechanism / contrarian reveal (CLAUDE.md → Script templates #6)
**Status:** REVIEWED — ready to film pending Aji's read-aloud pass and the figure check below. `/review-script` applied on top of the collaboratively-built draft. Changes were surgical, not structural: (1) added the missing rule-7 value tease to the hook, teasing the fourth question — the one gap the review found that mattered; (2) paid that tease off explicitly in the landing ("the one I promised you at the start"); (3) fixed three repeated constructions the raw word-count hid ("just sits" ×2, "just never decided/made a decision" ×2, "really just"); (4) broke the long subject-access-request paragraph into three for the ear. Everything else from the collaborative build is preserved verbatim.
**Before filming — verify:** the four fine figures (Meta €1.2bn 2023; British Airways £20m and Marriott £18.4m — both the *reduced final* penalties, correctly stated as such; H&M €35.3m). They match my understanding but they're the highest-risk claims in the script because they're stated as precise facts on camera.
**Build history:** all sections built via `/build-script`. Hook = sensory "junk drawer" + real named GDPR fines. THE PRECEDENT opens on the actual scene and is fact-corrected on Aji's notes (demographic information not contact details; landed with a direct report not Aji directly; access-request policy created *after* the incident; vaccination-dates story framed as "a Health and Demographic Surveillance System at a health research institution"). THE MECHANISM bridges the two failure modes (accumulation over time vs. fragmentation across systems) with an explicit drawer callback. LANDING: three questions as a named repeatable habit, ethics turn as a fourth question, tease corrected from Video 1 (backwards) to Video 4. Principles and ethics woven throughout per CLAUDE.md → "Leaving the viewer with ethics, principles, and practice."
**Motif/spine:** the cost of the decision nobody made. Two images: the *drawer* (how data ends up where it shouldn't) and the *meeting room* (where the decision didn't happen). Spine = three questions planted in the reveal — what do we hold, why, when were we supposed to stop — restated from a different angle in every section, then handed over as homework. The click: fines punish being *unable to answer*, not being attacked.
**Principle progression:** plain language first (hook/reveal), one name at the moment it's lived (data minimisation and accuracy in the precedent), then the formal set once the viewer already understands the behaviour (purpose limitation, storage limitation, accountability in the mechanism). Ethics turn lands in the precedent (the vaccination date as a record of whether a child was protected) and again in the landing.
**Actual runtime:** ~14.7 minutes (~2058 words) — on target; timestamps below reflect this
**Target runtime:** ~15 minutes (~2,150 words)
**Thumbnail text:** "NOT A HACK" or "THE REAL REASON" (with Aji, direct to camera)
**Description/tags:** GDPR explained, data protection fines, GDPR mistakes, data governance, GDPR compliance, data manager explains
**Playlist:** Foundations & Governance
**Pillar:** Foundations (ethics & GDPR)

---

### THE HOOK (0:00–1:52)

Every house has one. A drawer somewhere — kitchen, hallway, wherever — where things just end up. A dead charger. A receipt from a shop that closed years ago. A key that doesn't open anything you still own. Nobody decided to keep any of it. It accumulated, one thing at a time, because throwing it out never felt urgent enough to actually do.

Every organisation has a version of that drawer. Except instead of a dead charger, it's a customer's old address. Instead of a receipt, it's someone's medical history.

Here's what happens when someone official finally opens one.

One point two billion euros. That's the record GDPR fine, handed to Meta.

British Airways — twenty million pounds. Marriott hotels — over eighteen million. And H&M — the clothing shop — thirty-five million euros.

Now, when you hear numbers like that, you probably picture hackers in hoodies, breaking through firewalls at three in the morning.

But here's the uncomfortable truth. Behind most of these fines, there's no evil genius. There's a meeting room. Ordinary people, making ordinary decisions about other people's data — decisions that felt completely harmless at the time. Decisions that, statistically speaking, someone in your organisation is probably making this week.

I'm going to show you exactly what that decision looks like, and why it costs so much. And stay to the end, because I'll give you the one question I ask myself when I'm genuinely unsure about a record. It has no legal force whatsoever. It's still the fastest way I know to get to the right answer.

### THE REVEAL (1:52–4:11)

Breaches happen, and they do get punished — that part's true. But look past the headline, at what the regulator's own investigation usually describes, and a striking share of the biggest fines involve no attacker at all. The organisation simply couldn't answer a basic question about its own data: what do we hold, why do we hold it, and when were we supposed to stop holding it?

Think about what that actually means for a moment. A regulator doesn't need to find a criminal to hand out a fine. They only need to ask an organisation to produce, in writing, exactly what personal data it holds on one named individual, where it came from, and how long it's been kept.

And it isn't only regulators who can ask. Any member of the public can trigger that request today, right now — your neighbour, a former employee, a customer who hasn't shopped with you since 2019. It's called a subject access request, and it's one of the most ordinary legal rights GDPR created.

Plenty of organisations can answer it within days. Plenty of others discover, in that moment, that the honest answer means checking a dozen different systems, built by a dozen different teams, over a dozen different years — none of which fully agree with each other. That gap, the days or weeks it takes just to attempt an answer, is usually the first sign of trouble. And it shows up years before any headline does.

That's not a break-in. Nobody forced their way past anything. The information was sitting right where the organisation put it — nobody had ever decided, clearly, whether it should still be there. Call it what it is: not a security failure. A governance failure. And governance failures don't announce themselves. Nothing breaks. No alarm fires. It sits there, patiently, until the day someone with real authority finally asks the one question the organisation was never prepared to answer.

### THE PRECEDENT (4:11–8:11)

I've watched this exact test happen twice, in two very different jobs.

A request landed in my team's inbox not long after I started in UK higher education: a full extract of every student's demographic information — everything we held, no scope, no stated purpose. One of my direct reports was about to process it. I stopped him, and had him go back to the requester and ask for only what was actually needed.

That instinct has a formal name, by the way. Data minimisation. Collect and share the least you need for the job in front of you — not the most you can technically justify.

That one incident is what led me to introduce a formal data access request policy afterward — I drafted a form and got my line manager's approval: state what you need, state why, we run a needs assessment against that, and you get exactly that. Nobody could turn a request like that into an actual justification once they had to write one down — and that's exactly the kind of gap that turns into a fine, years later, once enough of them pile up unnoticed.

It's a small policy. Nobody outside the data team ever sees it get enforced, and it doesn't feel like it's protecting against anything dramatic. But it's the only thing standing between "we assumed it was fine to keep this" and "we can prove, in writing, exactly why we kept it" — and a regulator only ever asks for the second one.

I'd seen a sharper version of the same test years earlier, where the stakes left no room to miss it.

When I worked on a Health and Demographic Surveillance System at a health research institution, vaccination dates were recorded three different ways across three sites, because nobody had ever agreed what the date was supposed to mean. We only caught it because the consequences were immediate and visible: a region's vaccine coverage numbers simply didn't add up.

And that's the part I want you to sit with for a second. A vaccination date isn't a value in a column. It's a record of whether a child was protected. If we can't say what the date means, we can't honestly say that either — and somewhere downstream, someone makes a decision about a real community based on a number we quietly got wrong. Accuracy is a data protection principle, written into the law. But long before it was law, it was just the difference between doing this job carefully and doing it fast.

Most organisations don't get that early warning. Their version of the same mistake sits in a spreadsheet for years, unnoticed, until somebody outside the organisation finally asks the question nobody inside ever did.

What connects those two moments isn't the sector, or the scale — it's that in both cases, the fix wasn't a piece of software. It was a person willing to stop a request in progress and ask an uncomfortable question out loud, in a room, when saying nothing and letting it through would have been so much easier. Regulators can't inspect an organisation's intentions. They can only inspect what happened to the data — and what happened almost always traces back to whether that person existed, or whether the request just sailed through because nobody was in the room to stop it.

### THE MECHANISM, COMPRESSED (8:11–11:17)

If the same person's data exists in five systems and nobody's sure which one's correct, that's not five records. That's one person you can no longer honestly answer "what do we hold on you" about.

Those are the two ways this goes wrong, and they compound. The drawer is about time — data still sitting there years after anyone needed it. The five systems are about space — the same person, scattered, with no version anyone can point to as the true one. Different failures. Same ending: a question about a real person that your organisation cannot answer.

And that ending is what's underneath every fine on that list. Remember those three questions? They aren't mine. They're the law, in plain clothes. *Why do we hold this* is purpose limitation — you collect data for a stated reason, and that reason is a fence, not a suggestion. *When were we supposed to stop* is storage limitation — you don't keep it longer than the reason justifies. And underneath both sits accountability: somebody, by name, has to be able to answer for it.

Purpose nobody re-checks. Retention nobody enforces. Access nobody scopes. None of it looks dramatic from the inside. It looks like Tuesday.

Here's how it actually happens — and it's the drawer again, just bigger.

Picture an ordinary mid-sized company running a customer loyalty scheme. A person signs up once, gets a discount code, and never comes back. Nobody decides to keep their data forever. Nobody decides anything at all. Then the company changes CRM, and that record gets migrated across, because migrating everything is easier than deciding what's worth migrating. Then it changes again, and the same thing happens. Somewhere in year four, someone opens that table, doesn't recognise half of what's in it, and quietly leaves it alone — because nobody wants to be the person who deleted something that turned out to matter.

Ten years on, that company holds accurate, current, explainable data on its active customers — and a decade of silent clutter on everyone else. From the outside, both look identical. Rows in a database. A regulator's investigation is the process of finding out which rows are which.

And you can test this on your own organisation in under a minute — you don't need my job title to do it. Ask anyone: "if I asked you what personal data of mine you're holding right now, and why, could you tell me?" Watch the pause before the answer. That pause is the mechanism. It's the same pause, at a much bigger scale, sitting inside every regulator's investigation report.

### LANDING (11:17–14:12)

So let's land this.

The fines at the start of this video weren't punishment for being attacked. They were punishment for not being able to answer — what do we hold, why do we hold it, when were we supposed to stop. Nobody in those meeting rooms set out to break a law. They just never made a decision. And "never decided" is a decision too — it's the most expensive one on that list.

The good news is that fixing it doesn't need a bigger legal team or new software. That loyalty-scheme company could close most of its exposure in an afternoon: one person going through each system, writing down what's in it, why, and when it goes — then actually scheduling the deletion instead of noting it as a good idea for later. The technology to enforce a retention date has existed for decades. What's missing is the decision, made once, by someone with the standing to make it stick.

So here's the habit I'd give you. Call it the three-question check, and run it on one dataset a week — not once, as a project. Every week. What is this? Why do we have it? When does it stop being ours to hold?

If any one of those makes you pause, you've found the gap regulators are trained to look for — and you found it first.

But there's a fourth question — the one I promised you at the start, and the one that does the real work. When you're looking at a record and you're genuinely unsure — whether to keep it, share it, copy it into that spreadsheet — picture the person that record describes standing behind you, reading your screen over your shoulder.

Would you be comfortable?

That question has no legal force whatsoever. It isn't in any regulation. And it's still the fastest way I know to get to the right answer — it works long before a lawyer would ever need to be involved.

Now — everything today assumed the data was worth protecting in the first place. But what if it's wrong? Wrong data gets protected too. It gets backed up, secured, retained beautifully — and then somebody makes a decision on it. There's a reason your colleagues quietly don't trust the reports in your organisation, and next time I'll show you exactly why that happens and how to fix it. Watch that one before your next big meeting.

### THE CLOSE (14:12–14:38)

If this was useful, like the video and subscribe. And send it to the person in your organisation who's never once stopped to ask whether they still need what they're holding onto. You know the one.

I'll leave you with this.

Nobody's asking you to never have a drawer. Every organisation has one. The difference is whether you know what's in it.

### SIGN-OFF (14:38–14:41)

I'll see you in the next one.
