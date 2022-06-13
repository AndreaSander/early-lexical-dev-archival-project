# The_more_they_hear_the_more_they_learn?
 load, merge, analyses and visualization scripts for the 2022 bilingual word comprehension study entitled: The more they hear the more they learn? Using data from bilinguals to test models of early lexical development.
To replicate the findings from the study, the Rscripts should be run in order starting by #1. However the scripts are all set up to be run individually if desired. 
This repository contains anonymized data from Looking-While-Listening studies performed on bilingual children in Montreal Canada, as well as anonymized demographic data from the same children. When the data is made public it will be so under an MIT license. 

Script#1 should be run to load all the separate eyetracking and demographic datasets from the 5 studies that composed our final dataset. This script also contains code detailing any data exclusions and data transformations.

Script#2 should be run to reproduce the main analyses (linear mixed models) of the paper. This script also include all model criticism and evaluation measures taken.

Script#3 should be run to reproduce the data visualizations of the paper.

Script#4 should be run to reproduce the supplementary data analyses performed on our data set (whcih included running the analyses using different statistical modelling techniques eg., growth curve analyses, logistic mixed models).

The merged data folder contains the cleaned and merged data resulting from running the load and merge R script. The supplementary tables folder contains result tables resulting from running the other exploratory analyses script.
