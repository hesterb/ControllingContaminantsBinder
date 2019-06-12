## Controlling Contaminants in 16S rRNA Gene Sequencing Experiments

We recently performed a study to understand the impact of decreasing microbial biomass on 16S rRNA gene sequencing experiments and evaluate the current computational strategies to control for contaminants (available [here](https://msystems.asm.org/content/4/4/e00290-19)).

This repository contains the compiled R Markdown documents to reproduce the analysis presented in the manuscript, divided into 6 primary sections:

* [Introduction and evaluating contaminants](https://lakarstens.github.io/ControllingContaminants16S/Analyses/ControllingContaminants16S.html)
* [Removing contaminant ASVs with filtering methods](https://lakarstens.github.io/ControllingContaminants16S/Analyses/ControllingContaminants16S_Filtering.html)
* [Removing contaminant ASVs with decontam](https://lakarstens.github.io/ControllingContaminants16S/Analyses/ControllingContaminants16S_decontam.html)
* [Removing contaminant ASVs with SourceTracker](https://lakarstens.github.io/ControllingContaminants16S/Analyses/ControllingContaminants16S_SourceTrackerPrep.html)
* [Evaluating SourceTracker results](https://lakarstens.github.io/ControllingContaminants16S/Analyses/ControllingContaminants16S_SourceTracker.html)
* [Final evaluation of all methods](https://lakarstens.github.io/ControllingContaminants16S/Analyses/ControllingContaminantsResults.html)

We hope that this will serve as a resource and tutorial for those wishing to use these computational approaches on their own data. We have created a Binder so that the code in this repository can be run without having to install R/RStudio and all associated packages used. To access, click the Launch Binder logo below (it may take a bit to load). 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lakarstens/ControllingContaminantsBinder/master)

