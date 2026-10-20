<div align="center">

<img src="assets/header.svg" width="100%" alt="Anwar Debes: interpretable AI, Tsetlin Machines and AI safety. A 3D glass box opens to show the logical clause behind each decision."/>

<p>
<a href="https://safemediai.com"><img src="https://img.shields.io/badge/SafeMediAI-CFO-7c3aed?style=for-the-badge" alt="CFO at SafeMediAI"/></a>
<a href="https://declassifai.com"><img src="https://img.shields.io/badge/DeclassifAI-product-0ea5e9?style=for-the-badge" alt="DeclassifAI"/></a>
<a href="https://cair.uia.no"><img src="https://img.shields.io/badge/MSc_AI-UiA_%C2%B7_CAIR-10b981?style=for-the-badge" alt="MSc in AI at UiA, CAIR"/></a>
<a href="https://nyheter.ntnu.no/disse-har-vunnet-eurekaprisen-2025/#:~:text=Automatic%20Removal%20of%20Sensitive%20Content,Yasin%20Hessnawi"><img src="https://img.shields.io/badge/Eurekaprisen-2025-f59e0b?style=for-the-badge" alt="Eurekaprisen 2025, NTNU"/></a>
<a href="#papers-and-technical-reports"><img src="https://img.shields.io/badge/papers-20%2B_PDFs-ec4899?style=for-the-badge" alt="20+ papers and technical reports"/></a>
<a href="https://github.com/AnwarDebes?tab=followers"><img src="https://img.shields.io/github/followers/AnwarDebes?label=follow&style=for-the-badge&logo=github&color=0f172a" alt="Follow on GitHub"/></a>
</p>

<sub><a href="#about">About</a> &nbsp;·&nbsp; <a href="#research-map">Research map</a> &nbsp;·&nbsp; <a href="#selected-work">Selected work</a> &nbsp;·&nbsp; <a href="#papers-and-technical-reports">Papers</a> &nbsp;·&nbsp; <a href="#built-after-hours">Built after hours</a> &nbsp;·&nbsp; <a href="#frequently-avoided-questions">FAQ</a> &nbsp;·&nbsp; <a href="#activity">Activity</a></sub>

</div>

## About

Most AI today is a black box: it hands you an answer and asks for your trust. I work on the opposite. I build models whose decisions are made of **readable logic**, so anyone can open the box, see exactly why it decided what it decided, and check it.

