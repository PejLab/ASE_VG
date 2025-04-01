# ASE VG
This repository contains reference VG estimates from population level reference datasets using our ANEVA-h framework. The value of VG can be used for performing outlier testing for allele-specific expression (ASE) Data using [ANEVA-DOT](https://github.com/PejLab/ANEVA-DOT).

## Data Format
Each file is an excel file with the following:
* Each row corresponds to a gene ID (idenitifed by ENSEMBL ID)
* For GTEx, each column is a tissue (abbreviated) with corresponding values being the VG of the gene (lower bound, VG, upperbound) from a parametric bootrap.  
* For MAGE, each column in an ancestry group with corresponding values being the VG of the gene (lower bound, VG, upperbound) from a parametric bootrap.  

## Datasets
### GTEx
_gtex_vg.xlsx_: VG computed from 15,000+ RNA-seq samples spanning 49 GTEx (v8) tissues with over 25 samples per tissue. VGs are computed per tissue using ASE data from [here](https://www.gtexportal.org/home/downloads/adult-gtex/haplotype_expression) and with tissue abbreviations consistent with our previous [efforts[(https://www.science.org/doi/10.1126/science.aay0256?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed). 

### MAGE
_mage_vg.xlsx_: VG computed from 701 LCL cell-lines spanning 25 population groups in MAGE with ASE data derived from [here](https://github.com/Krganapa/ASE_Data). VGs are computed per tissue with abbreviations consistent with our previous [efforts[(https://www.science.org/doi/10.1126/science.aay0256?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed).  
