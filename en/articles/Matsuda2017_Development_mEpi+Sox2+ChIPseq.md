---
tags: [2026-07]
extract: 2026-07-16
---

# ChIP-seq analysis of genomic binding regions of five major transcription factors highlights a central role for ZIC2 in the mouse epiblast stem cell gene regulatory network

## Citation (NLM)
Matsuda K, Mikami T, Oki S, Iida H, Andrabi M, Boss JM, Yamaguchi K, Shigenobu S, Kondoh H. ChIP-seq analysis of genomic binding regions of five major transcription factors highlights a central role for ZIC2 in the mouse epiblast stem cell gene regulatory network. Development. 2017;144(11):1948-1958. doi:10.1242/dev.143479

**DOI:** [https://doi.org/10.1242/dev.143479](https://doi.org/10.1242/dev.143479)

---

## Background
Mammalian somatic cells originate from the epiblast of postimplantation embryos. Epiblast stem cells (EpiSCs), derived from egg-cylinder-stage mouse embryos, provide a model for investigating gene regulatory networks in the epiblast and for deriving specific somatic lineages, including anterior neural plate (ANP) cells upon removal of activin/Nodal signaling. In prior work, the authors identified ZIC2, OTX2, SOX2, POU5F1 and POU3F1 as major regulators in EpiSCs and during the EpiSC-to-ANP transition; these TFs change their anteroposterior localization in the epiblast after E6.5, and their manipulation strongly impacts downstream TFs governing somatic lineage derivation.

While the SOX2–POU5F1 pair is well established as the core regulatory module in embryonic stem cells (ESCs), it remained unclear how the genomic binding of these and other TFs is organized in the more developmentally advanced (primed) EpiSC state, and how binding is repartitioned during the ESC-to-EpiSC transition. This study uses ChIP-seq to map genome-wide binding of the five TFs in EpiSCs to gain insight into TF-dependent regulation relevant to early-stage embryogenesis and neural lineage priming.

---

## Key Experiment Methods
1. **In vivo biotinylated ChIP-seq:** A simplified ChIP-seq method using TFs C-terminally fused to a biotin ligase recognition peptide (BLRP) and co-expressed E. coli biotin ligase (BirA), from a single pCAGGS-BLRP-IRES-BirA vector, avoiding antibody-dependent efficiency variation.
2. **Transient transfection at physiological levels:** High-efficiency (75–95%) transient transfection of a feeder-free EpiSC line with 5 µg vector/10-cm dish, calibrated to keep exogenous TF near-physiological (validated by immunofluorescence normalized to histone H2; NANOG/POU5F1 checks confirmed the EpiSC state was maintained).
3. **ChIP and library prep:** Formalin fixation, whole-cell lysate chromatin fragmentation (~150 bp), streptavidin magnetic-bead capture of biotinylated TF–DNA complexes, TruSeq library prep, Illumina HiSeq2500 single-end 100 bp sequencing.
4. **Peak calling and analysis:** Bowtie2 alignment to mm9; MACS1.4 peak calling (60,000–120,000 peaks per TF); MEME-ChIP motif enrichment; peak-width, gap-size, and TSS-proximity analyses; IGV/ChIP-Atlas visualization; GREAT for gene association; BioVenn for overlaps.
5. **Integration with published data:** Overlay with histone H3 modification ChIP-seq (H3K4me1/K27ac active enhancers, H3K4me1/K27me3 poised enhancers), microarray expression of somatic cells (ATDC5 chondrocytes, MEFs, myoblasts), and ESC/EpiLC/human-ESC ChIP-seq (with UCSC LiftOver to mm9 coordinates).

---

## Results
- **Alternating Mb-scale domains:** Megabase-scale genomic domains rich in ZIC2 peaks (and gene-rich) alternate with domains rich in POU3F1 peaks (but gene-sparse), reflecting clustering of short-range (ZIC2) versus long-range (POU3F1) regulatory sequences. OTX2 tended to co-locate with ZIC2, and SOX2/POU5F1 with POU3F1.
- **Two TF groups by peak overlap:** ZIC2 and OTX2 peaks overlapped extensively (~16–19%), while ZIC2–POU3F1 overlap was minimal (~1.2–1.3%). SOX2 and POU factors formed a second overlapping group. ZIC2/OTX2 versus SOX2/POUs behaved as largely separate modules.
- **TSS proximity:** ~55% of ZIC2 and OTX2 peaks lay within 50 kb of a TSS (gene-proximal), whereas >80% of SOX2, POU5F1 and POU3F1 peaks were >50 kb from a TSS (gene-remote).
- **Enhancer signatures:** ZIC2 binding associated most frequently with both active (H3K4me1/K27ac) and poised (H3K4me1/K27me3) enhancer marks; ~33% of ZIC2–OTX2 co-bound peaks carried active-enhancer marks, indicating ZIC2–OTX2 acts mainly as a transcriptional activator. Examples: Fgf5 (active in EpiSCs) and Pax6 (poised, ANP gene).
- **ZIC2–OTX2 regulates TF genes:** Genes near histone-marked ZIC2–OTX2 co-bound regions, especially TF genes (e.g., Mycn, Nanog, Otx2, Pou5f1, Sall4, Sox2), were preferentially downregulated in somatic cells relative to EpiSCs, confirming these are functional EpiSC enhancers.
- **Divergent SOX2/POU5F1 binding across stem cells:** SOX2–POU5F1 peaks overlapped ~78% in ESCs but only ~8% in EpiSCs. Cross-species/state comparison ordered developmental progression as mouse ESC → EpiLC → human ESC → mouse EpiSC.
- **ZIC2 as an enhancer-priming/pioneer factor:** ~80% of ESC ZIC2-bound regions remained ZIC2-bound in EpiSCs; ZIC2 in ESCs interacts with the NuRD complex at bivalent enhancers. ZIC2 appears to prime genomic positions in ESCs that later become active enhancers (bound by OTX2) after SOX2/POU5F1 disengage — shown for pluripotency genes (Mycn, Nanog, Nodal, Sall4) and the EpiSC-specific Fgf5.

---

## Perspective
This study introduces an efficient in vivo-biotinylation ChIP-seq procedure and provides new genomic resources (GEO GSE74636) for five key TFs in mouse EpiSCs. Conceptually, it reframes the primed-pluripotency network: the major acting TF pair shifts from SOX2/POU5F1 (ESCs) to ZIC2/OTX2 (EpiSCs) while regulating a similar gene set, with ZIC2 acting as an enhancer-priming ("pioneer"/"seed-enhancer") factor that pre-marks positions in ESCs for later activation. The relevance to neural lineage is notable: SOX2, the nestin (Nes30) enhancer, and the ANP marker Pax6 feature prominently, linking this regulatory logic to neural plate specification and neural stem/progenitor priming. Limitations include reliance on transient overexpression (albeit near-physiological), the anti-ZIC2 antibody's cross-reactivity with ZIC1/ZIC3, and the correlative (ChIP/histone/expression) rather than functional-perturbation nature of most conclusions. Open questions raised include whether the alternating Mb-scale domain organization is EpiSC-specific and how it relates to higher-order genome architecture, and the detailed ZIC2/SOX2 binding dynamics in the intermediate EpiLC state.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
