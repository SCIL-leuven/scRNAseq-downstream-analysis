# scRNAseq-downstream-analysis
R scripts for downstream analysis for single-cell RNA-seq

## Data
Datasets used as examples here include:
* 3000 mouse cortex cells from [Zeisel et al, 2015.](http://science.sciencemag.org/content/347/6226/1138)
* 1200 mouse embryonic cells from [Scialdone et al, 2016.](http://www.nature.com/nature/journal/v535/n7611/full/nature18633.html?foxtrotcallback=true)

Kudos to the authors of these studies who have made their data available.
* For the mouse cortex data, see the [Linnarsson Lab website.](http://linnarssonlab.org/cortex/)
* For the mouse embryonic cell data, see the [Cambridge University Stem Cells website.](http://gastrulation.stemcells.cam.ac.uk/scialdone2016)

## Tutorial

A great tutorial that I used for analyzing single-cell RNA-seq data is the [Hemberg course](https://hemberg-lab.github.io/scRNA.seq.course/).
It will go through all the important steps that I will also describe to you and contains scripts and videos.

Very intersting [page](https://github.com/seandavi/awesome-single-cell) with on overview of all the techniques and tutorials available for single cell RNA sequencing

## Setting up
Download the latest version of R and Rstudio

Open the reqs script, this contains all packages required for the downstream analysis

Clone this repository in your Rstudio
```R
https://github.com/SCIL-leuven/scRNAseq-downstream-analysis.git
```

1. New project
2. Version control
3. Copy URL

## Starting material

Make sure to have a **count file** containing single cells as columns and genes as rows.
Make an **annotation file** that contains important annotation about your experiment.
More information is given in the [Hemberg course](https://hemberg-lab.github.io/scRNA.seq.course/exprs-qc.html#tung-dataset)

## Quality control

For QC we use the package [scater](https://github.com/davismcc/scater) developed by David McCarthy from Cambridge

You go to his [tutorial](https://github.com/davismcc/scater_tutorials_open_data) or clone this repository:
```R
https://github.com/davismcc/scater_tutorials_open_data.git
```

## Clustering

For clustering we use the package [SC3](https://github.com/hemberg-lab/SC3) developed by the Hemberg lab from Cambridge

A seperate tutorial for SC3 is not available but it is used in the [Hemberg course on single-cell RNA-sequencing.](https://hemberg-lab.github.io/scRNA.seq.course/)
