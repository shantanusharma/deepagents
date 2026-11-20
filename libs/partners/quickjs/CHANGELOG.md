<!-- markdownlint-disable MD024 -->

# Changelog

## [0.5.0](https://github.com/shantanusharma/deepagents/compare/langchain-quickjs==0.4.0...langchain-quickjs==0.5.0) (2026-11-20)


### ⚠ BREAKING CHANGES

* **quickjs:** keep QuickJS slots warm in a process-wide LRU ([#7790](https://github.com/shantanusharma/deepagents/issues/7790))
* **quickjs:** upgrade to quickjs-rs 0.3.0
* **quickjs:** upgrade to 0.2.0 quickjs-rs ([#4067](https://github.com/shantanusharma/deepagents/issues/4067))
* **quickjs:** add default `subagent` bridge ([#3850](https://github.com/shantanusharma/deepagents/issues/3850))
* **quickjs:** remove `skills_backend` ([#3843](https://github.com/shantanusharma/deepagents/issues/3843))
* **quickjs:** use quickjs-rs ([#2979](https://github.com/shantanusharma/deepagents/issues/2979))

### Features

* **code,quickjs:** dynamic subagents UI ([#4221](https://github.com/shantanusharma/deepagents/issues/4221)) ([10bcba2](https://github.com/shantanusharma/deepagents/commit/10bcba25600e51aba135f170b34aa6315c0f53d6))
* **quickjs:** add `max_ptc_calls` budget for ptc calls ([#2994](https://github.com/shantanusharma/deepagents/issues/2994)) ([13f6c2d](https://github.com/shantanusharma/deepagents/commit/13f6c2dec448e270d7e685447292d394d31fe528))
* **quickjs:** add `writeFile`, `readdir`, `access`, and `rm` to `fs` ([#7638](https://github.com/shantanusharma/deepagents/issues/7638)) ([0cef0a8](https://github.com/shantanusharma/deepagents/commit/0cef0a8e3ec34de25e826305dce076b86cedc8bb))
* **quickjs:** add an opt-in `fs.readFile` over the agent's backend ([#7637](https://github.com/shantanusharma/deepagents/issues/7637)) ([e4c8748](https://github.com/shantanusharma/deepagents/commit/e4c8748d4cc5fd86c5569d82464927912524bd67))
* **quickjs:** add async support using a daemon thread ([#1918](https://github.com/shantanusharma/deepagents/issues/1918)) ([3a7dd49](https://github.com/shantanusharma/deepagents/commit/3a7dd494c2eedf2302d550484721bee55c56ed6e))
* **quickjs:** add default `subagent` bridge ([#3850](https://github.com/shantanusharma/deepagents/issues/3850)) ([85fd7c2](https://github.com/shantanusharma/deepagents/commit/85fd7c283da6744e403a01861e17e99e13e0f481))
* **quickjs:** add hmac check to snapshot bytes ([#5601](https://github.com/shantanusharma/deepagents/issues/5601)) ([749b386](https://github.com/shantanusharma/deepagents/commit/749b386f97ed7b920acfd5936b01f8c425976d92))
* **quickjs:** add REPL persistence modes ([#3557](https://github.com/shantanusharma/deepagents/issues/3557)) ([0cda6f3](https://github.com/shantanusharma/deepagents/commit/0cda6f3ab28bc83cd16ec9fcc48229bdf6f2dc1a))
* **quickjs:** add snapshot-based repl persistence between turns ([#3064](https://github.com/shantanusharma/deepagents/issues/3064)) ([c46feed](https://github.com/shantanusharma/deepagents/commit/c46feed66e83876054489a8454904de4c87ddf6b))
* **quickjs:** add swarm task tool ([#3472](https://github.com/shantanusharma/deepagents/issues/3472)) ([2c28b7b](https://github.com/shantanusharma/deepagents/commit/2c28b7b8c2ac7571fc3a1f0d8d00f5697fe3e90e))
* **quickjs:** adding quickjs repl ([#1860](https://github.com/shantanusharma/deepagents/issues/1860)) ([8b3cf38](https://github.com/shantanusharma/deepagents/commit/8b3cf387522a4b0cf73a3238def83c3456e7db9f))
* **quickjs:** allow disabling the per-call `timeout` ([#6958](https://github.com/shantanusharma/deepagents/issues/6958)) ([3b992d2](https://github.com/shantanusharma/deepagents/commit/3b992d2d8dfa3bade91e612b2d6ef2dfb57603b6))
* **quickjs:** let `fs=True` use the agent's backend ([#7669](https://github.com/shantanusharma/deepagents/issues/7669)) ([94657a4](https://github.com/shantanusharma/deepagents/commit/94657a47f8d47acfc17c19157f823b7bdd902994))
* **quickjs:** make subagent concurrency configurable ([#6926](https://github.com/shantanusharma/deepagents/issues/6926)) ([f957b8e](https://github.com/shantanusharma/deepagents/commit/f957b8edd29d3146bf265aa7886c24e5fcd9a50f))
* **quickjs:** prefer async when on async path ([#1922](https://github.com/shantanusharma/deepagents/issues/1922)) ([0c51ea0](https://github.com/shantanusharma/deepagents/commit/0c51ea0798bfa87e655b7d7f050de057eb293e44))
* **quickjs:** prompt tuning on task global ([#4066](https://github.com/shantanusharma/deepagents/issues/4066)) ([a47696f](https://github.com/shantanusharma/deepagents/commit/a47696f6d3e57eccb5ea19fb344305a7995ecc76))
* **quickjs:** propagate return types ([#3210](https://github.com/shantanusharma/deepagents/issues/3210)) ([e26bccb](https://github.com/shantanusharma/deepagents/commit/e26bccbe81b4e3ff2f0332f56f683106e0bafd88))
* **quickjs:** rename middleware ([#3334](https://github.com/shantanusharma/deepagents/issues/3334)) ([fc80075](https://github.com/shantanusharma/deepagents/commit/fc80075c65c3b4beb8f672b6bb27464fee6d79c2))
* **quickjs:** stream PTC tool calls natively ([#5735](https://github.com/shantanusharma/deepagents/issues/5735)) ([c366c49](https://github.com/shantanusharma/deepagents/commit/c366c495129a67629a4477c51e0d1dec778d36e3))
* **quickjs:** support toolruntime ([#1932](https://github.com/shantanusharma/deepagents/issues/1932)) ([0df44f9](https://github.com/shantanusharma/deepagents/commit/0df44f9d77c917c3422127ae622ac6aec2294d20))
* **quickjs:** surface tool exceptions as the original error ([#3049](https://github.com/shantanusharma/deepagents/issues/3049)) ([d96dc8c](https://github.com/shantanusharma/deepagents/commit/d96dc8ce4a1d2d25abc606266cfe14629789c457))
* **quickjs:** upgrade to 0.2.0 quickjs-rs ([#4067](https://github.com/shantanusharma/deepagents/issues/4067)) ([4ffea88](https://github.com/shantanusharma/deepagents/commit/4ffea88690418207b5e4fa800ee8c1abfa454bec))
* **quickjs:** upgrade to quickjs-rs 0.3.0 ([d60e40e](https://github.com/shantanusharma/deepagents/commit/d60e40e30731cdc3bd6a1e1ee2412316d97b290e))
* **quickjs:** use quickjs-rs ([#2979](https://github.com/shantanusharma/deepagents/issues/2979)) ([7491899](https://github.com/shantanusharma/deepagents/commit/7491899074fa1ed7946f2f5a0e84c2b3793d39bd))


### Bug Fixes

* **quickjs:** add `ls_code_input_language` metadata to `eval` tool ([#3062](https://github.com/shantanusharma/deepagents/issues/3062)) ([b9bc674](https://github.com/shantanusharma/deepagents/commit/b9bc674fe67ac40e000b30bbb4a753a9b6e167ed))
* **quickjs:** apply state updates from `tools.*` calls in eval ([#7838](https://github.com/shantanusharma/deepagents/issues/7838)) ([c6bde12](https://github.com/shantanusharma/deepagents/commit/c6bde125f5974a12f64d56e0fb1058100ed7d59b))
* **quickjs:** auto-await final-expression Promise in eval REPL ([#3499](https://github.com/shantanusharma/deepagents/issues/3499)) ([f7f894a](https://github.com/shantanusharma/deepagents/commit/f7f894aa9f313cf8157bc6d7711013f5509d0b46))
* **quickjs:** bound console buffering at capture time ([#2999](https://github.com/shantanusharma/deepagents/issues/2999)) ([251e405](https://github.com/shantanusharma/deepagents/commit/251e405d8b1897ae09ee47b0a8be48edfaaad8a1))
* **quickjs:** close slots left open by failed runs and idle slots ([#7463](https://github.com/shantanusharma/deepagents/issues/7463)) ([1a7d602](https://github.com/shantanusharma/deepagents/commit/1a7d602a7ef6b54269bbb268e4bbc71f27ada0f9))
* **quickjs:** correct `eval` await description ([#4371](https://github.com/shantanusharma/deepagents/issues/4371)) ([4ab860f](https://github.com/shantanusharma/deepagents/commit/4ab860f007832821bd303809d7c2c1d2c86a6528))
* **quickjs:** defer runtime initialization until evaluation ([#7301](https://github.com/shantanusharma/deepagents/issues/7301)) ([12b4a78](https://github.com/shantanusharma/deepagents/commit/12b4a7801981e6edcc928da158dcb872a870a447))
* **quickjs:** don't block interpreter shutdown in CodeInterpreterMiddleware.__del__ ([#7460](https://github.com/shantanusharma/deepagents/issues/7460)) ([6578cc1](https://github.com/shantanusharma/deepagents/commit/6578cc10b3fe5f81d423921b0ff8c82f63bb609f))
* **quickjs:** don't evict a slot while a cancelled eval still runs ([#7850](https://github.com/shantanusharma/deepagents/issues/7850)) ([533e4b3](https://github.com/shantanusharma/deepagents/commit/533e4b3046dfa5e915c5eed86e8a7d3b01319446))
* **quickjs:** ensure top-level title on subagent response schemas ([#4155](https://github.com/shantanusharma/deepagents/issues/4155)) ([08f917e](https://github.com/shantanusharma/deepagents/commit/08f917eea79513e7e894731f884e738c2d30383f))
* **quickjs:** handle top-level await in snapshot step ([#3161](https://github.com/shantanusharma/deepagents/issues/3161)) ([b330c22](https://github.com/shantanusharma/deepagents/commit/b330c222ee661f7944a59d7b0ef2e0c7a42b1e29))
* **quickjs:** keep private state out of subagent propagation ([#3543](https://github.com/shantanusharma/deepagents/issues/3543)) ([916d7d7](https://github.com/shantanusharma/deepagents/commit/916d7d740563f8cc7e16299d5aba88f9467473de))
* **quickjs:** keep PTC loop and runtime context in `_PTCState` ([#3134](https://github.com/shantanusharma/deepagents/issues/3134)) ([c70cc5a](https://github.com/shantanusharma/deepagents/commit/c70cc5a602bd26191f347dd31cc4e5d17c75f65f))
* **quickjs:** keep QuickJS slots warm in a process-wide LRU ([#7790](https://github.com/shantanusharma/deepagents/issues/7790)) ([beeb0a0](https://github.com/shantanusharma/deepagents/commit/beeb0a032e65a86910a280a1037bbf3f8e24fe26)), refs [#7262](https://github.com/shantanusharma/deepagents/issues/7262) [#5387](https://github.com/shantanusharma/deepagents/issues/5387) [#4546](https://github.com/shantanusharma/deepagents/issues/4546) [#6311](https://github.com/shantanusharma/deepagents/issues/6311)
* **quickjs:** normalize nested `undefined` tool args ([#3935](https://github.com/shantanusharma/deepagents/issues/3935)) ([1b461a0](https://github.com/shantanusharma/deepagents/commit/1b461a0d6c6a7a6d323db18505596fcce4326b92))
* **quickjs:** parent PTC calls and `task()` subagents on the eval run ([#7665](https://github.com/shantanusharma/deepagents/issues/7665)) ([f2a6e02](https://github.com/shantanusharma/deepagents/commit/f2a6e02dc8e2dcb05885c5133b94102ccc79b794))
* **quickjs:** per-thread_id Runtimes ([#2931](https://github.com/shantanusharma/deepagents/issues/2931)) ([4021b03](https://github.com/shantanusharma/deepagents/commit/4021b032f79913ddbfbb233fce5aff3f245fd1db))
* **quickjs:** persist top-level JS declarations across evals ([#4147](https://github.com/shantanusharma/deepagents/issues/4147)) ([7574fea](https://github.com/shantanusharma/deepagents/commit/7574fea88b51c77f7afa8279c4f561d6ecb47e3f))
* **quickjs:** preserve subagent identity across interrupt replays ([#6370](https://github.com/shantanusharma/deepagents/issues/6370)) ([d31d7fc](https://github.com/shantanusharma/deepagents/commit/d31d7fcca9fd2c1b891318c97b95b06bb31fd630))
* **quickjs:** prompt improvements ([#2564](https://github.com/shantanusharma/deepagents/issues/2564)) ([4999c6b](https://github.com/shantanusharma/deepagents/commit/4999c6b064266a0f0189964241323fd0f0ba345e))
* **quickjs:** propagate JS `task()` subagent interrupts ([#4401](https://github.com/shantanusharma/deepagents/issues/4401)) ([0b30e49](https://github.com/shantanusharma/deepagents/commit/0b30e494d59187de2e6e23db062abbf835a6d265))
* **quickjs:** ptc tools in tools namespace are rendered without prepended `tools.` in system prompt and task as ptc duplicated task global ([#4075](https://github.com/shantanusharma/deepagents/issues/4075)) ([014a903](https://github.com/shantanusharma/deepagents/commit/014a9033af70b5b8b08ad2eb36f98590f5f1cca8))
* **quickjs:** raise minimum quickjs-rs version to 0.2.5 ([#5059](https://github.com/shantanusharma/deepagents/issues/5059)) ([794513b](https://github.com/shantanusharma/deepagents/commit/794513bbc58a859bbd858326e61565bd3f50e694))
* **quickjs:** remove `skills_backend` ([#3843](https://github.com/shantanusharma/deepagents/issues/3843)) ([1159e50](https://github.com/shantanusharma/deepagents/commit/1159e504abaeec4f81d5e777ecde6a6cee641edb))
* **quickjs:** remove ptc command buffering ([#3023](https://github.com/shantanusharma/deepagents/issues/3023)) ([ac1218a](https://github.com/shantanusharma/deepagents/commit/ac1218a1b14cde2f066c59804ab86567821f8c9d))
* **quickjs:** render dict (MCP) `args_schema` inline in PTC signatures ([#7464](https://github.com/shantanusharma/deepagents/issues/7464)) ([41841fc](https://github.com/shantanusharma/deepagents/commit/41841fc2e2424e5b78bc2875718fb1feb6e2dbc4))
* **quickjs:** require deepagents 0.7.x ([#5151](https://github.com/shantanusharma/deepagents/issues/5151)) ([4cb7e27](https://github.com/shantanusharma/deepagents/commit/4cb7e27abbca6f1bb1d75861b6a1a76e7011ae31))
* **quickjs:** resolve nested schema `$ref`s in PTC signatures ([#7441](https://github.com/shantanusharma/deepagents/issues/7441)) ([5829691](https://github.com/shantanusharma/deepagents/commit/5829691de8f43d201f9534fb731643223c0bbccc))
* **quickjs:** run quickjs tests in CI and restore host exception propagation ([#3162](https://github.com/shantanusharma/deepagents/issues/3162)) ([78cb42c](https://github.com/shantanusharma/deepagents/commit/78cb42c1f57f83b90c4e2d91002967b1bfc047e6))
* **quickjs:** scope REPL prompt sandbox bullet to the runtime ([#3528](https://github.com/shantanusharma/deepagents/issues/3528)) ([1b395ab](https://github.com/shantanusharma/deepagents/commit/1b395ab9699b1f384a85efeeef732ea7e4fc523a))
* **quickjs:** steer code mode to `Promise.allSettled` for parallel calls ([#7871](https://github.com/shantanusharma/deepagents/issues/7871)) ([40cdd33](https://github.com/shantanusharma/deepagents/commit/40cdd334d831e5c6737708811cc0335ec6105ac6))
* **quickjs:** swarm subagent doesn't allow configuring middleware ([#3757](https://github.com/shantanusharma/deepagents/issues/3757)) ([3394a9d](https://github.com/shantanusharma/deepagents/commit/3394a9d9c7c89c0a28fa1328c9f6bae68a83ff14))
* **quickjs:** update system prompt snapshots ([#3450](https://github.com/shantanusharma/deepagents/issues/3450)) ([9f9220d](https://github.com/shantanusharma/deepagents/commit/9f9220d80737208faa9262c0bdfb3eeafc0e13c8))


### Performance Improvements

* **code,quickjs:** omit middleware trace inputs ([#6015](https://github.com/shantanusharma/deepagents/issues/6015)) ([673844d](https://github.com/shantanusharma/deepagents/commit/673844d06fe0ee186f2e492c3c0a19ec5facffc2))


### Reverted Changes

* **quickjs:** release: 0.1.1 ([#3255](https://github.com/shantanusharma/deepagents/issues/3255)) ([8125f71](https://github.com/shantanusharma/deepagents/commit/8125f71a6ffd40b75a25c017e2b255eeb3be48a6))

## [0.4.0](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.12...langchain-quickjs==0.4.0) (2026-11-19)

langchain-quickjs 0.4.0 is out! Code mode gets a real filesystem, tools that actually update your agent's state, and a much lighter footprint.

### 📁 `fs` in code mode

Code can now read and write the agent's files directly, the same files its file tools see, through a Node-style `fs` global. Pass `fs=True` with `create_deep_agent` (or pass any backend yourself):

```python
agent = create_deep_agent(
    model,
    middleware=[CodeInterpreterMiddleware(ptc=True, fs=True)],
)
```

One eval can now do what used to take a dozen file-tool round trips:

```js
const files = await fs.readdir("/reports");
const totals = {};
for (const name of files.filter((f) => f.endsWith(".json"))) {
  const { region, revenue } = JSON.parse(await fs.readFile(`/reports/${name}`));
  totals[region] = (totals[region] ?? 0) + revenue;
}
await fs.writeFile("/summary.json", JSON.stringify(totals, null, 2));
```

It has `readFile`, `writeFile`, `readdir`, `access` and `rm`, all async, and errors come back as Node errors (`err.code === "ENOENT"`).

### 🔁 Tools called from code now respect `Command`

Before, when a tool returned `Command(update=...)` and you called it from code, the update was silently dropped. Now it lands in graph state just like a normal tool call, later calls in the same eval see it, and your JS gets the tool's message back:

```python
@tool
def save_plan(plan: str, tool_call_id: Annotated[str, InjectedToolCallId]) -> Command:
    """Save the plan to state."""
    return Command(update={
        "plan": plan,
        "messages": [ToolMessage("plan saved", tool_call_id=tool_call_id)],
    })
```

```js
await tools.savePlan({ plan: "1. research 2. draft" }); // "plan saved", and state.plan is set
```

### ⚡ Faster startup, lower overhead

Interpreters are now created on the first eval, not when the agent starts, so threads that never run code never pay for one. Closing them no longer blocks the event loop, and runs that error or get cancelled release their interpreter cleanly. The code-mode system prompt is cached by content, so it isn't re-rendered every turn.

Also in this release: one `tools.*` proxy (with `defer_loading` tools still callable), typed signatures for MCP tools, and quickjs-rs 0.3.0.

> **Heads up:** JS state saved by 0.3.x won't restore, so existing threads start from a fresh JS context on their next eval.

### ⚠ BREAKING CHANGES

- Upgrade to quickjs-rs 0.3.0. JavaScript state saved by 0.3.x cannot be restored; existing threads start with a fresh JavaScript context on their next evaluation.
- Keep QuickJS interpreters warm in a process-wide LRU cache. ([#7790](https://github.com/langchain-ai/deepagents/pull/7790), [#7262](https://github.com/langchain-ai/deepagents/pull/7262), [#5387](https://github.com/langchain-ai/deepagents/pull/5387), [#4546](https://github.com/langchain-ai/deepagents/pull/4546), [#6311](https://github.com/langchain-ai/deepagents/pull/6311))

### Features

- Add an opt-in, Node-style `fs` global with async `readFile`, `writeFile`, `readdir`, `access`, and `rm` methods and Node-style errors. Set `fs=True` to use the agent's backend, or supply a backend explicitly. ([#7638](https://github.com/langchain-ai/deepagents/pull/7638), [#7637](https://github.com/langchain-ai/deepagents/pull/7637), [#7669](https://github.com/langchain-ai/deepagents/pull/7669))
- Unify tool access through a single `tools.*` proxy while keeping tools configured with `defer_loading` callable.

### Bug Fixes

- Apply `Command` state updates returned by tools called from code. Later calls in the same evaluation see the updated state, and JavaScript receives the tool's message. ([#7838](https://github.com/langchain-ai/deepagents/pull/7838))
- Clean up interpreters left open by failed runs or inactivity, and prevent eviction while a cancelled evaluation is still running. ([#7463](https://github.com/langchain-ai/deepagents/pull/7463), [#7850](https://github.com/langchain-ai/deepagents/pull/7850))
- Correctly parent programmatic tool calls and `task()` subagents under the evaluation run. ([#7665](https://github.com/langchain-ai/deepagents/pull/7665))
- Render dictionary-based MCP argument schemas inline as typed signatures for programmatic tool calling. ([#7464](https://github.com/langchain-ai/deepagents/pull/7464))
- Update code-mode guidance to prefer `Promise.allSettled` for parallel calls. ([#7871](https://github.com/langchain-ai/deepagents/pull/7871))

### Performance Improvements

- Create interpreters only on the first evaluation, avoiding interpreter overhead for threads that never run code, and close interpreters without blocking the event loop.
- Cache the code-mode system prompt by content to avoid re-rendering it every turn.

## [0.3.12](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.11...langchain-quickjs==0.3.12) (2026-11-07)

### Features

- Added support for disabling the per-call `timeout` ([#6958](https://github.com/langchain-ai/deepagents/pull/6958)).

### Bug Fixes

- Fixed interpreter shutdown blocking in `CodeInterpreterMiddleware.__del__` ([#7460](https://github.com/langchain-ai/deepagents/pull/7460)).
- Fixed resolution of nested schema `$ref`s in PTC signatures ([#7441](https://github.com/langchain-ai/deepagents/pull/7441)).

## [0.3.11](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.10...langchain-quickjs==0.3.11) (2026-10-27)

### Bug Fixes

- Defer QuickJS runtime initialization until evaluation ([#7301](https://github.com/langchain-ai/deepagents/pull/7301)).

## [0.3.10](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.9...langchain-quickjs==0.3.10) (2026-10-26)

### Bug Fixes

- Fixed PTC prompt caching to cache prompts per slot and tool identity. ([#7296](https://github.com/langchain-ai/deepagents/pull/7296))

## [0.3.9](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.8...langchain-quickjs==0.3.9) (2026-10-13)

### Features

- Configure the number of concurrent subagents with `CodeInterpreterMiddleware(max_subagent_concurrency=16)`. The default remains 32 per REPL; requests above the cap queue until a slot opens. Lower limits can reduce memory use, load, and cost, while higher limits allow more parallel work. The prompt now recommends batches of around 10 rather than requiring them, even at the default setting. ([#6926](https://github.com/langchain-ai/deepagents/pull/6926))

## [0.3.8](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.7...langchain-quickjs==0.3.8) (2026-09-29)

### Bug Fixes

- Preserve subagent identity when replaying interrupts. ([#6370](https://github.com/langchain-ai/deepagents/pull/6370))

## [0.3.7](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.6...langchain-quickjs==0.3.7) (2026-09-06)

### Features

- Stream PTC tool calls natively. ([#5735](https://github.com/langchain-ai/deepagents/issues/5735))

### Bug Fixes

- Keep private state out of subagent propagation. ([#3543](https://github.com/langchain-ai/deepagents/issues/3543))

## [0.3.6](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.5...langchain-quickjs==0.3.6) (2026-09-03)

### Features

- Added an HMAC check for QuickJS snapshot bytes ([#5601](https://github.com/langchain-ai/deepagents/issues/5601)) ([749b386](https://github.com/langchain-ai/deepagents/commit/749b386f97ed7b920acfd5936b01f8c425976d92)).

### Performance Improvements

- Omitted middleware trace inputs to improve QuickJS performance ([#6015](https://github.com/langchain-ai/deepagents/issues/6015)) ([673844d](https://github.com/langchain-ai/deepagents/commit/673844d06fe0ee186f2e492c3c0a19ec5facffc2)).

## [0.3.5](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.4...langchain-quickjs==0.3.5) (2026-07-29)

### Bug Fixes

* Require deepagents 0.7.x ([#5151](https://github.com/langchain-ai/deepagents/issues/5151)) ([4cb7e27](https://github.com/langchain-ai/deepagents/commit/4cb7e27abbca6f1bb1d75861b6a1a76e7011ae31))

## [0.3.4](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.3...langchain-quickjs==0.3.4) (2026-07-24)

### Bug Fixes

* Raise minimum quickjs-rs version to 0.2.5 ([#5059](https://github.com/langchain-ai/deepagents/issues/5059)) ([794513b](https://github.com/langchain-ai/deepagents/commit/794513bbc58a859bbd858326e61565bd3f50e694))

## [0.3.3](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.2...langchain-quickjs==0.3.3) (2026-07-16)

### Bug Fixes

* Propagate JS `task()` subagent interrupts ([#4401](https://github.com/langchain-ai/deepagents/issues/4401)) ([0b30e49](https://github.com/langchain-ai/deepagents/commit/0b30e494d59187de2e6e23db062abbf835a6d265))
* Correct `eval` await description ([#4371](https://github.com/langchain-ai/deepagents/issues/4371)) ([4ab860f](https://github.com/langchain-ai/deepagents/commit/4ab860f007832821bd303809d7c2c1d2c86a6528))

## [0.3.2](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.1...langchain-quickjs==0.3.2) (2026-06-25)

### Features

* Dynamic subagents UI ([#4221](https://github.com/langchain-ai/deepagents/issues/4221)) ([10bcba2](https://github.com/langchain-ai/deepagents/commit/10bcba25600e51aba135f170b34aa6315c0f53d6))

### Bug Fixes

* Ensure top-level title on subagent response schemas ([#4155](https://github.com/langchain-ai/deepagents/issues/4155)) ([08f917e](https://github.com/langchain-ai/deepagents/commit/08f917eea79513e7e894731f884e738c2d30383f))
* Normalize nested `undefined` tool args ([#3935](https://github.com/langchain-ai/deepagents/issues/3935)) ([1b461a0](https://github.com/langchain-ai/deepagents/commit/1b461a0d6c6a7a6d323db18505596fcce4326b92))

## [0.3.1](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.3.0...langchain-quickjs==0.3.1) (2026-06-22)

### Bug Fixes

* Persist top-level JS declarations across evals ([#4147](https://github.com/langchain-ai/deepagents/issues/4147)) ([7574fea](https://github.com/langchain-ai/deepagents/commit/7574fea88b51c77f7afa8279c4f561d6ecb47e3f))
* PTC tools in tools namespace are rendered without prepended `tools.` in system prompt and task as ptc duplicated task global ([#4075](https://github.com/langchain-ai/deepagents/issues/4075)) ([014a903](https://github.com/langchain-ai/deepagents/commit/014a9033af70b5b8b08ad2eb36f98590f5f1cca8))

## [0.3.0](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.2.0...langchain-quickjs==0.3.0) (2026-06-18)

### ⚠ BREAKING CHANGES

* Upgrade to 0.2.0 quickjs-rs ([#4067](https://github.com/langchain-ai/deepagents/issues/4067))

### Features

* Prompt tuning on task global ([#4066](https://github.com/langchain-ai/deepagents/issues/4066)) ([a47696f](https://github.com/langchain-ai/deepagents/commit/a47696f6d3e57eccb5ea19fb344305a7995ecc76))
* Upgrade to 0.2.0 quickjs-rs ([#4067](https://github.com/langchain-ai/deepagents/issues/4067)) ([4ffea88](https://github.com/langchain-ai/deepagents/commit/4ffea88690418207b5e4fa800ee8c1abfa454bec))

## [0.2.0](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.1.4...langchain-quickjs==0.2.0) (2026-06-12)

### ⚠ BREAKING CHANGES

* Add default `subagent` bridge ([#3850](https://github.com/langchain-ai/deepagents/issues/3850))
* Remove `skills_backend` ([#3843](https://github.com/langchain-ai/deepagents/issues/3843))

### Features

* Add default `subagent` bridge ([#3850](https://github.com/langchain-ai/deepagents/issues/3850)) ([85fd7c2](https://github.com/langchain-ai/deepagents/commit/85fd7c283da6744e403a01861e17e99e13e0f481))

### Bug Fixes

* Remove `skills_backend` ([#3843](https://github.com/langchain-ai/deepagents/issues/3843)) ([1159e50](https://github.com/langchain-ai/deepagents/commit/1159e504abaeec4f81d5e777ecde6a6cee641edb))

## [0.1.4](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.1.3...langchain-quickjs==0.1.4) (2026-06-03)

### Bug Fixes

* Swarm subagent doesn't allow configuring middleware ([#3757](https://github.com/langchain-ai/deepagents/issues/3757)) ([3394a9d](https://github.com/langchain-ai/deepagents/commit/3394a9d9c7c89c0a28fa1328c9f6bae68a83ff14))

## [0.1.3](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.1.2...langchain-quickjs==0.1.3) (2026-06-01)

### Features

* Add REPL persistence modes ([#3557](https://github.com/langchain-ai/deepagents/issues/3557)) ([0cda6f3](https://github.com/langchain-ai/deepagents/commit/0cda6f3ab28bc83cd16ec9fcc48229bdf6f2dc1a))
* Add swarm task tool ([#3472](https://github.com/langchain-ai/deepagents/issues/3472)) ([2c28b7b](https://github.com/langchain-ai/deepagents/commit/2c28b7b8c2ac7571fc3a1f0d8d00f5697fe3e90e))

### Bug Fixes

* Auto-await final-expression Promise in eval REPL ([#3499](https://github.com/langchain-ai/deepagents/issues/3499)) ([f7f894a](https://github.com/langchain-ai/deepagents/commit/f7f894aa9f313cf8157bc6d7711013f5509d0b46))
* Scope REPL prompt sandbox bullet to the runtime ([#3528](https://github.com/langchain-ai/deepagents/issues/3528)) ([1b395ab](https://github.com/langchain-ai/deepagents/commit/1b395ab9699b1f384a85efeeef732ea7e4fc523a))
* Update system prompt snapshots ([#3450](https://github.com/langchain-ai/deepagents/issues/3450)) ([9f9220d](https://github.com/langchain-ai/deepagents/commit/9f9220d80737208faa9262c0bdfb3eeafc0e13c8))
* Stable `HumanMessage` IDs across resumed threads ([#3591](https://github.com/langchain-ai/deepagents/issues/3591)) ([82c3194](https://github.com/langchain-ai/deepagents/commit/82c31947f9dc938ffc71e1cea96d162a39aec3a1))

## [0.1.2](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.1.1...langchain-quickjs==0.1.2) (2026-05-11)

### Features

* Rename middleware ([#3334](https://github.com/langchain-ai/deepagents/issues/3334)) ([fc80075](https://github.com/langchain-ai/deepagents/commit/fc80075c65c3b4beb8f672b6bb27464fee6d79c2))

## [0.1.1](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.1.0...langchain-quickjs==0.1.1) (2026-05-08)

### Features

* Propagate return types ([#3210](https://github.com/langchain-ai/deepagents/issues/3210)) ([e26bccb](https://github.com/langchain-ai/deepagents/commit/e26bccbe81b4e3ff2f0332f56f683106e0bafd88))

## [0.1.0](https://github.com/langchain-ai/deepagents/compare/langchain-quickjs==0.0.1...langchain-quickjs==0.1.0) (2026-05-05)

This release introduces a new QuickJS runtime implementation backed by `quickjs-rs`.

---

## Prior Releases

Versions prior to 0.0.2 were released without release-please and do not have changelog entries. Refer to the [releases page](https://github.com/langchain-ai/deepagents/releases?q=langchain-quickjs) for details on previous versions.
