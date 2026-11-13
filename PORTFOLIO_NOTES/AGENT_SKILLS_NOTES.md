# Agent and Skills Notes — Ollama Fork

## Instruction precedence

Upstream AGENTS.md, CONTRIBUTING.md and repository conventions remain authoritative. This document adds local portfolio constraints only.

## Bounded agent workflow

- Inspect upstream issues, version history and affected platform before editing.
- Keep local examples/benchmarks separate from upstream core changes.
- Never log API keys, private prompts, model credentials or user data.
- Add tests for affected platform/runtime behavior and note when hardware is unavailable.
- Benchmark with exact model digest, quantisation, prompt, output length and hardware.
- Do not publish releases, installers or packages autonomously.

## Skill areas

- Local model runtime configuration.
- Model quantisation and platform compatibility.
- Inference latency, throughput and memory profiling.
- Reproducible prompt/output quality evaluation.
- Upstream contribution and fork maintenance.
