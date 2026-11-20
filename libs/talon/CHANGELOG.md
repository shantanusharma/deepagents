# Changelog

## [0.2.0](https://github.com/shantanusharma/deepagents/compare/deepagents-talon==0.1.1...deepagents-talon==0.2.0) (2026-11-20)


### ⚠ BREAKING CHANGES

* **deps:** `deepagents-code` and `deepagents-talon` now require Python 3.14 (`>=3.14,<3.15`). Re-run the dcode installer, or recreate your environment on Python 3.14.

### Features

* **code,talon:** require Python 3.12 or greater ([#5603](https://github.com/shantanusharma/deepagents/issues/5603)) ([04de43e](https://github.com/shantanusharma/deepagents/commit/04de43e05adcbd38f1022f1fafe93f6748c2a032))
* **deps:** require Python 3.14 ([#7052](https://github.com/shantanusharma/deepagents/issues/7052)) ([96eca0b](https://github.com/shantanusharma/deepagents/commit/96eca0b2e13db0b9e3dd9822d062ad316ba0b5fa))
* **sdk:** optional video frame extraction on `read_file` ([#4094](https://github.com/shantanusharma/deepagents/issues/4094)) ([b927147](https://github.com/shantanusharma/deepagents/commit/b927147d026749c6c790bb06c9853515dabf579c))
* **talon:** `DEEPAGENTS_TALON_RECURSION_LIMIT` env var ([#4354](https://github.com/shantanusharma/deepagents/issues/4354)) ([82d1eac](https://github.com/shantanusharma/deepagents/commit/82d1eac59a43f096096e86849733aa716adb18fc))
* **talon:** add /help command ([#6106](https://github.com/shantanusharma/deepagents/issues/6106)) ([919ad2b](https://github.com/shantanusharma/deepagents/commit/919ad2b56335c4e4cc416d474745efd78e0324a3))
* **talon:** add `/context-doctor` command ([#6557](https://github.com/shantanusharma/deepagents/issues/6557)) ([60c0228](https://github.com/shantanusharma/deepagents/commit/60c0228aad14d042080743ead04e135994d3fa75))
* **talon:** add `/effort` reasoning controls ([#7043](https://github.com/shantanusharma/deepagents/issues/7043)) ([692c234](https://github.com/shantanusharma/deepagents/commit/692c23400e813b37959a206f96e31b89460a310f))
* **talon:** add `/model` command for per-chat model switching ([#6577](https://github.com/shantanusharma/deepagents/issues/6577)) ([40873ba](https://github.com/shantanusharma/deepagents/commit/40873baa880133ae19ea921239ad9142c1972f4f))
* **talon:** add `media-cpu` extra with CPU-only torch on Linux ([#7596](https://github.com/shantanusharma/deepagents/issues/7596)) ([f7c3af6](https://github.com/shantanusharma/deepagents/commit/f7c3af67565f00894cb596f689d41bee10ae89af))
* **talon:** add `openshell` sandbox extra ([#7000](https://github.com/shantanusharma/deepagents/issues/7000)) ([85c1311](https://github.com/shantanusharma/deepagents/commit/85c1311cc2b859a231e1fe1f556564ac80c07474))
* **talon:** add `send_message` for progress updates ([#6264](https://github.com/shantanusharma/deepagents/issues/6264)) ([15606d2](https://github.com/shantanusharma/deepagents/commit/15606d280a8ddb86c8966fef0bab257f8070944f))
* **talon:** add a current_time tool ([#6065](https://github.com/shantanusharma/deepagents/issues/6065)) ([0fe5f94](https://github.com/shantanusharma/deepagents/commit/0fe5f942d6359f956614584f37137bbba78ab589))
* **talon:** add approved one-off `ask_for_help` consultations ([#6605](https://github.com/shantanusharma/deepagents/issues/6605)) ([15d8f47](https://github.com/shantanusharma/deepagents/commit/15d8f471d8c6ba6868fc6d94beb7fad89ef7406f))
* **talon:** add channel debug logging ([#5983](https://github.com/shantanusharma/deepagents/issues/5983)) ([1c14626](https://github.com/shantanusharma/deepagents/commit/1c14626d068ee5e1724d53dc17927d37987ebe36))
* **talon:** add chat-scoped conversation history ([#6105](https://github.com/shantanusharma/deepagents/issues/6105)) ([d121141](https://github.com/shantanusharma/deepagents/commit/d12114143ec4ec15a04c5a7970c82899bf1b3caa))
* **talon:** add configurable conversation history storage ([#6115](https://github.com/shantanusharma/deepagents/issues/6115)) ([99fcef8](https://github.com/shantanusharma/deepagents/commit/99fcef85410736e211f5b0bcb2e9f1651e685105))
* **talon:** add configurable interim progress verbosity ([#7037](https://github.com/shantanusharma/deepagents/issues/7037)) ([4bf5022](https://github.com/shantanusharma/deepagents/commit/4bf50225d9f2bd777c1b2aa722e76273eb772ab0))
* **talon:** add configuration hardening self-review skill ([#6136](https://github.com/shantanusharma/deepagents/issues/6136)) ([e760662](https://github.com/shantanusharma/deepagents/commit/e760662c956c581a0aca2cd4c95a3a7ce2cbd187))
* **talon:** add cron expressions and `until` expiry to scheduled jobs ([#6526](https://github.com/shantanusharma/deepagents/issues/6526)) ([71ae3f6](https://github.com/shantanusharma/deepagents/commit/71ae3f69b161fdb0d009fe91e112e9aa39369a4d))
* **talon:** add Discord channel adapter ([#5992](https://github.com/shantanusharma/deepagents/issues/5992)) ([67c6c17](https://github.com/shantanusharma/deepagents/commit/67c6c17a316c84a6f21eafb95f12e56eedf11e7e))
* **talon:** add Fleet zip import command ([#4493](https://github.com/shantanusharma/deepagents/issues/4493)) ([0289dd0](https://github.com/shantanusharma/deepagents/commit/0289dd0a190e5060e631e840da115dd59c64cf5c))
* **talon:** add general-purpose safety preflight skill ([#6587](https://github.com/shantanusharma/deepagents/issues/6587)) ([86923e1](https://github.com/shantanusharma/deepagents/commit/86923e160c18a6c090045ef1d60a17bd0d65760d))
* **talon:** add independent Slack and Discord breakout tasks ([#6932](https://github.com/shantanusharma/deepagents/issues/6932)) ([aed3f7f](https://github.com/shantanusharma/deepagents/commit/aed3f7f1e17c6bf627fe804ad4219b24678935db))
* **talon:** add local runtime host ([#3759](https://github.com/shantanusharma/deepagents/issues/3759)) ([7358a66](https://github.com/shantanusharma/deepagents/commit/7358a6663b1b2cda42392616eb04d39d01f42b2b))
* **talon:** add main-agent command hooks ([#7380](https://github.com/shantanusharma/deepagents/issues/7380)) ([13e3eab](https://github.com/shantanusharma/deepagents/commit/13e3eab6064015e700e8c3e1c41efcc222d8d62b))
* **talon:** add MCP configuration tools with default approval ([#6097](https://github.com/shantanusharma/deepagents/issues/6097)) ([f5f8dfe](https://github.com/shantanusharma/deepagents/commit/f5f8dfec051905befc83f65ff40100fd01ad2865))
* **talon:** add opt-in agent activity logging ([#5984](https://github.com/shantanusharma/deepagents/issues/5984)) ([3a0f68c](https://github.com/shantanusharma/deepagents/commit/3a0f68ccd08166394e02fd736869482be5759f83))
* **talon:** add optional hybrid conversation history search ([#6108](https://github.com/shantanusharma/deepagents/issues/6108)) ([904326a](https://github.com/shantanusharma/deepagents/commit/904326a7932f72a189fcf0a74ba1f77a4087f79f))
* **talon:** add reaction approval routing ([#4345](https://github.com/shantanusharma/deepagents/issues/4345)) ([3fe8c0c](https://github.com/shantanusharma/deepagents/commit/3fe8c0c35536626f583df08573469506b9529706))
* **talon:** add sender pairing for DM access ([#6579](https://github.com/shantanusharma/deepagents/issues/6579)) ([135e849](https://github.com/shantanusharma/deepagents/commit/135e849484d15974a5dbc997828c9889b2d098fd))
* **talon:** add Slack channel adapter ([#6575](https://github.com/shantanusharma/deepagents/issues/6575)) ([15bd7fd](https://github.com/shantanusharma/deepagents/commit/15bd7fdcfb5b6a02a650a5faa7aced0faf6dd6d8))
* **talon:** add targeted conversation deletion ([#6235](https://github.com/shantanusharma/deepagents/issues/6235)) ([4fb301d](https://github.com/shantanusharma/deepagents/commit/4fb301d647c860d0d8f2108149e58cd9fe623352))
* **talon:** add Telegram channel adapter, CLI wiring, and offset persistence ([#4097](https://github.com/shantanusharma/deepagents/issues/4097)) ([7c87cec](https://github.com/shantanusharma/deepagents/commit/7c87ceca069874db8555705efab3973301baa1cb))
* **talon:** add timezone-aware wall-clock cron schedules ([#6062](https://github.com/shantanusharma/deepagents/issues/6062)) ([afff4f8](https://github.com/shantanusharma/deepagents/commit/afff4f8841bcc370d01c2739f53e882a92ef5c6a))
* **talon:** add tool approval env override ([#4349](https://github.com/shantanusharma/deepagents/issues/4349)) ([d26481d](https://github.com/shantanusharma/deepagents/commit/d26481da615881bae4401dfa485ad925945e667a))
* **talon:** admit paired senders in every chat ([#6592](https://github.com/shantanusharma/deepagents/issues/6592)) ([6744083](https://github.com/shantanusharma/deepagents/commit/6744083d1978b187fce1de0226aad3c5c9a647dc))
* **talon:** allow outbound Slack user mentions ([#6602](https://github.com/shantanusharma/deepagents/issues/6602)) ([b329965](https://github.com/shantanusharma/deepagents/commit/b32996518f9bad4d156d19e35915d51ead7e6019))
* **talon:** answer Discord guild mentions in threads, like Slack ([#7012](https://github.com/shantanusharma/deepagents/issues/7012)) ([2540af1](https://github.com/shantanusharma/deepagents/commit/2540af1ecfc61452b2695bcda032db61279ce1bd))
* **talon:** ask structured clarifying questions over chat ([#7607](https://github.com/shantanusharma/deepagents/issues/7607)) ([0ce4259](https://github.com/shantanusharma/deepagents/commit/0ce42594e2bfd261b1da5e63e41d14e79fd3aa24))
* **talon:** audit reaction approval attempts ([#4348](https://github.com/shantanusharma/deepagents/issues/4348)) ([d7895c4](https://github.com/shantanusharma/deepagents/commit/d7895c4f9b996ad6fe194936bbeaa8beea21e913))
* **talon:** authorize MCP servers through channels ([#6073](https://github.com/shantanusharma/deepagents/issues/6073)) ([76dd223](https://github.com/shantanusharma/deepagents/commit/76dd22334c95083449cc858dec245f98a383bba4))
* **talon:** batch concurrent tool approvals ([#6435](https://github.com/shantanusharma/deepagents/issues/6435)) ([1660147](https://github.com/shantanusharma/deepagents/commit/16601472424400ab4a90608d7d95e8fc61f23267))
* **talon:** deliver thread cron results to the channel by default ([#6632](https://github.com/shantanusharma/deepagents/issues/6632)) ([07628a5](https://github.com/shantanusharma/deepagents/commit/07628a59010348aca443087a19c477f148997b5b))
* **talon:** enable and disable configured MCP servers ([#7608](https://github.com/shantanusharma/deepagents/issues/7608)) ([63e4816](https://github.com/shantanusharma/deepagents/commit/63e4816937aade3536a2f31bcef91d2a5b584df7))
* **talon:** filter conversation history by time window and role ([#7712](https://github.com/shantanusharma/deepagents/issues/7712)) ([c4f08a3](https://github.com/shantanusharma/deepagents/commit/c4f08a3de015003a9f16ebf560e5fef439000f11))
* **talon:** ingest Telegram approval reactions ([#4346](https://github.com/shantanusharma/deepagents/issues/4346)) ([437af0b](https://github.com/shantanusharma/deepagents/commit/437af0bf79332b20ae0c1883c3cc4d91a98c2457))
* **talon:** inspect and guide background subagents ([#7609](https://github.com/shantanusharma/deepagents/issues/7609)) ([e20be5f](https://github.com/shantanusharma/deepagents/commit/e20be5f22e87dd088d706525917b51f1a2945c63))
* **talon:** interrupt active turns for new messages ([#6023](https://github.com/shantanusharma/deepagents/issues/6023)) ([f93752f](https://github.com/shantanusharma/deepagents/commit/f93752f855836b2af358a7c71c35a9f774af58e3))
* **talon:** keep typing indicator alive during long agent turns ([#5993](https://github.com/shantanusharma/deepagents/issues/5993)) ([e0d0afa](https://github.com/shantanusharma/deepagents/commit/e0d0afa18a3b8209f20c24cfda2ad766e476a102))
* **talon:** make background subagent capacity configurable ([#7048](https://github.com/shantanusharma/deepagents/issues/7048)) ([3e904c8](https://github.com/shantanusharma/deepagents/commit/3e904c8cffd39ddf461de2d890118383897c0c74))
* **talon:** make checkpoint backends configurable ([#6727](https://github.com/shantanusharma/deepagents/issues/6727)) ([7bc9474](https://github.com/shantanusharma/deepagents/commit/7bc94742bb503772e207a46d29bbd7cea13e7129))
* **talon:** manage tool approvals through `tools.json` ([#6248](https://github.com/shantanusharma/deepagents/issues/6248)) ([a273ad6](https://github.com/shantanusharma/deepagents/commit/a273ad6c6a595c3aff915b744750711b50d544e3))
* **talon:** opt-in sandboxed execution via `DEEPAGENTS_TALON_SANDBOX` ([#6574](https://github.com/shantanusharma/deepagents/issues/6574)) ([b5f22b0](https://github.com/shantanusharma/deepagents/commit/b5f22b01aff7cfe328d632de086c31247c2b1081))
* **talon:** persist LangGraph checkpoints ([#6088](https://github.com/shantanusharma/deepagents/issues/6088)) ([337416a](https://github.com/shantanusharma/deepagents/commit/337416a85800818a5660afe8cfaedca16f8ac085))
* **talon:** pin skills to scheduled jobs ([#6906](https://github.com/shantanusharma/deepagents/issues/6906)) ([a2b287d](https://github.com/shantanusharma/deepagents/commit/a2b287d36006f0369dc1e7a8a4374b7c3d7cb8dc))
* **talon:** register chat commands as Discord slash commands ([#6303](https://github.com/shantanusharma/deepagents/issues/6303)) ([f36b641](https://github.com/shantanusharma/deepagents/commit/f36b641ce3e1f44dbd47835d6dc9f5bb1c82324a))
* **talon:** reload MCP configuration without restarting ([#6084](https://github.com/shantanusharma/deepagents/issues/6084)) ([1ac5386](https://github.com/shantanusharma/deepagents/commit/1ac5386790ad2a069923161393410ef49a39a2b0))
* **talon:** reload skills when skill files change ([#6904](https://github.com/shantanusharma/deepagents/issues/6904)) ([bfd09fb](https://github.com/shantanusharma/deepagents/commit/bfd09fb46e52e436fc1727d743cff915823a4093))
* **talon:** reload subagent configuration on demand ([#6099](https://github.com/shantanusharma/deepagents/issues/6099)) ([bf78360](https://github.com/shantanusharma/deepagents/commit/bf78360c87725a3af546e97d03915fb64ecf13c0))
* **talon:** run a scheduled job's subagents inline ([#6425](https://github.com/shantanusharma/deepagents/issues/6425)) ([c3a041e](https://github.com/shantanusharma/deepagents/commit/c3a041e3d8f593e4e4c9bfc273d52264ceff165b))
* **talon:** run command hooks in local subagents ([#7381](https://github.com/shantanusharma/deepagents/issues/7381)) ([f8a6a7f](https://github.com/shantanusharma/deepagents/commit/f8a6a7fdd7241dea0c40fb31d30cd3c4c98f95fb))
* **talon:** run expendable subagents in the background ([#6098](https://github.com/shantanusharma/deepagents/issues/6098)) ([c7a4841](https://github.com/shantanusharma/deepagents/commit/c7a48414e90456bc6a453a3cbb60cc787221fc74))
* **talon:** send Slack mention pairing codes in DMs ([#6584](https://github.com/shantanusharma/deepagents/issues/6584)) ([a31b310](https://github.com/shantanusharma/deepagents/commit/a31b31009b3f7fad90cc567cd794def20e280bd3))
* **talon:** share public Discord thread history by guild channel ([#6606](https://github.com/shantanusharma/deepagents/issues/6606)) ([936a37e](https://github.com/shantanusharma/deepagents/commit/936a37ef7b85a5ea3a2dca989e3e3a218fb96700))
* **talon:** ship defensive research defaults ([#6131](https://github.com/shantanusharma/deepagents/issues/6131)) ([1a835d2](https://github.com/shantanusharma/deepagents/commit/1a835d216260d3b140af528d42fbb75eca26f818))
* **talon:** store inbound media as backend blobs ([#6905](https://github.com/shantanusharma/deepagents/issues/6905)) ([a96a3b6](https://github.com/shantanusharma/deepagents/commit/a96a3b63b206feef23af9237a1a64a93d1f52aef))
* **talon:** support dcode-style subagents in fork mode ([#6085](https://github.com/shantanusharma/deepagents/issues/6085)) ([91bcf63](https://github.com/shantanusharma/deepagents/commit/91bcf63805c656fe0399aeaf9d25c0ae7f7a2cf2))
* **talon:** support DeepSeek reasoning levels ([#7439](https://github.com/shantanusharma/deepagents/issues/7439)) ([3a217ce](https://github.com/shantanusharma/deepagents/commit/3a217cec7183b601f2b33e0144e09bb50ad44f01))
* **talon:** support explicit public MCP OAuth clients ([#6670](https://github.com/shantanusharma/deepagents/issues/6670)) ([7475059](https://github.com/shantanusharma/deepagents/commit/7475059432e9eda77b8b9a5bc7178f5f3a532bd9))
* **talon:** support fresh subagents and per-task tool selection ([#6129](https://github.com/shantanusharma/deepagents/issues/6129)) ([276a385](https://github.com/shantanusharma/deepagents/commit/276a385d6c49ef63f0cae107e5a1afa591191e03))
* **talon:** support GitHub MCP device authentication ([#6079](https://github.com/shantanusharma/deepagents/issues/6079)) ([d91ec7d](https://github.com/shantanusharma/deepagents/commit/d91ec7d0a7b8d0a703fa16b5ee4237c84d10526c))
* **talon:** support sender pairing on Slack ([#6582](https://github.com/shantanusharma/deepagents/issues/6582)) ([90cd463](https://github.com/shantanusharma/deepagents/commit/90cd463830418f79dc994f7b84c01f6256409435))
* **talon:** support skill-scoped MCP tools ([#7280](https://github.com/shantanusharma/deepagents/issues/7280)) ([2a5b748](https://github.com/shantanusharma/deepagents/commit/2a5b748dcc1e76c3eb5cd1735351e230788f00d7))
* **talon:** support Slack MCP OAuth login ([#6078](https://github.com/shantanusharma/deepagents/issues/6078)) ([f8b137e](https://github.com/shantanusharma/deepagents/commit/f8b137ef22bf81f8178fe490f6dad7621f161a16))


### Bug Fixes

* **talon:** accept any Slack slash command name ([#6589](https://github.com/shantanusharma/deepagents/issues/6589)) ([31ae532](https://github.com/shantanusharma/deepagents/commit/31ae53291c23854912d3237c20e108445c6b6f11))
* **talon:** accept labeled Slack OAuth callbacks ([#6593](https://github.com/shantanusharma/deepagents/issues/6593)) ([0359577](https://github.com/shantanusharma/deepagents/commit/035957706fc34545ae1e7485aa03f8415694cd71))
* **talon:** align progress tool guidance with verbosity ([#7041](https://github.com/shantanusharma/deepagents/issues/7041)) ([0089e63](https://github.com/shantanusharma/deepagents/commit/0089e635dce525055272883b53bc222f385beac1))
* **talon:** allow operator pairing approvals in shared chats ([#6710](https://github.com/shantanusharma/deepagents/issues/6710)) ([b00affd](https://github.com/shantanusharma/deepagents/commit/b00affd643cac9789a2fc4b47bf74056eefdc423))
* **talon:** avoid duplicate subagent result delivery ([#7619](https://github.com/shantanusharma/deepagents/issues/7619)) ([dbb8ab1](https://github.com/shantanusharma/deepagents/commit/dbb8ab19b9498463973a5ff039f88fbee30ddd9a))
* **talon:** avoid retranscribing voice on background follow-ups ([#6682](https://github.com/shantanusharma/deepagents/issues/6682)) ([1614a38](https://github.com/shantanusharma/deepagents/commit/1614a389ea48c12182c167d3ecf69224a69d4043))
* **talon:** avoid stale WhatsApp Web cache on startup ([#7631](https://github.com/shantanusharma/deepagents/issues/7631)) ([a21f53a](https://github.com/shantanusharma/deepagents/commit/a21f53a007f770cfd5c09e6b44682eb25ad8462a))
* **talon:** backfill missing research subagent defaults ([#6135](https://github.com/shantanusharma/deepagents/issues/6135)) ([54cf354](https://github.com/shantanusharma/deepagents/commit/54cf354d04d094eaf77c17ed239fdd235e4ebc83))
* **talon:** block precompiled delegation with enabled approvals ([#7604](https://github.com/shantanusharma/deepagents/issues/7604)) ([34b802d](https://github.com/shantanusharma/deepagents/commit/34b802d29b044cd9b3fbf7dcd50d025a2e9a4a98))
* **talon:** bound archive scans, query embeddings, and deletion markers ([#6162](https://github.com/shantanusharma/deepagents/issues/6162)) ([79c23e6](https://github.com/shantanusharma/deepagents/commit/79c23e669bf81cddf16e4ab1582ccc9b26d8bea7))
* **talon:** bound the vector rebuild, break the import cycle, pin postgres ([#6165](https://github.com/shantanusharma/deepagents/issues/6165)) ([8462c24](https://github.com/shantanusharma/deepagents/commit/8462c24524541f49a3eb53037580110586973c8c))
* **talon:** close a url swap past the MCP auto-approve guard ([#6173](https://github.com/shantanusharma/deepagents/issues/6173)) ([d886742](https://github.com/shantanusharma/deepagents/commit/d8867426af3ab83c31d64a11e5b84a21ce86a43d))
* **talon:** correct history embedding token budget and prompt defaults ([#6132](https://github.com/shantanusharma/deepagents/issues/6132)) ([caabca2](https://github.com/shantanusharma/deepagents/commit/caabca2b479ec731a81fa42e4c53c9471895fd7b))
* **talon:** declare the packages talon imports directly ([#6436](https://github.com/shantanusharma/deepagents/issues/6436)) ([c63eba4](https://github.com/shantanusharma/deepagents/commit/c63eba426b28f1d1685e40767f087dcc3f34334c))
* **talon:** default workspace to current directory ([#4099](https://github.com/shantanusharma/deepagents/issues/4099)) ([5e337ae](https://github.com/shantanusharma/deepagents/commit/5e337ae50a76bc174b752be187e62698a389cbe6))
* **talon:** delegate lengthy investigations early ([#7621](https://github.com/shantanusharma/deepagents/issues/7621)) ([ab8db29](https://github.com/shantanusharma/deepagents/commit/ab8db292c7b15efee53346a1e8907f60e1c0d34e))
* **talon:** deliver background subagents launched by a scheduled job ([#6228](https://github.com/shantanusharma/deepagents/issues/6228)) ([b6dc5c5](https://github.com/shantanusharma/deepagents/commit/b6dc5c5a8c6c1124f8e243868a83b9af188b08c7))
* **talon:** deliver narration before running tools ([#6681](https://github.com/shantanusharma/deepagents/issues/6681)) ([a8bf07b](https://github.com/shantanusharma/deepagents/commit/a8bf07bf604524e98530034027414254ae215f78))
* **talon:** download only Transformers files for local speech models ([#7597](https://github.com/shantanusharma/deepagents/issues/7597)) ([cb1635d](https://github.com/shantanusharma/deepagents/commit/cb1635d027f1afc1cba780590e094aa2817e5c34))
* **talon:** drop extract-zip from the WhatsApp bridge dependency tree ([#5924](https://github.com/shantanusharma/deepagents/issues/5924)) ([7301d01](https://github.com/shantanusharma/deepagents/commit/7301d01e483d0b76745c725134ec09db82f38856))
* **talon:** enumerate selectable gateway models ([#6595](https://github.com/shantanusharma/deepagents/issues/6595)) ([5b29445](https://github.com/shantanusharma/deepagents/commit/5b29445dd387bb9e8b8c3fed8f7382a91a990e06))
* **talon:** erase hook transcripts with conversation history ([#7382](https://github.com/shantanusharma/deepagents/issues/7382)) ([701c986](https://github.com/shantanusharma/deepagents/commit/701c986640635807ee19b5b0adce63ea9c8f888d))
* **talon:** exclude OAuth callbacks from Slack thread context ([#6687](https://github.com/shantanusharma/deepagents/issues/6687)) ([f566a09](https://github.com/shantanusharma/deepagents/commit/f566a09da6141935ee564caa01c921da08f34036))
* **talon:** expose channel documents without inlining contents ([#7049](https://github.com/shantanusharma/deepagents/issues/7049)) ([fc21074](https://github.com/shantanusharma/deepagents/commit/fc210741b2da06c93409100e0c92be3391db70a5))
* **talon:** extract plain text from subagent results ([#7645](https://github.com/shantanusharma/deepagents/issues/7645)) ([215951c](https://github.com/shantanusharma/deepagents/commit/215951c556a4a493dda77c12e9e2fe959fc375fc))
* **talon:** extract text from tool-attached task results ([#7652](https://github.com/shantanusharma/deepagents/issues/7652)) ([2429841](https://github.com/shantanusharma/deepagents/commit/24298415103c809e31ae6d0291632062ed44bdb5))
* **talon:** fix local voice transcription and embedding retries ([#6255](https://github.com/shantanusharma/deepagents/issues/6255)) ([a97ba32](https://github.com/shantanusharma/deepagents/commit/a97ba320fa797e9546efe3486ce703e8efd30fb4))
* **talon:** harden the MCP OAuth device flow and credential paths ([#6170](https://github.com/shantanusharma/deepagents/issues/6170)) ([e6c5829](https://github.com/shantanusharma/deepagents/commit/e6c58294d6792bcf433eb5f38fec1b5be70cc065))
* **talon:** identify MCP OAuth requests with a user agent ([#6981](https://github.com/shantanusharma/deepagents/issues/6981)) ([7f474e1](https://github.com/shantanusharma/deepagents/commit/7f474e1527dd8b014d53ebb6aa66321a54798ced))
* **talon:** identify user interruptions in traces ([#7623](https://github.com/shantanusharma/deepagents/issues/7623)) ([ca275e6](https://github.com/shantanusharma/deepagents/commit/ca275e6c8c7ae260ec1191899a72c270da710956))
* **talon:** improve channel reconnect resilience ([#6040](https://github.com/shantanusharma/deepagents/issues/6040)) ([54fe91f](https://github.com/shantanusharma/deepagents/commit/54fe91fd3745e285899961bfe74380c837674164))
* **talon:** improve subagent research handoffs ([#6674](https://github.com/shantanusharma/deepagents/issues/6674)) ([ab57eab](https://github.com/shantanusharma/deepagents/commit/ab57eab7e51121a2677d0c5b5aa396487ed2b9ee))
* **talon:** include authorized bot replies in Slack thread history ([#6742](https://github.com/shantanusharma/deepagents/issues/6742)) ([3a8a983](https://github.com/shantanusharma/deepagents/commit/3a8a983e379a4bcccace15dcbc0914bd3cea753c))
* **talon:** include preceding Slack replies on thread mentions ([#6634](https://github.com/shantanusharma/deepagents/issues/6634)) ([0e5f6f8](https://github.com/shantanusharma/deepagents/commit/0e5f6f893b91bed16837f2cd7966049c7cafc650))
* **talon:** index only visible conversation text ([#6358](https://github.com/shantanusharma/deepagents/issues/6358)) ([f6850e9](https://github.com/shantanusharma/deepagents/commit/f6850e9d25854b5679010c08f02adae99e6b8a2c))
* **talon:** keep legacy Slack thread archives writable ([#6679](https://github.com/shantanusharma/deepagents/issues/6679)) ([166b0e0](https://github.com/shantanusharma/deepagents/commit/166b0e0ce1e424bb24f49ee5c48155458b4b1dce))
* **talon:** keep results a discarded turn never reported ([#6231](https://github.com/shantanusharma/deepagents/issues/6231)) ([481773c](https://github.com/shantanusharma/deepagents/commit/481773caed336c86034e1c72b4988e7e93968610))
* **talon:** keep the cron ticker alive through a failed tick ([#6087](https://github.com/shantanusharma/deepagents/issues/6087)) ([4c062ec](https://github.com/shantanusharma/deepagents/commit/4c062ec76e2cf19abb3ac8a78b1bf68cf7ece3cd))
* **talon:** label bot history as participant messages ([#6743](https://github.com/shantanusharma/deepagents/issues/6743)) ([e156592](https://github.com/shantanusharma/deepagents/commit/e156592ac2dcb667193c885d1529cef83311d6f7))
* **talon:** let scheduled jobs read their origin chat's history ([#6583](https://github.com/shantanusharma/deepagents/issues/6583)) ([e70cf09](https://github.com/shantanusharma/deepagents/commit/e70cf09267d93ce54f381d77fb577a76adac6300))
* **talon:** make background subagents and host start/stop recoverable ([#6166](https://github.com/shantanusharma/deepagents/issues/6166)) ([d4c41b0](https://github.com/shantanusharma/deepagents/commit/d4c41b048132eb27e2337b60b21463403b615390))
* **talon:** make MCP configuration updates bounded and non-destructive ([#6171](https://github.com/shantanusharma/deepagents/issues/6171)) ([f995931](https://github.com/shantanusharma/deepagents/commit/f9959311bfeb788191f971fe32552b01adbac199))
* **talon:** make MCP login failures actionable ([#7646](https://github.com/shantanusharma/deepagents/issues/7646)) ([ee5071a](https://github.com/shantanusharma/deepagents/commit/ee5071a3ba8e23ec4dc2d4c91eb2cf1d0612d707))
* **talon:** make remote embedding settings explicit and search non-blocking ([#6133](https://github.com/shantanusharma/deepagents/issues/6133)) ([3698f10](https://github.com/shantanusharma/deepagents/commit/3698f10bc46ef6ac6d7b30c1fcdc499a8ac08b28))
* **talon:** make subagent orchestration state what it enforces ([#6167](https://github.com/shantanusharma/deepagents/issues/6167)) ([05620cc](https://github.com/shantanusharma/deepagents/commit/05620cc72bfa7b81ce41064641cfa5808cb7c74a))
* **talon:** materialize agents under home ([f2b26a8](https://github.com/shantanusharma/deepagents/commit/f2b26a8915fb70c26d32af6e8240442e5e6118e6))
* **talon:** migrate MCP discovery to `discover_mcp_config_sources` ([#5803](https://github.com/shantanusharma/deepagents/issues/5803)) ([5cdd977](https://github.com/shantanusharma/deepagents/commit/5cdd97730708b0480cb7d32792717dcdcd02f4ea))
* **talon:** normalize OAuth TLS server hostname ([#6102](https://github.com/shantanusharma/deepagents/issues/6102)) ([34005a4](https://github.com/shantanusharma/deepagents/commit/34005a4efab0ab2ee2466fec413844ddae0b27c1))
* **talon:** omit empty optional MCP arguments ([#6077](https://github.com/shantanusharma/deepagents/issues/6077)) ([632f2c9](https://github.com/shantanusharma/deepagents/commit/632f2c941b877eff70407606b58e393212448a26))
* **talon:** parse comma-separated skills and memory paths ([#7625](https://github.com/shantanusharma/deepagents/issues/7625)) ([1cf989a](https://github.com/shantanusharma/deepagents/commit/1cf989a30166ae56adc75e9ed60cca94789c9f9b))
* **talon:** persist history vector deduplication ([#6357](https://github.com/shantanusharma/deepagents/issues/6357)) ([b3d4967](https://github.com/shantanusharma/deepagents/commit/b3d4967bdcda5b42e976b3e97c357deea82d63ac))
* **talon:** persist local model downloads ([#6137](https://github.com/shantanusharma/deepagents/issues/6137)) ([fc91199](https://github.com/shantanusharma/deepagents/commit/fc91199a44b99990cca49341169aea858da222fc))
* **talon:** persist model selection across conversations ([#6603](https://github.com/shantanusharma/deepagents/issues/6603)) ([156a682](https://github.com/shantanusharma/deepagents/commit/156a6824e53c3f483dca75d08e0d084c0788b3a3))
* **talon:** persist OAuth token expiry ([#6090](https://github.com/shantanusharma/deepagents/issues/6090)) ([a02d2df](https://github.com/shantanusharma/deepagents/commit/a02d2df874332784530082261f801512bbf62dee))
* **talon:** preserve gateway provider reasoning controls ([#7047](https://github.com/shantanusharma/deepagents/issues/7047)) ([1e3bbef](https://github.com/shantanusharma/deepagents/commit/1e3bbef613ab916161115fe47b29463a905147b0))
* **talon:** preserve MIME types when downloading WhatsApp voice messages ([#6590](https://github.com/shantanusharma/deepagents/issues/6590)) ([e739e4d](https://github.com/shantanusharma/deepagents/commit/e739e4d66c367f91b430062ee841055ac311c57c))
* **talon:** preserve optional MCP arguments on Responses ([#7530](https://github.com/shantanusharma/deepagents/issues/7530)) ([f161e20](https://github.com/shantanusharma/deepagents/commit/f161e20568619f9ff61d483ea0fdf00e63c45215))
* **talon:** preserve other participants in Slack thread context ([#6862](https://github.com/shantanusharma/deepagents/issues/6862)) ([bfd9f22](https://github.com/shantanusharma/deepagents/commit/bfd9f22fc558d5e90c809cf3beccb64aa69f3556))
* **talon:** preserve SDK refusal reporting for tool-attached tasks ([#7760](https://github.com/shantanusharma/deepagents/issues/7760)) ([33d5416](https://github.com/shantanusharma/deepagents/commit/33d541623fd0b9a5e7b4bc6db28d2c7179f5c858))
* **talon:** preserve WhatsApp approval loops and handle reactions ([#6104](https://github.com/shantanusharma/deepagents/issues/6104)) ([eca6203](https://github.com/shantanusharma/deepagents/commit/eca6203338a4d7927456ff1ec70b3a29f01e9799))
* **talon:** preserve WhatsApp quoted message context ([#6025](https://github.com/shantanusharma/deepagents/issues/6025)) ([03436b3](https://github.com/shantanusharma/deepagents/commit/03436b369c0324498602fe6b7918cf36f3629d76))
* **talon:** prevent shell workarounds for unavailable integrations ([#7622](https://github.com/shantanusharma/deepagents/issues/7622)) ([d315d8e](https://github.com/shantanusharma/deepagents/commit/d315d8e12dd4f2c250a759a38825f1ea1c9484d6))
* **talon:** raise dependency minimums ([#6952](https://github.com/shantanusharma/deepagents/issues/6952)) ([3c1aac9](https://github.com/shantanusharma/deepagents/commit/3c1aac97c96755530eefaf8b0d1d88fbf43c4566))
* **talon:** reject symlinked hook configuration ([#7603](https://github.com/shantanusharma/deepagents/issues/7603)) ([7725f7b](https://github.com/shantanusharma/deepagents/commit/7725f7b650b001090871dddb8e8454eea004d021))
* **talon:** reject tool approvals without a sender ([#7605](https://github.com/shantanusharma/deepagents/issues/7605)) ([324ee54](https://github.com/shantanusharma/deepagents/commit/324ee54956dfec2ba85164a17fdece70bcdfdfb1))
* **talon:** report Discord gateway failures after startup ([#6113](https://github.com/shantanusharma/deepagents/issues/6113)) ([94e4520](https://github.com/shantanusharma/deepagents/commit/94e452077cf2650b0a410da7fa1e23b28d5dd8e1))
* **talon:** report MCP protocol errors to the model ([#6239](https://github.com/shantanusharma/deepagents/issues/6239)) ([edd0bcf](https://github.com/shantanusharma/deepagents/commit/edd0bcfc61dc16eabea0b3a59aa84569e3b240dc))
* **talon:** restore WhatsApp bridge compatibility ([#5999](https://github.com/shantanusharma/deepagents/issues/5999)) ([568b398](https://github.com/shantanusharma/deepagents/commit/568b398df9b9f4f3464b4107c0ef9001f530d728))
* **talon:** restrict WhatsApp replies to self-chat ([#6010](https://github.com/shantanusharma/deepagents/issues/6010)) ([40359ec](https://github.com/shantanusharma/deepagents/commit/40359ec683eaff3a67b39d3f6b3003e70db9ec4d))
* **talon:** resume history search past the scan budget ([#6740](https://github.com/shantanusharma/deepagents/issues/6740)) ([11600fb](https://github.com/shantanusharma/deepagents/commit/11600fb7ab9a3f081c1f0c8640f1a864c1c7d71b))
* **talon:** retry provider overload and connection errors ([#6580](https://github.com/shantanusharma/deepagents/issues/6580)) ([b3f1a39](https://github.com/shantanusharma/deepagents/commit/b3f1a3919fe39853ee29acee1fb49b077507428f))
* **talon:** retry statusless provider overload errors ([#6304](https://github.com/shantanusharma/deepagents/issues/6304)) ([f8acbd0](https://github.com/shantanusharma/deepagents/commit/f8acbd0ae24278d35aeb1fa014056084a58f70d2))
* **talon:** secure OAuth discovery and restart token refresh ([#6100](https://github.com/shantanusharma/deepagents/issues/6100)) ([43c2994](https://github.com/shantanusharma/deepagents/commit/43c299460042b8ae44b2162fba24be456088bdb9))
* **talon:** serialize cron store mutations ([#6688](https://github.com/shantanusharma/deepagents/issues/6688)) ([67b0bef](https://github.com/shantanusharma/deepagents/commit/67b0bef01082bf94e8641bf4e1a94a71b3f6ebc9))
* **talon:** share cron jobs across channel threads ([#6707](https://github.com/shantanusharma/deepagents/issues/6707)) ([6bae886](https://github.com/shantanusharma/deepagents/commit/6bae88610c035b923f538beb99c1dc70850225e1))
* **talon:** share one optional-driver loader and close provider clients ([#6164](https://github.com/shantanusharma/deepagents/issues/6164)) ([02cea21](https://github.com/shantanusharma/deepagents/commit/02cea210d7f3e5bc2bf89453e8a6e4af59031f59))
* **talon:** share Slack channel conversation archives across threads ([#6665](https://github.com/shantanusharma/deepagents/issues/6665)) ([6bf7665](https://github.com/shantanusharma/deepagents/commit/6bf76658f88af8328d9a9625d2c6444e01896248))
* **talon:** start each cron run on a fresh thread ([#6936](https://github.com/shantanusharma/deepagents/issues/6936)) ([7a27b8c](https://github.com/shantanusharma/deepagents/commit/7a27b8c3c945bdae2932769a25969202800c8a37))
* **talon:** stop HistoryEmbeddings defaulting to Qwen's query prefix ([#6134](https://github.com/shantanusharma/deepagents/issues/6134)) ([933d863](https://github.com/shantanusharma/deepagents/commit/933d86350f0d0ffa54359d4f00510e52ccdc2b85))
* **talon:** stop losing MCP refresh tokens on a refresh response ([#6172](https://github.com/shantanusharma/deepagents/issues/6172)) ([7dc07cb](https://github.com/shantanusharma/deepagents/commit/7dc07cbb60f144e2b7fc266ee452b06c8b8dd10c))
* **talon:** stop one conversation from stalling or outliving the rest ([#6168](https://github.com/shantanusharma/deepagents/issues/6168)) ([134ffc7](https://github.com/shantanusharma/deepagents/commit/134ffc7bb4eba504ee90aaae3a70df87c6ea3217))
* **talon:** stop swallowing a turn's cancel during typing cleanup ([#6594](https://github.com/shantanusharma/deepagents/issues/6594)) ([eff90de](https://github.com/shantanusharma/deepagents/commit/eff90dec8c6bfe9636da064c7c9310b660d89b32))
* **talon:** store offloaded artifacts in the assistant home ([#6530](https://github.com/shantanusharma/deepagents/issues/6530)) ([74d768b](https://github.com/shantanusharma/deepagents/commit/74d768bd45dd4eca977dc320ebfe5838f1691682))
* **talon:** summarize fresh subagent context ([#7676](https://github.com/shantanusharma/deepagents/issues/7676)) ([7c8a85e](https://github.com/shantanusharma/deepagents/commit/7c8a85e27026b234ce9223933d6ea29767088f64))
* **talon:** summarize stored values in MCP approval prompts ([#7812](https://github.com/shantanusharma/deepagents/issues/7812)) ([16966e7](https://github.com/shantanusharma/deepagents/commit/16966e76e433465fcd8feb3a01534f31095c52a3))
* **talon:** suppress unchanged `list_subagents` polls ([#7677](https://github.com/shantanusharma/deepagents/issues/7677)) ([c158f2a](https://github.com/shantanusharma/deepagents/commit/c158f2ad5b49459b1bdc42efd5f1252f54a51005))
* **talon:** surface indexing failures and bound the indexing worker ([#6163](https://github.com/shantanusharma/deepagents/issues/6163)) ([03653d6](https://github.com/shantanusharma/deepagents/commit/03653d6d95ceb0b1b6739998fd9475e304489d12))
* **talon:** transcribe inbound audio attachments ([#6680](https://github.com/shantanusharma/deepagents/issues/6680)) ([184f547](https://github.com/shantanusharma/deepagents/commit/184f547e12f57df358eb49536a02cbe672f95888))
* **talon:** treat trailing [SILENT] as a suppression marker ([#6110](https://github.com/shantanusharma/deepagents/issues/6110)) ([92576da](https://github.com/shantanusharma/deepagents/commit/92576daf1cfaadfc811445b29be9457a78eb4e5e))
* **talon:** unwind the channel that fails mid-start, and keep teardown safe ([#6169](https://github.com/shantanusharma/deepagents/issues/6169)) ([5406820](https://github.com/shantanusharma/deepagents/commit/5406820ec1c00ce521b0f54bb786c511da092f01))
* **talon:** validate archive pagination arguments ([#6442](https://github.com/shantanusharma/deepagents/issues/6442)) ([f84d963](https://github.com/shantanusharma/deepagents/commit/f84d96358a111872fba3f9b69c5b08ad1565c083))


### Performance Improvements

* **talon:** reduce archive replay transactions ([#6320](https://github.com/shantanusharma/deepagents/issues/6320)) ([89bd48f](https://github.com/shantanusharma/deepagents/commit/89bd48f7d531c9affafa3f0dc096083cbc5969dd))
* **talon:** store cron jobs in a structured, versioned format ([#6086](https://github.com/shantanusharma/deepagents/issues/6086)) ([4e5f935](https://github.com/shantanusharma/deepagents/commit/4e5f9350e4d77b8bf19e472e8414662d3fa59dc0))

## [0.1.1](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.1.0...deepagents-talon==0.1.1) (2026-11-19)

### Features

- Ask structured clarifying questions in chat. ([#7607](https://github.com/langchain-ai/deepagents/pull/7607))
- Inspect and guide background subagents. ([#7609](https://github.com/langchain-ai/deepagents/pull/7609))
- Enable or disable configured MCP servers, and use skill-scoped MCP tools. ([#7608](https://github.com/langchain-ai/deepagents/pull/7608), [#7280](https://github.com/langchain-ai/deepagents/pull/7280))
- Add command hooks for the main agent and local subagents. ([#7380](https://github.com/langchain-ai/deepagents/pull/7380), [#7381](https://github.com/langchain-ai/deepagents/pull/7381))
- Filter conversation history by time window and role. ([#7712](https://github.com/langchain-ai/deepagents/pull/7712))
- Support DeepSeek reasoning levels. ([#7439](https://github.com/langchain-ai/deepagents/pull/7439))
- Add a `media-cpu` extra with CPU-only PyTorch on Linux. ([#7596](https://github.com/langchain-ai/deepagents/pull/7596))

### Bug Fixes

- Block precompiled delegation when approvals are enabled, and reject tool approvals without a sender. ([#7604](https://github.com/langchain-ai/deepagents/pull/7604), [#7605](https://github.com/langchain-ai/deepagents/pull/7605))
- Reject symlinked hook configuration. ([#7603](https://github.com/langchain-ai/deepagents/pull/7603))
- Erase hook transcripts when deleting conversation history. ([#7382](https://github.com/langchain-ai/deepagents/pull/7382))
- Prevent shell workarounds for unavailable integrations. ([#7622](https://github.com/langchain-ai/deepagents/pull/7622))
- Avoid duplicate subagent result delivery, and correctly extract text from subagent and tool-attached task results. ([#7619](https://github.com/langchain-ai/deepagents/pull/7619), [#7645](https://github.com/langchain-ai/deepagents/pull/7645), [#7652](https://github.com/langchain-ai/deepagents/pull/7652))
- Preserve SDK refusal reporting for tool-attached tasks. ([#7760](https://github.com/langchain-ai/deepagents/pull/7760))
- Avoid stale WhatsApp Web cache on startup. ([#7631](https://github.com/langchain-ai/deepagents/pull/7631))
- Preserve gateway provider reasoning controls. ([#7047](https://github.com/langchain-ai/deepagents/pull/7047))
- Preserve optional MCP arguments when using the Responses API. ([#7530](https://github.com/langchain-ai/deepagents/pull/7530))
- Provide actionable MCP login errors and summarize stored values in MCP approval prompts. ([#7646](https://github.com/langchain-ai/deepagents/pull/7646), [#7812](https://github.com/langchain-ai/deepagents/pull/7812))
- Correctly parse comma-separated skills and memory paths. ([#7625](https://github.com/langchain-ai/deepagents/pull/7625))
- Delegate lengthy investigations earlier and summarize fresh subagent context. ([#7621](https://github.com/langchain-ai/deepagents/pull/7621), [#7676](https://github.com/langchain-ai/deepagents/pull/7676))
- Download only Transformers files for local speech models. ([#7597](https://github.com/langchain-ai/deepagents/pull/7597))
- Suppress unchanged `list_subagents` polls. ([#7677](https://github.com/langchain-ai/deepagents/pull/7677))
- Identify user interruptions in traces. ([#7623](https://github.com/langchain-ai/deepagents/pull/7623))

## [0.1.0](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.9...deepagents-talon==0.1.0) (2026-10-22)

### ⚠ BREAKING CHANGES

- `deepagents-talon` now requires Python 3.14 (`>=3.14,<3.15`). ([#7052](https://github.com/langchain-ai/deepagents/pull/7052))

### Features

- Added `/effort` controls for reasoning. ([#7043](https://github.com/langchain-ai/deepagents/pull/7043))
- Added the NVIDIA OpenShell sandbox provider and an `openshell` extra for Talon. ([#6999](https://github.com/langchain-ai/deepagents/pull/6999), [#7000](https://github.com/langchain-ai/deepagents/pull/7000))
- Added independent breakout tasks for Slack and Discord. ([#6932](https://github.com/langchain-ai/deepagents/pull/6932))
- Discord guild mentions now receive replies in threads, as they do in Slack. ([#7012](https://github.com/langchain-ai/deepagents/pull/7012))
- Added configurable verbosity for interim progress updates. ([#7037](https://github.com/langchain-ai/deepagents/pull/7037))
- Made background subagent capacity and checkpoint backends configurable. ([#7048](https://github.com/langchain-ai/deepagents/pull/7048), [#6727](https://github.com/langchain-ai/deepagents/pull/6727))
- Skills can now be pinned to scheduled jobs and reload when their files change. ([#6906](https://github.com/langchain-ai/deepagents/pull/6906), [#6904](https://github.com/langchain-ai/deepagents/pull/6904))
- Inbound media is now stored as backend blobs. ([#6905](https://github.com/langchain-ai/deepagents/pull/6905))

### Bug Fixes

- Slack thread context now preserves other participants, includes authorized bot replies, and labels bot history as participant messages. ([#6862](https://github.com/langchain-ai/deepagents/pull/6862), [#6742](https://github.com/langchain-ai/deepagents/pull/6742), [#6743](https://github.com/langchain-ai/deepagents/pull/6743))
- Scheduled jobs are now shared across channel threads, while each run starts on a fresh thread. ([#6707](https://github.com/langchain-ai/deepagents/pull/6707), [#6936](https://github.com/langchain-ai/deepagents/pull/6936))
- Operator pairing approvals now work in shared chats. ([#6710](https://github.com/langchain-ai/deepagents/pull/6710))
- History search now resumes past the scan budget. ([#6740](https://github.com/langchain-ai/deepagents/pull/6740))
- Channel documents are now exposed without inlining their contents. ([#7049](https://github.com/langchain-ai/deepagents/pull/7049))
- Progress-tool guidance now reflects the configured verbosity. ([#7041](https://github.com/langchain-ai/deepagents/pull/7041))
- MCP OAuth requests now include a user agent. ([#6981](https://github.com/langchain-ai/deepagents/pull/6981))
- Raised minimum dependency versions. ([#6952](https://github.com/langchain-ai/deepagents/pull/6952))

## [0.0.9](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.8...deepagents-talon==0.0.9) (2026-10-01)

### Features

- Add a Slack channel adapter, with support for outbound user mentions. ([#6575](https://github.com/langchain-ai/deepagents/pull/6575), [#6602](https://github.com/langchain-ai/deepagents/pull/6602))
- Add sender pairing for DM access and Slack, including DM delivery of pairing codes for Slack mentions. Paired senders are admitted in every chat. ([#6579](https://github.com/langchain-ai/deepagents/pull/6579), [#6582](https://github.com/langchain-ai/deepagents/pull/6582), [#6584](https://github.com/langchain-ai/deepagents/pull/6584), [#6592](https://github.com/langchain-ai/deepagents/pull/6592))
- Add `/model` for per-chat model switching. ([#6577](https://github.com/langchain-ai/deepagents/pull/6577))
- Add cron expressions and `until` expiry for scheduled jobs, run their subagents inline, and deliver results from thread-based jobs to the channel by default. ([#6526](https://github.com/langchain-ai/deepagents/pull/6526), [#6425](https://github.com/langchain-ai/deepagents/pull/6425), [#6632](https://github.com/langchain-ai/deepagents/pull/6632))
- Add opt-in sandboxed execution via `DEEPAGENTS_TALON_SANDBOX`. ([#6574](https://github.com/langchain-ai/deepagents/pull/6574))
- Register chat commands as Discord slash commands and share public thread history by guild channel. ([#6303](https://github.com/langchain-ai/deepagents/pull/6303), [#6606](https://github.com/langchain-ai/deepagents/pull/6606))
- Add approved, one-off `ask_for_help` consultations. ([#6605](https://github.com/langchain-ai/deepagents/pull/6605))
- Batch approvals for concurrent tool calls. ([#6435](https://github.com/langchain-ai/deepagents/pull/6435))
- Add a `/context-doctor` command. ([#6557](https://github.com/langchain-ai/deepagents/pull/6557))
- Add a general-purpose safety preflight skill. ([#6587](https://github.com/langchain-ai/deepagents/pull/6587))
- Support explicitly configured public MCP OAuth clients. ([#6670](https://github.com/langchain-ai/deepagents/pull/6670))

### Bug Fixes

- Retry provider overload and connection errors, including overload errors without a status code. ([#6580](https://github.com/langchain-ai/deepagents/pull/6580), [#6304](https://github.com/langchain-ai/deepagents/pull/6304))
- Transcribe inbound audio attachments, preserve MIME types for downloaded WhatsApp voice messages, and avoid retranscribing voice on background follow-ups. ([#6680](https://github.com/langchain-ai/deepagents/pull/6680), [#6590](https://github.com/langchain-ai/deepagents/pull/6590), [#6682](https://github.com/langchain-ai/deepagents/pull/6682))
- List selectable gateway models and persist model selection across conversations. ([#6595](https://github.com/langchain-ai/deepagents/pull/6595), [#6603](https://github.com/langchain-ai/deepagents/pull/6603))
- Preserve Slack conversation context across threads, include preceding replies when mentioned in a thread, and keep legacy thread archives writable. ([#6665](https://github.com/langchain-ai/deepagents/pull/6665), [#6634](https://github.com/langchain-ai/deepagents/pull/6634), [#6679](https://github.com/langchain-ai/deepagents/pull/6679))
- Allow scheduled jobs to read their origin chat's history and serialize changes to the cron store. ([#6583](https://github.com/langchain-ai/deepagents/pull/6583), [#6688](https://github.com/langchain-ai/deepagents/pull/6688))
- Accept any Slack slash command name and labeled Slack OAuth callbacks, while excluding OAuth callbacks from thread context. ([#6589](https://github.com/langchain-ai/deepagents/pull/6589), [#6593](https://github.com/langchain-ai/deepagents/pull/6593), [#6687](https://github.com/langchain-ai/deepagents/pull/6687))
- Deliver narration before running tools and preserve turn cancellation during typing cleanup. ([#6681](https://github.com/langchain-ai/deepagents/pull/6681), [#6594](https://github.com/langchain-ai/deepagents/pull/6594))
- Index only visible conversation text and persist history-vector deduplication. ([#6358](https://github.com/langchain-ai/deepagents/pull/6358), [#6357](https://github.com/langchain-ai/deepagents/pull/6357))
- Improve subagent research handoffs. ([#6674](https://github.com/langchain-ai/deepagents/pull/6674))
- Store offloaded artifacts in the assistant home. ([#6530](https://github.com/langchain-ai/deepagents/pull/6530))
- Validate archive pagination arguments. ([#6442](https://github.com/langchain-ai/deepagents/pull/6442))
- Declare packages that Talon imports directly as dependencies. ([#6436](https://github.com/langchain-ai/deepagents/pull/6436))

### Performance Improvements

- Reduce transactions when replaying conversation archives. ([#6320](https://github.com/langchain-ai/deepagents/pull/6320))

## [0.0.8](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.7...deepagents-talon==0.0.8) (2026-09-11)

### Features

- Added `send_message` support for progress updates. ([#6264](https://github.com/langchain-ai/deepagents/pull/6264))
- Added targeted conversation deletion. ([#6235](https://github.com/langchain-ai/deepagents/pull/6235))
- Added support for managing tool approvals through `tools.json`. ([#6248](https://github.com/langchain-ai/deepagents/pull/6248))

### Bug Fixes

- Improved MCP reliability and safety by hardening OAuth device-flow and credential handling, preserving refresh tokens, making configuration updates bounded and non-destructive, reporting protocol errors to the model, and preventing URL swaps past the auto-approve guard. ([#6170](https://github.com/langchain-ai/deepagents/pull/6170), [#6172](https://github.com/langchain-ai/deepagents/pull/6172), [#6171](https://github.com/langchain-ai/deepagents/pull/6171), [#6239](https://github.com/langchain-ai/deepagents/pull/6239), [#6173](https://github.com/langchain-ai/deepagents/pull/6173))
- Improved background subagent and conversation reliability, including recoverable start/stop behavior, scheduled-job delivery, clearer orchestration enforcement, preventing one conversation from stalling or outliving the rest, and suppressing results from discarded turns. ([#6166](https://github.com/langchain-ai/deepagents/pull/6166), [#6228](https://github.com/langchain-ai/deepagents/pull/6228), [#6167](https://github.com/langchain-ai/deepagents/pull/6167), [#6168](https://github.com/langchain-ai/deepagents/pull/6168), [#6231](https://github.com/langchain-ai/deepagents/pull/6231))
- Improved indexing and vector maintenance by bounding archive scans, query embeddings, deletion markers, vector rebuilds, and indexing workers, while surfacing indexing failures and resolving import-cycle and PostgreSQL dependency issues. ([#6162](https://github.com/langchain-ai/deepagents/pull/6162), [#6165](https://github.com/langchain-ai/deepagents/pull/6165), [#6163](https://github.com/langchain-ai/deepagents/pull/6163))
- Fixed local voice transcription and embedding retries, and ensured local model downloads persist. ([#6255](https://github.com/langchain-ai/deepagents/pull/6255), [#6137](https://github.com/langchain-ai/deepagents/pull/6137))
- Improved startup, teardown, and provider cleanup by safely unwinding channels that fail mid-start, sharing the optional-driver loader, and closing provider clients. ([#6169](https://github.com/langchain-ai/deepagents/pull/6169), [#6164](https://github.com/langchain-ai/deepagents/pull/6164))

## [0.0.7](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.6...deepagents-talon==0.0.7) (2026-09-07)

### Highlights

- Added Discord channel support, including improved gateway failure reporting after startup. ([#5992](https://github.com/langchain-ai/deepagents/issues/5992), [#6113](https://github.com/langchain-ai/deepagents/issues/6113))
- Added chat-scoped conversation history with configurable storage and optional hybrid search. ([#6105](https://github.com/langchain-ai/deepagents/issues/6105), [#6115](https://github.com/langchain-ai/deepagents/issues/6115), [#6108](https://github.com/langchain-ai/deepagents/issues/6108))
- Added MCP configuration tools, channel-based MCP server authorization, hot reload for MCP configuration, and OAuth/device authentication support for Slack and GitHub MCP integrations. ([#6097](https://github.com/langchain-ai/deepagents/issues/6097), [#6073](https://github.com/langchain-ai/deepagents/issues/6073), [#6084](https://github.com/langchain-ai/deepagents/issues/6084), [#6078](https://github.com/langchain-ai/deepagents/issues/6078), [#6079](https://github.com/langchain-ai/deepagents/issues/6079))
- Added more flexible subagent execution, including background expendable subagents, dcode-style subagents in fork mode, fresh subagents, per-task tool selection, and on-demand subagent configuration reloads. ([#6098](https://github.com/langchain-ai/deepagents/issues/6098), [#6085](https://github.com/langchain-ai/deepagents/issues/6085), [#6129](https://github.com/langchain-ai/deepagents/issues/6129), [#6099](https://github.com/langchain-ai/deepagents/issues/6099))
- Added defensive research defaults and a configuration-hardening self-review skill, with missing research subagent defaults backfilled. ([#6131](https://github.com/langchain-ai/deepagents/issues/6131), [#6136](https://github.com/langchain-ai/deepagents/issues/6136), [#6135](https://github.com/langchain-ai/deepagents/issues/6135))

### New features

- Added a `/help` command. ([#6106](https://github.com/langchain-ai/deepagents/issues/6106))
- Added a `current_time` tool and timezone-aware wall-clock cron schedules. ([#6065](https://github.com/langchain-ai/deepagents/issues/6065), [#6062](https://github.com/langchain-ai/deepagents/issues/6062))
- Added persistent LangGraph checkpoints. ([#6088](https://github.com/langchain-ai/deepagents/issues/6088))
- Added channel debug logging and opt-in agent activity logging. ([#5983](https://github.com/langchain-ai/deepagents/issues/5983), [#5984](https://github.com/langchain-ai/deepagents/issues/5984))
- New messages can now interrupt active turns. ([#6023](https://github.com/langchain-ai/deepagents/issues/6023))
- Long agent turns now keep the typing indicator alive. ([#5993](https://github.com/langchain-ai/deepagents/issues/5993))

### Fixes and improvements

- Improved channel reconnect resilience. ([#6040](https://github.com/langchain-ai/deepagents/issues/6040))
- Improved cron reliability by keeping the ticker alive after failed ticks, and stored cron jobs in a structured, versioned format. ([#6087](https://github.com/langchain-ai/deepagents/issues/6087), [#6086](https://github.com/langchain-ai/deepagents/issues/6086))
- Improved conversation history embeddings and search by correcting token budgets and prompt defaults, making remote embedding settings explicit, keeping search non-blocking, and removing the default Qwen query prefix. ([#6132](https://github.com/langchain-ai/deepagents/issues/6132), [#6133](https://github.com/langchain-ai/deepagents/issues/6133), [#6134](https://github.com/langchain-ai/deepagents/issues/6134))
- Fixed OAuth and MCP integration issues, including TLS hostname normalization, omitted empty optional MCP arguments, persisted OAuth token expiry, secured OAuth discovery, and restarted token refresh. ([#6102](https://github.com/langchain-ai/deepagents/issues/6102), [#6077](https://github.com/langchain-ai/deepagents/issues/6077), [#6090](https://github.com/langchain-ai/deepagents/issues/6090), [#6100](https://github.com/langchain-ai/deepagents/issues/6100))
- Fixed WhatsApp behavior by restoring bridge compatibility, preserving quoted message context and approval loops, handling reactions, and restricting replies to self-chat. ([#5999](https://github.com/langchain-ai/deepagents/issues/5999), [#6025](https://github.com/langchain-ai/deepagents/issues/6025), [#6104](https://github.com/langchain-ai/deepagents/issues/6104), [#6010](https://github.com/langchain-ai/deepagents/issues/6010))
- Treated trailing `[SILENT]` as a suppression marker. ([#6110](https://github.com/langchain-ai/deepagents/issues/6110))

## [0.0.6](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.5...deepagents-talon==0.0.6) (2026-08-28)

### Bug Fixes

- Removed `extract-zip` from the WhatsApp bridge dependency tree. ([#5924](https://github.com/langchain-ai/deepagents/issues/5924))

## [0.0.5](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.4...deepagents-talon==0.0.5) (2026-08-26)

### Bug Fixes

- Migrated MCP discovery to `discover_mcp_config_sources`. ([#5803](https://github.com/langchain-ai/deepagents/issues/5803))

## [0.0.4](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.3...deepagents-talon==0.0.4) (2026-08-24)

### Features

- Require Python 3.12 or greater. ([#5603](https://github.com/langchain-ai/deepagents/issues/5603))

## [0.0.3](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.2...deepagents-talon==0.0.3) (2026-07-06)


### Features

* **sdk:** optional video frame extraction on `read_file` ([#4094](https://github.com/langchain-ai/deepagents/issues/4094)) ([b927147](https://github.com/langchain-ai/deepagents/commit/b927147d026749c6c790bb06c9853515dabf579c))
* **talon:** add Fleet zip import command ([#4493](https://github.com/langchain-ai/deepagents/issues/4493)) ([0289dd0](https://github.com/langchain-ai/deepagents/commit/0289dd0a190e5060e631e840da115dd59c64cf5c))


### Bug Fixes

* **talon:** materialize agents under home ([f2b26a8](https://github.com/langchain-ai/deepagents/commit/f2b26a8915fb70c26d32af6e8240442e5e6118e6))

## [0.0.2](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.1...deepagents-talon==0.0.2) (2026-06-30)


### Features

* **talon:** `DEEPAGENTS_TALON_RECURSION_LIMIT` env var ([#4354](https://github.com/langchain-ai/deepagents/issues/4354)) ([82d1eac](https://github.com/langchain-ai/deepagents/commit/82d1eac59a43f096096e86849733aa716adb18fc))
* **talon:** add reaction approval routing ([#4345](https://github.com/langchain-ai/deepagents/issues/4345)) ([3fe8c0c](https://github.com/langchain-ai/deepagents/commit/3fe8c0c35536626f583df08573469506b9529706))
* **talon:** add Telegram channel adapter, CLI wiring, and offset persistence ([#4097](https://github.com/langchain-ai/deepagents/issues/4097)) ([7c87cec](https://github.com/langchain-ai/deepagents/commit/7c87ceca069874db8555705efab3973301baa1cb))
* **talon:** add tool approval env override ([#4349](https://github.com/langchain-ai/deepagents/issues/4349)) ([d26481d](https://github.com/langchain-ai/deepagents/commit/d26481da615881bae4401dfa485ad925945e667a))
* **talon:** audit reaction approval attempts ([#4348](https://github.com/langchain-ai/deepagents/issues/4348)) ([d7895c4](https://github.com/langchain-ai/deepagents/commit/d7895c4f9b996ad6fe194936bbeaa8beea21e913))
* **talon:** ingest Telegram approval reactions ([#4346](https://github.com/langchain-ai/deepagents/issues/4346)) ([437af0b](https://github.com/langchain-ai/deepagents/commit/437af0bf79332b20ae0c1883c3cc4d91a98c2457))


### Bug Fixes

* **talon:** default workspace to current directory ([#4099](https://github.com/langchain-ai/deepagents/issues/4099)) ([5e337ae](https://github.com/langchain-ai/deepagents/commit/5e337ae50a76bc174b752be187e62698a389cbe6))

## Changelog

All notable changes to this project will be documented in this file.
