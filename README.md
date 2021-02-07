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

# Lesson 4
### Title: RNA assembly with Trinity
_Instructors: Alexis Marshall_

* Read QC and assessment prior to assembly
* rRNA depletion 
* Trinity

[Watch the tutorial](https://youtu.be/midCCiARfBA)

[Follow along with the tutorial](https://github.com/biovcnet/bvcn-binder-trinity)
