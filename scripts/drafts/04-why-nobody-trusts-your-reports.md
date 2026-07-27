# Video 4 — Why Nobody Trusts Your Reports (And How to Fix It)

**Status:** Drafted — self-reviewed (ten rules + AI-voice test), awaiting Aji's review
**Placeholders needing Aji:** 2 — see Part 3 and Part 4 (a real report-challenged-then-retrusted moment; a real logged-correction moment). Both optional but strongly recommended over leaving the general framework unillustrated.
**Template:** Flagship / deep-dive teaching (pillar 1–3 cornerstone; the video needs to unlearn a misconception — "it's a quality problem" — before the fix lands)
**Target runtime:** ~15 minutes (~2,150 words at 140wpm)
**Thumbnail text:** "NOBODY TRUSTS THIS NUMBER" or "IT'S NOT A QUALITY PROBLEM"
**Description/tags:** why don't people trust data, data quality vs data trust, data governance, trusted reporting, data management
**Playlist:** DMBOK Explained

---

### THE HOOK (0:00–0:45)

You spend three hours building a report. You check the formulas twice. You send it.

And the first thing anyone says in the meeting is: "Are we sure this number's right?"

Not "great work." Not even "interesting." Just — are we sure. Every time.

Here's the bit that should bother you: that question usually isn't about whether the report is accurate. Most of the time, it is accurate. It's about something else entirely, and chasing accuracy harder won't fix it.

By the end of this video you'll know exactly what that "something else" is, and I'll give you three questions that fix it — the same three I use before any number leaves my desk.

### CREDIBILITY + PROMISE (0:45–2:00)

Quick reintroduction — Aji Saine, twelve-plus years across software development and data management.

I currently work in statutory data reporting for a UK university. The numbers my team submits decide funding and regulatory standing — which means every one of them gets questioned, by someone, before it's allowed to matter. So I've spent a lot of time thinking about what actually makes a number survive that questioning.

By the end of this video, you'll be able to tell the difference between a data quality problem and a data trust problem in your own organisation — and you'll have a way to close the second one that has nothing to do with cleaning more data.

Let's get into it.

### PART 1 — THE QUALITY TRAP (2:00–4:15)

Here's the thing to unlearn first. When a report gets challenged, the instinct is always the same: check the data. Re-run the query. Audit the source table. Find the error.

Sometimes there is one. Most of the time, there isn't — and the report gets questioned again next month anyway.

That's because accuracy and trust aren't the same axis. Accuracy is a property of the data. Trust is a property of the relationship between the person reading the number and everything they can't see behind it — where it came from, what it means, who'd catch it if it were wrong. You can be completely accurate and still be completely disbelieved, because disbelief isn't checking your maths. It's checking your maths against a mental list of everything that's gone wrong before that nobody explained properly at the time.

This is exactly why "data quality" has quietly become the wrong word for what most organisations are actually missing. The industry's own research is starting to say the same thing out loud: most organisations don't have a data quality problem. They have a data trust problem. The number can be right and still be worthless, because worthless is what happens the moment somebody decides not to act on it.

Think about what actually happens after a report gets challenged once. Nobody writes "this was fine" in an email and moves on. What happens is quieter and much more expensive: the next report, and the one after that, gets a private cross-check before anyone acts on it. A second spreadsheet, built by someone who doesn't quite believe the first one. That's not a data quality cost. Nothing in the data caused it. It's a trust cost, and it compounds — every unexplained "are we sure" adds one more person, one more silent re-check, one more version of the truth living somewhere in someone's own workbook.

So if trust isn't about the data being clean — what is it about? That's what took me the longest to actually see, because the evidence was sitting in my own team, and I walked past it for months.

### PART 2 — THE DICTIONARY NOBODY OPENED (4:15–7:00)

My team had a data dictionary. A proper one — field names, definitions, who owned each one. It existed. It was accurate. Nobody had touched it in a long time, because nobody knew to.

I only found out when I asked someone directly what a field meant, expecting them to point me to it, and they didn't know it existed. Neither did most of the team. It had been built once, filed somewhere sensible, and quietly forgotten — while people kept asking each other in Slack messages and corridor conversations what a field actually meant, getting slightly different answers depending on who they asked.

I've said before that metadata is your torch in the warehouse. Well — my team had the torch. It was just sitting in a drawer, switched off, while everyone stumbled around the same shelves in the dark, each convinced they knew where things were. The light existing isn't the same as the light being on.

Nothing about that data dictionary was wrong. The quality was fine. But if you'd asked anyone on my team that week whether they trusted the reports built on top of those definitions, you'd have got a shrug, not a yes — because trust doesn't come from the definition existing. It comes from people knowing where to find it, and knowing it's the same answer everyone else got.

That's the gap. Quality lives in the data. Trust lives in whether the people reading the output can see, immediately, where it came from and what it means — without having to ask around and hope two colleagues give the same answer.

