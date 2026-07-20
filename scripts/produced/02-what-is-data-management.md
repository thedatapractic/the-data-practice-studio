# Video 2 — What Is Data Management? The $3 Trillion Problem Nobody in Your Company Owns

**Status:** Produced — script final
**Target runtime:** ~15 minutes (~2,150 words at 140wpm)
**Thumbnail text:** "$3 TRILLION PROBLEM" or "NOBODY OWNS IT" (with Aji + the DMBOK book)
**Description/tags:** DMBOK, DAMA-DMBOK Chapter 1, CDMP, data management explained
**Playlist:** DMBOK Explained

---

### THE HOOK (0:00–0:45)

Let me ask you a question.

If your organisation's building caught fire tonight — God forbid — the insurance would cover the building. The laptops, the desks, the servers. All replaceable. All insured.

But what about your data?

Twenty years of customer records, patient histories, student records, transactions? If that vanished, there's no insurance policy on earth that brings it back.

And here's the strange part — most organisations spend more time and money managing their office chairs than they do managing their data.

In this video I'm going to show you why that is, what it's actually costing — the best estimates put it in the trillions of $ — and near the end I'll give you a fifteen-minute exercise that will tell you more about your organisation's data than a fifty-page consultancy report.

### CREDIBILITY + PROMISE (0:45–2:00)

Hi — my name is Aji Saine, and I've over twelve years of combined experience in data management and software development. I have spent my career in both sides of this problem.

I managed clinical and health data covering over 285,000 people across research sites in West Africa, where a single data error could affect a medical decision. And today I work in statutory data reporting for a UK university, where the data we submit literally determines funding and regulation.

So when I tell you data management matters — I'm not quoting a textbook. I've lived it.

But there is a textbook. The big one.

This is the DAMA-DMBOK — the Data Management Body of Knowledge. It's the reference book for my entire profession — and, let's be honest, it's intimidating. Six hundred pages, 17 chapters. Most people buy it, read ten, and it becomes the most expensive bookend in their house.

So I'm doing the reading for you. On this channel I'm going to take the whole discipline apart, one idea at a time — and today we start with its single most important argument.

And by the end of this video, you'll see data differently. Not as an IT problem. Not as files on a server. But as what it really is — an asset. Maybe the most valuable asset your organisation owns.

So grab a coffee. Let's get into it.

### PART 1 — DATA DOESN'T SPEAK FOR ITSELF (2:00–4:00)

Right. Before we can manage data, we have to agree on what it is.

You've probably seen the classic pyramid — data at the bottom, then information, knowledge, and wisdom at the top. The idea being that data is just raw, meaningless stuff.

The professionals say: be careful. That's misleading.

Data isn't raw. Data is a form of representation. When somebody recorded that fact — a birth date, a blood pressure reading, an exam grade — they made choices. What to capture. How to define it. What to leave out. Data already carries meaning baked in.

Let me make that real. In my clinical data management days, we recorded vaccination dates for children across three sites.

One site recorded the date the vaccine was given. Another recorded the date it was entered into the register. And sometimes a parent could only remember it was around the rainy season.

Same field. Same format. Three completely different meanings. Treat that column as "raw facts" and you'd draw the wrong conclusions about vaccine coverage — and in public health, wrong conclusions are costly.

So here's your first mindset shift: data doesn't speak for itself. Data needs context to become information — and that context is called metadata.

Hold onto that word. Metadata. We're coming back to it.

### PART 2 — THE ONE SENTENCE THAT MATTERS (4:00–6:30)

Now, if you remember one sentence from this entire video, make it this one:

Data is an asset. And assets must be managed.

Think about it. Your organisation manages its money — there's a whole finance department for that. It manages its people — that's HR. It manages its buildings and equipment.

Now ask yourself honestly: who, in your organisation, manages the data? Not the servers. Not the software. The data itself.

In most organisations, the answer is... nobody in particular. Everybody touches it. Nobody owns it.

And data is a weird asset. It doesn't behave like money or buildings — and these differences explain almost every data problem you've ever had.

