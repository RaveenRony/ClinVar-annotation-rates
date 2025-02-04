This folder contains the code used to analyse data received from Ken. 
For the scores given by Ken, all variants were annotated in HGVs.g format using GnomAD IDs, after this, the variants were converted from the GRCh38 build to the GRCh37 build. After the output was received, the files were loaded and used to analyse and create PCAs using data from dbNSFP rankscores aggregated by MyVariant for each gene.
The PCA was created using only rankscores that were between 0 and 1, and the PCA for each gene was created using variants with no missing rankscores.
The distribution of the population-private variants that are unreported on ClinVar from GnomAD that is present in OncoKB was observed as well.
