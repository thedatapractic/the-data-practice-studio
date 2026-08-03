# What a Data Manager Actually Does All Day (It's Not Spreadsheets)

**Status:** Draft v2 — Dan's ordinal-label fix applied. Ready to film. (1,042 words, 7.4 min)
**Template chosen:** career-thread / multi-chapter reflection (`templates/career-thread.md`) — this is the video that template was written for: one pattern pulled through several chapters of a career, building to a nameable framework.
**Target runtime:** 7–8 minutes
**Thumbnail text:** "NOT SPREADSHEETS"
**Description/tags:** what does a data manager do, data management career, data manager job description, data governance career
**Playlist:** Behind the Data Job

---

### THE HOOK (0:00–0:45)

Years ago, back when I was writing software for a living, I built a system with a field on it called "client".

It worked perfectly. The code was clean, the validation passed, and there was not a single bug anywhere in it. But some people typed the name of the organisation into that field, and other people typed the name of a particular member of staff at that organisation, and the system had no way of telling the difference. Nobody had ever agreed what "client" actually meant before the form went live.

I could not fix that with better code. I have spent the rest of my career on the other side of that problem, and it turns out it has a job title.

In the next few minutes I'll show you what a data manager actually does all day, so you can spot the work in your own organisation even when nobody is calling it data management.

### WHO I AM (0:45–1:15)

My name is Aji Saine, and I have over twelve years of combined experience in software development and data management. I looked after health records for more than 285,000 people across research sites in West Africa, and today I handle statutory data reporting for a UK university.

Three chapters, three completely different worlds, and the same job underneath all of them.

### PART 1 — YOU DECIDE WHAT THINGS MEAN (1:15–3:30)

Deciding what the data means is where it starts, and that decision usually happens long before anyone writes a line of code.

Years later, in my clinical data years in West Africa, I hit that same "client" problem at a scale where it mattered a great deal more. I've mentioned before that we recorded vaccination dates three different ways across three sites. What I haven't told you is what we actually did about it.

We built a data dictionary, we wrote standard operating procedures for how the data was captured, and we trained every site against both. Getting there was not clean. Every single site believed they were the ones doing it correctly, and they each had a reasonable argument. It took a meeting with all three sites in the room, reconciling three different correct answers into one, before we had a definition anybody would stand behind.

That definition then decided how vaccine coverage was reported for a quarter of a million people, and getting it wrong in either direction has real consequences for a public health programme.

And it's still happening now. Not long after I started in higher education, I noticed my own team fielding requests for all of it, every student's data, no scope and no stated purpose, handed over because saying yes was quicker than asking why. So we stopped. We introduced a data access request policy: state what you need, state why, we assess that against what you actually need, and you get exactly that and nothing more.

Nobody outside the team ever sees that policy being applied. It is the difference between an organisation that hands out personal data because somebody asked nicely, and one that can account for who holds what.

Different decades, different countries, same job underneath. Decide what the data means before anyone is asked to trust what it says.

### PART 2 — YOU TRANSLATE (3:30–5:15)

Translating is the part that happens almost entirely outside a database.

While I was building dashboards for the Medical Research Council, on a health and demographic surveillance system covering a very large population, requests to change those dashboards arrived constantly. A new metric, a quick tweak, one more breakdown. My rule was that every request was assessed before it went anywhere near the dashboard, and if it would blur a definition or quietly change what a number meant, it did not go in. That held even when the request came from management, because I had the standing to give my own recommendation on how the data was presented, and I used it.

That is what translating means. You stand between the language of a system, its tables and keys and fields, and the language people actually use in a meeting: the student, the return, the case. Your job is making sure both sides are still describing the same thing, because the moment they drift apart is the moment a report stops being trusted and nobody can explain why.

Saying no is part of the job. Nobody writes that down anywhere.

### PART 3 — YOU SEE IT COMING (5:15–7:00)

Seeing it coming is the one that is happening to me right now, rather than being a tidy story from the past.

The university has been planning a move to a new student record system, one that runs on SQL Server, for two years. It still has not gone live, because the institution's own timeline keeps slipping. My team, until recently, only had real depth in Access.

I did not wait for the go-live date. A date that has already slipped once tends to slip again, and the day it finally arrives is the worst possible day to discover your team does not have the skills for it. So I started training them in SQL Server now, on top of everything else they are carrying. Nobody assigned me that, and it is not on any list of duties. It is the job anyway.

Decide, translate, foresee. That is the actual job description, and none of it fits on a business card.

### THE LANDING (7:00–7:45)

So that is what the work is. You decide what the data means, you translate between the system and the people who depend on it, and you see the change coming before the organisation is ready for it. Notice that almost none of that is technical. It is judgement, and it is mostly invisible until it is missing.

Here is something to try this week. Think about the last time two people in your organisation disagreed about a number. Not about what to do, about what the number actually was. Somebody in that room was doing this job, whatever their title says. It may well have been you.

Next time I want to show you the data mistake that has cost companies hundreds of millions in fines, and almost nobody who made it saw it coming.

If this was useful, subscribe and send it to the colleague who needs it more than you do. I will see you in the next one.