- 🎓 Master's student in Artificial Intelligence at the **University of Agder**, doing my research at [CAIR](https://cair.uia.no) under Ole-Christoffer Granmo, who introduced the Tsetlin Machine
- 🔭 Currently building **[glassbox-lm](https://github.com/AnwarDebes/glassbox-lm)**: steps toward a language model whose knowledge is a set of logical clauses you can read
- 🏆 **[Eurekaprisen 2025](https://nyheter.ntnu.no/disse-har-vunnet-eurekaprisen-2025/#:~:text=Automatic%20Removal%20of%20Sensitive%20Content,Yasin%20Hessnawi)** for the best bachelor thesis of the Faculty of Information Technology and Electrical Engineering at NTNU Gjøvik: [*Automatic Removal of Sensitive Content in Images and Documents for Efficient Archiving*](https://hdl.handle.net/11250/3203861), written with Rami Amer and Yasin Hessnawi. Our tool, Hide Me AI, was built for the needs of Mattilsynet.
- 🔐 Bachelor in computer engineering (cybersecurity and programming) from **NTNU Gjøvik**
- 🚀 CFO at **[SafeMediAI](https://safemediai.com)**, the Norwegian AI startup behind **[DeclassifAI](https://declassifai.com)**
- 🤝 Open to collaborations on AI that helps people and holds up to scrutiny

**The common thread is systems that show their work.** Clauses you can read. Certificates anyone can re-check. Hypotheses registered before the runs, and results reported as measured, including the ones that did not work. Even my IDE project follows the house rule: the animation never lies.

<div align="center">

| 60+ | 20+ | 20+ | 0 |
|:---:|:---:|:---:|:---:|
| public repositories | Tsetlin Machine projects | papers and reports (PDF) | black boxes |

</div>

## Research map

<img src="assets/research-map.svg" width="100%" alt="Rotating 3D map of 39 public projects in seven research lines: language models, Graph Tsetlin Machines, safety and verification, interpretability, Tsetlin Machine foundations, climate and health simulators, tools and products."/>

## Selected work

<table>
<tr>
<td width="50%" valign="top">

### [glassbox-lm](https://github.com/AnwarDebes/glassbox-lm)
<sub>MASTER'S RESEARCH · ONGOING</sub>

Measured steps toward a language model whose knowledge is a set of readable Tsetlin Machine clauses. Three studies so far, **91 hypotheses registered before the runs** in the first one alone, and every result reported as measured.

▸ The README leads with what did *not* work. On purpose.

</td>
<td width="50%" valign="top">

### [CANDOR](https://github.com/AnwarDebes/candor)
<sub>INTERPRETABILITY BY CONSTRUCTION · PAPER</sub>

A Legible Bottleneck routes a layer's computation through named concepts and emits a **Faithfulness Certificate** on every forward pass, re-checkable by anyone.

▸ On synthetic ground truth: δ ≈ 0.002 (99.9% agreement) with no measurable accuracy tax, and backdoor detection at AUC ≈ 0.90.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [TRACE](https://github.com/AnwarDebes/trace)
<sub>AI SAFETY · PAPER</sub>

A CPU-only guardrail for AI agents: a Tsetlin content guard with readable clauses, bounded-memory temporal monitors, and a tamper-evident certificate ledger verifiable without the model.

▸ F1 **0.827** on deepset/prompt-injections at **107 µs** per check, in 12.5 KiB.

</td>
<td width="50%" valign="top">

### [THGTM](https://github.com/AnwarDebes/THGTM)
<sub>AI SAFETY · PAPER</sub>

Tsetlin Machines that remember: Echo-Trace automata and bounded temporal literals for verifying whole agent trajectories, not single steps.

▸ Slow-roll exfiltration (synthetic): attack success **0.687** per step, **0.000** with trajectory-level monitors.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [VERITAS](https://github.com/AnwarDebes/veritas)
<sub>FORMAL VERIFICATION · PAPER</sub>

An interpretable guardrail whose declared safety properties are proved or refuted by SAT/SMT solvers, with bypasses repaired by construction.

▸ Retraining stalls at 8 provable bypasses; constructive repair reaches **0** while accuracy goes 0.69 → 0.71.

</td>
<td width="50%" valign="top">

### [attention-distilled-graphtm](https://github.com/AnwarDebes/attention-distilled-graphtm)
<sub>NLP · DISTILLATION</sub>

BERT lends its attention edges as the graph, then gets uninstalled. A Graph Tsetlin Machine learns pure Boolean clauses on top.

▸ **94.77%** mean accuracy on R8 over 5 seeds (the BERT teacher: ~98%).

</td>
</tr>
</table>

**The safety stack:** [THGTM](https://github.com/AnwarDebes/THGTM) learns, [TRACE](https://github.com/AnwarDebes/trace) detects and certifies, [REINS](https://github.com/AnwarDebes/reins) enforces, [VERITAS](https://github.com/AnwarDebes/veritas) verifies.

<details>
<summary><b>All Tsetlin Machine work</b> (click to expand)</summary>
<br/>

| Project | What it does | Measured |
|---|---|---|
| [DiTM](https://github.com/AnwarDebes/DiTM) | Generative Tsetlin Machine: discrete diffusion over Boolean vectors, readable at every step | anomaly ROC AUC 0.677 vs 0.580 for naive Bayes |
| [REINS](https://github.com/AnwarDebes/reins) | Least-cost repair of AI agent tool calls under temporal safety policies | 3× the task completion of blocking at the same safety (synthetic) |
| [LUCID](https://github.com/AnwarDebes/lucid) | Glass-box agent for ARC-AGI-3 with a readable world model | completes 2 public levels |
| [Clause-Driven-LLM](https://github.com/AnwarDebes/Clause-Driven-LLM) | Clause-based routing for LLM agents with SAT-checkable receipts | 94.2% on CLINC150 (logistic regression: 95.6%) |
| [graphtm-cbr](https://github.com/AnwarDebes/graphtm-cbr) | Mutagenicity prediction that proposes minimal valid molecule edits | recourse success 95.5% (191/200) |
| [Multi-HGTM](https://github.com/AnwarDebes/Multi-HGTM) | Multi-view Graph Tsetlin Machine with clause fusion | 0.968 vs 0.727 for late fusion (synthetic) |
| [subword-dep-graphtm](https://github.com/AnwarDebes/subword-dep-graphtm) | Subword and dependency graphs for text classification | 95.05% mean on R8 |
| [decoder-attention-distill-graphtm](https://github.com/AnwarDebes/decoder-attention-distill-graphtm) | Decoder LLM attention as graph structure | 94.53% mean on R8 (work in progress) |
| [ConfTM](https://github.com/AnwarDebes/ConfTM) | Conformal prediction sets and recourse for Tsetlin Machines | coverage 0.900 at a 0.9 target under drift (synthetic) |
| [FedTM](https://github.com/AnwarDebes/FedTM) | Federated Tsetlin Machine with differential privacy | 0.875 accuracy at ε = 4 (synthetic) |
| [RobTM](https://github.com/AnwarDebes/RobTM) | Certified flip-distance robustness and abstention | certificate in ~0.05 ms per sample |
| [CCTM](https://github.com/AnwarDebes/CCTM) | Training on counterfactual pairs, with recourse receipts | demographic parity gap 0.041 vs 0.181 (synthetic) |
| [HGTM](https://github.com/AnwarDebes/HGTM) · [RGTM](https://github.com/AnwarDebes/RGTM) | Hierarchical and recurrent Graph Tsetlin Machines | alpha, negative results documented |
| [lifelong-tm](https://github.com/AnwarDebes/lifelong-tm) | Continual learning for Tsetlin Machines | work in progress |
| [tm-llm-robustness-benchmark](https://github.com/AnwarDebes/tm-llm-robustness-benchmark) | One robustness harness for Tsetlin Machines and transformers | honest negative: the TM loses 27 points on counterfactual IMDb, BERT loses 2 |
| [clauseguard](https://github.com/AnwarDebes/clauseguard) · [clausegate](https://github.com/AnwarDebes/clausegate) · [clause86](https://github.com/AnwarDebes/clause86) | Clause-based audit layers for LLM claims, agent tool calls and hiring decisions | prototypes |
| [tsetlin-zoo](https://github.com/AnwarDebes/tsetlin-zoo) | A survey of Boolean clause learners | survey draft |

</details>

## Papers and technical reports

Every PDF lives next to the code that produced its numbers.

| | |
|---|---|
| [**CANDOR**](https://github.com/AnwarDebes/candor/blob/main/paper/candor.pdf) | The Explanation Is the Forward Pass: Interpretability by Construction with Certified Legible Bottlenecks |
| [**TRACE**](https://github.com/AnwarDebes/trace/blob/main/paper/trace.pdf) | A Tsetlin Runtime Assurance and Certification Engine for Interpretable, Tamper-Evident Guardrails on Agentic AI |
| [**THGTM**](https://github.com/AnwarDebes/THGTM/blob/main/paper/thgtm.pdf) | A Temporal Hierarchical Graph Tsetlin Machine with Echo-Trace Automata for Trajectory-Level Verification of Agentic AI |
| [**VERITAS**](https://github.com/AnwarDebes/veritas/blob/main/paper/veritas.pdf) | Formally Verified, Competence-Aware Interpretable Guardrails for Language Models |
| [**REINS**](https://github.com/AnwarDebes/reins/blob/main/paper/reins.pdf) | Model-Free, Certifying Least-Cost Repair of LLM-Agent Tool-Call Trajectories |
| [**LUCID**](https://github.com/AnwarDebes/lucid/blob/main/paper/lucid.pdf) | A Glass-Box, Safety-Shielded Agent for Open-World Interactive Reasoning on ARC-AGI-3 |
| [**DiTM**](https://github.com/AnwarDebes/DiTM/blob/main/paper/ditm.pdf) | A Discrete-Diffusion Tsetlin Machine for Interpretable Generative Modelling of Tabular Boolean Data |
| [**Multi-HGTM**](https://github.com/AnwarDebes/Multi-HGTM/blob/main/paper/multihgtm.pdf) | A Multi-View Hierarchical Graph Tsetlin Machine |
| [**ConfTM**](https://github.com/AnwarDebes/ConfTM/blob/main/paper/conftm.pdf) · [**FedTM**](https://github.com/AnwarDebes/FedTM/blob/main/paper/fedtm.pdf) · [**RobTM**](https://github.com/AnwarDebes/RobTM/blob/main/paper/robtm.pdf) · [**CCTM**](https://github.com/AnwarDebes/CCTM/blob/main/paper/cctm.pdf) | Conformal, federated, robust and counterfactual Tsetlin Machines |
| [**Clause-Driven-LLM**](https://github.com/AnwarDebes/Clause-Driven-LLM/blob/main/paper/report.pdf) | An Interpretable Tsetlin Machine Control Layer for LLM Agent Routing and Escalation |

<sub>Plus a technical report for each of the eight climate and health simulators below.</sub>

## Built after hours

| | |
|---|---|
| 🖥️ **[vsclaude](https://github.com/AnwarDebes/vsclaude)** | A native desktop IDE (Tauri, React, Rust) where Pixie, a pixel-art companion, acts out what your AI coding agent is really doing. House rule: the animation never lies. |
| 📱 **[PocketOS](https://github.com/AnwarDebes/PocketOS)** | A whole desktop environment inside your phone's browser: windows, a virtual filesystem, a terminal and a code editor. Offline and installable. |
| 📚 **[Mneme](https://github.com/AnwarDebes/Mneme-Education-Ecosystem)** | Textbook in, Anki deck out. Runs on local models, so nothing leaves your machine. |
| 🍪 **[cookie-galaxy](https://github.com/AnwarDebes/cookie-galaxy)** | A scroll-driven Three.js storefront for a fictional cookie brand, where the hero cookie is a planet. |
| ♟️ **[NEXUS](https://github.com/AnwarDebes/RL-CCA)** | An AlphaZero-style Chinese Checkers agent with Gumbel MCTS and a conv-transformer network. |
| 🌍 **Climate and health** | [PyroPredict](https://github.com/AnwarDebes/PyroPredict) · [ThermoGuard](https://github.com/AnwarDebes/ThermoGuard) · [SmokeShield](https://github.com/AnwarDebes/SmokeShield) · [PipeGuard](https://github.com/AnwarDebes/PipeGuard) · [HotCarWatch](https://github.com/AnwarDebes/HotCarWatch) · [HomeJoule](https://github.com/AnwarDebes/HomeJoule) · [SleepArchitect](https://github.com/AnwarDebes/SleepArchitect) · [CaffeineSense](https://github.com/AnwarDebes/CaffeineSense): physics-based simulators, most of them running right in your browser, each with a technical report. |

## Frequently avoided questions

**What is a Tsetlin Machine?**<br/>
A learning algorithm built from teams of tiny automata that decide which inputs belong in logical AND-clauses. The clauses then vote. Think of it as a parliament of very small, very honest robots: every decision comes with the clauses that voted for it.

**Why not just use a neural network?**<br/>
Sometimes I do. Then I distill what it learned into clauses and let it go. BERT once lent me its attention for a project; afterwards it was politely uninstalled.

**Do your experiments ever fail?**<br/>
Regularly, and I write it down. glassbox-lm registers its hypotheses before the runs and publishes the misses right next to the hits.

**What does a CFO do at an AI startup?**<br/>
Keeps the runway longer than the training runs.

**"Black boxes belong on airplanes"?**<br/>
Fun fact: flight recorders are painted bright orange so they are easy to find. Even aviation agrees that if it matters, it should be visible.

## Activity

<div align="center">

<img src="https://raw.githubusercontent.com/AnwarDebes/AnwarDebes/output/contrib-3d.svg" width="100%" alt="3D contribution calendar"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AnwarDebes/AnwarDebes/output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AnwarDebes/AnwarDebes/output/snake.svg"/>
  <img alt="A snake eating the contribution graph" src="https://raw.githubusercontent.com/AnwarDebes/AnwarDebes/output/snake.svg"/>
</picture>

</div>

## Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,pytorch,cpp,rust,ts,react,nextjs,tauri,threejs,fastapi,docker,linux,git,postgres&perline=14" alt="Python, PyTorch, C++, Rust, TypeScript, React, Next.js, Tauri, Three.js, FastAPI, Docker, Linux, Git, PostgreSQL"/>
</p>

<br/>

```text
IF   you.like(interpretable_ai) ∧ you.value(honest_results) ∧ ¬you.trust(black_boxes)
THEN star(⭐) ∧ follow(@AnwarDebes)
```

<div align="center">

<img src="https://komarev.com/ghpvc/?username=AnwarDebes&style=flat-square&color=7c3aed&label=profile+views" alt="Profile views"/>

</div>
