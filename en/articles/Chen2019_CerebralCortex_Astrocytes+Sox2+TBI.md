---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
raw_data:
  - "GEO: GSE85213"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Astrocyte-Specific Deletion of Sox2 Promotes Functional Recovery After Traumatic Brain Injury

## Citation (NLM)

Chen C, Zhong X, Smith DK, Tai W, Yang J, Zou Y, Wang LL, Sun J, Qin S, Zhang CL. Astrocyte-Specific Deletion of Sox2 Promotes Functional Recovery After Traumatic Brain Injury. Cereb Cortex. 2019;29(1):54-69. doi:10.1093/cercor/bhx303

**DOI:** [https://doi.org/10.1093/cercor/bhx303](https://doi.org/10.1093/cercor/bhx303)

---

## Background

Traumatic brain injury (TBI) triggers a complex pathological cascade including glial activation, inflammation, cell death, and tissue loss. Astrocytes are a principal cell type driving this glial response; upon injury they convert into "reactive astrocytes" characterized by morphological change, altered gene expression, cell-cycle re-entry, and cytokine production. This reactive astrogliosis is central to scar formation and wound healing, but its net effect on recovery remains debated. The molecular mechanisms governing astrocyte activation after injury were largely unknown.

SOX2 is an SRY-related HMG-box transcription factor best known for its role in neural stem cells and brain development. In the adult it is enriched in neurogenic niches (subventricular zone, subgranular zone) and can be reactivated in astrocytes by injury. This study examined SOX2 expression and function in adult cortical astrocytes under normal conditions and after TBI, testing whether SOX2 is required for injury-induced reactive astrogliosis and how its loss affects recovery.

---

## Key Experiment Methods

1. Immunohistochemistry to map SOX2 expression across adult mouse cortical cell types (astrocytes via Aldh1l1-EGFP and glutamine synthetase; oligodendrocyte lineage via OLIG2/NG2; microglia via IBA1; neurons via RBFOX3), including young vs. aged (2 vs. 24 months) mice.
2. Genome-wide ChIP-seq of SOX2 on adult wild-type cortical tissue (anti-SOX2, triplicate, Illumina HiSeq; Bowtie alignment to mm10; HOMER peak calling, motif discovery, GO/Wikipathway analysis; GEO GSE85213).
3. Inducible astrocyte-specific knockout: hGFAP-CreERT2; Sox2f/f; Rosa-tdT mice (Sox2-cKO) with tamoxifen induction; floxed-negative littermates as controls.
4. Controlled cortical impact (CCI) model of TBI (2-mm tip, 1-mm depth, 3.0 m/s).
5. Behavioral battery: modified neurological severity score (mNSS), tail suspension, elevated plus maze, Morris water maze.
6. Quantification of reactive gliosis (GFAP+ area), lesion size, proliferation (BrdU/KI67), and cell densities; primary and adult astrocyte isolation (immunopanning) with qRT-PCR validation of SOX2 target genes.

---

## Results

- SOX2 is predominantly expressed in adult cortical astrocytes (≈60% of SOX2+ cells are GS+ astrocytes), weakly in a minority of neurons and OLIG2+ oligodendrocyte-lineage cells, and absent from IBA1+ microglia. Expression is unchanged with aging.
- ChIP-seq identified 9334 shared bound sites (2114 high-fidelity, peak score ≥10). Enriched motifs matched the canonical SOX/HMG-box and POU factors. SOX2 bound regulatory regions of astrogliosis genes including Nr2e1, Mmd2, Wnt7a, and Akt2; GO analysis enriched WNT, Delta-Notch, TGF-β, IL-6, and MAPK pathways.
- Under homeostasis, Sox2 deletion caused no change in astrocyte density, morphology, or behavior (mNSS, tail suspension, elevated plus maze, Morris water maze), though it mildly reduced dentate gyrus/lateral ventricle neurogenesis.
- CCI rapidly increased SOX2+ cell number and expression around the injury; >20% of these cells were KI67+. The SOX2+ reactive population was predominantly astrocytes (YFP+GFAP+, rising from 60% to >80% of SOX2+ cells), with smaller NG2+ and OLIG2+ fractions; microglia never expressed SOX2.
- Astrocyte proliferation occurred mainly in the first 7 days post-injury. Sox2 deletion reduced proliferating reactive astrocytes by >50%, reduced total GFAP+ area by ~50%, and reduced astrocyte cell-body hypertrophy. It also non-cell-autonomously reduced microglia/macrophage activation (>50%) and increased peri-injury neuronal density.
- Most unexpectedly, Sox2-cKO mice showed significantly smaller lesion size and reduced glial scar at 2 months, plus improved neurological recovery (mNSS), reduced depression-like behavior (tail suspension), and reduced risk-taking behavior (elevated plus maze). Morris water maze performance was unchanged.

---

## Perspective

This work establishes SOX2 as an essential transcriptional driver of injury-induced reactive astrogliosis in the adult cortex and shows, unexpectedly, that dampening this SOX2-dependent response is beneficial after TBI—reducing lesion size and improving behavioral recovery. Mechanistically, SOX2 acts by directly targeting multiple astrogliosis signaling pathways (WNT, Notch, TGF-β, IL-6, MAPK) via genes such as Nr2e1, Mmd2, Wnt7a, and Akt2, and its loss in astrocytes non-cell-autonomously restrains microglial activation. This positions SOX2-dependent signaling in reactive astrocytes as a candidate therapeutic target for brain trauma.

The finding sits within a contested literature: some studies show reactive astrocytes and glial scars protect tissue and restrict inflammation (and that preventing scar formation impedes spinal cord injury recovery), while others show gliosis contributes to secondary tissue loss and inhibits regeneration. The authors note these divergent roles likely depend on injury type and manipulation method. Limitations include reliance on a single CCI model, the mild neurogenesis reduction inherent to Sox2 deletion, and that the beneficial effect may be context-specific. The authors also relate this to their prior work in which SOX2 overexpression reprograms astrocytes/NG2 glia into neurons, suggesting an expression threshold governs whether endogenous SOX2 drives gliosis versus fate reprogramming—an avenue for future study in brain and spinal cord.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE85213


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
