<!-- markdownlint-disable MD024 -->

# Deep Agents Changelog

## [0.8.0](https://github.com/shantanusharma/deepagents/compare/deepagents==0.7.40...deepagents==0.8.0) (2026-11-20)


### ⚠ BREAKING CHANGES

* **sdk,code,quickjs:** make the `ToDoListMiddleware` list opt-in ([#4929](https://github.com/shantanusharma/deepagents/issues/4929))
* **sdk:** remove deprecated backend compatibility shims ([#4541](https://github.com/shantanusharma/deepagents/issues/4541))
* **sdk:** disambiguate `read_file` line gutters ([#4561](https://github.com/shantanusharma/deepagents/issues/4561))
* **sdk:** Agents can now overwrite existing files with `write_file` instead of receiving a file-exists error. Workflows, prompts, tests, or guardrails that relied on that error to force `edit_file` usage or to protect existing content must add explicit permission/HITL checks or use `edit_file` when preserving existing content matters.
* **sdk:** Agents now see a destructive `delete` filesystem tool when the backend supports it. Existing agents may choose to remove files or directories recursively, and existing filesystem permission rules that allow writes can now authorize deletion unless a narrower deny or interrupt rule blocks the target subtree.
* **sdk:** v0.6 ([#3193](https://github.com/shantanusharma/deepagents/issues/3193))
* **sdk:** move sandbox provider back to cli ([#1226](https://github.com/shantanusharma/deepagents/issues/1226))
* **deepagents:** add async implementations for backend, sandbox, filesystem ([#504](https://github.com/shantanusharma/deepagents/issues/504))

* **sdk:** move sandbox provider back to cli ([#1226](https://github.com/shantanusharma/deepagents/issues/1226)) ([c6dedbf](https://github.com/shantanusharma/deepagents/commit/c6dedbf9a827164b81c19435e372cc6db8f7ce13))
* **sdk:** remove deprecated backend compatibility shims ([#4541](https://github.com/shantanusharma/deepagents/issues/4541)) ([540a0fa](https://github.com/shantanusharma/deepagents/commit/540a0fa7eb9a88d82413cf10a5cb5c807d491385))


### feature

* **deepagents:** add async implementations for backend, sandbox, filesystem ([#504](https://github.com/shantanusharma/deepagents/issues/504)) ([99d5341](https://github.com/shantanusharma/deepagents/commit/99d534123aa1f6be5f30d683b1d183aadae33fd7))


### Features

* add ability to paste images in input ([#555](https://github.com/shantanusharma/deepagents/issues/555)) ([e7b8b80](https://github.com/shantanusharma/deepagents/commit/e7b8b808f52deb98da3582b1100bb787c2ec2eb7))
* add agent name when creating subagents ([#735](https://github.com/shantanusharma/deepagents/issues/735)) ([05a34a7](https://github.com/shantanusharma/deepagents/commit/05a34a75466e3807b03fd68114c6a26ddeff3875))
* **cli,sdk:** compaction hook ([#1420](https://github.com/shantanusharma/deepagents/issues/1420)) ([e87cdad](https://github.com/shantanusharma/deepagents/commit/e87cdaddb9a984c4fd189b4f71303881edb32cb2))
* **cli:** `--acp` mode to run CLI agent as ACP server ([#1297](https://github.com/shantanusharma/deepagents/issues/1297)) ([c9ba00a](https://github.com/shantanusharma/deepagents/commit/c9ba00a56b7ee5e48b56b13f9f093bb8bf639700))
* **cli:** `/compact` command ([#1579](https://github.com/shantanusharma/deepagents/issues/1579)) ([46e9e95](https://github.com/shantanusharma/deepagents/commit/46e9e950087e973175d49d6a863cfa9d2f241528))
* **cli:** custom subagents ([#916](https://github.com/shantanusharma/deepagents/issues/916)) ([4a630e8](https://github.com/shantanusharma/deepagents/commit/4a630e88d6e433cb60687d21cafb0641ba31d497))
* **cli:** inject local context into system prompt via `LocalContextMiddleware` ([aaab491](https://github.com/shantanusharma/deepagents/commit/aaab491b90c21a64c00fc7a25946c2e5e655b329))
* **code,sdk:** add rubric iteration controls ([#4405](https://github.com/shantanusharma/deepagents/issues/4405)) ([d6692a7](https://github.com/shantanusharma/deepagents/commit/d6692a7c713490f170b17510d613e02ee37574ab))
* **code:** add Claude Opus 5 support ([#5049](https://github.com/shantanusharma/deepagents/issues/5049)) ([c0afec5](https://github.com/shantanusharma/deepagents/commit/c0afec5ab7e9860d1572002c1f689f95dd15cf8e))
* **deepagents:** add skills to sdk ([#591](https://github.com/shantanusharma/deepagents/issues/591)) ([75ec1fc](https://github.com/shantanusharma/deepagents/commit/75ec1fc4c2cbd20a11c5ec09eb1ce3932cdce3b6))
* **deepagents:** truncate middle of content instead of end on tool response eviction ([#901](https://github.com/shantanusharma/deepagents/issues/901)) ([90a3515](https://github.com/shantanusharma/deepagents/commit/90a35158ac05f020fafe35d9e4b5b7ddafa3e204))
* **deepagents:** truncate old write / edit calls in message history ([#806](https://github.com/shantanusharma/deepagents/issues/806)) ([2b58cb8](https://github.com/shantanusharma/deepagents/commit/2b58cb844067ae64ea050d82ed5ff93c2bb60c53))
* **deepagents:** truncate tool messages from read_file ([#897](https://github.com/shantanusharma/deepagents/issues/897)) ([d068ec7](https://github.com/shantanusharma/deepagents/commit/d068ec771679c94411f4d8f724dc25e680b062ed))
* **deepagents:** use context window fractions for SummarizationMiddleware when available ([#484](https://github.com/shantanusharma/deepagents/issues/484)) ([deec90d](https://github.com/shantanusharma/deepagents/commit/deec90db1cae749d7aaf42a1e3c3d69f59ae122a))
* expose id on base abstraction ([#382](https://github.com/shantanusharma/deepagents/issues/382)) ([d2edf7c](https://github.com/shantanusharma/deepagents/commit/d2edf7c0d399c9b9d27f4e68a561247e4f7ec31c))
* **infra:** add fireworks as eval provider ([#1684](https://github.com/shantanusharma/deepagents/issues/1684)) ([eb26f61](https://github.com/shantanusharma/deepagents/commit/eb26f61cbceaeffef3414b402d28cac7af3e3a9a))
* **quickjs:** add swarm task tool ([#3472](https://github.com/shantanusharma/deepagents/issues/3472)) ([2c28b7b](https://github.com/shantanusharma/deepagents/commit/2c28b7b8c2ac7571fc3a1f0d8d00f5697fe3e90e))
* **quickjs:** rename middleware ([#3334](https://github.com/shantanusharma/deepagents/issues/3334)) ([fc80075](https://github.com/shantanusharma/deepagents/commit/fc80075c65c3b4beb8f672b6bb27464fee6d79c2))
* sandbox protocol ([#319](https://github.com/shantanusharma/deepagents/issues/319)) ([460c49b](https://github.com/shantanusharma/deepagents/commit/460c49b82f5e2a3e8a3ebab14d1b380c9f94ef16))
* **sdk,cli:** add openrouter SDK attribution ([#2205](https://github.com/shantanusharma/deepagents/issues/2205)) ([2798e51](https://github.com/shantanusharma/deepagents/commit/2798e51fd90128ffd1a2064383db17c699805395))
* **sdk,cli:** add package version metadata to traces ([#2129](https://github.com/shantanusharma/deepagents/issues/2129)) ([e4a44b4](https://github.com/shantanusharma/deepagents/commit/e4a44b467dee1e284ebe741a0e568f2dc613e068))
* **sdk,code,quickjs:** lean system prompt by default, restorable ([#4859](https://github.com/shantanusharma/deepagents/issues/4859)) ([a8d1b32](https://github.com/shantanusharma/deepagents/commit/a8d1b32aa4136d0498ba7b48367c8001ac462bd0))
* **sdk,code,quickjs:** make the `ToDoListMiddleware` list opt-in ([#4929](https://github.com/shantanusharma/deepagents/issues/4929)) ([9340518](https://github.com/shantanusharma/deepagents/commit/9340518a26c4287f9ad0c543edc9b69106c15154))
* **sdk,code:** update `read_file` output formatting ([#5648](https://github.com/shantanusharma/deepagents/issues/5648)) ([276beca](https://github.com/shantanusharma/deepagents/commit/276becae1bbaa38d6253aee90e99212e7bdf0606))
* **sdk:** `BASE_AGENT_PROMPT` tweaks ([#2541](https://github.com/shantanusharma/deepagents/issues/2541)) ([812eef1](https://github.com/shantanusharma/deepagents/commit/812eef185ffda7bc9e6f11425eb5eddc3d3b32e8))
* **sdk:** `ls_agent_type` configurable tag on subagent runs ([#2788](https://github.com/shantanusharma/deepagents/issues/2788)) ([3bcc51a](https://github.com/shantanusharma/deepagents/commit/3bcc51a95da80094cfc8bc4bcaf25dc1e2ad8f44))
* **sdk:** `RubricMiddleware` for self-evaluated agent iteration ([#3529](https://github.com/shantanusharma/deepagents/issues/3529)) ([5b8d44d](https://github.com/shantanusharma/deepagents/commit/5b8d44d65c6ec43084687019cf00a37d730ac2fa))
* **sdk:** add `artifacts_root` to `CompositeBackend` and middleware ([#2490](https://github.com/shantanusharma/deepagents/issues/2490)) ([753ee56](https://github.com/shantanusharma/deepagents/commit/753ee567f1cc4d544dc2afea7b414564fd07d37d))
* **sdk:** add `ContextHubBackend` backend type ([#3338](https://github.com/shantanusharma/deepagents/issues/3338)) ([6962826](https://github.com/shantanusharma/deepagents/commit/69628263cb2c1f6951b1b37bbc0edbb85983ad51))
* **sdk:** add `enabled_tools` allowlist to `FilesystemMiddleware` ([#4325](https://github.com/shantanusharma/deepagents/issues/4325)) ([704a70d](https://github.com/shantanusharma/deepagents/commit/704a70dddbd59b8c6abf658a4211c76bce1445f0))
* **sdk:** add `notify_parent` to `AsyncSubAgent` ([#7132](https://github.com/shantanusharma/deepagents/issues/7132)) ([3ae25ff](https://github.com/shantanusharma/deepagents/commit/3ae25ff85f94f15815c377e73841173a722299d6))
* **sdk:** add `subagent_model` param to `create_deep_agent` ([#1369](https://github.com/shantanusharma/deepagents/issues/1369)) ([40f9620](https://github.com/shantanusharma/deepagents/commit/40f96208e64aec1feaa0e9b8a78ea53e0af04719))
* **sdk:** add `system_prompt` override slot to memory, skills, and summarization ([#3451](https://github.com/shantanusharma/deepagents/issues/3451)) ([7583f4a](https://github.com/shantanusharma/deepagents/commit/7583f4aff6a6044bc987ee7980d322bb5c791428))
* **sdk:** add `webhook` to `AsyncSubAgent` ([#7072](https://github.com/shantanusharma/deepagents/issues/7072)) ([7a7c4e3](https://github.com/shantanusharma/deepagents/commit/7a7c4e3708981568f96eb7fbc86aaef696c03001))
* **sdk:** add async subagent middleware for remote LangGraph servers ([#1758](https://github.com/shantanusharma/deepagents/issues/1758)) ([0c5d501](https://github.com/shantanusharma/deepagents/commit/0c5d501066e7e9cb74737740d9b3c1dfc74751a6))
* **sdk:** add base agent prompt ([#1314](https://github.com/shantanusharma/deepagents/issues/1314)) ([74ddcbf](https://github.com/shantanusharma/deepagents/commit/74ddcbffa781ff8a6cfb34cbb1cc19ea541176f3))
* **sdk:** add Bedrock prompt caching middleware ([#4108](https://github.com/shantanusharma/deepagents/issues/4108)) ([a398382](https://github.com/shantanusharma/deepagents/commit/a398382c85ce518ea1b7f365e49df905cdcd498b))
* **sdk:** add factory function for summarization tool middleware ([#1749](https://github.com/shantanusharma/deepagents/issues/1749)) ([282b4c2](https://github.com/shantanusharma/deepagents/commit/282b4c209bde73632392cd8453e9c7430a9cbef3))
* **sdk:** add GPT-5.5 harness profile ([#3082](https://github.com/shantanusharma/deepagents/issues/3082)) ([73bc9cc](https://github.com/shantanusharma/deepagents/commit/73bc9ccc0f66ad72ce90c5efcc5a4fbf2331db37))
* **sdk:** add interrupt mode to filesystem permissions ([#3505](https://github.com/shantanusharma/deepagents/issues/3505)) ([a090162](https://github.com/shantanusharma/deepagents/commit/a090162ea9fd950c54fac874b8a165ca770fd2dc))
* **sdk:** Add LangSmith integration metadata to deepagents ([#1837](https://github.com/shantanusharma/deepagents/issues/1837)) ([0e572ff](https://github.com/shantanusharma/deepagents/commit/0e572ff4ac296c52ea0ec450a1410671b0287cd4))
* **sdk:** add LocalShellBackend ([#930](https://github.com/shantanusharma/deepagents/issues/930)) ([b45fbfd](https://github.com/shantanusharma/deepagents/commit/b45fbfd4dacfae1d0772c2b21e6b87cccd47e698))
* **sdk:** add MemoryAgentBench evaluation suite ([#1807](https://github.com/shantanusharma/deepagents/issues/1807)) ([6a0763d](https://github.com/shantanusharma/deepagents/commit/6a0763d301b6d66813f7168abc300243e0a4d1ea))
* **sdk:** add notification metadata to async subagent notifications ([#7334](https://github.com/shantanusharma/deepagents/issues/7334)) ([6b9e9c9](https://github.com/shantanusharma/deepagents/commit/6b9e9c9f9088deab6d1c3f12c3c9626605d803a2))
* **sdk:** add NVIDIA Nemotron 3 Ultra harness profile ([#4192](https://github.com/shantanusharma/deepagents/issues/4192)) ([d5a60ec](https://github.com/shantanusharma/deepagents/commit/d5a60ece7379c37c81edcef2cd6c2811ddc90c9a))
* **sdk:** add NVIDIA NIM app-origin attribution ([#4455](https://github.com/shantanusharma/deepagents/issues/4455)) ([4cb4749](https://github.com/shantanusharma/deepagents/commit/4cb47491b024991322b7c24062c58cbcdc26a727))
* **sdk:** add per-command `timeout` override to `execute()` ([#1154](https://github.com/shantanusharma/deepagents/issues/1154)) ([49277d4](https://github.com/shantanusharma/deepagents/commit/49277d45a026c86b5bf176142dcb1dfc2c7643ae))
* **sdk:** add permissions system for filesystem access control ([#2633](https://github.com/shantanusharma/deepagents/issues/2633)) ([41dc759](https://github.com/shantanusharma/deepagents/commit/41dc7597deb3fc036f1f850e68edc3c0870f27da))
* **sdk:** add prompt guidance for large tool results ([#1763](https://github.com/shantanusharma/deepagents/issues/1763)) ([3d3cb3c](https://github.com/shantanusharma/deepagents/commit/3d3cb3c31ca7ec5a98426f68335ec8d810a90015))
* **sdk:** add recursive filesystem delete support ([f2a21ec](https://github.com/shantanusharma/deepagents/commit/f2a21ec1606c2560bd2fd5765409a05c2a44edee))
* **sdk:** add rubric grader integration hooks ([#5874](https://github.com/shantanusharma/deepagents/issues/5874)) ([07c0340](https://github.com/shantanusharma/deepagents/commit/07c0340bc41e3717f1cd73705b71f1f6a87d753f))
* **sdk:** add sandbox provider exceptions ([#1108](https://github.com/shantanusharma/deepagents/issues/1108)) ([390c2bf](https://github.com/shantanusharma/deepagents/commit/390c2bff35e83657771df51d54207a84f9a7c14b))
* **sdk:** add static structured output to subagent response ([#2437](https://github.com/shantanusharma/deepagents/issues/2437)) ([6e57731](https://github.com/shantanusharma/deepagents/commit/6e57731fc6d908ac1ebe131e782696a4776147e9))
* **sdk:** add subagent conversation forking ([#5714](https://github.com/shantanusharma/deepagents/issues/5714)) ([6b4427f](https://github.com/shantanusharma/deepagents/commit/6b4427f07dc35a0b61cf8224db090ea6bee6f72f))
* **sdk:** add timestamp tracking to `AsyncSubAgentJob` ([#2071](https://github.com/shantanusharma/deepagents/issues/2071)) ([93aa3cf](https://github.com/shantanusharma/deepagents/commit/93aa3cf16dedeec7d97834d5ea6dcd65cd4c6256))
* **sdk:** add total match cap and streaming to grep ([#4570](https://github.com/shantanusharma/deepagents/issues/4570)) ([8e86f5e](https://github.com/shantanusharma/deepagents/commit/8e86f5ecc8908762a2c748880287f190dde70600))
* **sdk:** allow `FilesystemMiddleware` to store blobs on backend ([#6550](https://github.com/shantanusharma/deepagents/issues/6550)) ([e38e6c9](https://github.com/shantanusharma/deepagents/commit/e38e6c91def8067e0dec2694d5410d0306f32553))
* **sdk:** allow `write_file` to overwrite existing files ([2506fcc](https://github.com/shantanusharma/deepagents/commit/2506fccfac0e09b656d5e2fefe23162f1c762331))
* **sdk:** allow passing `state_schema` in `create_deep_agent` ([#3642](https://github.com/shantanusharma/deepagents/issues/3642)) ([37839bd](https://github.com/shantanusharma/deepagents/commit/37839bd7d67fba8c11ff0ccaaa8ac92b39609450))
* **sdk:** allow users to override default middleware by name ([#4251](https://github.com/shantanusharma/deepagents/issues/4251)) ([90c8472](https://github.com/shantanusharma/deepagents/commit/90c8472ae226394a186bf2075459645c2056db7d))
* **sdk:** bound grep/glob with partial results and a `truncated` flag ([#4063](https://github.com/shantanusharma/deepagents/issues/4063)) ([ef591e7](https://github.com/shantanusharma/deepagents/commit/ef591e7a86b13bbdcb0fdedd45a8f1fe33573839))
* **sdk:** deprecate `model=None` in `create_deep_agent` ([#2677](https://github.com/shantanusharma/deepagents/issues/2677)) ([149df41](https://github.com/shantanusharma/deepagents/commit/149df415d17f3cf3b7eb0bd1e78460112bfa9b04))
* **sdk:** disable tracing inputs on middleware ([#5377](https://github.com/shantanusharma/deepagents/issues/5377)) ([0aade99](https://github.com/shantanusharma/deepagents/commit/0aade99211dc45cc85ce8b95fc375612f982b48a))
* **sdk:** enable type checking in deepagents and resolve most linting issues ([#991](https://github.com/shantanusharma/deepagents/issues/991)) ([5c90376](https://github.com/shantanusharma/deepagents/commit/5c90376c02754c67d448908e55d1e953f54b8acd))
* **sdk:** evict large HumanMessages ([#2183](https://github.com/shantanusharma/deepagents/issues/2183)) ([4f72c34](https://github.com/shantanusharma/deepagents/commit/4f72c34221aea0516738be566de0fffc2c7386ac))
* **sdk:** expose `execute` exit code in artifact ([#5300](https://github.com/shantanusharma/deepagents/issues/5300)) ([de8bfca](https://github.com/shantanusharma/deepagents/commit/de8bfca8255d673c1e7860e8c158ed119238197e))
* **sdk:** expose `summarizer` on summarization middleware ([#6900](https://github.com/shantanusharma/deepagents/issues/6900)) ([4b955e8](https://github.com/shantanusharma/deepagents/commit/4b955e844f09ccb0f546644ae705e9fc3b9928b0))
* **sdk:** expose execution output retention metadata ([#6876](https://github.com/shantanusharma/deepagents/issues/6876)) ([8b8e70a](https://github.com/shantanusharma/deepagents/commit/8b8e70a1c5858e44cc4b8e7c499265c90a8c5786))
* **sdk:** hand the agent's backend to middleware that ask for it ([#7668](https://github.com/shantanusharma/deepagents/issues/7668)) ([d9c2af4](https://github.com/shantanusharma/deepagents/commit/d9c2af40ea4ab8729e4a9a0fc4f70070b000ff47))
* **sdk:** improve system prompt configurability ([#4437](https://github.com/shantanusharma/deepagents/issues/4437)) ([56c5a5e](https://github.com/shantanusharma/deepagents/commit/56c5a5e0e64cabe5fbe27308d3ddfd8a8fd9eb22))
* **sdk:** load a skill's tools only when the skill is read ([#6552](https://github.com/shantanusharma/deepagents/issues/6552)) ([92cd8e7](https://github.com/shantanusharma/deepagents/commit/92cd8e7fa8b1f8da346ec91e420a820518497f2c))
* **sdk:** log when grep falls back from ripgrep ([#3593](https://github.com/shantanusharma/deepagents/issues/3593)) ([379b1ff](https://github.com/shantanusharma/deepagents/commit/379b1ffdc3ccf5da72d9f7264d531be108f0b36d))
* **sdk:** mark editable installs in `lc_versions.deepagents` ([#5158](https://github.com/shantanusharma/deepagents/issues/5158)) ([ee7ac3d](https://github.com/shantanusharma/deepagents/commit/ee7ac3d47980e4037403bfea1a13b7b51e06fb4a))
* **sdk:** namespace improvements for deepagents ([#2386](https://github.com/shantanusharma/deepagents/issues/2386)) ([66c57e1](https://github.com/shantanusharma/deepagents/commit/66c57e1e33e21d5ed0b7ceaa615b0e1c27ac556b))
* **sdk:** nest async subagent runs under the parent's trace ([#6823](https://github.com/shantanusharma/deepagents/issues/6823)) ([3cd9463](https://github.com/shantanusharma/deepagents/commit/3cd94633d3fe5d434fbf492d64f6f53a3e6dcafe))
* **sdk:** optional video frame extraction on `read_file` ([#4094](https://github.com/shantanusharma/deepagents/issues/4094)) ([b927147](https://github.com/shantanusharma/deepagents/commit/b927147d026749c6c790bb06c9853515dabf579c))
* **sdk:** pin skills by name via `pinned_skills` ([#6810](https://github.com/shantanusharma/deepagents/issues/6810)) ([7022633](https://github.com/shantanusharma/deepagents/commit/70226333bac013b1b1e37acedfb7955f7e6cd6f8))
* **sdk:** port `LangSmithSandbox` from CLI to SDK ([#1983](https://github.com/shantanusharma/deepagents/issues/1983)) ([dfff6e7](https://github.com/shantanusharma/deepagents/commit/dfff6e7d2f91c269290ab677a9bd7454bc2f4989))
* **sdk:** queue async subagent follow-ups without interrupting active work ([#7082](https://github.com/shantanusharma/deepagents/issues/7082)) ([a7e1e25](https://github.com/shantanusharma/deepagents/commit/a7e1e2575c1e96b721a0a3e0ecde6e85612ac30d))
* **sdk:** raise on model refusals by default and report subagent refusals to the parent ([#7512](https://github.com/shantanusharma/deepagents/issues/7512)) ([0fd438a](https://github.com/shantanusharma/deepagents/commit/0fd438a4b952efcc13a4f599d2d7699dd6966f2d))
* **sdk:** read inline skill tool support from model profiles ([#6879](https://github.com/shantanusharma/deepagents/issues/6879)) ([f5d9c31](https://github.com/shantanusharma/deepagents/commit/f5d9c31163dda54898bdb4f73a2580c9430a16d5))
* **sdk:** record the `task` call id on subagent checkpoints ([#7509](https://github.com/shantanusharma/deepagents/issues/7509)) ([213f034](https://github.com/shantanusharma/deepagents/commit/213f0345fbd2dc1b09b9595028df9cc8682cc270))
* **sdk:** record the subagent's checkpoint namespace on the `task` tool message ([#7580](https://github.com/shantanusharma/deepagents/issues/7580)) ([7eee174](https://github.com/shantanusharma/deepagents/commit/7eee17462177b7079940587523af01f315edfd46))
* **sdk:** reduce round trips when offloading large tool results with `sandbox.execute` ([#4230](https://github.com/shantanusharma/deepagents/issues/4230)) ([02f5bd7](https://github.com/shantanusharma/deepagents/commit/02f5bd7bc02f2baaf5a1eefce7d686ba62493647))
* **sdk:** refactor namespace gen for StoreBackend ([#1169](https://github.com/shantanusharma/deepagents/issues/1169)) ([2177fcd](https://github.com/shantanusharma/deepagents/commit/2177fcd0a779cee4abc71470dbe4c63d9a086579))
* **sdk:** reimplement skill loading via `skill` tool calling ([#1306](https://github.com/shantanusharma/deepagents/issues/1306)) ([4a57f0f](https://github.com/shantanusharma/deepagents/commit/4a57f0f716df02f1d6282645df418275aee6d146))
* **sdk:** reload skills when `skills_metadata` is reset to `None` ([#6364](https://github.com/shantanusharma/deepagents/issues/6364)) ([f86b4e9](https://github.com/shantanusharma/deepagents/commit/f86b4e9abef7620b63a7258bc9fab0ccd83de8a4))
* **sdk:** rename backend methods ([#1907](https://github.com/shantanusharma/deepagents/issues/1907)) ([7665066](https://github.com/shantanusharma/deepagents/commit/7665066c093c2583c4cd3bf83515b0906277306f))
* **sdk:** report async subagents that are waiting for a human ([#6842](https://github.com/shantanusharma/deepagents/issues/6842)) ([825acb3](https://github.com/shantanusharma/deepagents/commit/825acb3ca03bd103e4df6013b122eca8475d1982))
* **sdk:** report remaining lines for paginated reads ([#4540](https://github.com/shantanusharma/deepagents/issues/4540)) ([8321194](https://github.com/shantanusharma/deepagents/commit/83211940a2cdf4c52ac21a6cde8647716a998504))
* **sdk:** return native image content blocks from read_file ([#1163](https://github.com/shantanusharma/deepagents/issues/1163)) ([65600b1](https://github.com/shantanusharma/deepagents/commit/65600b1c295ae85e0901f6c4b0b88aa5081d6103))
* **sdk:** sandbox provider interface ([#900](https://github.com/shantanusharma/deepagents/issues/900)) ([d431cfd](https://github.com/shantanusharma/deepagents/commit/d431cfd4a56713434e84f4fa1cdf4a160b43db95))
* **sdk:** scope permissions to routes for composite backends with sandbox default ([#2659](https://github.com/shantanusharma/deepagents/issues/2659)) ([6dd6122](https://github.com/shantanusharma/deepagents/commit/6dd612237a7ee707726c4cafc4b691704e4cdb37))
* **sdk:** subagent skills, middleware refactor ([#1041](https://github.com/shantanusharma/deepagents/issues/1041)) ([db0e8f4](https://github.com/shantanusharma/deepagents/commit/db0e8f480c86cc7fb1aa23ab051cc7853e831d2f))
* **sdk:** support configurable subagent response format ([#3882](https://github.com/shantanusharma/deepagents/issues/3882)) ([b0e4d7a](https://github.com/shantanusharma/deepagents/commit/b0e4d7aa8d0ad58c65bddef3835e539b3d5b2a99))
* **sdk:** support fork mode for async subagents ([#6739](https://github.com/shantanusharma/deepagents/issues/6739)) ([c31c7fd](https://github.com/shantanusharma/deepagents/commit/c31c7fd89d0b7cf77af292f5629cc4929d51e429))
* **sdk:** support surrounding lines in filesystem grep results ([#4706](https://github.com/shantanusharma/deepagents/issues/4706)) ([65230df](https://github.com/shantanusharma/deepagents/commit/65230df6f91d2bbe5f83d4d938da6bfac52363a1))
* **sdk:** surface subagents via inherited lc_agent_name projection ([#3644](https://github.com/shantanusharma/deepagents/issues/3644)) ([e0a1ed2](https://github.com/shantanusharma/deepagents/commit/e0a1ed24e6b44c31d0aac3358aeee0d6cb66b2c4))
* **sdk:** tell async subagents which agent launched them ([#6836](https://github.com/shantanusharma/deepagents/issues/6836)) ([168ac6b](https://github.com/shantanusharma/deepagents/commit/168ac6b7054edec7eb4c1923059cbaec67a7f5c1))
* **sdk:** tell the main agent about async subagent status updates ([#6853](https://github.com/shantanusharma/deepagents/issues/6853)) ([9cf009b](https://github.com/shantanusharma/deepagents/commit/9cf009bb21b6bf3578f94555ac4ebfbc59d4e500))
* **sdk:** trim built-in tool descriptions ([#5009](https://github.com/shantanusharma/deepagents/issues/5009)) ([761f5f0](https://github.com/shantanusharma/deepagents/commit/761f5f0882dee186f2700f3c903829a5542626fe))
* **sdk:** update backend return types for ls, glob, grep ([#1870](https://github.com/shantanusharma/deepagents/issues/1870)) ([23cf264](https://github.com/shantanusharma/deepagents/commit/23cf264d0d9784cfce8f8720b125c6ed05a2e2c3))
* **sdk:** update FileData and backend.read return type to support multimodal data ([#1869](https://github.com/shantanusharma/deepagents/issues/1869)) ([6fb4ede](https://github.com/shantanusharma/deepagents/commit/6fb4ede894fe5333ea11598468e924442b3b48a7))
* **sdk:** use `FireworksPromptCachingMiddleware` for session affinity ([#4598](https://github.com/shantanusharma/deepagents/issues/4598)) ([5d878bf](https://github.com/shantanusharma/deepagents/commit/5d878bf1341afc3f96398733b7ef18eec4b66139))
* **sdk:** v0.6 ([#3193](https://github.com/shantanusharma/deepagents/issues/3193)) ([4db09ac](https://github.com/shantanusharma/deepagents/commit/4db09acba34b38521192b8f278723524be560779))
* show allowed tools for each skill in skill list ([#837](https://github.com/shantanusharma/deepagents/issues/837)) ([ce73102](https://github.com/shantanusharma/deepagents/commit/ce73102f3d7490d40b9d1d4991a39cbafb143a26))
* summarization offloading ([#742](https://github.com/shantanusharma/deepagents/issues/742)) ([d46e0b8](https://github.com/shantanusharma/deepagents/commit/d46e0b8db45910eae90ba242cb81316c34861b49))
* support `SystemMessage` for parity w/ `create_agent` ([#803](https://github.com/shantanusharma/deepagents/issues/803)) ([00b4040](https://github.com/shantanusharma/deepagents/commit/00b404021599b09fcf52496f7010a0be908445ec))
* update memory prompt to be more barebones ([#685](https://github.com/shantanusharma/deepagents/issues/685)) ([df83e65](https://github.com/shantanusharma/deepagents/commit/df83e65d7c3e80092f6b49ea05cca4282c2325c4))


### Bug Fixes

* add py.typed to deepagents ([#1024](https://github.com/shantanusharma/deepagents/issues/1024)) ([2a21f9e](https://github.com/shantanusharma/deepagents/commit/2a21f9e63bcb48180628fbc647168a7290cc726a))
* added error catching for file operations without permissions ([#734](https://github.com/shantanusharma/deepagents/issues/734)) ([35a41ca](https://github.com/shantanusharma/deepagents/commit/35a41ca3a0773ad967c9b646a245d9ae6cf4f995))
* **cli,sdk:** harden path hardening ([#918](https://github.com/shantanusharma/deepagents/issues/918)) ([fc34a14](https://github.com/shantanusharma/deepagents/commit/fc34a144a2791c75f8b4c11f67dd1adbc029c81e))
* **cli:** prevent stdin hang by passing `DEVNULL` ([#2427](https://github.com/shantanusharma/deepagents/issues/2427)) ([5bf5fae](https://github.com/shantanusharma/deepagents/commit/5bf5fae8d93beba90628f2f71e3e79817a36ac9e))
* **code:** persist `_context_tokens` via `after_model` middleware ([#3496](https://github.com/shantanusharma/deepagents/issues/3496)) ([e2bb284](https://github.com/shantanusharma/deepagents/commit/e2bb284e506e0e49a05169fc6de01bdf42350267))
* **daytona:** fix execute implementation ([#1756](https://github.com/shantanusharma/deepagents/issues/1756)) ([080f3a5](https://github.com/shantanusharma/deepagents/commit/080f3a5ce6de137209702e04e03a506242263a93))
* **deepagents:** better async support in skills, and propagate runnable config ([#672](https://github.com/shantanusharma/deepagents/issues/672)) ([fe3e4f9](https://github.com/shantanusharma/deepagents/commit/fe3e4f902d8c82df158c38549ba9d9fad5326cb1))
* **deepagents:** composite backend grep implementation ([#659](https://github.com/shantanusharma/deepagents/issues/659)) ([721f85a](https://github.com/shantanusharma/deepagents/commit/721f85aa5c846d0ff4f69dd8cf561d101022aa92))
* **deepagents:** exclude structured response from state update ([#603](https://github.com/shantanusharma/deepagents/issues/603)) ([d27751f](https://github.com/shantanusharma/deepagents/commit/d27751f932b4e4e467bbeaf7702901dac03c1687))
* **deepagents:** fix content block handling in filesystem middleware tool result eviction ([#674](https://github.com/shantanusharma/deepagents/issues/674)) ([a046df0](https://github.com/shantanusharma/deepagents/commit/a046df0240eb441f36297e4ff56c80bc05163326))
* **deepagents:** Fix Memory prompt guidelines that could lead to wrong actions ([#1448](https://github.com/shantanusharma/deepagents/issues/1448)) ([ac47036](https://github.com/shantanusharma/deepagents/commit/ac470364bc869cf93df6da2635fbfb142bf3a256))
* **deepagents:** fix type for file info ([#471](https://github.com/shantanusharma/deepagents/issues/471)) ([381b959](https://github.com/shantanusharma/deepagents/commit/381b959fbdd3904d80d0a8fa6cb46ab6ec833109))
* **deepagents:** make memory permissive if AGENTS.md not found ([#682](https://github.com/shantanusharma/deepagents/issues/682)) ([ccb767e](https://github.com/shantanusharma/deepagents/commit/ccb767e7e7f74c542870454c768365ac7ee8f0df))
* **deepagents:** Pass through runtime config to subagents ([#602](https://github.com/shantanusharma/deepagents/issues/602)) ([d4901e2](https://github.com/shantanusharma/deepagents/commit/d4901e2a00d91a9bf049db356dbbd98000a70e9e))
* **deepagents:** preserve ToolMessage artifact when evicting large outputs ([#1482](https://github.com/shantanusharma/deepagents/issues/1482)) ([026b792](https://github.com/shantanusharma/deepagents/commit/026b7928e0d01d0b7610d2bed7ce0f310e4f51db))
* **deepagents:** prevent state merge error in parallel sub-agents ([#954](https://github.com/shantanusharma/deepagents/issues/954)) ([fbb659c](https://github.com/shantanusharma/deepagents/commit/fbb659c1ea1bf77b40557865fd7a2b833edb48b2))
* **deepagents:** refactor summarization middleware ([#1138](https://github.com/shantanusharma/deepagents/issues/1138)) ([e87001e](https://github.com/shantanusharma/deepagents/commit/e87001eace2852c2df47095ffd2611f09fdda2f5))
* **deepagents:** respect continuation markers when reading files ([#809](https://github.com/shantanusharma/deepagents/issues/809)) ([77b6580](https://github.com/shantanusharma/deepagents/commit/77b6580a7de9790a8cb5cfc07d47bac56a2f24cd))
* **deepagents:** restore full routed path in write/edit results ([#1681](https://github.com/shantanusharma/deepagents/issues/1681)) ([8a00369](https://github.com/shantanusharma/deepagents/commit/8a00369010cf3b37b0f45a92575f0cd8ba4383d5))
* **deepagents:** strip trailing whitespace from subagent messages to prevent Anthropic API errors ([#586](https://github.com/shantanusharma/deepagents/issues/586)) ([8e98984](https://github.com/shantanusharma/deepagents/commit/8e9898435401cae3ff7d1e5bd829dd31a83b7703))
* **deepagents:** throw a clear exception message when 'messages' key missing from the output of the subagent ([#678](https://github.com/shantanusharma/deepagents/issues/678)) ([f40a076](https://github.com/shantanusharma/deepagents/commit/f40a076ef0a815616f334344d862aeb59405aeb0))
* **deepagents:** truncate lines on read ([#784](https://github.com/shantanusharma/deepagents/issues/784)) ([f86aa96](https://github.com/shantanusharma/deepagents/commit/f86aa96d36190a0c5dc06b8d7a691cb06af5ce30))
* Don't error when "subagent" does not exist. And add test for truncation logic ([#343](https://github.com/shantanusharma/deepagents/issues/343)) ([766c41c](https://github.com/shantanusharma/deepagents/commit/766c41cf7eb9c413f405aa6f493d87ae137630be))
* fix docstring formatting errors in backends ([#514](https://github.com/shantanusharma/deepagents/issues/514)) ([6947cc0](https://github.com/shantanusharma/deepagents/commit/6947cc02b1835a46b8d4f1e5d081af76850bf08e))
* import rules ([#763](https://github.com/shantanusharma/deepagents/issues/763)) ([2c54297](https://github.com/shantanusharma/deepagents/commit/2c54297054ae68b2a98673d2f58d44652815467b))
* **infra:** change `release-please` component ([#1002](https://github.com/shantanusharma/deepagents/issues/1002)) ([cb572b9](https://github.com/shantanusharma/deepagents/commit/cb572b941f94b910cc5b5a49b93f246cd0eb02fa))
* **infra:** exclude `build/` from typechecking ([#808](https://github.com/shantanusharma/deepagents/issues/808)) ([476071c](https://github.com/shantanusharma/deepagents/commit/476071c9d46486b7203357809569839cb853de5d))
* **langsmith-sandbox:** sandbox glob path boundary checks ([#4588](https://github.com/shantanusharma/deepagents/issues/4588)) ([c6c7213](https://github.com/shantanusharma/deepagents/commit/c6c72139b3ee7d090f657dd19ced59a9bbc41140))
* **middleware:** prevent silent corruption from Windows absolute paths (Issue [#427](https://github.com/shantanusharma/deepagents/issues/427)) ([#454](https://github.com/shantanusharma/deepagents/issues/454)) ([d13e341](https://github.com/shantanusharma/deepagents/commit/d13e341c4cb385be5b90dc7e67600a27799266b7))
* no f string needed ([#750](https://github.com/shantanusharma/deepagents/issues/750)) ([8596d46](https://github.com/shantanusharma/deepagents/commit/8596d465a6191608ddd3027b7f2ac5ff526cf077))
* Path Traversal via Unsanitized Glob Pattern in glob_info() Bypasses Virtual Mode Sandbox ([#1322](https://github.com/shantanusharma/deepagents/issues/1322)) ([0802cf0](https://github.com/shantanusharma/deepagents/commit/0802cf014e11b6babf6106ddf234bcd266ba40b0))
* plumb through generics for `create_deep_agent` ([#2383](https://github.com/shantanusharma/deepagents/issues/2383)) ([6c28e22](https://github.com/shantanusharma/deepagents/commit/6c28e22cc5768a82b27102adcea4dbb4b5ae6213))
* remove legacy subagents API ([#2443](https://github.com/shantanusharma/deepagents/issues/2443)) ([56bbfd3](https://github.com/shantanusharma/deepagents/commit/56bbfd3a7c9fc993f7ea6c54d5c54fca234c2273))
* **sdk,acp,harbor:** don't allow relative imports ([#882](https://github.com/shantanusharma/deepagents/issues/882)) ([acc8e3d](https://github.com/shantanusharma/deepagents/commit/acc8e3ddc496c106c833b667833c4a91f28db86e))
* **sdk,cli,deps:** support `timeout=0` for sandbox `execute()` ([#1558](https://github.com/shantanusharma/deepagents/issues/1558)) ([ed14443](https://github.com/shantanusharma/deepagents/commit/ed14443b5aec8afde1f74bb2e12a17cb7d1829b6))
* **sdk,cli:** align error messages and clean up recent refactors ([#2171](https://github.com/shantanusharma/deepagents/issues/2171)) ([e2db737](https://github.com/shantanusharma/deepagents/commit/e2db73779926e1effd6d227e14b137b93393461e))
* **sdk,code:** rename trace version metadata to `lc_versions` ([#3928](https://github.com/shantanusharma/deepagents/issues/3928)) ([27f38c5](https://github.com/shantanusharma/deepagents/commit/27f38c51f960941e102dfc2f9c0220bc16736749))
* **sdk,code:** use `file_path` kwarg in `read_file` examples ([#3630](https://github.com/shantanusharma/deepagents/issues/3630)) ([97946ee](https://github.com/shantanusharma/deepagents/commit/97946ee09eb167c63d8c07f8bb116f40cfc9603f))
* **sdk:** `last_updated_at` field doesn't account for task status changes ([#2370](https://github.com/shantanusharma/deepagents/issues/2370)) ([8e1a2d6](https://github.com/shantanusharma/deepagents/commit/8e1a2d671eda3903d9ebacca4a5e4aa7378646c2))
* **sdk:** `read_file` pagination skipping lines after wrapping ([#3641](https://github.com/shantanusharma/deepagents/issues/3641)) ([390551d](https://github.com/shantanusharma/deepagents/commit/390551d61d57ce68c2a80ed78c07eaa8e985908b))
* **sdk:** accept list format for skill `allowed-tools` ([#4140](https://github.com/shantanusharma/deepagents/issues/4140)) ([d62534c](https://github.com/shantanusharma/deepagents/commit/d62534c86b87a91aca16c6bfb71209232d69a6ec))
* **sdk:** accommodate routes without trailing slash in CompositeBackend ([#7028](https://github.com/shantanusharma/deepagents/issues/7028)) ([0ce837b](https://github.com/shantanusharma/deepagents/commit/0ce837bf69ff0efb10c2fa100039cc0c78a74a11))
* **sdk:** add `files` state only for state backends ([#5643](https://github.com/shantanusharma/deepagents/issues/5643)) ([63c13f3](https://github.com/shantanusharma/deepagents/commit/63c13f3e6bc79a5304e542178ac410b517c64c31))
* **sdk:** add explicit `NotImplementedError` to protocol method bodies ([#1152](https://github.com/shantanusharma/deepagents/issues/1152)) ([82de717](https://github.com/shantanusharma/deepagents/commit/82de717323e3f9b7d431c78f2bdfae01c3491eaa))
* **sdk:** add new line after HEREDOC for edit inline sandbox ([#2340](https://github.com/shantanusharma/deepagents/issues/2340)) ([beb4dbb](https://github.com/shantanusharma/deepagents/commit/beb4dbb6c75700c6969f2c3bfe8f7bf6046ef3bb))
* **sdk:** add newlines in tool result message for large outputs ([#1053](https://github.com/shantanusharma/deepagents/issues/1053)) ([22d4092](https://github.com/shantanusharma/deepagents/commit/22d40920e3cf1d4698f794110697503783b9fdbd))
* **sdk:** add timeout to glob in FilesystemMiddleware ([#1508](https://github.com/shantanusharma/deepagents/issues/1508)) ([2201e11](https://github.com/shantanusharma/deepagents/commit/2201e11b09d616d29618b135d7b51b6ea94adbb4))
* **sdk:** add write preflight and native read to langsmith sandbox ([#2695](https://github.com/shantanusharma/deepagents/issues/2695)) ([741221c](https://github.com/shantanusharma/deepagents/commit/741221c9d8b65a535816e318ee24d3c19a4bde80))
* **sdk:** align `glob` path default with `grep` ([#3666](https://github.com/shantanusharma/deepagents/issues/3666)) ([ece8e75](https://github.com/shantanusharma/deepagents/commit/ece8e752059f493254753194bcf59befe54b3556))
* **sdk:** align `MemoryMiddleware` prompt with investigate-first agent behavior ([#2461](https://github.com/shantanusharma/deepagents/issues/2461)) ([d53c8f4](https://github.com/shantanusharma/deepagents/commit/d53c8f4f481288a3aa04a5e62362beba6ed7e57a))
* **sdk:** allow colons in profile model keys ([#6334](https://github.com/shantanusharma/deepagents/issues/6334)) ([257872e](https://github.com/shantanusharma/deepagents/commit/257872eea59368a0c3aac003f71d3c83ce44c833))
* **sdk:** anchor ripgrep glob to search root ([#3454](https://github.com/shantanusharma/deepagents/issues/3454)) ([e50fa3f](https://github.com/shantanusharma/deepagents/commit/e50fa3f00ab1b1a84bbaed74bf7e89118b7c2d82))
* **sdk:** anchor summarization cutoff by message id ([#7567](https://github.com/shantanusharma/deepagents/issues/7567)) ([de0bef7](https://github.com/shantanusharma/deepagents/commit/de0bef7770a3e30a3a7fea2f333ef68a2e85ef28))
* **sdk:** assign UUIDs to ID-less messages in _messages_delta_reducer ([#3513](https://github.com/shantanusharma/deepagents/issues/3513)) ([6d959ad](https://github.com/shantanusharma/deepagents/commit/6d959ade30655eae3967c9809994434e0bbd1148))
* **sdk:** auto-added GP subagent inherits parent permissions ([#3131](https://github.com/shantanusharma/deepagents/issues/3131)) ([0d55b3b](https://github.com/shantanusharma/deepagents/commit/0d55b3ba8b974d06b1e0f52893f33e44496bff8b))
* **sdk:** avoid deprecated-use warnings in `CompositeBackend` path mutation ([#3244](https://github.com/shantanusharma/deepagents/issues/3244)) ([64d45f6](https://github.com/shantanusharma/deepagents/commit/64d45f67c86edb4df2ced0e7b82f1a8fd158ec8c))
* **sdk:** avoid warning-filter races in `warn_deprecated` ([#7749](https://github.com/shantanusharma/deepagents/issues/7749)) ([c9732c8](https://github.com/shantanusharma/deepagents/commit/c9732c8f1859d65865ea2957f2a685a3769063e6))
* **sdk:** BaseSandbox.ls_info() to return absolute paths ([#797](https://github.com/shantanusharma/deepagents/issues/797)) ([0234039](https://github.com/shantanusharma/deepagents/commit/0234039d49339929ccd5c74f7afe8ba48dc7928c))
* **sdk:** batch concurrent `ContextHubBackend` mutations ([#5471](https://github.com/shantanusharma/deepagents/issues/5471)) ([822f7c9](https://github.com/shantanusharma/deepagents/commit/822f7c9b02e6d99bdb46b5545bb2543783c01769))
* **sdk:** bound compaction recovery and validate input budgets ([#6267](https://github.com/shantanusharma/deepagents/issues/6267)) ([bb6d431](https://github.com/shantanusharma/deepagents/commit/bb6d4316eb59b368b862e5517b888e5e70b1c3ae))
* **sdk:** bound tool offload paths and abbreviate long IDs ([#6519](https://github.com/shantanusharma/deepagents/issues/6519)) ([ca5f0e5](https://github.com/shantanusharma/deepagents/commit/ca5f0e5eae7ee749e81ae8e9e3bbc1762447fcc2))
* **sdk:** bump recursion limit to 10_000 in deepagents and set agent name ([#2194](https://github.com/shantanusharma/deepagents/issues/2194)) ([7dbc251](https://github.com/shantanusharma/deepagents/commit/7dbc25180e05261fba4d5ec752d3052fbc826e4c))
* **sdk:** bundle read template params into single base64 payload ([#1500](https://github.com/shantanusharma/deepagents/issues/1500)) ([a117145](https://github.com/shantanusharma/deepagents/commit/a1171457dc7de9b13a2abb0610853f4a35fe74dc))
* **sdk:** cache optional prompt caching provider lookups ([#7585](https://github.com/shantanusharma/deepagents/issues/7585)) ([4a51d63](https://github.com/shantanusharma/deepagents/commit/4a51d6370b9eb1085376897e905136866cf5cb94))
* **sdk:** catch `UnicodeDecodeError` in `FilesystemBackend.read` ([#2319](https://github.com/shantanusharma/deepagents/issues/2319)) ([9783fe4](https://github.com/shantanusharma/deepagents/commit/9783fe43b71ad0fbe30593a263a27f38c6bf8f55))
* **sdk:** catch PermissionError in FilesystemBackend ripgrep ([#2571](https://github.com/shantanusharma/deepagents/issues/2571)) ([3d5d673](https://github.com/shantanusharma/deepagents/commit/3d5d67349c8e88e33af98137db9634742f018cb0))
* **sdk:** check filesystem permissions against the symlink-resolved path ([#6818](https://github.com/shantanusharma/deepagents/issues/6818)) ([7a69743](https://github.com/shantanusharma/deepagents/commit/7a6974309ac78f0b2ea636afc70bd8a0268bed7f))
* **sdk:** clarify skill source labels in system prompt ([#3464](https://github.com/shantanusharma/deepagents/issues/3464)) ([fc6a24f](https://github.com/shantanusharma/deepagents/commit/fc6a24f18829cf3f36089945226edfa50d52ab9e))
* **sdk:** clarify zero execute timeout semantics ([#5752](https://github.com/shantanusharma/deepagents/issues/5752)) ([4b49286](https://github.com/shantanusharma/deepagents/commit/4b4928613262ac23d419f0e8788f24412a8fdafb))
* **sdk:** clean up cancelled shell commands ([#5907](https://github.com/shantanusharma/deepagents/issues/5907)) ([00f0486](https://github.com/shantanusharma/deepagents/commit/00f04867996f7ecc99f57aa8f4472117c4cef25d))
* **sdk:** clip long `grep` lines to a window around the match ([#7526](https://github.com/shantanusharma/deepagents/issues/7526)) ([98ff834](https://github.com/shantanusharma/deepagents/commit/98ff83427cd8dbda3fd51c1f7135217bf2544491))
* **sdk:** compare provider in `model_matches_spec` ([#3943](https://github.com/shantanusharma/deepagents/issues/3943)) ([34244b6](https://github.com/shantanusharma/deepagents/commit/34244b6aebde4c237758dacedccdc3e22f3ca8e5))
* **sdk:** condition `execute` search guidance on visible tools ([#4921](https://github.com/shantanusharma/deepagents/issues/4921)) ([b65cc00](https://github.com/shantanusharma/deepagents/commit/b65cc0076caab2e35c07598055b8b338a47e5e1a))
* **sdk:** condition large-result guidance on visible tools ([#4920](https://github.com/shantanusharma/deepagents/issues/4920)) ([d3650c7](https://github.com/shantanusharma/deepagents/commit/d3650c7b1f5ca968abd72345a511719d4ba65907))
* **sdk:** default OpenRouter routing to ignore Azure upstream ([#3157](https://github.com/shantanusharma/deepagents/issues/3157)) ([01a9113](https://github.com/shantanusharma/deepagents/commit/01a911379d368fab8280cd827c38776800abe7b8))
* **sdk:** diagnose rubric grader structured output errors ([#4938](https://github.com/shantanusharma/deepagents/issues/4938)) ([f51d3a0](https://github.com/shantanusharma/deepagents/commit/f51d3a0145a0301317c36b0ae15263007dacd6f1))
* **sdk:** disambiguate `read_file` line gutters ([#4561](https://github.com/shantanusharma/deepagents/issues/4561)) ([cf057b4](https://github.com/shantanusharma/deepagents/commit/cf057b4bcdb77ad67014f7dabe71e71f2366c95e))
* **sdk:** disclose byte-cap losses in capture-offload execute previews ([#5567](https://github.com/shantanusharma/deepagents/issues/5567)) ([dbdd6fb](https://github.com/shantanusharma/deepagents/commit/dbdd6fbb47f340de8d23092187aa2882242963f8))
* **sdk:** disclose per-line clipping in large-result previews ([#5564](https://github.com/shantanusharma/deepagents/issues/5564)) ([5014cf7](https://github.com/shantanusharma/deepagents/commit/5014cf7f7480c5e080095c9e3396e4ce93421053))
* **sdk:** don't dedent summarization prompt ([#870](https://github.com/shantanusharma/deepagents/issues/870)) ([7ee5d40](https://github.com/shantanusharma/deepagents/commit/7ee5d40fca1d2682942e6549c0c61bfbb82ab351))
* **sdk:** don't swallow `TypeError` from custom `token_counter` ([#3927](https://github.com/shantanusharma/deepagents/issues/3927)) ([a6ec9d0](https://github.com/shantanusharma/deepagents/commit/a6ec9d0e797a8b8a7d53d7debb197bb25e80be41))
* **sdk:** drop reasoning blocks bound to history a summary replaced ([#7127](https://github.com/shantanusharma/deepagents/issues/7127)) ([6032a5a](https://github.com/shantanusharma/deepagents/commit/6032a5ade4908d75eb2662e602f1f61a1d7a9bcf))
* **sdk:** drop redundant backend line from `execute` tool description ([#7862](https://github.com/shantanusharma/deepagents/issues/7862)) ([3b18c75](https://github.com/shantanusharma/deepagents/commit/3b18c75de24112f924d6997d1f6e8e2505ce0006))
* **sdk:** drop results from ls, grep, glob when a symlink resolves outside approved search scope ([#7706](https://github.com/shantanusharma/deepagents/issues/7706)) ([ba7d8a0](https://github.com/shantanusharma/deepagents/commit/ba7d8a06abcb9481af1f4fa10c54495fa168eac3))
* **sdk:** emit terminal rubric iteration status ([#4406](https://github.com/shantanusharma/deepagents/issues/4406)) ([a51c8d2](https://github.com/shantanusharma/deepagents/commit/a51c8d2b1723d143439a1466f5a49a52c442bdfc))
* **sdk:** empty read for degenerate `read_file` windows ([#5184](https://github.com/shantanusharma/deepagents/issues/5184)) ([6bf3b68](https://github.com/shantanusharma/deepagents/commit/6bf3b68441e04e9e25883a4f91e6b8d0d6c15703))
* **sdk:** enforce `LocalShellBackend` output limits in UTF-8 bytes ([#7074](https://github.com/shantanusharma/deepagents/issues/7074)) ([953d5dd](https://github.com/shantanusharma/deepagents/commit/953d5dda8bd866663f49dfa0659a87c3f2cf0c26))
* **sdk:** enforce full criterion coverage in `RubricMiddleware` ([#5234](https://github.com/shantanusharma/deepagents/issues/5234)) ([ddb69b6](https://github.com/shantanusharma/deepagents/commit/ddb69b609a02d7203cda7f3ea2796ca73e5b5795))
* **sdk:** enforce path boundaries in `CompositeBackend` routing ([#1659](https://github.com/shantanusharma/deepagents/issues/1659)) ([3dcf5c4](https://github.com/shantanusharma/deepagents/commit/3dcf5c4984ead5b1f9ded64047a8f42096127348))
* **sdk:** exclude tools from execution when setting `excluded_tools` in harness profiles ([#5809](https://github.com/shantanusharma/deepagents/issues/5809)) ([553d412](https://github.com/shantanusharma/deepagents/commit/553d412bb4f4b868fbf080ab561f76b4dd335f52))
* **sdk:** explain truncation markers only when preview omits lines ([#5563](https://github.com/shantanusharma/deepagents/issues/5563)) ([7b4fcd3](https://github.com/shantanusharma/deepagents/commit/7b4fcd398b2a9bcd875b193c32d1eb97f152ce21))
* **sdk:** export `DeepAgentState` ([#3653](https://github.com/shantanusharma/deepagents/issues/3653)) ([14a9047](https://github.com/shantanusharma/deepagents/commit/14a904757c2d9d797945b6ea1bc9529f1f8cf369))
* **sdk:** extract text from all content blocks for large tool result eviction ([#1673](https://github.com/shantanusharma/deepagents/issues/1673)) ([336a20d](https://github.com/shantanusharma/deepagents/commit/336a20d448d06bc46e39ef29f46e4aba81999319))
* **sdk:** FilesystemMiddleware forward 'name' attribute in large_tool_result from the original tool msg ([#825](https://github.com/shantanusharma/deepagents/issues/825)) ([41b41c2](https://github.com/shantanusharma/deepagents/commit/41b41c216faea85cda3b2795252b6193090726fa))
* **sdk:** fix character counting in `ls` and `glob` output ([#6204](https://github.com/shantanusharma/deepagents/issues/6204)) ([4ca678f](https://github.com/shantanusharma/deepagents/commit/4ca678fe11fcb8f452b59b31923f37dabbc26d6a))
* **sdk:** fix glob matching with ** in _python_search fallback ([#1350](https://github.com/shantanusharma/deepagents/issues/1350)) ([a1de63f](https://github.com/shantanusharma/deepagents/commit/a1de63f606b4c6bfbe8a49f114aa9684eb612ec0))
* **sdk:** fix offloading for state backend ([#2266](https://github.com/shantanusharma/deepagents/issues/2266)) ([92f5507](https://github.com/shantanusharma/deepagents/commit/92f55075d978c27a6aa658968a1999754af973fe))
* **sdk:** fix TypeError in async sub-agents ([#2376](https://github.com/shantanusharma/deepagents/issues/2376)) ([8be4a2e](https://github.com/shantanusharma/deepagents/commit/8be4a2ee3878a3e15c15d56fd64ba8db248a6328))
* **sdk:** give id-less tool result offloads unique paths ([#6316](https://github.com/shantanusharma/deepagents/issues/6316)) ([a0c2ad0](https://github.com/shantanusharma/deepagents/commit/a0c2ad03c6dcd52340e91bea6483ee7750d5deee))
* **sdk:** grep crashing when files vanish mid-walk ([#3592](https://github.com/shantanusharma/deepagents/issues/3592)) ([0b8301b](https://github.com/shantanusharma/deepagents/commit/0b8301b2067f7dbbc83ebcf05c52e91413260fd1))
* **sdk:** grep should perform literal search instead of regex ([#975](https://github.com/shantanusharma/deepagents/issues/975)) ([91d93f2](https://github.com/shantanusharma/deepagents/commit/91d93f293d0a3dd530dff1ae5eee6ef0e9279b56))
* **sdk:** guard empty binary reads with empty-content warning ([#3675](https://github.com/shantanusharma/deepagents/issues/3675)) ([2c2cec8](https://github.com/shantanusharma/deepagents/commit/2c2cec87476f06e32c7b09cedd2c44e0c713f147))
* **sdk:** guard timeout forwarding for older backend packages ([#1461](https://github.com/shantanusharma/deepagents/issues/1461)) ([5fb4450](https://github.com/shantanusharma/deepagents/commit/5fb44505dd327fe88e8db6f3155cb442524b0788))
* **sdk:** handle `None` state in messages delta reducer ([#3636](https://github.com/shantanusharma/deepagents/issues/3636)) ([5a6d920](https://github.com/shantanusharma/deepagents/commit/5a6d920d9dec2199cbe743062a5cc1ff8f298567))
* **sdk:** handle `Overwrite`-wrapped messages in tool result interception ([#3905](https://github.com/shantanusharma/deepagents/issues/3905)) ([a043c5a](https://github.com/shantanusharma/deepagents/commit/a043c5a6717374c405a3ed740cfdafdd196f5f21))
* **sdk:** handle base64 reads with unknown file extensions ([#3663](https://github.com/shantanusharma/deepagents/issues/3663)) ([9857a08](https://github.com/shantanusharma/deepagents/commit/9857a08b6144b2f001d8f4bf03ac2f254c6b2da4))
* **sdk:** handle exact file paths in grep and glob operations ([#1017](https://github.com/shantanusharma/deepagents/issues/1017)) ([25d153d](https://github.com/shantanusharma/deepagents/commit/25d153dab974b3e494f80f2ad0aad4f3cd963664))
* **sdk:** handle large payloads and headless container execution ([#872](https://github.com/shantanusharma/deepagents/issues/872)) ([f21ee57](https://github.com/shantanusharma/deepagents/commit/f21ee57df3f9946b1c9b2a0351496692f23e48d7))
* **sdk:** harden `FilesystemBackend` against symlink loops ([#3035](https://github.com/shantanusharma/deepagents/issues/3035)) ([abd02f9](https://github.com/shantanusharma/deepagents/commit/abd02f99ef12030bdfe429fdc3ad80a2785bea61))
* **sdk:** harden skills metadata parsing, improve spec compliance ([#1189](https://github.com/shantanusharma/deepagents/issues/1189)) ([b5c8a99](https://github.com/shantanusharma/deepagents/commit/b5c8a99808694b94cb1a3f3aeeb3be895e44af2c))
* **sdk:** identify file-capable provider classes ([#5326](https://github.com/shantanusharma/deepagents/issues/5326)) ([e5d5391](https://github.com/shantanusharma/deepagents/commit/e5d53917c01aadcebe4e7e4a1974322033ae6c87))
* **sdk:** implement upload_files for StateBackend ([#2661](https://github.com/shantanusharma/deepagents/issues/2661)) ([5798345](https://github.com/shantanusharma/deepagents/commit/579834513a4ba1a024a52fc4edf918f526eab5f2))
* **sdk:** import profile re-exports from leaf modules ([#3377](https://github.com/shantanusharma/deepagents/issues/3377)) ([ca99391](https://github.com/shantanusharma/deepagents/commit/ca99391668ea1510932f8e9097e8ed3c0caadf73))
* **sdk:** import profile symbols directly from `harness_profiles` ([#3291](https://github.com/shantanusharma/deepagents/issues/3291)) ([503453c](https://github.com/shantanusharma/deepagents/commit/503453c06f7e0545914789a07ddba6ca6b0c8ec5))
* **sdk:** improve grep literal guidance and sandbox glob routing ([#4168](https://github.com/shantanusharma/deepagents/issues/4168)) ([b1dbf5e](https://github.com/shantanusharma/deepagents/commit/b1dbf5e66ac81a9fd95abf6987ba058bb14a5edf))
* **sdk:** improvements in default sandbox.write and sandbox.read implementations ([#2321](https://github.com/shantanusharma/deepagents/issues/2321)) ([4a37a46](https://github.com/shantanusharma/deepagents/commit/4a37a469ffd8a2d3b515c4de72674673f433082b))
* **sdk:** include HTTP status in rubric grader errors ([#4967](https://github.com/shantanusharma/deepagents/issues/4967)) ([bca70aa](https://github.com/shantanusharma/deepagents/commit/bca70aa1f30ee1472809894e2474a76e4ff2f8bd))
* **sdk:** inherit parent `interrupt_on` for subagents ([#2334](https://github.com/shantanusharma/deepagents/issues/2334)) ([acad9bb](https://github.com/shantanusharma/deepagents/commit/acad9bb6ceebee7dc74bd75dcffa49faa8697658))
* **sdk:** isolate composite glob paths ([#4531](https://github.com/shantanusharma/deepagents/issues/4531)) ([cbdb0a7](https://github.com/shantanusharma/deepagents/commit/cbdb0a7df8cd4bbacff9ca7ac2e42232ef290c10))
* **sdk:** isolate private custom state from subagents ([#4587](https://github.com/shantanusharma/deepagents/issues/4587)) ([a4662c0](https://github.com/shantanusharma/deepagents/commit/a4662c07296c378045006c9f45ed1d12bd1a9da6))
* **sdk:** keep blank read windows out of the empty-file warning ([#5050](https://github.com/shantanusharma/deepagents/issues/5050)) ([a892a0e](https://github.com/shantanusharma/deepagents/commit/a892a0ee26d045256b6d3b0c224b3de663c83eb5))
* **sdk:** keep forked subagents on the parent's prompt-cache prefix ([#7628](https://github.com/shantanusharma/deepagents/issues/7628)) ([e3cb6bb](https://github.com/shantanusharma/deepagents/commit/e3cb6bb097c1b5e2654e23a236c83ca0c17edea8))
* **sdk:** keep private state out of subagent propagation ([#3542](https://github.com/shantanusharma/deepagents/issues/3542)) ([7ff9553](https://github.com/shantanusharma/deepagents/commit/7ff9553fc057a682ba503ebfe9a870adb51ab848))
* **sdk:** make `BackendProtocol.glob` recursive for bare patterns ([#5026](https://github.com/shantanusharma/deepagents/issues/5026)) ([32f35d5](https://github.com/shantanusharma/deepagents/commit/32f35d5e01f460549c10365eb569978909f5c969))
* **sdk:** make `ContextHubBackend.glob` honor `path` ([#6998](https://github.com/shantanusharma/deepagents/issues/6998)) ([dd6706d](https://github.com/shantanusharma/deepagents/commit/dd6706d3007b4a077985b38bbc0d4a792c7016bc))
* **sdk:** make created_at and modified_at NotRequired fields on FileData ([#2248](https://github.com/shantanusharma/deepagents/issues/2248)) ([9862b5a](https://github.com/shantanusharma/deepagents/commit/9862b5ad0e94fa52fde6971ac9c2a0a1875ee451))
* **sdk:** make skill truncation warnings actionable ([#4141](https://github.com/shantanusharma/deepagents/issues/4141)) ([2f5f5b8](https://github.com/shantanusharma/deepagents/commit/2f5f5b85793d944167a42e8d5b8e0a11bb1e3932))
* **sdk:** make sure that tool truncation applies to execute ([#547](https://github.com/shantanusharma/deepagents/issues/547)) ([18ad629](https://github.com/shantanusharma/deepagents/commit/18ad62992949a5482378bfa5f9d126a4799e5e98))
* **sdk:** make sync glob timeout bound wall-clock time ([#3866](https://github.com/shantanusharma/deepagents/issues/3866)) ([cba6caf](https://github.com/shantanusharma/deepagents/commit/cba6caf8f708133381506ecc9e217e7e3ca1c7f2))
* **sdk:** mark read_file media and Nemotron nudges as harness notifications ([#7589](https://github.com/shantanusharma/deepagents/issues/7589)) ([eb81f68](https://github.com/shantanusharma/deepagents/commit/eb81f68ca932217c9e3430b48dc047732e800d29))
* **sdk:** match example_agent_descriptions closing tag in task tool prompt ([#2462](https://github.com/shantanusharma/deepagents/issues/2462)) ([c36a41c](https://github.com/shantanusharma/deepagents/commit/c36a41ccacd46d54806943821ebf16c606a5bc9f))
* **sdk:** missing `_validate_path()` on `Glob` tool's `path` parameter allows directory traversal ([#1320](https://github.com/shantanusharma/deepagents/issues/1320)) ([194a2db](https://github.com/shantanusharma/deepagents/commit/194a2db672188cbd22e300d8f3656cea8f9dd23f))
* **sdk:** move `get_sync()` inside try in `check_async_task` and `cancel_async_task` ([#3967](https://github.com/shantanusharma/deepagents/issues/3967)) ([b0d92c0](https://github.com/shantanusharma/deepagents/commit/b0d92c0f38ca0aa037b56e26b2b0d322cdd07856))
* **sdk:** normalize CRLF line endings in `FilesystemBackend.edit()` ([#2256](https://github.com/shantanusharma/deepagents/issues/2256)) ([69bd21e](https://github.com/shantanusharma/deepagents/commit/69bd21e2b14fa4bfd88d858702aff0e64237d35d))
* **sdk:** normalize read slices after windowing ([#3888](https://github.com/shantanusharma/deepagents/issues/3888)) ([33d900c](https://github.com/shantanusharma/deepagents/commit/33d900c98b686aa7e7782d0be3019010ced5f03a))
* **sdk:** normalize Windows backslash paths before PurePosixPath processing ([#1859](https://github.com/shantanusharma/deepagents/issues/1859)) ([e1c1d50](https://github.com/shantanusharma/deepagents/commit/e1c1d5024729f5205eaa42bf6a9bc1c93a30d043))
* **sdk:** offload conversation history to distinct session ID when summarizing ([#5470](https://github.com/shantanusharma/deepagents/issues/5470)) ([fa55c52](https://github.com/shantanusharma/deepagents/commit/fa55c52fe774462b2775c0d77dcf811d6dfd0e35))
* **sdk:** omit async task IDs from user replies by default ([#7174](https://github.com/shantanusharma/deepagents/issues/7174)) ([a551c88](https://github.com/shantanusharma/deepagents/commit/a551c88389e390454e8363a4f1b74d41fd6b8c80))
* **sdk:** overwrite `write` on LangSmithSandbox ([#2097](https://github.com/shantanusharma/deepagents/issues/2097)) ([c492a76](https://github.com/shantanusharma/deepagents/commit/c492a7697e390ae760945d06ca4e824c4f47cf92))
* **sdk:** pass through summarization factory prompt knobs ([#3559](https://github.com/shantanusharma/deepagents/issues/3559)) ([a663cad](https://github.com/shantanusharma/deepagents/commit/a663cad8858a78a5d063af0c51bb789bfb1aba2b))
* **sdk:** patch invalid partial tool calls ([#5430](https://github.com/shantanusharma/deepagents/issues/5430)) ([edc7c1c](https://github.com/shantanusharma/deepagents/commit/edc7c1ca69831c1827c1f479696a5450ffd1df9d))
* **sdk:** patch invalid tool calls ([#3386](https://github.com/shantanusharma/deepagents/issues/3386)) ([c916d1b](https://github.com/shantanusharma/deepagents/commit/c916d1b2e3a81dcd4fb2e595d6b971923c18fa31))
* **sdk:** preserve `ContextT` on `create_deep_agent` `middleware` ([#4055](https://github.com/shantanusharma/deepagents/issues/4055)) ([7be76c7](https://github.com/shantanusharma/deepagents/commit/7be76c752117e6e61dcdc931ea5147261fad6768))
* **sdk:** preserve backend exit status when capture metadata is missing ([#6451](https://github.com/shantanusharma/deepagents/issues/6451)) ([c9926b1](https://github.com/shantanusharma/deepagents/commit/c9926b1a96d204309d0b211701b288ce3bb4244b))
* **sdk:** preserve CRLF line endings in sandbox edit ([#2899](https://github.com/shantanusharma/deepagents/issues/2899)) ([291aebe](https://github.com/shantanusharma/deepagents/commit/291aebe21f8a53604a2bf47daa120761dace2536))
* **sdk:** preserve filesystem permissions in middleware overrides ([#7166](https://github.com/shantanusharma/deepagents/issues/7166)) ([6ae83f4](https://github.com/shantanusharma/deepagents/commit/6ae83f4bc3ac444a6555f3cdd3878c4559fe5b81))
* **sdk:** preserve legacy large-result templates behind deprecation ([#5568](https://github.com/shantanusharma/deepagents/issues/5568)) ([4932d70](https://github.com/shantanusharma/deepagents/commit/4932d7066fc9f3464921ab72d5d86922ea4b26ec))
* **sdk:** preserve media references in summarization archives ([#3990](https://github.com/shantanusharma/deepagents/issues/3990)) ([2d6fb53](https://github.com/shantanusharma/deepagents/commit/2d6fb53cd8c94680a42fa9d7041509ff78050616))
* **sdk:** preserve output from timed-out shell commands ([#6349](https://github.com/shantanusharma/deepagents/issues/6349)) ([54b64dc](https://github.com/shantanusharma/deepagents/commit/54b64dcf952406c0de3b7d60ef3add449e100bc3))
* **sdk:** preserve parent rubric during parallel subagent calls ([#6849](https://github.com/shantanusharma/deepagents/issues/6849)) ([9740b88](https://github.com/shantanusharma/deepagents/commit/9740b88c06109890447ddd005871943f251c99c5))
* **sdk:** preserve resolved tool-result paths ([#6968](https://github.com/shantanusharma/deepagents/issues/6968)) ([29d646f](https://github.com/shantanusharma/deepagents/commit/29d646fd2d832a44c476964333eddecb0ec1c0cd))
* **sdk:** preserve symlink names in virtual filesystem results ([#7618](https://github.com/shantanusharma/deepagents/issues/7618)) ([2a4c5fa](https://github.com/shantanusharma/deepagents/commit/2a4c5faeb580ce6db1e560017846545b144a7e26))
* **sdk:** prevent local shell commands from stealing TUI input ([#5873](https://github.com/shantanusharma/deepagents/issues/5873)) ([c94a090](https://github.com/shantanusharma/deepagents/commit/c94a090c1b21918c9e4eced52ecb4e3bf7476f43))
* **sdk:** promote rubric middleware out of beta ([#7368](https://github.com/shantanusharma/deepagents/issues/7368)) ([98773a7](https://github.com/shantanusharma/deepagents/commit/98773a73843421f85a2113e6c3b0262f53d9bcd6))
* **sdk:** propagate `CompiledSubAgent` name into `lc_agent_name` metadata ([#3045](https://github.com/shantanusharma/deepagents/issues/3045)) ([f671e6b](https://github.com/shantanusharma/deepagents/commit/f671e6b18aa49700a535f7b48441662b67dafef9))
* **sdk:** propagate goto and graph in Commands returned by tools ([#3391](https://github.com/shantanusharma/deepagents/issues/3391)) ([d92aef6](https://github.com/shantanusharma/deepagents/commit/d92aef68f70a5e5277c43a50581e7895e682c417))
* **sdk:** propagate root listing errors from `CompositeBackend` ([#4925](https://github.com/shantanusharma/deepagents/issues/4925)) ([4c3b166](https://github.com/shantanusharma/deepagents/commit/4c3b1667035e3be6ae88cf8c431e0d6f143d2ff4))
* **sdk:** propagate subagent name to subagents ([#6987](https://github.com/shantanusharma/deepagents/issues/6987)) ([610a5fb](https://github.com/shantanusharma/deepagents/commit/610a5fb036120e272842684e4bbd4909c6cf7c1f))
* **sdk:** propagate subagent state keys for provided subagent middleware ([#5553](https://github.com/shantanusharma/deepagents/issues/5553)) ([ff8dda9](https://github.com/shantanusharma/deepagents/commit/ff8dda912b0d1651f234b9d49cec06e79b7c1b6b))
* **sdk:** put a subagent's own `SkillsMiddleware` in the skills slot ([#6820](https://github.com/shantanusharma/deepagents/issues/6820)) ([9a91d79](https://github.com/shantanusharma/deepagents/commit/9a91d79e18dacfe900ac62e59c756e87f3b586a7))
* **sdk:** raise `ValueError` for permission paths without leading slash and path traversal ([#2665](https://github.com/shantanusharma/deepagents/issues/2665)) ([723d27d](https://github.com/shantanusharma/deepagents/commit/723d27dcdce03cc9ffaa757c70533f0134a43a44))
* **sdk:** re-export filesystem permission for backwards compatibility ([#3036](https://github.com/shantanusharma/deepagents/issues/3036)) ([e04b50a](https://github.com/shantanusharma/deepagents/commit/e04b50ae291abefa64ee2750a0c1bbfd93954b32))
* **sdk:** recover from context overflow in the summary call ([#6864](https://github.com/shantanusharma/deepagents/issues/6864)) ([efd88ff](https://github.com/shantanusharma/deepagents/commit/efd88ff8fd1279361de77a83c9f75d98ed2f36d5))
* **sdk:** recover from rejected `read_file` media ([#6515](https://github.com/shantanusharma/deepagents/issues/6515)) ([802140c](https://github.com/shantanusharma/deepagents/commit/802140c1a7d1fff35a7edd8d0f1697eb460ce623))
* **sdk:** reject empty old_string in edit_file paths ([#5747](https://github.com/shantanusharma/deepagents/issues/5747)) ([1281b04](https://github.com/shantanusharma/deepagents/commit/1281b04f7eafaf654982b99a3c93f72744208eda))
* **sdk:** reject parallel same-file edits ([#6446](https://github.com/shantanusharma/deepagents/issues/6446)) ([2e2ee91](https://github.com/shantanusharma/deepagents/commit/2e2ee91b794ed549b299445b7bb5de641e9a4f4d))
* **sdk:** reject text edits of binary files ([#7069](https://github.com/shantanusharma/deepagents/issues/7069)) ([7a70d6e](https://github.com/shantanusharma/deepagents/commit/7a70d6e0e55ec818a454f071ff99295e5c12eab9))
* **sdk:** reject unknown keys in the task tool arguments ([#6299](https://github.com/shantanusharma/deepagents/issues/6299)) ([00fef9c](https://github.com/shantanusharma/deepagents/commit/00fef9c012b20f91785dc5e83c642fb439832178))
* **sdk:** relax skills parsing for allowed tools ([#1232](https://github.com/shantanusharma/deepagents/issues/1232)) ([72cecea](https://github.com/shantanusharma/deepagents/commit/72cecea955169ebb2e8c62c2b45bd0d925d39ca7))
* **sdk:** remove excluded tools from `ToolNode` ([#4698](https://github.com/shantanusharma/deepagents/issues/4698)) ([9709525](https://github.com/shantanusharma/deepagents/commit/970952550e8f53cd89a64a4ee98969ce757693ff))
* **sdk:** remove false unread-file error claim ([#7823](https://github.com/shantanusharma/deepagents/issues/7823)) ([e3eb70e](https://github.com/shantanusharma/deepagents/commit/e3eb70e4f4ba097a94310570d4d71fd9d128652d))
* **sdk:** rename `handoff` subagent mode to `isolated` ([#6030](https://github.com/shantanusharma/deepagents/issues/6030)) ([15454a8](https://github.com/shantanusharma/deepagents/commit/15454a85438146a59c804af3a525f96091c55fe8))
* **sdk:** report async subagent runs cancelled on the server, and drop reasoning from check results ([#7060](https://github.com/shantanusharma/deepagents/issues/7060)) ([ac8d8e9](https://github.com/shantanusharma/deepagents/commit/ac8d8e942a46bbc8e1f078fcb6b8d6393534abe2))
* **sdk:** report failed compaction with error status ([#7538](https://github.com/shantanusharma/deepagents/issues/7538)) ([2c11c92](https://github.com/shantanusharma/deepagents/commit/2c11c92ee2f47e4ce62e7e6510a77b0f2ad6b638))
* **sdk:** report UTF-8 byte sizes ([#6258](https://github.com/shantanusharma/deepagents/issues/6258)) ([5bac4aa](https://github.com/shantanusharma/deepagents/commit/5bac4aae53494329a533294564353b10c3385244))
* **sdk:** require a real Nemotron task transition ([#6296](https://github.com/shantanusharma/deepagents/issues/6296)) ([3d6392e](https://github.com/shantanusharma/deepagents/commit/3d6392e82408c1a5e24d0c1d32c53934552fd314))
* **sdk:** reset stale encoding on text overwrite ([#6737](https://github.com/shantanusharma/deepagents/issues/6737)) ([fb62fb0](https://github.com/shantanusharma/deepagents/commit/fb62fb067b924a36359505f9445c1ecc55fd7d66))
* **sdk:** resolve exact-file `delete` targets with first-match-wins o… ([#5229](https://github.com/shantanusharma/deepagents/issues/5229)) ([6dd2a7d](https://github.com/shantanusharma/deepagents/commit/6dd2a7d2f83bd63844a987f6ec65ac9244ec8c5b))
* **sdk:** restore deprecated protocol return types ([#2342](https://github.com/shantanusharma/deepagents/issues/2342)) ([845cdf5](https://github.com/shantanusharma/deepagents/commit/845cdf52d7f15ab2b260de95f8448c04264c1efc))
* **sdk:** restrict inline file blocks to supported MIME types ([#6447](https://github.com/shantanusharma/deepagents/issues/6447)) ([191e93a](https://github.com/shantanusharma/deepagents/commit/191e93a05e30aad705ee2cb33d5b03e7104dbe5a))
* **sdk:** restrict Python grep fallback to the requested file ([#7539](https://github.com/shantanusharma/deepagents/issues/7539)) ([3a0c7bb](https://github.com/shantanusharma/deepagents/commit/3a0c7bb935fefb5d283f0799ef4551add6c2a361))
* **sdk:** retry an async subagent check when its thread can't be read ([#7124](https://github.com/shantanusharma/deepagents/issues/7124)) ([d57b09b](https://github.com/shantanusharma/deepagents/commit/d57b09b1a7a9890fee2db649e6418416f039df14))
* **sdk:** return error message instead of raising ValueError for invalid paths ([#994](https://github.com/shantanusharma/deepagents/issues/994)) ([ead0433](https://github.com/shantanusharma/deepagents/commit/ead0433ef485f6bbf9dd19cd6b6be5d5a878f526))
* **sdk:** return grep errors for sandbox exec failures ([#3637](https://github.com/shantanusharma/deepagents/issues/3637)) ([f87d61f](https://github.com/shantanusharma/deepagents/commit/f87d61f01a23fcfb994e88b7f9324d404e66faef))
* **sdk:** return sentinel for empty file lists ([#3709](https://github.com/shantanusharma/deepagents/issues/3709)) ([efafd1e](https://github.com/shantanusharma/deepagents/commit/efafd1e070aeae8901ee3123c7fcbf1815a33c4f))
* **sdk:** route `BaseSandbox async` helpers through aexecute ([#3996](https://github.com/shantanusharma/deepagents/issues/3996)) ([52dcf1a](https://github.com/shantanusharma/deepagents/commit/52dcf1a42cb00dd614b336038e4398472f78859d))
* **sdk:** route subagent model resolution to `resolve_model` ([#2208](https://github.com/shantanusharma/deepagents/issues/2208)) ([6720e4c](https://github.com/shantanusharma/deepagents/commit/6720e4c520295ac1cb24c19cf3d315d2d05ba257))
* **sdk:** sandbox not-found contract and glob deny over-blocking on delete ([#4321](https://github.com/shantanusharma/deepagents/issues/4321)) ([d77496b](https://github.com/shantanusharma/deepagents/commit/d77496b969b9c59ce1c7c44e2085e5388e12c306))
* **sdk:** sanitize paths in BaseSandbox ls_info and read templates ([#1484](https://github.com/shantanusharma/deepagents/issues/1484)) ([2252194](https://github.com/shantanusharma/deepagents/commit/2252194d2e0d49868e3182c5afa909474f7b07c2))
* **sdk:** scrub multimodal content blocks unsupported by the model's profile ([#5194](https://github.com/shantanusharma/deepagents/issues/5194)) ([bdc6104](https://github.com/shantanusharma/deepagents/commit/bdc610445534ba339360f3988de6b50b60482f1d))
* **sdk:** skill loading should default to 1000 lines ([#2721](https://github.com/shantanusharma/deepagents/issues/2721)) ([badc4d3](https://github.com/shantanusharma/deepagents/commit/badc4d3921ae0ede4305f44f85fa7266df9465e7))
* **sdk:** skip binary files in in-memory `grep` ([#7032](https://github.com/shantanusharma/deepagents/issues/7032)) ([97f856d](https://github.com/shantanusharma/deepagents/commit/97f856dcb08264ef78722a4687cab9133ec5fb7a))
* **sdk:** stable `HumanMessage` IDs across resumed threads ([#3591](https://github.com/shantanusharma/deepagents/issues/3591)) ([82c3194](https://github.com/shantanusharma/deepagents/commit/82c31947f9dc938ffc71e1cea96d162a39aec3a1))
* **sdk:** stop `FilesystemBackend.download_files` hanging on a FIFO ([#7663](https://github.com/shantanusharma/deepagents/issues/7663)) ([b493490](https://github.com/shantanusharma/deepagents/commit/b493490a1793955b6c3bae4651fd1a531ee49b1a))
* **sdk:** store NUL-containing uploads as base64 in StoreBackend ([#7710](https://github.com/shantanusharma/deepagents/issues/7710)) ([e1c7735](https://github.com/shantanusharma/deepagents/commit/e1c7735f1044519db63d9ab511bf881a0a8efddc))
* **sdk:** stream async subagent runs to apps that join them ([#7722](https://github.com/shantanusharma/deepagents/issues/7722)) ([62e422a](https://github.com/shantanusharma/deepagents/commit/62e422a0dda11d0da4449d7e252f1fca31eccefa))
* **sdk:** stream Python grep fallback ([#3886](https://github.com/shantanusharma/deepagents/issues/3886)) ([3673d95](https://github.com/shantanusharma/deepagents/commit/3673d95d41aa00f03fbfe2083e46afa485800f3a))
* **sdk:** string interpolation in BaseSandbox write/edit tools  ([#955](https://github.com/shantanusharma/deepagents/issues/955)) ([dc77082](https://github.com/shantanusharma/deepagents/commit/dc7708274f690c1415f7453bdac7ac7b4bf2349c))
* **sdk:** strip HTML comments from memory content before system prompt injection ([#3462](https://github.com/shantanusharma/deepagents/issues/3462)) ([bfbb8bc](https://github.com/shantanusharma/deepagents/commit/bfbb8bc5575ebd1ba9aa29430f6d2f86c24b7d3c))
* **sdk:** strip leading slash from glob patterns before matching ([#1846](https://github.com/shantanusharma/deepagents/issues/1846)) ([073893c](https://github.com/shantanusharma/deepagents/commit/073893c3ea82a1e7047eb939cf147091cb4c50c1))
* **sdk:** subagents: update prompt and make fetching of last message more robust ([#3406](https://github.com/shantanusharma/deepagents/issues/3406)) ([4421bec](https://github.com/shantanusharma/deepagents/commit/4421bec94ffbe1f3a3bf44088ebcf8ab8c24a736))
* **sdk:** suggest populating path in `glob` tool result where appropriate ([#6199](https://github.com/shantanusharma/deepagents/issues/6199)) ([26954ea](https://github.com/shantanusharma/deepagents/commit/26954eaafb581db641dd7ce3f9d4ba470a9af878))
* **sdk:** summarization offloading ([#920](https://github.com/shantanusharma/deepagents/issues/920)) ([fc5544a](https://github.com/shantanusharma/deepagents/commit/fc5544ae3d063b38c834a0e10d408163bdbdafca))
* **sdk:** summarization: truncate trailing ToolMessages to keep context within `keep` limit ([#3405](https://github.com/shantanusharma/deepagents/issues/3405)) ([bee514f](https://github.com/shantanusharma/deepagents/commit/bee514fd24862b6b22a5993eb8b6cfc69e42dd80))
* **sdk:** support read-your-writes in StateBackend ([#2991](https://github.com/shantanusharma/deepagents/issues/2991)) ([0924869](https://github.com/shantanusharma/deepagents/commit/0924869bc3d946577e7c3cbc79a86e4aaf522edd))
* **sdk:** surface EOF-newline mismatch in `edit_file` ([#3031](https://github.com/shantanusharma/deepagents/issues/3031)) ([d30686e](https://github.com/shantanusharma/deepagents/commit/d30686ec82d36a0e9430f7c512c34835aba2c079))
* **sdk:** surface missing path errors in `FilesystemBackend.ls` ([#3574](https://github.com/shantanusharma/deepagents/issues/3574)) ([4c28760](https://github.com/shantanusharma/deepagents/commit/4c28760abbbe43117f2118793f11ff9d4f71761e))
* **sdk:** surface OS errors in sandbox ls/read/edit/glob ([#3359](https://github.com/shantanusharma/deepagents/issues/3359)) ([7598bd9](https://github.com/shantanusharma/deepagents/commit/7598bd93f72b609a46da64f7c458c42ac07a0f3a))
* **sdk:** surface sandbox glob failures instead of reporting no matches ([#5566](https://github.com/shantanusharma/deepagents/issues/5566)) ([0286f62](https://github.com/shantanusharma/deepagents/commit/0286f628646d4196e5e89164b45803fb7b97a0cc))
* **sdk:** tag binary `StateBackend.upload_files` content as base64 ([#6551](https://github.com/shantanusharma/deepagents/issues/6551)) ([b1ebc5b](https://github.com/shantanusharma/deepagents/commit/b1ebc5bd51aab19c1251197b1b8eb699c85cfc00))
* **sdk:** timeout python grep fallback ([#1937](https://github.com/shantanusharma/deepagents/issues/1937)) ([665a18e](https://github.com/shantanusharma/deepagents/commit/665a18e7fe7f291319af6780328384cc658af899))
* **sdk:** tolerate missing `modified_at` in glob sort ([#4376](https://github.com/shantanusharma/deepagents/issues/4376)) ([09b2e53](https://github.com/shantanusharma/deepagents/commit/09b2e53617968a06c2b4ee6d821fca71a1d94d49))
* **sdk:** treat boundary-truncated UTF-8 in `read()` prefix check as text ([#2980](https://github.com/shantanusharma/deepagents/issues/2980)) ([c36ebc7](https://github.com/shantanusharma/deepagents/commit/c36ebc7be5840e9008279992741c67a8377ffc01))
* **sdk:** unify `grep` include-glob semantics across backends ([#3936](https://github.com/shantanusharma/deepagents/issues/3936)) ([feab6e0](https://github.com/shantanusharma/deepagents/commit/feab6e0b3762aa42fa458af16d0a3e8d04d8b075))
* **sdk:** update imputed `ToolMessage` content in `PatchToolCallsMiddleware` ([#6277](https://github.com/shantanusharma/deepagents/issues/6277)) ([178417d](https://github.com/shantanusharma/deepagents/commit/178417d0dad063fea0300db68455f4574ef67db3))
* **sdk:** update middleware order ([#2070](https://github.com/shantanusharma/deepagents/issues/2070)) ([def526b](https://github.com/shantanusharma/deepagents/commit/def526b9621ee3c9e10b723acceb532341395554))
* **sdk:** update recursion limit ([#2273](https://github.com/shantanusharma/deepagents/issues/2273)) ([fd91a30](https://github.com/shantanusharma/deepagents/commit/fd91a30bf394d4d0ebf8deed9e7835dfc05c9891))
* **sdk:** updates for multimodal ([#2514](https://github.com/shantanusharma/deepagents/issues/2514)) ([a2edf3e](https://github.com/shantanusharma/deepagents/commit/a2edf3ed80e17a87027c41a46283387031ebd3e5))
* **sdk:** Use configurable directly instead of tracing context for subagent tagging ([#2845](https://github.com/shantanusharma/deepagents/issues/2845)) ([bd6ec6b](https://github.com/shantanusharma/deepagents/commit/bd6ec6bcebcdcc26f6b79e2c55611074b0e01631))
* **sdk:** use consistent path stripping in CompositeBackend grep and glob ([#1504](https://github.com/shantanusharma/deepagents/issues/1504)) ([0dc8548](https://github.com/shantanusharma/deepagents/commit/0dc85483dd2ac6ff0d95894ba3d021b2df45e930))
* **sdk:** use file transfer instead of command strings for sandbox write/edit ([#2117](https://github.com/shantanusharma/deepagents/issues/2117)) ([6c2d559](https://github.com/shantanusharma/deepagents/commit/6c2d559b574a5a5d9de3adc36d6cf02d6cf93d9d)), refs [#1402](https://github.com/shantanusharma/deepagents/issues/1402)
* **sdk:** use separate middleware for filtering unsupported multimodal content ([#6366](https://github.com/shantanusharma/deepagents/issues/6366)) ([737621b](https://github.com/shantanusharma/deepagents/commit/737621ba73c39ac822c78c144612336bd02de6fb))
* **sdk:** use Sequence instead of list for subagents parameter ([#1905](https://github.com/shantanusharma/deepagents/issues/1905)) ([b6f015e](https://github.com/shantanusharma/deepagents/commit/b6f015e6178d1bf7bf470d049dbbf544e3a0ac94))
* **sdk:** validate tool_call_id before subagent invocation ([#1506](https://github.com/shantanusharma/deepagents/issues/1506)) ([0323fd6](https://github.com/shantanusharma/deepagents/commit/0323fd65c0a417fcc1c031284f59163467c66791))
* **sdk:** warn instead of silently skipping unresolved state schemas ([#5166](https://github.com/shantanusharma/deepagents/issues/5166)) ([2054c07](https://github.com/shantanusharma/deepagents/commit/2054c078071b4248707c2b28c7e5254e36703e66))
* **sdk:** warn on virtual mode ([#1462](https://github.com/shantanusharma/deepagents/issues/1462)) ([7b3e05c](https://github.com/shantanusharma/deepagents/commit/7b3e05c7eddd8e3cc21ce64bad47335e9c148ad8))
* use `request.override` instead of direct attribute overrides ([#431](https://github.com/shantanusharma/deepagents/issues/431)) ([bf02091](https://github.com/shantanusharma/deepagents/commit/bf02091435c31a545c280c35b804789de411132d))


### Performance Improvements

* **langsmith-sandbox:** run LangSmith sandbox commands over the async client ([#5061](https://github.com/shantanusharma/deepagents/issues/5061)) ([0d08747](https://github.com/shantanusharma/deepagents/commit/0d0874710615df2c89c3c30e56bfdabb73b44d99))
* **sdk:** add cache breakpoint to `MemoryMiddleware` ([#2713](https://github.com/shantanusharma/deepagents/issues/2713)) ([1699f3a](https://github.com/shantanusharma/deepagents/commit/1699f3aea710985087b16318bb8e6f6e80e02a1b))
* **sdk:** batch memory source loading into a single download_files call ([#1490](https://github.com/shantanusharma/deepagents/issues/1490)) ([cf72bcd](https://github.com/shantanusharma/deepagents/commit/cf72bcdb7cc985582ce4b7f88f16a374e1d8eecb))
* **sdk:** cache filesystem system prompts ([#3889](https://github.com/shantanusharma/deepagents/issues/3889)) ([2f432ba](https://github.com/shantanusharma/deepagents/commit/2f432ba63687d7c8488d5d41d0551d02b4ae00b4))
* **sdk:** cache grep glob matchers ([#3887](https://github.com/shantanusharma/deepagents/issues/3887)) ([eae3cf1](https://github.com/shantanusharma/deepagents/commit/eae3cf148de3f8c8ee9ffd8af6e5a5e06cce9d6f))
* **sdk:** count tokens once per model call in summarization middleware ([#3877](https://github.com/shantanusharma/deepagents/issues/3877)) ([6558c8c](https://github.com/shantanusharma/deepagents/commit/6558c8ca3d8e10e3309f95c807e740914af3175f))
* **sdk:** discover profile plugins in a single entry-point scan ([#7755](https://github.com/shantanusharma/deepagents/issues/7755)) ([cf1fc13](https://github.com/shantanusharma/deepagents/commit/cf1fc137c2f3ddd5dcff509c27df3930f8521673))
* **sdk:** filter editable-install scan to `deepagents` records ([#7752](https://github.com/shantanusharma/deepagents/issues/7752)) ([8771981](https://github.com/shantanusharma/deepagents/commit/877198138d384ffbef0159bcc6d4b39d2461558c))
* **sdk:** parallelize summarization offload and LLM summary generation ([#1488](https://github.com/shantanusharma/deepagents/issues/1488)) ([5e12eb7](https://github.com/shantanusharma/deepagents/commit/5e12eb79f8dacaf39ed0259825fbc2139a493a45))
* **sdk:** prefer ripgrep for sandbox searches ([#6919](https://github.com/shantanusharma/deepagents/issues/6919)) ([7a655f7](https://github.com/shantanusharma/deepagents/commit/7a655f77382484a6e6ca27e8724b08064af670c8))
* **sdk:** skip `.git` in sandbox `grep` and fix path-glob `grep` ([#6910](https://github.com/shantanusharma/deepagents/issues/6910)) ([f8ecffa](https://github.com/shantanusharma/deepagents/commit/f8ecffad6523775a323a807bc57097a98aa27e01))
* **sdk:** stop importing `langchain_anthropic` at import time ([#7204](https://github.com/shantanusharma/deepagents/issues/7204)) ([492a184](https://github.com/shantanusharma/deepagents/commit/492a184c5fc07364edaae464dd0bdc4e49af3e9e))
* **sdk:** stop importing `langchain_openai` at import time ([#7185](https://github.com/shantanusharma/deepagents/issues/7185)) ([1fe9631](https://github.com/shantanusharma/deepagents/commit/1fe963145de49dd62af807bff1b0e96f24c9ae07))


### Reverted Changes

* **code,sdk:** revert `SystemPromptConfig` ([#4969](https://github.com/shantanusharma/deepagents/issues/4969)) ([d046427](https://github.com/shantanusharma/deepagents/commit/d046427b536c8ddbce5d804d6ae8b860511a9b44))
* **deepagents:** refactor summarization middleware ([#1172](https://github.com/shantanusharma/deepagents/issues/1172)) ([621c2be](https://github.com/shantanusharma/deepagents/commit/621c2be76a36df805f4c48991b6262a5a4ea8717))
* **sdk:** reimplement skill loading via `skill` tool calling ([#1328](https://github.com/shantanusharma/deepagents/issues/1328)) ([342fcf1](https://github.com/shantanusharma/deepagents/commit/342fcf1b0b74b2801ea904085fb54be57d981aa8))

## [0.7.40](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.39...deepagents==0.7.40) (2026-11-18)

### Bug Fixes

- Preserve output from timed-out shell commands. ([#6349](https://github.com/langchain-ai/deepagents/pull/6349))
- Clean up cancelled shell commands. ([#5907](https://github.com/langchain-ai/deepagents/pull/5907))
- Avoid warning-filter race conditions in `warn_deprecated`. ([#7749](https://github.com/langchain-ai/deepagents/pull/7749))

### Performance Improvements

- Discover profile plugins in a single entry-point scan. ([#7755](https://github.com/langchain-ai/deepagents/pull/7755))

## [0.7.39](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.38...deepagents==0.7.39) (2026-11-16)

### Bug Fixes

- Fixed streaming of asynchronous subagent runs to apps that join them ([#7722](https://github.com/langchain-ai/deepagents/pull/7722)).
- Fixed uploads containing NUL bytes by storing them as base64 in `StoreBackend` ([#7710](https://github.com/langchain-ai/deepagents/pull/7710)).

### Performance Improvements

- Limited editable-install scans to `deepagents` records ([#7752](https://github.com/langchain-ai/deepagents/pull/7752)).

## [0.7.38](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.37...deepagents==0.7.38) (2026-11-13)

### Bug Fixes

- Exclude results from `ls`, `grep`, and `glob` when a symlink resolves outside the approved search scope. ([#7706](https://github.com/langchain-ai/deepagents/pull/7706))

## [0.7.37](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.36...deepagents==0.7.37) (2026-11-12)

### Bug Fixes

- Cache optional prompt-caching provider lookups in the SDK ([#7585](https://github.com/langchain-ai/deepagents/pull/7585)).

## [0.7.36](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.35...deepagents==0.7.36) (2026-11-12)

### Features

- Pass the agent's backend to middleware that requests it ([#7668](https://github.com/langchain-ai/deepagents/pull/7668)).
- Record the subagent's checkpoint namespace on the `task` tool message ([#7580](https://github.com/langchain-ai/deepagents/pull/7580)).

### Bug Fixes

- Prevent `FilesystemBackend.download_files` from hanging on FIFO files ([#7663](https://github.com/langchain-ai/deepagents/pull/7663)).

## [0.7.35](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.34...deepagents==0.7.35) (2026-11-09)

### Bug Fixes

- Keep forked subagents on their parent's prompt-cache prefix ([#7628](https://github.com/langchain-ai/deepagents/pull/7628)).
- Preserve symlink names in virtual filesystem results ([#7618](https://github.com/langchain-ai/deepagents/pull/7618)).
- Correctly mark `read_file` media and Nemotron nudges as harness notifications ([#7589](https://github.com/langchain-ai/deepagents/pull/7589)).

## [0.7.34](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.33...deepagents==0.7.34) (2026-11-05)

### Bug Fixes

- Fixed summarization cutoff handling by anchoring it to the message ID ([#7567](https://github.com/langchain-ai/deepagents/pull/7567)).

## [0.7.33](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.32...deepagents==0.7.33) (2026-11-05)

### Features

- Raise errors on model refusals by default and report subagent refusals to the parent agent ([#7512](https://github.com/langchain-ai/deepagents/pull/7512)).
- Add notification metadata to async subagent notifications ([#7334](https://github.com/langchain-ai/deepagents/pull/7334)).
- Record the `task` call ID on subagent checkpoints ([#7509](https://github.com/langchain-ai/deepagents/pull/7509)).

### Bug Fixes

- Restrict the Python `grep` fallback to the requested file and clip long result lines to a window around the match ([#7539](https://github.com/langchain-ai/deepagents/pull/7539), [#7526](https://github.com/langchain-ai/deepagents/pull/7526)).
- Report failed compaction with an error status ([#7538](https://github.com/langchain-ai/deepagents/pull/7538)).
- Promote rubric middleware out of beta ([#7368](https://github.com/langchain-ai/deepagents/pull/7368)).

## [0.7.32](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.31...deepagents==0.7.32) (2026-10-23)

### Performance Improvements

- Avoid importing `langchain_anthropic` and `langchain_openai` at SDK import time ([#7204](https://github.com/langchain-ai/deepagents/pull/7204), [#7185](https://github.com/langchain-ai/deepagents/pull/7185)).

## [0.7.31](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.30...deepagents==0.7.31) (2026-10-23)

### Features

- Expose execution output retention metadata in tracing ([#6876](https://github.com/langchain-ai/deepagents/pull/6876)).

### Bug Fixes

- Omit async task IDs from user replies by default ([#7174](https://github.com/langchain-ai/deepagents/pull/7174)).
- Preserve filesystem permissions in SDK middleware overrides ([#7166](https://github.com/langchain-ai/deepagents/pull/7166)).

## [0.7.30](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.29...deepagents==0.7.30) (2026-10-22)

### Features

- Async subagent follow-ups can now queue without interrupting active work ([#7082](https://github.com/langchain-ai/deepagents/pull/7082)).
- Added `notify_parent` ([#7132](https://github.com/langchain-ai/deepagents/pull/7132)) and `webhook` ([#7072](https://github.com/langchain-ai/deepagents/pull/7072)) to `AsyncSubAgent`.

### Bug Fixes

- Async subagent checks now report runs cancelled on the server and omit reasoning from results ([#7060](https://github.com/langchain-ai/deepagents/pull/7060)).
- Async subagent checks now retry when a thread cannot be read ([#7124](https://github.com/langchain-ai/deepagents/pull/7124)).
- Summaries now remove reasoning blocks associated with the history they replace ([#7127](https://github.com/langchain-ai/deepagents/pull/7127)).
- `LocalShellBackend` now enforces output limits in UTF-8 bytes ([#7074](https://github.com/langchain-ai/deepagents/pull/7074)).

## [0.7.29](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.28...deepagents==0.7.29) (2026-10-20)

### Bug Fixes

- `CompositeBackend` now handles routes without a trailing slash ([#7028](https://github.com/langchain-ai/deepagents/pull/7028)).
- Text edits to binary files are now rejected ([#7069](https://github.com/langchain-ai/deepagents/pull/7069)).
- In-memory `grep` now skips binary files ([#7032](https://github.com/langchain-ai/deepagents/pull/7032)).

## [0.7.28](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.27...deepagents==0.7.28) (2026-10-16)

### Bug Fixes

- Fixed `ContextHubBackend.glob` to honor the `path` argument ([#6998](https://github.com/langchain-ai/deepagents/pull/6998)).

## [0.7.27](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.26...deepagents==0.7.27) (2026-10-16)

### Features

- Keep the main agent informed of asynchronous subagent status updates ([#6853](https://github.com/langchain-ai/deepagents/pull/6853)).

### Bug Fixes

- Pass subagent names to subagents ([#6987](https://github.com/langchain-ai/deepagents/pull/6987)).

## [0.7.26](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.25...deepagents==0.7.26) (2026-10-15)

### Features

- Async subagents now report when they're waiting for a human. ([#6842](https://github.com/langchain-ai/deepagents/pull/6842))
- Async subagent runs now appear under their parent's trace and identify the agent that launched them. ([#6823](https://github.com/langchain-ai/deepagents/pull/6823), [#6836](https://github.com/langchain-ai/deepagents/pull/6836))
- Summarization middleware now exposes its `summarizer`. ([#6900](https://github.com/langchain-ai/deepagents/pull/6900))

### Bug Fixes

- Preserve resolved tool-result paths. ([#6968](https://github.com/langchain-ai/deepagents/pull/6968))

## [0.7.25](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.24...deepagents==0.7.25) (2026-10-13)

### Features

- Read inline skill tool support from model profiles. ([#6879](https://github.com/langchain-ai/deepagents/pull/6879))

### Bug Fixes

- Filesystem permission rules and `interrupt_on` approvals now check both the requested and symlink-resolved paths; previously, `FilesystemBackend` followed symlinks after the check, potentially allowing access to denied paths. Review your rules and approvals for symlink targets. ([#6818](https://github.com/langchain-ai/deepagents/pull/6818))
- Fixed path-glob `grep` in sandboxes. ([#6910](https://github.com/langchain-ai/deepagents/pull/6910))

### Performance Improvements

- Sandbox searches now prefer ripgrep, and sandbox `grep` skips `.git`. ([#6919](https://github.com/langchain-ai/deepagents/pull/6919), [#6910](https://github.com/langchain-ai/deepagents/pull/6910))

## [0.7.24](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.23...deepagents==0.7.24) (2026-10-12)

### Features

- Added fork mode support for async subagents ([#6739](https://github.com/langchain-ai/deepagents/pull/6739)).

### Bug Fixes

- Recover from context overflow during summary calls ([#6864](https://github.com/langchain-ai/deepagents/pull/6864)).
- Preserve the parent rubric during parallel subagent calls ([#6849](https://github.com/langchain-ai/deepagents/pull/6849)).

## [0.7.23](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.22...deepagents==0.7.23) (2026-10-07)

### Features

- Pin skills by name with `pinned_skills` in the SDK ([#6810](https://github.com/langchain-ai/deepagents/pull/6810)).

### Bug Fixes

- Ensure each subagent uses its own `SkillsMiddleware` in the skills slot ([#6820](https://github.com/langchain-ai/deepagents/pull/6820)).

## [0.7.22](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.21...deepagents==0.7.22) (2026-10-05)

### Features

- Load a skill's tools only when the skill is read. ([#6552](https://github.com/langchain-ai/deepagents/pull/6552))

### Bug Fixes

- Reset stale encoding when overwriting text. ([#6737](https://github.com/langchain-ai/deepagents/pull/6737))

## [0.7.21](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.20...deepagents==0.7.21) (2026-09-30)

### Features

- `FilesystemMiddleware` can now store blobs on the backend ([#6550](https://github.com/langchain-ai/deepagents/pull/6550)).

## [0.7.20](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.19...deepagents==0.7.20) (2026-09-29)

### Bug Fixes

- Fixed binary content in `StateBackend.upload_files` being tagged as base64 ([#6551](https://github.com/langchain-ai/deepagents/pull/6551)).

## [0.7.19](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.18...deepagents==0.7.19) (2026-09-24)

### Bug Fixes

- Recover when `read_file` media is rejected ([#6515](https://github.com/langchain-ai/deepagents/pull/6515)).
- Filter unsupported multimodal content through separate middleware ([#6366](https://github.com/langchain-ai/deepagents/pull/6366)).
- Bound tool offload paths and abbreviate long IDs ([#6519](https://github.com/langchain-ai/deepagents/pull/6519)).

## [0.7.18](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.17...deepagents==0.7.18) (2026-09-22)

### Bug Fixes

- Large tool result previews now more clearly explain when output was clipped or truncated, including byte-cap losses, per-line clipping, and showing truncation notices only when truncation occurs. Legacy large-result preview templates are preserved behind a deprecation path. ([#5567](https://github.com/langchain-ai/deepagents/pull/5567), [#5564](https://github.com/langchain-ai/deepagents/pull/5564), [#5563](https://github.com/langchain-ai/deepagents/pull/5563), [#5568](https://github.com/langchain-ai/deepagents/pull/5568))
- Task tool calls now reject unknown argument keys instead of silently dropping unexpected input. ([#6299](https://github.com/langchain-ai/deepagents/pull/6299))
- Correct `FileInfo.size` to represent the file size in bytes across backends. ([#6258](https://github.com/langchain-ai/deepagents/pull/6258))

## [0.7.17](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.16...deepagents==0.7.17) (2026-09-22)

### Bug Fixes

- Preserve the backend exit status when capture metadata is missing. ([#6451](https://github.com/langchain-ai/deepagents/pull/6451))
- Restrict inline file blocks to supported MIME types. ([#6447](https://github.com/langchain-ai/deepagents/pull/6447))

## [0.7.16](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.15...deepagents==0.7.16) (2026-09-21)

### Features

- Reload skills when `skills_metadata` is reset to `None` ([#6364](https://github.com/langchain-ai/deepagents/pull/6364)).

### Bug Fixes

- Reject parallel edits to the same file to prevent conflicting changes ([#6446](https://github.com/langchain-ai/deepagents/pull/6446)).

## [0.7.15](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.14...deepagents==0.7.15) (2026-09-16)

### Bug Fixes

- Gave tool result offloads without IDs unique paths to avoid collisions. ([#6316](https://github.com/langchain-ai/deepagents/pull/6316))
- Propagated subagent state keys for provided subagent middleware. ([#5553](https://github.com/langchain-ai/deepagents/pull/5553))
- Allow colons in model profile keys. ([#6334](https://github.com/langchain-ai/deepagents/pull/6334))
- Required a real Nemotron task transition for built-in profile. ([#6296](https://github.com/langchain-ai/deepagents/pull/6296))

## [0.7.14](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.13...deepagents==0.7.14) (2026-09-13)

### Features

- Updated `read_file` output formatting. ([#5648](https://github.com/langchain-ai/deepagents/pull/5648))

### Bug Fixes

- Bounded compaction recovery and added validation for input budgets. ([#6267](https://github.com/langchain-ai/deepagents/pull/6267))
- Fixed invalid partial tool-call patching and updated imputed `ToolMessage` content in `PatchToolCallsMiddleware`. ([#5430](https://github.com/langchain-ai/deepagents/pull/5430), [#6277](https://github.com/langchain-ai/deepagents/pull/6277))
- Rejected empty `old_string` values in `edit_file` paths. ([#5747](https://github.com/langchain-ai/deepagents/pull/5747))
- Fixed character counting in `ls` and `glob` output. ([#6204](https://github.com/langchain-ai/deepagents/pull/6204))
- Improved `glob` tool results to suggest populating `path` when appropriate. ([#6199](https://github.com/langchain-ai/deepagents/pull/6199))
- Prevented blank read windows from triggering the empty-file warning. ([#5050](https://github.com/langchain-ai/deepagents/pull/5050))

## [0.7.13](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.12...deepagents==0.7.13) (2026-09-02)

### Bug Fixes

- Renamed the SDK subagent mode from `handoff` to `isolated` ([#6030](https://github.com/langchain-ai/deepagents/issues/6030)).

## [0.7.12](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.11...deepagents==0.7.12) (2026-09-01)

### Features

- Added subagent conversation forking in the SDK ([#5714](https://github.com/langchain-ai/deepagents/issues/5714)).

### Bug Fixes

- Fixed glob sorting to tolerate missing `modified_at` values in the SDK ([#4376](https://github.com/langchain-ai/deepagents/issues/4376)).

## [0.7.11](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.10...deepagents==0.7.11) (2026-08-28)

### Features

- Added SDK integration hooks for rubric graders ([#5874](https://github.com/langchain-ai/deepagents/issues/5874))

## [0.7.10](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.9...deepagents==0.7.10) (2026-08-28)

### Bug Fixes

- Prevent local shell commands from stealing TUI input ([#5873](https://github.com/langchain-ai/deepagents/issues/5873))
- Surface sandbox glob failures instead of reporting no matches ([#5566](https://github.com/langchain-ai/deepagents/issues/5566))

## [0.7.9](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.8...deepagents==0.7.9) (2026-08-25)

### Features

- Disabled tracing inputs on middleware. ([#5377](https://github.com/langchain-ai/deepagents/issues/5377))

### Bug fixes

- Exclude tools from execution when `excluded_tools` is set in harness profiles. ([#5809](https://github.com/langchain-ai/deepagents/issues/5809))
- Enforce full criterion coverage in `RubricMiddleware`. ([#5234](https://github.com/langchain-ai/deepagents/issues/5234))
- Clarified zero execute-timeout semantics. ([#5752](https://github.com/langchain-ai/deepagents/issues/5752))

## [0.7.8](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.7...deepagents==0.7.8) (2026-08-20)

### Bug Fixes

- Add `files` state only for state backends ([#5643](https://github.com/langchain-ai/deepagents/issues/5643))

## [0.7.7](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.6...deepagents==0.7.7) (2026-08-18)

### Bug fixes

- Batched concurrent `ContextHubBackend` mutations to improve SDK backend behavior ([#5471](https://github.com/langchain-ai/deepagents/issues/5471)) ([822f7c9](https://github.com/langchain-ai/deepagents/commit/822f7c9b02e6d99bdb46b5545bb2543783c01769)).
- Made `BackendProtocol.glob` recursive for bare patterns ([#5026](https://github.com/langchain-ai/deepagents/issues/5026)) ([32f35d5](https://github.com/langchain-ai/deepagents/commit/32f35d5e01f460549c10365eb569978909f5c969)).

## [0.7.6](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.5...deepagents==0.7.6) (2026-08-13)

### Bug Fixes

- Offload conversation history to a distinct session ID when summarizing. ([#5470](https://github.com/langchain-ai/deepagents/issues/5470))

## [0.7.5](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.4...deepagents==0.7.5) (2026-08-06)

### Bug Fixes

- Identify SDK provider classes that support files. ([#5326](https://github.com/langchain-ai/deepagents/issues/5326))

## [0.7.4](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.3...deepagents==0.7.4) (2026-08-04)

### Features

- Exposed the `execute` exit code in SDK artifacts. ([#5300](https://github.com/langchain-ai/deepagents/issues/5300))

## [0.7.3](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.2...deepagents==0.7.3) (2026-08-03)

### Bug Fixes

- Fixed exact-file `delete` target resolution in the SDK using first-match-wins behavior. ([#5229](https://github.com/langchain-ai/deepagents/issues/5229))

## [0.7.2](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.1...deepagents==0.7.2) (2026-08-03)

### Bug Fixes

- Scrub multimodal content blocks that are unsupported by the model's profile. ([#5194](https://github.com/langchain-ai/deepagents/issues/5194))

## [0.7.1](https://github.com/langchain-ai/deepagents/compare/deepagents==0.7.0...deepagents==0.7.1) (2026-07-30)

### Features

- Mark editable installs in `lc_versions.deepagents` ([#5158](https://github.com/langchain-ai/deepagents/issues/5158))

### Bug Fixes

- Return an empty read for degenerate `read_file` windows ([#5184](https://github.com/langchain-ai/deepagents/issues/5184))
- Warn instead of silently skipping unresolved state schemas ([#5166](https://github.com/langchain-ai/deepagents/issues/5166))

## [0.7.0](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.12...deepagents==0.7.0) (2026-07-29)

See [the docs](https://docs.langchain.com/oss/python/releases/changelog#deepagents-v0-7-0) for curated release notes.

### ⚠ BREAKING CHANGES

* `create_deep_agent` no longer includes `TodoListMiddleware` by default, the `write_todos` tool, `todos` state channel, and todo-planning prompt are now absent. Pass `middleware=[TodoListMiddleware()]` to restore them on the main agent; add it to each `SubAgent`'s middleware to restore them there. ([#4929](https://github.com/langchain-ai/deepagents/issues/4929)) ([9340518](https://github.com/langchain-ai/deepagents/commit/9340518a26c4287f9ad0c543edc9b69106c15154))
* Default agent prompts are now lean: the authored base prompt is empty, and tool-usage prose that duplicates tool schemas is trimmed. `BASE_AGENT_PROMPT` is deprecated (removal in `deepagents==0.9.0`) but remains importable and still returns the previous authored prompt verbatim; pass it as `create_deep_agent(system_prompt=BASE_AGENT_PROMPT)` to restore the old behavior. ([#4859](https://github.com/langchain-ai/deepagents/issues/4859)) ([#4979](https://github.com/langchain-ai/deepagents/issues/4979)) ([a8d1b32](https://github.com/langchain-ai/deepagents/commit/a8d1b32aa4136d0498ba7b48367c8001ac462bd0)) ([d9f54fc](https://github.com/langchain-ai/deepagents/commit/d9f54fc09925171c6c0a933abd33507f85e8851c))
* The built-in tool-usage prompt constants `TASK_SYSTEM_PROMPT`, `ASYNC_TASK_SYSTEM_PROMPT`, `SUMMARIZATION_SYSTEM_PROMPT`, `FILESYSTEM_SYSTEM_PROMPT`, and `EXECUTION_SYSTEM_PROMPT` are removed, and the `system_prompt` default on `SubAgentMiddleware`, `AsyncSubAgentMiddleware`, `SummarizationToolMiddleware`, and `create_summarization_tool_middleware` is now `None`, which injects no prose. Pass your own string to restore prompt text. ([#4859](https://github.com/langchain-ai/deepagents/issues/4859)) ([a8d1b32](https://github.com/langchain-ai/deepagents/commit/a8d1b32aa4136d0498ba7b48367c8001ac462bd0))
* `FilesystemBackend` and `LocalShellBackend` now default to `virtual_mode=True`. Filesystem paths are anchored under `root_dir`, `..` traversal is rejected, and paths resolving outside `root_dir` raise `ValueError`. Previously an unspecified `virtual_mode` emitted a deprecation warning and fell back to `False`, where absolute host paths were used as-is and `..` could escape `root_dir`. Pass `virtual_mode=False` explicitly to restore the old filesystem behavior. ([#4541](https://github.com/langchain-ai/deepagents/issues/4541)) ([540a0fa](https://github.com/langchain-ai/deepagents/commit/540a0fa7eb9a88d82413cf10a5cb5c807d491385))
* Agents now see a destructive, recursive `delete` filesystem tool whenever the backend supports it, and filesystem permissions classify `delete` as a write operation — so an existing rule allowing writes to a path also authorizes recursively deleting that subtree unless a narrower deny or interrupt rule covers the target. Because recursive deletes affect descendants, deny and interrupt checks use bulk path overlap instead of exact-path matching. To keep the previous behavior, add a deny or interrupt rule, or omit `delete` from `FilesystemMiddleware(tools=...)`. Missing paths return a not-found error, `CompositeBackend` reports an unsupported-operation error when a routed sub-backend cannot delete, and the tool is hidden from the model entirely when the backend itself does not implement it. ([#3659](https://github.com/langchain-ai/deepagents/issues/3659)) ([#3691](https://github.com/langchain-ai/deepagents/issues/3691)) ([#3765](https://github.com/langchain-ai/deepagents/issues/3765)) ([#3851](https://github.com/langchain-ai/deepagents/issues/3851)) ([f2a21ec](https://github.com/langchain-ai/deepagents/commit/f2a21ec1606c2560bd2fd5765409a05c2a44edee))
* `write_file` can now create a file if it is missing and replaces it entirely if it already exists, instead of returning a file-exists error. The `write_file` tool description no longer requires reading the file first. There is no "create-only" compatibility mode. Workflows, prompts, tests, or guardrails that relied on the file-exists error to force `edit_file` usage or to protect existing content must omit `write_file`, add explicit permission or interrupt rules, or use `edit_file` where preserving existing content matters. ([#4109](https://github.com/langchain-ai/deepagents/issues/4109)) ([2506fcc](https://github.com/langchain-ai/deepagents/commit/2506fccfac0e09b656d5e2fefe23162f1c762331))
* Removed deprecated backend compatibility shims. Callers must pass concrete `BackendProtocol` instances (not factories), configure `StoreBackend` with an explicit `namespace`, and use the current `ls` / `glob` / `grep` / `ReadResult` APIs. ([#4541](https://github.com/langchain-ai/deepagents/issues/4541)) ([540a0fa](https://github.com/langchain-ai/deepagents/commit/540a0fa7eb9a88d82413cf10a5cb5c807d491385))
* The deprecated `files_update` attribute and constructor keyword are removed from `WriteResult` and `EditResult`. Custom backends must stop passing `files_update=`, and callers must stop reading `result.files_update`; state writes are emitted directly by `StateBackend`. ([#4541](https://github.com/langchain-ai/deepagents/issues/4541)) ([540a0fa](https://github.com/langchain-ai/deepagents/commit/540a0fa7eb9a88d82413cf10a5cb5c807d491385))
* Removed the deprecated `BackendProtocol` methods `ls_info`, `als_info`, `glob_info`, `aglob_info`, `grep_raw`, and `agrep_raw`. Use `ls` / `glob` / `grep` and their async counterparts. ([#4541](https://github.com/langchain-ai/deepagents/issues/4541)) ([540a0fa](https://github.com/langchain-ai/deepagents/commit/540a0fa7eb9a88d82413cf10a5cb5c807d491385))
* `SummarizationMiddleware(history_path_prefix=...)` was removed and now raises `TypeError`. Configure `CompositeBackend(artifacts_root=...)` instead. ([#4541](https://github.com/langchain-ai/deepagents/issues/4541)) ([540a0fa](https://github.com/langchain-ai/deepagents/commit/540a0fa7eb9a88d82413cf10a5cb5c807d491385))
* Agent-facing `ls` and `glob` tool output now renders empty results as `No files found` instead of `[]`; direct backend APIs continue to return structured empty `LsResult` and `GlobResult` values. Callers that parse tool output should update those checks. ([#3709](https://github.com/langchain-ai/deepagents/issues/3709)) ([efafd1e](https://github.com/langchain-ai/deepagents/commit/efafd1e070aeae8901ee3123c7fcbf1815a33c4f))
* `read_file` no longer renders raw text with a fixed-width `cat -n`-style line-number gutter and tab separator. Line and continuation markers are dynamically aligned and separated from source content by two spaces, and the `LINE_NUMBER_WIDTH` constant is removed from `deepagents.backends.utils` and `deepagents.middleware.filesystem`. Callers that parse raw tool output should update those parsers. ([#4561](https://github.com/langchain-ai/deepagents/issues/4561)) ([cf057b4](https://github.com/langchain-ai/deepagents/commit/cf057b4bcdb77ad67014f7dabe71e71f2366c95e))

### Features

* Custom middleware passed to `create_deep_agent(..., middleware=[...])` can replace a default middleware instance when `.name` matches, so defaults such as `SummarizationMiddleware` can be overridden without also excluding the built-in instance. ([#4251](https://github.com/langchain-ai/deepagents/issues/4251)) ([90c8472](https://github.com/langchain-ai/deepagents/commit/90c8472ae226394a186bf2075459645c2056db7d))
* `FilesystemMiddleware(tools=[...])` accepts a keyword-only allowlist of built-in filesystem tools, typed by the newly exported `FsToolName` literal (`"ls"`, `"read_file"`, `"write_file"`, `"edit_file"`, `"delete"`, `"glob"`, `"grep"`, `"execute"`); pass `"all"` or omit the argument to keep every tool. A list must include `"read_file"` or the constructor raises `ValueError`. Omitted built-in tools are non-executable, and custom user tools are unaffected. ([#4325](https://github.com/langchain-ai/deepagents/issues/4325)) ([#4698](https://github.com/langchain-ai/deepagents/issues/4698)) ([704a70d](https://github.com/langchain-ai/deepagents/commit/704a70dddbd59b8c6abf658a4211c76bce1445f0)) ([9709525](https://github.com/langchain-ai/deepagents/commit/970952550e8f53cd89a64a4ee98969ce757693ff))
* Shorten LLM-facing descriptions for the `task` tool and filesystem tools (`read_file`, `grep`, `edit_file`, `glob`, `execute`). ([#5009](https://github.com/langchain-ai/deepagents/issues/5009)) ([761f5f0](https://github.com/langchain-ai/deepagents/commit/761f5f0882dee186f2700f3c903829a5542626fe))
* `GrepResult` and `GlobResult` now carry a `truncated` flag so supporting backends can return valid partial results when a match cap or backend deadline is reached; agent-facing tool output adds a note telling the model to narrow the search. `FilesystemBackend` returns partial `grep` and `glob` results on its backend timeout rather than erroring, while other backend or middleware timeouts may still return errors. Its `glob` also gains brace expansion such as `*.{py,md}` (already supported by the state and store backends). ([#4063](https://github.com/langchain-ai/deepagents/issues/4063)) ([ef591e7](https://github.com/langchain-ai/deepagents/commit/ef591e7a86b13bbdcb0fdedd45a8f1fe33573839))
* The agent-facing `grep` match cap is configurable: `FilesystemMiddleware(grep_max_count=...)` sets the default (`1000`; `None` disables it) and the model can override it per call through the tool's new `max_count` argument. `grep` / `agrep` on `BackendProtocol` and all built-in backends accept a keyword-only `max_count`. Local ripgrep output is streamed and terminated once the cap is reached. Direct `FilesystemBackend.grep()` callers can request surrounding lines with keyword-only `context_lines`. ([#4570](https://github.com/langchain-ai/deepagents/issues/4570)) ([#4706](https://github.com/langchain-ai/deepagents/issues/4706)) ([8e86f5e](https://github.com/langchain-ai/deepagents/commit/8e86f5ecc8908762a2c748880287f190dde70600)) ([65230df](https://github.com/langchain-ai/deepagents/commit/65230df6f91d2bbe5f83d4d938da6bfac52363a1))
* Paginated built-in `read_file` responses report the returned source-line range and next `offset`; total and remaining line counts are included when the backend knows the file length. Resume offsets remain safe when sandbox or middleware limits shorten the visible page. ([#4540](https://github.com/langchain-ai/deepagents/issues/4540)) ([8321194](https://github.com/langchain-ai/deepagents/commit/83211940a2cdf4c52ac21a6cde8647716a998504))
* Optional video frame extraction for `read_file`, enabled by the new `deepagents[video]` extra. Video files are sampled into JPEG frames, with `offset` and `limit` interpreted as seconds. Without the extra, existing generic video/file content-block behavior remains. ([#4094](https://github.com/langchain-ai/deepagents/issues/4094)) ([b927147](https://github.com/langchain-ai/deepagents/commit/b927147d026749c6c790bb06c9853515dabf579c))
* `FilesystemMiddleware` can capture oversized `execute` tool output directly inside the sandbox artifact path on compatible, opted-in `BaseSandbox` implementations to reduce round trips; `LangSmithSandbox` opts in by default. ([#4230](https://github.com/langchain-ai/deepagents/issues/4230)) ([02f5bd7](https://github.com/langchain-ai/deepagents/commit/02f5bd7bc02f2baaf5a1eefce7d686ba62493647))
* Automatically enable Fireworks prompt-cache session affinity when a compatible `langchain-fireworks` installation is available. ([#4598](https://github.com/langchain-ai/deepagents/issues/4598)) ([5d878bf](https://github.com/langchain-ai/deepagents/commit/5d878bf1341afc3f96398733b7ef18eec4b66139))
* Add a built-in NVIDIA Nemotron 3 Ultra harness profile and NVIDIA NIM app-origin attribution. ([#4192](https://github.com/langchain-ai/deepagents/issues/4192)) ([#4455](https://github.com/langchain-ai/deepagents/issues/4455)) ([d5a60ec](https://github.com/langchain-ai/deepagents/commit/d5a60ece7379c37c81edcef2cd6c2811ddc90c9a)) ([4cb4749](https://github.com/langchain-ai/deepagents/commit/4cb47491b024991322b7c24062c58cbcdc26a727))
* `RubricMiddleware` now accepts any positive `max_iterations` cap instead of enforcing a hard upper bound. ([#4405](https://github.com/langchain-ai/deepagents/issues/4405)) ([d6692a7](https://github.com/langchain-ai/deepagents/commit/d6692a7c713490f170b17510d613e02ee37574ab))

### Bug Fixes

* Keep fields marked with `PrivateStateAttr`, including fields declared through `create_deep_agent(state_schema=...)`, out of subagent inputs and returned parent-state updates. ([#4587](https://github.com/langchain-ai/deepagents/issues/4587)) ([a4662c0](https://github.com/langchain-ai/deepagents/commit/a4662c07296c378045006c9f45ed1d12bd1a9da6))
* Preserve `ContextT` through the `create_deep_agent(..., middleware=[...])` type annotation so type checkers accept context-aware middleware when a matching `context_schema` is passed. ([#4055](https://github.com/langchain-ai/deepagents/issues/4055)) ([7be76c7](https://github.com/langchain-ai/deepagents/commit/7be76c752117e6e61dcdc931ea5147261fad6768))
* Accept YAML list values as well as comma-separated strings for skill `allowed-tools` frontmatter, and make skill truncation warnings actionable with field name, path, length, configured limit, and impact. ([#4140](https://github.com/langchain-ai/deepagents/issues/4140)) ([#4141](https://github.com/langchain-ai/deepagents/issues/4141)) ([d62534c](https://github.com/langchain-ai/deepagents/commit/d62534c86b87a91aca16c6bfb71209232d69a6ec)) ([2f5f5b8](https://github.com/langchain-ai/deepagents/commit/2f5f5b85793d944167a42e8d5b8e0a11bb1e3932))
* Align filesystem instructions with the tools that remain after allowlist and backend-capability filtering, so agents no longer reference hidden `grep`/`glob` tools or prohibit equivalent shell search when dedicated search tools are unavailable. ([#4920](https://github.com/langchain-ai/deepagents/issues/4920)) ([#4921](https://github.com/langchain-ai/deepagents/issues/4921)) ([d3650c7](https://github.com/langchain-ai/deepagents/commit/d3650c7b1f5ca968abd72345a511719d4ba65907)) ([b65cc00](https://github.com/langchain-ai/deepagents/commit/b65cc0076caab2e35c07598055b8b338a47e5e1a))
* Propagate default-backend failures from `CompositeBackend.ls("/")` and `CompositeBackend.als("/")` instead of returning successful route-only listings. ([#4925](https://github.com/langchain-ai/deepagents/issues/4925)) ([4c3b166](https://github.com/langchain-ai/deepagents/commit/4c3b1667035e3be6ae88cf8c431e0d6f143d2ff4))
* Correct `CompositeBackend.glob` / `CompositeBackend.aglob` routing so explicit default-backend paths such as `/tools` do not also return files from routed backends such as `/memories`. ([#4531](https://github.com/langchain-ai/deepagents/issues/4531)) ([cbdb0a7](https://github.com/langchain-ai/deepagents/commit/cbdb0a7df8cd4bbacff9ca7ac2e42232ef290c10))
* Propagate default- and routed-backend failures from root `CompositeBackend.glob(..., path=None)` / `aglob(..., path=None)` and `path="/"` searches instead of returning incomplete successful results. ([#4063](https://github.com/langchain-ai/deepagents/issues/4063)) ([ef591e7](https://github.com/langchain-ai/deepagents/commit/ef591e7a86b13bbdcb0fdedd45a8f1fe33573839))
* Constrain sandbox `glob` and slash-pattern `grep` searches to their declared search root by treating leading `/` as search-root-relative, rejecting `..` traversal segments, and filtering symlink-resolved matches outside the root. ([#4588](https://github.com/langchain-ai/deepagents/issues/4588)) ([c6c7213](https://github.com/langchain-ai/deepagents/commit/c6c72139b3ee7d090f657dd19ced59a9bbc41140))
* Unify `grep(..., glob=...)` include-glob semantics across filesystem and in-memory backends: basename patterns like `*.py` match at any depth, and slash-containing patterns like `src/**/*.py` match relative paths consistently. ([#3936](https://github.com/langchain-ai/deepagents/issues/3936)) ([feab6e0](https://github.com/langchain-ai/deepagents/commit/feab6e0b3762aa42fa458af16d0a3e8d04d8b075))
* Improve agent-facing `grep` descriptions and no-match hints to steer regex-looking patterns toward literal searches, route slash-containing sandbox include-globs correctly, and shorten default search timeouts so bad patterns and huge trees return guidance faster. ([#4168](https://github.com/langchain-ai/deepagents/issues/4168)) ([b1dbf5e](https://github.com/langchain-ai/deepagents/commit/b1dbf5e66ac81a9fd95abf6987ba058bb14a5edf))
* Align sandbox delete behavior with other backends by returning not-found errors for missing paths, and avoid over-blocking unrelated sibling deletes when deny rules use glob patterns. ([#4321](https://github.com/langchain-ai/deepagents/issues/4321)) ([d77496b](https://github.com/langchain-ai/deepagents/commit/d77496b969b9c59ce1c7c44e2085e5388e12c306))
* Improve rubric grader failure diagnostics with configured model, structured-output strategy, and integer HTTP status when available. ([#4938](https://github.com/langchain-ai/deepagents/issues/4938)) ([#4967](https://github.com/langchain-ai/deepagents/issues/4967)) ([f51d3a0](https://github.com/langchain-ai/deepagents/commit/f51d3a0145a0301317c36b0ae15263007dacd6f1)) ([bca70aa](https://github.com/langchain-ai/deepagents/commit/bca70aa1f30ee1472809894e2474a76e4ff2f8bd))
* Emit `max_iterations_reached` as the terminal `RubricMiddleware` status when the iteration cap is exhausted, instead of a final `needs_revision` event that will not loop. ([#4406](https://github.com/langchain-ai/deepagents/issues/4406)) ([a51c8d2](https://github.com/langchain-ai/deepagents/commit/a51c8d2b1723d143439a1466f5a49a52c442bdfc))
* Handle missing async subagent URLs consistently in `check_async_task` and `cancel_async_task`. ([#3967](https://github.com/langchain-ai/deepagents/issues/3967)) ([b0d92c0](https://github.com/langchain-ai/deepagents/commit/b0d92c0f38ca0aa037b56e26b2b0d322cdd07856))

### Performance Improvements

* Run LangSmith sandbox commands over the async client. ([#5061](https://github.com/langchain-ai/deepagents/issues/5061)) ([0d08747](https://github.com/langchain-ai/deepagents/commit/0d0874710615df2c89c3c30e56bfdabb73b44d99))

## [0.6.12](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.11...deepagents==0.6.12) (2026-06-25)

This release adds the `deepagents[aws]` extra, which installs `langchain-aws` so Bedrock users get the automatic prompt caching integration added in [#4108](https://github.com/langchain-ai/deepagents/issues/4108).

### Features

* Add Bedrock prompt caching middleware ([#4108](https://github.com/langchain-ai/deepagents/issues/4108)) ([a398382](https://github.com/langchain-ai/deepagents/commit/a398382c85ce518ea1b7f365e49df905cdcd498b))

### Bug Fixes

* Preserve media references in summarization archives ([#3990](https://github.com/langchain-ai/deepagents/issues/3990)) ([2d6fb53](https://github.com/langchain-ai/deepagents/commit/2d6fb53cd8c94680a42fa9d7041509ff78050616))

## [0.6.11](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.10...deepagents==0.6.11) (2026-06-18)

### Bug Fixes

* Route `BaseSandbox async` helpers through aexecute ([#3996](https://github.com/langchain-ai/deepagents/issues/3996)) ([52dcf1a](https://github.com/langchain-ai/deepagents/commit/52dcf1a42cb00dd614b336038e4398472f78859d))

## [0.6.10](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.9...deepagents==0.6.10) (2026-06-13)

### Bug Fixes

* Compare provider in `model_matches_spec` ([#3943](https://github.com/langchain-ai/deepagents/issues/3943)) ([34244b6](https://github.com/langchain-ai/deepagents/commit/34244b6aebde4c237758dacedccdc3e22f3ca8e5))

## [0.6.9](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.8...deepagents==0.6.9) (2026-06-12)

### Features

* Support configurable subagent response format ([#3882](https://github.com/langchain-ai/deepagents/issues/3882)) ([b0e4d7a](https://github.com/langchain-ai/deepagents/commit/b0e4d7aa8d0ad58c65bddef3835e539b3d5b2a99))

### Bug Fixes

* Don't swallow `TypeError` from custom `token_counter` ([#3927](https://github.com/langchain-ai/deepagents/issues/3927)) ([a6ec9d0](https://github.com/langchain-ai/deepagents/commit/a6ec9d0e797a8b8a7d53d7debb197bb25e80be41))
* Handle `Overwrite`-wrapped messages in tool result interception ([#3905](https://github.com/langchain-ai/deepagents/issues/3905)) ([a043c5a](https://github.com/langchain-ai/deepagents/commit/a043c5a6717374c405a3ed740cfdafdd196f5f21))
* Keep private state out of subagent propagation ([#3542](https://github.com/langchain-ai/deepagents/issues/3542)) ([7ff9553](https://github.com/langchain-ai/deepagents/commit/7ff9553fc057a682ba503ebfe9a870adb51ab848))
* Make sync glob timeout bound wall-clock time ([#3866](https://github.com/langchain-ai/deepagents/issues/3866)) ([cba6caf](https://github.com/langchain-ai/deepagents/commit/cba6caf8f708133381506ecc9e217e7e3ca1c7f2))
* Normalize read slices after windowing ([#3888](https://github.com/langchain-ai/deepagents/issues/3888)) ([33d900c](https://github.com/langchain-ai/deepagents/commit/33d900c98b686aa7e7782d0be3019010ced5f03a))
* Stream Python grep fallback ([#3886](https://github.com/langchain-ai/deepagents/issues/3886)) ([3673d95](https://github.com/langchain-ai/deepagents/commit/3673d95d41aa00f03fbfe2083e46afa485800f3a))

### Performance Improvements

* Count tokens once per model call in summarization middleware ([#3877](https://github.com/langchain-ai/deepagents/issues/3877)) ([6558c8c](https://github.com/langchain-ai/deepagents/commit/6558c8ca3d8e10e3309f95c807e740914af3175f))
* Cache filesystem system prompts ([#3889](https://github.com/langchain-ai/deepagents/issues/3889)) ([2f432ba](https://github.com/langchain-ai/deepagents/commit/2f432ba63687d7c8488d5d41d0551d02b4ae00b4))
* Cache grep glob matchers ([#3887](https://github.com/langchain-ai/deepagents/issues/3887)) ([eae3cf1](https://github.com/langchain-ai/deepagents/commit/eae3cf148de3f8c8ee9ffd8af6e5a5e06cce9d6f))

## [0.6.8](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.7...deepagents==0.6.8) (2026-06-03)

### Features

* Add interrupt mode to filesystem permissions ([#3505](https://github.com/langchain-ai/deepagents/issues/3505)) ([a090162](https://github.com/langchain-ai/deepagents/commit/a090162ea9fd950c54fac874b8a165ca770fd2dc))
* Surface subagents via inherited `lc_agent_name` projection ([e0a1ed2](https://github.com/langchain-ai/deepagents/commit/e0a1ed24e6b44c31d0aac3358aeee0d6cb66b2c4))

### Bug Fixes

* Pass through summarization factory prompt knobs ([#3559](https://github.com/langchain-ai/deepagents/issues/3559)) ([a663cad](https://github.com/langchain-ai/deepagents/commit/a663cad8858a78a5d063af0c51bb789bfb1aba2b))
* Align `glob` path default with `grep` ([#3666](https://github.com/langchain-ai/deepagents/issues/3666)) ([ece8e75](https://github.com/langchain-ai/deepagents/commit/ece8e752059f493254753194bcf59befe54b3556))
* Guard empty binary reads with empty-content warning ([#3675](https://github.com/langchain-ai/deepagents/issues/3675)) ([2c2cec8](https://github.com/langchain-ai/deepagents/commit/2c2cec87476f06e32c7b09cedd2c44e0c713f147))
* Surface missing path errors in `FilesystemBackend.ls` ([#3574](https://github.com/langchain-ai/deepagents/issues/3574)) ([4c28760](https://github.com/langchain-ai/deepagents/commit/4c28760abbbe43117f2118793f11ff9d4f71761e))
* Timeout python grep fallback ([#1937](https://github.com/langchain-ai/deepagents/issues/1937)) ([665a18e](https://github.com/langchain-ai/deepagents/commit/665a18e7fe7f291319af6780328384cc658af899))

### Warnings

* We are dropping public exports of `SubagentRunStream`, `AsyncSubagentRunStream`, and `SubagentTransformer`. These are internal classes for the beta `stream_events(version="v3")` streaming API that should not have been publicly exported in the first place.

## [0.6.7](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.6...deepagents==0.6.7) (2026-05-30)

### Bug Fixes

* Propagate goto and graph in Commands returned by tools ([#3391](https://github.com/langchain-ai/deepagents/issues/3391)) ([d92aef6](https://github.com/langchain-ai/deepagents/commit/d92aef68f70a5e5277c43a50581e7895e682c417))
* Handle base64 reads with unknown file extensions ([#3663](https://github.com/langchain-ai/deepagents/issues/3663)) ([9857a08](https://github.com/langchain-ai/deepagents/commit/9857a08b6144b2f001d8f4bf03ac2f254c6b2da4))
* Export `DeepAgentState` ([#3653](https://github.com/langchain-ai/deepagents/issues/3653)) ([14a9047](https://github.com/langchain-ai/deepagents/commit/14a904757c2d9d797945b6ea1bc9529f1f8cf369))

## [0.6.6](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.5...deepagents==0.6.6) (2026-05-28)

### Features

* Allow passing `state_schema` in `create_deep_agent` ([#3642](https://github.com/langchain-ai/deepagents/issues/3642)) ([37839bd](https://github.com/langchain-ai/deepagents/commit/37839bd7d67fba8c11ff0ccaaa8ac92b39609450))

## [0.6.5](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.4...deepagents==0.6.5) (2026-05-28)

### Features

* `RubricMiddleware` for self-evaluated agent iteration ([#3529](https://github.com/langchain-ai/deepagents/issues/3529)) ([5b8d44d](https://github.com/langchain-ai/deepagents/commit/5b8d44d65c6ec43084687019cf00a37d730ac2fa))
* Log when grep falls back from ripgrep ([#3593](https://github.com/langchain-ai/deepagents/issues/3593)) ([379b1ff](https://github.com/langchain-ai/deepagents/commit/379b1ffdc3ccf5da72d9f7264d531be108f0b36d))

### Bug Fixes

* Use `file_path` kwarg in `read_file` examples ([#3630](https://github.com/langchain-ai/deepagents/issues/3630)) ([97946ee](https://github.com/langchain-ai/deepagents/commit/97946ee09eb167c63d8c07f8bb116f40cfc9603f))
* `read_file` pagination skipping lines after wrapping ([#3641](https://github.com/langchain-ai/deepagents/issues/3641)) ([390551d](https://github.com/langchain-ai/deepagents/commit/390551d61d57ce68c2a80ed78c07eaa8e985908b))
* Handle `None` state in messages delta reducer ([#3636](https://github.com/langchain-ai/deepagents/issues/3636)) ([5a6d920](https://github.com/langchain-ai/deepagents/commit/5a6d920d9dec2199cbe743062a5cc1ff8f298567))
* Return grep errors for sandbox exec failures ([#3637](https://github.com/langchain-ai/deepagents/issues/3637)) ([f87d61f](https://github.com/langchain-ai/deepagents/commit/f87d61f01a23fcfb994e88b7f9324d404e66faef))

## [0.6.4](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.3...deepagents==0.6.4) (2026-05-26)

### Bug Fixes

* Grep crashing when files vanish mid-walk ([#3592](https://github.com/langchain-ai/deepagents/issues/3592)) ([0b8301b](https://github.com/langchain-ai/deepagents/commit/0b8301b2067f7dbbc83ebcf05c52e91413260fd1))
* Stable `HumanMessage` IDs across resumed threads ([#3591](https://github.com/langchain-ai/deepagents/issues/3591)) ([82c3194](https://github.com/langchain-ai/deepagents/commit/82c31947f9dc938ffc71e1cea96d162a39aec3a1))

## [0.6.3](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.2...deepagents==0.6.3) (2026-05-20)

### Bug Fixes

* Anchor ripgrep glob to search root ([#3454](https://github.com/langchain-ai/deepagents/issues/3454)) ([e50fa3f](https://github.com/langchain-ai/deepagents/commit/e50fa3f00ab1b1a84bbaed74bf7e89118b7c2d82))
* Assign UUIDs to ID-less messages in _messages_delta_reducer ([#3513](https://github.com/langchain-ai/deepagents/issues/3513)) ([6d959ad](https://github.com/langchain-ai/deepagents/commit/6d959ade30655eae3967c9809994434e0bbd1148))
* Clarify skill source labels in system prompt ([#3464](https://github.com/langchain-ai/deepagents/issues/3464)) ([fc6a24f](https://github.com/langchain-ai/deepagents/commit/fc6a24f18829cf3f36089945226edfa50d52ab9e))
* Strip HTML comments from memory content before system prompt injection ([#3462](https://github.com/langchain-ai/deepagents/issues/3462)) ([bfbb8bc](https://github.com/langchain-ai/deepagents/commit/bfbb8bc5575ebd1ba9aa29430f6d2f86c24b7d3c))

## [0.6.2](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.1...deepagents==0.6.2) (2026-05-18)

### Features

* Add `system_prompt` override slot to memory, skills, and summarization ([#3451](https://github.com/langchain-ai/deepagents/issues/3451)) ([7583f4a](https://github.com/langchain-ai/deepagents/commit/7583f4aff6a6044bc987ee7980d322bb5c791428))

### Bug Fixes

* Patch invalid tool calls ([#3386](https://github.com/langchain-ai/deepagents/issues/3386)) ([c916d1b](https://github.com/langchain-ai/deepagents/commit/c916d1b2e3a81dcd4fb2e595d6b971923c18fa31))
* Align `MemoryMiddleware` prompt with investigate-first agent behavior ([#2461](https://github.com/langchain-ai/deepagents/issues/2461)) ([d53c8f4](https://github.com/langchain-ai/deepagents/commit/d53c8f4f481288a3aa04a5e62362beba6ed7e57a))
* Subagents: update prompt and make fetching of last message more robust ([#3406](https://github.com/langchain-ai/deepagents/issues/3406)) ([4421bec](https://github.com/langchain-ai/deepagents/commit/4421bec94ffbe1f3a3bf44088ebcf8ab8c24a736))
* Summarization: truncate trailing ToolMessages to keep context within `keep` limit ([#3405](https://github.com/langchain-ai/deepagents/issues/3405)) ([bee514f](https://github.com/langchain-ai/deepagents/commit/bee514fd24862b6b22a5993eb8b6cfc69e42dd80))
* Surface OS errors in sandbox ls/read/edit/glob ([#3359](https://github.com/langchain-ai/deepagents/issues/3359)) ([7598bd9](https://github.com/langchain-ai/deepagents/commit/7598bd93f72b609a46da64f7c458c42ac07a0f3a))

## [0.6.1](https://github.com/langchain-ai/deepagents/compare/deepagents==0.6.0...deepagents==0.6.1) (2026-05-12)

### Bug Fixes

* Import profile re-exports from leaf modules ([#3377](https://github.com/langchain-ai/deepagents/issues/3377)) ([ca99391](https://github.com/langchain-ai/deepagents/commit/ca99391668ea1510932f8e9097e8ed3c0caadf73))

## [0.6.0](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.9...deepagents==0.6.0) (2026-05-12)

### Features

* **[`CodeInterpreterMiddleware`](https://pypi.org/project/langchain-quickjs)**: (experimental) `deepagents` now supports code execution and programmatic tool calling through a scoped QuickJS runtime. Install via the optional dependency: `deepagents[quickjs]`.
* Support for `version="v3"` in `stream_events` / `astream_events`. Refer to the [event streaming](https://docs.langchain.com/oss/python/deepagents/event-streaming) guide for details.

## [0.5.9](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.8...deepagents==0.5.9) (2026-05-10)

### Bug Fixes

* Import profile symbols directly from `harness_profiles` ([#3291](https://github.com/langchain-ai/deepagents/issues/3291)) ([503453c](https://github.com/langchain-ai/deepagents/commit/503453c06f7e0545914789a07ddba6ca6b0c8ec5))

## [0.5.8](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.7...deepagents==0.5.8) (2026-05-08)

### Bug Fixes

* Avoid deprecated-use warnings in `CompositeBackend` path mutation ([#3244](https://github.com/langchain-ai/deepagents/issues/3244)) ([64d45f6](https://github.com/langchain-ai/deepagents/commit/64d45f67c86edb4df2ced0e7b82f1a8fd158ec8c))

## [0.5.7](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.6...deepagents==0.5.7) (2026-05-05)

### Bug Fixes

* Auto-added GP subagent inherits parent permissions ([#3131](https://github.com/langchain-ai/deepagents/issues/3131)) ([0d55b3b](https://github.com/langchain-ai/deepagents/commit/0d55b3ba8b974d06b1e0f52893f33e44496bff8b))
* Default OpenRouter routing to ignore Azure upstream ([#3157](https://github.com/langchain-ai/deepagents/issues/3157)) ([01a9113](https://github.com/langchain-ai/deepagents/commit/01a911379d368fab8280cd827c38776800abe7b8))

## [0.5.6](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.5...deepagents==0.5.6) (2026-05-01)

### Bug Fixes

* Add write preflight and native read to langsmith sandbox ([#2695](https://github.com/langchain-ai/deepagents/issues/2695)) ([741221c](https://github.com/langchain-ai/deepagents/commit/741221c9d8b65a535816e318ee24d3c19a4bde80))
* Propagate `CompiledSubAgent` name into `lc_agent_name` metadata ([#3045](https://github.com/langchain-ai/deepagents/issues/3045)) ([f671e6b](https://github.com/langchain-ai/deepagents/commit/f671e6b18aa49700a535f7b48441662b67dafef9))

## [0.5.5](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.4...deepagents==0.5.5) (2026-04-30)

### Bug Fixes

* Harden `FilesystemBackend` against symlink loops ([#3035](https://github.com/langchain-ai/deepagents/issues/3035)) ([abd02f9](https://github.com/langchain-ai/deepagents/commit/abd02f99ef12030bdfe429fdc3ad80a2785bea61))
* Surface EOF-newline mismatch in `edit_file` ([#3031](https://github.com/langchain-ai/deepagents/issues/3031)) ([d30686e](https://github.com/langchain-ai/deepagents/commit/d30686ec82d36a0e9430f7c512c34835aba2c079))
* Prevent stdin hang by passing `DEVNULL` ([#2427](https://github.com/langchain-ai/deepagents/issues/2427)) ([5bf5fae](https://github.com/langchain-ai/deepagents/commit/5bf5fae8d93beba90628f2f71e3e79817a36ac9e))

## [0.5.4](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.3...deepagents==0.5.4) (2026-04-29)

### Highlights

Until this release, `deepagents` shipped a single set of prompts, tools, and middleware tuned to work across *all* model families. Today's headline change is **harness profiles** — a declarative override layer for the parts of the harness that vary per model (system-prompt prefix/suffix, tool inclusion and naming, middleware selection, subagent configuration, skills). `ProviderProfile` shapes how `resolve_model` builds the client; `HarnessProfile` / `HarnessProfileConfig` shape how `create_deep_agent` assembles the agent. Both are keyed by provider (`"openai"`) or full `provider:model` spec (`"openai:gpt-5.4"`), and registrations are additive — your call site doesn't change when you swap models.

We currently ship built-ins for OpenAI and Anthropic out of the box, drawn directly from each vendor's published prompting guides (Codex's `apply_patch` / `shell_command` conventions, Claude's tool-result reflection and active-investigation patterns, etc.). On a curated tau2-bench subset, applying these profiles produced a 10–20 point lift over the default harness (GPT-5.3 Codex: 33% -> 53%; Claude Opus 4.7: 43% -> 53%). Third-party plugins can register via the `deepagents.provider_profiles` and `deepagents.harness_profiles` entry points.

See the [profiles documentation](https://docs.langchain.com/oss/python/deepagents/profiles) for the full field surface, merge semantics, and plugin packaging.

### Features

* Profiles API ([#2892](https://github.com/langchain-ai/deepagents/issues/2892)) ([7365ad1](https://github.com/langchain-ai/deepagents/commit/7365ad1600064eec616c5de970320104189ddf80))
* `ls_agent_type` configurable tag on subagent runs ([#2788](https://github.com/langchain-ai/deepagents/issues/2788)) ([3bcc51a](https://github.com/langchain-ai/deepagents/commit/3bcc51a95da80094cfc8bc4bcaf25dc1e2ad8f44))

### Bug Fixes

* Normalize Windows backslash paths before `PurePosixPath` processing ([#1859](https://github.com/langchain-ai/deepagents/issues/1859)) ([e1c1d50](https://github.com/langchain-ai/deepagents/commit/e1c1d5024729f5205eaa42bf6a9bc1c93a30d043))
* Preserve CRLF line endings in sandbox edit ([#2899](https://github.com/langchain-ai/deepagents/issues/2899)) ([291aebe](https://github.com/langchain-ai/deepagents/commit/291aebe21f8a53604a2bf47daa120761dace2536))
* Support read-your-writes in `StateBackend` ([#2991](https://github.com/langchain-ai/deepagents/issues/2991)) ([0924869](https://github.com/langchain-ai/deepagents/commit/0924869bc3d946577e7c3cbc79a86e4aaf522edd))
* Treat boundary-truncated UTF-8 in `read()` prefix check as text ([#2980](https://github.com/langchain-ai/deepagents/issues/2980)) ([c36ebc7](https://github.com/langchain-ai/deepagents/commit/c36ebc7be5840e9008279992741c67a8377ffc01))
* Use `configurable` directly instead of tracing context for subagent tagging ([#2845](https://github.com/langchain-ai/deepagents/issues/2845)) ([bd6ec6b](https://github.com/langchain-ai/deepagents/commit/bd6ec6bcebcdcc26f6b79e2c55611074b0e01631))

### Performance Improvements

* Add cache breakpoint to `MemoryMiddleware` ([#2713](https://github.com/langchain-ai/deepagents/issues/2713)) ([1699f3a](https://github.com/langchain-ai/deepagents/commit/1699f3aea710985087b16318bb8e6f6e80e02a1b))

## [0.5.3](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.2...deepagents==0.5.3) (2026-04-14)

### Features

* **sdk:** add static structured output to subagent response ([#2437](https://github.com/langchain-ai/deepagents/issues/2437)) ([6e57731](https://github.com/langchain-ai/deepagents/commit/6e57731fc6d908ac1ebe131e782696a4776147e9))
* **sdk:** deprecate `model=None` in `create_deep_agent` ([#2677](https://github.com/langchain-ai/deepagents/issues/2677)) ([149df41](https://github.com/langchain-ai/deepagents/commit/149df415d17f3cf3b7eb0bd1e78460112bfa9b04))

### Bug Fixes

* **sdk:** skill loading should default to 1000 lines ([#2721](https://github.com/langchain-ai/deepagents/issues/2721)) ([badc4d3](https://github.com/langchain-ai/deepagents/commit/badc4d3921ae0ede4305f44f85fa7266df9465e7))

## [0.5.2](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.1...deepagents==0.5.2) (2026-04-10)

### Features

* Permissions system for filesystem access control ([#2633](https://github.com/langchain-ai/deepagents/issues/2633)) ([41dc759](https://github.com/langchain-ai/deepagents/commit/41dc7597deb3fc036f1f850e68edc3c0870f27da))
  * Scope permissions to routes for composite backends with sandbox default ([#2659](https://github.com/langchain-ai/deepagents/issues/2659)) ([6dd6122](https://github.com/langchain-ai/deepagents/commit/6dd612237a7ee707726c4cafc4b691704e4cdb37))
  * Raise `ValueError` for permission paths without leading slash and path traversal ([#2665](https://github.com/langchain-ai/deepagents/issues/2665)) ([723d27d](https://github.com/langchain-ai/deepagents/commit/723d27dcdce03cc9ffaa757c70533f0134a43a44))
* Implement `upload_files` for `StateBackend` ([#2661](https://github.com/langchain-ai/deepagents/issues/2661)) ([5798345](https://github.com/langchain-ai/deepagents/commit/579834513a4ba1a024a52fc4edf918f526eab5f2))

### Bug Fixes

* Catch `PermissionError` in `FilesystemBackend` ripgrep ([#2571](https://github.com/langchain-ai/deepagents/issues/2571)) ([3d5d673](https://github.com/langchain-ai/deepagents/commit/3d5d67349c8e88e33af98137db9634742f018cb0))

## [0.5.1](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.0...deepagents==0.5.1) (2026-04-07)

### Features

* **sdk:** `BASE_AGENT_PROMPT` tweaks ([#2541](https://github.com/langchain-ai/deepagents/issues/2541)) ([812eef1](https://github.com/langchain-ai/deepagents/commit/812eef185ffda7bc9e6f11425eb5eddc3d3b32e8))
* **sdk:** add `artifacts_root` to `CompositeBackend` and middleware ([#2490](https://github.com/langchain-ai/deepagents/issues/2490)) ([753ee56](https://github.com/langchain-ai/deepagents/commit/753ee567f1cc4d544dc2afea7b414564fd07d37d))

### Bug Fixes

* **sdk:** updates for multimodal ([#2514](https://github.com/langchain-ai/deepagents/issues/2514)) ([a2edf3e](https://github.com/langchain-ai/deepagents/commit/a2edf3ed80e17a87027c41a46283387031ebd3e5))

---

## Prior Releases

Versions prior to 0.5.1 were released without release-please and do not have changelog entries. Refer to the [releases page](https://github.com/langchain-ai/deepagents/releases?q=deepagents) for details on previous versions.
