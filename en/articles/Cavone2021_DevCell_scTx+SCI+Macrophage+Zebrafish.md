---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
raw_data:
  - "ArrayExpress: E-MTAB-10379, E-MTAB-10390"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# A unique macrophage subpopulation signals directly to progenitor cells to promote regenerative neurogenesis in the zebrafish spinal cord

## Citation (NLM)
Cavone L, McCann T, Drake LK, Aguzzi EA, Oprișoreanu AM, Pedersen E, Sandi S, Selvarajah J, Tsarouchas TM, Wehner D, Keatinge M, Mysiak KS, Henderson BEP, Dobie R, Henderson NC, Becker T, Becker CG. A unique macrophage subpopulation signals directly to progenitor cells to promote regenerative neurogenesis in the zebrafish spinal cord. Dev Cell. 2021;56(11):1617-1630. doi:10.1016/j.devcel.2021.04.031

**DOI:** [https://doi.org/10.1016/j.devcel.2021.04.031](https://doi.org/10.1016/j.devcel.2021.04.031)

---

## Background

After central nervous system injury, anamniotes (fishes and amphibians) re-initiate neurogenesis from spinal progenitor cells, whereas mammals do not; mammalian spinal progenitors instead produce scar-related astrocytes. Activation of the innate immune system is known to promote regenerative neurogenesis in zebrafish, but a fundamental unresolved question is whether immune cells act indirectly by re-inducing developmental signaling pathways (Wnt, Fgf, Shh, dopamine), or whether they signal directly to progenitor cells via regeneration-specific mechanisms.

Tumor necrosis factor (Tnf/Tnf-a), mainly produced by macrophages at the injury site, is a candidate regeneration-specific signal. The authors test whether a specific pro-regenerative macrophage subtype signals directly to ependymo-radial glia (ERG) spinal progenitors through Tnf to switch them from oligodendrogenesis to neurogenesis after injury.

---

## Key Experiment Methods

1. Single-cell RNA-seq of FACS-isolated her4.3:GFP ERG progenitor cells at 24 hpl vs. uninjured larval (3 dpf) zebrafish (2,477 unlesioned, 1,203 lesioned cells), and scRNA-seq of mpeg1:GFP+ macrophage-lineage cells from the injury site (3,767 unlesioned, 4,579 lesioned cells), with unsupervised clustering and differential expression.
2. Triple in vivo labeling of Tnf protein (antibody), macrophages (mpeg1:GFP), and motor neuron progenitor ERGs (olig2:DsRed) to assess spatial proximity.
3. Immune manipulation with dexamethasone (immunosuppression) and LPS (immune augmentation), with qRT-PCR of tnfa and hdac1 and EdU-based counts of proliferating olig2:GFP+ progenitors and new mnx1:GFP+ motor neurons.
4. Loss-of-function of Tnf signaling: pomalidomide (Tnf-release inhibitor), acute tnfa gRNA/Cas9, stable tnfa mutant line, and tnfrsf1a gRNA, scored by motor neuron and HuC+ neurogenesis.
5. Ex vivo exposure of purified her4.3:GFP+ ERGs to recombinant zebrafish and human TNF, with AP-1 inhibitor SR11302, measuring mnx1 and hdac1 expression.
6. Hdac1 functional tests: pan-Hdac inhibitor TSA and Hdac1-selective mocetinostat, plus a conditional cell-type-specific Tg(her4.3:TetA;TetRe:YFP-dnhdac1) dominant-negative line under doxycycline.

---

## Results

- scRNA-seq showed injury drives a switch from oligodendrogenesis to neurogenesis in ERG progenitors (~480% relative increase in neuroblasts; upregulation of gap43, sox11b, atf3; downregulation of plp1b, mbpa, mag).
- Tnf-signaling genes were enriched and upregulated specifically in progenitors after injury: AP-1 components fosl2 and junbb, the Tnf-regulated gene tnfaip2b, and the receptor tnfrsf1a (tnfrsf1a+ progenitors rose from 18% to 45%); tnfa/b ligands were absent from progenitors, arguing against autocrine signaling. NF-kB1 was essentially undetectable.
- tnfa was mainly expressed by blood-derived (phagocytic) macrophages rather than microglia; a lesion-activated fth1a+ tnfa+ macrophage subpopulation expanded after injury (19%→55%), showed high cathepsin expression and a mix of M1/M2 markers, defining a pro-regenerative macrophage subtype.
- In vivo, macrophages and granular Tnf protein concentrated within 20 um of olig2:DsRed+ ERGs, confirming progenitors are exposed to macrophage-derived Tnf.
- Manipulating immunity scaled neurogenesis with Tnf: dexamethasone reduced tnfa, hdac1, progenitor proliferation, and motor neurons, while LPS increased hdac1 (1.7-fold), motor neuron progenitors (+57.5%), and new motor neurons (+104%). LPS alone did not augment constitutive neurogenesis in uninjured larvae.
- Blocking Tnf signaling (pomalidomide, tnfa gRNA, tnfa mutant) reduced regenerative neurogenesis by ~33-53%; tnfrsf1a knockdown reduced lesion-induced motor neurons ~46-51% but did not affect developmental neurogenesis, showing the receptor is specifically required for regeneration.
- Ex vivo, both zebrafish and human TNF directly upregulated mnx1 and hdac1 in isolated ERGs; the AP-1 inhibitor SR11302 abolished Tnf-induced hdac1, establishing an AP-1-dependent mechanism.
- Hdac1 function was necessary: TSA and mocetinostat reduced progenitor proliferation and new motor neurons and blunted the LPS effect; progenitor-specific dominant-negative hdac1 reduced new HuC+ neurons by ~43% after injury. In situ hybridization confirmed injury-induced hdac1 upregulation in ventricular ERGs in both larval and adult (2-week) spinal cord.

---

## Perspective

This study establishes a direct, regeneration-specific signaling axis in which lesion-activated pro-regenerative macrophages secrete Tnf that acts on ERG spinal progenitors via Tnfrsf1a, activating AP-1 to upregulate hdac1 and drive motor neuron neurogenesis after spinal cord injury. Crucially, tnfrsf1a is dispensable for developmental neurogenesis but required for regenerative neurogenesis, and human TNF is sufficient to drive isolated ERGs toward neurons, highlighting translational relevance for the regeneration-deficient mammalian spinal cord. Limitations, acknowledged by the authors, include incomplete inhibition (~50%) implying additional macrophage-derived and developmental signals, and the need for further scRNA-seq and direct transcription-factor binding assays to fully map intracellular ERG signaling. Because enhancing extracellular Tnf broadly may harm other aspects of repair, the identified downstream nodes (AP-1, Hdac1) are proposed as more precise therapeutic targets.

## Data Availability

**Raw data generated by this study:**
- ArrayExpress: E-MTAB-10379, E-MTAB-10390


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
