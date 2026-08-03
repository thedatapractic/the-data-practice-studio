# What Is Data Management? The Million-Dollar Problem Nobody Owns

**Status:** Draft v4.1 — Aji's editorial pass applied, plus a domain-language pass against `domain-knowledge.md` (2026-08-02)
**Template chosen:** flagship / explainer (`templates/flagship.md`) — definitional start-here topic, so it answers what it is, why we need it, and how we do it, and nothing else.
**Target runtime:** 7–8 minutes target, 10 maximum
**Thumbnail text:** "NOBODY OWNS IT"
**Description/tags:** what is data management, data management explained, metadata management, data quality, data ownership, data governance
**Playlist:** Data Foundations

---

### THE HOOK (0:00–0:50)

Let me ask you a question.

If a fire went through your office tonight, you would be insured for every single thing in it. The desks, the laptops, the server humming away in the cupboard nobody ever opens. Someone would write you a cheque, and you would buy it all back.

But what about your data? Twenty years of customer records, patient histories, student records, transactions. If that vanished, there is no policy on earth that brings it back.

Your organisation has someone who manages the money, someone who manages the people, and someone who manages the buildings. So who in your organisation manages the data?

### WHO I AM (0:50–1:20)

My name is Aji Saine, and I have over twelve years of combined experience in software development and data management. I looked after health records for more than 285,000 people across research sites in West Africa, where one wrong value could change what a doctor decided to do, and today I handle statutory reporting for a UK university.

So let me give you three things: what data management actually is, why an organisation cannot function without it, and how you would start on Monday.

### PART 1 — WHAT IT ACTUALLY IS (1:20–3:40)

Here is the plainest definition I can give you. Data management is the development and execution of the plans, policies, procedures and practices that deliver, control, protect and improve the value of data throughout its lifecycle, from the moment it is created to the day it is properly destroyed.

Notice what is missing from that sentence. There is no software in it and there are no servers, because the biggest misunderstanding about my profession is that managing data is the same thing as managing databases.

When I was managing clinical data, we recorded vaccination dates for children across three sites. One site recorded the date the vaccine was given. Another recorded the date it was entered into the register, which might be a fortnight later. And at the third, a fieldworker wrote down their best estimate, from a mother who could only remember it happened around the rainy season.

Same field. Same format. Three completely different meanings.

Run a coverage analysis on that and you get a clean, confident, beautifully formatted answer that happens to be wrong, and in public health a wrong answer is not a spreadsheet problem, it is a child who never got a vaccine.

And it is worth naming that failure precisely. Every one of those dates was valid. They passed every format rule and every range check you could write. They simply were not accurate, because they did not all describe the same event. Validation catches data that is malformed. Only knowing what a field means catches data that is wrong.

And here is the part that took me years to properly appreciate. There was nothing wrong with our database. It did its job perfectly, because a database has no opinion about meaning. What was missing was the business metadata, the agreed and written-down definition of what that column actually held, and that has a proper name in my profession. It is called metadata management, and it is one of the core disciplines inside data management.

That agreement is the work. Data management is somebody deciding what a field means, who owns it, what good looks like and what happens when it goes wrong, and then writing those decisions down as policy and procedure so they outlive the person who made them. The technology really is the easy part.

Which brings me to the question I get asked most often. If nobody is doing this, what is the actual harm?

### PART 2 — WHY YOU NEED IT (3:40–5:20)

Imagine there is a factory operating inside your building that nobody ever told you about. It runs all day, every day, it quietly employs a surprising number of your colleagues, and everything it produces goes straight in the bin.

That factory is real and you are paying for it. It is the analyst rebuilding a report because she does not trust the last one, and the two managers arguing about whose figure is correct instead of making the decision they came into the room to make. You are already paying for data quality, you are simply paying for the absence of it. Gartner puts that bill at around twelve million dollars a year for the average organisation.

Then there is the part that has nothing to do with money at all. Most of the data your organisation holds is not really yours. It is personal data, about people who handed it over and assumed somebody sensible was looking after it. I used to tell my team to treat every record as though it belonged to their own mother, because somewhere, it belongs to somebody's.

### PART 3 — HOW YOU ACTUALLY DO IT (5:20–8:00)

There are three moves here, and you could genuinely begin all of them this month.

The first is to put a name against the data, and I mean a person's name rather than a department's. For anything that matters, somebody should be able to answer who decides what this means and whether it is right. When the honest answer is that everybody does, what you actually have is nobody.

And be precise about which name you need. The person who holds that decision is your data owner. The person who maintains the definitions and chases down the problems day to day is your data steward. Those are two different jobs, and treating them as one is why so many organisations believe they have ownership when what they really have is a name on a slide.

But naming an owner is not an email you send. The people who create your data usually do not report to you, and they will not change how they work because a policy told them to. In my experience you win them over by making their job easier rather than harder, by training them properly, and by giving them the credit publicly when the data gets better. That is stakeholder engagement, and it is the difference between a data owner who exists on an org chart and one who actually does the job.

The second move is to write down what things mean. Ask five people in your organisation what counts as an active customer and you will often get five answers, and ask them when a student is properly enrolled and you will get five more. Get those definitions agreed and written down, stored beside the data itself, and you have started doing metadata management. What you are building is a business glossary. Think back to those vaccination dates, because that entire mess was one sentence nobody had written down.

The third is to fix problems where they start rather than where you happen to notice them. Data is like water in a river. If it is polluted at the source, everybody downstream drinks polluted water, and cleansing it separately at every point is the most expensive way to manage data. So put the validation where the data is created, and write it into the procedure people follow, rather than leaving it to a monthly tidy-up. When I moved our checks upstream in my own team, processing time fell by around sixty percent, and the people entering the data were noticeably happier, because they were corrected in the moment rather than criticised a month later.

None of that is a five-year transformation programme. It is a start you could make on Monday.

### THE LANDING (8:00–8:45)

So let me pull this together. Data management is the deliberate work of making data trustworthy, and you do it through plans, policies and practices that name an owner, write down what things mean, and catch problems at the source.

Here is something to try this week. Think of the one report your organisation argues about most, and see whether you can answer three questions about it. Who owns it, by name? Where is the metadata, meaning the written definition of what each field actually holds? And what happens downstream if it is wrong? Whatever you cannot answer is exactly where your work starts, so tell me in the comments which of those three stopped you.

Next time I want to show you the data mistake that has cost companies hundreds of millions in fines, and almost nobody who made it saw it coming.

If this was useful, subscribe and send it to the colleague who needs it more than you do. I will see you in the next one.
