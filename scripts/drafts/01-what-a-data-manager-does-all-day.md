# Video 1 — What a Data Manager Actually Does All Day (It's Not Spreadsheets)

**Status:** Drafted — fresh rewrite, built natively as the career-thread template
**Template:** Career-thread / multi-chapter reflection (CLAUDE.md → Script templates #3)
**Target runtime:** ~15 minutes (~2,150 words at 140wpm)
**Thumbnail text:** "NOT SPREADSHEETS" or "MY ACTUAL JOB" (with Aji, direct to camera)
**Description/tags:** what does a data manager do, data management career, data manager job description, day in the life data professional
**Playlist:** Behind the Data Job

---

### THE HOOK (0:00–0:45)

Forty minutes. That's how long I sat in a meeting last Tuesday, arguing about a single word: "active."

Whiteboard covered in half-erased definitions. Three people, all convinced they were right. A submission deadline creeping closer with every one of those forty minutes.

Not a formula. Not a system. A word.

By the end of it, I'd made the call that decided how a report to a regulator counted thousands of people.

Tell someone your job title is "data manager" and they picture a spreadsheet. Or IT. Or — my personal favourite — "so you fix computers?"

Nobody puts this on the job description. So let me show you what actually fills it — three different careers, one pattern running underneath all of them. By the end, you'll know exactly what this work is, whether you're already doing it under a different title, or wondering if it's the one you're meant for.

### CREDIBILITY + PROMISE (0:45–2:00)

I'm Aji Saine. Twelve-plus years, and I've done this job in three genuinely different worlds: software development, clinical data for over 285,000 people across research sites in West Africa, and right now, statutory data reporting for a UK university, where the numbers I sign off decide funding — not hypothetically, this year's actual funding.

Three different worlds, three completely different sets of stakes. This video pulls one thread through all of them, because the pattern is identical every time, even when nothing else is. By the end, you'll be able to spot this exact work happening in your own organisation — even when nobody around you is calling it "data management."

Let's get into it.

### THE DEVELOPER YEARS (2:00–4:00)

Back in my developer years, I built a system with a "client" field. It validated fine. It ran fine — no bug anywhere in the code. But some people typed in the organisation. Others typed in a specific staff member at that organisation, because nobody had actually agreed what "client" meant before the form went live. Same field, two different realities living inside it, and the software couldn't tell the difference.

Nobody noticed for months. The system kept running, the reports kept generating, everything looked fine — right up until someone tried to reconcile two departments' client counts and got two different answers out of the exact same database.

Fixing it wasn't a five-minute change, either. We had to agree, formally, whether "client" meant the organisation paying the invoice or the individual using the service, write that decision down somewhere everyone could actually see it, and then go back and correct records that had already been entered wrong. The code never changed. The definition did. That's usually where the real work turns out to be.

That was the first time I understood something that's never left me since: clean code sitting on top of a shaky definition is still a shaky system. It just fails more expensively, later, when nobody's looking.

It wouldn't be the last time deciding what data actually meant turned out to be the real job. The stakes just got a lot higher from here.

### THE CLINICAL DATA YEARS, WEST AFRICA (4:00–7:15)

Years later, I hit the same wall at a completely different scale. Vaccination dates, recorded three different ways across three research sites — the date the vaccine was given, on one site's forms. The date it was entered into the register, on another. And on a third, whatever a parent could remember, which was sometimes just "around the rainy season."

Same field. Same format. Three different realities — and this time the stakes weren't a messy internal report. They were how vaccine coverage got calculated for a quarter of a million people. Get that wrong, and a whole region gets marked as under-vaccinated when it isn't. Or worse, the other way round.

Fixing it took more than a decision. We built a data dictionary — clear, agreed descriptions for every field — wrote standard operating procedures for how data got captured, and trained every site against both. But getting there wasn't clean. Every single site believed they were the ones doing it right. It took a meeting with all three sites in the room, reconciling three different "correct" answers into one, before we had a definition anybody would actually stand behind.

It wasn't a comfortable meeting. Three teams, three sets of good intentions, and nobody wanting to hear that the way they'd been doing it for years was part of the problem. But by the end, we had one definition, written down, that all three sites could point to instead of arguing from memory.

One of those sites had, for two years, been reporting coverage numbers that looked strong on paper. Once we standardised the definition, the real number came in noticeably lower — not because vaccination rates had actually dropped, but because we'd finally stopped double-counting children whose paperwork had passed through two different systems. That's not a comfortable number to hand to a funder. It was, however, the true one.

I used to tell my team afterwards: treat every record like it belongs to your own mother. Because somewhere behind every "edge case" you're tempted to wave through, there's a real person who has no idea a decision about them is being made by someone they've never met.

That instinct — decide, then defend the decision, then live with what it protects — followed me straight into the job I'm in now.

### RIGHT NOW, UK HIGHER EDUCATION (7:15–10:00)

Not long after I started in UK higher education, I noticed my own team fielding requests for "all of it" — every student's data, no scope, no stated purpose, handed over because saying yes was quicker than asking why. So I stopped it. We introduced a data access request policy: state what you need, state why, we run a needs assessment against that, and you get exactly that.

One request, early on, was for a full extract of every current and former student's contact details, "just in case it's useful." That's the kind of request that used to sail through without a second thought. Now it doesn't — not without someone telling us specifically why they need it. Nobody outside the data team ever sees that policy get enforced. But it's the difference between a university that hands out data because someone asked nicely, and one that can actually account for who has access to what.

There's something else happening in this job right now, too — not a tidy story from the past. The university's been planning a move to a new student record system, one that runs on SQL Server, for two years. It still hasn't gone live; the institution's own timeline keeps slipping. My team, until recently, only had real depth in Access.

I didn't wait for the go-live date, because a date that's already slipped once tends to slip again, and the day it finally happens is the worst possible day to discover your team doesn't have the skills for it. So I started training them now — an hour here, a real piece of work there, on top of everything else they're already doing. Slower than a dedicated crash course would be, but it means that whenever the switch actually flips, that's not the thing we're behind on.

Six months in, two of my team can now write queries in SQL Server that would have taken them a full day in Access. They don't love every session — nobody loves homework stacked on top of a full workload — but they show up, because I've been straight with them about why. Nobody assigned me any of that. It's not on any list of duties. It's the job anyway.

### ONE MORE CHAPTER (10:00–11:45)

While I was building dashboards for the Medical Research Council, on a Health and Demographic Surveillance System covering a huge population, that dashboard was the first thing several directors looked at every morning — birth registrations, death registrations, disease surveillance, across a population most spreadsheets were never built to hold. Requests to change it came constantly — a new metric, a "quick" tweak, one more breakdown. My rule was simple: every request gets assessed before it goes anywhere near the dashboard. If it would blur a definition, or quietly change what a number meant, it doesn't go in. That held even when the request came from management. I had the standing to give my own recommendation on how the data got presented, and I used it.

One request I remember well: someone wanted a new metric added mid-year that would have sat right next to an existing one, looking almost identical on screen, but calculated a completely different way underneath. An innocent-sounding request. It would have quietly made every month-on-month comparison meaningless the moment it went live. It didn't go in. Another time, someone asked to merge two age brackets that had always been reported separately, because the smaller one "wasn't statistically interesting on its own." Harmless on paper. In practice, it would have erased exactly the group a maternal health programme needed visibility into. That one didn't go in either.

Four jobs. Four completely different worlds — a dev team, a health surveillance programme, a UK statutory body, twice over. And underneath every single one of them, the same few things kept happening, whether anyone called it a job or not.

I didn't plan that thread on purpose. I moved from writing code, to health data, to statutory reporting because each job interested me for its own reasons at the time, not because I could see some grand pattern coming. It was only looking back, putting these stories next to each other the way I'm doing right now, that I noticed I'd been doing the same job the whole time — just with the furniture rearranged.

None of it was clerical work. A clerk follows the rule. I was usually the one in the room deciding what the rule should be — quietly, under a deadline, with real consequences riding on getting it right. Get it wrong, and it's not a bug ticket. Somewhere, it's a wrong medical picture on a clinician's screen. And somewhere else, wrong for long enough, it's a fine with your organisation's name on it.

### THE LANDING + HOMEWORK (11:45–15:00)

So here's what those four jobs actually add up to.

I decide what data means — the "active," the "client," the "vaccinated" — before anyone's allowed to trust what it says. I translate, standing between the language a system speaks and the language people actually use, and I say no when the two are about to quietly drift apart, even when "no" is the least popular answer in the room. And I foresee the change coming, before the organisation itself is ready for it, because waiting for the official announcement is how teams get caught flat-footed.

Decide. Translate. Foresee. That's the actual job description, and it's never once fit on a business card.

If any of that sounds less like a job title and more like something you're already doing — under "analyst," "administrator," or a title with no mention of data in it at all — you may already be in this job. Nobody's given you the title yet.

Here's something to try this week. Notice the next time someone in a meeting uses a word like "active," "current," or "complete" as if everyone agrees what it means. Ask, out loud: "quick check — what do we actually mean by that?" Don't let it slide even if it makes the meeting run two minutes long. Watch how many different answers you get in the room. That gap — the space between what everyone assumed and what people actually meant — is the job. It was in a meeting room in Access years ago, it was on a whiteboard last Tuesday, and it'll be there again next week, whether or not anyone in the room calls it data management.

Now — remember I mentioned a definition, done wrong, can end in a fine? Next time, I'll show you the exact kind of data mistake that's cost companies hundreds of millions of pounds — and most of the people who made it had no idea they were making it, right up until the fine landed. Watch that one before it happens to you.

If this gave you a clearer picture of the job, subscribe — there's a lot more of this coming, one decision at a time.

I'll see you in the next one.
