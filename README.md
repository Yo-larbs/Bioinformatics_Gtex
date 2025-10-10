# GTEX analysis

In this notebook i analyse latest Gtex RNAseq data with the metadata.

THings done in this notebook

## metadata analyis
Samples per tissue type split by Age and SEX

## Filtering data
Took top 1000 genes in variance only kept metadat that mapped to samples in counts data

## PCA analysis 
Scree plot and PCA analysis of Top variable genes

## UMAP embedding
used PCAs for UMAP embedding can see clear separation when coloured by Tissue type, tissue type mostly drives variation

## Heatmap visualisations

Gene expression in tissue types and Gene correlation plot 

## Random forest
used Random forest ML classifier to build model that predicted tissue type, 98 Accuracry
confusion matrix in figures

## Neural Network

created 3 layer neural network to classify tissue type, 99% accurate
Training data and Confusion matrix in figures

