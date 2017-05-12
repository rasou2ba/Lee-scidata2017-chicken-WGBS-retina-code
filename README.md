This repository contains code used for quality control and data analysis presented in:

    Langouet-Astrie CJ, Meinsen AL, Grunwald ER, Turner SD, Enke RA. RNA sequencing analysis of the developing chicken retina: a resource for the vision research community. Scientific Data 2016.

Data availability

Data is available in GEO under the accession number GSE65938.
Software used
Software 	Version 	URL
FastQC 	0.11.4 	http://www.bioinformatics.babraham.ac.uk/projects/fastqc/
STAR 	2.5.1b 	https://github.com/alexdobin/STAR/releases
FeatureCounts 	1.5.0 	http://bioinf.wehi.edu.au/featureCounts/
DESeq2 	1.6.2 	http://bioconductor.org/packages/DESeq2
Data analysis code

Code used for all of the quality assessment and data analysis steps are available in each of the scripts below.

    Quality assessment with FastQC
    Alignment with STAR
    Quantitation with featureCounts
    Normalization, visualization, and differential expression analysis with DESeq2

