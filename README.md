# LMB-panel-2021

This repository contains code and Jupyter Notebooks detailing the development of a 73 SNP assay from Genotype-by-Sequencing (GBS) data in three largemouth bass lineages (*Micropterus salmoides*, *Micropterus floridanus*), as presented in:

* Silliman K., Zhao H., Justice M., Thongda W., Bowen B., Peatman E. Complex introgression among three diverged largemouth bass lineages. *Evolutionary Applications*, In press. [doi: 10.1111/eva.13314](https://https://onlinelibrary.wiley.com/doi/full/10.1111/eva.13314)

This repository is intended to facilitate full reproducibility of the paper, as well as demonstrate how to perform a variety of phylogenetic and population genetic analyses on reduced-representation genomic SNP data. Please submit a Github issue if you have any difficulty accessing data or following along with the notebooks.

## Associated data repositories
* [NCBI SRA (# SSRP124535](https://trace.ncbi.nlm.nih.gov/Traces/sra/?run=SRR6266391): Raw multiplexed DNA sequences for X *Micropterus* samples, includi. 
* [figshare repository](https://figshare.com/projects/Complex_introgression_among_three_diverged_largemouth_bass_lineages/125746): VCF files of all filtered SNPs and diagnostic SNPs, Excel file with MassArray genotypes for the 73 SNP panel, input file for maximum likelihood phylogenetic analyses, sample metadata, and output files from Stacks.
* [NCBI GenBank #NRCI01000000.1](https://www.ncbi.nlm.nih.gov/nuccore/NRCI00000000.1/): draft *Micropterus floridanus* genome used for mapping of GBS data. 

## \* Documentation in progress
All of the code used for this project is in the repo, but I'm still in the process of organizing and documenting it so it is of general utility. Feel free to poke around and leave comments, but know it will be much more organized soon! 

## assembly folder
Markdown files and shell scripts detailing how to go from raw sequencing data to assembled GBS loci using bowtie and Stacks.

## code folder
Code to filter SNPs in a variety of ways, convert file formats, identify SNPs that are fixed betweeen different lineages, run population genetic/phylogenetic analyses, make plots in R, and do a little geographical modeling.

## analysis folder
Input and output files that go with code.







