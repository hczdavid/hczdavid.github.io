---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

## Project 1: Phylogeny-guided Microbiome OTU-specific Association Test ([Paper](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-022-01266-3); [Poster](http://hczdavid.github.io/files/JSM_post.pdf))

**Background**: The relationship between host conditions and microbiome profiles, typically characterized by operational taxonomic units (OTUs), contains important information about the microbial role in human health. Traditional association testing frameworks are challenged by the high-dimensionality, sparsity and compositionality of typical microbiome profiles.

**Methods**: We propose a local collapsing test called POST. It is constructed under the kernel machine framework to accommodate complex OTU effects and extends kernel machine microbiome tests from community-level to OTU-level. In POST, whether or not to borrow information and how much information to borrow from the neighboring OTUs in the phylogenetic tree are supervised by phylogenetic distance and the outcome-OTU association.

**Conclusions**: Using POST, we show that adaptively leveraging the phylogenetic information can enhance the selection performance of associated microbiome features by improving the overall true positive and false positive detection. We developed a user-friendly R package [POSTm](https://cran.r-project.org/web/packages/POSTm/index.html) which is freely available on CRAN.


<img src="http://hczdavid.github.io/images/project1.png" alt="projects" width="1000"/>