First — data isn't consumed when it's used. Spend a pound and it's gone. Use a dataset and it's still there. You and I can even use the same data at the same time.

Second — data can be copied effortlessly. And that's a curse as much as a blessing, because the same "fact" ends up living in ten places, the copies drift apart, and nobody knows which one is right. Trust starts to erode.

Third — data isn't tangible, so nobody notices it degrading. If a delivery van breaks down, everyone sees it. If a customer database quietly rots, nobody sees anything until a decision goes wrong. Data problems are invisible until they're expensive.

And fourth — the value of data is hard to measure. But here's the clever bit: even if you can't price the data itself, you can absolutely measure the cost of bad data. Rework. Fines. Missed opportunities. Reputational damage.

I see this every day. In UK higher education, universities submit statutory data returns to regulators. If that data is wrong, funding is affected. League tables are affected. The regulator can come knocking with an audit.

Nobody would say "our data is worth X pounds" — but everybody understands what it costs when it's wrong.

So stop thinking of data as a by-product — the exhaust fumes of doing business. It's an asset on a par with money and people. Which raises the obvious question: how on earth do we manage it?

### PART 3 — WHAT MANAGING DATA ACTUALLY MEANS (6:30–8:30)

The formal definition says data management is the development, execution, and supervision of plans, policies, programs, and practices that deliver, control, protect, and enhance the value of data throughout its lifecycle.

That's a mouthful, so let me pull out the three things that matter.

One — notice it's plans, policies, programs, and practices. This is organised, deliberate work. Not heroics. Not one clever analyst fixing things at midnight. Structured, ongoing activity.

Two — notice the verbs: deliver, control, protect, enhance. Deliver — get data to the people who need it. Control — govern it and keep it consistent. Protect — security, privacy, compliance. Enhance — actively increase its value over time.

Three — data has a lifecycle. It gets planned for, designed, created, stored, used, shared, and eventually archived or destroyed. And the decisions made early in that lifecycle determine everything downstream.

Data is like water in a river — if it's polluted at the source, everyone downstream drinks polluted water. Cleaning it downstream, over and over, is the most expensive way to manage it. Getting it right at the point of creation is the cheapest.

One more thing — and this is one of my favourite points. Managing data is not the same as managing databases.

Buying a shiny new system does not manage your data, any more than buying a filing cabinet organises your paperwork. The business defines what the data means and what quality looks like. IT provides the machinery. Hand it all to IT, and you get technically perfect systems full of data nobody trusts.

I learned this the hard way when I moved from software development into data management. I could write the cleanest code you've ever seen — but if two departments define "active customer" differently, my beautiful system faithfully stores beautiful nonsense.

The system was never the problem. The shared understanding was.

### PART 4 — WHY IT'S SO HARD: THE FOUR CHALLENGES (8:30–12:00)

So why is this so hard? Let me give you the four big reasons — and stay with me, because challenge four is the one that gets personal.

Challenge one: quality doesn't happen by accident. High-quality data is not the natural state of things. Left alone, data degrades — people move house, definitions drift, systems change.

Data quality is a garden, not a statue. You don't achieve it once. You maintain it forever.

And the cost of ignoring it is staggering. Estimates put bad data at between ten and thirty percent of company revenue — IBM famously priced the cost of bad data in the US alone at over three trillion dollars in a single year. Trillion. With a T.

Where does that money go? Into what I call the hidden data factory — all the people quietly correcting, reconciling, and working around bad data instead of doing their actual jobs. Think about how much time your colleagues spend arguing about whose spreadsheet is right. You're already paying for data quality. You're just paying for the absence of it.

Challenge two: metadata. Told you it was coming back. You cannot manage data without metadata, because metadata is the context — the data about the data. Definitions, origins, rules, lineage, who owns it, how it's used.

Remember my vaccination dates story? The problem wasn't the data. It was the missing metadata about what the date actually meant. And because data is intangible, metadata is how we make it visible. Metadata is your torch in the warehouse.

