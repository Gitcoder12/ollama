# Ollama Fork — Feature and Experiment Plan

## Objective

Create a reproducible local-inference study while maintaining a clean, attribution-safe fork.

## P0 — reproducible baseline

- [ ] Document local hardware/OS baseline and supported Ollama version with exact model tag/digest.
- [ ] Measure model load time, time-to-first-token, generation throughput, peak memory and cold/warm behavior using fixed prompts.

## P1 — controlled configuration study

- [ ] Compare quantisation and CPU/GPU settings with fixed prompts and output lengths.
- [ ] Measure output quality as well as speed/memory.
- [ ] Document model digest, settings and device/runtime versions.

## P2 — maintainable contribution workflow

- [ ] Compare CPU/GPU and quantisation settings with accuracy/quality checks; do not compare unlike models as direct speedups.
- [ ] Keep local benchmark scripts and result tables in a separate portfolio path; preserve upstream runtime code unless a focused bug is reproduced.
- [ ] For upstream issues, pin a version, provide a minimal reproduction and follow upstream contribution guidance.

## Definition of done

- [ ] Another contributor can reproduce each result on the stated hardware class.
- [ ] Model/version/digest and prompt set are recorded.
- [ ] Performance and quality are both reported.
- [ ] Local experiments are separate from upstream-owned runtime code.
