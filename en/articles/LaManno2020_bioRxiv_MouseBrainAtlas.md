---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
raw_data:
  - "SRA: PRJNA637987"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Molecular architecture of the developing mouse brain

## Citation (NLM)
La Manno G, Siletti K, Furlan A, Gyllborg D, Vinsland E, Langseth CM, Khven I, Johnsson A, Nilsson M, Lönnerberg P, Linnarsson S. Molecular architecture of the developing mouse brain. bioRxiv. 2020 Jul 3. doi:10.1101/2020.07.02.184051

**DOI:** [https://doi.org/10.1101/2020.07.02.184051](https://doi.org/10.1101/2020.07.02.184051)

---

## Background
The mammalian brain develops through the interplay of diffusible morphogens, cell-cell interactions, and intrinsic genetic programs, generating likely more than a thousand distinct cell types. A complete understanding requires systematic mapping of cell states across the full spatiotemporal range. The nervous system arises from the neuroepithelium, which folds into the neural tube and generates neurons, glia, and their derivatives; single-cell RNA-seq has been especially valuable for resolving this molecular heterogeneity.

Here the authors report a comprehensive single-cell transcriptome atlas of mouse brain development spanning from gastrulation to birth, aiming to capture the emergence of the neuroepithelium, region-specific organizers, and the full developmental program of neural cell types (including spinal cord patterning progenitors, radial glia, glioblasts, astrocytes, ependymal cells, and OPCs).

---

## Key Experiment Methods
1. Droplet-based single-cell RNA sequencing of embryonic brain tissue collected daily from E7 to E18 (43 pregnant CD-1 mice, 105 samples; 96 retained after QC), yielding a curated set of ~292,495 high-quality cells organized into 942 clusters.
2. Dimensionality reduction (tSNE), clustering, cell-cycle scoring, and spliced/unspliced RNA analysis; alignment to a prior gastrulation atlas (Pijuan-Sala et al. 2019).
3. In situ sequencing (HybISS) of 119 genes in an E10.5 mouse brain to spatially validate secondary organizers; clustering into ~40 embryonic territories.
4. Pseudolineage tree construction (shortest paths / geodesics on a radius-nearest-neighbor graph) to infer lineage trajectories and gene expression progressions to specific end states.
5. Comparison of human glioblastoma / anaplastic astrocytoma single-cell data against a merged developmental + adolescent brain reference to test the "fetal cell state" hypothesis of glioma.

---

## Results
- Cells organized primarily by gestational age, branching into major lineages from the neuroepithelium; disconnected islets (microglia, erythrocytes, vascular cells) reflected non-neuroepithelial origins.
- Early stages revealed germ-layer clusters and a neural-tube emergence; twelve neuroepithelial clusters, a neuromesodermal progenitor cluster (Cdx4, Cdx1, caudal Hox), and early neuroblasts were identified, with anterior-to-caudal patterning signatures (including midbrain/hindbrain/spinal cord patterning factors, e.g., NEpitC).
- A rich repertoire of secondary organizers was defined: ventralizing (Shh), dorsalizing (Wnts, Bmps), Fgf-expressing boundary organizers, and Neuregulin-expressing antihem organizers, each secreting distinct region-specific molecule combinations; validated spatially by in situ sequencing.
- After ~E14, radial glia lost proliferative capacity and switched to a glioblast state giving rise to astrocytes, ependymal cells, and OPCs; two major radial glia groups (neurogenic vs glial/glioblast) were distinguished, with evidence for loss of regionalization in the oligodendrocyte lineage.
- Pseudolineage analysis confirmed expected trajectories (e.g., pia/arachnoid from cranial neural crest; astrocytes and OPCs from distinct but related radial glia); nearly all neuronal but no glial lineages passed through an Nhlh1/Nhlh2+ early neuroblast state.
- Human glioblastoma aneuploid tumor cells predominantly matched embryonic cell types (radial glia, neuroblasts) or adult astrocytes, while normal (euploid) cells matched adult immune, oligodendrocyte, and vascular types, confirming the essentially fetal cellular nature of glioblastoma.

---

## Perspective
This atlas is a major resource for dissecting mammalian nervous-system development, providing time-, lineage-, and region-specific gene expression across the entire prenatal window. It offers tools for genetic targeting and for understanding neurodevelopmental disorders and brain cancer, and directly tested (and supported) the hypothesis that glioblastoma reflects a reversion to embryonic developmental cell states. For the spinal cord/regeneration knowledgebase, its value lies in mapping the developmental origins of neural progenitors, radial glia, ependymal cells, astrocytes, and OPCs, and in cataloguing the morphogen-secreting organizers that pattern the neural tube. Companion resources are available at mousebrain.org. As a preprint, findings await peer review.

## Data Availability

**Raw data generated by this study:**
- SRA: PRJNA637987


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
