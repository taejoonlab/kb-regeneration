---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# HDAC Inhibitor Titration of Transcription and Axolotl Tail Regeneration

## Citation (NLM)
Voss SR, Smith JJ, Cecil RF, Kabangu M, Duerr TJ, Monaghan JR, Timoshevskaya N, Ponomareva LV, Thorson JS, Veliz-Cuba A, Murrugarra D. HDAC Inhibitor Titration of Transcription and Axolotl Tail Regeneration. Front Cell Dev Biol. 2021;9:767377. doi:10.3389/fcell.2021.767377

**DOI:** [https://doi.org/10.3389/fcell.2021.767377](https://doi.org/10.3389/fcell.2021.767377)

---

## Background
Tissue regeneration requires numerous, precisely regulated changes in gene expression from injury to completion of repair. The axolotl (Ambystoma mexicanum) regenerates whole appendages, including the tail and spinal cord, in aquatic settings amenable to small-molecule screening. Building on prior work showing that the FDA-approved class I HDAC inhibitor romidepsin potently blocks axolotl embryo tail regeneration by altering the initial transcriptional response to injury, this study introduces an experimental and conceptual framework: treating regeneration as a discrete failure-versus-success trait with a critical threshold concentration.

By quantifying transcription across romidepsin concentrations that span the threshold defining regenerative failure versus success, the authors sought to identify the key genes most likely regulated by histone acetylation dynamics at the outset of regeneration.

---

## Key Experiment Methods
1. Romidepsin dosing (0, 0.05, 0.1, 0.5, 1.0, 5.0, 10.0 μM) on stage 42 axolotl embryos after 2 mm tail amputation, treated for 6 or 12 h post amputation (HPA); regeneration outcome scored at 6 days post amputation (DPA).
2. Targeted transcriptional analysis of 100 regeneration-associated genes (Nanostring probeset; 72 previously romidepsin-responsive) across the concentration series at 6 and 12 HPA (60 samples).
3. Non-linear (sigmoidal and biphasic) response-curve modeling to identify genes whose inflection points align with the critical threshold concentration.
4. Functional test of hyaluronan synthase 2 (Has2) via CRISPR-Cas9 gene editing (two gRNAs, 1-cell-stage injection) and chemical inhibition with calcitriol (active vitamin D); tissue regenerated quantified at 7 DPA.
5. Whole-mount V3 HCR fluorescent in situ hybridization for spatial gene expression.
6. Single-nuclei RNA-Seq (10x) of distal tail tips at 0 HPA and at 6 HPA in control and 10 μM romidepsin-treated embryos (133,193 nuclei; GEO GSE183645), with graph-based clustering and cell-type annotation.

---

## Results
- A critical romidepsin concentration defined regenerative outcome: embryos treated with ≤0.05 μM fully regenerated, whereas ≥0.5 μM produced blunt, non-regenerative tails (threshold higher, ≥0.5 to ≤1.0 μM, for 1-min treatment). Outcome depends on both concentration and dosage time.
- Transcript responses were largely concentration dependent: 90 of 100 genes were classified as sigmoidal or biphasic, and 38 response curves had inflection points between 0.05 and 0.5 μM. Cbx4 and Cited2 increased with dose; Has2 and Lep (fibroblast-like progenitor genes) decreased.
- Functional analysis implicated Has2 in tail regeneration: CRISPR-Cas9 Has2 editing caused pericardial edema, enlarged hearts, and reduced vasculature, and significantly less tail tissue regeneration; calcitriol inhibition of Has2 similarly reduced regeneration.
- Single-nuclei RNA-Seq identified 29 clusters (epidermal, muscle, fibroblast, notochord, spinal cord, endothelial, erythrocyte, and multiple neural cell types). Romidepsin-upregulated genes (Cbx4, Cited2, Smad7, Spry1, G0s2) were enriched in an injury cluster (cluster 1) associated with a non-regenerative state, while regeneration-associated genes (Lep, Has2) marked cluster 2; romidepsin drove more cells into the non-regenerative cluster 1.
- Key regeneration genes were expressed across multiple cell types rather than confined to one type; romidepsin altered them in the same direction across cell types, indicating HDAC activity integrates transcriptional regulation across cell types.
- The authors also detected alternative high/low global transcriptional states associated with repetitive-sequence transcripts and chromatin-modifying factors (e.g., Brd4), independent of injury or romidepsin.

---

## Perspective
This work establishes a titratable, dose-response framework for dissecting how a small molecule (romidepsin, a class I HDAC inhibitor) shapes transcription and regenerative outcome, and it validates the axolotl embryo as an epigenetic model for tail regeneration. It advances the field by showing that HDAC-mediated gene regulation is a shared, integrative property across many cell types and by providing candidate genes (e.g., Has2) prioritized for functional study. Limitations include uncertainty over direct versus indirect romidepsin effects (including on non-histone proteins), the correlative link between transcription and outcome, and unresolved questions about whether embryonic tail regeneration shows greater transcriptional plasticity than larval/adult regeneration. Future directions include ChIP-Seq of histone acetylation at permissive versus inhibitory concentrations and snRNA-Seq across a romidepsin concentration series.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
