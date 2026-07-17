---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p03.txt
---

# Single-cell analysis uncovers convergence of cell identities during axolotl limb regeneration

## Citation (NLM)
Gerber T, Murawala P, Knapp D, Masselink W, Schuez M, Hermann S, Gac-Santel M, Nowoshilow S, Kageyama J, Khattak S, Currie JD, Camp JG, Tanaka EM, Treutlein B. Single-cell analysis uncovers convergence of cell identities during axolotl limb regeneration. Science. 2018;362(6413):eaaq0681. doi:10.1126/science.aaq0681

**DOI:** [https://doi.org/10.1126/science.aaq0681](https://doi.org/10.1126/science.aaq0681)

---

## Background

Axolotls (Ambystoma mexicanum) and other salamanders are the only tetrapods capable of regenerating entire limbs. After amputation, cells near the amputation plane accumulate in a transient tissue called the blastema, which serves as the progenitor source for the new limb. Connective tissue (CT) cells, descendants of lateral plate mesoderm, are the most abundant lineage contributing to the blastema and include bone, cartilage, tendon, periskeleton, and dermal/interstitial fibroblasts. These CT cells detect positional information and guide regeneration of appropriate limb parts.

A central unresolved question was whether mature CT cells molecularly "reprogram" into embryonic limb progenitor–like cells, or whether the CT harbors preexisting stem cells that selectively seed the blastema. Previously, molecular study was hampered by the inability to identify and isolate blastema precursor cells in the adult tissue. This work combines Cre-loxP lineage tracing with single-cell RNA sequencing (scRNA-seq) to track mature CT heterogeneity and its transition into the blastema state.

---

## Key Experiment Methods

1. Generated germline transgenic axolotl lines expressing tamoxifen-inducible Cre-ERT2 under the Prrx1 limb enhancer (Prrx1:Cre-ER;Caggs:lp-Cherry) to genetically label and track CT cells; validated with an anti-PRRX1 antibody as a pan-CT marker.
2. Generated a second driver line (Col1a2:ER-Cre-ER;Caggs:lp-Cherry) labeling a CT subset (skeleton, periskeleton, tendon).
3. High-throughput droplet-based scRNA-seq (10x Genomics) of dissociated adult limb and late blastema; high-transcriptome-coverage scRNA-seq (Fluidigm C1) of FACS-sorted mCherry+ CT cells along a dense regeneration time course (0, 3, 5, 8, 11, 18 dpa, and fully regenerated).
4. scRNA-seq of embryonic limb stages (stage 28 limb field, stage 40 and 44 limb bud) to compare regeneration with development.
5. Computational analyses: tSNE clustering, diffusion pseudotime, SPRING, mock bulk correlations, and intercellular heterogeneity metrics.
6. Tissue/humerus transplantation experiments between labeled and unlabeled animals to resolve proximal vs distal cell sources.
7. Brainbow transgenic clonal lineage tracing to test multipotency of single CT cells.

---

## Results

- scRNA-seq of the uninjured adult upper arm CT identified eight clusters: tenocytes (Tnmd), periskeletal cells (Col8a2), actively cycling cells (Ccnb1), and five fibroblastic CT subpopulations (fCT I–V), providing a cell atlas and marker set.
- During blastema formation, heterogeneous differentiated CT cells "funnel" into a relatively homogeneous progenitor state; intercellular heterogeneity progressively decreases from the uninjured arm through the early blastema up to 11 dpa, then increases at 18 dpa as redifferentiation begins.
- No blastema-like cells were found in the uninjured tissue, and cell-contribution analyses showed no numerical bias — arguing that blastema formation does NOT involve selection of a preexisting stem cell population, but rather dedifferentiation of mature CT.
- Transcriptional dynamics: ECM genes down-regulated during blastema formation; inflammation (Il11, Cxcl2) and MMPs (Mmp8, Mmp13) at 3–5 dpa; proliferation genes by 8 dpa; repatterning (Hoxa13, Hoxd12) and ECM reestablishment (Matn4) by 11–18 dpa; skeletal genes (Hoxd13, Col2a1, Sox9) by 18 dpa.
- CT reprogramming passes through a blastema-specific state (distinct from embryonic development) before converging on an embryonic limb bud–like program; correlation with stage 40/44 limb bud transcriptomes peaks at 11 dpa.
- Distinct cell sources for proximal vs distal regenerate: Col1a2 line–derived cells (periskeleton/tendon) mainly extend existing bone at the amputation site, whereas fibroblastic CT cells regenerate distal skeletal segments de novo. Transplantation showed this spatial bias is due to callus association, not intrinsic segmental limitation.
- Late blastema (18/25/38 dpa) trajectories show multipotent progenitors expressing embryonic limb/cell cycle markers (Prdx2, Nrep, Ccnb1) branching into nonskeletal and skeletal (cartilage/bone) lineages; adult CT subtypes reemerge by 38 dpa.
- Brainbow clonal tracing confirmed that single CT cells give rise to skeletal, periskeletal, fibroblastic, and tendon cells — establishing a multipotent CT/skeletal progenitor.

---

## Perspective

This study provides a molecular map of how mature, heterogeneous connective tissue cells dedifferentiate into a common, multipotent limb bud–like progenitor during complex vertebrate organ regeneration, resolving a long-standing debate in favor of reprogramming rather than preexisting stem cell selection. The convergence-then-divergence ("funneling") model, supported by both single-cell transcriptomics and clonal lineage tracing, reframes blastema formation as molecular reprogramming.

Significance: it demonstrates that adult cells can be reprogrammed to embryonic limb potential capable of orchestrating limb morphogenesis, with clear implications for regenerative engineering. Limitations/future directions noted by the authors include the need to test which components of the transition state are required for dedifferentiation, and to examine how regeneration-associated genes and their chromatin structure are regulated. The work also raises the hypothesis that the limited regeneration in mammals may reflect an inability to reprogram CT to such embryonic states.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
