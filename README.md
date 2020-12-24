# MEG team - AMR++ workshop
## Course syllabus
Start Date: January 5, 2020

Email: meglab.metagenomics@gmail.com
  * Paul Morley - pmorley@tamu.edu
  * Noelle Noyes - nnoyes@umn.edu
  * Enrique Doster - enriquedoster@gmail.com

Slack group: https://meg-research.slack.com
  * Join us here for general discussion and help with course content
  * [Slack invite link](https://join.slack.com/t/meg-research/shared_invite/zt-ej7f576o-QfNwH_yfg0ljyvk3K~ORDg)
    * This link expires every 30 days, so let us know if it doesn't work for you.

[Dropbox link](https://www.dropbox.com/sh/1xvpvxecesddfsc/AADYGmwC1p52eBeYjy_4qJ_-a?dl=0)
  * This dropbox folder contains all of the videos from our zoom course sessions and recordings from a previous MEG bioinformatics workshop.


[![Binder](https://mybinder.org/badge_logo.svg)](https://hub.gke.mybinder.org/user/enriquedoster-m-ro_stats_course-ag2p4r3f/tree)

[![RStudio Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/EnriqueDoster/MEG_intro_stats_course/master?urlpath=rstudio)

https://mybinder.org/v2/gh/EnriqueDoster/MEG_intro_stats_course/master?urlpath=rstudio

## Course content
* [Course summary](#summary)
* [Learning objectives](#learning-objectives)
* [Resources](#resources)
* [Bioinformatics overview](#bioinformatics-overview)
* [Statistics overview](#statistics-overview)

### Summary
These lessons are designed to introduce researchers to the R programming language for statistical analysis of metagenomic sequencing data. While we are primarily developing these training resources for the Microbial Ecology Group (MEG), we would love to get your input on improvements to any component so that we can one day provide this as a useful public resource. As the lessons are meant to be an informal collection of resources and tutorials, we have have liberally used parts and pieces of other online lessons and tailored it for our purposes. We attempt to give credit when possible by linking the original source and we are happy to hear recommendations for other resources to include.

The focus of lesson 1 is to help students install R on their computer, install the necessary R packages, and start playing around with R's functionality. In Lesson 2, students will learn how to calculate and plot summary statistics, including alpha-diversity indices to summarize the microbiome and resistome. In Lesson 3, we'll dive into count normalization using cumulative sum scaling (CSS), ordination with non-metric multidimensional scaling, differential abundance testing with a zero-inflated Gaussian (ZIG) model, and advanced plotting using ggplot2.

This will be the first time that we attempt going through this lesson with a group of students, so please participate in the slack group and ask any questions you have!
* We'll organize a group to all take the same lesson together and **we'll have a virtual meeting once per week for 30 minutes** to go over each of the steps in that lesson. The majority of the work will be self-directed and on your own time, but we encourage you to work in groups and participate in asking questions in the slack group. If you don't have any questions and find this all extremely easy, please help others with their questions and help us improve our lessons.
  * There is 1 "deliverable" per step. Some steps require something be sent to "meglab.metagenomics@gmail.com" or will have a link to a corresponding set of questions.

We wholeheartedly encourage students to independently troubleshoot the majority of problems they might encounter by:
* googling it (or using another search engine)
* getting help from other students by using our slackgroup channel #2021-AMR++workshop
* searching bioinformatic forums such as (stackoverflow.com, biostars.org, seqanswers.com, etc.)


### Learning objectives:
Upon completion of these lessons, students will:
* have their computer set up with the R and RStudio software
* know how to read-in count matrices from bioinformatic analysis of sequence data
* be able to explore and summarize bioinformatic results using
  * diversity indices and box plots
  * ordination with non-metric multidimensional scaling (NMDS)
  * heatmaps
* be familiar with common statistical techiniques such as:
  * Wilcoxon test
  * Generalized linear models
  * Analysis of similarities (ANOSIM)
  * Differential abundance testing using a zero-inflated Gaussian (ZIG) model

### Resources:
MEG resources
* [MEG bioinformatic term glossary](https://github.com/EnriqueDoster/MEG_intro_stats_course/blob/master/misc_resources/Glossary.md)
* [AMR ++ pipeline overview](https://github.com/EnriqueDoster/MEG_intro_stats_course/blob/master/misc_resources/AMR%2B%2B_v2_pipeline_overview.pdf)
* [Bioinformatic AMR and 16S pipeline overview](https://github.com/EnriqueDoster/MEG_intro_stats_course/blob/master/misc_resources/Bioinformatic_AMR_and_16S_pipeline_overview.pdf)
* [Bioinformatics statistics overview](https://github.com/EnriqueDoster/MEG_intro_stats_course/blob/master/misc_resources/Bioinformatic_statistics_overview.pdf)

R programming
* [RStudio cheatsheets](https://rstudio.com/resources/cheatsheets/)
  * This website has tons of helpful cheatsheets for various R packages and analyses methods. Also includes cheatsheets translated to other languages.
* [YaRrr! The Pirate’s Guide to R](https://bookdown.org/ndphillips/YaRrr/)
  * This is a free online book that goes over many useful topics in a quirky, but fun way! Follow along with our simplified R scripts in Lesson 1 and reference this book if you have any other questions.
* [R programming coursera course](https://www.coursera.org/learn/r-programming)
  * This free coursera course goes in-depth with all of the functionality of R. It combines videos with example R scripts for you to follow along with. We recommend this course after you have been playing around with R a bit and want to learn more about the details into how R works.
* [Introduction to R workshop](https://bioinformatics.ca/workshops/2018-introduction-to-R/)
  * We haven't personally tried this workshop, but they have a combination of videos, slides, and R code for various topics.

Data visualization
* [dataviz project](https://datavizproject.com/)
  * This website is for a private company, but they have a great interface for exploring different figure types
* [Visual vocabulary](https://gramener.github.io/visual-vocabulary-vega/#)
   * Handy outline and explanation for the uses of different plots.
   * You can also check out [this interactive figure](http://ft-interactive.github.io/visual-vocabulary/) of the same material
* [FT Visual Journalism Team](https://www.ft.com/visual-and-data-journalism)
  * Awesome site with articles covering various topics and with the emphasis on creating awesome graphics to convey
* [Interactive Jupyter notebooks](https://voila-gallery.org/)
  * Also use [this site for neat jupyter tips and tricks](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)

Command-line
* [Explain shell](https://explainshell.com/)
  * cool website that explains bash commands piece by piece


Statistics resources
* [GUide to STatistical Analysis in Microbial Ecology (GUSTA ME)](https://mb3is.megx.net/gustame)
* [LHS 610: Exploratory Data Analysis for Health](https://kdpsingh.lab.medicine.umich.edu/lhs-610)
  * We haven't personally tried this course, but they provide great videos and code examples for learning how to explore data using R.
* [#bioinformatics live twitter feed](https://twitter.com/search?q=%23bioinformatics&src=hash)
* R-specific resources
  * [ggpubr](http://www.sthda.com/english/articles/24-ggpubr-publication-ready-plots/76-add-p-values-and-significance-levels-to-ggplots/)
    * Nice package for "publication-ready" figures.
  * [Harvard's Data Science: R Basics](https://www.edx.org/course/data-science-r-basics)
* [Collaborative spreadsheet of resources](https://docs.google.com/document/d/1A9BbOCsrg1ikLaBltKhXVKj-eetlrBqR-1u-2V99I2c/edit#)
* [Choose the right test](https://stats.idre.ucla.edu/other/mult-pkg/whatstat/)
* Batch effects
  * [Tackling the widespread and critical impact of batch effects in high-throughput data](https://www.nature.com/articles/nrg2825)
  * [Why Batch Effects Matter in Omics Data, and How to Avoid Them](https://www.sciencedirect.com/science/article/pii/S0167779917300367?casa_token=HQ5ZeDg7XccAAAAA:djpolv0azNOtCZk9XaKjUw8Z1A055LbdgtwFg8CLf6_B4jZggIdVv4GI2dvrDzS8i-LBp9p1aQ)
  * [Beware the bane of batch effects](https://bitesizebio.com/20998/beware-the-bane-of-batch-effects/#:~:text=Batch%20effects%20occur%20whenever%20external,a%20wrench%20in%20your%20findings.)
  * [Mitigating the adverse impact of batch effects in sample pattern detection](https://academic.oup.com/bioinformatics/article/34/15/2634/4916062)
  * [Identifying and mitigating batch effects in whole genome sequencing data](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1756-z)
  * [Why Batch Effects Matter in Omics Data, and How to Avoid Them](https://www.cell.com/trends/biotechnology/pdf/S0167-7799(17)30036-7.pdf)

## Bioinformatic overview

Metagenomic sequencing approach determines the type of analysis you can perform:
  * Shotgun metagenomic sequencing
    * can analyze both the microbiome and resistome, in addition to other sequences such as plasmid-associated or virulence factors
  * Target-enriched resistome sequencing (MEGARes baits)
    * can only analyze the resistome
  * 16S rRNA amplicon sequencing
    * can only analyze the microbiome
    
In this repository, we'll show you examples of running variants of the AMR++ pipeline to achieve your bioinformatic analysis goals. We'll be using code found in [this repository of bioinformatic pipelines](https://github.com/EnriqueDoster/bioinformatic-nextflow-pipelines)
  * AMR++ pipeline
    * The [main_AmrPlusPlus_v2_withKraken.nf](https://github.com/EnriqueDoster/bioinformatic-nextflow-pipelines/blob/master/main_AmrPlusPlus_v2_withKraken.nf) script nalyzes shotgun metagenomic sequencing reads to characterize the microbiome using the taxanomic classier, [kraken2](https://github.com/DerrickWood/kraken2), and alignment of reads to our [MEGARes database](https://megares.meglab.org/) to characterize the resistome.
    * The [main_AmrPlusPlus_v2.nf](https://github.com/EnriqueDoster/bioinformatic-nextflow-pipelines/blob/master/main_AmrPlusPlus_v2.nf) script is simply a subset of the entire pipeline and only performs the resistome analysis.
  * [Qiime2 pipeline](https://qiime2.org/) 
    * We use the Qiime2 pipeline to analyze 16S rRNA reads and export the results to a file format that we can use to analyze with R.


## Statistics overview

Remember, the analysis will always have to be based on your study design and performed with the goal of testing your apriori hypotheses. The scripts in this repository are merely meant to provide an outline for you to begin your analysis and branch off as needed.

The main steps of data exploration and statistical analysis we will cover are divided into four main steps:
1) Loading count matrix results from bioinformatic analyses into R
    * [Load kraken microbiome data](https://github.com/Microbial-Ecology-Group/AMRplusplus_bioinformatic_workshop/blob/main/scripts/Step1_load_kraken_microbiome_data.R)
    * [Load qiime microbiome data](https://github.com/Microbial-Ecology-Group/AMRplusplus_bioinformatic_workshop/blob/main/scripts/Step1_load_qiime2_microbiome_data.R)
    * [Load MEGARes resistome data](https://github.com/Microbial-Ecology-Group/AMRplusplus_bioinformatic_workshop/blob/main/scripts/Step1_load_megares_resistome_data.R)
2) Calculating summary statistics
    * [Calculating summary statistics](https://github.com/Microbial-Ecology-Group/AMRplusplus_bioinformatic_workshop/blob/main/scripts/Step2_R_Data_summary_statistics.R)
3) Normalizing counts and creating exploratory figures
    * [Count normalization](https://github.com/Microbial-Ecology-Group/AMRplusplus_bioinformatic_workshop/blob/main/scripts/Step3_Count_normalization.R)
    * [Introduction to plotting with ggplot2](https://github.com/Microbial-Ecology-Group/AMRplusplus_bioinformatic_workshop/blob/main/scripts/Step3_Introduction_to_plotting.R)
    * [Ordination plots](https://github.com/Microbial-Ecology-Group/AMRplusplus_bioinformatic_workshop/blob/main/scripts/Step3_Ordination.R)
4) Running some common statistical tests
    * [Basic stats with R](https://github.com/Microbial-Ecology-Group/AMRplusplus_bioinformatic_workshop/blob/main/scripts/Step4_R_Basic_stats.R)
    * [Differential abundance testing](https://github.com/Microbial-Ecology-Group/AMRplusplus_bioinformatic_workshop/blob/main/scripts/Step4_Differential_abundance_testing.R)
    * [Advanced plotting](https://github.com/Microbial-Ecology-Group/AMRplusplus_bioinformatic_workshop/blob/main/scripts/Step4_Advanced_plotting.R)
  


## Funding Information:
The development of this tutorial was supported in part by USDA NIFA Grant No. 2018-51300-28563, University of Minnesota College of Veterinary Medicine, The VERO Program at Texas A&M University and West Texas A&M University, and the State of Minnesota Agricultural Research, Education, Extension and Technology Transfer program.

