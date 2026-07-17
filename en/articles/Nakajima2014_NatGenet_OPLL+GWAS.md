---
tags: [2026-07, Ossification]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# A genome-wide association study identifies susceptibility loci for ossification of the posterior longitudinal ligament of the spine

## Citation (NLM)

Nakajima M, Takahashi A, Tsuji T, Karasugi T, Baba H, Uchida K, et al. A genome-wide association study identifies susceptibility loci for ossification of the posterior longitudinal ligament of the spine. Nat Genet. 2014;46(9):1012-1016. doi:10.1038/ng.3045

**DOI:** [https://doi.org/10.1038/ng.3045](https://doi.org/10.1038/ng.3045)

---

## Background

Ossification of the posterior longitudinal ligament of the spine (OPLL, MIM 602475) is a common spinal disorder in which the posterior longitudinal ligament undergoes abnormal ectopic ossification within the spinal canal, compressing the cord and nerve roots to cause myelopathy and radiculopathy. It affects 0.8–3.0% of Asians and 0.1–1.7% of European Caucasians. Twin/sib-pair linkage and candidate-gene studies had suggested a strong genetic contribution, but earlier candidate associations failed to replicate, and no high-density GWAS had been reported. This study performed the first GWAS of OPLL in a Japanese population to identify robust susceptibility loci.

---

## Key Experiment Methods

**1. GWAS discovery**
- 1,130 OPLL cases and 7,135 controls (Japanese); after QC, 616,496 autosomal SNPs in 1,112 cases / 6,810 controls (major Hondo cluster)
- Cochran-Armitage trend test; genomic inflation λGC = 1.01; imputation with Minimac against 1000 Genomes JPT/CHB/CHS
- X-chromosome association tested separately (no significant hits)

**2. Replication and meta-analysis**
- Top SNP per locus genotyped in an independent 548 cases / 6,469 controls (multiplex PCR Invader assay)
- GWAS + replication combined by Mantel-Haenszel; heterogeneity by Breslow-Day; genome-wide threshold P < 9.68 × 10⁻⁹
- Age/sex-adjusted logistic regression and conditional analysis for independent signals

**3. Functional / expression follow-up**
- RT-PCR of candidate genes in human bone cells and fibroblasts
- Expression during chondrogenesis in the ATDC5 endochondral-ossification cell model (Sox9, Acan, Col2a1)
- FANTOM5 cell-type profiling + qPCR of 63 genes within 1 Mb; MSCs from spinal ligament of OPLL vs non-OPLL subjects (microarray + qPCR); eQTL (Genevar) and GRAIL pathway analysis

---

## Results

**Six genome-wide significant susceptibility loci**
The meta-analysis identified six loci: 20p12.3 (rs2423294, P = 1.10 × 10⁻¹³, near HAO1), 8q23.1 (rs374810, P = 1.88 × 10⁻¹³, RSPO2/EIF3E/EMC2), 12p11.22 (rs1979679, P = 4.34 × 10⁻¹², CCDC91, adjacent to PTHLH), 12p12.2 (rs11045000, P = 2.95 × 10⁻¹¹, LOC100506393 lincRNA), 8q23.3 (rs13279799, P = 1.28 × 10⁻¹⁰, between LINC00536 and EIF3H), and 6p21.1 (rs927485, P = 9.40 × 10⁻⁹, CDC5L/MIR4642/SUPT3H). No independent secondary signals were found by conditional analysis.

**Convergence on ossification-relevant pathways**
Two of the six loci harbor eIF-3 translation-initiation components (EIF3E and EIF3H), and GRAIL linked these two genes functionally (P ≈ 0.02), suggesting the translation-initiation pathway as a candidate mechanism. RSPO2 activates canonical Wnt/β-catenin signaling — indispensable for osteoblastogenesis and reported to promote osteoblast mineralization — while CCDC91 sits adjacent to PTHLH, whose PTH/PTH1R axis regulates endochondral ossification relevant to OPLL progression.

**Expression evidence for membranous vs endochondral routes**
In the ATDC5 model, Hao1, Rspo2, and Ccdc91 were low during early chondrogenesis (when Sox9 was high), implicating them in endochondral ossification. FANTOM5/qPCR profiling confirmed osteoblast-enriched expression of RSPH9 and STK38L, implicating them in membranous ossification. eQTL analysis showed no significant genotype-expression association in lymphoblastoid cells, and spinal-ligament MSCs showed no significant differential expression at the associated loci.

**Genetic heterogeneity by subtype**
One locus (20p12.3) overlapped a previously reported linkage region. Stratified analysis increased OR estimates, and a diabetes-free stratum reached genome-wide significance at 7q22 (rs10486860, P = 4.31 × 10⁻⁸), consistent with OPLL being genetically heterogeneous and linked to insulin/diabetes-associated subtypes.

---

## Perspective

This first OPLL GWAS defines six robust susceptibility loci and reframes OPLL as a genetically tractable disorder of pathological ligament ossification. It is a cornerstone reference for the vault's ossification theme because OPLL is a clinically important form of ectopic ossification, and the identified genes partition its etiology into recognizable bone-forming programs — membranous ossification (RSPH9, STK38L) and endochondral ossification (HAO1, RSPO2, CCDC91).

The results tie ectopic spinal ossification to canonical osteogenic signaling: RSPO2-driven Wnt/β-catenin activation and the PTHLH/PTH1R endochondral axis echo the same osteoblastic pathways implicated across the vault's calcification and bone-formation papers. The recurrence of eIF-3 subunits at two independent loci is a more novel, unexpected lead.

Limitations include the Japanese-only cohort (transferability to other ancestries untested), largely intergenic/gene-desert associations that complicate causal-gene assignment, and the absence of eQTL or MSC expression signals at most loci — leaving the functional variants unresolved. The authors call for further genetic and functional studies to clarify OPLL pathogenesis.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
