# Reliable Agents

A curated list of open-source tools for improving the reliability of AI agents.

## Coding reliable agents

- [Trustabl Agent Reliability Skills](https://github.com/trustabl/agent-reliability-skills) — Reads a repository's dependencies and generates a `SKILL.md` with reliability rules for its agent SDKs, helping coding agents apply them while writing code.

## Test and evaluate

### Testing and evaluation

- [AgentEvals](https://github.com/langchain-ai/agentevals) — LangChain evaluators for agent trajectories, including whether the agent took the right steps and made the right tool calls.
- [DeepEval](https://github.com/confident-ai/deepeval) — Pytest-style evaluation framework with agent, tool-use, and task-completion metrics.
- [Giskard](https://github.com/Giskard-AI/giskard) — Testing library that scans LLM applications and agents for quality, robustness, and security issues.
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) — Evaluation framework from the UK AI Security Institute for agentic and tool-using tasks.
- [LangWatch Scenario](https://github.com/langwatch/scenario) — Simulation-based agent testing, where an agent tests another agent across multi-turn scenarios in CI.
- [OpenEvals](https://github.com/langchain-ai/openevals) — LangChain's library of ready-made evaluators for LLM applications.
- [promptfoo](https://github.com/promptfoo/promptfoo) — Test and red-team prompts, agents, and RAG pipelines with declarative test cases.
- [Ragas](https://github.com/explodinggradients/ragas) — Evaluation toolkit for LLM applications, including retrieval-augmented generation and agent metrics.

### Agent benchmarks

- [AgentBench](https://github.com/THUDM/AgentBench) — Benchmark suite for evaluating LLM-based agents across interactive environments.
- [BrowserGym](https://github.com/ServiceNow/BrowserGym) — Benchmark and environment framework for evaluating web-browsing agents.
- [OSWorld](https://github.com/xlang-ai/OSWorld) — Benchmark environment for evaluating agents on realistic computer-use tasks.
- [τ-bench](https://github.com/sierra-research/tau-bench) — Benchmark measuring agent consistency over repeated runs (pass^k) in tool-use domains.

## Contain and control

### Sandboxes and access probes

- [Trustabl Agent Network Access Probe](https://github.com/trustabl/agent-network-access-probe) — Runs an agent tool in an OpenShell or Docker sandbox, records the network destinations it contacts, and drafts a least-privilege network policy from that evidence.
- [E2B](https://github.com/e2b-dev/infra) — Cloud sandboxes for running agent-generated code.
- [NVIDIA OpenShell](https://github.com/NVIDIA/OpenShell) — Sandbox runtime for AI agents with policy-controlled filesystem, network, and process access.
- [Strands Box](https://github.com/strands-agents/box) — Agent sandbox from AWS with kernel-enforced isolation and policy checks for shell commands, Python, MCP tool calls, and network traffic. Developer preview for macOS.

### Runtime guardrails

- [Guardrails AI](https://github.com/guardrails-ai/guardrails) — Input and output validators that enforce structure and policy on model responses.
- [LlamaFirewall](https://github.com/meta-llama/PurpleLlama) — Meta's framework for detecting prompt injection and unsafe agent actions, part of PurpleLlama.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — Programmable rails for topical control, safety, and execution in LLM applications and agents.

## Observe and learn

- [Trustabl Agent OpenTelemetry Rules](https://github.com/trustabl/agent-opentelemetry-rules) — Runtime rules that evaluate agent telemetry for reliability issues, designed to run inside observability platforms.
- [Trustabl Agent Reliability OTel Labels](https://github.com/trustabl/agent-reliability-otel-labels) — OpenTelemetry labels SDK that adds agent-specific reliability context to traces so observability platforms can evaluate agent behavior.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) — AI observability and evaluation built on OpenTelemetry and OpenInference.
- [Langfuse](https://github.com/langfuse/langfuse) — LLM engineering platform for tracing, evaluations, prompt management, and datasets.
- [LangWatch](https://github.com/langwatch/langwatch) — LLM operations platform for agent monitoring, evaluation, and optimization.
- [OpenLIT](https://github.com/openlit/openlit) — OpenTelemetry-native observability for LLMs and agents, with evaluations and guardrails on live traces.
- [OpenLLMetry](https://github.com/traceloop/openllmetry) — OpenTelemetry instrumentation for LLM providers and agent frameworks.
- [OpenTelemetry GenAI semantic conventions](https://github.com/open-telemetry/semantic-conventions/tree/main/docs/gen-ai) — Semantic conventions for GenAI and agent spans, metrics, and events.
- [Pydantic Logfire SDK](https://github.com/pydantic/logfire) — OpenTelemetry-based observability SDK with first-class Pydantic AI support.
- [Weave](https://github.com/wandb/weave) — Toolkit from Weights & Biases to trace, inspect, and evaluate LLM and agent calls.

## Turn failures into reliability improvements

- **Capture the failed run's trace** to create a reproducible scenario test.
- **Identify the code pattern behind the failure** and turn it into a static-analysis rule that checks every agent.
- **Save the triggering input** as an evaluation case and run it on every release.
- **Assess the blast radius** and improve containment with tighter permissions, budgets, or approval gates.

## Contributions

Contributions are welcome. Suggest open-source tools that help code, test, contain, or observe AI agents. Include a short description and place each entry in the most relevant category.

> Tool capabilities and project status can change. Check each project's documentation and license before adopting it.
