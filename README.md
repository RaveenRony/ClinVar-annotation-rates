# **Putative Breast Cancer Risk Variants from Populations of South Asian Ancestry are Under-Represented in Public Variant Classification Databases.**  

This repository contains the data and code used to analyse and visualise the data and generate figures used in the paper. 

## **Repository Structure**  
[Code](Code/) - Scripts used for analysing and visualising the data.

[Data](Data/) - Data downloaded from gnomAD [v4.0.0](Data/v4/) and gnomAD [v2.1.1](Data/v2/).

## **Requirements & Installation**
R was used for all the analysis.
To install all packages that were used for this analysis, run the code below.

install.packages(c("tidyverse", "here", "janitor", "visdat", "skimr", "rstatix", "dplyr", "knitr", "corr", "ggcorrplot", "FactorMineR", "factoextra", "rtracklayer", "GenomicRanges", "ggExtra"))