Which raises the obvious next question: if trust isn't built by cleaning data harder, what actually builds it?

### PART 3 — THE THREE S'S (7:00–10:30)

I use three questions before any number leaves my desk. Source. Sense. Stake.

Source — where did this number actually come from, and can you show that in one sentence? Not "the system." Which table, which extract, run on which date. If you can't answer that in a sentence, neither can the person reading your report, and they'll fill the gap with suspicion instead.

Sense — does the definition match what the reader thinks it means? This is the trap my team fell into. A field can be perfectly documented and still be misread, if the documentation lives somewhere nobody looks. "Sense" means the definition travels with the number — a footnote, a hover-tooltip, a line in the email — not buried in a document from eighteen months ago.

Stake — who's accountable if this number turns out to be wrong, and do they know it's them? This is the one people skip, because it's uncomfortable. But think about the reports you personally trust most at work. I'd bet every one of them has a name attached — someone you could go to and ask "is this right," and who'd treat that as their job to answer, not a personal attack. A number with no owner is a number nobody defends, and a number nobody defends is a number nobody quite believes.

Here's where the HDSS dashboard work made this real for me. Every proposed change to those dashboards — a new metric, a reworded label, a different breakdown — went through an assessment before it touched a single number people relied on. That held even when the request came from management. Not because I didn't trust my colleagues — because the dashboard's credibility depended on there being one person whose job was to ask "does this still mean what it said it meant yesterday." That's Stake, in practice. Somebody has to be the one the number answers to.

Source tells the reader where it came from. Sense tells them what it means. Stake tells them who stands behind it if they push back. Miss any one of the three, and you get exactly the meeting I described at the start — an accurate report, and a room full of people still asking "are we sure?"

It's close to why statutory reporting works the way it does where I sit — funding decisions get made on these numbers, so nobody outside my team is willing to just take my word for one.

[PLACEHOLDER: Aji — a specific instance from your own work (statutory reporting or elsewhere) of a report being challenged, then re-trusted once you could point to source, definition, and owner in one sentence. A real example lands harder here than the framework alone — happy to slot in whichever moment you're comfortable naming on camera.]

So now you've got the three questions. The real test is whether you can answer them before anyone asks — not scramble to answer them after. And notice what they have in common: none of them require touching a single row of the underlying data. You can run all three on a report that's already sitting in someone's inbox right now.

### PART 4 — WHY HIDING THE MISTAKE MAKES IT WORSE (10:30–12:30)

One more thing that surprises people: showing your corrections builds trust faster than never having any.

The instinct, when a number turns out to be wrong, is to fix it quietly and move on — nobody wants to be the person who got it wrong. But a report that's never once been visibly corrected isn't proof it's always been right. It's usually proof nobody's checking closely enough to catch it. The reports people trust most over time are the ones where you can point to a time it was wrong, say exactly what happened, and show it got fixed in the open. That's not a weakness in the report. That's Stake, working as intended — someone was accountable, and it showed.

[PLACEHOLDER: Aji — a real instance from statutory reporting (or elsewhere) where a logged, explained correction actually rebuilt trust rather than damaging it, if you have one you're comfortable sharing.] A visible correction trail is the single fastest way I know to prove a report has a real owner behind it, rather than a name attached to it after the fact.

I'd take a report with one visible, well-explained correction over a report that's "never been wrong" any day of the week. One of those has evidence behind it. The other is just unexamined.

### PART 5 — MAKING IT STICK BEYOND ONE REPORT (12:30–13:45)

None of this works if it lives in your head alone. The dictionary my team had already proved that — a good definition, known to one person, might as well not exist.

So the three S's have to attach to the report itself, not to a conversation you had once in a meeting. A line at the bottom of the page, not a policy document nobody opens. If someone forwards your report to a colleague who's never spoken to you, source, sense, and stake should travel with it anyway — because the reader who trusts your number today won't be the only one reading it in six months.

That's the actual test of whether you've fixed a trust problem or just reassured one person in one meeting: can the report defend itself with you out of the room?

### THE LANDING + HOMEWORK (13:45–15:00)

So here's the whole argument, in one breath. Accuracy and trust are different things — you can have one without the other, and cleaning the data harder only fixes the one that usually wasn't broken. Trust gets built through three questions, attached to the report itself: Source, Sense, and Stake. Where did it come from. What does it actually mean. Who's accountable if it's wrong. Skip any one of them, and the report survives the audit but fails the meeting.

Here's your exercise. Take the next report you send — just one. Add a single line at the bottom: source, definition, owner, one sentence each. Watch what happens to the questions you get back. I'd put money on there being fewer of them.

Now — a few videos back I promised you the data mistake that's cost companies hundreds of millions in fines, the kind nobody realises they're making until it's too late. That one's still coming, and it's next.

If this changed how you think about your own reports, subscribe — there's a lot more of this coming, one decision at a time.

I'll see you in the next one.
