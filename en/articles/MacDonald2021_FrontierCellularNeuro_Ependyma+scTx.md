---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add Data Availability section"
---

# Single Cell Transcriptomics of Ependymal Cells Across Age, Region and Species Reveals Cilia-Related and Metal Ion Regulatory Roles as Major Conserved Ependymal Cell Functions

## Citation (NLM)

MacDonald A, Lu B, Caron M, Caporicci-Dinucci N, Hatrock D, Petrecca K, Bourque G, Stratton JA. Single Cell Transcriptomics of Ependymal Cells Across Age, Region and Species Reveals Cilia-Related and Metal Ion Regulatory Roles as Major Conserved Ependymal Cell Functions. Front Cell Neurosci. 2021;15:703951. doi:10.3389/fncel.2021.703951

**DOI:** [https://doi.org/10.3389/fncel.2021.703951](https://doi.org/10.3389/fncel.2021.703951)

---

## Background

Ependymal cells are ciliated-epithelial glial cells that develop from radial glia and line the ventricular system of the brain and the central canal of the spinal cord. They are critical for cerebrospinal fluid (CSF) homeostasis, brain metabolism, and waste clearance, and are implicated in developmental disorders, cancer, and neurodegenerative disease. Three subtypes are defined by cilia number and location: E1 (multiciliated; dominant in the adult forebrain ventricles), E2 (biciliated; line the spinal canal and parts of the third/fourth ventricles), and E3 (uniciliated; restricted third-ventricle regions). Despite their importance, ependymal cells remain understudied.

Here the authors mine publicly available single-cell RNA sequencing (scRNA-seq) datasets to define conserved and divergent ependymal cell gene signatures across age, nervous system region, and species, then validate key findings in tissue.

---

## Key Experiment Methods

1. Screening of public scRNA-seq datasets to identify high-quality ependymal cells; four datasets used: neonatal mouse forebrain (GSE123335), adult mouse forebrain (GSE100320), mouse spinal cord (PanglaoDB SRA667466), and adult human forebrain (provided by co-author).
2. Seurat (v4.0.1) quality control and clustering; ependymal clusters identified by marker genes Foxj1, Pifo, Dynlrb1/Dynlrb2 (radial glia by Gfap).
3. Slingshot pseudotime ordering of neonatal ependymal cells and radial-glia precursors to define immature vs mature gene signatures.
4. GO-term enrichment (clusterProfiler v3.18.1) on top 200 differentially expressed genes per ependymal cluster; top 30 GO-terms compared across datasets.
5. Integration of mouse neonatal, adult, and spinal cord datasets (SCTransform) to identify region/age-specific differentially expressed genes.
6. RNAscope in situ hybridization validation in neonatal and adult (P12 week) mouse brain, mouse spinal cord, and adult human brain autopsy tissue for Foxj1, Fam183b, Mt3 (metallothionein 3), and Rarres2.

---

## Results

- A single ependymal cluster (Foxj1+, Pifo+, Dynlrb1+) was identified in each dataset. Mature ependymal cells are already detectable at postnatal day 0: 14/15 top "mature-state" genes (Lrrc1, Meig1, Fam183b, Foxj1, etc.) from neonatal pseudotime were also highly expressed in adult cells, while immature-state genes (Phyhipl, Ncan, Bcan) were absent in adults.
- RNAscope confirmed Foxj1 and Fam183b along the ventricular lining at both ages; in the neonatal brain expression was restricted to the medial wall (Foxj1 ~34%, Fam183b ~20%), supporting a medial-to-lateral developmental progression.
- GO-terms clustered into three conserved categories across age and species: cilia-related, metal ion-related, and transport-related. Cilia terms dominated (20/30 neonatal, 15/30 adult mouse, 20/30 human). Metal ion regulation was strikingly overrepresented and conserved (4/30 neonatal, 9/30 adult mouse, 8/30 human; 8/30 in spinal cord).
- Metallothionein 3 (Mt3), a metal-ion-buffering gene, was highly expressed (74.6-100%) along all ventricular and spinal canal linings, including the neonatal lateral border where mature ependymal cells are not yet present, suggesting metal-ion functions may initiate before full maturation. MT3 was also confirmed in adult human ventricular lining.
- Region/age differences: spinal cord (E2) ependymal cells were the most distinct, uniquely enriched for an "oligodendrocyte differentiation" GO-term and upregulating Plp1. Transport-related GO-terms (e.g., driven by Aquaporin-4) were prominent in forebrain (E1) but absent in spinal cord. Neonatal-unique genes included Ccdc104/Ccdc19 (cilia development); adult-brain-unique genes included Rarres2 (Chemerin; inflammation).
- Rarres2 was highly expressed in adult brain (100%), minimal in neonatal brain (~12%), and undetectable in spinal cord (0%), consistent with periventricular inflammatory-lesion topography in the adult brain.
- Spinal cord (E2) ependymal cells uniquely carried a "negative regulation of neural precursor cell proliferation" GO-term, consistent with prior reports that E2 cells contribute to the regenerative response after spinal cord injury while E1 cells do not.

---

## Perspective

This resource-style study establishes that ependymal cell transcriptomes are remarkably homogeneous and conserved across age, species, and subtype, with cilia function as expected but also a previously underappreciated and conserved role in metal ion homeostasis (via metallothioneins), relevant to oxidative stress and neurodegenerative disease. For spinal cord/regeneration research, the most salient finding is that spinal canal E2 ependymal cells are transcriptionally distinct from brain E1 cells, uniquely expressing oligodendrocyte-differentiation and negative-proliferation-regulation programs, aligning with their documented latent regenerative capacity after spinal cord injury. Limitations include small ependymal cell numbers per dataset (33-344 cells), reliance on heterogeneous public datasets, a single human spinal cord absence (human data limited to brain), and correlative GO-based function inference validated for only a few genes. Future work should functionally test ependymal metal-ion regulation in disease and clarify the mechanistic basis of E1 vs E2 regenerative differences in the spinal cord.

## Data Availability

**Other accessions referenced in the text (reused/external data):**
- GEO: GSE123335, GSE100320


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
