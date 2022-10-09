---
layout: archive
title: "Projects"
permalink: /projects/project4
author_profile: true
---

## Project 5: CDSeqR: Fast Complete Deconvolution for Gene Expression Data from Bulk Tissues ([Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04186-5); [Github](https://github.com/hczdavid/CDSeq))

**Background**: Biological tissues consist of heterogenous populations of cells. Because gene expression patterns from bulk tissue samples reflect the contributions from all cells in the tissue, understanding the contribution of individual cell types to the overall gene expression in the tissue is fundamentally important. We recently developed a computational method, CDSeq, that can simultaneously estimate both sample-specific cell-type proportions and cell-type-specific gene expression profiles using only bulk RNA-Seq counts from multiple samples. Here we present an R implementation of CDSeq (CDSeqR) with significant performance improvement over the original implementation in MATLAB and an added new function to aid cell type annotation. The R package would be of interest for the broader R community.

**Result**: We developed a novel strategy to substantially improve computational efficiency in both speed and memory usage. In addition, we designed and implemented a new function for annotating the CDSeq estimated cell types using single-cell RNA sequencing (scRNA-seq) data. This function allows users to readily interpret and visualize the CDSeq estimated cell types. In addition, this new function further allows the users to annotate CDSeq-estimated cell types using marker genes. We carried out additional validations of the CDSeqR software using synthetic, real cell mixtures, and real bulk RNA-seq data from the Cancer Genome Atlas (TCGA) and the Genotype-Tissue Expression (GTEx) project.


**Conclusions**: The existing bulk RNA-seq repositories, such as TCGA and GTEx, provide enormous resources for better understanding changes in transcriptomics and human diseases. They are also potentially useful for studying cell–cell interactions in the tissue microenvironment. Bulk level analyses neglect tissue heterogeneity, however, and hinder investigation of a cell-type-specific expression. The CDSeqR package may aid in silico dissection of bulk expression data, enabling researchers to recover cell-type-specific information.


<img src="http://hczdavid.github.io/images/cdseq.png" alt="projects" width="1000"/>









