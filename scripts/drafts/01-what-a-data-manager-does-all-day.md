# Video 1 — What a Data Manager Actually Does All Day (It's Not Spreadsheets)

**Status:** Drafted — all placeholders filled, ready for `/review-script`
**Target runtime:** ~15 minutes (~2,150 words at 140wpm)
**Thumbnail text:** "NOT SPREADSHEETS" or "MY ACTUAL JOB" (with Aji, direct to camera)
**Description/tags:** what does a data manager do, data management career, data manager job description, day in the life data professional
**Playlist:** Behind the Data Job

---

### THE HOOK (0:00–0:45)

Tell someone your job title is "data manager" and watch what happens to their face.

They picture someone hunched over a spreadsheet. Or IT. Or — my personal favourite — "so you fix computers?"

Here's what actually filled my Tuesday last week: a fight about what the word "active" means.

Not a fight about a formula. A fight about a word. And by the end of it, I'd made a call that would decide how a report to a regulator counted thousands of people.

That's the job. Nobody puts it on the tin.

In this video I'm going to walk you through what a data manager actually does — the decisions, not the job description — so you know exactly what this work is, whether you're already doing it under a different title, or wondering if it's the career you're supposed to be having.

### CREDIBILITY + PROMISE (0:45–2:00)

Quick reintroduction if you're new here — I'm Aji Saine. Twelve-plus years split between software development and data management.

I've done this work in two very different worlds. I managed clinical and health data covering over 285,000 people across research sites in West Africa. And today I work in statutory data reporting for a UK university, where the numbers I sign off decide funding.

In between, I've trained a team through the shift from Access to SQL Server — proactively, ahead of a system migration that's been "coming" for two years and still hasn't landed — and built dashboards, including for a demographic surveillance system covering hundreds of thousands of people, that people open every morning without a second thought.

Last week I told you data is an asset, and almost nobody's actually managing it properly. This week I'm going to show you what it looks like when somebody is — because it's not what you think, and by the end of this video you'll be able to spot the real work happening in your own organisation, even when nobody's calling it "data management."

Let's get into it.

### PART 1 — THE JOB TITLE IS LYING TO YOU (2:00–4:00)

Here's the first thing to unlearn. "Data manager" sounds like a technical title. It isn't, mostly.

I write code. I can, anyway — that's where I started. But on any given day, the code is the smallest part of the job. The actual work is decisions. Specifically, decisions nobody else in the building wants to make, because they sound boring until you realise how much rides on them.

What counts as an "active" customer. Whether a missing date means "we don't know" or "it never happened" — those are not the same thing, and treating them as the same thing has burned entire reports. Who is allowed to change a record, and who just gets to look at it. What happens to data the day someone leaves the organisation.

None of that is a technology question. You could ask it with pen and paper. It's a governance question wearing a technology costume.

I put it this way to people I train: a database administrator keeps the filing cabinet working. A data manager decides what goes in which drawer, who's allowed to open it, and what it means when the label doesn't match what's inside.

So when I say I "manage data," I don't mean I sit with data all day. I mean I sit in the argument about what the data is supposed to represent — and somebody has to, because if nobody does, everyone downstream just guesses.

Which raises the obvious question: what does that argument actually look like, day to day?

### PART 2 — THREE DECISIONS, THREE CAREERS (4:00–7:15)

Let me take you through three real ones, from three different chapters of my career, because the pattern's the same even though the stakes look completely different.

First — the developer years. Early on, I built a system with a "client" field. It validated fine. It ran fine. No bug anywhere in the code. But some people typed in the organisation. Others typed in a specific staff member at that organisation — because nobody had actually agreed what "client" meant before the form went live. Same field, two different realities living inside it, and the software couldn't tell the difference. That was the first time I understood that clean code sitting on top of a shaky definition is still a shaky system. It just fails more expensively, later, when nobody's looking.

Second — the clinical data years in West Africa. I've told you before about vaccination dates recorded three different ways across three sites. Here's what we actually did about it: built a data dictionary — clear, agreed descriptions for every field — wrote standard operating procedures for how data got captured, and trained every site against both. Getting there wasn't clean, though. Every single site believed they were the ones doing it right. It took a meeting with all three sites in the room, reconciling three different "correct" answers into one, before we had a definition anybody would actually stand behind. That decision affected how vaccine coverage got reported for a quarter of a million people. Get that wrong, and a region gets marked as under-vaccinated when it isn't — or worse, the other way round.

Third — right now, in UK higher education. Not long after I started, I noticed my own team fielding requests for "all of it" — every student's data, no scope, no stated purpose, just handed over because it was easier to say yes. So I stopped it. We introduced a data access request policy: state what you need and why, we run a needs assessment against that, and you get exactly that — not the whole database because asking for everything was quicker than asking properly. Nobody outside the data team ever sees that policy get enforced. But it's the difference between a university that hands out data because someone asked nicely, and one that can actually account for who has access to what, and why.

