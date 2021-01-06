# expressed-variant-impact

# Contributors
Brian Haas 
Olaitan
Meghana Pagadala 
Kym Pagel


# Intro statement

# Why Trinity CTAT?

The CTAT-Mutation pipeline (https://github.com/NCIP/ctat-mutations/wiki) makes it easy to discover variants from rna-seq data, and requires only the RNA-seq reads as input. The pipeline also annotates variants, including the RADAR and RediPortal databases for identifying likely RNA-editing events, dbSNP and gnomAD for annotating common variants, COSMIC to highlight known cancer mutations, and OpenCRAVAT to annotate and prioritize variants according to likely biological impact and relevance to cancer.

The CTAT-Mutations Pipeline integrates GATK Best Practices along with downstream steps to annotate and filter variants, and to additionally prioritize variants that may be relevant to cancer biology. 

# How does it work?

# How to use

# Quickstart

## Input

## Output

# Annotations included by default

- Known or predicted RNA-editing site
- If the variant has entries in OMIM/OMIA or Clinical PubMed
- dbSNP ID and Variant Allele Origin (VAO, 0-unspecified 1-Germline 2-Somatic 3-Both)
- gnomAD allele frequency
- VAF
- Repeat family from UCSC Genome Browser Repeatmasker Annotations
- ADjacency to homopolymer sequence or splice sites
- Entropy around the variant
- COSMIC annotations, including somatic status
- HUGO Gene impacted and canonical transcript identifier
- Variant impact (sequence ontology)
- HGVS notation
- Number of samples that contain this variant
- CHASMplus driver status prediction
- ClinVar annotations
- Link to protein visualization
- Variant pathogenicity prediction by VEST and FATHMM

# Testing

# Installation

## Install Nim
