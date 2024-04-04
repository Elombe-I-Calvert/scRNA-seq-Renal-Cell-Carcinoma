# scRNA-seq-Renal-Cell-Carcinoma
**Dissecting the Impact of Immune Checkpoint Inhibitors on Differential Expression and Abundance in Single-Cell Data of Advanced Renal Cell Carcinoma: A Comprehensive Analysis**

The link to viewing the html document outputted from this code is attached: [Code Link]( https://rawcdn.githack.com/Elombe-I-Calvert/scRNA-seq-Renal-Cell-Carcinoma/0c40d2072f3c1ddeb9aa8d5c1677281812fd6c24/Final-Project%20Code.html)

<div align="justify"> In this study, I followed several steps for data exploration, quality control, pre-processing, dimensionality reduction, and cell type annotation. The quality control and batch correction methods included calculating the percentage of mitochondrial UMI, removing cells with less than 200 genes, and removing cells with more than 25% mitochondrial RNA. For data pre-processing, we normalized, scaled by 10,000, and log-transformed the data, selecting 10,000 variable features.
Dimensionality reduction was performed using PCA, selecting the first 15 PCs, and UMAP for visualization. Potential batch effects were assessed and harmonized using the Harmony algorithm. Data was clustered using the Louvain algorithm with a resolution of 0.5 as was done by Bi, et al . The Wilcoxon test was employed to identify marker genes that were highly expressed in each cluster.</div>
&nbsp;
<div align="justify"> I annotated the cell type clusters based on the marker genes, validated by the paper and Panglao DB, including plasma cells, dendritic cells, TP1 cells (tumor cells), fibroblasts, NK cells, monocytes, hepatocytes, cycling cells, B cells, and endothelial cells. These cells encapsulate the microenvironment of the renal cell carcinoma and the tumor itself.</div>
