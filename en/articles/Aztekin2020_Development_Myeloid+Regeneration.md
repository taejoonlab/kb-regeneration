---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
---

# The myeloid lineage is required for the emergence of a regeneration-permissive environment following Xenopus tail amputation

## Citation (NLM)
Aztekin C, Hiscock TW, Butler R, De Jesús Andino F, Robert J, Gurdon JB, Jullien J. The myeloid lineage is required for the emergence of a regeneration-permissive environment following Xenopus tail amputation. Development. 2020;147(3):dev185496. doi:10.1242/dev.185496

**DOI:** [https://doi.org/10.1242/dev.185496](https://doi.org/10.1242/dev.185496)

---

## Background
Regeneration-competent vertebrates are thought to suppress inflammation faster than non-regenerating ones. The immune system, and the myeloid lineage in particular, can positively influence regeneration in appendages and cardiac tissue across salamander, zebrafish, and mouse, largely through ECM remodeling, histolysis, vascularization, and apoptotic cell clearance. However, the cellular events controlled by inflammatory states in highly regenerative animals were poorly defined.

*Xenopus laevis* tadpoles regenerate their tails but temporarily lose this ability at defined developmental stages. The authors previously showed this loss is caused by failure to mobilize the regeneration-organizing cells (ROCs) that form the wound epidermis and secrete growth factors. Here they ask how the myeloid lineage contributes to establishing a regeneration-permissive environment, using naturally occurring regeneration-competent and -incompetent tadpole stages.

---

## Key Experiment Methods
1. **Myeloid depletion (three complementary approaches):** clodronate-containing liposomes (Clodrosome vs. Encapsome control) injected into the ventral vein; slurp1l:NTR + metronidazole (MTZ) genetic ablation; CRISPR/Cas9 mosaic knockout of spib.
2. **Regeneration assays:** ~30-50% tail amputation, scored at 7 dpa with a regeneration index; regenerated-tail-to-body-length ratio by Fiji.
3. **RT-qPCR** of myeloid genes (normalized to ef1α/gapdh) to confirm depletion.
4. **Tissue remodeling** quantified as a "remodelling index" (amputation plane length / posterior somitic tissue length).
5. **Apoptosis assay** using LysoSensor (cytoplasmic acidity) validated against caspase-3 IHC; apoptosis inhibitor NS3694 and hyaluronic-acid (HA) synthesis inhibitor 4-MU used for epistasis.
6. **ROC mobilization assay** with pbin7Lef:GFP reporter and anti-EGFP staining.
7. **scRNA-seq re-analysis** of the Aztekin et al. 2019 tail cell atlas to characterize myeloid subpopulations and their differential abundance.
8. **Immune-suppressing drug rescue** (FK506, Celastrol) in regeneration-incompetent tadpoles.
9. **Adult frog experiments:** peritoneal leukocytes after FV3 virus or heat-killed *E. coli* stimulation, sorted by flow cytometry.

---

## Results
- **Myeloid lineage is required for regeneration:** all three depletion strategies (clodronate, slurp1l:NTR/MTZ, spib CRISPR) reduced tail regeneration in regeneration-competent tadpoles. (Note: the slurp1l promoter was activated in non-myeloid cells, including ROCs, upon amputation, cautioning its use in later stages.)
- **Myeloid lineage controls a hierarchy of cellular events:** depletion reduced tissue/ECM remodeling, increased amputation-induced apoptosis, and impaired ROC mobilization to the amputation plane.
- **Epistasis:** blocking HA synthesis (4-MU) reduced remodeling but not apoptosis; blocking apoptosis (NS3694) reduced remodeling. This places myeloid activity upstream, controlling apoptosis → HA-mediated ECM remodeling → ROC relocalization.
- **Inflammatory vs. reparative myeloid balance:** the tail atlas contained two myeloid clusters — inflammatory (e.g., tnf-enriched) and reparative (e.g., arg1, mmp1/9-enriched). Intact tails had similar ratios regardless of competency, but at 1 dpa competent tadpoles showed dominant reparative myeloid activity whereas incompetent tadpoles showed dominant inflammatory activity.
- **Immune suppression restores competency:** FK506 or Celastrol treatment of regeneration-incompetent tadpoles reduced inflammatory myeloid gene expression, lowered apoptosis, enabled remodeling, and permitted (slightly delayed) ROC mobilization, rescuing regeneration in some tadpoles. Co-treatment with 4-MU or NS3694 abrogated this rescue.

---

## Perspective
The study establishes the myeloid lineage as essential for tail regeneration in a regeneration-competent vertebrate and defines the sequence of cellular events it controls: apoptosis regulation, HA-dependent ECM remodeling, and ROC relocalization, which together create a regeneration-permissive environment. Regeneration incompetency is characterized by a failure to shift from inflammatory to reparative myeloid activity, and pharmacological immune suppression can partially reinstate competency.

Significance: because suppression of inflammatory myeloid cells supports repair across mouse injury models (from spinal cord injury to hair regeneration and scar reduction), *Xenopus* offers a tractable system for drug/genetic screens to promote reparative myeloid activity. Limitations: the proposed hierarchy is one-directional and correlative — direct causal links and reciprocal crosstalk remain untested; whether inflammatory myeloid cells directly block regeneration is unproven; no neutrophil cluster was captured; and LysoSensor may label some non-apoptotic (high-pH) cells. A conserved myeloid role in specialized wound epidermis formation (as in axolotl limb, mouse digit tip, zebrafish fin) is proposed but requires cross-species validation.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
