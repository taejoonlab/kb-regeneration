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
The axolotl (*Ambystoma mexicanum*) can fully regenerate its injured spinal cord, making it a unique model for successful spinal cord regeneration. Ependymal cells lining the central canal retain neural stem cell potential and, after tail amputation, reactivate a developmental-like program: they switch from slow neurogenic divisions (cell cycle ~14.2 days) to fast proliferative divisions (~4.9 days). Prior work established that cell cycle acceleration is the main driver of regenerative outgrowth and identified a high-proliferation zone that emerges ~4 days post-amputation within ~800 μm of the injury and shifts posteriorly as the cord grows.

What remained unknown was the spatiotemporal nature of the signal producing this precise proliferation pattern. Drawing on the idea that developmental patterning can arise from morphogenetic signals spreading from localized sources, the authors ask whether amputation triggers a signal that propagates along the injured cord to recruit resident cells into an accelerated cycle.

---

## Key Experiment Methods
1. **1D mathematical model of the ependymal tube**: cells modeled as rigid spheres along the anterior-posterior (AP) axis; cycling vs. quiescent (growth fraction), with a "cell pushing mechanism" whereby dividing daughters displace posterior cells.
2. **Regeneration model with a recruitment signal**: amputation releases a signal spreading anteriorly at constant speed, recruiting cells within λ μm up to time τ; recruited cells shorten G1 (partial skipping/synchronization) and S (proportional mapping) phases, while G2+M are unchanged.
3. **Parameter inference**: Approximate Bayesian Computation (pyABC) fitting the model recruitment limit ξ(t) to the previously measured experimental proliferation switchpoint (Rost et al., 2016). Fixed cell-phase parameters taken from Rodrigo Albors et al., 2015.
4. **In silico perturbations**: varying τ and λ; blocking cell cycle acceleration; isolating contributions of G1-only vs. S-only shortening.
5. **AxFUCCI**: de novo axolotl-specific FUCCI reporter built from axolotl Cdt1[aa1-128]-mVenus and Gmnn[aa1-93]-mCherry, co-expressed via CAGGs promoter and T2A peptide.
6. **AxFUCCI validation**: live imaging of electroporated AL1 cells; flow-cytometry DNA content; EdU incorporation; co-staining with NeuN (neurons, G0) and Sox2 (ependymal cells).
7. **In vivo measurement**: stable transgenic AxFUCCI axolotls; tail amputation; optical clearing and lightsheet wholemount imaging with digital re-sectioning; quantification of G0/G1- and S/G2-AxFUCCI cells in 100 μm bins to detect the recruitment zone and test cell cycle synchrony.

---

## Results
- The model reproduced the experimental switchpoint with best-fit parameters N0 = 196 ± 2 cells, λ = 828 ± 30 μm, and τ = 85 ± 12 hours — i.e., a signal acting for ~85 h post-amputation, recruiting cells within ~828 μm anterior to the amputation plane.
- The parameterized model quantitatively predicted the in vivo spinal cord outgrowth kinetics and reproduced scaling behavior and clonal trajectories consistent with prior experimental data.
- Blocking cell cycle acceleration reduced predicted outgrowth to 694 ± 77 μm vs. the observed 1127 ± 103 μm at day 6, matching experimental outgrowth in Sox2 knock-out axolotls where acceleration does not occur.
- Modeling dissection: shortening of S phase alone explains the explosive outgrowth up to day 4; G1 shortening alone has minimal early effect; both S and G1 shortening are needed to match outgrowth from day 5 on. S phase shortening dominates the early regenerative response.
- AxFUCCI faithfully discriminated cell cycle phases in vivo: G0/G1 (mVenus only), S/G2 (mCherry only), and transitions (double positive); 100% of AxFUCCI-expressing neurons were mVenus-positive, while Sox2+ ependymal cells expressed both.
- In vivo, S/G2-AxFUCCI cells increased sharply at the amputation site and propagated anteriorly, forming a recruitment zone detectable statistically only at days 4 and 5. The measured AP border (-717 ± 272 μm at day 4; -446 ± 112 μm at day 5) overlapped model predictions within 2 sigma, confirming both the predicted timing (~85 h) and size of the recruitment zone.
- Regenerating ependymal cells showed high cell cycle synchrony with one another, consistent with the model's G1-skipping (synchronization) prediction.

---

## Perspective
This study integrates tightly coupled mathematical modeling and a purpose-built in vivo reporter (AxFUCCI) to characterize when and where a recruitment signal drives ependymal cell proliferation during axolotl spinal cord regeneration. Its significance lies in quantitatively defining the spatiotemporal window (~85 h, ~828 μm) and mechanism (predominant S-phase shortening early, with G1 shortening and cell cycle synchronization) of the regenerative response, and in delivering AxFUCCI as a reusable tool for studying proliferation in development and regeneration. Limitations include the reliance on a 1D idealization of the ependymal tube and inference of an as-yet-unidentified signal — the work localizes where and when to search for the signal but does not identify its molecular identity. Future directions include identifying the recruitment signal(s) and applying AxFUCCI to further dissect proliferation dynamics in vivo.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
