---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
---

# Cell type-specific transcriptome analysis unveils secreted signaling molecule genes expressed in apical epithelial cap during appendage regeneration

## Citation (NLM)
Okumura A, Hayashi T, Ebisawa M, Yoshimura M, Sasagawa Y, Nikaido I, Umesono Y, Mochii M. Cell type-specific transcriptome analysis unveils secreted signaling molecule genes expressed in apical epithelial cap during appendage regeneration. Dev Growth Differ. 2019;61(9):447-456. doi:10.1111/dgd.12635

**DOI:** [https://doi.org/10.1111/dgd.12635](https://doi.org/10.1111/dgd.12635)

---

## Background
Amphibians and fishes can regenerate amputated appendages (limb, tail, fins) through proliferation and differentiation of remaining stem/progenitor cells. The first critical step of successful appendage regeneration is formation of the wound epidermis (WE), which in amphibians thickens distally into a specialized multilayered structure called the apical epithelial cap (AEC). WE/AEC are believed to trigger and sustain regeneration by releasing secreted signaling molecules that regulate the recruitment, proliferation, and differentiation of underlying cells. Prior work established roles for FGF (especially FGF8), Wnt, BMP, TGFβ, Notch, and ROS signaling in WE/AEC of various regenerating systems, but the comprehensive gene expression profile of WE/AEC cells remained unclear.

The authors previously identified Xenopus laevis *es1*, expressed abundantly in AEC cells during tadpole tail regeneration, and generated an *es1:egfp* transgenic reporter line marking WE and AEC after tail amputation. Here they used this line to isolate WE/AEC cells and catalogue the signaling molecule genes they express, comparing tail versus limb bud AEC.

---

## Key Experiment Methods
1. Used *es1:egfp* transgenic Xenopus laevis tadpoles (NF stage 49-51) in which WE/AEC cells are labeled with EGFP; hind-limb bud experiments used NF stage 52-53.
2. Amputated tails and dissociated tail stump tissue (collagenase/EDTA); isolated EGFP-positive WE/AEC cells at 1, 2, 3, and 4 days post-amputation (dpa) by fluorescence-activated cell sorting (FACS). Uncut controls were sorted from wild-type tadpoles labeled with Alexa488-WGA.
3. Performed whole-transcriptome shotgun RNA sequencing on triplicate pools of 100 sorted cells per condition using Quartz-Seq whole-transcript amplification and Illumina HiSeq2500; mapped to X. laevis v9.1 genome and quantified as TPM.
4. Differential expression analysis with edgeR (padj < 0.05); hierarchical clustering and PCA to assess sample similarity.
5. Gene ontology enrichment analysis via DAVID using human orthologs of expressed genes.
6. Manual curation of 649 candidate secreted signaling molecule genes (excluding ECM components/remodelers) using GeneCards and UniProt.
7. Whole-mount and section in situ hybridization (DIG-labeled probes) to validate spatial expression of candidate genes in regenerating tail and limb bud.

---

## Results
- From 45,099 detected transcripts, 8,017 differentially expressed genes (DEGs) were identified across conditions. Triplicates clustered tightly; the largest difference was between uncut and amputated samples, and a clear shift occurred between the early (1-2 dpa) and late (3-4 dpa) phases.
- More than 8,000 genes changed dynamically during tail regeneration, including genes in ROS, FGF, canonical/non-canonical Wnt, TGFβ, and Notch pathways.
- GO enrichment: 1 dpa WE enriched for wound-healing terms (cellular response to hydrogen peroxide, ROS metabolic process, FGF receptor signaling, Ras signal transduction); "epithelial to mesenchymal transition" enriched at 2 dpa; cell-division terms enriched at 3-4 dpa (late-stage proliferation).
- More than 100 candidate secreted signaling molecule genes were expressed in WE/AEC cells, including *bmp*, *wnt*, and *tgfβ* ligand genes, indicating WE/AEC releases a cocktail of molecules rather than a few.
- Seven signaling molecule genes were newly identified as highly expressed in tail AEC: *mdk*, *fstl*, *slit1*, *tgfβ1*, *bmp7.1*, *angptl2*, and *egfl6*.
- In situ hybridization confirmed *mdk*, *fstl1*, *slit1*, *tgfβ1*, and *bmp7.1* are expressed in AEC of BOTH tail and limb bud ("pan-AEC factors"), while *angptl2* and *egfl6* are specific to tail AEC.
- Notably, *fgf8* was NOT expressed in tail WE/AEC (only low *fgf20* and *fgf13*), despite being expressed in limb-bud AEC — so *fgf8* is a limb-specific AEC factor. This is consistent with regenerating notochord (not WE/AEC) being the major FGF/SHH source in the tail.
- Findings partly align with Aztekin et al. (2019) regeneration-organizing cells (ROCs): both lack *fgf8*, but differ in other FGF expression and in resident vs injury-induced status, and were isolated at different developmental stages.

---

## Perspective
This study provides one of the first cell type-specific, time-resolved transcriptomic catalogues of WE/AEC signaling molecules during Xenopus tail regeneration, distinguishing shared "pan-AEC" factors from appendage-specific factors. It challenges the assumption that FGF8 is a universal AEC-derived regeneration factor, showing that the source of FGF ligands varies by system (notochord in tail, AEC in limb bud). The identification of tail-specific factors (ANGPTL2, EGFL6) suggests roles in tail-specific tissues such as notochord and vasculature. The regenerating tail contains spinal cord, notochord, and muscle, making these AEC-derived signals relevant to understanding how CNS/spinal cord tissue is regenerated within an appendage.

Limitations include reliance on the *es1:egfp* reporter (which may not capture all WE/AEC subpopulations), section in situ detection limits for lower-abundance transcripts, and the functional roles of the newly identified genes remaining untested. Future work should functionally validate candidate factors (e.g., ANGPTL2/EGFL6 in tail regeneration) and clarify the relationship between es1-labeled cells and ROCs across developmental stages.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
