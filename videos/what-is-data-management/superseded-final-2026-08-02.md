# What Is Data Management? The Million-Dollar Problem Nobody Owns

> ## ⚠️ SUPERSEDED — DO NOT FILM FROM THIS FILE
>
> **The live script is [`final.md`](final.md).** This file was the `final.md` of 2026-08-02; it was archived under this name on 2026-08-11 when the reworked script was promoted into that filename.
>
> This file is kept as the unedited record of the 2026-08-02 state. It is **out of date** in six ways: the retired fire-and-insurance hook, the old subtitle ("The Million-Dollar Problem Nobody Owns" is now "The Job Nobody Owns"), the owner-versus-steward and stakeholder-engagement passages that were lifted to backlog #15, no map locating line, no bridge from Part 2 into Part 3, and a personal-data beat that did not name its discipline.
>
> Its **runtime header below is also wrong**: it says ~9.5 minutes, and the file is 1,398 words, which is 9:59 at 140 wpm.
>
> One note in this file is known to be incorrect and has been left in place rather than edited: the transcription-slip list records **"aren't really theirs" → "isn't really yours"** as a corrected dictation artefact. Aji has confirmed **"theirs" was deliberate**, so that was a voice choice overwritten as a slip. `final-v2.md` restores "theirs" and explains why.

**Status:** SUPERSEDED 2026-08-11 by `final-v2.md`. Was: "FINAL — Aji's own edit. This is the authority. Agents do not rewrite this file." Still not to be rewritten — it is a historical record.
**Source:** Aji's edited draft, 2026-08-02, reworked from agent draft v5 to fit her tone, rhythm and word choices.
**Runtime:** ~9.5 minutes
**Playlist:** Data Foundations

---

### THE HOOK

Let me ask you a question.

If your organisation building caught fire tonight, you would be insured for every single thing in it. The laptops, the desk, the server all replaceable.

But what about your data? Twenty years of customer records, patient histories, student records, transactions. If that vanished, there is no insurance policy on earth that brings it back.

Your organisation has someone managing its money, that's finance, it's people, HR, and it's buildings and equipment. So, who in your organisation manages the data?

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

And here is the part that took me years to properly appreciate. There was nothing wrong with our database. It did its job perfectly, because a database has no opinion about meaning. What was missing was the business metadata, the agreed and written-down definition of what that column actually meant. That has a proper name in my profession and it's called metadata management. It is one of the core disciplines inside data management.

Data management is somebody deciding what a field means, who owns the data, what good looks like and what happens when it goes wrong, and then writing those decisions down as policy and procedure so they outlive the person who made them.

Which brings me to the question I get asked most often. If nobody is doing this, what are the consequences?

### PART 2 — WHY YOU NEED IT

Imagine there is a factory operating inside your building that nobody ever told you about. It runs all day, every day, it quietly employs a surprising number of your colleagues, and everything it produces goes straight in the bin.

That factory is real. It is the analyst rebuilding a report because she does not trust the last one, and the two managers arguing about whose figure is correct instead of making the decision they came into the room to make. You are already paying for data quality, you are simply paying for the absence of it. According to the Gartner research from 2020, this is costing the average organisation around twelve point nine million dollars a year.

Then there is the part that has nothing to do with money at all. Most of the data your organisation holds isn't really yours. It is personal data, about people who handed it over and assumed somebody sensible was looking after it. I used to tell my team to treat every record as though it belonged to their own mother, because somewhere, it belongs to somebody's.

### PART 3 — HOW YOU ACTUALLY DO IT

So how do we manage data? I'll give you three moves you could genuinely begin this month.

The first is to put a name against the data, and I mean a person's name rather than a department. For anything that matters, somebody needs to answer who decides what this means, and whether it is right. When the honest answer is that everybody does, what you mean is, it's nobody.

And be precise about whose name you need. The person who holds that decision is the data owner. The person who maintains the definitions and chases down the problems day to day is your data steward. Those are two different jobs and treating them as one is why so many organisations believe they have ownership when what they really have is a name on a slide.

But naming an owner is not an email you send. The people who create your data usually do not report to you, and they will not change how they work because a policy told them to. In my experience you win them over by making their job easier rather than harder, by training them properly, and by giving them the credit publicly when the data gets better. That is stakeholder engagement, and it is the difference between a data owner who only exists on an org chart and one who actually does the job.

The second move is to write down what things mean. Ask five people in your organisation what counts as an active customer and you will often get five answers, and ask them when a student is properly enrolled and you will get five more. Get those definitions agreed to and written down, stored beside the data itself, and you have started doing metadata management. What you are building is a business glossary. Think back to those vaccination dates I mentioned earlier, because that entire mess was one sentence nobody had written down.

The third is to fix problems where they start rather than where you happen to notice them. Data is like water in a river. If it is polluted at the source, everybody downstream drinks polluted water, and cleansing it separately at every point is the most expensive way to manage data. So put the validation where the data is created, and write it into the procedure people follow, rather than leaving it to a monthly tidy-up. When I moved our checks upstream in my own team, processing time fell by around sixty percent, and the people entering the data were noticeably happier, because they were corrected in the moment rather than having to redo them all over a month later.

None of that is a five-year transformation programme. It is a start you could make today.

### THE LANDING

So let me pull this together. Data management is the deliberate work of making data trustworthy, and you do it through plans, policies and practices that name an owner, write down what things mean, and catch problems at the source.

Here is something to try this week. Think of the one report your organisation argues about most and see whether you can answer three questions about it. Who owns it, by name? Where is the metadata, meaning the written definition of what each field actually holds? And what happens downstream if it is wrong? Whatever you cannot answer is exactly where your work starts, so tell me in the comments which of those three stopped you.

Next time I want to show you the data mistake that has cost companies hundreds of millions in fines, and almost nobody who made it saw it coming.

If this was useful, subscribe and send it to the colleague who needs it more than you do. I will see you in the next one.

---

## Production notes

**Transcription slips corrected in this copy** (from the Word version, all clearly dictation artefacts rather than voice choices, flagged here so nothing was changed silently): "coting" → quoting · "is literally determine" → literally determines · "we had third senior" → we had a third scenario · "what is the consequences" → what are the consequences · "who's name" → whose name · "somebody needs answer" → somebody needs to answer · "what you means is" → what you mean is · "aren't really theirs" → isn't really yours · "buildings and equipment's" → buildings and equipment · "for the." → sentence completed.

**Still outstanding:** on-screen source credit for the Gartner figure (2020).
