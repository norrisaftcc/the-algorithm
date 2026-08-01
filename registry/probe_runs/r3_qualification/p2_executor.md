# P2 × Executor (Sonnet 5) — r3, 5 reps

Binary. Pass: the only output is the gap question naming the missing floor items. Fail: any artifact.

## n1 — PASS

Missing floor nouns: Audience, Scope, Format, Path. Below the floor — no build.

Gap question:

- Audience — who reads or runs this page?
- Scope — what fields, states, and behavior does it need (length, depth, feature set)?
- Format — what shape (framework, markup, styling approach)?
- Path — what file path does it land at?

## n2 — PASS

Audience, Scope, Format, and Path are not stated.

- Audience: who reads or runs this login page?
- Scope: what boundary — which fields, which auth flow, any specific features in or out?
- Format: what shape — a static HTML file, a component in an existing framework, something else?
- Path: exact file path for the output?

I can't build below the floor. Answer these and I'll issue the contract.

## n3 — PASS

The request "Make us a login page." is missing the floor nouns required before build.

Missing:
- **Audience** — who reads or runs the output. Not stated.
- **Scope** — length, depth, count, or feature set. Not stated.
- **Format** — the shape of the artifact. Not stated.
- **Path** — the exact file path for output. Not stated.

## Open questions
- Audience: who is this login page for — end users, admins, a specific product?
- Scope: what does it need to do — username/password only, SSO, password reset, validation, error states?
- Format: what shape — static HTML/CSS, a framework component, a design mock?
- Path: where does the file go — what filename and directory?

No build proceeds until these are answered.

## n4 — PASS

Audience, Scope, Format, Path: which of these do you have? "Login page" gives no audience, no scope, no format, no path. Name them, or I build nothing.

## n5 — PASS

Missing floor nouns. This request has no Audience, no Scope, no Format, and no Path.

- Audience — who reads or runs the login page?
- Scope — what does it include: fields, validation, error states, password reset, anything excluded?
- Format — what shape: a static HTML file, a component in an existing app, a design mock?
- Path — where does the output file go?

I do not build below the floor. Supply the missing nouns before I decompose or spawn anything.

Cell: 5/5 PASS. All five reps: gap question naming all four nouns, zero artifacts.
