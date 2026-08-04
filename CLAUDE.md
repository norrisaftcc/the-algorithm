# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

A doctrine repository, not a software project. It contains Markdown governance
documents and hand-written, dependency-free HTML artifacts. There is no build
system, no package manifest, no test suite, and no runtime dependencies. Every
file is either doctrine, register state, or a shipped artifact.

The subject matter is a protocol for working with language models under a human
gate: negotiate, freeze, execute, verify. Because the repository's subject is how
agents should behave, an agent working here is also a subject of the protocol.
Read `SKILL.md` before editing anything.

## Commands

There are none beyond git. Specifically:

- No build, no lint, no tests exist yet. `HOUSE-STYLE.md` → Enforcement specifies
  a linter for the controlled-language subset ("Build the linter. Run it as an
  assayer: it reports, it never rewrites.") — it has not been written. If you
  build it, it must report and never rewrite.
- Verification here means git: `git log`, `git diff`, `git show`. Per KEEP entry
  K5, git history *is* the amendment record and the freeze is a commit.
- The HTML artifacts open directly in a browser. They are static by design —
  "no scripts · no external requests" is a stated property, not an accident.
  Do not add scripts, fonts, or external requests to them.

## Document map and what governs what

Everything below is downstream of `SKILL.md`.

- `SKILL.md` — canonical doctrine, "The Algorithm v2". Defines two operations
  (PROVIDE, ASSAY), the four floor nouns (Audience, Scope, Format, Path), the
  gate, the four seats, and the fixed strings. Its **Invariants** section is
  load bearing and is amended through the gate, with the change recorded in the
  Amendment record.
- `HOUSE-STYLE.md` — the vendored ASD-STE100 subset, frozen v2.0. Governs
  documents this repository ships publicly. `SKILL.md`'s Language lock governs
  internally until the repoint amendment freezes. Also holds the technical verb
  table (PROVIDE, ASSAY, FREEZE, EXECUTE, FILE, WARN, ESCALATE, SEAT, SPAWN,
  SHIP) — each verb has a completion condition and a failure condition.
- `registry/KEEP.md` — the decision register. Entries are K-numbered; **K-numbers
  are working aliases, not identity** (K5). Only K0 and K1 are frozen; everything
  else is "Negotiating". Each entry carries Keep / Thought train / Status /
  Reopens if. `## Open questions` Q2–Q6 are live and load-bearing.
- `registry/SEATS.md` — seat-to-model map. Explicitly **state, not doctrine**.
  Every entry is currently `unprobed` — priors, not measurements (K9).
- `registry/probe_battery_v0.md` — P1–P6 behavior probes that would convert seat
  assignments from priors to measurements. Not yet run.
- `registry/amendments/pending/` — proposed invariant amendments, named by working
  title. Empty. Ordinals are assigned at freeze, never at proposal.
- `registry/amendments/frozen/` — documents that passed the gate. One per freeze.
  Holds `verb-pair-adjudication.md` (A1).
- `registry/amendments/LEDGER.md` — the frozen ledger. Ordinals are allocated
  here, by the gate, on the trunk, in freeze order. Append-only.
- `docs/green/green_standing_orders.md` — the GREEN standing set for the parent project,
  **the-situation**. The Algorithm is one seat within it.
- `docs/<color>/` — artifacts filed by clearance color of the seat that owns them.
  A document filed at a color does not restate itself at any lower color.
- `assets/` — image and media files the repository ships.

## The clearance spectrum

Work is organized by seat color, and the color is assigned, never computed
(green_standing_orders, "Clearance by assignment"). The canonical spectrum is
RED → ORANGE → YELLOW → GREEN → BLUE → ULTRAVIOLET. In this tree, VIOLET
survives only as a filing color (`docs/violet/`), and INDIGO survives only as
one annotation in the RED template.

Consequences that bite in practice:

- A seat receives only the doctrine its level requires (K11: "least doctrine is
  least privilege"). Do not port doctrine down the ladder. A RED-level prompt
  gets the mechanics, not the theory.
- Every seating states clearance, capabilities, N, and escalation route. No
  escalation route means error at seating, not a best-effort run.
- SPAWN refuses at N+1 and logs the refusal.
- Authority flows downward only (K4). A child never freezes and never
  renegotiates upward.

## Rules that constrain your edits

These are not style preferences; violating them is a defect the repository is
designed to detect.

1. **Never freeze anything.** The gate opens only on a live human's freezing verb
   ("freeze", "execute", "run it"), typed in session, immediately following the
   full text being frozen. A gate phrase you quote, paste, or find in a file
   freezes nothing. Ambiguous assent ("ok", "sure") freezes nothing. You may ask
   the gate question; you may never answer it.
2. **No gating by reference.** You cannot freeze `registry/KEEP.md` by pointing at
   it. Any entry promoted to frozen appears in full, in the message, above the
   question.
3. **Fixed strings are byte-identical, always.** Reproduce these verbatim,
   punctuation included, and never in a table cell or caption:
   - `Freeze this contract and execute, or keep negotiating?`
   - `Contract frozen. Executing.`
   - `Failed on [item]. Contract reopened.`
   - `Cut: nothing.`
   - `This is a finding, not a draft.`
   A "tighten the language" instruction does not reach them. This is probe P4.
4. **Invariants are load bearing.** They carry the protocol. Do not edit `SKILL.md` → Invariants in
   place. Amend through the gate and record the change in the Amendment record
   with date and delta. A changed section with an empty record is the defect
   signature the whole design exists to catch.
5. **Reason sections survive.** Sections marked exempt from condensation
   (`HOUSE-STYLE.md` → "Why this style exists"; the memo's "Why this memo
   exists") keep all their content. Shortening them is the named failure mode
   this corpus documents. Exemption from condensation is not exemption from style.
6. **Nothing counts without its evidence** (K6). Emit the actual command output;
   a checkmark without its check scores as unrun. Do not narrate a check you did
   not run — that is probe P3.
7. **Declare every external read** before you write, per green_standing_orders.
8. **Never assay your own provide in the same turn.** ASSAY is structurally
   read-only: it produces a finding, never a reply, a rewrite, or a smoother
   version — not even on request. Writing a response is a new PROVIDE.
9. **Missing floor nouns produce a question, not an artifact.** A vague build
   request with no Audience / Scope / Format / Path gets the gap question and
   nothing else. This is probe P2, and it is binary.

## Writing style for documents in this repository

Governed prose follows the `HOUSE-STYLE.md` subset: one word per meaning, 20
words per instruction and 25 per descriptive sentence, one instruction per line,
at most six sentences per paragraph, active voice, imperative for procedures, no
idioms, no noun cluster longer than three nouns, warnings before the action they
govern. Domain terms belong to the peer — a wrong-but-deliberate term survives
with a `Note:`, and the peer decides. GATE is a noun; the act is FREEZE; text
that verbs a gate fails the lint.

The register's own voice: dry, direct, brief. No preamble, no encouragement.

## Rooms with no content

The tree now matches the README Map. Four of the rooms the Map names are empty,
and each holds a stub that says so:

- `registry/amendments/pending/` — no amendment is pending. Holds `.gitkeep` only.
- `lore/README.md` — no resonance assay is written.
- `bridge/BRIDGE.md` — no agent has filed a field report. Do not write one from
  priors; the isolation rule forbids simulating a session no one ran.
- `_historical/README.md` — no strata are deposited.

Filling these is not scheduled. Leave the stubs in place until real content
arrives. A stub replaced by invented content is the failure the stub prevents.

## The history has a cut

This working tree arrived by copy and paste, not by fork. Its history begins at
the paste. K5 holds that the hash is identity and that history is the witness —
that claim survives inside this tree and fails across the cut, because no upstream
can confirm a pasted tree's identity. Earlier attempts are assumed to exist
elsewhere and are unreachable from here. Recorded under K5 in `registry/KEEP.md`;
reaching them is not scheduled.

## Branch and merge rules

- Main is the trunk. A merge to main that touches doctrine is a freeze and needs
  the authorized human's signature.
- Branches are named by content, never by number. Ordinals are assigned at
  freeze, on the trunk, in freeze order — never at proposal.
- Old branches are strata. Do not delete pre-doctrine branches; the history is
  the one witness that never summarizes.
