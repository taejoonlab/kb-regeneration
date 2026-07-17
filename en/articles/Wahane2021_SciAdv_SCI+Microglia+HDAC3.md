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
The innate immune response strongly influences neural repair after spinal cord injury (SCI). Microglia, the resident myeloid cells of the CNS, are activated within minutes of injury and, together with blood-borne monocyte-derived macrophages, form injury-activated microglia/macrophages (IAM). Prolonged inflammatory phenotypes of IAM are thought to exacerbate secondary neuronal damage. A key open question is whether IAM share hallmark genes and regulatory mechanisms with neurodegeneration-associated / disease-associated microglia (DAM) seen in Alzheimer's disease and ALS.

The authors had previously shown robust up-regulation of histone deacetylase 3 (HDAC3) in IAM after SCI, and that pharmacological HDAC3 inhibition produced global inflammatory suppression and improved functional recovery. This study dissects, at bulk and single-cell resolution, the diversified transcriptional responses of myeloid and glial cells after SCI and the extent to which HDAC3 shapes them.

---

## Key Experiment Methods
1. Generated Cx3cr1CreER INTACT mice for myeloid-specific nuclear tagging; tamoxifen given before T8 dorsal column transection to GFP-tag myeloid nuclei.
2. INTACT (isolation of nuclei tagged in specific cell types) immunopurification of GFP-labeled myeloid nuclei followed by bulk RNA-seq at 3, 7, and 14 days post injury (dpi) vs laminectomy controls (triplicate libraries).
3. Bioinformatic analyses: UMAP, k-means clustering, non-negative matrix factorization (NMF), hierarchical gene clustering, WGCNA, differential exon usage / alternative splicing, IPA upstream regulator and interactome analysis.
4. Single-cell RNA-seq (10X Genomics) on injured spinal cord at 5 dpi comparing CTRL, SCI, and SCI + HDAC3 inhibitor (RGFP966) conditions (9937 cells total).
5. HDAC3 inhibition functional study (RGFP966, acute vs subacute regimens) with Basso Mouse Scale (BMS) locomotor scoring.
6. Slingshot single-cell trajectory analysis; validation by immunohistochemistry (LPL, CD11c, SPP1, fibronectin, P2ry12, HDAC3).

---

## Results
- INTACT RNA-seq revealed temporally distinct IAM transcriptional programs: proliferation/migration/ECM and interferon signaling dominant at 3 dpi, ion channel/migration at 7 dpi, ECM reorganization at 14 dpi.
- 131 core IAM genes shared across all time points, enriched for phagosome and lipid metabolism (Apoe, Lpl, Axl, Ctsb, Ctsd, Abca1/Abcg1) and LXR/RXR, phagosome maturation, and cholesterol pathways; a second cluster involved immunity (IRF, TLR, TNF signaling).
- Despite up-regulation of inflammatory genes, IAM displayed an overall reparative, anti-inflammatory (M2-leaning) profile; DAM marker genes Trem2 and Tyrobp were NOT significantly up-regulated in IAM, distinguishing IAM from DAM.
- IAM showed extensive alternative splicing (most differential exons at 3 dpi) and partial reactivation of developmental microglial gene programs.
- HDAC3 was identified as closely interacting with upstream regulators of IAM programs; acute HDAC3 inhibition gave better BMS locomotor recovery than subacute treatment.
- scRNA-seq identified nine cell clusters; immune and vascular populations expanded after SCI. Microglia and macrophages remained transcriptionally distinct (916 DEGs). HDAC3 inhibition affected microglia and macrophages differently (55 HDAC3-dependent injury-response genes in microglia linked to proliferation/chemokine activity).
- Myeloid cells resolved into 8 subclusters (MG1-MG4, Mac1-Mac4). MG4 was proliferative and preferentially expressed Hdac3; trajectory analysis showed MG3→MG1→MG2→MG4 progression, which HDAC3i shifted (starting point moved from MG3 to MG4). Microglia showed diverse cell states even in healthy cord.
- A distinct ependymal population (Sox2, Foxj1, Riiad1) expanded after SCI with a reactive signature (ECM, Wnt, Hedgehog, PDGF-B), and 78% of HDAC3-regulated ependymal genes were repressed by HDAC3.

---

## Perspective
This work provides a high-resolution map of the diversified myeloid and glial transcriptional landscape after SCI and positions HDAC3 as a broad epigenetic regulator acting across microglia, macrophages, and ependymal cells. The distinction between IAM and DAM (notably the lack of Trem2/Tyrobp induction) refines how injury versus degeneration reprogram microglia. The identification of an immediate-response microglia subtype serving as a source population and a proliferative HDAC3-controlled subtype suggests targetable nodes to steer myeloid responses toward repair. Limitations include the approximate nature of scRNA-seq cell-frequency estimates (capture bias), the single injury model/time points, and correlative links between HDAC3 and specific subclusters. Future work exploiting HDAC3 modulation with cell-type specificity may enhance functional recovery after SCI.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
