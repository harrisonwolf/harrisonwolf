# Harrison Wolf

Computational research engineer designing and building AI governance and reliability systems.

I build computational machinery for problems where getting an answer is not enough—you need a way to know whether the answer deserves to be believed. My work ranges from hand-written C++ engines for mathematical and geometric problems to larger systems whose architecture, interfaces, tests, and review gates I define before implementation, sometimes through coding-agent fleets.

**Portfolio:** [harrisonwolf.github.io](https://harrisonwolf.github.io/) · **Contact:** [harrisonwolf42@gmail.com](mailto:harrisonwolf42@gmail.com) · **LinkedIn:** [harrison-wolf-5aa216187](https://www.linkedin.com/in/harrison-wolf-5aa216187/)

## Selected work

### [Nexora Audit Edition](https://github.com/harrisonwolf/nexora-audit-edition)

A synthetic, executable extraction of five reliability mechanisms from a larger private neighborhood-intelligence system. It includes integrity-bound manifests, bounded publication, a journaled multi-target transition, typed SQLite carry-over, and evidence-qualified ranking, together with tests, claims, a source map, and explicit limitations. Released under AGPL-3.0 for independent inspection; the product, real data, interface, configuration, and private history remain private.

### [Boij–Söderberg search engine](https://github.com/harrisonwolf/boij-soderberg-engine)

A hand-written C++ engine for conjecture searches over pure Betti tables. On matched searches it runs approximately 70–115 times faster than Macaulay2 on the same machine. A larger search campaign surfaced counterexamples used in one of the three main theorems of [*Arithmetic in the Boij–Söderberg Cone*](https://arxiv.org/abs/2512.24320). The repository includes benchmark methodology, raw data, and known limits.

### [Planar geometry engine](https://github.com/harrisonwolf/planar-geometry-engine)

A standard-library-only C++ workbench implementing geometric predicates, polygon operations, collision and containment queries, ear-clipping and Delaunay triangulation, Voronoi construction, and local viewers. The repository includes a hand-rolled test harness, boundary-case fixtures, and benchmark records.

### [LTX Studio](https://github.com/harrisonwolf/ltx-studio)

A local video-generation workflow built around two published open-weight backends on one 8 GB GPU. It combines a terminal interface, model orchestration, archived run settings and telemetry, seam/drift measurements, and a blind A/B comparison harness. It is an orchestration and measurement project, not a new video model.

## Current work

- Developing a private governance layer for multi-agent software work: preregistered checks, retained run evidence, adversarial review, and operator-reserved decisions. The design and implementation remain in progress.
- Evaluating frontier coding agents at DataAnnotation since August 2024: reasoning traces, code correctness, failure modes, containerized evaluation tasks, and quality review of other evaluators' work.
- Maintaining the full private Nexora system; its public Audit Edition exposes selected reliability mechanisms without publishing the product, data, interface, configuration, or private history.

## How I work

On compact problems, I keep the implementation small enough to inspect directly and measure boundary cases, performance, and failure. On larger systems, I define the architecture, interfaces, and acceptance tests before implementation, then review the result against them. The algebra and geometry cores are hand-written; coding agents produced most of Nexora's Python implementation under my architecture, schema, scoring, and test gates. Each project identifies external models, algorithms, and implementation boundaries.

I also take on a small number of paid [Agent Trust Reviews](https://harrisonwolf.github.io/#reviews): bounded technical second opinions on one AI-agent architecture, evaluation, persistent failure, or deployment decision.
