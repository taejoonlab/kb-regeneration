---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
raw_data:
  - "GEO: GSE158380"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# A harmonized atlas of mouse spinal cord cell types and their spatial organization

## Citation (NLM)
Russ DE, Patterson Cross RB, Li L, Koch SC, Matson KJE, Yadav A, Alkaslasi MR, Lee DI, Le Pichon CE, Menon V, Levine AJ. A harmonized atlas of mouse spinal cord cell types and their spatial organization. Nat Commun. 2021;12(1):5722. doi:10.1038/s41467-021-25125-1

**DOI:** [https://doi.org/10.1038/s41467-021-25125-1](https://doi.org/10.1038/s41467-021-25125-1)

---

## Background

Single-cell RNA sequencing can reveal the molecular diversity of cell types, and several groups have profiled the postnatal mouse spinal cord. However, these datasets had not been integrated, and there was no consensus cell type atlas of the spinal cord. A major obstacle was the lack of an accepted ground truth for spinal cell types, compounded by the difficulty of comparing data across studies even when the same tissue and techniques were used — differences in analysis parameters and technical artifacts obscure underlying biological similarities and produce a fragmented set of incomplete, conflicting atlases.

The authors set out to build a harmonized, validated atlas of postnatal spinal cord cell types that could reveal the organizing principles of spinal neuronal diversity and serve as a standard reference framework for future work.

---

## Key Experiment Methods

1. Assembled a merged meta-dataset (>100,000 cells/nuclei) from the first six publicly available postnatal mouse spinal cord single-cell/nucleus datasets (Sathyamurthy, Hayashi, Haring, Rosenberg, Zeisel, Baek), starting from raw sequencing reads and reprocessing with uniform alignment (exons + introns) and uniform filters (>200 genes/cell, <5% mitochondrial genes).
2. Tested whether prior atlases could simply be registered to one another via correlation of gene expression between clusters, and via naive co-clustering (PCA/UMAP).
3. Applied Seurat integration to align cells/nuclei across studies; benchmarked against three additional integration methods (Harmony, Conos, LIGER) using UMAP inspection and Local Inverse Simpson Index (LISI) scores.
4. Performed coarse clustering to define major cell types, then refined clustering of neurons; validated a combinatorial marker gene code with high-content in situ hybridization to map spatial distribution in adult tissue.
5. Co-integrated postnatal data with embryonic cell types to infer lineage relationships.
6. Tested a range of automated classification algorithms and built SeqSeek, an open-source web resource and two-tiered classifier (label transfer + neural networks).

---

## Results

- Prior published atlases could not simply be registered to one another: correlation-based linking of clusters was weak/incomplete, and naive co-clustering segregated cells almost entirely by study of origin (study is a major source of variability).
- Seurat integration interposed cells/nuclei from all six studies in UMAP space and separated them into groups expressing established markers (Snap25 neurons, Mbp oligodendrocytes, Aqp4 astrocytes, Ctss microglia). Integration preserved biological differences while reducing technical variability; results were robust across four integration methods.
- The final integrated dataset contained ~52,623 high-quality cells/nuclei.
- Sixteen major cell types were identified, covering all known spinal cord classes: OPCs, two oligodendrocyte progenitor stages, two oligodendrocyte types, Schwann cells, peripheral glia, two meningeal types (vascular leptomeningeal and arachnoid barrier), ependymal cells, two astrocyte types, two vascular types (endothelial and pericytes), microglia, and neurons.
- Neuronal analysis resolved dozens of refined populations. The atlas showed a hierarchical structure of cell-type relationships in which location provides the highest level of organization, followed by neurotransmitter status, family, and finally refined populations.
- A validated combinatorial marker code mapped the spatial distribution and prevalence of each neuronal cell type in adult tissue, revealing striking differences between dorsal and ventral neuronal cell types.
- Co-integration with embryonic cell types uncovered complex, often convergent lineage contributions from multiple embryonic lineages to individual postnatal cell types.
- SeqSeek was released as a web-based resource for querying data by gene or cell type and for automated classification of any spinal cord cell/nucleus from raw sequencing data.

---

## Perspective

This work provides an integrated, harmonized reference for spinal cord cell types, standardizing a field that had been fragmented across incompatible datasets. The demonstration that published atlases cannot be trivially cross-registered — and that integration is required to recover shared cell types — is an important methodological lesson for the broader single-cell community. The hierarchical organizing logic (location > neurotransmitter > family > population) and the validated in situ marker code make the atlas directly usable for designing genetic tools and interpreting new datasets. SeqSeek lowers the barrier to standardized cell-type identification.

Limitations noted in the text include residual technical differences between studies that integration reduces but does not eliminate (e.g., high-throughput nuclei studies detect fewer genes; cell-based studies show more stress/immediate-early gene expression). The atlas is built on postnatal mouse data from a specific set of studies, so extension to other ages, species, and injury/disease states remains future work, as does deeper validation of the inferred convergent lineage relationships.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE158380

**Other accessions referenced in the text (reused/external data):**
- GEO: GSE103892, GSE130312, GSE103840, GSE110823, GSE108788, GSE161621, GSE167597
- SRA: SRP117727, SRP128071, SRP135960, SRP117627, SRP133097
- ArrayExpress: E-MTAB-7320


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
