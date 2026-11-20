<!-- markdownlint-disable MD024 -->

# Changelog

## [0.0.10](https://github.com/shantanusharma/deepagents/compare/langchain-daytona==0.0.9...langchain-daytona==0.0.10) (2026-11-20)


### Features

* add partner packages for modal and runloop ([#1207](https://github.com/shantanusharma/deepagents/issues/1207)) ([497846f](https://github.com/shantanusharma/deepagents/commit/497846f94432e058981fd7a1f5782d906f4383d2))
* **daytona:** add polling policy (callable function) ([#1797](https://github.com/shantanusharma/deepagents/issues/1797)) ([c1abb8c](https://github.com/shantanusharma/deepagents/commit/c1abb8cfa55c80dd92e45a88ab93fedf4b5eeb9b))
* **daytona:** expose timeout and polling interval params ([#1792](https://github.com/shantanusharma/deepagents/issues/1792)) ([537ed6c](https://github.com/shantanusharma/deepagents/commit/537ed6cf153f9f6e50546c9d8674c32587540942))
* **sdk:** add per-command `timeout` override to `execute()` ([#1154](https://github.com/shantanusharma/deepagents/issues/1154)) ([49277d4](https://github.com/shantanusharma/deepagents/commit/49277d45a026c86b5bf176142dcb1dfc2c7643ae))


### Bug Fixes

* **daytona:** apply request timeouts and keep partial output on timeout ([#7121](https://github.com/shantanusharma/deepagents/issues/7121)) ([10c02fe](https://github.com/shantanusharma/deepagents/commit/10c02fe01678b976eb2ce6a73e17820215700955))
* **daytona:** fix execute implementation ([#1756](https://github.com/shantanusharma/deepagents/issues/1756)) ([080f3a5](https://github.com/shantanusharma/deepagents/commit/080f3a5ce6de137209702e04e03a506242263a93))
* **daytona:** require deepagents 0.7.x ([#5147](https://github.com/shantanusharma/deepagents/issues/5147)) ([e326721](https://github.com/shantanusharma/deepagents/commit/e326721d2de3bdcb01843f4bd1ef2165aefd9a7f))
* **sdk:** guard timeout forwarding for older backend packages ([#1461](https://github.com/shantanusharma/deepagents/issues/1461)) ([5fb4450](https://github.com/shantanusharma/deepagents/commit/5fb44505dd327fe88e8db6f3155cb442524b0788))

## [0.0.9](https://github.com/langchain-ai/deepagents/compare/langchain-daytona==0.0.8...langchain-daytona==0.0.9) (2026-10-23)

### Bug Fixes

- Apply request timeouts and preserve partial output when a timeout occurs ([#7121](https://github.com/langchain-ai/deepagents/pull/7121)).

## [0.0.8](https://github.com/langchain-ai/deepagents/compare/langchain-daytona==0.0.7...langchain-daytona==0.0.8) (2026-07-29)

### Bug Fixes

* Require deepagents 0.7.x ([#5147](https://github.com/langchain-ai/deepagents/issues/5147)) ([e326721](https://github.com/langchain-ai/deepagents/commit/e326721d2de3bdcb01843f4bd1ef2165aefd9a7f))

## [0.0.7](https://github.com/langchain-ai/deepagents/compare/langchain-daytona==0.0.6...langchain-daytona==0.0.7) (2026-06-03)

* Version bumps

## [0.0.6](https://github.com/langchain-ai/deepagents/compare/langchain-daytona==0.0.5...langchain-daytona==0.0.6) (2026-05-12)

### Features

* v0.6 ([4db09ac](https://github.com/langchain-ai/deepagents/commit/4db09acba34b38521192b8f278723524be560779))

---

## Prior Releases

Versions prior to 0.0.6 were released without release-please and do not have changelog entries. Refer to the [releases page](https://github.com/langchain-ai/deepagents/releases?q=langchain-daytona) for details on previous versions.
