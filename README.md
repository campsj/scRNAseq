# scRNAseq
Template Rmd files for scRNAseq analysis

Use these templates together with the **scTools** package:

```devtools::install_github("JC203/scTools")```

### 1. Quality control
+ Set up singlecellexperiment
+ Add mtDNA and ERCCs
+ Annotate genes
+ Filter cells for counts, detected genes, mtDNA and ERCCs
+ Plot highest expressed genes
+ filter genes

### 2. Identifying confounding factors
Identify confounders in principal components
+ plotqc: to see if PC1 is contstructed on variance in detected genes
+ explained variance to see how much of the dataset is explained by technical variability

### 3. Normalization
+ normalization by scran

### 4. Dealing with confounders
+ RUVg
+ RUVs
Only for balanced design:
+ Combat
+ mnnCorrect
+ GLM
+ Four ways to detect if methods were able to diminish variability of confounders

### 5. Clustering with SC3
+ Perform clustering with SC3
+ Check clusters online
+ Plot PCA and tSNE with sc3 clusters
+ Plot expression of clusters
+ Make adjusted heatmaps

### 6. PCA and tSNE analysis
+ Export gene weights in principal components
+ Plot PCA and tSNE
+ Plot gene expression on PCA and tSNE

### 7. SCENIC
+ Gene regulatory network analysis

### 8. PSEUDOTIME
+ Monocle
+ TSCAN
+ SLICER
+ SCORPIUS

### 9. SCRAT
+ Pipeline for interactome analysis with Single-Cell R analysis toolkot of Treutlein lab

## To do
+ Automate functions for easy analysis
