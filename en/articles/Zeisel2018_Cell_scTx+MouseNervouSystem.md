---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
---

# Molecular Architecture of the Mouse Nervous System

## Citation (NLM)
Zeisel A, Hochgerner H, Lönnerberg P, Johnsson A, Memic F, van der Zwan J, Häring M, Braun E, Borm LE, La Manno G, Codeluppi S, Furlan A, Lee K, Skene N, Harris KD, Hjerling-Leffler J, Arenas E, Ernfors P, Marklund U, Linnarsson S. Molecular Architecture of the Mouse Nervous System. Cell. 2018;174(4):999-1014. doi:10.1016/j.cell.2018.06.021

**DOI:** [https://doi.org/10.1016/j.cell.2018.06.021](https://doi.org/10.1016/j.cell.2018.06.021)

---

## Background

The adult mammalian nervous system is organized by developmental, functional, evolutionary, and biomechanical constraints, with dorsoventral and rostrocaudal compartments arising from patterning of the early neural tube. Yet many cell types (telencephalic interneurons, oligodendrocyte precursor cells, vascular and immune cells) migrate far from their birthplace, and convergent functional specialization occurs across regions. This raises the fundamental question of whether a cell's molecular identity is determined chiefly by developmental ancestry, local environment, or function.

Single-cell RNA sequencing (scRNA-seq) enables unbiased discovery of cell types based on gene activity, and atlas initiatives were underway for human and model organisms. Here the authors used systematic scRNA-seq across the entire mouse central nervous system (CNS) and peripheral nervous system (PNS) to build a comprehensive census of cell types, derive a data-driven taxonomy, and use it to interpret the overall architecture of the mammalian nervous system — including the spinal cord and its neuronal and glial diversity.

---

## Key Experiment Methods

1. Dissection of the adolescent mouse brain and spinal cord into contiguous anatomical regions plus peripheral sensory, enteric, and sympathetic nervous system — 19 regions total, 133 samples, at least two mice per tissue.
2. Droplet-microfluidics scRNA-seq (10X Genomics Chromium) profiling 509,876 cells; mostly unbiased sampling, with FACS enrichment of enteric neural-crest cells (Wnt1-Cre;R26Tomato) and cortical/hippocampal inhibitory neurons (vGat-Cre;TdTomato).
3. A custom multi-stage analysis pipeline ("cytograph") using iterative manifold learning and clustering to discover cell types while mitigating technical artifacts (low-quality cells, batch, sex, activity-dependent genes).
4. Curation to 160,796 high-quality single-cell transcriptomes in 265 clusters; downsampling of superabundant hindbrain/spinal-cord oligodendrocytes to balance tissues.
5. Robustness assessment via a random-forest classifier (80/20 train/test; ~82% precision and recall).
6. Concordance validation against six previously published, experimentally validated scRNA-seq datasets across cortex, striatum, dentate gyrus, spinal cord, and sympathetic nervous system.
7. Spatial mapping of cell types to anatomical regions and construction of a hierarchical, neurotransmitter- and developmental-unit-based taxonomy.

---

## Results

- Generated a detailed census of cell types across the mouse nervous system, organized into a hierarchical, data-driven taxonomy spanning CNS neurons, PNS neurons, and non-neuronal classes (astroependymal, oligodendrocyte, immune, vascular, neural-crest-like glia).
- Neurons were the most diverse class and were grouped by developmental anatomical units (telencephalon, di-/mesencephalon, hindbrain, spinal cord, etc.) and by neurotransmitter/neuropeptide expression (glutamatergic VGLUT1/2/3, GABAergic, glycinergic, dopaminergic, cholinergic, adrenergic/noradrenergic, serotonergic, nitric oxide).
- Neuronal diversity was driven by genes encoding cell identity, synaptic connectivity, neurotransmission, and membrane conductance, and was broadly similar in magnitude across brain regions.
- Discovered seven distinct astrocyte types with regionally restricted distributions that obeyed developmental boundaries and correlated with the spatial distribution of key glutamate and glycine neurotransmitters — indicating that astrocyte identity retains a developmental/regional imprint.
- In contrast, oligodendrocytes showed a loss of regional identity followed by a secondary diversification (into maturation states rather than regional types).
- Spinal cord neurons formed distinct excitatory (SCGLU) and inhibitory (SCINH) clusters within the taxonomy, embedded among the broader CNS neuronal hierarchy.
- Clustering was highly conservative (265 clusters, ~82% classifier precision/recall) and concordant with prior validated datasets, providing a robust reference atlas.

---

## Perspective

This Resource lays a foundation for understanding the molecular architecture of the mammalian nervous system, providing a reference atlas of ~half a million cells and a data-driven taxonomy that enables genetic targeting of specific cell types. Its central conceptual contribution is that different cell classes answer the identity question differently: astrocytes retain strong developmental/regional imprints (seven region-restricted types), whereas oligodendrocytes largely erase regional identity and diversify by maturation state, and neuronal diversity is patterned primarily by developmental anatomical unit and neurotransmitter usage. The inclusion of the spinal cord and PNS makes it directly relevant to CNS/spinal-cord cell-type and glial-biology research.

Limitations include omission of several regions (retina, olfactory epithelium, vomeronasal organ, inner ear, parasympathetic ganglia), deliberate downsampling of oligodendrocytes, conservative clustering that likely leaves residual heterogeneity within clusters, and the technical artifacts inherent to large-scale droplet scRNA-seq. Future work can refine subtypes within clusters, add spatial and developmental time-course data, and extend the taxonomy to other species.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
