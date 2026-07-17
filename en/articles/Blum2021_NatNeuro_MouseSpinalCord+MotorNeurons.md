---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# Single-cell transcriptomic analysis of the adult mouse spinal cord reveals molecular diversity of autonomic and skeletal motor neurons

## Citation (NLM)
Blum JA, Klemm S, Shadrach JL, Guttenplan KA, Nakayama L, Kathiria A, Hoang PT, Gautier O, Kaltschmidt JA, Greenleaf WJ, Gitler AD. Single-cell transcriptomic analysis of the adult mouse spinal cord reveals molecular diversity of autonomic and skeletal motor neurons. Nat Neurosci. 2021;24(4):572–583. doi:10.1038/s41593-020-00795-0

**DOI:** [https://doi.org/10.1038/s41593-020-00795-0](https://doi.org/10.1038/s41593-020-00795-0)

---

## Background
Spinal motor neurons transmit signals from the CNS to diverse peripheral targets and control virtually all skeletal and smooth muscle activity. Because their identity is tuned to the effector cells they control, they form a highly heterogeneous population, yet spinal motor neuron dysfunction underlies neuromuscular diseases such as ALS and spinal muscular atrophy, in which some motor neuron populations are selectively vulnerable while others are spared. Defining the transcriptional "ground state" of adult motor neuron subtypes is therefore key to understanding cell-type-specific vulnerability.

A major obstacle is that spinal motor neurons make up less than 0.4% of cells in the mammalian spinal cord, making them extremely difficult to profile transcriptionally. The authors developed a motor-neuron enrichment strategy that yielded roughly a 100-fold increase in motor-neuron nucleus representation over prior efforts, enabling an unbiased single-nucleus survey of motor neuron diversity in the adult mouse spinal cord.

---

## Key Experiment Methods
1. Single-nucleus RNA sequencing (snRNA-seq) of 43,890 nuclei from adult mouse spinal cord (male, female and mixed cohorts).
2. Motor-neuron nucleus enrichment using a Chat-Cre nuclear fluorescent reporter mouse to isolate cholinergic (Chat+) nuclei, plus FACS sorting of DAPI+GFP+tdTomato- nuclei (myelin depletion, sucrose cushion).
3. Graph-based clustering and marker-gene annotation to assign seven broad cell categories and to subcluster cholinergic neurons into 21 clusters (skeletal MN, cholinergic interneurons, visceral MN).
4. Iterative subclustering of visceral motor neurons, cholinergic interneurons, and skeletal motor neurons.
5. Single- and multiplexed in situ hybridization (e.g., Chat/Nos1, Chat/Nts/Fbn2, Chat/Htr1d/Npas1, Chat/Rbfox3/Vipr2, Htr1d/Plch1/Creb5) to validate markers and map spatial localization along the rostral–caudal axis.
6. Cross-referencing with the Allen Mouse Spinal Cord Atlas for spatial expression; deposition of data in an interactive web portal (spinalcordatlas.org).

---

## Results
- ~30% (13,589) of profiled nuclei were cholinergic neurons; seven broad categories identified (excitatory/inhibitory interneurons, cholinergic neurons, astrocytes, microglia, oligodendrocytes, endothelial cells).
- Cholinergic interneurons distinguished by Pax2; visceral (sympathetic) motor neurons by Nos1; skeletal motor neurons marked by Bcl6/Tns1. Dozens of new markers separate skeletal from visceral MNs; the study argues against previously proposed markers Fbn2 and Zeb2 for α motor neurons.
- Visceral motor neurons resolved into 16 transcriptionally distinct subpopulations with organ-relevant, cluster-specific hormone/neuropeptide receptor expression (e.g., Rxfp1 restricted to sacral cord; Adra1a in sacral clusters 3/7). The most common subtype (cluster 0) is neurotensinergic (high Nts), with binary Nts on/off expression.
- Cholinergic interneurons formed eight subpopulations; Nos1+ subsets and Pitx2+ partition cells (clusters 0/1) making "C bouton" synapses were characterized. Gldn selectively marks partition cells; Nrxn3 marks a transcriptional bifurcation possibly corresponding to ipsi- vs contralateral projecting populations.
- Skeletal motor neurons: γ motor neurons identified by high Htr1d / low Rbfox3, Spp1 (clusters 0, 2, 6); novel markers Npas1 (γ) and Vipr2 (α, exclusively expressed) validated by ISH.
- A novel γ motor neuron subpopulation, termed γ* (gamma star), was identified — distinguished from canonical γ by reciprocal Stxbp6/Plch1 (γ*) vs Creb5/Pard3b (γ) expression. The authors hypothesize γ* represents a fundamental subdivision of the fusimotor system and may correspond to the elusive β motor neuron.

---

## Perspective
This resource provides the first high-resolution single-nucleus transcriptional atlas of the adult mouse spinal motor system, defining the molecular logic (neuropeptides, transmitters, receptors) by which motor neurons communicate with peripheral targets. Its significance lies in furnishing a marker toolkit and web portal (spinalcordatlas.org) to genetically access previously uncharacterized motor neuron populations, enabling study of cell-type vulnerability in diseases such as ALS. Limitations include reliance on snRNA-seq (nuclear transcriptome), the need for further in vivo validation of newly proposed markers, and the unresolved question of whether γ vs γ* represent developmentally/functionally distinct cell types or transient activity states. Future directions include deeper characterization of putative markers (e.g., Bcl6, Tns1), functional testing of partition-cell circuitry (Nrxn3), and using this roadmap to reprogram stem cells into specific motor neuron subtypes.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
