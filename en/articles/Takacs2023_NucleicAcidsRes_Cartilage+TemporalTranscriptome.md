---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# The temporal transcriptomic signature of cartilage formation

## Citation (NLM)
Takács R, Vágó J, Póliska S, Pushparaj PN, Ducza L, Kovács P, Jin EJ, Barrett-Jolley R, Zákány R, Matta C. The temporal transcriptomic signature of cartilage formation. Nucleic Acids Res. 2023;51(8):3590-3617. doi:10.1093/nar/gkad210

**DOI:** [https://doi.org/10.1093/nar/gkad210](https://doi.org/10.1093/nar/gkad210)

---

## Background

Chondrogenesis is a multistep process in which cartilage progenitor cells generate tissue with unique structural and functional properties. Although various approaches for cartilage regeneration rely on the differentiation of implanted progenitor cells, the temporal transcriptomic landscape of in vitro chondrogenesis has not been reported across different models. Collagen, a major component of the cartilage extracellular matrix (ECM), provides tensile and shear strength to the tissue, with type II collagen constituting over 90% of the hyaline cartilage ECM. However, little is known about the various collagen types synthesized by differentiating chondrocytes during chondrogenesis. Mesenchymal stem cells (MSCs) are a promising cell source for cartilage tissue engineering, but MSC-derived chondrocytes exhibit unstable phenotypes and a tendency to progress toward hypertrophy. The chicken micromass model using embryonic limb-derived mesenchymal progenitors (LMPs) more consistently recapitulates hyaline cartilage chondrogenesis. This study aimed to comprehensively analyze the temporal transcriptome profile of chondrogenesis in LMP-based micromass cultures using RNA-seq and to identify novel chondrogenesis-related transcription factors and collagen types.

---

## Key Experiment Methods

- **Micromass culture**: LMPs isolated from chicken embryonic limbs (Hamburger-Hamilton stage 22-24), high-density culture at 1.5×10⁷ cells/ml. Sampling at 8 time points (day 0, 1, 2, 3, 4, 6, 10, 15). Adult chicken knee joint chondrocytes also analyzed for comparison.
- **ECM analysis**: Alcian blue, Safranin-O, DMMB staining for cartilage matrix production. Collagen type I/II immunohistochemistry (DAB chromogen).
- **RNA-seq**: Illumina platform, alignment to chicken reference genome GRCg6a. DEG selection at Benjamini-Hochberg adjusted P<0.05, LFC ±2.0.
- **Bioinformatics analysis**: PCA, UMAP dimensionality reduction, Monocle 3 pseudotime analysis, GO enrichment, IPA network analysis, Cytoscape + STRING plugin protein-protein interaction network.
- **Gene expression validation**: RT-qPCR (normalized to RPS7 reference gene).
- **Transient gene silencing (siRNA)**: ATOH8 and EBF1 targeted siRNAs introduced into LMPs via nucleofector electroporation. Chondrogenesis assessed by DMMB staining and MTT assay at day 6. Bone/cartilage marker gene expression analyzed by RT-qPCR.

---

## Results

### Global transcriptome changes during chondrogenesis
- PCA: Samples progressively separated by culture time. PC1 explained 52.46% of variance. Progression from undifferentiated to differentiated state until day 10, with day 15 showing regression.
- Adult chondrocytes clustered separately from micromass cells → similar but distinct transcriptomes.
- Monocle 3 pseudotime analysis: developmental saturation occurred around day 6.
- Hierarchical clustering: early (days 0-2), middle (days 3-6), late (days 10-15) stages and adult chondrocytes.

### Stage-specific DEG profiles
- Total of 3,470 DEGs identified. Early stage (days 0→1): 590 DEGs (458 up, 132 down).
- Mid-differentiation (days 3→4): only 14 DEGs, the fewest → transcriptomic stabilization.
- Late stage (days 10→15): 408 DEGs (84 up, 324 down) → mostly downregulated.
- Proportion of cartilage development-related genes (GO:0051216) increased until day 10 then decreased.
- Key DEGs: included GDF5, MATN1, COMP, SPP1, MMP13, COL10A1, and many other cartilage development-related genes.

### Major collagen gene expression dynamics
- COL2A1, COL9A1, COL11A1: expression increased from early differentiation and maintained until day 10.
- COL1A1, COL1A2: highly expressed in early stage → decreased with differentiation (reflecting fibroblast→chondrocyte transition).
- First report of expression dynamics for other collagen types (COL14A1, etc.).
- Collagen type II protein: accumulated in ECM from day 4; type I was high initially then decreased.

### Identification of novel chondrogenesis-related transcription factors
- Next-generation sequencing data analysis identified ATOH8 (atonal homolog 8) and EBF1 (early B-cell factor 1).
- **ATOH8 siRNA**: decreased cartilage ECM production (DMMB staining ↓), reduced MTT viability. Downregulation of Col2a1, Acan, Sox9 expression.
- **EBF1 siRNA**: similarly inhibited chondrogenesis. Reduced cartilage marker gene expression.

### Protein-protein interaction network
- Day 0: highest number of interactions (6,099 interactions) → complex network at early differentiation.
- Interactions decreased during differentiation → increased again in mature micromass/day 15.
- Central hub genes: chaperones (CCT2, HSP90AA1), ribosomal proteins (RPLP0, RPS27A), glycolytic enzymes (GAPDH), etc.

---

## Perspective

- This study provides the first comprehensive temporal transcriptomic map across 8 time points of chondrogenesis in chicken LMP-based micromass cultures.
- It reveals that chondrogenesis proceeds in three phases: early active gene expression changes → middle stabilization → late downregulation.
- It identifies ATOH8 and EBF1 as novel chondrogenesis-regulating transcription factors and confirms that their transient silencing impairs chondrogenesis.
- The transcriptomic differences between adult chondrocytes and micromass-derived chondrocytes highlight the limitations of in vitro models, and the regression after day 15 suggests a need for further optimization.
- This dataset can serve as a molecular platform for cartilage tissue engineering and regenerative medicine research.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
