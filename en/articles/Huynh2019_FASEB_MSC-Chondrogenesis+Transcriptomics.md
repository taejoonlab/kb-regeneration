---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
raw_data:
  - "GEO: GSE109503"
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# High-depth transcriptomic profiling reveals the temporal gene signature of human mesenchymal stem cells during chondrogenesis

## Citation (NLM)
Huynh NPT, Zhang B, Guilak F. High-depth transcriptomic profiling reveals the temporal gene signature of human mesenchymal stem cells during chondrogenesis. FASEB J. 2019;33(1):358-372. doi:10.1096/fj.201800534R

**DOI:** [https://doi.org/10.1096/fj.201800534R](https://doi.org/10.1096/fj.201800534R)

---

## Background

Articular cartilage has little capacity for self-repair after injury or disease, prompting active research into tissue engineering approaches combining biomaterials and stem cells. Mesenchymal stem cells (MSCs) are easily obtainable from bone marrow and other sources and can differentiate into multiple skeletal lineages, making them a promising cell source for cartilage regeneration. MSC chondrogenic differentiation is regulated by complex interactions of molecular pathways, but a comprehensive understanding of its temporal transcriptomic changes is still lacking. Previous studies focused on specific genes or limited time points, whereas this study aimed to construct a transcriptomic map across 6 time points of MSC chondrogenesis using high-depth RNA-seq and to identify key gene signatures and regulatory networks through differential expression analysis, gene ontology, and weighted gene correlation network analysis (WGCNA).

---

## Key Experiment Methods

- **MSC isolation and culture**: Human bone marrow-derived MSCs, 3 individual donors. CD44+/CD73+/CD90+/CD105+/CD45− phenotype confirmed.
- **Chondrogenic differentiation**: Pellet culture method (2.5×10⁵ cells/pellet), chondrogenic medium containing TGF-β3, 21-day culture. Sampling at 6 time points: 0, 1, 3, 7, 14, 21 days.
- **RNA-seq**: TruSeq Stranded Total RNA with Ribo-Zero Gold, HiSeq 2500, paired-end 100 bp, 100M reads per sample. 18 libraries (3 donors × 6 time points). GEO: GSE109503.
- **Analysis**: DESeq differential expression analysis, DAVID GO enrichment, WGCNA (soft thresholding 7, height cutoff 0.25), K-means clustering, JASPAR TF database, Cytoscape network visualization.
- **Histochemistry**: Safranin O/Fast Green (GAG), type I/II/X collagen immunohistochemistry.
- **Biochemistry**: PicoGreen (DNA), DMB assay (GAG).
- **Web tool development**: Online searchable encyclopedia built with Shiny R package.

---

## Results

### Transcriptomic dynamics of MSC chondrogenesis
- PCA: gradual transcriptomic changes over time confirmed. Initial rapid change from d0→d1, followed by gradual changes from d3→d21.
- Sequential comparisons across 6 time points: 5,788 DE genes at d0→d1, 438 at d1→d3, 1,018 at d3→d7, 125 at d7→d14, 55 at d14→d21.
- Greatest transcriptomic changes occurred in the early stage (0-1 day), with decreasing numbers of DE genes toward later stages.

### Temporal changes in major biological pathways
- **d0→d1 (early)**: ECM organization, collagen metabolism, cell adhesion, skeletal system development, cell proliferation, apoptosis pathways activated.
- **d1→d3 (early to mid)**: Continued changes in apoptosis and cell motility pathways.
- **d3→d7 (mid)**: Collagen metabolism, cartilage development, cell differentiation, monosaccharide metabolism pathways activated. Upregulation of TGF-β signaling-related genes.
- **d7→d14 (late)**: Inhibition of apoptosis, cell adhesion, I-kB kinase/NF-kB signaling pathway activation.
- **d14→d21 (terminal)**: Fewest changes. Pathways related to cartilage homeostasis maintenance.

### Identification of gene modules by WGCNA
- 9 co-expression modules identified.
- **Turquoise module**: Highest correlation with chondrogenesis. Enriched in ECM, cartilage development, collagen-related genes. Key hub genes: COL2A1, COL11A1, COL9A1, ACAN, MATN3.
- **Brown module**: Related to collagen metabolism, protein digestion/absorption.
- **Yellow module**: Related to cell adhesion, vascular development.
- **Blue module**: Related to cell cycle, DNA replication (early proliferation stage).
- **TF analysis**: Key transcription factors identified for each module (e.g., SOX9, RUNX2 in turquoise module).

### Discovery of non-coding RNAs
- Identified 405 lncRNAs and 170 miRNAs whose expression changed during chondrogenesis.
- Many of these are novel candidates not previously associated with chondrogenesis.

### MSC cartilage vs. human articular cartilage transcriptome comparison
- Analysis of similarities and differences between MSC-derived cartilage and human articular cartilage transcriptomes.
- ECM gene expression patterns were similar, but differences were identified in specific markers.

### Online encyclopedia construction
- Shiny-based interactive web tool: searchable by gene and temporal expression pattern. Open resource for data mining and pathway analysis.

---

## Perspective

- This study provides the first comprehensive temporal transcriptomic map of MSC chondrogenesis across 6 time points using high-depth RNA-seq data.
- It reveals that the greatest transcriptomic changes occur early (d0-1) during chondrogenesis, followed by gradual stabilization.
- Through WGCNA, it identified the core chondrogenesis module (turquoise module) and hub genes (COL2A1, COL9A1, ACAN, etc.) and presented the TF network regulating them.
- It suggests the regulatory potential of novel lncRNA and miRNA candidates in chondrogenesis, providing a foundation for future functional validation.
- The constructed online encyclopedia will be a valuable public resource for MSC chondrogenesis researchers.
- Future research directions: (1) functional validation of identified lncRNAs/miRNAs, (2) optimization of culture conditions to overcome differences between MSC-derived cartilage and native cartilage, (3) heterogeneity analysis at single-cell resolution.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE109503

**Other accessions referenced in the text (reused/external data):**
- GEO: GSE106292


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
