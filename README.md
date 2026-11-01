<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg" /><img src="assets/hero-dark.svg" alt="AI/LLM Engineer @ ilert" width="100%" /></picture>
</p>

<p align="center">
  Production LLM agents for alerting and incident response at <a href="https://www.ilert.com">ilert</a>, Köln.<br />
  Multi-agent / A2A · MCP · realtime voice · Rust LLM gateway · AWS Bedrock · evals and guardrails
</p>

<p align="center">
  <a href="https://huggingface.co/spaces/Quexoo/docrag-bench"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/link-live-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/link-live-light.svg" /><img src="assets/link-live-dark.svg" alt="Live demo docrag-bench" height="36" /></picture></a>&nbsp;
  <a href="https://www.npmjs.com/package/agent-approval-gate"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/link-npm-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/link-npm-light.svg" /><img src="assets/link-npm-dark.svg" alt="npm agent-approval-gate" height="36" /></picture></a>&nbsp;
  <a href="https://crates.io/crates/agent-approval-gate"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/link-cratesio-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/link-cratesio-light.svg" /><img src="assets/link-cratesio-dark.svg" alt="crates.io agent-approval-gate" height="36" /></picture></a>
</p>

<br />

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/div-projects-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/div-projects-light.svg" /><img src="assets/div-projects-dark.svg" alt="Projects" width="100%" /></picture>

| | Project | What it does | Result |
|:-:|:--|:--|:--|
| <picture><source media="(prefers-color-scheme: dark)" srcset="assets/i-docrag-bench-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/i-docrag-bench-light.svg" /><img src="assets/i-docrag-bench-dark.svg" alt="" width="36" height="36" /></picture> | **[docrag-bench](https://github.com/byQuexo/docrag-bench)**<br /><sub>Python</sub> | PDF question answering with verified citations, plus a benchmark of what actually helps. | <picture><source media="(prefers-color-scheme: dark)" srcset="assets/m-docrag-bench-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/m-docrag-bench-light.svg" /><img src="assets/m-docrag-bench-dark.svg" alt="0 → 0.83 recall@10 on scanned PDFs" height="30" /></picture><br /><sub>recall@10 on scanned PDFs</sub> |
| <picture><source media="(prefers-color-scheme: dark)" srcset="assets/i-agent-approval-gate-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/i-agent-approval-gate-light.svg" /><img src="assets/i-agent-approval-gate-dark.svg" alt="" width="36" height="36" /></picture> | **[agent-approval-gate](https://github.com/byQuexo/agent-approval-gate)**<br /><sub>TypeScript · Rust</sub> | Human-in-the-loop approval for LLM agent tool calls. On npm and crates.io. | <picture><source media="(prefers-color-scheme: dark)" srcset="assets/m-agent-approval-gate-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/m-agent-approval-gate-light.svg" /><img src="assets/m-agent-approval-gate-dark.svg" alt="51 tests, 42 TS + 9 Rust" height="30" /></picture><br /><sub>tests, 42 TS + 9 Rust</sub> |
| <picture><source media="(prefers-color-scheme: dark)" srcset="assets/i-Alert-Grouping-Evaluation-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/i-Alert-Grouping-Evaluation-light.svg" /><img src="assets/i-Alert-Grouping-Evaluation-dark.svg" alt="" width="36" height="36" /></picture> | **[Alert-Grouping-Evaluation](https://github.com/byQuexo/Alert-Grouping-Evaluation)**<br /><sub>Python</sub> | BSc dissertation: grouping Prometheus alerts with multilingual embeddings. | <picture><source media="(prefers-color-scheme: dark)" srcset="assets/m-Alert-Grouping-Evaluation-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/m-Alert-Grouping-Evaluation-light.svg" /><img src="assets/m-Alert-Grouping-Evaluation-dark.svg" alt="0.91–0.95 F1 on EN / FR / ES" height="30" /></picture><br /><sub>F1 on EN / FR / ES</sub> |
| <picture><source media="(prefers-color-scheme: dark)" srcset="assets/i-incident-triage-demo-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/i-incident-triage-demo-light.svg" /><img src="assets/i-incident-triage-demo-dark.svg" alt="" width="36" height="36" /></picture> | **[incident-triage-demo](https://github.com/byQuexo/incident-triage-demo)**<br /><sub>TypeScript</sub> | On-call SRE agent on Gemini that asks before it acts. | <picture><source media="(prefers-color-scheme: dark)" srcset="assets/m-incident-triage-demo-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/m-incident-triage-demo-light.svg" /><img src="assets/m-incident-triage-demo-dark.svg" alt="3 risk tiers, reads run, writes wait" height="30" /></picture><br /><sub>risk tiers, reads run, writes wait</sub> |

<br />

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/div-rig-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/div-rig-light.svg" /><img src="assets/div-rig-dark.svg" alt="Upstream: Rig" width="100%" /></picture>

<p align="center"><a href="https://github.com/0xPlaygrounds/rig">Rig</a> is the Rust LLM framework behind ilert AI's agentic LLM proxy. Three merged fixes · <a href="https://github.com/0xPlaygrounds/rig/pulls?q=is%3Apr+is%3Amerged+author%3AbyQuexo">all PRs</a></p>

| PR | Change | Merged |
|:--|:--|:--|
| <a href="https://github.com/0xPlaygrounds/rig/pull/1725"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/pr-1725-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/pr-1725-light.svg" /><img src="assets/pr-1725-dark.svg" alt="#1725" height="24" /></picture></a> | fix(mistral): expose cached and audio token fields in Usage | 4 May 2026 |
| <a href="https://github.com/0xPlaygrounds/rig/pull/1683"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/pr-1683-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/pr-1683-light.svg" /><img src="assets/pr-1683-dark.svg" alt="#1683" height="24" /></picture></a> | fix(bedrock): preserve adaptive-thinking signatures in streaming reasoning | 28 Apr 2026 |
| <a href="https://github.com/0xPlaygrounds/rig/pull/1675"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/pr-1675-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/pr-1675-light.svg" /><img src="assets/pr-1675-dark.svg" alt="#1675" height="24" /></picture></a> | fix(bedrock): handle adaptive-thinking interactions for prompt caching and reasoning conversion | 28 Apr 2026 |

<br />

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/div-stack-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/div-stack-light.svg" /><img src="assets/div-stack-dark.svg" alt="Stack" width="100%" /></picture>

<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="assets/stack-light.svg" /><img src="assets/stack-dark.svg" alt="Rust, TypeScript, Python, AWS Bedrock, Qdrant, Hugging Face, MCP" height="36" /></picture>
</p>

<br />

<img src="https://raw.githubusercontent.com/byQuexo/byQuexo/output/snake.svg" width="100%" alt="contribution snake" />

<!-- Optional, enable if it applies: -->
<!-- Open to conversations about LLM agents in production. -->
