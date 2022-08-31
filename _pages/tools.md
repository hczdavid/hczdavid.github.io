---
layout: archive
title: "Tools"
permalink: /tools/
author_profile: true
redirect_from:
  - /resume
---

### POSTm R package ([CRAN](https://CRAN.R-project.org/package=POSTm); [Github](https://github.com/hczdavid/POSTm))

* The POSTm package implements the phylogeny-guided microbiome OTU-specific association test as described in [Huang et al. 2022](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-022-01266-3). This method boosts the testing power by adaptively borrowing information from phylogenetically close OTUs of the target OTU. Whether or not borrowing information or the amount of information from the neighboring OTUs is data adaptive and supervised by phylogenetic distance and the outcome variable. POSTm is built on a kernel machine regression framework and inherited its advantages including flexible modeling of microbiome effects (e.g., effects from opposite direction), easy adjustment for covariates, and accommodation of both continuous and binary outcomes. 

### CDSeq R package ([CRAN](https://CRAN.R-project.org/package=CDSeq); [Github](https://github.com/kkang7/CDSeq_R_Package); [Example](https://github.com/hczdavid/CDSeq))

* The CDSeq implements a complete deconvolution method (CDSeq) using bulk RNA-seq data. Simply put, CDSeq takes bulk RNA-Seq read counts data as input and estimates the cell-type-specific gene expression profiles (csGEPs) and sample-specific cell-type proportions (SSP) simultaneously. (Please install from Github)

### Other tools

**VSARgraph R package/Shiny app ([Github](https://github.com/hczdavid/ImmunoGraph))**

* VSARgraph R pacakge is designed to draw RCDC and forest plot, which are commonly used to visualize the immunogenecity results. The R function “makeForest” in “VSARgraph” package is designed to support multi-block (e.g. top and bottom blocks) and multi-panel (e.g. more than one dataset) forest plot. Users can input multiple datasets and choose up to 2 blocks for each dataset. The data table attached to the right of the forest plot can be turned on or turned off. Three steps are included to make a final forest graph. The R function “makeRCDC” in the package is the designed to support multi-panel (e.g. multiple serotypes) RCDC plot. Users can define the by variable to determine how many step lines will be drawn in one plot and define the filter variable to determine what data is used. R package “ggplot2” is used to draw Lower connection step plot.


**Bio-Discovery R Shiny app ([Github](https://github.com/hczdavid/biodiscovery))**

* This Bio-Discovery Shiny app can be used to perform the following analyses: (1) differential abundance analysis; (2) functional connection; (3) material connection; (4) exploration of data pattern; (5) phenotypic outcome prediction with a machine learning model.  

**Loan calculator R Shiny app ([Github](https://github.com/hczdavid/LoanCalculator);[App](https://davidnadia.shinyapps.io/mortgage_calculator/); [Slides](http://hczdavid.github.io/files/loan.pdf))**

* Our calculator provides functions/tools to answer the following questions: 
  * <span style="font-size:0.5em;">How much I need to pay monthly (interest and principle) given loan amount, interest rate and loan term? (Original Loan)</span>
  * How much interest I can save from my original loan with current principal balance, new interest rate and new term? (Refinance)
  * How much interest and time I can save from my original loan with a Lump-Sum payment? (Lump-Sum Payment)
  * How much interest and time I can save from my original loan with additional monthly payment? (Additional Monthly Payment)


**Automation of filling interactive PDF Shiny app ([Github](https://github.com/hczdavid/fillPDF))**




