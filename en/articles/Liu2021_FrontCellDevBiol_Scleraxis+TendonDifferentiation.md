---
tags: [2026-07, Tenocyte, RawDataAvailable]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
raw_data:
  - "GEO: GSE173428"
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# The Scleraxis Transcription Factor Directly Regulates Multiple Distinct Molecular and Cellular Processes During Early Tendon Cell Differentiation

## Citation (NLM)

Liu H, Xu J, Lan Y, Lim H-W, Jiang R. The Scleraxis Transcription Factor Directly Regulates Multiple Distinct Molecular and Cellular Processes During Early Tendon Cell Differentiation. Front Cell Dev Biol. 2021;9:654397. doi:10.3389/fcell.2021.654397

**DOI:** [https://doi.org/10.3389/fcell.2021.654397](https://doi.org/10.3389/fcell.2021.654397)

---

## Background

Tendons and ligaments are collagen-rich connective tissues (primarily type I collagen) that transmit muscle force to bone and stabilize joints, yet the molecular mechanisms controlling tendon development and tenocyte differentiation remain poorly understood. Among many gene knockouts, only loss of the basic helix-loop-helix (bHLH) transcription factor Scleraxis (Scx) or of TGFβ signaling causes severe disruption of tendon development; Scx-null mice show severe hypoplasia or absence of force-transmitting tendons. Scx function is dispensable for tendon progenitor initiation but essential for tenocyte differentiation. However, only a handful of putative direct Scx targets (e.g., Col1a1, Tnmd) had been identified, mostly by in vitro promoter assays, largely because no specific Scx antibody exists for genome-wide binding studies in vivo. This study generates a ScxFlag knock-in mouse to map endogenous Scx binding sites genome-wide, characterizes a new Scx-knockout line, and integrates ChIP-seq with RNA-seq to define direct Scx target genes in early tendon cell differentiation.

---

## Key Experiment Methods

**1. Generation of ScxFlag knock-in mice**
- CRISPR/Cas9 insertion of a 2xFLAG epitope tag at the carboxy terminus of endogenous Scx
- ScxFlag/Flag homozygotes born at Mendelian ratio with no phenotypic abnormality (FLAG tag does not impair Scx function)
- Anti-FLAG immunofluorescence confirmed Scx-FLAG expression specifically in tendons and ligaments

**2. Genome-wide Scx binding by ChIP-seq**
- Triplicate anti-FLAG ChIP-seq on E13.5 ScxFlag/Flag forelimbs (10 forelimb pairs per replicate)
- STAR alignment, HOMER peak calling, EdgeR differential analysis (log2FC > 2, FDR < 0.01)
- De novo motif analysis (HOMER); peak–gene association with GREAT (basal-plus-extension)

**3. Characterization of a new Scx-knockout mouse line**
- KOMP Scxtm1.1(KOMP)Vlcg line (LacZ cassette replacing the Scx coding sequence)
- Structure confirmed by Sanger sequencing; in situ hybridization confirmed complete loss of Scx mRNA in Scx−/−
- Skeletal preparations and Scx-GFP reporter to assess tendon/skeletal phenotypes

**4. Scx-dependent transcriptome (RNA-seq)**
- FACS isolation of Scx-GFP+ cells from E15.5 forelimbs of Scx−/− and control littermates
- RUVseq correction for sex, DESeq2 differential expression (FDR < 0.05), GO analysis (ToppGene)

**5. Integration and validation**
- Overlap of ChIP-seq peaks with Scx-dependent differentially expressed genes to define direct targets
- Whole-mount and section in situ hybridization plus qRT-PCR (at E13.5 and E15.5) for candidate genes (Fmod, Kera, Htra3, Ssc5d, Tnmd, Zfp185)

---

## Results

**A functional ScxFlag mouse enables genome-wide mapping of endogenous Scx binding**
The 2xFLAG tag did not alter Scx function, and Scx-FLAG was strongly and specifically expressed in tendons and ligaments. Anti-FLAG ChIP-seq on E13.5 forelimbs identified 12,097 high-quality Scx-binding peaks; ~77% were intronic/intergenic and only ~14% in promoters. The most enriched de novo motif was C-A-G/T-A/C-T-G, matching the EMSA-determined preferential Scx binding motif; the second most enriched motif matched the NFAT consensus (TGGAAA), consistent with reported Scx–Nfatc4 cooperation on Col1a1.

**ChIP-seq recovers Scx-associated genes enriched for ECM and tendon programs**
GREAT associated the peaks with 7,520 genes. Comparing with prior developing-tendon RNA-seq, 490 of 970 genes upregulated during E13.5→E15.5 tendon differentiation carried Scx ChIP-seq peaks; these were highly enriched for "extracellular matrix organization," "collagen fibril organization," and "connective tissue development."

**A new KOMP Scx-knockout line reproduces tendon defects**
Scx−/− mice were born at Mendelian ratio but with reduced body size and severely impaired limbs (autopods locked in dorsal flexure), severe hypoplasia of major limb and tail tendons, and skeletal changes (absent deltoid tuberosity, reduced patella and calcaneal entheseal cartilage, reduced lumbar transverse processes). Tendon differentiation and condensation were disrupted by E15.5, matching previously reported Scx mutant lines.

**Integrated ChIP-seq/RNA-seq defines direct Scx target genes**
RNA-seq of E15.5 Scx-GFP+ cells identified 68 significantly changed genes in Scx−/−. Of the downregulated genes, 32 carried Scx binding peaks (candidate activated targets; GO enriched for "tendon development," "tendon cell differentiation," "keratan sulfate biosynthesis," "ECM organization"), and 17 upregulated genes carried peaks (candidate suppressed targets; GO enriched for "regulation of cell migration," "ECM organization," "induction of chemotaxis," including Ccbe1, Cxcl12, Fgf10, Igf1, Postn). The most downregulated targets included Fmod, Tnmd, Kera, and Col11a1, plus transcription factors Mkx, Six2, and Eya1 — yet only Tnmd had previously been reported as a Scx target.

**Multiple targets show Scx-dependent tendon-specific expression**
Whole-mount in situ hybridization showed Fmod, Htra3, Kera, Ssc5d, Tnmd, and Zfp185 with highly specific tendon expression in E14.5 wild type, dramatically reduced in Scx−/−; qRT-PCR confirmed significant reduction already at E13.5. Scx binding was enriched at basal promoters of Fmod, Ssc5d, and Zfp185 and at distal regulatory elements of Fmod, Kera, Htra3, and Tnmd. The previously uncharacterized Htra3, Ssc5d, and Zfp185 emerge as direct Scx targets activated during early tendon differentiation.

---

## Perspective

This study establishes the first genome-wide map of endogenous Scx binding in developing tendon tissue and, by integrating ChIP-seq with Scx-dependent transcriptomics, defines a set of direct Scx target genes that mediate early tenocyte differentiation.

First, the ScxFlag knock-in mouse overcomes the long-standing lack of a specific Scx antibody and provides a broadly useful tool for direct analysis of endogenous Scx function across development, homeostasis, and injury repair. The de novo Scx motif (CAG/TA/CTG) from in vivo binding validates and refines earlier in vitro EMSA findings.

Second, the work greatly expands the known Scx target repertoire beyond Col1a1 and Tnmd, revealing that Scx coordinately regulates ECM components (Fmod, Kera, Col11a1, Ssc5d), tendon transcription factors (Mkx, Six2, Eya1), and cell-migration/chemotaxis genes, and that it both activates and represses distinct gene programs during tendon formation.

Third, the KOMP-derived Scx-knockout line is a community-accessible resource that reproduces the canonical Scx tendon phenotype, and the ChIP-seq/RNA-seq datasets (GSE173428) offer a rich foundation for further study of tendon cell differentiation and tendon tissue regeneration.

Within the vault's connective-tissue regeneration theme, these Scx target genes and gene-regulatory logic are directly relevant to tendon/ligament repair and to distinguishing tenogenic from chondrogenic differentiation programs. The main limitations are that the direct-target set is defined at a single early stage (E13.5–E15.5) in the limb and that functional roles of newly nominated targets (Htra3, Ssc5d, Zfp185) in tendon development remain to be established.


## Data Availability

**Raw data generated by this study:**
- GEO: GSE173428


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
