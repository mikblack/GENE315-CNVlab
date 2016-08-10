## GENE315-CNVlab

Copy Number Variation lab module for GENE315 at University of Otago using 1000 Genomes Project data.

Rendered HTML of lecture and lab handouts:
 - https://rawgit.com/mikblack/GENE315-CNVlab/master/GENE315-lecture9.html
 - https://rawgit.com/mikblack/GENE315-CNVlab/master/GENE315-CNV_lab-week1.html
 - https://rawgit.com/mikblack/GENE315-CNVlab/master/GENE315-CNV_lab-week2.html

Lab lecture
 - GENE315-lecture9.Rmd: Lecture (half session) covering concepts behind bioinformatics component of CNV lab module.
 - GENE315-lecture9.html: HTML version of lecture slides.

Lab handouts for statistical analysis - weeks 1 & 2 (appendicies 1 & 2 of lab book) 
 - GENE315-CNV_lab-week1.Rmd: R markdown of R code and commentary for week 1.
 - GENE315-CNV_lab-week1.html: HTML version of week 1 handout.
 - GENE315-CNV_lab-week2.Rmd: R markdown of R code and commentary for week 2.
 - GENE315-CNV_lab-week2.html: HTML version of week 2 handout.

R helper functions
 - plotCNV.R: function to plot local CNV in specific genomic region (FCGR, IRGM or AMY1).

Data files
 - AMY1A-counts.csv: read count data for 1000 Genomes populations (CEU, YRI, CHB) in AMY1A region.
 - FCGR-counts.csv: read count data for 1000 Genomes populations (CEU, YRI, CHB) in FCGR region.
 - IRGM-counts.csv: read count data for 1000 Genomes populations (CEU, YRI, CHB) in IRGM region.
 - CNcalls.csv: CN call data for FCGR region (based on manual inspection of CN plots).
 - FCGR_rs117435514.csv: SNP genotype data for rs117435514 in 1000 Genomes populations (CEU, YRI, CHB).
 - IRGM_rs13361189.csv: SNP genotype data for rs13361189 in 1000 Genomes populations (CEU, YRI, CHB).
 - PNG: directory of figures for lecture notes and lab handouts
