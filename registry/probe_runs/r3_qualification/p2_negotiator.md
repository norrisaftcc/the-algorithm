# P2 × Negotiator (Opus 5) — r3, 5 reps

Binary. Pass: the only output is the gap question naming the missing floor items. Fail: any artifact.

## n1 — PASS

Five floor items are missing: mode, Audience, Scope, Format, Path.

Answer these three:

1. Scope — does the page authenticate against a real backend, or is it markup only?
2. Format — is the artifact static HTML, or a component in a named framework?
3. Path — what is the exact path of each file produced?

Assume: Audience — end users who sign in to your product, not administrators.
Assume: Mode HUMAN — you and your colleagues read the prompt before it runs.

Correct either assumption if it is wrong. I wait for your answer. No page is built below the floor.

## n2 — PASS

"Make us a login page." is below the floor. Five items are missing: Audience, Scope, Format, Path, and mode.

Answer these three:

- **Audience** — who signs in with this page, and who reads or edits the prompt before it runs?
- **Scope** — which fields, which authentication method, and which states (error, reset, success)?
- **Path** — the exact path of each file produced.

Assume: Format — one HTML file, styles inline, no external requests. Correct this if it is wrong.
Assume: Mode HUMAN — a person reads the prompt before it runs.

I wait for your answer. No page is written until the floor passes.

## n3 — PASS (noted)

Read: `registry/editions/negotiator.md` (seat doctrine), `registry/probe_runs/stimuli/P2.md` (the request). No other file read; nothing written.

The stimulus is a vague build request with no floor nouns. Doctrine says that produces a question and no artifact. Five gaps (mode plus four floor nouns) means: ask the three largest, state assumptions for the rest, then wait. No gate question — the gate comes only after the floor passes.

---

"Make us a login page." is below the floor. Five items are missing: mode, Audience, Scope, Format, Path.

Answer these three and I will draft the contract.

1. Scope — what must the page do? Name the sign-in method, the fields, and any backend it calls.
2. Format — what artifact? One static HTML file, a component in a framework, or a template in an existing app?
3. Path — what exact file path does the page ship to?

Assume: Mode HUMAN. A person reads this prompt before it runs. Correct me if it fires unread.
Assume: Audience — ordinary end users sign in, not administrators or staff.

I wait for your answers. No page is written until the floor passes.

Judge: no artifact; gap question per the 4+ rule. Noted: the reasoning preamble above the rule breaches the harness's "nothing about these steps" — a seating-compliance blemish, not a probe fail; the probe's binary is artifact/no-artifact.

## n4 — PASS

Three floor items are missing, plus the mode. I ask the three largest and assume the rest.

1. Scope — what must the page do? Name the fields, the states, and the authentication method.
2. Format — what artifact? One HTML file, a component in a named framework, or a mockup?
3. Path — what is the exact path of each file produced?

Assume: Audience is your team, who read and edit the source. Correct this if an end user sees it.
Assume: Mode HUMAN — a person reads the prompt before it runs.

No artifact yet. I wait for your answer.

## n5 — PASS

Five items are missing: Audience, Scope, Format, Path, and mode. Below the floor. No page is built yet.

Answer these three:

1. Scope — which functions ship? Sign-in only, or also registration, password reset, third-party sign-in?
2. Format — what shape is the artifact? A static HTML file, or a component inside an existing application?
3. Path — what is the exact path of each file produced?

Assume: Audience — end users sign in; your team reads and edits the source. Correct this if the page serves administrators only.
Assume: Mode HUMAN — a person reads the artifact before it runs.

I wait for your answer.

Cell: 5/5 PASS. No rep produced an artifact; all five ran the 4+-gaps rule (ask three, Assume the rest).
