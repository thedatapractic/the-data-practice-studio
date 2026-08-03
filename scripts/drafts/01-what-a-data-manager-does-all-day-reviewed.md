# Video 1 — What a Data Manager Actually Does All Day (It's Not Spreadsheets)

**Status:** Reviewed — ready for filming pending Aji's read-aloud pass
**Target runtime:** ~15 minutes (~2,150 words at 140wpm)
**Thumbnail text:** "NOT SPREADSHEETS" or "MY ACTUAL JOB" (with Aji, direct to camera)
**Description/tags:** what does a data manager do, data management career, data manager job description, day in the life data professional
**Playlist:** Behind the Data Job

---

### THE HOOK (0:00–0:45)

Tell someone your job title is "data manager" and watch what happens to their face.

They picture someone hunched over a spreadsheet. Or IT. Or — my personal favourite — "so you fix computers?"

Here's what actually filled my Tuesday last week: an argument about what the word "active" means.

Not a formula. A word. And by the end of it, I'd made the call that decided how a report to a regulator counted thousands of people.

That's the job. Nobody puts it on the tin.

Stick with me, because by the end of this video I'll hand you one question — one sentence, thirty seconds — that exposes this exact problem on your own team. In this video: what a data manager actually does. The decisions, not the job description.

### CREDIBILITY + PROMISE (0:45–2:00)

Quick reintroduction if you're new here — I'm Aji Saine. Twelve-plus years split between software development and data management.

I've done this work in two very different worlds. I managed clinical and health data covering over 285,000 people across research sites in West Africa. And today I work in statutory data reporting for a UK university, where the numbers I sign off decide funding.

In between, I've trained a team through the shift from Access to SQL Server — proactively, ahead of a system migration that's been "coming" for two years and still hasn't landed — and built dashboards, including for a demographic surveillance system covering hundreds of thousands of people, that people open every morning without a second thought.

Last week I told you data is an asset, and almost nobody's actually managing it properly. This week: what it looks like when somebody is. By the end, you'll be able to spot this exact work happening in your own organisation — even when nobody's calling it "data management."

Let's get into it.

### PART 1 — THE JOB TITLE IS LYING TO YOU (2:00–3:45)

Here's the first thing to unlearn. "Data manager" sounds like a technical title. It isn't, mostly.

I write code. I can, anyway — that's where I started. But on any given day, the code is the smallest part of the job. The actual work is decisions. Specifically, decisions nobody else in the building wants to make, because they sound boring until you realise how much rides on them.

What counts as an "active" customer. Whether a missing date means "we don't know" or "it never happened" — those are not the same thing, and treating them as the same thing has burned entire reports. Who's allowed to change a record, and who just gets to look at it. What happens to someone's data the day they leave the organisation — deleted, archived, or quietly kept forever because nobody ever decided.

None of that is a technology question. You could ask it with pen and paper. It's a governance question wearing a technology costume.

I put it this way to people I train: a database administrator keeps the filing cabinet working. A data manager decides what goes in which drawer, who's allowed to open it, and what it means when the label doesn't match what's inside.

So when I say I "manage data," I don't mean I sit with data all day. I mean I sit in the argument about what the data is supposed to represent.

That argument breaks down into three things nobody trains you for: you decide, you translate, and you foresee. None of that's on the job spec. All of it's the job. Let's start with deciding.

### PART 2 — YOU DECIDE (3:45–7:00)

Deciding what data means has followed me through three very different jobs, and the pattern's identical every time even though the stakes look nothing alike.

Back in my developer years, I built a system with a "client" field. It validated fine. It ran fine. No bug anywhere in the code. But some people typed in the organisation. Others typed in a specific staff member at that organisation — because nobody had actually agreed what "client" meant before the form went live. Same field, two different realities living inside it, and the software couldn't tell the difference. That was the first time I understood something: clean code sitting on top of a shaky definition is still a shaky system. It just fails more expensively, later, when nobody's looking.

Years later, in the clinical data years in West Africa, I hit the same wall at a much bigger scale. I've told you before about vaccination dates recorded three different ways across three sites. Here's what we actually did about it: built a data dictionary, wrote standard operating procedures for how data got captured, and trained every site against both. Getting there wasn't clean. Every single site believed they were the ones doing it right. It took a meeting with all three sites in the room, reconciling three different "correct" answers into one, before we had a definition anybody would actually stand behind. That decision affected how vaccine coverage got reported for a quarter of a million people. Get it wrong, and a region gets marked as under-vaccinated when it isn't — or worse, the other way round.

