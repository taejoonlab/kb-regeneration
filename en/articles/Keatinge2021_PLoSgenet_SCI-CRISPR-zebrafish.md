---
tags: [2026-07]
extract: 2026-07-16
---

# CRISPR gRNA phenotypic screening in zebrafish reveals pro-regenerative genes in spinal cord injury

## Citation (NLM)
Keatinge M, Tsarouchas TM, Munir T, Porter NJ, Larraz J, Gianni D, Tsai HH, Becker CG, Lyons DA, Becker T. CRISPR gRNA phenotypic screening in zebrafish reveals pro-regenerative genes in spinal cord injury. PLoS Genet. 2021;17(4):e1009515. doi:10.1371/journal.pgen.1009515

**DOI:** [https://doi.org/10.1371/journal.pgen.1009515](https://doi.org/10.1371/journal.pgen.1009515)

---

## Background
In contrast to mammals, zebrafish functionally regenerate axonal connections across the injury site after spinal cord injury. Prolonged inflammation is detrimental to recovery in mammals, but in zebrafish pro-inflammatory cytokines are rapidly down-regulated and the immune response promotes regeneration. Prior work showed that blood-derived macrophages are crucial for axonal reconnection and recovery from paralysis, controlling the injury environment by reducing anti-regenerative neutrophils and mitigating pro-inflammatory cytokines such as il1b. However, the mechanisms by which macrophages keep neutrophils and il1b in check during regeneration were largely unknown.

CRISPR/Cas9 approaches allow scalable assessment of gene function in zebrafish because phenotypes can be observed in acutely injected, mosaically mutated embryos. Synthetic RNA Oligo CRISPR guide RNAs (sCrRNAs) offer efficient targeting, but their activity is variable and unpredictable. The authors reasoned that pre-screening guides for high activity in vivo would enable robust phenotypic screening while minimizing off-target effects.

---

## Key Experiment Methods
1. Pre-screened over 350 sCrRNAs for in vivo activity using a restriction fragment length polymorphism (RFLP) assay, where the Cas9 cut site overlaps a restriction enzyme recognition site; defined highly active sCrRNAs (haCRs) as >90% efficiency.
2. Validated haCR effectiveness by direct allele sequencing (frameshift rates) and a hexb enzyme activity assay.
3. Phenotypic screen of 30 potentially macrophage-related genes using haCRs (max 2 per gene) injected into zygotes of Xla.Tubb:DsRed transgenic zebrafish; spinal cord stab/incision injury at 3 dpf at the 15th myotome.
4. Read-out: percentage of larvae with axonal "bridging" across the injury site at 24 and 48 hpl, scored blinded.
5. Generated stable mutant lines (F3 heterozygous incrosses) for five hit genes (tgfb1a, tgfb3, tnfa, sparc, cst7) to validate acute phenotypes.
6. Mechanistic analysis of tgfb1a/tgfb3: quantified macrophages (mpeg1:GFP), neutrophils (anti-Mpx), and il1b (qRT-PCR); pharmacological Tgf-β receptor inhibition (SB431542); Il-1β inhibition rescue (caspase-1 inhibitor YVAD); glial bridging (GFAP); touch-evoked swimming.

---

## Results
- 44% of the 350 tested sCrRNAs were haCRs (>90% activity); conventional in silico design rules correlated weakly with observed in vivo activity (R² ≈ 0.028–0.044), underscoring the value of in vivo pre-screening.
- Two haCRs together produced ~87% frameshift rate; a single haCR against hexb reduced enzyme activity by up to 80%, confirming strong gene disruption.
- Of 30 targeted genes, 10 hits significantly reduced axon bridging at 48 hpl (including cst7, sparc, tgfb1a, tgfb3, tnfa, ifngr1, hspd1, tbrg1, serpinb1, mertk); tnfa served as a positive control.
- Stable mutants confirmed impaired regeneration for 4 of 5 tested genes (tgfb1a, tgfb3, tnfa, sparc), but not cst7 (a false positive); pharmacological Tgf-β inhibition also reduced bridging, confirming Tgf-β signaling is necessary.
- tgfb1a haCR/mutant animals failed to resolve inflammation: neutrophils increased ~63-66% and il1b expression rose ~120% at 48 hpl, phenocopying macrophage loss, while macrophage numbers were unchanged. tgfb3 showed only a non-significant trend.
- Inhibition of Il-1β (YVAD) rescued the axon bridging defect in tgfb1a mutants, establishing that tgfb1a promotes regeneration at least in part by controlling neutrophil numbers and il1b expression. Only tgfb3 (not tgfb1a/sparc/tnfa) showed impaired glial bridging, indicating distinct glial vs axonal mechanisms.

---

## Perspective
The study establishes a rapid, scalable sCrRNA phenotypic screening paradigm — the key innovation being an in vivo RFLP pre-screen that identifies highly active guides, allowing a minimal 2-guide-per-gene approach that limits off-target and false-negative results. Applied to spinal cord regeneration, it identified functional pro-regenerative genes and provided mechanistic insight into how the immune response promotes repair: tgfb1a controls post-injury inflammation (neutrophils, Il-1β), extending the understanding of macrophage-mediated regeneration. Limitations include a false positive (cst7), some mutants showing milder phenotypes than acute injection (possible off-target exaggeration), inability to screen genes with essential developmental functions (dmt3 caused excessive mortality), and a highly targeted read-out that does not exclude other immune functions of hit genes. The authors note the approach can be adapted to any biological context with a transgenic label and robust read-out, and that future single-cell RNA-Seq could distinguish direct neuronal versus environmental actions of hit genes.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
