---
description: Run the standard script review workflow (ten rules + AI-voice test) against a draft
---

Review a script using The Data Practice's own review workflow (see `CLAUDE.md` → "Voice and the AI-voice test" and "The ten scripting rules").

Script file: $ARGUMENTS

Steps:

1. Read the target script file.
2. **Rule-by-rule diagnosis** — go through all ten scripting rules from `CLAUDE.md` one at a time. For each, state pass/fail/partial and quote the specific line(s) that justify the verdict. Do not skip rules that obviously pass — a one-line confirmation is enough.
3. **AI-voice test** — scan for machine-voice symptoms: overly balanced sentences, words like "delve/crucial/furthermore", lists of three everywhere, relentless smoothness, generic enthusiasm. Quote every offending passage.
4. **Intensifier-density scan** — count occurrences of crutch words used to manufacture emphasis instead of earning it ("actually," "exactly," "quietly," "genuinely," "honestly" and similar). Flag any single word appearing more than ~3 times per 1,000 words, and quote the worst cluster.
5. **Raw-material check** (see CLAUDE.md → "Content generation process" and "Citing real facts, companies, and cases") — does the hook lean on a real, verifiable, specific fact or number where one plausibly exists, rather than an anonymised composite invented out of excess caution? Is there one story given real space and narrative tension, rather than several thin ones stacked together? Is there at least one fresh analogy, not only recycled signature devices? Flag any of these that are missing — this is usually the difference between a structurally-correct script and a genuinely good one.
6. **Runtime check** — estimate word count and compare to the stated target runtime at ~140 words/minute. Flag if more than ~10% over (rule 8: cut 15–20% before filming).
7. **Rewrite** — produce a full rewritten version of the script that fixes every issue found above, preserving anything that already works. Save it alongside the original as `<original-filename>-reviewed.md` in the same folder.
8. **Placeholder list** — list every spot in the rewritten script (with line/section reference) where only the presenter's own lived experience can fill the gap, e.g. `[PLACEHOLDER: ...]` markers left from drafting, or generic examples that should be replaced with something personal. If the raw-material check in step 5 surfaced a gap only Aji can fill (a better real story, a fact worth verifying), ask directly rather than leaving it as a silent placeholder.

End with a short verdict: ready to film, needs one more pass, or needs a structural rewrite — and why.
