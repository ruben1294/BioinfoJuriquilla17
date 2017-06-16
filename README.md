# Bioinformatics school (Juriquilla 2017)

Clone or download this repository to your computer and open the `.Rmd` files in Rstudio.

## Main Analysis Template R Markdown:

* [`analysis_template.Rmd`](https://github.com/areyesq89/BioinfoJuriquilla17/blob/master/analysis_template.Rmd): R markdown template which each team will use to create a fully reproducible analysis with the goal of assessing and interpreting the replicability of two pharmacogenomic experiments. This document will contain all of the text and code of their analyses, which are quided by a series of questions. The tools and concepts needed to answer the questions are explored in the tutorials.

## Datasets:

The package PhamPlotter contain the following two data frames:

* rawData: contains drug response data at every dose and for each cell line and drug used in both studies. 

* summarizedData: contains drug response data (combined over all doses using either AUC or IC50 statistics) for each cell line and drug used in both studies.

## Tutorials:
Each tutorial contains text and code that explores various aspects of data science, replicability, and reproducibility. Tutorials 1-4 contain questions to fill in, some require written answers and some require code to produce a plot or numerical summary.

* [`01_exploration.Rmd`](https://github.com/areyesq89/BioinfoJuriquilla17/blob/master/01_exploration.Rmd) : R markdown tutorial 1 - "What to do when you first get data"

* [`02_correlation.Rmd`](https://github.com/areyesq89/BioinfoJuriquilla17/blob/master/02_correlation.Rmd) : R markdown tutorial 2 - "Evaluating replicability of large pharmacological studies"

* [`03_therapies.Rmd`](https://github.com/areyesq89/BioinfoJuriquilla17/blob/master/03_therapies.Rmd) : R markdown tutorial 3 - "Identifying biological factors that influence replicability"

* [`04_regression.Rmd`](https://github.com/areyesq89/BioinfoJuriquilla17/blob/master/04_regression.Rmd) : R markdown tutorial 4 - "Regression approaches for summarizing drug response data"

## Useful Links:

* [CCLE (Cancer Cell Line Encyclopedia) Study](https://www.ncbi.nlm.nih.gov/pubmed/22460905) from March 2012

* [GDSC (Genomics of Drug Sensitivity in Cancer) Study](https://www.ncbi.nlm.nih.gov/pubmed/22460902) from March 2012

* [Reanalysis of CCLE and GDSC](https://www.ncbi.nlm.nih.gov/pubmed/24284626) from December 2013

* [Commentary 1 on the reanalysis](https://www.ncbi.nlm.nih.gov/pubmed/27905415) from December 2016

* [Commentary 2 on the reanalysis](https://www.ncbi.nlm.nih.gov/pubmed/27905421) from December 2016

* [Commentary 3 on the reanalysis](http://www.nature.com/nature/journal/v540/n7631/full/nature20580.html) from December 2016
