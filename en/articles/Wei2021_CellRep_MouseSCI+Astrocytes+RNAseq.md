---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Systematic analysis of purified astrocytes after SCI unveils Zeb2os function during astrogliosis

## Citation (NLM)
Wei H, Wu X, You Y, Cuevas-Diaz Duran R, Zheng Y, Narayanan KL, Hai B, Li X, Tallapragada N, Prajapati TJ, Kim DH, Deneen B, Cao QL, Wu JQ. Systematic analysis of purified astrocytes after SCI unveils Zeb2os function during astrogliosis. Cell Rep. 2021;34(5):108721. doi:10.1016/j.celrep.2021.108721

**DOI:** [https://doi.org/10.1016/j.celrep.2021.108721](https://doi.org/10.1016/j.celrep.2021.108721)

---

## Background
Spinal cord injury (SCI) is a devastating neurological condition with no effective therapy. Astrocytes are the predominant component of the glial scar; after injury they become reactive, proliferate, and can serve both protective (limiting inflammatory spread, promoting tissue repair) and inhibitory (secreting molecules that block axonal regeneration) roles. Understanding reactive astrogliosis is therefore central to developing SCI therapies.

Long non-coding RNAs (lncRNAs, >200 nt) regulate many CNS processes but their functions in reactive astrogliosis remain a knowledge gap. This study systematically profiles coding and long non-coding gene expression in SCI epicenter tissue and in purified astrocytes from acute to chronic stages, and identifies a highly conserved lncRNA, Zeb2os, as a functional regulator of astrogliosis via a Zeb2os/Zeb2/Stat3 axis.

---

## Key Experiment Methods
1. RNA-seq of SCI epicenter tissue at acute (2D, 7D) and chronic (1M, 3M) stages using a moderate contusive SCI model; hierarchical clustering of 6,453 DEGs (5,675 coding, 778 lncRNAs).
2. Comprehensive lncRNA annotation (GENCODE + NCBI); cross-species (mouse vs rat) DEG comparison to find common bioprocesses.
3. Homology analysis of upregulated lncRNAs (slncky); "guilt-by-association" correlation with coding genes; TF-binding motif search (FIMO/ENCODE) in DE lncRNA promoters.
4. STAT3 ChIP-seq on sham and injured (7D) epicenter tissue; GSEA of STAT3 targets.
5. FACS purification of astrocytes from GFAP-Cre:R26-tdT mice at 7D, 1M, 3M post-injury; RNA-seq and IPA pathway analysis; comparison of purified astrocyte vs bulk tissue transcriptomes.
6. Zeb2os and Zeb2 shRNA knockdown (lentivirus) in primary astrocytes; RNA-seq, qPCR, BrdU proliferation, scratch/migration assays; RNAscope + immunostaining for Zeb2os/Zeb2 co-localization.
7. Cre-dependent Zeb2os KD eGFP-AAV injected into GFAP-Cre SCI mice at 10 dpi; analysis at 17 dpi of GFAP, pSTAT3, lesion volume, CD68 (neuroinflammation), and 5-HT axon sprouting.

---

## Results
- SCI produced large temporal shifts in both coding genes and lncRNAs; acute stages enriched for proliferation/differentiation, cell cycle, STAT3 and NF-kB signaling, chronic stages for ECM and cell-cell adhesion. Common mouse/rat bioprocesses were identified.
- 297 upregulated DE lncRNAs; 15 conserved between mouse and human. 47% (369/778) of DE lncRNA promoters contained STAT3 motifs, implicating STAT3 as a major lncRNA regulator after SCI. STAT3 ChIP-seq found 13,465 targets, including binding peaks at the Zeb2 promoter.
- Purified astrocytes showed dynamic gene expression; complement pathway (C3, C3ar1) and STAT3 signaling were strongly upregulated. Astrocytes were identified as a key source of both axon-permissive (Lamb1, Ncam1, Bmp7) and inhibitory factors.
- The conserved lncRNA Zeb2os and its antisense coding gene Zeb2 were both upregulated in astrocytes at 7D and remained elevated at 1M and 3M; they co-localized (RNAscope/immunostaining) at the outer nuclear edge and cytoplasm, and Zeb2os expression correlated with Stat3 across injury stages.
- Zeb2os knockdown in primary astrocytes reduced Zeb2os, Zeb2, Gfap, Stat3, integrins, complement genes (C3, C3ar1), scar-formation and inhibitory genes (Ncan, phosphacan, Ephb2/3, Robo1/2, Pten, Sema3f), and decreased astrocyte proliferation (BrdU); Zeb2os KD had a stronger effect than Zeb2 KD. Migration was unaffected.
- In vivo AAV-mediated Zeb2os KD in SCI mice significantly reduced GFAP-IR and pSTAT3-IR areas and lesion volume at 17 dpi, without exacerbating neuroinflammation (CD68 unchanged); a non-significant trend toward increased 5-HT axon sprouting was observed.
- ChIP-seq showed STAT3 binding to the Zeb2 promoter, supporting a Zeb2os/Zeb2/Stat3 regulatory axis. A public resource (GEO: GSE153721) was provided.

---

## Perspective
This study fills a significant gap by defining lncRNA contributions to reactive astrogliosis and establishing Zeb2os as a previously unknown, conserved regulator acting through the Zeb2os/Zeb2/Stat3 axis. Because Zeb2os KD reduces astrogliosis, scar-related gene expression, and lesion volume without worsening inflammation, targeting Zeb2os represents a candidate RNA-based therapeutic strategy for SCI and other diseases involving astrogliosis. Limitations include the correlative nature of some axis links, the modest (non-significant) axon-sprouting effect, and the need for longer survival/functional (behavioral) outcomes. The authors note Zeb2os may have stage-dependent (early protective vs later inhibitory) functions, motivating study of its role in chronic scar progression and combinatorial approaches with growth-supportive interventions.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
