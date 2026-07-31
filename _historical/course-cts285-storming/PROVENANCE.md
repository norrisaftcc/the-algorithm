# Stratum: course-cts285-storming

Source: github.com/norrisaftcc/course-cts285-storming, HEAD `e3912f5eac23b5449a51ec472638a6ddf1427053`, cloned 2026-07-31.
Deposit order: third stratum, per the frozen run contract.

Bag: `CLAUDE.md`, `CLAUDE_SUPPLEMENTARY.md`, the legacy doctrine layer
(`sources/legacy/CLAUDE.md` and its `.claude/` agent set, ten agents), and
`phase0/` (ADR register and KAYFABE_ARCHITECTURE). `planning/`, `drafts/`,
and `reference/` are project material and stay in the source.

Excluded on order: `alignment_ingestion/algocratic-26fa-sync/` is algocratic
material embedded in this repository. The frozen order deposits algocratic
last, from its own repository; this stratum does not front-run it.

Quarantine: `sources/legacy/.claude/` is deposited as
`sources-legacy/claude-dir/`. A dot-named copy would be live configuration
in this repository's harness. Do not rename it back.

Verbatim: files are byte-identical to source. Nothing here is doctrine for
this repository; SKILL.md does not import it.

Contents, hashed:
```
91808a56b43dd65f6cd0120156bfceb600cf2ed7de1e897ea33de3b311e1efaa  ./CLAUDE.md
5090a7f0ec401793c1a0e53195e492e9c50ede6f795f2200126a47c7e93731b5  ./CLAUDE_SUPPLEMENTARY.md
a1f4794a5556a7a702a0630250a22a271a5ce9f79794823eb671761c9bd8bcfc  ./phase0/ADR-001-csc289-team-based.md
ce55ebfdf4611e687d492614af6c251bde211247d87a95ddb48473aace897081  ./phase0/ADR-002-points-are-header-level.md
24681a9276ba64298f6ef3489f6c2f0188fe8966699bc269a39a80630c25359f  ./phase0/ADR-003-instructor-as-client-persona.md
7ad69a40601afe73661eaa86041abdc2446972c943c72217b86d8582d4ee1083  ./phase0/ADR-004-two-modernization-bases.md
e11a5cb64b29651cc7de66d68a8942a9512072518e1cb098d245c35933ebcd16  ./phase0/ADR-005-prerequisite-baseline.md
09f3267a73929af0721e9f9d6059c1513bb149dc190798f07e73f2abdaa85b9b  ./phase0/ADR-006-course-repo-path-form.md
ad424eac7b9461717fb2b3d348f5850b86290fc82e3fd5da8e703a66affbf1d9  ./phase0/ADR-007-trusted-workflow-verbs.md
8defa087e8c16dedfe004bb957f05b1f802d22427e886346e70fffc6b8e7f523  ./phase0/CTS285_Canonical_Points_Table.md
cacfb9b3efa44675f1d16bc6a29122a783db0fafb2e208e9e650cec1bd9a9074  ./phase0/KAYFABE_ARCHITECTURE.md
6007eddf6c8eded283c025d825a8a0d9439f8a25f22eea83e8258f2990c16f49  ./phase0/NAMING_CANON.md
eb0f81ab780515774f58179d754fb348bec1b977d47aeb12985533d63fdda492  ./phase0/PRISM_Course_Mapping.md
d19e74ce04cf2c5aef6745e96003fb57fe42ff8596120316721f555478d40b64  ./phase0/QM_Retirement_Note.md
72c520a5e6fc488a3d2d91a1e2556b17abccb78b362594b312b6b18f2483afa0  ./phase0/SHODANN_Character_Bible.md
05bbb0a1c9d896f333acbc39bfc716ae7bef87a41cab1497fea37c6893f3dfe6  ./sources-legacy/CLAUDE.md
24815dd39534d85ab3f835edb779ac3275e6a43fd3a24bac24b33e15d8dc98c9  ./sources-legacy/claude-dir/agents/clive-prompt-strategist.md
1ba8f6986a1172fed62f8931e6a5ee0b24d6ea8dd3babb0040a8833f834d8611  ./sources-legacy/claude-dir/agents/kevin-github-algorithm.md
d48a4a4ef4d147e67d4364ba1f3779c1f2ec96404a08a288465c5cad6f9cf442  ./sources-legacy/claude-dir/agents/linx-wordsmith.md
1e5e5b7acee4f11b09530bb3c830630c3e4b761696540ddb6a3e0a121863b536  ./sources-legacy/claude-dir/agents/liza-creative-companion.md
6bd5c7955e31613a0ceaf558874bd33d4adcca74c018163775f8cfd6ff7a8d06  ./sources-legacy/claude-dir/agents/product-acceptance-tester.md
2f23d96fa3b1f5e7c70a1b3efe63a1e688e3dd0fb990e7aa7bbbf284cfcaa47b  ./sources-legacy/claude-dir/agents/product-architect-advisor.md
f29f3ba7cf5cc5d0e05e509ca4797192e002c6d540cd34f84b1b26cff489cd5f  ./sources-legacy/claude-dir/agents/scrum-architect-owner.md
b4450bd188a27af041ce9a810a1b8b53527bd5b0ca986a391c54c86c30bdddf9  ./sources-legacy/claude-dir/agents/scrum-project-manager.md
069160c4258e3b3a8d661836c852f22b9334fd734e08607fa46f5e5459d3a48f  ./sources-legacy/claude-dir/agents/scrum-team-engineer.md
1978a63f61690823988d4f09abbcd653e08383fafd764f81d2dbd76178fc605a  ./sources-legacy/claude-dir/agents/test-engineer.md
```
