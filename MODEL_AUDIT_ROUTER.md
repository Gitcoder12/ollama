# Independent Model Audit Router — ollama

**Revision date:** 2026-11-13  
**Repository class:** Personal fork of upstream project **ollama/ollama**.

## Upstream attribution and integrity
- This repository is a fork. Do not claim the upstream project, codebase, README, maintainers, commits or releases as original work by this repository owner.
- Preserve upstream copyright, licence, notices, README, contribution rules and provenance.
- Audit only changes made in this fork separately from upstream history. Record the exact fork-specific diff and base/upstream SHA.
- Never rewrite the upstream README. Any portfolio note must be a separate, dated, clearly labelled section at the very bottom and must not remove or modify upstream technical content.
- Do not repackage, relabel, or misrepresent upstream datasets, benchmarks, model results, maintainers or contributors.

## Data integrity rules
- Never replace upstream or maintainer-provided datasets with fabricated, generated, synthetic or placeholder records.
- Trace every data change to its original source, licence, date, upstream commit and documented limitations.
- If provenance is unknown, preserve current data and mark it unknown/unverified. Never invent replacements.
- Synthetic fixtures belong only in clearly labelled tests/examples and must be separate from runtime data.
- Never invent citations, metrics, benchmark results, customers, partnerships, deployments, endorsements or individual contributors.
- Test claims need reproducible evidence on the exact fork commit reviewed.

## Independent audit roles
1. Upstream provenance, attribution and licence reviewer.
2. Dataset and benchmark integrity reviewer.
3. Code/security/dependency reviewer.
4. Tests, build, CI and reproducibility reviewer.
5. README/documentation and public-claim reviewer.
6. Career-integrity reviewer distinguishing fork maintenance from upstream authorship.

## Audit sequence
1. Record fork URL, upstream URL, base branch, exact HEAD SHA and merge-base SHA.
2. Compare fork with upstream; enumerate fork-only commits, files and changes.
3. Review all fork PRs and classify them as merged, open, closed-unmerged, reverted or unverified.
4. Inspect datasets, benchmark inputs, generated files, fixtures, licenses and provenance.
5. Preserve upstream README exactly; append a clearly separated portfolio addendum only if needed.
6. Run documented checks on the exact fork commit and inspect CI for suppressed failures.
7. Report security, reproducibility, attribution and performance issues with evidence.

## Required finding format
Severity (**P0/P1/P2/P3**), exact path/line, upstream/fork comparison, reproduction, expected vs actual, evidence and SHA, confirmed/suspected/unverifiable status, minimal fix, regression test and attribution impact.

## Merge gate
- [ ] Fork-specific work is distinguished from upstream work.
- [ ] Upstream licence, copyright, notices and README are preserved.
- [ ] No real data is silently replaced with synthetic records.
- [ ] Data and benchmarks have source/licence/provenance notes.
- [ ] Exact-head tests/CI are checked; failures disclosed.
- [ ] No secrets, private personal details, classified or confidential information.
- [ ] Second independent review and maintainer approval recorded.

**Do not claim ownership of upstream work.** Do not merge, delete, force-push, replace datasets or alter upstream documentation during an audit. The repository owner has final approval.
