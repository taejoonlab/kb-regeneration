---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p04.txt
raw_data:
  - "SRA: SRP349043"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# hoxc12/c13 as key regulators for rebooting the developmental program in Xenopus limb regeneration

## Citation (NLM)
Kawasumi-Kita A, Lee SW, Ohtsuka D, Niimi K, Asakura Y, Kitajima K, Sakane Y, Tamura K, Ochi H, Suzuki KT, Morishita Y. hoxc12/c13 as key regulators for rebooting the developmental program in Xenopus limb regeneration. Nat Commun. 2024;15:3340. doi:10.1038/s41467-024-47093-y

**DOI:** [https://doi.org/10.1038/s41467-024-47093-y](https://doi.org/10.1038/s41467-024-47093-y)

---

## Background

During organ regeneration, after the initial responses to injury (wound healing, blastema formation, apical ectodermal cap formation), gene expression patterns similar to those in normal development are reestablished during the subsequent morphogenesis phase. This supports the idea that regeneration recapitulates development and predicts the existence of "rebooting" genes that reactivate the developmental program after the initial injury response—yet such rebooting mechanisms had been largely unknown.

Xenopus is a valuable model because of its life-stage-dependent regenerative ability: larvae regenerate a complete limb, whereas after metamorphosis froglets/adults form only a rod-like cartilage/skin "spike" despite forming an initial blastema. This makes the Xenopus froglet/adult limb a gain-of-function model for enhancing regeneration. The authors sought regeneration-specific factors (distinct from known developmental genes such as shh and fgfs) that reboot the developmental program during larval limb regeneration, and tested whether inducing them could improve froglet regeneration.

---

## Key Experiment Methods

1. **Comparative transcriptomic analysis** of Xenopus laevis developing limb buds (8 samples: distal/proximal at St. 52, 52.5, 53, 54; devDi/devPi) versus larval regenerating blastema (4 samples: distal/proximal at two time points; regDi/regPi); 12 sample types sequenced in triplicate, with principal component analysis and DEG quantification.
2. **Three-step screening** for regeneration-specific expression: (Screen 1) 1488 genes differentially expressed between corresponding development/regeneration pairs; (Screen 2) 104 genes with higher distal-than-proximal expression during regeneration; (Screen 3) regeneration-specificity scoring (max 8 points) yielding 10 top genes.
3. **RNAscope** for spatial expression of hoxc12.L, hoxc13.L, hoxa13.L (autopod marker), hoxa11.L (zeugopod marker).
4. **CRISPR/Cas9 knockout** of hoxc12 and hoxc13 (ATG target site) in diploid Xenopus tropicalis; left hindlimb amputated at prospective knee (~St. 52), right hindlimb as developmental control; phenotypes scored by digit number.
5. **Marker analysis** (msx1 for initial blastema), RNAscope/qPCR/bulk-transcriptome of patterning genes (shh, hoxd13, hoxa13, hoxa11, fgf8), and PH3+ cell counts for proliferation in the hoxa13-defined prospective autopod.
6. **Gain-of-function**: transgenic Xenopus laevis with heat-shock (hsp70)-inducible hoxc12/c13 linked to GFP via 2A peptide; localized heat shock to froglet blastema; morphological, histological (nerve/muscle), and transcriptomic analysis.

---

## Results

- hoxc12 and hoxc13 (transcription factors) showed the highest regeneration specificity in expression; their levels in regenerating tissue (regD1/regD2) were several- to ten-fold higher than other samples. Both were expressed in the prospective autopod region of the regenerating blastema, whereas during development only hoxc12 showed clear zeugopod-restricted expression.
- Knocking out either hoxc12 or hoxc13 had no effect on limb development (0/98 and 0/69 defects) or on initial blastema formation (normal wound healing, cone-shaped blastema, normal msx1 expression), but caused severe autopod regeneration defects (~40–50% abnormal, reduced digit numbers) in larval regeneration.
- hoxc12/c13 are required to reactivate axial patterning genes: shh and hoxd13 (posterior/distal) showed near-absent expression in severely affected knockouts; fgf8 and hoxa13 were reduced; P-D regionalization failed (hoxa11 abnormally expressed to the distal-most region). Bulk transcriptomics confirmed broad downregulation of patterning genes (except proximal meis1/2), indicating hoxc13 controls rebooting of a gene set rather than a single pathway.
- Proliferation (PH3+ cells) was significantly reduced specifically in the hoxa13-expressing prospective autopod region of knockouts.
- Gain-of-function: heat-shock induction of hoxc12/c13 in froglet blastema produced an AP-widened bulge; strikingly, ~one-third of transgenic froglets (hoxc12Tg 10/30, hoxc13Tg 7/21) showed distal cartilage trifurcation/bifurcation and paddle-like shape even without artificial heat shock (transgene induced by amputation stress). Cell proliferation and nerve quantity increased in Tg branches (muscle did not regenerate). Transcriptome shifted toward the developmental limb-bud state.
- Excessive heat-shock expression suppressed branching, suggesting an appropriate expression level is required. Branched cartilage lacked clear joints, so additional rebooting factors beyond hoxc12/c13 are needed for complete regeneration.

---

## Perspective

This study demonstrates the existence of genes (hoxc12/c13) that can, on their own, profoundly impact rebooting of the developmental program in a regeneration-specific manner—functioning during the morphogenesis phase after the initial injury response, without affecting normal development or initial blastema formation. It bridges the "regeneration recapitulates development" hypothesis with a concrete molecular trigger, and shows partial restoration of the very limited post-metamorphic (froglet) regenerative capacity via induced expression.

Limitations: gain-of-function only partially restored regeneration—branched cartilage lacked joint-like structures, muscle did not regenerate in Tg branches, and complete regeneration was not achieved, indicating additional rebooting factors are required. The knockout used X. tropicalis while transgenics used X. laevis. Future directions include identifying the full complement of rebooting factors, the upstream regulators and precise level-dependence of hoxc12/c13, and translating such rebooting strategies toward enhancing regeneration in low-capacity species including mammals.

## Data Availability

**Raw data generated by this study:**
- SRA: SRP349043

**Other accessions referenced in the text (reused/external data):**
- GEO: GSE165901


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
