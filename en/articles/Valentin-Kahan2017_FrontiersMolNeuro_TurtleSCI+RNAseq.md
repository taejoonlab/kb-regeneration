---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Gene Expression Profiling in the Injured Spinal Cord of Trachemys scripta elegans: An Amniote with Self-Repair Capabilities

## Citation (NLM)
Valentin-Kahan A, García-Tejedor GB, Robello C, Trujillo-Cenóz O, Russo RE, Alvarez-Valin F. Gene Expression Profiling in the Injured Spinal Cord of Trachemys scripta elegans: An Amniote with Self-Repair Capabilities. Front Mol Neurosci. 2017;10:17. doi:10.3389/fnmol.2017.00017

**DOI:** [https://doi.org/10.3389/fnmol.2017.00017](https://doi.org/10.3389/fnmol.2017.00017)

---

## Background

Spinal cord injury (SCI) causes permanent loss of nervous function below the lesion in mammals, and available therapies (mesenchymal/neural stem cells, gene therapy with neurotrophins such as BDNF) achieve little functional recovery. The inability to regenerate the spinal cord is shared by mammals, birds and most reptiles, whereas non-amniote vertebrates such as salamanders and, more modestly, zebrafish can regenerate.

Slider turtles are the only known amniotes with spinal cord self-repair leading to substantial (though incomplete) functional recovery, forming a cellular bridge permissive for axon growth after injury and eventually regaining the ability to walk. Because turtles are the closest relatives of mammals with this capacity (a sister group of crocodilians and birds), they are a strategic model for asking why some vertebrate lineages regenerate the cord and others do not. Prior molecular studies used only limited candidate-gene sets; no genome-scale profiling of the turtle SCI response, nor a broad comparative analysis across vertebrates, existed. This study profiles the genome-wide gene expression response to SCI in Trachemys scripta elegans.

---

## Key Experiment Methods

1. Spinal cord transection in freshwater turtles (T. scripta elegans, ~6 cm carapace, n=12); "sham injured" surgical controls to subtract surgery effects.
2. Tissue collected 4 days after surgery from a 4 mm cord segment centered on the lesion epicenter (RNAlater), RIN>7.
3. RNA-seq: polyA-selected libraries (ScriptSeq); sequencing on Illumina GAIIX (2×100 PE) and MiSeq (2×75 PE); data deposited under SRA SRP082501.
4. Mapping reference: genome of the close relative Chrysemys picta (cpic v3.0.1) combined with a de novo transcriptome assembly of T. scripta (Trinity); reads assembled with TopHat/Cufflinks/Cuffmerge; divergent/unmapped reads analyzed separately.
5. Differential expression with DESeq2 (DE criteria: FDR<0.1, ≥2-fold change, ≥50 reads).
6. Functional analysis: Gene Ontology enrichment (Blast2GO, Fisher's exact test, FDR<0.05), metabolic pathway enrichment (PANTHER), protein-protein interaction networks (STRING, confidence >0.7; Louvain clustering in Pajek; visualization in Gephi).
7. Evolutionary/orthology analysis across human, mouse, opossum, chicken, green anole, Xenopus tropicalis, zebrafish and soft-shell turtle (fastortho + web databases).
8. Cross-species expression comparison of SCI response using published RNA-seq from mouse (non-regenerative) and Xenopus (regenerative tadpole vs non-regenerative post-metamorphic).

---

## Results

- 1057 genes were differentially expressed at 4 days post-injury (1300 under a less stringent criterion): 800 up-regulated and 257 down-regulated.
- Down-regulated genes were enriched for cholesterol biosynthesis (SQLE, HMGCS1, FDFT1, LSS), glutamatergic synaptic transmission, and other small-molecule biosynthesis; also cadherin and Wnt signaling.
- Up-regulated genes fell into four main groups: (1) response to ischemic/hypoxic insult and reactive oxygen species; (2) extracellular matrix (ECM) reorganization (>90 genes: MMPs, TIMPs, ADAMs/ADAMTs, cathepsins, integrin signaling, coagulation); (3) cell proliferation and death (>220 genes: mitosis, cell-cycle regulation, differentiation, gliogenesis, neural tube development, angiogenesis); and (4) immune response and inflammation (>180 genes: chemokines, complement, leukocyte/macrophage migration, antigen presentation).
- PPI network clustering also revealed smaller functional groups (carbohydrate catabolism, vesicular transport, myelination) not detected by enrichment analysis.
- Evolutionary distribution: almost all DE genes are present across vertebrates; no genes exclusive to regenerating taxa (no shared "regeneration genes" between turtle and zebrafish) were found. Gene absences were mostly attributable to incomplete assemblies or lineage-specific losses.
- Cross-species expression comparison: the turtle SCI response was more similar to mouse and non-regenerative (post-metamorphic) Xenopus than to regenerative (tadpole) Xenopus, which showed a radically different pattern (~60-70% of genes with departing behavior).
- Candidate genes potentially underlying turtle recovery included anoxia/carbohydrate-metabolism genes (BPGM/BPGG, LDHB), axon-guidance/regrowth genes (SEMA3A, SEMA4A, PAK1, MAP3K12) up-regulated in turtle but not others, and KDR (VEGFR) down-regulated in turtle but up-regulated in mouse.
- 8389 previously unannotated transcribed regions were identified; most did not have protein-coding features.

---

## Perspective

The work provides the first genome-scale characterization of the SCI response in a self-repairing amniote and situates it in a comparative evolutionary framework. Its central and somewhat unexpected conclusion is that the turtle's regenerative capacity is not a retained ancestral vertebrate character but a lineage-specific innovation, built by re-organizing the expression of genes present across all amniotes on an essentially non-regenerative genetic background (its response resembles that of non-regenerative mammals and post-metamorphic Xenopus more than regenerative tadpole Xenopus). Consistent with modern reptile phylogeny (turtles as sister to archosaurs), attributing turtle repair to an ancestral trait would require three independent losses, favoring the innovation interpretation.

The authors nominate anoxia tolerance, ECM remodeling and axonal regrowth pathways as promising candidates underlying functional recovery. Limitations include a single acute time point (4 days), pooled/small biological replicate numbers, reliance on a related-species genome (C. picta) with ~8% divergent sequences, and cross-species comparisons complicated by differing injury time points and paces. The finding that turtles and zebrafish share no exclusive "regeneration genes" suggests distinct molecular strategies for cord repair across regenerating lineages, cautioning against a single conserved regeneration program and motivating deeper, time-resolved and functionally validated studies.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
