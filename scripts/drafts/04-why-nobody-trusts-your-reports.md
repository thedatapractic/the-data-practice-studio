# Video 4 — Why Nobody Trusts Your Reports (And How To Fix It)

**Status:** Drafted — self-reviewed, pending Aji's read-aloud pass
**Template:** Flagship / deep-dive teaching — chosen because the fix requires unlearning a misconception (people blame the dashboard, not the data) before the real cause and framework can land. See reasoning in `production-log.md`.
**Target runtime:** ~15 minutes (~2,150 words at 140wpm)
**Thumbnail text:** "NOBODY TRUSTS THIS NUMBER" or "74% CATCH IT FIRST" (with Aji, arms folded next to a dashboard)
**Description/tags:** why doesn't anyone trust our data, data quality explained, data trust problem, fixing bad data, data quality by design, Monte Carlo data quality survey
**Playlist:** Foundations — Data Quality & Governance

---

### THE HOOK (0:00–0:45)

Here's a number that should worry every manager reading a dashboard right now.

A data quality survey out this year found that seventy-four percent of business stakeholders — not the data team, the people just trying to do their jobs — are now the ones catching data problems first, "all or most of the time." Four years ago that number was forty-seven percent.

Read that again. The people who are supposed to be served by the report are now doing the data team's job for them — spotting the error before anyone else does. And every time that happens, a little more trust in that report walks out the door and doesn't come back.

If you've ever sat in a meeting where someone said "that number doesn't look right" and three different people opened three different spreadsheets to "check" — this video's for you.

By the end, I'll give you a framework I use professionally to stop this happening, and a five-minute exercise that'll show you exactly where your organisation's trust is leaking.

### CREDIBILITY + PROMISE (0:45–2:00)

Aji Saine — twelve-plus years across software development and data management, currently running statutory data reporting for a UK university, and before that managing clinical and health data across research sites in West Africa.

Two videos ago I told you data is an asset. Last video, I showed you what the person managing that asset actually does day to day. Today we're solving the problem that shows up on everybody's desk: the report nobody quite believes.

Here's the promise. By the end of this video you'll understand why trust breaks — and it's almost never where people think — and you'll have a two-part framework for building reports people stop double-checking.

Let's get into it.

### PART 1 — YOU'RE BLAMING THE WRONG THING (2:00–4:15)

When a report looks wrong, here's what happens in almost every organisation I've seen. Someone blames the dashboard. Get a new BI tool. Reformat the chart. Ask IT to "look into it."

None of that touches the actual problem, because the dashboard didn't do anything wrong. It faithfully displayed exactly what was put into it.

The distrust isn't a reporting problem. It's a data quality problem wearing a reporting costume. By the time a bad number reaches a dashboard, it's already travelled through however many systems, hand-offs, and human judgment calls got it there — and the dashboard is just the last stop, the place where the damage finally becomes visible.

Blaming the dashboard for a bad number is like blaming the tap for what's coming out of a polluted river. The tap didn't pollute anything. It's just where you happen to notice.

Think about how often this plays out at your own workplace — weeks spent on a new dashboard tool, new charts, a nicer layout — and a few months later someone's back in the same meeting saying the numbers still don't add up. Of course they don't. Nobody touched the thing that was actually broken. They just gave the same wrong number a nicer font.

So if the real problem is upstream, that's where we need to go looking — and I've got a story that'll show you exactly what "upstream" actually looks like in practice.

### PART 2 — WHERE TRUST ACTUALLY BREAKS (4:15–7:15)

I managed a Health and Demographic Surveillance System across three sites in West Africa — tracking demographic data for a quarter of a million people. At some point, the numbers coming out of the three sites stopped lining up. Not wildly. Just enough that anyone comparing them across sites started quietly not trusting either.

The instinct is to assume someone typed something wrong. It wasn't that. When I went digging — field visits, sitting down with the teams actually collecting the data — I found the three sites had drifted into three different interpretations of the exact same collection protocol. Same form. Same field names. Different understanding of what counted, sitting in three different people's heads. Nobody had done anything wrong by their own definition. That was the problem.

Here's what actually fixed it, because "retrain everyone" is what people say and it's not specific enough to work. We built visual decision trees for the genuinely ambiguous cases — the ones a written procedure alone couldn't cover. We ran site-specific training against those trees. We added real-time validation at the point of entry, so a value that didn't fit got flagged immediately, not three months later in a report. And we gave every site its own live dashboard, so they could see their own numbers the same day, not find out about a problem from head office weeks later.

The result was a ninety-five percent improvement in accuracy across the sites. And something I didn't fully expect — the field staff told us they were happier, because instead of a critical email landing on their desk a month after the fact, they got the correction the same day, while they still remembered the context.

Notice what actually fixed the trust problem. It wasn't a new dashboard. It was going back to where the number was born and fixing the definition and the moment of entry. Everything downstream sorted itself out once that was true.

Which brings us to the actual framework, because "go and fix it at the source" is easy to say and needs a system behind it to actually happen.

