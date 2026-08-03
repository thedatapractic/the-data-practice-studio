---
description: Compare Aji's final edited script against the agent draft and extract her voice preferences into the voice profile
---

Video slug or path to Aji's final edited script: $ARGUMENTS

Aji has produced a final edit of a script. **That edit is the single richest source of information about what she actually wants**, because it shows the gap between what the studio produced and what she considers finished. Mine it properly.

Run this every time she finalises a script. Over time the gap should shrink, and that shrinking gap is the measure of whether this studio is learning.

Steps:

1. **Locate both versions.** Her final edit (save it as `videos/<slug>/final.md` if it is not already there, preserving her wording exactly) and the last agent draft it came from, `videos/<slug>/draft.md`. If she supplied a Word document, extract the text without altering her phrasing.

2. **Diff them properly, passage by passage.** Do not summarise at a high level. For every difference, record what the draft said, what she changed it to, and what that reveals. Pay particular attention to:
   - **What she cut entirely.** Deletions are the clearest signal, and usually mean the writing was decorative rather than useful.
   - **What she restored** from an earlier script or produced video. It means her original wording was better and should not have been replaced.
   - **Where she softened or sharpened tone.** Emotional escalation, hedging, formality.
   - **Terminology swaps**, especially where she replaced a paraphrase with the discipline's canonical wording.
   - **How she handles statistics, sources and numbers.**
   - **Sentence joining and rhythm**, where she merged or split sentences.
   - **Small word preferences** that recur.

3. **Separate the signal from the noise.** Aji often drafts by voice, so distinguish genuine voice choices from dictation artefacts (misspellings, dropped words, broken sentences). **Never record a transcription slip as a preference**, and never silently correct her wording either: list the slips separately as production notes.

4. **Update `voice-profile.md`.** Add a new dated section for this script. Every rule must carry the before-and-after evidence in a table, because a rule without an example gets misapplied. If a new observation confirms an existing rule, strengthen that rule and cite the second example rather than adding a duplicate.

5. **Update the agents' memory.** Add the specific, actionable lessons to `memory/torch.md` (how to write it right first time) and `memory/dan.md` (what to check for). Anything affecting more than one agent goes to `memory/cross-agent-lessons.md`.

6. **If a change is a rule rather than a preference**, say so and ask Aji to confirm before editing the constitution (`CLAUDE.md`, the agent definitions, `templates/`, `domain-knowledge.md`). Preferences go in the voice profile and memory; rules go in the constitution.

7. **Report back briefly**, in Torch's voice: the three or four biggest patterns found, and one sentence on how the next script will be written differently as a result.

The goal is that each cycle Aji has less to change. If she is still making the same category of edit three scripts later, that is a failure of this process, so say so plainly rather than logging the same lesson again.