Three completely different worlds — a startup-style dev team, a health NGO, a UK statutory body — and the actual job was identical every time. Somebody has to decide what the data means before anyone's allowed to trust what it says. That somebody is the data manager.

And here's the part nobody warns you about: half of that job is fought outside any database entirely.

### PART 3 — THE JOB IS MOSTLY TRANSLATION (7:15–10:30)

I called data governance "the referee" in last week's video. Turns out my actual job description is closer to referee than engineer most days.

Here's an example that's happening to me right now, not a tidy story from the past. The university's been planning a move to a new student record system — one that runs on SQL Server — for two years. It still hasn't gone live; the institution itself hasn't been ready, on its own timeline, more than once. My team, until recently, only had real depth in Access.

I didn't wait for the go-live date, because a date that's already slipped tends to slip again, and the day it finally happens is the worst possible day to discover your team doesn't have the skills for it. So I started training them in SQL Server now, on top of the work they're already doing, so that whenever the switch actually flips, that's not the thing we're behind on. Nobody assigned me that. It's not on any list of duties. It's the job anyway — noticing the change coming before the organisation itself is ready for it, and making sure your people aren't the bottleneck when it lands.

The other kind of translation looks more like conflict. While I was building dashboards for the Medical Research Council, on a Health and Demographic Surveillance System covering a huge population, requests to change those dashboards came constantly — a new metric, a "quick" tweak, one more breakdown. My rule was simple: every request gets assessed before it goes anywhere near the dashboard. If it doesn't hold up — if it would blur a definition or quietly change what a number meant — it doesn't go in. That held even when the request came from management. I had the standing to give my own recommendation on how the data got presented, and I used it.

That's the unglamorous half of the job — the half that doesn't show up in a portfolio. You're constantly standing between two languages: the technical language of tables, keys, and constraints, and the business language of "the student," "the return," "the active case." Your job is to make sure those two languages are still describing the same thing, because the moment they quietly drift apart, that's when reports stop being trusted and nobody can tell you why.

Saying no is part of the job description, even though it's never written down anywhere.

So if the job is mostly foresight, translation, and the occasional necessary "no" — why does any of it matter enough to lose sleep over? That's the part that made me take this career seriously in the first place.

### PART 4 — WHY THE JUDGMENT CALLS ARE PERSONAL (10:30–12:45)

I've managed data about real people for most of my career. Not rows. People.

When you're the one deciding how a health record gets standardised, you're not tidying a spreadsheet — you're shaping what a clinician sees the next time that patient walks in. When you're the one deciding how a university's return is compiled, you're shaping whether a struggling department gets flagged for support or gets quietly deprioritised, based on numbers most people will never question.

I used to tell my team: treat every record as if it belonged to your own mother. I still mean it. Because somewhere behind every "edge case" you're tempted to wave through, there's a person who has no idea a decision about them is being made by someone they've never met, based on a definition they never agreed to.

That's why the job isn't clerical. A clerk follows the rule. A data manager is often the one in the room deciding what the rule should be — quietly, with no fanfare, usually under a deadline, and usually with real consequences riding on getting it right. Get it wrong and it's not a bug ticket. It's a wrong medical picture, a wrongly funded department, a company fined for something nobody meant to do.

That weight is exactly why this work needs people who take it seriously — not just people who are good with computers.

### PART 5 — DOES THIS SOUND LIKE YOU? (12:45–13:30)

So who actually thrives doing this? Not necessarily who you'd expect.

The best data people I've worked with weren't always the strongest coders. They were the ones who got uncomfortable when two people used the same word to mean two different things. Who asked "but what do we actually mean by that?" in meetings, even when it made the meeting run long. Who could sit between a technical team and a business team and translate for both without losing patience with either.

If that's already how your brain works — even if your job title says analyst, or administrator, or something with no mention of data in it at all — you may already be doing this job. Nobody's given you the title yet.

### THE LANDING + HOMEWORK (13:30–15:00)

So here's what a data manager actually does. Not spreadsheets. Not "fixing computers." Decisions — about what data means, who's accountable for it, and what happens when the technical answer and the right answer aren't the same thing. And translation — standing between the people who build the systems and the people who depend on them, making sure both sides are still describing the same reality.

It's quiet work. Almost nobody claps for a well-defined field. But get it wrong, and the consequences show up everywhere from a clinic to a funding return to a fine in the newspaper.

Here's the exercise. This week, notice the next time someone in a meeting says a word like "active," "current," or "complete" as if everyone agrees what it means. Ask, out loud: "quick check — what do we actually mean by that?" Watch how many different answers you get in the room. That gap is the job. That's the work I do every day, and if that question fascinated you rather than annoyed you, this channel's for you.

Now — remember I mentioned getting a definition wrong can end in a fine? Next time, I'll show you the exact kind of data mistake that's cost companies hundreds of millions of pounds — and most of the people who made it had no idea they were making it, right up until the fine landed. Watch that one before it happens to you.

If this gave you a clearer picture of the job, subscribe — there's a lot more of this coming, one decision at a time.

I'll see you in the next one.
