# sPlotOpen
sPlot - The global vegetation-plot database
(Public repository -- Mirror)

# Description

sPlotOpen is a large, open-access dataset of vegetation plots. 

It contains data on 95,104 vegetation plots, organized in three partially overlapping, environmentally-balanced datasets (~50,000 plots each), to be used as replicates in global analyses. 

Besides geographic location, date, plot size, biome, elevation, slope, aspect, vegetation type, naturalness, coverage of various vegetation layers and source dataset, plot-level data also include community-weighted means and variances of 18 plant functional traits from the ‘TRY’ database. 

sPlotOpen has a global spatial extent; the spatial grain is 0.01-40,000 m². Plots were recorded between 1888 and 2015. 

sPlotOpen contains data on 42,677 vascular plant species.

### Archive content
sPlotOpen_Metadata_dataset_3474.txt
sPlotOpen_CWM_CWV.txt
sPlotOpen_DT.txt
sPlotOpen_header.txt
sPlotOpen_metadata.txt
sPlotOpen.RData
sPlotOpen_references.bib
Demo.pdf

### File description
sPlotOpen_Metadata_dataset_3474.txt - File describing the dataset
sPlotOpen_CWM_CWV.txt - Community Weighted Means and Community Weighted Variance of all vegetation plots
sPlotOpen_DT.txt - List of species and relative cover in each vegetation plot
sPlotOpen_header.txt - Plot level information
sPlotOpen_metadata.txt - Plot level metadata
sPlotOpen.RData - RData containing all tables above
sPlotOpen_references.bib - Reference list in BibTeX format
Demo.pdf - A Notebook illustrating how sPlotOpen data can be imported and selected in R

All text files use the encoding: UTF-8. 
Please note that all .txt files should be opened as tab-delimited (not comma-delimited) text - the values in some variables are strings that contain commas.
Missing values are indicated with the 'NA' placeholder.

A full data description is available at: https://fmsabatini.github.io/sPlotOpen_Manuscript/

This repository is fully based on:
> Sabatini, F.M., Lenoir, J., Bruelheide, H. & the sPlot Consortium (2021) sPlotOpen – An environmentally-balanced, open-access, global dataset of vegetation plots (Version 2.0) [Dataset]. iDiv Data Repository. https://doi.org/10.25829/idiv.3474-bb7k72
