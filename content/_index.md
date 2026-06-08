---
title: "Dreamscape ecosystem"
featured_image: "/images/header.svg"     
featured_image_class: "pv2-l pv2-m pv1" 
omit_header_text: false
---

Recent advances in single cell/nucleus transcriptomic technology have enabled collection of population-scale datasets to study cell type specific gene expression differences associated with disease state, stimulus, and genetic regulation. The scale of these data, complex study designs, and low read count per cell mean that characterizing cell type specific molecular mechanisms requires a purpose-built analytical framework. 

Dreamscape is a set of [R](https://www.r-project.org) / [Bioconductor](https://bioconductor.org) packages that powers differential expression analysis, variance decomposition, cell-type composition analysis, gene set enrichment, and genetic regulation of gene expression on population-scale single cell datasets.  

| | | 
|-|-|
|![](https://gabrielhoffman.github.io/lucida/reference/figures/logo.png)|[lucida](https://gabrielhoffman.github.io/lucida/): Scalable differential expression analysis at the single cell level[^lucida]| 
| ![](https://gabrielhoffman.github.io/GenomicDataStream/reference/figures/logo.png) |    [GenomicDataStream](https://gabrielhoffman.github.io/GenomicDataStream/): A scalable interface between genomic data and analysis underneath R[^GenomicDataStream] | 
|![](https://gabrielhoffman.github.io/fastglmm/reference/figures/logo.png)|[fastglmm](https://gabrielhoffman.github.io/fastglmm/): Efficiently Fit Generalized Linear Mixed Model with a Single Random Effect on Massive Datasets[^fastglmm]| 
|![](https://gabrielhoffman.github.io/BatchRegression/reference/figures/logo.png) |[BatchRegression](https://gabrielhoffman.github.io/BatchRegression/): Fit regression models on large-scale datasets| 
| ![](https://diseaseneurogenomics.github.io/dreamlet/reference/figures/logo.png) | [dreamlet](https://diseaseneurogenomics.github.io/dreamlet/): Scalable differential expression analysis of single cell transcriptomics datasets with complex study designs [^dreamlet]
| ![](https://diseaseneurogenomics.github.io/crumblr/reference/figures/logo.png)| [crumblr](https://diseaseneurogenomics.github.io/crumblr/): Count ratio uncertainty modeling based linear regression [^crumblr]
| ![](https://gabrielhoffman.github.io/img/dream_icon.png)| [dream](https://diseaseneurogenomics.github.io/variancePartition/articles/dream.html): Powerful differential expression analysis for repeated measures designs [^dream]
| ![](https://gabrielhoffman.github.io/img/variancePartition2.png)| [variancePartition](https://diseaseneurogenomics.github.io/variancePartition/): Interpreting drivers of variation in complex gene expression studies with linear mixed models [^vp]

[^lucida]: Hoffman, et al. Scalable differential expression analysis at the single cell level increases power in rare cell types. (in prep)
[^GenomicDataStream]: Hoffman, Li and Roussos. GenomicDataStream: A scalable C++ interface between genomic data and analysis underneath R [in prep]
[^fastglmm]: Hoffman. Efficiently Fit Generalized Linear Mixed Model with a Single Random Effect on Massive Datasets [in prep]
[^dreamlet]: [Hoffman, et al. Nat Comm (accepted)](https://www.biorxiv.org/content/10.1101/2023.03.17.533005v2)
[^crumblr]: [Hoffman and Roussos. Nat Comm (accepted)](https://www.biorxiv.org/content/10.1101/2025.01.29.635498v1) |
[^dream]: [Hoffman and Roussos. Bioinformatics (2021)](https://academic.oup.com/bioinformatics/article/37/2/192/5878955)
[^vp]: [Hoffman and Schadt. BMC Bioinformatics (2016)](https://link.springer.com/article/10.1186/s12859-016-1323-z)