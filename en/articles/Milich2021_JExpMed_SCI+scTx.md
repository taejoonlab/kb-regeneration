---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Single-cell analysis of the cellular heterogeneity and interactions in the injured mouse spinal cord

## Citation (NLM)
Milich LM, Choi JS, Ryan C, Cerqueira SR, Benavides S, Yahn SL, Tsoulfas P, Lee JK. Single-cell analysis of the cellular heterogeneity and interactions in the injured mouse spinal cord. J Exp Med. 2021;218(8):e20210040. doi:10.1084/jem.20210040

**DOI:** [https://doi.org/10.1084/jem.20210040](https://doi.org/10.1084/jem.20210040)

---

## Background

After spinal cord injury (SCI), a wound healing process maintains tissue homeostasis and limits damage, but eventually produces a scar-like environment that is not conducive to regeneration and repair. This process is highly dynamic in the first 7 days, involving an innate immune response, glial proliferation/gliosis, monocyte-to-macrophage differentiation, fibrosis, and angiogenesis, offering a therapeutic window. A major obstacle to targeting the appropriate pathobiology has been the large cellular heterogeneity and complex cellular interactions at the injury site.

Prior transcriptomic approaches (FACS, cell-type-specific ribosome/nuclei profiling) focused on single cell types and lacked information on subpopulation heterogeneity and cell states. This study applies single-cell RNA sequencing (scRNA-seq) to profile virtually all cell types comprising the uninjured and injured mouse spinal cord, providing a resource to dissect cellular interactions during angiogenesis, gliosis, and fibrosis.

---

## Key Experiment Methods

1. Mid-thoracic (T8) contusion SCI in female C57BL/6J mice using the Infinite Horizon Impactor (65 kdyne).
2. scRNA-seq of dissociated spinal cord tissue at uninjured, 1, 3, and 7 dpi (66,178 cells total; astrocyte enrichment with anti-ACSA-2 beads).
3. Clustering (UMAP), differential expression, SingleR annotation, and GO enrichment to identify major cell types and subtypes.
4. Ligand-receptor "interaction score" analysis (adapted CellPhoneDB) using known ligand-receptor pairs to predict cellular signaling.
5. Flow cytometry validation of microglia (P2RY12/MSR1) and macrophage (CD63/CD11b/APOE) subtypes.
6. Immunohistochemistry and RNAscope in situ hybridization (Apln, Crym, Osm, Itgam) for spatial/temporal validation.
7. Genetic lineage tracing of activated fibroblasts using Postn-CreER; Rosa26-EYFP mice.

---

## Results

- Identified 15 clusters covering all major SCI-site cell types (microglia, monocytes, macrophages, neutrophils, dendritic cells, astrocytes, oligodendrocytes, OPCs, fibroblasts, pericytes, ependymal, endothelial cells); many highest DEGs were noncanonical (e.g., Tnr for OPCs) and temporally specific (e.g., Postn in fibroblasts).
- Myeloid analysis: four microglia subtypes (homeostatic, inflammatory, dividing, migrating) and macrophage subtypes (chemotaxis-inducing vs inflammatory) that did NOT correspond to M1/M2 nomenclature; peripheral myeloid composition shifts toward a proinflammatory state over time.
- Vascular analysis: identified arterial, venous, capillary, and tip cell endothelial subtypes; tip cells (Apln+) were absent in uninjured cord, peaked at 1 dpi, and largely disappeared by 7 dpi.
- Angiogenesis signaling: tip cells are a major source of Angpt2 (vessel destabilization) and Plgf (vessel formation); Angpt1 shifted from VSMCs (1 dpi) to astrocytes (3-7 dpi), implicating astrocytes in later vessel stabilization/maturation.
- Macroglia analysis: identified injury-induced astroependymal cells (Crym+, present 1-3 dpi) and two OPC subtypes; OPC-B appeared after injury and clustered with astrocytes/astroependymal cells. Axon growth-inhibitory proteoglycans (Acan, Bcan, Ncan, Vcan) were expressed preferentially by OPCs rather than astrocytes.
- Gliosis/fibrosis: myeloid-derived oncostatin M (OSM) signaling to OSMR/gp130 on astrocytes and fibroblasts was identified as a common activation mechanism (validated histologically at 7 dpi); macrophage-fibroblast interactions were more numerous than macrophage-astrocyte, with Spp1 and Apoe signaling being the highest-scoring shared pathways.

---

## Perspective

This is the first comprehensive scRNA-seq atlas capturing virtually all cells at the acute SCI site, enabling less-biased assessment of the wound healing process. It reveals distinct temporal regulation of angiogenesis, gliosis, and fibrosis by specific myeloid subtypes, and generates testable hypotheses (e.g., OSM-gp130 as a shared myeloid-driven astrocyte/fibroblast activation axis; tip cell autocrine/paracrine control of revascularization; astrocyte role in vessel maturation). The dataset is a valuable community resource applicable to other traumatic CNS disorders.

Limitations: neurons and lymphocytes were excluded; cell recovery numbers do not reflect true in vivo proportions due to dissociation biases (though within-population subtype proportions appear accurate); some subpopulations (inflammatory/dividing microglia) partly reflect dissociation-induced stress, mitigated by comparison with bulk RNA-seq and Allen Brain Atlas data. Ligand-receptor interaction scores are predictive models requiring future experimental validation. A key therapeutic challenge is limiting the proinflammatory macrophage state without interfering with beneficial wound-healing functions (e.g., Vegfa, Spp1, Apoe).

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
