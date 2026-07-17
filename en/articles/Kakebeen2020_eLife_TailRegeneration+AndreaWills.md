---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p04.txt
raw_data:
  - "GEO: GSE146837"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Chromatin accessibility dynamics and single cell RNA-Seq reveal new regulators of regeneration in neural progenitors

## Citation (NLM)
Kakebeen AD, Chitsazan AD, Williams MC, Saunders LM, Wills AE. Chromatin accessibility dynamics and single cell RNA-Seq reveal new regulators of regeneration in neural progenitors. eLife. 2020;9:e52648. doi:10.7554/eLife.52648

**DOI:** [https://doi.org/10.7554/eLife.52648](https://doi.org/10.7554/eLife.52648)

---

## Background
Unlike mammals, Xenopus tadpoles achieve scarless healing and full regeneration of the limb, spinal cord, and tail, but this capacity declines at metamorphosis and is lost in the adult, making Xenopus a valuable model for studying the cell-intrinsic and -extrinsic properties governing regeneration. Injury triggers rapid transcriptional remodeling that partly recapitulates developmental signaling (Wnt, FGF, BMP, TGF-β, Notch, Shh). However, prior genome-wide studies were performed on bulk regenerating tissue, obscuring which cell types drive specific expression changes and which transcription factors interpret injury cues.

Neural progenitor cells (NPCs) are a critical cell type for spinal cord regeneration and a focus of regenerative-medicine efforts to restore motor function. During development, neural stem cells give rise to lineage-restricted progenitor domains, and the decision to exit the cell cycle and differentiate is directed by extrinsic cues such as Notch repression. To define the gene regulatory dynamics governing NPC fate decisions during regeneration, the authors profiled chromatin accessibility and transcription specifically in pax6-expressing NPCs from regenerating Xenopus tropicalis tails.

---

## Key Experiment Methods
1. Used the Xtr.Tg(pax6:GFP) transgenic line to mark NPCs; confirmed GFP colocalization with Sox2 and pax6 domain around the central canal, distinct from differentiated-neuron markers (Dcx, neurofilament).
2. FACS-isolated pax6:GFP+ cells and prepared ATAC-Seq libraries from sorted NPCs ("pax6") and bulk tail tissue ("all-tissue") at 0, 6, 24, 72 hpa plus uninjured tips; QC'd against ENCODE ATAC-Seq standards.
3. Differential accessibility analysis and GO:BP analysis (gProfileR2, ReviGO) across timepoints; MDS clustering; peak-to-TSS annotation.
4. scRNA-Seq of neural cells from uninjured (2617 cells) and 24hpa (1090 cells) tails; Seurat integration, UMAP clustering, cell-cycle phase prediction; identified 8 neural sub-clusters.
5. Gene regulatory network prediction integrating ATAC-Seq (HOMER motif analysis), bulk RNA-Seq, and scRNA-Seq differential expression.
6. Functional validation of Meis1 and Pbx3 by translation-blocking morpholinos, second independent morpholinos, CRISPR/Cas9 guides, and tissue-permeable vivo-morpholinos injected at stage 35; assessed neurofilament staining, regenerated tail/spinal cord length, spinal cord area, and PH3+ mitotic cells; validated marker genes by in situ hybridization.

---

## Results
- ATAC-Seq of sorted NPCs revealed neural-specific accessible regions (3604 regions more accessible than bulk, enriched for "Neurogenesis," "Nervous system development") undetectable in bulk-tissue analysis.
- Temporal accessibility shifted priorities: tubule/ependymal morphogenesis at 6hpa, neuronal differentiation at 24hpa, and neural precursor proliferation at 72hpa.
- scRNA-Seq resolved 8 neural sub-clusters (spinal cord progenitors, floor plate progenitors, differentiating neurons, interneurons, motor neurons, vulnerable motor neurons, leptin+ motor neurons, dopaminergic neurons) with new candidate markers; unlike axolotl limb connective tissue, Xenopus neural cells maintained heterogeneous identity after injury.
- At 24hpa, NSCs dropped 38%→25%, differentiating neurons 20%→10%, and differentiated neurons rose 42%→65%, with a cell-cycle shift toward G1 — supporting early prioritization of differentiation (especially motor neurons and interneurons) over proliferation.
- Gene regulatory network prediction identified Meis1 and Pbx3 (homeodomain TFs) as candidate regulators; both are expressed in neural cells, increase in motor/inter/dopaminergic neurons at 24hpa, and share overlapping target regions (Meis1 targets peak at 24hpa, Pbx3 at 72hpa).
- Knockdown of either Meis1 or Pbx3 (morpholino, vivo-MO, or CRISPR) produced shortened regenerated tails and spinal cords, reduced spinal cord area, and disorganized/reduced neurofilament staining, establishing both as necessary for successful tail and spinal cord regeneration.

---

## Perspective
This study advances vertebrate regeneration biology by combining cell-type-specific ATAC-Seq (via FACS) with scRNA-Seq to define the gene regulatory landscape of NPCs — revealing regulatory peaks invisible to bulk analysis and bringing lowly-expressed, lineage-restricted regulators (pbx3, meis1) to the top of candidate lists. A central conceptual insight is the temporal uncoupling of differentiation and proliferation: pax6+ progenitors prioritize neuronal differentiation before proliferation, an intriguing counterpoint to embryonic development where progenitors proliferate before neurogenesis. Limitations acknowledged include incomplete capture of NPCs (some Sox2+/pax6- cells, dorsal-most progenitors excluded), possible inclusion of recently-differentiated pax6+/Sox2- cells retaining GFP, and unverified marker colocalization during the earliest regeneration stages. Future work with additional and region-specific reporters, birthdating, and single-cell approaches could distinguish direct neuronal versus environmental actions of hit genes and fully resolve progenitor subtype priorities.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE146837


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
