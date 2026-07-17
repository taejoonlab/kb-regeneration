---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p04.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Highly conserved molecular pathways, including Wnt signaling, promote functional recovery from spinal cord injury in lampreys

## Citation (NLM)
Herman PE, Papatheodorou A, Bryant SA, Waterbury CKM, Herdy JR, Arcese AA, Buxbaum JD, Smith JJ, Morgan JR, Bloom O. Highly conserved molecular pathways, including Wnt signaling, promote functional recovery from spinal cord injury in lampreys. Sci Rep. 2018;8:742. doi:10.1038/s41598-017-18757-1

**DOI:** [https://doi.org/10.1038/s41598-017-18757-1](https://doi.org/10.1038/s41598-017-18757-1)

---

## Background
In mammals, spinal cord injury (SCI) causes dramatic loss of neurons and synaptic connections with permanent functional deficits. Unlike mammals, lampreys — an ancient vertebrate lineage that diverged from a common ancestor of humans ~550 million years ago — undergo spontaneous regeneration and functional recovery after complete spinal cord transection, recovering swimming within ~12 weeks. The lamprey CNS is highly analogous to that of jawed vertebrates, and the sequenced lamprey genome revealed conserved pathways for axon guidance, synaptic transmission, and neural patterning. The authors set out to identify deeply conserved pro-regenerative pathways by defining the complete transcriptional responses after SCI in both spinal cord and brain, since many regenerating descending axons originate from reticulospinal (RS) neurons in the brain.

---

## Key Experiment Methods
1. Complete spinal cord transection in late larval sea lampreys (Petromyzon marinus) with quantitative behavioral scoring of swimming recovery (scale 0-4) over 12 weeks.
2. RNA-Seq on cDNA libraries from spinal cord (1 cm around lesion) and brain (whole brain minus olfactory lobes) from uninjured controls and 10 post-injury time points (6 h to 12 weeks; n=6 pooled per time point).
3. Read mapping to the published lamprey genome (Ensembl Pmarinus_7.0), expression quantified with RSEM; differential expression via EBSeq (PPDE >=0.95); hierarchical clustering.
4. Functional/pathway inference using Enrichr (GO, KEGG) and TRANSFAC/JASPAR transcription-factor network analysis, leveraging human/mouse orthology.
5. BLAST validation of homology for key regeneration/proliferation/cell-death genes.
6. Pharmacological Wnt blockade: single dose of the PORCN inhibitor Wnt-C59 (10 uM) vs vehicle applied via Gelfoam at the transection site, with 12-week behavioral scoring and follow-up RNA-Seq at 3 dpi.
7. qPCR validation of JUN and ATF3 temporal expression.

---

## Results
- SCI triggered robust, dynamic transcriptional responses in both spinal cord and brain; uninjured profiles clustered separately, and new differentially expressed transcripts continued to appear through late recovery (12 wpi), so recovery is not a return to the uninjured state.
- Enriched functional categories included immune function, ECM remodeling, development, neuronal function, proliferation, cell death, cytoskeleton, and ion channels — mirroring responses in regenerative zebrafish/axolotl and mammalian PNS.
- TF network analysis implicated FOXC1, NFKB1, and the canonical Wnt member LEF1; 17 regeneration-associated genes (RAGs) known from mammalian PNS were enriched, with CEBPB, GATA2, JUN, and LEF1 differentially expressed in both tissues at all 10 time points.
- ATF3 was the most robustly induced RAG in both spinal cord and brain; JUN, SOX11, SMAD, and REL homologs were highly up-regulated, matching core mammalian PNS injury networks.
- Growth-promoting transcripts (SNAP25, ACVR1) were up-regulated while growth-restricting transcripts (RHOB, SLIT2/3, ROBO2/3) were down-regulated; neurofilaments, synapsins, semaphorins, ECM genes (collagens, laminins), and immune genes (IL8, CXCR4) were differentially expressed.
- ~3% of differentially expressed transcripts mapped to Wnt pathways (121 in spinal cord, 101 in brain), peaking within the first week post-injury.
- Pharmacological Wnt inhibition (C59) blocked functional recovery: C59-treated animals reached only ~1.6 movement score at 12 wpi vs ~3.33 for vehicle, and 3-dpi RNA-Seq confirmed altered expression of direct Wnt targets (CDH2, Cldn19, CCNB2, FN1, keratins; brain: Axin1, JAG2, JUN, MMP9, Tbr1/TBX20).

---

## Perspective
This is the first RNA-Seq analysis of spinal cord and brain during natural SCI recovery in the sea lamprey, a basal vertebrate. It demonstrates that highly conserved, mammalian PNS-associated pro-regenerative programs (ATF3/JUN networks) and, critically, Wnt signaling are engaged and required for functional recovery, supporting the translational relevance of the lamprey model. The surprisingly robust supraspinal (brain) response emphasizes that recovery involves the cell bodies of injured descending neurons, relevant to promoting recovery in chronic-phase human SCI. Limitations acknowledged by the authors include an incomplete lamprey reference transcriptome, limited functional-genetics tools (though morpholino/CRISPR/pharmacology are available), bulk tissue profiling that masks cell-type-specific programs, and use of a pan-Wnt secretion inhibitor that cannot pinpoint the required Wnt components.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
