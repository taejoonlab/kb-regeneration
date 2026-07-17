---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
---

# Identification of transcription factors responsible for dysregulated networks in human osteoarthritis cartilage by global gene expression analysis

## Citation (NLM)
Fisch KM, Gamini R, Alvarez-Garcia O, Akagi R, Saito M, Muramatsu Y, Sasho T, Koziol JA, Su AI, Lotz MK. Identification of transcription factors responsible for dysregulated networks in human osteoarthritis cartilage by global gene expression analysis. Osteoarthritis Cartilage. 2018;26(11):1531-1538. doi:10.1016/j.joca.2018.07.012

**DOI:** [https://doi.org/10.1016/j.joca.2018.07.012](https://doi.org/10.1016/j.joca.2018.07.012)

---

## Background

Osteoarthritis (OA) is the most common joint disease and a major cause of disability in the elderly, yet disease-modifying therapies have not been developed. Although all tissues within the OA joint are affected, articular cartilage is most vulnerable to trauma and age-related changes. Genome-wide association studies (GWAS) have contributed to understanding OA pathology but are limited in discovering new therapeutic targets due to the small number of identified candidate genes and low odds ratios. Transcriptome analysis (RNA-seq) offers the potential for discovering new mechanisms and therapeutic targets. This study aimed to integrate RNA-seq data from normal and OA human knee cartilage to identify differentially expressed (DE) genes and regulatory networks in OA, with a focus on discovering new therapeutic targets centered on transcription factors (TFs).

---

## Key Experiment Methods

- **Clinical samples**: 18 normal knee cartilage samples (cadavers, female 5/male 13, mean age 38), 20 OA cartilage samples (knee replacement, female 12/male 8, mean age 66). No significant difference in BMI between groups.
- **RNA-seq**: Illumina HiSeq 2000, 100bp paired-end, 19-24M reads per sample. STAR aligner to hg19.
- **Expression analysis**: limma-voom for DE gene analysis (adjusted P<0.05, |log2FC|>1). Background genes: 12,463 (Entrez ID-mapped genes with detectable expression).
- **GO enrichment analysis**: topGO (weight01 method, Fisher's exact test, BH correction). KEGG pathway overrepresentation (WebGestalt).
- **TF enrichment analysis**: TF selection based on GO:0003700 (TF activity). oPOSSUM single site analysis (Fisher's test) for overrepresentation of JASPAR PWMs in DE gene promoters (1 kb upstream of TSS). BH adjusted P<0.1 significant.
- **Network analysis**: HumanBase cartilage-specific gene interaction network used. Subnetwork constructed using 14 DE enriched TFs as seeds (max 50 genes, min interaction confidence 0.17). Cytoscape v3.6.0 visualization.
- **Data availability**: GEO accession GSE114007.

---

## Results

### OA transcriptome profiling
- 13,102 transcripts detected, 12,463 mapped to Entrez IDs.
- MDS plot showed clear separation between OA and normal samples.
- 1,332 DE genes identified (630 upregulated, 702 downregulated; log2FC range −4.8 to 6.8).

### Dysregulated pathways
- **Upregulated**: ECM genes (COL10A1, COL13A1, COL15A1, COL1A2), proteases (MMP13, ADAMTS5), complement activation pathway.
- **KEGG pathway analysis** identified 15 significantly perturbed pathways:
  - ECM-receptor interaction
  - **PI3K-Akt signaling**: related to cartilage ECM degradation and autophagy regulation.
  - **FoxO signaling**: negative regulator of PI3K-Akt; decreased in OA and aging cartilage.
  - **HIF-1 signaling**: central regulator of hypoxic response; promotes chondrocyte differentiation and survival.
  - **Circadian rhythm**: disruption confirmed in OA cartilage, regulating TGFβ pathway.
- TGF-β/WNT, inflammation, and angiogenesis pathways showed no significant perturbation (contrary to previous reports).

### Transcription factor network analysis
- Cartilage-expressed TFs: 1,090. Among these, DE TFs in OA: 93 (mostly downregulated).
- TF binding site analysis: 44 TFs showed overrepresentation of binding sites in DE gene promoters.
- 93 DE TFs ∩ 44 enriched TFs → **14 DE enriched TFs** selected:
  - **JUN, EGR1, JUND, FOSL2, MYC, KLF4, RELA, FOS** — 8 TFs identified as particularly important.
  - These 8 TFs were all **downregulated** in OA.
  - These TFs target a large number of DE genes and are themselves suppressed in OA.

### Network-based TF prioritization
- Subnetwork of 62 genes constructed from 14 seed TFs.
- Top genes by degree (number of connections): JUN, MYC, EGR1, FOS, HIF1A, RELA, JUND, FOSL2, etc.
- Major pathways within the subnetwork: cancer-related pathways, FoxO, HIF-1 signaling.

---

## Perspective

- This study constructed a comprehensive transcriptome profile of human OA cartilage and, through network analysis, identified a novel regulatory network of 8 downregulated TFs (JUN, EGR1, JUND, FOSL2, MYC, KLF4, RELA, FOS) as key regulators of OA pathogenesis.
- This TF network is a major mediator of aberrant gene expression patterns in OA, suggesting that restoring their expression could be a therapeutic strategy for OA.
- Perturbation of PI3K-Akt, FoxO, HIF-1, and circadian rhythm pathways indicates disruption of essential mechanisms for maintaining cartilage homeostasis, providing a molecular basis for OA progression.
- Limitations: (1) analysis limited to promoter regions, excluding enhancers and other regulatory regions, (2) relatively small sample size, (3) causal relationships between TFs and target genes require further validation.
- Future directions: (1) functional validation of identified TFs in OA chondrocytes, (2) drug development targeting TF networks, (3) validation studies in larger cohorts.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