### PART 3 — PRINCIPLE ONE: CATCH IT AT THE SOURCE, NOT IN THE REPORT (7:15–10:00)

I call this Quality by Design, and it rests on two principles. The first: upstream prevention beats downstream correction, every single time.

Most organisations do the opposite by default. They let data flow in from wherever, then run a monthly check, a quarterly audit, a "data cleaning" exercise before the big report goes out. That feels responsible. It's actually the most expensive way to do this, because by the time you're cleaning it, the bad data has often already been used — someone made a call based on it, three other reports pulled from it, and now you're not just fixing a number, you're unwinding decisions.

The alternative is boring and it works: validation rules built into the system at the point of entry, so a nonsensical value simply can't get saved in the first place. Automated checks at every point data moves from one system to another, because that hand-off is exactly where meaning gets lost without anyone noticing — remember the "active customer" problem from two videos ago.

When I moved my own team toward this, we cut data processing time by sixty percent, simply by catching errors at entry instead of finding them in a post-hoc check weeks later. And query resolution — the back-and-forth of "what did you actually mean by this value" — dropped from roughly twenty-four hours to minutes, because the automated validation was asking the question at the moment the data was typed in, while the person could still just answer it.

Think of it like a clinical trial database lock. Nobody on a drug trial waits until the day before submission to check whether the data's clean — by then it's far too late to fix anything that matters. You check continuously, from day one, so the lock at the end is a formality, not a scramble.

And this is where the "active customer" definition from two videos ago actually gets solved, not just diagnosed. You don't solve it by writing the definition down once and hoping people remember. You solve it by putting that definition into the validation rule itself, so the system enforces the agreed meaning at the moment someone tries to enter something that doesn't fit it. The definition stops being a document nobody reads and starts being a gate nobody can accidentally walk through wrong.

That's principle one. But prevention only helps if you know where to actually point it — you can't validate everything with the same intensity, or you'll drown your team in checks that don't matter. Which is principle two.

### PART 4 — PRINCIPLE TWO: KNOW WHERE THE RISK ACTUALLY IS (10:00–12:45)

Principle two is systematic risk management — and the word "systematic" is doing a lot of work there, because ad hoc risk-spotting is exactly what got you into this mess.

Start by mapping your actual data flow, end to end, and marking every point where it moves — system to system, team to team, spreadsheet to spreadsheet. Every one of those hand-offs is a place meaning can drift without anyone clocking it, the same way it did across my three field sites.

Then be honest about which fields actually matter. Not every field deserves the same scrutiny. I run intensive validation on the handful of high-impact variables — the ones that, if wrong, change a decision or a funding outcome — and lighter, automated monitoring on the routine ones. Treating every field as equally critical is how teams burn out on checks that don't move the needle, while the one variable that actually mattered slips through unwatched.

Set up automated anomaly alerts, so something outside the expected range gets flagged the moment it appears, not the moment someone happens to notice. And decide, in advance, what happens when an alert fires — who looks at it, how fast, what the escalation looks like — because deciding that under deadline pressure, for the first time, is how bad calls get made.

In my current role, we're working toward statutory deadlines where the numbers we submit affect funding and regulatory standing. The teams that panic in that final week are the ones who left validation until the end. We test the actual submission process — not just the data, the process — well before the deadline, so the only thing happening in that last week is the thing we already know works.

[PLACEHOLDER: a specific example from the UWE Bristol HESA/OfS reporting cycle — a moment where advance testing caught something that would otherwise have surfaced in the final week — if Aji has one she's comfortable sharing on camera.]

None of this needs to sit with one person, either. Cross-train more than one person on the high-risk fields, so the whole submission doesn't rest on whether one specific colleague is at their desk that week. Half the "data crisis" moments I've seen weren't data problems at all — they were the one person who understood a field being off sick, with nobody else able to say what it meant.

Catch it at the source. Know where the risk actually sits. That's Quality by Design — and it's the difference between a report people believe and one they quietly double-check in their own spreadsheet.

### THE LANDING + HOMEWORK (12:45–15:00)

Let's land this. Nobody distrusts your report because of the chart type or the colour scheme. They distrust it because, somewhere upstream, a number was allowed to be wrong before anyone checked. Fix that, and the dashboard looks after itself.

Quality by Design is two moves. Catch errors at the point of entry, not in the review meeting. And know which fields actually carry the risk, so your validation effort goes where it matters instead of everywhere at once.

Here's your exercise. Pick one report at work that people don't quite believe — you know the one. Trace a single number in it back to where it was first entered. Ask yourself honestly: was this checked when it went in, or only after someone complained about it? That one answer will tell you more about your organisation's data quality than the report itself ever will.

And here's something worth sitting with — a separate data-integrity study out this year found that organisations with a real data governance programme report far higher trust in their own data than those without one. Prevention and risk management get you a long way. But governance is what makes sure somebody's actually responsible for keeping it that way. That's next video — data governance, explained without the jargon, for anyone who's never had to think about it before.

If this changed how you'll look at the next dodgy number in a meeting, subscribe — there's a lot more of this coming.

I'll see you in the next one.
