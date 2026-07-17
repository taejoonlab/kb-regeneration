---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p03.txt
---

# Cross-Species Single-Cell Analysis Reveals Divergence of the Primate Microglia Program

## Citation (NLM)
Geirsdottir L, David E, Keren-Shaul H, Weiner A, Bohlen SC, Neuber J, Balic A, Giladi A, Sheban F, Dutertre CA, et al. Cross-Species Single-Cell Analysis Reveals Divergence of the Primate Microglia Program. Cell. 2019;179(7):1609-1622. doi:10.1016/j.cell.2019.11.010

**DOI:** [https://doi.org/10.1016/j.cell.2019.11.010](https://doi.org/10.1016/j.cell.2019.11.010)

---

## Background
Microglia are the primary resident immune cells of the CNS parenchyma, seeded during development from mesodermal (yolk-sac) progenitors and maintained by local self-renewal. They shape brain processes such as synaptic pruning and are central players in neurodegenerative disease pathology (e.g., Alzheimer's disease via Trem2-Tyrobp and ApoE pathways). Despite heavy reliance on transgenic animal models for neurodegeneration, disease manifestation differs greatly between humans and animal models. Understanding conserved versus divergent microglia pathways across evolution is therefore critical. This study characterizes microglia morphology and transcriptional programs across species spanning >450 million years of evolution, using single-cell RNA-seq to bypass the antibody/epitope limitations of cross-species cell purification.

---

## Key Experiment Methods
1. Iba1 immunohistochemistry with 3D-Imaris morphometric quantification across 18 evolutionarily distant species (pan-myeloid markers mPEG1-GFP for zebrafish, CSF1R-mApple for chicken).
2. Combined single-cell (MARS-seq2.0) and bulk RNA-seq of FACS-sorted CD45+ (Ptprc) brain immune cells from eight species with high-quality genomes (human, macaque, marmoset, sheep, mouse, hamster, chicken, zebrafish); ~4,458 QC-positive microglia.
3. Metacell algorithm to identify robust cell groups; single-cell data used to deconvolute bulk RNA-seq and remove contaminating genes.
4. "Metagene"/ortholog-conjecture strategy to define homologous genes across species; quantile normalization and k-means (17) clustering; PCA and hierarchical clustering.
5. Intra- vs inter-cluster correlation and cell-to-cell correlation to assess within-species microglia heterogeneity; expanded to rat and long-lived blind mole rat.
6. Cross-comparison of microglia expression with human neurodegenerative-disease GWAS susceptibility genes (AD, PD, HD, SCZ); comparison to mouse tissue-macrophage compendium (Lavin et al., 2014).

---

## Results
- CNS parenchymal cells with ramified microglia-like morphology and markers were found across all animals examined, though the degree of ramification and cell size varied considerably; highest density in leech ganglia, lowest in axolotl. Microglial density did not correlate with neuronal density.
- Microglia express a conserved core gene program in all mammals (clusters 1–10), with zebrafish and chicken forming an outgroup. Core orchestrators Spi1, Irf8, Csf1r, Tgfbr2, plus lysosomal hydrolases (cathepsins, Hexa) and homeostatic genes (C1qc, P2ry12, Tardbp, Vsir) are highly conserved.
- 163 genes were identified as conserved and unique to microglia versus other tissue macrophages (e.g., Adgrg1/Gpr56, Apbb1ip), enriched for neuron-projection and cerebellum development pathways.
- Most mammals display a single dominant microglia transcriptional state, but human microglia show significant heterogeneity organized into several subtypes across all six individuals (independent of sex).
- A human microglia subpopulation (~20%) co-expresses a senescence-associated/inflammatory signature (CDKN1, CCL3, CCL4, CCL3L3, CCL4L2, TNF, IL1B) not seen in young adult mouse microglia.
- Inter-species comparison revealed divergence in metabolic and immune pathways; human vs rodent showed many differentially expressed genes, whereas human vs macaque differed mainly in metabolic genes (NADK, BCO2). Non-mouse mammals were enriched for DNA repair, phagocytosis/apoptotic clearance, complement, and negative regulation of ferroptosis.
- Neurodegeneration susceptibility genes (AD, PD) showed significant expression divergence in primates/humans compared with rodents.

---

## Perspective
The study provides an essential cross-evolutionary resource of conserved and divergent microglia pathways, highlighting that human microglia are uniquely heterogeneous and that key neurodegeneration-associated genes diverge between rodents and primates. This has important implications for the limitations of rodent models in neurodegeneration research and for the future development of human microglia-based immunotherapies. Data are accessible via an interactive web tool. Limitations include the reliance on ortholog conjecture for cross-species gene pairing, genome-quality constraints restricting deep transcriptomics to eight species, and the descriptive (resource) nature of the divergent pathways, which await functional validation.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
