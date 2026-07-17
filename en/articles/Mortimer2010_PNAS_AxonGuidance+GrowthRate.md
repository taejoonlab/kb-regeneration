---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
---

# Axon guidance by growth-rate modulation

## Citation (NLM)
Mortimer D, Pujic Z, Vaughan T, Thompson AW, Feldner J, Vetter I, Goodhill GJ. Axon guidance by growth-rate modulation. Proc Natl Acad Sci U S A. 2010 Mar 16;107(11):5202-5207. doi:10.1073/pnas.0909254107

**DOI:** [https://doi.org/10.1073/pnas.0909254107](https://doi.org/10.1073/pnas.0909254107)

---

## Background

Wiring of the developing nervous system depends on the guidance of axons by molecular gradients, and defective wiring underlies several nervous system disorders and contributes to injury outcomes. It is generally assumed that the defining signature of gradient guidance is immediate and biased turning of the axon tip toward (or away from) the gradient. However, while such biased turning is reliably seen in 2D in vitro assays exposed to steep gradients, 3D assays that more closely mimic the in vivo environment often fail to show consistent turning; instead, the collective growth of an axon population is biased by the gradient.

This study asks how a growth cone converts a decision about gradient direction into directed motion. Combining precisely controlled gradient experiments with computational modeling, the authors propose growth-rate modulation as an alternative guidance mechanism that does not require biased turning, and they test which mechanism dominates as a function of gradient steepness.

---

## Key Experiment Methods

1. Printing (collagen gel pump) assay: ~2,500 rat P2 DRG explants embedded in 3D collagen gels and exposed to precisely printed exponential NGF gradients (varying steepness and absolute concentration) for 48 h, then immunostained for beta3-tubulin.
2. Automated turning quantification using a steerable ridge filter to assign a turning ratio (TR = (U-D)/(U+D)) to each explant, validated against human scoring and curvature-based measures; guidance ratio (GR = (H-L)/(H+L)) used for outgrowth asymmetry.
3. Zigzag explant patterning experiment to distinguish tropic (direction-dependent) from trophic (concentration-dependent) responses.
4. Delayed gradient application (up to 24 h) and time-lapse imaging to rule out early intra-explant turning and tension-driven straightening.
5. Computational modeling: extension of a prior Bayesian gradient-sensing model coupled to (a) a biased random-walk turning model vs. (b) a growth-rate modulation model; simulated explants matched to experimental noise/n.
6. Pipette (growth cone turning) assay with rat SCG neurites in 2D and adapted to 3D collagen, comparing turning and growth rates with pipette placed in front vs. behind the growth cone.

---

## Results

- DRG explants displayed strongly asymmetric neurite outgrowth (high GR) but near-zero turning ratios, even where outgrowth was strongly biased up-gradient.
- The zigzag experiment showed outgrowth depended on gradient direction rather than absolute concentration (group 1 ~= group 3 > group 2 ~= group 4), consistent with a tropic and inconsistent with a purely trophic response.
- Delaying gradient application did not induce turning, and time-lapse imaging showed instantaneous and final trajectories were similar, ruling out later straightening by tension.
- Simulations confirmed the turning-quantification method could detect biased turning when present; the pure biased-turning model reproduced the GR but produced TR values far larger than observed experimentally.
- The growth-rate modulation model (speed modulated along the front-to-back axis by SNR, with turning direction random) reproduced both the GR and the small TR of the experimental data.
- In the 2D pipette assay with steep localized gradients, SCG neurites turned toward NGF, and growth rate was independent of whether the pipette was in front or behind, indicating turning dominates in steep gradients.
- Adapting the pipette assay to 3D collagen (changing gradient parameters, not substrate) restored turning, showing gradient steepness rather than substrate determines the dominant strategy.

---

## Perspective

The work establishes growth-rate modulation as a distinct readout mechanism for gradient guidance, complementing immediate biased turning, and shows the two operate on a continuum governed by gradient steepness. The authors argue that comparing concentrations over the long front-to-back axis of the axon (potentially between growth cone and soma) is far more reliable than comparing across the narrow growth cone width in shallow gradients, explaining why growth-rate modulation dominates there. A key implication is that a lack of biased turning does not imply an absence of guidance. Limitations include that the comparison distance underlying growth-rate modulation could not be resolved (folded into a proportionality constant), and the two mechanisms may also vary with growth cone size across species/assays. This is relevant to CNS wiring and to strategies for directing axon regrowth after injury.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
