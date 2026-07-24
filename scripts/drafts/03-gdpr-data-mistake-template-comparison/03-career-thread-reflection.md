# The Data Mistake That Gets Companies Fined Millions (GDPR Explained by a Data Manager)

**Template:** 3 — Career-thread / multi-chapter reflection (CLAUDE.md → Script templates #3)
**Status:** Comparison draft — one of six, same topic, different template
**Target runtime:** ~15 minutes (~2,150 words)
**Pillar:** Foundations (ethics & GDPR) — told through pillar 5 mechanics

---

### THE HOOK (0:00–0:45)

A colleague once asked me to pull "everything we've got" on a group of former students. No form. No reason given. Just: it might be useful.

I said no. Not because I suspected anything — because I couldn't answer one question: what's it for? And if I can't answer that question, neither can anyone else in the room, and that's exactly the gap regulators are trained to find.

Companies don't usually get fined millions because a hacker broke in. They get fined because nobody could answer that question — what's this data for, and why do we still have it — and I've watched that exact gap open up in three completely different jobs, for three completely different reasons. Let me show you the pattern.

### CREDIBILITY + PROMISE (0:45–2:00)

I'm Aji Saine. Twelve-plus years across software development, clinical data covering over 285,000 people in West Africa, and right now, statutory reporting for a UK university — three jobs where personal data wasn't an abstraction, it was someone's actual life sitting in a system I was responsible for.

By the end of this video, you'll have the real underlying pattern behind most GDPR fines — not the legal jargon, the actual habit that causes it — because I've watched it show up in health data, in higher education, and in the plainest software I ever wrote.

Let's get into it.

### THE DEVELOPER YEARS (2:00–4:00)

Back in my developer years, I built a system with a "client" field. It validated fine, it ran fine — but some people typed in the organisation, others typed in a specific person at that organisation, because nobody had agreed what "client" actually meant before the form went live.

At the time I thought of that as a data quality problem. Looking back, it was something sharper: nobody could tell you, with confidence, exactly whose personal information was sitting in that field, or why. If a real person had asked "what do you hold on me, and why," the honest answer would have taken days to work out — not because anyone was hiding anything, but because nobody had ever been made to define it clearly enough to answer quickly.

I didn't think of it in those terms then. I thought of it as an annoying bug to schedule for next sprint. It took me years, and two more jobs, to understand that "annoying bug" and "the exact thing regulators investigate" are often the same gap, just discovered at different points in its life.

That's the first shape of the pattern: personal data sitting somewhere nobody can precisely account for.

### THE CLINICAL DATA YEARS, WEST AFRICA (4:00–7:00)

Years later, the stakes on that same pattern got a great deal higher. I managed clinical and health data across research sites in West Africa — vaccination dates, patient histories, records covering a quarter of a million people. This wasn't administrative data. This was someone's medical history, and getting careless with it doesn't cost you a fine. It costs someone their trust, or worse.

I used to tell my team: treat every record as if it belonged to your own mother. I still mean it. Because behind every field, every "edge case" you're tempted to wave through, there's a real person who has no idea a decision about their data is being made by someone they've never met.

We built a data dictionary, wrote standard operating procedures for how every field got captured, and trained every site against both — not because a lawyer told us to, but because without it, we genuinely could not have told a parent, honestly, what we held on their child and why. That's the part that's easy to miss when you first read GDPR as a piece of legislation: the discipline it demands isn't new. It's the same discipline any responsible person managing other people's information already owes them, whether or not a law says so.

What that job taught me — long before I'd ever read a GDPR regulation — is that data about people isn't neutral. It comes with an obligation attached the moment you collect it: to know why you have it, and to treat "why" as something you have to keep being able to answer, not something you answer once and forget.

### RIGHT NOW, UK HIGHER EDUCATION (7:00–9:45)

Which brings me to right now. Not long after I started in UK higher education, I noticed my own team fielding requests for "all of it" — full extracts of student and staff data, no scope, no stated purpose, handed over because saying yes was quicker than asking why. Nobody making those requests was trying to do anything wrong. They just genuinely didn't know there was a better way to ask, because nobody had ever told them there needed to be one.

So I stopped it. We introduced a data access request policy: state what you need, state why, we run a needs assessment against that, and you get exactly that — not the whole database because asking for everything was easier than asking properly. One of the earliest requests under that policy was for a full extract of former students' contact details, "just in case it's useful." Under the old habit, that would have gone out the same afternoon. Under the new one, it didn't go out at all, because nobody could say what it was actually for.

That policy isn't really about GDPR compliance on paper. It's the same instinct from the West Africa years, translated into a UK statutory context: don't let anyone touch personal data without being able to say, out loud, why. The law just happens to formalise an instinct that should have been there anyway — and once I'd lived through the version with the highest possible stakes, I couldn't unsee the same pattern showing up in something as ordinary as an email request.

### THE PATTERN, NAMED (9:45–12:00)

Three jobs. A dev team, a health programme, a UK university. And in every single one, the moment things nearly went wrong traced back to the same missing habit — not a hacker, not a broken system, just nobody being able to answer, on demand: what is this, why do we have it, and when does it stop being ours to hold?

I didn't plan that thread on purpose — I moved through those jobs for their own reasons, not because I saw the pattern coming. It was only putting these stories next to each other, the way I'm doing right now, that I noticed it was the same test every time, just with higher and higher stakes attached.

Call it three questions, because that's genuinely all a regulator is checking, underneath the legal language: what is it, why do we have it, and when does it go. Answer those honestly, every time, and you're doing most of what GDPR actually asks of you. Fail to answer them, at scale, across an entire organisation, and that's the gap that gets companies fined millions — not a villain, just an unanswered question nobody was ever assigned to own.

What strikes me now, looking back across all three jobs, is how little the underlying skill actually changed. The client field, the vaccination date, the "everything" request — none of them needed a lawyer to spot. They needed someone willing to stop and ask an uncomfortable question out loud, in a room, when it would have been so much easier to just let the request go through. That's not a legal skill. It's closer to the instinct a good editor has — the discomfort that kicks in when something reads fine on the surface but doesn't actually hold together underneath.

### THE LANDING + HOMEWORK (12:00–15:00)

So that's the real mistake, threaded through three very different careers: treating personal data as something you're allowed to hold by default, instead of something you have to keep justifying. It's rarely a hacker that brings the fine. It's the silence when someone finally asks why the data's still there.

I think that's why this topic sits so close to the rest of what I talk about on this channel. Data quality, metadata, ownership, governance — GDPR isn't a separate subject bolted onto data management from the outside. It's what happens when you fail at the same basic discipline this whole channel is about, except this time a regulator is the one asking the question instead of a colleague, and the consequences show up as a fine instead of an awkward meeting.

Here's the exercise. Think of one piece of personal data your own team holds — a customer record, a former colleague's contact details, anything. Ask yourself the three questions, out loud, right now: what is it, why do we have it, and when does it go? If any one of those makes you pause, you've just found the gap.

Next time, I want to zoom out from these personal moments and show you exactly how this plays out at organisational scale — the actual mechanics that turn one unanswered question into a multi-million-pound fine. Watch that one next.

If this gave you a clearer sense of what data management is actually protecting, subscribe — there's a lot more of this coming, one decision at a time.

I'll see you in the next one.
