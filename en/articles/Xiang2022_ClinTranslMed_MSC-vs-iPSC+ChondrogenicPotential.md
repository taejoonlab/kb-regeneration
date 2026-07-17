---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-07
extract_file: extract/2026-06-07_p02.txt
raw_data:
  - "GEO: GSE197172"
log:
  - "2026-06-07 · create · qwen3.6-plus (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Differences in the Intrinsic Chondrogenic Potential of Human Mesenchymal Stromal Cells and iPSC-Derived Multipotent Cells

## Citation (NLM)
Xiang S, Lin Z, Makarcyzk MJ, Riewruja K, Zhang Y, Zhang X, Li Z, Clark KL, Li E, Liu S, Hao T, Fritch MR, Alexander PG, Lin H. Differences in the Intrinsic Chondrogenic Potential of Human Mesenchymal Stromal Cells and iPSC-Derived Multipotent Cells. Clin Transl Med. 2022;12(12):e1112. doi:10.1002/ctm2.1112

**DOI:** [https://doi.org/10.1002/ctm2.1112](https://doi.org/10.1002/ctm2.1112)

---

## Background
Human induced pluripotent stem cell-derived multipotent progenitor cells (hiMPCs) represent a promising new cell source for cartilage regeneration. Unlike human mesenchymal stromal cells (hMSCs), which respond robustly to TGF-β alone for chondrogenesis, hiMPCs require bone morphogenetic proteins (BMPs) in addition to TGF-β. The mechanism underlying this difference is not fully understood. Additionally, MSC-derived chondrocytes often undergo hypertrophic conversion leading to ossification, while iPSC-derived chondrocytes may generate more stable hyaline-like cartilage. This study compares the chondrogenic potential of hiMPCs and hMSCs and elucidates the signaling mechanisms responsible for their differential responses to TGF-β.

## Key Experiment Methods
1. Generation of iMPCs from three human iPSC lines using sequential mesenchymal induction medium treatment without embryoid body formation
2. Pellet culture chondrogenic differentiation with various growth factor combinations (TGF-β3, BMP2, BMP4, BMP6, and their combinations)
3. Comparison of P3, P5, and P7 passage iMPCs to assess differentiation capacity loss with expansion
4. Subcutaneous implantation of chondrogenic pellets in SCID mice with micro-CT and histological analysis at 14 and 21 days to assess hypertrophy/ossification
5. Rat osteochondral defect model (2 mm diameter, 2 mm depth) implantation with MSC- or iMPC-derived cartilage pellets and evaluation after 8 weeks
6. RNA-sequencing and differential expression analysis (DESeq) with Ingenuity Pathway Analysis (IPA)
7. Western blot analysis of Smad phosphorylation (Smad2/3, Smad1/5) and chondrogenic/hypertrophic markers (SOX9, COL2, RUNX2, COL10)
8. Treatment with BMP pathway inhibitor LDN-193189 to test the role of Smad1/5 activation in iMPC chondrogenesis

## Results
- iMPCs rapidly lost differentiation capacity with increasing passage number: colony-forming ability decreased from ~24 colonies (P3) to ~4 colonies (P7) per 100 cells; chondrogenic potential declined from P3 to P7
- Conventional chondrogenic medium with TGF-β3 alone induced minimal chondrogenesis in iMPCs; BMP4+TGF-β3 induced robust chondrogenesis but with high hypertrophy (COL10, MMP13); BMP6+TGF-β3 induced high chondrogenic gene expression with minimal hypertrophy
- iMPCs cultured with TGF-β3+BMP6 deposited ~80% more GAG than hMSCs under the same conditions and showed COL2/COL10 ratio ~50 times higher than MSC groups at day 14-21
- TGF-β3 induced phosphorylation of both Smad2/3 and Smad1/5 in hMSCs, but only Smad2/3 in iMPCs; adding BMP6 activated Smad1/5 in iMPCs and significantly enhanced chondrogenesis
- LDN-193189 (BMP pathway inhibitor) abolished the chondro-promoting effect of BMP6, confirming Smad1/5 activation is critical for iMPC chondrogenesis
- Subcutaneous implantation: MSC-derived pellets underwent robust ossification by 14 days (Alizarin Red+, COL10+), while iMPC-derived pellets maintained cartilage phenotype (GAG+, COL2+) without calcification at 21 days
- In rat osteochondral defect model, both MSC and iMPC implants filled defects, but iMPC group showed significantly more COL2 deposition and no COL10 or COL1 expression, indicating superior hyaline cartilage regeneration without fibrous tissue or hypertrophy

## Perspective
This study demonstrates that dual activation of Smad2/3 and Smad1/5 is critical for initiating chondrogenesis in multipotent progenitor cells. The requirement for BMP6 supplementation in iMPCs (but not hMSCs) is explained by their inability to activate Smad1/5 via TGF-β alone. The TGF-β3+BMP6 combination generates hyaline-like cartilage from iMPCs with minimal hypertrophy, superior to MSC-derived cartilage that undergoes endochondral ossification. These findings support iMPCs as a potentially better cell source than MSCs for hyaline cartilage repair. Key limitations include rapid loss of iMPC chondrogenic capacity with passage number, necessitating use of early passage cells, and the need for further long-term stability studies in vivo. The mechanistic insight into Smad signaling differences provides a foundation for optimizing chondrogenic protocols for various progenitor cell types.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE197172


---

*Processed by **qwen3.6-plus** (OpenCode Go) on 2026-06-07*
