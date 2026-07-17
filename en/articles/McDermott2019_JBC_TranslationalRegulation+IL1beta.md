---
tags: [2026-06, Chondrocyte]
extract: 2026-06-08
log:
  - "2026-06-08 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Translational regulation contributes to the secretory response of chondrocytic cells following exposure to interleukin-1β

## Citation (NLM)
McDermott BT, Peffers MJ, McDonagh B, Tew SR. Translational regulation contributes to the secretory response of chondrocytic cells following exposure to interleukin-1β. J Biol Chem. 2019;294(35):13027-13039. doi:10.1074/jbc.RA118.006865

**DOI:** [https://doi.org/10.1074/jbc.RA118.006865](https://doi.org/10.1074/jbc.RA118.006865)

---

## Background

Osteoarthritis (OA) is a chronic disease characterized by degradation of the articular cartilage extracellular matrix (ECM), in which inflammatory cytokines play a key role. IL-1β and TNFα induce the expression of MMP family proteases, promoting cartilage destruction. While transcriptomic studies have greatly advanced the understanding of OA pathology, the contributions of post-transcriptional (mRNA stability) and translational regulation to the cellular phenotype are relatively understudied. In particular, how protein translation changes at the transcript level in chondrocytes upon IL-1β stimulation had not been investigated by ribosome profiling. This study used the SW1353 chondrosarcoma cell line as a model to analyze the effects of IL-1β stimulation on translational regulation by combining ribosome profiling and proteomics.

---

## Key Experiment Methods

1. **Cell culture and IL-1β treatment**: SW1353 chondrosarcoma cells were treated with 10 ng/mL IL-1β for 3 h (for ribosome profiling) or 24 h (for proteomics). Primary human articular chondrocytes (HACs) were also used for comparison.
2. **Ribosome profiling (Ribo-Seq)**: The ARTseq Ribosome Profiling kit was used. Translation was halted with cycloheximide, and ribosome-protected mRNA fragments (RPFs) were isolated by nuclease digestion. rRNA was removed, and RNA-seq libraries were constructed and sequenced on an Illumina HiSeq2500.
3. **RiboGalaxy pipeline**: Sequence alignment and triplet periodicity analysis were performed using Cutadapt, Bowtie, and riboSeqR. Differential translation analysis was conducted with baySeq.
4. **Proteomics analysis**: Cellular proteome and conditioned media (secretome) were analyzed by in-solution trypsin digestion followed by LC-MS/MS. Label-free quantification was performed using PEAKS 7 software.
5. **ELISA**: Quantification of CCL2 and IL-6 secretion in a time- and concentration-dependent manner, with comparison to primary chondrocytes.
6. **Western blot**: SOD2 protein expression confirmed using anti-SOD2 antibody.
7. **ROS detection**: Intracellular reactive oxygen species (ROS) levels after IL-1β treatment were measured using the CM-H₂DCFDA fluorescent dye.

---

## Results

- Triplet periodicity analysis of ribosome profiling data showed that most reads were 28-mers aligned to frame 1, confirming accurate capture of translating mRNAs.
- Differential translation analysis (q < 0.001) revealed that among the top 200 transcripts, the majority (n = 108) showed increased translation after IL-1β treatment. Only 4 transcripts (ZC3H12A, PIM1, and some TNFAIP2 variants) showed decreased translation.
- STRING analysis: 18.5% of differentially translated transcripts were inflammation-related genes (NFKB1, TNFAIP2, MMP13, CCL2, CCL7), and 31.5% were ribosome-related genes.
- Secretome analysis confirmed a similar cluster of inflammation-related proteins.
- An intriguing pattern emerged: for CCL2, CCL7, and NFKBIZ, total mRNA levels decreased while RPF levels increased, indicating a "transcription–translation dissociation" phenomenon where transcriptional repression and translational activation occur simultaneously.
- Increased ribosome occupancy was observed in the 3′-UTR of certain genes (TNFAIP2, SOX9), suggesting a potential novel mechanism of translational regulation.
- SOD2 was among the most strongly upregulated genes at the translational level (RPF 55 → 1509, with no change in total RNA). Western blot and ROS assays confirmed that IL-1β rapidly induces ROS, followed by increased SOD2 expression that reduces ROS, revealing a redox regulatory mechanism.
- Both SW1353 and primary chondrocytes showed concentration- and time-dependent increases in CCL2 and IL-6 secretion, with primary cells responding to lower IL-1β concentrations (0.1 ng/mL).

---

## Perspective

- This study is the first to apply ribosome profiling in a chondrocyte-like cell type, revealing a rapid translational response to IL-1β cytokine stimulation.
- Demonstrates that a substantial portion of the inflammatory response is mediated through translational rather than transcriptional regulation. The translational upregulation of CCL2/CCL7 chemokines may represent a physiological mechanism enabling rapid intercellular signaling.
- IL-1β induces a redox regulatory pathway: NF-κB activation → ROS increase → SOD2 translation upregulation, which serves as an oxidative stress defense mechanism in chondrocytes.
- The SW1353 cell line shows IL-1β responsiveness similar to primary chondrocytes, but has limitations including lower matrix component expression and reduced sensitivity to low cytokine concentrations.
- Future research directions: functional significance of 3′-UTR ribosome occupancy, translational regulation via the mTOR/4E-BP1 pathway, and validation of translational regulation in in vivo tissues.
- A key unresolved question is how the rapid translational response of chondrocytes to cytokine signaling contributes to maintaining healthy tissue homeostasis.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-08*
