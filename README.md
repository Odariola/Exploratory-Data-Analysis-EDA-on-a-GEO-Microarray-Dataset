# Exploratory-Data-Analysis-EDA-on-a-GEO-Microarray-Dataset
📁 Dataset: GSE68849 | 📊 Domain: Bioinformatics / Transcriptomics

This project explores a GEO (Gene Expression Omnibus) microarray dataset using Python. It demonstrates skills in data handling, visualization, biological interpretation, and working with high-dimensional gene expression data.

🚀 Project Overview

This repository contains an end-to-end Exploratory Data Analysis (EDA) workflow on the GEO dataset GSE68849, downloaded using the GEOparse package.

The goal is to:
-Understand the structure and quality of the raw microarray expression data

-Visualize sample distributions and correlations

-Perform dimensionality reduction

-Identify highly variable genes

-Demonstrate differential expression concepts

-Build strong intuition for transcriptomics data analysis

This project was created as part of a bioinformatics learning journey and is written to be clear, reproducible, and recruiter-friendly.

📦 What’s Inside
✔ Jupyter Notebook

Microarray EDA on GEO Dataset.ipynb contains:

1. Dataset Download & Parsing
Using GEOparse to retrieve the Series Matrix file.

2. Preprocessing

-Setting probe IDs as index

-Cleaning metadata

-Handling missing values (if any)

3. Summary Statistics
Understanding expression intensity range and variation.

4. Sample Quality Assessment

-Boxplots

-Distribution checks

-Log2 transformation

5. Correlation Heatmap
Visualizing sample-to-sample similarity and detecting outliers.

6. Principal Component Analysis (PCA)
Reducing dimensionality and observing natural clustering.

7. Highly Variable Genes (HVG)
Identifying top genes with strongest variance across samples.

8. Volcano Plot (Demo)
A conceptual demonstration of differential expression using synthetic labels.

9. Export of Cleaned Matrix
CSV file of expression data for further downstream analysis.

🛠 Tools & Technologies

-Python 3

-Pandas / NumPy

-Matplotlib / Seaborn

-Scikit-learn

-GEOparse

-Jupyter Notebook

These tools are standard in bioinformatics data exploration workflows.

📚 Dataset Information

-Source: Gene Expression Omnibus (GEO)

-Accession: GSE68849

-Type: Microarray gene expression

-Format: Series Matrix processed expression table

🔍 Key Insights From the EDA

-Samples show consistent distribution, indicating high-quality normalization.

-Heatmap and PCA reveal sample relationships and potential biological variance.

-Highly variable genes highlight which probes drive most differences across samples.

-The volcano plot demonstrates how differential expression is typically visualized (concept-only).

This workflow mirrors real transcriptomic QC steps used in research labs and biotech teams.
