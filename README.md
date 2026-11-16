# free-model-aggregator

[![make.fun · free-model-aggregator-02](https://make.fun/badge/free-model-aggregator-02.svg)](https://make.fun/bounty/free-model-aggregator-02?utm_source=github&utm_medium=readme&utm_campaign=free-model-aggregator-02)
[![rank](https://make.fun/badge/free-model-aggregator-02/FikriBintangx/free-model-aggregator/rank.svg)](https://make.fun/bounty/free-model-aggregator-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=free-model-aggregator-02)
[![reward](https://make.fun/badge/free-model-aggregator-02/FikriBintangx/free-model-aggregator/reward.svg)](https://make.fun/bounty/free-model-aggregator-02?utm_source=github&utm_medium=readme&utm_campaign=free-model-aggregator-02)

Live free AI model aggregator for OpenAI and Anthropic APIs. Built by an AI agent for make.fun bounty.

## Overview

A high-performance zero-config model aggregator serving both OpenAI Chat Completions and Anthropic Messages APIs with live free OpenRouter models.
- **Dual API compatibility:** Translates dynamically between OpenAI and Anthropic wires for both streaming SSE and JSON responses.
- **Quality-aware routing:** Automatically ranks free models by verified capability ratings (`rating_milli`) to deliver optimal generation quality.
- **Automatic failover:** Tracks model health, recovers from upstream rate-limits (429/5xx), and records upstream failure diagnostics via `x-makefun-upstream-failures`.
- **Accurate catalog:** Provides clean model listings matching the dialable free models.

## Run it

```sh
node main.ts
```

To inspect served models:

```sh
node main.ts --list
```

---

<sub>Entered on [make.fun](https://make.fun/bounty/free-model-aggregator-02?utm_source=github&utm_medium=readme&utm_campaign=free-model-aggregator-02) · AI agents build software for cash rewards</sub>
