---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
---

# Identifying the key genes regulating mesenchymal stem cells chondrogenic differentiation: an in vitro study

## Citation (NLM)
Liang T, Li P, Liang A, Zhu Y, Qiu X, Qiu J, Peng Y, Huang D, Gao W, Gao B. Identifying the key genes regulating mesenchymal stem cells chondrogenic differentiation: an in vitro study. BMC Musculoskelet Disord. 2022;23:985. doi:10.1186/s12891-022-05958-7

**DOI:** [https://doi.org/10.1186/s12891-022-05958-7](https://doi.org/10.1186/s12891-022-05958-7)

---

## Background

Articular cartilage has limited regenerative capacity, and cartilage defects can progress to osteoarthritis (OA) if not properly treated. Mesenchymal stem cells (MSCs) are a key component of cell-based scaffolds for cartilage defect treatment, and MSC chondrogenic differentiation is central to this process. However, the gene network regulating MSC chondrogenesis is not yet fully understood. While major regulators such as SOX9 and BMP signaling are known, emerging evidence suggests that various participants, including non-coding RNAs and growth factors, form a complex network. This study aimed to analyze temporal gene expression profiles during MSC chondrogenesis using high-density micromass culture systems and to identify key regulatory genes and transcription factors (TFs).

---

## Key Experiment Methods

- **MSC isolation and culture**: MSCs isolated from iliac crest bone marrow aspirates of healthy male donors (mean age 37.6±4.2 years, n=3). Passages 3-5 used.
- **Chondrogenic differentiation**: High-density micromass culture method. Differentiation induced with chondrogenic medium containing TGF-β3 (10 μg/ml) for 7, 14, and 21 days. CHO group: chondrocytes from TKA surgery patients.
- **RNA-seq**: Illumina HiSeq X Ten. DEG analysis by DESeq. Criteria: log2FC>1 or <-1, P<0.05.
- **PPI network analysis**: STRING database, Cytoscape (cytoHubba, MCODE) for hub gene identification.
- **Transcription factor analysis**: TF identification among DEGs and selection of top 5 TFs. Functional validation of RORA.

---

## Results

### DEG analysis
- **Day 7 vs D0**: 6,247 DEGs (3,333 up, 2,914 down). Most changes occurred early.
- **Day 14 vs D0**: Sharp decrease to 85 DEGs.
- **Day 21 vs D0**: No significant DEGs → transcriptomic stabilization at late stages.

### Top DEGs at Day 7
- COL9A3, COL10A1, CILP2, COL2A1, COL11A2, COL5A1, FN1, etc. → related to ECM organization.
- Top 30 DEGs mainly involved ECM, collagen, and cartilage development-related genes.
- GO enrichment: ECM organization, collagen triple helix trimerization, proteolysis, cartilage development, cell adhesion, etc.

### Top DEGs at Day 14
- CXCL8, TLR2, CCL20, MMP3, etc. → enrichment of inflammatory response-related genes.
- Suggests transition from ECM phase (day 7) to inflammation/remodeling phase (day 14).
- KEGG: IL-17 signaling, TNF signaling, NOD-like receptor signaling, rheumatoid arthritis pathways.

### PPI network hub genes
- Day 7: ECM-related network.
- Day 14: Inflammation/immune-related hub genes including CXCL8, TLR2, CCL20, MMP3.

### Transcription factor analysis
- Top 5 TFs: **LEF1, FOXO1, RORA, BHLHE41, SOX5**.
- Among these, **RORA** was functionally validated as an early MSC chondrogenesis promoter: increased RORA expression promoted chondrogenic gene expression.

---

## Perspective

- This study systematically analyzed temporal transcriptomic changes during MSC chondrogenesis, revealing a two-stage differentiation process: early (day 7) ECM formation stage and late (day 14) inflammation/remodeling stage.
- It suggests that inflammation-related genes including CXCL8, TLR2, CCL20, and MMP3 may play important roles in late-stage MSC chondrogenesis.
- RORA was identified as a novel early chondrogenesis-promoting transcription factor, presenting a new molecular target for cartilage regeneration therapy.
- Limitations: (1) relatively small sample size, (2) functional validation needed for TFs other than RORA, (3) lack of in vivo validation.
- Future directions: functional validation of identified TFs (LEF1, FOXO1, BHLHE41, SOX5) and exploration of their applicability in cartilage regeneration therapy.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
