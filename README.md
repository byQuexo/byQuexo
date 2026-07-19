<img src="./assets/terminal.svg" width="100%" alt="byQuexo@ilert terminal" />

<p align="center">
  <img src="https://img.shields.io/github/followers/byQuexo?style=flat-square&logo=github&logoColor=white&label=followers&labelColor=0d1117&color=3fb950" alt="followers" />
  <img src="https://komarev.com/ghpvc/?username=byQuexo&style=flat-square&label=visitors&labelColor=0d1117&color=58a6ff" alt="visitors" />
  <a href="https://ilert.com"><img src="https://img.shields.io/badge/on--call-@ilert-0375E5?style=flat-square&labelColor=0d1117" alt="ilert" /></a>
</p>

```rust
impl Engineer for ByQuexo {
    const ROLE:  &str = "Software Engineer @ ilert";
    const FOCUS: &str = "wiring LLMs into alert & incident response";

    fn stack(&self) -> Stack {
        Stack {
            languages: vec![Rust, TypeScript, Python],
            ml:        vec![PyTorch, TensorFlow],
            infra:     vec![Aws, Kafka, Redis, Postgres, Docker],
        }
    }

    fn currently(&self) -> &str {
        "teaching on-call automation to reason with adaptive thinking"
    }
}
```

#### `byQuexo@ilert:~/oss$ git log --author=byQuexo --oneline`

Contributing to [**Rig**](https://github.com/0xPlaygrounds/rig) — the Rust LLM framework (**7.2k ⭐**) powering [ilert AI](https://ilert.com)'s agentic LLM proxy:

- [`#1725`](https://github.com/0xPlaygrounds/rig/pull/1725) &nbsp;expose Mistral's cached & audio token fields in `Usage` — unblocks accurate cost tracking + prompt-cache observability
- [`#1683`](https://github.com/0xPlaygrounds/rig/pull/1683) &nbsp;preserve AWS Bedrock adaptive-thinking signatures in streaming — fixes dropped cryptographic signatures in multi-turn Claude conversations
- [`#1675`](https://github.com/0xPlaygrounds/rig/pull/1675) &nbsp;fix Bedrock cache-point placement + empty-text reasoning conversion with signatures

#### `byQuexo@ilert:~/oss$ npm publish && cargo publish`

**[agent-approval-gate](https://github.com/byQuexo/agent-approval-gate)** — human-in-the-loop approval for LLM agent tool calls. Classify tools read/write, hold every write & destructive action behind an approver, and never cache a grant across turns.

<p>
  <a href="https://www.npmjs.com/package/agent-approval-gate"><img src="https://img.shields.io/npm/v/agent-approval-gate?style=flat-square&logo=npm&label=npm&labelColor=0d1117&color=cb3837" alt="npm" /></a>
  <a href="https://crates.io/crates/agent-approval-gate"><img src="https://img.shields.io/crates/v/agent-approval-gate?style=flat-square&logo=rust&label=crates.io&labelColor=0d1117&color=3fb950" alt="crates.io" /></a>
  <img src="https://img.shields.io/badge/tests-51%20passing-3fb950?style=flat-square&labelColor=0d1117" alt="tests" />
</p>

- one shared policy format across **TypeScript & Rust** — 42 TS + 9 Rust tests, CI on both
- drop-in adapters: **OpenAI · Anthropic · Gemini · AWS Bedrock · MCP · Vercel AI SDK · Rig**
- [**incident-triage-demo**](https://github.com/byQuexo/incident-triage-demo) &nbsp;·&nbsp; a Gemini-powered on-call agent that asks before it acts

#### `byQuexo@ilert:~$ uptime --activity`

<img src="https://github-readme-activity-graph.vercel.app/graph?username=byQuexo&theme=github-compact&hide_border=true&bg_color=0d1117&color=3fb950&line=58a6ff&point=f0f6fc&area=true&area_color=3fb950" width="100%" alt="contribution activity" />

<img src="https://raw.githubusercontent.com/byQuexo/byQuexo/output/snake.svg" width="100%" alt="contribution snake" />

<sub>`byQuexo@ilert:~$ exit` &nbsp;·&nbsp; thanks for dropping by 👋</sub>
