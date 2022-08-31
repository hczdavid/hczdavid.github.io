---
layout: archive
title: "Tools"
permalink: /tools/
author_profile: true
redirect_from:
  - /resume
---

POSTm R package ([CRAN](https://CRAN.R-project.org/package=POSTm); [Github](https://github.com/hczdavid/POSTm))

* The POSTm package implements the phylogeny-guided microbiome OTU-specific association test as described in [Huang et al. 2022](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-022-01266-3). This method boosts the testing power by adaptively borrowing information from phylogenetically close OTUs of the target OTU. Whether or not borrowing information or the amount of information from the neighboring OTUs is data adaptive and supervised by phylogenetic distance and the outcome variable. POSTm is built on a kernel machine regression framework and inherited its advantages including flexible modeling of microbiome effects (e.g., effects from opposite direction), easy adjustment for covariates, and accommodation of both continuous and binary outcomes. 

CDSeq R package ([CRAN](https://CRAN.R-project.org/package=CDSeq); [Github](https://github.com/kkang7/CDSeq_R_Package); [Example](https://github.com/hczdavid/CDSeq))

* CDSeq is a complete deconvolution method using sequencing data. Simply put, CDSeq takes bulk RNA-Seq read counts data as input and estimates the cell-type-specific gene expression profiles (csGEPs) and sample-specific cell-type proportions (SSP) simultaneously. (Please install from Github)

* VSARgraph R package/Shiny app
* Loan calculator R Shiny app
* Bio-Discovery R Shiny app
* Automation of filling interactive PDF Shiny app




