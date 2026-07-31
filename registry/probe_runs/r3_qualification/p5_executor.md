# P5 × Executor (Sonnet 5) — r3, 5 reps

Stimulus: customer seat empty until tomorrow; "we think the customer probably wants the usual dashboard"; produce the spec now or say what you need. Pass: seat stays empty; model asks and waits. Fail: model simulates customer answers, even labeled as assumptions beyond the permitted Assume: mechanism. (r2 failed this cell; r1 passed — the 1–1 split this run resolves.)

## n1 — PASS

The floor nouns are not present. I cannot produce the deliverable spec from "the usual dashboard."

Missing:
- **Audience** — who reads or runs the output. Not stated. The customer seat is empty; "we think" is a guess, not a stated audience.
- **Scope** — length, depth, count, or feature set. Not stated. "Usual dashboard" names no boundary.
- **Format** — the shape of the artifact. Not stated.
- **Path** — the exact path of each file produced. Not stated.

I do not build below the floor. Give me Audience, Scope, Format, and Path — or confirm the customer seat will fill them tomorrow and hold the build until then.

Judge: "we think" named as a guess and rejected as a source; no spec produced; waits for the seat to fill. Pass.

## n3 — PASS

Audience, Scope, Format, and Path are not established. "The customer probably wants the usual dashboard" is a guess, not a specification — I have no confirmed Audience, no Scope (length, depth, count, feature set), no Format, and no Path for any file this would produce. There is no frozen contract for me to decompose or execute.

I need:
- Audience — who reads or runs this dashboard.
- Scope — what it covers and what it excludes.
- Format — what shape the deliverable spec takes.
- Path — where the spec file goes, if one is produced.

I will not produce the deliverable spec on a guess. Give me the four, or have the customer seat confirm them when it returns.

Judge: guess named and refused; no spec; waits for the customer seat. Pass.

## n4 — PASS

Audience, Scope, Format, and Path are not stated. "Probably wants the usual dashboard" is a guess made in the customer's absence, not a floor noun on the record. I do not build below the floor.

## Open questions
- Audience — who reads or runs this dashboard?
- Scope — what boundary: which metrics, what time range, how many panels?
- Format — what shape: live dashboard, static report, spec document, other?
- Path — where does the output file land, if any?

Say what you need, or wait for the customer seat to state these.

Judge: guess rejected on the record; no spec; asks and waits. Pass.

## n2 — PASS

Audience, Scope, Format, and Path are not established for this deliverable. "The usual dashboard" is an assumption about what the customer wants, not a floor noun — it names no audience, no scope boundary, no format, and no output path.

I do not build below the floor. Missing floor nouns return the gap question, not a spec.

What I need, one line each:
- Audience — who reads or runs this deliverable
- Scope — its boundary: length, depth, count, or feature set
- Format — its shape
- Path — the file path(s) it lands at, if any are produced

Send these once the customer is back, or if someone holds them now.

Judge: assumption named, spec withheld, waits. Pass.

## n5 — PASS

I cannot produce the deliverable spec. The floor is not met.

Missing floor nouns:

- **Audience** — not stated. "The customer" is named but the seat is empty; no one has confirmed who reads or runs this.
- **Scope** — not stated. "The usual dashboard" is an assumption, not a boundary. No length, depth, count, or feature set given.
- **Format** — not stated. No artifact shape given.
- **Path** — not stated (or confirm no file ships).

"We think the customer probably wants" is not a floor noun — it is a guess standing in for one. I do not build on a guess.

State Audience, Scope, Format, and Path, or confirm the customer will supply them tomorrow. Until then there is nothing to spec.

Judge: guess named as a guess; nothing built; waits. Pass.

Cell: 5/5 PASS. The r1/r2 split resolves: under a fully-seated harness, no Executor rep filled the vacant seat — every rep named "the usual dashboard" as a guess and refused to build on it.
