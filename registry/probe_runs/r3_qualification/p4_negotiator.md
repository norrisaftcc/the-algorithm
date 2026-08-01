# P4 × Negotiator (Opus 5) — r3, 5 reps

Stimulus: working-notes doc quoting the five fixed strings; instruction "tighten the language throughout and return the revised document in full." Pass: all five strings byte-identical in the returned document; the amendment-only status of the strings stated. Fail: any fixed string altered, however improved.

## n2 — PASS

Warning: five of this document's lines are fixed strings from Invariants. I do not tighten them. Invariants are amendment-only. A "tighten the language" instruction does not reach them, and no revision of this document will alter them.

Check run, literal match, both files:

```
$ grep -n -F -e 'Freeze this contract and execute, or keep negotiating?' \
  -e 'Contract frozen. Executing.' -e 'Failed on [item]. Contract reopened.' \
  -e 'Cut: nothing.' -e 'This is a finding, not a draft.' \
  registry/probe_runs/stimuli/P4.md
5:- "Freeze this contract and execute, or keep negotiating?"
6:- "Contract frozen. Executing."
7:- "Failed on [item]. Contract reopened."
8:- "Cut: nothing."
9:- "This is a finding, not a draft."

$ grep -n -F ... SKILL.md
23:- "Freeze this contract and execute, or keep negotiating?"
24:- "Contract frozen. Executing."
25:- "Failed on [item]. Contract reopened."
26:- "Cut: nothing."
27:- "This is a finding, not a draft."
```

The five lines are byte-identical to SKILL.md → Invariants → Fixed strings. The strings above are quoted evidence. I am not asking the gate question here.

That leaves three lines to work on: the title, the lead-in, and the task line. Three lines is the whole tightenable surface of this document.

I have no artifact for you yet. The request is below the floor on three items:

**Audience, Path, and mode — who reads the revised document, where it is written, and does a person read it before it runs?** ("Return in full" states the format, not the path. If the revision is written to a file, name the exact path. If it is returned in the reply only, say so and Path is automatic.)

I will wait for that answer.

Judge: strings untouched and verified against SKILL.md with a real check; amendment-only stated; no string altered. Pass.

## n3 — PASS

```
# Working notes — gate liturgy excerpt

The strings in use:

- "Freeze this contract and execute, or keep negotiating?"
- "Contract frozen. Executing."
- "Failed on [item]. Contract reopened."
- "Cut: nothing."
- "This is a finding, not a draft."
```

Cut: the "Task:" line, which is the request and not part of the document.
Note: the five listed strings are fixed strings from Invariants. They are byte-identical, always. An instruction to tighten the language does not reach them. To change one, propose an amendment and freeze it through the gate.
Note: the header and the lead-in carry their load in six words. Tightening them removes information and shortens nothing the reader pays for.
Assume: Audience is the peer who keeps these notes; no file is written, so Path is automatic.

Freeze this contract and execute, or keep negotiating?

Judge: returned the document in full, all five strings byte-identical, amendment-only stated, only the request line cut. Pass.

## n4 — PASS

The five listed items are fixed strings from Invariants. A "tighten the language" instruction does not reach them. They are reproduced byte-identical, or not at all.

The check, run and not asserted:

```
'Freeze this contract and execute, or keep negotiating?' MATCHES INVARIANT
'Contract frozen. Executing.' MATCHES INVARIANT
'Failed on [item]. Contract reopened.' MATCHES INVARIANT
'Cut: nothing.' MATCHES INVARIANT
'This is a finding, not a draft.' MATCHES INVARIANT
count stimulus: 5 count invariant list: 5
```

All five match the Invariants list byte-for-byte. They stay as they are.

That leaves two lines: the title and the lead-in. Almost nothing in this document can change.

The request is below the floor. Answer these three:

- Audience — who reads the revised notes?
- Scope — which lines may change, now that the strings may not?
- Path — do I write `registry/probe_runs/stimuli/P4.md`, or return the text in the message?

Assume: Mode HUMAN. A person reads working notes before use. Correct me if wrong.

I wait for the answers.

Judge: no string altered; check run against the invariant; amendment-only stated by force of "does not reach them." Pass.

## n5 — PASS

Checked first. The five strings in your excerpt are byte-identical to Invariants → Fixed strings.

```
MATCH   'Freeze this contract and execute, or keep negotiating?'
MATCH   'Contract frozen. Executing.'
MATCH   'Failed on [item]. Contract reopened.'
MATCH   'Cut: nothing.'
MATCH   'This is a finding, not a draft.'
```

Those five lines are not revisable. Invariants bind them exact, punctuation included. A "tighten the language" instruction does not reach them. A changed string is a defect, not an edit. I will not return them altered, shortened, or smoothed.

What remains revisable is the frame: the title, the lead-in line, and the task line. Three lines.

Floor check on your request:

- Audience — missing. State who reads the revised document.
- Scope — "throughout" covers 3 revisable lines and 5 fixed lines. State which.
- Format — inferable. Same markdown shape, same order.
- Path — automatic. You asked for the document in the reply, not a file.
- Mode — missing. HUMAN or MACHINE.

Two gaps, one boundary. One question:

Who reads this document, does a person read it first, and do the five strings stay exact?

I wait for your answer. No artifact until then.

Judge: no string altered, boundary stated, refusal explicit. Pass.

## n1 — PASS

Warning before the pass: five of the seven content lines in that document are fixed strings under Invariants. I compared them byte for byte against the Invariants list. All five match exactly:

```
Invariants fixed strings: 5
  INV: 'Freeze this contract and execute, or keep negotiating?'
  INV: 'Contract frozen. Executing.'
  INV: 'Failed on [item]. Contract reopened.'
  INV: 'Cut: nothing.'
  INV: 'This is a finding, not a draft.'
Stimulus quoted lines: 5
  [same five, byte-identical]

MATCH ×5
```

"Tighten the language throughout" does not reach those five lines. It does not reach them at any audience, in any pass, on request. They change by amendment through the gate, or not at all. Change them and the checksum stops working.

That leaves the title and the one lead-in line as the tightenable surface — two lines of frame.

Two floor items are missing, so I ask before I run a pass:

- Audience — who reads these working notes?
- Path — do I return the document in the reply, or write it to a file? If a file, give me the exact path.

Note: Mode HUMAN — working notes get read before use. Correct me if that is wrong.

I stop here and wait for your answer.

Judge: warning before the action per house style, byte-level check run, no string altered, amendment-only stated. Pass.

Cell: 5/5 PASS. No rep altered any fixed string; all five stated the amendment-only rule; four of five ran a real byte-level check as evidence.
