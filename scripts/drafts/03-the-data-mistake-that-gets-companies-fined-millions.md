# The Data Mistake That Gets Companies Fined Millions (GDPR Explained by a Data Manager)

**Template:** 6 — Myth vs. mechanism / contrarian reveal (CLAUDE.md → Script templates #6)
**Status:** Drafted — final pick from the 6-template comparison (`scripts/drafts/03-gdpr-data-mistake-template-comparison/`), rewritten to fix all review findings (intensifier overuse cut, duplicate sentence with draft 01 rewritten, reveal fattened, precedent split into two weighted sections, self-announcing line cut). Needs `/review-script` before filming.
**Actual runtime:** ~13.2 minutes (~1,850 words) — slightly under the 15 min target; timestamps below reflect this
**Target runtime:** ~15 minutes (~2,150 words)
**Thumbnail text:** "NOT A HACK" or "THE REAL REASON" (with Aji, direct to camera)
**Description/tags:** GDPR explained, data protection fines, GDPR mistakes, data governance, GDPR compliance, data manager explains
**Playlist:** Foundations & Governance
**Pillar:** Foundations (ethics & GDPR)

---

### THE HOOK — THE TURNING POINT (0:00–0:45)

On the 25th of May 2018, a new law took effect across Europe that most organisations, seven years on, still fundamentally misunderstand.

GDPR's arrival came with countdown emails, campaigns, entire law firms built almost overnight around it. Every company with a European customer spent that spring rewriting a privacy policy nobody would ever read, hoping that alone would be enough. And in the years since, regulators have handed out some of the largest data protection fines in corporate history — numbers with enough zeros to make the news on their own, sitting right next to the details of exactly what each company got wrong.

Here's what almost nobody takes away from those headlines correctly.

### THE REVEAL (0:45–2:00)

Everyone assumes the biggest fines happen because a company got hacked. Look at how the story gets told, every single time: an attacker, a stolen database, a scramble to notify customers before the news does. It's a clean story. It has a villain, and villains are easy to write headlines about.

I don't believe that's the real story behind most of the largest penalties. Breaches happen, and they do get punished — that part is true. But look past the headline, at what the regulator's own investigation usually describes, and a striking share of the biggest fines involve no attacker at all. The organisation simply couldn't answer a basic question about its own data: what do we hold, why do we hold it, and when were we supposed to stop holding it?

Think about what that actually means for a moment. A regulator doesn't need to find a criminal to hand out a fine. They just need to ask an organisation to produce, in writing, exactly what personal data it holds on one named individual, where it came from, and how long it's been kept. Any member of the public can trigger that request today, right now, with no regulator involved at all — it's called a subject access request, and it's one of the most ordinary legal rights GDPR created. Plenty of organisations can answer it within days. Plenty of others discover, in that exact moment, that the honest answer requires checking a dozen different systems built by a dozen different teams over a dozen different years, none of which fully agree with each other. That gap — the days or weeks it takes just to attempt an answer — is usually the first sign of trouble, and it shows up years before any headline does.

That's not a break-in. Nobody forced their way past anything. The information was sitting right where the organisation put it — the organisation just never decided, clearly, whether it should still be there. Call it what it is: not a security failure. A governance failure. And governance failures don't announce themselves. Nothing breaks. No alarm fires. It just sits there, patiently, until the day someone with real authority finally asks the one question the organisation was never prepared to answer.

### THE PRECEDENT (2:00–7:15)

I've watched this pattern up close more than once, in two very different jobs.

Not long after I started in UK higher education, I noticed my own team fielding requests for "all of it" — full extracts of student and staff data, no scope, no stated purpose, handed over because saying yes was faster than asking why. Nobody involved was reckless. Nobody was trying to break a law. It was simply the default, because no one had ever been assigned the job of asking the question out loud.

So I stopped it. We introduced a data access request policy: state what you need, state why, we run a needs assessment against that, and you get exactly that — not the whole database, because asking for everything used to be quicker than asking properly. One of the very first requests to hit that new policy was for a full extract of former students' contact details, "just in case it's useful." Under the old habit, that goes out the same afternoon. Under the new one, it doesn't go out at all, because nobody in the room could give a reason for it beyond "it might be useful someday" — which is precisely the sentence that turns into a fine, years later, once enough of them pile up unnoticed.

That single habit — extending trust by default instead of by justification — is the mechanism regulators are built to find. It's a small policy. Nobody outside the data team ever sees it get enforced, and it doesn't feel like it's protecting against anything dramatic. But policies like that are the only thing standing between "we assumed it was fine to keep this" and "we can prove, in writing, exactly why we kept it" — and a regulator only ever asks for the second one.

I'd seen a sharper version of the same habit years earlier, in a completely different world, where the stakes left no room to miss it.

I managed clinical data across research sites in West Africa, where vaccination dates were recorded three different ways across three sites, because nobody had ever agreed what the date was supposed to mean. Different domain, wildly different stakes, same root cause underneath: nobody had been made to answer, clearly and continuously, what a piece of personal data was for. We only caught it because the consequences were immediate and visible — a region's vaccine coverage numbers simply didn't add up. Most organisations don't get that early warning. Their version of the same mistake just sits quietly in a spreadsheet for years, until somebody outside the organisation finally asks the question nobody inside ever did.

Neither of those moments involved a hacker. Both were precisely the kind of gap that, left alone in an organisation with millions of records instead of a few thousand, is what regulators are punishing when the fine finally lands.

What connects them isn't the sector, or the country, or even the scale — it's that in both cases, the fix wasn't a piece of software. It was a person willing to stop a request in progress and ask an uncomfortable question out loud, in a room, when saying nothing and letting it through would have been so much easier. Regulators can't inspect an organisation's intentions. They can only inspect what happened to the data — and what happened almost always traces back to whether that person existed, or whether the request just sailed through because nobody was in the room to stop it.

### THE MECHANISM, COMPRESSED (7:15–9:15)

Here's the whole thing in one line you could repeat to a colleague: if the same person's data exists in five systems and nobody's sure which one's correct, that's not five records. That's one person you can no longer honestly answer "what do we hold on you" about.

Every fine, underneath the legal language, comes back to that same broken sentence, repeated thousands of times across an organisation's systems. Purpose nobody re-checks. Retention nobody enforces. Access nobody scopes. None of it looks dramatic from the inside. It looks like Tuesday. That's why it survives so long before anyone notices — there's no alarm, no error message, just a slow accumulation of unanswered questions until the day someone with real authority finally asks one.

Picture an ordinary mid-sized company running a customer loyalty scheme. A person signs up once, gets a discount code, and never interacts with the brand again. Nobody decides to keep their data forever — nobody decides anything. The record just survives every system migration, every re-platforming, every "let's not touch that table, we don't know what depends on it," because deleting it was never anyone's job and leaving it alone was always the easier call. Ten years later, that one company might be holding accurate, current, easily explainable data on its active customers, and a decade of silent, unexplainable clutter on everyone else. From the outside, both look identical: rows in a database. A regulator's investigation is really just the process of discovering which rows are which.

You can test this on your own organisation in under a minute, and you don't need my job title to do it. Ask anyone — genuinely anyone — "if I asked you what personal data of mine you're holding right now, and why, could you tell me?" Watch the pause before the answer. That pause is the mechanism. It's the same pause, at a much bigger scale, sitting inside every regulator's investigation report.

### LANDING (9:15–11:30)

This isn't going away, and it isn't going to get softer. Regulators have spent the years since 2018 getting better at this kind of investigation — not looking for a break-in, looking for the paper trail of decisions an organisation never made. The organisations that get caught out next won't be the reckless ones. They'll be the ordinary ones who assumed "we haven't been hacked" meant "we're fine."

This has very little to do with the law, and everything to do with a discipline most organisations never built in the first place. GDPR didn't invent the obligation to know what you're holding and why. It just put a fine on the organisations that never bothered to find out — and gave the rest of us a clean, plain-language reason to finally build the discipline we should have had regardless.

None of this requires a bigger legal team, or expensive new software. The loyalty-scheme company from a moment ago could close most of its exposure in a single afternoon: one person going through each major system, writing down what's in it, why, and when it should go, then actually scheduling the deletion instead of noting it as a good idea for later. The technology to enforce a retention date has existed for decades. What's usually missing is a decision, made once, by someone with the standing to make it stick — which is a data management problem wearing a legal costume, not the other way round.

Here's what to do with that. This week, pick one piece of personal data your own team holds, and answer three questions about it, honestly: what is it, why do we have it, and when does it stop being ours to hold? If any one of those makes you pause, you've found the exact gap regulators are trained to look for — and you found it before they did.

Do it with real honesty, not the kind that protects your own team's reputation, and you'll likely find at least one answer you don't like. That's not a failure on your part — most organisations would fail the same test, which is precisely why the fines keep happening. It's the first accurate map anyone's drawn of that particular gap, and an accurate map, however uncomfortable, is worth more than the comfortable assumption it replaces. You can't fix what you've never been willing to look at honestly, and most organisations have simply never looked.

Next time, I'll show you what this looks like from the inside — the specific, unglamorous judgment calls a data manager makes to stop this exact gap from opening in the first place. Watch that one next.

### SIGN-OFF (11:30–11:45)

I'll see you in the next one.
