---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Localized EMT reprograms glial progenitors to promote spinal cord repair

## Citation (NLM)
Klatt Shaw D, Muraleedharan Saraswathy V, Zhou L, McAdow AR, Burris B, Butka E, Morris SA, Dietmann S, Mokalled MH. Localized EMT reprograms glial progenitors to promote spinal cord repair. Dev Cell. 2021;56(5):613-626. doi:10.1016/j.devcel.2021.01.017

**DOI:** [https://doi.org/10.1016/j.devcel.2021.01.017](https://doi.org/10.1016/j.devcel.2021.01.017)

---

## Background

In mammals, anti-regenerative scarring obstructs spinal cord (SC) repair and reactive, scar-bordering astrocytes separate spared neurons from the non-neuronal lesion core. In contrast, adult zebrafish possess specialized glial cells that spontaneously repair SC injuries by forming a pro-regenerative glial bridge across the severed tissue, reversing paralysis within 6-8 weeks of complete SC transection. Prior work established that connective tissue growth factor a (ctgfa) is a central bridging factor expressed in ependymal radial glial (ERG) progenitors after injury.

Glial bridging in zebrafish shares morphological and functional similarities with Schwann cell-mediated repair after mammalian peripheral nerve injury, where Schwann cells undergo partial reprogramming from an epithelial to a more plastic mesenchymal fate. This study set out to define the molecular identity of zebrafish bridging glia, perform cross-species comparisons with mammalian glia, and identify the gene regulatory network that drives differential regenerative capacity.

---

## Key Experiment Methods

1. Generated ctgfa:mCherry reporter lines combined with gfap:EGFP to label bridging glia; performed FACS sorting of ctgfa+gfap+ cells at 5 dpi.
2. FACS-seq (deep RNA-seq of sorted cells) plus bulk SC RNA-seq at 5, 10, and 21 dpi versus uninjured controls after complete SC transection.
3. Cross-species transcriptomic comparisons of zebrafish bridging glia against murine repair Schwann cells and murine scar-bordering astrocytes after SCI.
4. Assessment of 120 epithelial/mesenchymal EMT markers by FACS-seq and qRT-PCR; RNAscope and immunohistochemistry for twist1a, Cdh1, Cdh2, Vimentin.
5. Single-nucleus RNA-seq (10x Genomics) of gfap:EGFP SC tissue at 1 wpi (33,185 nuclei) to resolve glial heterogeneity.
6. Large-scale in vivo CRISPR-Cas9 F0 mutagenesis of 9+ transcription factors in adult zebrafish, with swim-tunnel functional recovery assays and glial bridge quantification; stable egr1 and junbb mutant lines.
7. Heat-inducible transgenics: hsp70:dsRed-dnYap (dominant-negative Yap) and hsp70:Twist1a-2A-EGFP for loss- and gain-of-function of Yap and Twist1a.

---

## Results

- FACS-seq defined the first transcriptome of pro-regenerative zebrafish bridging glia; ctgfa was enriched while gfap and neuronal/oligodendrocyte markers (neurod1, mbpa) were depleted. EMT genes vimentin, twist1, and zeb2 were enriched.
- Cross-species comparison: zebrafish bridging glia shared regeneration/wound-healing and EMT genes (snai2, tgfb1, cdh1, ctgf/ccn2) with murine repair Schwann cells but are a distinct cell fate; they also showed substantial (~12% enriched, ~9% depleted) transcriptional overlap with mouse scar-bordering astrocytes, including s100a10 (A2 astrocyte marker) and stat3.
- Ventral ependymal progenitors undergo EMT after SCI: epithelial markers downregulated, mesenchymal markers enriched; twist1a localized to ventral ependymal progenitors at 1-2 wpi, Cdh2/Vimentin upregulated and Cdh1 downregulated in ctgfa+ cells.
- snRNA-seq resolved 10 glial subclusters; clusters Glial-7, -8, -9 corresponded to bridging glia (ctgfa+twist1a+, ctgfa+twist1b+, and proliferative subsets) undergoing mesenchymal transition, with axon guidance signatures.
- CRISPR-Cas9 screen identified a functionally validated gene regulatory network (bach1a/b, egr1, junbb, spi1a, taz/yap1) required for glial bridging and functional SC repair; egr1 and junbb loss attenuated twist1a expression.
- Yap signaling: Yap preferentially activated (nuclear) in ventral ependymal progenitors; dnYap expression impaired functional recovery, reduced glial bridging by ~50%, and diminished ctgfa and twist1a expression. Yap thus lies upstream of ctgfa-dependent bridging and twist1a-driven EMT.
- Twist1a gain-of-function (heat-inducible) enhanced functional recovery and doubled glial bridging and ependymal proliferation, demonstrating EMT activation is sufficient to promote repair.

---

## Perspective

- **Significance**: Identifies EMT as a hallmark distinguishing regenerative zebrafish glia from non-regenerative mammalian glia, and defines a multi-nodal Yap → ctgfa/twist1a gene regulatory network that is both necessary and sufficient for glial bridging and functional SC repair. Proposes that shifting mammalian glia toward a bridging/mesenchymal phenotype could abate scarring and support axon regrowth.
- **Limitations**: Mechanistic dissection focused on a defined set of transcription factors; the precise mechanical/Hippo sensing upstream of Yap and the direct translatability to mammalian astrocytes remain to be established. Cross-species comparisons rely on published mammalian datasets.
- **Future directions**: Test whether activating this EMT-driving network in mammalian glia promotes bridging and recovery; further resolve the ventral ependymal progenitor niche and its lineage restriction toward motor-domain fates.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
