# TOPIC: Transcriptomics
A repository for the lessons and tutorials for the Transcriptomics TOPIC channel of the [BVCN](https://biovcnet.github.io/)


## Prerequisites
* [A working Unix environment](https://github.com/biovcnet/biovcnet.github.io/wiki/1.-Setting-up-a-local-Linux-(or-Unix)-environment)
* [Experience with the command line](https://github.com/biovcnet/biovcnet.github.io/wiki/2.-Using-the-Command-line)

# Overview
This BVCN topic will cover:

* An overview of transcriptomics and metatranscriptomics
* Lessons covering various applications, including:
    * Wetlab and _in silico_ rRNA depletion
    * Recovery/removal of rRNA from metatranscriptomic data

# Lesson 1
### Title: Introduction to Transcriptomics
_Instructors: Arkadiy Garber_

* What is a transcriptome?
* Case studies using transcriptomics: 
  * Differential gene expression 
  * Gene expression by community (metatranscriptomics)
  * Combining metatranscriptomics and metagenomics 
* General transcriptomic pipeline overview
* Transcript assemblers and read aligners

[Watch the lesson](https://www.youtube.com/watch?v=P6mB9CEVVR8&feature=youtu.be)


# Lesson 2
### Title: rRNA depletion (wet lab and in silico)
_Instructors: Arkadiy Garber_

* Why remove rRNA from you RNA samples?
* Various wet-lab rRNA depletion methods: 
  * NEBNext rRNA depletion using RNase H 
  * NEBNext mRNA enrichment using magnetic beads
  * DIY method using probes and streptavidin-coated magnetic beads
  * DASH: using Cas9 to remove unwatned high-abundance sequences
  * Illumina RiboZero kits
* Brief SortMeRNA intro

[Watch the lesson](https://www.youtube.com/watch?v=ZsXssq8b6o4&feature=youtu.be)

[Watch the tutorial](https://www.youtube.com/watch?v=GreyzZ5J0xo&feature=youtu.be)

[Follow along with the tutorial](https://github.com/Arkadiy-Garber/bcvn-binder-sortmerna)


# Lesson 3
### Title: Read counting with htseq-count
_Instructors: Arkadiy Garber_

* Generating count tables: where this is in the RNA seq pipeline
* The HTSeq framework
* htseq-count
* read mapping paramaters
* count table output
* comparison to other read counting tools

[Watch the lesson](https://youtu.be/7A5IgfZd0rM)

[Watch the tutorial](https://youtu.be/3n0ncYz5TlM)

[Follow along with the tutorial](https://github.com/biovcnet/bvcn-binder-htseq)

# Lesson 4 -- RNA assembly with Trinity

Initially forked from [here](https://github.com/binder-examples/conda). Thank you to the awesome [binder](https://mybinder.org/) team!

[![Binder](https://mybinder.org/badge_logo.svg)](https://gesis.mybinder.org/v2/gh/alexismarshall/bvcn-binder-trinity/master?urlpath=lab)
Click the Binder Badge to start. This binder may take some time to load ~5-10 min

Part of the [Bioinformatics Virtual Coordination Network](https://biovcnet.github.io/) :)

This tutorial is a step-by-step guide on how to de novo assemble pared-end RNA reads.   

## Recommended knowledge base and/or pre-reading

[Quality Control using FastQC and MultiQC](https://github.com/biovcnet/biovcnet.github.io/wiki/TOPIC%3A-Transcriptomics#lesson-2----rrna-depletion-wet-lab-and-in-silico)

[rRNA depletion](https://github.com/biovcnet/biovcnet.github.io/wiki/TOPIC%3A-Transcriptomics#lesson-2----rrna-depletion-wet-lab-and-in-silico)

## About this tutorial 
This tutorial will take you through the general advice provided for the [Best practices for de novo transcriptome assembly with Trinity](https://informatics.fas.harvard.edu/best-practices-for-de-novo-transcriptome-assembly-with-trinity.html) and show you how to assemble these quality trimmed and corrected reads with the de novo RNA assembler [Trinity](https://github.com/trinityrnaseq/trinityrnaseq/wiki)

We have provided two subsampled datasets from the following studies:
1. Sieradzki, E., Ignacio-Espinoza, J.C., Needham, D. et al. Dynamic marine viral infections and major contribution to photosynthetic processes shown by spatiotemporal picoplankton metatranscriptomes. Nat Commun 10, 1169 (2019). https://doi.org/10.1038/s41467-019-09106-z

2. Husnik F, Nikoh N, Koga R, et al. Horizontal gene transfer from diverse bacteria to an insect genome enables a tripartite nested mealybug symbiosis. Cell. 2013;153(7):1567-1578. https://doi:10.1016/j.cell.2013.05.040 
   
   Total dataset is available here https://www.ncbi.nlm.nih.gov/sra/SRX7867216[accn] 
   
   For more information see the following [MicroSeminar talk](https://www.youtube.com/watch?v=sG5qWK_9sf8&t=5s)

These two datasets represent vastly different ecosystems and are both provided to demonstrate the different challenges between de novo assembly of single organisms or more "simple" communities (2) verses de novo assembly of a metatranscriptome from more "complex" community assemblages (1).

[Watch the tutorial]()

[Follow along with the tutorial]()
