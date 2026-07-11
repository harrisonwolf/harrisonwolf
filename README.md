## Harrison Wolf

Research engineer building high-performance mathematical software and reliable agentic systems.

**Portfolio:** [harrisonwolf.github.io](https://harrisonwolf.github.io) — projects, the paper, and how to reach me.

---

### Pinned work

**[boij-soderberg-engine](https://github.com/harrisonwolf/boij-soderberg-engine)** — C++, hand-written
A pure-Betti-table engine that tests two lower-bound conjectures and searches degree-sequence
space for counterexamples; benchmarked against Macaulay2 on task-matched searches (data and
methodology in the repo), and it swept search sizes Macaulay2 can't practically reach. Produced the computation behind one of three
main theorems in *Arithmetic in the Boij–Söderberg Cone* ([arXiv:2512.24320](https://arxiv.org/abs/2512.24320)).

**[ltx-studio](https://github.com/harrisonwolf/ltx-studio)** — Python
A local multi-model generative-video studio (LTX-Video + Wan) on a single 8GB GPU, with an
in-process Qwen3-VL "creative director" agent that turns natural language into runnable configs,
plus a quantitative eval layer (seam-MSE / drift telemetry + blind A/B harness). Its predecessor
was an AnimateDiff pipeline I steered onto the same 8GB card (a PyTorch-SDPA attention backport,
a from-scratch LCM scheduler, and a conv-aware LoRA merge).

**[geo-map-v2](https://github.com/harrisonwolf/geo-map-v2)** — Python, roughly 1:1 code to tests
A geospatial data platform whose first vertical is a county real-estate heatmap: a hashed canonical
SQLite ledger with provenance, immutable monthly snapshots, a strictly read-only serving runtime, and
a MapLibre-GL renderer over official county GIS (parcels, roads, ZIPs, schools, attendance zones).
Built by orchestrating Codex + Claude across git worktrees under a governance-heavy AGENTS.md
(prompt-injection defense, test-first rules).

**[planar-geometry-engine](https://github.com/harrisonwolf/planar-geometry-engine)** — C++, standard library only
A from-scratch computational-geometry engine built in vim + make: robust predicates with explicit
epsilon handling, ear-clipping and Delaunay triangulation, Voronoi diagrams, and a hand-rolled TDD harness
(14 suites). Core hand-written before my agent workflow; later upgrades AI-assisted.

---

### What I actually do

- **Agentic-coding orchestration** — I architect, direct, test, and evaluate AI coding agents
  (Codex, Claude, etc.) across parallel worktrees with phase plans and governance rules. The large
  systems above are AI-built under my direction; what makes that work is the architecture, the
  test gates, and the evaluation around the agents.
- **Agentic-coding evaluation** — Agentic Coding Model Evaluator / Analyst at DataAnnotation since Aug 2024, reviewing
  agentic coding models: reasoning traces, code correctness, and failure modes. Selected for the
  quality-review team based on performance; I audit other evaluators' and analysts' work.
- **ML-systems + diffusion internals** — attention backports, custom schedulers, latent-space
  drift control, quantitative seam/drift evals on consumer hardware.
- **Raw engineering** — the C++ engines are hand-written at their core and hand-designed / architected; overflow-avoiding early-exit, honest
  algorithm-vs-language benchmarking methodology.

**Reach me:** harrisonwolf42@gmail.com · [LinkedIn](https://www.linkedin.com/in/harrison-wolf-5aa216187)
