---
tags: [2026-07]
extract: 2026-07-16
---

# A CRISPRi/a platform in human iPSC-derived microglia uncovers regulators of disease states

## Citation (NLM)
Dräger NM, Sattler SM, Huang CT, Teter OM, Leng K, Hashemi SH, Hong J, Aviles G, Clelland CD, Zhan L, Udeochu JC, Kodama L, Singleton AB, Nalls MA, Ichida J, Ward ME, Faghri F, Gan L, Kampmann M. A CRISPRi/a platform in human iPSC-derived microglia uncovers regulators of disease states. Nat Neurosci. 2022;25(9):1149-1162. doi:10.1038/s41593-022-01131-4

**DOI:** [https://doi.org/10.1038/s41593-022-01131-4](https://doi.org/10.1038/s41593-022-01131-4)

---

## Background

Microglia are central to brain development and homeostasis and are emerging as key drivers of neurological diseases, including Alzheimer's disease (AD), where disease-associated genetic variants likely act in microglia. To understand and therapeutically target the role of microglia in disease, it is necessary to bridge the gap between disease-associated genetic variants and changes in microglial function. A major challenge is that microglia adopt many distinct functional states in health and disease, and the molecular mechanisms regulating these states are not systematically understood.

CRISPR-based functional genomics (pooled CRISPR interference, CRISPRi, and CRISPR activation, CRISPRa) combined with iPSC technology enables scalable, cell-type-specific genetic screens in human cells. However, such screens had not been implemented in iPSC-derived microglia because mature microglia are difficult to transduce with lentivirus and most differentiation protocols are lengthy, creating population bottlenecks that skew sgRNA library representation. This study develops a rapid transcription-factor-based microglia differentiation protocol integrated with inducible CRISPRi/a to enable pooled genetic screens in human microglia.

---

## Key Experiment Methods

1. **iTF-Microglia generation**: an iPSC line with doxycycline-inducible expression of six transcription factors (PU.1, MAFB, CEBPα, CEBPβ, IRF5, IRF8) integrated at the AAVS1 and CLYBL safe-harbor loci, differentiated into microglia-like cells in an 8-day, three-step protocol with GM-CSF, IL-34, M-CSF and TGF-β.
2. **Functional characterization**: phagocytosis of fluorescent beads and rat synaptosomes (± Cytochalasin D), LPS stimulation with RNA-seq and cytokine array, and coculture with iPSC-derived glutamatergic neurons.
3. **Inducible CRISPRi/a**: constitutive and inducible (DHFR-degron, TMP-stabilized) dCas9-BFP-KRAB (CRISPRi) and dCas9-VPH (CRISPRa) integrated at CLYBL; validated by TFRC knockdown and CXCR4 overexpression.
4. **Pooled screens of the "druggable genome"** (~2,325 genes, 5 sgRNAs/gene + 500 NTC): survival/proliferation screen (day 0 vs. day 15), microglial activation screen (FACS on cell-surface CD38), and parallel CRISPRi/CRISPRa phagocytosis screens (FACS on pHrodo-synaptosome uptake).
5. **CROP-seq screen**: sgRNA library targeting 39 hit genes coupled to scRNA-seq of 58,302 iTF-Microglia on day 8 to link genetic perturbations to transcriptional states.

---

## Results

- The 8-day iTF-Microglia protocol produced ramified microglia-like cells expressing canonical markers (GPR34, IBA1, P2RY12, CSF1R, CX3CR1, TREM2); transcriptomes were comparable to other iPSC-derived microglia protocols and compatible with large-scale pooled screens without bottlenecks.
- iTF-Microglia were functional: they phagocytosed synaptosomes (actin-dependent), responded to LPS with an ameboid morphology and induction of immune genes (C3, CXCL10, IL32, SAA1, NF-κB) and cytokine secretion (IL-6, IL-8, CXCL10), and were cocultured with iNeurons.
- **Survival screen**: knockdown of CSF receptor family genes (CSF1R, CSF2RB, CSF2RA) strongly and specifically reduced microglial (not neuronal or iPSC) survival; CSF1R essentiality became pronounced from day 8. Genes affecting survival differed across microglia, neurons and iPSCs. CDK8 and TGFBR2 knockdown disrupted microglial differentiation.
- **Activation (CD38) screen**: knockdown of transcriptional regulators CDK12 and MED1, and of mitochondrial Complex I subunits (NDUFA8, NDUFS5), increased CD38 surface levels.
- **Phagocytosis screens**: little overlap between CRISPRi and CRISPRa hits. PFN1 (an ALS gene) had opposing effects; CSF1R and INPP5D knockdown increased phagocytosis; CD209 overexpression greatly increased synaptosome phagocytosis with substrate specificity. PFN1 overexpression increased F-actin and altered immune/AD-risk gene expression.
- **CROP-seq**: iTF-Microglia adopted a spectrum of transcriptional states mirroring those in human brains; the screen identified regulators of specific states. A disease-associated state characterized by osteopontin (SPP1) expression was selectively depleted by CSF1R inhibition.

---

## Perspective

This work establishes a scalable, rapid and genetically tractable human iPSC-microglia platform that overcomes prior barriers to CRISPR screening in this cell type. By combining pooled loss- and gain-of-function screens with single-cell readouts, it systematically links genetic perturbations to microglial survival, activation, phagocytosis and, importantly, discrete disease-relevant transcriptional states—including an SPP1+ state depleted by CSF1R inhibition, connecting a druggable target to a specific microglial state.

Limitations include the imperfect inducible CRISPRi system (e.g., PICALM was knocked down by the constitutive but not the inducible system), transcriptomes that remain distinct from primary human microglia (a general caveat for iPSC-derived microglia), and reliance on transcription-factor-forced differentiation rather than ontogeny. The platform provides a resource for functional characterization and therapeutic targeting of microglial states and, given the shared role of microglia across CNS injury and neurodegeneration, is relevant to CNS repair and regeneration research.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
