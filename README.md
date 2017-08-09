# scRNAseq-downstream-analysis
R scripts for downstream analysis for single-cell RNA-seq

## Data
Datasets used as examples here include:
* 3000 mouse cortex cells from [Zeisel et al, 2015.](http://science.sciencemag.org/content/347/6226/1138)
* 1200 mouse embryonic cells from [Scialdone et al, 2016.](http://www.nature.com/nature/journal/v535/n7611/full/nature18633.html?foxtrotcallback=true)

Kudos to the authors of these studies who have made their data available.
* For the mouse cortex data, see the [Linnarsson Lab website.](http://linnarssonlab.org/cortex/)
* For the mouse embryonic cell data, see the [Cambridge University Stem Cells website.](http://gastrulation.stemcells.cam.ac.uk/scialdone2016)

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

## Quality control

For QC we use the package scater developed by David McCarthy from Cambridge

you go to his [tutorial](https://github.com/davismcc/scater_tutorials_open_data) or clone this repository:
```R
https://github.com/davismcc/scater_tutorials_open_data.git
```
