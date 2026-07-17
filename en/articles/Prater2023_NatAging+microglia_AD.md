---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
---

# Human microglia show unique transcriptional changes in Alzheimer's disease

## Citation (NLM)
Prater KE, Green KJ, Mamde S, Sun W, Cochoit A, Smith CL, et al. Human microglia show unique transcriptional changes in Alzheimer's disease. Nat Aging. 2023;3(7):894-907. doi:10.1038/s43587-023-00424-y

**DOI:** [https://doi.org/10.1038/s43587-023-00424-y](https://doi.org/10.1038/s43587-023-00424-y)

---

## Background

Microglia are the resident innate immune myeloid cells of the CNS and are strongly implicated in Alzheimer's disease (AD), where neuroinflammation is now considered a modifiable feature of pathology. Genetic studies have localized AD risk variants to genes uniquely expressed by brain myeloid cells, and microglia are thought to contribute to amyloid-beta clearance, tau spreading, and aberrant synaptic pruning. However, microglia are functionally heterogeneous, and the full range of their transcriptional states in the human AD brain has been difficult to resolve because standard single-nucleus RNA-seq (snRNA-seq) captures relatively few microglia per individual.

The authors hypothesized that datasets containing far more microglia per subject would reveal additional cellular processes and regulatory factors. They applied fluorescence-activated nuclei sorting (FANS) for the myeloid transcription factor PU.1 to enrich microglia nuclei before snRNA-seq, aiming to define transcriptomic phenotypes, infer gene regulatory networks, and map putative relationships between microglial states in aged control and AD brains.

---

## Key Experiment Methods

1. PU.1 FANS enrichment of nuclei from postmortem human dorsolateral prefrontal cortex (dlPFC), validated to yield ~20-fold more microglia nuclei versus unsorted controls.
2. snRNA-seq on 22 individuals (12 AD, 10 control; 7 males, 15 females; all >60 years), yielding 200,948 QC-passed nuclei and 127,371 microglia (avg 5,790 microglia/individual).
3. Unsupervised clustering and differential expression analysis (each cluster vs. all others; and vs. the homeostatic-marker cluster), with GSEA for biological pathway enrichment.
4. SCENIC transcription-factor regulon (gene regulatory network) analysis to identify cluster-specific regulons.
5. Monocle3 trajectory inference to model transitions among microglial transcriptomic states.
6. APOE ε3/ε3-only subset analysis (13 individuals, 75,018 microglia) to control for APOE genotype.
7. GSEA enrichment of 46 AD GWAS risk genes across clusters; subclustering of the homeostatic cluster.
8. Immunohistochemistry validation (LAMP1, PTGDS, P2RX7, dsDNA, P2RY12, PDE4B) in human brain tissue.

---

## Results

- Ten microglia clusters were identified. Cluster 1 (HM) was the largest, enriched for homeostatic markers (CX3CR1, P2RY12). Clusters matched previously described phenotypes: dystrophic/degenerative (cluster 4, high FTL), motile (cluster 7), canonical inflammatory (cluster 8, NFκB1/RELB/IL1β), senescent-like (cluster 9), and cell-cycle/DNA-repair (cluster 10).
- Three previously undescribed endolysosomal network (ELN) clusters (3, 5, 6) were defined by endosome/lysosome and vesicle-trafficking gene signatures. Cluster 5 showed autophagy/stress and glycolytic activity; cluster 6 combined ELN signatures with interferon signaling (IRF3/5/7), inflammasome, and cytosolic nucleic-acid recognition genes.
- Cluster-specific transcription-factor regulons (e.g., MAFB in cluster 3; IRF7/IRF3 in cluster 6; IRF1/NFKB2 in cluster 8) supported the functional distinctness of clusters.
- Trajectory analysis suggested multiple transition states radiating from the homeostatic cluster, with dystrophic (4) and senescent (9) clusters as end states and a branch point toward autophagic-stress (5) versus inflammatory ELN (6).
- The interferon-ELN cluster 6 was overrepresented in AD cases (adjusted P = 0.006) and was enriched for differentially expressed AD GWAS risk genes (PICALM, SORL1, PLCG2 lower; APP, APOE, BIN1 higher). Cluster 10 (cell cycle/DNA repair) was reduced in AD relative to control.
- An AD-specific subcluster (1.5) was found within the homeostatic cluster, nearly exclusive to AD cases, with highest P2RY12 and markers WIPF3, PDE4B, KCNIP, and enrichment for motility and calcium-signaling genes; validated by IHC (P2RY12/PDE4B double-positive).
- Findings, including ELN-cluster diversity, were reproduced in the APOE ε3/ε3-only cohort.

---

## Perspective

Using deep PU.1-enriched profiling, this study substantially expands the catalog of human microglial transcriptional states in aged and AD brain, uncovering endolysosomal and type-I-interferon phenotypes and an AD-specific homeostatic subcluster not resolvable with sparser datasets. The interferon-ELN cluster 6, enriched in AD cases and for AD risk genes, is nominated as a candidate therapeutic target, and the inferred regulons provide testable regulatory handles. Limitations acknowledged by the authors include the hypothesis-generating nature of trajectory inference (a transcriptomic "snapshot" of potentially reversible states), the small size of some clusters (e.g., cluster 10) needing replication, and the postmortem cross-sectional design. Future work should test the plasticity/reversibility of these states and their causal roles in AD pathogenesis. While centered on the AD cortex rather than spinal cord, the work is directly relevant to CNS glial biology and to microglial heterogeneity in neurodegeneration and injury.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
