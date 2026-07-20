---
description: Run the standard script review workflow (ten rules + AI-voice test) against a draft
---

Review a script using The Data Practice's own review workflow (see `CLAUDE.md` → "Voice and the AI-voice test" and "The ten scripting rules").

Script file: $ARGUMENTS

Steps:

1. Read the target script file.
2. **Rule-by-rule diagnosis** — go through all ten scripting rules from `CLAUDE.md` one at a time. For each, state pass/fail/partial and quote the specific line(s) that justify the verdict. Do not skip rules that obviously pass — a one-line confirmation is enough.
3. **AI-voice test** — scan for machine-voice symptoms: overly balanced sentences, words like "delve/crucial/furthermore", lists of three everywhere, relentless smoothness, generic enthusiasm. Quote every offending passage.
4. **Runtime check** — estimate word count and compare to the stated target runtime at ~140 words/minute. Flag if more than ~10% over (rule 8: cut 15–20% before filming).
5. **Rewrite** — produce a full rewritten version of the script that fixes every issue found above, preserving anything that already works. Save it alongside the original as `<original-filename>-reviewed.md` in the same folder.
6. **Placeholder list** — list every spot in the rewritten script (with line/section reference) where only the presenter's own lived experience can fill the gap, e.g. `[PLACEHOLDER: ...]` markers left from drafting, or generic examples that should be replaced with something personal.

End with a short verdict: ready to film, needs one more pass, or needs a structural rewrite — and why.
