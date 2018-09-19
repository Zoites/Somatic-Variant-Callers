Last Updated: December 20, 2017

# Somatic-Variant-Callers

## SNP and Indel Callers
[MuTect2](https://software.broadinstitute.org/gatk/documentation/tooldocs/current/org_broadinstitute_gatk_tools_walkers_cancer_m2_MuTect2.php) calls somatic short variants (both SNVs and indels) via local assembly of haplotypes. Tool is still under BETA status.

[EBCall](https://github.com/friend1ws/EBCall) detect somatic mutations including indels. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/?term=23471004)

[Strelka2](https://github.com/Illumina/strelka) calls both somatic SNVs and indels. Strelka2 also calls germline mutations. [Preprint](https://www.biorxiv.org/content/early/2017/09/25/192872)

[Samtools-mpileup](http://www.htslib.org/doc/samtools.html) call SNPs and short INDELs. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/21320865) 

[LoFreq](https://sourceforge.net/projects/lofreq/?source=navbar) is a fast and sensitive variant-caller for inferring SNVs and indels. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/23066108)

[Seurat](https://sites.google.com/site/seuratsomatic/) supports detection of small somatic mutations (SNVs/indels), LOH events, structural variation and allelic imbalance. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/23642077)

[VarScan](http://varscan.sourceforge.net/somatic-calling.html) calls somatic variants (SNPs and indels). [Paper](https://www.ncbi.nlm.nih.gov/pubmed/22300766)

[HapMuC](https://github.com/usuyama/hapmuc) utilize the information of heterozygous germline variants near candidate mutations to call SNPs. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/25123903)

[SNVSniffer](http://snvsniffer.sourceforge.net/homepage.htm#introduction) identifies both germline and somatic SNVs/indels. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/27489955)

[OutLyzer](https://github.com/EtieM/outLyzer) detects low allele frequency variants (SNVs/indels). [Paper](https://www.ncbi.nlm.nih.gov/pubmed/27825131)

[smCounter](https://github.com/xuchang116/smCounter) is a barcode/UMI-aware variant caller thats detects SNVs and indels. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/28049435). [Update: smCounter2](https://www.ncbi.nlm.nih.gov/pubmed/30192920)

[PECaller](https://github.com/wingolab-org/pecaller) detects SNVs and indels in whole-genome datasets. [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5347547/)

[16GT](https://github.com/aquaskyline/16GT) is a variant caller for Illumina whole-genome and whole-exome sequencing data.[Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5570013/)

## SNP Callers
[deepSNV](http://www.bioconductor.org/packages/release/bioc/html/deepSNV.html) detects low frequency variants in deep sequencing experiments (>=100x coverage). [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3998123/)

[LoLoPicker](https://github.com/jcarrotzhang/LoLoPicker) calls somatic variants from tumor sample against matched normal sample plus a user-defined control panel of additional normal samples. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/28416765)

[mutationSeq](http://shahlab.ca/projects/mutationseq/) is a software for somatic SNV detection. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/22084253)

[QuadGT](http://www.iro.umontreal.ca/~csuros/quadgt/) is a software package for calling single-nucleotide variants in four sequenced genomes comprising a normal-tumor pair and the two parents. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/?term=23734724)

[JointSNVMix](https://code.google.com/archive/p/joint-snv-mix/) implements a probabilistic graphical model to analyse sequence data from tumour/normal pairs jointly to more accurately classify germline and somatic mutations. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/22285562)

[Shimmer](https://github.com/nhansen/Shimmer) identifies somatic SNVs from matched normal and tumor samples. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/23620360)

[SomaticSniper](https://github.com/genome/somatic-sniper) identify SNPs that are different between tumor and normal (or in theory, any two bam files). [Paper](https://www.ncbi.nlm.nih.gov/pubmed/?term=22155872)

[Virmid](https://sourceforge.net/projects/virmid/) is a SNP caller designed for disease-control matched samples where the diseased sample cannot be purified enough. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/23987214)

## Multi-Sample Callers
[multiSNV](https://bitbucket.org/joseph07/multisnv/wiki/Home) calls somatic SNVs using NGS data from a normal and multiple tumour samples of the same patient. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/25722372)

[RePlow](https://sourceforge.net/p/replow/wiki/Home/) detects somatic SNVs from multiple samples. [Preprint](https://www.biorxiv.org/content/early/2017/08/23/179713)

[Shearwater](http://www.bioconductor.org/packages/release/bioc/html/deepSNV.html) detects low frequency variants in deep sequencing experiments (>=100x coverage). [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3998123/)

## Tumor-Only/Single/Unpaired Sample Callers
[ISOWN](https://github.com/ikalatskaya/ISOWN) is a supervised machine learning algorithm for predicting somatic mutations from tumor only samples. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/28659176)

[SomVarIUS](https://github.com/kylessmith/SomVarIUS) identifies somatic mutations from unpaired samples. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/26589277)

[LumosVar](https://github.com/tgen/LumosVar) is designed for calling somatic variants in tumor samples lacking matched normals. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/29052513)

## Single and Paired Sample Callers
[VarDict](https://github.com/AstraZeneca-NGS/VarDict) is a variant caller for both single and paired samples. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/27060149)

## Integrated Tools/Pipeline/Workflows
[BAYSIC](https://bitbucket.org/jtr4v/baysic) combines SNP variant calls produced by different methods using a bayesian approach. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/24725768)

[Cake](http://cakesomatic.sourceforge.net/) integrates four somatic variant-calling algorithms to identify SNVs. [Paper](https://www.ncbi.nlm.nih.gov/pubmed/23803469/)

[pyAmpli](https://github.com/MBeyens/pyAmpli) is an amplicon-based variant filter pipeline for targeted resequencing data. [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5729461/)
