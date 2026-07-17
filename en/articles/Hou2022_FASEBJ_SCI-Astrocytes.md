---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p04.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Heterogeneity analysis of astrocytes following spinal cord injury at single-cell resolution

## Citation (NLM)
Hou J, Bi H, Ge Q, Teng H, Wan G, Yu B, Jiang Q, Gu X. Heterogeneity analysis of astrocytes following spinal cord injury at single-cell resolution. FASEB J. 2022;36(8):e22442. doi:10.1096/fj.202200463R

**DOI:** [https://doi.org/10.1096/fj.202200463R](https://doi.org/10.1096/fj.202200463R)

---

## Background

Astrocytes perform many important functions in response to spinal cord injury (SCI), including clearance of necrotic tissue, formation of a protective barrier, maintenance of microenvironment balance, interaction with immune cells, and formation of the glial scar. Reactive astrocytes (RAs), the main component of the glial scar around the lesion core, have traditionally been considered a primary obstacle to axonal regeneration and functional recovery. Yet astrocytes have both neuroprotective and neurotoxic roles, and prior attempts to block glial scar formation (e.g., Gfap/Vim double knockout, conditional Stat3 knockout, ablation of scar-forming astrocytes) failed to promote axon regeneration and instead worsened injury, underscoring the need to understand astrocyte heterogeneity.

Neuroinflammation and ischemia are known to induce two reactive astrocyte types, "A1" (harmful) and "A2" (helpful). However, the astrocyte subtypes arising from SCI had not been clearly defined. This study uses single-cell RNA sequencing to build a high-resolution transcriptomic profile of astrocytes across the acute, subacute, and intermediate phases after mouse hemisection SCI, aiming to characterize their heterogeneity and dynamic evolution.

---

## Key Experiment Methods

1. Lateral (over-)hemisection SCI at thoracic level T10 in two-month-old C57Bl/6 mice; tissue collected from uninjured cord and at seven time points post-SCI (0.5d, 1d, 3d, 7d, 14d, 60d, 90d), spanning acute, subacute, and intermediate phases (47 mice total).
2. Droplet-based single-cell RNA sequencing (10x Genomics Chromium), NovaSeq6000, aligned to mm10 with Cell Ranger/STAR; quality control and clustering in Seurat (v3), with t-SNE visualization and Louvain graph-based clustering; cell types assigned by SingleR and canonical markers.
3. Astrocyte subclustering: cells selected by expression of astrocyte markers (Gfap, Gss, Aldh1l1, Slc1a3, AldoC, Aqp4, Id3, Fabp7, Lcn2) while excluding Dock2/Cx3cr1 to remove macrophages/microglia; re-scaled and re-clustered.
4. Enrichment analysis (GO/KEGG via Metascape) on up- and down-regulated genes per cluster; cell-proportion tracking across time points; heatmaps of gene expression.
5. Immunofluorescence validation on tissue sections (e.g., Aqp4, Id3, Fabp7, AldoC, GFAP, S100a4, G0S2, C3, Tm4sf1, Mki67, Iba1) including Cx3cr1-Cre (EYFP) reporter mice to test astrocyte/microglia intermediate states.

---

## Results

- 86,972 high-quality cells were clustered into major CNS cell types (microglia, macrophages, granulocytes, endothelial/epithelial cells, erythrocytes, monocytes, astrocytes, oligodendrocytes, B and T cells); microglia and macrophage clusters were phase-dependent.
- Reactive astrocytes did not cluster cleanly by standard methods because RAs adopt non-astrocytic gene expression; 33,692 cells expressing canonical astrocyte markers were selected and re-clustered into 12 clusters, revealing six molecularly distinct astrocyte states: Atp1b2+, S100a4+, Gpr84+, C3+/G0s2+, GFAP+/Tm4sf1+, and Gss+/Cryab+.
- Astrocytes were less heterogeneous in uninjured cord and more diverse after SCI; cluster proportions were phase-dependent, with Clusters 1 and 3 dominating early glial scar (after 7d) and Clusters 2, 5, 9 increasing later to form mature scar.
- Cluster 4 (Atp1b2+, Aqp4/Fabp7/Id3+) represents naïve astrocytes that dropped sharply in the acute phase; residual Cluster 4 cells behaved as A2 (neuroprotective, expressing Ccls/Cxcls/S100a) in acute/subacute phases and shifted toward A1 (Camp, C1q, Eef1a1) at 90d.
- Cluster 1 (Gpr84+) had dual astrocyte/microglia characteristics: 86.9% expressed Cx3cr1; validated by EYFP+/Iba1+ cells co-expressing GFAP or AldoC; associated with necrotic tissue clearance, immune response, and glial scar fibrosis.
- Cluster 3 (S100a4+) was nearly absent in uninjured tissue, peaked at 3d, expressed neuroprotective A2 markers (S100a10, Emp1) and genes consistent with prior bulk-RNA-seq of injured spinal astrocytes, identifying it as neuroprotective A2 astrocytes.
- Clusters 2, 5, 9 were Gfap-low, high in Lcn2/Vim/C3, and specifically expressed the cell-cycle regulator G0s2 (co-expressed with C3/Vim/Lcn2 but not Gfap).

---

## Perspective

This work provides one of the first single-cell, time-resolved atlases of astrocyte heterogeneity across the full course of SCI, defining six transcriptionally distinct astrocyte states and tracking their dynamic evolution and shifting A1/A2-like functions. The discovery that the same naïve population (Cluster 4) can evolve toward neuroprotective (acute/subacute) or neurotoxic (chronic) fates, and that an astrocyte-microglia intermediate state (Gpr84+ Cluster 1) participates in scar and debris clearance, reframes reactive astrogliosis as a heterogeneous, stage-dependent process rather than a uniformly inhibitory response. These signatures offer candidate targets (e.g., specific subtypes/markers) for promoting spinal cord repair.

Limitations noted in the text include the failure to capture adult neurons due to their fragility during enzymatic dissociation, inclusion of blood-borne macrophages because tissue was not perfused, and the descriptive/correlative nature of the subtypes (functions inferred from GO enrichment and marker co-expression rather than functional perturbation). Future work should functionally test whether manipulating specific astrocyte subtypes improves regeneration and recovery.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
