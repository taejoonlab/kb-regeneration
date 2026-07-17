---
tags: [2026-07]
extract: 2026-07-16
---

# Diversified transcriptional responses of myeloid and glial cells in spinal cord injury shaped by HDAC3 activity

## Citation (NLM)
Wahane S, Zhou X, Zhou X, Guo L, Friedl MS, Kluge M, Ramakrishnan A, Shen L, Friedel CC, Zhang B, Friedel RH, Zou H. Diversified transcriptional responses of myeloid and glial cells in spinal cord injury shaped by HDAC3 activity. Sci Adv. 2021;7(9):eabd8811. doi:10.1126/sciadv.abd8811

**DOI:** [https://doi.org/10.1126/sciadv.abd8811](https://doi.org/10.1126/sciadv.abd8811)

---

## Background

Microglia are the resident myeloid cells of the CNS and help maintain homeostasis; upon injury they are rapidly activated and, together with blood-derived macrophages, form the innate immune response (injury-activated microglia/macrophages, IAM). Prolonged inflammatory phenotypes of IAM are thought to worsen secondary neuronal damage after spinal cord injury (SCI), so understanding the diversity and regulation of these responses is central to neural repair. A key open question is whether IAM share hallmark genes and regulatory mechanisms with the disease-associated microglia (DAM) described in neurodegeneration (e.g., Alzheimer's disease, ALS).

Immune activation requires large-scale gene reprogramming governed by chromatin modification. The authors had previously shown that histone deacetylase 3 (HDAC3) is up-regulated in IAM after SCI and that pharmacological HDAC3 inhibition suppresses inflammation and improves recovery. Here they combine myeloid-specific bulk transcriptomics with single-cell RNA-seq to define the temporal and cell-type diversity of myeloid and glial responses to SCI and to map the extent of HDAC3's influence.

---

## Key Experiment Methods

1. Cx3cr1CreER INTACT mouse model with tamoxifen-induced GFP tagging of myeloid nuclear envelopes; INTACT (isolation of nuclei tagged in specific cell types) immunopurification of GFP-labeled nuclei from snap-frozen spinal cord to avoid dissociation-induced artifacts.
2. Bulk RNA-seq (triplicate cDNA libraries) on immunopurified myeloid nuclei at 3, 7, and 14 days post injury (dpi) after T8 dorsal column transection, versus laminectomy-only controls; qRT-PCR specificity controls.
3. Analyses: UMAP, k-means clustering, non-negative matrix factorization (NMF), hierarchical gene clustering, weighted gene coexpression network analysis (WGCNA), differential exon usage (alternative splicing), GO/Ingenuity Pathway Analysis (IPA), GSEA (M1 vs M2 polarization), upstream regulator and interactome analysis.
4. Comparison of IAM signatures to published DAM signatures and to neurodegeneration-associated microglial gene sets (connectivity map).
5. Functional recovery study with the specific HDAC3 inhibitor RGFP966 (HDAC3i), comparing acute (2, 24, 48 h) versus subacute regimens by Basso Mouse Scale (BMS) scoring.
6. Single-cell RNA-seq (10X Genomics) of injured spinal cord at 5 dpi (T8 contusion) across three conditions: CTRL (uninjured reference), SCI, and SCI_HDAC3i; 9937 cells total, with unbiased clustering, subclustering, and Slingshot single-cell trajectory analysis.
7. Immunohistochemistry validation (IBA1, Tmem119, LPL, CD11c, P2ry12, SPP1, FN, HDAC3, etc.).

---

## Results

- INTACT bulk RNA-seq showed temporally distinct IAM transcriptional programs, with 3-dpi samples most divergent. Four gene clusters mapped to proliferation/migration/ECM (up at 3 dpi), metabolism/RNA processing (down at 3 dpi), neuronal interaction (down 7 dpi, up 14 dpi), and nervous-system development/ECM (down across time). WGCNA identified 103 modules, 13 significantly enriched for these clusters.
- 131 core IAM genes shared across all time points (104 up, 27 down) were enriched for phagosome and lipid-metabolism pathways, including DAM markers Apoe and Lpl, plus Axl, Ctsb, Ctsd, Grn, Abca1, Abcg1, and immunity/ECM genes (Spp1, Fn1, Ccl3, Csf1, Igf1). Voltage-gated Ca2+ channel genes (Cacnab2, Hcn1, Slc24a2, Trpc5) were down-regulated.
- IAM and DAM shared 11 genes (immunity, scavenging, tissue repair). Notably, the DAM markers Trem2 and Tyrobp were NOT significantly up-regulated in IAM, a key distinction from neurodegeneration-associated microglia.
- Despite up-regulation of many inflammatory genes, IAM did not show a predominant proinflammatory profile: only 9 of 57 proinflammatory genes were significantly up, and GSEA indicated an overall reparative (M2-leaning) profile across all time points. Time-resolved events: cell cycle + interferon signaling at 3 dpi, migration + ion-channel changes at 7 dpi, ECM reorganization + LXR/RXR at 14 dpi. IAM used extensive alternative splicing, greatest at 3 dpi (1361 differential exons).
- Upstream regulators of the IAM program (CSF2, LPS, IL-6, IFN, TGFβ1; p53/CDKN1A as negative regulators; TFs NFκB, STAT, IRF families) were linked by interactome analysis to HDAC3. Acute HDAC3i (RGFP966) improved BMS locomotor recovery better than a subacute regimen.
- scRNA-seq at 5 dpi identified nine cell clusters (oligodendrocytes, myeloid, endothelial, neurons, astrocytes, neutrophils, OPCs, pericytes, and an OPC/Oligo transitional cluster). SCI expanded immune and vascular populations and the OPC/Oligo transitional cluster; HDAC3i modestly shifted distributions (smaller neutrophil cluster, modest neuronal/oligodendrocyte expansion). Hdac3 mRNA was heterogeneous across cells and unchanged by SCI, implying post-transcriptional regulation of HDAC3 protein.
- Microglia and macrophages remained transcriptionally distinct even after injury (916 DEGs between them). HDAC3 dependence differed by cell type: in microglia, HDAC3-dependent genes concerned proliferation, chemokine/cytokine activity, synaptogenesis, and PI3K/AKT; in macrophages, xenobiotic metabolism, leukocyte migration, and survival. ~20% of HDAC3-dependent genes were shared (chemotaxis, chemokine, RANKL, p38 MAPK).
- Myeloid cells resolved into four microglial (MG1–MG4) and four macrophage (Mac1–Mac4) subtypes with specialized tasks: MG1 immune/homeostatic, MG2 phagocytosis/lipid metabolism (reactive, TyroBP/TGFβ), MG3 immediate-response (BDNF signaling, IEGs Fos/Jun/Egr1), MG4 proliferative (Cdk1, Top2a, p53 signaling; preferential Hdac3 expression). All four MG states existed even in healthy spinal cord, revealing baseline microglial heterogeneity.
- SCI expanded MG1 and MG2 (MG2 rising most, from 5% to 22% of microglia) and contracted MG3 and MG4. Slingshot trajectory ran MG3→MG1→MG2→MG4; HDAC3i shifted the starting point from MG3 to MG4 (trajectory MG4→MG2→MG1→MG3), consistent with HDAC3 controlling proliferation and chemokine/RANKL activation.
- Macrophage subtypes (Mac1 dominant, ~75%) carried both IAM and DAM hallmarks; IAM/DAM core signatures were predominantly enriched in Mac1 and the reactive microglial subset MG2, highlighting functional convergence on phagocytosis and debris clearance.
- A distinct ependymal population (Sox2, Foxj1, Riiad1) separated from neurons; SCI contracted neuronal populations but markedly expanded reactive ependymal cells (ECM organization; Wnt, Hedgehog, PDGF-B signaling). HDAC3i affected 448 ependymal genes, 78% repressed by HDAC3 (Frizzled/integrin binding, collagen biosynthesis).

---

## Perspective

This work provides an integrated bulk (myeloid-specific INTACT) and single-cell atlas of the innate immune and glial response to spinal cord injury, and positions HDAC3 as a broad epigenetic regulator acting across microglia, macrophages, and ependymal cells. Conceptually important findings are: (1) injury-activated microglia adopt an overall reparative rather than purely proinflammatory profile; (2) IAM and DAM share a lipid-metabolism/phagocytosis core yet differ in Trem2/Tyrobp usage; (3) microglial heterogeneity (MG1–MG4) exists even in healthy cord, with an immediate-response MG3 acting as a source state and a proliferative MG4 preferentially expressing HDAC3; and (4) HDAC3 inhibition, most effective when given acutely, reshapes microglial transformation trajectories and improves locomotor recovery. This nominates HDAC3 as a therapeutic target for tuning innate-immune responses after SCI.

Limitations include cell-type frequency estimates that can be biased by dissociation fragility and capture efficiency, use of two SCI models (dorsal column transection for INTACT vs. contusion for scRNA-seq), a single scRNA-seq time point (5 dpi), the tamoxifen-labeling scheme favoring microglia over peripheral macrophages, and the fact that HDAC3 regulation appears largely post-transcriptional (protein up-regulated without mRNA change). Future directions include defining the mechanistic targets of HDAC3 in each glial subtype and optimizing HDAC3i timing to maximize functional recovery.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
