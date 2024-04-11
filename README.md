# COVID-19 Virus Analysis

This project focuses on analyzing COVID-19 virus sequences and performing various analyses, including sequence alignment, phylogenetic tree construction, and comparative analysis. The analysis is conducted using R programming language and various R packages.

## Overview

The repository contains an R Markdown document (`CovidAnalysis.Rmd`) that performs the following tasks:
- Obtaining sequences of COVID-19 virus from GenBank database.
- Calculating the length of nucleotides and visualizing the comparison.
- Performing hierarchical global analysis.
- Concentrating the sequences in a FASTA file.
- Aligning the sequences using the DECIPHER package.
- Visualizing the alignment result.
- Creating a phylogenetic tree using the APE package.
- Analyzing the phylogenetic tree and providing insights into virus similarities and differences.

## Video Results

You can view the results of the analysis in the following video:
[![COVID-19 Virus Analysis Results](http://img.youtube.com/vi/Uwn1xaN3Vsk/0.jpg)](https://www.youtube.com/watch?v=Uwn1xaN3Vsk)

## Requirements

To run the analysis, you need to have the following installed:
- R programming language
- Required R packages: Biostrings, seqinr, adegenet, ape, ggtree, DECIPHER, viridis, ggplot2, msa, RColorBrewer

## Usage

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/andrea2702/CovidGenomicAnalysis
2. Open CovidAnalysis.Rmd in RStudio or any R Markdown compatible editor.

3. Install any missing R packages mentioned in the document.

4. Knit the R Markdown document to generate the analysis report.
