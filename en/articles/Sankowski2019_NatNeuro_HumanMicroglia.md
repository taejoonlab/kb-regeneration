---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
---

# Mapping microglia states in the human brain through the integration of high-dimensional techniques

## Citation (NLM)
Sankowski R, Böttcher C, Masuda T, Geirsdottir L, Sagar, Sindram E, Seredenina T, Muhs A, Scheiwe C, Shah MJ, Heiland DH, Schnell O, Grün D, Priller J, Prinz M. Mapping microglia states in the human brain through the integration of high-dimensional techniques. Nat Neurosci. 2019;22(12):2098-2110. doi:10.1038/s41593-019-0532-y

**DOI:** [https://doi.org/10.1038/s41593-019-0532-y](https://doi.org/10.1038/s41593-019-0532-y)

---

## Background

Microglia are the tissue-resident macrophages of the CNS that orchestrate local immune responses and contribute to numerous neurological and psychiatric diseases. In the healthy brain they surveil the microenvironment, modulate synaptic plasticity and clear dying cells, while in disease they take on immunological functions. Genome-wide association studies of neurodegenerative and neuroinflammatory disorders have linked many risk-associated single nucleotide polymorphisms to microglia, underscoring the importance of innate immune cells in CNS disease.

Despite this, little was known about human microglia, and evidence for specialized microglia subsets in vivo was scarce. Key questions about the single-cell composition of microglia states in the human brain—regional and functional heterogeneity—remained unanswered, in part because of the difficulty of obtaining healthy human brain tissue and the limitations of methods that require pooling large numbers of cells. This study combines single-cell RNA sequencing (scRNA-seq) with time-of-flight mass cytometry (CyTOF) to define microglia states in the human brain during homeostasis and disease.

---

## Key Experiment Methods

1. **scRNA-seq of human microglia**: 4,396 microglial cells (of 4,564 CD45+DAPI− FACS-sorted cells) from control brain regions of 15 adults undergoing surgery for epilepsy (n=10), malignant glioma (n=4) or metastasis (n=1), profiled with the 3′-end mCEL-Seq2 protocol.
2. **RaceID3 clustering**: unsupervised clustering designed to detect rare populations, yielding nine major microglia clusters (C1–C9).
3. **Neural-network classifier**: trained on 70% of cells to assign microglia from independent published datasets (Masuda, Velmeshev, Schirmer, Jäkel, Mathys) to the defined clusters for cross-dataset validation.
4. **Gene ontology (GO) enrichment analysis** (clusterProfiler) of cluster-enriched differentially expressed genes to infer functional states.
5. **Regional and age comparisons**: gray vs. white matter temporal lobe samples (11/15 subjects) and three age bins (<30, 30–50, >50 years).
6. **Protein-level validation**: immunohistochemistry (IBA1, P2RY12, TMEM119, HLA-DR, CD68, CD74, SPP1) and CyTOF on gray/white matter samples.
7. **Glioma analysis**: scRNA-seq of microglia from four IDH wild-type primary glioblastomas (GBM) vs. four age-matched controls; StemID2 and Monocle pseudotime analysis; CyTOF validation.

---

## Results

- Human microglia occupy a continuous spectrum of transcriptional states rather than discrete cell types; all clusters formed a single diffuse "microglia cloud" distinct from monocytes and oligodendrocytes.
- Homeostatic clusters C2 and C3, characterized by core signature genes (CX3CR1, TMEM119, CSF1R, P2RY12, P2RY13, SELPLG, MARCKS), received contributions from all 15 subjects; C2 additionally showed high MHC-II and antiviral genes (HLA-DRA, CD74, IFI44L).
- Clusters C6/C7 showed low CX3CR1 and high metabolic/integrin genes (SPP1, APOE, LPL); smaller clusters C1, C5, C8, C9 expressed chemokine/cytokine genes (CCL2, IL1B, CD83).
- The classifier reproduced cluster assignments across independent datasets, confirming in vivo relevance of the proinflammatory clusters.
- **Regional heterogeneity**: white matter microglia were enriched in MHC-II-high clusters (C2, C5–C7) with higher HLA-DR, CD68, APOE and EMR1; gray matter microglia were enriched in MHC-II-low clusters (C3, C8). Confirmed by IHC and CyTOF.
- **Age dependence**: clusters C6/C7 (SPP1/osteopontin-high) were enriched in subjects >50 years; SPP1+IBA1+ cells increased with age and in white matter.
- **Glioma-associated microglia (GAMs)**: acquired a disease-associated signature with downregulated core genes (CX3CR1, SELPLG) and upregulated inflammatory/metabolic/hypoxia genes (CD163, APOE, LPL, IFI27, IFITM3, HIF1A, VEGFA). Pseudotime (StemID2, Monocle) suggested a homeostatic → aging-associated → GAM trajectory. A unique glioma-associated cluster was identified by CyTOF, and GAMs were transcriptionally related to aging-associated microglia.

---

## Perspective

By integrating two orthogonal high-dimensional techniques (scRNA-seq and CyTOF) with in situ validation, this study provides one of the first single-cell resolution maps of human microglia in the healthy and diseased brain. It establishes that human microglia exist along a spatial- and age-shaped transcriptional continuum and that glioma reshapes microglia toward an aging-related, inflammatory/metabolic state. This offers a resource for developing microglia subset-specific therapies.

Limitations include the small number of subjects, reliance on "control" access tissue from patients undergoing surgery (which may not equal truly healthy brain), relatively low cell numbers in some comparison datasets, and reduced classifier accuracy on external test sets—reflecting technical differences across protocols (mCEL-Seq2 vs. nuc-seq) and patient age. Future work would benefit from larger cohorts, additional brain regions, and functional characterization of the defined states. For CNS injury and regeneration research, the framework of regionally and disease-defined microglia states is directly relevant to understanding glial responses in the CNS.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
