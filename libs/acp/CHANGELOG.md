<!-- markdownlint-disable MD024 -->

# Changelog

## [0.0.14](https://github.com/shantanusharma/deepagents/compare/deepagents-acp==0.0.13...deepagents-acp==0.0.14) (2026-11-20)


### Features

* **acp:** add acp implementation ([#865](https://github.com/shantanusharma/deepagents/issues/865)) ([13eacfc](https://github.com/shantanusharma/deepagents/commit/13eacfc2dc464f6b9fdda4d4a0c2eec62d56086a))
* **acp:** Add local context middleware to ACP example agent, update script working dir ([#1332](https://github.com/shantanusharma/deepagents/issues/1332)) ([80e739b](https://github.com/shantanusharma/deepagents/commit/80e739b621cf2005e68f858c22604f5b7396d703))
* **acp:** Adds execute tool handling, allow of type permissions, demo coding agent ([#1302](https://github.com/shantanusharma/deepagents/issues/1302)) ([e89143f](https://github.com/shantanusharma/deepagents/commit/e89143ff905248407013fe3ef48c885f4ff5c7c4))
* **acp:** Adds Opus 4.7 and Baseten to demo agent ([#2787](https://github.com/shantanusharma/deepagents/issues/2787)) ([bfb16a6](https://github.com/shantanusharma/deepagents/commit/bfb16a645178f8134611d90b4aca4ddd43e2fdb9))
* **acp:** Bump ACP version ([#1214](https://github.com/shantanusharma/deepagents/issues/1214)) ([a853357](https://github.com/shantanusharma/deepagents/commit/a8533579b815b677f0316e930b1f816915e3dd00))
* **acp:** draft acp support ([#589](https://github.com/shantanusharma/deepagents/issues/589)) ([66e07d2](https://github.com/shantanusharma/deepagents/commit/66e07d29167eeeb956e07af2188857adddf76c47))
* **acp:** model switching ([#2135](https://github.com/shantanusharma/deepagents/issues/2135)) ([f4272c4](https://github.com/shantanusharma/deepagents/commit/f4272c4ad4b1eae8c3ee95168e951068ced5e554))
* **acp:** Show raw input in tool calls ([#1349](https://github.com/shantanusharma/deepagents/issues/1349)) ([8750a72](https://github.com/shantanusharma/deepagents/commit/8750a729c3222a3911e9b4051ca0044fb0888d48))
* **acp:** stream visible reasoning as thought chunks ([#5880](https://github.com/shantanusharma/deepagents/issues/5880)) ([7e96bf0](https://github.com/shantanusharma/deepagents/commit/7e96bf0ab1494217251010a30d27198d0c9532c9))
* **acp:** support persistent session loading ([#5365](https://github.com/shantanusharma/deepagents/issues/5365)) ([aaefb1e](https://github.com/shantanusharma/deepagents/commit/aaefb1eea1652abf370b5ac699be8307aee979e5))
* **acp:** Update Claude model list in demo agent ([#4414](https://github.com/shantanusharma/deepagents/issues/4414)) ([fa5e8b9](https://github.com/shantanusharma/deepagents/commit/fa5e8b91d6d3284cf2480777a2b2e79548351da8))
* **acp:** Update OpenAI and Baseten model in ACP example agent ([#2939](https://github.com/shantanusharma/deepagents/issues/2939)) ([eb9e491](https://github.com/shantanusharma/deepagents/commit/eb9e491acb57f9b1346b68a479ffd67cbbdb98f8))
* **cli:** `--acp` mode to run CLI agent as ACP server ([#1297](https://github.com/shantanusharma/deepagents/issues/1297)) ([c9ba00a](https://github.com/shantanusharma/deepagents/commit/c9ba00a56b7ee5e48b56b13f9f093bb8bf639700))


### Bug Fixes

* ACP Command Type Extraction Ignores Piped Commands, Enabling Privilege Escalation via "Always Allow" ([#1321](https://github.com/shantanusharma/deepagents/issues/1321)) ([c7109e3](https://github.com/shantanusharma/deepagents/commit/c7109e3b11925d440b0748e9355da095f7ef9d97))
* **acp:** add support for agent-client-protocol 1.0 so `dcode --acp` doesn't crash ([#7779](https://github.com/shantanusharma/deepagents/issues/7779)) ([39d15c8](https://github.com/shantanusharma/deepagents/commit/39d15c8e60f45ea27d9689f94e8037d11921f8b3))
* **acp:** block dangerous shell patterns in command auto-approve ([#2308](https://github.com/shantanusharma/deepagents/issues/2308)) ([b167013](https://github.com/shantanusharma/deepagents/commit/b1670136b96ec2433d2882f727ea20aef18dddc9))
* **acp:** cwd for agent session context ([#2130](https://github.com/shantanusharma/deepagents/issues/2130)) ([a7e924a](https://github.com/shantanusharma/deepagents/commit/a7e924a145c0934781a5405f09e682f82d5276d1))
* **acp:** defer interrupt state reads until stream closes ([#4542](https://github.com/shantanusharma/deepagents/issues/4542)) ([35199ab](https://github.com/shantanusharma/deepagents/commit/35199ab22b2111474d1f46b3ad7cc677d82ed46b))
* **acp:** Fix double approval bug ([#1335](https://github.com/shantanusharma/deepagents/issues/1335)) ([4fbc31c](https://github.com/shantanusharma/deepagents/commit/4fbc31ce8c7dc2b49915c5c66187c6f57610bb8e))
* **acp:** Fix issue in ACP demo agent ([#2422](https://github.com/shantanusharma/deepagents/issues/2422)) ([5bd164c](https://github.com/shantanusharma/deepagents/commit/5bd164c9f53bdf242211493fd699a03a5e12009b))
* **acp:** Fix mode switching for ACP client ([#1331](https://github.com/shantanusharma/deepagents/issues/1331)) ([e4dd005](https://github.com/shantanusharma/deepagents/commit/e4dd0052b63227df87a7c0b65474dc4cbce00114))
* **acp:** preserve local context prompt across compaction ([#6840](https://github.com/shantanusharma/deepagents/issues/6840)) ([b7e777f](https://github.com/shantanusharma/deepagents/commit/b7e777fb55023a78c88ed055bc846f52a334ae76))
* **acp:** Remove CLI dep from ACP demo agent ([#1474](https://github.com/shantanusharma/deepagents/issues/1474)) ([589762a](https://github.com/shantanusharma/deepagents/commit/589762a3cbee2ad5152c78cf8ccece0908792c9e))
* **acp:** require `agent-client-protocol>=0.9.0` ([#3733](https://github.com/shantanusharma/deepagents/issues/3733)) ([376d981](https://github.com/shantanusharma/deepagents/commit/376d9816833ef02a00fd4f1c4ccdf625629c36a4))
* **acp:** restore passing tests after acp v0.9 schema bump ([#2813](https://github.com/shantanusharma/deepagents/issues/2813)) ([29a351a](https://github.com/shantanusharma/deepagents/commit/29a351a8f5de8c460a3eeaadd76a3c2ace0072e0))
* **acp:** scope cancel() to the requested session ([#5107](https://github.com/shantanusharma/deepagents/issues/5107)) ([96236d2](https://github.com/shantanusharma/deepagents/commit/96236d275f6799eeed80235eaa2054ee0e5bc8b7))
* **acp:** scope shell permissions to exact commands ([#6881](https://github.com/shantanusharma/deepagents/issues/6881)) ([2cbef82](https://github.com/shantanusharma/deepagents/commit/2cbef82a0a8ed9fdc318ab23a926f6b11438da6f))
* **acp:** Upper bound ACP ([#2733](https://github.com/shantanusharma/deepagents/issues/2733)) ([02ff02f](https://github.com/shantanusharma/deepagents/commit/02ff02f5424afc7fd7cb82bd7dbb5c07272ed923))
* **acp:** use valid Claude 5.5 model IDs in demo ([#6684](https://github.com/shantanusharma/deepagents/issues/6684)) ([dd0e2f5](https://github.com/shantanusharma/deepagents/commit/dd0e2f5366da3704585a372aa905734cafcec900))
* import rules ([#763](https://github.com/shantanusharma/deepagents/issues/763)) ([2c54297](https://github.com/shantanusharma/deepagents/commit/2c54297054ae68b2a98673d2f58d44652815467b))
* **sdk,acp,harbor:** don't allow relative imports ([#882](https://github.com/shantanusharma/deepagents/issues/882)) ([acc8e3d](https://github.com/shantanusharma/deepagents/commit/acc8e3ddc496c106c833b667833c4a91f28db86e))

## [0.0.13](https://github.com/langchain-ai/deepagents/compare/deepagents-acp==0.0.12...deepagents-acp==0.0.13) (2026-10-12)

### Bug Fixes

- Shell permissions now apply only to the exact commands authorized. ([#6881](https://github.com/langchain-ai/deepagents/pull/6881))
- Local context prompts are preserved across compaction. ([#6840](https://github.com/langchain-ai/deepagents/pull/6840))
- The demo now uses valid Claude 5.5 model IDs. ([#6684](https://github.com/langchain-ai/deepagents/pull/6684))

## [0.0.12](https://github.com/langchain-ai/deepagents/compare/deepagents-acp==0.0.11...deepagents-acp==0.0.12) (2026-09-18)

### Bug Fixes

- Scoped `cancel()` requests to the requested session. ([#5107](https://github.com/langchain-ai/deepagents/pull/5107))

## [0.0.11](https://github.com/langchain-ai/deepagents/compare/deepagents-acp==0.0.10...deepagents-acp==0.0.11) (2026-08-27)

### Features

- Stream visible reasoning as thought chunks. ([#5880](https://github.com/langchain-ai/deepagents/issues/5880))

## [0.0.10](https://github.com/langchain-ai/deepagents/compare/deepagents-acp==0.0.9...deepagents-acp==0.0.10) (2026-08-12)

### Features

- Added support for loading persistent ACP sessions ([#5365](https://github.com/langchain-ai/deepagents/issues/5365)).

## [0.0.9](https://github.com/langchain-ai/deepagents/compare/deepagents-acp==0.0.8...deepagents-acp==0.0.9) (2026-07-07)


### Bug Fixes

* **acp:** defer interrupt state reads until stream closes ([#4542](https://github.com/langchain-ai/deepagents/issues/4542)) ([35199ab](https://github.com/langchain-ai/deepagents/commit/35199ab22b2111474d1f46b3ad7cc677d82ed46b))

## [0.0.8](https://github.com/langchain-ai/deepagents/compare/deepagents-acp==0.0.7...deepagents-acp==0.0.8) (2026-06-03)

### Bug Fixes

* Require `agent-client-protocol>=0.9.0` ([#3733](https://github.com/langchain-ai/deepagents/issues/3733)) ([376d981](https://github.com/langchain-ai/deepagents/commit/376d9816833ef02a00fd4f1c4ccdf625629c36a4))

## [0.0.7](https://github.com/langchain-ai/deepagents/compare/deepagents-acp==0.0.6...deepagents-acp==0.0.7) (2026-06-03)

* Bumping dependencies

## [0.0.6](https://github.com/langchain-ai/deepagents/compare/deepagents-acp==0.0.5...deepagents-acp==0.0.6) (2026-04-18)

### Features

* Add Opus 4.7 and Baseten to demo agent ([#2787](https://github.com/langchain-ai/deepagents/issues/2787)) ([bfb16a6](https://github.com/langchain-ai/deepagents/commit/bfb16a645178f8134611d90b4aca4ddd43e2fdb9))

### Bug Fixes

* Restore passing tests after acp v0.9 schema bump ([#2813](https://github.com/langchain-ai/deepagents/issues/2813)) ([29a351a](https://github.com/langchain-ai/deepagents/commit/29a351a8f5de8c460a3eeaadd76a3c2ace0072e0))

---

## Prior Releases

Versions prior to 0.0.6 were released without release-please and do not have changelog entries. Refer to the [releases page](https://github.com/langchain-ai/deepagents/releases?q=deepagents-acp) for details on previous versions.
