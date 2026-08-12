## ngmos T-DNA Homologous Sequence Dataset
## Project Overview

This dataset contains T-DNA homologous sequences identified from 2,614 naturally genetically modified organisms (ngmos) through systematic mining of publicly available sequencing repositories. The data were obtained by screening Sequence Read Archive (SRA) and Whole Genome Shotgun (WGS) datasets and recovering candidate cT-DNA fragments via assembly and validation pipelines.

These sequence resources can support:

- Identification of T-DNA insertion sites

- Homology and comparative sequence analysis

- Molecular detection primer design

- Evolutionary and phylogenetic studies of horizontal gene transfer

## Data Sources
## Primary Data Repositories

All raw sequencing data were retrieved from public databases:

- NCBI Sequence Read Archive (SRA)

- NCBI Whole Genome Shotgun (WGS) database

## Scope of Data Retrieval

The screening covered:

All publicly available Embryophyte sequencing datasets

Release period: earliest available records to May 2025

## Data Processing Workflow

The dataset was generated using a standardized bioinformatic pipeline:

- Whole Genome Shotgun (WGS) data analysis

- Retrieval and analysis of SRA datasets

- Recovery of cT-DNA sequences and assembly

- Filtering and removal of false positives

## Sequence Format and Naming Rules

All sequences are provided in FASTA format.

## Early Naming Convention
[SRR_ID]_[1/2/blank]_[list]

Explanation:

_1 or _2 indicates paired-end reads

Blank indicates single-end sequencing data

## Later Naming Convention
[SpeciesName]_[SRR_ID]_[1/2/blank]

This updated rule was introduced during later stages of the project to improve species traceability.

Notes

- Because the dataset was generated over an extended period, both naming systems coexist. However, all identifiers retain clear links to their original SRR accession number.
- This dataset does not imply that only 2,614 ngmos exist among Embryophytes. As new sequencing data continue to be released, additional ngmos may be discovered in future analyses.
