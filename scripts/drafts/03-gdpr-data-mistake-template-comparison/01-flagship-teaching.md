# The Data Mistake That Gets Companies Fined Millions (GDPR Explained by a Data Manager)

**Template:** 1 — Flagship / deep-dive teaching (CLAUDE.md → Script templates #1)
**Status:** Comparison draft — one of six, same topic, different template
**Target runtime:** ~15 minutes (~2,150 words)
**Pillar:** Foundations (ethics & GDPR)

---

### THE HOOK (0:00–0:45)

Picture the headline: "Company fined millions under GDPR." What do you picture caused it? A hacker. A leaked database. Some dramatic breach on the evening news.

Here's the uncomfortable truth: most of the biggest data protection fines have nothing to do with hackers at all. They're handed out for something far more boring, and far more common — a mistake sitting quietly inside almost every organisation I've ever worked in. Including, probably, yours.

By the end of this video, you'll know exactly what that mistake is, why it's so easy to make without anyone noticing, and the one question you can ask this week that tells you whether your own organisation is sitting on it right now.

### CREDIBILITY + PROMISE (0:45–2:00)

I'm Aji Saine — twelve-plus years in data management and software development, including running statutory data reporting for a UK university, where getting this exact thing wrong isn't hypothetical. It's a live regulatory risk I manage. I've also sat on the other side of it, building the policies that stop this mistake before it happens.

GDPR gets treated like a legal problem — something for the compliance team, or an external lawyer, to worry about once a year. It isn't. It's a data management problem wearing a legal disguise, and by the end of this video you'll see exactly where the two meet.

Let's get into it.

### PART 1 — THE MYTH: IT'S ABOUT HACKERS (2:00–4:00)

Start with the myth, because it's worth killing first. When people imagine a data protection fine, they imagine a breach — someone breaking in, stealing records, an organisation reacting too late to a headline already written.

Breaches do get fined, and they're the ones that make the news, because "hacked" is a simple story with a villain. But look past the headlines at how regulators actually describe their largest penalties, and a huge share of them involve no hacker at all. The organisation simply couldn't answer basic questions about its own data: what it was holding, why it was holding it, and for how long.

That's not a security failure. Security is about keeping the wrong people out. This is a governance failure — about never deciding, in the first place, what should be in there at all — and it's a completely different problem to solve. You can buy your way out of a security gap with better software. You cannot buy your way out of nobody having decided what your data is for.

Think about a mid-sized retailer, the kind with a loyalty scheme and a decade of order history. No breach, ever. Firewalls fine, encryption fine, IT genuinely doing its job well. And still, on paper, that retailer can be sitting on exactly the profile a regulator is trained to investigate — because "secure" and "accountable" are two completely different questions, and most organisations only ever prepare an answer for the first one.

So what does that governance failure actually look like inside a real organisation? Let me show you.

### PART 2 — THE REAL MISTAKE: PURPOSE AND RETENTION DRIFT (4:00–7:00)

GDPR rests on a handful of plain principles. Two of the most routinely broken: you should only collect personal data for a specific, stated purpose, and you shouldn't keep it any longer than that purpose requires.

In practice, almost nobody enforces the second one. Data gets collected for a good reason — a job application, a customer enquiry, a one-off event registration — and then it just stays. Nobody's job is to delete it. Deleting things feels risky. Keeping them feels safe, or at least feels like nobody's problem today. So years later, an organisation is sitting on personal data for a purpose that expired long ago, with no one left who can explain why it's still there, in a system three people down the line inherited without documentation.

I saw a version of this myself, early in my time at a UK university. My own team was fielding requests for full extracts of student and staff data — "just in case it's useful" — with no stated purpose and no expiry in mind. That's not malicious. Nobody sat down and decided to hoard personal data. Nobody decided anything at all, and that's exactly the problem: a decision that never gets made defaults to "keep everything, forever," and that default is precisely what a regulator is trained to look for.

Multiply that one habit across every department, every system, every well-meaning "let's keep this just in case," and you get an organisation that genuinely cannot say, with confidence, what personal data it holds. Not because anyone hid anything. Because nobody was ever assigned the job of finding out.

Here's what that looks like scaled up. Imagine a company that ran a competition five years ago — a simple email sign-up, a prize draw, a one-line purpose: "to notify the winner." The winner was notified. The purpose was fulfilled that same week. But the marketing team liked the size of the list, so it never got deleted — it got quietly folded into the general newsletter database instead, without anyone re-asking whether those thousands of people had actually agreed to that. Nobody made a decision to break the rules. Somebody just never made the decision to stop, and five years of silence is exactly what turns a one-line purpose into a liability with thousands of names attached to it.

Which raises the real question underneath all of this: whose job is it to decide?

### PART 3 — NOBODY OWNS THE DECISION (7:00–10:00)

This is the part that actually causes the fines. Not the data existing — the fact that no single person or team is responsible for deciding what should and shouldn't be kept.

Ask around your own organisation: who decides how long customer records are retained after the relationship ends? Who decides which systems personal data is allowed to sit in, and which copies of it are the "real" one? Most of the time, the honest answer is nobody. It isn't written down anywhere. It's whatever the system's default happened to be when someone ticked a box during setup five years ago, because nobody was in the room to configure it on purpose.

And that ownership gap is exactly what an investigation finds. Regulators rarely uncover one dramatic villain. They uncover a hundred small, unowned decisions — a spreadsheet nobody remembers exporting, a "temporary" extract that's been live for four years, a marketing list built from a customer service system that was never meant to leave it — that quietly added up to personal data sitting somewhere it should never have been, for reasons nobody can now reconstruct.

I think about this the same way I think about metadata generally: it's your torch in the warehouse. Without it, you're not being careless on purpose — you simply cannot see what's stacked in the dark corners of your own organisation. GDPR compliance, underneath the legal language, is mostly just turning that torch on and pointing it at every shelf.

Picture what an actual investigation looks like from the inside. A regulator doesn't usually start by asking "were you hacked." They start by asking an organisation to produce, in writing, exactly what personal data it holds on a specific individual, where it came from, and how long it's been kept — a request called a subject access request, and any member of the public can trigger one at any time, no regulator required. Plenty of organisations can answer that in days. Plenty of others discover, in that exact moment, that the honest answer requires checking eleven different systems built by eleven different teams over eleven different years, none of which agree with each other. That gap — the days or weeks it takes to even attempt an answer — is usually the first sign of trouble, and it shows up years before any fine does.

So if nobody owns it by default, what does actually owning it look like?

### PART 4 — WHAT OWNERSHIP ACTUALLY LOOKS LIKE (10:00–12:30)

It's not complicated, and it's not really a legal exercise — it's a data management one. Three things, done properly, by someone whose job it actually is: know what personal data you hold and where it lives. Have a stated, specific reason for holding each category of it. And have an actual, enforced point at which it gets deleted or anonymised, not just a policy document that says it should.

That's it. Everything a regulator asks a data controller to demonstrate collapses into those three things, done consistently, with a named person accountable for each one. The organisations that get fined aren't usually the ones with no privacy policy on their website — most have a perfectly good one. They're the ones where the policy says one thing and the actual systems, quietly, do something completely different, because nobody's job was to keep the two in sync once the policy was signed off.

This is also, not coincidentally, exactly the discipline I described a data access request policy solving in a different video — someone has to be able to say what a piece of data is for, on demand, or the honest answer is that nobody really knows.

None of this needs to be dramatic to work. It doesn't require a new system, or a six-figure compliance platform. The retailer from earlier could fix most of its exposure with a single afternoon: one person going through each major system, writing down what's in it, why, and when it should go — then actually scheduling the deletion instead of noting it as a good idea for later. The technology to enforce a retention date has existed for decades. What's usually missing is the decision, made once, by someone with the authority to make it stick.

### THE LANDING + HOMEWORK (12:30–15:00)

So here's the mistake, in one sentence: treating personal data as something to collect and keep by default, instead of something you have to justify holding at every point in its life. It's not usually a hacker that gets an organisation fined millions. It's the absence of anyone whose job it was to ask "why do we still have this, and who decided we should?"

Here's your exercise. Pick one system in your organisation — your CRM, your HR system, whatever you can actually see into. Find one field of personal data, and ask two questions: what's the stated purpose for holding this, and when does it get deleted? If you can't answer both halves of that question in under a minute, you've just found exactly the kind of gap that gets organisations fined.

Now — I've talked today about the organisation-wide version of this problem. Next time, I want to take you inside a single day and show you what it looks like when a data manager actually has to decide, live, in a room, what a piece of data means before a regulator ever gets anywhere near it. Watch that one next.

If this changed how you think about GDPR, subscribe — there's a lot more of this coming, one decision at a time.

I'll see you in the next one.
