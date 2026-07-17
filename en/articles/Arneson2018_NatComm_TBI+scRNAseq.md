---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
raw_data:
  - "GEO: GSE101901"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Single cell molecular alterations reveal target cells and pathways of concussive brain injury

## Citation (NLM)
Arneson D, Zhang G, Ying Z, Zhuang Y, Byun HR, Ahn IS, Gomez-Pinilla F, Yang X. Single cell molecular alterations reveal target cells and pathways of concussive brain injury. Nat Commun. 2018;9:3894. doi:10.1038/s41467-018-06222-0

**DOI:** [https://doi.org/10.1038/s41467-018-06222-0](https://doi.org/10.1038/s41467-018-06222-0)

---

## Background

Traumatic brain injury (TBI) is common in domestic, sports, and military settings and often leads to long-term neurological and psychiatric disorders. The hippocampus, central to learning and memory, is a major site of TBI pathology, and its dysfunction causes cognitive impairment. Mild TBI (mTBI) is especially hard to diagnose because it has no accepted biomarkers, yet it raises the risk of Alzheimer's disease (AD), chronic traumatic encephalopathy (CTE), PTSD, epilepsy, and dementia.

Because gene regulatory programs determine cell function, large-scale genomic analysis can reveal molecular determinants of mTBI, but prior profiling relied on bulk tissue that masks signals from vulnerable cell types within the convoluted hippocampal cytoarchitecture. Here the authors apply unbiased single-cell sequencing (Drop-seq) to individual hippocampal cells to define which cell types, genes, pathways, and cell-cell interactions are perturbed at the acute (24 h) phase after concussive injury, providing a hippocampal cell atlas under physiological and pathological conditions.

---

## Key Experiment Methods

1. Mild fluid percussion injury (FPI) mouse model of concussive mTBI vs Sham; hippocampi harvested at 24 h post-injury (3 mTBI + 3 Sham animals).
2. Drop-seq single-cell RNA-sequencing (2818 mTBI + 3414 Sham cells); digital expression matrix, t-SNE clustering (15 clusters).
3. Cell-type identification via cluster-specific gene signatures compared to known Fluidigm/Div-Seq hippocampal signatures; BackSPIN biclustering to resolve nine neuronal subclusters.
4. Validation of novel marker genes with Allen Brain Atlas in situ hybridization (ISH) data.
5. Differential expression (DEG, FDR<0.05) within each cell type; pathway annotation with KEGG, Reactome, BIOCARTA, Gene Ontology.
6. Cell-cell gene co-expression analysis using secreted-peptide source markers correlated with target-cell effector genes (permutation-based scoring) to infer circuit interactions.
7. Functional test: modulation of the thyroid hormone T4 transporter transthyretin (Ttr) to assess rescue of mTBI genomic/behavioral abnormalities.

---

## Results

- Recovered all known major hippocampal cell types (neurons, oligodendrocytes, oligodendrocyte progenitor cells, microglia, mural cells, endothelial cells, astrocytes, ependymal cells) confirmed by canonical markers (Aqp4, Mog, C1qc) and identified novel markers (e.g., Calml4 for ependymal, Vcan for oligodendrocytes, Ly6a for endothelial).
- Identified two previously undefined clusters: Unknown1 (migration/growth + endothelial markers; likely migrating endothelial cells) and Unknown2 (differentiation markers localising to choroid plexus; likely progenitor cells).
- Neuronal subclustering resolved GABAergic interneurons, DG granule cells, and 4 CA pyramidal subtypes plus two subtypes without established identity; novel neuronal markers included Ptn (CA1), Ly6e (CA3), Sema5a (DG); CA Subtype2 mapped to the subicular complex, relevant to CTE/dementia.
- Vulnerable cell types: ependymal cells shifted markedly in relative abundance after mTBI (consistent with roles in circuit repair, scar formation, progenitor source); DG, ependymal, astrocytes, microglia, oligodendrocytes, oligoPCs, endothelial, and several neuronal populations showed significant global transcriptomic shifts. mTBI split DG granule cells into two distinct clusters, relevant to post-traumatic epilepsy.
- mTBI reorganized cell-cell gene co-expression: enhanced astrocyte/ependymal→neuron and microglia→oligodendrocyte interactions; decreased microglia→neuron and oligodendrocyte→neuron interactions. AD-risk gene Apoe in astrocytes/ependymal cells correlated with neuronal mitochondrial metabolism genes after injury.
- DEG/pathway analysis: astrocytes, oligodendrocytes, and neurons had the most DEGs; pathways spanned energy/metabolism (astrocytes, neurons), inflammation (microglia, oligoPCs), myelination (oligodendrocytes), amyloid handling (endothelial, ependymal), neurogenesis/synaptic signaling (neurons), and cell death regulation. Down-regulation of mitochondrial metabolic genes in astrocytes and CA1 pyramidal cells reflected the metabolic crisis; endothelial/ependymal cells implicated in amyloid buildup (up B2m; down Apoe, Itm2a/b/c).
- Prioritizing Ttr as a data-driven target, modulating transthyretin (thyroid hormone pathway) improved behavioral phenotypes and reversed mTBI-associated molecular changes.

---

## Perspective

This is presented as the first single-cell sequencing study of mTBI pathogenesis across thousands of individual hippocampal cells, delivering a cell atlas and demonstrating that mTBI acutely affects nearly all hippocampal cell types (including understudied and putatively novel populations) through cell-type-specific genes, pathways, and altered inter-cellular gene co-expression. The transcriptome-driven approach uncovers new cell states/markers that morphology cannot resolve, and provides candidate signatures linking mTBI to secondary disorders such as AD, CTE, and epilepsy. The Ttr proof-of-concept shows the atlas can nominate actionable therapeutic targets.

Limitations acknowledged by the authors: Drop-seq capture rates vary by cell type so shifts in proportion do not directly imply proliferation/death; the co-expression analysis is in silico and requires downstream validation; the putative novel clusters and neuronal subtypes need functional characterization. The study captures only the acute 24 h timepoint.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE101901


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
