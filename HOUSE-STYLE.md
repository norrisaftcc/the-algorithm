# HOUSE-STYLE v2.0 — public edition (proposed)

Status: proposal. Governs documents this repository ships publicly. The SKILL.md
Language lock governs internally until the repoint amendment freezes. This file
supersedes nothing until a gate says so.

## Why this style exists — exempt from condensation
Controlled language here serves the reader's recovery of meaning, not the writer's
control of the reader. The mechanism is parallel to Newspeak, and this file says so,
because a style guide that will not name its nearest neighbor cannot be trusted near it.
Three differences hold the parallel apart. Each is an invariant of this file:
- The dictionary is open. Every change passes a gate and enters the record.
- Every cut is kept. Nothing governed by this style is ever silently smaller.
- The peer's meaning outranks the vocabulary. Always.
A revision that weakens any of the three has failed, whatever else it improves.

## The enforced subset
1. One word, one meaning, one part of speech.
2. Twenty words per instruction. Twenty-five per descriptive sentence. One instruction per line.
3. Six sentences per paragraph, at most.
4. Active voice. Imperative mood for procedures. Present tense unless time is the subject.
5. No idioms. No noun cluster longer than three nouns.
6. Warnings come before the action they govern. Command form.
7. Mode governs grammar. HUMAN mode: connective grammar is load-bearing. MACHINE mode:
   shorthand is fine if the downstream receiver succeeds.
8. Fixed strings are contracts, not prose. Exempt from style and from all editing
   outside the amendment process.
9. Domain terms belong to the peer. A wrong-but-deliberate term survives with a Note.
   The peer decides.
10. The reason section of any governed document is exempt from condensation.
    The exemption is written inside the section it protects.

## The dictionary
- Seed: the ASD-STE100 approved-word list, imported by diff. Each import is an
  amendment through the gate, recorded with a hash.
- Additions and removals pass the same gate. The dictionary is versioned.
- A dictionary that shrinks without a record is the failure this file exists to prevent.

## Enforcement
- The subset is machine-checkable: word counts, sentence lengths, approved-word
  membership, part-of-speech conflicts.
- Build the linter. Run it as an assayer: it reports, it never rewrites.
- Rule 9 outranks the linter. The linter flags; the peer decides.

## Supplier record
Upstream inspiration: ASD-STE100, recorded as a supplier, not an authority. No license
held; no external document governs this repository. Upstream releases may be diffed and
selectively imported — each import an amendment, recorded.
