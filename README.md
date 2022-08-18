# Comparative-Genomics-tools

## **Tools for comparative genome analyses.**
It is not my intention to have a comprehensive list. Here I added tools I found useful, tools that others found useful (and tested their performance with simulated and/or real data), tools that were rewritten and maintained by others as an attempt to keep the tool update and easy to use.

The first time a software/pipeline/approach appears in this document, I included its webpage link (if available).

### **Tools for Multiple Sequence Alignment (MSA)**

- [MACSE](https://bioweb.supagro.inra.fr/macse/index.php?menu=releases), also [here](https://github.com/ranwez/MACSE_V2_PIPELINES). **MACSE: Multiple Alignment of Coding SEquences Accounting for Frameshifts and Stop Codons.** MACSE aligns coding NT sequences concerning their AA translation while allowing NT sequences to contain multiple frameshifts and/or stop codons. MACSE is the first automatic solution to align protein-coding gene datasets containing non-functional sequences (pseudogenes) without disrupting the underlying codon structure. It has also proved useful in detecting undocumented frameshifts in public database sequences and aligning next-generation sequencing reads/contigs against a reference coding sequence.

- [Mauve](http://darlinglab.org/mauve/mauve.html). Mauve is a system for constructing multiple genome alignments in the presence of large-scale evolutionary events such as rearrangement and inversion.

- [MafFilter](https://jydu.github.io/maffilter/). MafFilter is a program dedicated to the analysis of genome alignments. It parses and manipulates MAF files as well as more simple fasta files.

### **Tools for Pairwise genome alignment (MSA)**
- [Cgaln](https://github.com/rnakato/Cgaln). **Cgaln** (Coarse grained alignment) is a program designed to align a pair of whole genomic sequences of not only bacteria but also entire chromosomes of vertebrates on a nominal desktop computer.

### **Tools for orthology analysis**
- [OrthoFinder](https://github.com/davidemms/OrthoFinder)
- [OrthoMCL](https://orthomcl.org/orthomcl/app)
- [HaMStR](https://bionf.github.io/HaMStR/)

### **Tools for trascriptome assembly and downstream analyses**
- [Trinity](https://github.com/trinityrnaseq/trinityrnaseq). For transcriptome assembly.
- [TransDecoder](https://github.com/TransDecoder/TransDecoder/wiki). For finding long open-read frames on transcriptomes.
- [diamond](https://github.com/bbuchfink/diamond). Pairwise alignment of proteins and translated DNA faster than [BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi).
- [HMMER](http://hmmer.org). For searching sequence databases for sequence homologs, and for making sequence alignments. It implements methods using probabilistic models called profile hidden Markov models (profile HMMs).

### **Tools for paralogous prunning**
- [PhyloPyPruner](https://pypi.org/project/phylopypruner/). PhyloPyPruner is a Python package for phylogenetic tree-based orthology inference, using the species overlap method. It uses trees and alignments inferred from the output of a graph-based orthology inference approach, such as OrthoMCL, OrthoFinder or HaMStR, in order to obtain sets of sequences that are 1:1 orthologous

### **Tools for molecular evolution using phylogenies**
- [HyPhy](http://www.hyphy.org/about/)
- [PAML](http://abacus.gene.ucl.ac.uk/software/paml.html). Both tools for $D_N/D_S$ analysis.