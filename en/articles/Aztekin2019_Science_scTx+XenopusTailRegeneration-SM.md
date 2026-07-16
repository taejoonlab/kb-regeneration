---
tags: [2026-07]
extract: 2026-07-16
---

# Identification of a regeneration-organizing cell in the Xenopus tail (Supplementary Materials)

## Citation (NLM)
Aztekin C, Hiscock TW, Marioni JC, Gurdon JB, Simons BD, Jullien J. Identification of a regeneration-organizing cell in the Xenopus tail. Science. 2019;364(6441):653-658. doi:10.1126/science.aav9996 [Supplementary Materials, Materials and Methods, Figs. S1-S11, Tables S1-S3]

**DOI:** [https://doi.org/10.1126/science.aav9996](https://doi.org/10.1126/science.aav9996)

---

## Background
This is the Supplementary Materials document accompanying the *Science* research article that identified the regeneration-organizing cell (ROC) in the regenerating *Xenopus laevis* tail. It provides the detailed Materials and Methods and supplementary figure/table descriptions underpinning the main study, in which scRNA-seq of regeneration-competent and -incompetent tadpoles revealed a LEF1+/TP63+ epidermal cell type that relocalizes to the amputation plane to form the specialized wound epidermis and acts as a signaling center for regeneration.

---

## Key Experiment Methods
1. **Tadpole husbandry and regeneration assays:** *X. laevis* raised in 0.1X MMR; regeneration-competent staged NF 40-41, incompetent NF 46-47; ~30-50% tail amputated; scored at 7 dpa (excellent/good/partial/none) and converted to a numeric regeneration index (3/2/1/0 points).
2. **Single-cell dissociation and sequencing:** tails dissociated with trypsin, sorted for live single cells (PI-negative, Hoechst-positive) on a Sony SH800s; 10X Genomics libraries sequenced on Illumina HiSeq 4000.
3. **Data processing:** CellRanger v2.1.0 aligned to *Xenopus laevis* 9.1 genome (Xenbase); normalization to transcripts-per-10^4 (TPX); allele-specific (Gene.L / Gene.S) expression retained given pseudotetraploidy.
4. **Visualization/clustering:** highly variable genes (Fano factor) selected; UMAP projection; fuzzy-simplicial-set graph + walktrap clustering; 46 clusters annotated from marker genes (fig. S1); 23/46 clusters given broad labels.
5. **Differential abundance:** edgeR following the cydar mass-cytometry method, comparing regeneration-competent vs. -incompetent at 1 dpa.
6. **GO / gene-set enrichment:** findMarkers (scran) for ROC markers; GO enrichment on human orthologs; scGSEA via AUCell; cell-cycle phase via Seurat CellCycleScoring.
7. **Microsurgery / grafting:** "large" (tail-bud progenitors + skin) and "small" (skin only) grafts to host trunk regions.
8. **Immunofluorescence:** TP63, EGFP, PCNA, PHH3, NCAM1, COL2A1 antibodies; live imaging of pbin7Lef:GFP tadpoles.
9. **Chemical perturbations:** DPI, SU5402 (FGF), SB-505124 (TGFβ) to assess ROC mobilization.
10. **Genetic ablation:** Krt.L:CFP-NTR transgenesis + metronidazole (MTZ); NTR/MTZ ablation combined with grafting.

---

## Results
- **Fig. S1:** cell-state identification for all 46 clusters (skin, immune/RBC, somite, nervous system); neuronal differentiation markers Hes1 (progenitors/floor plate), Neurod4 (differentiating neurons), Tubb3 (terminal neurons).
- **Fig. S2:** biological replicates mingle across the UMAP, confirming atlas reproducibility.
- **Fig. S3:** inferred cell-cycle phases separate progenitors, terminally differentiated cells, and cycling erythrocytes (GATA1:GFP+ / PCNA+ / PHH3+).
- **Fig. S4:** pairwise sample comparisons separate developmental, amputation, and regeneration-specific changes; differential abundance ranks ROC change as the most significant regeneration-specific event at 1 dpa.
- **Fig. S5:** ROCs identified as TP63+/LEF1+ regeneration-specific epidermal cells at the amputation plane; removed after amputation and reappearing at the wound epidermis only in competent tadpoles.
- **Fig. S6-S7:** Krt.L:NTR/MTZ specifically ablates ROCs without gross off-target effects; genetic ablation or manual extirpation reduces regeneration; extent of ROC removal correlates with regeneration outcome.
- **Fig. S8:** DPI and SB-505124 (TGFβ) block ROC mobilization, whereas FGF inhibition (SU5402) does not.
- **Fig. S9:** ROCs express high ligand levels and progenitors express receptors across FGF, BMP, WNT, TGFβ, and Notch-Delta pathways (complementary receptor/ligand pairing).
- **Fig. S10:** ROC transcriptome enriched for limb-development genes and GO terms.
- **Fig. S11:** transplants of ROC-containing regions induce ectopic tail-like (large graft) or fin-enriched (small graft) structures; Krt.L:NTR/MTZ ablation of donor ROCs significantly reduces outgrowth length.
- **Tables S1-S3:** scRNA-seq QC summary (>13,000 cells), published ROC marker genes at the midline epidermis, and gene lists for cell-cycle/scGSEA analysis.

---

## Perspective
The Supplementary Materials document the computational and experimental rigor behind the ROC discovery: reproducible replicate structure, differential-abundance ranking that pinpoints ROCs as the dominant regeneration-specific change, and orthogonal functional validation (genetic ablation, manual extirpation, chemical perturbation, and grafting). Together these support the main conclusion that ROCs form the specialized wound epidermis and act as a ligand-secreting signaling center.

Limitations noted in the supplement include the low replicate number for differential-abundance testing (n = 2, inflating test statistics), the inability to unambiguously annotate roughly half of the clusters, and reliance on the pseudotetraploid *X. laevis* genome requiring allele-specific interpretation. Future work would extend the atlas-based approach to other regenerating species.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
