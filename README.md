# scRNA-seq Immunology Pipeline

## Project Overview

This project aims to explore single-cell RNA sequencing (scRNA-seq) data to understand immune-cell heterogeneity and gene-expression patterns following bacterial skin infection.

## Research Context

The selected study, GSE287038, investigates how *Staphylococcus aureus* skin infection influences bone marrow immune cells and allergic skin–lung crosstalk.

## Objectives

- Understand scRNA-seq data and count matrices.
- Perform quality control and exploratory data analysis.
- Identify cell populations and examine gene-expression patterns.
- Compare infection-associated and control conditions, subject to sample metadata and experimental design.
- Learn to automate reproducible analysis using Snakemake.

## Dataset

- **Repository:** NCBI Gene Expression Omnibus (GEO)
- **Accession:** GSE287038
- **Organism:** Mouse (*Mus musculus*)
- **Tissue:** Bone marrow

## Planned Workflow

1. Dataset and metadata inspection
2. Count-matrix loading
3. Quality control and filtering
4. Normalization and dimensionality reduction
5. Cell-population exploration and annotation
6. Differential expression, if supported by the experimental design
7. Workflow automation with Snakemake

## Tools

Python, Scanpy, pandas, Matplotlib, Git, Linux/WSL, and Snakemake.

## Project Status

**Status:** Initial setup

The analysis workflow and results will be added progressively as the project develops.
