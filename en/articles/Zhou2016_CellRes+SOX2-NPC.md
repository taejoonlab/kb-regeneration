---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
raw_data:
  - "GEO: GSE69476, GSE69479"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Comprehensive profiling reveals mechanisms of SOX2-mediated cell fate specification in human ESCs and NPCs

## Citation (NLM)
Zhou C, Yang X, Sun Y, Yu H, Zhang Y, Jin Y. Comprehensive profiling reveals mechanisms of SOX2-mediated cell fate specification in human ESCs and NPCs. Cell Res. 2016;26(2):171-189. doi:10.1038/cr.2016.15

**DOI:** [https://doi.org/10.1038/cr.2016.15](https://doi.org/10.1038/cr.2016.15)

---

## Background

Cell type-specific master transcription factors establish and maintain cell identity by directing specific gene regulatory networks, and the same factor can exert distinct roles across cell types and developmental stages. SOX2 is a pioneer factor essential in embryonic stem cells (ESCs) and in neural progenitor cells (NPCs), yet most mechanistic work had been done in mouse cells, and its role in human ESCs (hESCs) and human NPCs (hNPCs) remained poorly defined and controversial. Reports differed on whether canonical Wnt signaling promotes self-renewal or differentiation of hESCs, and the relationship between SOX2 and Wnt signaling in human cells was unresolved.

This study performs comprehensive genome-wide profiling — comparing SOX2 DNA-binding, SOX2-regulated genes, and the SOX2 protein interactome between genetically identical hESCs and hESC-derived hNPCs — to define how SOX2 controls cell fate specification along the neural differentiation trajectory, a topic directly relevant to neural stem/progenitor biology and CNS development.

---

## Key Experiment Methods

1. Generation and full characterization of hNPCs from hESCs (H9 and SHhES2 lines).
2. ChIP-seq of SOX2 and Pol II in genetically identical hESCs and hNPCs, integrated with published histone-modification ChIP-seq (H3K4me3, H3K4me1, H3K27me3, H3K27ac) to classify binding sites into active/poised/repressed promoters and enhancers.
3. RNA-seq of SOX2-depleted (siRNA) hESCs and hNPCs (with SOX3 co-knockdown in hESCs to counter compensation) to identify direct functional targets by combining ChIP-seq and RNA-seq.
4. Time-course ChIP-qPCR and RT-qPCR of Notch pathway components and proneural genes (DLL1, HES5, JAG1, HES3, NEUROD1, NEUROG1) during neural differentiation.
5. Functional Wnt assays: Western blot (β-catenin, p-LRP6), nuclear fractionation, TOP/FOP luciferase reporter, and pharmacological modulation (CHIR99021, Wnt3A, IWR1-e, IWP2, DKK1, Noggin).
6. Rescue experiments dissecting the Wnt modulators SFRP2 and WLS (siRNA/shRNA knockdown, recombinant SFRP2 supplementation).
7. SOX2 protein interactome by immunoprecipitation + mass spectrometry; co-IP validation of SOX2–H2A.Z and H2A.Z–PRC2 interactions; ChIP-qPCR of H2A.Z, EZH2, and histone marks at target promoters (WLS, WNT5B).
8. Cross-species comparison with published mouse ESC/NPC SOX2 ChIP-seq.

---

## Results

- SOX2 bound 17,992 sites in hESCs and 67,021 in hNPCs (~50% of hESC peaks overlapping hNPCs); most peaks were promoter-distal. Promoter binding was associated with active marks and self-renewal/housekeeping processes, while poised enhancer binding was largely cell-type-specific and linked to developmental (including CNS) programs.
- SOX2 occupies a poised proneural transcription program in hESCs; along neural differentiation, SOX2 increasingly bound promoters of Notch pathway components (DLL1, HES5, JAG1, HES3, but not HES1), placing SOX2 upstream of Notch signaling in neural differentiation and hNPC maintenance.
- SOX2 controls four cell type-/stage-dependent programs: (a) a common self-renewal-safeguarding program, (b) a proneural program in hESCs, (c) a hESC-specific repression of non-neural (mesoderm/endoderm) lineages, and (d) a CNS differentiation program in hNPCs.
- In hESCs, SOX2 represses non-neural lineages by inhibiting canonical Wnt signaling: SOX2/3 knockdown rapidly activated Wnt (β-catenin, p-LRP6, TOP/FOP, Wnt targets); Wnt inhibitor IWR1-e (but not BMP inhibitor Noggin) abrogated the resulting lineage-marker upregulation, independent of OCT4 levels.
- In hNPCs, SOX2 both inhibits canonical Wnt signaling and directly activates proneural genes (NEUROD1, NEUROG1) to initiate neuronal differentiation; the inhibitory role of Wnt in human neuronal differentiation contrasts with its inductive role in mouse adult neurogenesis, indicating species-specific function.
- SOX2 inhibits the Wnt pathway by direct transcriptional control of two modulators — the Wnt antagonist SFRP2 and the Wnt-secretion protein WLS; combined SFRP2 supplementation + WLS knockdown rescued SOX2/3-knockdown differentiation phenotypes.
- SOX2 interacts with histone variant H2A.Z (68 partners in hESCs, 191 in hNPCs; many splicing/chromatin factors) to recruit PRC2 and poise bivalent developmental genes; SOX2/3 knockdown reduced H2A.Z and EZH2 occupancy and H3K27me3 at target promoters.
- Cross-species comparison revealed low conservation of SOX2-binding profiles (most peaks unique per species), with retained promoter binding underlying conserved stem-cell maintenance and divergent distal binding underlying species-specific developmental regulation.

---

## Perspective

This work provides mechanistic evidence that a core pluripotency/neural master factor, SOX2, specifies cell fate by controlling distinct signaling pathways and by recruiting a histone variant to modify chromatin state. It identifies WLS and SFRP2 as novel direct SOX2 targets mediating Wnt inhibition in hESCs, positions SOX2 upstream of Notch signaling in neural differentiation, and establishes SOX2–H2A.Z–PRC2 poising of bivalent developmental genes. For neural stem/progenitor biology, it clarifies how SOX2 primes and then executes neuronal differentiation from human NPCs, with a Wnt role opposite to mouse — underscoring the importance of studying human cells directly.

Limitations include reliance on in vitro hESC/hNPC models (not in vivo CNS), use of siRNA/shRNA knockdown with attendant off-target and compensation issues (necessitating SOX2/3 co-knockdown), and correlative genome-wide integration for some mechanistic claims. Future directions noted by the authors include testing whether SOX2 contributes to tumorigenesis through WLS/SFRP2 regulation and further dissecting the SOX2–chromatin regulator network.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE69476, GSE69479


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
