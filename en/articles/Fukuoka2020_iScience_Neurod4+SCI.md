---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p03.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Neurod4 converts endogenous neural stem cells to neurons with synaptic formation after spinal cord injury

## Citation (NLM)
Fukuoka T, Kato A, Hirano M, Ohka F, Aoki K, Awaya T, et al. Neurod4 converts endogenous neural stem cells to neurons with synaptic formation after spinal cord injury. iScience. 2021;24(2):102074. doi:10.1016/j.isci.2021.102074

**DOI:** [https://doi.org/10.1016/j.isci.2021.102074](https://doi.org/10.1016/j.isci.2021.102074)

---

## Background
Traumatic spinal cord injury (SCI) frequently causes permanent and severe disability, in part because the human spinal cord has limited capacity to repair and regenerate neural tissue. After SCI, ependymal cells lining the central canal (CC) can dedifferentiate into radial glia and neural stem cells (NSCs) that migrate to the injury site, but they predominantly redifferentiate into astrocytes and oligodendrocytes (contributing to the glial scar) rather than neurons. The authors hypothesized that reprogramming these endogenous injury-induced NSCs toward a neuronal fate could achieve nerve regeneration.

Xenopus laevis tadpoles, which recover nearly completely after SCI (a capacity lost after metamorphosis into froglets), provide a powerful comparative model. Leveraging whole-transcriptome (RNA-seq) data comparing regenerative (tadpole) versus non-regenerative (froglet) stages, the authors screened basic-helix-loop-helix (bHLH) transcription factors and identified Neurod4 as the most promising neuroregenerative candidate for mammalian SCI.

---

## Key Experiment Methods
1. Comparative transcriptome analysis of 107 bHLH transcription factor genes between regenerative and non-regenerative stages in injured X. laevis, plus qPCR quantification of candidate genes (Neurod4, Neurod1, Atoh1, Neurog2, Ascl1) in a mouse SCI model.
2. Construction of a pseudotyped retroviral vector with the neurotropic lymphocytic choriomeningitis virus (LCMV) envelope to selectively transduce dividing (activated) NSCs; delivered via cisterna magna injection with AcGFP1/tauAcGFP1 reporters and murine Neurod4 (neurod4.L/.S orthologs).
3. Validation of NSC tropism using BrdU labeling and Nestin/Sox-2 immunostaining around the central canal after SCI.
4. Neuronal differentiation assessed by DCX (immature) and NeuN (mature) markers; neuronal subtype identity by in situ hybridization (Slc17a6/VGlut2 excitatory; Slc6a5/GlyT2 inhibitory) and ChAT immunohistochemistry (motor neurons); qPCR confirmation.
5. Synapse analysis with Syp-AcGFP1 (presynaptic) and PSD-95/GlyR (postsynaptic) markers; structured illumination microscopy for pre-/postsynaptic distances; corticospinal tract tracing via AAV-Syn-pal-mKate2 / Syp-mKate2 into M1 cortex with tissue clearing.
6. GFAP immunostaining/qPCR for glial scar assessment; hindlimb locomotor recovery scored by Basso Mouse Scale (BMS) over 6 weeks.

---

## Results
- In X. laevis, Neurod4 mRNA was markedly upregulated at 2 days post-injury (DPI) during the regenerative stage, coinciding with the rise of the stem cell marker Sox-2; its acute-phase expression was substantially higher than in injured mice.
- In mice, Neurod4 showed no injury-induced increase, suggesting exogenous Neurod4 could provide a complementary regenerative effect.
- The LCMV-pseudotyped retrovirus selectively transduced BrdU+/Nestin+/Sox-2+ activated NSCs (~70% Nestin+ around CC at 7 DPI) derived from dedifferentiated ependymal cells, and did not infect ependymal cells themselves.
- Neurod4 introduction progressively increased NeuN+ neurons among transduced cells (46.7% vs 20.7% control at 42 DPI, p<0.0001) and DCX+ immature neurons at 5 DPI.
- Neurod4-expressing cells differentiated into excitatory (Slc17a6/VGlut2, 49%), inhibitory (Slc6a5/GlyT2, 34%), and other/motor (ChAT, 17%) neurons.
- Neurod4-induced excitatory neurons projected to PSD-95+ subsynaptic domains of motor neurons at L2-L5; inhibitory neurons projected to GlyR+ domains at the epicenter, indicating functional synapse formation (pre-/postsynaptic distances 202 nm excitatory, 135 nm inhibitory).
- Neurod4 suppressed GFAP+ astrocyte/glial scar formation (GFAP+ cells fell to ~10% vs rose to ~40% in control by 42 DPI) and promoted corticospinal axon regrowth beyond the injury site.
- Neurod4-treated mice showed significant BMS locomotor recovery (4.3 vs 0.6 at 6 weeks post-injury, p=0.0080).

---

## Perspective
This study demonstrates a gene-therapy strategy fundamentally distinct from exogenous stem cell transplantation: a neuroregenerative bHLH factor (Neurod4), identified through cross-species comparison with the highly regenerative Xenopus, is delivered directly into endogenous ependymal-derived activated NSCs already present in the injured cord using an NSC-tropic LCMV-pseudotyped retrovirus. Reprogramming these cells toward excitatory, inhibitory, and motor neuron fates produced relay neurons that formed synapses onto lumbar motor neurons, suppressed glial scarring as a secondary effect, enabled corticospinal axon regrowth, and improved hindlimb locomotion.

Limitations acknowledged by the authors include: reliance on a mouse model only; the need to confirm safety/efficacy of the retroviral vector (integration/insertional mutagenesis risk, LCMV pathogenicity); histological rather than electrophysiological confirmation of functional circuits; and species differences in corticomotoneuronal connectivity (disynaptic in rodents vs monosynaptic in primates). Recovery was incomplete, indicating the regenerated network remains unrefined. Future work requires a treatment protocol translatable to patients and electrophysiological validation of the new circuits.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