Challenge three: data doesn't respect departmental boundaries. A student's record flows through admissions, finance, support services, reporting. No single team sees the whole journey, but the data has to be coherent across all of it.

That's why data governance exists. Not as bureaucracy for its own sake — but as the referee that lets many players play the same game.

And challenge four — this one deserves a moment. Much of the data organisations hold isn't really theirs, is it? It's data about people. Customers, patients, students, employees. Real human beings who handed over their information and trusted us with it.

That trust comes with ethical and legal obligations — privacy law like GDPR here in the UK and Europe, plus regulations across finance, health, and beyond. Data can be lost, stolen, misused. And low-quality data is a risk all of its own — decisions made on wrong information hurt real people.

This is personal for me. When you've managed health data for hundreds of thousands of people — mothers, children, entire communities — you stop seeing rows in a table.

I used to tell my data team: treat every record as if it belonged to your own mother. Because somewhere, it belongs to somebody's mother.

Now notice something about all four challenges. Almost none of them are technology problems. They're problems of ownership, definition, planning, and behaviour. Which is exactly why data management is a discipline — not a product you can buy.

### PART 5 — THE MAP: THE DAMA WHEEL (12:00–13:30)

So where do you start? With a map — and the profession has a famous one, called the DAMA Wheel.

Picture a wheel with data governance at the centre, and around it the knowledge areas: architecture, modelling, storage and operations, security, integration, document and content management, reference and master data, warehousing and business intelligence, metadata, and data quality. Eleven areas in total.

Don't panic — I'll cover each of these properly in its own video. What matters today is the shape.

Governance sits at the hub because every spoke connects to it. Governance is where the organisation decides how decisions about data get made — who owns what, what the standards are, who's accountable. Without the hub, the spokes just fall on the floor.

And here's how I'd use it: the wheel isn't a syllabus to memorise. It's a mirror.

When I first led a data team, I mentally lived in two segments — storage and a bit of BI, because that's where my developer instincts pointed. The wheel forced me to ask uncomfortable questions. Who governs our definitions? Where is our metadata written down — or is it living in three people's heads?

Hold the wheel up to your organisation and you'll instantly see which segments are strong, which are weak, and which are simply missing.

One last thing — the strategy point. Your data strategy must come from the business strategy. Nobody wakes up craving master data. The goal is what your organisation can do because its data is trustworthy: better decisions, better services, less waste, less risk.

If your executives can't understand your data strategy, it isn't finished.

### THE LANDING + HOMEWORK (13:30–15:00)

So let's land this plane.

We started with the one asset insurance can't replace. And in fifteen minutes we've built the whole argument.

Data is an asset. Assets must be managed. Managing data means managing its quality, its context, its lifecycle, and its risks — deliberately, across the whole organisation, with real leadership behind it. And that is a discipline.

Tomorrow morning, when you open that spreadsheet at work, I want a small voice in your head asking three questions. Who owns this data? What does this field actually mean — and where is that written down? And what happens downstream if this is wrong?

The moment you start asking those questions, you've started doing data management.

And here's the exercise I promised you at the start. Sketch the DAMA wheel for your own organisation. Eleven segments. Give each one a traffic light — green, amber, red — based on your honest gut feeling.

That one-page picture will tell you more about your data maturity than a fifty-page consultancy report — and it costs you fifteen minutes and a cup of coffee. Tell me in the comments which segment came out reddest. I have a suspicion it'll be metadata or governance for most of you, and I'd love to be proven wrong.

Now — remember challenge four? Other people's data, and the trust that comes with it? There's a data mistake connected to exactly that which has cost companies hundreds of millions in fines — and most of the people who made it had no idea they were making it. That's the next video. Watch it before your organisation stars in it.

If this was useful, you know what to do. Like the video, subscribe, and share it with that one colleague.

I'll leave you with this. Buildings depreciate. Equipment wears out. Money gets spent. But data, managed well, is the one asset that can become more valuable every single year you hold it.

The question is never whether your organisation has valuable data. The question is whether anyone's managing it.

I'll see you in the next one.
