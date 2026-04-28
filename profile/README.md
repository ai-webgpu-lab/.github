# AI WebGPU Lab

Browser-first research organization for WebGPU graphics, scientific visualization, and on-device AI workloads.

## Focus Areas
- WebGPU graphics library comparisons
- Blackhole, compute, and scientific visualization experiments
- Browser ML, LLM, audio, multimodal, and agent baselines
- Reproducible benchmark harnesses and demo applications

## Repository Model
- `tpl-*`: starter templates
- `shared-*`: shared schema, capability, and automation utilities
- `exp-*`: single-question experiments
- `bench-*`: comparison and measurement harnesses
- `app-*`: integrated demos and showcases
- `docs-*`: roadmap, ADR, and reporting repositories

## Operating Rules
- One repository answers one question.
- Every experiment publishes `RESULTS.md` and raw JSON output.
- WebGPU-first, with fallback paths recorded explicitly.
- Repositories are reviewed on a promote / continue / archive cadence.

## Live Status
- Pages/demo status: `docs-lab-roadmap/docs/PAGES-STATUS.md`
- Integration status: `docs-lab-roadmap/docs/INTEGRATION-STATUS.md`
- Sketch metrics: `docs-lab-roadmap/docs/SKETCH-METRICS.md`
- Representative real-mode smoke targets: `bench-runtime-shootout`, `exp-three-webgpu-core`, `bench-renderer-shootout`, `app-blackhole-observatory`

## Start Here
- Master summary: `docs-lab-roadmap/docs/00-master-summary.md`
- Repository map: `docs-lab-roadmap/docs/01-org-repo-map.md`
- Projects design: `docs-lab-roadmap/docs/04-github-projects-design.md`
