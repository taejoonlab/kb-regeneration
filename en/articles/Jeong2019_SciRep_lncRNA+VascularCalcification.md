---
tags: [2026-07, Ossification]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# Long noncoding RNAs in vascular smooth muscle cells regulate vascular calcification

## Citation (NLM)

Jeong G, Kwon DH, Shin S, Choe N, Ryu J, Lim YH, Kim J, Park WJ, Kook H, Kim YK. Long noncoding RNAs in vascular smooth muscle cells regulate vascular calcification. Sci Rep. 2019;9(1):5848. doi:10.1038/s41598-019-42283-x

**DOI:** [https://doi.org/10.1038/s41598-019-42283-x](https://doi.org/10.1038/s41598-019-42283-x)

---

## Background

Vascular calcification is the pathological accumulation of hydroxyapatite crystals in the vessel wall, resulting from an imbalance of calcium-phosphate metabolism. It reduces vessel elasticity and raises the risk of myocardial ischemia, heart failure, and arrhythmias. Once considered a passive degenerative process, vascular calcification is now recognized as an active, cell-mediated process that shares features with bone formation: mature vascular smooth muscle cells (VSMCs) undergo "phenotype switching" from a contractile to an osteoblastic/chondrogenic phenotype, upregulating osteoblast-related factors such as Runx2, BMPs, and Msx2 while downregulating contractile markers. Although microRNAs in cardiovascular disease are well studied, the role of long noncoding RNAs (lncRNAs) in vascular calcification had not been reported. This study set out to identify lncRNAs differentially expressed during VSMC calcification and to define their function.

---

## Key Experiment Methods

**1. Calcification model and RNA sequencing**
- Primary rat VSMCs treated with 2 mM inorganic phosphate (Pi) for 6 h, 3 days, or 6 days to mimic calcification
- Ribo-Zero total RNA-seq (HiSeq 2500, paired-end, duplicate); merged Ensembl + RefSeq annotations (8,357 reference lncRNAs); Cufflinks assembly identified 1,201 novel rat lncRNAs

**2. Candidate lncRNA selection and characterization**
- Three criteria: differential expression on Pi treatment, cross-species locus conservation, and neighboring gene with a known calcification role → four candidates (Snhg1, Linc00116, Snhg16, Lrrc75a-as1)
- qRT-PCR validation; 5′/3′ RACE for full-length transcript structure; subcellular fractionation (A10 cells) for localization; CPC/CPAT coding-potential assessment (Linc00116 excluded for moderate coding potential)

**3. Functional gain/loss of function**
- Overexpression of candidate lncRNAs (pcDNA3) and knockdown of Lrrc75a-as1 by two siRNAs in A10 vascular smooth muscle cells
- Calcium deposition by colorimetric assay and Alizarin red S staining/quantification
- qRT-PCR of osteoblast-related factors Runx2, Msx2, Bmp2

**4. Regulatory network analysis**
- miRNA target prediction (miRNA_Targets) intersected with VSMC calcification miRNA profiles → miR-29a-3p, miR-24-3p
- ENCODE ChIP-seq analysis of the human LRRC75A-AS1 promoter for VSMC-relevant transcription factors (SRF, CREB1, STAT3)

---

## Results

**Hundreds of lncRNAs change during calcification; four candidates selected**
RNA-seq revealed hundreds of differentially expressed lncRNAs in Pi-treated VSMCs, with pathway analysis confirming downregulation of VSMC-contraction genes (successful phenotype switch). Four candidates (Snhg1, Linc00116, Snhg16, Lrrc75a-as1) passed the selection criteria and were qRT-PCR validated. Lrrc75a-as1, Snhg16, and Linc00116 localized to the cytoplasm; Snhg1 to the nucleus.

**Lrrc75a-as1 is a negative regulator of calcium deposition**
The candidates were downregulated by Pi. Overexpression of Lrrc75a-as1 (and, less potently, Snhg16) reduced calcium deposition in A10 cells. Because Lrrc75a-as1 had the strongest effect it was selected for follow-up. Knockdown of Lrrc75a-as1 by both siRNAs augmented calcium deposition, corroborated by increased Alizarin red S staining.

**Lrrc75a-as1 suppresses osteoblast-related factors**
Overexpression of Lrrc75a-as1 markedly reduced mRNA of the osteoblast-related factors Runx2, Msx2, and Bmp2 — the same osteogenic switch that drives VSMC transdifferentiation — indicating that Lrrc75a-as1 acts by dampening the osteoblastic phenotype program.

**Proposed regulatory mechanism**
As a cytoplasmic lncRNA, Lrrc75a-as1 is predicted to act as a miRNA sponge; among 47 predicted partners, miR-29a-3p and miR-24-3p (both implicated in VSMC calcification/phenotype transition) had binding sites. Promoter ChIP-seq implicated calcification-associated transcription factors SRF, CREB1, and STAT3 as upstream regulators. The human/mouse orthologous loci also host snoRNAs (Snord49a/b, Snord65), suggesting an additional possible layer of function.

---

## Perspective

This is the first report identifying an lncRNA that directly regulates vascular calcification, establishing Lrrc75a-as1 as a negative regulator that suppresses calcium accumulation by downregulating the osteoblast-related factors Runx2, Msx2, and Bmp2.

The finding sits squarely within the vault's ossification theme through the concept of osteogenic phenotype switching: VSMC calcification recapitulates a bone-formation program (Runx2/BMP2/Msx2), and Lrrc75a-as1 opposes precisely this osteoblastic transdifferentiation. This parallels the osteoblast-lineage transcriptional programs seen across the vault's bone and ectopic-ossification papers, but places a noncoding-RNA brake on the pathway.

Mechanistic details remain open: the direct calcium-regulatory target of Lrrc75a-as1 is unknown, and the proposed miR-29a-3p/miR-24-3p sponging and SRF/CREB1/STAT3 promoter regulation require experimental validation. The lncRNA is nonetheless proposed as a potential therapeutic target for vascular calcification and related cardiovascular diseases.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
