# Stratum: course-csc134-template

Source: github.com/norrisaftcc/course-csc134-template, HEAD `6f39d0a84d3de7c6bc4ba8fd873f1fc2a8fd9f03`, cloned 2026-07-31.
Deposit order: second stratum, per the frozen run contract.

Bag: agent doctrine and its registers — `CLAUDE.md`, `.claude/` (ten agents,
seven skills, settings), `_past_work/CLAUDE.md`, `_claude_sage/` (the
customization kit the doctrine came from), `_lore/` (ADR-000 through the
findings register; ADR-003 assigns fleet models to seats). Course content
(modules, assignments, outline) is project material and stays in the source.

Quarantine: `.claude/` is deposited as `claude-dir/`. A dot-named copy would be
live configuration in this repository's harness. Do not rename it back.

Verbatim: files are byte-identical to source. Nothing here is doctrine for
this repository; SKILL.md does not import it.

Contents, hashed:
```
f99b8f3496da09de05278a007fc9bbfa3bb3d35c5651041b9c4eef1cb22934f1  ./CLAUDE.md
ef8dc5ceb39594649d30c238c38bc912dc335c139e2f1fc38c27eae814d8272d  ./_claude_sage/README.md
31b6cf1f3b4647cc9f33340ff04053d4b10bb208f1aef006ae815be17921bae0  ./_claude_sage/files/ARCHITECTURE.md
893e6e8859c6ebc29dccc0585758ee2db623ff3f0c4955cf2e1b46c74e783cf1  ./_claude_sage/files/SKILL.md
a2c90fb17b5308a7e523cb6a333fb82deeecddf9df1e0122944fabb432ecc322  ./_claude_sage/files/claude-code-customization-kit.zip
78b3de69aec39df0bdfc8b9cf690198c4fa5a49b706bd331f7bb54f7f7c94081  ./_claude_sage/files/hook-completion-report.sh
893e6e8859c6ebc29dccc0585758ee2db623ff3f0c4955cf2e1b46c74e783cf1  ./_claude_sage/files/mnt/user-data/outputs/SKILL.md
59877f4250d3bc29ffad8223552efb200f62ee26232e5c7450e7497f098e097a  ./_claude_sage/files/skill-course-content-writer.md
893e6e8859c6ebc29dccc0585758ee2db623ff3f0c4955cf2e1b46c74e783cf1  ./_claude_sage/files/skill-reading-generator.md
3ddb229a6776458b02320060c25d1784ec734878baf01711525837310a93e19d  ./_lore/README.md
acbad5fa165ec85a0b5bc63de20f0c22f9965de3b0d29b4acea17835ecd4cd59  ./_lore/decisions/ADR-000-the-repo-is-the-wiki.md
befd5d8ca581a8da9aa638cfedef54d8090fba13a4d9ba680fc31164cfb57fe9  ./_lore/decisions/ADR-001-alpha-scope-and-locked-decisions.md
6285de167fd770aa987a448b782dd392ada4771f768d01e702fd2b613a627eab  ./_lore/decisions/ADR-002-phase0-rulings.md
ccbd35a39faf486bd148e5895dafc0df3dc380f6630e9790991db436c8453d8a  ./_lore/decisions/ADR-003-fleet-model-assignments.md
5bee6945ee6acf90f0713162e269de985fbbf9dd795713c9b4571f15d21e8e01  ./_lore/decisions/ADR-004-two-tier-git-workflow.md
923aedf665a476f4843412d93177cab5d4c9b55fd90a9c98cb00605029ce893a  ./_lore/decisions/ADR-005-negative-tacos.md
db337ee5d24c6ee352d5e26fe1fdcdc9532b7fc704c1dbaa4da481efc1861984  ./_lore/decisions/ADR-006-mail-run-and-import-direction.md
bf18636c55e23cb5d1197972f672d9d1f432241e93893978d3c3f84abd94745d  ./_lore/decisions/ADR-007-postmark-rule.md
2c9c50814a0761ca3a545ad4ec08584dfeb3475a93b791048fb5b5fa3084f471  ./_lore/decisions/ADR-008-two-tree-module-layout.md
a5c596897d21019530c2d0ac350f95ee697d609e5bb33c0f6ec8eec94475831d  ./_lore/decisions/ADR-009-teach-using-namespace-std.md
6dd2eaf2f7d03fff05f602cb364279fd0ecbf61245f86fc03a547cd1ec7d99c8  ./_lore/decisions/ADR-010-m3-remap-recreate-with-salvage.md
a257caabd40b5eb5b80db96f72b38367c8a71ce18fcbdc27619b2f65346ac04e  ./_lore/decisions/ADR-011-descope-stl-and-file-io.md
45ad4d7d31c19532b32cb5d1c4763d6ead5d0fb5194a128cbdc5804f3f656711  ./_lore/decisions/ADR-012-canvas-compositor-enters-alpha-scope.md
49a40f00f48e1b19f470cab25d0128d2ce775fd439e772383553cd331faf569d  ./_lore/decisions/ADR-014-compile-gate-runs-on-gcc-in-ci.md
fd9bfb54d4f4b51d746da7bce2871958a9f467543f0c698d8b58f705262a3873  ./_lore/decisions/ADR-015-markdown-blocks-mirror-gated-source.md
9db6d737d33db83dfde09fea103cd62121d695cc5062339d81b30662cdf8f260  ./_lore/decisions/ADR-016-breadth-first-pass.md
64303454e393861aeb548ddce71d47adee0a45189f9b96f5f1a91cf36f37b0da  ./_lore/findings/F-000-fleet-and-guild-install.md
fd6ad8b257281a893eb26c16fce2fca5edc45a84c1bcc27d52c4647c1214c8cb  ./_lore/findings/F-001-numbering-reconciliation.md
790254b4f812fd921266affe84fdb590652904544c2fc5f5cb1802d87fde47da  ./_lore/findings/F-002-interface-contracts.md
0de003db566acd1c4a3a2f9c3db0bddaff8bf0d5233069dea0ed580fd219009d  ./_lore/findings/F-003-module-skeleton-and-persona-review.md
3473142f854bbe5a2002c650b15a589a54ffc340230095886329cc588761631c  ./_lore/findings/F-004-m4-deep-build.md
8d21e653c728c3797c08107772842dda2ff5ed6c1393bdab2751502b9f2a3efd  ./_lore/findings/F-005-m4-cohort-round1.md
16c68b684b16ffc2006ea889c92137d465604aadf42ef677414f8d18e1ba06cc  ./_lore/findings/F-006-m4-fixes-and-ready.md
8201929aa58f20b341b2bef362ffe89133ddeb11849be86c27e92262e412217f  ./_lore/findings/F-007-m5-deep-build.md
81023fdf668b53d0a3a5788e46b985e2caa63d93f531bccc09943750d54a80bb  ./_lore/findings/F-008-canvas-compositor-import.md
01eef54779de4374fd54a49aefa068496d548f26e9ea174ea4b8838799b14ff6  ./_lore/findings/F-009-fallthrough-warning-claim-is-toolchain-dependent.md
cf9fbd1838513f859f7c3c30dce18955e2809d6af76f546261724edb5899bf98  ./_lore/findings/F-009-verification-procedure.md
284f024f6746f855356e6b3bbdcdff4a221540631a493ca4f97180eba861460c  ./_lore/findings/F-010-m4-compiler-claim-fixes.md
bc0ed19d81acf4e18118214ed0b6e5595dedb2f1fd22f165b9baf1861814143e  ./_lore/findings/F-013-markdown-blocks-are-unversioned-copies.md
97f24e3011376c83a4b35dd3b358590bf380434a45fb3be8faa37ba589a57144  ./_lore/findings/F-014-breadth-pass-state-audit.md
a37f5e2eb99dcb970929da74f14f597c7c352c65715818d9519713d7d1e108fa  ./_lore/findings/F-015-breadth-pass-recipe.md
67b8e1cd07533b1f2104a1c992f23257c9a0b36b23d9ee1794f9c0eaf7966423  ./_lore/findings/F-016-m4-fence-migration-partial.md
d5e8b09f04c3dae67fa3fc2778f384d0e299b900ac56bcb02a563b394bb41020  ./_lore/findings/F-017-m5-cohort-round1.md
d6da373601ae0b6dbc1bd8836b4f3592c92fd300f9d7881cd27571f6e23810db  ./_lore/findings/README.md
eba9df254bd6afebd28fd7f4cebb86341853cd57675d17e78adb31cab32beed5  ./_lore/glossary.md
8449aaec821b7360191164957373e832db031d97a031803c4a09995bd6221479  ./_past_work/CLAUDE.md
fbd9486162de715898a52eeb2c87c273196ae12aba87024d1c00c5e16df31c06  ./claude-dir/agents/cadence-master.md
cbd578a055a1cc00e7088672fb66a68dd64e26e20b24abb35f1feb799eae2f56  ./claude-dir/agents/clive-prompt-warden.md
27dedcce4daf98d3cf7b3571472bae02dea7994677d5496afd1c0a3f7579b975  ./claude-dir/agents/cohort-lead.md
20fedbb9a8cd59ff6e4f254626f0825ff9230c5e76a54415c97a9a581bca93ad  ./claude-dir/agents/compile-warden.md
c3a3a5ca81ce1f1aceca217a63090fd15d6ddb864858d948ebbd1bf4a6cf5392  ./claude-dir/agents/kevin-repo-warden.md
2e284f02624e46ae241fb534163189c54cdd4aa4089f85623d87eaaceebf442d  ./claude-dir/agents/linx-voice-readability-editor.md
6353e193505bb6de4c9100e619d4dab755d688d5795db7e41ba007b4196f75ac  ./claude-dir/agents/liza-theme-skinner.md
294e196a41255e191b9e77cd45c37fe6d914086fa79a6049f0f6ca983be97eae  ./claude-dir/agents/module-builder.md
b4db667cd07485ed8b32d66dc187f1949242d4e5b32711044390ef8074cb50b7  ./claude-dir/agents/program-advisor.md
da5cd7d0e90f975b4fb1a17463c7893def968ae17cbe41f5be479d8d2f0c42f3  ./claude-dir/agents/spine-owner.md
b65f19b3e3515816f44f8a3b3d752a2f30310c1d7757f4f9e7f844a120172e62  ./claude-dir/settings.json
09486045bd3fd0329a5f3d021c3783de0c85d56306a9ba3078af5df0f44902bf  ./claude-dir/skills/apply-tutorial-generator/SKILL.md
2d80b8ecd509f7ce48fa2b8774260c2f784f0039ac4bc3197a5fe80536390e03  ./claude-dir/skills/course-content-writer/SKILL.md
9f52ad580e58c5a35507d5b8487e74b8d37ba006f204e244d19f40665e270b7f  ./claude-dir/skills/csc134-canvas-compositor/SKILL.md
6927ba822889e5b099e8b5bf9a128da0f4e69cd65e394afb49637fb26f0f0408  ./claude-dir/skills/csc134-canvas-compositor/gate.py
79851f9db587345970c1dba7c96b0046cd9b3f9a7462453900311e23d1b57b24  ./claude-dir/skills/csc134-canvas-compositor/references/PLACEHOLDERS.md
837e7f9a23683fbea41a263beb3eac66805b623edb2d8337685679e1c0ee3f0e  ./claude-dir/skills/csc134-canvas-compositor/references/README.md
31cd08155cb6df84ff9cc47b94848c0ae9a475f9484ca4c936f3fc5390b5a220  ./claude-dir/skills/csc134-canvas-compositor/references/m01-page-talk-to-computers.html
60ff76d6e4defda23b18e050bfb998a0ad7a6361aeda3e9461345f3a35384212  ./claude-dir/skills/csc134-canvas-compositor/references/m02-page-draw-it-first.html
4d1ffabcf92b0b5f0427f048a91e8d69798fedb9ff25467b2296983a68517528  ./claude-dir/skills/csc134-canvas-compositor/references/m02-practice-ANSWERS.md
0d031ca4effb0f7ae0483381a718ae2e66c89f0c7b45495d0b5097c51e13c919  ./claude-dir/skills/csc134-canvas-compositor/references/m02-practice-exit-ticket.html
701c195c1aa13685e7035c1fc8918b2775492390fd1584f4cf2bea68def242d0  ./claude-dir/skills/csc134-canvas-compositor/references/m04-page-apply-gatekeeper.html
2edf20233f7003d102ba1ab384d42ef2bd2d40716c7fdfe1fc0c93566d9fdd35  ./claude-dir/skills/csc134-canvas-compositor/references/m07-page-apply-rooms-struct.html
835c36ab8b0fae55b8e3726963c7c5ce3ed510d3bd0f30e803be6830c0b7463b  ./claude-dir/skills/exit-ticket-generator/SKILL.md
f0476b91b09f2020198ebc96e421b202d09dc39832953387e6eb97747c0be63d  ./claude-dir/skills/lab-creator/SKILL.md
b646f3dfdaddb4b8fe787d03ac803e8a3746027f69c7218416af2190ab11e9db  ./claude-dir/skills/reading-generator/SKILL.md
f0c429d5d82a74d47a17d3a745ca62cbf266ded893250a863b13939da363a927  ./claude-dir/skills/rubric-converter/SKILL.md
```
