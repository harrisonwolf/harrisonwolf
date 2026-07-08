## Harrison Wolf

C++ / math / algorithms engineer who architects, directs, and evaluates fleets of
AI coding agents to ship real ML systems. Fresno, CA — available now.

I build the parts that have to be right: a from-scratch C++ computation engine that
outran the industry-standard CAS on a published math problem, and larger Python systems
built through AI-agent orchestration under my architecture, testing, and evaluation.

**Focus:** research-engineer / applied-AI / agentic-coding roles; commissions also.
**Portfolio:** [harrisonwolf.github.io](https://harrisonwolf.github.io) — projects, the paper, and how to reach me.

---

### Pinned work

**[boij-soderberg-engine](https://github.com/harrisonwolf/boij-soderberg-engine)** — C++, ~2,700 lines, hand-written
A pure-Betti-table engine that tests two lower-bound conjectures and searches degree-sequence
space for counterexamples; benchmarked up to ~50x faster than Macaulay2 (~30x typical) and
completed searches Macaulay2 ran out of memory on. Produced the computation behind one of three
main theorems in *Arithmetic in the Boij–Söderberg Cone* ([arXiv:2512.24320](https://arxiv.org/abs/2512.24320)).

**[ltx-studio](https://github.com/harrisonwolf/ltx-studio)** — Python, ~8,470 lines
A local multi-model generative-video studio (LTX-Video + Wan) on a single 8GB GPU, with an
in-process Qwen3-VL "creative director" agent that turns natural language into runnable configs,
plus a quantitative eval layer (seam-MSE / drift telemetry + blind A/B harness). Its predecessor
was an AnimateDiff pipeline I steered onto the same 8GB card — a PyTorch-SDPA attention backport,
a from-scratch LCM scheduler, and a conv-aware LoRA merge.

**[geo-map-v2](https://github.com/harrisonwolf/geo-map-v2)** — Python, ~30,000 lines (~14,600 in tests)
A geospatial data platform — a county real-estate heatmap is its first vertical: a hashed canonical
SQLite ledger with provenance, immutable monthly snapshots, a strictly read-only serving runtime, and
a MapLibre-GL renderer over official county GIS (parcels, roads, ZIPs, schools, attendance zones).
Built by orchestrating Codex + Claude across git worktrees under a governance-heavy AGENTS.md
(prompt-injection defense, test-first discipline).

**[planar-geometry-engine](https://github.com/harrisonwolf/planar-geometry-engine)** — C++, ~5,600 lines, standard library only
A from-scratch computational-geometry engine built in vim + make: robust predicates with epsilon
discipline, ear-clipping and Delaunay triangulation, Voronoi diagrams, and a hand-rolled TDD harness
(14 suites). Core hand-written before my agent workflow; later upgrades AI-assisted.

---

### What I actually do

- **Agentic-coding orchestration** — I architect, direct, test, and evaluate AI coding agents
  (Codex, Claude) across parallel worktrees with phase plans and governance rules. The large
  systems above are AI-built under my direction; my differentiator is the judgment, architecture,
  and testing that make that trustworthy.
- **Agentic-coding evaluation** — Software Engineer at DataAnnotation since Aug 2024, reviewing
  agentic coding models: reasoning traces, code correctness, and failure modes. Selected for
  the quality-review team.
- **ML-systems + diffusion internals** — attention backports, custom schedulers, latent-space
  drift control, quantitative seam/drift evals on consumer hardware.
- **Raw engineering** — the C++ engine is hand-written; overflow-avoiding early-exit, honest
  algorithm-vs-language benchmarking methodology.

**Reach me:** harrisonwolf42@gmail.com · [LinkedIn](https://www.linkedin.com/in/harrison-wolf-5aa216187)