And it's still happening now, in UK higher education. Not long after I started, I noticed my own team fielding requests for "all of it" — every student's data, no scope, no stated purpose, handed over because saying yes was quicker than asking why. So I stopped it. We introduced a data access request policy: state what you need, state why, we run a needs assessment against that, and you get exactly that. Nobody outside the data team ever sees that policy get enforced. But it's the difference between a university that hands out data because someone asked nicely, and one that can actually account for who has access to what.

Different worlds, same job underneath: decide what the data means before anyone's allowed to trust what it says.

And deciding is the easy third of this job. The other two-thirds happen mostly outside any database at all.

### PART 3 — YOU TRANSLATE, YOU FORESEE (7:00–10:30)

Translating is next. Here's what that actually looks like.

While I was building dashboards for the Medical Research Council, on a Health and Demographic Surveillance System covering a huge population, requests to change those dashboards came constantly — a new metric, a "quick" tweak, one more breakdown. My rule was simple: every request gets assessed before it goes anywhere near the dashboard. If it would blur a definition, or quietly change what a number meant, it doesn't go in. That held even when the request came from management. I had the standing to give my own recommendation on how the data got presented, and I used it.

That's translating — standing between the technical language of a system, tables and keys and fields, and the language people actually use every day: "the student," "the return," "the active case." Your job is making sure both sides are still describing the same thing, because the moment they quietly drift apart, that's when a report stops being trusted and nobody can say why. Saying no is part of the job description, even though nobody writes it down anywhere.

Foreseeing is the third one, and it's happening to me right now — not a tidy story from the past. The university's been planning a move to a new student record system, one that runs on SQL Server, for two years. It still hasn't gone live — the institution's own timeline keeps slipping. My team, until recently, only had real depth in Access.

I didn't wait for the go-live date, because a date that's already slipped once tends to slip again, and the day it finally happens is the worst possible day to discover your team doesn't have the skills for it. So I started training them in SQL Server now, on top of everything else they're doing. Nobody assigned me that. It's not on any list of duties. It's the job anyway — spotting the change coming before the organisation itself is ready for it.

Decide. Translate. Foresee. That's the actual job description, and none of it fits on a business card.

So if that's the job — deciding, translating, foreseeing, mostly invisible — why does any of it matter enough to lose sleep over? That's the part that made me take this career seriously in the first place.

### PART 4 — WHY THE JUDGMENT CALLS ARE PERSONAL (10:30–12:30)

I've managed data about real people for most of my career. Not rows. People.

When you're the one deciding how a health record gets standardised, you're not tidying a spreadsheet — you're shaping what a clinician sees the next time that patient walks in. When you're the one deciding how a university's return is compiled, you're shaping whether a struggling department gets flagged for support or gets quietly deprioritised, based on numbers most people will never question.

I used to tell my team: treat every record as if it belonged to your own mother. I still mean it. Because somewhere behind every "edge case" you're tempted to wave through, there's a person who has no idea a decision about them is being made by someone they've never met, based on a definition they never agreed to.

That's why the job isn't clerical. A clerk follows the rule. A data manager is often the one in the room deciding what the rule should be — quietly, under a deadline, with real consequences riding on getting it right. Get it wrong, and it's not a bug ticket. Somewhere, it's a wrong medical picture on a clinician's screen. Somewhere else, it's a department wrongly flagged as underperforming, because of one number nobody double-checked.

That weight is exactly why this work needs people who take it seriously — not just people who are good with computers. Which, weirdly, is good news: it means this job isn't reserved for whoever's best at SQL.

### THE LANDING + HOMEWORK (12:30–15:00)

So here's what a data manager actually does. Decide what the data means. Translate between the people who build the systems and the people who depend on them. Foresee the changes coming before the organisation itself is ready. None of it's clerical. All of it's quiet — nobody claps for a well-defined field — but get it wrong and the consequences show up everywhere from a clinic to a funding return to a fine in the newspaper.

And the best data people I've worked with weren't always the strongest coders. They were the ones who got genuinely uncomfortable when two people used the same word to mean two different things — who'd stop a meeting to ask what a term actually meant, even when it made the meeting run long. If any of that sounds less like a job title and more like something you're already doing — under "analyst," "administrator," or a title with no mention of data in it at all — you may already be in this job. Nobody's given you the title yet.

Here's the question I promised you at the start. This week, notice the next time someone in a meeting uses a word like "active," "current," or "complete" as if everyone agrees what it means. Ask, out loud: "quick check — what do we actually mean by that?" Watch how many different answers you get in the room. That gap is the job.

Now — remember I mentioned a definition, done wrong, can end in a fine? Next time, I'll show you the exact kind of data mistake that's cost companies hundreds of millions of pounds — and most of the people who made it had no idea they were making it, right up until the fine landed. Watch that one before it happens to you.

If this gave you a clearer picture of the job, subscribe — there's a lot more of this coming, one decision at a time.

I'll see you in the next one.
