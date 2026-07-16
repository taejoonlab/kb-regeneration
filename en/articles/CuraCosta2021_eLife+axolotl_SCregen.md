---
tags: [2026-07]
extract: 2026-07-16
---

# Spatiotemporal control of cell cycle acceleration during axolotl spinal cord regeneration

## Citation (NLM)
Cura Costa E, Otsuki L, Rodrigo Albors A, Tanaka EM, Chara O. Spatiotemporal control of cell cycle acceleration during axolotl spinal cord regeneration. eLife. 2021;10:e55665. doi:10.7554/eLife.55665

**DOI:** [https://doi.org/10.7554/eLife.55665](https://doi.org/10.7554/eLife.55665)

---

## Background
The axolotl (*Ambystoma mexicanum*) uniquely regenerates its injured spinal cord, making it a model for studying successful CNS regeneration. Ependymal cells lining the central canal retain neural stem cell potential throughout life and drive this response. Prior work by the authors showed that tail amputation reactivates a developmental-like program in ependymal cells: they switch from slow, neurogenic divisions (cell cycle ~14.2 days) to fast, proliferative divisions (~4.9 days), and a high-proliferation zone emerges ~4 days post-amputation within ~800 μm of the injury, shifting posteriorly as the cord grows.

What underlies this precise spatiotemporal proliferation pattern remained unknown. The authors hypothesized that amputation triggers a signal spreading along the injured cord that recruits resident cells and accelerates their cell cycle, analogous to morphogenetic signals spreading from localized sources during development.

---

## Key Experiment Methods
1. Developed a 1D mathematical/agent-based model of the spinal cord anterior-posterior (AP) axis, modeling ependymal cells as rigid spheres that are cycling or quiescent, incorporating a "cell pushing" mechanism where daughter cells displace posterior neighbors.
2. Modeled amputation as release of a signal spreading anteriorly at constant speed, recruiting cells within a maximal distance λ over a maximal time τ, shortening recruited cells' G1 (partial skipping) and S (proportional mapping) phases.
3. Fitted free parameters (N0, λ, τ) to the experimentally measured proliferation switchpoint using Approximate Bayesian Computation (pyABC framework).
4. Ran in silico perturbations: blocking cell cycle acceleration, isolating S-phase-only vs G1-phase-only shortening, and varying λ and τ.
5. Designed and generated AxFUCCI — an axolotl-specific Fluorescent Ubiquitination-based Cell Cycle Indicator — using axolotl Cdt1[aa1-128]-mVenus and Gmnn[aa1-93]-mCherry fragments co-expressed via T2A under the CAGGs promoter; generated stable transgenic lines via I-SceI transgenesis.
6. Validated AxFUCCI with live imaging (AL1 cells), flow-cytometry DNA content, EdU pulse labeling, and co-staining with NeuN (neurons, G0) and Sox2 (ependymal cells).
7. Optically cleared and light-sheet imaged whole regenerating tails to measure the recruitment zone in vivo, quantifying G0/G1- vs S/G2-AxFUCCI cells in 100 μm AP bins.

---

## Results
- The model reproduced the experimental proliferation switchpoint with best-fitting parameters N0 = 196 ± 2 cells, λ = 828 ± 30 μm, and τ = 85 ± 12 hours — i.e., a signal acting for ~85 h post-amputation recruiting cells within ~828 μm.
- The parameterized model quantitatively predicted the in vivo spinal cord outgrowth kinetics and showed scaling behavior (clones preserve relative AP position), consistent with earlier cell-trajectory data.
- Blocking cell cycle acceleration reduced predicted outgrowth to 694 ± 77 μm vs the observed 1127 ± 103 μm at day 6, matching experimental outgrowth in Sox2 knockout axolotls (which fail to accelerate the cell cycle).
- In silico, shortening of S phase alone explained the explosive outgrowth up to day 4, whereas G1 shortening had little early effect; both S and G1 shortening were required to match outgrowth from day 5 onward. S-phase shortening dominates the initial regenerative response.
- AxFUCCI faithfully discriminated cell cycle phases in axolotl: G0/G1 (mVenus only), S/G2 (mCherry only), and G1/S plus G2/M transitions (double positive); 100% of AxFUCCI+ neurons were mVenus-only, while Sox2+ ependymal cells showed all combinations.
- In vivo, AxFUCCI confirmed the recruitment zone: S/G2 cells increased sharply at the amputation site then propagated anteriorly, with a statistically detectable anterior/posterior border appearing between days 3 and 4 (accommodating the 85 h prediction). Measured AP borders (−717 ± 272 μm at day 4; −446 ± 112 μm at day 5) overlapped model predictions within 2 sigma.
- The model's G1-shortening mechanism predicted cell cycle synchrony among recruited ependymal cells, which was observed in vivo.

---

## Perspective
This work integrates quantitative modeling tightly with experiment to define *when* (~85 h) and *where* (~828 μm) an injury signal must act to reproduce axolotl spinal cord regenerative outgrowth, and identifies S-phase shortening as the dominant early driver of cell cycle acceleration. The newly developed AxFUCCI transgenic line is a broadly useful tool for visualizing cell cycle dynamics in vivo during axolotl development and regeneration. Limitations include the 1D abstraction of the ependymal tube and the fact that the recruiting signal's molecular identity remains unknown — the study provides spatiotemporal coordinates for where to search for it. Future work should identify the signal and test the G1/S shortening mechanism at molecular resolution.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
