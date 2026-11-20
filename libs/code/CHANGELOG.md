<!-- markdownlint-disable MD024 -->

# Deep Agents Code Changelog

## [0.1.0](https://github.com/shantanusharma/deepagents/compare/deepagents-code==0.2.11...deepagents-code==0.1.0) (2026-11-20)


### ⚠ BREAKING CHANGES

* **deps:** `deepagents-code` and `deepagents-talon` now require Python 3.14 (`>=3.14,<3.15`). Re-run the dcode installer, or recreate your environment on Python 3.14.
* **sdk,code,quickjs:** make the `ToDoListMiddleware` list opt-in ([#4929](https://github.com/shantanusharma/deepagents/issues/4929))

### Features

* **code,evals:** GLM-5.2 harness profile ([#4710](https://github.com/shantanusharma/deepagents/issues/4710)) ([47cfc33](https://github.com/shantanusharma/deepagents/commit/47cfc33cf9145347b57eb2daf6ef82cdaa342ca4))
* **code,evals:** inject goal/rubric context, dropping `get_goal`/`get_rubric` ([#5041](https://github.com/shantanusharma/deepagents/issues/5041)) ([2c80153](https://github.com/shantanusharma/deepagents/commit/2c801537885ea511c91fc880f6f8daa0a71342be))
* **code,quickjs:** dynamic subagents UI ([#4221](https://github.com/shantanusharma/deepagents/issues/4221)) ([10bcba2](https://github.com/shantanusharma/deepagents/commit/10bcba25600e51aba135f170b34aa6315c0f53d6))
* **code,sdk:** add rubric iteration controls ([#4405](https://github.com/shantanusharma/deepagents/issues/4405)) ([d6692a7](https://github.com/shantanusharma/deepagents/commit/d6692a7c713490f170b17510d613e02ee37574ab))
* **code,talon:** require Python 3.12 or greater ([#5603](https://github.com/shantanusharma/deepagents/issues/5603)) ([04de43e](https://github.com/shantanusharma/deepagents/commit/04de43e05adcbd38f1022f1fafe93f6748c2a032))
* **code:** `--timeout` flag for non-interactive ([#3351](https://github.com/shantanusharma/deepagents/issues/3351)) ([44e86ab](https://github.com/shantanusharma/deepagents/commit/44e86abbb1870f689dace8b1be6ed430d65e74c1))
* **code:** `/context-doctor` ([#5830](https://github.com/shantanusharma/deepagents/issues/5830)) ([80719ce](https://github.com/shantanusharma/deepagents/commit/80719ceee8d12060d7ffcdfff880777dc3aaf212))
* **code:** `/install` optional extras ([#3606](https://github.com/shantanusharma/deepagents/issues/3606)) ([7ffaa93](https://github.com/shantanusharma/deepagents/commit/7ffaa93dca6910cd454040d416ff7e0e8bcbcea5))
* **code:** `/model` Ctrl+N toggle for names vs raw specs ([#4592](https://github.com/shantanusharma/deepagents/issues/4592)) ([518c322](https://github.com/shantanusharma/deepagents/commit/518c322e7dda840b5a740541afc895516a74925f))
* **code:** `/model` footer Ctrl+N hint follows display mode ([#5247](https://github.com/shantanusharma/deepagents/issues/5247)) ([cf87266](https://github.com/shantanusharma/deepagents/commit/cf87266105ee6ed79e56d72dea58c1c5f431228f))
* **code:** `/model` toggle for recommended-only list ([#3453](https://github.com/shantanusharma/deepagents/issues/3453)) ([c326b7e](https://github.com/shantanusharma/deepagents/commit/c326b7ec1b9940861175e0466ab4221f03e2bcba))
* **code:** `/restart` hidden slash command ([#3514](https://github.com/shantanusharma/deepagents/issues/3514)) ([74bdd36](https://github.com/shantanusharma/deepagents/commit/74bdd3688948d8369cdd978590f5a822eabeb12c))
* **code:** `/timestamps` shows a toast instead of an app message ([#4096](https://github.com/shantanusharma/deepagents/issues/4096)) ([ae1de8b](https://github.com/shantanusharma/deepagents/commit/ae1de8b0766c69f6eac0c3cb919c6aac7d9e136c))
* **code:** `/tools` slash command ([#4649](https://github.com/shantanusharma/deepagents/issues/4649)) ([b1600a8](https://github.com/shantanusharma/deepagents/commit/b1600a8da784899d9db5bdf93be07b4c7f53a46c))
* **code:** `Ctrl+S` in `/auto model` stores `[models].auto_classifier` ([#5313](https://github.com/shantanusharma/deepagents/issues/5313)) ([e742d04](https://github.com/shantanusharma/deepagents/commit/e742d04c8ca6f615327d7d1eab7994be8fcb3000))
* **code:** `dcode config get` accepts sections ([#5134](https://github.com/shantanusharma/deepagents/issues/5134)) ([874a137](https://github.com/shantanusharma/deepagents/commit/874a137f7bf694f647f6f1dcbcf563eae5589ef2))
* **code:** `dcode doctor` diagnostics command ([#4148](https://github.com/shantanusharma/deepagents/issues/4148)) ([8179731](https://github.com/shantanusharma/deepagents/commit/81797312c7d857e7d94d03c9c695cd3c8d88799a))
* **code:** `dcode mcp config` and unify `--mcp-config` flag ([#3541](https://github.com/shantanusharma/deepagents/issues/3541)) ([f037b14](https://github.com/shantanusharma/deepagents/commit/f037b140f90a1ba3725b3ef23ab385b3cafe223b))
* **code:** `dcode_term_program` trace metadata ([#5329](https://github.com/shantanusharma/deepagents/issues/5329)) ([8d3a1a9](https://github.com/shantanusharma/deepagents/commit/8d3a1a929f7569630060ab68862b2a21c382d58c))
* **code:** `managed_config.toml` ([#5604](https://github.com/shantanusharma/deepagents/issues/5604)) ([d419122](https://github.com/shantanusharma/deepagents/commit/d419122bfb748a823d1fa7cfd7207c428f4fbcab))
* **code:** `tool.use` and `tool.result` hook events ([#3954](https://github.com/shantanusharma/deepagents/issues/3954)) ([ba1979d](https://github.com/shantanusharma/deepagents/commit/ba1979d64c3ed5e96ebc896197bc8f97f6f84bac))
* **code:** add "always allow" to project MCP approval prompt ([#4562](https://github.com/shantanusharma/deepagents/issues/4562)) ([ffab82a](https://github.com/shantanusharma/deepagents/commit/ffab82a9458d2a03b95cbc515f883212090a6992))
* **code:** add `--allow-fs-tools` filesystem tool allowlist to dcode ([#4635](https://github.com/shantanusharma/deepagents/issues/4635)) ([3fbb85e](https://github.com/shantanusharma/deepagents/commit/3fbb85e3565f270f3a567f771ebd28323f10245d))
* **code:** add `--no-tracing` and explicit tracing status ([#6721](https://github.com/shantanusharma/deepagents/issues/6721)) ([df20c07](https://github.com/shantanusharma/deepagents/commit/df20c0748015af173bc60588d69fef6865c01319))
* **code:** add `--sandbox-snapshot-name` flag ([#3538](https://github.com/shantanusharma/deepagents/issues/3538)) ([b01392e](https://github.com/shantanusharma/deepagents/commit/b01392e7549798434f27f3784fa8c4e734053787))
* **code:** add `-s` alias for `--skill` ([#4620](https://github.com/shantanusharma/deepagents/issues/4620)) ([c9b7ac2](https://github.com/shantanusharma/deepagents/commit/c9b7ac20752e4270d286b4af3fcf710e7e5bee87))
* **code:** add `[startup].mode` default approval mode ([#4573](https://github.com/shantanusharma/deepagents/issues/4573)) ([7c5bf54](https://github.com/shantanusharma/deepagents/commit/7c5bf542c2f58fa46ecd708c66cd1817a0ebdc41))
* **code:** add `/context` usage report ([#5407](https://github.com/shantanusharma/deepagents/issues/5407)) ([0355416](https://github.com/shantanusharma/deepagents/commit/0355416c0d4817ac58d3e14aa8b7ab099b6db74d))
* **code:** add `/summarization-model` ([#5884](https://github.com/shantanusharma/deepagents/issues/5884)) ([4f34c51](https://github.com/shantanusharma/deepagents/commit/4f34c51d4b9f6ed508af6a8e1ca6dbcf6e3e3877))
* **code:** add `Ctrl+X` to goal review editing ([#4780](https://github.com/shantanusharma/deepagents/issues/4780)) ([641b906](https://github.com/shantanusharma/deepagents/commit/641b906157db2c6ae476805f0714ae8f51040492))
* **code:** add `dcode tools list` command ([#4461](https://github.com/shantanusharma/deepagents/issues/4461)) ([1402d0e](https://github.com/shantanusharma/deepagents/commit/1402d0e735a1580503f240457c77db76fcd779d7))
* **code:** add `DeepSeek-V4-Pro-0813` to model picker ([#5512](https://github.com/shantanusharma/deepagents/issues/5512)) ([f23d81b](https://github.com/shantanusharma/deepagents/commit/f23d81b910b7c3343fda293d70f0a75d44f45ba0))
* **code:** add `editable` trace metadata ([#5737](https://github.com/shantanusharma/deepagents/issues/5737)) ([23b83ad](https://github.com/shantanusharma/deepagents/commit/23b83ad50f63d241d0069a3dc426d43b211adf2e))
* **code:** add `get_current_thread_id` tool ([#3820](https://github.com/shantanusharma/deepagents/issues/3820)) ([18ce094](https://github.com/shantanusharma/deepagents/commit/18ce094b7036796c7e23ce1338f4da56dc2ef126))
* **code:** add `google_anthropic_vertex` provider for Claude on Vertex AI ([#5760](https://github.com/shantanusharma/deepagents/issues/5760)) ([aa69916](https://github.com/shantanusharma/deepagents/commit/aa69916baf74c904a70a7497f78752d294df82ac))
* **code:** add `GPT-5.6` model family ([#4600](https://github.com/shantanusharma/deepagents/issues/4600)) ([4a806bc](https://github.com/shantanusharma/deepagents/commit/4a806bc703b69334cccd05bcd27d411602e82318))
* **code:** add `GPT-6 Astra` support ([#6141](https://github.com/shantanusharma/deepagents/issues/6141)) ([048f989](https://github.com/shantanusharma/deepagents/commit/048f9890bfe8b640e1e72085a4fa50d9084545f0))
* **code:** add `install` subcommand ([#5080](https://github.com/shantanusharma/deepagents/issues/5080)) ([2f2116d](https://github.com/shantanusharma/deepagents/commit/2f2116d5cd7bba98e1b0731d5da760a4b93ffb37))
* **code:** add `memory.auto_save` config flag ([#4700](https://github.com/shantanusharma/deepagents/issues/4700)) ([55b60ca](https://github.com/shantanusharma/deepagents/commit/55b60ca08da4eef294ac3c162610b2a151584ea5))
* **code:** add `multi_select` question type to `ask_user` ([#5097](https://github.com/shantanusharma/deepagents/issues/5097)) ([878ab3e](https://github.com/shantanusharma/deepagents/commit/878ab3e20d35de63001476d5e68c29b12fad4f12))
* **code:** add `reconnect`/`connect` hidden keywords for `/restart` ([#4807](https://github.com/shantanusharma/deepagents/issues/4807)) ([99250ee](https://github.com/shantanusharma/deepagents/commit/99250ee1749c977e95389baafde3d358c953ea0f))
* **code:** add agent filter dropdown to `/threads` picker ([#3677](https://github.com/shantanusharma/deepagents/issues/3677)) ([f8193df](https://github.com/shantanusharma/deepagents/commit/f8193df41d7c47626d94252039217f4079d117cd))
* **code:** add Baseten `zai-org/GLM-5.3-Flash` to model switcher ([#5844](https://github.com/shantanusharma/deepagents/issues/5844)) ([731d2d5](https://github.com/shantanusharma/deepagents/commit/731d2d5a56dc0f9e78cec77722af592ad939edd3))
* **code:** add Baseten built-in pricing overrides ([#5312](https://github.com/shantanusharma/deepagents/issues/5312)) ([f34ffa0](https://github.com/shantanusharma/deepagents/commit/f34ffa0cb8c0c7943b116a753535df47e32de2a3))
* **code:** add built-in thread inspector skill ([#4769](https://github.com/shantanusharma/deepagents/issues/4769)) ([2d729b3](https://github.com/shantanusharma/deepagents/commit/2d729b30c5df7265e8062bccd38026b745c6cf02))
* **code:** add cache and context status row ([#5408](https://github.com/shantanusharma/deepagents/issues/5408)) ([2b3edf9](https://github.com/shantanusharma/deepagents/commit/2b3edf9ba4f3b43911f118b8e942374091602854))
* **code:** add Claude Opus 5 support ([#5049](https://github.com/shantanusharma/deepagents/issues/5049)) ([c0afec5](https://github.com/shantanusharma/deepagents/commit/c0afec5ab7e9860d1572002c1f689f95dd15cf8e))
* **code:** add Claude Sonnet 5 to model picker ([#4386](https://github.com/shantanusharma/deepagents/issues/4386)) ([64758dd](https://github.com/shantanusharma/deepagents/commit/64758dddf8b46c5b68c345fb1eac1fb7bcbf7f7e))
* **code:** add config command and canonical config manifest ([#3763](https://github.com/shantanusharma/deepagents/issues/3763)) ([79899a3](https://github.com/shantanusharma/deepagents/commit/79899a306d01de6217a1dfcc013ae92c808a47a0))
* **code:** add configurable chat cursor style ([#4687](https://github.com/shantanusharma/deepagents/issues/4687)) ([a22484b](https://github.com/shantanusharma/deepagents/commit/a22484ba2e001fd62fbff0fe916f1b3b93889fc3))
* **code:** add Deep Agents client version metadata ([#3934](https://github.com/shantanusharma/deepagents/issues/3934)) ([058cec6](https://github.com/shantanusharma/deepagents/commit/058cec654645dd1a504408d712ab678edc48273d))
* **code:** add durable Debug Console cost breakdown ([#6246](https://github.com/shantanusharma/deepagents/issues/6246)) ([c981748](https://github.com/shantanusharma/deepagents/commit/c9817483eeea620b1523dcfaed2802269c79d4fe))
* **code:** add extension trust and inspection UX ([#5634](https://github.com/shantanusharma/deepagents/issues/5634)) ([da5dcdc](https://github.com/shantanusharma/deepagents/commit/da5dcdc1df38218f50d57be37908bc39438e3f2b))
* **code:** add Fireworks `kimi-k3` to model switcher ([#5082](https://github.com/shantanusharma/deepagents/issues/5082)) ([82e799c](https://github.com/shantanusharma/deepagents/commit/82e799c7191adcb3bf96eb0435d55edd58cc1883))
* **code:** add Fireworks session settings ([#4360](https://github.com/shantanusharma/deepagents/issues/4360)) ([90ebb1d](https://github.com/shantanusharma/deepagents/commit/90ebb1d68cb5942f07847f6dce48c14c7caef992))
* **code:** add GLM-5.2-Fast and Kimi-K3 to recommended models ([#5072](https://github.com/shantanusharma/deepagents/issues/5072)) ([a33494e](https://github.com/shantanusharma/deepagents/commit/a33494ec580c289c58f725e19364fc21ef8cc26c))
* **code:** add GPT-6.1 Terra ([#7295](https://github.com/shantanusharma/deepagents/issues/7295)) ([315c2c9](https://github.com/shantanusharma/deepagents/commit/315c2c964e3cf0eded2c36eff5cd5bf8c2e6dfb9))
* **code:** add GPT-6.2 Astra and Sol to model picker ([#7831](https://github.com/shantanusharma/deepagents/issues/7831)) ([759a795](https://github.com/shantanusharma/deepagents/commit/759a795ecc496953e4e57fdff985b9c7bd58a9f8))
* **code:** add Grok 4.5 model ([#4596](https://github.com/shantanusharma/deepagents/issues/4596)) ([b0a209d](https://github.com/shantanusharma/deepagents/commit/b0a209da3a8c9f80e2e3d5e199340736c854c567))
* **code:** add Hooks v2 capability snapshots ([#4916](https://github.com/shantanusharma/deepagents/issues/4916)) ([8b4e508](https://github.com/shantanusharma/deepagents/commit/8b4e508d4664ef02e220854d50f5d98e0913aed8))
* **code:** add Hooks v2 execution engine ([#4880](https://github.com/shantanusharma/deepagents/issues/4880)) ([f0b198f](https://github.com/shantanusharma/deepagents/commit/f0b198faa220ad90f24713f08acc09d41e4a81de))
* **code:** add Hooks v2 session transcripts ([#4918](https://github.com/shantanusharma/deepagents/issues/4918)) ([ca86fbe](https://github.com/shantanusharma/deepagents/commit/ca86fbecca1a43facb4281397760c5e52edb1ddd))
* **code:** add interactive goal management ([#4693](https://github.com/shantanusharma/deepagents/issues/4693)) ([64205e2](https://github.com/shantanusharma/deepagents/commit/64205e238c280ae05b2bf9253ac40c6f85ffb49c))
* **code:** add isolated `/btw` side questions ([#6434](https://github.com/shantanusharma/deepagents/issues/6434)) ([7ca901a](https://github.com/shantanusharma/deepagents/commit/7ca901ac4bf8fc1342ddca486c1bd4895a5a0f48))
* **code:** add Kimi K3 to model selector under OpenRouter ([#4803](https://github.com/shantanusharma/deepagents/issues/4803)) ([fc94bb7](https://github.com/shantanusharma/deepagents/commit/fc94bb7da9e66218de063aa4415dcf9717f15fce))
* **code:** add LangSmith base URL to `/auth` ([#4228](https://github.com/shantanusharma/deepagents/issues/4228)) ([88d167f](https://github.com/shantanusharma/deepagents/commit/88d167f9ceec1cfadd7c3feac6f63c0da7c893f1))
* **code:** add LangSmith tracing config to `/auth` ([#4193](https://github.com/shantanusharma/deepagents/issues/4193)) ([8e62957](https://github.com/shantanusharma/deepagents/commit/8e6295791093c2ddfec7e6ac57f0df7f12048447))
* **code:** add latest frontier models to recommended list ([#4045](https://github.com/shantanusharma/deepagents/issues/4045)) ([1145356](https://github.com/shantanusharma/deepagents/commit/114535637eaee383c64eac5282bc9ac57007c83f))
* **code:** add macOS keyboard shortcuts for line navigation ([#3575](https://github.com/shantanusharma/deepagents/issues/3575)) ([2a3031d](https://github.com/shantanusharma/deepagents/commit/2a3031d7846572f91face567ffdd8976b9dda64d))
* **code:** add MCP error detail modal ([#3687](https://github.com/shantanusharma/deepagents/issues/3687)) ([4ae4754](https://github.com/shantanusharma/deepagents/commit/4ae475453ce0df6d6b057b7e163396aa27d55143))
* **code:** add Meta `muse-spark-1.2` to model switcher ([#5389](https://github.com/shantanusharma/deepagents/issues/5389)) ([922b285](https://github.com/shantanusharma/deepagents/commit/922b285598be3b2ca6b3ec01e7362e31ad2014b2))
* **code:** add Meta model provider ([#4650](https://github.com/shantanusharma/deepagents/issues/4650)) ([70829c5](https://github.com/shantanusharma/deepagents/commit/70829c5846b6bdde1cee51f0f4929e819ba1026b))
* **code:** add NVIDIA OpenShell sandbox provider ([#6999](https://github.com/shantanusharma/deepagents/issues/6999)) ([84d4b14](https://github.com/shantanusharma/deepagents/commit/84d4b146cdc3ab45e3e0b9c79c972690ad814ab1))
* **code:** add OpenRouter `z-ai/glm-5.3` to model switcher ([#5641](https://github.com/shantanusharma/deepagents/issues/5641)) ([6295924](https://github.com/shantanusharma/deepagents/commit/6295924d428fb061945cd83940c47c765091353b))
* **code:** add optional extra uninstall commands ([#5875](https://github.com/shantanusharma/deepagents/issues/5875)) ([d36f226](https://github.com/shantanusharma/deepagents/commit/d36f22694d4b5d9ac9fa806292389954861cd53b))
* **code:** add Opus 4.8 to recommended models ([#4204](https://github.com/shantanusharma/deepagents/issues/4204)) ([8faf2b0](https://github.com/shantanusharma/deepagents/commit/8faf2b025f8429481a41a3e65544d26614e53589))
* **code:** add persistent thread names and manual renaming ([#6715](https://github.com/shantanusharma/deepagents/issues/6715)) ([16e84d9](https://github.com/shantanusharma/deepagents/commit/16e84d927e7e13c41a10c071380c875af6a562f5))
* **code:** add plugin list search ([#4765](https://github.com/shantanusharma/deepagents/issues/4765)) ([a6c20b1](https://github.com/shantanusharma/deepagents/commit/a6c20b1a4d2a8b8a03690460a30c501ab7fbb6cb))
* **code:** add plugin marketplace support ([#4554](https://github.com/shantanusharma/deepagents/issues/4554)) ([0187d14](https://github.com/shantanusharma/deepagents/commit/0187d14b83301c116a2f177e6e04ae7a8cc99ca7))
* **code:** add pre-release update support ([#3960](https://github.com/shantanusharma/deepagents/issues/3960)) ([341a5cc](https://github.com/shantanusharma/deepagents/commit/341a5cc55a30d808dbb366b396923c7801c431d2))
* **code:** add project hooks workspace trust ([#5105](https://github.com/shantanusharma/deepagents/issues/5105)) ([9b2185b](https://github.com/shantanusharma/deepagents/commit/9b2185b65d4cbbaad9dd1b632162810a0aefd7eb))
* **code:** add provider-specific auth guidance ([#4004](https://github.com/shantanusharma/deepagents/issues/4004)) ([6a39247](https://github.com/shantanusharma/deepagents/commit/6a392471ba30089b1a63135494873d55209bb081))
* **code:** add reasoning effort selector ([#4403](https://github.com/shantanusharma/deepagents/issues/4403)) ([6ee0ac4](https://github.com/shantanusharma/deepagents/commit/6ee0ac4cca998f84e157187d565084e2a1912626))
* **code:** add rubric-backed goal workflow ([#4365](https://github.com/shantanusharma/deepagents/issues/4365)) ([8fca61d](https://github.com/shantanusharma/deepagents/commit/8fca61dc036888a4414ff5a4536b957c63dab4a5))
* **code:** add shell completion scripts via `dcode completion` ([#7264](https://github.com/shantanusharma/deepagents/issues/7264)) ([41b8cdb](https://github.com/shantanusharma/deepagents/commit/41b8cdbf1c2f764e9cd8da8182094befb3859910))
* **code:** add structured TUI display for `js_eval` ([#4151](https://github.com/shantanusharma/deepagents/issues/4151)) ([91c0dae](https://github.com/shantanusharma/deepagents/commit/91c0dae3fe0253f02a5926fcd3c6f796cd8d11fe))
* **code:** add thread picker ([#6197](https://github.com/shantanusharma/deepagents/issues/6197)) ([9d3da12](https://github.com/shantanusharma/deepagents/commit/9d3da1287ba5656d52ad7f2c75cf9062d46a4959))
* **code:** add toggleable message timestamp footers ([#3662](https://github.com/shantanusharma/deepagents/issues/3662)) ([977e110](https://github.com/shantanusharma/deepagents/commit/977e11006cfbd78fbaba4e7bb2a13acf6b788652))
* **code:** add typed hooks data models ([#4870](https://github.com/shantanusharma/deepagents/issues/4870)) ([0967012](https://github.com/shantanusharma/deepagents/commit/09670121b8d20fa8029804143852f6fcc6135dba))
* **code:** adopt coding-agent-v1 trace metadata ([#4367](https://github.com/shantanusharma/deepagents/issues/4367)) ([cb39747](https://github.com/shantanusharma/deepagents/commit/cb3974748024fcec2e2ee0ccc0a9b23c880733a2))
* **code:** allow dependency updates without requiring release ([#4157](https://github.com/shantanusharma/deepagents/issues/4157)) ([7beb97a](https://github.com/shantanusharma/deepagents/commit/7beb97a2b02e2fd238baf3b6f05d43a4accf3f42))
* **code:** allow muting the "YOLO is active" toast ([#5103](https://github.com/shantanusharma/deepagents/issues/5103)) ([4d2d6ae](https://github.com/shantanusharma/deepagents/commit/4d2d6aed808575e2e03539bc7fa84562c93b7eb5))
* **code:** apply hook command rewrites before tool approval ([#7384](https://github.com/shantanusharma/deepagents/issues/7384)) ([8117715](https://github.com/shantanusharma/deepagents/commit/81177151d9002cabff40601f73ae73961dc11246))
* **code:** attribute skill invocations in trace metadata ([#5925](https://github.com/shantanusharma/deepagents/issues/5925)) ([68fa627](https://github.com/shantanusharma/deepagents/commit/68fa627522e60fe5d5278b454d21fa63a40b2d35))
* **code:** auto-accept `/goal` criteria in YOLO mode ([#4784](https://github.com/shantanusharma/deepagents/issues/4784)) ([cc662f2](https://github.com/shantanusharma/deepagents/commit/cc662f236dbf72303be5cbf2c4cfd00710a2d32c))
* **code:** auto-detect MCP OAuth from 401 challenge ([#4364](https://github.com/shantanusharma/deepagents/issues/4364)) ([9763ffc](https://github.com/shantanusharma/deepagents/commit/9763ffceab8800526ae9fe10decdb2f32d8e4707))
* **code:** auto-install ripgrep on first run ([#3348](https://github.com/shantanusharma/deepagents/issues/3348)) ([fecf22b](https://github.com/shantanusharma/deepagents/commit/fecf22b0909e79ff7bdf180baf20abf5fdf1f390))
* **code:** auto-retry credentials-blocked startup after `/auth` ([#4176](https://github.com/shantanusharma/deepagents/issues/4176)) ([d10ba3d](https://github.com/shantanusharma/deepagents/commit/d10ba3dc162e47cc71df56b8e3d0000b6e0ed847))
* **code:** auto-update installed plugins ([#5368](https://github.com/shantanusharma/deepagents/issues/5368)) ([3bf6ca7](https://github.com/shantanusharma/deepagents/commit/3bf6ca7ac076bc0330b65d244e3b46f398674de8))
* **code:** bind conversations to a recorded workspace ([#5946](https://github.com/shantanusharma/deepagents/issues/5946)) ([4ca758e](https://github.com/shantanusharma/deepagents/commit/4ca758ed8efd9b586b26685bc3dc787501f3d502))
* **code:** bring selected text into the chat input ([#6955](https://github.com/shantanusharma/deepagents/issues/6955)) ([09b14d9](https://github.com/shantanusharma/deepagents/commit/09b14d917a859021b7c66e2868e917ad6663034d))
* **code:** browser loopback OAuth callback for MCP auth ([#3467](https://github.com/shantanusharma/deepagents/issues/3467)) ([d83aa07](https://github.com/shantanusharma/deepagents/commit/d83aa07c818af35800f81d062a147fa45a47ace7))
* **code:** carry `TERM_PROGRAM` into the resume hint ([#5548](https://github.com/shantanusharma/deepagents/issues/5548)) ([3cdc821](https://github.com/shantanusharma/deepagents/commit/3cdc82181bc94a904290cce23db04d8a1341b123))
* **code:** ChatGPT OAuth sign-in for Codex models ([#3532](https://github.com/shantanusharma/deepagents/issues/3532)) ([202e0bd](https://github.com/shantanusharma/deepagents/commit/202e0bd3e5b8b874a69656815489308d75a77d05))
* **code:** clarify install-script messaging for editable installs ([#3600](https://github.com/shantanusharma/deepagents/issues/3600)) ([5e4306f](https://github.com/shantanusharma/deepagents/commit/5e4306feed530e2b3bdc081ba703b591cbc53eac))
* **code:** classifier-backed Auto approval mode ([#4804](https://github.com/shantanusharma/deepagents/issues/4804)) ([eae7c28](https://github.com/shantanusharma/deepagents/commit/eae7c28f1152a5116b5b330c9fa1088ce173656d))
* **code:** clear chat input via `esc+esc`, add `[ X ]/[ COPY ]` buttons ([#4000](https://github.com/shantanusharma/deepagents/issues/4000)) ([c20546f](https://github.com/shantanusharma/deepagents/commit/c20546feac7876786e6816776d1ccfa5fcd4b2c8))
* **code:** CLI config provider ([#5774](https://github.com/shantanusharma/deepagents/issues/5774)) ([951a1cf](https://github.com/shantanusharma/deepagents/commit/951a1cf54b9fa373f1853685b21a084512ab2937))
* **code:** click the splash `thread` ID to copy it ([#5173](https://github.com/shantanusharma/deepagents/issues/5173)) ([be2e505](https://github.com/shantanusharma/deepagents/commit/be2e5054b9dffdf9ba9032a198c0ae5f8a0cccd1))
* **code:** collapse completed tool calls into group summaries ([#4373](https://github.com/shantanusharma/deepagents/issues/4373)) ([3735829](https://github.com/shantanusharma/deepagents/commit/3735829a0c14fb1537daf930140c66b647c8222c))
* **code:** collapse large pastes into compact placeholders ([#4447](https://github.com/shantanusharma/deepagents/issues/4447)) ([9ae927d](https://github.com/shantanusharma/deepagents/commit/9ae927d73ebf30ba50bbb7ec0c1076a0937e5cb7))
* **code:** collect Tavily key during onboarding ([#4233](https://github.com/shantanusharma/deepagents/issues/4233)) ([e321cba](https://github.com/shantanusharma/deepagents/commit/e321cba5701313e974f979069186680f1a39587c))
* **code:** compact large idle sessions before cache expiry ([#6956](https://github.com/shantanusharma/deepagents/issues/6956)) ([3698b14](https://github.com/shantanusharma/deepagents/commit/3698b146b7c2db6d15d42b2d77568f93e169f36a))
* **code:** condense status bar cwd from the middle, tail intact ([#6252](https://github.com/shantanusharma/deepagents/issues/6252)) ([f733893](https://github.com/shantanusharma/deepagents/commit/f7338933e5ebd6959820023efb66704d6ab8ce7f))
* **code:** configurable Auto classifier review timeout ([#5302](https://github.com/shantanusharma/deepagents/issues/5302)) ([7bd977b](https://github.com/shantanusharma/deepagents/commit/7bd977bc9d4c11aad90dbef7872d83c2affd584e))
* **code:** configure and load Python extensions ([#5632](https://github.com/shantanusharma/deepagents/issues/5632)) ([017d7ae](https://github.com/shantanusharma/deepagents/commit/017d7ae41fe1dfe3fe7fa07bfa206959170707ed))
* **code:** configure Auto goal criteria acceptance ([#4940](https://github.com/shantanusharma/deepagents/issues/4940)) ([37addfc](https://github.com/shantanusharma/deepagents/commit/37addfc8bb5533d6670d14defea38770c8d54d1e))
* **code:** confirm "Launched" after auto-update restart ([#4098](https://github.com/shantanusharma/deepagents/issues/4098)) ([df8db8a](https://github.com/shantanusharma/deepagents/commit/df8db8af6a7cbfc2ab535020b951d73759da73dd))
* **code:** confirm modal for `/install --package` ([#3840](https://github.com/shantanusharma/deepagents/issues/3840)) ([3d75026](https://github.com/shantanusharma/deepagents/commit/3d75026e2f241648fae78d9e1de2cbb4985f58ff))
* **code:** confirm model switches with large context ([#5829](https://github.com/shantanusharma/deepagents/issues/5829)) ([acc3d33](https://github.com/shantanusharma/deepagents/commit/acc3d33f357c027ec298bf7682d407a15249e706))
* **code:** copy current model from picker header ([#5904](https://github.com/shantanusharma/deepagents/issues/5904)) ([cfd9e7a](https://github.com/shantanusharma/deepagents/commit/cfd9e7aedfd4438d284bf5b567dbc858936af2e4))
* **code:** copy focused input selection on `Ctrl+C` ([#3841](https://github.com/shantanusharma/deepagents/issues/3841)) ([99f782c](https://github.com/shantanusharma/deepagents/commit/99f782cf08336c200d02a24ae4edaa650af67ed2))
* **code:** copy highlighted thread ID with `ctrl+c` ([#6431](https://github.com/shantanusharma/deepagents/issues/6431)) ([0a6bd89](https://github.com/shantanusharma/deepagents/commit/0a6bd899a0760af76bca025ea6af39997b78e611))
* **code:** copy model slug with Ctrl+click ([#6243](https://github.com/shantanusharma/deepagents/issues/6243)) ([8a5c317](https://github.com/shantanusharma/deepagents/commit/8a5c317e45edb0df4ad42ae79c1c5a6f8cff407f))
* **code:** customize terminal tab titles ([#6768](https://github.com/shantanusharma/deepagents/issues/6768)) ([a4a51d0](https://github.com/shantanusharma/deepagents/commit/a4a51d07cd756d2ff285e0e59655887e30e56bf8))
* **code:** Debug Console thread ID click-to-copy with LangSmith link ([#4760](https://github.com/shantanusharma/deepagents/issues/4760)) ([2d35507](https://github.com/shantanusharma/deepagents/commit/2d35507b5c7ff7f504f3d294ac499140752c4f59))
* **code:** debug-log skill-name override collisions ([#4772](https://github.com/shantanusharma/deepagents/issues/4772)) ([77603c6](https://github.com/shantanusharma/deepagents/commit/77603c69e2eeededf6f1df68b384da27f7d2843f))
* **code:** default Anthropic Auto classifier to Claude Sonnet 5.5 ([#7163](https://github.com/shantanusharma/deepagents/issues/7163)) ([ad0fc5e](https://github.com/shantanusharma/deepagents/commit/ad0fc5ea19c41611891e40af403bcacb0a123fdf))
* **code:** default Auto classifier by provider ([#6039](https://github.com/shantanusharma/deepagents/issues/6039)) ([99ed6c8](https://github.com/shantanusharma/deepagents/commit/99ed6c83238851eb334e19b27d3faec8869fc9a7))
* **code:** default general-purpose subagents to fork mode ([#6024](https://github.com/shantanusharma/deepagents/issues/6024)) ([d3ad134](https://github.com/shantanusharma/deepagents/commit/d3ad134a49287d80b9897b0ef38b4635f8d7de94))
* **code:** default the stale editable-deps prompt to `Refresh environment now` ([#5810](https://github.com/shantanusharma/deepagents/issues/5810)) ([de60958](https://github.com/shantanusharma/deepagents/commit/de60958a7d79bd4f63b678e8b4e3f02230060879))
* **code:** defer MCP schemas with provider-native tool search ([#7304](https://github.com/shantanusharma/deepagents/issues/7304)) ([f9cbdba](https://github.com/shantanusharma/deepagents/commit/f9cbdbaebe9a07c3024d389bbaa2cabde4fc3a7b))
* **code:** define and discover Python extensions ([#5631](https://github.com/shantanusharma/deepagents/issues/5631)) ([738bf07](https://github.com/shantanusharma/deepagents/commit/738bf077f8b079164f11742bfcaa2fa93df138d7))
* **code:** detect and notify plugin updates ([#7234](https://github.com/shantanusharma/deepagents/issues/7234)) ([ebd7592](https://github.com/shantanusharma/deepagents/commit/ebd7592723b5989d155ee94b9ff7df9ac2afe425))
* **code:** disable MCP servers from TUI ([#3501](https://github.com/shantanusharma/deepagents/issues/3501)) ([5725de8](https://github.com/shantanusharma/deepagents/commit/5725de857722dbca768a95bc6d97af5b838a11a9))
* **code:** distinguish skill reads in the transcript ([#6825](https://github.com/shantanusharma/deepagents/issues/6825)) ([65a21a4](https://github.com/shantanusharma/deepagents/commit/65a21a47f7ffe31afa0a525a0d1ec2fff1262da5))
* **code:** drop `TodoListMiddleware` ([#4685](https://github.com/shantanusharma/deepagents/issues/4685)) ([d3a3077](https://github.com/shantanusharma/deepagents/commit/d3a3077e8536696dcf4a9dcd8555e9c871562e74))
* **code:** drop redundant `shell` and `web_search` prompt guidance ([#5213](https://github.com/shantanusharma/deepagents/issues/5213)) ([6305fdb](https://github.com/shantanusharma/deepagents/commit/6305fdbf8d94d061193a908715f2c629893b47ff))
* **code:** dual-write agent traces to extra LangSmith projects ([#3998](https://github.com/shantanusharma/deepagents/issues/3998)) ([1b94cf3](https://github.com/shantanusharma/deepagents/commit/1b94cf322949e0cafd6f2bacf343fb0044ec5a8c))
* **code:** emit a `cache_expiring` hook before prompt-cache expiry ([#6638](https://github.com/shantanusharma/deepagents/issues/6638)) ([30975d0](https://github.com/shantanusharma/deepagents/commit/30975d02b9a18e5d6c1dede8bf02313cc024ea70))
* **code:** enable `js_eval` by default ([#4245](https://github.com/shantanusharma/deepagents/issues/4245)) ([2e04ff3](https://github.com/shantanusharma/deepagents/commit/2e04ff397e60389c9a19c4a9b528e15602ad8338))
* **code:** enable secret redaction by default ([#5816](https://github.com/shantanusharma/deepagents/issues/5816)) ([fd7d268](https://github.com/shantanusharma/deepagents/commit/fd7d2682271cc36180f361f89d1a69557637a03f))
* **code:** encode multi-select `ask_user` answers as JSON arrays ([#5660](https://github.com/shantanusharma/deepagents/issues/5660)) ([fc70294](https://github.com/shantanusharma/deepagents/commit/fc70294bcf9ac134c21646bcbe8546aab001442d))
* **code:** enforce configured model allowlists ([#5649](https://github.com/shantanusharma/deepagents/issues/5649)) ([dd8b8ad](https://github.com/shantanusharma/deepagents/commit/dd8b8ad84aab54dfe1da4a277dfa9539a03e645c))
* **code:** escape to manual mode in YOLO notice, mode slash commands ([#5092](https://github.com/shantanusharma/deepagents/issues/5092)) ([d93336b](https://github.com/shantanusharma/deepagents/commit/d93336bfca4664abc3994cb28970ea3fbeeb1b77))
* **code:** expand environment variables in MCP config ([#4681](https://github.com/shantanusharma/deepagents/issues/4681)) ([4f5d7be](https://github.com/shantanusharma/deepagents/commit/4f5d7be1b4073dee346e5a974841721646fa4860))
* **code:** expand truncated `task` descriptions on click or `Ctrl+O` ([#4811](https://github.com/shantanusharma/deepagents/issues/4811)) ([2ddb551](https://github.com/shantanusharma/deepagents/commit/2ddb551bd77d210d689f3a75037259ade4fbf54a))
* **code:** fall back to folder name for subagents ([#4504](https://github.com/shantanusharma/deepagents/issues/4504)) ([9db3db5](https://github.com/shantanusharma/deepagents/commit/9db3db5f31a93fb8598a5dc5bedf4fe61fe92c94))
* **code:** first-class `[retries]` config ([#3772](https://github.com/shantanusharma/deepagents/issues/3772)) ([9334d91](https://github.com/shantanusharma/deepagents/commit/9334d91ef94997e46d5373daca9c146fa9498763))
* **code:** float unauthorized MCP servers to top and prompt before reconnect ([#3493](https://github.com/shantanusharma/deepagents/issues/3493)) ([2d66580](https://github.com/shantanusharma/deepagents/commit/2d665804131961dfa7e2849248047deec818e4ef))
* **code:** frame HITL rejection reasons for the model ([#5259](https://github.com/shantanusharma/deepagents/issues/5259)) ([89c814b](https://github.com/shantanusharma/deepagents/commit/89c814b29249b44a8a6122f6c359db3601a6802e))
* **code:** gate `TERM_PROGRAM` resume hints ([#5580](https://github.com/shantanusharma/deepagents/issues/5580)) ([e8035e7](https://github.com/shantanusharma/deepagents/commit/e8035e78e8be9d1edfe9a131bcc0df12349f754d))
* **code:** gate debug console click-to-copy behind a checkbox ([#4810](https://github.com/shantanusharma/deepagents/issues/4810)) ([a485404](https://github.com/shantanusharma/deepagents/commit/a4854042e5fe9f3acf629b0646a6bf8e348ccc9a))
* **code:** gate onboarding integrations modal behind opt-in flag ([#4227](https://github.com/shantanusharma/deepagents/issues/4227)) ([6c930c5](https://github.com/shantanusharma/deepagents/commit/6c930c5e4502f572be554acc896c5fb6d061e0e5))
* **code:** gate paste auto-collapse behind `display.collapse_pastes` ([#4473](https://github.com/shantanusharma/deepagents/issues/4473)) ([ff5dd56](https://github.com/shantanusharma/deepagents/commit/ff5dd564a3a590e7d2d521b20df495b5e1512e12))
* **code:** generate thread names automatically and on demand ([#6767](https://github.com/shantanusharma/deepagents/issues/6767)) ([218b3d6](https://github.com/shantanusharma/deepagents/commit/218b3d68c9ab8e2857dd0aafceeadeb34d0f0d01))
* **code:** guard managed onboarding-name memory block from edits ([#3822](https://github.com/shantanusharma/deepagents/issues/3822)) ([dc0a51f](https://github.com/shantanusharma/deepagents/commit/dc0a51fc81d01b62dc8043148a9fd87099fc9123))
* **code:** hide diff widget for credential files ([#4593](https://github.com/shantanusharma/deepagents/issues/4593)) ([4c49a24](https://github.com/shantanusharma/deepagents/commit/4c49a24c4c488f45859b45628cfa57719e52f596))
* **code:** highlight expired prompt caches as banner ([#6957](https://github.com/shantanusharma/deepagents/issues/6957)) ([70f4342](https://github.com/shantanusharma/deepagents/commit/70f43426ce7c0bf2d03c616e4ef4845ab9b75ca5))
* **code:** highlight shell commands in the chat input ([#5675](https://github.com/shantanusharma/deepagents/issues/5675)) ([d711bc6](https://github.com/shantanusharma/deepagents/commit/d711bc61300090181dc89e3e116e8b343fb65425))
* **code:** highlight the active multiline chat input line ([#6746](https://github.com/shantanusharma/deepagents/issues/6746)) ([99e1e9a](https://github.com/shantanusharma/deepagents/commit/99e1e9a4f9e58b7e436df29e7458731e9fd5bd89))
* **code:** host Python extensions in the agent runtime ([#5633](https://github.com/shantanusharma/deepagents/issues/5633)) ([2c8d154](https://github.com/shantanusharma/deepagents/commit/2c8d154c7616071919cab4947403dff701e74b31))
* **code:** improve `/goal` criteria UX ([#4694](https://github.com/shantanusharma/deepagents/issues/4694)) ([06f46ff](https://github.com/shantanusharma/deepagents/commit/06f46fffe36efa9f3adcb331b07df283d8bed874))
* **code:** improve onboarding Installed Integrations screen ([#4195](https://github.com/shantanusharma/deepagents/issues/4195)) ([0827bf1](https://github.com/shantanusharma/deepagents/commit/0827bf1b635b825121740ac8946dd6d98c815c7d))
* **code:** in-app Debug Console ([#4564](https://github.com/shantanusharma/deepagents/issues/4564)) ([4f94a30](https://github.com/shantanusharma/deepagents/commit/4f94a30c11efb1819b08647d15b50b9b1e7bf043))
* **code:** in-the-moment trust prompt for symlinked skills ([#4200](https://github.com/shantanusharma/deepagents/issues/4200)) ([a4431e4](https://github.com/shantanusharma/deepagents/commit/a4431e4339348431e91533cb2b177259ab94b083))
* **code:** in-TUI MCP OAuth login with auto-refresh ([#3469](https://github.com/shantanusharma/deepagents/issues/3469)) ([20e38b8](https://github.com/shantanusharma/deepagents/commit/20e38b8ebd8d9aa4697334432f7832a0a07aea3a))
* **code:** include `yolo` mode in `Shift+Tab` approval cycle ([#5035](https://github.com/shantanusharma/deepagents/issues/5035)) ([9f2cc21](https://github.com/shantanusharma/deepagents/commit/9f2cc212dc3ba59540a9f738d2849e38ac9ecfc2))
* **code:** include the official marketplace by default ([#7364](https://github.com/shantanusharma/deepagents/issues/7364)) ([0f803ba](https://github.com/shantanusharma/deepagents/commit/0f803ba3296fcc3ce702395a424d71d743ddd99c))
* **code:** integrate Hooks v2 client lifecycle events ([#5104](https://github.com/shantanusharma/deepagents/issues/5104)) ([e8702df](https://github.com/shantanusharma/deepagents/commit/e8702df601e137b65fe276270c3d3d589340bddf))
* **code:** integrate Hooks v2 server lifecycle events ([#4997](https://github.com/shantanusharma/deepagents/issues/4997)) ([2487c4b](https://github.com/shantanusharma/deepagents/commit/2487c4b87dff264ae1e8d34c7ce9249dd4b29760))
* **code:** JS interpreter middleware via `langchain-quickjs` ([#3525](https://github.com/shantanusharma/deepagents/issues/3525)) ([f0ca89c](https://github.com/shantanusharma/deepagents/commit/f0ca89c962c22058194121526638bc2d29f546bd))
* **code:** label plugin servers in the MCP viewer ([#6539](https://github.com/shantanusharma/deepagents/issues/6539)) ([d9defc1](https://github.com/shantanusharma/deepagents/commit/d9defc124448fed2261b290e060c0cd532b0143a))
* **code:** let the rubric grader inspect working-directory files ([#4835](https://github.com/shantanusharma/deepagents/issues/4835)) ([5dcf749](https://github.com/shantanusharma/deepagents/commit/5dcf749a6e7d5ab6611f30d485a3382c7ef31f22))
* **code:** limit thread resume age ([#6068](https://github.com/shantanusharma/deepagents/issues/6068)) ([318311f](https://github.com/shantanusharma/deepagents/commit/318311f56c3d3b9c4af4ece22fcfc387eeece5cc))
* **code:** link doctor commit hash to GitHub ([#5920](https://github.com/shantanusharma/deepagents/issues/5920)) ([c9e6f55](https://github.com/shantanusharma/deepagents/commit/c9e6f55c3ee4b6efedfc945fd1c9b160e6e2a872))
* **code:** list DeepSeek V4.1 Flash in picker ([#6254](https://github.com/shantanusharma/deepagents/issues/6254)) ([0a93587](https://github.com/shantanusharma/deepagents/commit/0a9358749d7654cc0bd9273a9e007be89abf316d))
* **code:** list MCP servers needing login ([#5867](https://github.com/shantanusharma/deepagents/issues/5867)) ([a71cafd](https://github.com/shantanusharma/deepagents/commit/a71cafdbbd851db65dc311eebe5574982866b222))
* **code:** list valid extras when `/install` has no argument ([#3695](https://github.com/shantanusharma/deepagents/issues/3695)) ([c7d529c](https://github.com/shantanusharma/deepagents/commit/c7d529ca0fc478dec9060ea04bcc8589f9b1cd3a))
* **code:** load hooks from installed plugins ([#5198](https://github.com/shantanusharma/deepagents/issues/5198)) ([0828b02](https://github.com/shantanusharma/deepagents/commit/0828b02d30c7b5557ecfce7c4a4039e0d9c4c571))
* **code:** load managed config from a remote source ([#5776](https://github.com/shantanusharma/deepagents/issues/5776)) ([9f3a1dd](https://github.com/shantanusharma/deepagents/commit/9f3a1dd38f8b5dbd828d2f366e9b03dad359fadf))
* **code:** load older threads from the thread switcher ([#7051](https://github.com/shantanusharma/deepagents/issues/7051)) ([82cca1d](https://github.com/shantanusharma/deepagents/commit/82cca1da885152718f7e055a4b96835425da841f))
* **code:** local pricing overrides as a fallback when genai-prices misses ([#5304](https://github.com/shantanusharma/deepagents/issues/5304)) ([89bcaf2](https://github.com/shantanusharma/deepagents/commit/89bcaf2c31ab347cb4cb4563bc18f296dbecea08))
* **code:** make `/offload` server-owned ([#5261](https://github.com/shantanusharma/deepagents/issues/5261)) ([b494f43](https://github.com/shantanusharma/deepagents/commit/b494f43437de3569c8c512d65f5f3accda8e0730))
* **code:** make auto-update opt-out by default ([#3994](https://github.com/shantanusharma/deepagents/issues/3994)) ([7ff6e22](https://github.com/shantanusharma/deepagents/commit/7ff6e2224d7ba8462c073333da937c35831f9b34))
* **code:** make Hooks v2 generally available ([#5307](https://github.com/shantanusharma/deepagents/issues/5307)) ([4edebde](https://github.com/shantanusharma/deepagents/commit/4edebdedd61d6793f0f7b666f5ee26b414576805))
* **code:** make idle compaction settings filterable in traces ([#7624](https://github.com/shantanusharma/deepagents/issues/7624)) ([316aee2](https://github.com/shantanusharma/deepagents/commit/316aee267240de92c5b030265d5b85c92f8760c8))
* **code:** make plugins generally available ([#4797](https://github.com/shantanusharma/deepagents/issues/4797)) ([3da6e47](https://github.com/shantanusharma/deepagents/commit/3da6e471c26f1da4cddeb12a435bab92bd7866c6))
* **code:** make project `.env` loading configurable ([#5726](https://github.com/shantanusharma/deepagents/issues/5726)) ([995cad6](https://github.com/shantanusharma/deepagents/commit/995cad67519af294851282133f8c40f643807c88))
* **code:** make teardown usage stats configurable ([#5696](https://github.com/shantanusharma/deepagents/issues/5696)) ([c1d965a](https://github.com/shantanusharma/deepagents/commit/c1d965aa0db93f923ec17947fab34a5300c19141))
* **code:** make Version, Model, CWD copyable in Debug Console ([#4975](https://github.com/shantanusharma/deepagents/issues/4975)) ([52b8993](https://github.com/shantanusharma/deepagents/commit/52b8993489a9b6b92be077fe835743ef7704b6a0))
* **code:** manage Tavily web-search API key in `/auth` ([#4062](https://github.com/shantanusharma/deepagents/issues/4062)) ([90cc099](https://github.com/shantanusharma/deepagents/commit/90cc099b0998a9aa55df01e3bc12ad1597c65365))
* **code:** mark the interrupt cancellation message with `lc_source` ([#7501](https://github.com/shantanusharma/deepagents/issues/7501)) ([08ef3f6](https://github.com/shantanusharma/deepagents/commit/08ef3f65b45b2f23e5e7a1af197851a28fbe98a9))
* **code:** MCP screen metadata ([#3349](https://github.com/shantanusharma/deepagents/issues/3349)) ([ce2f07e](https://github.com/shantanusharma/deepagents/commit/ce2f07e7211f22b3f44a1a232088b89a469a0a99))
* **code:** migrate legacy hooks to v2 events ([#4971](https://github.com/shantanusharma/deepagents/issues/4971)) ([fdb585c](https://github.com/shantanusharma/deepagents/commit/fdb585c87b054979b8440bdc6ac97fc8ae628134))
* **code:** model-node retry middleware for transient model errors ([#4569](https://github.com/shantanusharma/deepagents/issues/4569)) ([948fea8](https://github.com/shantanusharma/deepagents/commit/948fea88e2c1e0660a3c1c7a077121c573f11675))
* **code:** move `/goal` criteria generation server-side ([#4754](https://github.com/shantanusharma/deepagents/issues/4754)) ([9fdd498](https://github.com/shantanusharma/deepagents/commit/9fdd498937842e2ac490ae0e0ca74eef47abd0bb))
* **code:** move MCP onto FastMCP and `langchain.mcp` ([#5922](https://github.com/shantanusharma/deepagents/issues/5922)) ([0692ef1](https://github.com/shantanusharma/deepagents/commit/0692ef1550568a585afe48705d54a4aa07002697))
* **code:** non-interactive `deepagents auth` subcommands ([#3910](https://github.com/shantanusharma/deepagents/issues/3910)) ([11a71bb](https://github.com/shantanusharma/deepagents/commit/11a71bbf00c4e6c1f989e70fb3472a65c8d39662))
* **code:** non-interactive rubric grading flags ([#4305](https://github.com/shantanusharma/deepagents/issues/4305)) ([1bcb112](https://github.com/shantanusharma/deepagents/commit/1bcb112ee78138eca9cb400c206ce198322aae32))
* **code:** note minimum OpenAI key permissions in `/auth` ([#4040](https://github.com/shantanusharma/deepagents/issues/4040)) ([14be63d](https://github.com/shantanusharma/deepagents/commit/14be63d476ed8dece75e20fff05016122c258be8))
* **code:** offer abort during resume ([#4188](https://github.com/shantanusharma/deepagents/issues/4188)) ([a4c25cd](https://github.com/shantanusharma/deepagents/commit/a4c25cd74de9902fd0ea9440b5dda2d4248bb3d2))
* **code:** offer abort in `/threads` cwd-switch prompt ([#4583](https://github.com/shantanusharma/deepagents/issues/4583)) ([aaeac99](https://github.com/shantanusharma/deepagents/commit/aaeac99d9f17b6a55d663c21a4d063444b6a1870))
* **code:** offer restart after restart-capable install ([#3821](https://github.com/shantanusharma/deepagents/issues/3821)) ([e356efe](https://github.com/shantanusharma/deepagents/commit/e356efeff1c8bfb894119cebbb7d3c0853d327a2))
* **code:** offer restart after saving Tavily key via `/auth` ([#4560](https://github.com/shantanusharma/deepagents/issues/4560)) ([12df81a](https://github.com/shantanusharma/deepagents/commit/12df81ad00d814c570b4d24a2b06de9b18d51abd))
* **code:** offer summarized threads when cache expires ([#6477](https://github.com/shantanusharma/deepagents/issues/6477)) ([64dccb0](https://github.com/shantanusharma/deepagents/commit/64dccb0600486786bdcd1bcd45eb9514f2b23cd4))
* **code:** open cost breakdown from the footer ([#6723](https://github.com/shantanusharma/deepagents/issues/6723)) ([4c55f5a](https://github.com/shantanusharma/deepagents/commit/4c55f5a80c376f61144e91cb796ca4303e7bc2a4))
* **code:** open effort selector during active runs ([#6724](https://github.com/shantanusharma/deepagents/issues/6724)) ([6ac63cf](https://github.com/shantanusharma/deepagents/commit/6ac63cf2cead6adb50e4404adc1cbf1b27ccdc41))
* **code:** open footer pickers on click ([#5674](https://github.com/shantanusharma/deepagents/issues/5674)) ([4f65325](https://github.com/shantanusharma/deepagents/commit/4f65325ed322ce1c650152b31532b219bfa3850c))
* **code:** open footer pickers with `ctrl+click` ([#5611](https://github.com/shantanusharma/deepagents/issues/5611)) ([ee339fb](https://github.com/shantanusharma/deepagents/commit/ee339fb8c39a1432f0cc12c181431c60b4e235f9))
* **code:** open summarization model picker ([#5932](https://github.com/shantanusharma/deepagents/issues/5932)) ([f90d4fe](https://github.com/shantanusharma/deepagents/commit/f90d4fe114efe1de1e3d8dd8e5aee5b9f631093d))
* **code:** optionally show visible reasoning ([#5887](https://github.com/shantanusharma/deepagents/issues/5887)) ([457ac43](https://github.com/shantanusharma/deepagents/commit/457ac435e1216d3f7cac76d4e856b7aa020b5ea8))
* **code:** pair model API keys with their endpoints ([#3770](https://github.com/shantanusharma/deepagents/issues/3770)) ([cf98030](https://github.com/shantanusharma/deepagents/commit/cf9803072dc0fdc1d5850c9fd2fc4eb6893ed8c9))
* **code:** persist `/threads` directory-scope preference ([#3824](https://github.com/shantanusharma/deepagents/issues/3824)) ([51a29f4](https://github.com/shantanusharma/deepagents/commit/51a29f4a0c28c122acae296a0df03bee20474455))
* **code:** persist and reconfigure ACP sessions ([#5366](https://github.com/shantanusharma/deepagents/issues/5366)) ([22a36d2](https://github.com/shantanusharma/deepagents/commit/22a36d25d9e82902fa28cdacdcb51cd6a9b013d7))
* **code:** persist Debug Console `Ctrl+L` clear across reopen ([#4812](https://github.com/shantanusharma/deepagents/issues/4812)) ([20089a5](https://github.com/shantanusharma/deepagents/commit/20089a53703b031726fdc898831bb09f434527b7))
* **code:** persist project MCP startup denials ([#6597](https://github.com/shantanusharma/deepagents/issues/6597)) ([5c2533e](https://github.com/shantanusharma/deepagents/commit/5c2533e0972daf6478b02b0e2eb66e9e46c27d5c))
* **code:** persist reasoning effort across restarts ([#4728](https://github.com/shantanusharma/deepagents/issues/4728)) ([c584dcf](https://github.com/shantanusharma/deepagents/commit/c584dcfb3ad287446e0209b8bd4ca31cee587eea))
* **code:** persistent banner when installation is stale ([#4459](https://github.com/shantanusharma/deepagents/issues/4459)) ([b74c185](https://github.com/shantanusharma/deepagents/commit/b74c18591a8ce9a49a5fee43b07e602ca9fbf68a))
* **code:** personalize external editor hints ([#5445](https://github.com/shantanusharma/deepagents/issues/5445)) ([b72b3dd](https://github.com/shantanusharma/deepagents/commit/b72b3dd72e0a31962ebf19261dba547462b4e394))
* **code:** pluggable third-party sandbox backends ([#3842](https://github.com/shantanusharma/deepagents/issues/3842)) ([2b635a7](https://github.com/shantanusharma/deepagents/commit/2b635a7e6e6b50ca8ce783c2ac96ed8643ae0224))
* **code:** point back to the previous thread after a switch ([#5172](https://github.com/shantanusharma/deepagents/issues/5172)) ([4507f9f](https://github.com/shantanusharma/deepagents/commit/4507f9f1985f29e9d4af7577293da64ec12b131c))
* **code:** port from `libs/cli` ([#3388](https://github.com/shantanusharma/deepagents/issues/3388)) ([2ac7d41](https://github.com/shantanusharma/deepagents/commit/2ac7d4153398889100d5fd163ab4a122633862b5))
* **code:** prompt before updating an out-of-date dcode install ([#3995](https://github.com/shantanusharma/deepagents/issues/3995)) ([a5ec6dd](https://github.com/shantanusharma/deepagents/commit/a5ec6dd0fec66ad321c1cc0f5e2f990c9026e03f))
* **code:** prompt clipboard ([#5733](https://github.com/shantanusharma/deepagents/issues/5733)) ([c2f44ff](https://github.com/shantanusharma/deepagents/commit/c2f44ffd2759401a5ba31b5f7c41a12b441d6663))
* **code:** prompt to install provider when selecting an uninstalled model ([#3981](https://github.com/shantanusharma/deepagents/issues/3981)) ([619207c](https://github.com/shantanusharma/deepagents/commit/619207c8d4d4308a9a3ab9d2d039506feeaf8a67))
* **code:** prompt to reconnect when leaving `/mcp` with pending toggles ([#5211](https://github.com/shantanusharma/deepagents/issues/5211)) ([53d1fb8](https://github.com/shantanusharma/deepagents/commit/53d1fb80cbd43f983782975d540fac34a11c4ccc))
* **code:** quiet install script's full dependency list ([#4058](https://github.com/shantanusharma/deepagents/issues/4058)) ([de2c9fd](https://github.com/shantanusharma/deepagents/commit/de2c9fd8c7437fdcdfe738599f83808c5423c55c))
* **code:** quieter diff hunks with word-level highlights ([#5106](https://github.com/shantanusharma/deepagents/issues/5106)) ([529f7e8](https://github.com/shantanusharma/deepagents/commit/529f7e8a16c7441873a305a9fa36c2721fa7a5b7))
* **code:** quit shortcut on completed update modal ([#4312](https://github.com/shantanusharma/deepagents/issues/4312)) ([5e6eae9](https://github.com/shantanusharma/deepagents/commit/5e6eae9f094a5167b6bf01f2d84cf06ca5cd80c3))
* **code:** raise agent recursion limit to 2000 and make it configurable ([#4994](https://github.com/shantanusharma/deepagents/issues/4994)) ([94962a5](https://github.com/shantanusharma/deepagents/commit/94962a5f588ce84991ad382b7713155d6a5a231e))
* **code:** re-auth MCP servers from viewer ([#5637](https://github.com/shantanusharma/deepagents/issues/5637)) ([d7c24d8](https://github.com/shantanusharma/deepagents/commit/d7c24d85f7b4d478116f022e1e969ddac89aeb2f))
* **code:** recognize LangSmith Gateway credentials ([#5042](https://github.com/shantanusharma/deepagents/issues/5042)) ([dcbff9c](https://github.com/shantanusharma/deepagents/commit/dcbff9c4d046bcd38ceef8e362691e8030036213))
* **code:** recommend DeepSeek V4 Flash 0731 ([#5244](https://github.com/shantanusharma/deepagents/issues/5244)) ([fbe4ec8](https://github.com/shantanusharma/deepagents/commit/fbe4ec8046c35313c6c05a986779111d84fe2536))
* **code:** recommend GLM 5.3 models ([#6211](https://github.com/shantanusharma/deepagents/issues/6211)) ([e7e88d5](https://github.com/shantanusharma/deepagents/commit/e7e88d5efaf2bbce33237ea323fb68487eabd721))
* **code:** recommend Haiku 5.5 for sidecar models ([#6844](https://github.com/shantanusharma/deepagents/issues/6844)) ([9597f95](https://github.com/shantanusharma/deepagents/commit/9597f95948b7b018af919448a0d67b4c3d71c2b1))
* **code:** refresh price catalog hourly in the background ([#5264](https://github.com/shantanusharma/deepagents/issues/5264)) ([2454afa](https://github.com/shantanusharma/deepagents/commit/2454afa58521f9dddb64bbde364a475694f45f4d))
* **code:** refresh stable model recommendations ([#7734](https://github.com/shantanusharma/deepagents/issues/7734)) ([f7ea946](https://github.com/shantanusharma/deepagents/commit/f7ea946df33f3a18ab6b5ad1e85eee0375aaad77))
* **code:** reload env from `/auth` modal via Ctrl+R ([#4566](https://github.com/shantanusharma/deepagents/issues/4566)) ([f07d638](https://github.com/shantanusharma/deepagents/commit/f07d6387b7dc1f0e880f77784905c2aa94143adb))
* **code:** rename `/summarization-model` to `/offload model` ([#6774](https://github.com/shantanusharma/deepagents/issues/6774)) ([b643f6f](https://github.com/shantanusharma/deepagents/commit/b643f6f34be0142fc3e33cd7402f171e62e69cc3))
* **code:** replace Gemini 3.5 Flash with 3.6 Flash in model switcher ([#4890](https://github.com/shantanusharma/deepagents/issues/4890)) ([5c99687](https://github.com/shantanusharma/deepagents/commit/5c99687bdecfd9e33051373581cacddbf7d0202a))
* **code:** replace Gemini 3.6 Flash with 3.7 Flash ([#5681](https://github.com/shantanusharma/deepagents/issues/5681)) ([9446182](https://github.com/shantanusharma/deepagents/commit/94461821d8d7e1ef1f1cd29bc0212c731c195ae5))
* **code:** report agent status to terminals with OSC 7501 ([#7772](https://github.com/shantanusharma/deepagents/issues/7772)) ([085128d](https://github.com/shantanusharma/deepagents/commit/085128d2a46737e32061246c69872dc218db53de))
* **code:** report tracing gateway in `dcode doctor` ([#4466](https://github.com/shantanusharma/deepagents/issues/4466)) ([a912427](https://github.com/shantanusharma/deepagents/commit/a9124275504bc1af5f76dfdd9a6c558c98eea92d))
* **code:** require an explicit or saved model selection ([#7365](https://github.com/shantanusharma/deepagents/issues/7365)) ([98de5eb](https://github.com/shantanusharma/deepagents/commit/98de5eb6ec5f8471f6919455466a77da4dd88a54))
* **code:** resize chat input by dragging its top border ([#5524](https://github.com/shantanusharma/deepagents/issues/5524)) ([d01e4ac](https://github.com/shantanusharma/deepagents/commit/d01e4ac5bf36752e5c89c1c6645d486282cb611f))
* **code:** resolve and trust-check invoked skills on the server ([#6837](https://github.com/shantanusharma/deepagents/issues/6837)) ([03fa53f](https://github.com/shantanusharma/deepagents/commit/03fa53ff68745610e2da15e30051c5e639047f88))
* **code:** restore interrupted prompt to input on ESC ([#4544](https://github.com/shantanusharma/deepagents/issues/4544)) ([fccf037](https://github.com/shantanusharma/deepagents/commit/fccf03732140d39749e70e8fc6cb7d73124a1d70))
* **code:** resume threads in non-interactive mode ([#7011](https://github.com/shantanusharma/deepagents/issues/7011)) ([a2f8843](https://github.com/shantanusharma/deepagents/commit/a2f88434c5a4b5ce5244c468bb9f69b27831842d))
* **code:** resume threads in-TUI with `/threads -r [ID]` ([#4609](https://github.com/shantanusharma/deepagents/issues/4609)) ([d442673](https://github.com/shantanusharma/deepagents/commit/d44267358e272553c8ece33d367514430be7c0da))
* **code:** reuse server across workspace switches ([#6152](https://github.com/shantanusharma/deepagents/issues/6152)) ([ca2d1ef](https://github.com/shantanusharma/deepagents/commit/ca2d1ef7f270d0fa1040e5473f43e99937b5f03f))
* **code:** running session cost in status bar and usage ([#5036](https://github.com/shantanusharma/deepagents/issues/5036)) ([539d4a0](https://github.com/shantanusharma/deepagents/commit/539d4a04380182438ca63ba6b902eb921dc8a600))
* **code:** selectable model for the Auto approval classifier ([#5205](https://github.com/shantanusharma/deepagents/issues/5205)) ([1d3feb1](https://github.com/shantanusharma/deepagents/commit/1d3feb1275a875f84f96f04a07e47cb6ec974b78))
* **code:** selective per-server project MCP trust ([#4507](https://github.com/shantanusharma/deepagents/issues/4507)) ([aaa22a9](https://github.com/shantanusharma/deepagents/commit/aaa22a9340cb3d2c8e9ce1a921957d0a9121da20))
* **code:** set `DEEPAGENTS_CODE=1` in the local shell environment ([#7701](https://github.com/shantanusharma/deepagents/issues/7701)) ([55951fc](https://github.com/shantanusharma/deepagents/commit/55951fc6ce7b751aa72f7aff5e5c2d4c7c1b8e2e))
* **code:** set `prompt_cache_key` for OpenAI models ([#4632](https://github.com/shantanusharma/deepagents/issues/4632)) ([8cf57ac](https://github.com/shantanusharma/deepagents/commit/8cf57aca9f41c3c4ca6d9796dc2cb80d4b22fb6d))
* **code:** show `"Took <duration>"` after `execute` finishes ([#4301](https://github.com/shantanusharma/deepagents/issues/4301)) ([a5240eb](https://github.com/shantanusharma/deepagents/commit/a5240ebe3654e72fa5beb4070224f52f944768c8))
* **code:** show `(debug enabled)` on splash when `DEEPAGENTS_CODE_DEBUG` is set ([#4584](https://github.com/shantanusharma/deepagents/issues/4584)) ([f10b877](https://github.com/shantanusharma/deepagents/commit/f10b877e5e48c3a1e15bd72d2ce06dfb16203231))
* **code:** show `ask_user` answers on the answered tool row ([#5100](https://github.com/shantanusharma/deepagents/issues/5100)) ([78ebe2d](https://github.com/shantanusharma/deepagents/commit/78ebe2d27c0ec5b5bf1368f1f1b1f442f9212717))
* **code:** show `read_file` arguments when expanded ([#6392](https://github.com/shantanusharma/deepagents/issues/6392)) ([902905f](https://github.com/shantanusharma/deepagents/commit/902905f2508fe74dc0ba13d857f502e8ddbc807e))
* **code:** show Auto approval review progress ([#5729](https://github.com/shantanusharma/deepagents/issues/5729)) ([8fe11f0](https://github.com/shantanusharma/deepagents/commit/8fe11f0c2566d95b0ca9af6db9ade7a4c58753e6))
* **code:** show cache timing in the footer ([#6394](https://github.com/shantanusharma/deepagents/issues/6394)) ([f4c226b](https://github.com/shantanusharma/deepagents/commit/f4c226b21cc07ee6cee6472ed726f86e69b8af36))
* **code:** show cached updates in version output ([#5817](https://github.com/shantanusharma/deepagents/issues/5817)) ([b6a7792](https://github.com/shantanusharma/deepagents/commit/b6a77921ceafbe5b6db576e62b5f3f1609e4ebe9))
* **code:** show changelog link before install-script update prompt ([#5034](https://github.com/shantanusharma/deepagents/issues/5034)) ([e3d2a87](https://github.com/shantanusharma/deepagents/commit/e3d2a870b77e548611929be56952f68825d3d52e))
* **code:** show connection state in the status bar ([#3710](https://github.com/shantanusharma/deepagents/issues/3710)) ([3e3e8fe](https://github.com/shantanusharma/deepagents/commit/3e3e8feb0e6e1b77be75a7756fbf32e5c9497c28))
* **code:** show conversation turns alongside message counts ([#5571](https://github.com/shantanusharma/deepagents/issues/5571)) ([3dd4fe5](https://github.com/shantanusharma/deepagents/commit/3dd4fe5cdc548f5408d5b74b82084d9d4c01a664))
* **code:** show Escape hint in model picker ([#5775](https://github.com/shantanusharma/deepagents/issues/5775)) ([a103a88](https://github.com/shantanusharma/deepagents/commit/a103a88f8a93ef318d64fa9e3bcdd2007cf7a45c))
* **code:** show experimental mode in splash and debug console ([#4863](https://github.com/shantanusharma/deepagents/issues/4863)) ([44d9dec](https://github.com/shantanusharma/deepagents/commit/44d9dec39b2570d16c285a8b0a99cbe1afab4f1b))
* **code:** show human invocations in usage teardown ([#6500](https://github.com/shantanusharma/deepagents/issues/6500)) ([0779f31](https://github.com/shantanusharma/deepagents/commit/0779f314841ec4216a189b70c615d06194731ecd))
* **code:** show last update check time in `dcode doctor` ([#4307](https://github.com/shantanusharma/deepagents/issues/4307)) ([b669f37](https://github.com/shantanusharma/deepagents/commit/b669f37fb08998cfbf983da76f57822215614e7b))
* **code:** show MCP tool counts in `/tools` headers ([#7327](https://github.com/shantanusharma/deepagents/issues/7327)) ([93143ba](https://github.com/shantanusharma/deepagents/commit/93143ba1b501bd94307f6e7009f8abca11abcd9c))
* **code:** show model name instead of spec in switcher ([#4460](https://github.com/shantanusharma/deepagents/issues/4460)) ([0059620](https://github.com/shantanusharma/deepagents/commit/005962088ad31b16745c399e4ab2e725e97f7858))
* **code:** show provider in usage stats table ([#4049](https://github.com/shantanusharma/deepagents/issues/4049)) ([309b054](https://github.com/shantanusharma/deepagents/commit/309b054fdd040adb5086408a3bcb2550ba73439e))
* **code:** show provider-visible reasoning by default in the TUI ([#6850](https://github.com/shantanusharma/deepagents/issues/6850)) ([23994c0](https://github.com/shantanusharma/deepagents/commit/23994c038d02f60ef83ec8c15142e8607ddb3b79))
* **code:** show session length in Debug Console ([#6224](https://github.com/shantanusharma/deepagents/issues/6224)) ([05edbb1](https://github.com/shantanusharma/deepagents/commit/05edbb14d0855303ce74d42a4bf368804856c43a))
* **code:** show the prompt-cache expiration time ([#7005](https://github.com/shantanusharma/deepagents/issues/7005)) ([3407dc3](https://github.com/shantanusharma/deepagents/commit/3407dc33b9918c98c126097bf485dbf6d2f035bd))
* **code:** show thread message count in the Debug Console ([#5117](https://github.com/shantanusharma/deepagents/issues/5117)) ([04cf25d](https://github.com/shantanusharma/deepagents/commit/04cf25d27068070979552a5c914fc7dad715ce70))
* **code:** shutdown toast for deferred exits ([#4830](https://github.com/shantanusharma/deepagents/issues/4830)) ([a8a05f5](https://github.com/shantanusharma/deepagents/commit/a8a05f58f2ffb755bf373cd8f9a4cced2778370c))
* **code:** simplify welcome banner to compact box ([#4482](https://github.com/shantanusharma/deepagents/issues/4482)) ([b7f46e9](https://github.com/shantanusharma/deepagents/commit/b7f46e931807f86476c9c2d661dcd4e9623c10a2))
* **code:** standardize external editor shortcut ([#5911](https://github.com/shantanusharma/deepagents/issues/5911)) ([f75300f](https://github.com/shantanusharma/deepagents/commit/f75300f12dc363132dc187e674cf3cd52eb93595))
* **code:** suggest compacting large resumed threads ([#5318](https://github.com/shantanusharma/deepagents/issues/5318)) ([cb2329d](https://github.com/shantanusharma/deepagents/commit/cb2329d1ec480455a7ba4e2b277cbd727c9215c7))
* **code:** summarize plugin changes on reload ([#4767](https://github.com/shantanusharma/deepagents/issues/4767)) ([9cad2f0](https://github.com/shantanusharma/deepagents/commit/9cad2f00dd0473828f80f782c889b939483727f6))
* **code:** support `DEEPAGENTS_CODE_LANGSMITH_PROJECT_URL` and cache rejected project lookups ([#7332](https://github.com/shantanusharma/deepagents/issues/7332)) ([028439e](https://github.com/shantanusharma/deepagents/commit/028439ef1bfdca7207713d018fe9b476ba1f996e))
* **code:** support `DEEPAGENTS_HOME` ([#5773](https://github.com/shantanusharma/deepagents/issues/5773)) ([feb5736](https://github.com/shantanusharma/deepagents/commit/feb5736dfb7309008674020442c943ac3e2dc19d))
* **code:** support ACP approval modes ([#5394](https://github.com/shantanusharma/deepagents/issues/5394)) ([7772a14](https://github.com/shantanusharma/deepagents/commit/7772a1495440739130b8b613aa69433fbc0afbad))
* **code:** support custom Slack OAuth app identity ([#7061](https://github.com/shantanusharma/deepagents/issues/7061)) ([612ccbd](https://github.com/shantanusharma/deepagents/commit/612ccbd463b9eaa8f326e40ed0335bf4ee42b784))
* **code:** support Fireworks `/routers` model ids ([#4591](https://github.com/shantanusharma/deepagents/issues/4591)) ([1c08d27](https://github.com/shantanusharma/deepagents/commit/1c08d2705f73f6870610849e00910b94458accf1))
* **code:** support skill-scoped MCP tools ([#7010](https://github.com/shantanusharma/deepagents/issues/7010)) ([227580e](https://github.com/shantanusharma/deepagents/commit/227580e26c6cf0ebe2581dc5b488ad3eb3695b43))
* **code:** surface `/auth` in `/trace not-configured` hint ([#4206](https://github.com/shantanusharma/deepagents/issues/4206)) ([392e410](https://github.com/shantanusharma/deepagents/commit/392e410e48639a56fda5e35b6f7f85a5215cce9c))
* **code:** surface Daytona sandbox snapshots ([#6854](https://github.com/shantanusharma/deepagents/issues/6854)) ([40fbf9d](https://github.com/shantanusharma/deepagents/commit/40fbf9d85b0c3554120bb10ab59db424d34c78d4))
* **code:** surface deferred MCP reconnect state in `/mcp` ([#3612](https://github.com/shantanusharma/deepagents/issues/3612)) ([d8205c2](https://github.com/shantanusharma/deepagents/commit/d8205c2a39d00e8b6f7f70afe7cc9bb92fee42d8))
* **code:** surface editable mode and core deps in `/version` ([#3898](https://github.com/shantanusharma/deepagents/issues/3898)) ([d4f5a12](https://github.com/shantanusharma/deepagents/commit/d4f5a12cc6d73dc19d24d5748242705d79fa65bf))
* **code:** surface gateway key mismatch on `PermissionDeniedError` ([#3813](https://github.com/shantanusharma/deepagents/issues/3813)) ([5bd1ef8](https://github.com/shantanusharma/deepagents/commit/5bd1ef8cb29db781ccbb37755db44ce0ab1d7bd2))
* **code:** surface Hooks v2 runtime feedback ([#5045](https://github.com/shantanusharma/deepagents/issues/5045)) ([66d526f](https://github.com/shantanusharma/deepagents/commit/66d526f0e43c4c1c5d3ab9cc3d423fefe1606e6f))
* **code:** surface LangSmith tracing projects in `LocalContextMiddleware` ([#3836](https://github.com/shantanusharma/deepagents/issues/3836)) ([676abec](https://github.com/shantanusharma/deepagents/commit/676abecf892ff537fcb1425ba5929cace3c5d503))
* **code:** surface locally tracked GitHub stacks ([#6290](https://github.com/shantanusharma/deepagents/issues/6290)) ([c08cae6](https://github.com/shantanusharma/deepagents/commit/c08cae693e0036fcd45d979a7dfa3a7e306a0515))
* **code:** surface MCP servers awaiting reconnect on splash banner ([#3615](https://github.com/shantanusharma/deepagents/issues/3615)) ([24c5258](https://github.com/shantanusharma/deepagents/commit/24c5258ae6664bc3d3875d8065038716f7c86161))
* **code:** surface tracing in `doctor` and `config show` ([#4163](https://github.com/shantanusharma/deepagents/issues/4163)) ([2bb3e44](https://github.com/shantanusharma/deepagents/commit/2bb3e44243553a5f2954a0f3ec42364563842a87))
* **code:** surface uninstalled known providers in `/auth` menu ([#4059](https://github.com/shantanusharma/deepagents/issues/4059)) ([73db271](https://github.com/shantanusharma/deepagents/commit/73db2719bce5ad3c933ffee643df4a62cfd60e17))
* **code:** tag offload traces with what triggered them ([#7630](https://github.com/shantanusharma/deepagents/issues/7630)) ([91b17f4](https://github.com/shantanusharma/deepagents/commit/91b17f4476a90a8d29d7a758cadf2e82f462bbf0))
* **code:** teach the agent to discover marketplace plugins ([#6719](https://github.com/shantanusharma/deepagents/issues/6719)) ([52cc3e2](https://github.com/shantanusharma/deepagents/commit/52cc3e2f52b5dac038da9f56ddfeb6898c3e8c85))
* **code:** toast on saved `/auth` API key ([#4558](https://github.com/shantanusharma/deepagents/issues/4558)) ([ee3c264](https://github.com/shantanusharma/deepagents/commit/ee3c26415be84e369b829fefb21461c8ec210a5e))
* **code:** toast to re-paste when a chat paste collapses ([#4742](https://github.com/shantanusharma/deepagents/issues/4742)) ([e50e238](https://github.com/shantanusharma/deepagents/commit/e50e2383261ba39923b5d6c48b7fe3b058475cd3))
* **code:** toast when opening a clicked URL ([#4368](https://github.com/shantanusharma/deepagents/issues/4368)) ([434f29e](https://github.com/shantanusharma/deepagents/commit/434f29e5cb3d94988e2a4d80b78452bee4b10812))
* **code:** toast when submitting empty required `ask_user` answer ([#5095](https://github.com/shantanusharma/deepagents/issues/5095)) ([a80355a](https://github.com/shantanusharma/deepagents/commit/a80355abd9d4579eee483f654faa5f2b373590a0))
* **code:** toggle diff line numbers ([#5427](https://github.com/shantanusharma/deepagents/issues/5427)) ([4cd21b6](https://github.com/shantanusharma/deepagents/commit/4cd21b61592ef0239f59cf4e3f27a2a70d226737))
* **code:** trace auto-approve (YOLO) mode in trace metadata ([#4764](https://github.com/shantanusharma/deepagents/issues/4764)) ([d88601e](https://github.com/shantanusharma/deepagents/commit/d88601ed582b89d4a5b517e842029d06370c0891))
* **code:** trace effective approval mode ([#5972](https://github.com/shantanusharma/deepagents/issues/5972)) ([c56958d](https://github.com/shantanusharma/deepagents/commit/c56958d633cd9513ba699f940d4fadfee6cd3963))
* **code:** trace experimental mode in metadata ([#4705](https://github.com/shantanusharma/deepagents/issues/4705)) ([22d5045](https://github.com/shantanusharma/deepagents/commit/22d50456324e9b8c0121a3a06787e19c1b88e1aa))
* **code:** tri-state `DEEPAGENTS_CODE_ONBOARDING` env var ([#5301](https://github.com/shantanusharma/deepagents/issues/5301)) ([43293e9](https://github.com/shantanusharma/deepagents/commit/43293e95cb072c8b92a734eca8c0292e45d279e8))
* **code:** trust user-declared endpoints for cold-cache policies ([#5462](https://github.com/shantanusharma/deepagents/issues/5462)) ([107980e](https://github.com/shantanusharma/deepagents/commit/107980e387b3fa060c2b33e9bd31b57c387eddb6))
* **code:** unify `config show`/`list` around effective values ([#4174](https://github.com/shantanusharma/deepagents/issues/4174)) ([ccd9d21](https://github.com/shantanusharma/deepagents/commit/ccd9d216e77855a28b88850beb525f47ce8b686a))
* **code:** unify notification center and settings ([#5698](https://github.com/shantanusharma/deepagents/issues/5698)) ([9767f42](https://github.com/shantanusharma/deepagents/commit/9767f420c622a31a7511c4601739534ddc6062a7))
* **code:** warn above configurable session cost threshold ([#5405](https://github.com/shantanusharma/deepagents/issues/5405)) ([8cf8517](https://github.com/shantanusharma/deepagents/commit/8cf8517e7fb728fedd07db15a0577b305cd69f70))
* **code:** warn before expensive cold-cache turns ([#5439](https://github.com/shantanusharma/deepagents/issues/5439)) ([8d2298f](https://github.com/shantanusharma/deepagents/commit/8d2298ff54797e224233349e4baf68e19b110040))
* **code:** warn on `--interpreter-tools` without `--interpreter` ([#3976](https://github.com/shantanusharma/deepagents/issues/3976)) ([e68e720](https://github.com/shantanusharma/deepagents/commit/e68e720e2c3caa4e4e7c5e937faf718db7ad2e98))
* **code:** word-level double-click selection ([#3740](https://github.com/shantanusharma/deepagents/issues/3740)) ([4bb4286](https://github.com/shantanusharma/deepagents/commit/4bb4286a26c9c9bc69a36f2714d9eb0e3e5e4d40))
* **deps:** require Python 3.14 ([#7052](https://github.com/shantanusharma/deepagents/issues/7052)) ([96eca0b](https://github.com/shantanusharma/deepagents/commit/96eca0b2e13db0b9e3dd9822d062ad316ba0b5fa))
* **runloop:** add blueprint bootstrapping for Runloop sandboxes ([#3556](https://github.com/shantanusharma/deepagents/issues/3556)) ([13dafd8](https://github.com/shantanusharma/deepagents/commit/13dafd8823c4b530c8e096012733ad74cd501b59))
* **sdk,code,quickjs:** make the `ToDoListMiddleware` list opt-in ([#4929](https://github.com/shantanusharma/deepagents/issues/4929)) ([9340518](https://github.com/shantanusharma/deepagents/commit/9340518a26c4287f9ad0c543edc9b69106c15154))
* **sdk,code:** update `read_file` output formatting ([#5648](https://github.com/shantanusharma/deepagents/issues/5648)) ([276beca](https://github.com/shantanusharma/deepagents/commit/276becae1bbaa38d6253aee90e99212e7bdf0606))
* **sdk:** optional video frame extraction on `read_file` ([#4094](https://github.com/shantanusharma/deepagents/issues/4094)) ([b927147](https://github.com/shantanusharma/deepagents/commit/b927147d026749c6c790bb06c9853515dabf579c))
* **talon:** add local runtime host ([#3759](https://github.com/shantanusharma/deepagents/issues/3759)) ([7358a66](https://github.com/shantanusharma/deepagents/commit/7358a6663b1b2cda42392616eb04d39d01f42b2b))
* **vercel:** add Vercel Sandbox provider ([#3588](https://github.com/shantanusharma/deepagents/issues/3588)) ([e5e4748](https://github.com/shantanusharma/deepagents/commit/e5e4748cb6c66ddaa9444ab464990c1a5d10854d))


### Bug Fixes

* **cli:** clarify post-update restart semantics ([#4046](https://github.com/shantanusharma/deepagents/issues/4046)) ([6318b81](https://github.com/shantanusharma/deepagents/commit/6318b817399f7dd2f2e6dc07987dca46f1da9886))
* **code,evals:** allow instrumental Auto actions ([#5832](https://github.com/shantanusharma/deepagents/issues/5832)) ([56f51d8](https://github.com/shantanusharma/deepagents/commit/56f51d83a7d6621f2c3954ce69740c46e3cc1426))
* **code,evals:** unify goal activation signaling ([#4980](https://github.com/shantanusharma/deepagents/issues/4980)) ([0c4016e](https://github.com/shantanusharma/deepagents/commit/0c4016e3c8a7293fdf1a24e12340759068a2bb9a))
* **code:** `--reinstall` on `/install` so upgrades rebuild a clean env ([#4196](https://github.com/shantanusharma/deepagents/issues/4196)) ([5e152ac](https://github.com/shantanusharma/deepagents/commit/5e152ac0256d64376f96b293f8844bc8acc993ec))
* **code:** `dcode doctor` shows `not configured` for unset tracing ([#4318](https://github.com/shantanusharma/deepagents/issues/4318)) ([e323d0c](https://github.com/shantanusharma/deepagents/commit/e323d0c7d91f3b11e03a016c14cf52008dc66b55))
* **code:** abort project MCP approval on Esc ([#4888](https://github.com/shantanusharma/deepagents/issues/4888)) ([46bb1a8](https://github.com/shantanusharma/deepagents/commit/46bb1a86c8041d5c161d7cd07de66d068fb100c0))
* **code:** abort YOLO launch on `Ctrl+C`/`Ctrl+D` ([#4953](https://github.com/shantanusharma/deepagents/issues/4953)) ([e6ab9c0](https://github.com/shantanusharma/deepagents/commit/e6ab9c05e8fcb9a332396a9425e2b302607be823))
* **code:** accept bare relative paths in marketplace plugin sources ([#5959](https://github.com/shantanusharma/deepagents/issues/5959)) ([28468d6](https://github.com/shantanusharma/deepagents/commit/28468d62f208e3dea5a574898d19e7d9618db928))
* **code:** add `/resume` alias and rank alias matches ([#6988](https://github.com/shantanusharma/deepagents/issues/6988)) ([964ec92](https://github.com/shantanusharma/deepagents/commit/964ec92aeeb81e26e807805e611aeab1ee83c7be))
* **code:** add debug-log guidance for truncated startup errors ([#3849](https://github.com/shantanusharma/deepagents/issues/3849)) ([cd1ef30](https://github.com/shantanusharma/deepagents/commit/cd1ef303cf5d0e9d746c787eb09a4a89437e965a))
* **code:** add marketplaces asynchronously ([#4766](https://github.com/shantanusharma/deepagents/issues/4766)) ([0d1bb6a](https://github.com/shantanusharma/deepagents/commit/0d1bb6a1224b91cae9dcdb7014a6410a82b79001))
* **code:** add terminal progress preference ([#3728](https://github.com/shantanusharma/deepagents/issues/3728)) ([d9e4976](https://github.com/shantanusharma/deepagents/commit/d9e4976826ae2281e90e06facb5a70a785703029))
* **code:** agent retries `gh search` with invalid `mergedAt` field ([#3802](https://github.com/shantanusharma/deepagents/issues/3802)) ([0b683a9](https://github.com/shantanusharma/deepagents/commit/0b683a9435b95bce79d10451868eae54c6a3e88c))
* **code:** align context diff rows with changed rows ([#4714](https://github.com/shantanusharma/deepagents/issues/4714)) ([f9915db](https://github.com/shantanusharma/deepagents/commit/f9915db4206ef2d794ad07fdccbdd4ee58963142))
* **code:** align file and console debug log formatting ([#6426](https://github.com/shantanusharma/deepagents/issues/6426)) ([6c219d3](https://github.com/shantanusharma/deepagents/commit/6c219d3a39a869b55c5ec434acf76f84217eb002))
* **code:** align prompt clipboard word deletion ([#6345](https://github.com/shantanusharma/deepagents/issues/6345)) ([777d633](https://github.com/shantanusharma/deepagents/commit/777d6336de3c7f1b6759a3f092fbfeddc4c54499))
* **code:** align wrapped debug snapshot values ([#5727](https://github.com/shantanusharma/deepagents/issues/5727)) ([1f74959](https://github.com/shantanusharma/deepagents/commit/1f7495949232fe2e3e3328b6ff9054c202002f95))
* **code:** allow `/remember` with args when no conversation history ([#4418](https://github.com/shantanusharma/deepagents/issues/4418)) ([5df9c83](https://github.com/shantanusharma/deepagents/commit/5df9c83b58f2529561848ae9f1364961e1c80641))
* **code:** allow cleanup of agent-created scratch files ([#4860](https://github.com/shantanusharma/deepagents/issues/4860)) ([fe08582](https://github.com/shantanusharma/deepagents/commit/fe08582a386b86f78f7a8047db067ea45e7e2650))
* **code:** allow recovery commands when startup fails ([#3706](https://github.com/shantanusharma/deepagents/issues/3706)) ([727d022](https://github.com/shantanusharma/deepagents/commit/727d022cd1526836c3d1de997c1f036e870881f7))
* **code:** allow safe OS-temp scratch artifacts ([#4869](https://github.com/shantanusharma/deepagents/issues/4869)) ([4330534](https://github.com/shantanusharma/deepagents/commit/4330534d18cbf79260842dde0e0c450312ef55ca))
* **code:** allow suppressing LangSmith key override warning ([#4436](https://github.com/shantanusharma/deepagents/issues/4436)) ([ddcae5e](https://github.com/shantanusharma/deepagents/commit/ddcae5e0bd9aebc946be1d9fb3f5e35eeb690fa6))
* **code:** allowlist Git options in Auto mode's read-only fast path ([#7276](https://github.com/shantanusharma/deepagents/issues/7276)) ([2abf323](https://github.com/shantanusharma/deepagents/commit/2abf323e67b3c600d71b34bdfcc41008b753f75f))
* **code:** always restart after a successful startup auto-update ([#5317](https://github.com/shantanusharma/deepagents/issues/5317)) ([8cdee15](https://github.com/shantanusharma/deepagents/commit/8cdee15bbc54381229a686f8263656be0202b9b5))
* **code:** anchor editable refresh to its checkout ([#6455](https://github.com/shantanusharma/deepagents/issues/6455)) ([a6d844d](https://github.com/shantanusharma/deepagents/commit/a6d844d47126bb905f30e76569110cd68294a0b3))
* **code:** anchor toasts above the chat input ([#5101](https://github.com/shantanusharma/deepagents/issues/5101)) ([f1727c7](https://github.com/shantanusharma/deepagents/commit/f1727c785c44809e7b1b7ed8c5d0b31c560ae3ad))
* **code:** append refreshed local context after compaction ([#5828](https://github.com/shantanusharma/deepagents/issues/5828)) ([3a78de7](https://github.com/shantanusharma/deepagents/commit/3a78de7c3feeea4bc180e91003f6a43ee1a29064))
* **code:** attribute dotenv config sources ([#6222](https://github.com/shantanusharma/deepagents/issues/6222)) ([6f1ac85](https://github.com/shantanusharma/deepagents/commit/6f1ac85c46604ef093a9d295fbcc52a8108aa8ed))
* **code:** authorize Auto actions from active goal/rubric directives ([#5017](https://github.com/shantanusharma/deepagents/issues/5017)) ([728dbe7](https://github.com/shantanusharma/deepagents/commit/728dbe7df62ad9960f21cabd6e6c37e8d9a66da7))
* **code:** auto-migrate to Python 3.14 when no other session is running ([#7160](https://github.com/shantanusharma/deepagents/issues/7160)) ([acfb272](https://github.com/shantanusharma/deepagents/commit/acfb272c132e17d8fa813e52c218c5e9c0c0387a))
* **code:** avoid blocking MCP imports during graph readiness ([#4302](https://github.com/shantanusharma/deepagents/issues/4302)) ([7533ca8](https://github.com/shantanusharma/deepagents/commit/7533ca89f3afc9863ba5e1ecee2d4c5974dea320))
* **code:** avoid blocking MCP OAuth token refresh ([#4770](https://github.com/shantanusharma/deepagents/issues/4770)) ([3b2ffce](https://github.com/shantanusharma/deepagents/commit/3b2ffce923e06370efe177e9ca91f70e86f19602))
* **code:** avoid detached spacer mount anchors ([#5516](https://github.com/shantanusharma/deepagents/issues/5516)) ([a38dc42](https://github.com/shantanusharma/deepagents/commit/a38dc4297b225e424207df5efd7dec0cf38ce832))
* **code:** avoid duplicate "criteria ready" message on `/goal` revisions ([#4559](https://github.com/shantanusharma/deepagents/issues/4559)) ([1110497](https://github.com/shantanusharma/deepagents/commit/1110497e17fac6deceb9d1d6e530f9197bfc0d4a))
* **code:** avoid duplicate Auto denial notices ([#5501](https://github.com/shantanusharma/deepagents/issues/5501)) ([41395c5](https://github.com/shantanusharma/deepagents/commit/41395c586d9743550c27073260539724a4bfedd3))
* **code:** avoid misleading `/reload` change summary ([#7063](https://github.com/shantanusharma/deepagents/issues/7063)) ([b6504f6](https://github.com/shantanusharma/deepagents/commit/b6504f6654ee6f25e1cd923087291de9e51572cc))
* **code:** avoid plugin reload prompt flash ([#5500](https://github.com/shantanusharma/deepagents/issues/5500)) ([e03f030](https://github.com/shantanusharma/deepagents/commit/e03f03026984bf4bdeb8bd661707f29a4d682738))
* **code:** avoid redundant Auto approval prompts ([#4993](https://github.com/shantanusharma/deepagents/issues/4993)) ([9975874](https://github.com/shantanusharma/deepagents/commit/9975874d897ada8979c084145eb730e15c9cf979))
* **code:** avoid repeated startup auto-update stalls ([#4648](https://github.com/shantanusharma/deepagents/issues/4648)) ([12a9c9d](https://github.com/shantanusharma/deepagents/commit/12a9c9d6813a83e5eeff9feed0c4068d1fcc69c4))
* **code:** avoid tracking inline restart callers ([#4894](https://github.com/shantanusharma/deepagents/issues/4894)) ([0b071ef](https://github.com/shantanusharma/deepagents/commit/0b071ef71a1f0d63cb09de7ac528e030cd75af2e))
* **code:** avoid transcript hydration lag ([#5479](https://github.com/shantanusharma/deepagents/issues/5479)) ([3c8cae6](https://github.com/shantanusharma/deepagents/commit/3c8cae6fa44d4e12062fdb10421b48587925eade))
* **code:** await background worker cleanup on shutdown ([#7810](https://github.com/shantanusharma/deepagents/issues/7810)) ([c81b7a8](https://github.com/shantanusharma/deepagents/commit/c81b7a8bc2d2ee8e16066797e4e9be13409d1d0b))
* **code:** bake release commit into `dcode doctor` ([#4225](https://github.com/shantanusharma/deepagents/issues/4225)) ([6dc0246](https://github.com/shantanusharma/deepagents/commit/6dc0246f5c6e9170e05191e1c82fad6975ac945c))
* **code:** bind Auto-mode "yes" to the paired `ask_user` question ([#5038](https://github.com/shantanusharma/deepagents/issues/5038)) ([f4f138d](https://github.com/shantanusharma/deepagents/commit/f4f138db65484d4938ef3759cb26cec1e789357d))
* **code:** bind ephemeral port instead of squatting `langgraph dev`'s 2024 ([#4264](https://github.com/shantanusharma/deepagents/issues/4264)) ([11e5359](https://github.com/shantanusharma/deepagents/commit/11e5359851f0291783661b4311ad5e4436a36fb7))
* **code:** bind request-time working directories ([#5968](https://github.com/shantanusharma/deepagents/issues/5968)) ([98db566](https://github.com/shantanusharma/deepagents/commit/98db566f2cc654a535ed68de4dbdd2e10a2edd30))
* **code:** block auto mode when its classifier cannot resolve ([#7346](https://github.com/shantanusharma/deepagents/issues/7346)) ([6b317a4](https://github.com/shantanusharma/deepagents/commit/6b317a4a8e0e64e6ab6524b310bff70fe71e9eab))
* **code:** block dotenv git config injection keys ([#5723](https://github.com/shantanusharma/deepagents/issues/5723)) ([328f916](https://github.com/shantanusharma/deepagents/commit/328f9160e0f95a459be8ad57f76e7178b24a3ef8))
* **code:** block dotenv shell startup hooks ([#4288](https://github.com/shantanusharma/deepagents/issues/4288)) ([686d6f3](https://github.com/shantanusharma/deepagents/commit/686d6f3a1da8b6393efb4c0cf87b3eb35e0cca50))
* **code:** bound Hooks v2 session-end teardown ([#5248](https://github.com/shantanusharma/deepagents/issues/5248)) ([28a7d5b](https://github.com/shantanusharma/deepagents/commit/28a7d5bdd3f78044b4f3612f71e13ce38ef47bf4))
* **code:** bound MCP tool calls with configurable timeouts ([#6625](https://github.com/shantanusharma/deepagents/issues/6625)) ([d1c5a8e](https://github.com/shantanusharma/deepagents/commit/d1c5a8ef6af2a2bf3951808a53a257e97d87946f))
* **code:** bound transcript tail reconciliation ([#6057](https://github.com/shantanusharma/deepagents/issues/6057)) ([8da3264](https://github.com/shantanusharma/deepagents/commit/8da32644dc7dcad1125a840bc17ec3d5ea66b8c3))
* **code:** bridge upgrades to Python 3.14 ([#7081](https://github.com/shantanusharma/deepagents/issues/7081)) ([914de8b](https://github.com/shantanusharma/deepagents/commit/914de8be68ff48b22418ceb2f9c6baf801f41afa))
* **code:** bust CDN cache on forced `dcode update` checks ([#4862](https://github.com/shantanusharma/deepagents/issues/4862)) ([3733526](https://github.com/shantanusharma/deepagents/commit/3733526f5faa187627c650435fa5478754c55fb4))
* **code:** bypass proxies for local server traffic ([#7613](https://github.com/shantanusharma/deepagents/issues/7613)) ([46b040a](https://github.com/shantanusharma/deepagents/commit/46b040ade4183d6e19221cefd9908b8e1e4a2295))
* **code:** cancel server-side runs before re-trying interrupted-state writes ([#3611](https://github.com/shantanusharma/deepagents/issues/3611)) ([7d46357](https://github.com/shantanusharma/deepagents/commit/7d46357c5446bbc6225f972fd66dc52af8dd0547))
* **code:** cap MCP tool names for provider compatibility ([#5953](https://github.com/shantanusharma/deepagents/issues/5953)) ([0eb8e57](https://github.com/shantanusharma/deepagents/commit/0eb8e578708a18c3a789f76c4bb13d92bd768192))
* **code:** capture input typed before TUI startup ([#4684](https://github.com/shantanusharma/deepagents/issues/4684)) ([ef9a4a8](https://github.com/shantanusharma/deepagents/commit/ef9a4a8770f4daec70e640d6d2f23dd798d4ede2))
* **code:** capture stdio MCP server stderr into the logger ([#5610](https://github.com/shantanusharma/deepagents/issues/5610)) ([a61bc6f](https://github.com/shantanusharma/deepagents/commit/a61bc6feeb6aefd780ad8435acc9ce2057fe9151))
* **code:** centralize debug logging setup to package root ([#3650](https://github.com/shantanusharma/deepagents/issues/3650)) ([5145ed1](https://github.com/shantanusharma/deepagents/commit/5145ed1f8296f41d78c905c2ce899d2742f7dc9b))
* **code:** char-truncate execute tool preview output ([#3627](https://github.com/shantanusharma/deepagents/issues/3627)) ([bb276e2](https://github.com/shantanusharma/deepagents/commit/bb276e2c41177b0dfe6ffd44fd37a293fbfdcb27))
* **code:** chat input history navigation and newline scrolling ([#3560](https://github.com/shantanusharma/deepagents/issues/3560)) ([3b51cbd](https://github.com/shantanusharma/deepagents/commit/3b51cbdc8c50d9990477e18a47de6a58e9165bab))
* **code:** clarify `/restart` message during server startup ([#3823](https://github.com/shantanusharma/deepagents/issues/3823)) ([49ded9e](https://github.com/shantanusharma/deepagents/commit/49ded9ef448dcd263bee07ac15f4904dd342bfa2))
* **code:** clarify auth environment setup ([#5767](https://github.com/shantanusharma/deepagents/issues/5767)) ([a095af9](https://github.com/shantanusharma/deepagents/commit/a095af93cf3e8ef0c06d9958cfca52dfe9230fcb))
* **code:** clarify Auto mode file-edit example ([#5685](https://github.com/shantanusharma/deepagents/issues/5685)) ([50dedf0](https://github.com/shantanusharma/deepagents/commit/50dedf086bb923ec71f585d907ac3920d0442754))
* **code:** clarify clear command descriptions ([#5841](https://github.com/shantanusharma/deepagents/issues/5841)) ([a6b069d](https://github.com/shantanusharma/deepagents/commit/a6b069db380c5483c414f48d9b57899c749c8528))
* **code:** clarify clear hint starts a new thread ([#6726](https://github.com/shantanusharma/deepagents/issues/6726)) ([8468bad](https://github.com/shantanusharma/deepagents/commit/8468bad7054cb778aa8b199ee5a644a5acca0332))
* **code:** clarify compaction prompt ([#6429](https://github.com/shantanusharma/deepagents/issues/6429)) ([15cf630](https://github.com/shantanusharma/deepagents/commit/15cf6301e49e00963df876b6697fcc7c42d027d8))
* **code:** clarify credential setup recovery ([#7347](https://github.com/shantanusharma/deepagents/issues/7347)) ([1e178f1](https://github.com/shantanusharma/deepagents/commit/1e178f1b053d0d4f4953c0d1a8aba9ff10a2e5fb))
* **code:** clarify dependency warning prompt ([#5489](https://github.com/shantanusharma/deepagents/issues/5489)) ([31e4941](https://github.com/shantanusharma/deepagents/commit/31e49418c7538542ff30b2701cf8ac9d1182bbeb))
* **code:** clarify line number toggle message ([#5694](https://github.com/shantanusharma/deepagents/issues/5694)) ([bb75e96](https://github.com/shantanusharma/deepagents/commit/bb75e96192f30ffccb193f2ccdc349a0227ca1af))
* **code:** clarify managed `rg` install failures ([#4578](https://github.com/shantanusharma/deepagents/issues/4578)) ([434c84a](https://github.com/shantanusharma/deepagents/commit/434c84ae144b0319afe37d6f2dbadfd7f5fc9f70))
* **code:** clarify MCP configuration refresh in `/reload` ([#7497](https://github.com/shantanusharma/deepagents/issues/7497)) ([d29e85f](https://github.com/shantanusharma/deepagents/commit/d29e85f5d2f69f39643c78279e931d610b42d3b4))
* **code:** clarify plugin component discovery and reload status ([#4774](https://github.com/shantanusharma/deepagents/issues/4774)) ([7d707b8](https://github.com/shantanusharma/deepagents/commit/7d707b840f132ad65e5ac8443ec7fece393180f8))
* **code:** clarify project hooks trust prompt and stop prompting for user hooks ([#5426](https://github.com/shantanusharma/deepagents/issues/5426)) ([61d3279](https://github.com/shantanusharma/deepagents/commit/61d32797ef85d1380e356cd2f9de1eb7926417ec))
* **code:** clarify Python update instructions ([#7343](https://github.com/shantanusharma/deepagents/issues/7343)) ([cec8d8e](https://github.com/shantanusharma/deepagents/commit/cec8d8e2bcbb7a04b9fecd4f63d2c8c50c5205a0))
* **code:** clarify thread message count header ([#6428](https://github.com/shantanusharma/deepagents/issues/6428)) ([e775680](https://github.com/shantanusharma/deepagents/commit/e775680e1cb5a52ba816e6c4663a647a7025d566))
* **code:** clarify unknown effort default ([#6337](https://github.com/shantanusharma/deepagents/issues/6337)) ([5ee1073](https://github.com/shantanusharma/deepagents/commit/5ee1073e9ab2fe9a286becb27ec7e694a4b3de4f))
* **code:** clean offloaded history when deleting a thread ([#4751](https://github.com/shantanusharma/deepagents/issues/4751)) ([47788ed](https://github.com/shantanusharma/deepagents/commit/47788ededafd44f74b4368ec6793bf4685ad3a3a))
* **code:** clean up new sandboxes when setup fails ([#6475](https://github.com/shantanusharma/deepagents/issues/6475)) ([1ec8996](https://github.com/shantanusharma/deepagents/commit/1ec8996c91fa6f68b3ec8145f279b8c1dea5dc20))
* **code:** clear dynamic subagents on next turn ([#5437](https://github.com/shantanusharma/deepagents/issues/5437)) ([9a37479](https://github.com/shantanusharma/deepagents/commit/9a37479f866160f92474847720b57db9598ddb3e))
* **code:** clear stale live approval mode keys ([#4242](https://github.com/shantanusharma/deepagents/issues/4242)) ([f11a769](https://github.com/shantanusharma/deepagents/commit/f11a76962c9d536a38e27ac05b32feca364b2424))
* **code:** clear transient update launch status ([#4355](https://github.com/shantanusharma/deepagents/issues/4355)) ([b870b18](https://github.com/shantanusharma/deepagents/commit/b870b18750f65442009028a85a2ac18f1b06640c))
* **code:** clearer MCP config JSON parse errors ([#4327](https://github.com/shantanusharma/deepagents/issues/4327)) ([9cee602](https://github.com/shantanusharma/deepagents/commit/9cee60274d38d4ad8a2d7a7e9d3ae59aebce5261))
* **code:** close subprocess transport on install teardown ([#4735](https://github.com/shantanusharma/deepagents/issues/4735)) ([625e601](https://github.com/shantanusharma/deepagents/commit/625e601da8cd77e13b98b2b81626f320478108dc))
* **code:** coalesce streamed markdown writes to keep input responsive ([#3819](https://github.com/shantanusharma/deepagents/issues/3819)) ([b45eeeb](https://github.com/shantanusharma/deepagents/commit/b45eeebaf7e6ae6e07b8f9ca521525c66fe14f63))
* **code:** collapse ChatGPT sign-in browser URL by default ([#7348](https://github.com/shantanusharma/deepagents/issues/7348)) ([eaeb71b](https://github.com/shantanusharma/deepagents/commit/eaeb71bb59952061a6c5ae59c98f5b2888583152))
* **code:** collapse idle subagents and reopen new work ([#6782](https://github.com/shantanusharma/deepagents/issues/6782)) ([70288ad](https://github.com/shantanusharma/deepagents/commit/70288ad564d31631ed409566c71f0cb58fc6c437))
* **code:** collapse resized chat input on double-click ([#5578](https://github.com/shantanusharma/deepagents/issues/5578)) ([fdde617](https://github.com/shantanusharma/deepagents/commit/fdde617eb590191162a1ebbd9a5fb6c2763ee462))
* **code:** compare effective interpreter permissions ([#6993](https://github.com/shantanusharma/deepagents/issues/6993)) ([23361fb](https://github.com/shantanusharma/deepagents/commit/23361fb4bf796016e4ad7e07d0b223c02765491f))
* **code:** complete `--flag=value` in bash ([#7656](https://github.com/shantanusharma/deepagents/issues/7656)) ([c41e786](https://github.com/shantanusharma/deepagents/commit/c41e7865048fe5de9ac2cdddd3fc6884151981cb))
* **code:** complete ASCII UI fallbacks ([#5930](https://github.com/shantanusharma/deepagents/issues/5930)) ([e9a1623](https://github.com/shantanusharma/deepagents/commit/e9a16234f14ea570e04a936cf8070156d01eae99))
* **code:** complete goals after satisfied grading ([#4781](https://github.com/shantanusharma/deepagents/issues/4781)) ([682ce0f](https://github.com/shantanusharma/deepagents/commit/682ce0fc760e96cf546ea9c97050293548aebc45))
* **code:** complete the `dcode config` surface ([#5581](https://github.com/shantanusharma/deepagents/issues/5581)) ([84eb09d](https://github.com/shantanusharma/deepagents/commit/84eb09d8edaa52297ca3e2ad76a2c85a9adf4130))
* **code:** condition relative timestamp toggle ([#5503](https://github.com/shantanusharma/deepagents/issues/5503)) ([96d72a1](https://github.com/shantanusharma/deepagents/commit/96d72a188bf951c9d3ca103e6611dcb50961af93))
* **code:** confirm auto-update success only after loading new version ([#7344](https://github.com/shantanusharma/deepagents/issues/7344)) ([ab57336](https://github.com/shantanusharma/deepagents/commit/ab5733605b4398e3be26f7f2b2cfc768f71585b6))
* **code:** confirm server restart for workspace switch ([#6178](https://github.com/shantanusharma/deepagents/issues/6178)) ([7997203](https://github.com/shantanusharma/deepagents/commit/7997203245915aa83e87db83252c04391bd00440))
* **code:** consistent modal backdrop dimming for selectors ([#4990](https://github.com/shantanusharma/deepagents/issues/4990)) ([3606e3f](https://github.com/shantanusharma/deepagents/commit/3606e3f3fa2faac97f30141f9ee54e37631d16ad))
* **code:** consistent styling and links for thread status messages ([#5118](https://github.com/shantanusharma/deepagents/issues/5118)) ([9ad8dde](https://github.com/shantanusharma/deepagents/commit/9ad8dded08533a7915dc35e05f4c92c3b1ecb736))
* **code:** constrain `/effort` for between-tools thinking ([#6630](https://github.com/shantanusharma/deepagents/issues/6630)) ([17eea22](https://github.com/shantanusharma/deepagents/commit/17eea22b966f3fc136c27a60437ecb40636b34ca))
* **code:** contain JavaScript subagent failures ([#7211](https://github.com/shantanusharma/deepagents/issues/7211)) ([b93aff0](https://github.com/shantanusharma/deepagents/commit/b93aff082ede97cecbd21fd456f879c1fae5b9e2))
* **code:** correct editable SDK detection to scan and correlate ([#5199](https://github.com/shantanusharma/deepagents/issues/5199)) ([4693ee7](https://github.com/shantanusharma/deepagents/commit/4693ee774771c5936ffa1783396aa4e2126211b1))
* **code:** correct LangSmith sandbox working directory ([#3415](https://github.com/shantanusharma/deepagents/issues/3415)) ([b0e8d83](https://github.com/shantanusharma/deepagents/commit/b0e8d83f97a2a698268173a839000c84e8368324))
* **code:** correct transcript height hints for folded tool rows ([#7251](https://github.com/shantanusharma/deepagents/issues/7251)) ([1a1d484](https://github.com/shantanusharma/deepagents/commit/1a1d4840dad2370f26acc5bdea5452081cb7502f))
* **code:** count distinct targets in grouped tool summaries ([#5409](https://github.com/shantanusharma/deepagents/issues/5409)) ([cf8ea93](https://github.com/shantanusharma/deepagents/commit/cf8ea93a634b2ae03fa9033db6e0e240ed2ae1a1))
* **code:** count only running tools in live tool-group line ([#4809](https://github.com/shantanusharma/deepagents/issues/4809)) ([4d483fd](https://github.com/shantanusharma/deepagents/commit/4d483fdf39b6d7c691322041a4fc58be06ecfd6b))
* **code:** cursor at end when popping queued message to input ([#3832](https://github.com/shantanusharma/deepagents/issues/3832)) ([aa522c9](https://github.com/shantanusharma/deepagents/commit/aa522c94fffb93dc578addb39b4879f779ac5899))
* **code:** decode git output as UTF-8 ([#7142](https://github.com/shantanusharma/deepagents/issues/7142)) ([4f3ca06](https://github.com/shantanusharma/deepagents/commit/4f3ca06ef1dad7a8a03c9ead515860f52ab1de4d))
* **code:** dedupe Auto classifier-unavailable transcript spam ([#5013](https://github.com/shantanusharma/deepagents/issues/5013)) ([9500306](https://github.com/shantanusharma/deepagents/commit/9500306a17f90dc2f27897c364c24cafffbc474a))
* **code:** dedupe update/install log path output ([#4553](https://github.com/shantanusharma/deepagents/issues/4553)) ([1398fee](https://github.com/shantanusharma/deepagents/commit/1398feeca507cab9ec51a66604d46c747f7fcd2f))
* **code:** deduplicate content from system prompt by overwriting base prompt ([#4516](https://github.com/shantanusharma/deepagents/issues/4516)) ([2266f58](https://github.com/shantanusharma/deepagents/commit/2266f58e4713d23ba0b30eb8646424d01165c11b))
* **code:** deduplicate footer picker clicks ([#6344](https://github.com/shantanusharma/deepagents/issues/6344)) ([811e927](https://github.com/shantanusharma/deepagents/commit/811e92738ffa491e991b9dea6573fff57a84d938))
* **code:** deduplicate mixed-ID model usage ([#6432](https://github.com/shantanusharma/deepagents/issues/6432)) ([bdca132](https://github.com/shantanusharma/deepagents/commit/bdca132ee7fbf84ab611392adb6846a1c545d26c))
* **code:** defer in-app uv installs on Windows ([#7518](https://github.com/shantanusharma/deepagents/issues/7518)) ([c4e2811](https://github.com/shantanusharma/deepagents/commit/c4e2811312718e98b1465b6e67c34997ca72c793))
* **code:** defer plugin reload hint during startup ([#5502](https://github.com/shantanusharma/deepagents/issues/5502)) ([dc029ef](https://github.com/shantanusharma/deepagents/commit/dc029ef5072e9114125e4d332d3631dc1c3d4883))
* **code:** defer server graph construction ([#4300](https://github.com/shantanusharma/deepagents/issues/4300)) ([220dfc0](https://github.com/shantanusharma/deepagents/commit/220dfc0e6b03f9ccb499c6b850c586b9d57cc077))
* **code:** defer the recursion limit to the LangGraph server ([#5882](https://github.com/shantanusharma/deepagents/issues/5882)) ([4379a46](https://github.com/shantanusharma/deepagents/commit/4379a463a181a978aab206e93cdcc0788f7eac2b))
* **code:** delay hook status in footer ([#6322](https://github.com/shantanusharma/deepagents/issues/6322)) ([7f9e8ed](https://github.com/shantanusharma/deepagents/commit/7f9e8ed3a555933902045792da9bb184950ee7b2))
* **code:** delay tool group progress to avoid flashing ([#7357](https://github.com/shantanusharma/deepagents/issues/7357)) ([cd24d8c](https://github.com/shantanusharma/deepagents/commit/cd24d8c52849fdb24e0ac2cab2f909f8df6ba5ca))
* **code:** demote no-output hint suppression to debug ([#6245](https://github.com/shantanusharma/deepagents/issues/6245)) ([d93ab33](https://github.com/shantanusharma/deepagents/commit/d93ab3351bbf4c3687212f665094ccad100f2c08))
* **code:** detach owned `langgraph dev` server from terminal ([#4642](https://github.com/shantanusharma/deepagents/issues/4642)) ([d1f3afe](https://github.com/shantanusharma/deepagents/commit/d1f3afecdc015b5d1c9fb098d6347c7d7180e417))
* **code:** diagnose workspace binding and runtime refusals ([#6384](https://github.com/shantanusharma/deepagents/issues/6384)) ([f9ffd51](https://github.com/shantanusharma/deepagents/commit/f9ffd51154296f81f832f5f184407bc0067acbaf))
* **code:** disable Git terminal prompts in `execute` ([#5878](https://github.com/shantanusharma/deepagents/issues/5878)) ([a535b61](https://github.com/shantanusharma/deepagents/commit/a535b610a158a79a2629fac73fa788d7b31f4096))
* **code:** disable LangSmith secret redaction by default ([#4970](https://github.com/shantanusharma/deepagents/issues/4970)) ([d029585](https://github.com/shantanusharma/deepagents/commit/d029585ab79432d00edfa5a70e77a31f2388ed5b))
* **code:** disclose inherited classifier model switches ([#7351](https://github.com/shantanusharma/deepagents/issues/7351)) ([3c7cd4b](https://github.com/shantanusharma/deepagents/commit/3c7cd4bc4e857849e21ebca287065e590157ff55))
* **code:** disentangle version diagnostics for editable installs ([#4816](https://github.com/shantanusharma/deepagents/issues/4816)) ([7408378](https://github.com/shantanusharma/deepagents/commit/7408378896344e4db7dbc45a35ae6b02cc746d31))
* **code:** dismiss startup tip on `-m` initial submission ([#4779](https://github.com/shantanusharma/deepagents/issues/4779)) ([8acd414](https://github.com/shantanusharma/deepagents/commit/8acd414a2e712d8b8b1968e40bff40483196856b))
* **code:** distinguish LangSmith failure modes in `/trace` ([#3558](https://github.com/shantanusharma/deepagents/issues/3558)) ([4d158a0](https://github.com/shantanusharma/deepagents/commit/4d158a031aecad8862e02e332f127573003938ec))
* **code:** don't move cursor on click that re-focuses terminal ([#3893](https://github.com/shantanusharma/deepagents/issues/3893)) ([b76788b](https://github.com/shantanusharma/deepagents/commit/b76788b7850e910fe2882cb1a62ffff6ff5085b0))
* **code:** don't show `"No threads found"` while threads load ([#3815](https://github.com/shantanusharma/deepagents/issues/3815)) ([68e6426](https://github.com/shantanusharma/deepagents/commit/68e64263f590b3244b689664715f354fb3a389cd))
* **code:** drain hook pipes after timeout ([#5606](https://github.com/shantanusharma/deepagents/issues/5606)) ([575a8ac](https://github.com/shantanusharma/deepagents/commit/575a8acb0307bbea9e08f4f8c15d850580a55cb3))
* **code:** drop `Muse Spark 1.1` recommendation ([#5683](https://github.com/shantanusharma/deepagents/issues/5683)) ([fa2e8ab](https://github.com/shantanusharma/deepagents/commit/fa2e8abb4da1f07163cb5ee3daff4d57ea97fe9f))
* **code:** drop `uv install` tip from `/version` update hint ([#4822](https://github.com/shantanusharma/deepagents/issues/4822)) ([4e618f0](https://github.com/shantanusharma/deepagents/commit/4e618f07b4b00f94133b4d1c105011c438cb35be))
* **code:** drop duplicate token-request `client_id` under Basic auth ([#4323](https://github.com/shantanusharma/deepagents/issues/4323)) ([426dfad](https://github.com/shantanusharma/deepagents/commit/426dfad3ea1e453914cb87efa8fc70fb85a9efcb))
* **code:** drop lock-key events so Caps Lock in iTerm2 doesn't type ([#3855](https://github.com/shantanusharma/deepagents/issues/3855)) ([110f1a7](https://github.com/shantanusharma/deepagents/commit/110f1a7a975743efda12e181cb3afc8404202254))
* **code:** drop redundant `/restart` hint from restart prompt ([#5083](https://github.com/shantanusharma/deepagents/issues/5083)) ([b34899f](https://github.com/shantanusharma/deepagents/commit/b34899fccd051ab741000c771eef9a2dc4439d80))
* **code:** drop redundant version from "already up to date" message ([#4223](https://github.com/shantanusharma/deepagents/issues/4223)) ([5d080df](https://github.com/shantanusharma/deepagents/commit/5d080df2776d380214bf20ae31266b9628e4e5b0))
* **code:** drop sections from `system_prompt.md` already supplied by SDK middleware ([#3448](https://github.com/shantanusharma/deepagents/issues/3448)) ([9dbf2c2](https://github.com/shantanusharma/deepagents/commit/9dbf2c2f19e941e012d0c93418ef09fb56f30d6a))
* **code:** drop stale Anthropic thinking blocks ([#6300](https://github.com/shantanusharma/deepagents/issues/6300)) ([fe01fac](https://github.com/shantanusharma/deepagents/commit/fe01fac1fa3c4d30d9379a9e5f4273a622710049))
* **code:** drop the "Message restored to input" toast ([#5253](https://github.com/shantanusharma/deepagents/issues/5253)) ([c206eb4](https://github.com/shantanusharma/deepagents/commit/c206eb450d612f77924ee55ecd136fbc52f459ab))
* **code:** eager managed ripgrep install via `dcode tools install` ([#4199](https://github.com/shantanusharma/deepagents/issues/4199)) ([cf536f3](https://github.com/shantanusharma/deepagents/commit/cf536f339958d6726fa41f896c4a3e42df644c9f))
* **code:** editable-install guidance for adding extras ([#3610](https://github.com/shantanusharma/deepagents/issues/3610)) ([771e55f](https://github.com/shantanusharma/deepagents/commit/771e55f171b8087b876ecf767d2f23c86c2a27b9))
* **code:** enable Claude prompt caching on OpenRouter ([#7358](https://github.com/shantanusharma/deepagents/issues/7358)) ([417af26](https://github.com/shantanusharma/deepagents/commit/417af26f694d7d65f82e7f89e037c4565a47f955))
* **code:** end typing deferral when submitting a prompt ([#7335](https://github.com/shantanusharma/deepagents/issues/7335)) ([9a6bc92](https://github.com/shantanusharma/deepagents/commit/9a6bc92312293d95594bf6bd473b35679f6d7263))
* **code:** ensure rubric coverage ([#5369](https://github.com/shantanusharma/deepagents/issues/5369)) ([442933d](https://github.com/shantanusharma/deepagents/commit/442933da662d4497a29558f889ca972cd36b5488))
* **code:** ensure unique message widget IDs on history load ([#4454](https://github.com/shantanusharma/deepagents/issues/4454)) ([de2f7d2](https://github.com/shantanusharma/deepagents/commit/de2f7d2835485df905772e1c96e33d2c239d8e22))
* **code:** exclude managed bin dir from agent picker ([#4190](https://github.com/shantanusharma/deepagents/issues/4190)) ([d869d1e](https://github.com/shantanusharma/deepagents/commit/d869d1e1fa8558510fb48e71f78fb74c69ca4840))
* **code:** exclude prompt prefix from `UserMessage` selection ([#4002](https://github.com/shantanusharma/deepagents/issues/4002)) ([8ee6ba6](https://github.com/shantanusharma/deepagents/commit/8ee6ba6e64895d3d36a5957627221ed7667bc1d4))
* **code:** explain disabled Slack MCP access on login ([#7498](https://github.com/shantanusharma/deepagents/issues/7498)) ([7618f1f](https://github.com/shantanusharma/deepagents/commit/7618f1fedffd1c8f42e0781eb5eb947c08f466fa))
* **code:** explain repeated skill-trust denials and clear them on `/reload` ([#7291](https://github.com/shantanusharma/deepagents/issues/7291)) ([47cf0fb](https://github.com/shantanusharma/deepagents/commit/47cf0fb888591bf841637da371a344598ce09718))
* **code:** explain why `doctor` has no latest-version answer ([#5209](https://github.com/shantanusharma/deepagents/issues/5209)) ([ef3e078](https://github.com/shantanusharma/deepagents/commit/ef3e078795e01b8334151081d026d6a88268d5a9))
* **code:** explain workspace conflicts and MCP login failures ([#7499](https://github.com/shantanusharma/deepagents/issues/7499)) ([a783c14](https://github.com/shantanusharma/deepagents/commit/a783c149c7655d45e5e0fcb09a6ff0a3c15ca516))
* **code:** expose `/restart` slash command ([#3809](https://github.com/shantanusharma/deepagents/issues/3809)) ([64505b8](https://github.com/shantanusharma/deepagents/commit/64505b848868b80213b6da87113cd63890c3d520))
* **code:** expose unknown reasoning effort ([#6241](https://github.com/shantanusharma/deepagents/issues/6241)) ([ed715ee](https://github.com/shantanusharma/deepagents/commit/ed715eeba608af47c9ed7943822c25d935a30b9e))
* **code:** extend text selection with `Shift` + `click` ([#5732](https://github.com/shantanusharma/deepagents/issues/5732)) ([e05931b](https://github.com/shantanusharma/deepagents/commit/e05931b3016ed3d1500df0c5b77402f457ee5686))
* **code:** extend triple-click selection across blocks ([#6819](https://github.com/shantanusharma/deepagents/issues/6819)) ([4f6a798](https://github.com/shantanusharma/deepagents/commit/4f6a798928d2445f8efec3a7a85324cdf0638b3d))
* **code:** fail closed when hook context changes on resume ([#6712](https://github.com/shantanusharma/deepagents/issues/6712)) ([3086f7b](https://github.com/shantanusharma/deepagents/commit/3086f7b918b53b12a6ad675231ebd4752d4a420a))
* **code:** find editor launchers like `code.cmd` on Windows ([#7642](https://github.com/shantanusharma/deepagents/issues/7642)) ([1ea2055](https://github.com/shantanusharma/deepagents/commit/1ea2055a7615b647cc1961a68b9742b88aef731a))
* **code:** fire `PreCompact` before auto-compaction ([#5277](https://github.com/shantanusharma/deepagents/issues/5277)) ([f4cc516](https://github.com/shantanusharma/deepagents/commit/f4cc5160c75eb44e8ddee8b049048690ea0f8616))
* **code:** fix product and command names in skill guides ([#6637](https://github.com/shantanusharma/deepagents/issues/6637)) ([cc95cc8](https://github.com/shantanusharma/deepagents/commit/cc95cc8f0e7e51b44d416ceaafd67a6a4fdefeee))
* **code:** fix zero tool MCP server rendering ([#3649](https://github.com/shantanusharma/deepagents/issues/3649)) ([7e7a567](https://github.com/shantanusharma/deepagents/commit/7e7a567556110ad927a78b45c3a3d4ac37b65e86))
* **code:** flag and repair enabled plugins with missing installed files ([#7278](https://github.com/shantanusharma/deepagents/issues/7278)) ([89efee3](https://github.com/shantanusharma/deepagents/commit/89efee335dfdf08c874b54e4f6c911e3b7185ffb))
* **code:** flag empty env override shadowing LangSmith key in `/trace` ([#4996](https://github.com/shantanusharma/deepagents/issues/4996)) ([313f952](https://github.com/shantanusharma/deepagents/commit/313f9520cef28c105aa53eac645176d422ec4a97))
* **code:** flush traces before server shutdown ([#5837](https://github.com/shantanusharma/deepagents/issues/5837)) ([804fdcc](https://github.com/shantanusharma/deepagents/commit/804fdcc436538686ca345965c0511e0664eb7c34))
* **code:** full-width chat messages, hide scrollbar, flush input bg ([#4374](https://github.com/shantanusharma/deepagents/issues/4374)) ([1f8e8dc](https://github.com/shantanusharma/deepagents/commit/1f8e8dc942ac54c4014ac48f9345ee0201be0b1b))
* **code:** gate `delete` file operations ([#4299](https://github.com/shantanusharma/deepagents/issues/4299)) ([92a8681](https://github.com/shantanusharma/deepagents/commit/92a86819adfefbc6ccfd01a861191ba292eca754))
* **code:** gate Hooks v2 behind `DEEPAGENTS_CODE_EXPERIMENTAL` ([#5146](https://github.com/shantanusharma/deepagents/issues/5146)) ([7d4acb6](https://github.com/shantanusharma/deepagents/commit/7d4acb6804cd17eb4c2337b9af11aee9f3601d01))
* **code:** generic "missing credentials" in model switcher ([#4182](https://github.com/shantanusharma/deepagents/issues/4182)) ([456ce5c](https://github.com/shantanusharma/deepagents/commit/456ce5c2f5487a754d1fea7046e32c03b7e27a17))
* **code:** give `config get` a useful missing-key message ([#4976](https://github.com/shantanusharma/deepagents/issues/4976)) ([260c33e](https://github.com/shantanusharma/deepagents/commit/260c33ee28ade91741ba226ef3e719b6b8c8c02c))
* **code:** give transcript spacers their real height so scrolling reaches the newest message ([#7253](https://github.com/shantanusharma/deepagents/issues/7253)) ([793ac5a](https://github.com/shantanusharma/deepagents/commit/793ac5af081079977616fe1925b09670871121d3))
* **code:** group resume trace rounds ([#5593](https://github.com/shantanusharma/deepagents/issues/5593)) ([345859e](https://github.com/shantanusharma/deepagents/commit/345859e8e13d5b48348efebd0a48bfb4d3fbf132))
* **code:** guard `fetch_url` against SSRF ([#3411](https://github.com/shantanusharma/deepagents/issues/3411)) ([54d8521](https://github.com/shantanusharma/deepagents/commit/54d8521976940dfe147ead4b56565360241335be))
* **code:** guard against misconfigured LangSmith tracing ([#3993](https://github.com/shantanusharma/deepagents/issues/3993)) ([81acc2e](https://github.com/shantanusharma/deepagents/commit/81acc2ecdada55a98e512f96b0caf8cb0f2c6d29))
* **code:** guard pasted-path probes against `OSError` ([#3745](https://github.com/shantanusharma/deepagents/issues/3745)) ([c9617d3](https://github.com/shantanusharma/deepagents/commit/c9617d3594ab1448c4f3ee2212cdc66cbf138b77))
* **code:** guard path expansion in the Auto approval gate ([#5941](https://github.com/shantanusharma/deepagents/issues/5941)) ([46dea07](https://github.com/shantanusharma/deepagents/commit/46dea076a77f2b580829b5a211469c68b8924f2a))
* **code:** guard restart-prompt import against in-place self-upgrade ([#3980](https://github.com/shantanusharma/deepagents/issues/3980)) ([7af13f6](https://github.com/shantanusharma/deepagents/commit/7af13f6ec2440c2e3eb63bad2ff31e809f772804))
* **code:** hand pointer over splash tracing project link ([#3858](https://github.com/shantanusharma/deepagents/issues/3858)) ([ea7dae5](https://github.com/shantanusharma/deepagents/commit/ea7dae58a37cfb1d2b96544eb7c941aad331b280))
* **code:** handle LangSmith project-not-found and default tracing project ([#4153](https://github.com/shantanusharma/deepagents/issues/4153)) ([e303ce9](https://github.com/shantanusharma/deepagents/commit/e303ce986a3595f0cf458e796d857f7c8f5f8b5c))
* **code:** handle malformed hook resumes ([#5233](https://github.com/shantanusharma/deepagents/issues/5233)) ([bd562c8](https://github.com/shantanusharma/deepagents/commit/bd562c879ad3a8eec0a930bba23ef57fee163c05))
* **code:** handle MCP tool errors locally ([#3830](https://github.com/shantanusharma/deepagents/issues/3830)) ([97a7052](https://github.com/shantanusharma/deepagents/commit/97a7052b3eef7ec80bc90a4c3b606deeaf13cb9b))
* **code:** handle recursive `fetch_url` conversion ([#4257](https://github.com/shantanusharma/deepagents/issues/4257)) ([f240a40](https://github.com/shantanusharma/deepagents/commit/f240a40dc05d812c38e9926c1d81ba38deb86e3f))
* **code:** handle stale slash-command `Enter` before completion popup renders ([#3647](https://github.com/shantanusharma/deepagents/issues/3647)) ([9a28742](https://github.com/shantanusharma/deepagents/commit/9a287424e86d5d52d0a328388c3fe453b160f597))
* **code:** harden `dcode completion` output and setup steps ([#7658](https://github.com/shantanusharma/deepagents/issues/7658)) ([277c8b5](https://github.com/shantanusharma/deepagents/commit/277c8b5d16dcf8d7af8b6f81bd87e8797f552856))
* **code:** harden approval content rendering ([#4581](https://github.com/shantanusharma/deepagents/issues/4581)) ([38446fd](https://github.com/shantanusharma/deepagents/commit/38446fda649b891dd8604e788701eabe739c1dd0))
* **code:** harden Hooks v2 command execution ([#4917](https://github.com/shantanusharma/deepagents/issues/4917)) ([05dd0d1](https://github.com/shantanusharma/deepagents/commit/05dd0d1bee7d79be6ac7f18db0d05b521e760326))
* **code:** harden installer downloads and paths ([#4871](https://github.com/shantanusharma/deepagents/issues/4871)) ([9a5bbeb](https://github.com/shantanusharma/deepagents/commit/9a5bbeb7558405054e970decfc1aef5b96a026f3))
* **code:** hide "Recent" section during onboarding model selection ([#4198](https://github.com/shantanusharma/deepagents/issues/4198)) ([af882e4](https://github.com/shantanusharma/deepagents/commit/af882e4f6c859878e350d8a37bb75b7bc01bb453))
* **code:** hide `[SYSTEM]` interrupt notices from `/threads` prompt ([#3988](https://github.com/shantanusharma/deepagents/issues/3988)) ([68fa0cb](https://github.com/shantanusharma/deepagents/commit/68fa0cb4d48ff3f3e552bbf16f8316433c7b6f34))
* **code:** hide `Auto` option in approval widget when ineligible ([#4839](https://github.com/shantanusharma/deepagents/issues/4839)) ([1a1f06f](https://github.com/shantanusharma/deepagents/commit/1a1f06f506d5a167609de336cced740151b6615a))
* **code:** hide chat input action buttons in same frame as empty draft ([#4178](https://github.com/shantanusharma/deepagents/issues/4178)) ([f94d417](https://github.com/shantanusharma/deepagents/commit/f94d417d5ad9928db967777fe1d7bc2c37684fb9))
* **code:** hide chat input cursor while unfocused ([#5258](https://github.com/shantanusharma/deepagents/issues/5258)) ([c66d9b8](https://github.com/shantanusharma/deepagents/commit/c66d9b8500f120d6552af258750da8bb0dede7b8))
* **code:** hide dependency details after updates ([#5519](https://github.com/shantanusharma/deepagents/issues/5519)) ([cf7578d](https://github.com/shantanusharma/deepagents/commit/cf7578d1c3403bde960a43cba51f5dad7c336cb3))
* **code:** hide empty previous-thread hints ([#5552](https://github.com/shantanusharma/deepagents/issues/5552)) ([0f5bd4f](https://github.com/shantanusharma/deepagents/commit/0f5bd4f3356d0fcbdea436a27c8011629416a61c))
* **code:** hide inactive F2 tool hint ([#5939](https://github.com/shantanusharma/deepagents/issues/5939)) ([fd7ba1a](https://github.com/shantanusharma/deepagents/commit/fd7ba1ac47e9afbf7a60a40010f72130ff47ee25))
* **code:** hide incomplete extras from version output ([#5352](https://github.com/shantanusharma/deepagents/issues/5352)) ([38f32cd](https://github.com/shantanusharma/deepagents/commit/38f32cdbfdfcf1728178dbee85a42751dd3f3d2e))
* **code:** hide invalid cache metrics ([#5475](https://github.com/shantanusharma/deepagents/issues/5475)) ([33a57cb](https://github.com/shantanusharma/deepagents/commit/33a57cbe6808e3da5f4067b7567f77845578ff61))
* **code:** hide MCP token path outside debug mode ([#5866](https://github.com/shantanusharma/deepagents/issues/5866)) ([bd79104](https://github.com/shantanusharma/deepagents/commit/bd791048b3dfafae3df81e89aa81388e26bc9667))
* **code:** hide onboarding Tavily cancel hint ([#5684](https://github.com/shantanusharma/deepagents/issues/5684)) ([b91da61](https://github.com/shantanusharma/deepagents/commit/b91da61716253dbcf1805c6dede589ec41a09ec5))
* **code:** hide startup tips when resuming threads ([#5349](https://github.com/shantanusharma/deepagents/issues/5349)) ([ff421f2](https://github.com/shantanusharma/deepagents/commit/ff421f2f316f3819d8ac92225ea032dabfbcefe9))
* **code:** hide thread IDs when tracing is disabled ([#5692](https://github.com/shantanusharma/deepagents/issues/5692)) ([1680237](https://github.com/shantanusharma/deepagents/commit/1680237e69bf27740001df7a7f67de5a053536c1))
* **code:** hide timestamp footers with the rows they belong to ([#5167](https://github.com/shantanusharma/deepagents/issues/5167)) ([a3e3798](https://github.com/shantanusharma/deepagents/commit/a3e3798599705afd2d0a3fce8116df61f22a551d))
* **code:** hide unavailable prompt search hints ([#6543](https://github.com/shantanusharma/deepagents/issues/6543)) ([3ba4356](https://github.com/shantanusharma/deepagents/commit/3ba435604c4b7f664978fa3c5f81914b05d86321))
* **code:** highlight expired prompt cache in the footer ([#6970](https://github.com/shantanusharma/deepagents/issues/6970)) ([23bc1d7](https://github.com/shantanusharma/deepagents/commit/23bc1d77f94bef746f64cfae7730705e23485d52))
* **code:** highlight just-installed provider on `/auth` reopen ([#4311](https://github.com/shantanusharma/deepagents/issues/4311)) ([85e47b5](https://github.com/shantanusharma/deepagents/commit/85e47b532b5caf92a52f1a070a95bdb39bee6d3d))
* **code:** highlight the first line of multiline chat input ([#6781](https://github.com/shantanusharma/deepagents/issues/6781)) ([2fd6686](https://github.com/shantanusharma/deepagents/commit/2fd66863c277cacc82dbcb39021e01691fb43e1f))
* **code:** honest MCP OAuth callback close message ([#4410](https://github.com/shantanusharma/deepagents/issues/4410)) ([ef637f4](https://github.com/shantanusharma/deepagents/commit/ef637f4a3f38ee155ad7d31e64a5cdd7bfaee62c))
* **code:** honor Baseten base URL env precedence ([#4328](https://github.com/shantanusharma/deepagents/issues/4328)) ([8f20d74](https://github.com/shantanusharma/deepagents/commit/8f20d74892112c3b88aaca63d8c04a355fd6726f))
* **code:** honor MCP hook approval policies ([#7766](https://github.com/shantanusharma/deepagents/issues/7766)) ([709070b](https://github.com/shantanusharma/deepagents/commit/709070b4128068fa1ce178a78a7065d6874dc15c))
* **code:** honor MCP server disables for plugins ([#4848](https://github.com/shantanusharma/deepagents/issues/4848)) ([eea0a84](https://github.com/shantanusharma/deepagents/commit/eea0a84d9621565a707c161c2f22878771d9b38b))
* **code:** hydrate resumed history on demand ([#6342](https://github.com/shantanusharma/deepagents/issues/6342)) ([8ea734a](https://github.com/shantanusharma/deepagents/commit/8ea734a809dd7d4e8c56ceeb286b5718ad1c7753))
* **code:** hydrate transcript tail when scrolled to the bottom edge ([#4733](https://github.com/shantanusharma/deepagents/issues/4733)) ([02a2461](https://github.com/shantanusharma/deepagents/commit/02a246144c764a1c57b60223652ade8716c7529b))
* **code:** hydrate virtualized transcript on scroll offset changes ([#4646](https://github.com/shantanusharma/deepagents/issues/4646)) ([f77eeb0](https://github.com/shantanusharma/deepagents/commit/f77eeb0a036281f84bf7d0b05ea60e02630f55c1))
* **code:** ignore LangSmith default US endpoint as custom target ([#5022](https://github.com/shantanusharma/deepagents/issues/5022)) ([ffb7aab](https://github.com/shantanusharma/deepagents/commit/ffb7aabe25d3d5ad7c5fce139f3bc3e14e245adf))
* **code:** ignore mouse hits on detached widgets ([#5114](https://github.com/shantanusharma/deepagents/issues/5114)) ([d4d2b60](https://github.com/shantanusharma/deepagents/commit/d4d2b60e37ae034e69f60ab5f34267b542c00dd5))
* **code:** ignore stale cwd warmers in file autocomplete cache ([#3835](https://github.com/shantanusharma/deepagents/issues/3835)) ([9c8c2b2](https://github.com/shantanusharma/deepagents/commit/9c8c2b24853b7b3a7610cbcfc368a6464c0711e0))
* **code:** improve `/rubric` help and empty-state messaging ([#5015](https://github.com/shantanusharma/deepagents/issues/5015)) ([1a3f46b](https://github.com/shantanusharma/deepagents/commit/1a3f46b85861779ed44e880cc7921cdd6f28fdfa))
* **code:** improve empty marketplace onboarding and list polish ([#4759](https://github.com/shantanusharma/deepagents/issues/4759)) ([ab2e101](https://github.com/shantanusharma/deepagents/commit/ab2e101d02d0fc5be45b0581c4e04d441402dc29))
* **code:** include skill invocations in input history ([#4211](https://github.com/shantanusharma/deepagents/issues/4211)) ([7b8d0b2](https://github.com/shantanusharma/deepagents/commit/7b8d0b2ec184e0d9a0cbe858a0d9a7128791969d))
* **code:** increase warm limit to 800 ([#5728](https://github.com/shantanusharma/deepagents/issues/5728)) ([f954cde](https://github.com/shantanusharma/deepagents/commit/f954cde37f1171adc2ec3f1516a0393bded47e82))
* **code:** indent wrapped ask-user choices and add selection styling ([#5442](https://github.com/shantanusharma/deepagents/issues/5442)) ([a78d7b1](https://github.com/shantanusharma/deepagents/commit/a78d7b1744050c3221aab5e0c0300cc5f5bec519))
* **code:** infer additional model providers ([#4675](https://github.com/shantanusharma/deepagents/issues/4675)) ([4ceed24](https://github.com/shantanusharma/deepagents/commit/4ceed24d3758801ed9df1024602e90488004cef1))
* **code:** infer Fireworks provider from qualified model IDs ([#4594](https://github.com/shantanusharma/deepagents/issues/4594)) ([4d2aa8a](https://github.com/shantanusharma/deepagents/commit/4d2aa8a9684609eee45cd93b0af5149d8dd09eea))
* **code:** inject OpenAI `prompt_cache_key` for any OpenAI-provider endpoint ([#4995](https://github.com/shantanusharma/deepagents/issues/4995)) ([6d6632f](https://github.com/shantanusharma/deepagents/commit/6d6632fa39822f1b774fcabd61ed371a90427113))
* **code:** install script binary checks reference `dcode` ([#3546](https://github.com/shantanusharma/deepagents/issues/3546)) ([f8977a6](https://github.com/shantanusharma/deepagents/commit/f8977a63769e3f2037619f32596cb9bb7bd1020b))
* **code:** interrupt remote runs on chat cancellation ([#4234](https://github.com/shantanusharma/deepagents/issues/4234)) ([37c5fa2](https://github.com/shantanusharma/deepagents/commit/37c5fa23e621616836694bc59c1b0c38def81604))
* **code:** isolate debug logs by thread ([#5921](https://github.com/shantanusharma/deepagents/issues/5921)) ([4358cce](https://github.com/shantanusharma/deepagents/commit/4358ccee79dc9350600af02e4e52633b919d7382))
* **code:** isolate LangSmith auth and workspace tracing ([#6061](https://github.com/shantanusharma/deepagents/issues/6061)) ([794eda8](https://github.com/shantanusharma/deepagents/commit/794eda83b777a2a7278e5726607e4b305801298d))
* **code:** isolate parallel `task` failures ([#5954](https://github.com/shantanusharma/deepagents/issues/5954)) ([e0a474f](https://github.com/shantanusharma/deepagents/commit/e0a474fed575992abc991f6a8049cc8e18e328c0))
* **code:** isolate stored provider endpoints in workspace models ([#6771](https://github.com/shantanusharma/deepagents/issues/6771)) ([7803173](https://github.com/shantanusharma/deepagents/commit/78031730dbe1ae418f39be96f6d2b1e60fbe4545))
* **code:** isolate user shell tracing credentials ([#6242](https://github.com/shantanusharma/deepagents/issues/6242)) ([35c21fa](https://github.com/shantanusharma/deepagents/commit/35c21faafe329f4f6932c0941d163306e1aa06e5))
* **code:** join aiosqlite worker thread after close ([#3585](https://github.com/shantanusharma/deepagents/issues/3585)) ([152cec0](https://github.com/shantanusharma/deepagents/commit/152cec04affed3508d4bfdffe7cae522b16d45e6))
* **code:** keep `/update` and `/install --package` prompts responsive ([#5127](https://github.com/shantanusharma/deepagents/issues/5127)) ([5726872](https://github.com/shantanusharma/deepagents/commit/5726872cd5efec9367ae2ce678aa7183af74335d))
* **code:** keep `task` timers monotonic across nested subagent HITL ([#4771](https://github.com/shantanusharma/deepagents/issues/4771)) ([6952011](https://github.com/shantanusharma/deepagents/commit/69520118a7f96866a5e92e7b31894d8ba3312938))
* **code:** keep absolute paths in normal input mode ([#6379](https://github.com/shantanusharma/deepagents/issues/6379)) ([141ce98](https://github.com/shantanusharma/deepagents/commit/141ce9851b876f733ef390ead3edbc509536a8e8))
* **code:** keep auth modal interactive after install-on-select ([#4187](https://github.com/shantanusharma/deepagents/issues/4187)) ([afbc56a](https://github.com/shantanusharma/deepagents/commit/afbc56a1d9dbe8a89015f4c2f90bb87547d5c1d4))
* **code:** keep chat input focused when clicking a message ([#3655](https://github.com/shantanusharma/deepagents/issues/3655)) ([daf6571](https://github.com/shantanusharma/deepagents/commit/daf65716d7c999eadb2b7c37e412ec07b2c7aed3))
* **code:** keep chat input responsive during `/reload` ([#5529](https://github.com/shantanusharma/deepagents/issues/5529)) ([5aa266e](https://github.com/shantanusharma/deepagents/commit/5aa266eab5ca0aedee58367c63599a926863d2cf))
* **code:** keep chat input responsive during `/restart` ([#4808](https://github.com/shantanusharma/deepagents/issues/4808)) ([a915c59](https://github.com/shantanusharma/deepagents/commit/a915c590dfb7c50d9bf697953ce724bad8dd4149))
* **code:** keep chat input responsive during MCP viewer `Ctrl+R` reconnect ([#4753](https://github.com/shantanusharma/deepagents/issues/4753)) ([28dc96d](https://github.com/shantanusharma/deepagents/commit/28dc96d08bc057f2e435b557062a819db4191310))
* **code:** keep compaction feedback and offload usage when summaries don't stream ([#7644](https://github.com/shantanusharma/deepagents/issues/7644)) ([0edc892](https://github.com/shantanusharma/deepagents/commit/0edc892d2b260199f9dd3a55ae1130b947f260e7))
* **code:** keep cut-off reply handling when `ModelRefusalMiddleware` raises ([#7548](https://github.com/shantanusharma/deepagents/issues/7548)) ([a9a0eb1](https://github.com/shantanusharma/deepagents/commit/a9a0eb116de959cd7210d3517102e95b3e035dcd))
* **code:** keep empty MCP servers searchable and match descriptions ([#6540](https://github.com/shantanusharma/deepagents/issues/6540)) ([8d599c9](https://github.com/shantanusharma/deepagents/commit/8d599c983e1b5e596d06b2569450dc2411ea8f3f))
* **code:** keep finished calls on live tool-group line ([#4927](https://github.com/shantanusharma/deepagents/issues/4927)) ([976c54b](https://github.com/shantanusharma/deepagents/commit/976c54b2e1392282044d9890a4a5d5d655f3e8dc))
* **code:** keep footer branch visible and ellipsized instead of hiding when narrow ([#4506](https://github.com/shantanusharma/deepagents/issues/4506)) ([ccf30c3](https://github.com/shantanusharma/deepagents/commit/ccf30c342e5ead677aafd196d8f1ddd2bdf95196))
* **code:** keep goal criteria proposal when marker clear fails ([#4785](https://github.com/shantanusharma/deepagents/issues/4785)) ([487b25f](https://github.com/shantanusharma/deepagents/commit/487b25f885c74b43ad2df837c6c0f6c45626be2a))
* **code:** keep harness-profile diagnostics out of terminal output ([#4943](https://github.com/shantanusharma/deepagents/issues/4943)) ([812bae4](https://github.com/shantanusharma/deepagents/commit/812bae4afad6749add097f9d58e489df9ec703a2))
* **code:** keep install-required `/model` rows dimmed after navigation ([#4048](https://github.com/shantanusharma/deepagents/issues/4048)) ([c499634](https://github.com/shantanusharma/deepagents/commit/c499634c530dcab9b18e3126b4573ff0d36c3efa))
* **code:** keep installation locks outside the uv tool directory ([#6472](https://github.com/shantanusharma/deepagents/issues/6472)) ([ec128d1](https://github.com/shantanusharma/deepagents/commit/ec128d14bd59561e955115c39b8d2a1cdd4dc720))
* **code:** keep installed providers visible in `/auth` ([#5689](https://github.com/shantanusharma/deepagents/issues/5689)) ([f0854e8](https://github.com/shantanusharma/deepagents/commit/f0854e82ed8cedd8a8455539eef596d1433eb68e))
* **code:** keep long thread resumes responsive ([#5772](https://github.com/shantanusharma/deepagents/issues/5772)) ([85e1e5b](https://github.com/shantanusharma/deepagents/commit/85e1e5b130b7501308e7e57d0be389f41f5b72df))
* **code:** keep MCP shutdown-race traceback off the terminal ([#5325](https://github.com/shantanusharma/deepagents/issues/5325)) ([7d97097](https://github.com/shantanusharma/deepagents/commit/7d9709700dd24cc2477cd091f01de990f23ee4a9))
* **code:** keep notification center open for API-key entry ([#4568](https://github.com/shantanusharma/deepagents/issues/4568)) ([6e89417](https://github.com/shantanusharma/deepagents/commit/6e8941776cdcc35909da305f3bb39500c0f479cb))
* **code:** keep paste placeholder when backspacing newline below it ([#4757](https://github.com/shantanusharma/deepagents/issues/4757)) ([ea82538](https://github.com/shantanusharma/deepagents/commit/ea825386b3c817f8461ea9e92c71de3411991e2a))
* **code:** keep post-install restart modal responsive ([#5086](https://github.com/shantanusharma/deepagents/issues/5086)) ([c4e2480](https://github.com/shantanusharma/deepagents/commit/c4e24804ebde93563f0596102bd5d9fc163ec0bf))
* **code:** keep prompt recall out of file picker ([#6494](https://github.com/shantanusharma/deepagents/issues/6494)) ([86b7f85](https://github.com/shantanusharma/deepagents/commit/86b7f85af7424ff2491206070897818d71e163cb))
* **code:** keep queued prompts beside long message text ([#7611](https://github.com/shantanusharma/deepagents/issues/7611)) ([cdbcaff](https://github.com/shantanusharma/deepagents/commit/cdbcaffcb309e983a9e2dc0dba9fa0b819e118f9))
* **code:** keep rapid typing visible ([#5424](https://github.com/shantanusharma/deepagents/issues/5424)) ([6a7c7d6](https://github.com/shantanusharma/deepagents/commit/6a7c7d6575915dbc4b1549133735f50666919979))
* **code:** keep server hook state out of task results ([#5164](https://github.com/shantanusharma/deepagents/issues/5164)) ([88ea7da](https://github.com/shantanusharma/deepagents/commit/88ea7da18e8be84e65df0edb8ffc4b904182f843))
* **code:** keep startup import prewarm from crashing the TUI mid-upgrade ([#3756](https://github.com/shantanusharma/deepagents/issues/3756)) ([867a2e5](https://github.com/shantanusharma/deepagents/commit/867a2e5c341bd9dfa70b47c7fafc194ac51d7469))
* **code:** keep terminal-default theme on Esc in `/theme` selector ([#3854](https://github.com/shantanusharma/deepagents/issues/3854)) ([c3bc67b](https://github.com/shantanusharma/deepagents/commit/c3bc67b0cdeda6f4dbcc6360ddd72b455aec4fe7))
* **code:** keep the `/goal` criteria prompt responsive ([#5142](https://github.com/shantanusharma/deepagents/issues/5142)) ([6f9ea6a](https://github.com/shantanusharma/deepagents/commit/6f9ea6a943dabe6c055766a43a204db6f4d95c98))
* **code:** keep the TUI responsive when quitting during server startup ([#7190](https://github.com/shantanusharma/deepagents/issues/7190)) ([4a77435](https://github.com/shantanusharma/deepagents/commit/4a7743569b4de9080d48b841b2e5f7eebaceda6b))
* **code:** keep thread picker open on ownership conflicts ([#6824](https://github.com/shantanusharma/deepagents/issues/6824)) ([bbae958](https://github.com/shantanusharma/deepagents/commit/bbae958439826bc3823a4cf5ea7a6b9fb6e70025))
* **code:** keep thread picker resume failures recoverable ([#6476](https://github.com/shantanusharma/deepagents/issues/6476)) ([6a41c53](https://github.com/shantanusharma/deepagents/commit/6a41c537fb1d4af7a34ef2340fff0f1c088548f4))
* **code:** keep TODO and edit tools expanded ([#4704](https://github.com/shantanusharma/deepagents/issues/4704)) ([1d549d3](https://github.com/shantanusharma/deepagents/commit/1d549d3f3c9bb60c3ce39d4a0c913bcefe9610d5))
* **code:** label `-r` resume as `"Resuming..."` in the status bar ([#3892](https://github.com/shantanusharma/deepagents/issues/3892)) ([70cd286](https://github.com/shantanusharma/deepagents/commit/70cd28643bc2ca7da5a61a7b7203c6de2266ca4e))
* **code:** launch stdio MCP servers in the session directory ([#6626](https://github.com/shantanusharma/deepagents/issues/6626)) ([d36ac68](https://github.com/shantanusharma/deepagents/commit/d36ac688242286b5c1e30d290648fcee0ea25b23))
* **code:** leave piped stdin to subcommands ([#7601](https://github.com/shantanusharma/deepagents/issues/7601)) ([ea91574](https://github.com/shantanusharma/deepagents/commit/ea91574b2240b06ce785bb49fa48ad9f2f153da7))
* **code:** let MCP footer wrap on narrow windows ([#5651](https://github.com/shantanusharma/deepagents/issues/5651)) ([d00926e](https://github.com/shantanusharma/deepagents/commit/d00926e9e0278d6e74f91622b00d1375c7af19ab))
* **code:** load MCP trust lists off the server event loop ([#7798](https://github.com/shantanusharma/deepagents/issues/7798)) ([f33c85e](https://github.com/shantanusharma/deepagents/commit/f33c85ea19b99cef80df8e5f6158fa7009b4956e))
* **code:** log underlying Auto classifier failures ([#5011](https://github.com/shantanusharma/deepagents/issues/5011)) ([bd03e8a](https://github.com/shantanusharma/deepagents/commit/bd03e8a1ca4b38883e11148d5614a444cdefa407))
* **code:** make `/goal` completion and grading reliable ([#4691](https://github.com/shantanusharma/deepagents/issues/4691)) ([9da63c6](https://github.com/shantanusharma/deepagents/commit/9da63c64a59503e3366e9bc7224cb1251af476be))
* **code:** make `/offload` interruptible ([#5590](https://github.com/shantanusharma/deepagents/issues/5590)) ([ab82d48](https://github.com/shantanusharma/deepagents/commit/ab82d48cc012c5a991660ad53785c2e26030596e))
* **code:** make `/timestamps` toggle instant via per-footer class ([#4095](https://github.com/shantanusharma/deepagents/issues/4095)) ([7ae32b0](https://github.com/shantanusharma/deepagents/commit/7ae32b0a606cc200d4311e11036a65f17e8282b3))
* **code:** make Auto mode generally available ([#4957](https://github.com/shantanusharma/deepagents/issues/4957)) ([1709dbf](https://github.com/shantanusharma/deepagents/commit/1709dbf9b27766aacce1a5a9c17396b3654f026c))
* **code:** make Auto mode resolve relative paths the same way the file tools do ([#7821](https://github.com/shantanusharma/deepagents/issues/7821)) ([ba1095e](https://github.com/shantanusharma/deepagents/commit/ba1095ee548d7a2ba9ed4100cdcfa6dc8cce8a50))
* **code:** make debug log path click-to-copy ([#5845](https://github.com/shantanusharma/deepagents/issues/5845)) ([1fc7d1e](https://github.com/shantanusharma/deepagents/commit/1fc7d1e26d21ff27327b1b0c0a926673c4663001))
* **code:** make execute command expandable in code TUI transcript ([#4428](https://github.com/shantanusharma/deepagents/issues/4428)) ([d999181](https://github.com/shantanusharma/deepagents/commit/d999181e8424498681f1e442c71380bf6b82b0aa))
* **code:** make markdown `AppMessage` output selectable ([#4814](https://github.com/shantanusharma/deepagents/issues/4814)) ([2d6b2ce](https://github.com/shantanusharma/deepagents/commit/2d6b2ceeda97f8c77d1b3ea70c674b076e7d713f))
* **code:** make non-incognito `!` shell output visible to the model ([#3825](https://github.com/shantanusharma/deepagents/issues/3825)) ([2407bca](https://github.com/shantanusharma/deepagents/commit/2407bca66bac5d199a923a0e58872c813eb006bc))
* **code:** make prompt clipboard Tab insert ([#5820](https://github.com/shantanusharma/deepagents/issues/5820)) ([8e03e9c](https://github.com/shantanusharma/deepagents/commit/8e03e9c37f80a348a14fb87ef875bc2f9b5b3ee9))
* **code:** make reject-with-feedback discoverable in approval menu ([#5260](https://github.com/shantanusharma/deepagents/issues/5260)) ([b1e3240](https://github.com/shantanusharma/deepagents/commit/b1e324038771c55460793e2e35d9d9ce5ea7b3f5))
* **code:** make tool arg validation errors recoverable ([#5659](https://github.com/shantanusharma/deepagents/issues/5659)) ([a7027ed](https://github.com/shantanusharma/deepagents/commit/a7027edc6449e9a7dbf0e082b8747d0999125ca2))
* **code:** make workspace configuration warnings actionable ([#6546](https://github.com/shantanusharma/deepagents/issues/6546)) ([05900e7](https://github.com/shantanusharma/deepagents/commit/05900e7ecc14ce64d9535617400a5e2f35d4c734))
* **code:** make YOLO warning friendlier for new users ([#4950](https://github.com/shantanusharma/deepagents/issues/4950)) ([fe07f39](https://github.com/shantanusharma/deepagents/commit/fe07f39ad78c5c09ea6959540a49196cd2f47f3e))
* **code:** match primary-input `Ctrl+D` behavior in inline free-text fields ([#4729](https://github.com/shantanusharma/deepagents/issues/4729)) ([8a6963b](https://github.com/shantanusharma/deepagents/commit/8a6963ba52eee2ab8de5df2c14210f472c828d38))
* **code:** mention `Ctrl+R` in MCP reconnect toast ([#3622](https://github.com/shantanusharma/deepagents/issues/3622)) ([3b4b086](https://github.com/shantanusharma/deepagents/commit/3b4b0867665e58959073e660d85b74c700acaa1e))
* **code:** move Auto mode path checks off the event loop ([#4856](https://github.com/shantanusharma/deepagents/issues/4856)) ([511203a](https://github.com/shantanusharma/deepagents/commit/511203a2c247f6756af3f06581ab9af761a4c4ef))
* **code:** move debug MCP server details into a modal ([#6720](https://github.com/shantanusharma/deepagents/issues/6720)) ([40df83f](https://github.com/shantanusharma/deepagents/commit/40df83ff74ddeba9c3e8575a2b8f228b3819a7be))
* **code:** move editable path to debug console ([#5850](https://github.com/shantanusharma/deepagents/issues/5850)) ([e85f4b7](https://github.com/shantanusharma/deepagents/commit/e85f4b7bd0acc696a3f29f5c298d3353d7d5495f))
* **code:** move MCP trust state out of user config ([#3742](https://github.com/shantanusharma/deepagents/issues/3742)) ([a97f2fd](https://github.com/shantanusharma/deepagents/commit/a97f2fd394e6b0b943225a0195b0901188bd368c))
* **code:** name models in classifier errors ([#6038](https://github.com/shantanusharma/deepagents/issues/6038)) ([fff2c77](https://github.com/shantanusharma/deepagents/commit/fff2c77c755c6d9dce3a6f776a9b94599ad05cfd))
* **code:** normalize empty file list tool output ([#3697](https://github.com/shantanusharma/deepagents/issues/3697)) ([b67aead](https://github.com/shantanusharma/deepagents/commit/b67aead2b86e04aaee8f2dbfba7b263e3e23597d))
* **code:** note subscription plans unusable for Anthropic in `/auth` ([#4207](https://github.com/shantanusharma/deepagents/issues/4207)) ([28cd19d](https://github.com/shantanusharma/deepagents/commit/28cd19db08bacf981ab2c91195638e66072816fe))
* **code:** offer cwd switch on resume ([#3810](https://github.com/shantanusharma/deepagents/issues/3810)) ([d417f53](https://github.com/shantanusharma/deepagents/commit/d417f530aafa8c77523487393dc3039cc822dc09))
* **code:** offer recovery for server startup timeouts ([#7610](https://github.com/shantanusharma/deepagents/issues/7610)) ([e3a7898](https://github.com/shantanusharma/deepagents/commit/e3a789816e2a38932360cae05ec53c133e79465e))
* **code:** offload `create_model` in server graph factory to unblock Codex ([#4324](https://github.com/shantanusharma/deepagents/issues/4324)) ([064ea0c](https://github.com/shantanusharma/deepagents/commit/064ea0c6851353d0b0bc347a0758149765688945))
* **code:** offload server config import ([#6089](https://github.com/shantanusharma/deepagents/issues/6089)) ([90fe4f4](https://github.com/shantanusharma/deepagents/commit/90fe4f4ac0a1311f1527b1a5cd02bd3ac8664580))
* **code:** offload server graph bootstrap cwd calls off the event loop ([#5081](https://github.com/shantanusharma/deepagents/issues/5081)) ([e05f7c2](https://github.com/shantanusharma/deepagents/commit/e05f7c2a825f3dc2fdfc075d4092b7b15d89b1a9))
* **code:** omit `plugins/` and `conversation_history/` from `/agent` picker ([#4991](https://github.com/shantanusharma/deepagents/issues/4991)) ([db26688](https://github.com/shantanusharma/deepagents/commit/db26688eee32232a1b73e98cc02642b5bf4165f4))
* **code:** omit unavailable web-search prompt guidance ([#5602](https://github.com/shantanusharma/deepagents/issues/5602)) ([9feaf51](https://github.com/shantanusharma/deepagents/commit/9feaf51030a30203f43231b7fb9420293be9fedc))
* **code:** only highlight actionable tool rows ([#5769](https://github.com/shantanusharma/deepagents/issues/5769)) ([b78413c](https://github.com/shantanusharma/deepagents/commit/b78413c708afae7fba806ae81336007d5d4c0c58))
* **code:** only open `http` and `https` links from the TUI ([#7277](https://github.com/shantanusharma/deepagents/issues/7277)) ([f40ecaf](https://github.com/shantanusharma/deepagents/commit/f40ecafeca78a8d461f163f9d30bbd83c61644b2))
* **code:** open `/auto model` selector immediately while connecting ([#5341](https://github.com/shantanusharma/deepagents/issues/5341)) ([72bfc1e](https://github.com/shantanusharma/deepagents/commit/72bfc1e68574909ceb929be869c66fbdc9fe5a1d))
* **code:** open debug console at log bottom ([#6218](https://github.com/shantanusharma/deepagents/issues/6218)) ([34f1b6b](https://github.com/shantanusharma/deepagents/commit/34f1b6b037b24a1f2fe8b1d6112d9f8cdfe32bf2))
* **code:** open the token and cost modal with `/cost` ([#7363](https://github.com/shantanusharma/deepagents/issues/7363)) ([d23799b](https://github.com/shantanusharma/deepagents/commit/d23799b0525796474c8e3d5546dc68b6a421e1b1))
* **code:** order debug console log filters ([#6217](https://github.com/shantanusharma/deepagents/issues/6217)) ([4bbad10](https://github.com/shantanusharma/deepagents/commit/4bbad10385b22cb76dc40aaa4709d4726f20db02))
* **code:** own sandbox lifetime from the client in non-interactive runs ([#6368](https://github.com/shantanusharma/deepagents/issues/6368)) ([4711bf2](https://github.com/shantanusharma/deepagents/commit/4711bf2fe0fc0c0f161db59f42a4708473b9769e))
* **code:** parse extra skill dirs with platform separator ([#6151](https://github.com/shantanusharma/deepagents/issues/6151)) ([56e4ef1](https://github.com/shantanusharma/deepagents/commit/56e4ef1a5f447950a04ba37a7855c8e0babd2f11))
* **code:** partition Debug Console log retention by level ([#4718](https://github.com/shantanusharma/deepagents/issues/4718)) ([c6e3b35](https://github.com/shantanusharma/deepagents/commit/c6e3b351f1826aa6ea97be244acd867950a032ee))
* **code:** pass through async subagent `webhook` configuration ([#7130](https://github.com/shantanusharma/deepagents/issues/7130)) ([6f6002c](https://github.com/shantanusharma/deepagents/commit/6f6002c08c4efa12b847ce319c36bd41df5f3b72))
* **code:** pause loading timer during approvals ([#3782](https://github.com/shantanusharma/deepagents/issues/3782)) ([f98fb0c](https://github.com/shantanusharma/deepagents/commit/f98fb0c80d08e408a018ea33a8aa7144180f4e93))
* **code:** persist `_context_tokens` via `after_model` middleware ([#3496](https://github.com/shantanusharma/deepagents/issues/3496)) ([e2bb284](https://github.com/shantanusharma/deepagents/commit/e2bb284e506e0e49a05169fc6de01bdf42350267))
* **code:** persist Auto approval mode between sessions ([#5665](https://github.com/shantanusharma/deepagents/issues/5665)) ([3ac059e](https://github.com/shantanusharma/deepagents/commit/3ac059e1574963fe216692642aa1b1a4044daaa9))
* **code:** persist resume model state privately ([#4400](https://github.com/shantanusharma/deepagents/issues/4400)) ([bbd0f0d](https://github.com/shantanusharma/deepagents/commit/bbd0f0d1ddc9d22d399a819d7b4363f7997d119e))
* **code:** persist rubric model after server restart ([#4419](https://github.com/shantanusharma/deepagents/issues/4419)) ([5605a68](https://github.com/shantanusharma/deepagents/commit/5605a681c9fec888d8c6dfbde2decd4692c8cef0))
* **code:** pin app version when installing extras ([#4313](https://github.com/shantanusharma/deepagents/issues/4313)) ([c20c8e2](https://github.com/shantanusharma/deepagents/commit/c20c8e2fc138f72f1444107d2a936305a591807b))
* **code:** pin filelock below 3.30 to avoid blocking import ([#4786](https://github.com/shantanusharma/deepagents/issues/4786)) ([f9b7d75](https://github.com/shantanusharma/deepagents/commit/f9b7d75f24301081ae8973cd59f00e609eb024c5))
* **code:** pin resumed history to newest message ([#6225](https://github.com/shantanusharma/deepagents/issues/6225)) ([9b5ca38](https://github.com/shantanusharma/deepagents/commit/9b5ca384ff727f16c4f66a13308170cfba899b97))
* **code:** pluralize singular MCP login splash text ([#3689](https://github.com/shantanusharma/deepagents/issues/3689)) ([492b0fc](https://github.com/shantanusharma/deepagents/commit/492b0fc9209e13cd7004a255ef67b31b7e78e95e))
* **code:** point MCP re-enable guidance at `Ctrl+R` ([#3688](https://github.com/shantanusharma/deepagents/issues/3688)) ([15ca302](https://github.com/shantanusharma/deepagents/commit/15ca3029f18fa38c1592859febc2a6d0469bff2d))
* **code:** point model switch warning to `/offload` ([#5901](https://github.com/shantanusharma/deepagents/issues/5901)) ([2f4d606](https://github.com/shantanusharma/deepagents/commit/2f4d606ee338720dd6ae6758761f08c3cb9c2350))
* **code:** point the ACP import error at a working upgrade command ([#7780](https://github.com/shantanusharma/deepagents/issues/7780)) ([d6a2dd1](https://github.com/shantanusharma/deepagents/commit/d6a2dd140d6359ec86bd572d5414da060f45f8d3))
* **code:** polish MCP auth success UX ([#3614](https://github.com/shantanusharma/deepagents/issues/3614)) ([d225cb4](https://github.com/shantanusharma/deepagents/commit/d225cb41f41a0a9b2876aff2443eaa0ada24bf29))
* **code:** preflight Ollama host reachability before discovery probe ([#4702](https://github.com/shantanusharma/deepagents/issues/4702)) ([96fe71a](https://github.com/shantanusharma/deepagents/commit/96fe71a3815e1020edeb3be1af70b0cadb85931c))
* **code:** preload auth UI before notification handoff ([#5697](https://github.com/shantanusharma/deepagents/issues/5697)) ([57c0678](https://github.com/shantanusharma/deepagents/commit/57c0678c4994b8b253c5f7edf11b7a558ece7df9))
* **code:** preserve `ask_user` consent receipts across user turns ([#6307](https://github.com/shantanusharma/deepagents/issues/6307)) ([ca00490](https://github.com/shantanusharma/deepagents/commit/ca004904d1e48385d805d6e3b7f62f82739cfc11))
* **code:** preserve `Ctrl+D` deletion in non-empty input ([#4626](https://github.com/shantanusharma/deepagents/issues/4626)) ([306bd89](https://github.com/shantanusharma/deepagents/commit/306bd893f214237b6b4eede7c2ce0eaff66f5527))
* **code:** preserve dispatch timers across interrupt replays ([#6722](https://github.com/shantanusharma/deepagents/issues/6722)) ([899a9f7](https://github.com/shantanusharma/deepagents/commit/899a9f79161ef9a19bc5a378cbd4215bb946f583))
* **code:** preserve editables during dependency refresh ([#5521](https://github.com/shantanusharma/deepagents/issues/5521)) ([f0446c8](https://github.com/shantanusharma/deepagents/commit/f0446c8c8aecff243545fe0c551a6539ccf482a2))
* **code:** preserve extras during install ([#3707](https://github.com/shantanusharma/deepagents/issues/3707)) ([e636ce9](https://github.com/shantanusharma/deepagents/commit/e636ce9e979fd1c30335ec340acdabbd0a5ae79e))
* **code:** preserve fork goal visibility without grading ([#6893](https://github.com/shantanusharma/deepagents/issues/6893)) ([f776228](https://github.com/shantanusharma/deepagents/commit/f7762288bc5b65d8820d386daf206103b1c01888))
* **code:** preserve goal notice history for prompt caching ([#5823](https://github.com/shantanusharma/deepagents/issues/5823)) ([aa8ae71](https://github.com/shantanusharma/deepagents/commit/aa8ae718644dac19d7f1cdc3febe2740a79fa058))
* **code:** preserve inherited `PYTHONPATH` for server subprocess ([#3833](https://github.com/shantanusharma/deepagents/issues/3833)) ([4689569](https://github.com/shantanusharma/deepagents/commit/4689569f94138987319cd9cbb45ce66a1f496934))
* **code:** preserve JavaScript subagent costs across resume ([#6433](https://github.com/shantanusharma/deepagents/issues/6433)) ([340a73c](https://github.com/shantanusharma/deepagents/commit/340a73c5b3a8d503bbdc7141d23b2523bbf715d3))
* **code:** preserve MCP token refresh when metadata discovery fails ([#3685](https://github.com/shantanusharma/deepagents/issues/3685)) ([afafeeb](https://github.com/shantanusharma/deepagents/commit/afafeeb471c4008d4eb4263ec478cf868833fe0b))
* **code:** preserve reasoning in remote message chunks ([#7341](https://github.com/shantanusharma/deepagents/issues/7341)) ([b26e78f](https://github.com/shantanusharma/deepagents/commit/b26e78f570ccf2b3d14296b265972055e42f702c))
* **code:** preserve remembered MCP approvals with env allowlist ([#4889](https://github.com/shantanusharma/deepagents/issues/4889)) ([b513bf3](https://github.com/shantanusharma/deepagents/commit/b513bf3b2aaa30738da9b9b0ced1c001efb1bd5a))
* **code:** preserve remote message completion markers ([#6831](https://github.com/shantanusharma/deepagents/issues/6831)) ([62b2692](https://github.com/shantanusharma/deepagents/commit/62b2692cb1b66430670053f02b7a7a821ad9afe7))
* **code:** preserve runtime offload archive routing ([#5328](https://github.com/shantanusharma/deepagents/issues/5328)) ([768b061](https://github.com/shantanusharma/deepagents/commit/768b061805f65a36c71a1ad8f6a41b4e67063e91))
* **code:** preserve shipped bytecode for read-only installs ([#7196](https://github.com/shantanusharma/deepagents/issues/7196)) ([76fe0cb](https://github.com/shantanusharma/deepagents/commit/76fe0cb47947906fdea632bff17f71082d4a342f))
* **code:** preserve transcript order during virtualization ([#4549](https://github.com/shantanusharma/deepagents/issues/4549)) ([f6ee70c](https://github.com/shantanusharma/deepagents/commit/f6ee70c00ac6ad7b1b180155018b794308a18361))
* **code:** preserve transcript position when opening pickers ([#6635](https://github.com/shantanusharma/deepagents/issues/6635)) ([8508cb9](https://github.com/shantanusharma/deepagents/commit/8508cb9329a92ccf93fbace8fa78670a39fc3371))
* **code:** preserve uv tool context when installing extras ([#4201](https://github.com/shantanusharma/deepagents/issues/4201)) ([fcc616c](https://github.com/shantanusharma/deepagents/commit/fcc616cf9bc2bbc7b2dc2574ae8649e2f270dc53))
* **code:** prevent `UnicodeEncodeError` crash in non-interactive mode on legacy Windows consoles ([#4478](https://github.com/shantanusharma/deepagents/issues/4478)) ([b1b16cd](https://github.com/shantanusharma/deepagents/commit/b1b16cd114d4ee4f077cf5824a0176cd94ebd851))
* **code:** prevent concurrent local thread writers ([#6717](https://github.com/shantanusharma/deepagents/issues/6717)) ([b0f9b41](https://github.com/shantanusharma/deepagents/commit/b0f9b41cad6089640ea479a3fbc255a1fb0171b6))
* **code:** prevent duplicate-id crash on MCP reconnect and clipboard `NoScreen` ([#3632](https://github.com/shantanusharma/deepagents/issues/3632)) ([6b9a3c0](https://github.com/shantanusharma/deepagents/commit/6b9a3c051586c26c542e958849e952d08a4b5a88))
* **code:** prevent failed exit setup from stranding the app ([#4913](https://github.com/shantanusharma/deepagents/issues/4913)) ([e4d69b0](https://github.com/shantanusharma/deepagents/commit/e4d69b04a84de226d26d9ca3adea96f1337eef04))
* **code:** prevent post-tool hook replay ([#5376](https://github.com/shantanusharma/deepagents/issues/5376)) ([d37b54f](https://github.com/shantanusharma/deepagents/commit/d37b54f6bfb03f41fc7ff6b05436ad49db688d19))
* **code:** preview remote plugin contents before installation ([#6542](https://github.com/shantanusharma/deepagents/issues/6542)) ([ec56c57](https://github.com/shantanusharma/deepagents/commit/ec56c57fb086dc5bee06547f9896e49a52ead3b3))
* **code:** price Fireworks GLM-5.3 Flash usage ([#6223](https://github.com/shantanusharma/deepagents/issues/6223)) ([d3627ea](https://github.com/shantanusharma/deepagents/commit/d3627eaaeda2de62c19b0647ac29f80767057241))
* **code:** price Fireworks GLM-5.3 usage ([#6221](https://github.com/shantanusharma/deepagents/issues/6221)) ([07c5d2e](https://github.com/shantanusharma/deepagents/commit/07c5d2ecfe5db6238eff782f714fbbe08865e8d4))
* **code:** price nested usage with its own model and honor completions ([#6251](https://github.com/shantanusharma/deepagents/issues/6251)) ([f413a40](https://github.com/shantanusharma/deepagents/commit/f413a40f7e74ada749b18491aa276ee1224c7368))
* **code:** probe unreachable Ollama daemon once per reload ([#4806](https://github.com/shantanusharma/deepagents/issues/4806)) ([45baf6c](https://github.com/shantanusharma/deepagents/commit/45baf6c7a47e08e656ba56eb76beea30a9956403))
* **code:** propagate runtime model switches to subagents ([#3771](https://github.com/shantanusharma/deepagents/issues/3771)) ([f577182](https://github.com/shantanusharma/deepagents/commit/f577182c84746e625b65c3c2fda95f8ca21164cf))
* **code:** protect TUI from native stderr writes ([#5813](https://github.com/shantanusharma/deepagents/issues/5813)) ([a4d9b8a](https://github.com/shantanusharma/deepagents/commit/a4d9b8aa7dfde39f37a4fa40aac8b149e2f66b00))
* **code:** put field descriptions on first-party tool schemas ([#5019](https://github.com/shantanusharma/deepagents/issues/5019)) ([4ccb873](https://github.com/shantanusharma/deepagents/commit/4ccb87325f3f97e416683233c94405e3ee105cda))
* **code:** put local offloaded tool results on the real filesystem ([#4740](https://github.com/shantanusharma/deepagents/issues/4740)) ([36051e2](https://github.com/shantanusharma/deepagents/commit/36051e2a6cdcd9c22f6118f5cfc481e0540913ea))
* **code:** queue `/copy` during active generation ([#5447](https://github.com/shantanusharma/deepagents/issues/5447)) ([8dfe282](https://github.com/shantanusharma/deepagents/commit/8dfe282006108dd0c47c50d5a1e3a41558e14723))
* **code:** queue `/mcp login` sent before the server connects ([#4533](https://github.com/shantanusharma/deepagents/issues/4533)) ([edac82c](https://github.com/shantanusharma/deepagents/commit/edac82c837de8e12b58b97ac25acc31f743d4c5d))
* **code:** quiet expected non-repo `git ls-files` logging ([#4701](https://github.com/shantanusharma/deepagents/issues/4701)) ([3d499db](https://github.com/shantanusharma/deepagents/commit/3d499db8a6c76743810a8983107d7c7d7bdb35e6))
* **code:** quiet MCP auth-skip debug logging for known patterns ([#4805](https://github.com/shantanusharma/deepagents/issues/4805)) ([c2c27d6](https://github.com/shantanusharma/deepagents/commit/c2c27d621b63d5af18870e034f99355dc410cbda))
* **code:** quiet routine ripgrep installer output ([#4417](https://github.com/shantanusharma/deepagents/issues/4417)) ([a52c18d](https://github.com/shantanusharma/deepagents/commit/a52c18d3ef8fe462d1289dca8798c51450e0368a))
* **code:** quiet uv installer output and require Xcode CLT on macOS ([#4180](https://github.com/shantanusharma/deepagents/issues/4180)) ([785c8d0](https://github.com/shantanusharma/deepagents/commit/785c8d0061114f8f3c457d4afc35a83bd405fc1b))
* **code:** quit with `Ctrl+D` at end of prompt ([#4678](https://github.com/shantanusharma/deepagents/issues/4678)) ([2f8c111](https://github.com/shantanusharma/deepagents/commit/2f8c11176f5cc9350c3337b2dfcf9f19886d5d02))
* **code:** ranked durable-mask config resolver ([#5672](https://github.com/shantanusharma/deepagents/issues/5672)) ([9f24b9f](https://github.com/shantanusharma/deepagents/commit/9f24b9fcaf7ed399b7888b2f0f9d13363939ea87))
* **code:** re-apply theme preference on `/reload` ([#4514](https://github.com/shantanusharma/deepagents/issues/4514)) ([5d1c392](https://github.com/shantanusharma/deepagents/commit/5d1c3928f7ca0ea97f28fd4d34ae1a4ee885e888))
* **code:** read `hooks.json` as UTF-8 in the legacy hook loader ([#6501](https://github.com/shantanusharma/deepagents/issues/6501)) ([61bada8](https://github.com/shantanusharma/deepagents/commit/61bada8bcbb62a40bfbe0345831228756f0ba353))
* **code:** read `LANGSMITH_PROJECT` for `tracing.langsmith_project` + show default ([#4054](https://github.com/shantanusharma/deepagents/issues/4054)) ([fec1551](https://github.com/shantanusharma/deepagents/commit/fec1551e901a4fe88bd74ee4833a91ef93b1e93f))
* **code:** read exposed PTC tools instead of the QuickJS prompt cache ([#7848](https://github.com/shantanusharma/deepagents/issues/7848)) ([a29e854](https://github.com/shantanusharma/deepagents/commit/a29e85409c9bea2650a822153c195d11118cbf4d))
* **code:** read the branch of reftable repositories through git ([#7268](https://github.com/shantanusharma/deepagents/issues/7268)) ([ca1b44e](https://github.com/shantanusharma/deepagents/commit/ca1b44e2ec16bf77082f12051d2fabe9da2850e5))
* **code:** reap langgraph dev server when startup is cancelled ([#4629](https://github.com/shantanusharma/deepagents/issues/4629)) ([904ff05](https://github.com/shantanusharma/deepagents/commit/904ff05620a576100e05fd65810d38405c4942d4))
* **code:** recognize in-flight trace messages ([#5738](https://github.com/shantanusharma/deepagents/issues/5738)) ([f1d1f63](https://github.com/shantanusharma/deepagents/commit/f1d1f632812a85646d25ac2f3d2d7f39b65a0b49))
* **code:** recommend GPT-6 Luna for auto review ([#6821](https://github.com/shantanusharma/deepagents/issues/6821)) ([26918db](https://github.com/shantanusharma/deepagents/commit/26918db7791f79ac91921e04eddf8774b3c4dfea))
* **code:** reconcile cache expiry during model requests ([#6763](https://github.com/shantanusharma/deepagents/issues/6763)) ([a282003](https://github.com/shantanusharma/deepagents/commit/a282003b502e5b7a97cee97b792efd1ec87e9972))
* **code:** reconcile coding-agent git trace attribution ([#7117](https://github.com/shantanusharma/deepagents/issues/7117)) ([aabaf95](https://github.com/shantanusharma/deepagents/commit/aabaf9509ab7f397c884813dba75187a74700951))
* **code:** reconcile interrupted tool requests ([#6321](https://github.com/shantanusharma/deepagents/issues/6321)) ([376e988](https://github.com/shantanusharma/deepagents/commit/376e988f98fea5e501050efe250d683259e551f5))
* **code:** reconstruct message counts for `DeltaChannel` threads from writes table ([#3668](https://github.com/shantanusharma/deepagents/issues/3668)) ([27e1940](https://github.com/shantanusharma/deepagents/commit/27e1940a924abfc999126cf46024003f453ba0c8))
* **code:** record Auto classifier deadline as a traced error ([#5944](https://github.com/shantanusharma/deepagents/issues/5944)) ([9a643c7](https://github.com/shantanusharma/deepagents/commit/9a643c75843a95d3ef770ac69dd1452435596efe))
* **code:** record shell output as user context ([#4353](https://github.com/shantanusharma/deepagents/issues/4353)) ([0d504a5](https://github.com/shantanusharma/deepagents/commit/0d504a5df8454e871597932ce1cd3e95b10ab00e))
* **code:** recover from tool errors instead of aborting run ([#3804](https://github.com/shantanusharma/deepagents/issues/3804)) ([45691c5](https://github.com/shantanusharma/deepagents/commit/45691c556105e171c7210c7c10388dc73202a025))
* **code:** recover initial session prompts from writes table ([#3535](https://github.com/shantanusharma/deepagents/issues/3535)) ([46b6f3f](https://github.com/shantanusharma/deepagents/commit/46b6f3f3e6ce880cd5ec9cf59622bb745d6ac2eb))
* **code:** recover stale pending work before compaction ([#5909](https://github.com/shantanusharma/deepagents/issues/5909)) ([213f0c8](https://github.com/shantanusharma/deepagents/commit/213f0c8a7dd01febff2a52c9ca0ea61b2cd8fd9d))
* **code:** redact LangSmith trace secrets by default ([#4356](https://github.com/shantanusharma/deepagents/issues/4356)) ([5e01fec](https://github.com/shantanusharma/deepagents/commit/5e01fec72d8b179a3b075b07268162d2eaebfe84))
* **code:** reduce OAuth login modal noise ([#3693](https://github.com/shantanusharma/deepagents/issues/3693)) ([0e8a780](https://github.com/shantanusharma/deepagents/commit/0e8a780e2dfea2e22ac44545a16279dbe30eb8ee))
* **code:** refocus `/mcp` filter input after in-place refresh ([#4080](https://github.com/shantanusharma/deepagents/issues/4080)) ([d79cd74](https://github.com/shantanusharma/deepagents/commit/d79cd74cb8a44c300c3bbad712fe77e709f9221a))
* **code:** refresh hooks after cwd switches ([#5249](https://github.com/shantanusharma/deepagents/issues/5249)) ([6f48dd5](https://github.com/shantanusharma/deepagents/commit/6f48dd59efd27c3476cf32cb8c965155c59993a5))
* **code:** refresh MCP OAuth tokens on restart ([#3509](https://github.com/shantanusharma/deepagents/issues/3509)) ([8919b3f](https://github.com/shantanusharma/deepagents/commit/8919b3f78c736108b5446b0ff8992a96d6965ac6))
* **code:** refresh splash version after update ([#5520](https://github.com/shantanusharma/deepagents/issues/5520)) ([c2ec5e6](https://github.com/shantanusharma/deepagents/commit/c2ec5e6d9f85bf114a3666bba982de0c63ec5eb5))
* **code:** refresh status bar model after recovering from failed startup ([#3511](https://github.com/shantanusharma/deepagents/issues/3511)) ([c96f822](https://github.com/shantanusharma/deepagents/commit/c96f822de187431404d093b852c4a855d3ab8d30))
* **code:** refresh subscription model lineup ([#7340](https://github.com/shantanusharma/deepagents/issues/7340)) ([c3d0080](https://github.com/shantanusharma/deepagents/commit/c3d00807e7c5386a6478d663dfd8be79443a2de7))
* **code:** refresh the agent skill catalog on `/reload` ([#6843](https://github.com/shantanusharma/deepagents/issues/6843)) ([d9594da](https://github.com/shantanusharma/deepagents/commit/d9594dae242546fcb7c1c9d23d1a731bf2a0ca20))
* **code:** refresh token and cost breakdown while open ([#6520](https://github.com/shantanusharma/deepagents/issues/6520)) ([22524ed](https://github.com/shantanusharma/deepagents/commit/22524edb7702d6fb31ffefd2d7d19549b17d2ed6))
* **code:** refuse a second sandbox workspace ([#5979](https://github.com/shantanusharma/deepagents/issues/5979)) ([cb4c973](https://github.com/shantanusharma/deepagents/commit/cb4c973172f7838eefa328ea0c6ca334b6aaab98))
* **code:** reject `--auto-approve` in headless mode ([#4617](https://github.com/shantanusharma/deepagents/issues/4617)) ([997be16](https://github.com/shantanusharma/deepagents/commit/997be1643aff6d6900b8b8c95832cdf93be8c0d7))
* **code:** reject stale successful updates ([#5847](https://github.com/shantanusharma/deepagents/issues/5847)) ([23976f4](https://github.com/shantanusharma/deepagents/commit/23976f414a928eb50d13d351bdc19971098ea7b9))
* **code:** release the turn when an interrupted worker never starts ([#5196](https://github.com/shantanusharma/deepagents/issues/5196)) ([42e01a9](https://github.com/shantanusharma/deepagents/commit/42e01a9585be8847aff6b97e520d7b84de922767))
* **code:** remove advanced config tip from empty MCP modal ([#7356](https://github.com/shantanusharma/deepagents/issues/7356)) ([f129ae4](https://github.com/shantanusharma/deepagents/commit/f129ae4703d4b01481cd2511b16aeddeda8ccb03))
* **code:** remove contradictory and invalid system-prompt instructions ([#6072](https://github.com/shantanusharma/deepagents/issues/6072)) ([2776a66](https://github.com/shantanusharma/deepagents/commit/2776a66a955976e4fffbf4cd8612828012feaebc))
* **code:** remove MCP OAuth success page message shift ([#4463](https://github.com/shantanusharma/deepagents/issues/4463)) ([69bb06c](https://github.com/shantanusharma/deepagents/commit/69bb06c0680fa6d37b917deb6b70927c3eff9c09))
* **code:** remove misleading agent names from help ([#4671](https://github.com/shantanusharma/deepagents/issues/4671)) ([ac15732](https://github.com/shantanusharma/deepagents/commit/ac1573281530c1564fe07f8a21608e4d4dec2c3b))
* **code:** remove notification settings expand flicker and trailing disclosure glyph ([#5734](https://github.com/shantanusharma/deepagents/issues/5734)) ([5397812](https://github.com/shantanusharma/deepagents/commit/5397812ad5f217cd84f871f121cf9ea8f3d63f4f))
* **code:** remove optional-provider startup tip ([#5421](https://github.com/shantanusharma/deepagents/issues/5421)) ([f137897](https://github.com/shantanusharma/deepagents/commit/f1378978e20f94762601ed38787a6fdb7fb39784))
* **code:** remove plugin type-to-search caret flash ([#5078](https://github.com/shantanusharma/deepagents/issues/5078)) ([7d69e37](https://github.com/shantanusharma/deepagents/commit/7d69e379678d8491ab62c9e229426d50b7366c45))
* **code:** remove review failure approval copy ([#5687](https://github.com/shantanusharma/deepagents/issues/5687)) ([b6a4146](https://github.com/shantanusharma/deepagents/commit/b6a41461d1834f673795e39a8928649de142d976))
* **code:** remove transient `Restarting server...` message after restart ([#4047](https://github.com/shantanusharma/deepagents/issues/4047)) ([87cc504](https://github.com/shantanusharma/deepagents/commit/87cc50428bc96ef11dfb11cee4020bff322a7216))
* **code:** remove undispatched `SessionEndCause` members ([#5240](https://github.com/shantanusharma/deepagents/issues/5240)) ([ee1e0f5](https://github.com/shantanusharma/deepagents/commit/ee1e0f50bfaff3690c6164147cdf22c94c289768))
* **code:** rename `ls_agent_kind` to `ls_agent_purpose` ([#4708](https://github.com/shantanusharma/deepagents/issues/4708)) ([2678b16](https://github.com/shantanusharma/deepagents/commit/2678b1680d8928e72e8efae00632a694c9b2737a))
* **code:** rename OpenAI subscription login label ([#5680](https://github.com/shantanusharma/deepagents/issues/5680)) ([14b09aa](https://github.com/shantanusharma/deepagents/commit/14b09aa18567de9325bbf7fa083fe339c90fce0e))
* **code:** rename stale usage commands ([#3460](https://github.com/shantanusharma/deepagents/issues/3460)) ([da43b7f](https://github.com/shantanusharma/deepagents/commit/da43b7f9d913e6190ff03c496a269faf08bbf182))
* **code:** render first streamed text immediately ([#5761](https://github.com/shantanusharma/deepagents/issues/5761)) ([19de73d](https://github.com/shantanusharma/deepagents/commit/19de73de163d2ca907fa4d9a44f2e19af635aa39))
* **code:** render MCP tool errors and drop empty-string optional params ([#3624](https://github.com/shantanusharma/deepagents/issues/3624)) ([fdf3db4](https://github.com/shantanusharma/deepagents/commit/fdf3db464cd9f3de4e84c246547dd2971d26c726))
* **code:** render thread timestamps without the glibc-only `%-I` strftime flag ([#5886](https://github.com/shantanusharma/deepagents/issues/5886)) ([ef6b5be](https://github.com/shantanusharma/deepagents/commit/ef6b5beec93bdcbb38ea44f157a029bc07b8b5ee))
* **code:** repair MCP OAuth login redirect and stale client registration ([#3692](https://github.com/shantanusharma/deepagents/issues/3692)) ([f741293](https://github.com/shantanusharma/deepagents/commit/f741293524f7d47eb8a16a3cd4def336c3c3c13f))
* **code:** replace chat input when recalling a prompt ([#6994](https://github.com/shantanusharma/deepagents/issues/6994)) ([ba72013](https://github.com/shantanusharma/deepagents/commit/ba72013ff06cfb9d41670e7dc37c219b9f5cc7c0))
* **code:** replace composer with prompt search and prevent query feedback ([#6346](https://github.com/shantanusharma/deepagents/issues/6346)) ([a52ecea](https://github.com/shantanusharma/deepagents/commit/a52ecea1f4b159a5ec0c667c6d05e26ea701db30))
* **code:** replace repeated thread resume errors ([#6990](https://github.com/shantanusharma/deepagents/issues/6990)) ([fd3e64a](https://github.com/shantanusharma/deepagents/commit/fd3e64ab6b605450bed5a2c22ef2ec84cd40542e))
* **code:** replace unencodable characters in redirected output ([#7717](https://github.com/shantanusharma/deepagents/issues/7717)) ([a9ccfb7](https://github.com/shantanusharma/deepagents/commit/a9ccfb778876fc5c1190227889c7b26e271cb415))
* **code:** report a mis-encoded `config.toml` from the older config writers ([#6514](https://github.com/shantanusharma/deepagents/issues/6514)) ([a6e2140](https://github.com/shantanusharma/deepagents/commit/a6e21408ccc1b9a80f941d3458a0ae58dcc29abe))
* **code:** report Auto classifier timeout budget ([#5025](https://github.com/shantanusharma/deepagents/issues/5025)) ([516619b](https://github.com/shantanusharma/deepagents/commit/516619b7bf516e56f0e56ebc319dcab928c68c40))
* **code:** report editable SDK runtime version ([#4304](https://github.com/shantanusharma/deepagents/issues/4304)) ([4439e91](https://github.com/shantanusharma/deepagents/commit/4439e912da4bfa6f1e38e14b5a03d2bfe9367d3b))
* **code:** report MCP server changes on reload ([#5504](https://github.com/shantanusharma/deepagents/issues/5504)) ([b16a740](https://github.com/shantanusharma/deepagents/commit/b16a74085af0057a24ce00f23a6a165bf5f21ed2))
* **code:** report same-version dependency updates ([#4146](https://github.com/shantanusharma/deepagents/issues/4146)) ([156e118](https://github.com/shantanusharma/deepagents/commit/156e1185242a19746f8c268904637c73f07b9a10))
* **code:** report total context after `/offload` ([#5488](https://github.com/shantanusharma/deepagents/issues/5488)) ([5d806c8](https://github.com/shantanusharma/deepagents/commit/5d806c88cf2a8b10d9b13b832540151491c13e19))
* **code:** report workspace refusals accurately during resume ([#6992](https://github.com/shantanusharma/deepagents/issues/6992)) ([0dfa1f6](https://github.com/shantanusharma/deepagents/commit/0dfa1f6047006687b825d7909f9a3a890934057b))
* **code:** require `AGENTS.md` marker for `/agent` discovery ([#5076](https://github.com/shantanusharma/deepagents/issues/5076)) ([aff1435](https://github.com/shantanusharma/deepagents/commit/aff1435ce8d56c623cfeffb2731adcd4bf057c30)), refs [#4991](https://github.com/shantanusharma/deepagents/issues/4991)
* **code:** rescaffold server workspace on `/restart` when config is missing ([#4050](https://github.com/shantanusharma/deepagents/issues/4050)) ([de51b0e](https://github.com/shantanusharma/deepagents/commit/de51b0e082293f5f795d96d3bf717c82efb9337e))
* **code:** resolve `/threads` header link on mount, not after load ([#4453](https://github.com/shantanusharma/deepagents/issues/4453)) ([4cba728](https://github.com/shantanusharma/deepagents/commit/4cba72893fc4aae5b429d8c573c1a513d97ddf8a))
* **code:** resolve editable SDK version metadata ([#4394](https://github.com/shantanusharma/deepagents/issues/4394)) ([3239bf4](https://github.com/shantanusharma/deepagents/commit/3239bf4edf2be3037bb18315463ac6a0c3537e5c))
* **code:** resolve interactive model metadata on the server ([#6772](https://github.com/shantanusharma/deepagents/issues/6772)) ([3d16423](https://github.com/shantanusharma/deepagents/commit/3d16423afbcbb11ea428265c91c203235c2e82b2))
* **code:** resolve interpreter PTC allowlist against the runtime tool registry ([#3845](https://github.com/shantanusharma/deepagents/issues/3845)) ([c59a27e](https://github.com/shantanusharma/deepagents/commit/c59a27ef2405b8e04c4351ce7ffa53d8d16d519c))
* **code:** resolve message pointer shapes per cell ([#5592](https://github.com/shantanusharma/deepagents/issues/5592)) ([cd4c399](https://github.com/shantanusharma/deepagents/commit/cd4c3993faf9aabfc6bb6c22bb56a57c33563106))
* **code:** resolve origin from worktree common Git dir ([#5818](https://github.com/shantanusharma/deepagents/issues/5818)) ([a8ae714](https://github.com/shantanusharma/deepagents/commit/a8ae71480f767aac0f0f7cf754ec49e6fd9bf826))
* **code:** resolve plugin MCP servers for login ([#6524](https://github.com/shantanusharma/deepagents/issues/6524)) ([ae00358](https://github.com/shantanusharma/deepagents/commit/ae00358ed85fb2207cb3ef260d5181a601b5b585))
* **code:** resolve project policy per workspace ([#6064](https://github.com/shantanusharma/deepagents/issues/6064)) ([ea1f253](https://github.com/shantanusharma/deepagents/commit/ea1f2536537efb01c71dce54c46894b9318c4f80))
* **code:** resolve summarization cutoff by message id ([#7570](https://github.com/shantanusharma/deepagents/issues/7570)) ([93e10b3](https://github.com/shantanusharma/deepagents/commit/93e10b3c5f44ff5a5c4ca93ca3ff90c588670b38))
* **code:** resolve underspecified goal objectives from conversation context ([#5201](https://github.com/shantanusharma/deepagents/issues/5201)) ([8fdb9c3](https://github.com/shantanusharma/deepagents/commit/8fdb9c306fd9a5b5368eb065b100cbfe8c8cbc58))
* **code:** respect ASCII mode in splash border ([#5923](https://github.com/shantanusharma/deepagents/issues/5923)) ([437c2db](https://github.com/shantanusharma/deepagents/commit/437c2dbbe287c6b37a4fe7466b5f9d5305163d85))
* **code:** respect line width in tool output previews ([#3646](https://github.com/shantanusharma/deepagents/issues/3646)) ([ba1ad2d](https://github.com/shantanusharma/deepagents/commit/ba1ad2dbabd19b3821490537465a3bcd39c6fed6))
* **code:** restore `"Server log preserved at:"` notice on exit ([#4999](https://github.com/shantanusharma/deepagents/issues/4999)) ([5bc7714](https://github.com/shantanusharma/deepagents/commit/5bc7714fe55a73ac4892deb1785522ea310607ce))
* **code:** restore caller's LangSmith API key in shell subprocess env ([#4458](https://github.com/shantanusharma/deepagents/issues/4458)) ([9293b19](https://github.com/shantanusharma/deepagents/commit/9293b190170a872b73d0d94e66479bcc5f7962c7))
* **code:** restore console input after piped prompts on Windows ([#6572](https://github.com/shantanusharma/deepagents/issues/6572)) ([f2a98d2](https://github.com/shantanusharma/deepagents/commit/f2a98d2bb409496f9a49f59e883fc63dd082fca1))
* **code:** restore edit diffs in resumed threads ([#5391](https://github.com/shantanusharma/deepagents/issues/5391)) ([6a5d93f](https://github.com/shantanusharma/deepagents/commit/6a5d93f9ba7391189f65e6b999b724253577085d))
* **code:** restore marketplace details keyboard focus [closes DCD-50] ([#4763](https://github.com/shantanusharma/deepagents/issues/4763)) ([e821d3d](https://github.com/shantanusharma/deepagents/commit/e821d3dd26e8cd0c6ada1a44ceaceddad9f5ee80))
* **code:** restore resumed thread model ([#3651](https://github.com/shantanusharma/deepagents/issues/3651)) ([550a8ab](https://github.com/shantanusharma/deepagents/commit/550a8abf3c595d738162a97f694b5d9527613323))
* **code:** restore welcome banner tips ([#4528](https://github.com/shantanusharma/deepagents/issues/4528)) ([3f1e55e](https://github.com/shantanusharma/deepagents/commit/3f1e55eafbc1fde79cb75f631561cf35d4b8ff4c))
* **code:** restrict auto classifier IDs to the review batch enum ([#6250](https://github.com/shantanusharma/deepagents/issues/6250)) ([6152733](https://github.com/shantanusharma/deepagents/commit/6152733cbd6b73709a704f3f41b93e2576c5cd52))
* **code:** resume hints echo the launched command name ([#5119](https://github.com/shantanusharma/deepagents/issues/5119)) ([991b7e7](https://github.com/shantanusharma/deepagents/commit/991b7e769d8afa98edc8dac1c68994ca4dc765d2))
* **code:** retry bare `openai.APIError` raised mid-stream ([#6499](https://github.com/shantanusharma/deepagents/issues/6499)) ([0f95915](https://github.com/shantanusharma/deepagents/commit/0f959156b828f9deb08438b71dbc9a65c13b1714))
* **code:** retry interrupted model streams ([#5905](https://github.com/shantanusharma/deepagents/issues/5905)) ([dfcd941](https://github.com/shantanusharma/deepagents/commit/dfcd9417a88c774a232de33e41bb0e69d76ec7ce))
* **code:** reuse fresh known updates in explicit update ([#7355](https://github.com/shantanusharma/deepagents/issues/7355)) ([6d4ce0a](https://github.com/shantanusharma/deepagents/commit/6d4ce0af4b46630853423a214459a1a5da846c03))
* **code:** reuse persisted DCR loopback port across OAuth launches ([#3613](https://github.com/shantanusharma/deepagents/issues/3613)) ([f2f7471](https://github.com/shantanusharma/deepagents/commit/f2f747104945ac79b68e6524d6da886f7cfeb1b0))
* **code:** route `ctrl+x` to focused `ask_user` input ([#4926](https://github.com/shantanusharma/deepagents/issues/4926)) ([005f9bb](https://github.com/shantanusharma/deepagents/commit/005f9bb4d790e6cd92be8712ec86cd45192b699f))
* **code:** route Anthropic effort through output config ([#4446](https://github.com/shantanusharma/deepagents/issues/4446)) ([1e8ed81](https://github.com/shantanusharma/deepagents/commit/1e8ed81940a862dde44f704826b61650336367e0))
* **code:** route explicit `--stdin` + `--skill` to headless path ([#4611](https://github.com/shantanusharma/deepagents/issues/4611)) ([724e24a](https://github.com/shantanusharma/deepagents/commit/724e24a31546e1f31feca3bb2344717550682595))
* **code:** route failures to `PostToolUseFailure` ([#5315](https://github.com/shantanusharma/deepagents/issues/5315)) ([c1f4ac3](https://github.com/shantanusharma/deepagents/commit/c1f4ac3d53b3231d80be97691763850d230e8080))
* **code:** run `/offload` server-side ([#4696](https://github.com/shantanusharma/deepagents/issues/4696)) ([564e5a0](https://github.com/shantanusharma/deepagents/commit/564e5a05bca5236ae33ce1147865111f931d257c))
* **code:** run auto-update before startup ([#3784](https://github.com/shantanusharma/deepagents/issues/3784)) ([c160ea3](https://github.com/shantanusharma/deepagents/commit/c160ea3eeda1d0ba707bb524cfd0ce087a854e08))
* **code:** run MCP login during a run, queue the restart ([#4643](https://github.com/shantanusharma/deepagents/issues/4643)) ([65e1ee8](https://github.com/shantanusharma/deepagents/commit/65e1ee802e2f69762a6d8e6c7c6d37060161ea5a))
* **code:** run sandbox creation and entry off the guarded event loop ([#6017](https://github.com/shantanusharma/deepagents/issues/6017)) ([fd28bfb](https://github.com/shantanusharma/deepagents/commit/fd28bfb5c5e1ca18af975d8e57d361c1c23f81b7))
* **code:** run stdio MCP server pre-flight check off the event loop ([#4434](https://github.com/shantanusharma/deepagents/issues/4434)) ([c9636e2](https://github.com/shantanusharma/deepagents/commit/c9636e22725a5bd32c1f8b9e739b02b4aa7c3dc7))
* **code:** say which source path a plugin install rejected ([#5960](https://github.com/shantanusharma/deepagents/issues/5960)) ([6f8c488](https://github.com/shantanusharma/deepagents/commit/6f8c48800b02397fd262bfd9caea5096984d4220))
* **code:** scope `@` file completion to current cwd ([#3874](https://github.com/shantanusharma/deepagents/issues/3874)) ([dd237ac](https://github.com/shantanusharma/deepagents/commit/dd237acd21a39e98e37bb9d98dfae09bc44d5457))
* **code:** scope project dotenv to workspaces ([#5980](https://github.com/shantanusharma/deepagents/issues/5980)) ([678c115](https://github.com/shantanusharma/deepagents/commit/678c11559d7534ee5e16ceebfacf01eeb6536ac7))
* **code:** scope selection copy to the clicked screen ([#5140](https://github.com/shantanusharma/deepagents/issues/5140)) ([4de6037](https://github.com/shantanusharma/deepagents/commit/4de6037cbe31de005a493eaa719f5269f29be764))
* **code:** scroll overflowing chat input pastes ([#6382](https://github.com/shantanusharma/deepagents/issues/6382)) ([b522fd4](https://github.com/shantanusharma/deepagents/commit/b522fd4a74b2349b25f3f1f630265f7e456430ee))
* **code:** scroll resumed threads to the bottom ([#5543](https://github.com/shantanusharma/deepagents/issues/5543)) ([1c6d358](https://github.com/shantanusharma/deepagents/commit/1c6d358c60306aad2af0067dcca76f85f4deeba1))
* **code:** search all models from `/model` filter ([#3690](https://github.com/shantanusharma/deepagents/issues/3690)) ([5fcb877](https://github.com/shantanusharma/deepagents/commit/5fcb877d094c4504f671bb7aeb52efa7bf3a5b48))
* **code:** separate access-policy compatibility from runtime identity ([#6386](https://github.com/shantanusharma/deepagents/issues/6386)) ([95c7630](https://github.com/shantanusharma/deepagents/commit/95c763059fdec12991232fc63418755ba568af74))
* **code:** separate YOLO exit hint ([#5688](https://github.com/shantanusharma/deepagents/issues/5688)) ([5d604ee](https://github.com/shantanusharma/deepagents/commit/5d604eed6d7ff567bb6c2c3046e385fc8d987698))
* **code:** serialize `QueuedUserMessage` as user input ([#3708](https://github.com/shantanusharma/deepagents/issues/3708)) ([307d598](https://github.com/shantanusharma/deepagents/commit/307d59826da9b1ddcbcdab8dccef6d18ecf16d10))
* **code:** serialize cold SDK imports ([#3712](https://github.com/shantanusharma/deepagents/issues/3712)) ([fb2adc0](https://github.com/shantanusharma/deepagents/commit/fb2adc0585e978b12646602ba922e252abf41f81))
* **code:** serialize dcode self-upgrades across processes ([#5252](https://github.com/shantanusharma/deepagents/issues/5252)) ([e12acba](https://github.com/shantanusharma/deepagents/commit/e12acbac89e553048b03fb6132b53e61b3433271))
* **code:** serialize MCP OAuth token refreshes to prevent reuse revocation ([#4565](https://github.com/shantanusharma/deepagents/issues/4565)) ([c37100d](https://github.com/shantanusharma/deepagents/commit/c37100d4763e527fce12fa4451794ca25ded7640))
* **code:** serialize transcript tail reconciliation ([#6143](https://github.com/shantanusharma/deepagents/issues/6143)) ([5fb8b69](https://github.com/shantanusharma/deepagents/commit/5fb8b699843ecf93debc592d9dbb8a534f54db09))
* **code:** set dcode agent names in trace metadata ([#3901](https://github.com/shantanusharma/deepagents/issues/3901)) ([ac94dd6](https://github.com/shantanusharma/deepagents/commit/ac94dd6b139211187cad8685c1152f02c51ba086))
* **code:** share cache-expiring notifications with the TUI ([#6639](https://github.com/shantanusharma/deepagents/issues/6639)) ([e1940f5](https://github.com/shantanusharma/deepagents/commit/e1940f5f86ed37f4a19a970707aab61343e07e2a))
* **code:** share defaults between runtime and CLI help ([#6613](https://github.com/shantanusharma/deepagents/issues/6613)) ([e672a05](https://github.com/shantanusharma/deepagents/commit/e672a05872dcd930cbb7f5d46d7e8fee70449338))
* **code:** share MCP approvals across Git worktrees ([#4939](https://github.com/shantanusharma/deepagents/issues/4939)) ([467f9dd](https://github.com/shantanusharma/deepagents/commit/467f9dd0400087c2918bcf19f270bd934cec623a))
* **code:** share OpenAI `prompt_cache_key` across threads of an install ([#7839](https://github.com/shantanusharma/deepagents/issues/7839)) ([3eae64b](https://github.com/shantanusharma/deepagents/commit/3eae64b57fe6642399fd09804ae27f23b4e8b1a9))
* **code:** share paste handling with inline free-text prompts ([#4736](https://github.com/shantanusharma/deepagents/issues/4736)) ([369ec69](https://github.com/shantanusharma/deepagents/commit/369ec6920af35cdec713b9e27d0d1816cafaf556))
* **code:** shorten Auto classifier selection message ([#5446](https://github.com/shantanusharma/deepagents/issues/5446)) ([c43919c](https://github.com/shantanusharma/deepagents/commit/c43919c5c05643d03cf00009339cd0e4d3c17d6d))
* **code:** show "Loading..." in `/threads` agent dropdown while loading ([#4101](https://github.com/shantanusharma/deepagents/issues/4101)) ([c2d949e](https://github.com/shantanusharma/deepagents/commit/c2d949e8765fbbbdb81e5a70125932842358099f))
* **code:** show "Took &lt;duration&gt;" when `task` tool completes ([#4638](https://github.com/shantanusharma/deepagents/issues/4638)) ([19538e0](https://github.com/shantanusharma/deepagents/commit/19538e0a46a5c2c050412b79fd45608a63cdde52))
* **code:** show `-m` prompt as queued immediately on startup ([#4861](https://github.com/shantanusharma/deepagents/issues/4861)) ([d0e148a](https://github.com/shantanusharma/deepagents/commit/d0e148a72612137fc7bc1e49a8972643e0ca2c28))
* **code:** show `(local)` tag under ANSI themes ([#4534](https://github.com/shantanusharma/deepagents/issues/4534)) ([699e439](https://github.com/shantanusharma/deepagents/commit/699e439699723e477a621f95eef87a7d76aac5f5))
* **code:** show `/restart` feedback ([#3808](https://github.com/shantanusharma/deepagents/issues/3808)) ([c40bef9](https://github.com/shantanusharma/deepagents/commit/c40bef9b2aaace3909593503b28e8b548bc20014))
* **code:** show 100 recent threads by default ([#6604](https://github.com/shantanusharma/deepagents/issues/6604)) ([f0863be](https://github.com/shantanusharma/deepagents/commit/f0863be6661e5746edb4d7d9b0f7ed170bbc7a2d))
* **code:** show and handle escape during MCP browser login ([#6541](https://github.com/shantanusharma/deepagents/issues/6541)) ([0a1967e](https://github.com/shantanusharma/deepagents/commit/0a1967e94c4bce9cb4a28b8368510f3392e9e52b))
* **code:** show Auto enable notice modal only on first global enable ([#5012](https://github.com/shantanusharma/deepagents/issues/5012)) ([c2dbd17](https://github.com/shantanusharma/deepagents/commit/c2dbd176f06ff1a29637107101ae61344a09fc59))
* **code:** show Auto first-enable notice as pre-confirmation ([#5686](https://github.com/shantanusharma/deepagents/issues/5686)) ([32f565f](https://github.com/shantanusharma/deepagents/commit/32f565f46519d9c35919640bdf9374506d0572d2))
* **code:** show bound workspace in shell approvals ([#5966](https://github.com/shantanusharma/deepagents/issues/5966)) ([716ab9f](https://github.com/shantanusharma/deepagents/commit/716ab9fb9c1f27d912aac89a663a75c4861418a5))
* **code:** show contextual auth footer actions ([#5690](https://github.com/shantanusharma/deepagents/issues/5690)) ([074a501](https://github.com/shantanusharma/deepagents/commit/074a5019e1f3edfd589614774958400d051e5fe1))
* **code:** show editable install status in debug version ([#6797](https://github.com/shantanusharma/deepagents/issues/6797)) ([cc1be0d](https://github.com/shantanusharma/deepagents/commit/cc1be0d17d1a0eee6bd95e39b6261e7cd0510148))
* **code:** show incognito label on chat input border ([#6627](https://github.com/shantanusharma/deepagents/issues/6627)) ([a99ab3e](https://github.com/shantanusharma/deepagents/commit/a99ab3e9997e80261a58c86a6c4a3de7a444e731))
* **code:** show incognito shell command widget ([#5768](https://github.com/shantanusharma/deepagents/issues/5768)) ([9bef676](https://github.com/shantanusharma/deepagents/commit/9bef676fe69a3b79c0702fda59b555d1ef6ad3bc))
* **code:** show loading labels for thread details ([#6430](https://github.com/shantanusharma/deepagents/issues/6430)) ([5c09b92](https://github.com/shantanusharma/deepagents/commit/5c09b9291924df7f67fbc73fda2214a0a50005ea))
* **code:** show loading state during model switch ([#4209](https://github.com/shantanusharma/deepagents/issues/4209)) ([7cc4e9f](https://github.com/shantanusharma/deepagents/commit/7cc4e9f9bda5a8ae42bb072b82b634ad8c39ade1))
* **code:** show months instead of "0y ago" for 360-364 day old timestamps ([#4267](https://github.com/shantanusharma/deepagents/issues/4267)) ([820b331](https://github.com/shantanusharma/deepagents/commit/820b331552cb7ce4695ddca3c9b8343a3144392b))
* **code:** show resume hint after crashes ([#5412](https://github.com/shantanusharma/deepagents/issues/5412)) ([015a019](https://github.com/shantanusharma/deepagents/commit/015a0197f588e34475db63c2a03f04987583b081))
* **code:** show rubric grader defaults ([#4966](https://github.com/shantanusharma/deepagents/issues/4966)) ([465b9de](https://github.com/shantanusharma/deepagents/commit/465b9de17f9f4e6cd07a8674d9a186e60f5bf4d4))
* **code:** show session cost warnings in a modal ([#6393](https://github.com/shantanusharma/deepagents/issues/6393)) ([c1395da](https://github.com/shantanusharma/deepagents/commit/c1395dab009690a30d495bfcae33fb92f62d08c4))
* **code:** show the spinner during pre-stream turn setup ([#6253](https://github.com/shantanusharma/deepagents/issues/6253)) ([fa609c2](https://github.com/shantanusharma/deepagents/commit/fa609c23ba883557d015529d431ae266847e388c))
* **code:** show tool call previews during batched HITL approvals ([#3530](https://github.com/shantanusharma/deepagents/issues/3530)) ([84daa1a](https://github.com/shantanusharma/deepagents/commit/84daa1a2e27963a6d7694dc9278de83782b4a7b7))
* **code:** silence absent themes config warning ([#6220](https://github.com/shantanusharma/deepagents/issues/6220)) ([b93f748](https://github.com/shantanusharma/deepagents/commit/b93f7483bb5722bbae281a19a80a7aea21d38832))
* **code:** silence no-op automatic cache offloads ([#7078](https://github.com/shantanusharma/deepagents/issues/7078)) ([215392a](https://github.com/shantanusharma/deepagents/commit/215392aa3dfa08d21bc30a696b2347dcfbd44ebf))
* **code:** silence non-media path decoder traces ([#6427](https://github.com/shantanusharma/deepagents/issues/6427)) ([3693e9d](https://github.com/shantanusharma/deepagents/commit/3693e9d01a94a4e881cbb5f92438adfec27cd77e))
* **code:** simplify Auto fallback copy ([#5670](https://github.com/shantanusharma/deepagents/issues/5670)) ([42afcde](https://github.com/shantanusharma/deepagents/commit/42afcded97029070f393232778c84aaf3b69fb1c))
* **code:** simplify classifier notice copy ([#5691](https://github.com/shantanusharma/deepagents/issues/5691)) ([c23c960](https://github.com/shantanusharma/deepagents/commit/c23c960459e931631842f1a7214b98a2d383f72a))
* **code:** simplify empty `/tokens` message ([#5693](https://github.com/shantanusharma/deepagents/issues/5693)) ([8a4fc3a](https://github.com/shantanusharma/deepagents/commit/8a4fc3a3104ab5131bedec0ca1f76289285d5efa))
* **code:** simplify paste expansion toast ([#5443](https://github.com/shantanusharma/deepagents/issues/5443)) ([217b9eb](https://github.com/shantanusharma/deepagents/commit/217b9eb372fa51b0439434f31abc3ac22e6cd7f2))
* **code:** size compaction input budget against selected model ([#7545](https://github.com/shantanusharma/deepagents/issues/7545)) ([89c8634](https://github.com/shantanusharma/deepagents/commit/89c86340c78d06d932c95df4f70259d8ca8dbca6))
* **code:** skip a subagent `AGENTS.md` that is not UTF-8 instead of failing startup ([#7361](https://github.com/shantanusharma/deepagents/issues/7361)) ([4934d74](https://github.com/shantanusharma/deepagents/commit/4934d74e427cb5fc141229cc90f2a8895e24cb7e))
* **code:** skip background sync in Apple Terminal ([#5666](https://github.com/shantanusharma/deepagents/issues/5666)) ([a2782ff](https://github.com/shantanusharma/deepagents/commit/a2782ff36efd5e9c9ebd9abb17b6fb51a2f01e8b))
* **code:** skip Esc prompt-restore once output generation begins ([#4582](https://github.com/shantanusharma/deepagents/issues/4582)) ([14f384f](https://github.com/shantanusharma/deepagents/commit/14f384fc0083c07a7f44f97543b40b74cf93c13f))
* **code:** skip grading during `/goal` proposals ([#4941](https://github.com/shantanusharma/deepagents/issues/4941)) ([d1ce66e](https://github.com/shantanusharma/deepagents/commit/d1ce66ea03e3726e6077c6700fc480209a849a7e))
* **code:** skip startup auto-update when already updated in-session ([#3915](https://github.com/shantanusharma/deepagents/issues/3915)) ([3ba3471](https://github.com/shantanusharma/deepagents/commit/3ba347138ac61a474bad58365fdeaa0d00cc1a42))
* **code:** skip tool interrupts once auto-approve is set ([#4092](https://github.com/shantanusharma/deepagents/issues/4092)) ([9e21c34](https://github.com/shantanusharma/deepagents/commit/9e21c346a6eb8ad25b9cc671f24527b07732e2b7))
* **code:** skip unchanged config writes ([#5919](https://github.com/shantanusharma/deepagents/issues/5919)) ([c313ff0](https://github.com/shantanusharma/deepagents/commit/c313ff0e6b3549d9f959578ae177291d8c8f13a3))
* **code:** skip uncorrelated-result warning for auto-mode policy denials ([#5869](https://github.com/shantanusharma/deepagents/issues/5869)) ([35fd008](https://github.com/shantanusharma/deepagents/commit/35fd00833a03e9e76858195aae8b13e7753cfa47))
* **code:** skip update prompts for editable installs ([#3781](https://github.com/shantanusharma/deepagents/issues/3781)) ([ae2874e](https://github.com/shantanusharma/deepagents/commit/ae2874e8ece96c04233c1a88a9da1bd7b9ee2bb2))
* **code:** speed up thread-switch preflight and show progress early ([#6607](https://github.com/shantanusharma/deepagents/issues/6607)) ([ded8cbf](https://github.com/shantanusharma/deepagents/commit/ded8cbfd90fea8cb47dcb52fc369b83a77089d67))
* **code:** stabilize hook resumes across identity and Command tool results ([#5176](https://github.com/shantanusharma/deepagents/issues/5176)) ([08e6e8b](https://github.com/shantanusharma/deepagents/commit/08e6e8ba8d8ea629d78976542a061a2acab1fa9c))
* **code:** standardize modal navigation hints ([#5699](https://github.com/shantanusharma/deepagents/issues/5699)) ([85c6833](https://github.com/shantanusharma/deepagents/commit/85c6833734a547e968221c1199a769d7aac69430))
* **code:** standardize recent-thread environment variable ([#6205](https://github.com/shantanusharma/deepagents/issues/6205)) ([a4c218e](https://github.com/shantanusharma/deepagents/commit/a4c218e185bc49a11a381c3afde91f6efa7226fc))
* **code:** standardize search previews and restart status ([#3806](https://github.com/shantanusharma/deepagents/issues/3806)) ([71a6d50](https://github.com/shantanusharma/deepagents/commit/71a6d508b21b275c0c7c6bd2e0752adfba496ea9))
* **code:** stop duplicating Auto transcript events on interrupt replay ([#5157](https://github.com/shantanusharma/deepagents/issues/5157)) ([5bbcf42](https://github.com/shantanusharma/deepagents/commit/5bbcf428a8131f0fca149abba34096fbcd2dfde8))
* **code:** stop leaking turn coroutines and sqlite handles ([#5218](https://github.com/shantanusharma/deepagents/issues/5218)) ([994799b](https://github.com/shantanusharma/deepagents/commit/994799b2f25950eb76e1085b5026d1f19eceb563))
* **code:** stop passing removed `checkpoint_metadata` ([#5473](https://github.com/shantanusharma/deepagents/issues/5473)) ([61ae398](https://github.com/shantanusharma/deepagents/commit/61ae398a60a2f6c23954d89332950570e0b6b431))
* **code:** stop project `.env` from setting extension, shell, plugin, and skill trust ([#7275](https://github.com/shantanusharma/deepagents/issues/7275)) ([ebdee3e](https://github.com/shantanusharma/deepagents/commit/ebdee3ef5be4ecea4e1bd973c24e219ffaa4464e))
* **code:** stop the local server from uploading usage metadata to LangSmith ([#7252](https://github.com/shantanusharma/deepagents/issues/7252)) ([305a185](https://github.com/shantanusharma/deepagents/commit/305a185c1c867c1641f73db21e2b180772f030e0))
* **code:** stop the local server when its owner dies ([#7038](https://github.com/shantanusharma/deepagents/issues/7038)) ([fc1dbad](https://github.com/shantanusharma/deepagents/commit/fc1dbad249e82cb77776683aa891ec24dfb584fc))
* **code:** store update logs under the OS cache dir ([#5363](https://github.com/shantanusharma/deepagents/issues/5363)) ([f69804b](https://github.com/shantanusharma/deepagents/commit/f69804bfce2673de4f2171664ac5b91c1c248ea0))
* **code:** stream tool-call args in linear time ([#5712](https://github.com/shantanusharma/deepagents/issues/5712)) ([57bfa6b](https://github.com/shantanusharma/deepagents/commit/57bfa6bdc57056265047744dc32f3337a964ddc8))
* **code:** strip input before Ctrl+C copy-input fallback ([#4590](https://github.com/shantanusharma/deepagents/issues/4590)) ([505d55a](https://github.com/shantanusharma/deepagents/commit/505d55ad83e8569213175911ee6c8c39fbbf340c))
* **code:** strip media placeholders from model-facing message text ([#4462](https://github.com/shantanusharma/deepagents/issues/4462)) ([aa0ae36](https://github.com/shantanusharma/deepagents/commit/aa0ae36b00df6411a9200610a9075ef2dc28b1af))
* **code:** support non-ASCII file names in `@` mentions ([#7023](https://github.com/shantanusharma/deepagents/issues/7023)) ([12f70f2](https://github.com/shantanusharma/deepagents/commit/12f70f27cc2e96ac715f4563e05b205be7adc275))
* **code:** support plain `exit` quit command ([#4543](https://github.com/shantanusharma/deepagents/issues/4543)) ([e6f10a1](https://github.com/shantanusharma/deepagents/commit/e6f10a149051128677c9f6f37663922054a7ac26))
* **code:** support unambiguous `read_file` gutters ([#4711](https://github.com/shantanusharma/deepagents/issues/4711)) ([2089b54](https://github.com/shantanusharma/deepagents/commit/2089b54e2a674ede313e790b59febf9dc6f22571))
* **code:** suppress auto-update migration notice on fresh installs ([#4224](https://github.com/shantanusharma/deepagents/issues/4224)) ([eb8ff80](https://github.com/shantanusharma/deepagents/commit/eb8ff809a1b3130a261083c66a193e532095c6db))
* **code:** suppress expected MCP reauth logs ([#4359](https://github.com/shantanusharma/deepagents/issues/4359)) ([15ee384](https://github.com/shantanusharma/deepagents/commit/15ee384117ccd955f7481346dd92b7f4b007a60d))
* **code:** suppress historical cost warnings on resume ([#6471](https://github.com/shantanusharma/deepagents/issues/6471)) ([13170ea](https://github.com/shantanusharma/deepagents/commit/13170ea5b07206c94d535141af7e311666f17b7b))
* **code:** suppress interrupt-cleanup state writes from traces ([#3465](https://github.com/shantanusharma/deepagents/issues/3465)) ([319b24e](https://github.com/shantanusharma/deepagents/commit/319b24e6f179eaf56f105a6db683901c82fe95be))
* **code:** suppress model-switch defer toast on bare reconnect ([#4060](https://github.com/shantanusharma/deepagents/issues/4060)) ([60b1052](https://github.com/shantanusharma/deepagents/commit/60b10520d24c87b9c8c9d85b94cffae9e3c67c43))
* **code:** suppress ownership warnings for root installs ([#6907](https://github.com/shantanusharma/deepagents/issues/6907)) ([f6c579c](https://github.com/shantanusharma/deepagents/commit/f6c579c932e2e283f0399dde5686fdcba44e8742))
* **code:** suppress stale update notices ([#3801](https://github.com/shantanusharma/deepagents/issues/3801)) ([db25241](https://github.com/shantanusharma/deepagents/commit/db252411d8ca945aca86429acb644540ec970bdb))
* **code:** surface `/auth`-stored credentials in `config show`/`get` ([#4258](https://github.com/shantanusharma/deepagents/issues/4258)) ([c7c8788](https://github.com/shantanusharma/deepagents/commit/c7c8788ecf0068914298a6055a5f3fd31c36bd44))
* **code:** surface `langchain-quickjs` in `/version` core deps ([#4813](https://github.com/shantanusharma/deepagents/issues/4813)) ([4112392](https://github.com/shantanusharma/deepagents/commit/41123924da6f6aa0243b51f2374210bee86df089))
* **code:** surface actionable Groq tool-limit errors ([#6996](https://github.com/shantanusharma/deepagents/issues/6996)) ([12b12f9](https://github.com/shantanusharma/deepagents/commit/12b12f966dd679f8ba3f134e6f4853fa88da80b3))
* **code:** surface cached MCP errors as failed tool messages ([#3829](https://github.com/shantanusharma/deepagents/issues/3829)) ([d83b428](https://github.com/shantanusharma/deepagents/commit/d83b428f7f97bc40b9219c02846c2d8b4ccac434))
* **code:** surface hook stops without agent errors ([#5276](https://github.com/shantanusharma/deepagents/issues/5276)) ([ed0e3e2](https://github.com/shantanusharma/deepagents/commit/ed0e3e236eea691d7c8c586ac1f9c82eba352b1a))
* **code:** surface model replies that stop before producing output ([#7333](https://github.com/shantanusharma/deepagents/issues/7333)) ([4ff9266](https://github.com/shantanusharma/deepagents/commit/4ff926659cfb1281b01d6821052135cef151dde3))
* **code:** surface recommended models missing from installed provider profiles ([#4057](https://github.com/shantanusharma/deepagents/issues/4057)) ([56e0d31](https://github.com/shantanusharma/deepagents/commit/56e0d31b6c507d5a1e95c3f2058a8d3b9488a4db))
* **code:** surface stale updates in-session ([#6063](https://github.com/shantanusharma/deepagents/issues/6063)) ([cdb9d4c](https://github.com/shantanusharma/deepagents/commit/cdb9d4c30f4419c0eb2c98ad53940875e4dfbe9e))
* **code:** surface the LangSmith credential in `dcode config` ([#6083](https://github.com/shantanusharma/deepagents/issues/6083)) ([a1a0887](https://github.com/shantanusharma/deepagents/commit/a1a0887f7e42d0f8515ad415c9b9062e89350e8c))
* **code:** surface tool calls awaiting approval ([#4739](https://github.com/shantanusharma/deepagents/issues/4739)) ([8148724](https://github.com/shantanusharma/deepagents/commit/814872492eb2bed4d5c382c6c1fe985ad4354b68))
* **code:** surface untracked files in `@` completion ([#3872](https://github.com/shantanusharma/deepagents/issues/3872)) ([2bdf6ea](https://github.com/shantanusharma/deepagents/commit/2bdf6ea329c6b4c8be5f0075528e00c7ce2c1e6a))
* **code:** sweep expired history archives at startup ([#5751](https://github.com/shantanusharma/deepagents/issues/5751)) ([d9dc96e](https://github.com/shantanusharma/deepagents/commit/d9dc96ed555c94f9973e9b49d4b12fd543038f8b))
* **code:** switch input mode without flashing the mode trigger ([#4243](https://github.com/shantanusharma/deepagents/issues/4243)) ([fc5d9cb](https://github.com/shantanusharma/deepagents/commit/fc5d9cb8fb978ec95f98407692d4809ea1e86577))
* **code:** sync `ask_user` active-question highlight with focus ([#4599](https://github.com/shantanusharma/deepagents/issues/4599)) ([e4c29b5](https://github.com/shantanusharma/deepagents/commit/e4c29b5264413d23d8dc70cabae72feb5f3f3dcb))
* **code:** sync approval toggles during active runs ([#4239](https://github.com/shantanusharma/deepagents/issues/4239)) ([4600365](https://github.com/shantanusharma/deepagents/commit/4600365ea0b60c3e9113ecf59b5336be37d03428))
* **code:** targeted uv constraints for dcode prerelease deps ([#4744](https://github.com/shantanusharma/deepagents/issues/4744)) ([36c4024](https://github.com/shantanusharma/deepagents/commit/36c40241b85ec5b0452d9ca334e5f09b95dc16aa))
* **code:** thread `session_id` through forced-compaction fork ([#5492](https://github.com/shantanusharma/deepagents/issues/5492)) ([33d323c](https://github.com/shantanusharma/deepagents/commit/33d323c98bda90c7fe75bcf4a44fb083ed87fa81))
* **code:** thread id always copies on click in Debug Console ([#4945](https://github.com/shantanusharma/deepagents/issues/4945)) ([b4cb393](https://github.com/shantanusharma/deepagents/commit/b4cb3937bf8883e616f47621547a775ce9b29995))
* **code:** toast and expand long transcript user messages ([#5073](https://github.com/shantanusharma/deepagents/issues/5073)) ([a34713b](https://github.com/shantanusharma/deepagents/commit/a34713b122383dccad2572cd7213fd56f467fcce))
* **code:** toast model no-op notice instead of inline message ([#5074](https://github.com/shantanusharma/deepagents/issues/5074)) ([92b5193](https://github.com/shantanusharma/deepagents/commit/92b519391f584acb7786121469e45e850a94e06c))
* **code:** toast when media is dropped into a free-text question ([#5099](https://github.com/shantanusharma/deepagents/issues/5099)) ([da8d4c3](https://github.com/shantanusharma/deepagents/commit/da8d4c3ccc237e57294088d2437b13031a73c52d))
* **code:** token-safe MCP OAuth login error handling and loopback edge cases ([#3492](https://github.com/shantanusharma/deepagents/issues/3492)) ([6199c71](https://github.com/shantanusharma/deepagents/commit/6199c71d6056a603a261b33b99ca3c421670ea4f))
* **code:** tool spinner, result formatting, and expand-hint fixes ([#3661](https://github.com/shantanusharma/deepagents/issues/3661)) ([54485a3](https://github.com/shantanusharma/deepagents/commit/54485a305854f46a6ce00ae4df51f3301c652a38))
* **code:** track live dynamic subagent cost ([#5833](https://github.com/shantanusharma/deepagents/issues/5833)) ([37d7777](https://github.com/shantanusharma/deepagents/commit/37d7777195ff5c30ef789052d02d4387725182b8))
* **code:** treat effort changes as cache identity for OpenAI and Anthropic ([#6196](https://github.com/shantanusharma/deepagents/issues/6196)) ([cacd50a](https://github.com/shantanusharma/deepagents/commit/cacd50adc365e949e4f0b9a7e94ad6f8eeb7d497))
* **code:** treat multi-line key-event pastes as one input ([#3856](https://github.com/shantanusharma/deepagents/issues/3856)) ([6bb15d4](https://github.com/shantanusharma/deepagents/commit/6bb15d4bd97bd16f47504f937c8458d1b53d9cc4))
* **code:** trim `web_search` and `fetch_url` tool descriptions ([#5016](https://github.com/shantanusharma/deepagents/issues/5016)) ([170b4a6](https://github.com/shantanusharma/deepagents/commit/170b4a6c4590b3f95fb5219b5d9074c7f01a1937))
* **code:** turn off server log colors so dcode starts on Windows ([#7591](https://github.com/shantanusharma/deepagents/issues/7591)) ([f59b391](https://github.com/shantanusharma/deepagents/commit/f59b39119418cdbc9cdcd4e4e3b80937bf671f63))
* **code:** unblock `/remember` in server mode ([#3812](https://github.com/shantanusharma/deepagents/issues/3812)) ([12e00e1](https://github.com/shantanusharma/deepagents/commit/12e00e1a78e2d6be106147a0aa95a518be66849f))
* **code:** unblock MCP force reconnect modal ([#4396](https://github.com/shantanusharma/deepagents/issues/4396)) ([8b7eab0](https://github.com/shantanusharma/deepagents/commit/8b7eab023db686f577d16f4f9ac872205baf136f))
* **code:** unblock TUI input during `/restart` ([#3826](https://github.com/shantanusharma/deepagents/issues/3826)) ([366cd81](https://github.com/shantanusharma/deepagents/commit/366cd81269e2d3891a477848b774cf51af0cefc0))
* **code:** unify auth status labels ([#3773](https://github.com/shantanusharma/deepagents/issues/3773)) ([8e743ac](https://github.com/shantanusharma/deepagents/commit/8e743ac895c4e38df8efa192501b8993d37f94a7))
* **code:** unify model catalogs and selection on the server ([#6773](https://github.com/shantanusharma/deepagents/issues/6773)) ([4b94102](https://github.com/shantanusharma/deepagents/commit/4b9410272a4e4885ec70fb1ec8549e307a15e585))
* **code:** unpin uv self-updates and warn when a stale dcode shadows PATH ([#4185](https://github.com/shantanusharma/deepagents/issues/4185)) ([8ca0a18](https://github.com/shantanusharma/deepagents/commit/8ca0a185a15f800267cc057178a348fb5063df1e))
* **code:** update rubric grader model without restart ([#5885](https://github.com/shantanusharma/deepagents/issues/5885)) ([428e760](https://github.com/shantanusharma/deepagents/commit/428e760668d8fdfbb920966e2969c76040e30745))
* **code:** update stale model recommendations and `Ctrl+R` hint ([#7350](https://github.com/shantanusharma/deepagents/issues/7350)) ([547603b](https://github.com/shantanusharma/deepagents/commit/547603bf4b8bb8ef02e12764c5ca90b41ac2d839))
* **code:** use `ChatBedrockConverse` for non-Anthropic Bedrock models ([#6718](https://github.com/shantanusharma/deepagents/issues/6718)) ([1d468d9](https://github.com/shantanusharma/deepagents/commit/1d468d9f3d7f43de096a342dabd7abafbad61f73))
* **code:** use dismissed copy for ask-user prompts ([#5331](https://github.com/shantanusharma/deepagents/issues/5331)) ([920fb66](https://github.com/shantanusharma/deepagents/commit/920fb66763e85b759c2ec3cac090bccd7f05b55f))
* **code:** use listed skill paths instead of inferring locations ([#6711](https://github.com/shantanusharma/deepagents/issues/6711)) ([1342568](https://github.com/shantanusharma/deepagents/commit/13425688e6a8e8508b1905dba5330c38032520e3))
* **code:** use native structured output for Anthropic Auto classifier ([#7162](https://github.com/shantanusharma/deepagents/issues/7162)) ([7bb57e6](https://github.com/shantanusharma/deepagents/commit/7bb57e664ea2ff41df22042f9aebcf15295b20cd))
* **code:** use SDK pin as effective editable version ([#4949](https://github.com/shantanusharma/deepagents/issues/4949)) ([1b270c8](https://github.com/shantanusharma/deepagents/commit/1b270c86fe24381c28d3ed35a31d754bd58bbf6e))
* **code:** use sharp splash border ([#5970](https://github.com/shantanusharma/deepagents/issues/5970)) ([096d20c](https://github.com/shantanusharma/deepagents/commit/096d20cc7f0d61ed027686b226217f4a717925b0))
* **code:** use UTF-8 for prompts and skill files ([#6474](https://github.com/shantanusharma/deepagents/issues/6474)) ([8feaa0f](https://github.com/shantanusharma/deepagents/commit/8feaa0fcce7ee967b1411c247d6f4eab202aa66d))
* **code:** wait for graph readiness after server restart ([#5947](https://github.com/shantanusharma/deepagents/issues/5947)) ([358bc33](https://github.com/shantanusharma/deepagents/commit/358bc3347135793afd12b8b387bda94e61bb6f07))
* **code:** warm lazy MCP caches off the event loop ([#6517](https://github.com/shantanusharma/deepagents/issues/6517)) ([e6419a6](https://github.com/shantanusharma/deepagents/commit/e6419a6fbabf18d8232fb6b0a0283bc933b4bae3))
* **code:** warm MCP auth imports off event loop ([#4855](https://github.com/shantanusharma/deepagents/issues/4855)) ([75d37c3](https://github.com/shantanusharma/deepagents/commit/75d37c347556d962ff14850bdde489657c86feb4))
* **code:** warn and ignore `--auto-approve`/`--yolo` in headless mode ([#5750](https://github.com/shantanusharma/deepagents/issues/5750)) ([9223593](https://github.com/shantanusharma/deepagents/commit/922359307cb0e7728ab58613b29631500e9c5abc))
* **code:** warn on `/trace` when thread has no messages ([#4162](https://github.com/shantanusharma/deepagents/issues/4162)) ([c338fc9](https://github.com/shantanusharma/deepagents/commit/c338fc914fcd383beb4b97c13f53dfb2684f8c90))
* **code:** warn on misconfigured subagent files ([#3873](https://github.com/shantanusharma/deepagents/issues/3873)) ([f1614d6](https://github.com/shantanusharma/deepagents/commit/f1614d67827c3d4d3bd01a784f57f83a50ec3410))
* **code:** warn on stale dependencies in editable installs ([#5386](https://github.com/shantanusharma/deepagents/issues/5386)) ([10353bd](https://github.com/shantanusharma/deepagents/commit/10353bda7196f307db9b22ef1173764aeda6daa7))
* **code:** word-delete backspace parity in ask-user text area ([#4079](https://github.com/shantanusharma/deepagents/issues/4079)) ([ed3c499](https://github.com/shantanusharma/deepagents/commit/ed3c499354467bc5e8476e5c7cdf0cd5f8b6aec1))
* **code:** wrap debug logs before the scrollbar ([#6219](https://github.com/shantanusharma/deepagents/issues/6219)) ([ca7999a](https://github.com/shantanusharma/deepagents/commit/ca7999a8a9984e110a3b80d2e5f71dbe895f58ec))
* **code:** wrap MCP viewer navigation ([#4677](https://github.com/shantanusharma/deepagents/issues/4677)) ([cffc732](https://github.com/shantanusharma/deepagents/commit/cffc73213bfdcec26cb82c413fa7e27db4afc0ca))
* **sdk,code:** rename trace version metadata to `lc_versions` ([#3928](https://github.com/shantanusharma/deepagents/issues/3928)) ([27f38c5](https://github.com/shantanusharma/deepagents/commit/27f38c51f960941e102dfc2f9c0220bc16736749))
* **sdk,code:** use `file_path` kwarg in `read_file` examples ([#3630](https://github.com/shantanusharma/deepagents/issues/3630)) ([97946ee](https://github.com/shantanusharma/deepagents/commit/97946ee09eb167c63d8c07f8bb116f40cfc9603f))
* **sdk:** stable `HumanMessage` IDs across resumed threads ([#3591](https://github.com/shantanusharma/deepagents/issues/3591)) ([82c3194](https://github.com/shantanusharma/deepagents/commit/82c31947f9dc938ffc71e1cea96d162a39aec3a1))


### Performance Improvements

* **code,quickjs:** omit middleware trace inputs ([#6015](https://github.com/shantanusharma/deepagents/issues/6015)) ([673844d](https://github.com/shantanusharma/deepagents/commit/673844d06fe0ee186f2e492c3c0a19ec5facffc2))
* **code:** avoid restyling transcript history on message insertion ([#6951](https://github.com/shantanusharma/deepagents/issues/6951)) ([462ead2](https://github.com/shantanusharma/deepagents/commit/462ead206995c1c78ff8da703b35d0a429fc89d9))
* **code:** background refresh for `@` file completion cache ([#3911](https://github.com/shantanusharma/deepagents/issues/3911)) ([aa22d6b](https://github.com/shantanusharma/deepagents/commit/aa22d6b6d5a49e4d6c3aa2d4932df75d14d65f78))
* **code:** build the agent graph during server startup ([#7214](https://github.com/shantanusharma/deepagents/issues/7214)) ([4d461e3](https://github.com/shantanusharma/deepagents/commit/4d461e3ab01e2c5ef9f96b2a5fb099907960d78c))
* **code:** cache LangSmith secret redaction across traced runs ([#7209](https://github.com/shantanusharma/deepagents/issues/7209)) ([5a3039b](https://github.com/shantanusharma/deepagents/commit/5a3039b4b63464b8d62b573bac142b7d0cd76470))
* **code:** cache the SDK version lookup in `build_stream_config` ([#7230](https://github.com/shantanusharma/deepagents/issues/7230)) ([d87a459](https://github.com/shantanusharma/deepagents/commit/d87a459bb10f3b9110ea7edc4f823433394b178e))
* **code:** cache theme colors/charset, fix `O(n^2)` tool-call streaming ([#3881](https://github.com/shantanusharma/deepagents/issues/3881)) ([9d463f5](https://github.com/shantanusharma/deepagents/commit/9d463f52fb3a4d458477982963f3d278d5362b48))
* **code:** compact finished live tool runs into lazy `TOOL_GROUP` rows ([#7254](https://github.com/shantanusharma/deepagents/issues/7254)) ([a18ca04](https://github.com/shantanusharma/deepagents/commit/a18ca04b534718e396fdd1815e236ecfb3d5fea7))
* **code:** coordinate async shutdown teardown to cut exit latency ([#4831](https://github.com/shantanusharma/deepagents/issues/4831)) ([a2e501b](https://github.com/shantanusharma/deepagents/commit/a2e501b71f3d91769f56d5b3e433af8e03f7656e))
* **code:** drop dcode routes from the OpenAPI spec and defer Textual in the server ([#7242](https://github.com/shantanusharma/deepagents/issues/7242)) ([2815f6b](https://github.com/shantanusharma/deepagents/commit/2815f6bece7d01e9c8aa6730eb88d2cd25977573))
* **code:** fetch only cost and cache channels after each turn ([#7206](https://github.com/shantanusharma/deepagents/issues/7206)) ([5162474](https://github.com/shantanusharma/deepagents/commit/516247424485d4d3623891503464b3d576625b1d))
* **code:** filter editable-SDK scan to `deepagents` records ([#7756](https://github.com/shantanusharma/deepagents/issues/7756)) ([27f9b48](https://github.com/shantanusharma/deepagents/commit/27f9b48ea6a4c5d023e9ca9a1b85f95d5f4221ca))
* **code:** filter the thread picker without remounting rows ([#7207](https://github.com/shantanusharma/deepagents/issues/7207)) ([3d34b96](https://github.com/shantanusharma/deepagents/commit/3d34b961d30c5dd81aa5079f63022a8a0636efa6))
* **code:** forward delta-channel history reads to the SQLite saver ([#7244](https://github.com/shantanusharma/deepagents/issues/7244)) ([5fa7317](https://github.com/shantanusharma/deepagents/commit/5fa73172dec5a96f042ebd6aaec5237571df7e8d))
* **code:** halve git attribution probes, back off on failures, add opt-out ([#7661](https://github.com/shantanusharma/deepagents/issues/7661)) ([7ffdf97](https://github.com/shantanusharma/deepagents/commit/7ffdf97fe3351a774d1ba25e295b94c85837f60a))
* **code:** install the LangSmith redacting client after first paint ([#7215](https://github.com/shantanusharma/deepagents/issues/7215)) ([470b075](https://github.com/shantanusharma/deepagents/commit/470b0753986696b41952c772acd2ee316f930890))
* **code:** keep `list_threads` on its covering index ([#7232](https://github.com/shantanusharma/deepagents/issues/7232)) ([b82f3b3](https://github.com/shantanusharma/deepagents/commit/b82f3b326da3267d3a822c2fe7a4ba6980792c31))
* **code:** keep LangChain imports off the first-paint path ([#7189](https://github.com/shantanusharma/deepagents/issues/7189)) ([a429412](https://github.com/shantanusharma/deepagents/commit/a42941234fbf98d25db6794d0726fc48aac4fccf))
* **code:** keep the `/btw` system prompt out of checkpoints ([#7202](https://github.com/shantanusharma/deepagents/issues/7202)) ([2025b7c](https://github.com/shantanusharma/deepagents/commit/2025b7ca6ad8976e42c24a925dddbea81d0c9cee))
* **code:** let the server process cache its bytecode ([#7193](https://github.com/shantanusharma/deepagents/issues/7193)) ([e53babb](https://github.com/shantanusharma/deepagents/commit/e53babb2df71d995816fab39f3ac762ba670f85c))
* **code:** load MCP servers concurrently during graph build ([#4659](https://github.com/shantanusharma/deepagents/issues/4659)) ([c5345cc](https://github.com/shantanusharma/deepagents/commit/c5345cc04cd810c6238e42dfbfa14497ae1b9020))
* **code:** log thread loading phase timings ([#6490](https://github.com/shantanusharma/deepagents/issues/6490)) ([ad038f8](https://github.com/shantanusharma/deepagents/commit/ad038f87e07e13791ff9b1e239326d2c959fd412))
* **code:** make `threads list` fast on large session databases ([#4005](https://github.com/shantanusharma/deepagents/issues/4005)) ([85ca01a](https://github.com/shantanusharma/deepagents/commit/85ca01a43b002c2bdb4205f48fac5fa6f66a3276))
* **code:** merge streamed chunks once in the transcript recorder ([#7200](https://github.com/shantanusharma/deepagents/issues/7200)) ([4c91940](https://github.com/shantanusharma/deepagents/commit/4c91940b0af1dcfda1b8a4294c5bf959f73b1746))
* **code:** omit `BtwOperation` hook inputs from traces ([#7199](https://github.com/shantanusharma/deepagents/issues/7199)) ([23ae4bb](https://github.com/shantanusharma/deepagents/commit/23ae4bb16ff0178791d2234b00dd06210a72076a))
* **code:** omit middleware trace inputs ([#5815](https://github.com/shantanusharma/deepagents/issues/5815)) ([39b760f](https://github.com/shantanusharma/deepagents/commit/39b760f12452e1b04bcd0fa15850662ce83ceee8))
* **code:** queue in-process checkpoint writers instead of polling the ownership gate ([#7245](https://github.com/shantanusharma/deepagents/issues/7245)) ([d5801f1](https://github.com/shantanusharma/deepagents/commit/d5801f121c8f320a253ac13fd6a3988ea1f8bf71))
* **code:** rank checkpoint row IDs before loading blobs ([#6488](https://github.com/shantanusharma/deepagents/issues/6488)) ([933eaea](https://github.com/shantanusharma/deepagents/commit/933eaeaddea12d1d6fcd0a8cd7716e948ff1df58))
* **code:** rank message row IDs before loading prompts ([#6489](https://github.com/shantanusharma/deepagents/issues/6489)) ([17ea378](https://github.com/shantanusharma/deepagents/commit/17ea378fcb04f15c916e64eaf24a833b3a63c504))
* **code:** re-render streamed markdown only when blocks diverge ([#7210](https://github.com/shantanusharma/deepagents/issues/7210)) ([18f5543](https://github.com/shantanusharma/deepagents/commit/18f55433e0b82f4668e5228b04385023067cb9c4))
* **code:** refresh `/threads` cache after each turn ([#5174](https://github.com/shantanusharma/deepagents/issues/5174)) ([872f9d5](https://github.com/shantanusharma/deepagents/commit/872f9d5647759a84e7abfa79d43fc128c54e29a4))
* **code:** remove pruned transcript rows in one batch ([#7250](https://github.com/shantanusharma/deepagents/issues/7250)) ([ec98477](https://github.com/shantanusharma/deepagents/commit/ec9847732f947d9809c41e92f0d78c9131caeb2a))
* **code:** remove redundant MCP startup probes ([#7303](https://github.com/shantanusharma/deepagents/issues/7303)) ([1f4237a](https://github.com/shantanusharma/deepagents/commit/1f4237af32eef17581e507f914424d523fd7b296))
* **code:** render finished assistant replies as one widget ([#7255](https://github.com/shantanusharma/deepagents/issues/7255)) ([9243a1c](https://github.com/shantanusharma/deepagents/commit/9243a1cbb7a012fb327a278dee94e295a10aeb7f))
* **code:** restore the terminal before the server finishes stopping ([#7192](https://github.com/shantanusharma/deepagents/issues/7192)) ([56971e2](https://github.com/shantanusharma/deepagents/commit/56971e2631ac26c57aaf9010f4c6c03c5170a0a7))
* **code:** reuse Auto classifier history ([#6056](https://github.com/shantanusharma/deepagents/issues/6056)) ([44926fa](https://github.com/shantanusharma/deepagents/commit/44926fa8f26dfb24d9a0e3ded335c48b123d193d))
* **code:** reuse Git status for local context branch detection ([#7299](https://github.com/shantanusharma/deepagents/issues/7299)) ([da49416](https://github.com/shantanusharma/deepagents/commit/da49416595221317b8a2951a1f861b54fd3ad499))
* **code:** reuse the parent's local context in forked subagents ([#7233](https://github.com/shantanusharma/deepagents/issues/7233)) ([8d2c868](https://github.com/shantanusharma/deepagents/commit/8d2c868e010fdf0939e6285bb4965deea42bf1e6))
* **code:** scale the stream flush interval to markdown render cost ([#7205](https://github.com/shantanusharma/deepagents/issues/7205)) ([e79aaa5](https://github.com/shantanusharma/deepagents/commit/e79aaa5a1e413fdd7a923ab5556981074ceed12f))
* **code:** scan the worktree once per git evidence probe ([#7660](https://github.com/shantanusharma/deepagents/issues/7660)) ([172814d](https://github.com/shantanusharma/deepagents/commit/172814d25a58f22c0e6da2b88714ca493853e04a))
* **code:** shrink the mounted transcript window to 350 rows ([#7256](https://github.com/shantanusharma/deepagents/issues/7256)) ([71c9792](https://github.com/shantanusharma/deepagents/commit/71c9792c998b30b4130f7379a8cda9d93398d3e7))
* **code:** skip `traceable` thread hops when tracing is off ([#7247](https://github.com/shantanusharma/deepagents/issues/7247)) ([fb05a5d](https://github.com/shantanusharma/deepagents/commit/fb05a5db3a070f89e3022a3aa869225fb6dae647))
* **code:** skip redundant goal-notice history scans in `GoalToolsMiddleware` ([#7201](https://github.com/shantanusharma/deepagents/issues/7201)) ([918a8c8](https://github.com/shantanusharma/deepagents/commit/918a8c80363d06d3ddb2d5847fe1062ad25ee45d))
* **code:** skip the `langgraph-api` PyPI version check at server launch ([#7198](https://github.com/shantanusharma/deepagents/issues/7198)) ([61c9645](https://github.com/shantanusharma/deepagents/commit/61c9645699cdc33370a513d7ff6be05ef8e80379))
* **code:** skip the final GC pass when the TUI exits ([#7191](https://github.com/shantanusharma/deepagents/issues/7191)) ([a3b1ea9](https://github.com/shantanusharma/deepagents/commit/a3b1ea9844af3447d265fb64e2d5f18c0d0bc90d))
* **code:** skip the full shutdown wait for an abandoned server startup ([#7194](https://github.com/shantanusharma/deepagents/issues/7194)) ([a7e09c1](https://github.com/shantanusharma/deepagents/commit/a7e09c1a54bb3200b7e59ead1c1042ab9e0345fc))
* **code:** skip transcript scan on prompt submit ([#6402](https://github.com/shantanusharma/deepagents/issues/6402)) ([443d34b](https://github.com/shantanusharma/deepagents/commit/443d34bfde4f22cbc7f9ac71be766922a041e08c))
* **code:** spawn server before waiting on import prewarm ([#7184](https://github.com/shantanusharma/deepagents/issues/7184)) ([6d184fd](https://github.com/shantanusharma/deepagents/commit/6d184fd8f38f0a49729030a0e3b5d111ffc14e77))
* **code:** spawn the server before importing the app module ([#7249](https://github.com/shantanusharma/deepagents/issues/7249)) ([89824bb](https://github.com/shantanusharma/deepagents/commit/89824bb4e8b32964013f9101f41e9ecaa5378476))
* **code:** speed up `@` file completion scoring ([#7248](https://github.com/shantanusharma/deepagents/issues/7248)) ([bca2b9c](https://github.com/shantanusharma/deepagents/commit/bca2b9cb9c899fd063fd2fdf3c2d23539fbc7d7c))
* **code:** speed up local context detection ([#4922](https://github.com/shantanusharma/deepagents/issues/4922)) ([0b512d4](https://github.com/shantanusharma/deepagents/commit/0b512d4b79b1a03c7e452f1e76350cf726b1ec38))
* **code:** speed up shutdown after Ctrl+C/Ctrl+D ([#4351](https://github.com/shantanusharma/deepagents/issues/4351)) ([db441ed](https://github.com/shantanusharma/deepagents/commit/db441ed306a8e03fb68f2ae6a2c08523e248976d))
* **code:** start server runs without the in-memory queue's poll delay ([#7243](https://github.com/shantanusharma/deepagents/issues/7243)) ([e47f4e2](https://github.com/shantanusharma/deepagents/commit/e47f4e286571ac2f2873ad1a87baa5bb6eea470d))
* **code:** start the server before post-paint init ([#7208](https://github.com/shantanusharma/deepagents/issues/7208)) ([4b2842c](https://github.com/shantanusharma/deepagents/commit/4b2842cd6c5370002fc326c2554b04b81a4aec8a))
* **code:** stop relayouting the transcript on spinner ticks ([#7203](https://github.com/shantanusharma/deepagents/issues/7203)) ([84b3bbe](https://github.com/shantanusharma/deepagents/commit/84b3bbe9887f530a6a773ef21b541eb1812af68f))
* **code:** stop walking the DOM on the 1 Hz cache-expiry tick ([#7246](https://github.com/shantanusharma/deepagents/issues/7246)) ([97f518d](https://github.com/shantanusharma/deepagents/commit/97f518d5870c77673db8551de831c9ec71295928))


### Reverted Changes

* **code,sdk:** revert `SystemPromptConfig` ([#4969](https://github.com/shantanusharma/deepagents/issues/4969)) ([d046427](https://github.com/shantanusharma/deepagents/commit/d046427b536c8ddbce5d804d6ae8b860511a9b44))
* **code:** "add macOS keyboard shortcuts for line navigation" ([#3589](https://github.com/shantanusharma/deepagents/issues/3589)) ([73402e8](https://github.com/shantanusharma/deepagents/commit/73402e817340d1f5a643328a063129894be768e6))

## [0.2.11](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.10...deepagents-code==0.2.11) (2026-11-18)

### Bug Fixes

- Honor MCP hook approval policies ([#7766](https://github.com/langchain-ai/deepagents/pull/7766)).
- Wait for background worker cleanup to complete during shutdown ([#7810](https://github.com/langchain-ai/deepagents/pull/7810)).

## [0.2.10](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.9...deepagents-code==0.2.10) (2026-11-17)

### Features

- Report agent status to terminals using OSC 7501 ([#7772](https://github.com/langchain-ai/deepagents/pull/7772)).

### Bug Fixes

- Load MCP trust lists without blocking the server event loop ([#7798](https://github.com/langchain-ai/deepagents/pull/7798)).
- Show a working upgrade command in the ACP import error message ([#7780](https://github.com/langchain-ai/deepagents/pull/7780)).

## [0.2.9](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.8...deepagents-code==0.2.9) (2026-11-16)

### Features

- Updated stable model recommendations ([#7734](https://github.com/langchain-ai/deepagents/pull/7734)).

### Performance Improvements

- Limited editable-SDK scanning to `deepagents` records ([#7756](https://github.com/langchain-ai/deepagents/pull/7756)).

## [0.2.8](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.7...deepagents-code==0.2.8) (2026-11-13)

### Features

- Set `DEEPAGENTS_CODE=1` in the local shell environment. ([#7701](https://github.com/langchain-ai/deepagents/pull/7701))

### Bug Fixes

- Replace unencodable characters in redirected output. ([#7717](https://github.com/langchain-ai/deepagents/pull/7717))

## [0.2.7](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.6...deepagents-code==0.2.7) (2026-11-10)

### Features

- Added shell completion scripts via `dcode completion` ([#7264](https://github.com/langchain-ai/deepagents/pull/7264)).

### Bug Fixes

- Fixed detection of editor launchers such as `code.cmd` on Windows ([#7642](https://github.com/langchain-ai/deepagents/pull/7642)).
- Improved `dcode completion` output and setup steps, and fixed Bash completion for `--flag=value` arguments ([#7658](https://github.com/langchain-ai/deepagents/pull/7658), [#7656](https://github.com/langchain-ai/deepagents/pull/7656)).
- Preserved compaction feedback and offload usage when summaries do not stream ([#7644](https://github.com/langchain-ai/deepagents/pull/7644)).

### Performance Improvements

- Reduced Git attribution overhead by halving probes, backing off after failures, and scanning the worktree only once per evidence probe. Added an option to disable attribution probes ([#7661](https://github.com/langchain-ai/deepagents/pull/7661), [#7660](https://github.com/langchain-ai/deepagents/pull/7660)).

## [0.2.6](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.5...deepagents-code==0.2.6) (2026-11-09)

### Features

- Make idle compaction settings filterable in traces ([#7624](https://github.com/langchain-ai/deepagents/pull/7624)).
- Tag offload traces with their triggers ([#7630](https://github.com/langchain-ai/deepagents/pull/7630)).

### Bug Fixes

- Fix dcode startup on Windows by disabling server log colors ([#7591](https://github.com/langchain-ai/deepagents/pull/7591)).
- Bypass proxies for local server traffic ([#7613](https://github.com/langchain-ai/deepagents/pull/7613)).
- Offer recovery options when server startup times out ([#7610](https://github.com/langchain-ai/deepagents/pull/7610)).
- Leave piped standard input available to subcommands ([#7601](https://github.com/langchain-ai/deepagents/pull/7601)).
- Resolve the summarization cutoff by message ID ([#7570](https://github.com/langchain-ai/deepagents/pull/7570)).
- Keep queued prompts beside long message text ([#7611](https://github.com/langchain-ai/deepagents/pull/7611)).

## [0.2.5](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.4...deepagents-code==0.2.5) (2026-11-05)

### Bug Fixes

- Size the compaction input budget to match the selected model. ([#7545](https://github.com/langchain-ai/deepagents/pull/7545))
- Preserve cut-off reply handling when `ModelRefusalMiddleware` raises an error. ([#7548](https://github.com/langchain-ai/deepagents/pull/7548))
- Defer in-app `uv` installations on Windows. ([#7518](https://github.com/langchain-ai/deepagents/pull/7518))

## [0.2.4](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.3...deepagents-code==0.2.4) (2026-11-02)

### Features

- Mark interrupt cancellation messages with `lc_source` ([#7501](https://github.com/langchain-ai/deepagents/pull/7501)).

### Bug Fixes

- Clarify workspace conflicts, MCP login failures, and disabled Slack MCP access during login ([#7499](https://github.com/langchain-ai/deepagents/pull/7499), [#7498](https://github.com/langchain-ai/deepagents/pull/7498)).
- Clarify how `/reload` refreshes MCP configuration ([#7497](https://github.com/langchain-ai/deepagents/pull/7497)).

## [0.2.3](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.2...deepagents-code==0.2.3) (2026-11-02)

### Features

- Defer loading MCP tool schemas with provider-native tool search ([#7304](https://github.com/langchain-ai/deepagents/pull/7304)).
- Include the official marketplace by default ([#7364](https://github.com/langchain-ai/deepagents/pull/7364)).
- Require an explicit or saved model selection ([#7365](https://github.com/langchain-ai/deepagents/pull/7365)).
- Apply hook command rewrites before requesting tool approval ([#7384](https://github.com/langchain-ai/deepagents/pull/7384)).
- Support `DEEPAGENTS_CODE_LANGSMITH_PROJECT_URL` and cache rejected project lookups ([#7332](https://github.com/langchain-ai/deepagents/pull/7332)).
- Show MCP tool counts in `/tools` headers ([#7327](https://github.com/langchain-ai/deepagents/pull/7327)).

### Bug Fixes

- Block auto mode when its classifier cannot be resolved, and disclose inherited classifier model switches ([#7346](https://github.com/langchain-ai/deepagents/pull/7346), [#7351](https://github.com/langchain-ai/deepagents/pull/7351)).
- Skip subagent `AGENTS.md` files that are not UTF-8 instead of failing startup ([#7361](https://github.com/langchain-ai/deepagents/pull/7361)).
- Surface model replies that stop before producing output ([#7333](https://github.com/langchain-ai/deepagents/pull/7333)).
- Preserve reasoning in remote message chunks ([#7341](https://github.com/langchain-ai/deepagents/pull/7341)).
- Enable Claude prompt caching on OpenRouter ([#7358](https://github.com/langchain-ai/deepagents/pull/7358)).
- Confirm auto-update success only after the new version loads, and reuse fresh update information during explicit updates ([#7344](https://github.com/langchain-ai/deepagents/pull/7344), [#7355](https://github.com/langchain-ai/deepagents/pull/7355)).
- Refresh the subscription model lineup and update stale model recommendations and the `Ctrl+R` hint ([#7340](https://github.com/langchain-ai/deepagents/pull/7340), [#7350](https://github.com/langchain-ai/deepagents/pull/7350)).
- Make `/cost` open the token and cost modal ([#7363](https://github.com/langchain-ai/deepagents/pull/7363)).
- End typing deferral when a prompt is submitted ([#7335](https://github.com/langchain-ai/deepagents/pull/7335)).
- Correct coding-agent Git trace attribution ([#7117](https://github.com/langchain-ai/deepagents/pull/7117)).
- Clarify how to recover from credential setup issues ([#7347](https://github.com/langchain-ai/deepagents/pull/7347)).
- Clarify Python update instructions ([#7343](https://github.com/langchain-ai/deepagents/pull/7343)).
- Collapse the ChatGPT sign-in browser URL by default ([#7348](https://github.com/langchain-ai/deepagents/pull/7348)).
- Delay tool-group progress indicators to avoid flashing ([#7357](https://github.com/langchain-ai/deepagents/pull/7357)).
- Remove the advanced configuration tip from the empty MCP modal ([#7356](https://github.com/langchain-ai/deepagents/pull/7356)).

### Performance Improvements

- Remove redundant MCP startup probes ([#7303](https://github.com/langchain-ai/deepagents/pull/7303)).
- Reuse Git status when detecting the branch for local context ([#7299](https://github.com/langchain-ai/deepagents/pull/7299)).

## [0.2.2](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.1...deepagents-code==0.2.2) (2026-10-26)

This update includes considerable security and performance improvements. We recommend upgrading as soon as feasible.

### Features

- Add support for GPT-6.1 Terra ([#7295](https://github.com/langchain-ai/deepagents/pull/7295)).
- Bring selected text into the chat input ([#6955](https://github.com/langchain-ai/deepagents/pull/6955)).
- Detect plugin updates and notify you when they are available ([#7234](https://github.com/langchain-ai/deepagents/pull/7234)).

### Bug Fixes

- Prevent project `.env` files from setting extension, shell, plugin, and skill trust ([#7275](https://github.com/langchain-ai/deepagents/pull/7275)).
- Restrict links opened from the terminal UI to HTTP and HTTPS ([#7277](https://github.com/langchain-ai/deepagents/pull/7277)).
- Restrict Git options in Auto mode's read-only fast path to an allowlist ([#7276](https://github.com/langchain-ai/deepagents/pull/7276)).
- Stop the local server from uploading usage metadata to LangSmith ([#7252](https://github.com/langchain-ai/deepagents/pull/7252)).
- Detect and repair enabled plugins with missing installed files ([#7278](https://github.com/langchain-ai/deepagents/pull/7278)).
- Explain repeated skill-trust denials and clear them on `/reload` ([#7291](https://github.com/langchain-ai/deepagents/pull/7291)).
- Fix transcript height calculations for folded tool rows and spacers so scrolling reaches the newest message ([#7251](https://github.com/langchain-ai/deepagents/pull/7251), [#7253](https://github.com/langchain-ai/deepagents/pull/7253)).
- Keep the terminal UI responsive when quitting during server startup ([#7190](https://github.com/langchain-ai/deepagents/pull/7190)).
- Contain JavaScript subagent failures ([#7211](https://github.com/langchain-ai/deepagents/pull/7211)).
- Manage sandbox lifetime from the client in non-interactive runs ([#6368](https://github.com/langchain-ai/deepagents/pull/6368)).
- Preserve shipped bytecode for read-only installations ([#7196](https://github.com/langchain-ai/deepagents/pull/7196)).
- Correctly read the current branch in reftable repositories through Git ([#7268](https://github.com/langchain-ai/deepagents/pull/7268)).

### Performance Improvements

- Reuse the parent's local context in forked subagents ([#7233](https://github.com/langchain-ai/deepagents/pull/7233)).
- Show the terminal UI sooner by deferring imports and trace redacting-client setup until after the initial display ([#7189](https://github.com/langchain-ai/deepagents/pull/7189), [#7215](https://github.com/langchain-ai/deepagents/pull/7215)).
- Start the server earlier, before import prewarming, app-module imports, and post-display initialization ([#7184](https://github.com/langchain-ai/deepagents/pull/7184), [#7249](https://github.com/langchain-ai/deepagents/pull/7249), [#7208](https://github.com/langchain-ai/deepagents/pull/7208)).
- Streamline server startup by deferring Textual imports, excluding custom routes from the OpenAPI specification, caching bytecode, and skipping a PyPI version check ([#7242](https://github.com/langchain-ai/deepagents/pull/7242), [#7193](https://github.com/langchain-ai/deepagents/pull/7193), [#7198](https://github.com/langchain-ai/deepagents/pull/7198)).
- Build the agent graph during server startup and start runs without the in-memory queue's polling delay ([#7214](https://github.com/langchain-ai/deepagents/pull/7214), [#7243](https://github.com/langchain-ai/deepagents/pull/7243)).
- Improve streaming responsiveness by re-rendering Markdown only when blocks change, adapting the flush interval to rendering cost, and avoiding duplicate chunk merging ([#7210](https://github.com/langchain-ai/deepagents/pull/7210), [#7205](https://github.com/langchain-ai/deepagents/pull/7205), [#7200](https://github.com/langchain-ai/deepagents/pull/7200)).
- Reduce transcript rendering overhead by compacting finished tool runs into lazy group rows, rendering completed replies as single widgets, limiting mounted rows to 350, and batching row removal ([#7254](https://github.com/langchain-ai/deepagents/pull/7254), [#7255](https://github.com/langchain-ai/deepagents/pull/7255), [#7256](https://github.com/langchain-ai/deepagents/pull/7256), [#7250](https://github.com/langchain-ai/deepagents/pull/7250)).
- Reduce background UI work by avoiding transcript relayouts on spinner ticks and DOM traversal on cache-expiry ticks ([#7203](https://github.com/langchain-ai/deepagents/pull/7203), [#7246](https://github.com/langchain-ai/deepagents/pull/7246)).
- Return control to the terminal sooner on exit by restoring it before server shutdown finishes, skipping the final garbage-collection pass, and avoiding the full shutdown wait for abandoned startups ([#7192](https://github.com/langchain-ai/deepagents/pull/7192), [#7191](https://github.com/langchain-ai/deepagents/pull/7191), [#7194](https://github.com/langchain-ai/deepagents/pull/7194)).
- Speed up `@` file-completion scoring ([#7248](https://github.com/langchain-ai/deepagents/pull/7248)).
- Speed up the thread picker by filtering without remounting rows and keeping thread-list queries on a covering index ([#7207](https://github.com/langchain-ai/deepagents/pull/7207), [#7232](https://github.com/langchain-ai/deepagents/pull/7232)).
- Reduce post-turn data fetching to cost and cache channels, and cache SDK version lookups when building stream configuration ([#7206](https://github.com/langchain-ai/deepagents/pull/7206), [#7230](https://github.com/langchain-ai/deepagents/pull/7230)).
- Reduce tracing overhead by caching tracing secret redaction across runs, omitting `BtwOperation` hook inputs from traces, and skipping tracing-related thread hops when tracing is disabled ([#7209](https://github.com/langchain-ai/deepagents/pull/7209), [#7199](https://github.com/langchain-ai/deepagents/pull/7199), [#7247](https://github.com/langchain-ai/deepagents/pull/7247)).
- Improve checkpoint efficiency by forwarding delta-channel history reads to the SQLite saver, queuing in-process writers instead of polling, and keeping the `/btw` system prompt out of checkpoints ([#7244](https://github.com/langchain-ai/deepagents/pull/7244), [#7245](https://github.com/langchain-ai/deepagents/pull/7245), [#7202](https://github.com/langchain-ai/deepagents/pull/7202)).
- Skip redundant goal-notice history scans ([#7201](https://github.com/langchain-ai/deepagents/pull/7201)).

## [0.2.1](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.2.0...deepagents-code==0.2.1) (2026-10-23)

### Features

- Support skill-scoped MCP tools ([#7010](https://github.com/langchain-ai/deepagents/pull/7010)).
- Default the Anthropic Auto classifier to Claude Sonnet 5.5 ([#7163](https://github.com/langchain-ai/deepagents/pull/7163)).

### Bug Fixes

- Automatically migrate to Python 3.14 when no other session is running ([#7160](https://github.com/langchain-ai/deepagents/pull/7160)).
- Use native structured output for the Anthropic Auto classifier ([#7162](https://github.com/langchain-ai/deepagents/pull/7162)).

## [0.2.0](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.88...deepagents-code==0.2.0) (2026-10-22)

### ⚠ BREAKING CHANGES

- `deepagents-code` now requires Python 3.14 (`>=3.14,<3.15`). If you have auto-upgrade enabled, this should be handled for you automatically. Otherwise, re-run the dcode installer or recreate your environment with Python 3.14 ([#7052](https://github.com/langchain-ai/deepagents/pull/7052)).

### Bug Fixes

- Decode Git output as UTF-8 ([#7142](https://github.com/langchain-ai/deepagents/pull/7142)).

## [0.1.88](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.87...deepagents-code==0.1.88) (2026-10-22)

### Bug Fixes

- Fixed async subagents to pass through `webhook` configuration ([#7130](https://github.com/langchain-ai/deepagents/pull/7130)).
- Fixed bridge compatibility with Python 3.14 ([#7081](https://github.com/langchain-ai/deepagents/pull/7081)).
- Silenced no-op automatic cache offloads ([#7078](https://github.com/langchain-ai/deepagents/pull/7078)).

## [0.1.87](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.86...deepagents-code==0.1.87) (2026-10-20)

### Features

- Resume threads in non-interactive mode ([#7011](https://github.com/langchain-ai/deepagents/pull/7011)).
- Compact large idle sessions before the prompt cache expires ([#6956](https://github.com/langchain-ai/deepagents/pull/6956)) and show the prompt-cache expiration time ([#7005](https://github.com/langchain-ai/deepagents/pull/7005)).
- Support custom Slack OAuth app identity ([#7061](https://github.com/langchain-ai/deepagents/pull/7061)).
- Load older threads from the thread switcher ([#7051](https://github.com/langchain-ai/deepagents/pull/7051)).

### Bug Fixes

- Stop the local server when its owner dies ([#7038](https://github.com/langchain-ai/deepagents/pull/7038)).
- Support non-ASCII file names in `@` mentions ([#7023](https://github.com/langchain-ai/deepagents/pull/7023)).
- Correct misleading `/reload` change summaries ([#7063](https://github.com/langchain-ai/deepagents/pull/7063)).

## [0.1.86](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.85...deepagents-code==0.1.86) (2026-10-16)

### Features

- Add NVIDIA OpenShell as a sandbox provider ([#6999](https://github.com/langchain-ai/deepagents/pull/6999)).
- Show a banner when a prompt cache expires ([#6957](https://github.com/langchain-ai/deepagents/pull/6957)).

### Bug Fixes

- Add `/resume` as an alias and improve how alias matches are ranked ([#6988](https://github.com/langchain-ai/deepagents/pull/6988)).
- Report workspace refusals accurately when resuming a thread ([#6992](https://github.com/langchain-ai/deepagents/pull/6992)).
- Replace repeated thread-resume errors ([#6990](https://github.com/langchain-ai/deepagents/pull/6990)).
- Replace the chat input when recalling a prompt ([#6994](https://github.com/langchain-ai/deepagents/pull/6994)).
- Show an expired prompt cache in the footer ([#6970](https://github.com/langchain-ai/deepagents/pull/6970)).
- Provide actionable errors when Groq tool limits are reached ([#6996](https://github.com/langchain-ai/deepagents/pull/6996)).
- Compare effective interpreter permissions ([#6993](https://github.com/langchain-ai/deepagents/pull/6993)).

## [0.1.85](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.84...deepagents-code==0.1.85) (2026-10-14)

### Bug Fixes

- Suppress ownership warnings for root installs ([#6907](https://github.com/langchain-ai/deepagents/pull/6907)).

### Performance Improvements

- Avoid restyling transcript history when inserting messages ([#6951](https://github.com/langchain-ai/deepagents/pull/6951)).

## [0.1.84](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.83...deepagents-code==0.1.84) (2026-10-12)

### Features

- Resolve invoked skills on the server and check whether they are trusted ([#6837](https://github.com/langchain-ai/deepagents/pull/6837)).
- Show provider-visible reasoning by default in the TUI ([#6850](https://github.com/langchain-ai/deepagents/pull/6850)).
- Surface Daytona sandbox snapshots ([#6854](https://github.com/langchain-ai/deepagents/pull/6854)).

### Bug Fixes

- Refresh the agent skill catalog when `/reload` is run ([#6843](https://github.com/langchain-ai/deepagents/pull/6843)).
- Keep fork goals visible without grading them ([#6893](https://github.com/langchain-ai/deepagents/pull/6893)).

## [0.1.83](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.82...deepagents-code==0.1.83) (2026-10-07)

### Features

- Recommend Haiku 5.5 for sidecar models ([#6844](https://github.com/langchain-ai/deepagents/pull/6844)).

## [0.1.82](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.81...deepagents-code==0.1.82) (2026-10-07)

### Features

- Create persistent thread names automatically or on demand, and rename threads manually. ([#6715](https://github.com/langchain-ai/deepagents/pull/6715), [#6767](https://github.com/langchain-ai/deepagents/pull/6767))
- Customize terminal tab titles. ([#6768](https://github.com/langchain-ai/deepagents/pull/6768))
- Distinguish skill reads in the transcript. ([#6825](https://github.com/langchain-ai/deepagents/pull/6825))

### Bug Fixes

- Keep the thread picker open when ownership conflicts occur. ([#6824](https://github.com/langchain-ai/deepagents/pull/6824))
- Preserve completion markers on remote messages. ([#6831](https://github.com/langchain-ai/deepagents/pull/6831))
- Extend triple-click selection across blocks. ([#6819](https://github.com/langchain-ai/deepagents/pull/6819))
- Recommend GPT-6 Luna for auto review. ([#6821](https://github.com/langchain-ai/deepagents/pull/6821))
- Show editable install status in debug version information. ([#6797](https://github.com/langchain-ai/deepagents/pull/6797))

## [0.1.81](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.80...deepagents-code==0.1.81) (2026-10-06)

### Features

- The agent can now discover marketplace plugins ([#6719](https://github.com/langchain-ai/deepagents/pull/6719)).
- You can open the effort selector during active runs ([#6724](https://github.com/langchain-ai/deepagents/pull/6724)) and the cost breakdown from the footer ([#6723](https://github.com/langchain-ai/deepagents/pull/6723)).
- Added `--no-tracing` and an explicit tracing status indicator ([#6721](https://github.com/langchain-ai/deepagents/pull/6721)).
- Renamed `/summarization-model` to `/offload model` ([#6774](https://github.com/langchain-ai/deepagents/pull/6774)).
- Highlighted the active line in multiline chat input ([#6746](https://github.com/langchain-ai/deepagents/pull/6746), [#6781](https://github.com/langchain-ai/deepagents/pull/6781)).

### Bug Fixes

- Use `ChatBedrockConverse` for non-Anthropic Bedrock models ([#6718](https://github.com/langchain-ai/deepagents/pull/6718)).
- Prevented concurrent writes to local threads ([#6717](https://github.com/langchain-ai/deepagents/pull/6717)).
- Hook execution now fails closed if its context changes when a run resumes ([#6712](https://github.com/langchain-ai/deepagents/pull/6712)).
- Improved server-side model catalog, selection, and interactive model metadata handling ([#6773](https://github.com/langchain-ai/deepagents/pull/6773), [#6772](https://github.com/langchain-ai/deepagents/pull/6772)).
- Isolated stored provider endpoints in workspace models ([#6771](https://github.com/langchain-ai/deepagents/pull/6771)).
- Reconciled cache expiry during model requests ([#6763](https://github.com/langchain-ai/deepagents/pull/6763)).
- Preserved dispatch timers across interrupt replays ([#6722](https://github.com/langchain-ai/deepagents/pull/6722)).
- Collapsed idle subagents and reopened them for new work ([#6782](https://github.com/langchain-ai/deepagents/pull/6782)).
- Moved debug MCP server details into a modal ([#6720](https://github.com/langchain-ai/deepagents/pull/6720)).
- Clarified that clearing the chat starts a new thread ([#6726](https://github.com/langchain-ai/deepagents/pull/6726)).

## [0.1.80](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.79...deepagents-code==0.1.80) (2026-10-01)

### Features

- Emit a `cache_expiring` hook before the prompt cache expires ([#6638](https://github.com/langchain-ai/deepagents/pull/6638)).

### Bug Fixes

- Keep the transcript at its current position when opening pickers ([#6635](https://github.com/langchain-ai/deepagents/pull/6635)).
- Share cache-expiring notifications with the TUI ([#6639](https://github.com/langchain-ai/deepagents/pull/6639)).
- Use listed skill paths instead of inferring their locations ([#6711](https://github.com/langchain-ai/deepagents/pull/6711)).
- Correct product and command names in skill guides ([#6637](https://github.com/langchain-ai/deepagents/pull/6637)).

## [0.1.79](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.78...deepagents-code==0.1.79) (2026-09-29)

### Bug Fixes

- MCP tool calls now use configurable timeouts to prevent them from hanging indefinitely ([#6625](https://github.com/langchain-ai/deepagents/pull/6625)).
- Stdio MCP servers now start in the session directory ([#6626](https://github.com/langchain-ai/deepagents/pull/6626)).
- JavaScript subagent costs are preserved when resuming a session ([#6433](https://github.com/langchain-ai/deepagents/pull/6433)).
- Thread switching now completes its preflight faster and shows progress sooner ([#6607](https://github.com/langchain-ai/deepagents/pull/6607)).
- The `/effort` setting is now constrained for between-tools thinking ([#6630](https://github.com/langchain-ai/deepagents/pull/6630)).
- CLI help now displays the same defaults used at runtime ([#6613](https://github.com/langchain-ai/deepagents/pull/6613)).
- The incognito label now appears on the chat input border ([#6627](https://github.com/langchain-ai/deepagents/pull/6627)).

## [0.1.78](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.77...deepagents-code==0.1.78) (2026-09-28)

### Features

- Ask isolated side questions with `/btw` ([#6434](https://github.com/langchain-ai/deepagents/pull/6434)).
- Offer to summarize threads and switch when the cache expires ([#6477](https://github.com/langchain-ai/deepagents/pull/6477)).
- Persist project MCP startup denials ([#6597](https://github.com/langchain-ai/deepagents/pull/6597)).

### Bug Fixes

- Show 100 recent threads by default ([#6604](https://github.com/langchain-ai/deepagents/pull/6604)).
- Restore console input after piped prompts on Windows ([#6572](https://github.com/langchain-ai/deepagents/pull/6572)).
- Load resumed conversation history on demand ([#6342](https://github.com/langchain-ai/deepagents/pull/6342)).

## [0.1.77](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.76...deepagents-code==0.1.77) (2026-09-24)

### Bug Fixes

- Preview remote plugin contents before installation ([#6542](https://github.com/langchain-ai/deepagents/pull/6542)).
- Report mis-encoded `config.toml` files created by older config writers ([#6514](https://github.com/langchain-ai/deepagents/pull/6514)).
- Show how to cancel MCP browser login and handle Escape ([#6541](https://github.com/langchain-ai/deepagents/pull/6541)).
- Make workspace configuration warnings actionable ([#6546](https://github.com/langchain-ai/deepagents/pull/6546)).
- Hide prompt search hints when search is unavailable ([#6543](https://github.com/langchain-ai/deepagents/pull/6543)).

## [0.1.76](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.75...deepagents-code==0.1.76) (2026-09-24)

### Features

- Label plugin servers in the MCP viewer ([#6539](https://github.com/langchain-ai/deepagents/pull/6539)).

### Bug Fixes

- Resolve plugin MCP servers during login ([#6524](https://github.com/langchain-ai/deepagents/pull/6524)).
- Keep empty MCP servers searchable and include descriptions in search results ([#6540](https://github.com/langchain-ai/deepagents/pull/6540)).

## [0.1.75](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.74...deepagents-code==0.1.75) (2026-09-23)

### Bug Fixes

- Lazy MCP caches now warm without blocking the event loop ([#6517](https://github.com/langchain-ai/deepagents/pull/6517)).
- Token and cost breakdowns now refresh while the view is open ([#6520](https://github.com/langchain-ai/deepagents/pull/6520)).

## [0.1.74](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.73...deepagents-code==0.1.74) (2026-09-23)

### Features

- Added inline thread mentions & picker via `@@` ([#6197](https://github.com/langchain-ai/deepagents/pull/6197)).
- Usage summaries now show human invocations ([#6500](https://github.com/langchain-ai/deepagents/pull/6500)).

### Bug Fixes

- Retry bare `openai.APIError` exceptions raised mid-stream ([#6499](https://github.com/langchain-ai/deepagents/pull/6499)).
- Keep prompt recall results out of the file picker ([#6494](https://github.com/langchain-ai/deepagents/pull/6494)).
- Read `hooks.json` as UTF-8 in the legacy hook loader ([#6501](https://github.com/langchain-ai/deepagents/pull/6501)).

### Performance Improvements

- Reuse Auto classifier history ([#6056](https://github.com/langchain-ai/deepagents/pull/6056)).
- Rank checkpoint and message row IDs before loading blobs and prompts ([#6488](https://github.com/langchain-ai/deepagents/pull/6488), [#6489](https://github.com/langchain-ai/deepagents/pull/6489)).
- Log thread-loading phase timings ([#6490](https://github.com/langchain-ai/deepagents/pull/6490)).

## [0.1.73](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.72...deepagents-code==0.1.73) (2026-09-22)

### Features

- Added cache bust timer to the footer. ([#6394](https://github.com/langchain-ai/deepagents/pull/6394))
- Added a durable Debug Console cost breakdown. ([#6246](https://github.com/langchain-ai/deepagents/pull/6246))
- Added support for copying the highlighted thread ID with `Ctrl+C`. ([#6431](https://github.com/langchain-ai/deepagents/pull/6431))

### Bug Fixes

- Improved cost-warning behavior by showing session cost warnings in a modal and suppressing historical cost warnings when resuming. ([#6393](https://github.com/langchain-ai/deepagents/pull/6393), [#6471](https://github.com/langchain-ai/deepagents/pull/6471))
- Made thread browsing and resume flows more resilient with recoverable thread-picker resume failures, loading labels for thread details, and a clearer thread message count header. ([#6476](https://github.com/langchain-ai/deepagents/pull/6476), [#6430](https://github.com/langchain-ai/deepagents/pull/6430), [#6428](https://github.com/langchain-ai/deepagents/pull/6428))
- Removed contradictory and invalid system-prompt instructions. ([#6072](https://github.com/langchain-ai/deepagents/pull/6072))
- Preserved `ask_user` consent receipts across user turns and reconciled interrupted tool requests. ([#6307](https://github.com/langchain-ai/deepagents/pull/6307), [#6321](https://github.com/langchain-ai/deepagents/pull/6321))
- Cleaned up newly created sandboxes when setup fails. ([#6475](https://github.com/langchain-ai/deepagents/pull/6475))
- Fixed editable refreshes so they stay anchored to the correct checkout. ([#6455](https://github.com/langchain-ai/deepagents/pull/6455))
- Kept installation locks outside the uv tool directory. ([#6472](https://github.com/langchain-ai/deepagents/pull/6472))
- Improved workspace and runtime diagnostics, including separating access-policy compatibility from runtime identity. ([#6384](https://github.com/langchain-ai/deepagents/pull/6384), [#6386](https://github.com/langchain-ai/deepagents/pull/6386))
- Deduplicated mixed-ID model usage. ([#6432](https://github.com/langchain-ai/deepagents/pull/6432))
- Clarified the compaction prompt. ([#6429](https://github.com/langchain-ai/deepagents/pull/6429))
- Restricted auto classifier IDs to the review batch enum. ([#6250](https://github.com/langchain-ai/deepagents/pull/6250))
- Used UTF-8 for prompts and skill files. ([#6474](https://github.com/langchain-ai/deepagents/pull/6474))

## [0.1.72](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.71...deepagents-code==0.1.72) (2026-09-21)

### Features

- Expanded `read_file` calls now show their arguments. ([#6392](https://github.com/langchain-ai/deepagents/pull/6392))

### Bug Fixes

- Aligned debug log formatting between file and console output. ([#6426](https://github.com/langchain-ai/deepagents/pull/6426))
- Silenced unnecessary decoder traces for non-media paths. ([#6427](https://github.com/langchain-ai/deepagents/pull/6427))

### Performance Improvements

- Skipped transcript scans when submitting prompts for faster prompt submission. ([#6402](https://github.com/langchain-ai/deepagents/pull/6402))

## [0.1.71](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.70...deepagents-code==0.1.71) (2026-09-18)

### Features

- Moved MCP support onto FastMCP and `langchain.mcp`. ([#5922](https://github.com/langchain-ai/deepagents/pull/5922))
- Condensed the current working directory in the status bar from the middle, preserving the end of the path. ([#6252](https://github.com/langchain-ai/deepagents/pull/6252))

### Bug Fixes

- Replaced the composer with prompt search and prevented query feedback. ([#6346](https://github.com/langchain-ai/deepagents/pull/6346))
- Kept absolute paths intact in normal input mode. ([#6379](https://github.com/langchain-ai/deepagents/pull/6379))
- Pinned resumed history to the newest message. ([#6225](https://github.com/langchain-ai/deepagents/pull/6225))
- Improved handling of overflowing pasted content in the chat input so it scrolls correctly. ([#6382](https://github.com/langchain-ai/deepagents/pull/6382))
- Wrapped debug logs before the scrollbar. ([#6219](https://github.com/langchain-ai/deepagents/pull/6219))

## [0.1.70](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.69...deepagents-code==0.1.70) (2026-09-16)

### Bug Fixes

- Fixed prompt clipboard word deletion behavior. ([#6345](https://github.com/langchain-ai/deepagents/pull/6345))
- Clarified unknown model effort in footer. ([#6337](https://github.com/langchain-ai/deepagents/pull/6337))
- Prevented duplicate clicks in the footer model and effort pickers. ([#6344](https://github.com/langchain-ai/deepagents/pull/6344))
- Delayed hook status display in the footer to reduce UI noise. ([#6322](https://github.com/langchain-ai/deepagents/pull/6322))

## [0.1.69](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.68...deepagents-code==0.1.69) (2026-09-14)

### Features

- Update `read_file` output formatting. ([#5648](https://github.com/langchain-ai/deepagents/pull/5648))
- Surface DeepSeek V4.1 Flash in the model picker. ([#6254](https://github.com/langchain-ai/deepagents/pull/6254))
- Surface locally tracked GitHub stacks in agent context. ([#6290](https://github.com/langchain-ai/deepagents/pull/6290))
- Copy a model slug with Ctrl+click. ([#6243](https://github.com/langchain-ai/deepagents/pull/6243))
- Show session length in the Debug Console. ([#6224](https://github.com/langchain-ai/deepagents/pull/6224))

### Bug Fixes

- Price nested usage with its own model and honor completions. ([#6251](https://github.com/langchain-ai/deepagents/pull/6251))
- Drop stale Anthropic thinking blocks. ([#6300](https://github.com/langchain-ai/deepagents/pull/6300))
- Isolate credentials used for user shell tracing. ([#6242](https://github.com/langchain-ai/deepagents/pull/6242))
- Attribute dotenv configuration sources. ([#6222](https://github.com/langchain-ai/deepagents/pull/6222))
- Expose unknown reasoning effort values. ([#6241](https://github.com/langchain-ai/deepagents/pull/6241))
- Open the Debug Console at the bottom of the log. ([#6218](https://github.com/langchain-ai/deepagents/pull/6218))
- Order Debug Console log filters. ([#6217](https://github.com/langchain-ai/deepagents/pull/6217))
- Show the spinner during pre-stream turn setup. ([#6253](https://github.com/langchain-ai/deepagents/pull/6253))
- Demote no-output hint suppression messages to debug logging. ([#6245](https://github.com/langchain-ai/deepagents/pull/6245))

## [0.1.68](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.67...deepagents-code==0.1.68) (2026-09-10)

### Features

- Recommended GLM 5.3 models are now available in code workflows ([#6211](https://github.com/langchain-ai/deepagents/pull/6211)).

### Bug Fixes

- Added pricing support for Fireworks GLM-5.3 and GLM-5.3 Flash usage ([#6221](https://github.com/langchain-ai/deepagents/pull/6221), [#6223](https://github.com/langchain-ai/deepagents/pull/6223)).
- Workspace switches now ask for confirmation before restarting the server ([#6178](https://github.com/langchain-ai/deepagents/pull/6178)).
- Effort changes are now included in cache identity for OpenAI and Anthropic requests ([#6196](https://github.com/langchain-ai/deepagents/pull/6196)).
- Standardized the recent-thread environment variable ([#6205](https://github.com/langchain-ai/deepagents/pull/6205)).
- Silenced warnings when the themes config is absent ([#6220](https://github.com/langchain-ai/deepagents/pull/6220)).

## [0.1.67](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.66...deepagents-code==0.1.67) (2026-09-09)

### Features

- Added `GPT-6 Astra` support ([#6141](https://github.com/langchain-ai/deepagents/issues/6141)).
- Reuses the server across workspace switches ([#6152](https://github.com/langchain-ai/deepagents/issues/6152)).
- Limits thread resume age ([#6068](https://github.com/langchain-ai/deepagents/issues/6068)).

### Bug Fixes

- Improved workspace isolation by resolving project policy per workspace, scoping project dotenv to workspaces, and isolating LangSmith auth and workspace tracing ([#6064](https://github.com/langchain-ai/deepagents/issues/6064), [#5980](https://github.com/langchain-ai/deepagents/issues/5980), [#6061](https://github.com/langchain-ai/deepagents/issues/6061)).
- Improved transcript tail reconciliation by bounding and serializing reconciliation work ([#6057](https://github.com/langchain-ai/deepagents/issues/6057), [#6143](https://github.com/langchain-ai/deepagents/issues/6143)).
- Refuses a second sandbox workspace and moves sandbox creation and entry off the guarded event loop ([#5979](https://github.com/langchain-ai/deepagents/issues/5979), [#6017](https://github.com/langchain-ai/deepagents/issues/6017)).
- Surfaces stale updates in-session ([#6063](https://github.com/langchain-ai/deepagents/issues/6063)).
- Surfaces the LangSmith credential in `dcode config` ([#6083](https://github.com/langchain-ai/deepagents/issues/6083)).
- Offloads server config imports ([#6089](https://github.com/langchain-ai/deepagents/issues/6089)).
- Correctly parses extra skill directories with the platform separator ([#6151](https://github.com/langchain-ai/deepagents/issues/6151)).

## [0.1.66](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.65...deepagents-code==0.1.66) (2026-09-03)

### Features

- Defaulted general-purpose subagents to fork mode ([#6024](https://github.com/langchain-ai/deepagents/issues/6024)).
- Defaulted the Auto classifier by provider ([#6039](https://github.com/langchain-ai/deepagents/issues/6039)).
- Added support for binding conversations to a recorded workspace ([#5946](https://github.com/langchain-ai/deepagents/issues/5946)).
- Added tracing for the effective approval mode ([#5972](https://github.com/langchain-ai/deepagents/issues/5972)).

### Bug Fixes

- Fixed request-time working directory binding and now show the bound workspace in shell approvals ([#5968](https://github.com/langchain-ai/deepagents/issues/5968), [#5966](https://github.com/langchain-ai/deepagents/issues/5966)).
- Fixed marketplace plugin installs to accept bare relative source paths and identify the rejected source path when validation fails ([#5959](https://github.com/langchain-ai/deepagents/issues/5959), [#5960](https://github.com/langchain-ai/deepagents/issues/5960)).
- Classifier errors now include model names ([#6038](https://github.com/langchain-ai/deepagents/issues/6038)).
- Updated the splash screen to use a sharp border ([#5970](https://github.com/langchain-ai/deepagents/issues/5970)).

### Performance Improvements

- Reduced QuickJS middleware tracing overhead by omitting trace inputs ([#6015](https://github.com/langchain-ai/deepagents/issues/6015)).

## [0.1.65](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.64...deepagents-code==0.1.65) (2026-08-28)

### Features

- Added Python extension support, including discovery, configuration and loading, runtime hosting, and trust and inspection UX ([#5631](https://github.com/langchain-ai/deepagents/issues/5631), [#5632](https://github.com/langchain-ai/deepagents/issues/5632), [#5633](https://github.com/langchain-ai/deepagents/issues/5633), [#5634](https://github.com/langchain-ai/deepagents/issues/5634))
- Added a `/summarization-model` command and model picker for configuring the summarization model ([#5884](https://github.com/langchain-ai/deepagents/issues/5884), [#5932](https://github.com/langchain-ai/deepagents/issues/5932))
- Added support for optional extra uninstall commands ([#5875](https://github.com/langchain-ai/deepagents/issues/5875))
- Added an option to show visible reasoning ([#5887](https://github.com/langchain-ai/deepagents/issues/5887))

### Bug Fixes

- Improved model and task reliability by retrying interrupted model streams, recovering stale pending work before compaction, and isolating parallel `task` failures ([#5905](https://github.com/langchain-ai/deepagents/issues/5905), [#5909](https://github.com/langchain-ai/deepagents/issues/5909), [#5954](https://github.com/langchain-ai/deepagents/issues/5954))
- Improved server restart handling by waiting for graph readiness before continuing ([#5947](https://github.com/langchain-ai/deepagents/issues/5947))
- Capped MCP tool names for provider compatibility ([#5953](https://github.com/langchain-ai/deepagents/issues/5953))
- Fixed Auto approval gate path expansion handling and now records Auto classifier deadline misses as traced errors ([#5941](https://github.com/langchain-ai/deepagents/issues/5941), [#5944](https://github.com/langchain-ai/deepagents/issues/5944))
- Completed ASCII UI fallbacks and hid inactive F2 tool hints ([#5930](https://github.com/langchain-ai/deepagents/issues/5930), [#5939](https://github.com/langchain-ai/deepagents/issues/5939))
- Isolated debug logs by thread ([#5921](https://github.com/langchain-ai/deepagents/issues/5921))
- Updated rubric grader model changes to apply without a restart ([#5885](https://github.com/langchain-ai/deepagents/issues/5885))

## [0.1.64](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.63...deepagents-code==0.1.64) (2026-08-28)

### Features

- Added trace metadata attribution for skill invocations ([#5925](https://github.com/langchain-ai/deepagents/issues/5925)).
- Added a list of MCP servers that require login ([#5867](https://github.com/langchain-ai/deepagents/issues/5867)).
- Added the ability to copy the current model from the picker header ([#5904](https://github.com/langchain-ai/deepagents/issues/5904)).
- Linked the doctor commit hash to GitHub ([#5920](https://github.com/langchain-ai/deepagents/issues/5920)).
- Standardized the external editor shortcut ([#5911](https://github.com/langchain-ai/deepagents/issues/5911)).

### Bug Fixes

- Deferred recursion-limit handling to the LangGraph server ([#5882](https://github.com/langchain-ai/deepagents/issues/5882)).
- Disabled Git terminal prompts in `execute` ([#5878](https://github.com/langchain-ai/deepagents/issues/5878)).
- Improved privacy and debug-only visibility for MCP token and editable paths ([#5866](https://github.com/langchain-ai/deepagents/issues/5866), [#5850](https://github.com/langchain-ai/deepagents/issues/5850)).
- Updated the model-switch warning to point to `/offload` ([#5901](https://github.com/langchain-ai/deepagents/issues/5901)).
- Rejected stale successful updates ([#5847](https://github.com/langchain-ai/deepagents/issues/5847)).
- Fixed thread timestamp rendering on systems without the glibc-only `%-I` `strftime` flag ([#5886](https://github.com/langchain-ai/deepagents/issues/5886)).
- Respected ASCII mode in the splash border ([#5923](https://github.com/langchain-ai/deepagents/issues/5923)).
- Skipped unchanged config writes ([#5919](https://github.com/langchain-ai/deepagents/issues/5919)).
- Skipped uncorrelated-result warnings for auto-mode policy denials ([#5869](https://github.com/langchain-ai/deepagents/issues/5869)).

## [0.1.63](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.62...deepagents-code==0.1.63) (2026-08-26)

### Features

- Added Baseten `zai-org/GLM-5.3-Flash` to the model switcher ([#5844](https://github.com/langchain-ai/deepagents/issues/5844)).
- Added support for loading managed config from a remote source ([#5776](https://github.com/langchain-ai/deepagents/issues/5776)).
- Added retry middleware for transient model errors in model nodes ([#4569](https://github.com/langchain-ai/deepagents/issues/4569)).

### Fixes

- Fixed live cost tracking for dynamic subagents ([#5833](https://github.com/langchain-ai/deepagents/issues/5833)).
- Improved `clear` command descriptions ([#5841](https://github.com/langchain-ai/deepagents/issues/5841)).
- Allowed instrumental Auto actions ([#5832](https://github.com/langchain-ai/deepagents/issues/5832)).
- Ensured traces are flushed before server shutdown ([#5837](https://github.com/langchain-ai/deepagents/issues/5837)).
- Made the debug log path click-to-copy ([#5845](https://github.com/langchain-ai/deepagents/issues/5845)).

## [0.1.62](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.61...deepagents-code==0.1.62) (2026-08-26)

### Features

- Added `/context-doctor` for inspecting and troubleshooting context issues ([#5830](https://github.com/langchain-ai/deepagents/issues/5830)).
- Added warning when switching models mid-session ([#5829](https://github.com/langchain-ai/deepagents/issues/5829)).
- Added support for `DEEPAGENTS_HOME` ([#5773](https://github.com/langchain-ai/deepagents/issues/5773)).
- (Re-)Enabled secret redaction by default ([#5816](https://github.com/langchain-ai/deepagents/issues/5816)).
- Improved update visibility by showing cached updates in version output ([#5817](https://github.com/langchain-ai/deepagents/issues/5817)).
- Improved prompts and pickers: the stale editable-deps prompt now defaults to `Refresh environment now`, and the model picker shows an Escape hint ([#5810](https://github.com/langchain-ai/deepagents/issues/5810), [#5775](https://github.com/langchain-ai/deepagents/issues/5775)).
- Added CLI config provider support ([#5774](https://github.com/langchain-ai/deepagents/issues/5774)).

### Bug Fixes

- Fixed refreshed local context handling after compaction to reduce cache busts ([#5828](https://github.com/langchain-ai/deepagents/issues/5828)).
- Preserved goal notice history for prompt caching ([#5823](https://github.com/langchain-ai/deepagents/issues/5823)).
- Improved rubric coverage checks ([#5369](https://github.com/langchain-ai/deepagents/issues/5369)).
- Protected the TUI from native stderr writes ([#5813](https://github.com/langchain-ai/deepagents/issues/5813)).
- Fixed Git origin resolution from worktree common Git directories ([#5818](https://github.com/langchain-ai/deepagents/issues/5818)).
- Fixed prompt clipboard behavior so Tab inserts instead of pages ([#5820](https://github.com/langchain-ai/deepagents/issues/5820)).

### Performance Improvements

- Reduced tracing overhead by omitting middleware trace inputs ([#5815](https://github.com/langchain-ai/deepagents/issues/5815)).

## [0.1.61](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.60...deepagents-code==0.1.61) (2026-08-24)

### Features

- Added `google_anthropic_vertex` provider support for Claude on Vertex AI ([#5760](https://github.com/langchain-ai/deepagents/issues/5760)).
- Enforced configured model allowlists ([#5649](https://github.com/langchain-ai/deepagents/issues/5649)).
- Injected goal and rubric context directly, replacing `get_goal` and `get_rubric` ([#5041](https://github.com/langchain-ai/deepagents/issues/5041)).
- Made `/offload` server-owned ([#5261](https://github.com/langchain-ai/deepagents/issues/5261)).
- Added prompt clipboard support ([#5733](https://github.com/langchain-ai/deepagents/issues/5733)).
- Show Auto approval review progress ([#5729](https://github.com/langchain-ai/deepagents/issues/5729)).

### Bug Fixes

- Kept long thread resumes responsive ([#5772](https://github.com/langchain-ai/deepagents/issues/5772)).
- Render first streamed text immediately ([#5761](https://github.com/langchain-ai/deepagents/issues/5761)).
- Show the incognito shell command widget ([#5768](https://github.com/langchain-ai/deepagents/issues/5768)).
- Only highlight actionable tool rows ([#5769](https://github.com/langchain-ai/deepagents/issues/5769)).
- Warn and ignore `--auto-approve` and `--yolo` in headless mode ([#5750](https://github.com/langchain-ai/deepagents/issues/5750)).
- Sweep expired history archives at startup ([#5751](https://github.com/langchain-ai/deepagents/issues/5751)).
- Clarified auth environment setup ([#5767](https://github.com/langchain-ai/deepagents/issues/5767)).

## [0.1.60](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.59...deepagents-code==0.1.60) (2026-08-23)

### Features

- Added `editable` trace metadata ([#5737](https://github.com/langchain-ai/deepagents/issues/5737)) ([23b83ad](https://github.com/langchain-ai/deepagents/commit/23b83ad50f63d241d0069a3dc426d43b211adf2e)).
- Added shell command highlighting in the chat input ([#5675](https://github.com/langchain-ai/deepagents/issues/5675)) ([d711bc6](https://github.com/langchain-ai/deepagents/commit/d711bc61300090181dc89e3e116e8b343fb65425)).
- Made project `.env` loading configurable ([#5726](https://github.com/langchain-ai/deepagents/issues/5726)) ([995cad6](https://github.com/langchain-ai/deepagents/commit/995cad67519af294851282133f8c40f643807c88)).
- Unified notification center and settings ([#5698](https://github.com/langchain-ai/deepagents/issues/5698)) ([9767f42](https://github.com/langchain-ai/deepagents/commit/9767f420c622a31a7511c4601739534ddc6062a7)).

### Bug Fixes

- Blocked dotenv git config injection keys ([#5723](https://github.com/langchain-ai/deepagents/issues/5723)) ([328f916](https://github.com/langchain-ai/deepagents/commit/328f9160e0f95a459be8ad57f76e7178b24a3ef8)).
- Persisted Auto approval mode between sessions and simplified Auto fallback copy ([#5665](https://github.com/langchain-ai/deepagents/issues/5665)) ([3ac059e](https://github.com/langchain-ai/deepagents/commit/3ac059e1574963fe216692642aa1b1a4044daaa9)), ([#5670](https://github.com/langchain-ai/deepagents/issues/5670)) ([42afcde](https://github.com/langchain-ai/deepagents/commit/42afcded97029070f393232778c84aaf3b69fb1c)).
- Fixed recognition of in-flight trace messages ([#5738](https://github.com/langchain-ai/deepagents/issues/5738)) ([f1d1f63](https://github.com/langchain-ai/deepagents/commit/f1d1f632812a85646d25ac2f3d2d7f39b65a0b49)).
- Increased the warm limit to 800 ([#5728](https://github.com/langchain-ai/deepagents/issues/5728)) ([f954cde](https://github.com/langchain-ai/deepagents/commit/f954cde37f1171adc2ec3f1516a0393bded47e82)).
- Improved text selection by supporting `Shift` + `click` to extend selections ([#5732](https://github.com/langchain-ai/deepagents/issues/5732)) ([e05931b](https://github.com/langchain-ai/deepagents/commit/e05931b3016ed3d1500df0c5b77402f457ee5686)).
- Polished notification settings by removing expand flicker and the trailing disclosure glyph ([#5734](https://github.com/langchain-ai/deepagents/issues/5734)) ([5397812](https://github.com/langchain-ai/deepagents/commit/5397812ad5f217cd84f871f121cf9ea8f3d63f4f)).
- Improved authentication footers with contextual actions ([#5690](https://github.com/langchain-ai/deepagents/issues/5690)) ([074a501](https://github.com/langchain-ai/deepagents/commit/074a5019e1f3edfd589614774958400d051e5fe1)).
- Standardized modal navigation hints ([#5699](https://github.com/langchain-ai/deepagents/issues/5699)) ([85c6833](https://github.com/langchain-ai/deepagents/commit/85c6833734a547e968221c1199a769d7aac69430)).
- Aligned wrapped debug snapshot values ([#5727](https://github.com/langchain-ai/deepagents/issues/5727)) ([1f74959](https://github.com/langchain-ai/deepagents/commit/1f7495949232fe2e3e3328b6ff9054c202002f95)).

## [0.1.59](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.58...deepagents-code==0.1.59) (2026-08-20)

### Features

- Added support for `managed_config.toml` configuration ([#5604](https://github.com/langchain-ai/deepagents/issues/5604))
- Multi-select `ask_user` answers are now encoded as JSON arrays ([#5660](https://github.com/langchain-ai/deepagents/issues/5660))
- Made teardown usage stats configurable ([#5696](https://github.com/langchain-ai/deepagents/issues/5696))
- Footer pickers now open on click ([#5674](https://github.com/langchain-ai/deepagents/issues/5674))
- Replaced Gemini 3.6 Flash with Gemini 3.7 Flash ([#5681](https://github.com/langchain-ai/deepagents/issues/5681))

### Bug fixes

- Made tool argument validation errors recoverable ([#5659](https://github.com/langchain-ai/deepagents/issues/5659))
- Improved streaming performance for tool-call arguments to run in linear time ([#5712](https://github.com/langchain-ai/deepagents/issues/5712))
- Fixed durable-mask config resolution with ranked resolver behavior ([#5672](https://github.com/langchain-ai/deepagents/issues/5672))
- Skipped background sync in Apple Terminal ([#5666](https://github.com/langchain-ai/deepagents/issues/5666))
- Hid thread IDs when tracing is disabled ([#5692](https://github.com/langchain-ai/deepagents/issues/5692))
- Kept installed providers visible in `/auth` ([#5689](https://github.com/langchain-ai/deepagents/issues/5689))
- Preloaded the auth UI before notification handoff ([#5697](https://github.com/langchain-ai/deepagents/issues/5697))
- Updated and clarified UI copy across Auto mode, YOLO hints, classifier notices, `/tokens`, line-number toggles, review failures, onboarding Tavily cancellation, and OpenAI subscription login labels ([#5685](https://github.com/langchain-ai/deepagents/issues/5685), [#5694](https://github.com/langchain-ai/deepagents/issues/5694), [#5684](https://github.com/langchain-ai/deepagents/issues/5684), [#5687](https://github.com/langchain-ai/deepagents/issues/5687), [#5680](https://github.com/langchain-ai/deepagents/issues/5680), [#5688](https://github.com/langchain-ai/deepagents/issues/5688), [#5686](https://github.com/langchain-ai/deepagents/issues/5686), [#5691](https://github.com/langchain-ai/deepagents/issues/5691), [#5693](https://github.com/langchain-ai/deepagents/issues/5693))
- Removed the `Muse Spark 1.1` recommendation ([#5683](https://github.com/langchain-ai/deepagents/issues/5683))

## [0.1.58](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.57...deepagents-code==0.1.58) (2026-08-19)

### Breaking Changes

- `deepagents-code` now requires Python 3.12 or newer. ([#5603](https://github.com/langchain-ai/deepagents/issues/5603))

### Features

- Added OpenRouter `z-ai/glm-5.3` to the model switcher. ([#5641](https://github.com/langchain-ai/deepagents/issues/5641))
- Added support for re-authenticating MCP servers from the viewer. ([#5637](https://github.com/langchain-ai/deepagents/issues/5637))
- Footer pickers can now be opened with `ctrl+click`. ([#5611](https://github.com/langchain-ai/deepagents/issues/5611))
- Resume hints now account for `TERM_PROGRAM` support before showing terminal-specific guidance. ([#5580](https://github.com/langchain-ai/deepagents/issues/5580))

### Fixes

- Completed the `dcode config` command surface. ([#5581](https://github.com/langchain-ai/deepagents/issues/5581))
- Made `/offload` interruptible. ([#5590](https://github.com/langchain-ai/deepagents/issues/5590))
- Improved chat and footer UI behavior: rapid typing stays visible, double-click collapses a resized chat input, and the MCP footer wraps on narrow windows. ([#5424](https://github.com/langchain-ai/deepagents/issues/5424), [#5578](https://github.com/langchain-ai/deepagents/issues/5578), [#5651](https://github.com/langchain-ai/deepagents/issues/5651))
- Captured stdio MCP server stderr in the logger. ([#5610](https://github.com/langchain-ai/deepagents/issues/5610))
- Drained hook pipes after timeout. ([#5606](https://github.com/langchain-ai/deepagents/issues/5606))
- Grouped resume trace rounds. ([#5593](https://github.com/langchain-ai/deepagents/issues/5593))
- Omitted web-search prompt guidance when web search is unavailable. ([#5602](https://github.com/langchain-ai/deepagents/issues/5602))
- Resolved message pointer shapes per cell. ([#5592](https://github.com/langchain-ai/deepagents/issues/5592))

## [0.1.57](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.56...deepagents-code==0.1.57) (2026-08-18)

### Features

- Added warnings before expensive cold-cache turns and trust user-declared endpoints for cold-cache policies ([#5439](https://github.com/langchain-ai/deepagents/issues/5439), [#5462](https://github.com/langchain-ai/deepagents/issues/5462)).
- Made the chat input resizable by dragging its top border ([#5524](https://github.com/langchain-ai/deepagents/issues/5524)).
- Added a `multi_select` question type to `ask_user` ([#5097](https://github.com/langchain-ai/deepagents/issues/5097)).
- Added support for ACP approval modes ([#5394](https://github.com/langchain-ai/deepagents/issues/5394)).
- Added `DeepSeek-V4-Pro-0813` to the model picker ([#5512](https://github.com/langchain-ai/deepagents/issues/5512)).
- Show conversation turns alongside message counts ([#5571](https://github.com/langchain-ai/deepagents/issues/5571)).
- Include `TERM_PROGRAM` in the resume hint ([#5548](https://github.com/langchain-ai/deepagents/issues/5548)).

### Bug Fixes

- Report total context after `/offload` ([#5488](https://github.com/langchain-ai/deepagents/issues/5488)).
- Fixed transcript and thread restoration issues, including hydration lag, scrolling resumed threads to the bottom, and hiding empty previous-thread hints ([#5479](https://github.com/langchain-ai/deepagents/issues/5479), [#5543](https://github.com/langchain-ai/deepagents/issues/5543), [#5552](https://github.com/langchain-ai/deepagents/issues/5552)).
- Fixed Auto-mode approval handling by binding "yes" to the paired `ask_user` question and avoiding duplicate Auto denial notices ([#5038](https://github.com/langchain-ai/deepagents/issues/5038), [#5501](https://github.com/langchain-ai/deepagents/issues/5501)).
- Improved reload behavior by keeping the chat input responsive during `/reload`, reporting MCP server changes, and avoiding plugin reload prompt flashes or startup hints ([#5529](https://github.com/langchain-ai/deepagents/issues/5529), [#5504](https://github.com/langchain-ai/deepagents/issues/5504), [#5500](https://github.com/langchain-ai/deepagents/issues/5500), [#5502](https://github.com/langchain-ai/deepagents/issues/5502)).
- Improved dependency update UI by preserving editable fields and hiding dependency details after updates ([#5521](https://github.com/langchain-ai/deepagents/issues/5521), [#5519](https://github.com/langchain-ai/deepagents/issues/5519)).
- Fixed chat UI polish issues, including detached spacer mount anchors, the unfocused input cursor, and relative timestamp toggle display ([#5516](https://github.com/langchain-ai/deepagents/issues/5516), [#5258](https://github.com/langchain-ai/deepagents/issues/5258), [#5503](https://github.com/langchain-ai/deepagents/issues/5503)).
- Refresh the splash version after updates ([#5520](https://github.com/langchain-ai/deepagents/issues/5520)).

## [0.1.56](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.55...deepagents-code==0.1.56) (2026-08-14)

### Features

- Personalized external editor hints to better match your setup ([#5445](https://github.com/langchain-ai/deepagents/issues/5445))

### Bug Fixes

- Improved dependency warning, Auto classifier, and paste expansion messages for clearer, more concise prompts and toasts ([#5489](https://github.com/langchain-ai/deepagents/issues/5489), [#5446](https://github.com/langchain-ai/deepagents/issues/5446), [#5443](https://github.com/langchain-ai/deepagents/issues/5443))
- Queued `/copy` commands while generation is active so they run at the right time ([#5447](https://github.com/langchain-ai/deepagents/issues/5447))
- Hid invalid cache metrics from the UI ([#5475](https://github.com/langchain-ai/deepagents/issues/5475))
- Fixed forced-compaction forks by preserving the `session_id` ([#5492](https://github.com/langchain-ai/deepagents/issues/5492))
- Stopped passing the removed `checkpoint_metadata` field ([#5473](https://github.com/langchain-ai/deepagents/issues/5473))

## [0.1.55](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.54...deepagents-code==0.1.55) (2026-08-12)

### Features

- Added a `/context` usage report for inspecting context consumption ([#5407](https://github.com/langchain-ai/deepagents/issues/5407)).
- Added a cache and context status row for at-a-glance session state ([#5408](https://github.com/langchain-ai/deepagents/issues/5408)).
- Added configurable warnings when a session exceeds the configured cost threshold ([#5405](https://github.com/langchain-ai/deepagents/issues/5405)).
- Added support for persisting and reconfiguring ACP sessions ([#5366](https://github.com/langchain-ai/deepagents/issues/5366)).
- Added automatic updates for installed plugins ([#5368](https://github.com/langchain-ai/deepagents/issues/5368)).
- Added a toggle for diff line numbers ([#5427](https://github.com/langchain-ai/deepagents/issues/5427)).
- `Ctrl+S` in `/auto model` now stores `[models].auto_classifier` ([#5313](https://github.com/langchain-ai/deepagents/issues/5313)).

### Fixes

- Restored edit diffs in resumed threads ([#5391](https://github.com/langchain-ai/deepagents/issues/5391)).
- Added a resume hint after crashes ([#5412](https://github.com/langchain-ai/deepagents/issues/5412)).
- Clarified the project hooks trust prompt and stopped prompting for user hooks ([#5426](https://github.com/langchain-ai/deepagents/issues/5426)).
- Cleared dynamic subagents on the next turn ([#5437](https://github.com/langchain-ai/deepagents/issues/5437)).
- Improved grouped tool summaries by counting distinct targets ([#5409](https://github.com/langchain-ai/deepagents/issues/5409)).
- Improved ask-user choice wrapping and selection styling ([#5442](https://github.com/langchain-ai/deepagents/issues/5442)).
- Serialized `dcode` self-upgrades across processes ([#5252](https://github.com/langchain-ai/deepagents/issues/5252)).
- Added warnings for stale dependencies in editable installs ([#5386](https://github.com/langchain-ai/deepagents/issues/5386)).
- Hid incomplete extras from version output ([#5352](https://github.com/langchain-ai/deepagents/issues/5352)).
- Removed the optional-provider startup tip ([#5421](https://github.com/langchain-ai/deepagents/issues/5421)).
- Removed the "Message restored to input" toast ([#5253](https://github.com/langchain-ai/deepagents/issues/5253)).

## [0.1.54](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.53...deepagents-code==0.1.54) (2026-08-07)

### Features

- Added Meta `muse-spark-1.2` to the model switcher ([#5389](https://github.com/langchain-ai/deepagents/issues/5389)).
- Improved diff readability with quieter hunks and word-level highlights ([#5106](https://github.com/langchain-ai/deepagents/issues/5106)).

### Bug Fixes

- Hid startup tips when resuming threads ([#5349](https://github.com/langchain-ai/deepagents/issues/5349)).
- Prevented post-tool hook replay ([#5376](https://github.com/langchain-ai/deepagents/issues/5376)).
- Stored update logs under the OS cache directory ([#5363](https://github.com/langchain-ai/deepagents/issues/5363)).

## [0.1.53](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.52...deepagents-code==0.1.53) (2026-08-06)

### Features

- Added pricing coverage with Baseten built-in overrides and local fallback overrides when `genai-prices` is missing data ([#5312](https://github.com/langchain-ai/deepagents/issues/5312), [#5304](https://github.com/langchain-ai/deepagents/issues/5304)).
- Suggest compacting large resumed threads ([#5318](https://github.com/langchain-ai/deepagents/issues/5318)).
- Added terminal program trace metadata ([#5329](https://github.com/langchain-ai/deepagents/issues/5329)).

### Bug Fixes

- Preserved runtime offload archive routing ([#5328](https://github.com/langchain-ai/deepagents/issues/5328)).
- Always restart after a successful startup auto-update ([#5317](https://github.com/langchain-ai/deepagents/issues/5317)).
- Fixed leaked turn coroutines and SQLite handles ([#5218](https://github.com/langchain-ai/deepagents/issues/5218)).
- Keep MCP shutdown-race tracebacks from appearing in the terminal ([#5325](https://github.com/langchain-ai/deepagents/issues/5325)).
- Open the `/auto model` selector immediately while connecting ([#5341](https://github.com/langchain-ai/deepagents/issues/5341)).
- Route failures to `PostToolUseFailure` ([#5315](https://github.com/langchain-ai/deepagents/issues/5315)).
- Use dismissed copy for ask-user prompts ([#5331](https://github.com/langchain-ai/deepagents/issues/5331)).

## [0.1.52](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.51...deepagents-code==0.1.52) (2026-08-04)

### Features

- Hooks v2 is now generally available, with support for loading hooks from installed plugins. ([#5307](https://github.com/langchain-ai/deepagents/issues/5307), [#5198](https://github.com/langchain-ai/deepagents/issues/5198))
- Auto approval classifier configuration now supports selecting the classifier model and setting a review timeout. ([#5205](https://github.com/langchain-ai/deepagents/issues/5205), [#5302](https://github.com/langchain-ai/deepagents/issues/5302))
- HITL rejection reasons are now framed for the model, and the approval menu makes reject-with-feedback easier to discover. ([#5259](https://github.com/langchain-ai/deepagents/issues/5259), [#5260](https://github.com/langchain-ai/deepagents/issues/5260))
- Added a tri-state `DEEPAGENTS_CODE_ONBOARDING` environment variable. ([#5301](https://github.com/langchain-ai/deepagents/issues/5301))
- The `/model` footer Ctrl+N hint now follows the current display mode. ([#5247](https://github.com/langchain-ai/deepagents/issues/5247))
- The price catalog now refreshes hourly in the background. ([#5264](https://github.com/langchain-ai/deepagents/issues/5264))
- Updated recommendations to include DeepSeek V4 Flash 0731. ([#5244](https://github.com/langchain-ai/deepagents/issues/5244))

### Bug Fixes

- Fixed several Hooks v2 lifecycle issues: session-end teardown is now bounded, hooks refresh after cwd switches, malformed hook resumes are handled, hook stops surface without agent errors, and unused `SessionEndCause` members were removed. ([#5248](https://github.com/langchain-ai/deepagents/issues/5248), [#5249](https://github.com/langchain-ai/deepagents/issues/5249), [#5233](https://github.com/langchain-ai/deepagents/issues/5233), [#5276](https://github.com/langchain-ai/deepagents/issues/5276), [#5240](https://github.com/langchain-ai/deepagents/issues/5240))
- `PreCompact` now fires before auto-compaction. ([#5277](https://github.com/langchain-ai/deepagents/issues/5277))

## [0.1.51](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.50...deepagents-code==0.1.51) (2026-07-31)

### Features

- The status bar and usage view now show the running session cost. ([#5036](https://github.com/langchain-ai/deepagents/issues/5036))
- Removed redundant `shell` and `web_search` prompt guidance. ([#5213](https://github.com/langchain-ai/deepagents/issues/5213))
- After switching threads, Deep Agents now points back to the previous thread. ([#5172](https://github.com/langchain-ai/deepagents/issues/5172))
- Leaving `/mcp` with pending toggles now prompts you to reconnect. ([#5211](https://github.com/langchain-ai/deepagents/issues/5211))
- `dcode config get` now accepts configuration sections. ([#5134](https://github.com/langchain-ai/deepagents/issues/5134))

### Fixes

- Kept the `/goal` criteria prompt responsive. ([#5142](https://github.com/langchain-ai/deepagents/issues/5142))
- Improved goal handling so underspecified objectives can be resolved from conversation context. ([#5201](https://github.com/langchain-ai/deepagents/issues/5201))
- Released the turn when an interrupted worker never starts. ([#5196](https://github.com/langchain-ai/deepagents/issues/5196))
- Hid timestamp footers together with their associated rows. ([#5167](https://github.com/langchain-ai/deepagents/issues/5167))
- Fixed editable SDK detection by scanning and correlating SDK locations more accurately. ([#5199](https://github.com/langchain-ai/deepagents/issues/5199))
- Improved `doctor` output to explain why it may not have a latest-version answer. ([#5209](https://github.com/langchain-ai/deepagents/issues/5209))

## [0.1.50](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.49...deepagents-code==0.1.50) (2026-07-30)

### Highlights

- Added project hooks workspace trust and expanded Hooks v2 support with client and server lifecycle events plus runtime feedback ([#5105](https://github.com/langchain-ai/deepagents/issues/5105), [#5104](https://github.com/langchain-ai/deepagents/issues/5104), [#4997](https://github.com/langchain-ai/deepagents/issues/4997), [#5045](https://github.com/langchain-ai/deepagents/issues/5045)).
- Added an option to mute the "YOLO is active" toast ([#5103](https://github.com/langchain-ai/deepagents/issues/5103)).
- Made the splash screen `thread` ID clickable to copy it ([#5173](https://github.com/langchain-ai/deepagents/issues/5173)).
- Show `ask_user` answers directly on the answered tool row ([#5100](https://github.com/langchain-ai/deepagents/issues/5100)).
- Show a toast when submitting an empty required `ask_user` answer ([#5095](https://github.com/langchain-ai/deepagents/issues/5095)).
- Added thread message counts to the Debug Console ([#5117](https://github.com/langchain-ai/deepagents/issues/5117)).

### Fixes and improvements

- Gated Hooks v2 behind `DEEPAGENTS_CODE_EXPERIMENTAL` and improved hook resume stability across identity and Command tool results ([#5146](https://github.com/langchain-ai/deepagents/issues/5146), [#5176](https://github.com/langchain-ai/deepagents/issues/5176)).
- Kept server hook state out of task results ([#5164](https://github.com/langchain-ai/deepagents/issues/5164)).
- Stopped duplicate Auto transcript events during interrupt replay ([#5157](https://github.com/langchain-ai/deepagents/issues/5157)).
- Kept `/update` and `/install --package` prompts responsive ([#5127](https://github.com/langchain-ai/deepagents/issues/5127)).
- Refreshed the `/threads` cache after each turn ([#5174](https://github.com/langchain-ai/deepagents/issues/5174)).
- Anchored toasts above the chat input and added a toast when media is dropped into a free-text question ([#5101](https://github.com/langchain-ai/deepagents/issues/5101), [#5099](https://github.com/langchain-ai/deepagents/issues/5099)).
- Improved thread status message styling and links ([#5118](https://github.com/langchain-ai/deepagents/issues/5118)).
- Made resume hints echo the launched command name ([#5119](https://github.com/langchain-ai/deepagents/issues/5119)).
- Scoped selection copy to the clicked screen ([#5140](https://github.com/langchain-ai/deepagents/issues/5140)).
- Ignored mouse hits on detached widgets ([#5114](https://github.com/langchain-ai/deepagents/issues/5114)).

## [0.1.49](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.48...deepagents-code==0.1.49) (2026-07-27)

### Features

- Added recognition for LangSmith Gateway credentials. ([#5042](https://github.com/langchain-ai/deepagents/issues/5042))
- Added slash commands for mode changes and an option to escape to manual mode from the YOLO notice. ([#5092](https://github.com/langchain-ai/deepagents/issues/5092))
- Added an `install` subcommand. ([#5080](https://github.com/langchain-ai/deepagents/issues/5080))

### Bug Fixes

- Kept the post-install restart modal responsive. ([#5086](https://github.com/langchain-ai/deepagents/issues/5086))
- Moved server graph bootstrap `cwd` calls off the event loop. ([#5081](https://github.com/langchain-ai/deepagents/issues/5081))
- Improved handling of long transcript user messages with toast notifications and expansion. ([#5073](https://github.com/langchain-ai/deepagents/issues/5073))
- Show model no-op notices as toasts instead of inline messages. ([#5074](https://github.com/langchain-ai/deepagents/issues/5074))

## [0.1.48](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.47...deepagents-code==0.1.48) (2026-07-27)

### Features

- Added Fireworks `kimi-k3`, GLM-5.2-Fast, and Kimi-K3 to model selection and recommended models. ([#5082](https://github.com/langchain-ai/deepagents/issues/5082), [#5072](https://github.com/langchain-ai/deepagents/issues/5072))
- Migrated legacy hooks to v2 events. ([#4971](https://github.com/langchain-ai/deepagents/issues/4971))

### Bug Fixes

- Require an `AGENTS.md` marker for `/agent` discovery, resolving unintended discovery behavior. ([#5076](https://github.com/langchain-ai/deepagents/issues/5076), closes [#4991](https://github.com/langchain-ai/deepagents/issues/4991))
- Removed the redundant `/restart` hint from the restart prompt. ([#5083](https://github.com/langchain-ai/deepagents/issues/5083))
- Removed the caret flash in plugin type-to-search. ([#5078](https://github.com/langchain-ai/deepagents/issues/5078))

## [0.1.47](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.46...deepagents-code==0.1.47) (2026-07-24)

### Features

- Added `yolo` mode to the `Shift+Tab` approval cycle ([#5035](https://github.com/langchain-ai/deepagents/issues/5035)).
- Show the changelog link before prompting to update via the install script ([#5034](https://github.com/langchain-ai/deepagents/issues/5034)).

## [0.1.46](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.45...deepagents-code==0.1.46) (2026-07-24)

### Highlights

- Auto mode is now generally available. [#4957](https://github.com/langchain-ai/deepagents/issues/4957)
- Added configurable Auto goal-criteria acceptance. [#4940](https://github.com/langchain-ai/deepagents/issues/4940)
- Improved Auto behavior by authorizing actions from active goal/rubric directives, avoiding redundant approval prompts, showing the enable notice only on first global enable, deduplicating classifier-unavailable transcript spam, logging underlying classifier failures, and reporting classifier timeout budgets. [#5017](https://github.com/langchain-ai/deepagents/issues/5017) [#4993](https://github.com/langchain-ai/deepagents/issues/4993) [#5012](https://github.com/langchain-ai/deepagents/issues/5012) [#5013](https://github.com/langchain-ai/deepagents/issues/5013) [#5011](https://github.com/langchain-ai/deepagents/issues/5011) [#5025](https://github.com/langchain-ai/deepagents/issues/5025)
- Added Hooks v2 capability snapshots and session transcripts, and hardened Hooks v2 command execution. [#4916](https://github.com/langchain-ai/deepagents/issues/4916) [#4918](https://github.com/langchain-ai/deepagents/issues/4918) [#4917](https://github.com/langchain-ai/deepagents/issues/4917)
- Raised the agent recursion limit to 2000 and made it configurable. [#4994](https://github.com/langchain-ai/deepagents/issues/4994)

### Improvements and fixes

- Let the rubric grader inspect working-directory files, show rubric grader defaults, and improved `/rubric` help and empty-state messaging. [#4835](https://github.com/langchain-ai/deepagents/issues/4835) [#4966](https://github.com/langchain-ai/deepagents/issues/4966) [#5015](https://github.com/langchain-ai/deepagents/issues/5015)
- Unified goal activation signaling. [#4980](https://github.com/langchain-ai/deepagents/issues/4980)
- Made Version, Model, and CWD copyable in the Debug Console. [#4975](https://github.com/langchain-ai/deepagents/issues/4975)
- Improved `config get` output when a key is missing. [#4976](https://github.com/langchain-ai/deepagents/issues/4976)
- Aborted YOLO launch on `Ctrl+C`/`Ctrl+D` and made the YOLO warning friendlier for new users. [#4953](https://github.com/langchain-ai/deepagents/issues/4953) [#4950](https://github.com/langchain-ai/deepagents/issues/4950)
- Updated LangSmith handling: secret redaction is disabled by default, `/trace` now flags empty env overrides that shadow the LangSmith key, and the default US endpoint is no longer treated as a custom target. [#4970](https://github.com/langchain-ai/deepagents/issues/4970) [#4996](https://github.com/langchain-ai/deepagents/issues/4996) [#5022](https://github.com/langchain-ai/deepagents/issues/5022)
- Injected OpenAI `prompt_cache_key` for any OpenAI-provider endpoint. [#4995](https://github.com/langchain-ai/deepagents/issues/4995)
- Improved tool and schema presentation: finished calls stay on the live tool-group line, first-party tool schemas now include field descriptions, and `web_search`/`fetch_url` tool descriptions were trimmed. [#4927](https://github.com/langchain-ai/deepagents/issues/4927) [#5019](https://github.com/langchain-ai/deepagents/issues/5019) [#5016](https://github.com/langchain-ai/deepagents/issues/5016)
- Omitted `plugins/` and `conversation_history/` from the `/agent` picker. [#4991](https://github.com/langchain-ai/deepagents/issues/4991)
- Made selector modal backdrop dimming consistent. [#4990](https://github.com/langchain-ai/deepagents/issues/4990)
- Restored the `"Server log preserved at:"` notice on exit. [#4999](https://github.com/langchain-ai/deepagents/issues/4999)
- Used the SDK pin as the effective editable version. [#4949](https://github.com/langchain-ai/deepagents/issues/4949)

## [0.1.45](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.44...deepagents-code==0.1.45) (2026-07-22)

### Features

- Added the Hooks v2 execution engine and typed hooks data models ([#4880](https://github.com/langchain-ai/deepagents/issues/4880), [#4870](https://github.com/langchain-ai/deepagents/issues/4870))
- Added a filesystem tool allowlist for `dcode` with `--allow-fs-tools` ([#4635](https://github.com/langchain-ai/deepagents/issues/4635))
- Added a GLM-5.2 harness profile ([#4710](https://github.com/langchain-ai/deepagents/issues/4710))
- Added a built-in thread inspector skill ([#4769](https://github.com/langchain-ai/deepagents/issues/4769))
- Replaced Gemini 3.5 Flash with Gemini 3.6 Flash in the model switcher ([#4890](https://github.com/langchain-ai/deepagents/issues/4890))
- Show experimental mode in the splash screen and debug console ([#4863](https://github.com/langchain-ai/deepagents/issues/4863))
- Gate debug console click-to-copy behind a checkbox ([#4810](https://github.com/langchain-ai/deepagents/issues/4810))

### Bug Fixes

- Improved scratch-file handling by allowing cleanup of agent-created scratch files and safe OS-temp scratch artifacts ([#4860](https://github.com/langchain-ai/deepagents/issues/4860), [#4869](https://github.com/langchain-ai/deepagents/issues/4869))
- Skip grading during `/goal` proposals ([#4941](https://github.com/langchain-ai/deepagents/issues/4941))
- Improved MCP approval handling: Esc now aborts project MCP approval, disabled MCP servers are honored for plugins, remembered approvals are preserved with the env allowlist, and approvals are shared across Git worktrees ([#4888](https://github.com/langchain-ai/deepagents/issues/4888), [#4848](https://github.com/langchain-ai/deepagents/issues/4848), [#4889](https://github.com/langchain-ai/deepagents/issues/4889), [#4939](https://github.com/langchain-ai/deepagents/issues/4939))
- Hardened installer downloads and paths ([#4871](https://github.com/langchain-ai/deepagents/issues/4871))
- Fixed forced `dcode update` checks to bust the CDN cache ([#4862](https://github.com/langchain-ai/deepagents/issues/4862))
- Prevented failed exit setup from stranding the app ([#4913](https://github.com/langchain-ai/deepagents/issues/4913))
- Fixed routing so `ctrl+x` goes to the focused `ask_user` input ([#4926](https://github.com/langchain-ai/deepagents/issues/4926))
- Show `-m` prompts as queued immediately on startup ([#4861](https://github.com/langchain-ai/deepagents/issues/4861))
- Kept harness-profile diagnostics out of terminal output ([#4943](https://github.com/langchain-ai/deepagents/issues/4943))
- Avoid tracking inline restart callers ([#4894](https://github.com/langchain-ai/deepagents/issues/4894))
- Fixed debug console thread ID copying on click ([#4945](https://github.com/langchain-ai/deepagents/issues/4945))

### Performance Improvements

- Reduced exit latency by coordinating async shutdown teardown ([#4831](https://github.com/langchain-ai/deepagents/issues/4831))
- Sped up local context detection ([#4922](https://github.com/langchain-ai/deepagents/issues/4922))

## [0.1.44](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.43...deepagents-code==0.1.44) (2026-07-20)

### Bug Fixes

- Improved approval handling by hiding the `Auto` option when it isn't eligible and moving Auto mode path checks off the event loop. ([#4839](https://github.com/langchain-ai/deepagents/issues/4839), [#4856](https://github.com/langchain-ai/deepagents/issues/4856))
- Warmed MCP auth imports off the event loop to avoid blocking runtime work. ([#4855](https://github.com/langchain-ai/deepagents/issues/4855))

## [0.1.43](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.42...deepagents-code==0.1.43) (2026-07-17)

### Features

- Added classifier-backed Auto approval mode behind `DEEPAGENTS_CODE_EXPERIMENTAL=1` ([#4804](https://github.com/langchain-ai/deepagents/issues/4804)).
- Added a shutdown toast for deferred exits ([#4830](https://github.com/langchain-ai/deepagents/issues/4830)).
- Task descriptions that were truncated can now be expanded by clicking or pressing `Ctrl+O` ([#4811](https://github.com/langchain-ai/deepagents/issues/4811)).
- Debug Console clears with `Ctrl+L` now persist after reopening ([#4812](https://github.com/langchain-ai/deepagents/issues/4812)).
- Added debug logging for skill-name override collisions ([#4772](https://github.com/langchain-ai/deepagents/issues/4772)).

### Bug Fixes

- Keep chat input responsive during `/restart` ([#4808](https://github.com/langchain-ai/deepagents/issues/4808)).
- Fixed paste placeholders disappearing when backspacing a newline below them ([#4757](https://github.com/langchain-ai/deepagents/issues/4757)).
- Made markdown `AppMessage` output selectable ([#4814](https://github.com/langchain-ai/deepagents/issues/4814)).
- Fixed live tool-group counts to include only running tools ([#4809](https://github.com/langchain-ai/deepagents/issues/4809)).
- Kept `task` timers monotonic across nested subagent human-in-the-loop flows ([#4771](https://github.com/langchain-ai/deepagents/issues/4771)).
- Preserved goal criteria proposals when marker clearing fails ([#4785](https://github.com/langchain-ai/deepagents/issues/4785)).
- Reduced repeated probing of an unreachable Ollama daemon to once per reload ([#4806](https://github.com/langchain-ai/deepagents/issues/4806)).
- Quieted MCP auth-skip debug logging for known patterns ([#4805](https://github.com/langchain-ai/deepagents/issues/4805)).
- Improved `/version` diagnostics for editable installs and core dependency reporting, including surfacing `langchain-quickjs` ([#4816](https://github.com/langchain-ai/deepagents/issues/4816), [#4813](https://github.com/langchain-ai/deepagents/issues/4813)).
- Removed the `uv install` tip from the `/version` update hint ([#4822](https://github.com/langchain-ai/deepagents/issues/4822)).

## [0.1.42](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.41...deepagents-code==0.1.42) (2026-07-17)

### Features

- Plugins are now generally available. ([#4797](https://github.com/langchain-ai/deepagents/issues/4797))
- Added search to the plugin list and now summarize plugin changes after reloads. ([#4765](https://github.com/langchain-ai/deepagents/issues/4765), [#4767](https://github.com/langchain-ai/deepagents/issues/4767))
- Added Kimi K3 to the OpenRouter model selector. ([#4803](https://github.com/langchain-ai/deepagents/issues/4803))
- Added hidden `connect` and `reconnect` keywords for `/restart`. ([#4807](https://github.com/langchain-ai/deepagents/issues/4807))
- Debug Console thread IDs can now be clicked to copy, with an added LangSmith link. ([#4760](https://github.com/langchain-ai/deepagents/issues/4760))
- Added auto-approve (YOLO) mode to trace metadata. ([#4764](https://github.com/langchain-ai/deepagents/issues/4764))

### Bug Fixes

- Improved plugin marketplace loading and onboarding, including asynchronous marketplace additions and polish for empty marketplace states. ([#4766](https://github.com/langchain-ai/deepagents/issues/4766), [#4759](https://github.com/langchain-ai/deepagents/issues/4759))
- Clarified plugin component discovery and reload status. ([#4774](https://github.com/langchain-ai/deepagents/issues/4774))
- Avoided blocking MCP OAuth token refresh. ([#4770](https://github.com/langchain-ai/deepagents/issues/4770))
- Restored keyboard focus for marketplace details. ([#4763](https://github.com/langchain-ai/deepagents/issues/4763))
- Dismissed the startup tip when submitting an initial prompt with `-m`. ([#4779](https://github.com/langchain-ai/deepagents/issues/4779))

## [0.1.41](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.40...deepagents-code==0.1.41) (2026-07-16)

### Bug Fixes

- Pinned `filelock` below 3.30 to avoid blocking imports ([#4786](https://github.com/langchain-ai/deepagents/issues/4786))

## [0.1.40](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.39...deepagents-code==0.1.40) (2026-07-16)

### Features

- Added plugin marketplace support ([#4554](https://github.com/langchain-ai/deepagents/issues/4554)).
- Added an "always allow" option to the project MCP approval prompt ([#4562](https://github.com/langchain-ai/deepagents/issues/4562)).
- Improved `/goal` workflows: criteria generation now runs server-side, YOLO mode auto-accepts criteria, goals complete after satisfied grading, and goal review editing now supports `Ctrl+X` ([#4754](https://github.com/langchain-ai/deepagents/issues/4754), [#4784](https://github.com/langchain-ai/deepagents/issues/4784), [#4781](https://github.com/langchain-ai/deepagents/issues/4781), [#4780](https://github.com/langchain-ai/deepagents/issues/4780)).
- Reasoning effort now persists across restarts ([#4728](https://github.com/langchain-ai/deepagents/issues/4728)).
- Added a toast prompting you to re-paste when a chat paste collapses ([#4742](https://github.com/langchain-ai/deepagents/issues/4742)).

### Bug Fixes

- Tool calls awaiting approval are now surfaced correctly ([#4739](https://github.com/langchain-ai/deepagents/issues/4739)).
- Fixed transcript tail hydration when scrolled to the bottom edge ([#4733](https://github.com/langchain-ai/deepagents/issues/4733)).
- Kept chat input responsive during MCP viewer `Ctrl+R` reconnects ([#4753](https://github.com/langchain-ai/deepagents/issues/4753)).
- Improved inline free-text prompts by sharing paste handling and matching primary-input `Ctrl+D` behavior ([#4736](https://github.com/langchain-ai/deepagents/issues/4736), [#4729](https://github.com/langchain-ai/deepagents/issues/4729)).
- Fixed local offloaded tool results to use the real filesystem ([#4740](https://github.com/langchain-ai/deepagents/issues/4740)).
- Cleaned offloaded history when deleting a thread ([#4751](https://github.com/langchain-ai/deepagents/issues/4751)).
- Removed duplicated content from the system prompt by overwriting the base prompt ([#4516](https://github.com/langchain-ai/deepagents/issues/4516)).
- Closed subprocess transport during install teardown ([#4735](https://github.com/langchain-ai/deepagents/issues/4735)).
- Added targeted `uv` constraints for prerelease dependencies ([#4744](https://github.com/langchain-ai/deepagents/issues/4744)).

## [0.1.39](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.38...deepagents-code==0.1.39) (2026-07-14)

### Bug fixes

- Improved Debug Console log retention by partitioning retained logs by level ([#4718](https://github.com/langchain-ai/deepagents/issues/4718)) ([c6e3b35](https://github.com/langchain-ai/deepagents/commit/c6e3b351f1826aa6ea97be244acd867950a032ee)).
- Fixed `/offload` to run server-side ([#4696](https://github.com/langchain-ai/deepagents/issues/4696)) ([564e5a0](https://github.com/langchain-ai/deepagents/commit/564e5a05bca5236ae33ce1147865111f931d257c)).

## [0.1.38](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.37...deepagents-code==0.1.38) (2026-07-14)

### Features

* Improve `/goal` criteria UX ([#4694](https://github.com/langchain-ai/deepagents/issues/4694)) ([06f46ff](https://github.com/langchain-ai/deepagents/commit/06f46fffe36efa9f3adcb331b07df283d8bed874))
* Add interactive goal management ([#4693](https://github.com/langchain-ai/deepagents/issues/4693)) ([64205e2](https://github.com/langchain-ai/deepagents/commit/64205e238c280ae05b2bf9253ac40c6f85ffb49c))
* Conditionally drop `TodoListMiddleware` ([#4685](https://github.com/langchain-ai/deepagents/issues/4685)) ([d3a3077](https://github.com/langchain-ai/deepagents/commit/d3a3077e8536696dcf4a9dcd8555e9c871562e74))
* Add `memory.auto_save` config flag ([#4700](https://github.com/langchain-ai/deepagents/issues/4700)) ([55b60ca](https://github.com/langchain-ai/deepagents/commit/55b60ca08da4eef294ac3c162610b2a151584ea5))
* Trace experimental mode in metadata ([#4705](https://github.com/langchain-ai/deepagents/issues/4705)) ([22d5045](https://github.com/langchain-ai/deepagents/commit/22d50456324e9b8c0121a3a06787e19c1b88e1aa))

### Bug Fixes

* Align context diff rows with changed rows ([#4714](https://github.com/langchain-ai/deepagents/issues/4714)) ([f9915db](https://github.com/langchain-ai/deepagents/commit/f9915db4206ef2d794ad07fdccbdd4ee58963142))
* Hydrate virtualized transcript on scroll offset changes ([#4646](https://github.com/langchain-ai/deepagents/issues/4646)) ([f77eeb0](https://github.com/langchain-ai/deepagents/commit/f77eeb0a036281f84bf7d0b05ea60e02630f55c1))
* Keep TODO and edit tools expanded ([#4704](https://github.com/langchain-ai/deepagents/issues/4704)) ([1d549d3](https://github.com/langchain-ai/deepagents/commit/1d549d3f3c9bb60c3ce39d4a0c913bcefe9610d5))
* Make `/goal` completion and grading reliable ([#4691](https://github.com/langchain-ai/deepagents/issues/4691)) ([9da63c6](https://github.com/langchain-ai/deepagents/commit/9da63c64a59503e3366e9bc7224cb1251af476be))
* Preflight Ollama host reachability before discovery probe ([#4702](https://github.com/langchain-ai/deepagents/issues/4702)) ([96fe71a](https://github.com/langchain-ai/deepagents/commit/96fe71a3815e1020edeb3be1af70b0cadb85931c))
* Quiet expected non-repo `git ls-files` logging ([#4701](https://github.com/langchain-ai/deepagents/issues/4701)) ([3d499db](https://github.com/langchain-ai/deepagents/commit/3d499db8a6c76743810a8983107d7c7d7bdb35e6))
* Rename `ls_agent_kind` to `ls_agent_purpose` ([#4708](https://github.com/langchain-ai/deepagents/issues/4708)) ([2678b16](https://github.com/langchain-ai/deepagents/commit/2678b1680d8928e72e8efae00632a694c9b2737a))
* Run MCP login during a run, queue the restart ([#4643](https://github.com/langchain-ai/deepagents/issues/4643)) ([65e1ee8](https://github.com/langchain-ai/deepagents/commit/65e1ee802e2f69762a6d8e6c7c6d37060161ea5a))
* Show "Took &lt;duration&gt;" when `task` tool completes ([#4638](https://github.com/langchain-ai/deepagents/issues/4638)) ([19538e0](https://github.com/langchain-ai/deepagents/commit/19538e0a46a5c2c050412b79fd45608a63cdde52))
* Support unambiguous `read_file` gutters ([#4711](https://github.com/langchain-ai/deepagents/issues/4711)) ([2089b54](https://github.com/langchain-ai/deepagents/commit/2089b54e2a674ede313e790b59febf9dc6f22571))

## [0.1.37](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.36...deepagents-code==0.1.37) (2026-07-13)

### Features

* Add Meta model provider ([#4650](https://github.com/langchain-ai/deepagents/issues/4650)) ([70829c5](https://github.com/langchain-ai/deepagents/commit/70829c5846b6bdde1cee51f0f4929e819ba1026b))
* Set `prompt_cache_key` for OpenAI models ([#4632](https://github.com/langchain-ai/deepagents/issues/4632)) ([8cf57ac](https://github.com/langchain-ai/deepagents/commit/8cf57aca9f41c3c4ca6d9796dc2cb80d4b22fb6d))
* Support Fireworks `/routers` model ids ([#4591](https://github.com/langchain-ai/deepagents/issues/4591)) ([1c08d27](https://github.com/langchain-ai/deepagents/commit/1c08d2705f73f6870610849e00910b94458accf1))
* `/model` Ctrl+N toggle for names vs raw specs ([#4592](https://github.com/langchain-ai/deepagents/issues/4592)) ([518c322](https://github.com/langchain-ai/deepagents/commit/518c322e7dda840b5a740541afc895516a74925f))
* `/tools` slash command ([#4649](https://github.com/langchain-ai/deepagents/issues/4649)) ([b1600a8](https://github.com/langchain-ai/deepagents/commit/b1600a8da784899d9db5bdf93be07b4c7f53a46c))
* Add `-s` alias for `--skill` ([#4620](https://github.com/langchain-ai/deepagents/issues/4620)) ([c9b7ac2](https://github.com/langchain-ai/deepagents/commit/c9b7ac20752e4270d286b4af3fcf710e7e5bee87))
* Configurable chat cursor style ([#4687](https://github.com/langchain-ai/deepagents/issues/4687)) ([a22484b](https://github.com/langchain-ai/deepagents/commit/a22484ba2e001fd62fbff0fe916f1b3b93889fc3))
* Expand environment variables in MCP config ([#4681](https://github.com/langchain-ai/deepagents/issues/4681)) ([4f5d7be](https://github.com/langchain-ai/deepagents/commit/4f5d7be1b4073dee346e5a974841721646fa4860))
* Hide diff widget for credential files ([#4593](https://github.com/langchain-ai/deepagents/issues/4593)) ([4c49a24](https://github.com/langchain-ai/deepagents/commit/4c49a24c4c488f45859b45628cfa57719e52f596))
* In-app Debug Console ([#4564](https://github.com/langchain-ai/deepagents/issues/4564)) ([4f94a30](https://github.com/langchain-ai/deepagents/commit/4f94a30c11efb1819b08647d15b50b9b1e7bf043))
* Offer abort in `/threads` cwd-switch prompt ([#4583](https://github.com/langchain-ai/deepagents/issues/4583)) ([aaeac99](https://github.com/langchain-ai/deepagents/commit/aaeac99d9f17b6a55d663c21a4d063444b6a1870))
* Resume threads in-TUI with `/threads -r [ID]` ([#4609](https://github.com/langchain-ai/deepagents/issues/4609)) ([d442673](https://github.com/langchain-ai/deepagents/commit/d44267358e272553c8ece33d367514430be7c0da))
* Show `(debug enabled)` on splash when `DEEPAGENTS_CODE_DEBUG` is set ([#4584](https://github.com/langchain-ai/deepagents/issues/4584)) ([f10b877](https://github.com/langchain-ai/deepagents/commit/f10b877e5e48c3a1e15bd72d2ce06dfb16203231))

### Bug Fixes

* Avoid repeated startup auto-update stalls ([#4648](https://github.com/langchain-ai/deepagents/issues/4648)) ([12a9c9d](https://github.com/langchain-ai/deepagents/commit/12a9c9d6813a83e5eeff9feed0c4068d1fcc69c4))
* Infer Fireworks provider from qualified model IDs ([#4594](https://github.com/langchain-ai/deepagents/issues/4594)) ([4d2aa8a](https://github.com/langchain-ai/deepagents/commit/4d2aa8a9684609eee45cd93b0af5149d8dd09eea))
* Capture input typed before TUI startup ([#4684](https://github.com/langchain-ai/deepagents/issues/4684)) ([ef9a4a8](https://github.com/langchain-ai/deepagents/commit/ef9a4a8770f4daec70e640d6d2f23dd798d4ede2))
* Detach owned `langgraph dev` server from terminal ([#4642](https://github.com/langchain-ai/deepagents/issues/4642)) ([d1f3afe](https://github.com/langchain-ai/deepagents/commit/d1f3afecdc015b5d1c9fb098d6347c7d7180e417))
* Infer additional model providers ([#4675](https://github.com/langchain-ai/deepagents/issues/4675)) ([4ceed24](https://github.com/langchain-ai/deepagents/commit/4ceed24d3758801ed9df1024602e90488004cef1))
* Preserve `Ctrl+D` deletion in non-empty input ([#4626](https://github.com/langchain-ai/deepagents/issues/4626)) ([306bd89](https://github.com/langchain-ai/deepagents/commit/306bd893f214237b6b4eede7c2ce0eaff66f5527))
* Quit with `Ctrl+D` at end of prompt ([#4678](https://github.com/langchain-ai/deepagents/issues/4678)) ([2f8c111](https://github.com/langchain-ai/deepagents/commit/2f8c11176f5cc9350c3337b2dfcf9f19886d5d02))
* Reap langgraph dev server when startup is cancelled ([#4629](https://github.com/langchain-ai/deepagents/issues/4629)) ([904ff05](https://github.com/langchain-ai/deepagents/commit/904ff05620a576100e05fd65810d38405c4942d4))
* Reject `--auto-approve` in headless mode ([#4617](https://github.com/langchain-ai/deepagents/issues/4617)) ([997be16](https://github.com/langchain-ai/deepagents/commit/997be1643aff6d6900b8b8c95832cdf93be8c0d7))
* Route explicit `--stdin` + `--skill` to headless path ([#4611](https://github.com/langchain-ai/deepagents/issues/4611)) ([724e24a](https://github.com/langchain-ai/deepagents/commit/724e24a31546e1f31feca3bb2344717550682595))
* Skip Esc prompt-restore once output generation begins ([#4582](https://github.com/langchain-ai/deepagents/issues/4582)) ([14f384f](https://github.com/langchain-ai/deepagents/commit/14f384fc0083c07a7f44f97543b40b74cf93c13f))
* Remove misleading agent names from help ([#4671](https://github.com/langchain-ai/deepagents/issues/4671)) ([ac15732](https://github.com/langchain-ai/deepagents/commit/ac1573281530c1564fe07f8a21608e4d4dec2c3b))
* Support plain `exit` quit command ([#4543](https://github.com/langchain-ai/deepagents/issues/4543)) ([e6f10a1](https://github.com/langchain-ai/deepagents/commit/e6f10a149051128677c9f6f37663922054a7ac26))
* Sync `ask_user` active-question highlight with focus ([#4599](https://github.com/langchain-ai/deepagents/issues/4599)) ([e4c29b5](https://github.com/langchain-ai/deepagents/commit/e4c29b5264413d23d8dc70cabae72feb5f3f3dcb))
* Wrap MCP viewer navigation ([#4677](https://github.com/langchain-ai/deepagents/issues/4677)) ([cffc732](https://github.com/langchain-ai/deepagents/commit/cffc73213bfdcec26cb82c413fa7e27db4afc0ca))

### Performance Improvements

* Load MCP servers concurrently during graph build ([#4659](https://github.com/langchain-ai/deepagents/issues/4659)) ([c5345cc](https://github.com/langchain-ai/deepagents/commit/c5345cc04cd810c6238e42dfbfa14497ae1b9020))

## [0.1.36](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.35...deepagents-code==0.1.36) (2026-07-09)

### Features

* Add `GPT-5.6` model family ([#4600](https://github.com/langchain-ai/deepagents/issues/4600)) ([4a806bc](https://github.com/langchain-ai/deepagents/commit/4a806bc703b69334cccd05bcd27d411602e82318))
* Add Grok 4.5 model ([#4596](https://github.com/langchain-ai/deepagents/issues/4596)) ([b0a209d](https://github.com/langchain-ai/deepagents/commit/b0a209da3a8c9f80e2e3d5e199340736c854c567))

### Bug Fixes

* Strip input before Ctrl+C copy-input fallback ([#4590](https://github.com/langchain-ai/deepagents/issues/4590)) ([505d55a](https://github.com/langchain-ai/deepagents/commit/505d55ad83e8569213175911ee6c8c39fbbf340c))

## [0.1.35](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.34...deepagents-code==0.1.35) (2026-07-09)

### Features

* Restore interrupted prompt to input on ESC ([#4544](https://github.com/langchain-ai/deepagents/issues/4544)) ([fccf037](https://github.com/langchain-ai/deepagents/commit/fccf03732140d39749e70e8fc6cb7d73124a1d70))
* Add `[startup].mode` default approval mode ([#4573](https://github.com/langchain-ai/deepagents/issues/4573)) ([7c5bf54](https://github.com/langchain-ai/deepagents/commit/7c5bf542c2f58fa46ecd708c66cd1817a0ebdc41))
* Offer restart after saving Tavily key via `/auth` ([#4560](https://github.com/langchain-ai/deepagents/issues/4560)) ([12df81a](https://github.com/langchain-ai/deepagents/commit/12df81ad00d814c570b4d24a2b06de9b18d51abd))
* Reload env from `/auth` modal via Ctrl+R ([#4566](https://github.com/langchain-ai/deepagents/issues/4566)) ([f07d638](https://github.com/langchain-ai/deepagents/commit/f07d6387b7dc1f0e880f77784905c2aa94143adb))
* Toast on saved `/auth` API key ([#4558](https://github.com/langchain-ai/deepagents/issues/4558)) ([ee3c264](https://github.com/langchain-ai/deepagents/commit/ee3c26415be84e369b829fefb21461c8ec210a5e))

### Bug Fixes

* Harden approval content rendering ([#4581](https://github.com/langchain-ai/deepagents/issues/4581)) ([38446fd](https://github.com/langchain-ai/deepagents/commit/38446fda649b891dd8604e788701eabe739c1dd0))
* Preserve transcript order during virtualization ([#4549](https://github.com/langchain-ai/deepagents/issues/4549)) ([f6ee70c](https://github.com/langchain-ai/deepagents/commit/f6ee70c00ac6ad7b1b180155018b794308a18361))
* Run stdio MCP server pre-flight check off the event loop ([#4434](https://github.com/langchain-ai/deepagents/issues/4434)) ([c9636e2](https://github.com/langchain-ai/deepagents/commit/c9636e22725a5bd32c1f8b9e739b02b4aa7c3dc7))
* Avoid duplicate "criteria ready" message on `/goal` revisions ([#4559](https://github.com/langchain-ai/deepagents/issues/4559)) ([1110497](https://github.com/langchain-ai/deepagents/commit/1110497e17fac6deceb9d1d6e530f9197bfc0d4a))
* Restore welcome banner tips ([#4528](https://github.com/langchain-ai/deepagents/issues/4528)) ([3f1e55e](https://github.com/langchain-ai/deepagents/commit/3f1e55eafbc1fde79cb75f631561cf35d4b8ff4c))
* Clarify managed `rg` install failures ([#4578](https://github.com/langchain-ai/deepagents/issues/4578)) ([434c84a](https://github.com/langchain-ai/deepagents/commit/434c84ae144b0319afe37d6f2dbadfd7f5fc9f70))
* Dedupe update/install log path output ([#4553](https://github.com/langchain-ai/deepagents/issues/4553)) ([1398fee](https://github.com/langchain-ai/deepagents/commit/1398feeca507cab9ec51a66604d46c747f7fcd2f))
* Keep notification center open for API-key entry ([#4568](https://github.com/langchain-ai/deepagents/issues/4568)) ([6e89417](https://github.com/langchain-ai/deepagents/commit/6e8941776cdcc35909da305f3bb39500c0f479cb))
* Queue `/mcp login` sent before the server connects ([#4533](https://github.com/langchain-ai/deepagents/issues/4533)) ([edac82c](https://github.com/langchain-ai/deepagents/commit/edac82c837de8e12b58b97ac25acc31f743d4c5d))
* Serialize MCP OAuth token refreshes to prevent reuse revocation ([#4565](https://github.com/langchain-ai/deepagents/issues/4565)) ([c37100d](https://github.com/langchain-ai/deepagents/commit/c37100d4763e527fce12fa4451794ca25ded7640))

## [0.1.34](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.33...deepagents-code==0.1.34) (2026-07-07)

### Bug Fixes

* **code:** show `(local)` tag under ANSI themes ([#4534](https://github.com/langchain-ai/deepagents/issues/4534)) ([699e439](https://github.com/langchain-ai/deepagents/commit/699e439699723e477a621f95eef87a7d76aac5f5))

## [0.1.33](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.32...deepagents-code==0.1.33) (2026-07-06)

### Features

* In-the-moment trust prompt for symlinked skills ([#4200](https://github.com/langchain-ai/deepagents/issues/4200)) ([a4431e4](https://github.com/langchain-ai/deepagents/commit/a4431e4339348431e91533cb2b177259ab94b083))
* Selective per-server project MCP trust ([#4507](https://github.com/langchain-ai/deepagents/issues/4507)) ([aaa22a9](https://github.com/langchain-ai/deepagents/commit/aaa22a9340cb3d2c8e9ce1a921957d0a9121da20))
* Add `dcode tools list` command ([#4461](https://github.com/langchain-ai/deepagents/issues/4461)) ([1402d0e](https://github.com/langchain-ai/deepagents/commit/1402d0e735a1580503f240457c77db76fcd779d7))

### Bug Fixes

* Strip media placeholders from model-facing message text ([#4462](https://github.com/langchain-ai/deepagents/issues/4462)) ([aa0ae36](https://github.com/langchain-ai/deepagents/commit/aa0ae36b00df6411a9200610a9075ef2dc28b1af))
* Re-apply theme preference on `/reload` ([#4514](https://github.com/langchain-ai/deepagents/issues/4514)) ([5d1c392](https://github.com/langchain-ai/deepagents/commit/5d1c3928f7ca0ea97f28fd4d34ae1a4ee885e888))

## [0.1.32](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.31...deepagents-code==0.1.32) (2026-07-06)

### Features

* Simplify welcome banner to compact box ([#4482](https://github.com/langchain-ai/deepagents/issues/4482)) ([b7f46e9](https://github.com/langchain-ai/deepagents/commit/b7f46e931807f86476c9c2d661dcd4e9623c10a2))
* Add LangSmith base URL to `/auth` ([#4228](https://github.com/langchain-ai/deepagents/issues/4228)) ([88d167f](https://github.com/langchain-ai/deepagents/commit/88d167f9ceec1cfadd7c3feac6f63c0da7c893f1))
* `tool.use` and `tool.result` hook events ([#3954](https://github.com/langchain-ai/deepagents/issues/3954)) ([ba1979d](https://github.com/langchain-ai/deepagents/commit/ba1979d64c3ed5e96ebc896197bc8f97f6f84bac))
* Fall back to folder name for subagents ([#4504](https://github.com/langchain-ai/deepagents/issues/4504)) ([9db3db5](https://github.com/langchain-ai/deepagents/commit/9db3db5f31a93fb8598a5dc5bedf4fe61fe92c94))
* Report tracing gateway in `dcode doctor` ([#4466](https://github.com/langchain-ai/deepagents/issues/4466)) ([a912427](https://github.com/langchain-ai/deepagents/commit/a9124275504bc1af5f76dfdd9a6c558c98eea92d))
* Gate paste auto-collapse behind `display.collapse_pastes` ([#4473](https://github.com/langchain-ai/deepagents/issues/4473)) ([ff5dd56](https://github.com/langchain-ai/deepagents/commit/ff5dd564a3a590e7d2d521b20df495b5e1512e12))

### Bug Fixes

* Keep footer branch visible and ellipsized instead of hiding when narrow ([#4506](https://github.com/langchain-ai/deepagents/issues/4506)) ([ccf30c3](https://github.com/langchain-ai/deepagents/commit/ccf30c342e5ead677aafd196d8f1ddd2bdf95196))
* Remove MCP OAuth success page message shift ([#4463](https://github.com/langchain-ai/deepagents/issues/4463)) ([69bb06c](https://github.com/langchain-ai/deepagents/commit/69bb06c0680fa6d37b917deb6b70927c3eff9c09))
* Prevent `UnicodeEncodeError` crash in non-interactive mode on legacy Windows consoles ([#4478](https://github.com/langchain-ai/deepagents/issues/4478)) ([b1b16cd](https://github.com/langchain-ai/deepagents/commit/b1b16cd114d4ee4f077cf5824a0176cd94ebd851))

### Performance Improvements

* Make `threads list` faster on large session databases ([#4005](https://github.com/langchain-ai/deepagents/issues/4005)) ([85ca01a](https://github.com/langchain-ai/deepagents/commit/85ca01a43b002c2bdb4205f48fac5fa6f66a3276))

## [0.1.31](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.30...deepagents-code==0.1.31) (2026-07-03)

### Features

* Collapse large pastes into compact placeholders ([#4447](https://github.com/langchain-ai/deepagents/issues/4447)) ([9ae927d](https://github.com/langchain-ai/deepagents/commit/9ae927d73ebf30ba50bbb7ec0c1076a0937e5cb7))
* Show model name instead of spec in switcher ([#4460](https://github.com/langchain-ai/deepagents/issues/4460)) ([0059620](https://github.com/langchain-ai/deepagents/commit/005962088ad31b16745c399e4ab2e725e97f7858))
* Offer abort during resume ([#4188](https://github.com/langchain-ai/deepagents/issues/4188)) ([a4c25cd](https://github.com/langchain-ai/deepagents/commit/a4c25cd74de9902fd0ea9440b5dda2d4248bb3d2))
* Persistent banner when installation is stale ([#4459](https://github.com/langchain-ai/deepagents/issues/4459)) ([b74c185](https://github.com/langchain-ai/deepagents/commit/b74c18591a8ce9a49a5fee43b07e602ca9fbf68a))
* Show `"Took <duration>"` after `execute` finishes ([#4301](https://github.com/langchain-ai/deepagents/issues/4301)) ([a5240eb](https://github.com/langchain-ai/deepagents/commit/a5240ebe3654e72fa5beb4070224f52f944768c8))
* Unify `config show`/`list` around effective values ([#4174](https://github.com/langchain-ai/deepagents/issues/4174)) ([ccd9d21](https://github.com/langchain-ai/deepagents/commit/ccd9d216e77855a28b88850beb525f47ce8b686a))

### Bug Fixes

* Make execute command expandable in code TUI transcript ([#4428](https://github.com/langchain-ai/deepagents/issues/4428)) ([d999181](https://github.com/langchain-ai/deepagents/commit/d999181e8424498681f1e442c71380bf6b82b0aa))
* Allow suppressing LangSmith key override warning ([#4436](https://github.com/langchain-ai/deepagents/issues/4436)) ([ddcae5e](https://github.com/langchain-ai/deepagents/commit/ddcae5e0bd9aebc946be1d9fb3f5e35eeb690fa6))
* Ensure unique message widget IDs on history load ([#4454](https://github.com/langchain-ai/deepagents/issues/4454)) ([de2f7d2](https://github.com/langchain-ai/deepagents/commit/de2f7d2835485df905772e1c96e33d2c239d8e22))
* Resolve `/threads` header link on mount, not after load ([#4453](https://github.com/langchain-ai/deepagents/issues/4453)) ([4cba728](https://github.com/langchain-ai/deepagents/commit/4cba72893fc4aae5b429d8c573c1a513d97ddf8a))
* Restore caller's LangSmith API key in shell subprocess env ([#4458](https://github.com/langchain-ai/deepagents/issues/4458)) ([9293b19](https://github.com/langchain-ai/deepagents/commit/9293b190170a872b73d0d94e66479bcc5f7962c7))
* Route Anthropic effort through output config ([#4446](https://github.com/langchain-ai/deepagents/issues/4446)) ([1e8ed81](https://github.com/langchain-ai/deepagents/commit/1e8ed81940a862dde44f704826b61650336367e0))
* Show loading state during model switch ([#4209](https://github.com/langchain-ai/deepagents/issues/4209)) ([7cc4e9f](https://github.com/langchain-ai/deepagents/commit/7cc4e9f9bda5a8ae42bb072b82b634ad8c39ade1))

## [0.1.30](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.29...deepagents-code==0.1.30) (2026-07-02)

### Features

* Add reasoning effort selector ([#4403](https://github.com/langchain-ai/deepagents/issues/4403)) ([6ee0ac4](https://github.com/langchain-ai/deepagents/commit/6ee0ac4cca998f84e157187d565084e2a1912626))
* Collapse completed tool calls into group summaries ([#4373](https://github.com/langchain-ai/deepagents/issues/4373)) ([3735829](https://github.com/langchain-ai/deepagents/commit/3735829a0c14fb1537daf930140c66b647c8222c))
* Auto-detect MCP OAuth from 401 challenge ([#4364](https://github.com/langchain-ai/deepagents/issues/4364)) ([9763ffc](https://github.com/langchain-ai/deepagents/commit/9763ffceab8800526ae9fe10decdb2f32d8e4707))
* Toast when opening a clicked URL ([#4368](https://github.com/langchain-ai/deepagents/issues/4368)) ([434f29e](https://github.com/langchain-ai/deepagents/commit/434f29e5cb3d94988e2a4d80b78452bee4b10812))

### Bug Fixes

* Allow `/remember` with args when no conversation history ([#4418](https://github.com/langchain-ai/deepagents/issues/4418)) ([5df9c83](https://github.com/langchain-ai/deepagents/commit/5df9c83b58f2529561848ae9f1364961e1c80641))
* Persist rubric model after server restart ([#4419](https://github.com/langchain-ai/deepagents/issues/4419)) ([5605a68](https://github.com/langchain-ai/deepagents/commit/5605a681c9fec888d8c6dfbde2decd4692c8cef0))
* Persist resume model state privately ([#4400](https://github.com/langchain-ai/deepagents/issues/4400)) ([bbd0f0d](https://github.com/langchain-ai/deepagents/commit/bbd0f0d1ddc9d22d399a819d7b4363f7997d119e))
* Quiet routine ripgrep installer output ([#4417](https://github.com/langchain-ai/deepagents/issues/4417)) ([a52c18d](https://github.com/langchain-ai/deepagents/commit/a52c18d3ef8fe462d1289dca8798c51450e0368a))
* Honest MCP OAuth callback close message ([#4410](https://github.com/langchain-ai/deepagents/issues/4410)) ([ef637f4](https://github.com/langchain-ai/deepagents/commit/ef637f4a3f38ee155ad7d31e64a5cdd7bfaee62c))

## [0.1.29](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.28...deepagents-code==0.1.29) (2026-07-01)

### Features

* Add rubric iteration controls ([#4405](https://github.com/langchain-ai/deepagents/issues/4405)) ([d6692a7](https://github.com/langchain-ai/deepagents/commit/d6692a7c713490f170b17510d613e02ee37574ab))
* Add Claude Sonnet 5 to model picker ([#4386](https://github.com/langchain-ai/deepagents/issues/4386)) ([64758dd](https://github.com/langchain-ai/deepagents/commit/64758dddf8b46c5b68c345fb1eac1fb7bcbf7f7e))

### Bug Fixes

* Full-width chat messages, hide scrollbar, flush input bg ([#4374](https://github.com/langchain-ai/deepagents/issues/4374)) ([1f8e8dc](https://github.com/langchain-ai/deepagents/commit/1f8e8dc942ac54c4014ac48f9345ee0201be0b1b))
* Resolve editable SDK version metadata ([#4394](https://github.com/langchain-ai/deepagents/issues/4394)) ([3239bf4](https://github.com/langchain-ai/deepagents/commit/3239bf4edf2be3037bb18315463ac6a0c3537e5c))
* Unblock MCP force reconnect modal ([#4396](https://github.com/langchain-ai/deepagents/issues/4396)) ([8b7eab0](https://github.com/langchain-ai/deepagents/commit/8b7eab023db686f577d16f4f9ac872205baf136f))

## [0.1.28](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.27...deepagents-code==0.1.28) (2026-06-29)

### Features

* Add Fireworks session settings ([#4360](https://github.com/langchain-ai/deepagents/issues/4360)) ([90ebb1d](https://github.com/langchain-ai/deepagents/commit/90ebb1d68cb5942f07847f6dce48c14c7caef992))
* `RubricMiddleware` implementation (`/goal`/`--goal` and `/rubric`/`--rubric`)
  * Add rubric-backed goal workflow ([#4365](https://github.com/langchain-ai/deepagents/issues/4365)) ([8fca61d](https://github.com/langchain-ai/deepagents/commit/8fca61dc036888a4414ff5a4536b957c63dab4a5))
  * Non-interactive rubric grading flags ([#4305](https://github.com/langchain-ai/deepagents/issues/4305)) ([1bcb112](https://github.com/langchain-ai/deepagents/commit/1bcb112ee78138eca9cb400c206ce198322aae32))
* Adopt coding-agent-v1 trace metadata ([#4367](https://github.com/langchain-ai/deepagents/issues/4367)) ([cb39747](https://github.com/langchain-ai/deepagents/commit/cb3974748024fcec2e2ee0ccc0a9b23c880733a2))
* Quit shortcut on completed update modal ([#4312](https://github.com/langchain-ai/deepagents/issues/4312)) ([5e6eae9](https://github.com/langchain-ai/deepagents/commit/5e6eae9f094a5167b6bf01f2d84cf06ca5cd80c3))

### Bug Fixes

* Redact LangSmith trace secrets by default ([#4356](https://github.com/langchain-ai/deepagents/issues/4356)) ([5e01fec](https://github.com/langchain-ai/deepagents/commit/5e01fec72d8b179a3b075b07268162d2eaebfe84))
* Honor Baseten base URL env precedence ([#4328](https://github.com/langchain-ai/deepagents/issues/4328)) ([8f20d74](https://github.com/langchain-ai/deepagents/commit/8f20d74892112c3b88aaca63d8c04a355fd6726f))
* Highlight just-installed provider on `/auth` reopen ([#4311](https://github.com/langchain-ai/deepagents/issues/4311)) ([85e47b5](https://github.com/langchain-ai/deepagents/commit/85e47b532b5caf92a52f1a070a95bdb39bee6d3d))
* Clear transient update launch status ([#4355](https://github.com/langchain-ai/deepagents/issues/4355)) ([b870b18](https://github.com/langchain-ai/deepagents/commit/b870b18750f65442009028a85a2ac18f1b06640c))
* Clearer MCP config JSON parse errors ([#4327](https://github.com/langchain-ai/deepagents/issues/4327)) ([9cee602](https://github.com/langchain-ai/deepagents/commit/9cee60274d38d4ad8a2d7a7e9d3ae59aebce5261))
* Record shell output as user context ([#4353](https://github.com/langchain-ai/deepagents/issues/4353)) ([0d504a5](https://github.com/langchain-ai/deepagents/commit/0d504a5df8454e871597932ce1cd3e95b10ab00e))
* Suppress expected MCP reauth logs ([#4359](https://github.com/langchain-ai/deepagents/issues/4359)) ([15ee384](https://github.com/langchain-ai/deepagents/commit/15ee384117ccd955f7481346dd92b7f4b007a60d))

### Performance Improvements

* Background refresh for `@` file completion cache ([#3911](https://github.com/langchain-ai/deepagents/issues/3911)) ([aa22d6b](https://github.com/langchain-ai/deepagents/commit/aa22d6b6d5a49e4d6c3aa2d4932df75d14d65f78))
* Speed up shutdown after `Ctrl+C`/`Ctrl+D` ([#4351](https://github.com/langchain-ai/deepagents/issues/4351)) ([db441ed](https://github.com/langchain-ai/deepagents/commit/db441ed306a8e03fb68f2ae6a2c08523e248976d))

## [0.1.27](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.26...deepagents-code==0.1.27) (2026-06-26)

### Features

* Show last update check time in `dcode doctor` ([#4307](https://github.com/langchain-ai/deepagents/issues/4307)) ([b669f37](https://github.com/langchain-ai/deepagents/commit/b669f37fb08998cfbf983da76f57822215614e7b))

### Bug Fixes

* `dcode doctor` shows `not configured` for unset tracing ([#4318](https://github.com/langchain-ai/deepagents/issues/4318)) ([e323d0c](https://github.com/langchain-ai/deepagents/commit/e323d0c7d91f3b11e03a016c14cf52008dc66b55))
* Drop duplicate token-request `client_id` under Basic auth ([#4323](https://github.com/langchain-ai/deepagents/issues/4323)) ([426dfad](https://github.com/langchain-ai/deepagents/commit/426dfad3ea1e453914cb87efa8fc70fb85a9efcb))
* Include skill invocations in input history ([#4211](https://github.com/langchain-ai/deepagents/issues/4211)) ([7b8d0b2](https://github.com/langchain-ai/deepagents/commit/7b8d0b2ec184e0d9a0cbe858a0d9a7128791969d))
* Offload `create_model` in server graph factory to unblock Codex ([#4324](https://github.com/langchain-ai/deepagents/issues/4324)) ([064ea0c](https://github.com/langchain-ai/deepagents/commit/064ea0c6851353d0b0bc347a0758149765688945))

## [0.1.26](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.25...deepagents-code==0.1.26) (2026-06-26)

### Bug Fixes

* Pin app version when installing extras ([#4313](https://github.com/langchain-ai/deepagents/issues/4313)) ([c20c8e2](https://github.com/langchain-ai/deepagents/commit/c20c8e2fc138f72f1444107d2a936305a591807b))

## [0.1.25](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.24...deepagents-code==0.1.25) (2026-06-26)

### Bug Fixes

* Bind ephemeral port instead of squatting `langgraph dev`'s 2024 ([#4264](https://github.com/langchain-ai/deepagents/issues/4264)) ([11e5359](https://github.com/langchain-ai/deepagents/commit/11e5359851f0291783661b4311ad5e4436a36fb7))
* Block dotenv shell startup hooks ([#4288](https://github.com/langchain-ai/deepagents/issues/4288)) ([686d6f3](https://github.com/langchain-ai/deepagents/commit/686d6f3a1da8b6393efb4c0cf87b3eb35e0cca50))
* Defer server graph construction ([#4300](https://github.com/langchain-ai/deepagents/issues/4300)) ([220dfc0](https://github.com/langchain-ai/deepagents/commit/220dfc0e6b03f9ccb499c6b850c586b9d57cc077))
  * Avoid blocking MCP imports during graph readiness ([#4302](https://github.com/langchain-ai/deepagents/issues/4302)) ([7533ca8](https://github.com/langchain-ai/deepagents/commit/7533ca89f3afc9863ba5e1ecee2d4c5974dea320))
* Gate `delete` file operations ([#4299](https://github.com/langchain-ai/deepagents/issues/4299)) ([92a8681](https://github.com/langchain-ai/deepagents/commit/92a86819adfefbc6ccfd01a861191ba292eca754))
* Handle recursive `fetch_url` conversion ([#4257](https://github.com/langchain-ai/deepagents/issues/4257)) ([f240a40](https://github.com/langchain-ai/deepagents/commit/f240a40dc05d812c38e9926c1d81ba38deb86e3f))
* Report editable SDK runtime version ([#4304](https://github.com/langchain-ai/deepagents/issues/4304)) ([4439e91](https://github.com/langchain-ai/deepagents/commit/4439e912da4bfa6f1e38e14b5a03d2bfe9367d3b))
* Show months instead of "0y ago" for 360-364 day old timestamps ([#4267](https://github.com/langchain-ai/deepagents/issues/4267)) ([820b331](https://github.com/langchain-ai/deepagents/commit/820b331552cb7ce4695ddca3c9b8343a3144392b))
* Surface `/auth`-stored credentials in `config show`/`get` ([#4258](https://github.com/langchain-ai/deepagents/issues/4258)) ([c7c8788](https://github.com/langchain-ai/deepagents/commit/c7c8788ecf0068914298a6055a5f3fd31c36bd44))
* Switch input mode without flashing the mode trigger ([#4243](https://github.com/langchain-ai/deepagents/issues/4243)) ([fc5d9cb](https://github.com/langchain-ai/deepagents/commit/fc5d9cb8fb978ec95f98407692d4809ea1e86577))

## [0.1.24](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.23...deepagents-code==0.1.24) (2026-06-25)

### Features

* Enable `js_eval` by default ([#4245](https://github.com/langchain-ai/deepagents/issues/4245)) ([2e04ff3](https://github.com/langchain-ai/deepagents/commit/2e04ff397e60389c9a19c4a9b528e15602ad8338))
* Dynamic subagents UI ([#4221](https://github.com/langchain-ai/deepagents/issues/4221)) ([10bcba2](https://github.com/langchain-ai/deepagents/commit/10bcba25600e51aba135f170b34aa6315c0f53d6))
* Gate onboarding integrations modal behind opt-in flag ([#4227](https://github.com/langchain-ai/deepagents/issues/4227)) ([6c930c5](https://github.com/langchain-ai/deepagents/commit/6c930c5e4502f572be554acc896c5fb6d061e0e5))

### Bug Fixes

* Eager managed ripgrep install via `dcode tools install` ([#4199](https://github.com/langchain-ai/deepagents/issues/4199)) ([cf536f3](https://github.com/langchain-ai/deepagents/commit/cf536f339958d6726fa41f896c4a3e42df644c9f))
* Interrupt remote runs on chat cancellation ([#4234](https://github.com/langchain-ai/deepagents/issues/4234)) ([37c5fa2](https://github.com/langchain-ai/deepagents/commit/37c5fa23e621616836694bc59c1b0c38def81604))
* Sync approval toggles during active runs ([#4239](https://github.com/langchain-ai/deepagents/issues/4239)) ([4600365](https://github.com/langchain-ai/deepagents/commit/4600365ea0b60c3e9113ecf59b5336be37d03428))
* Clear stale live approval mode keys ([#4242](https://github.com/langchain-ai/deepagents/issues/4242)) ([f11a769](https://github.com/langchain-ai/deepagents/commit/f11a76962c9d536a38e27ac05b32feca364b2424))

## [0.1.23](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.22...deepagents-code==0.1.23) (2026-06-25)

### Features

* Collect Tavily key during onboarding ([#4233](https://github.com/langchain-ai/deepagents/issues/4233)) ([e321cba](https://github.com/langchain-ai/deepagents/commit/e321cba5701313e974f979069186680f1a39587c))
* Surface `/auth` in `/trace not-configured` hint ([#4206](https://github.com/langchain-ai/deepagents/issues/4206)) ([392e410](https://github.com/langchain-ai/deepagents/commit/392e410e48639a56fda5e35b6f7f85a5215cce9c))
* Add Opus 4.8 to recommended models ([#4204](https://github.com/langchain-ai/deepagents/issues/4204)) ([8faf2b0](https://github.com/langchain-ai/deepagents/commit/8faf2b025f8429481a41a3e65544d26614e53589))

### Bug Fixes

* `--reinstall` on `/install` so upgrades rebuild a clean env ([#4196](https://github.com/langchain-ai/deepagents/issues/4196)) ([5e152ac](https://github.com/langchain-ai/deepagents/commit/5e152ac0256d64376f96b293f8844bc8acc993ec))
* Suppress auto-update migration notice on fresh installs ([#4224](https://github.com/langchain-ai/deepagents/issues/4224)) ([eb8ff80](https://github.com/langchain-ai/deepagents/commit/eb8ff809a1b3130a261083c66a193e532095c6db))
* Bake release commit into `dcode doctor` ([#4225](https://github.com/langchain-ai/deepagents/issues/4225)) ([6dc0246](https://github.com/langchain-ai/deepagents/commit/6dc0246f5c6e9170e05191e1c82fad6975ac945c))
* Drop redundant version from "already up to date" message ([#4223](https://github.com/langchain-ai/deepagents/issues/4223)) ([5d080df](https://github.com/langchain-ai/deepagents/commit/5d080df2776d380214bf20ae31266b9628e4e5b0))
* Note subscription plans unusable for Anthropic in `/auth` ([#4207](https://github.com/langchain-ai/deepagents/issues/4207)) ([28cd19d](https://github.com/langchain-ai/deepagents/commit/28cd19db08bacf981ab2c91195638e66072816fe))

## [0.1.22](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.21...deepagents-code==0.1.22) (2026-06-24)

### Features

* Add LangSmith tracing config to `/auth` ([#4193](https://github.com/langchain-ai/deepagents/issues/4193)) ([8e62957](https://github.com/langchain-ai/deepagents/commit/8e6295791093c2ddfec7e6ac57f0df7f12048447))
* Auto-retry credentials-blocked startup after `/auth` ([#4176](https://github.com/langchain-ai/deepagents/issues/4176)) ([d10ba3d](https://github.com/langchain-ai/deepagents/commit/d10ba3dc162e47cc71df56b8e3d0000b6e0ed847))
* Improve onboarding Installed Integrations screen ([#4195](https://github.com/langchain-ai/deepagents/issues/4195)) ([0827bf1](https://github.com/langchain-ai/deepagents/commit/0827bf1b635b825121740ac8946dd6d98c815c7d))

### Bug Fixes

* Exclude managed bin dir from agent picker ([#4190](https://github.com/langchain-ai/deepagents/issues/4190)) ([d869d1e](https://github.com/langchain-ai/deepagents/commit/d869d1e1fa8558510fb48e71f78fb74c69ca4840))
* Warn on `/trace` when thread has no messages ([#4162](https://github.com/langchain-ai/deepagents/issues/4162)) ([c338fc9](https://github.com/langchain-ai/deepagents/commit/c338fc914fcd383beb4b97c13f53dfb2684f8c90))
* Hide "Recent" section during onboarding model selection ([#4198](https://github.com/langchain-ai/deepagents/issues/4198)) ([af882e4](https://github.com/langchain-ai/deepagents/commit/af882e4f6c859878e350d8a37bb75b7bc01bb453))
* Keep auth modal interactive after install-on-select ([#4187](https://github.com/langchain-ai/deepagents/issues/4187)) ([afbc56a](https://github.com/langchain-ai/deepagents/commit/afbc56a1d9dbe8a89015f4c2f90bb87547d5c1d4))
* Generic "missing credentials" in model switcher ([#4182](https://github.com/langchain-ai/deepagents/issues/4182)) ([456ce5c](https://github.com/langchain-ai/deepagents/commit/456ce5c2f5487a754d1fea7046e32c03b7e27a17))
* Hide chat input action buttons in same frame as empty draft ([#4178](https://github.com/langchain-ai/deepagents/issues/4178)) ([f94d417](https://github.com/langchain-ai/deepagents/commit/f94d417d5ad9928db967777fe1d7bc2c37684fb9))
* Preserve uv tool context when installing extras ([#4201](https://github.com/langchain-ai/deepagents/issues/4201)) ([fcc616c](https://github.com/langchain-ai/deepagents/commit/fcc616cf9bc2bbc7b2dc2574ae8649e2f270dc53))
* Unpin uv self-updates and warn when a stale dcode shadows PATH ([#4185](https://github.com/langchain-ai/deepagents/issues/4185)) ([8ca0a18](https://github.com/langchain-ai/deepagents/commit/8ca0a185a15f800267cc057178a348fb5063df1e))

## [0.1.21](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.20...deepagents-code==0.1.21) (2026-06-23)

### Features

* `dcode doctor` diagnostics command ([#4148](https://github.com/langchain-ai/deepagents/issues/4148)) ([8179731](https://github.com/langchain-ai/deepagents/commit/81797312c7d857e7d94d03c9c695cd3c8d88799a))
* Add structured TUI display for `js_eval` ([#4151](https://github.com/langchain-ai/deepagents/issues/4151)) ([91c0dae](https://github.com/langchain-ai/deepagents/commit/91c0dae3fe0253f02a5926fcd3c6f796cd8d11fe))
* Allow dependency updates without requiring release ([#4157](https://github.com/langchain-ai/deepagents/issues/4157)) ([7beb97a](https://github.com/langchain-ai/deepagents/commit/7beb97a2b02e2fd238baf3b6f05d43a4accf3f42))
* Clear chat input via `esc+esc`, add `[ X ]/[ COPY ]` buttons ([#4000](https://github.com/langchain-ai/deepagents/issues/4000)) ([c20546f](https://github.com/langchain-ai/deepagents/commit/c20546feac7876786e6816776d1ccfa5fcd4b2c8))
* Confirm "Launched" after auto-update restart ([#4098](https://github.com/langchain-ai/deepagents/issues/4098)) ([df8db8a](https://github.com/langchain-ai/deepagents/commit/df8db8af6a7cbfc2ab535020b951d73759da73dd))
* Surface tracing in `doctor` and `config show` ([#4163](https://github.com/langchain-ai/deepagents/issues/4163)) ([2bb3e44](https://github.com/langchain-ai/deepagents/commit/2bb3e44243553a5f2954a0f3ec42364563842a87))

### Bug Fixes

* Handle LangSmith project-not-found and default tracing project ([#4153](https://github.com/langchain-ai/deepagents/issues/4153)) ([e303ce9](https://github.com/langchain-ai/deepagents/commit/e303ce986a3595f0cf458e796d857f7c8f5f8b5c))
* Make `/timestamps` toggle instant via per-footer class ([#4095](https://github.com/langchain-ai/deepagents/issues/4095)) ([7ae32b0](https://github.com/langchain-ai/deepagents/commit/7ae32b0a606cc200d4311e11036a65f17e8282b3))
* Refocus `/mcp` filter input after in-place refresh ([#4080](https://github.com/langchain-ai/deepagents/issues/4080)) ([d79cd74](https://github.com/langchain-ai/deepagents/commit/d79cd74cb8a44c300c3bbad712fe77e709f9221a))
* Report same-version dependency updates ([#4146](https://github.com/langchain-ai/deepagents/issues/4146)) ([156e118](https://github.com/langchain-ai/deepagents/commit/156e1185242a19746f8c268904637c73f07b9a10))
* Show "Loading..." in `/threads` agent dropdown while loading ([#4101](https://github.com/langchain-ai/deepagents/issues/4101)) ([c2d949e](https://github.com/langchain-ai/deepagents/commit/c2d949e8765fbbbdb81e5a70125932842358099f))
* Skip tool interrupts once auto-approve is set ([#4092](https://github.com/langchain-ai/deepagents/issues/4092)) ([9e21c34](https://github.com/langchain-ai/deepagents/commit/9e21c346a6eb8ad25b9cc671f24527b07732e2b7))
* Word-delete backspace parity in ask-user text area ([#4079](https://github.com/langchain-ai/deepagents/issues/4079)) ([ed3c499](https://github.com/langchain-ai/deepagents/commit/ed3c499354467bc5e8476e5c7cdf0cd5f8b6aec1))

## [0.1.20](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.19...deepagents-code==0.1.20) (2026-06-17)

### Features

* Manage Tavily web-search API key in `/auth` ([#4062](https://github.com/langchain-ai/deepagents/issues/4062)) ([90cc099](https://github.com/langchain-ai/deepagents/commit/90cc099b0998a9aa55df01e3bc12ad1597c65365))
* Surface uninstalled known providers in `/auth` menu ([#4059](https://github.com/langchain-ai/deepagents/issues/4059)) ([73db271](https://github.com/langchain-ai/deepagents/commit/73db2719bce5ad3c933ffee643df4a62cfd60e17))
* Show provider in usage stats table ([#4049](https://github.com/langchain-ai/deepagents/issues/4049)) ([309b054](https://github.com/langchain-ai/deepagents/commit/309b054fdd040adb5086408a3bcb2550ba73439e))
* Quiet install script's full dependency list ([#4058](https://github.com/langchain-ai/deepagents/issues/4058)) ([de2c9fd](https://github.com/langchain-ai/deepagents/commit/de2c9fd8c7437fdcdfe738599f83808c5423c55c))

### Bug Fixes

* Read `LANGSMITH_PROJECT` for `tracing.langsmith_project` + show default ([#4054](https://github.com/langchain-ai/deepagents/issues/4054)) ([fec1551](https://github.com/langchain-ai/deepagents/commit/fec1551e901a4fe88bd74ee4833a91ef93b1e93f))
* Surface recommended models missing from installed provider profiles ([#4057](https://github.com/langchain-ai/deepagents/issues/4057)) ([56e0d31](https://github.com/langchain-ai/deepagents/commit/56e0d31b6c507d5a1e95c3f2058a8d3b9488a4db))
* Clarify post-update restart semantics ([#4046](https://github.com/langchain-ai/deepagents/issues/4046)) ([6318b81](https://github.com/langchain-ai/deepagents/commit/6318b817399f7dd2f2e6dc07987dca46f1da9886))
* Hide `[SYSTEM]` interrupt notices from `/threads` prompt ([#3988](https://github.com/langchain-ai/deepagents/issues/3988)) ([68fa0cb](https://github.com/langchain-ai/deepagents/commit/68fa0cb4d48ff3f3e552bbf16f8316433c7b6f34))
* Keep install-required `/model` rows dimmed after navigation ([#4048](https://github.com/langchain-ai/deepagents/issues/4048)) ([c499634](https://github.com/langchain-ai/deepagents/commit/c499634c530dcab9b18e3126b4573ff0d36c3efa))
* Rescaffold server workspace on `/restart` when config is missing ([#4050](https://github.com/langchain-ai/deepagents/issues/4050)) ([de51b0e](https://github.com/langchain-ai/deepagents/commit/de51b0e082293f5f795d96d3bf717c82efb9337e))
* Remove transient `Restarting server...` message after restart ([#4047](https://github.com/langchain-ai/deepagents/issues/4047)) ([87cc504](https://github.com/langchain-ai/deepagents/commit/87cc50428bc96ef11dfb11cee4020bff322a7216))
* Suppress model-switch defer toast on bare reconnect ([#4060](https://github.com/langchain-ai/deepagents/issues/4060)) ([60b1052](https://github.com/langchain-ai/deepagents/commit/60b10520d24c87b9c8c9d85b94cffae9e3c67c43))

## [0.1.19](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.18...deepagents-code==0.1.19) (2026-06-17)

### Features

* Add latest frontier models to recommended list ([#4045](https://github.com/langchain-ai/deepagents/issues/4045)) ([1145356](https://github.com/langchain-ai/deepagents/commit/114535637eaee383c64eac5282bc9ac57007c83f))
* Dual-write agent traces to extra LangSmith projects ([#3998](https://github.com/langchain-ai/deepagents/issues/3998)) ([1b94cf3](https://github.com/langchain-ai/deepagents/commit/1b94cf322949e0cafd6f2bacf343fb0044ec5a8c))
* Prompt to install provider when selecting an uninstalled model ([#3981](https://github.com/langchain-ai/deepagents/issues/3981)) ([619207c](https://github.com/langchain-ai/deepagents/commit/619207c8d4d4308a9a3ab9d2d039506feeaf8a67))
* Note minimum OpenAI key permissions in `/auth` ([#4040](https://github.com/langchain-ai/deepagents/issues/4040)) ([14be63d](https://github.com/langchain-ai/deepagents/commit/14be63d476ed8dece75e20fff05016122c258be8))

### Bug Fixes

* Exclude prompt prefix from `UserMessage` selection ([#4002](https://github.com/langchain-ai/deepagents/issues/4002)) ([8ee6ba6](https://github.com/langchain-ai/deepagents/commit/8ee6ba6e64895d3d36a5957627221ed7667bc1d4))

## [0.1.18](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.17...deepagents-code==0.1.18) (2026-06-16)

### Features

* Add provider-specific auth guidance ([#4004](https://github.com/langchain-ai/deepagents/issues/4004)) ([6a39247](https://github.com/langchain-ai/deepagents/commit/6a392471ba30089b1a63135494873d55209bb081))

## [0.1.17](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.16...deepagents-code==0.1.17) (2026-06-16)

### Features

* Make auto-update opt-out by default ([#3994](https://github.com/langchain-ai/deepagents/issues/3994)) ([7ff6e22](https://github.com/langchain-ai/deepagents/commit/7ff6e2224d7ba8462c073333da937c35831f9b34))
* Warn on `--interpreter-tools` without `--interpreter` ([#3976](https://github.com/langchain-ai/deepagents/issues/3976)) ([e68e720](https://github.com/langchain-ai/deepagents/commit/e68e720e2c3caa4e4e7c5e937faf718db7ad2e98))
* Add pre-release update support ([#3960](https://github.com/langchain-ai/deepagents/issues/3960)) ([341a5cc](https://github.com/langchain-ai/deepagents/commit/341a5cc55a30d808dbb366b396923c7801c431d2))
* Add agent filter dropdown to `/threads` picker ([#3677](https://github.com/langchain-ai/deepagents/issues/3677)) ([f8193df](https://github.com/langchain-ai/deepagents/commit/f8193df41d7c47626d94252039217f4079d117cd))
* Non-interactive `deepagents auth` subcommands ([#3910](https://github.com/langchain-ai/deepagents/issues/3910)) ([11a71bb](https://github.com/langchain-ai/deepagents/commit/11a71bbf00c4e6c1f989e70fb3472a65c8d39662))
* Prompt before updating an out-of-date dcode install ([#3995](https://github.com/langchain-ai/deepagents/issues/3995)) ([a5ec6dd](https://github.com/langchain-ai/deepagents/commit/a5ec6dd0fec66ad321c1cc0f5e2f990c9026e03f))

### Bug Fixes

* Guard against misconfigured LangSmith tracing ([#3993](https://github.com/langchain-ai/deepagents/issues/3993)) ([81acc2e](https://github.com/langchain-ai/deepagents/commit/81acc2ecdada55a98e512f96b0caf8cb0f2c6d29))
* Guard restart-prompt import against in-place self-upgrade ([#3980](https://github.com/langchain-ai/deepagents/issues/3980)) ([7af13f6](https://github.com/langchain-ai/deepagents/commit/7af13f6ec2440c2e3eb63bad2ff31e809f772804))
* Skip startup auto-update when already updated in-session ([#3915](https://github.com/langchain-ai/deepagents/issues/3915)) ([3ba3471](https://github.com/langchain-ai/deepagents/commit/3ba347138ac61a474bad58365fdeaa0d00cc1a42))

## [0.1.16](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.15...deepagents-code==0.1.16) (2026-06-13)

### Features

* ChatGPT OAuth sign-in for Codex models ([#3532](https://github.com/langchain-ai/deepagents/issues/3532)) ([202e0bd](https://github.com/langchain-ai/deepagents/commit/202e0bd3e5b8b874a69656815489308d75a77d05))
* Add Vercel Sandbox provider ([#3588](https://github.com/langchain-ai/deepagents/issues/3588)) ([e5e4748](https://github.com/langchain-ai/deepagents/commit/e5e4748cb6c66ddaa9444ab464990c1a5d10854d))

## [0.1.15](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.14...deepagents-code==0.1.15) (2026-06-12)

### Features

* Add Deep Agents client version metadata ([#3934](https://github.com/langchain-ai/deepagents/issues/3934)) ([058cec6](https://github.com/langchain-ai/deepagents/commit/058cec654645dd1a504408d712ab678edc48273d))

## [0.1.14](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.13...deepagents-code==0.1.14) (2026-06-12)

### Features

* Surface editable mode and core deps in `/version` ([#3898](https://github.com/langchain-ai/deepagents/issues/3898)) ([d4f5a12](https://github.com/langchain-ai/deepagents/commit/d4f5a12cc6d73dc19d24d5748242705d79fa65bf))

### Bug Fixes

* Don't move cursor on click that re-focuses terminal ([#3893](https://github.com/langchain-ai/deepagents/issues/3893)) ([b76788b](https://github.com/langchain-ai/deepagents/commit/b76788b7850e910fe2882cb1a62ffff6ff5085b0))
* Label `-r` resume as `"Resuming..."` in the status bar ([#3892](https://github.com/langchain-ai/deepagents/issues/3892)) ([70cd286](https://github.com/langchain-ai/deepagents/commit/70cd28643bc2ca7da5a61a7b7203c6de2266ca4e))
* Scope `@` file completion to current cwd ([#3874](https://github.com/langchain-ai/deepagents/issues/3874)) ([dd237ac](https://github.com/langchain-ai/deepagents/commit/dd237acd21a39e98e37bb9d98dfae09bc44d5457))
* Set dcode agent names in trace metadata ([#3901](https://github.com/langchain-ai/deepagents/issues/3901)) ([ac94dd6](https://github.com/langchain-ai/deepagents/commit/ac94dd6b139211187cad8685c1152f02c51ba086))
* Surface untracked files in `@` completion ([#3872](https://github.com/langchain-ai/deepagents/issues/3872)) ([2bdf6ea](https://github.com/langchain-ai/deepagents/commit/2bdf6ea329c6b4c8be5f0075528e00c7ce2c1e6a))
* Warn on misconfigured subagent files ([#3873](https://github.com/langchain-ai/deepagents/issues/3873)) ([f1614d6](https://github.com/langchain-ai/deepagents/commit/f1614d67827c3d4d3bd01a784f57f83a50ec3410))

### Performance Improvements

* Cache theme colors/charset, fix `O(n^2)` tool-call streaming ([#3881](https://github.com/langchain-ai/deepagents/issues/3881)) ([9d463f5](https://github.com/langchain-ai/deepagents/commit/9d463f52fb3a4d458477982963f3d278d5362b48))

## [0.1.13](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.12...deepagents-code==0.1.13) (2026-06-11)

### Features

* Pluggable third-party sandbox backends ([#3842](https://github.com/langchain-ai/deepagents/issues/3842)) ([2b635a7](https://github.com/langchain-ai/deepagents/commit/2b635a7e6e6b50ca8ce783c2ac96ed8643ae0224))
* Auto-install ripgrep on first run ([#3348](https://github.com/langchain-ai/deepagents/issues/3348)) ([fecf22b](https://github.com/langchain-ai/deepagents/commit/fecf22b0909e79ff7bdf180baf20abf5fdf1f390))
* `config` command and canonical config manifest ([#3763](https://github.com/langchain-ai/deepagents/issues/3763)) ([79899a3](https://github.com/langchain-ai/deepagents/commit/79899a306d01de6217a1dfcc013ae92c808a47a0))
* Confirm modal for `/install --package` ([#3840](https://github.com/langchain-ai/deepagents/issues/3840)) ([3d75026](https://github.com/langchain-ai/deepagents/commit/3d75026e2f241648fae78d9e1de2cbb4985f58ff))
* Copy focused input selection on `Ctrl+C` ([#3841](https://github.com/langchain-ai/deepagents/issues/3841)) ([99f782c](https://github.com/langchain-ai/deepagents/commit/99f782cf08336c200d02a24ae4edaa650af67ed2))
* `[retries]` config ([#3772](https://github.com/langchain-ai/deepagents/issues/3772)) ([9334d91](https://github.com/langchain-ai/deepagents/commit/9334d91ef94997e46d5373daca9c146fa9498763))
* Show connection state in the status bar ([#3710](https://github.com/langchain-ai/deepagents/issues/3710)) ([3e3e8fe](https://github.com/langchain-ai/deepagents/commit/3e3e8feb0e6e1b77be75a7756fbf32e5c9497c28))
* Surface LangSmith tracing projects in `LocalContextMiddleware` ([#3836](https://github.com/langchain-ai/deepagents/issues/3836)) ([676abec](https://github.com/langchain-ai/deepagents/commit/676abecf892ff537fcb1425ba5929cace3c5d503))

### Bug Fixes

* Add debug-log guidance for truncated startup errors ([#3849](https://github.com/langchain-ai/deepagents/issues/3849)) ([cd1ef30](https://github.com/langchain-ai/deepagents/commit/cd1ef303cf5d0e9d746c787eb09a4a89437e965a))
* Drop lock-key events so Caps Lock in iTerm2 doesn't type ([#3855](https://github.com/langchain-ai/deepagents/issues/3855)) ([110f1a7](https://github.com/langchain-ai/deepagents/commit/110f1a7a975743efda12e181cb3afc8404202254))
* Hand pointer over splash tracing project link ([#3858](https://github.com/langchain-ai/deepagents/issues/3858)) ([ea7dae5](https://github.com/langchain-ai/deepagents/commit/ea7dae58a37cfb1d2b96544eb7c941aad331b280))
* Keep terminal-default theme on Esc in `/theme` selector ([#3854](https://github.com/langchain-ai/deepagents/issues/3854)) ([c3bc67b](https://github.com/langchain-ai/deepagents/commit/c3bc67b0cdeda6f4dbcc6360ddd72b455aec4fe7))
* Preserve inherited `PYTHONPATH` for server subprocess ([#3833](https://github.com/langchain-ai/deepagents/issues/3833)) ([4689569](https://github.com/langchain-ai/deepagents/commit/4689569f94138987319cd9cbb45ce66a1f496934))
* Resolve interpreter PTC allowlist against the runtime tool registry ([#3845](https://github.com/langchain-ai/deepagents/issues/3845)) ([c59a27e](https://github.com/langchain-ai/deepagents/commit/c59a27ef2405b8e04c4351ce7ffa53d8d16d519c))
* Treat multi-line key-event pastes as one input ([#3856](https://github.com/langchain-ai/deepagents/issues/3856)) ([6bb15d4](https://github.com/langchain-ai/deepagents/commit/6bb15d4bd97bd16f47504f937c8458d1b53d9cc4))

## [0.1.12](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.11...deepagents-code==0.1.12) (2026-06-10)

### Features

* Add `get_current_thread_id` tool ([#3820](https://github.com/langchain-ai/deepagents/issues/3820)) ([18ce094](https://github.com/langchain-ai/deepagents/commit/18ce094b7036796c7e23ce1338f4da56dc2ef126))
* Guard managed onboarding-name memory block from edits ([#3822](https://github.com/langchain-ai/deepagents/issues/3822)) ([dc0a51f](https://github.com/langchain-ai/deepagents/commit/dc0a51fc81d01b62dc8043148a9fd87099fc9123))
* Offer restart after restart-capable install ([#3821](https://github.com/langchain-ai/deepagents/issues/3821)) ([e356efe](https://github.com/langchain-ai/deepagents/commit/e356efeff1c8bfb894119cebbb7d3c0853d327a2))
* Persist `/threads` directory-scope preference ([#3824](https://github.com/langchain-ai/deepagents/issues/3824)) ([51a29f4](https://github.com/langchain-ai/deepagents/commit/51a29f4a0c28c122acae296a0df03bee20474455))
* Surface gateway key mismatch on `PermissionDeniedError` ([#3813](https://github.com/langchain-ai/deepagents/issues/3813)) ([5bd1ef8](https://github.com/langchain-ai/deepagents/commit/5bd1ef8cb29db781ccbb37755db44ce0ab1d7bd2))

### Bug Fixes

* Surface cached MCP errors as failed tool messages ([#3829](https://github.com/langchain-ai/deepagents/issues/3829)) ([d83b428](https://github.com/langchain-ai/deepagents/commit/d83b428f7f97bc40b9219c02846c2d8b4ccac434))
* Handle MCP tool errors locally ([#3830](https://github.com/langchain-ai/deepagents/issues/3830)) ([97a7052](https://github.com/langchain-ai/deepagents/commit/97a7052b3eef7ec80bc90a4c3b606deeaf13cb9b))
* Make non-incognito `!` shell output visible to the model ([#3825](https://github.com/langchain-ai/deepagents/issues/3825)) ([2407bca](https://github.com/langchain-ai/deepagents/commit/2407bca66bac5d199a923a0e58872c813eb006bc))
* Expose `/restart` slash command ([#3809](https://github.com/langchain-ai/deepagents/issues/3809)) ([64505b8](https://github.com/langchain-ai/deepagents/commit/64505b848868b80213b6da87113cd63890c3d520))
* Agent retries `gh search` with invalid `mergedAt` field ([#3802](https://github.com/langchain-ai/deepagents/issues/3802)) ([0b683a9](https://github.com/langchain-ai/deepagents/commit/0b683a9435b95bce79d10451868eae54c6a3e88c))
* Clarify `/restart` message during server startup ([#3823](https://github.com/langchain-ai/deepagents/issues/3823)) ([49ded9e](https://github.com/langchain-ai/deepagents/commit/49ded9ef448dcd263bee07ac15f4904dd342bfa2))
* Cursor at end when popping queued message to input ([#3832](https://github.com/langchain-ai/deepagents/issues/3832)) ([aa522c9](https://github.com/langchain-ai/deepagents/commit/aa522c94fffb93dc578addb39b4879f779ac5899))
* Coalesce streamed markdown writes to keep input responsive ([#3819](https://github.com/langchain-ai/deepagents/issues/3819)) ([b45eeeb](https://github.com/langchain-ai/deepagents/commit/b45eeebaf7e6ae6e07b8f9ca521525c66fe14f63))
* Don't show `"No threads found"` while threads load ([#3815](https://github.com/langchain-ai/deepagents/issues/3815)) ([68e6426](https://github.com/langchain-ai/deepagents/commit/68e64263f590b3244b689664715f354fb3a389cd))
* Ignore stale cwd warmers in file autocomplete cache ([#3835](https://github.com/langchain-ai/deepagents/issues/3835)) ([9c8c2b2](https://github.com/langchain-ai/deepagents/commit/9c8c2b24853b7b3a7610cbcfc368a6464c0711e0))
* Offer cwd switch on resume ([#3810](https://github.com/langchain-ai/deepagents/issues/3810)) ([d417f53](https://github.com/langchain-ai/deepagents/commit/d417f530aafa8c77523487393dc3039cc822dc09))
* Recover from tool errors instead of aborting run ([#3804](https://github.com/langchain-ai/deepagents/issues/3804)) ([45691c5](https://github.com/langchain-ai/deepagents/commit/45691c556105e171c7210c7c10388dc73202a025))
* Show `/restart` feedback ([#3808](https://github.com/langchain-ai/deepagents/issues/3808)) ([c40bef9](https://github.com/langchain-ai/deepagents/commit/c40bef9b2aaace3909593503b28e8b548bc20014))
* Standardize search previews and restart status ([#3806](https://github.com/langchain-ai/deepagents/issues/3806)) ([71a6d50](https://github.com/langchain-ai/deepagents/commit/71a6d508b21b275c0c7c6bd2e0752adfba496ea9))
* Suppress stale update notices ([#3801](https://github.com/langchain-ai/deepagents/issues/3801)) ([db25241](https://github.com/langchain-ai/deepagents/commit/db252411d8ca945aca86429acb644540ec970bdb))
* Unblock `/remember` in server mode ([#3812](https://github.com/langchain-ai/deepagents/issues/3812)) ([12e00e1](https://github.com/langchain-ai/deepagents/commit/12e00e1a78e2d6be106147a0aa95a518be66849f))
* Unblock TUI input during `/restart` ([#3826](https://github.com/langchain-ai/deepagents/issues/3826)) ([366cd81](https://github.com/langchain-ai/deepagents/commit/366cd81269e2d3891a477848b774cf51af0cefc0))

## [0.1.11](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.10...deepagents-code==0.1.11) (2026-06-07)

### Bug Fixes

* Pause loading timer during approvals ([#3782](https://github.com/langchain-ai/deepagents/issues/3782)) ([f98fb0c](https://github.com/langchain-ai/deepagents/commit/f98fb0c80d08e408a018ea33a8aa7144180f4e93))
* Run auto-update before startup ([#3784](https://github.com/langchain-ai/deepagents/issues/3784)) ([c160ea3](https://github.com/langchain-ai/deepagents/commit/c160ea3eeda1d0ba707bb524cfd0ce087a854e08))
* Skip update prompts for editable installs ([#3781](https://github.com/langchain-ai/deepagents/issues/3781)) ([ae2874e](https://github.com/langchain-ai/deepagents/commit/ae2874e8ece96c04233c1a88a9da1bd7b9ee2bb2))

## [0.1.10](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.9...deepagents-code==0.1.10) (2026-06-05)

### Features

* Pair model API keys with their endpoints ([#3770](https://github.com/langchain-ai/deepagents/issues/3770)) ([cf98030](https://github.com/langchain-ai/deepagents/commit/cf9803072dc0fdc1d5850c9fd2fc4eb6893ed8c9))
* Word-level double-click selection ([#3740](https://github.com/langchain-ai/deepagents/issues/3740)) ([4bb4286](https://github.com/langchain-ai/deepagents/commit/4bb4286a26c9c9bc69a36f2714d9eb0e3e5e4d40))
* Blueprint bootstrapping for Runloop sandboxes ([#3556](https://github.com/langchain-ai/deepagents/issues/3556)) ([13dafd8](https://github.com/langchain-ai/deepagents/commit/13dafd8823c4b530c8e096012733ad74cd501b59))

### Bug Fixes

* Propagate runtime model switches to subagents ([#3771](https://github.com/langchain-ai/deepagents/issues/3771)) ([f577182](https://github.com/langchain-ai/deepagents/commit/f577182c84746e625b65c3c2fda95f8ca21164cf))
* Guard pasted-path probes against `OSError` ([#3745](https://github.com/langchain-ai/deepagents/issues/3745)) ([c9617d3](https://github.com/langchain-ai/deepagents/commit/c9617d3594ab1448c4f3ee2212cdc66cbf138b77))
* Keep startup import prewarm from crashing the TUI mid-upgrade ([#3756](https://github.com/langchain-ai/deepagents/issues/3756)) ([867a2e5](https://github.com/langchain-ai/deepagents/commit/867a2e5c341bd9dfa70b47c7fafc194ac51d7469))
* Move MCP trust state out of user config ([#3742](https://github.com/langchain-ai/deepagents/issues/3742)) ([a97f2fd](https://github.com/langchain-ai/deepagents/commit/a97f2fd394e6b0b943225a0195b0901188bd368c))

## [0.1.9](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.8...deepagents-code==0.1.9) (2026-06-03)

### Bug Fixes

* Add terminal progress preference ([#3728](https://github.com/langchain-ai/deepagents/issues/3728)) ([d9e4976](https://github.com/langchain-ai/deepagents/commit/d9e4976826ae2281e90e06facb5a70a785703029))

## [0.1.8](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.7...deepagents-code==0.1.8) (2026-06-02)

### Features

* List valid extras when `/install` has no argument ([#3695](https://github.com/langchain-ai/deepagents/issues/3695)) ([c7d529c](https://github.com/langchain-ai/deepagents/commit/c7d529ca0fc478dec9060ea04bcc8589f9b1cd3a))
* Add MCP error detail modal ([#3687](https://github.com/langchain-ai/deepagents/issues/3687)) ([4ae4754](https://github.com/langchain-ai/deepagents/commit/4ae475453ce0df6d6b057b7e163396aa27d55143))

### Bug Fixes

* Allow recovery commands when startup fails ([#3706](https://github.com/langchain-ai/deepagents/issues/3706)) ([727d022](https://github.com/langchain-ai/deepagents/commit/727d022cd1526836c3d1de997c1f036e870881f7))
* Preserve extras during install ([#3707](https://github.com/langchain-ai/deepagents/issues/3707)) ([e636ce9](https://github.com/langchain-ai/deepagents/commit/e636ce9e979fd1c30335ec340acdabbd0a5ae79e))
* Normalize empty file list tool output ([#3697](https://github.com/langchain-ai/deepagents/issues/3697)) ([b67aead](https://github.com/langchain-ai/deepagents/commit/b67aead2b86e04aaee8f2dbfba7b263e3e23597d))
* Point MCP re-enable guidance at `Ctrl+R` ([#3688](https://github.com/langchain-ai/deepagents/issues/3688)) ([15ca302](https://github.com/langchain-ai/deepagents/commit/15ca3029f18fa38c1592859febc2a6d0469bff2d))
* Preserve MCP token refresh when metadata discovery fails ([#3685](https://github.com/langchain-ai/deepagents/issues/3685)) ([afafeeb](https://github.com/langchain-ai/deepagents/commit/afafeeb471c4008d4eb4263ec478cf868833fe0b))
* Reduce OAuth login modal noise ([#3693](https://github.com/langchain-ai/deepagents/issues/3693)) ([0e8a780](https://github.com/langchain-ai/deepagents/commit/0e8a780e2dfea2e22ac44545a16279dbe30eb8ee))
* Repair MCP OAuth login redirect and stale client registration ([#3692](https://github.com/langchain-ai/deepagents/issues/3692)) ([f741293](https://github.com/langchain-ai/deepagents/commit/f741293524f7d47eb8a16a3cd4def336c3c3c13f))
* Search all models from `/model` filter ([#3690](https://github.com/langchain-ai/deepagents/issues/3690)) ([5fcb877](https://github.com/langchain-ai/deepagents/commit/5fcb877d094c4504f671bb7aeb52efa7bf3a5b48))
* Serialize `QueuedUserMessage` as user input ([#3708](https://github.com/langchain-ai/deepagents/issues/3708)) ([307d598](https://github.com/langchain-ai/deepagents/commit/307d59826da9b1ddcbcdab8dccef6d18ecf16d10))
* Serialize cold SDK imports ([#3712](https://github.com/langchain-ai/deepagents/issues/3712)) ([fb2adc0](https://github.com/langchain-ai/deepagents/commit/fb2adc0585e978b12646602ba922e252abf41f81))
* Pluralize singular MCP login splash text ([#3689](https://github.com/langchain-ai/deepagents/issues/3689)) ([492b0fc](https://github.com/langchain-ai/deepagents/commit/492b0fc9209e13cd7004a255ef67b31b7e78e95e))

## [0.1.7](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.6...deepagents-code==0.1.7) (2026-05-30)

### Features

* Add toggleable message timestamp footers ([#3662](https://github.com/langchain-ai/deepagents/issues/3662)) ([977e110](https://github.com/langchain-ai/deepagents/commit/977e11006cfbd78fbaba4e7bb2a13acf6b788652))

### Bug Fixes

* Fix zero tool MCP server rendering ([#3649](https://github.com/langchain-ai/deepagents/issues/3649)) ([7e7a567](https://github.com/langchain-ai/deepagents/commit/7e7a567556110ad927a78b45c3a3d4ac37b65e86))
* Centralize debug logging setup to package root ([#3650](https://github.com/langchain-ai/deepagents/issues/3650)) ([5145ed1](https://github.com/langchain-ai/deepagents/commit/5145ed1f8296f41d78c905c2ce899d2742f7dc9b))
* Char-truncate execute tool preview output ([#3627](https://github.com/langchain-ai/deepagents/issues/3627)) ([bb276e2](https://github.com/langchain-ai/deepagents/commit/bb276e2c41177b0dfe6ffd44fd37a293fbfdcb27))
* Handle stale slash-command `Enter` before completion popup renders ([#3647](https://github.com/langchain-ai/deepagents/issues/3647)) ([9a28742](https://github.com/langchain-ai/deepagents/commit/9a287424e86d5d52d0a328388c3fe453b160f597))
* Keep chat input focused when clicking a message ([#3655](https://github.com/langchain-ai/deepagents/issues/3655)) ([daf6571](https://github.com/langchain-ai/deepagents/commit/daf65716d7c999eadb2b7c37e412ec07b2c7aed3))
* Mention `Ctrl+R` in MCP reconnect toast ([#3622](https://github.com/langchain-ai/deepagents/issues/3622)) ([3b4b086](https://github.com/langchain-ai/deepagents/commit/3b4b0867665e58959073e660d85b74c700acaa1e))
* Prevent duplicate-id crash on MCP reconnect and clipboard `NoScreen` ([#3632](https://github.com/langchain-ai/deepagents/issues/3632)) ([6b9a3c0](https://github.com/langchain-ai/deepagents/commit/6b9a3c051586c26c542e958849e952d08a4b5a88))
* Reconstruct message counts for `DeltaChannel` threads from writes table ([#3668](https://github.com/langchain-ai/deepagents/issues/3668)) ([27e1940](https://github.com/langchain-ai/deepagents/commit/27e1940a924abfc999126cf46024003f453ba0c8))
* Render MCP tool errors and drop empty-string optional params ([#3624](https://github.com/langchain-ai/deepagents/issues/3624)) ([fdf3db4](https://github.com/langchain-ai/deepagents/commit/fdf3db464cd9f3de4e84c246547dd2971d26c726))
* Respect line width in tool output previews ([#3646](https://github.com/langchain-ai/deepagents/issues/3646)) ([ba1ad2d](https://github.com/langchain-ai/deepagents/commit/ba1ad2dbabd19b3821490537465a3bcd39c6fed6))
* Restore resumed thread model ([#3651](https://github.com/langchain-ai/deepagents/issues/3651)) ([550a8ab](https://github.com/langchain-ai/deepagents/commit/550a8abf3c595d738162a97f694b5d9527613323))
* Tool spinner, result formatting, and expand-hint fixes ([#3661](https://github.com/langchain-ai/deepagents/issues/3661)) ([54485a3](https://github.com/langchain-ai/deepagents/commit/54485a305854f46a6ce00ae4df51f3301c652a38))

## [0.1.6](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.5...deepagents-code==0.1.6) (2026-05-27)

### Features

* `/install` optional extras ([#3606](https://github.com/langchain-ai/deepagents/issues/3606)) ([7ffaa93](https://github.com/langchain-ai/deepagents/commit/7ffaa93dca6910cd454040d416ff7e0e8bcbcea5))
* Surface deferred MCP reconnect state in `/mcp` ([#3612](https://github.com/langchain-ai/deepagents/issues/3612)) ([d8205c2](https://github.com/langchain-ai/deepagents/commit/d8205c2a39d00e8b6f7f70afe7cc9bb92fee42d8))
* Surface MCP servers awaiting reconnect on splash banner ([#3615](https://github.com/langchain-ai/deepagents/issues/3615)) ([24c5258](https://github.com/langchain-ai/deepagents/commit/24c5258ae6664bc3d3875d8065038716f7c86161))

### Bug Fixes

* Cancel server-side runs before re-trying interrupted-state writes ([#3611](https://github.com/langchain-ai/deepagents/issues/3611)) ([7d46357](https://github.com/langchain-ai/deepagents/commit/7d46357c5446bbc6225f972fd66dc52af8dd0547))
* Editable-install guidance for adding extras ([#3610](https://github.com/langchain-ai/deepagents/issues/3610)) ([771e55f](https://github.com/langchain-ai/deepagents/commit/771e55f171b8087b876ecf767d2f23c86c2a27b9))
* Reuse persisted DCR loopback port across OAuth launches ([#3613](https://github.com/langchain-ai/deepagents/issues/3613)) ([f2f7471](https://github.com/langchain-ai/deepagents/commit/f2f747104945ac79b68e6524d6da886f7cfeb1b0))
* Polish MCP auth success UX ([#3614](https://github.com/langchain-ai/deepagents/issues/3614)) ([d225cb4](https://github.com/langchain-ai/deepagents/commit/d225cb41f41a0a9b2876aff2443eaa0ada24bf29))

## [0.1.5](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.4...deepagents-code==0.1.5) (2026-05-26)

### Bug Fixes

* Join aiosqlite worker thread after close ([#3585](https://github.com/langchain-ai/deepagents/issues/3585)) ([152cec0](https://github.com/langchain-ai/deepagents/commit/152cec04affed3508d4bfdffe7cae522b16d45e6))

## [0.1.4](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.3...deepagents-code==0.1.4) (2026-05-23)

### Features

* Add `--sandbox-snapshot-name` flag ([#3538](https://github.com/langchain-ai/deepagents/issues/3538)) ([b01392e](https://github.com/langchain-ai/deepagents/commit/b01392e7549798434f27f3784fa8c4e734053787))
* `dcode mcp config` and unify `--mcp-config` flag ([#3541](https://github.com/langchain-ai/deepagents/issues/3541)) ([f037b14](https://github.com/langchain-ai/deepagents/commit/f037b140f90a1ba3725b3ef23ab385b3cafe223b))
* Interpreter middleware via `langchain-quickjs` ([#3525](https://github.com/langchain-ai/deepagents/issues/3525)) ([f0ca89c](https://github.com/langchain-ai/deepagents/commit/f0ca89c962c22058194121526638bc2d29f546bd))

### Bug Fixes

* Chat input history navigation and newline scrolling ([#3560](https://github.com/langchain-ai/deepagents/issues/3560)) ([3b51cbd](https://github.com/langchain-ai/deepagents/commit/3b51cbdc8c50d9990477e18a47de6a58e9165bab))
* Distinguish LangSmith failure modes in `/trace` ([#3558](https://github.com/langchain-ai/deepagents/issues/3558)) ([4d158a0](https://github.com/langchain-ai/deepagents/commit/4d158a031aecad8862e02e332f127573003938ec))
* Recover initial session prompts from writes table ([#3535](https://github.com/langchain-ai/deepagents/issues/3535)) ([46b6f3f](https://github.com/langchain-ai/deepagents/commit/46b6f3f3e6ce880cd5ec9cf59622bb745d6ac2eb))
* Install script binary checks reference `dcode` ([#3546](https://github.com/langchain-ai/deepagents/issues/3546)) ([f8977a6](https://github.com/langchain-ai/deepagents/commit/f8977a63769e3f2037619f32596cb9bb7bd1020b))
* Show tool call previews during batched HITL approvals ([#3530](https://github.com/langchain-ai/deepagents/issues/3530)) ([84daa1a](https://github.com/langchain-ai/deepagents/commit/84daa1a2e27963a6d7694dc9278de83782b4a7b7))

## [0.1.3](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.2...deepagents-code==0.1.3) (2026-05-20)

### Features

* In-TUI MCP OAuth login with auto-refresh ([#3469](https://github.com/langchain-ai/deepagents/issues/3469)) ([20e38b8](https://github.com/langchain-ai/deepagents/commit/20e38b8ebd8d9aa4697334432f7832a0a07aea3a))
  * Float unauthorized MCP servers to top and prompt before reconnect ([#3493](https://github.com/langchain-ai/deepagents/issues/3493)) ([2d66580](https://github.com/langchain-ai/deepagents/commit/2d665804131961dfa7e2849248047deec818e4ef))
  * Disable MCP servers from TUI ([#3501](https://github.com/langchain-ai/deepagents/issues/3501)) ([5725de8](https://github.com/langchain-ai/deepagents/commit/5725de857722dbca768a95bc6d97af5b838a11a9))
* `/restart` hidden slash command ([#3514](https://github.com/langchain-ai/deepagents/issues/3514)) ([74bdd36](https://github.com/langchain-ai/deepagents/commit/74bdd3688948d8369cdd978590f5a822eabeb12c))

### Bug Fixes

* Persist `_context_tokens` via `after_model` middleware ([#3496](https://github.com/langchain-ai/deepagents/issues/3496)) ([e2bb284](https://github.com/langchain-ai/deepagents/commit/e2bb284e506e0e49a05169fc6de01bdf42350267))
* Refresh status bar model after recovering from failed startup ([#3511](https://github.com/langchain-ai/deepagents/issues/3511)) ([c96f822](https://github.com/langchain-ai/deepagents/commit/c96f822de187431404d093b852c4a855d3ab8d30))

## [0.1.2](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.1...deepagents-code==0.1.2) (2026-05-19)

### Features

* `/model` toggle for recommended-only list ([#3453](https://github.com/langchain-ai/deepagents/issues/3453)) ([c326b7e](https://github.com/langchain-ai/deepagents/commit/c326b7ec1b9940861175e0466ab4221f03e2bcba))
* `--timeout` flag for non-interactive ([#3351](https://github.com/langchain-ai/deepagents/issues/3351)) ([44e86ab](https://github.com/langchain-ai/deepagents/commit/44e86abbb1870f689dace8b1be6ed430d65e74c1))
* Browser loopback OAuth callback for MCP auth ([#3467](https://github.com/langchain-ai/deepagents/issues/3467)) ([d83aa07](https://github.com/langchain-ai/deepagents/commit/d83aa07c818af35800f81d062a147fa45a47ace7))
* MCP screen metadata ([#3349](https://github.com/langchain-ai/deepagents/issues/3349)) ([ce2f07e](https://github.com/langchain-ai/deepagents/commit/ce2f07e7211f22b3f44a1a232088b89a469a0a99))

### Bug Fixes

* Drop sections from `system_prompt.md` already supplied by SDK middleware ([#3448](https://github.com/langchain-ai/deepagents/issues/3448)) ([9dbf2c2](https://github.com/langchain-ai/deepagents/commit/9dbf2c2f19e941e012d0c93418ef09fb56f30d6a))
* Rename stale usage commands ([#3460](https://github.com/langchain-ai/deepagents/issues/3460)) ([da43b7f](https://github.com/langchain-ai/deepagents/commit/da43b7f9d913e6190ff03c496a269faf08bbf182))
* Suppress interrupt-cleanup state writes from traces ([#3465](https://github.com/langchain-ai/deepagents/issues/3465)) ([319b24e](https://github.com/langchain-ai/deepagents/commit/319b24e6f179eaf56f105a6db683901c82fe95be))

## [0.1.1](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.0...deepagents-code==0.1.1) (2026-05-16)

### Bug Fixes

* Correct LangSmith sandbox working directory ([#3415](https://github.com/langchain-ai/deepagents/issues/3415)) ([b0e8d83](https://github.com/langchain-ai/deepagents/commit/b0e8d83f97a2a698268173a839000c84e8368324))
* Guard `fetch_url` against SSRF ([#3411](https://github.com/langchain-ai/deepagents/issues/3411)) ([54d8521](https://github.com/langchain-ai/deepagents/commit/54d8521976940dfe147ead4b56565360241335be))

## [0.1.0](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.0.1...deepagents-code==0.1.0) (2026-05-12)

Hello world! Ported from `libs/cli`.

---

## Prior Releases

`deepagents-code` was forked from `deepagents-cli` at v0.1.0 (2026-05-12).
For history prior to the fork, see [the `deepagents-cli` changelog](https://github.com/langchain-ai/deepagents/blob/main/libs/cli/CHANGELOG.md).
