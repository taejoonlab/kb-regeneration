---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Developmental Heterogeneity of Microglia and Brain Myeloid Cells Revealed by Deep Single-Cell RNA Sequencing

## Citation (NLM)
Li Q, Cheng Z, Zhou L, Darmanis S, Neff NF, Okamoto J, Gulati G, Bennett ML, Sun LO, Clarke LE, Marschallinger J, Yu G, Quake SR, Wyss-Coray T, Barres BA. Developmental Heterogeneity of Microglia and Brain Myeloid Cells Revealed by Deep Single-Cell RNA Sequencing. Neuron. 2019;101(2):207-223.e10. doi:10.1016/j.neuron.2018.12.006

**DOI:** [https://doi.org/10.1016/j.neuron.2018.12.006](https://doi.org/10.1016/j.neuron.2018.12.006)

---

## Background

Microglia, the brain's parenchymal macrophages, are implicated in numerous neurological diseases and increasingly recognized as active participants in neural development (neurogenesis, synaptic pruning). Despite their importance, little was known about their molecular heterogeneity under physiological conditions, especially during development when they perform many non-immune functions. Prior bulk RNA-seq studies relied on general surface markers and could overlook transient developmental populations, while it remained unclear whether molecularly defined microglial subtypes exist across adult brain regions.

To address this, the authors took an unbiased deep single-cell RNA sequencing (scRNA-seq) approach to profile microglia and related brain myeloid cells across mouse brain regions and developmental stages, aiming to resolve subtle differences that shallower methods might miss.

---

## Key Experiment Methods

1. **Deep Smart-seq2 scRNA-seq**: Index-sorted innate immune cells from mouse brain sequenced to >1 million raw reads/cell (1,922 cells total; 1,816 passed QC) from E14.5, P7, and adult (P60) stages; ERCC spike-ins confirmed near single-molecule sensitivity (R=0.98).
2. **Regional sampling**: For P7 and P60, myeloid cells isolated from six regions (cortex, cerebellum, hippocampus, striatum, olfactory bulb, choroid plexus); FACS gating on c-Kit/CD45 (E14.5) and CD45low/hi CD11b+ (P7/P60).
3. **Unsupervised clustering** yielding 15 clusters (7 microglia, 2 choroid plexus macrophage, 3 monocyte, 3 other); differential expression to define cluster markers.
4. **Cell cycle pseudotime reconstruction**: regressed out cell-cycle effects, then used HeLa-derived conserved cell-cycle genes as seeds to build phase-specific gene sets for dividing microglia.
5. **Region-specific bulk RNA-seq** of TMEM119-sorted homeostatic microglia for cross-validation.
6. **Validation**: RNAscope RNA in situ, immunohistochemistry, FACS (GPNMB+CLEC7A+ sorting), pH-sensitive bead phagocytosis assays, and analyses in Trem2−/− and Apoe−/− mice.

---

## Results

- **15 distinct clusters** identified across developmental stages; microglia clusters segregated by developmental stage along the tSNE, consistent with progressive developmental gene-expression changes.
- **Choroid plexus macrophages** underwent a postnatal transcriptional switch, separating into distinct P7 (endocytosis/trafficking genes) and adult (MHC-II high; markers H2-Eb1, Lilra5) clusters.
- **Adult homeostatic microglia showed limited transcriptomic heterogeneity** across brain regions; <20 genes differentially expressed between regions, and one cluster differed mainly by immediate-early genes (IEGs) interpreted as an isolation artifact (Fos/Egr1 negative in tissue).
- **Phase-specific cell-cycle gene sets** derived for dividing P7 microglia (315 genes for P7-C0, 347 for P7-C1), including novel periodically expressed genes (e.g., Ankle1, Lig1, Eri1).
- **Discovery of PAM (proliferative-region-associated microglia)**: a P7 subset in developing corpus callosum and cerebellar white matter expressing a DAM-like signature (Spp1, Gpnmb, Igf1, Clec7a, Lpl, Itgax, Apoe). PAM are amoeboid, metabolically active (oxidative phosphorylation, glycolysis, lipid metabolism, lysosomal genes).
- **PAM appear transiently** (peak ~P7, gone by P14) and independently of the TREM2-APOE axis, unlike degenerative DAM.
- **PAM phagocytose newly formed (dying, cCASP3+/MBP+) oligodendrocytes** during myelination, and to a lesser extent astrocytes, but not OPCs (PDGFRA+).

---

## Perspective

This study provides a high-resolution, deeply sequenced scRNA-seq atlas of brain myeloid cells across development (integrated into brainrnaseq.org), establishing that adult homeostatic microglia are remarkably uniform while early postnatal microglia are heterogeneous. The discovery of PAM—a developmental microglial state mirroring disease-associated microglia (DAM)—supports the concept that developmental gene programs are reactivated in aging and neurodegeneration, offering a window into disease pathophysiology.

For spinal cord/CNS regeneration, the PAM phenotype and its DAM-like signature became a key reference (e.g., the same lab's neonatal spinal-cord repair study), linking developmental microglial states to reparative/phagocytic functions. Limitations include the plate-based Smart-seq2 throughput (relatively few cells versus droplet methods), analysis of a limited set of brain regions (potentially missing additional heterogeneity, e.g., midbrain), and the correlative nature of the phagocytosis inference. Future functional studies are needed to determine whether PAM are transcriptionally pre-disposed to phagocytosis or converted by the phagocytic act itself.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
