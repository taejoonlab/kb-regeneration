---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
raw_data:
  - "DDBJ: DRA009253, DRA015181"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Regeneration factors expressed on myeloid expression in macrophage-like cells is required for tail regeneration in Xenopus laevis tadpoles

## Citation (NLM)
Deguchi M, Fukazawa T, Kubo T. Regeneration factors expressed on myeloid expression in macrophage-like cells is required for tail regeneration in Xenopus laevis tadpoles. Development. 2023;150(15):dev200467. doi:10.1242/dev.200467

**DOI:** [https://doi.org/10.1242/dev.200467](https://doi.org/10.1242/dev.200467)

---

## Background
Xenopus laevis tadpoles can fully regenerate their tail—including muscle, notochord, and spinal cord—within about one week after amputation. After amputation, lineage-restricted progenitor cells derived from tissue-specific stem cells differentiate to rebuild the tail. The authors had previously shown that interleukin 11 (il11) is induced after amputation and is required and sufficient for producing several types of progenitor cells, and that Il11 acts non-cell-autonomously (even progenitors lacking Il11 receptors contribute to regeneration). This led to the hypothesis that Il11 induces progenitors via a specific supporting cell type.

To identify this putative supporting cell, the authors screened for genes acting downstream of Il11 signaling and identified two previously uncharacterized, homologous genes (Xenopus is allotetraploid) on the L and S chromosomes—Xetrov90002578m.L and Xetrov90002579m.S—which they named regeneration factors expressed on myeloid (rfem.L and rfem.S). The proteins have no recognizable domains (weak similarity to γ-crystallin, no signal peptide, suggesting intracellular function), have a putative orthologue in X. tropicalis, but no orthologues identified in fish or rodents.

---

## Key Experiment Methods
1. Candidate gene screening by re-analysis of published RNA-seq datasets: genes downregulated in il11 KD tails, filtered against proliferating tailbud cells and enriched in the non-proliferating regeneration-bud fraction.
2. Temporal expression analysis by qRT-PCR of tail stumps at 0, 1, 3, 5, 7 dpa (rfem.L/rfem.S normalized to ef1a); primers designed against the consensus sequence to detect both paralogs.
3. In situ hybridization on sagittal sections of intact and 3 dpa tails to localize rfem-expressing cells.
4. Loss-of-function by CRISPR/Cas9 knockdown (KD) of rfem.L and rfem.S (mosaic "crispant" tadpoles; two gRNAs each), with tyrosinase (tyr) KD as control; regeneration scored at 7 dpa (perfect/imperfect; area and length measured with Fiji); editing confirmed by ICE analysis (KO scores).
5. Bulk RNA-seq of rfem KD tail stumps to identify downstream downregulated genes.
6. Single-cell RNA-seq (scRNA-seq, 10x Genomics) of intact tail stump/tip and 2 dpa regeneration bud to identify rfem-expressing cell types (Seurat, UMAP, 50 clusters).
7. csf1 (colony-stimulating factor 1) CRISPR/Cas9 KD to deplete macrophage-lineage cells, quantifying rfem expression and cell numbers.
8. Cell-type-specific rescue by forced rfem.L expression under the zebrafish mpeg1 promoter (mpeg1:rfem vs mpeg1:gfp control) in rfem KD tadpoles via I-SceI-mediated transgenesis.

---

## Results
- rfem.L and rfem.S expression was induced by tail amputation, rising significantly at 1–3 dpa (coinciding with regeneration bud formation) and declining at 5–7 dpa as regeneration completed.
- In situ hybridization showed rfem-expressing cells scattered around the regeneration bud and adjacent regions at 3 dpa but rarely in intact tails; their number increased significantly at the amputation site by 1 dpa, consistent with migration of rfem-expressing cells to the wound.
- CRISPR/Cas9 KD of rfem.L and rfem.S reduced the regeneration rate and produced significantly smaller and shorter tails, often bent in abnormal directions; abnormal morphology persisted with growth and worsened after re-amputation—indicating rfem.L and/or rfem.S are required for normal tail regeneration.
- Bulk RNA-seq of rfem KD stumps found six significantly downregulated genes, including three hemoglobin genes, suggesting effects on wound repair/blood vessel formation.
- scRNA-seq placed rfem.L/rfem.S-expressing cells within a leukocyte cluster with a macrophage-like profile, enriched for c1qc.L, csf1r.S, trem2.S, art5.L, and crp.4.L; expression of c1qc.L and art5.L correlated well with rfem.
- il11ra.L (Il11 receptor subunit) was not detected in rfem-expressing cells, suggesting they are regulated indirectly by Il11 signaling rather than receiving Il11 directly (though low scRNA-seq sensitivity cannot exclude sub-threshold expression).
- csf1 KD (which depletes macrophage-lineage cells) significantly reduced rfem.L/rfem.S expression and cell numbers, and lowered regeneration rates, linking rfem-expressing cells to the Csf1-dependent macrophage lineage.
- Macrophage-like-cell-specific rescue with mpeg1:rfem significantly recovered regenerated tail area and length in rfem KD tadpoles, demonstrating that rfem expression specifically in macrophage-like cells is indispensable for successful tail regeneration.

---

## Perspective
This study identifies rfem.L and rfem.S as novel genes required for Xenopus tail regeneration and shows that their expression in macrophage-like (reparative myeloid) cells is essential for the regeneration-promoting function of these cells. Because leukocytes can both promote (reparative) and impair (inflammatory) regeneration, the rfem-expressing macrophage-like population defines a (sub)population of the previously described reparative myeloid cells, providing a molecular handle on how myeloid cells confer regenerative ability. Since the Xenopus tail regenerates its spinal cord along with muscle and notochord, these findings are relevant to understanding immune-cell contributions to CNS/appendage regeneration. Limitations noted by the authors include the intracellular, uncharacterized nature of the Rfem proteins (function not predictable from sequence), the use of mosaic CRISPR crispants, difficulty designing paralog-specific primers (both paralogs quantified together), the inability to detect a KO-score/regeneration correlation in peripheral blood cells (likely due to the small proportion of rfem-expressing leukocytes), and the lack of orthologues in fish and rodents, which may limit direct translation. The authors propose rfem.L/rfem.S as a clue to the cellular and molecular mechanisms that endow leukocytes with regenerative capacity.

## Data Availability

**Raw data generated by this study:**
- DDBJ: DRA009253, DRA015181


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
