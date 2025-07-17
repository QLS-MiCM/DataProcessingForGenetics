# Learning Your Data: Data Processing of Genetic Data
## Overview
This workshop provides a comprehensive introduction to the foundational quality control measures and analyses in population genetics. You'll learn to work with genetic data through the complete pipeline from raw VCF files to publication-ready analyses. The workshop covers essential topics including genome builds, liftover procedures, basic quality control, Principal Component Analysis (PCA), and Genome-Wide Association Studies (GWAS).
By the end of this workshop, you'll understand how to:

  * Perform genomic coordinate liftover between different genome builds
  * Apply standard quality control filters to genetic data
  * Conduct population structure analysis using PCA
  * Run basic GWAS analyses and interpret Manhattan plots
  * Process and standardize genetic datasets for downstream analysis

## Requirements
## Knowledge Requirements

  * Basic understanding of genetics and genomics concepts
  * Familiarity with Python programming (beginner to intermediate level)
  * Basic statistics knowledge (helpful but not required)

## Required Python Packages
The following packages will be used in this workshop:
  
  * scikit-allel - For genetic data manipulation and analysis
  * pandas - Data manipulation and analysis
  * numpy - Numerical computing
  * matplotlib - Data visualization
  * seaborn - Statistical data visualization
  * scikit-learn - Machine learning tools (for PCA)
  * scipy - Scientific computing
  * pysam - Reading/writing genomic data files
  * pyliftover - Genomic coordinate conversion
  
  Command-line installation instructions: pip install scikit-allel pandas numpy matplotlib seaborn scikit-learn scipy pysam pyliftover
## Required Dataset 
  * Attached to the GitHub repository
  * Tarball of this Tutorial's dataset and the GRCh38 FASTA can be downloaded in the first cell of the Tutorial_Lesson.ipynb

## Outline
## Workshop Structure
All Excercises can be found in the Jupyter Notebook labeled Tutorial_Lesson.ipynb

1. Introduction to Genetic Data Processing

* Understanding genome builds and their importance
* Introduction to VCF (Variant Call Format) files


2. Genomic Coordinate Liftover

* Exercise: Liftover Tutorial - Converting genomic coordinates between different genome builds 
* Understanding coordinate systems and reference genomes


3. Reference Genome Alignment

* Exercise: Reference Alignment - Aligning variants to the reference genome
* Quality control of genomic variants
* Filtering invalid and ambiguous variants
* Handling strand flips and palindromic SNPs

4. Variant Quality Control

* Exercise: Applying standard quality control filters
* Missing data filtering
* Hardy-Weinberg Equilibrium testing
* Minor Allele Frequency (MAF) filtering

5. Population Structure Analysis

* Exercise: Conducting Principal Component Analysis on genetic data
* Understanding population stratification
* Visualizing genetic ancestry and population clusters

6. Genome-Wide Association Studies (GWAS)

* Exercise: Running basic association tests
* Statistical testing for trait associations
* Creating and interpreting Manhattan plots
* Understanding genome-wide significance thresholds
## References
*Workshop material created by Benjamin Kaufman, PhD Student in Human Genetics*
*Workshop created as part of the McGill Initiative in Computational Medicine*
