---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
raw_data:
  - "GEO: GSE102931"
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Single cell analysis reveals inhibition of angiogenesis attenuates the progression of heterotopic ossification in Mkx−/− mice

## Citation (NLM)

Lin J, Yang Y, Zhou W, Dai C, Chen X, Xie Y, Han S, Liu H, Hu Y, Tang C, Bunpetch V, Zhang D, Chen Y, Zou X, Chen D, Liu W, Ouyang H. Single cell analysis reveals inhibition of angiogenesis attenuates the progression of heterotopic ossification in Mkx−/− mice. _Bone Res._ 2022 Jan 3;10(1):4. doi: [10.1038/s41413-021-00175-9](https://doi.org/10.1038/s41413-021-00175-9).

---

## Background

Tendon heterotopic ossification (HO) is a condition in which bone forms within tendon tissue, causing severe impairment in daily life. Current clinical treatments for HO are limited to physical therapy, nonsteroidal anti-inflammatory drugs, and surgical removal of ectopic bone, with frequent complications and high recurrence rates. Mohawk (MKX) is a tendon-specific transcription factor, and spontaneous tendon HO has been reported in Mkx-deficient mice and rats. However, the cellular and molecular mechanisms of HO pathogenesis, particularly the contribution of various tendon resident cell subpopulations and the role of angiogenesis, remain insufficiently understood. This study utilized Mkx−/− mice as a tendon HO model to elucidate the pathogenic mechanisms of HO at the single-cell level and to investigate whether inhibition of angiogenesis could attenuate HO progression.

---

## Key Experiment Methods

**1. Human HO specimen analysis**

- H&E staining and OCN and MKX immunofluorescence in tendons from healthy individuals and HO patients to evaluate MKX expression

**2. Mkx−/− mouse HO model characterization**

- HO phenotype confirmed in Achilles, patellar, and tail tendons of WT and Mkx−/− mice by micro-CT and SOFG staining
- Bulk RNA-seq of 4-week-old tail tendon (DESeq2, FDR<0.05, |log2FC|>1), GO and KEGG analysis

**3. Single-cell RNA sequencing (scRNA-seq)**

- 486 cells captured from 4-week-old WT and Mkx−/− tail tendons using Fluidigm C1 system (HT IFCs); 466 cells passed QC
- Integrated analysis using Seurat alignment workflow (SAW), t-SNE visualization, unsupervised graph-based clustering
- Pseudotime trajectory analysis with Monocle 2

**4. Gene set score analysis**

- Osteoblast development, ossification, and bone mineralization-related gene set scores calculated using Seurat AddModuleScore function

**5. Vascular analysis**

- Vascular density quantified by CD31 immunofluorescence
- Blood vessels confirmed by SOFG staining

**6. BIBF1120 angiogenesis inhibition experiment (Mkx−/− degenerative HO model)**

- BIBF1120 (4 µg) or vehicle administered subcutaneously 3 times per week for 3 weeks starting at 14 days of age into Achilles tendon of Mkx−/− mice
- Ossification and vascular evaluation at 8 and 12 weeks by micro-CT, SOFG staining, CD31/OCN immunofluorescence

**7. BIBF1120 trauma-induced HO model (rat)**

- Achilles tendon of 8-week-old male rats punctured 25 times with 27G needle (ATP)
- BIBF1120 (40 µg) or vehicle administered subcutaneously 3 times per week for 3 weeks starting 3 days after injury
- micro-CT, histology, and immunofluorescence analysis at 9 and 12 weeks

**8. BIBF1120 side effect evaluation**

- Cell proliferation assessed by BrdU assay
- Transcriptomic profiles compared by RNA-seq
- TSPC marker (Mcam, Thy1, Nes) and tendon marker (Scx, Mkx, Egr1, Tnmd, Tnc, Col1a1) expression analysis

---

## Results

**MKX suppression in human HO** MKX protein was detected in tendons of healthy individuals but was markedly reduced in tendons of HO patients. OCN+ osteoblasts were confirmed at HO sites and junctions.

**Tendon HO development due to Mkx deficiency** Ectopic bone formation was clearly observed in Achilles, patellar, and tail tendons of Mkx−/− mice. SOFG staining showed that Mkx−/− tendons were rich in proteoglycan accumulation (red staining) and chondrocytes with round nuclei, confirming cartilage lesions and endochondral ossification.

**Bulk RNA-seq: upregulation of angiogenesis and osteochondrogenic genes** 393 genes were upregulated and 283 genes were downregulated in Mkx−/− tendons. Upregulated genes were enriched in cell adhesion, angiogenesis, bone regeneration, and ossification, while downregulated genes were enriched in collagen fibril organization, ECM organization, and tendon formation. KEGG analysis showed upregulation of Wnt, PI3K-Akt, and Rap1 pathways, and both angiogenesis-related genes (Ctgf, Mmp2, Pecam1, Vegfa) and osteochondrogenic genes (Sox9, Runx2, Spp1, Postn) were elevated.

**Single-cell analysis: identification of 3 cell types** Three cell clusters were identified in WT and Mkx−/− tendons: TPC (tendon progenitor cells, Cd44+/Thy1+/Ly6a+/Fstl1+), TB (tenoblasts, Itm2a+), and TC (tenocytes, Col11a2+/Col1a1+/Sparc+/Tnmd+/Fmod+). No difference in cell composition ratios between WT and Mkx−/− confirmed that cell population shift was not the mechanism of HO.

**Pseudotime analysis: premature activation of osteochondrogenic genes in Mkx−/− cells** In the TPC→TB→TC differentiation trajectory, tenogenesis marker expression patterns (Ly6a, Tppp3→Itm2a, Lgals3→Tnmd, Col1a1) were similar between WT and Mkx−/−. However, osteochondrogenic markers such as Spp1, Ogn, Mgp, and Comp were expressed earlier and at higher levels in Mkx−/− cells than in WT. Osteoblast development-related gene scores were significantly increased in Mkx−/− TPCs, indicating that HO is associated with excessive activation of the osteochondrogenic program from the TPC stage.

**Increased angiogenesis genes and blood vessels in Mkx−/− tendons** Angiogenesis-related GO terms were enriched in all cell types (TPC, TB, TC). Hif1a was highly expressed in Mkx−/− TCs, and Thbs1 was elevated in Mkx−/− TPCs and TCs. SOFG staining and CD31 immunofluorescence confirmed increased blood vessels in Mkx−/− tendons.

**BIBF1120 attenuates Mkx−/− HO** Ectopic bone volume was significantly reduced in both 8-week and 12-week BIBF1120-treated groups. SOFG staining showed that the vehicle group had large cancellous bone and bone marrow, which were reduced in the BIBF1120 group. CD31+ blood vessels and Ocn+ osteoblast numbers were significantly decreased in the BIBF1120 group.

**BIBF1120 effective in trauma-induced HO model** In the rat ATP model, BIBF1120 treatment significantly reduced HO formation and bone volume at 9 and 12 weeks. CD31+ blood vessels and Ocn+ osteoblasts were also decreased.

**Minimal impact of BIBF1120 on tendon homeostasis** BrdU-positive cell ratios, proliferation marker (Mki67, Pcna, Mcm2) expression, and transcriptomic profiles were similar between BIBF1120 and vehicle groups. TSPC marker and canonical tendon marker expression also showed no differences, confirming that BIBF1120 had minimal side effects on tendon cell proliferation and differentiation.

---

## Perspective

This study used single-cell analysis in the Mkx−/− mouse tendon HO model to elucidate that HO progression is closely associated with excessive activation of osteochondrogenic genes from the TPC stage and activation of angiogenesis programs across all cell types. Notably, the angiogenesis inhibitor BIBF1120 significantly suppressed ectopic bone formation and vascularization in both degenerative HO (Mkx−/−) and trauma-induced HO (rat ATP) models while minimally affecting tendon homeostasis, suggesting its clinical potential as an HO therapeutic agent.

BIBF1120 is a triple vascular kinase inhibitor targeting Vegfr, Pdgfr, and Fgfr, inhibiting pro-angiogenic signaling in vascular endothelial cells, pericytes, and smooth muscle cells. While Fgf/Fgfr and Pdgf/Pdgfr signaling are important for tendon growth and homeostasis, raising concerns that pan-inhibition by BIBF1120 might cause side effects in surrounding tendon cells, this study showed no impact on proliferation or major marker expression, demonstrating relatively specific HO inhibitory function.

Future studies should include precise lineage tracing of TPCs, comprehensive analysis of vascular-related cell populations (endothelial cells, pericytes, smooth muscle cells) through high-throughput single-cell methods, and development of more specific angiogenesis-targeted therapeutic agents beyond BIBF1120. This study provides an important foundation for understanding the pathogenic mechanisms of tendon HO and developing new therapeutic approaches.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE102931


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
