# The Map — how the channel's videos connect

**Status: CONFIRMED by Aji, 2026-08-04.** The spine is the data journey. Everything else in the channel's structure follows from it, so treat a change to the spine as a constitution-level decision, not an adjustment.

---

## Why this exists

The channel has done the hard half already. Twenty-eight videos, each a graspable piece of a field too big to swallow whole, each written to a consistent template so the viewer learns the shape once. **That is decomposition, and it works.**

What is missing is the other half. **Nothing shows a viewer how the pieces relate.** A next-video tease is a thread, not a map. Playlists group by category, which is a list with labels on it.

**Decomposition alone produces a list. Interconnection is what turns the list back into a model.** A taxonomy tells you what exists; a model tells you how it behaves, and a model is what people remember and come back to.

## The spine: follow the data

Not a category tree, because a category tree is a list with boxes. **A journey**, because a journey has sequence and dependency built in, which is what makes it a model.

Data moves through six stages, and everything the channel teaches acts somewhere on that journey:

1. **Created.** Someone records a fact and makes choices doing it: what to capture, how to define it, what to leave out. Meaning is baked in here, and so are most later problems.
2. **Defined.** What the field actually means, who owns it, what good looks like, written down where others can find it.
3. **Stored and moved.** Where it lives and how it travels between systems, which is where copies drift apart.
4. **Trusted, or not.** Whether anyone believes it. Quality, reconciliation, and the cost of the gap.
5. **Used.** Analysis, reporting, and the decisions that follow.
6. **Kept or destroyed.** Retention, compliance, and the end of the lifecycle, which almost nobody covers.

**Governance is not a stage.** It runs the length of the journey, deciding the rules at every point. **Tooling (SQL and Python) is not a stage either**; it is how the work gets done throughout. **Careers content is about the people who do it.**

That gives the shape: a line with two bands running along it, and the people underneath.

## Where the videos sit

Illustrative, not exhaustive. The point is that every video can be located in one line.

*Numbering updated 2026-09-07 to match `backlog.md` after that week's renumbering (video 4 became the spine; everything at old #4–#16 shifted to #5–#17; #18 and beyond are unchanged).*

| Stage | Videos that live here |
|---|---|
| Created | Quality at source, validation, upstream prevention |
| Defined | Metadata (13), master data (11), who owns the data (16) |
| Stored and moved | Warehouses, lakes and lakehouses (18), Excel is not a database (14), what is a data contract (30, proposed) |
| Trusted, or not | Why nobody trusts your reports (5), the 60-second quality check (12), 5 signs (7), data quality projects (21) |
| Used | Dashboards (15), reading a dataset (28), your AI is only as good as your data (23) |
| Kept or destroyed | GDPR (17), the data mistake that cost millions (2), the EU AI Act (24) |
| Running the length | Data governance explained (6), governance as code (25), agentic AI governance (31, proposed) |
| The tools | SQL (10), Python (27) |
| The people | Career change (8), which path pays (9), certifications (19), jobs disappearing (26), what a data manager does (3), SQL interviews (32, proposed) |
| The whole journey | What Is Data Management (1), how data flows keyboard to boardroom (4), the complete map (22) |

## What this changes, concretely

**The data-flow video becomes the spine, not an ordinary explainer.** "How data flows through a company: from keyboard to boardroom" *is* this map. It sat at position 17 as though it were one topic among many for over a month after this was written — **moved to position 4 by Linda on 2026-09-07**, immediately after the three videos already locked into the current publish order, so it now sits early enough that every other video can point back at it as the map intended.

**Video 22 becomes buildable.** The capstone is currently waiting on "once the library exists", which is a condition that keeps receding. **The map does not need the library to exist.** Build the map now; the capstone becomes a presentation of it later.

**A locating convention for scripts.** Each video earns its place on the map in **one sentence**, near the top or in the landing, not a whole beat: *"This is the moment data gets created, and almost everything downstream depends on getting it right here."* One line, no runtime cost, and the viewer starts assembling the whole picture across videos instead of collecting unconnected explainers.

**Playlists follow the journey**, not the pillars, so the channel page shows the shape rather than a filing system.

## Why this spine, and what was rejected

*Recorded so the reasoning survives, and so a future change is made knowingly rather than by drift.* The alternatives considered and rejected:

- **A hub and spokes**, governance at the centre. Truer to how the profession describes itself, but it is DAMA's wheel with different labels, and the channel is deliberately not a DMBOK series.
- **By question the viewer is asking** ("I can't trust my numbers", "I want a data job"). Better for search intent, worse as a model, because it has no sequence or dependency.
- **The four subject areas as they stand.** Honest, but it is a categorisation, and a categorisation is the list this exercise exists to escape.

The journey was chosen because it shows **dependency**, which is the channel's actual argument: what happens at creation determines everything downstream. That is the same claim as Quality by Design, so the map and the philosophy say the same thing, which is what makes a map memorable rather than decorative.
