---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p04.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Distinct origin and region-dependent contribution of stromal fibroblasts to fibrosis following traumatic injury in mice

## Citation (NLM)
Holl D, Hau WF, Julien A, Banitalebi S, Kalkitsas J, Savant S, Llorens-Bobadilla E, Herault Y, Pavlovic G, Amiry-Moghaddam M, Dias DO, Göritz C. Distinct origin and region-dependent contribution of stromal fibroblasts to fibrosis following traumatic injury in mice. Nat Neurosci. 2024;27(7):1285-1298. doi:10.1038/s41593-024-01678-4

**DOI:** [https://doi.org/10.1038/s41593-024-01678-4](https://doi.org/10.1038/s41593-024-01678-4)

---

## Background
Regeneration in the adult mammalian CNS is limited, and one major limiting factor is the formation of fibrotic scar tissue. After injury, recruitment of fibroblasts and deposition of fibrotic extracellular matrix (ECM) are initially required for wound closure, but these processes result in persistent scar tissue. A moderate reduction of fibrotic scarring that still permits wound closure promotes axon regeneration and functional recovery after spinal cord injury (SCI) and alleviates disease severity in experimental autoimmune encephalomyelitis (EAE), making fibrotic scarring an attractive therapeutic target.

The authors had previously identified a small population of GLAST (Slc1a3)-expressing perivascular cells, named type A pericytes, as the cellular origin of scar-forming fibroblasts. GLAST+ cells represent roughly 10% of all PDGFRβ+ perivascular cells in the uninjured adult mouse brain and spinal cord. However, single-cell studies had also defined perivascular fibroblasts (sharing Pdgfrb but distinguished by Pdgfra and Col1a1), and it was unclear whether pericytes, perivascular fibroblasts, or both give rise to the fibrotic scar. This study set out to define the precise cellular origin and contribution of scar-forming stromal fibroblasts after SCI.

---

## Key Experiment Methods
1. **Genetic lineage tracing** with GLAST-CreERT2 and inducible Col1a1-CreERT2 transgenic mice crossed to R26R-tdTomato reporter and Pdgfrb-eGFP reporter lines, using tamoxifen-mediated recombination.
2. **Single-cell RNA sequencing (Smart-seq)** of FACS-sorted tdTomato+EGFP+ (GLAST+) and tdTomato−EGFP+ (GLAST−) perivascular cells from uninjured and injured spinal cords (520 cells passed QC; integrated with published Vanlandewijck et al. dataset; data in GEO GSE229916, GSE266250, GSE266251).
3. **SCI lesion models**: complete spinal crush (non-penetrating) at T10 and mild contusion (40 kdyn) at T9.
4. **Focal inflammation model**: intraspinal lipopolysaccharide (LPS) injection into gray or white matter.
5. **Optical tissue clearing and light-sheet microscopy** of 500-µm-thick spinal cord segments with SM22α (arterioles) and vWF (venules) labeling for 3D volumetric distribution analysis.
6. **Immunogold electron microscopy and 3D serial reconstruction** to compare ultrastructural features of GLAST+ and Col1a1+ cells.
7. **Proliferation-inhibition genetics**: Col1a1-CreERT2;Rasless mice to block injury-induced proliferation of perivascular fibroblasts.

---

## Results
- GLAST-expressing perivascular cells of the uninjured spinal cord comprise two transcriptionally distinct populations: pericytes (cluster 1; high Rgs5, Kcnj8, Abcc9, Cd248) and perivascular fibroblasts (cluster 2; high Col1a1, Col3a1, Lum, Dcn, Pdgfra); vSMCs formed a third cluster.
- Col1a1 was selected as a fibroblast-specific marker; the inducible Col1a1-CreERT2 line labeled ~6.9 fibroblasts per section vs ~28.5 cells for GLAST-CreERT2 (which labels both pericytes and fibroblasts). 98.3% of Col1a1+ fibroblasts co-expressed Slc1a3 (GLAST).
- Anatomically, Col1a1+ perivascular fibroblasts localize to large-caliber penetrating arterioles and venules (absent from capillaries), whereas GLAST+ pericytes also cover smaller arteriolar branches and the capillary bed. Gray matter contains more arteriolar branches/capillaries, giving more GLAST+ pericytes there; penetrating vessels run mostly in white matter.
- Electron microscopy confirmed that both lines label perivascular fibroblasts with similar ultrastructure, while GLAST-CreERT2 additionally labels capillary pericytes embedded in the vascular basement membrane.
- **Region-dependent scar contribution**: After complete crush, GLAST+ cells contributed ~77–90% of PDGFRβ+ scar-forming fibroblasts, whereas Col1a1+ fibroblasts contributed ~37–46%. Although virtually all scar-forming fibroblasts upregulate Col1a1 after SCI, only a fraction derive from Col1a1+ perivascular fibroblasts. Col1a1+ fibroblasts contributed significantly more to white matter scarring than gray matter, while GLAST+ pericytes contributed more to gray matter. Mild contusion confirmed these regional differences.
- Inhibiting proliferation in Col1a1-CreERT2;Rasless mice reduced scar-forming PDGFRβ+ fibroblast density by 29%, confirming a specific fibroblast contribution.
- **Inflammation**: Focal LPS injection recruited both cell types, but in gray matter only GLAST+ pericytes contributed to stromal fibroblasts (Col1a1+ contribution negligible), whereas both contributed in white matter—mirroring the SCI results.
- Integrated scRNA-seq of injured tissue revealed five connected stromal clusters and reconstructed molecular trajectories showing that pericytes and perivascular fibroblasts converge on generating stromal myofibroblasts.

---

## Perspective
This study resolves the cellular origin of the CNS fibrotic scar, showing that it derives from two distinct perivascular populations—pericytes and perivascular fibroblasts—whose contribution is region-dependent (pericytes dominate gray matter scarring, fibroblasts dominate white matter). Despite distinct origins, both converge transcriptionally on stromal myofibroblast generation, revealing previously unrecognized heterogeneity in scar formation. Significance: precise cell-of-origin and region-specific knowledge may enable targeted anti-fibrotic therapies tailored to lesion location to improve axon regeneration and functional recovery after SCI. Limitations: findings are from mouse models and rely on transgenic Cre lines with defined recombination efficiencies; human validation and biomarkers of injury severity remain to be established. Future directions include defining how these stromal populations contribute across different CNS injuries, developmental stages, and other neurological conditions.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
