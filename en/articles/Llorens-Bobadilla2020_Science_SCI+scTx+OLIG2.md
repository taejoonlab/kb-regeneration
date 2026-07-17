---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
---

# A latent lineage potential in resident neural stem cells enables spinal cord repair

## Citation (NLM)
Llorens-Bobadilla E, Chell JM, Le Merre P, Wu Y, Zamboni M, Bergenstråhle J, Stenudd M, Sopova E, Lundeberg J, Shupliakov O, Carlén M, Frisén J. A latent lineage potential in resident neural stem cells enables spinal cord repair. Science. 2020;370(6512):eabb8795. doi:10.1126/science.abb8795

**DOI:** [https://doi.org/10.1126/science.abb8795](https://doi.org/10.1126/science.abb8795)

---

## Background

Injuries to the central nervous system (CNS) are inefficiently repaired, and functional impairments typically persist permanently. Resident neural stem cells exist in the brain and spinal cord but, after injury, predominantly produce scar-forming astrocytes rather than the multilineage cell replacement needed for regeneration. In the spinal cord, this stem cell potential resides in a well-characterized population of ependymal cells lining the central canal, which are normally quiescent and generate almost exclusively astrocytes upon injury. Meanwhile, neural stem cell transplantation benefits recovery after spinal cord injury, in part by supplying oligodendrocytes that remyelinate demyelinated axons.

Because ependymal cells share a developmental origin with spinal oligodendrocytes, the authors hypothesized that a latent potential for expanded oligodendrocyte generation might exist in resident ependymal cells and could be unlocked to promote endogenous repair.

---

## Key Experiment Methods

1. Single-cell ATAC-seq (scATAC-seq, ~1100 cells) of non-neuronal spinal cord cells enriched for ependymal cells, integrated with reference scRNA-seq of the same tissue to annotate clusters.
2. Motif enrichment and analysis of OLIG2/SOX10 binding-site accessibility (including a conserved SOX10 enhancer) across cell clusters.
3. Generation of Rosa-CAG-LSL-Olig2-IRES-tdTomato mice crossed to Foxj1-creER (Foxj1-Olig2-tdT), with Foxj1-tdT controls, for ependymal-specific conditional OLIG2 expression and fate mapping.
4. ATAC-seq and RNA-seq on isolated ependymal cells (uninjured, 1 and 5 days post-injury) after dorsal funiculus incision.
5. Droplet-based 3′ scRNA-seq (~3000 cells) of fate-mapped tdTomato+ ependymal progeny (uninjured, 2 and 4 weeks post-injury); diffusion maps and pseudotime analysis.
6. Immunohistochemistry, RNAscope, expansion microscopy, and electron microscopy to assess oligodendrocyte identity and remyelination.
7. Moderate thoracic contusion model plus in vivo optogenetics/electrophysiology (AAV9-CAG-ChR2-EGFP in corticospinal tract) to measure light-evoked compound action potentials (optoCAP) and CST conduction velocity.

---

## Results

- scATAC-seq revealed that OLIG2 and SOX10 binding motifs — including a conserved SOX10 enhancer — were highly accessible in ependymal cells despite these factors not being expressed, indicating a latent (permissive) chromatin state for oligodendrogenesis.
- In uninjured Foxj1-Olig2-tdT mice, forced OLIG2 expression was compatible with ependymal identity and did not open the latent program. After injury, OLIG2-expressing ependymal cells rapidly gained accessibility at OPC-enriched OLIG2 binding sites (1.5× at 1 dpi, 1.9× at 5 dpi) and turned on SOX10.
- Injury induced abundant ependymal-derived oligodendrocyte lineage cells (epOLs): ~30% of ependymal progeny were SOX10+ at 4 weeks and ~11,000 cells by 12 weeks (>40-fold increase over controls). This occurred in parallel with, not at the expense of, astrocyte scarring, and did not deplete ependymal cells.
- Forced OLIG2 in parenchymal astrocytes failed to elicit efficient oligodendrogenesis, showing ependymal cells are specifically permissive.
- scRNA-seq resolved six clusters: an ependymal (EP) cluster, three astroependymal (AE) clusters (astrocyte scar fate), and two Sox10+ epOL clusters. Diffusion-map pseudotime showed OLIG2 biases early fate along divergent astroependymal vs. oligodendrocyte branches; epOLs recapitulated the stepwise developmental oligodendrocyte maturation program, including a self-amplifying OPC-like state, and matured to a MOL5/6 (Ptgds+, not Klk6+) identity.
- epOLs remyelinated axons: tdTomato membranes colocalized with MBP and paranodal CASPR; expansion and electron microscopy confirmed compact myelin ensheathment.
- In the contusion model, epOLs were far more numerous (~32,000 SOX10+ cells at 12 weeks) and partially rescued corticospinal tract conduction velocity (19.0% of uninjured in controls vs. 27.9% in Foxj1-Olig2-tdT mice); conduction velocity correlated with the percentage of CST myelin sheaths.

---

## Perspective

This work demonstrates that adult resident neural stem cells harbor a far greater regenerative potential than normally manifested: a latent, chromatin-encoded oligodendrogenic program that can be unlocked by a single transcription factor (OLIG2) together with an injury signal. Recruiting endogenous ependymal cells produced remyelinating oligodendrocytes in numbers comparable to cell transplantation (~30,000) and improved axon conduction, offering an alternative to exogenous cell therapy after CNS injury. Mechanistically, the latent enhancers may derive from developmental OLIG2 expression and require injury-dependent cofactors (e.g., Brg1) for unfolding. Limitations include the need for genetic OLIG2 induction (not yet a translatable delivery strategy), partial (not full) restoration of conduction velocity, and the requirement of injury as a permissive context; the additive effect with OPC-derived oligodendrogenesis suggests possible synergistic approaches for future therapy.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
