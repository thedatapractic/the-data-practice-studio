# Video brief — What a Data Manager Actually Does All Day

*Prepared by Linda, 2026-08-02. Backlog #1. Rebuilt from the existing reviewed draft to run through the new pipeline.*

## Confirmed: this is not a duplicate of Video 2

Checked against `videos/what-is-data-management/final.md`. They are genuinely different videos:

- **Video 2** is about the **discipline**: what data management is, why it is needed, how it is done. Definitional, search-intent.
- **Video 1** is about the **role**: what the person doing the work actually spends their days deciding. Identity, career-thread.

They are complementary, and Video 1 is written to publish **after** Video 2 (it opens with "last week I told you data is an asset"), despite the numbering.

## But three beats collide, and that needs fixing

Video 2 is final and publishes first, so Video 1 is the one that moves.

| Shared beat | In Video 2 | In Video 1 (current draft) | Recommendation |
|---|---|---|---|
| The word "active" being disputed | "ask five people what counts as an active customer and you will get five answers" | The hook: "a fight about what the word 'active' means" | **Change the Video 1 hook.** Two consecutive videos opening on the same disputed word reads as a thin bank of examples. |
| Vaccination dates | The core story of Part 1 | Retold in Part 2 | **Keep, but only as an explicit callback plus new material.** The draft already does this well: it references the problem in one line, then tells what was actually *done* about it (data dictionary, SOPs, the reconciliation meeting where every site believed it was right). That resolution is new and worth having. |
| "Treat every record as if it belonged to your own mother" | Part 2, the ethical beat | Part 4, the same line | **Aji's call.** It is a signature line and repeating it is defensible as a catchphrase, but back to back in consecutive videos it loses force. Suggest holding it for Video 1 and letting Video 2 own it this time, or vice versa. |
| "Enrolled" as a definition example | "at what point is a student properly enrolled" | — | Avoid reusing in Video 1. |

## Recommended hook change

Promote the **"client" field story** from Part 2 into the hook. It is the strongest unique moment in the script and nothing else in the channel uses it: a system she built as a developer where some people typed the organisation into the client field and others typed a person, no bug anywhere, clean code, validation passing, and the software could not tell the difference.

It works as a career-thread opener because it is a small, sharp, real moment that reveals the texture of the work, it belongs to the earliest chapter of her career so it sets up the multi-chapter structure, and it makes the misconception concrete immediately: this is not a technical problem, and no amount of good engineering fixes it.

## Purpose (one sentence)

Show that a data manager's real work is deciding what data means, translating between systems and people, and seeing change coming, so the viewer can recognise that work in their own organisation even when nobody calls it data management.

## Pillar, audience, template

- **Pillar 5** (real-world practice), identity and trust-building.
- **Audience:** primarily career-builders deciding whether this is their path, secondarily working professionals already doing this under another title.
- **Template: career-thread / multi-chapter reflection** (`templates/career-thread.md`). This is the template Video 1 defined, so it should be the model for it. Note its specific instruction: open on a small sharp real moment, **not** a rhetorical "let me ask you a question", and use chronological narrative markers ("back in my developer years... years later... and it's still happening now") rather than ordinal labels.

## The runtime problem

The reviewed draft is **1,979 words, about 14 minutes.** The rule is now 7–8 minutes with a 10 minute maximum, so roughly **45% has to come out.** That is too much to trim; whole beats have to go.

My recommendation on what to cut, in order:
1. **Part 4 in its entirety** (why the judgment calls are personal, ~330 words). It is good writing, but it is the beat that overlaps most with Video 2's ethical section, and its argument is really a separate video about why this work matters morally.
2. **One of the three "decide" examples.** The draft carries three (client field, vaccination dates, data access policy). Two is enough to establish "same pattern across chapters"; three is the same point made a third time.
3. **The credibility section**, which currently runs long for a video this length.

Keep at all costs: the **decide / translate / foresee** framework, because it is the nameable thing the viewer takes away, and the SQL upskilling story, because it is the only one happening in the present tense.

## Must-include points for Torch

- Chronological markers across career chapters, never ordinal labels.
- The framework named plainly and assembled piece by piece, not handed over at the start.
- The SQL upskilling story stated correctly: **she trained an Access-only team ahead of the university's own migration, which is still not live after two years. It is not a migration she delivered.** See `memory/torch.md`.
- Identity videos frame around **the role and the work**, not the employer. The university is a supporting example, never the organising frame.
- Domain language per `domain-knowledge.md`, and Aji's voice per `voice-profile.md`.
