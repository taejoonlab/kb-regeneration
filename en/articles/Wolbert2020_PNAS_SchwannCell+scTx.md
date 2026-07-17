---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Redefining the heterogeneity of peripheral nerve cells in health and autoimmunity

## Citation (NLM)
Wolbert J, Li X, Heming M, Mausberg AK, Akkermann D, Frydrychowicz C, Fledrich R, Groeneweg L, Schulz C, Stettner M, Alonso Gonzalez N, Wiendl H, Stassart R, Meyer zu Hörste G. Redefining the heterogeneity of peripheral nerve cells in health and autoimmunity. Proc Natl Acad Sci U S A. 2020;117(17):9466-9476. doi:10.1073/pnas.1912139117

**DOI:** [https://doi.org/10.1073/pnas.1912139117](https://doi.org/10.1073/pnas.1912139117)

---

## Background

The peripheral nervous system (PNS) is superficially simple: neuronal cell bodies are absent and only their axons extend into peripheral nerves, which are dominated by Schwann cells (SCs), classified morphologically as myelinating (mySCs) or nonmyelinating (nmSCs). While mySCs have been studied extensively, the phenotypes of nmSCs and non-SC cell types (nerve-associated fibroblasts, vascular cells, and resident leukocytes) remain poorly defined. Single-cell RNA sequencing (scRNA-seq) enables unbiased characterization of complex tissues, but a single-cell map of the nondiseased PNS had not been reported, with prior work focused only on the transcriptional response to nerve injury.

Here the authors generate an unbiased cellular map of the healthy rodent PNS at single-cell resolution and extend it to a model of chronic autoimmune neuritis, aiming to define cell-type markers and to understand how PNS parenchymal cells respond to local autoimmune damage — and whether that response is shared with CNS glia.

---

## Key Experiment Methods

1. Optimized cell extraction from mouse brachial plexus and sciatic nerves via enzymatic digestion, myelin depletion, and flow-cytometry sorting for viable cells.
2. Droplet/microfluidics-based scRNA-seq of pooled cells from naive adult female C57BL/6 mice (three biological replicates, 12 mice each; 36 total), yielding 5,400 high-quality PNS single-cell transcriptomes; clustering and manual annotation by marker genes.
3. Marker validation and spatial localization by RNA in situ hybridization (ISH; ViewRNA and BaseScope) and immunohistochemistry (IHC), including reporter mice (GfapGFP, PdgfraGFP).
4. Lineage-assignment costaining of candidate nmSC markers (Apod, Smoc2) with SC lineage markers (Ngfr, S100b, Sox10) and fibroblast markers, and of fibroblast markers (Sfrp4, Pi16).
5. Flow cytometry to confirm leukocyte composition and MHC class II heterogeneity of myeloid cells.
6. Leukocyte enrichment with rat donors for a second scRNA-seq dataset (12,500 transcriptomes) to resolve nerve-associated macrophage subsets.
7. Human sural nerve biopsies (patients without PNS pathology) stained for SOX10, MBP, CD34, ACTA2, CD45, CD68, CD4/CD8 to test conservation.
8. Chronic autoimmune neuritis model (ICAM-1−/−NOD mice) with cell–cell interactome analysis comparing PNS and CNS glial responses.

---

## Results

- Identified 12 PNS cell clusters: mySCs, nmSCs, fibroblasts, vascular smooth muscle cells, pericytes, lymphatic and two vascular endothelial types (EC1, EC2), and four hematopoietic clusters (myeloid MC, macrophage MP, T cells, B cells). ~65% of transcriptomes were SC/fibroblast, 20% vascular, 15% hematopoietic.
- mySCs expressed myelin genes (Plp1, Mbp, Mpz), Sox10, and lipid-metabolism/STAT3 genes; new-in-mySC candidates included metallothioneins (Mt1, Mt2), Fth1, and Btg2.
- nmSCs were defined by Apod, ceruloplasmin (Cp), and other markers; Apod/Smoc2 costained with SC lineage markers (Ngfr, S100b, Sox10, Gfap) but not with mySC (Mbp) or fibroblast markers, confirming SC-lineage identity. nmSC GSEA highlighted neural-crest and bone-formation pathways and the TF Osr2.
- Nerve-associated fibroblasts (Fn1, collagens, Pi16, Sfrp4) represented a matrix-fibroblast phenotype; they newly expressed the Wnt regulator Sfrp4, IGF-pathway members, and complement C3 (an axon-outgrowth inhibitor), suggesting a role in coregulating axonal growth.
- An unexpectedly abundant (15%) resident leukocyte compartment was found, including two transcriptionally distinct homeostatic myeloid/macrophage populations distinguished by Cx3cr1 vs. Pf4/Cxcl4 and by MHC class II expression; these differed from CNS microglia. The two-macrophage structure was confirmed in leukocyte-enriched rat data.
- Overall endoneurial leukocyte composition (T cells, macrophages) was conserved in human PNS, though B cells were not detected in nondiseased human nerve.
- In chronic autoimmune neuritis, infiltrating lymphocytes outnumbered homeostatic myeloid cells and remodeled the local cell–cell interactome, inducing a specific transcriptional response in glia that was partially shared between PNS and CNS glia.

---

## Perspective

This study provides the first unbiased single-cell census of the healthy PNS, delivering marker genes for previously underappreciated nmSCs and nerve-associated fibroblasts and revealing an unexpectedly complex, heterogeneous resident immune repertoire distinct from CNS microglia. The finding that autoimmune neuritis reshapes intercellular "immune networks" rather than affecting single cell types reframes inflammatory neuropathy, and the partially conserved glial autoimmunity module points to common response mechanisms across nervous system compartments.

Limitations include the absence of neuronal cell bodies from the dataset (which may exaggerate the apparent role of neuropathy genes in non-glial cells), low leukocyte numbers requiring rat enrichment and species mixing, and the inherent dropout of scRNA-seq (markers detected in only a fraction of cells per cluster). Future directions include functional dissection of nmSC/fibroblast markers in axonal support and regeneration, and leveraging the conserved PNS–CNS glial module for cross-compartment therapeutic strategies.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
