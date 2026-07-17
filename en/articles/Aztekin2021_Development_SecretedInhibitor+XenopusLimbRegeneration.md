---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
---

# Secreted inhibitors drive the loss of regeneration competence in Xenopus limbs

## Citation (NLM)
Aztekin C, Hiscock TW, Gurdon J, Jullien J, Marioni J, Simons BD. Secreted inhibitors drive the loss of regeneration competence in Xenopus limbs. Development. 2021;148(13):dev199158. doi:10.1242/dev.199158

**DOI:** [https://doi.org/10.1242/dev.199158](https://doi.org/10.1242/dev.199158)

---

## Background
Amphibian limb regeneration relies on a specialized wound epidermis (the apical-epithelial-cap, AEC), characterized primarily in salamanders. Absence or immaturity of this tissue is hypothesized to limit regeneration in higher vertebrates including mammals, but the factors preventing its formation in regeneration-incompetent animals were poorly understood. The AEC has been proposed to be analogous to the apical-ectodermal-ridge (AER) of developmental limb buds (both express Fgf8), but conflicting data left it unclear whether AEC cells use a novel transcriptional program or re-deploy the developmental AER program.

*Xenopus laevis* is the only common model organism that develops limbs like amniotes, has a detectable AER, and shows limb regeneration — while progressively losing regeneration ability during development (competent NF ~52-54; restricted NF ~55-57; incompetent NF ~58+). Competency also depends on amputation position (reduced when through bone or proximal/chondrogenic regions). The authors used scRNA-seq and ex vivo regenerating limb cultures to define the cellular framework of wound-epidermis formation and its failure.

---

## Key Experiment Methods
1. **scRNA-seq atlas** (42,348 cells, ≥2 replicates/condition, cell-cycle corrected): developing intact hindlimbs (NF ~52, ~54, ~56) and amputated limbs at 5 dpa for regeneration-competent (NF ~52-53), -restricted (NF ~55-56), and -incompetent (NF ~58-60) stages, plus contralateral controls; ~60 clusters annotated. Interactive platform provided.
2. **Transcriptomic comparison** of AER (Fgf8+ epidermal cells in development) vs. AEC (Fgf8+ epidermal cells at 5 dpa), and vs. tail ROCs.
3. **Ex vivo regenerating limb culture** protocol enabling drug screens, co-culture, and conditioned-media experiments inaccessible in vivo.
4. **Small-molecule pathway inhibitor screen** (SU5402/FGF, LDN193189/BMP, ICRT3/WNT, SB431542/TGFβ, DAPT/NOTCH) on explants, reading out Fgf8.L by HCR in situ.
5. **EdU incorporation** to test whether AER cells arise via cell division; factor analysis of Lgr5.S → Fgf8.L trajectory.
6. **Co-culture and conditioned-media** experiments (competent + incompetent explants) with anti-NOGGIN / anti-IgG antibody rescue.
7. **In vivo bead implantation** of anti-NOGGIN, FGF10, and FGF10+NOGGIN on amputation planes; tip-explant cultures to limit chondrogenesis; Alcian Blue histology.

---

## Results
- **AEC = re-deployed AER, not a novel state:** AEC (5 dpa) and developmental AER Fgf8+ epidermal cells were transcriptionally highly similar, aggregated in a single cluster, and both appeared largely as a monolayer of polarized cuboidal basal cells; they differ mainly in signaling-center potency. Limb AER cells and tail ROCs are similar but non-identical (appendage regeneration is context-dependent).
- **AER cell abundance correlates with regeneration outcome:** abundant AER cells in competent, limited in restricted, and largely absent in incompetent tadpoles at 5 dpa. Only AER cells co-express multiple ligands (FGF, BMP, WNT, DELTA, TGFβ) at high levels; Fgf8 alone does not discriminate potency.
- **Injury-induced mesenchymal plasticity:** upon amputation a subset of fibroblasts upregulated dedifferentiation/blastema and distal-progenitor/chondrogenesis genes (Sall4, Kazald1, Grem1, Shh, Msx1, Fgf10, Sox9); the extent correlated with AER cell abundance.
- **AER cell formation requires multiple pathways** (FGF, BMP, WNT, and also TGFβ and NOTCH) as shown by explant inhibitor screen; AER cells can form largely **without cell division** (~40% EdU+), via a stepwise Lgr5+ → Fgf8+ basal-epidermal trajectory.
- **Secreted inhibitors block AER formation:** co-culture with, or conditioned media from, regeneration-incompetent explants blocked AER cell formation in competent explants — a dominant inhibitory effect, not loss of promoting factors. Chondrogenic mesenchyme cells (enriched at late stages) express BMP/WNT antagonists, notably **Noggin**. Anti-NOGGIN antibody rescued AER formation in co-culture/conditioned media and mildly improved in vivo regeneration.
- **FGF10 operates upstream of Noggin:** FGF10 reduced proximal chondrogenesis (and FGFR blockade extended it); FGF10 + anti-NOGGIN induced ectopic proximal Fgf8 expression; FGF10-induced AER formation was cancelled by BMP inhibitors/NOGGIN; in vivo, co-loading beads with FGF10 + NOGGIN abolished the pro-regenerative effect of FGF10 alone.

---

## Perspective
Moving beyond tissue-level descriptions, this study shows that the specialized wound epidermis (AEC) is a re-deployment of the developmental AER program rather than a regeneration-specific novelty — implying mammals possess the transcriptional program but fail to redeploy it after injury. The key barrier to regeneration is the **enrichment of secreted inhibitory factors (e.g., Noggin) from the chondrogenic lineage**, rather than merely a lack of activating factors. FGF10 restores competency in part by suppressing chondrogenesis and thereby Noggin.

Significance: manipulating the extracellular environment (removing secreted inhibitors) or limiting chondrogenesis may be a strategy to restore regeneration potential in higher vertebrates. Limitations/future directions: anti-NOGGIN alone had only a mild in vivo effect, implying additional chondrogenic inhibitors (e.g., Chrdl1, Frzb) must also be neutralized (or reflecting delivery limitations); whether proximally-induced AER cells can support a proximal blastema, and the relationship to the "rule of distal transformation," remain open.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
