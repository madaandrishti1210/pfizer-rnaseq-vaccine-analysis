# Pfizer BNT162b2 Vaccine RNA-seq Analysis

## Project Overview

This project analyzes RNA sequencing data generated from individuals receiving the Pfizer-BioNTech BNT162b2 mRNA vaccine.

The objective is to identify transcriptional changes induced by vaccination and investigate immune-related gene expression responses.

## Dataset

Publicly available RNA-seq data were obtained from NCBI Sequence Read Archive (SRA).

Associated study:

Systems vaccinology of the BNT162b2 mRNA vaccine in humans.

## Workflow

1. Download SRA data
2. Convert SRA to FASTQ
3. Quality control using FastQC
4. Alignment to GRCh38 reference genome using HISAT2
5. Gene-level quantification using featureCounts
6. Differential expression analysis using DESeq2
7. Biological interpretation and visualization

## Tools

- SRA Toolkit
- FastQC
- HISAT2
- SAMtools
- featureCounts
- R
- DESeq2

## Current Status

Project in progress.
