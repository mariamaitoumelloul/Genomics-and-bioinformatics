### Comparison of Genomic Features of Invasive Lobular and Invase Ductal Breast Carcinomabased on the data from Comprehensive Molecular Portraits of Invasive Lobular Breast Cancer (Ciriello et. 2015)


# Abstract
Breast cancer is considered as the most frequent cancer affecting women worldwide. The most frequently diagnosed breast cancer histologic subtypes are Invasive Lobular Cancer (ILC) and Invasive Ductal Cancer (IDC). Besides the histological classification, breast cancer can also be categorized into intrinsic subtypesdepending on the gene expressed. There are five main molecular subtypes of breast cancer: LuminalA, Luminal B, HER2-enriched, Normal-like, and Basal-like. The histological and molecular characteristics have important implications for disease diagnosticsand therapy according to the molecular hallmarks of the breast cancer subtypes. This project aims to to identify the genomic characteristicsof the invasive lobular carcinoma (ILC).

# Objectives
- Which genomic characteristics are different between different types of breast cancer?
- What can we conclude from RPPA data analysis? Are the results in agreement with the author's observations?  
- Which biological functions are affected?

# The data
The data used is from Ciriello et al. (2015) analysis: Comprehensive Molecular Portraits of Invasive Lobular Breast Cancer. The data were extracted from a public web-service (http://cbio.mskcc.org/cancergenomics/tcga/brca_tcga).

# Programmation langage 
R and Python.

# Table of content

### RPPA Data Analysis

- [RPPA data preprocessing](RPPA_preprocessing.ipynb): The langage used here is Python. This file contains the code for selecting the samples of interest ( luminal A IDC and luminal A ILC) and to rank the columns of the dataset.

- [RPPA heatmap](RPPA_R.ipynb): The langage used here is R. This file contains the code for plotting the heatmap for the RPPA analysis.

### RNA-Seq Data Analysis

- [Differential Gene Expression Analysis](DEG_R.ipynb): The langage used here is R. This file contains the code for processing RNA-seq data, performing an exploratory data analysis (PCA and tSNE) and differential gene expression analysis between ILC and IDC.

- [Selection of luminal A samples](DEG_lumA_preprocessing.ipynb): The langage used here is Python. This file contains the code for selecting only luminal A ILC and luminal A IDC samples for the RNA-seq data analysis.

- [Differential Gene Expression Analysis for luminal A samples](DEG_lumA_R.ipynb): The langage used here is R. This file contains the code for processing RNA-seq data and differential gene expression analysis between luminal A ILC and luminal A IDC.





