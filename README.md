Last Updated: November 01, 2017

# Somatic-Variant-Callers

## SNP and Indel Callers
[MuTect2](https://software.broadinstitute.org/gatk/documentation/tooldocs/current/org_broadinstitute_gatk_tools_walkers_cancer_m2_MuTect2.php) calls somatic short variants (both SNVs and indels) via local assembly of haplotypes. Tool is still under BETA status.

[EBCall](https://github.com/friend1ws/EBCall) detect somatic mutations including indels. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/?term=23471004)

[Strelka2](https://github.com/Illumina/strelka) calls both somatic SNVs and indels. Strelka2 also calls germline mutations. [Preprint](https://www.biorxiv.org/content/early/2017/09/23/192872)

## SNP Callers
[deepSNV](http://www.bioconductor.org/packages/release/bioc/html/deepSNV.html) detects low frequency variants in deep sequencing experiments (>=100x coverage). [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3998123/)

[LoLoPicker](https://github.com/jcarrotzhang/LoLoPicker) calls somatic variants from tumor sample against matched normal sample plus a user-defined control panel of additional normal samples. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/28416765)

## Multi-Sample Callers
[multiSNV](https://bitbucket.org/joseph07/multisnv/wiki/Home) calls somatic SNVs using NGS data from a normal and multiple tumour samples of the same patient. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/25722372)

[RePlow](https://sourceforge.net/p/replow/wiki/Home/) detects somatic SNVs from multiple samples. [Preprint](https://www.biorxiv.org/content/early/2017/08/23/179713)

[Shearwater](http://www.bioconductor.org/packages/release/bioc/html/deepSNV.html) detects low frequency variants in deep sequencing experiments (>=100x coverage). [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3998123/)

## Tumor Only Sample Caller
[ISOWN](https://github.com/ikalatskaya/ISOWN) is a supervised machine learning algorithm for predicting somatic mutations from tumor only samples. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/28659176)

[SomVarIUS](https://github.com/kylessmith/SomVarIUS) identifies somatic mutations from unpaired samples. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/26589277)
